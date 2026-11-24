# Crear mensaje

<mark style="color:$info;">Crea y consulta los mensajes y pop-ups que se envían a través del BackOffice a los usuarios de la red comercial: puntos de venta, concesionarios y subconcesionarios.</mark>

{% hint style="warning" %}
**Nota:** Las comunicaciones para los jugadores de la plataforma de Usuarios Online _(mensajes, banners, pop-ups y franjas superiores)_ se envían desde **Mensajes > Lista**.
{% endhint %}

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Mensajes > Crear mensaje

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (589) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección crear mensaje.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="crear-mensaje.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los mensajes enviados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="crear-mensaje.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los mensajes en la tabla de resultados.</td></tr><tr><td><a href="crear-mensaje.md#id-6.-anadir-mensaje"><strong>Añadir mensaje</strong></a></td><td>Abre el formulario para crear y enviar un nuevo mensaje.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mensaje ID</code></strong></td><td>Campo numérico</td><td>Localiza un mensaje por su identificador único.</td></tr><tr><td><strong><code>Título</code></strong></td><td>Campo de texto</td><td>Busca los mensajes por su título.</td></tr><tr><td><strong><code>¿Leído?</code></strong></td><td>Lista desplegable</td><td>Separa los mensajes según si el destinatario los abrió <em>(Sí o No)</em>.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Muestra los mensajes según su forma de presentación <em>(Mensaje o Pop-up)</em>.</td></tr><tr><td><strong><code>Emisor</code></strong></td><td>Campo de texto</td><td>Consulta los mensajes enviados por el usuario indicado.</td></tr><tr><td><strong><code>Receptor</code></strong></td><td>Campo de texto</td><td>Identifica los mensajes dirigidos al usuario indicado.</td></tr><tr><td><strong><code>Tipo de red</code></strong></td><td>Lista desplegable</td><td>Acota los resultados al tipo de usuario de la red comercial <em>(Punto de venta, Concesionario o Subconcesionario)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los mensajes que cumplen con los filtros aplicados.

<table><thead><tr><th width="176">Campo</th><th width="120">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Muestra el identificador único del mensaje generado por el sistema.</td></tr><tr><td><strong><code>Emisor</code></strong></td><td>Texto</td><td>Indica el usuario o el sistema que envió el mensaje.</td></tr><tr><td><strong><code>Receptor</code></strong></td><td>Texto</td><td>Identifica al usuario que recibe el mensaje.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha</td><td>Registra el momento en que se creó el mensaje.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Fecha</td><td>Señala el momento en que el mensaje deja de estar vigente.</td></tr><tr><td><strong><code>Asunto</code></strong></td><td>Texto</td><td>Corresponde al título del mensaje.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Texto</td><td>Confirma si el destinatario abrió el mensaje <em>(Sí o No)</em>.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Texto</td><td>Presenta la forma en que se mostró el mensaje <em>(Mensaje o Pop-up)</em>.</td></tr><tr><td><strong><code>Tipo de red</code></strong></td><td>Texto</td><td>Refleja el tipo de usuario de la red comercial al que se dirigió el mensaje <em>(Punto de venta, Concesionario o Subconcesionario)</em>.</td></tr></tbody></table>

***

### 6. Añadir mensaje

Al presionar **Añadir mensaje**, se despliega el formulario para crear el mensaje y definir su destinatario.

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Define el identificador único del usuario que recibe el mensaje.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Establece hasta cuándo el mensaje permanece vigente.</td></tr><tr><td><strong><code>Asunto</code></strong></td><td>Campo de texto</td><td>Indica el título del mensaje.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país de los usuarios a los que se dirige el mensaje.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td><p>Determina cómo se presenta el mensaje al destinatario.</p><ul><li><strong>Mensaje:</strong> se entrega como un mensaje en la cuenta del destinatario.</li><li><strong>Pop-up:</strong> se muestra como una ventana emergente en el BackOffice del destinatario.</li></ul></td></tr><tr><td><strong><code>Tipo de red</code></strong></td><td>Lista desplegable</td><td><p>Especifica el tipo de usuario de la red comercial al que se dirige el mensaje.</p><ul><li><strong>Punto de venta:</strong> centro de operaciones de la red comercial, al que se afilian otros usuarios.</li><li><strong>Concesionario:</strong> usuario que administra uno o varios puntos de venta.</li><li><strong>Subconcesionario:</strong> usuario asociado a un concesionario, que administra los puntos de venta bajo su responsabilidad.</li></ul></td></tr><tr><td><strong><code>Mensaje</code></strong></td><td>Campo de texto</td><td>Contiene el texto que se muestra al destinatario.</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Botón</td><td>Crea el mensaje y lo envía al destinatario.</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* El mensaje se crea solo al presionar **Guardar**.
* Un pop-up se muestra únicamente a los usuarios a los que fue asignado.
* El mensaje deja de estar vigente al cumplirse su **`Fecha de Expiración`**.
* **Exportar** descarga únicamente los resultados mostrados tras aplicar los filtros.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>29/01/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
