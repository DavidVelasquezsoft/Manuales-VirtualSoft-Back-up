---
description: >-
  Este es el hook utilizado para la validación automática de la documentación
  tanto para el backend como para Integraciones
---

# Hook de backend.

```bash
#!/bin/bash

# ───────────────────────────────────────────────
# 🔍 VALIDACIÓN DE NOMBRE DE RAMA
# ───────────────────────────────────────────────

# Expresión regular para validar el formato básico de rama:
# feature|hotfix|bugfix / PROYECTO-NÚMERO
branch_regex="^(feature|hotfix|bugfix)\/(VSSUP|MARKECUA|SOPECUA|RISK|STI|GEP|VSFT|BUG|GEBD|GEC|GEP|GEPC|GEPD|GER)-[0-9]{3,5}$"

# Expresión regular que también permite sufijos adicionales en el nombre
branch="^(feature|hotfix|bugfix)\/(VSSUP|MARKECUA|SOPECUA|RISK|STI|GEP|VSFT|BUG|GEBD|GEC|GEP|GEPC|GEPD|GER)-[0-9]{3,5}(-[a-zA-Z]+([A-Za-z0-9]+)*)?$"

# Lista de nombres de ramas permitidas directamente
allowed_branches="^(environmentdev|environmentdevintegrations|main)$"

# Obtiene el nombre de la rama actual
branch_name=$(git rev-parse --abbrev-ref HEAD)

# Valida que el nombre de la rama cumpla con alguno de los formatos permitidos
if [[ ! $branch_name =~ $branch_regex && ! $branch_name =~ $allowed_branches && ! $branch_name =~ $branch ]]; then
    echo "❌ Error: El nombre de la rama '$branch_name' no cumple con el formato requerido."
    echo "Formato requerido: [ramaTemporal]/[IDProyecto]-[CodigoWorkItem] o debe ser una de las ramas permitidas: environmentdev, environmentdevintegrations, main."
    echo "Ejemplo válido: feature/MARKECUA-1234"
    exit 1
fi

# ───────────────────────────────────────────────
# 📄 VALIDACIÓN DE DOCUMENTACIÓN PHPDOC
# ───────────────────────────────────────────────

echo "🔍 Ejecutando validación PHPDoc con PHPCS..."

# Obtiene el nombre de la rama actual
CURRENT_BRANCH=$(git rev-parse --abbrev-ref HEAD)

# Obtiene la lista de archivos PHP modificados entre la rama actual y su origen
FILES=$(git diff --name-only origin/$CURRENT_BRANCH...HEAD --diff-filter=ACMR | grep -E '\.php$')

# Si no hay archivos PHP modificados, termina la ejecución
if [ -z "$FILES" ]; then
    echo "✅ No hay archivos PHP modificados para validar."
    exit 0
fi

# Muestra los archivos que serán validados
echo "📝 Archivos a validar:"
echo "$FILES"

# Variable para controlar si se encontraron errores
ERROR=0

# Itera sobre cada archivo PHP modificado
for FILE in $FILES; do
    # Verifica si el archivo existe
    if [ -f "$FILE" ]; then
        echo "📂 Validando $FILE ..."
        # Ejecuta PHPCS con las reglas definidas en phpcs.xml
        OUTPUT=$(./api/vendor/bin/phpcs --standard=api/phpcs.xml --report=full "$FILE" 2>&1)
        STATUS=$?
        
        # Si PHPCS encontró errores
        if [ $STATUS -ne 0 ]; then
            ERROR=1
            # Filtra la salida para mostrar solo los errores relevantes
            echo "$OUTPUT" | grep -v "^$" | grep -v "^FILE:" | grep -v "^Time:" | grep -v "^FOUND"
        fi
    else
        echo "⚠️ Archivo omitido (no existe): $FILE"
    fi
done

# Si se encontraron errores, impide el push
if [ $ERROR -ne 0 ]; then
    echo "❌ Se encontraron errores en la documentación PHPDoc. Corrige antes de hacer push."
    exit 1
fi

# Si todo está correcto, permite el push
echo "✅ Validación exitosa. Continuando con el push."
exit 0
```
