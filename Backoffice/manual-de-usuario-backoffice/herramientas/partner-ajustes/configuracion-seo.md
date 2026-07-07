# Configuración SEO

<mark style="color:$info;">Esta sección permite configurar el SEO de cada URL y sección del sitio de usuarios online para el partner y el país seleccionados. Desde aquí se definen los textos y parámetros que optimizan el posicionamiento de cada página en los motores de búsqueda, así como algunos contenidos que se muestran al usuario dentro de la plataforma.</mark>

{% hint style="warning" %}
**Nota:** Los cambios se aplican sobre el partner seleccionado previamente al ingresar a Partner ajustes y sobre el país e idioma definidos en los filtros. Verifica estas selecciones antes de realizar cualquier configuración.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Partner ajustes > Configuración SEO

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (693).png" alt=""><figcaption><p>Figura #1: Captura de pantalla seección Condiguración SEO</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="121.50830078125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="configuracion-seo.md#id-6.-anadir-seo"><strong>Añadir SEO</strong></a></td><td>Abre una ventana emergente para registrar la configuración SEO de una nueva URL o sección del sitio.</td></tr><tr><td><a href="configuracion-seo.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen el país y el idioma sobre los cuales se consultará y configurará el SEO.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="configuracion-seo.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las configuraciones SEO existentes.</td></tr><tr><td><strong>Guardar</strong></td><td><p>Guarda y aplica de forma general todos los cambios realizados en la configuración SEO.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Las modificaciones permanecerán únicamente en edición hasta que se presione el botón <strong>Guardar</strong>.</p></div></td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="116.51861572265625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país sobre el cual se configurará el SEO.</td></tr><tr><td><strong><code>Idioma</code></strong></td><td>Lista desplegable</td><td>Selecciona el idioma de la configuración SEO <em>(por ejemplo: español (ES))</em>.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** La configuración SEO se aplica de forma independiente por cada combinación de país e idioma, por lo que los cambios afectan únicamente a la selección realizada en estos filtros.
{% endhint %}

***

### 5. Resultados de consulta

Al ejecutar la consulta, se despliega la configuración SEO existente para la URL, el país y el idioma seleccionados. Cada configuración corresponde a una URL del sitio e incluye los siguientes campos editables:

<table><thead><tr><th width="190.7222900390625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Página (URL)</code></strong></td><td>URL o sección del sitio a la que corresponde la configuración SEO <em>(por ejemplo: https://doradobet.com/home)</em>.</td></tr><tr><td><strong><code>HEAD_TITLE</code></strong></td><td>Título de la página que se muestra como encabezado en la pestaña del navegador al ingresar a la URL dentro de la plataforma de usuarios online.</td></tr><tr><td><strong><code>HEAD_DESCRIPTION</code></strong></td><td>Descripción de la página utilizada por los motores de búsqueda para mostrar el resumen del contenido en los resultados.</td></tr><tr><td><strong><code>HEAD_KEYWORDS</code></strong></td><td>Palabras clave asociadas a la página, empleadas como referencia para el posicionamiento en buscadores.</td></tr><tr><td><strong><code>H1</code></strong></td><td>Encabezado principal de la página <em>(jerarquía de mayor relevancia)</em>.</td></tr><tr><td><strong><code>H2</code></strong></td><td>Encabezado secundario de la página.</td></tr><tr><td><strong><code>H3</code></strong></td><td>Encabezado de tercer nivel de la página.</td></tr><tr><td><strong><code>P</code></strong></td><td>Texto de párrafo que se muestra dentro de la plataforma de usuarios online como un desplegable ubicado encima del pie de página <em>(footer)</em> de la URL configurada.</td></tr><tr><td><strong><code>CANONICAL</code></strong></td><td>URL canónica que indica a los motores de búsqueda cuál es la versión principal de la página, evitando contenido duplicado.</td></tr><tr><td><strong><code>SCHEMA</code></strong></td><td>Datos estructurados de la página que ayudan a los motores de búsqueda a interpretar su contenido.</td></tr><tr><td><strong><code>QUESTIONS</code></strong></td><td>Permite configurar las preguntas frecuentes asociadas a la página, agregando una o varias preguntas y respuestas dentro de una misma configuración SEO. Al seleccionar el botón <strong>Añadir</strong>, se abrirá una ventana emergente con el siguiente campo:</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="98.7408447265625">Campo</th><th width="91.629638671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Pregunta</code></strong></td><td>Campo de texto</td><td>Permite ingresar el texto de la pregunta que se desea agregar.</td></tr></tbody></table>

Una vez guardada, la pregunta se muestra dentro del campo **QUESTIONS**. Al seleccionarla, se habilitan dos campos para completar su contenido:

<table><thead><tr><th width="102.44451904296875">Campo</th><th width="145.70367431640625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>QUESTION</code></strong></td><td>Campo de texto</td><td>Texto de la pregunta.</td></tr><tr><td><strong><code>RESPONSE</code></strong></td><td>Campo de texto</td><td>Texto de la respuesta correspondiente a la pregunta.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

### 6. Añadir SEO

Permite registrar la configuración SEO de una nueva URL o sección del sitio. Al seleccionar el botón **Añadir SEO**, se abre una ventana emergente con el siguiente campo:

<table><thead><tr><th width="99.4815673828125">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Página</code></strong></td><td>Campo de texto</td><td>Permite ingresar la URL de la página o sección del sitio que se desea configurar <em>(por ejemplo: https://doradobet.com/deportes)</em>.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Para registrar la nueva URL, es necesario seleccionar el botón **Guardar** dentro de la ventana emergente.
{% endhint %}

Una vez registrada, la URL queda creada pero aún sin contenido SEO. Para que la configuración tenga efecto, es necesario diligenciar todos sus campos. Puedes consultar cómo completar cada uno de estos campos en la sección  [#id-5.-resultados-de-consulta](configuracion-seo.md#id-5.-resultados-de-consulta "mention").

{% hint style="warning" %}
**Nota:** El proceso completo consta de dos pasos: primero **crear** la URL desde **Añadir SEO**, y luego **configurar** sus campos. Los cambios solo quedarán registrados al seleccionar el botón **Guardar** del módulo.
{% endhint %}

***

### 7. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, no será visible en el sistema.
* Los cambios se aplican sobre el partner seleccionado previamente al ingresar a Partner ajustes.
* La configuración SEO se realiza de forma independiente por cada combinación de país e idioma seleccionada en los filtros.
* Para aplicar todos los cambios realizados es obligatorio seleccionar el botón **Guardar** del módulo.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>23/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
