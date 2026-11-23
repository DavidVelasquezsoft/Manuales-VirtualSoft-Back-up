# Aprobación Logs

<mark style="color:$info;">Reúne y centraliza las solicitudes de modificación de la información de los usuarios que requieren autorización previa para su aplicación. Cada registro muestra el dato que se desea modificar, su valor anterior, el nuevo valor y el usuario que solicita el cambio, permitiendo revisar y gestionar las solicitudes desde este módulo.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Seguridad > Aprobación de logs

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2Fu7qLcdWre8p2xc9q1jWV%2Fimage.png?alt=media&#x26;token=e7ea426f-a42e-49db-ac47-74738688c976" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Aprobación de logs.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="160">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="aprobacion-logs.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los logs registrados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="aprobacion-logs.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los logs en la tabla de resultados.</td></tr><tr><td><strong>Aprobar</strong></td><td>Aplica el cambio solicitado en la información del usuario y cambia el estado del log a <strong>Aprobado</strong>. Se ejecuta desde la columna <strong><code>Acción</code></strong> de la tabla de resultados, solo en logs con estado <strong>Pendiente</strong>.</td></tr><tr><td><strong>Rechazar</strong></td><td>Descarta el cambio solicitado y cambia el estado del log a <strong>Rechazado</strong>. La información del usuario conserva su valor anterior. Al igual que Aprobar, solo está disponible en logs con estado <strong>Pendiente</strong>.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="156.66668701171875">Campo</th><th width="125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Delimita el rango de fechas en que se registraron las solicitudes de cambio.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Localiza las solicitudes asociadas al usuario cuya información se modifica, a partir de su identificador único.</td></tr><tr><td><strong><code>Usuario (Correo electrónico)</code></strong></td><td>Campo de texto</td><td>Consulta las solicitudes de un usuario a partir de su correo electrónico. Funciona como alternativa al <strong><code>ID Usuario</code></strong> cuando no se conoce el identificador.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Acota la consulta a las solicitudes de los usuarios del país seleccionado.</td></tr></tbody></table>

#### 4.1. Filtros avanzados

Los filtros avanzados complementan los filtros principales y precisan la búsqueda según el estado de la solicitud, el dato modificado y el usuario que solicita el cambio.

<table><thead><tr><th width="135">Campo</th><th width="124.16668701171875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente las solicitudes que se encuentran en el estado seleccionado <em>(Pendiente, Aprobado o Rechazado)</em>. El significado de cada estado se describe en la columna <strong><code>Estado</code></strong> de los resultados.</td></tr><tr><td><strong><code>Campo</code></strong></td><td>Campo de texto</td><td>Reúne las solicitudes que modifican un dato específico del usuario <em>(Ejemplo: documento de identidad)</em>.</td></tr><tr><td><strong><code>Usuario Solicita</code></strong></td><td>Campo numérico</td><td>Restringe la consulta a las solicitudes registradas por un usuario específico, a partir de su identificador único.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los logs que cumplen con los filtros aplicados.

<table><thead><tr><th width="139.16668701171875">Campo</th><th width="110">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acción</code></strong></td><td>Acción</td><td><p>Contiene las opciones para <strong>aprobar</strong> o <strong>rechazar</strong> la solicitud. Las opciones están disponibles solo cuando el log se encuentra en estado <strong>Pendiente</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al aprobar, el sistema aplica el valor de la columna <strong><code>Nuevo</code></strong> en la información del usuario. Al rechazar, el usuario conserva el valor de la columna <strong><code>Antiguo</code></strong>.</p></div><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al aprobar un cambio de documento de identidad, el sistema verifica que el número no esté registrado en otro usuario de la misma marca y país. Si ya existe, bloquea la aprobación y muestra mensaje de error.</p></div></td></tr><tr><td><strong><code>País</code></strong></td><td>Texto</td><td>Muestra, mediante una bandera, el país del usuario asociado a la solicitud.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identifica de forma única cada <a href="https://virtualsoft.gitbook.io/untitled/glosario#logs">log</a> registrado.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha</td><td>Indica la fecha y la hora en que se registró la solicitud de cambio.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identifica al usuario cuya información se modifica.</td></tr><tr><td><strong><code>Usuario Solicita</code></strong></td><td>Numérico</td><td><p>Registra el identificador del usuario que realizó la solicitud de cambio.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> si un operador del BO edita el documento de un jugador, <strong><code>ID Usuario</code></strong> muestra el ID del jugador y <strong><code>Usuario Solicita</code></strong>, el ID del operador.</p></div></td></tr><tr><td><strong><code>Usuario Aprueba</code></strong></td><td>Texto</td><td>Muestra el identificador y el nombre del usuario que aprobó la solicitud.</td></tr><tr><td><strong><code>Campo</code></strong></td><td>Texto</td><td>Indica el dato del usuario que se solicita modificar <em>(Ejemplo: documento de identidad o fecha de vencimiento del documento)</em>.</td></tr><tr><td><strong><code>Antiguo</code></strong></td><td>Texto</td><td>Muestra el valor que tenía el dato antes de la solicitud. Este valor se mantiene si el log se rechaza.</td></tr><tr><td><strong><code>Nuevo</code></strong></td><td>Texto</td><td>Muestra el valor solicitado. Este valor se aplica en la información del usuario solo cuando el log se aprueba.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td><p>Indica la etapa en que se encuentra la solicitud:</p><ul><li><strong>Pendiente:</strong> la solicitud espera revisión. Es el único estado que muestra opciones en la columna <strong><code>Acción</code></strong>.</li><li><strong>Aprobado:</strong> el cambio se aplicó en la información del usuario.</li><li><strong>Rechazado:</strong> el cambio se descartó y el usuario conserva el valor anterior.</li></ul></td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* Solo los logs en estado **Pendiente** pueden aprobarse o rechazarse.
* Los cambios sujetos a aprobación no se aplican en la información del usuario hasta que el log se aprueba en este módulo. Por ejemplo, la fecha de vencimiento del documento editada desde **BackOffice (BO) > Jugadores > Información** queda pendiente hasta su aprobación.
* Al aprobar un cambio de documento de identidad, el sistema valida que el número no esté registrado en otro usuario. Si ya existe, la aprobación se bloquea.
* La validación de documento duplicado aplica solo a la combinación marca + país. Si el documento está registrado en otra marca, aunque sea del mismo país, la aprobación se permite.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>10/12/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>03/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
