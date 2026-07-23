# Reporte de Apuestas

Reporte de las solicitudes de retiros realizadas por medio del punto de venta.

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Gestión punto de venta > 🔍 Ingresar a punto de venta > Reportes > Reporte de Retiros.

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (699).png" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte de Retiros.</p></figcaption></figure>

***

### 3.  Acciones de usuario

<table><thead><tr><th width="170.4444580078125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Permite buscar el historial de los retiros realizados por el punto de venta con la ayuda de filtros.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros por defecto.</td></tr><tr><td><strong>Consultar</strong></td><td>Aplica los filtros configurados y obtén los resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="135.25">Campo</th><th width="117.25">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Rango de fechas en la cual se realizaron los Retiros.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Estado en el que se encuentra la solicitud de retiro</td></tr><tr><td><strong><code>Por fecha de retiro pagado</code></strong></td><td>Selector</td><td>Muestra únicamente los retiros cuya solicitud de retiro fue pagada durante el rango de fechas seleccionado.</td></tr></tbody></table>

### 5. Resultado de Consulta

El reporte de solitudes de retiro se visualizará en una tabla que contiene las siguientes columnas:

<table><thead><tr><th width="140.25">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Punto de venta</code></strong></td><td>Nombre del punto de venta que realizó la gestión de la nota de retiro.</td></tr><tr><td><strong><code>🔍</code></strong></td><td>Accede a los detalles avanzados de la nota de retiro seleccionada.</td></tr><tr><td><strong><code>Id</code></strong></td><td>Identificador único del usuario que realizó la gestión de la nota de retiro.</td></tr><tr><td><strong><code>ID Cliente</code></strong></td><td>Identificador único del usuario al que se le gestionó la nota de retiro.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto total por el cual fue creada la nota de retiro.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado en el que se encuentra la nota de retiro.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha en la que se creó la nota de retiro.</td></tr><tr><td><strong><code>Fecha Pagado</code></strong></td><td>Fecha en la que se pagó al usuario el retiro solicitado.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Descripción breve de la nota de retiro.</td></tr><tr><td><strong><code>Por fecha de retiro pagado</code></strong></td><td>Fecha en la que se pagó la nota de retiro.</td></tr></tbody></table>

<details>

<summary><strong>Detalles Avanzados</strong></summary>

Los detalles avanzados presentan una tabla con información más exacta del retiro seleccionado

<table><thead><tr><th width="142">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>🔍</code></strong></td><td>Despliega la información del retiro en un panel de información.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del usuario al que se le pagará la nota de retiro.</td></tr><tr><td><strong><code>Modificó</code></strong></td><td>Identificador único del usuario que realizó la modificación de la nota de retiro.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se modificó la nota de retiro.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de acción tomada con la nota de retiro <em>(Creación o pagada).</em></td></tr><tr><td><strong><code>Monto</code></strong></td><td>Monto por el cual fue creado la nota de retiro.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Descripción breve de la nota de retiro.</td></tr></tbody></table>

**Panel de información**:

<table><thead><tr><th width="147">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del usuario relacionado a la nota de retiro.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de modificación realizada a la nota de retiro <em>(Creación o pagada)</em>.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se modificó la nota de retiro.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Monto total por el cual se gestionó la nota de retiro.</td></tr><tr><td><strong><code>Nombre sistema de pago</code></strong></td><td>Nombre de la pasarela de pago con la que se procesó el retiro.</td></tr></tbody></table>

</details>

***

### 6. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="119.14813232421875">Versión</th><th width="130.77777099609375">Fecha</th><th width="164.5555419921875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2026-07-22</td><td>Ronald Peláez</td><td>Documento inicial</td></tr></tbody></table>

</details>
