---
description: Permite visualizar y crear mensajes guiados a usuarios en la plataforma.
---

# Crear mensaje

### 1. Acceso al Módulo

**Ruta de Acceso**: Backoffice > Mensajes > Crear mensaje

***

### 2. 🖼️ Visualización

<figure><img src="../../.gitbook/assets/image (635).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección mensajes</p></figcaption></figure>

***

### &#x33;**.** 🧑‍💻 **Acciones disponibles**

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="crear-mensaje.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><strong>Añadir mensaje</strong></td><td>Permite crear un nuevo mensaje para un usuario en la plataforma.</td></tr><tr><td><a href="crear-mensaje.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

#### 3.1. 🔎 Filtros

<table><thead><tr><th width="144.00006103515625">Campo</th><th width="165">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mensaje ID</code></strong></td><td>Texto / Numérico</td><td>Permite filtrar los registros ingresando el identificador único del mensaje.</td></tr><tr><td><strong><code>Título</code></strong></td><td>Texto</td><td>Permite buscar mensajes según el título asociado.</td></tr><tr><td><strong><code>¿Leído?</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los mensajes según su estado de lectura.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los mensajes según el tipo de mensaje configurado en la plataforma (<em>pop-up o mensaje</em>).</td></tr><tr><td><strong><code>Emisor</code></strong></td><td>Texto</td><td>Permite filtrar los mensajes según el usuario que envió el mensaje.</td></tr><tr><td><strong><code>Receptor</code></strong></td><td>Texto</td><td>Permite filtrar los mensajes según el usuario destinatario.</td></tr><tr><td><strong><code>Tipo de red</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los mensajes según el tipo de red por la cual fue enviado.</td></tr></tbody></table>

#### 3.2. 🚀 Consultar

Aplica los filtros seleccionados y presenta los resultados de los mensajes validos.

<table><thead><tr><th width="177">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del mensaje generado por el sistema.</td></tr><tr><td><strong><code>Emisor</code></strong></td><td>Usuario, sistema o entidad que envió el mensaje.</td></tr><tr><td><strong><code>Receptor</code></strong></td><td>Usuario destinatario del mensaje.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha y hora en la que el mensaje fue creado en la plataforma.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Fecha y hora hasta la cual el mensaje permanece disponible o vigente.</td></tr><tr><td><strong><code>Asunto</code></strong></td><td>Título o asunto principal del mensaje.</td></tr><tr><td><strong><code>Leído</code></strong></td><td>Indica si el mensaje ha sido leído por el receptor.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Indica el tipo de mensaje que se mando (<em>Mensaje o pop-up</em>)</td></tr><tr><td><strong><code>Tipo de red</code></strong></td><td>Red utilizada para el envío del mensaje (<em>Ej: Punto de venta, concesionario o subconcesionario</em>).</td></tr></tbody></table>

#### 3.3. ➕ Añadir mensaje

Permite crear un nuevo mensaje destinado para un usuario en especifico dentro de la plataforma.

<table><thead><tr><th width="202.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Indica el identificador único del usuario al que se enviará el mensaje.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Define la fecha y hora en la que el mensaje dejará de estar vigente.</td></tr><tr><td><strong><code>Asunto</code></strong></td><td>Texto</td><td>Especifica el título o asunto principal del mensaje.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país de los usuarios a los que se dirigirá el mensaje.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Define  la forma en la que el mensaje se le va a  mostrar al usuario.</td></tr><tr><td><strong><code>Tipo de red</code></strong></td><td>Lista desplegable</td><td>Selecciona el canal o red a través de la cual se enviará el mensaje.</td></tr><tr><td><strong><code>Mensaje</code></strong></td><td>Texto</td><td>Indica el mensaje que se le va amostrar al usuario.</td></tr></tbody></table>

* Para crear el mensaje correctamente debes darle al botón **guardar**.

***

### 4. 🕓 Control de Versiones

<table><thead><tr><th width="141.88885498046875">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>29/01/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>
