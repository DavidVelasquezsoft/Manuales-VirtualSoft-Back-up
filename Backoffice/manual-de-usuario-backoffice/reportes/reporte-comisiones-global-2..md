# Reporte Comisiones Global 2.

<mark style="color:$info;">Consulta las comisiones generadas por afiliados, concesionarios y puntos de venta dentro de un período determinado. Permitiendo configurar qué campos se visualizan para adaptar la consulta a la información que se necesite analizar.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Reporte de Comisiones

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FJnWvufVPsyUO02jy5vw9%2Fimage.png?alt=media&#x26;token=66e0d90e-6800-47ba-82a2-49bd2119fad4" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Reporte Comisiones Global 2.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="194">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Click to configure</strong></td><td>Abre una ventana emergente para definir qué campos se aplican a los filtros y a la tabla de resultados, permitiendo adaptar la consulta a la información que se requiere analizar.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="186">Sección</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fields</code></strong> <em>(Campos)</em></td><td>Listado de todos los campos disponibles para distribuir entre las demás secciones.</td></tr><tr><td><strong><code>Filters</code></strong> <em>(Filtros)</em></td><td>Campos que se habilitan como filtro para acotar la búsqueda.</td></tr><tr><td><strong><code>Rows</code></strong> <em>(Filas)</em></td><td>Campos por los que se agrupan los registros de la tabla.</td></tr><tr><td><strong><code>Columns</code></strong> <em>(Columnas)</em></td><td>Campos por los que se abren las columnas de la tabla.</td></tr><tr><td><strong><code>Values</code></strong> <em>(Valores)</em></td><td>Campos numéricos que se muestran como resultado dentro de la tabla.</td></tr></tbody></table>

<table><thead><tr><th width="186">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Arrastrar</strong></td><td>Permite sujetar un campo y ubicarlo en la sección deseada.</td></tr><tr><td><strong>Eliminar ✖️</strong></td><td>Retira el campo de la sección en la que se encuentra.</td></tr><tr><td><strong>Cancel</strong> <em>(Cancelar)</em></td><td>Cierra la ventana sin aplicar los cambios realizados.</td></tr><tr><td><strong>Apply</strong> <em>(Aplicar)</em></td><td>Aplica los cambios realizados en todas las secciones y actualiza el reporte.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="194">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-comisiones-global-2..md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar las comisiones generadas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-comisiones-global-2..md#id-6.-validaciones-y-reglas-del-negocio"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las comisiones en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Delimita el período sobre el cual se consultan las comisiones generadas.</td></tr><tr><td><strong><code>Tipo Usuario</code></strong></td><td>Lista desplegable</td><td>Acota la consulta al tipo de usuario que generó la comisión <em>(Concesionario, Subconcesionario, Subconcesionario 2, Afiliado y Punto de Venta)</em>. <a href="https://virtualsoft.gitbook.io/untitled/glosario#tipos-de-usuario-comision">Ver definiciones</a>.</td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Lista desplegable</td><td>Restringe los resultados a un punto de venta determinado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente las comisiones generadas en el país seleccionado.</td></tr><tr><td><strong><code>Nombre Afiliado</code></strong></td><td>Campo de texto</td><td>Localiza las comisiones de un afiliado específico a partir de su nombre.</td></tr><tr><td><strong><code>Mi Comisión</code></strong></td><td>Botón de opción</td><td>Limita el reporte a las comisiones asociadas al usuario que realiza la consulta, en lugar de mostrar las de toda la red.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Botón de opción</td><td><p>Determina el nivel de detalle con el que se presenta el reporte.</p><ul><li><strong>Totales:</strong> muestra la información consolidada del período.</li><li><strong>Detallado:</strong> muestra el desglose de cada registro.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo es <strong>obligatorio</strong> para ejecutar la consulta.</p></div></td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta se despliega una tabla en la que **cada fila corresponde a un usuario de la red comercial** y **cada grupo de columnas a una categoría de comisión**. Dentro de cada categoría se repiten siempre los mismos campos, lo que permite comparar el resultado de un usuario entre una categoría y otra.

El contenido de las filas depende de la opción seleccionada en el filtro **`Tipo`**:&#x20;

* **Detallado** se muestra una fila por cada usuario, identificada con su moneda, su ID, su nombre y la jerarquía a la que pertenece.
* **Totales** se muestra una única fila por moneda que consolida a todos los usuarios, por lo que los campos de jerarquía aparecen vacíos.

<table><thead><tr><th width="232">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Moneda</code></strong></td><td>Texto</td><td>Moneda en la que se generaron las operaciones del registro.</td></tr><tr><td><strong><code>ID usuario</code></strong></td><td>Numérico</td><td>Identificador del usuario al que corresponde la comisión.</td></tr><tr><td><strong><code>Nombre de usuario</code></strong></td><td>Texto</td><td>Nombre o correo con el que está registrado el usuario.</td></tr><tr><td><strong><code>Concesionario</code></strong></td><td>Texto</td><td><p>Concesionario del que depende el usuario dentro de la red comercial.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Nota:</strong> El valor <strong>Directo</strong> en este campo y en los dos siguientes indica que el usuario <strong>no depende de nadie en ese nivel</strong>. Un usuario con los tres en <em>Directo</em> se encuentra en el nivel más alto de la red.</p></div></td></tr><tr><td><strong><code>Subconcesionario</code></strong></td><td>Texto</td><td>Subconcesionario del que depende el usuario.</td></tr><tr><td><strong><code>Subconcesionario 2</code></strong></td><td>Texto</td><td>Segundo nivel de subconcesionario del que depende el usuario.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Numérico</td><td>Valor total generado por las operaciones de la categoría. Es la base sobre la que se calcula la comisión.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Numérico</td><td><p>Valor de la comisión obtenida por el usuario en esa categoría.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo puede presentar <strong>valores negativos</strong> cuando, en el período consultado, los premios y bonos superan lo apostado dentro de la categoría. No corresponde a un error del reporte.</p></div></td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Numérico</td><td>Total apostado dentro de la categoría.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Numérico</td><td>Total pagado en premios dentro de la categoría.</td></tr><tr><td><strong><code>Bonos</code></strong></td><td>Numérico</td><td>Total otorgado en bonos dentro de la categoría.</td></tr><tr><td><strong><code>Impuesto (%)</code></strong></td><td>Numérico</td><td>Porcentaje de impuesto aplicado sobre la base antes de calcular la comisión.</td></tr><tr><td><strong><code>Valor del impuesto ($)</code></strong></td><td>Numérico</td><td>Monto efectivamente descontado por concepto de impuesto.</td></tr></tbody></table>

{% hint style="warning" %}
**Notas:**&#x20;

* La diferencia entre las categorías **GGR** y **NGR** está en qué se descuenta antes de calcular la comisión. El **GGR** _(ingreso bruto)_ corresponde a lo apostado menos los premios pagados, mientras que el **NGR** _(ingreso neto)_ parte del GGR y descuenta además los bonos otorgados y, cuando aplica, los impuestos. Por esta razón, una misma operación genera una comisión menor en una categoría NGR que en una GGR.
* En la parte inferior de la tabla se muestra una fila con el total de cada columna. El reporte **siempre genera resultados**, aun cuando no se hayan generado comisiones durante el período consultado; en ese caso los valores se muestran en cero, por lo que una tabla con resultados no implica que haya comisiones por pagar.
{% endhint %}

Los campos anteriores se repiten para cada una de las siguientes categorías de comisión:

<table><thead><tr><th width="274">Categoría</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Deposito Comision por Transaccion</strong></td><td>Comisión generada por cada transacción de depósito procesada.</td></tr><tr><td><strong>Deposito Punto venta</strong></td><td>Comisión generada sobre los depósitos realizados en el punto de venta.</td></tr><tr><td><strong>Deposito Afiliados</strong></td><td>Comisión generada sobre los depósitos de los usuarios asociados al afiliado.</td></tr><tr><td><strong>Notas de retiro Punto venta</strong></td><td>Comisión generada sobre las notas de retiro pagadas en el punto de venta.</td></tr><tr><td><strong>(SC#) Sportbook</strong> <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr"><strong>GGR</strong></a> <strong>Punto venta</strong></td><td>Comisión calculada sobre el <strong>GGR</strong> de apuestas deportivas del punto de venta.</td></tr><tr><td><strong>(SC#) Sportbook</strong> <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr"><strong>GGR</strong></a> <strong>Afiliados</strong></td><td>Comisión calculada sobre el <strong>GGR</strong> de apuestas deportivas de los usuarios asociados al afiliado.</td></tr><tr><td><strong>(SC#) Sportbook</strong> <a href="https://virtualsoft.gitbook.io/plantillas/glosario#net-gaming-revenue-ngr"><strong>NGR</strong></a> <strong>Afiliados</strong></td><td>Comisión calculada sobre el <strong>NGR</strong> de apuestas deportivas de los usuarios asociados al afiliado.</td></tr><tr><td><strong>(SC#) Sportbook</strong> <a href="https://virtualsoft.gitbook.io/plantillas/glosario#net-gaming-revenue-ngr"><strong>NGR</strong></a> <strong>Afiliados con impuesto del 12%</strong></td><td>Comisión calculada sobre el <strong>NGR</strong> de apuestas deportivas del afiliado, descontando previamente el <strong>12%</strong> de impuesto correspondiente a la normativa peruana.</td></tr><tr><td><strong>(SC#) Casino</strong> <a href="https://virtualsoft.gitbook.io/plantillas/glosario#net-gaming-revenue-ngr"><strong>NGR</strong></a> <strong>Afiliados</strong></td><td>Comisión calculada sobre el <strong>NGR</strong> de casino de los usuarios asociados al afiliado.</td></tr><tr><td><strong>Total</strong></td><td>Consolida los campos de todas las categorías anteriores.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El campo **`Tipo`** es obligatorio para ejecutar la consulta; los demás filtros son opcionales.
* Los resultados mostrados corresponden únicamente a los criterios seleccionados en los filtros.
* El reporte siempre devuelve resultados, incluso cuando no se generaron comisiones en el período consultado.
* La comisión no se calcula sobre el total apostado, sino sobre el **NGR neto**, es decir, sobre lo que efectivamente queda tras descontar premios, bonos e impuestos.
* La lógica de cálculo descrita a continuación aplica exclusivamente a los afiliados registrados en **Gangabet Perú** o **Doradobet Perú**, conforme a la normativa local vigente.

**Cálculo de la comisión del afiliado**

> **Fórmulas aplicadas**
>
> 1. _NGR = Apuestas − Premios − Bonos_
> 2. _Impuestos = NGR × 12%_
> 3. _NGR Neto = NGR − Impuestos_
> 4. _Comisión del afiliado = NGR Neto × % Comisión_

{% hint style="info" %}
**Ejemplo de cálculo**

Un afiliado con un **25%** de comisión cuyo período registra **1.000 PEN** en apuestas, **800 PEN** en premios y **50 PEN** en bonos:

* **NGR:** 1.000 − 800 − 50 = **150 PEN**
* **Impuesto (12%):** 150 × 12% = **18 PEN**
* **NGR Neto:** 150 − 18 = **132 PEN**
* **Comisión (25%):** 132 × 25% = **33 PEN**

En este ejemplo, el afiliado recibiría **33 PEN** como comisión neta del período.
{% endhint %}

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>30/07/2025</td><td>Karol Navia</td><td>Documento inicial, actualización del formato</td></tr><tr><td>1.1</td><td>25/08/2025</td><td>David Velasquez</td><td>Mejora de formato e incorporación de la sección "Click to configure".</td></tr><tr><td>1.2</td><td>19/10/2026</td><td>David Velasquez</td><td>Actualización de todo el módulo</td></tr></tbody></table>

</details>
