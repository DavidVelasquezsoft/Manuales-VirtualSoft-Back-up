# Documentos

<mark style="color:$info;">Reúne los documentos que el partner ha publicado para el perfil del usuario, desde esta sección el usuario consulta y descarga la documentación vigente que le corresponde, sin depender del envío manual de archivos por parte de otras áreas.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Documentos

{% hint style="warning" %}
**Nota:** El acceso a esta sección y a sus acciones se controla mediante permisos independientes. Los usuarios que no cuenten con el permiso correspondiente no visualizan la sección ni la acción asociada.
{% endhint %}

***

### 2. Visualización

<figure><img src="../.gitbook/assets/image (727).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección documentos</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="documentos.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los documentos disponibles.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="documentos.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los documentos en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="184">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Localiza un documento específico por el nombre en que se registró.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Lista desplegable</td><td>Filtra por una categoría de documento <em>(Formularios, Contratos, Manuales, Configuraciones o Términos y Condiciones)</em>.</td></tr><tr><td><strong><code>Fecha de publicación</code></strong></td><td>Calendario</td><td>Delimita los resultados según la fecha en la que se publicó el documento.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los documentos que cumplen con los filtros aplicados. El listado incluye únicamente los documentos publicados para el perfil del usuario con el que inicio sesión en el BackOffice.

{% hint style="warning" %}
**Nota:** Los documentos de esta sección se cargan y administran desde el reporte [**Documentos registrados**](reportes/documentos-registrados.md). Allí se define su nombre, su categoría, los perfiles que pueden acceder a ellos y si requieren aceptación del usuario. Esta sección únicamente los presenta para su consulta y descarga.
{% endhint %}

<table><thead><tr><th width="143.111083984375">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td>Acción</td><td>Muestra las acciones disponibles sobre cada documento.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Visualizar</strong> <i class="fa-file-lines">:file-lines:</i></td><td>Abre un pop-up para visualizar el documento, mostrando siempre la última versión vigente.</td></tr><tr><td><strong>Descargar</strong> <i class="fa-down-long-to-line">:down-long-to-line:</i></td><td>Descarga el archivo, conservando su formato original.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="145.77783203125">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del documento</code></strong></td><td>Texto</td><td>Nombre con el que se registró el documento.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Texto</td><td>Categoría a la que pertenece el documento <em>(Formularios, Contratos, Manuales, Configuraciones o Términos y Condiciones)</em>.</td></tr><tr><td><strong><code>Tipo de acceso</code></strong></td><td>Texto</td><td>Indica si el documento requiere o no la aceptación del usuario.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="134">Tipo de acceso</th><th>Comportamiento</th></tr></thead><tbody><tr><td><strong>Informativo</strong></td><td>El documento queda disponible para consultarlo y descargarlo cuando el usuario lo necesite. No requiere ninguna acción de su parte.</td></tr><tr><td><strong>Aprobación</strong></td><td>Además de aparecer en este listado, el documento se muestra en una ventana emergente al ingresar al BackOffice para que el usuario lo lea y lo acepte. La ventana continúa apareciendo en cada ingreso hasta que el usuario lo acepta.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="149.3333740234375">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de publicación</code></strong></td><td>Fecha</td><td>Fecha en la que se creó la primera versión del documento. No cambia cuando se carga una versión posterior.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Aceptar un documento de tipo **Aprobación** no lo retira de este listado. Una vez aceptado deja de mostrarse la ventana emergente, pero el documento permanece disponible para consultarlo y descargarlo cuando el usuario lo necesite.
{% endhint %}

***

### 6. Validaciones y reglas del negocio:

* Cada usuario visualiza únicamente los documentos que han sido publicados para su perfil.
* Un documento aparece en esta sección cuando se cumplen tres condiciones: se encuentra **activo**, está **asignado al perfil** del usuario y el usuario cuenta con el **permiso de consulta**. Para descargarlo se requiere adicionalmente el permiso de descarga.
* Cuando un documento se inactiva desde el módulo de administración, deja de mostrarse de inmediato tanto en este listado como en la ventana emergente de aceptación.
* La acción **Visualizar** presenta únicamente la última versión vigente del documento. Las versiones anteriores no se consultan desde esta sección.
* El documento conserva su formato original tanto al visualizarlo como al descargarlo. Si el formato no admite vista previa en el navegador, debe descargarse para consultarlo.
* La **`Fecha de publicación`** corresponde a la creación de la primera versión del documento y se mantiene aunque posteriormente se cargue una versión nueva.
* Aceptar un documento de tipo **Aprobación** no lo oculta del listado.
* Esta sección es de consulta: desde aquí no es posible crear, editar, reemplazar ni inactivar documentos. Esas acciones se realizan únicamente desde el reporte [**Documentos registrados**](reportes/documentos-registrados.md), que es el módulo donde se administran los documentos de la operación.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>20/10/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33887">Documento inicial</a></td></tr></tbody></table>

</details>
