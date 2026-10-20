# Documentos registrados

<mark style="color:$info;">Centraliza la gestión de documentos internos, como contratos, formularios, manuales, configuraciones y términos y condiciones, permitiendo cargarlos, clasificarlos, definir permisos de acceso y establecer si requieren aceptación del usuario.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Documentos registrados

{% hint style="warning" %}
**Nota:** El acceso a este módulo y a cada una de sus acciones se controla mediante permisos independientes.
{% endhint %}

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (726).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Documentos registrados.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="194">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="documentos-registrados.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los documentos registrados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="documentos-registrados.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los documentos en la tabla de resultados.</td></tr><tr><td><a href="documentos-registrados.md#id-6.-anadir-documento"><strong>Añadir documento</strong></a></td><td>Despliega el formulario para registrar un nuevo documento y definir los perfiles que podrán acceder a él.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="152">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Localiza un documento específico por su nombre.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Acota la búsqueda a una categoría de documento <em>(Formularios, Contratos, Manuales, Configuraciones o Términos y Condiciones)</em>.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente los documentos activos o los inactivos.</td></tr><tr><td><strong><code>Ordenar por</code></strong></td><td>Lista desplegable</td><td>Define el criterio con el que se organizan los resultados <em>(fecha de carga o nombre del documento)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los documentos que cumplen con los filtros aplicados.

<table><thead><tr><th width="147.111083984375">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td>Acción</td><td>Reúne las operaciones disponibles sobre cada documento registrado.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="129.7777099609375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Visualizar</strong> <i class="fa-file-lines">:file-lines:</i></td><td>Abre el documento para consultarlo sin descargarlo.</td></tr><tr><td><strong>Descargar</strong> <i class="fa-down-long-to-line">:down-long-to-line:</i></td><td>Descarga el archivo asociado al documento.</td></tr><tr><td><strong>Editar</strong> <i class="fa-pencil">:pencil:</i></td><td><p>Permite modificar el <strong>nombre</strong>, el <strong>estado</strong> y el <strong>archivo</strong> del documento.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El campo <strong><code>Tipo de acceso</code></strong> no puede modificarse después de crear el documento.</p></div></td></tr><tr><td><strong>Ver detalles</strong> <i class="fa-magnifying-glass">:magnifying-glass:</i></td><td>Despliega el historial de versiones del documento y permite cargar una nueva versión.</td></tr></tbody></table>

<details>

<summary>🔽 Ver detalles: historial de versiones</summary>

Cada vez que se reemplaza el archivo de un documento, la plataforma conserva la versión anterior y registra la nueva. Desde esta vista se consulta ese historial:

<table><thead><tr><th width="168">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acción</code></strong></td><td>Permite visualizar el documento correspondiente a esa versión.</td></tr><tr><td><strong><code>Versión</code></strong></td><td>Número de versión del documento.</td></tr><tr><td><strong><code>URL documento</code></strong></td><td>Ubicación en la que se encuentra almacenado el archivo de esa versión.</td></tr><tr><td><strong><code>Encriptación</code></strong></td><td>Método de encriptación aplicado a esa versión.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha en la que se cargó la versión.</td></tr></tbody></table>

Mediante el botón **Añadir nueva versión** se despliega una ventana emergente en la que se indica la **encriptación** y se carga el nuevo **archivo**.

</details>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="144.44439697265625">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único del documento dentro de la plataforma.</td></tr><tr><td><strong><code>Nombre del documento</code></strong></td><td>Texto</td><td>Nombre con el que se registró el documento.</td></tr><tr><td><strong><code>Ruta</code></strong></td><td>Texto</td><td>URL en la que se encuentra almacenado el archivo.</td></tr><tr><td><strong><code>Encriptación</code></strong></td><td>Texto</td><td>Método de encriptación aplicado al archivo.</td></tr><tr><td><strong><code>Id externo</code></strong></td><td>Texto</td><td>Identificador con el que se referencia el documento fuera de la plataforma <em>(proveedores, clientes, entidades externas, etc.)</em>.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Texto</td><td>Categoría a la que pertenece el documento.</td></tr><tr><td><strong><code>Fecha de carga</code></strong></td><td>Fecha</td><td>Fecha en la que se registró el documento en la plataforma.</td></tr><tr><td><strong><code>Cantidad de perfiles autorizados</code></strong></td><td>Numérico</td><td>Número de perfiles que tienen acceso al documento. Permite identificar de un vistazo qué tan amplia es su visibilidad.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Disponibilidad actual del documento <em>(Activo o Inactivo)</em>.</td></tr><tr><td><strong><code>País</code></strong></td><td>Texto</td><td>País para el que aplica el documento.</td></tr></tbody></table>

{% hint style="danger" %}
**Importante:** Cuando se reemplaza el archivo de un documento configurado como **Aprobación**, la plataforma lo trata como una **nueva versión** y vuelve a solicitar la aceptación a todos los usuarios de los perfiles autorizados, aunque ya hubieran aceptado la versión anterior. Las aceptaciones previas no se eliminan: quedan conservadas en el historia.
{% endhint %}

***

### 6. Añadir documento

Mediante el botón **Añadir documento** se despliega una ventana emergente con el formulario para registrar un nuevo documento.

{% hint style="warning" %}
**Nota:** Los documentos registrados en este módulo quedan disponibles para los usuarios en la sección [**Documentos**](../documentos.md), donde cada uno visualiza únicamente los documentos activos que estén asignados a su perfil. Los documentos de tipo **Aprobación** se muestran además mediante la ventana emergente de aceptación al ingresar.
{% endhint %}

<table><thead><tr><th width="141.3333740234375">Campo</th><th width="119.111083984375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Nombre con el que se identificará el documento en la plataforma.</td></tr><tr><td><strong><code>Ruta</code></strong></td><td>Campo de texto</td><td>URL en la que se encuentra almacenado el documento.</td></tr><tr><td><strong><code>Versión</code></strong></td><td>Campo de texto</td><td>Número de versión del documento.</td></tr><tr><td><strong><code>Encriptación</code></strong></td><td>Campo de texto</td><td>Método de encriptación aplicado al documento.</td></tr><tr><td><strong><code>Tipo documento</code></strong></td><td>Lista desplegable</td><td><p>Categoría a la que pertenece el documento. Determina cómo se agrupa y se localiza dentro del módulo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El listado es ampliable: pueden habilitarse nuevas categorías sin afectar los documentos ya registrados.</p></div></td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="196">Tipo documento</th><th>Contenido</th></tr></thead><tbody><tr><td><strong>Formularios</strong></td><td>Documentos que el usuario debe diligenciar o utilizar como plantilla en su operación.</td></tr><tr><td><strong>Contratos</strong></td><td>Acuerdos y documentos de carácter contractual suscritos con puntos de venta, concesionarios o terceros.</td></tr><tr><td><strong>Manuales</strong></td><td>Guías operativas y de uso de la plataforma dirigidas a los perfiles autorizados.</td></tr><tr><td><strong>Configuraciones</strong></td><td>Documentos técnicos o de parametrización asociados a la operación.</td></tr><tr><td><strong>Términos y Condiciones</strong></td><td>Documentos de carácter legal que establecen las condiciones de uso de la plataforma.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="140.4444580078125">Campo</th><th width="119.111083984375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Determina si el documento está disponible para los perfiles autorizados <em>(<strong>Activo</strong>)</em> o si deja de estarlo <em>(<strong>Inactivo</strong>)</em>.</td></tr><tr><td><strong><code>Perfil</code></strong></td><td>Lista desplegable múltiple</td><td><p>Define los perfiles que podrán consultar y descargar el documento <em>(Punto de Venta, Concesionario, Administrador de BackOffice, entre otros)</em>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Admite la selección de varios perfiles de forma simultánea. Cada usuario visualiza únicamente los documentos asociados a su perfil, por lo que un documento sin perfiles asignados no es visible para nadie.</p></div></td></tr><tr><td><strong><code>Tipo de acceso</code></strong></td><td>Lista desplegable</td><td><p>Determina cómo se le presenta el documento al usuario: si queda disponible para consultarlo cuando lo necesite o si debe aceptarlo para continuar.</p><div data-gb-custom-block data-tag="hint" data-style="danger" class="hint hint-danger"><p><strong>Importante:</strong> Este campo <strong>no puede modificarse una vez creado el documento</strong>. Si se requiere cambiar el tipo de acceso, debe inactivarse el documento y registrarse uno nuevo.</p></div></td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}


<table><thead><tr><th width="126">Tipo de acceso</th><th>Comportamiento</th></tr></thead><tbody><tr><td><strong>Informativo</strong></td><td>El documento <strong>no se presenta mediante ventana emergente</strong>. Queda disponible en la sección <a href="../documentos.md"><strong>Documentos</strong></a> para que los perfiles autorizados lo consulten y lo descarguen cuando lo necesiten, sin interrumpir el uso de la plataforma ni requerir ninguna aceptación.</td></tr><tr><td><strong>Aprobación</strong></td><td>Al ingresar al BackOffice, el usuario visualiza una ventana emergente con el documento para que lo lea y lo acepte. La ventana <strong>continúa apareciendo en cada ingreso hasta que el usuario lo acepta</strong>. Además, el documento queda disponible en la sección <a href="../documentos.md"><strong>Documentos</strong></a> para su consulta y descarga; la aceptación <strong>no lo oculta</strong> del listado.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="138.6666259765625">Campo</th><th width="118.22222900390625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo método</code></strong></td><td>Lista desplegable</td><td>Establece si el documento aplica para servicios propios o para servicios prestados con proveedores.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País para el que aplica el documento.</td></tr><tr><td><strong><code>Archivo</code></strong></td><td>Carga de archivo</td><td><p>Archivo que se almacena y queda asociado al documento. Formatos admitidos: <strong>PDF, DOC, DOCX, JPG, JPEG</strong> y <strong>PNG</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El peso máximo del archivo corresponde al límite que el BackOffice admite para documentos e imágenes. Si el formato no es válido, la plataforma muestra un mensaje indicando que no está permitido y no registra el documento.</p></div></td></tr></tbody></table>

{% hint style="danger" %}
**Importante:** Si un documento de tipo **Aprobación** debe dejar de solicitarse a los usuarios, la única forma de lograrlo es **inactivarlo**, ya que el tipo de acceso no puede modificarse.
{% endhint %}

***

### 7. Validaciones y reglas del negocio:

* No es obligatorio diligenciar todos los filtros para ejecutar la consulta.
* Los resultados mostrados corresponden únicamente a los criterios seleccionados en los filtros.
* Cada usuario visualiza únicamente los documentos asociados a su perfil. Un documento sin perfiles asignados no queda disponible para ningún usuario.
* Un mismo documento puede asignarse a varios perfiles de forma simultánea.
* El campo **`Tipo de acceso`** se define durante la creación y no puede modificarse posteriormente.
* Para que un documento de tipo **Aprobación** deje de solicitarse a los usuarios, debe inactivarse.
* Los formatos de archivo admitidos son **PDF, DOC, DOCX, JPG, JPEG** y **PNG**. Si el archivo cargado no corresponde a uno de ellos, la plataforma muestra un mensaje indicando que el formato no es válido.
* El peso máximo permitido para el archivo corresponde al límite que el BackOffice admite para documentos e imágenes.
* Al reemplazar el archivo de un documento de tipo **Aprobación**, la plataforma lo registra como una nueva versión y vuelve a solicitar la aceptación a los usuarios autorizados. Las aceptaciones de versiones anteriores se conservan en el historial de auditoría.
* Al inactivarlo, el documento deja de estar disponible de inmediato para los perfiles autorizados, pero su información y su historial de auditoría se conservan.
* Los documentos de tipo **Aprobación** se presentan mediante ventana emergente hasta su aceptación y, adicionalmente, quedan disponibles en la sección **Documentos**. La aceptación no los oculta del listado.
* Un documento se muestra en la sección [**Documentos**](../documentos.md) únicamente si está **activo**, **asignado al perfil** del usuario y este cuenta con el **permiso de consulta**; la descarga requiere además el **permiso de descarga**.
* Al **inactivar** un documento, deja de mostrarse tanto en la ventana emergente como en la sección **Documentos**.

***

### 9. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>09/10/2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>14/10/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33888">Incorporación de la nuevas acciones de usuario y actualización del módulo.</a></td></tr></tbody></table>

</details>
