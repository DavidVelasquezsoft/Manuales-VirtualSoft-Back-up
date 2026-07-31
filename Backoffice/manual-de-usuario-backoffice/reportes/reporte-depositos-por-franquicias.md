# Reporte Depósitos por franquicias

<mark style="color:$info;">Permite consultar los depósitos agrupados por franquicia y visualizar el detalle de las pasarelas de pago utilizadas en cada una. Su objetivo es facilitar el análisis del comportamiento de los depósitos según la franquicia seleccionada por el usuario al momento de realizar la transacción.</mark>

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Reportes > Reporte de Depósitos por Franquicias

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (708).png" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte depósitos por franquicias.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-depositos-por-franquicias.md#id-4.-filtros"><strong>Filtrar</strong></a></td><td>Definen los criterios de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-depositos-por-franquicias.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los depósitos en la vista seleccionada.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="168.5001220703125">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fechas</code></strong></td><td>Rango de fechas</td><td>Selecciona el periodo de consulta indicando una fecha de inicio y una fecha de fin.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/plantillas/glosario#franquicia"><strong><code>Franquicias</code></strong></a></td><td>Lista desplegable</td><td>Filtra los depósitos según la franquicia a través de la cual fueron procesados. Para seleccionarla, ingrese al menos los primeros tres caracteres del nombre de la franquicia y elija la opción correspondiente de la lista.</td></tr><tr><td><strong><code>ID de Usuario</code></strong></td><td>Numérico</td><td>Filtra por el identificador único del usuario que realizó los depósitos.</td></tr><tr><td><strong><code>Estado del depósito</code></strong></td><td>Lista desplegable</td><td>Filtra los depósitos según su estado (<em>Pagado, Enviado o rechazado</em>).</td></tr><tr><td><strong><code>Proveedor de pasarela de pago</code></strong></td><td>Lista desplegable</td><td>Filtra por el proveedor de la pasarela de pago que procesó los depósitos.</td></tr><tr><td><strong><code>Producto de pago</code></strong></td><td>Lista desplegable</td><td>Filtra por la pasarela de pago en especifico utilizada en los depósitos. Para seleccionarla, ingrese al menos los primeros tres caracteres del nombre de la pasarela y elija la opción correspondiente de la lista.</td></tr><tr><td><strong><code>Valor mínimo</code></strong></td><td>Numérico</td><td>Define el valor mínimo de los depósitos a incluir en la consulta.</td></tr><tr><td><strong><code>Valor máximo</code></strong></td><td>Numérico</td><td>Define el valor máximo de los depósitos a incluir en la consulta.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Campo de texto</td><td>Filtra los depósitos según la dirección IP desde la cual se originaron.</td></tr><tr><td><strong><code>Vista</code></strong></td><td>Selector</td><td>Alterna entre la <a href="reporte-depositos-por-franquicias.md#vista-resumida"><strong>Vista resumida</strong></a> y la <a href="reporte-depositos-por-franquicias.md#vista-detallada"><strong>Vista detallada</strong></a> de los resultados.</td></tr><tr><td><strong><code>Ordenar por</code></strong></td><td>Lista desplegable</td><td><p>Define el criterio de ordenamiento de los resultados <em>(ID de usuario, Fecha de creación o Valor)</em>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este filtro aplica únicamente para la vista detallada</p></div></td></tr><tr><td><strong><code>Orden</code></strong></td><td>Lista desplegable</td><td><p>Define el sentido del ordenamiento <em>(Ascendente o Descendente)</em>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este filtro aplica únicamente para la vista detallada</p></div></td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega la información según los filtros aplicados. El reporte cuenta con dos vistas que pueden seleccionarse según el nivel de análisis requerido.

{% tabs %}
{% tab title="Vista resumida" %}
La vista resumida presenta los depósitos en una única tabla de cuatro columnas, organizada en diferentes [**niveles jerárquicos**](reporte-depositos-por-franquicias.md#niveles-de-la-jerarquia) mediante carpetas expandibles. Cada nivel puede desplegarse o contraerse para navegar desde el total general hasta el detalle de cada pasarela.

Las columnas de esta vista son las mismas en todos los niveles:

<table><thead><tr><th width="220">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Franquicia / Pasarela</code></strong></td><td>Nombre del nivel que se está visualizando <em>(país,</em> <a href="https://virtualsoft.gitbook.io/plantillas/glosario#franquicia"><em>franquicia</em></a> <em>o pasarela)</em>, según la carpeta desplegada.</td></tr><tr><td><strong><code>Cantidad de Depósitos</code></strong></td><td>Número total de depósitos correspondientes a ese nivel durante el periodo consultado.</td></tr><tr><td><strong><code>Cantidad de Usuarios</code></strong></td><td>Cantidad de usuarios únicos que realizaron depósitos en ese nivel.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Suma total de los depósitos correspondientes a ese nivel durante el periodo consultado.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Una misma pasarela puede aparecer en varias [franquicias](https://virtualsoft.gitbook.io/plantillas/glosario#franquicia). En estos casos, las cantidades y valores se calculan de forma independiente por franquicia, según la franquicia seleccionada por el usuario al momento de iniciar el depósito; el reporte no consolida la información de una misma pasarela entre franquicias distintas.
{% endhint %}

#### **Niveles de la jerarquía**

Al ejecutar la consulta, la tabla inicia contraída en una sola fila (la carpeta raíz), que muestra los totales generales según los filtros aplicados. A partir de ahí, cada carpeta se despliega para revelar el siguiente nivel:

{% hint style="warning" %}
**Nota:** En cada nivel, los valores corresponden a la suma de los niveles inferiores que contiene: el total de una franquicia equivale a la suma de sus pasarelas, y el de un país a la suma de sus franquicias.
{% endhint %}

<table><thead><tr><th width="170.00006103515625">Nivel</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>1. Total general</strong></td><td>Carpeta raíz que consolida la totalidad de los depósitos según los filtros aplicados. Al desplegarla, muestra los países.</td></tr><tr><td><strong>2. País</strong></td><td>Agrupa los depósitos por país. Al desplegar un país, muestra las <a href="https://virtualsoft.gitbook.io/plantillas/glosario#franquicia">franquicias</a> que operaron en él.</td></tr><tr><td><strong>3. Franquicia</strong></td><td>Agrupa los depósitos por franquicia, consolidando todas sus pasarelas. Al desplegar una <a href="https://virtualsoft.gitbook.io/plantillas/glosario#franquicia">franquicia</a>, muestra las pasarelas que procesaron depósitos dentro de ella.</td></tr><tr><td><strong>4. Pasarela</strong></td><td>Último nivel del desglose. Cada fila corresponde a una pasarela de pago con los depósitos que procesó dentro de esa <a href="https://virtualsoft.gitbook.io/plantillas/glosario#franquicia">franquicia</a>.</td></tr></tbody></table>
{% endtab %}

{% tab title="Vista detallada" %}
La vista detallada presenta una tabla que refleja fila por fila cada uno de los depósitos que cumplen con los filtros aplicados.

<table><thead><tr><th width="191">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del depósito.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario que realizó el depósito.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha y hora en la que se generó el depósito.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Proveedor de la pasarela de pago que procesó el depósito.</td></tr><tr><td><strong><code>Producto de Pago</code></strong></td><td>Pasarela de pago utilizada para realizar el depósito.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/plantillas/glosario#franquicia"><strong><code>Franquicia</code></strong></a></td><td>Franquicia a través de la cual se procesó el depósito.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto del depósito.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Valor de la comisión aplicada al depósito.</td></tr><tr><td><strong><code>Impuesto Depósito</code></strong></td><td>Valor del impuesto aplicado al depósito.</td></tr><tr><td><strong><code>Modificado</code></strong></td><td>Fecha y hora de la última modificación del depósito.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del depósito (<em>Enviado, Rechazado o Pagado</em>).</td></tr><tr><td><strong><code>Notas</code></strong></td><td>Observaciones o información adicional asociada al depósito.</td></tr><tr><td><strong><code>External ID</code></strong></td><td>Identificador externo del depósito, asignado por la pasarela o el sistema de origen.</td></tr><tr><td><strong><code>IP</code></strong></td><td>Dirección IP desde la cual se originó el depósito.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos desde la sección [Perfiles - Options](../seguridad/perfiles-options.md); de lo contrario, el reporte no será visible en el sistema.
* Este es un reporte independiente del Reporte de Depósitos actual y no modifica su lógica, filtros, consultas ni comportamientos.
* La cantidad de depósitos y el valor total de cada franquicia corresponden a la consolidación de todas sus pasarelas asociadas; la suma de los depósitos y valores de las pasarelas coincide con el total de la franquicia.
* Cuando una misma pasarela participa en varias franquicias, sus cantidades y valores se calculan de forma independiente según la franquicia desde la cual se originó el depósito, sin consolidarse entre franquicias distintas.
* La información presentada es consistente con los depósitos registrados en el sistema.
* La exportación respeta la misma estructura jerárquica visualizada en pantalla.
* La información de este reporte puede contrastarse con la del reporte [**Solicitudes de Depósito**](../financiero/solicitudes-de-deposito.md), con una diferencia clave: este reporte incluye únicamente los depósitos procesados a través de una franquicia, mientras que el de Solicitudes de Depósito incluye la totalidad de los depósitos, sin importar si se realizaron o no mediante una franquicia.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>31/07/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-31448">Documento inicial</a></td></tr></tbody></table>

</details>
