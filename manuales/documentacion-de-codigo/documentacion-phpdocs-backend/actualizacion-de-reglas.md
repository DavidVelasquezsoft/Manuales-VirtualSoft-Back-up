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

# Actualización de reglas

### Archivo original:

#### Reglas enfocadas únicamente en:

* &#x20;Documentación de funciones (FunctionComment)
* Comentarios generales (DocComment)
* Longitud de línea
* Exclusión básica de carpetas (vendor/)
* Exclusión de comentarios en bloque y en línea

### Cambios realizados en el archivo actualizado:

1. **Nuevas exclusiones en FunctionComment:**

* IncorrectParamVarName
* InvalidReturn

Esto suaviza la validación sobre:

* Parámetros.
* Documentación del @return.

2. **Sección nueva: VariableComment**

* Squiz.Commenting.VariableComment con exclusiones:
* IncorrectVarType
* Missing

Ya será más flexible con el tipo de variable en la documentación.

3. **Nuevas exclusiones generales de alineación y estilo:**

* Squiz.Commenting.DocCommentAlignment
* PEAR.Commenting
* Generic.Commenting

Se desactivan todas las reglas de estilo y formato de comentarios para evitar conflictos con la documentación que se tiene de swagger.



### Archivo actualizado:

```xml
<?xml version="1.0"?>
<ruleset name="DocStandard">
<description>Reglas documentación phpdocs</description>
 
    <!-- Excluir carpetas -->
<exclude-pattern>*/vendor/*</exclude-pattern>
 
    <!-- Deshabilitar todas las reglas -->
<rule ref="Generic.Commenting.DocComment">
<exclude name="Generic.Commenting.DocComment.TagValueIndent"/>
<exclude name="Generic.Commenting.DocComment.NonParamGroup"/>
<exclude name="Generic.Commenting.DocComment.ParamNotFirst"/>
<exclude name="Generic.Commenting.DocComment.SpacingBeforeTags"/>
<exclude name="Generic.Commenting.DocComment.TagsNotGrouped"/>
<exclude name="Generic.Commenting.DocComment.ContentAfterOpen"/>
<exclude name="Generic.Commenting.DocComment.ContentBeforeClose"/>
<exclude name="Generic.Commenting.DocComment.SpacingAfterTagGroup"/>
<exclude name="Generic.Commenting.DocComment.LongNotCapital"/>
</rule>
 
    <!-- Deshabilitar límites de longitud -->
<rule ref="Generic.Files.LineLength">
<exclude name="Generic.Files.LineLength"/>
</rule>
 
    <!-- Verificar documentación -->
<rule ref="Squiz.Commenting.FunctionComment">
<exclude name="Squiz.Commenting.FunctionComment.IncorrectParamVarName"/>
<exclude name="Squiz.Commenting.FunctionComment.ParamNameNoMatch"/>
<exclude name="Squiz.Commenting.FunctionComment.InvalidTypeHint"/>
<exclude name="Squiz.Commenting.FunctionComment.EmptyThrows"/>
<exclude name="Squiz.Commenting.FunctionComment.ThrowsNotCapital"/>
<exclude name="Squiz.Commenting.FunctionComment.SpacingAfterParamType"/>
<exclude name="Squiz.Commenting.FunctionComment.SpacingAfterParamName"/>
<exclude name="Squiz.Commenting.FunctionComment.ParamCommentNotCapital"/>
<exclude name="Squiz.Commenting.FunctionComment.ParamCommentFullStop"/>
<exclude name="Squiz.Commenting.FunctionComment.ThrowsNoFullStop"/>
<exclude name="Squiz.Commenting.FunctionComment.Missing"/>
<exclude name="Squiz.Commenting.FunctionComment.ScalarTypeHintMissing"/>
<exclude name="Squiz.Commenting.FunctionComment.TypeHintMissing"/>
<exclude name="Squiz.Commenting.FunctionComment.IncorrectTypeHint"/>
<exclude name="Squiz.Commenting.FunctionComment.LongNotCapital"/>
<exclude name="Squiz.Commenting.FunctionComment.InvalidReturn"/>
</rule>
 
    <!-- Verificar documentación de variables -->
<rule ref="Squiz.Commenting.VariableComment">
<exclude name="Squiz.Commenting.VariableComment.IncorrectVarType"/>
<exclude name="Squiz.Commenting.VariableComment.Missing"/>
</rule>
 
    <!-- Excluir reglas para funciones anónimas y comentarios -->
<rule ref="Squiz.Commenting.InlineComment">
<exclude name="Squiz.Commenting.InlineComment"/>
</rule>
<rule ref="Squiz.Commenting.BlockComment">
<exclude name="Squiz.Commenting.BlockComment"/>
</rule>
 
    <!-- Excluir validación de alineación de Swagger -->
<rule ref="Squiz.Commenting.DocCommentAlignment">
<exclude name="Squiz.Commenting.DocCommentAlignment"/>
</rule>
<rule ref="PEAR.Commenting">
<exclude name="PEAR.Commenting"/>
</rule>
<rule ref="Generic.Commenting">
<exclude name="Generic.Commenting"/>
</rule>
 
    <arg name="extensions" value="php"/>
<arg value="s"/>
</ruleset>
```
