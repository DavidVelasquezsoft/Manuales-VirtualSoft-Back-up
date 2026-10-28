# Historial de mensajes

<mark style="color:$info;">Reúne el registro histórico de los mensajes creados desde el BackOffice y permite hacerles seguimiento. Desde este mismo módulo se crean los nuevos mensajes y se inactivan las campañas que ya no deben mostrarse.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Mensajes > Historial de mensajes

{% hint style="warning" %}
**Nota:** El acceso a este módulo requiere el permiso asignado para ello. Los usuarios que no cuenten con él no visualizan la sección.
{% endhint %}

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (732).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Historial de mensajes</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="154.88885498046875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="historial-de-mensajes.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los mensajes registrados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="historial-de-mensajes.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los mensajes en la tabla de resultados.</td></tr><tr><td><a href="historial-de-mensajes.md#id-6.-anadir-mensaje"><strong>Añadir Mensaje</strong></a></td><td>Despliega el formulario para crear un nuevo mensaje y definir a qué usuarios se dirige.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="124.888916015625">Campo</th><th width="116.44439697265625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Campaña</code></strong></td><td>Campo de texto</td><td>Localiza un mensaje puntual a partir del identificador de su campaña.</td></tr><tr><td><strong><code>Usuario creador</code></strong></td><td>Campo de texto</td><td><p>Consulta los mensajes creados por un usuario determinado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo no recibe el ID del usuario, sino su <strong>ID Agregator</strong>. Para conocerlo debe consultarse el reporte <a href="../reportes/usuario-agregator.md">Usuario - Agregator</a>.</p></div></td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Calendario</td><td>Delimita los resultados según el rango de fechas en el que se crearon los mensajes.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra la consulta según la vigencia del mensaje <em>(Activo, Inactivo o Todos)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los mensajes que cumplen con los filtros aplicados.

<table><thead><tr><th width="176">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Campaña</code></strong></td><td>Identificador único de la campaña de mensajes.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha y hora en la que se registró el mensaje en el sistema.</td></tr><tr><td><strong><code>Asunto</code></strong></td><td>Título con el que el mensaje se presenta al destinatario.</td></tr><tr><td><strong><code>Usuario creador</code></strong></td><td><p>Usuario del BackOffice que creó el mensaje.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Corresponde al <strong>ID Agregator</strong>, que es el identificador del usuario dentro del sistema interno y se vincula con el ID del usuario del partner. Para identificar a qué persona corresponde debe consultarse el reporte <a href="../reportes/usuario-agregator.md">Usuario - Agregator</a>.</p></div></td></tr><tr><td><strong><code>Fecha Inicio</code></strong></td><td>Fecha y hora a partir de la cual el mensaje se muestra a los destinatarios.</td></tr><tr><td><strong><code>Fecha Expiración</code></strong></td><td>Fecha y hora en la que el mensaje deja de mostrarse.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Vigencia actual de la campaña: <strong>Activo</strong> cuando el mensaje sigue disponible para los destinatarios, o <strong>Inactivo</strong> cuando se retiró de circulación.</td></tr><tr><td><strong><code>Visualizar</code></strong> <i class="fa-eye">:eye:</i></td><td><p>Despliega una ventana emergente con el contenido del mensaje tal como se creó.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p> <strong>Nota:</strong> La vista es únicamente de consulta: el contenido no puede modificarse desde allí.</p></div></td></tr><tr><td><strong><code>Cambiar estado</code></strong> <i class="fa-xmark">:xmark:</i></td><td><p>Inactiva la campaña y evita que el mensaje continúe mostrándose a los destinatarios. Antes de ejecutar la acción, el sistema solicita confirmación mediante una ventana emergente.</p><div data-gb-custom-block data-tag="hint" data-style="danger" class="hint hint-danger"><p><strong>Importante:</strong> La inactivación es <strong>definitiva</strong> y no puede revertirse. Una vez que la campaña se encuentra en estado <strong>Inactivo</strong>, esta acción deja de estar disponible. Si se requiere enviar nuevamente el mensaje, es necesario crear una nueva campaña.</p></div></td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Los registros del historial son permanentes: no se eliminan de forma automática ni al inactivar la campaña. Un mensaje inactivado conserva su registro con toda su información para efectos de trazabilidad.
{% endhint %}

***

### 6. Añadir mensaje

Mediante el botón **`Añadir Mensaje`** se despliega una ventana emergente con el formulario para crear una nueva campaña.

<table><thead><tr><th width="139.3333740234375">Campo</th><th width="131.16668701171875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuarios</code></strong></td><td>Archivo CSV</td><td>Permite cargar un archivo con los IDs de los usuarios destinatarios del mensaje, para campañas dirigidas a varios usuarios a la vez.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Identificador del usuario destinatario, cuando el mensaje se dirige a uno en particular.</td></tr><tr><td><strong><code>Fecha Inicio</code></strong></td><td>Calendario</td><td>Fecha y hora a partir de la cual el mensaje comienza a mostrarse a los destinatarios.</td></tr><tr><td><strong><code>Fecha Expiración</code></strong></td><td>Calendario</td><td>Fecha y hora en la que el mensaje deja de mostrarse.</td></tr><tr><td><strong><code>Asunto</code></strong></td><td>Campo de texto</td><td>Título con el que el mensaje se presenta al destinatario. Es el valor que se visualiza en la tabla de resultados.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País al que aplica la campaña.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Determina de qué forma se le presenta el mensaje al destinatario. Las dos opciones disponibles se describen a continuación.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
**Opciones del campo Tipo**

<table><thead><tr><th width="103.666748046875">Tipo</th><th>Comportamiento</th></tr></thead><tbody><tr><td><strong>Mensaje</strong></td><td>El mensaje llega a la <strong>bandeja de entrada</strong> del usuario dentro del BackOffice, donde permanece disponible para que lo consulte cuando lo necesite. No interrumpe su trabajo.</td></tr><tr><td><strong>Pop-up</strong></td><td>El mensaje se muestra en una <strong>ventana emergente al iniciar sesión</strong> en el BackOffice una sola vez. Se utiliza para comunicados que el usuario debe ver de inmediato.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="139.33331298828125">Campo</th><th width="128.66668701171875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de red</code></strong></td><td>Lista desplegable</td><td>Delimita el mensaje a un nivel de la red comercial <em>(Punto de venta, Concesionario o Subconcesionario)</em>, de modo que solo lo reciban los usuarios que pertenecen a ese nivel.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Contenido del mensaje que verá el destinatario. Es el texto que se despliega mediante la acción <strong>Visualizar</strong>.</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* Los resultados mostrados corresponden únicamente a los criterios seleccionados en los filtros.
* El mensaje se muestra a los destinatarios entre la **`Fecha Inicio`** y la **`Fecha Expiración`** configuradas, siempre que la campaña se encuentre en estado **Activo**.
* La inactivación de una campaña requiere confirmación y es **definitiva**: una campaña inactivada no puede reactivarse, y la acción deja de estar disponible en esos registros. Para volver a enviar el mensaje debe crearse una campaña nueva.
* El campo **`Usuario creador`**, tanto en el filtro como en la tabla de resultados, corresponde al **ID Agregator** del usuario y no a su ID de usuario. La equivalencia entre ambos se consulta en el reporte  [Usuario - Agregator](../reportes/usuario-agregator.md).

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>27/10/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-34262">Documento inicial</a></td></tr></tbody></table>

</details>
