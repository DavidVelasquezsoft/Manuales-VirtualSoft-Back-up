# Lista

<mark style="color:$info;">Envía y consulta las comunicaciones que se muestran a los usuarios en la plataforma de Usuarios Online: mensajes directos, banners, pop-ups y franjas superiores.</mark>

{% hint style="warning" %}
**Nota:** Este módulo envía comunicaciones a los jugadores de la plataforma. Los mensajes para los usuarios de la red comercial _(puntos de venta, concesionarios y subconcesionarios)_ se envían desde **Mensajes > Crear mensaje**.
{% endhint %}

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Mensajes > Lista

***

### 2. Tipos de comunicación

El módulo organiza las comunicaciones en cuatro pestañas. Cada pestaña tiene sus propios filtros, resultados y formulario de envío.

<table><thead><tr><th width="176">Pestaña</th><th>Cómo se muestra en la plataforma</th></tr></thead><tbody><tr><td><strong>Mensajes</strong></td><td>Mensaje directo con asunto y contenido, que llega a la cuenta de un usuario específico.</td></tr><tr><td><strong>Banner masivo</strong></td><td>Banner emergente con imagen, texto y botón, que redirige al usuario a un enlace.</td></tr><tr><td><strong>Pop-up</strong></td><td>Ventana emergente con título y contenido. Puede mostrarse dentro de un juego o presentar el contenido de otra página.</td></tr><tr><td><strong>Franja superior</strong></td><td>Barra de texto en la parte superior de la plataforma, que redirige al usuario a un enlace.</td></tr></tbody></table>

{% tabs %}
{% tab title="Mensajes" %}
Envía mensajes directos a un usuario específico de la plataforma.

#### Visualización

<figure><img src="../../.gitbook/assets/image (317) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla pestaña mensajes.</p></figcaption></figure>

#### Acciones disponibles

<table><thead><tr><th width="176">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Definen los criterios de búsqueda para consultar los mensajes enviados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><strong>Consultar</strong></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los mensajes en la tabla de resultados.</td></tr><tr><td><strong>Añadir mensaje</strong></td><td>Abre el formulario para enviar un nuevo mensaje a un usuario.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

#### Filtros

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Campo numérico</td><td>Localiza un mensaje por su identificador único.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Campo numérico</td><td>Busca el mensaje por su código global.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Consulta los mensajes enviados al usuario indicado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Acota los resultados a los usuarios del país seleccionado.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Calendario</td><td>Delimita los mensajes según el momento en que se enviaron.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Restringe los resultados según el momento en que el mensaje deja de estar disponible.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Lista desplegable</td><td>Separa los mensajes según si el usuario los abrió <em>(Sí o No)</em>.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Muestra los mensajes según su estado <em>(Activo o Inactivo)</em>.</td></tr></tbody></table>

#### Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los mensajes que cumplen con los filtros aplicados.

<table><thead><tr><th width="176">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Muestra el identificador único del mensaje.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Presenta el código global del mensaje.</td></tr><tr><td><strong><code>Emisor</code></strong></td><td>Indica el usuario o el sistema que generó el mensaje.</td></tr><tr><td><strong><code>Receptor</code></strong></td><td>Identifica al usuario que recibe el mensaje.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Señala el momento en que el mensaje deja de ser visible para el usuario.</td></tr><tr><td><strong><code>Asunto</code></strong></td><td>Corresponde al título del mensaje.</td></tr><tr><td><strong><code>Mensaje</code></strong></td><td>Contiene el texto enviado al usuario.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Confirma si el usuario abrió el mensaje <em>(Sí o No)</em>.</td></tr></tbody></table>

#### Añadir mensaje

Al presionar **Añadir mensaje**, se despliega el formulario para enviar un mensaje directo a un usuario.

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Define el usuario que recibe el mensaje.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Establece hasta cuándo el mensaje es visible para el usuario.</td></tr><tr><td><strong><code>Asunto</code></strong></td><td>Campo de texto</td><td>Indica el título del mensaje.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país del usuario destinatario.</td></tr><tr><td><strong><code>Mensaje</code></strong></td><td>Campo de texto</td><td>Contiene el texto que se envía al usuario.</td></tr></tbody></table>
{% endtab %}

{% tab title="Banner masivo" %}
Envía banners invasivos: ventanas emergentes con imagen, texto y botón, que se muestran a uno o varios usuarios y los redirigen a un enlace.

#### Visualización

<figure><img src="../../.gitbook/assets/image (293) (1).png" alt=""><figcaption><p>Figura #2: Captura de pantalla pestaña banner masivo.</p></figcaption></figure>

#### Acciones disponibles

<table><thead><tr><th width="176">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Definen los criterios de búsqueda para consultar los banners enviados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><strong>Consultar</strong></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los banners en la tabla de resultados.</td></tr><tr><td><strong>Enviar banner invasivo</strong></td><td>Abre el formulario para enviar un nuevo banner.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

#### Filtros

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Campo numérico</td><td>Localiza un banner por su identificador único.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Campo numérico</td><td>Busca el banner por su código global.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Consulta los banners enviados al usuario indicado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Acota los resultados a los usuarios del país seleccionado.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Calendario</td><td>Delimita los banners según el momento en que se enviaron.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Restringe los resultados según el momento en que el banner deja de mostrarse.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Lista desplegable</td><td>Separa los banners según si el usuario los visualizó <em>(Sí o No)</em>.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Muestra los banners según su estado <em>(Activo o Inactivo)</em>.</td></tr></tbody></table>

#### Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los banners que cumplen con los filtros aplicados.

<table><thead><tr><th width="176">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Muestra el identificador único del banner.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Presenta el código global del banner.</td></tr><tr><td><strong><code>URL Imagen</code></strong></td><td>Contiene el enlace de la imagen que se muestra en el banner.</td></tr><tr><td><strong><code>URL Redirección</code></strong></td><td>Indica la página a la que se dirige al usuario al interactuar con el banner.</td></tr><tr><td><strong><code>Contenido</code></strong></td><td>Corresponde al texto del banner.</td></tr><tr><td><strong><code>Texto del Botón</code></strong></td><td>Señala la etiqueta del botón de acción del banner.</td></tr><tr><td><strong><code>Usuarios ID</code></strong></td><td>Lista los identificadores de los usuarios que reciben el banner.</td></tr><tr><td><strong><code>País</code></strong></td><td>Identifica el país de los usuarios destinatarios.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Registra el momento en que se envió el banner.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Marca el momento en que el banner deja de mostrarse.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Refleja el estado del banner <em>(Activo o Inactivo)</em>.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Confirma si el usuario visualizó el banner <em>(Sí o No)</em>.</td></tr></tbody></table>

#### Enviar banner invasivo

Al presionar **Enviar banner invasivo**, se despliega el formulario para crear el banner y definir sus destinatarios.

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>URL Imagen</code></strong></td><td>Campo de texto</td><td>Define el enlace de la imagen que se muestra en el banner.</td></tr><tr><td><strong><code>URL Redirección</code></strong></td><td>Campo de texto</td><td>Establece la página a la que se dirige al usuario al interactuar con el banner.</td></tr><tr><td><strong><code>Contenido</code></strong></td><td>Campo de texto</td><td>Indica el texto del banner.</td></tr><tr><td><strong><code>Texto del Botón</code></strong></td><td>Campo de texto</td><td>Determina la etiqueta del botón de acción.</td></tr><tr><td><strong><code>Usuarios ID</code></strong></td><td>Campo numérico</td><td>Especifica los identificadores de los usuarios que reciben el banner.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país de los usuarios destinatarios.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Calendario</td><td>Programa el momento en que se envía el banner.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Fija el momento en que el banner deja de mostrarse.</td></tr></tbody></table>
{% endtab %}

{% tab title="Pop-up" %}
Envía [pop-ups](https://virtualsoft.gitbook.io/untitled/glosario/#pop-up), ventanas emergentes que se muestran en la plataforma. Un pop-up puede asociarse a un juego específico o presentar el contenido de otra página.

#### Visualización

<figure><img src="../../.gitbook/assets/image (295) (1).png" alt=""><figcaption><p>Figura #3: Captura de pantalla pestaña pop-up.</p></figcaption></figure>

#### Acciones disponibles

<table><thead><tr><th width="176">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Definen los criterios de búsqueda para consultar los pop-ups enviados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><strong>Consultar</strong></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los pop-ups en la tabla de resultados.</td></tr><tr><td><strong>Enviar Pop-up</strong></td><td>Abre el formulario para enviar un nuevo pop-up.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

#### Filtros

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Campo numérico</td><td>Localiza un pop-up por su identificador único.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Campo numérico</td><td>Busca el pop-up por su código global.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Consulta los pop-ups enviados al usuario indicado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Acota los resultados a los usuarios del país seleccionado.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Calendario</td><td>Delimita los pop-ups según el momento en que se enviaron.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Restringe los resultados según el momento en que el pop-up deja de mostrarse.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Lista desplegable</td><td>Separa los pop-ups según si el usuario los visualizó <em>(Sí o No)</em>.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Muestra los pop-ups según su estado.</td></tr></tbody></table>

#### Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los pop-ups que cumplen con los filtros aplicados.

<table><thead><tr><th width="176">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Muestra el identificador único del pop-up.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Presenta el código global del pop-up.</td></tr><tr><td><strong><code>Título</code></strong></td><td>Corresponde al encabezado del pop-up.</td></tr><tr><td><strong><code>Contenido</code></strong></td><td>Contiene el mensaje que se muestra dentro del pop-up.</td></tr><tr><td><strong><code>¿Es un juego?</code></strong></td><td>Indica si el pop-up está asociado a un juego específico <em>(Sí o No)</em>.</td></tr><tr><td><strong><code>URL Redirección</code></strong></td><td>Señala la página a la que se dirige al usuario desde el pop-up.</td></tr><tr><td><strong><code>URL Frame</code></strong></td><td>Registra la página cuyo contenido se muestra embebido <em>(incrustado)</em> dentro del pop-up.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Identifica el juego asociado al pop-up, cuando <strong><code>¿Es un juego?</code></strong> es <strong>Sí</strong>.</td></tr><tr><td><strong><code>Usuarios ID</code></strong></td><td>Lista los identificadores de los usuarios que reciben el pop-up.</td></tr><tr><td><strong><code>País</code></strong></td><td>Refleja el país de los usuarios destinatarios.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Marca el momento en que se envió o activó el pop-up.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Determina el momento en que el pop-up deja de mostrarse.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Describe la situación del pop-up <em>(Activo, Inactivo o Expirado)</em>.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Confirma si el usuario visualizó el pop-up <em>(Sí o No)</em>.</td></tr></tbody></table>

#### Enviar Pop-up

Al presionar **Enviar Pop-up**, se despliega el formulario para crear el pop-up y definir sus destinatarios.

{% hint style="warning" %}
**Nota:** Los campos que muestra el formulario son obligatorios.
{% endhint %}

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Título</code></strong></td><td>Campo de texto</td><td>Define el encabezado del pop-up.</td></tr><tr><td><strong><code>Contenido</code></strong></td><td>Campo de texto</td><td>Indica el mensaje que se muestra dentro del pop-up.</td></tr><tr><td><strong><code>¿Es un juego?</code></strong></td><td>Selector</td><td><p>Determina si el pop-up se muestra dentro de un juego específico.</p><ul><li><strong>Sí:</strong> habilita el campo <strong><code>Juego</code></strong>.</li><li><strong>No:</strong> el pop-up usa los campos <strong><code>URL Redirección</code></strong> y <strong><code>URL Frame</code></strong>.</li></ul></td></tr><tr><td><strong><code>Juego</code></strong></td><td>Lista desplegable</td><td><p>Selecciona el juego en el que aparece el pop-up.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Se habilita solo cuando <strong><code>¿Es un juego?</code></strong> es <strong>Sí</strong>.</p></div></td></tr><tr><td><strong><code>URL Redirección</code></strong></td><td>Campo de texto</td><td><p>Establece la página a la que se dirige al usuario desde el pop-up.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Aplica cuando <strong><code>¿Es un juego?</code></strong> es <strong>No</strong>.</p></div></td></tr><tr><td><strong><code>URL Frame</code></strong></td><td>Campo de texto</td><td><p>Especifica la página cuyo contenido se muestra embebido <em>(incrustado)</em> dentro del pop-up.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Aplica cuando <strong><code>¿Es un juego?</code></strong> es <strong>No</strong>.</p></div></td></tr><tr><td><strong><code>Usuarios ID</code></strong></td><td>Campo numérico</td><td>Precisa los identificadores de los usuarios que reciben el pop-up.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Asigna el país de los usuarios destinatarios.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Calendario</td><td>Programa el momento en que se envía el pop-up.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Fija el momento en que el pop-up deja de mostrarse.</td></tr></tbody></table>
{% endtab %}

{% tab title="Franja superior" %}
Envía franjas superiores: barras de texto que se muestran en la parte superior de la plataforma y redirigen al usuario a un enlace.

#### Visualización

<figure><img src="../../.gitbook/assets/image (297) (1).png" alt=""><figcaption><p>Figura #4: Captura de pantalla pestaña franja superior.</p></figcaption></figure>

#### Acciones disponibles

<table><thead><tr><th width="176">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Definen los criterios de búsqueda para consultar las franjas enviadas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><strong>Consultar</strong></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las franjas en la tabla de resultados.</td></tr><tr><td><strong>Enviar franja</strong></td><td>Abre el formulario para enviar una nueva franja superior.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

#### Filtros

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Campo numérico</td><td>Localiza una franja por su identificador único.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Campo numérico</td><td>Busca la franja por su código global.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Consulta las franjas enviadas al usuario indicado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Acota los resultados a los usuarios del país seleccionado.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Calendario</td><td>Delimita las franjas según el momento en que se enviaron.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Restringe los resultados según el momento en que la franja deja de mostrarse.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Lista desplegable</td><td>Separa las franjas según si el usuario las visualizó <em>(Sí o No)</em>.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Muestra las franjas según su estado.</td></tr></tbody></table>

#### Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las franjas que cumplen con los filtros aplicados.

<table><thead><tr><th width="176">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Muestra el identificador único de la franja.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Presenta el código global de la franja.</td></tr><tr><td><strong><code>Contenido</code></strong></td><td>Contiene el texto que se muestra en la franja.</td></tr><tr><td><strong><code>Usuarios ID</code></strong></td><td>Lista los identificadores de los usuarios que reciben la franja.</td></tr><tr><td><strong><code>URL Redirección</code></strong></td><td>Indica la página a la que se dirige al usuario al presionar la franja.</td></tr><tr><td><strong><code>País</code></strong></td><td>Identifica el país de los usuarios destinatarios.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Registra el momento en que se envió la franja.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Marca el momento en que la franja deja de mostrarse.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Refleja el estado actual de la franja.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Confirma si el usuario visualizó la franja <em>(Sí o No)</em>.</td></tr></tbody></table>

#### Enviar franja

Al presionar **Enviar franja**, se despliega el formulario para crear la franja superior y definir sus destinatarios.

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Contenido</code></strong></td><td>Campo de texto</td><td>Define el texto informativo de la franja.</td></tr><tr><td><strong><code>Usuarios ID</code></strong></td><td>Campo numérico</td><td>Especifica los identificadores de los usuarios que reciben la franja.</td></tr><tr><td><strong><code>URL Redirección</code></strong></td><td>Campo de texto</td><td>Establece la página a la que se dirige al usuario al presionar la franja.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país de los usuarios destinatarios.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Calendario</td><td>Programa el momento en que se envía la franja.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Fija el momento en que la franja deja de mostrarse.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 3. Validaciones y reglas del negocio:

* Cada comunicación deja de mostrarse al usuario al cumplirse su **`Fecha de Expiración`**.
* En el formulario de **Pop-up**, el campo **`¿Es un juego?`** en **Sí** habilita el campo **`Juego`**. En **No**, el pop-up usa los campos **`URL Redirección`** y **`URL Frame`**.
* En el formulario de **Pop-up**, los campos que se muestran son obligatorios.
* El campo **`Leído`** permite verificar si el usuario ya visualizó la comunicación.
* **Exportar** descarga únicamente los resultados mostrados tras aplicar los filtros de la pestaña activa.

***

### 4. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>23/01/2026</td><td>David Velasquez</td><td>Actualización de formato.</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
