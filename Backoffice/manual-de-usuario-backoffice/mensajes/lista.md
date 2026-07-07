---
description: >-
  Permite configurar los diferentes mensajes que aparecerán en la plataforma de
  usuarios online.
---

# Lista

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Mensajes > Lista

***

### 2. Secciones disponibles

Cada una de estas opciones permite

{% tabs %}
{% tab title="Mensajes" %}
Permite administrar el envío de **mensajes directos** a los usuarios dentro de la plataforma.

#### 🖼️ Visualización

<figure><img src="../../.gitbook/assets/image (339).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección mensajes.</p></figcaption></figure>

#### 🧑‍💻 Acciones disponibles

<table><thead><tr><th width="163.22222900390625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="lista.md#filtros"><strong>Filtros</strong></a></td><td>Permiten buscar mensajes enviados a los usuarios según distintos criterios.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="lista.md#consultar"><strong>Consultar</strong></a></td><td>Muestra los mensajes que cumplen con los filtros aplicados.</td></tr><tr><td><a href="lista.md#anadir-mensaje"><strong>Añadir mensaje</strong></a></td><td>Permite crear y enviar un nuevo mensaje a un usuario.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

#### 🔎 Filtros

<table><thead><tr><th width="187.5555419921875">Campo</th><th width="130">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único del mensaje.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Texto</td><td>Código único asignado al mensaje a nivel global.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificación del usuario destinatario.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista</td><td>País del usuario que recibe el mensaje.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Fecha</td><td>Fecha y hora en que se envió el mensaje.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Fecha</td><td>Fecha límite en la que el mensaje dejará de estar disponible.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Lista desplegable</td><td>Indica si el mensaje ha sido visualizado (Sí / No).</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Estado actual del mensaje (Activo / Inactivo).</td></tr></tbody></table>

#### 🚀 Consultar

Al consultar, se despliega una tabla en la parte inferior con la siguiente información:

<table><thead><tr><th width="193.4444580078125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del mensaje.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Código único del mensaje en el sistema.</td></tr><tr><td><strong><code>Emisor</code></strong></td><td>Usuario o sistema que generó el mensaje.</td></tr><tr><td><strong><code>Receptor</code></strong></td><td>Usuario destinatario del mensaje.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Fecha en la que el mensaje deja de ser visible.</td></tr><tr><td><strong><code>Asunto</code></strong></td><td>Título del mensaje.</td></tr><tr><td><strong><code>Mensaje</code></strong></td><td>Contenido del mensaje enviado.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Indica si el mensaje fue visualizado por el usuario.</td></tr></tbody></table>

#### ➕ Añadir mensaje

Permite crear un nuevo mensaje directo hacia un usuario en especifico en la plataforma

<table><thead><tr><th width="152.5555419921875">Campo</th><th width="129.111083984375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificación del usuario destinatario.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Fecha hasta la que el mensaje será visible.</td></tr><tr><td><strong><code>Asunto</code></strong></td><td>Texto</td><td>Título del mensaje.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País del usuario destinatario.</td></tr><tr><td><strong><code>Mensaje</code></strong></td><td>Descripción</td><td>Contenido del mensaje a enviar.</td></tr></tbody></table>
{% endtab %}

{% tab title="Banner masivo" %}
Permite gestionar los banners emergentes que aparecen en la plataforma para comunicar información relevante.

#### 🖼️ Visualización

<figure><img src="../../.gitbook/assets/image (313).png" alt=""><figcaption><p>Figura#2: Captura de pantalla sección Banner invasivo.</p></figcaption></figure>

#### 🧑‍💻 Acciones disponibles

<table><thead><tr><th width="181.88885498046875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="lista.md#filtros-1"><strong>Filtros</strong></a></td><td>Permiten buscar banners enviados a los usuarios.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados.</td></tr><tr><td><a href="lista.md#consultar-resultados"><strong>Consultar</strong></a></td><td>Muestra los banners que cumplen con los criterios definidos.</td></tr><tr><td><a href="lista.md#enviar-banner-invasivo"><strong>Enviar banner invasivo</strong></a></td><td>Permite crear y enviar un nuevo banner emergente.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

#### 🔎 Filtros

<table><thead><tr><th width="193.7777099609375">Campo</th><th width="135.5555419921875">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único del banner.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Texto</td><td>Código único del banner.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Usuario destinatario del banner.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País del usuario.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Fecha / Hora</td><td>Fecha en la que se envió el banner.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Fecha / Hora</td><td>Fecha en la que dejará de mostrarse.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Sí / No</td><td>Indica si el banner fue visualizado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Activo / Inactivo</td><td>Estado del banner.</td></tr></tbody></table>

#### 🚀 Consultar

<table><thead><tr><th width="213.88897705078125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador del banner.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Código único del banner.</td></tr><tr><td><strong><code>URL Imagen</code></strong></td><td>Enlace de la imagen del banner.</td></tr><tr><td><strong><code>URL Redirección</code></strong></td><td>Enlace al que redirige el banner.</td></tr><tr><td><strong><code>Contenido</code></strong></td><td>Texto del banner.</td></tr><tr><td><strong><code>Texto del Botón</code></strong></td><td>Texto del botón de acción.</td></tr><tr><td><strong><code>Usuarios ID</code></strong></td><td>Identificadores únicos de los usuarios destinatarios.</td></tr><tr><td><strong><code>País</code></strong></td><td>País de los destinatarios.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Fecha de envío del banner.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Fecha de expiración.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado del banner.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Indica si fue visualizado.</td></tr></tbody></table>

#### ➕ Enviar banner invasivo

Permite crear un banner emergente para enviarlo a unos usuarios en especifico

<table><thead><tr><th width="201.77783203125">Campo</th><th width="140.99993896484375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>URL Imagen</code></strong></td><td>URL</td><td>Enlace de la imagen del banner.</td></tr><tr><td><strong><code>URL Redirección</code></strong></td><td>URL</td><td>Enlace de destino.</td></tr><tr><td><strong><code>Contenido</code></strong></td><td>Texto</td><td>Texto del banner.</td></tr><tr><td><strong><code>Texto del Botón</code></strong></td><td>Texto</td><td>Texto del botón de acción.</td></tr><tr><td><strong><code>Usuarios ID</code></strong></td><td>Numérico</td><td>Usuarios que recibirán el banner.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País de los destinatarios.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Calendario</td><td>Fecha y hora de envío.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Fecha límite de visualización.</td></tr></tbody></table>
{% endtab %}

{% tab title="Pop-up" %}
Permite configurar mensajes emergentes tipo [pop-up](https://virtualsoft.gitbook.io/untitled/glosario/#pop-up) dentro de la plataforma.

#### 🖼️ Visualización

<figure><img src="../../.gitbook/assets/image (315).png" alt=""><figcaption><p>Figura#3: Captura de pantalla sección pop up.</p></figcaption></figure>

#### 🧑‍💻 Acciones disponibles

<table><thead><tr><th width="154.33331298828125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="lista.md#filtros-2"><strong>Filtros</strong></a></td><td>Permiten buscar pop-ups previamente creados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados por defecto.</td></tr><tr><td><a href="lista.md#consultar-2"><strong>Consultar</strong></a></td><td>Muestra los pop-ups existentes.</td></tr><tr><td><a href="lista.md#consultar-2"><strong>Enviar Pop-up</strong></a></td><td>Permite crear un nuevo pop-up para mostrar un mensaje en especifico.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

#### 🔎 Filtros

<table><thead><tr><th width="195.22222900390625">Campo</th><th width="141.66668701171875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador del pop-up.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Numérico</td><td>Código único del pop-up.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador único del usuario destinatario.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país del usuario.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Calendario</td><td>Fecha de envío.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Fecha de expiración.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Lista desplegable</td><td>Indica si fue visto el pop-up o no.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra por el estado del pop-up.</td></tr></tbody></table>

#### 🚀 Consultar

<table><thead><tr><th width="208.5555419921875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del pop-up generado por el sistema.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Código global que identifica de forma única el pop-up dentro de la plataforma.</td></tr><tr><td><strong><code>Título</code></strong></td><td>Nombre o encabezado principal del pop-up mostrado al usuario.</td></tr><tr><td><strong><code>Contenido</code></strong></td><td>Mensaje o información que contiene el pop-up.</td></tr><tr><td><strong><code>¿Es un juego?</code></strong></td><td>Indica si el pop-up está asociado a un juego específico.</td></tr><tr><td><strong><code>URL Redirección</code></strong></td><td>Enlace al que será dirigido el usuario al interactuar con el pop-up.</td></tr><tr><td><strong><code>URL Frame</code></strong></td><td>URL utilizada para mostrar contenido embebido dentro del pop-up.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Identificador del juego asociado al pop-up, cuando aplica.</td></tr><tr><td><strong><code>Usuarios ID</code></strong></td><td>Identificador de los usuarios a quienes fue enviado el pop-up.</td></tr><tr><td><strong><code>País</code></strong></td><td>País de los usuarios destinatarios del pop-up.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Fecha y hora en la que el pop-up fue enviado o activado.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Fecha en la que el pop-up deja o dejó de mostrarse a los usuarios.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del pop-up dentro de la plataforma (por ejemplo: Activo, Inactivo, Expirado).</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Indica si el usuario visualizó el pop-up.</td></tr></tbody></table>

#### ➕ Enviar Pop-up

Permite crear un nuevo pop-up indicando los siguientes campo obligatorios.

<table><thead><tr><th width="177.44439697265625">Campo</th><th width="131.33331298828125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Título</code></strong></td><td>Texto</td><td>Nombre del pop-up.</td></tr><tr><td><strong><code>Contenido</code></strong></td><td>Descripción</td><td>Mensaje mostrado dentro del pop-up.</td></tr><tr><td><strong><code>¿Es un juego?</code></strong></td><td>Selección</td><td><p>Indica si el pop-up está asociado a un juego.<br>En caso e que si sea ara un juego se habilitará el siguiente campo:</p><ul><li><strong><code>Juego</code></strong>:  Permite seleccionar el juego en especifico en el cual aparecerá el pop-up</li></ul></td></tr><tr><td><strong><code>URL Redirección</code></strong></td><td>URL</td><td>En caso de que no sea para un juego indica el enlace de redirección.</td></tr><tr><td><strong><code>URL Frame</code></strong></td><td>URL</td><td>En caso de que no sea para un juego indica el enlace para mostrar el contenido embebido del pop-up.</td></tr><tr><td><strong><code>Usuarios ID</code></strong></td><td>Numéricos</td><td>Identificadores únicos de los usuarios destinatarios.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País de visualización.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Calendario</td><td>Indica la fecha de envío.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Indica la fecha de expiración.</td></tr></tbody></table>
{% endtab %}

{% tab title="Franja superior" %}
Sección dedicada a la administración de los mensajes que se muestran en la parte superior de la plataforma.&#x20;

#### 🖼️ Visualización

<figure><img src="../../.gitbook/assets/image (317).png" alt=""><figcaption><p>Figura#4: Captura de pantalla sección franja superior.</p></figcaption></figure>

#### 🧑‍💻 Acciones disponibles

<table><thead><tr><th width="175.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="lista.md#filtros-3"><strong>Filtrar</strong></a></td><td>Permite buscar franjas enviadas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados por defecto.</td></tr><tr><td><a href="lista.md#consultar-3"><strong>Consultar</strong></a></td><td>Muestra las franjas configuradas.</td></tr><tr><td><a href="lista.md#anadir-franja-superior"><strong>Enviar franja</strong></a></td><td>Permite crear una nueva franja superior.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

#### 🔎 Filtros

<table><thead><tr><th width="209.77777099609375">Campo</th><th width="147.99993896484375">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador de la franja.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Texto</td><td>Código único de la franja.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Usuario destinatario.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País de visualización.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Fecha</td><td>Fecha de envío.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Fecha</td><td>Fecha límite.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Lista desplegable</td><td>Indica si fue visualizada.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra por el estado de la franja.</td></tr></tbody></table>

#### 🚀 Consultar

<table><thead><tr><th width="255.66668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único de la franja.</td></tr><tr><td><strong><code>Global ID</code></strong></td><td>Código único global de la franja.</td></tr><tr><td><strong><code>Contenido</code></strong></td><td>Texto mostrado.</td></tr><tr><td><strong><code>Usuarios ID</code></strong></td><td>Identificadores únicos de los usuarios destinatarios.</td></tr><tr><td><strong><code>URL Redirección</code></strong></td><td>Enlace de destino.</td></tr><tr><td><strong><code>País</code></strong></td><td>País de visualización.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Fecha de envío.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Fecha de finalización.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Indica si fue visualizada.</td></tr></tbody></table>

#### ➕ Añadir franja superior

Permite añadir una nueva franja superior indicando los siguientes campos:

<table><thead><tr><th width="203.11114501953125">Campo</th><th width="139.5555419921875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Contenido</code></strong></td><td>Texto</td><td>Texto informativo de la franja.</td></tr><tr><td><strong><code>Usuarios ID</code></strong></td><td>Numéricos</td><td>Indica los identificadores únicos de los usuarios destinatarios.</td></tr><tr><td><strong><code>URL Redirección</code></strong></td><td>URL</td><td>Enlace de destino  al hacer click en la franja superior.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país de visualización.</td></tr><tr><td><strong><code>Fecha de Envío</code></strong></td><td>Calendario</td><td>Fecha y hora de envío.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Fecha de finalización.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 3.  Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="141.88885498046875">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>23/01/2026</td><td>David Velásquez</td><td>Actualización de formato.</td></tr></tbody></table>



</details>
