---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
---

# Script SiteBuilder.

### 1. Instalar dependencias

Con este comando se instalan las dependencias necesarias para que el Eslint funciona de manera correcta y valide la documentación del código.

```
npm install -D eslint-plugin-jsdoc eslint-plugin-tsdoc vue-eslint-parser @typescript-eslint/parser eslint
```

### 2. Archivo de configuración ESLint

Se debe crear un archivo llamado eslint.config.js en la raíz del proyecto.

En este archivo se están estableciendo las reglas que tomará Eslint para poder realizar la validación de la documentación de código en base a la plantilla establecida.

```javascript
import jsdoc from 'eslint-plugin-jsdoc';
import tsdocPlugin from 'eslint-plugin-tsdoc';
import vueParser from 'vue-eslint-parser';
import tsParser from '@typescript-eslint/parser';

const commonSettings = {
    mode: "typescript",
    ignorePrivate: true,
    ignoreInternal: true,
};

const customVuePlugin = {
    rules: {
        "strict-vue-docs": {
            meta: { type: "problem" },
            create(context) {
                return {
                    Program() {
                        const sourceCode = context.sourceCode || context.getSourceCode();
                        const comments = sourceCode.getAllComments();

                        comments.forEach(comment => {
                            if (comment.type === "Block" && comment.value.startsWith("*")) {
                                if (!comment.value.includes("@description")) {
                                    context.report({
                                        loc: comment.loc,
                                        message: "El bloque de documentación debe contener la etiqueta @description."
                                    });
                                }

                                const contentBeforeTags = comment.value.split('@')[0];
                                const cleanTitle = contentBeforeTags.replace(/\*/g, '').trim();

                                if (!/[a-zA-Z0-9]/.test(cleanTitle)) {
                                    context.report({
                                        loc: comment.loc,
                                        message: "El bloque de documentación debe incluir un título descriptivo antes de las etiquetas."
                                    });
                                }
                            }
                        });
                    },
                    "CallExpression[callee.name='defineEmits'] TSPropertySignature"(node) {
                        if (node.typeAnnotation?.typeAnnotation?.type === "TSTupleType") {
                            const sourceCode = context.sourceCode || context.getSourceCode();
                            const comments = sourceCode.getCommentsBefore(node);
                            const jsdoc = comments.find(c => c.type === "Block" && c.value.startsWith("*"));

                            if (jsdoc) {
                                const elements = node.typeAnnotation.typeAnnotation.elementTypes;
                                const hasAnyParam = jsdoc.value.includes("@param");

                                if (elements.length > 0 && !hasAnyParam) {
                                    context.report({
                                        node,
                                        message: "Falta la etiqueta @param en la documentación del emit."
                                    });
                                    return;
                                }

                                elements.forEach(el => {
                                    if (el.type === "TSNamedTupleMember" && el.label) {
                                        const expectedName = el.label.name;

                                        // 1. Extraemos el tipo real del código
                                        const rawType = sourceCode.getText(el.elementType);

                                        // 2. Escapamos caracteres especiales
                                        const escapedType = rawType.replace(/[-\/\\^$*+?.()|[\]{}]/g, '\\$&');

                                        // 3. Validamos que coincida el tipo exacto y el nombre de la variable
                                        const paramRegex = new RegExp(`@param\\s+\\{${escapedType}\\}\\s+${expectedName}\\b`);

                                        if (!paramRegex.test(jsdoc.value)) {
                                            context.report({
                                                node,
                                                message: `El parámetro '${expectedName}' o su tipo '{${rawType}}' no coinciden en el @param.`
                                            });
                                        }
                                    }
                                });
                            }
                        }
                    }
                };
            }
        }
    }
};

export default [
    {
        ignores: ["eslint.config.js"]
    },
    {
        files: ["**/*.js", "**/*.ts", "**/*.vue"],
        languageOptions: {
            parser: vueParser,
            parserOptions: {
                parser: tsParser,
                sourceType: "module",
                ecmaVersion: 2022,
                extraFileExtensions: [".vue"]
            }
        },
        plugins: {
            jsdoc,
            tsdoc: tsdocPlugin,
            "custom-vue": customVuePlugin
        },
        rules: {
            "jsdoc/require-asterisk-prefix": "error",

            "custom-vue/strict-vue-docs": "error",

            "jsdoc/require-param": ["error", {
                contexts: [
                    "FunctionDeclaration",
                    "MethodDefinition",
                    "ArrowFunctionExpression",
                    "FunctionExpression",
                    "TSMethodSignature"
                ]
            }],
            "jsdoc/require-param-type": ["error", {
                contexts: [
                    "FunctionDeclaration",
                    "MethodDefinition",
                    "ArrowFunctionExpression",
                    "FunctionExpression",
                    "TSMethodSignature"
                ]
            }],
            "jsdoc/check-param-names": ["error", {
                checkDestructured: false,
                enableFixer: false
            }],
            "jsdoc/require-param-description": ["error", {
                contexts: [
                    "FunctionDeclaration",
                    "MethodDefinition",
                    "ArrowFunctionExpression",
                    "FunctionExpression",
                    "TSMethodSignature"
                ]
            }],

            "jsdoc/require-jsdoc": ["error", {
                require: {
                    FunctionDeclaration: true,
                    MethodDefinition: true,
                    ClassDeclaration: true,
                    ArrowFunctionExpression: true,
                    FunctionExpression: true
                },
                contexts: [
                    "TSInterfaceDeclaration",
                    "TSTypeAliasDeclaration",
                    "VariableDeclaration:has(CallExpression[callee.name='defineProps'])",
                    "VariableDeclaration:has(CallExpression[callee.name='defineEmits'])",
                    "CallExpression[callee.name='defineEmits'] TSPropertySignature",
                    "VariableDeclaration:has(CallExpression[callee.name='computed'])"
                ]
            }],

            "jsdoc/match-description": ["error", {
                matchDescription: "^[A-Z][a-zA-Z0-9,.'\"\\- \\(\\)\\n\\r]*$"
            }]
        },
        settings: {
            jsdoc: commonSettings
        }
    }
];
```

### 3. Hook

El hook ejecutará el Eslint de manera automática antes de hacer el push, si la validación por parte de Eslint da error, el hook cancelará el push.

```shellscript
#!/usr/bin/env bash
# ───────────────────────────────────────────────
# 📄 VALIDACIÓN DE DOCUMENTACIÓN TSDOC
# ───────────────────────────────────────────────
echo "🔍 Ejecutando validación TSDoc con ESLint..."
 
# Rama principal contra la que se compara cuando la rama actual aún no existe en el remoto.
MAIN_BRANCH="main"
 
# ── Verificación del entorno ────────────────────
if [ ! -f "./node_modules/.bin/eslint" ]; then
    echo "❌ ESLint no está instalado en este proyecto."
    echo "👉 Ejecuta 'npm install' en la raíz del proyecto y vuelve a intentar el push."
    exit 1
fi
 
CONFIG_FOUND=0
for CONFIG in eslint.config.js eslint.config.mjs eslint.config.cjs eslint.config.ts; do
    if [ -f "./$CONFIG" ]; then
        CONFIG_FOUND=1
        break
    fi
done
 
if [ $CONFIG_FOUND -eq 0 ]; then
    echo "❌ No se encontró el archivo eslint.config.js en la raíz del proyecto."
    echo "👉 Trae los últimos cambios de '$MAIN_BRANCH' a tu rama (git pull origin $MAIN_BRANCH) y vuelve a intentar."
    exit 1
fi
 
# ── Archivos a validar ──────────────────────────
CURRENT_BRANCH=$(git rev-parse --abbrev-ref HEAD)
 
if git rev-parse --verify --quiet "origin/$CURRENT_BRANCH" > /dev/null; then
    BASE="origin/$CURRENT_BRANCH"
elif git rev-parse --verify --quiet "origin/$MAIN_BRANCH" > /dev/null; then
    BASE="origin/$MAIN_BRANCH"
    echo "ℹ️  La rama '$CURRENT_BRANCH' no existe en el remoto. Se compara contra '$BASE'."
else
    echo "⚠️  No se encontró 'origin/$CURRENT_BRANCH' ni 'origin/$MAIN_BRANCH'. Ejecuta 'git fetch' e intenta de nuevo."
    exit 1
fi
 
FILES=$(git diff --name-only "$BASE"...HEAD --diff-filter=ACMR | grep -E '\.(ts|tsx|vue|js)$')
 
if [ -z "$FILES" ]; then
    echo "✅ No hay archivos TypeScript o Vue modificados para validar."
    exit 0
fi
 
echo "📝 Archivos a validar:"
echo "$FILES"
 
ERROR=0
 
for FILE in $FILES; do
    if [ -f "$FILE" ]; then
        echo "📂 Validando $FILE ..."
 
        # Ejecución limpia, ESLint tomará el archivo de configuración automáticamente
        OUTPUT=$(./node_modules/.bin/eslint --no-warn-ignored --max-warnings 0 "$FILE" 2>&1)
        STATUS=$?
 
        if [ $STATUS -ne 0 ]; then
            ERROR=1
            echo "$OUTPUT"
        fi
    else
        echo "⚠️ Archivo omitido (no existe): $FILE"
    fi
done
 
if [ $ERROR -ne 0 ]; then
    echo "❌ Se encontraron errores en la documentación TSDoc. Corrige antes de hacer push."
    exit 1
fi
 
echo "✅ Validación exitosa. Continuando con el push."
exit 0
```

### 4. Historial de versiones
