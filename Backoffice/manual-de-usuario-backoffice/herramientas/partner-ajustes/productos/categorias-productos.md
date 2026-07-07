# Categorías Productos

<mark style="color:$info;">Esta sección permite visualizar y organizar las categorías de productos de manera eficiente, facilitando su asignación a productos específicos y el mantenimiento de una estructura ordenada dentro del sistema.</mark>

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, no será visible en el sistema.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Herramientas > Partner Ajustes > Productos > Categorías Productos

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (695).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Categorías productos</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="categorias-productos.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información de las categorías.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="categorias-productos.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las categorías en la tabla de resultados.</td></tr><tr><td><a href="categorias-productos.md#id-6.-anadir-categoria-producto"><strong>Añadir Categoría Producto</strong></a></td><td>Permite asignar una categoría a un producto mediante una ventana emergente.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Indica el identificador único de la categoría.</td></tr><tr><td><strong><code>Categorías</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre de la categoría a consultar.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre del producto relacionado.</td></tr></tbody></table>

Adicionalmente, el módulo cuenta con un apartado de **Filtros avanzados** que, al desplegarse, habilita el siguiente criterio:

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra las categorías según su estado <em>(Todos, Activo o Inactivo)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las categorías que cumplen con los filtros aplicados.

<table><thead><tr><th width="197.6666259765625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Editar (</strong><i class="fa-pencil">:pencil:</i><strong>)</strong></td><td>Permite modificar la información de la categoría asociada al producto en el registro seleccionado.</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
Al seleccionar la acción **Editar** sobre un registro, se habilita una ventana que permite modificar la información de la categoría asociada al producto. Los campos editables son:

<table><thead><tr><th width="118.666748046875">Campo</th><th width="118">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>Numérico</td><td>Identificador único de la categoría.</td></tr><tr><td><strong><code>Categoría</code></strong></td><td>Lista desplegable</td><td>Categoría asignada al producto.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Producto al que se encuentra asociada la categoría.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Estado de la categoría <em>(Activo o Inactivo)</em>.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Numérico</td><td>Posición de la categoría dentro del listado de visualización.</td></tr><tr><td><strong><code>Explicación</code></strong></td><td>Campo de texto</td><td>Descripción o justificación del cambio que desea realizar.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Para que las modificaciones queden registradas, es necesario seleccionar el botón **Guardar**.
{% endhint %}
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden data-search="false"><thead><tr><th width="190.7222900390625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único de la categoría.</td></tr><tr><td><strong><code>Categoría</code></strong></td><td>Nombre de la categoría registrada.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Lista de productos asociados a la categoría.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual de la categoría <em>(Activo o Inactivo)</em>.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Posición de la categoría dentro del listado de visualización.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner relacionado con la categoría.</td></tr></tbody></table>

***

### 6. Añadir Categoría Producto

Permite asignar una categoría a un producto. Al seleccionar el botón **Añadir Categoría Producto**, se abre una ventana emergente con los siguientes campos:

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categoría</code></strong></td><td>Lista desplegable</td><td>Selecciona la categoría que se desea asignar al producto.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Selecciona el producto al que se asociará la categoría.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Indica si la categoría estará <em>Activada</em> o <em>Inactivada</em>.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Numérico</td><td>Define el orden en el que la categoría se mostrará dentro del listado.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Para finalizar la asignación y mantener organizada la estructura de productos y categorías, es necesario seleccionar el botón **Guardar**.
{% endhint %}

***

### 7. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, no será visible en el sistema.
* El filtro **Estado** se encuentra dentro del apartado de filtros avanzados.
* La asignación de una categoría a un producto requiere seleccionar el botón **Guardar** para completarse.
* Las modificaciones realizadas mediante la acción **Editar** requieren seleccionar el botón **Guardar** para aplicarse.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>01/07/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
