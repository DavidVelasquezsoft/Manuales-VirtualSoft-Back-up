# Reporte Depósitos por franquicias

<mark style="color:$info;">Permite consultar los depósitos procesados a través del Orquestador de Franquicias, agrupados por franquicia, y visualizar el detalle de las pasarelas de pago que participaron en el procesamiento. Su objetivo es analizar de forma independiente el comportamiento de los depósitos según la franquicia seleccionada por el usuario al momento de la transacción.</mark>

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Reporte de Depósitos por Franquicias

***

### 2. Visualización



***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-depositos-por-franquicias.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-depositos-por-franquicias.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los depósitos en la vista seleccionada.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="190.50006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fechas</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el periodo de consulta indicando una fecha de inicio y una fecha de fin.</td></tr><tr><td><strong><code>Franquicias</code></strong></td><td>Lista desplegable</td><td>Filtra los depósitos según la franquicia a través de la cual fueron procesados.</td></tr><tr><td><strong><code>Proveedor de pasarela de pago</code></strong></td><td>Lista desplegable</td><td>Filtra por el proveedor de la pasarela de pago que procesó los depósitos.</td></tr><tr><td><strong><code>Producto de pago</code></strong></td><td>Lista desplegable</td><td>Filtra por el producto de pago utilizado en los depósitos.</td></tr><tr><td><strong><code>ID de Usuario</code></strong></td><td>Numérico</td><td>Filtra por el identificador único del usuario que realizó los depósitos.</td></tr><tr><td><strong><code>Estado del depósito</code></strong></td><td>Lista desplegable</td><td>Filtra los depósitos según su estado.</td></tr><tr><td><strong><code>Valor mínimo</code></strong></td><td>Numérico</td><td>Define el valor mínimo de los depósitos a incluir en la consulta.</td></tr><tr><td><strong><code>Valor máximo</code></strong></td><td>Numérico</td><td>Define el valor máximo de los depósitos a incluir en la consulta.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Campo de texto</td><td>Filtra los depósitos según la dirección IP desde la cual se originaron.</td></tr><tr><td><strong><code>Ordenar por</code></strong></td><td>Lista desplegable</td><td>Define el criterio de ordenamiento de los resultados <em>(ID de usuario, Fecha de creación o Valor)</em>.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Lista desplegable</td><td>Define el sentido del ordenamiento <em>(Ascendente o Descendente)</em>.</td></tr><tr><td><strong><code>Vista</code></strong></td><td>Selector</td><td>Permite alternar entre la <strong>Vista resumida</strong> y la <strong>Vista detallada</strong> de los resultados.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega la información según los filtros aplicados. El reporte cuenta con dos vistas que pueden seleccionarse según el nivel de análisis requerido.

{% tabs %}
{% tab title="Vista resumida" %}
La vista resumida presenta los depósitos agrupados por franquicia mediante una estructura jerárquica. Cada fila principal representa una franquicia y consolida la información de todas las pasarelas asociadas que participaron en el procesamiento de los depósitos. Cada franquicia cuenta con un control de expansión que permite desplegar el detalle de sus pasarelas.

**Nivel franquicia**

<table><thead><tr><th width="220">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre de la franquicia</code></strong></td><td>Nombre de la franquicia a través de la cual se procesaron los depósitos.</td></tr><tr><td><strong><code>Cantidad de depósitos</code></strong></td><td>Número total de depósitos realizados a través de la franquicia durante el periodo consultado, consolidando todas sus pasarelas asociadas.</td></tr><tr><td><strong><code>Cantidad de usuarios</code></strong></td><td>Cantidad de usuarios únicos que realizaron depósitos a través de la franquicia.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Suma total de los depósitos procesados por la franquicia durante el periodo consultado.</td></tr></tbody></table>

**Nivel pasarela**

Al expandir una franquicia, se muestran en subfilas las pasarelas que procesaron depósitos dentro de esa franquicia.

<table><thead><tr><th width="220">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre de la pasarela</code></strong></td><td>Nombre de la pasarela de pago que procesó los depósitos dentro de la franquicia.</td></tr><tr><td><strong><code>Cantidad de depósitos</code></strong></td><td>Número de depósitos procesados por la pasarela dentro de la franquicia.</td></tr><tr><td><strong><code>Cantidad de usuarios</code></strong></td><td>Cantidad de usuarios únicos que realizaron depósitos a través de la pasarela dentro de la franquicia.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Valor total procesado por la pasarela dentro de la franquicia.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Una misma pasarela puede aparecer en varias franquicias. En estos casos, las cantidades y valores se calculan de forma independiente por franquicia, según la franquicia seleccionada por el usuario al momento de iniciar el depósito; el reporte no consolida la información de una misma pasarela entre franquicias distintas.
{% endhint %}

{% hint style="info" %}
La cantidad de depósitos y el valor total de cada franquicia corresponden a la suma de los valores de sus pasarelas asociadas.
{% endhint %}
{% endtab %}

{% tab title="Vista detallada" %}
La vista detallada presenta una tabla que refleja fila por fila cada uno de los depósitos que cumplen con los filtros aplicados.

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del depósito.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario que realizó el depósito.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha y hora en la que se generó el depósito.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Proveedor de la pasarela de pago que procesó el depósito.</td></tr><tr><td><strong><code>Producto de Pago</code></strong></td><td>Producto de pago utilizado para realizar el depósito.</td></tr><tr><td><strong><code>Franquicia</code></strong></td><td>Franquicia a través de la cual se procesó el depósito.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto del depósito.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Valor de la comisión aplicada al depósito.</td></tr><tr><td><strong><code>Impuesto Depósito</code></strong></td><td>Valor del impuesto aplicado al depósito.</td></tr><tr><td><strong><code>Modificado</code></strong></td><td>Fecha y hora de la última modificación del depósito.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del depósito.</td></tr><tr><td><strong><code>Notas</code></strong></td><td>Observaciones o información adicional asociada al depósito.</td></tr><tr><td><strong><code>External ID</code></strong></td><td>Identificador externo del depósito, asignado por la pasarela o el sistema de origen.</td></tr><tr><td><strong><code>IP</code></strong></td><td>Dirección IP desde la cual se originó el depósito.</td></tr></tbody></table>

{% hint style="info" %}
La vista detallada permite paginar los resultados en bloques de 10, 20, 50, 100, 1000 y 10.000 registros.
{% endhint %}
{% endtab %}
{% endtabs %}

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* Este es un reporte independiente del Reporte de Depósitos actual y no modifica su lógica, filtros, consultas ni comportamientos.
* En la vista resumida la información siempre se agrupa principalmente por franquicia.
* La cantidad de depósitos y el valor total de cada franquicia corresponden a la consolidación de todas sus pasarelas asociadas; la suma de los depósitos y valores de las pasarelas coincide con el total de la franquicia.
* Cuando una misma pasarela participa en varias franquicias, sus cantidades y valores se calculan de forma independiente según la franquicia desde la cual se originó el depósito, sin consolidarse entre franquicias distintas.
* La información presentada es consistente con los depósitos registrados en el sistema.
* La exportación respeta la misma estructura jerárquica visualizada en pantalla.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>06/07/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
