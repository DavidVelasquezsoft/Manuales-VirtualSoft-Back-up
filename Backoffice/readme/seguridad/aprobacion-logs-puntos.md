# Aprobación Logs Puntos

<mark style="color:$info;">Reúne las solicitudes de modificación de la información de los puntos de venta y su estado de aprobación. Cada registro muestra el dato que se desea modificar, su valor anterior, el nuevo valor y el usuario que solicita el cambio.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Seguridad > Aprobación Logs Puntos

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FPFmYstyM8oBDdWGMjeiQ%2Fimage.png?alt=media&#x26;token=c7d18ba2-0fd5-43a1-ae9f-5606b662cafa" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Aprobación Logs Puntos.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="160">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="aprobacion-logs-puntos.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los logs registrados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="aprobacion-logs-puntos.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los logs en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="200">Campo</th><th width="140">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Delimita el rango de fechas en que se registraron las solicitudes de cambio.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Localiza las solicitudes asociadas al punto de venta cuya información se modifica, a partir de su identificador único.</td></tr><tr><td><strong><code>Usuario (Correo electrónico)</code></strong></td><td>Campo de texto</td><td>Consulta las solicitudes de un punto de venta a partir de su correo electrónico. Funciona como alternativa al <strong><code>ID Usuario</code></strong> cuando no se conoce el identificador.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Acota la consulta a las solicitudes de los puntos de venta del país seleccionado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente las solicitudes que se encuentran en el estado seleccionado <em>(Pendiente, Aprobado o Rechazado)</em>. El significado de cada estado se describe en la columna <strong><code>Estado</code></strong> de los resultados.</td></tr><tr><td><strong><code>Campo</code></strong></td><td>Campo de texto</td><td>Reúne las solicitudes que modifican un dato específico del punto de venta.</td></tr><tr><td><strong><code>Usuario Solicita</code></strong></td><td>Campo numérico</td><td>Restringe la consulta a las solicitudes registradas por un usuario específico, a partir de su identificador único.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los logs que cumplen con los filtros aplicados.

<table><thead><tr><th width="170">Campo</th><th width="110">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acción</code></strong></td><td>Acción</td><td><p>Contiene las opciones para <strong>aprobar</strong> o <strong>rechazar</strong> la solicitud. Las opciones están disponibles solo cuando el log se encuentra en estado <strong>Pendiente</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al aprobar, el sistema aplica el valor de la columna <strong><code>Nuevo</code></strong> en la información del punto de venta. Al rechazar, el punto de venta conserva el valor de la columna <strong><code>Antiguo</code></strong>.</p></div></td></tr><tr><td><strong><code>País</code></strong></td><td>Texto</td><td>Muestra el país del punto de venta asociado a la solicitud.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identifica de forma única cada <a href="https://virtualsoft.gitbook.io/untitled/glosario#logs">log</a> registrado.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha</td><td>Indica la fecha y la hora en que se registró la solicitud de cambio.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identifica al punto de venta cuya información se modifica.</td></tr><tr><td><strong><code>Usuario Solicita</code></strong></td><td>Numérico</td><td><p>Registra el identificador del usuario que realizó la solicitud de cambio.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> si un usuario del BO edita la información de un punto de venta, <strong><code>ID Usuario</code></strong> muestra el ID del punto de venta y <strong><code>Usuario Solicita</code></strong>, el ID de quien realizó el cambio.</p></div></td></tr><tr><td><strong><code>Usuario Aprueba</code></strong></td><td>Texto</td><td>Muestra el usuario que aprobó la solicitud.</td></tr><tr><td><strong><code>Campo</code></strong></td><td>Texto</td><td>Indica el dato del punto de venta que se solicita modificar.</td></tr><tr><td><strong><code>Antiguo</code></strong></td><td>Texto</td><td>Muestra el valor que tenía el dato antes de la solicitud.</td></tr><tr><td><strong><code>Nuevo</code></strong></td><td>Texto</td><td>Muestra el valor solicitado para el dato.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td><p>Indica la etapa en que se encuentra la solicitud:</p><ul><li><strong>Pendiente:</strong> la solicitud espera revisión.</li><li><strong>Aprobado:</strong> la solicitud fue autorizada.</li><li><strong>Rechazado:</strong> la solicitud fue descartada.</li></ul></td></tr></tbody></table>

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>10/12/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>03/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
