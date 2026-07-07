---
description: Permite consultar los retiros hechos por el usuario
---

# Reporte de Retiros

### 1. Acceso al módulo

**Ruta de acceso**: Backoffice > Jugadores > Reportes > Reporte de retiros

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (581).png" alt=""><figcaption></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="119.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtro</strong></td><td>Permite filtrar la información para obtener resultados más precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="reporte-de-retiros.md#id-3.1.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. Filtros

Tendrás los siguientes filtros que te ayudarán a realizar una búsqueda más detallada:

<table><thead><tr><th width="125.11102294921875">Campo</th><th width="119.66668701171875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>fecha</code></strong></td><td>Calendario</td><td>Filtra según la fecha en la que se generó el reporte.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Numérico</td><td>Filtra por un ID externo que se genera al momento de realizar el movimiento.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Numérico</td><td>Dirección IP desde la cual se hizo el retiro.</td></tr><tr><td><strong><code>Punto de venta</code></strong></td><td>Lista desplegable</td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#punto-de-venta">Punto de venta</a> asociado al retiro.</td></tr><tr><td><strong><code>Formas de pago</code></strong></td><td>Lista desplegable</td><td>Filtra según el tipo de forma de pago por el cual se realizó el retiro.</td></tr><tr><td><strong><code>Valor minimo</code></strong></td><td>Numérico</td><td>Filtra por valor mínimo de retiros.</td></tr><tr><td><strong><code>Valor máximo</code></strong></td><td>Numérico</td><td>Filtra por el valor máximo de retiros.</td></tr></tbody></table>

***

### 5. Resultados de Consulta

Aplica los filtros seleccionados y muestra los reportes detallados del historial de retiros del usuario.

<table><thead><tr><th width="203.5">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td>🔎</td><td>Despliega barra lateral de detalles avanzados sobre ese retiro.</td></tr><tr><td>Columna de acciones</td><td>Permite realizar distintas acciones cuando un retiro esta en proceso.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se registró la solicitud de retiro.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual de la transacción <em>(Ej: pendiente, pagado, rechazado, etc.).</em></td></tr><tr><td><strong><code>Fecha Pagado</code></strong></td><td>Fecha en la que el retiro fue procesado y pagado.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto del retiro realizado.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del retiro.</td></tr><tr><td><strong><code>ID Cliente</code></strong></td><td>Identificador único del cliente que realizó el retiro.</td></tr><tr><td><strong><code>Forma de pago</code></strong></td><td>Canal de pago (Bancaria, Criptomonedas, etc.).</td></tr><tr><td><strong><code>Método de pago</code></strong></td><td>Forma en la que se realizó el pago (<em>Todos</em>, <em>Pagado físicamente</em> o <em>Pagado por sistema</em>.)</td></tr><tr><td><strong><code>Tipo de cuenta</code></strong></td><td>Tipo de cuenta por la que se solicitó el retiro.</td></tr><tr><td><strong><code>Cuenta bancaria</code></strong></td><td>Muestra el nombre de la cuenta utilizada para solicitar el retiro.</td></tr><tr><td><strong><code>Código interbancario</code></strong></td><td>Código de transacción interbancaria (si aplica).</td></tr><tr><td><strong><code>Departamento</code></strong></td><td>Departamento desde el cual se hizo el retiro.</td></tr><tr><td><strong><code>Ciudad</code></strong></td><td>Ciudad desde la cual se realizó el retiro.</td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Nombre o identificador del punto de venta asociado al retiro.</td></tr><tr><td><strong><code>IP</code></strong></td><td>Dirección IP registrada.</td></tr></tbody></table>

***

### 6. Control de versiones

<table><thead><tr><th width="169.22216796875" align="right">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td align="right">1.0</td><td>2025-09-23</td><td>David velasquez</td><td>Documento inicial.</td></tr></tbody></table>
