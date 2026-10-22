---
description: >-
  El Reporte de Apuestas permite consultar, analizar y realizar un seguimiento
  detallado de las apuestas registradas en el sistema, incluyendo información
  sobre estados, premios y detalles financieros.
---

# Reporte de Apuestas

<mark style="color:$info;">Permite consultar y hacer seguimiento a las apuestas registradas en la plataforma, con su estado, su valor, los premios asociados y el detalle financiero de cada operación. Desde cada registro es posible abrir el detalle del ticket para conocer qué jugó el cliente, en qué evento, con qué cuota y cuál fue el resultado, así como los movimientos de dinero que generó la apuesta.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Reporte de Apuestas

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FPo01zJFX3Ss2pqblcSpQ%2Fimage.png?alt=media&#x26;token=4b578383-bffb-4534-8ee0-c93e2d6f227b" alt=""><figcaption><p>Figura #1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-apuestas.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar las apuestas registradas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-apuestas.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las apuestas en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="176">Campo</th><th width="136">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Calendario</td><td>Delimita los resultados según el rango de fechas en el que se registraron las apuestas.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Delimita los resultados según el rango de fechas en el que vencen las apuestas.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente las apuestas registradas en el país seleccionado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Acota la consulta según la situación de la apuesta <em>(abierta, cerrada o anulada)</em>.</td></tr><tr><td><strong><code>Usuario ID</code></strong></td><td>Campo numérico</td><td>Consulta las apuestas realizadas por un usuario específico.</td></tr><tr><td><strong><code>Ticket ID</code></strong></td><td>Campo numérico</td><td>Localiza una apuesta puntual a partir del identificador de su ticket.</td></tr><tr><td><strong><code>Beneficiario ID</code></strong></td><td>Campo numérico</td><td>Reúne las apuestas cuyo premio quedó asignado a un beneficiario determinado.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Campo de texto</td><td>Localiza las apuestas realizadas desde una dirección IP específica.</td></tr><tr><td><strong><code>Tipo de Apuesta</code></strong></td><td>Lista desplegable</td><td>Acota la consulta según la composición de la apuesta <em>(simples, combinadas o sistemáticas)</em>.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td><p>Restringe la consulta a las apuestas gestionadas por un proveedor determinado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si no se selecciona ningún proveedor, el reporte devuelve las apuestas de todos ellos, según los demás filtros aplicados.</p></div></td></tr><tr><td><strong><code>Tipo de Usuario</code></strong></td><td>Lista desplegable</td><td>Filtra según el origen de la apuesta <em>(Usuario Final, Punto de Venta o todos)</em>.</td></tr><tr><td><strong><code>Tipo de</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#billetera"><strong><code>Billetera</code></strong></a></td><td>Lista desplegable</td><td>Selecciona la billetera con la que se realizó la apuesta <em>(Online o Quisk)</em>.</td></tr><tr><td><strong><code>Ordenar por</code></strong></td><td>Lista desplegable</td><td>Define el criterio con el que se organizan los resultados <em>(fecha, valor o estado)</em>.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Lista desplegable</td><td>Indica si los resultados se presentan de forma ascendente o descendente según el criterio seleccionado.</td></tr><tr><td><strong><code>Resumido</code></strong></td><td>Casilla de verificación</td><td><p>Cambia la forma en la que se presentan los resultados: en lugar de listar las apuestas una por una, la tabla las agrupa en carpetas que se despliegan por niveles. Al activarla, el filtro <strong><code>Tipo de Apuesta</code></strong> se reemplaza por <strong><code>Tipo para Premios</code></strong>.</p><p>Los resultados se organizan en los <strong>tres niveles</strong> que se describen a continuación:</p><div data-gb-custom-block data-tag="hint" data-style="danger" class="hint hint-danger"><p><strong>Importante:</strong> En la vista resumida <strong>no está disponible el detalle del ticket</strong>, ya que cada registro corresponde a una agrupación y no a una apuesta individual. Para consultar el detalle de una apuesta debe desactivarse esta casilla.</p></div><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La consulta resumida se realiza a <strong>día vencido</strong>, por lo que incluye únicamente fechas ya cerradas y no muestra información del día en curso.</p></div></td></tr></tbody></table>

{% columns %}
{% column width="41.66666666666667%" %}

{% endcolumn %}

{% column width="58.33333333333333%" %}
**Niveles de agrupación de la vista resumida**

Al ejecutar la consulta, la tabla muestra únicamente el primer nivel. Para llegar al detalle se despliega cada carpeta hasta alcanzar el resumen diario:

<table><thead><tr><th width="152">Nivel</th><th>Contenido</th></tr></thead><tbody><tr><td><strong>1. País</strong></td><td>Es lo primero que se visualiza. Agrupa todas las apuestas según el país en el que se registraron. Al desplegar un país se listan los usuarios que realizaron apuestas en él.</td></tr><tr><td><strong>2. Usuario</strong></td><td>Agrupa las apuestas de cada usuario dentro de ese país. Al desplegar un usuario se listan las fechas en las que registró apuestas.</td></tr><tr><td><strong>3. Día</strong></td><td>Último nivel. Presenta el resumen consolidado de las apuestas de ese usuario en cada fecha del período consultado.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="176">Campo</th><th width="126">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Con Eliminadas?</code></strong></td><td>Casilla de verificación</td><td>Incluye en la consulta las apuestas eliminadas.</td></tr></tbody></table>

#### 4.1. Filtros avanzados

<table><thead><tr><th width="212">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Premio Total Mínimo</code></strong></td><td>Campo numérico</td><td>Valor mínimo de premio total a partir del cual se incluyen las apuestas en la consulta.</td></tr><tr><td><strong><code>Premio Total Máximo</code></strong></td><td>Campo numérico</td><td>Valor máximo de premio total hasta el cual se incluyen las apuestas en la consulta.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las apuestas que cumplen con los filtros aplicados.

{% hint style="warning" %}
**Nota:** La estructura de esta tabla corresponde a la consulta **detallada**, en la que cada fila es una apuesta individual. Si se activa la casilla **`Resumido`**, se mantiene la misma vista, pero los registros se presentan agrupados en carpetas por **país**, **usuario** y **día**, y la acción de detalle del ticket deja de estar disponible.
{% endhint %}

<table><thead><tr><th width="150">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha</td><td>Fecha y hora en la que se registró la apuesta.</td></tr><tr><td><strong><code>Detalles</code></strong> <i class="fa-magnifying-glass">:magnifying-glass:</i></td><td>Acción</td><td>Despliega el detalle del ticket, con la composición de la apuesta y los movimientos de dinero que generó.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<details>

<summary>🔽 Detalles del Ticket</summary>

Presenta la jugada realizada por el cliente. Cada fila corresponde a una **selección** del ticket, por lo que una apuesta combinada muestra tantas filas como eventos incluya.

<table><thead><tr><th width="150">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ticket Det Id</code></strong></td><td>Identificador de la selección dentro del ticket.</td></tr><tr><td><strong><code>Ticket ID</code></strong></td><td>Identificador del ticket al que pertenece la selección.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Evento sobre el que el cliente realizó la apuesta.</td></tr><tr><td><strong><code>Market</code></strong></td><td>Mercado seleccionado dentro del evento, es decir, qué se está pronosticando <em>(por ejemplo: 1x2)</em>.</td></tr><tr><td><strong><code>Option</code></strong></td><td>Opción concreta que eligió el cliente dentro de ese mercado.</td></tr><tr><td><strong><code>Odds</code></strong></td><td>Cuota con la que se registró esa selección.</td></tr></tbody></table>

</details>

<details>

<summary>🔽 Historial de Transacciones</summary>

Presenta los movimientos de dinero que generó el ticket a lo largo de su ciclo, desde el descuento del monto apostado hasta su liquidación.

<table><thead><tr><th width="150">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ticket Det Id</code></strong></td><td>Identificador de la selección a la que corresponde el movimiento.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Clase de movimiento registrado <em>(por ejemplo: <strong>BET</strong> para el descuento del monto apostado y <strong>LOSS</strong> para el cierre de una apuesta perdida)</em>.</td></tr><tr><td><strong><code>Ticket ID</code></strong></td><td>Identificador del ticket al que pertenece el movimiento.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha y hora en la que se registró el movimiento.</td></tr><tr><td><strong><code>Transacción Id</code></strong></td><td>Identificador único del movimiento dentro del sistema.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Valor del movimiento. Los cierres que no generan pago se registran en cero.</td></tr></tbody></table>

</details>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="168">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ticket ID</code></strong></td><td>Numérico</td><td>Identificador único del ticket.</td></tr><tr><td><strong><code>Tipo de Apuesta</code></strong></td><td>Texto</td><td>Composición de la apuesta registrada.</td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Texto</td><td>Punto de venta en el que se registró la apuesta.</td></tr><tr><td><strong><code>Fecha de Pago</code></strong></td><td>Fecha</td><td>Fecha en la que se pagó el premio de la apuesta.</td></tr><tr><td><strong><code>Punto Venta Pagó</code></strong></td><td>Texto</td><td>Punto de venta que procesó el pago del premio.</td></tr><tr><td><strong><code>Cajero</code></strong></td><td>Texto</td><td>Cajero que gestionó la transacción.</td></tr><tr><td><strong><code>Usuario ID</code></strong></td><td>Numérico</td><td>Identificador del usuario que realizó la apuesta.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Texto</td><td>Nombre del usuario asociado a la apuesta.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Situación actual de la apuesta.</td></tr><tr><td><strong><code>Fecha Cierre</code></strong></td><td>Fecha</td><td>Fecha en la que se cerró la apuesta.</td></tr><tr><td><strong><code>Beneficiario ID</code></strong></td><td>Numérico</td><td>Identificador del beneficiario al que corresponde el premio, cuando aplique.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Numérico</td><td>Monto apostado en el ticket.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Numérico</td><td>Monto de los premios generados por la apuesta.</td></tr><tr><td><strong><code>Impuesto Premios</code></strong></td><td>Numérico</td><td>Impuesto aplicado sobre los premios.</td></tr><tr><td><strong><code>Impuesto Apuesta</code></strong></td><td>Numérico</td><td>Impuesto aplicado sobre el monto apostado.</td></tr><tr><td><strong><code>Premio Total</code></strong></td><td>Numérico</td><td>Valor del premio una vez descontados los impuestos.</td></tr><tr><td><strong><code>Odds</code></strong></td><td>Numérico</td><td>Cuota con la que se registró el ticket.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Texto</td><td><p>Proveedor que gestiona la apuesta.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Esta información se registra únicamente para las apuestas realizadas a partir de la incorporación de este campo. Las apuestas anteriores no tienen proveedor asociado y se muestran con el valor definido para información no disponible.</p></div></td></tr><tr><td><strong><code>IP</code></strong></td><td>Texto</td><td>Dirección IP desde la que se realizó la apuesta.</td></tr><tr><td><strong><code>Billetera</code></strong></td><td>Texto</td><td>Billetera utilizada en la transacción <em>(Online o Quisk)</em>.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** En la parte inferior de la tabla se muestra una fila con el total de cada columna, calculado sobre todos los registros devueltos por la consulta.
{% endhint %}

***

### 6. Validaciones y reglas del negocio:

* No es obligatorio diligenciar todos los filtros para ejecutar la consulta.
* Los resultados mostrados corresponden únicamente a los criterios seleccionados en los filtros.
* Si se activa la casilla **`Resumido`**, el filtro **`Tipo de Apuesta`** se reemplaza por **`Tipo para Premios`**.
* El filtro **`Proveedor`** devuelve únicamente las apuestas pertenecientes al proveedor seleccionado. Si no se selecciona ninguno, el reporte conserva su comportamiento habitual y muestra las apuestas de todos los proveedores según los demás filtros.
* La columna **`Proveedor`** aplica únicamente a las apuestas registradas a partir de la incorporación de este campo. Las apuestas anteriores se muestran con el valor definido para información no disponible, sin asignarles un proveedor.
* El detalle del ticket presenta una fila por cada selección de la apuesta, con el evento, el mercado, la opción elegida y la cuota tal como quedaron registrados en el ticket.
* La exportación descarga la totalidad de las columnas del reporte, incluida la columna **`Proveedor`**.
* El reporte es informativo: desde este módulo no es posible modificar, anular ni liquidar una apuesta.
* Al activar la casilla **`Resumido`**, el filtro **`Tipo de Apuesta`** se reemplaza por **`Tipo para Premios`** y los resultados se presentan agrupados en tres niveles: **país**, **usuario** y **día**.
* En la vista resumida no es posible consultar el detalle del ticket, ya que cada registro corresponde a una agrupación y no a una apuesta individual.
* La consulta resumida se realiza a **día vencido**: incluye únicamente fechas ya cerradas y no muestra información del día en curso.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="107">Versión</th><th width="139">Fecha</th><th width="157">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/08/2025</td><td>Ronald Peláez</td><td>Documento inicial del manual</td></tr><tr><td>1.1</td><td>22/10/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-34512#icft=VSFT-34512">Incorporación del filtro y la columna Proveedor, y documentación del detalle del ticket.</a></td></tr></tbody></table>

</details>
