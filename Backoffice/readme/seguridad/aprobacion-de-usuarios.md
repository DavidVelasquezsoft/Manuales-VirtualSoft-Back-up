# Aprobación de Usuarios

<mark style="color:$info;">Consulta la información de un usuario a partir de su ID y gestiona la aprobación de su registro mediante el interruptor Estado de Registro del Usuario. La información se presenta en secciones de solo lectura con los datos personales, de contacto, de identificación y las imágenes del documento de identidad.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Seguridad > Aprobación de usuarios

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FNJOkE7UhvWDfoR1zirkK%2Fimage.png?alt=media&#x26;token=dffb47c6-14df-48b8-9b93-1949ec972217" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Aprobación de usuarios.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="210">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="aprobacion-de-usuarios.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen el criterio de búsqueda para consultar el usuario.</td></tr><tr><td><a href="aprobacion-de-usuarios.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según el <strong><code>ID Usuario</code></strong> ingresado y carga la información del usuario en las secciones del módulo.</td></tr><tr><td><strong>Activar o inactivar registro</strong></td><td>Cambia el estado de registro del usuario mediante el interruptor <strong><code>Estado de Registro del Usuario</code></strong>, ubicado en la sección <strong>Resumen</strong>.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="170">Campo</th><th width="140">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Localiza al usuario a partir de su identificador único.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, el sistema completa la sección **Resumen** con el estado del usuario y su estado de registro, y carga su información en las secciones de detalle.

<table><thead><tr><th width="210">Campo</th><th width="110">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Muestra el estado actual de la cuenta del usuario en la plataforma.</td></tr><tr><td><strong><code>Estado de Registro del Usuario</code></strong></td><td>Acción</td><td><p>Activa o inactiva el registro del usuario mediante un interruptor:</p><ul><li><strong>Activo:</strong> el registro del usuario está aprobado.</li><li><strong>Inactivo:</strong> el registro del usuario no está aprobado.</li></ul><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Nota:</strong> <strong><code>Estado</code></strong> muestra la condición general de la cuenta, mientras que <strong><code>Estado de Registro del Usuario</code></strong> indica si el registro está aprobado.</p></div><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Antes de ejecutar la consulta, el interruptor se muestra en <strong>Inactivo</strong>. El estado real del registro se visualiza después de consultar el usuario.</p></div></td></tr></tbody></table>

#### 5.1. Detalles del usuario

La información del usuario se agrupa en secciones desplegables de solo lectura. Cada sección se contrae o se expande con la flecha ubicada a la derecha de su título.

<table><thead><tr><th width="140">Sección</th><th width="240">Campos</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Demografía</strong></td><td><ul><li><strong><code>Primer nombre</code></strong></li><li><strong><code>Segundo Nombre</code></strong></li><li><strong><code>Apellido</code></strong></li><li><strong><code>Segundo Apellido</code></strong></li><li><strong><code>Género</code></strong></li><li><strong><code>Cumpleaños</code></strong></li></ul></td><td><p>Contiene los datos personales básicos que identifican al usuario.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Nota:</strong> El campo <strong><code>Cumpleaños</code></strong> corresponde a la fecha de nacimiento del usuario.</p></div></td></tr><tr><td><strong>Contacto</strong></td><td><ul><li><strong><code>Celular</code></strong></li><li><strong><code>Email</code></strong></li><li><strong><code>País Residencia</code></strong></li><li><strong><code>Provincia/Región Residencia</code></strong></li><li><strong><code>Ciudad Residencia</code></strong></li><li><strong><code>Dirección</code></strong></li></ul></td><td>Reúne los medios de contacto y el lugar de residencia del usuario.</td></tr><tr><td><strong>Identificación</strong></td><td><ul><li><strong><code>Tipo de Documento</code></strong></li><li><strong><code>Numero de Documento</code></strong></li></ul></td><td>Muestra el tipo y el número del documento de identidad registrado por el usuario.</td></tr><tr><td><strong>Verificación</strong></td><td><ul><li><strong><code>DNI Anterior</code></strong></li><li><strong><code>DNI Posterior</code></strong></li></ul></td><td><p>Presenta las imágenes de la cara frontal y la cara posterior del documento de identidad cargadas por el usuario, que permiten validar visualmente su identidad.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Cuando el usuario no ha cargado una imagen, el espacio correspondiente muestra el mensaje <strong>No tiene DNI Anterior</strong> o <strong>No tiene DNI Posterior</strong>.</p></div></td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El interruptor **Estado de Registro del Usuario** es el único elemento editable del módulo. Los demás campos son de solo lectura.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>30/12/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>03/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
