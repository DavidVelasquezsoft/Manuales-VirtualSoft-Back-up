---
description: >-
  Esta sección permite visualizar y organizar los productos asociados a cada
  franquicia, facilitando su asignación y el mantenimiento de una estructura
  ordenada dentro del sistema.
---

# Productos Franquicia

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, no será visible en el sistema.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Herramientas > Partner Ajustes > Productos > Productos Franquicia

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (503).png" alt=""><figcaption><p>Figura#1: Captura de pantalla seccion productos a franquicia.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="productos-franquicia.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información de los productos por franquicia.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="productos-franquicia.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los productos en la tabla de resultados.</td></tr><tr><td><a href="productos-franquicia.md#id-6.-anadir-producto-a-franquicia"><strong>Añadir Producto a Franquicia</strong></a></td><td>Permite asignar un producto a una franquicia mediante una ventana emergente.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="136.666748046875">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Productos</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre del producto a consultar.</td></tr><tr><td><strong><code>Franquicia</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre de la <a href="https://virtualsoft.gitbook.io/plantillas/glosario#franquicia">franquicia</a> relacionada.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país sobre el cual se consultará la información.</td></tr></tbody></table>

Adicionalmente, el módulo cuenta con un apartado de **Filtros avanzados** que, al desplegarse, habilita el siguiente criterio:

<table><thead><tr><th width="135.3333740234375">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra los productos según su estado <em>(Todos, Activo o Inactivo)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los productos que cumplen con los filtros aplicados.

<table><thead><tr><th width="197.6666259765625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Editar (</strong><i class="fa-pencil">:pencil:</i><strong>)</strong></td><td>Permite modificar la información del producto asociado a la <a href="https://virtualsoft.gitbook.io/plantillas/glosario#franquicia">franquicia </a>en el registro seleccionado.</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
Al seleccionar la acción **Editar** sobre un registro, se habilita una ventana que permite modificar la información del producto asociado a la [franquicia](https://virtualsoft.gitbook.io/plantillas/glosario#franquicia). Los campos son:

<table><thead><tr><th width="116.666748046875">Campo</th><th width="118">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>No editable</td><td>Identificador único de la asociación. Se muestra solo como referencia.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>No editable</td><td>Nombre del producto o pasarela de pago asociado. Se muestra solo como referencia.</td></tr><tr><td><strong><code>Franquicia</code></strong></td><td>No editable</td><td>Nombre de la <a href="https://virtualsoft.gitbook.io/plantillas/glosario#franquicia">franquicia</a> vinculada. Se muestra solo como referencia.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Campo de texto (URL)</td><td>Permite reemplazar la URL actual por una nueva para cambiar la imagen del producto.</td></tr><tr><td><strong><code>Abreviado</code></strong></td><td>Campo de texto</td><td>Permite actualizar el nombre corto o código que identifica la asociación.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite cambiar el estado del producto a <em>Activo</em> o <em>Inactivo</em>.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Para que las modificaciones queden registradas, es necesario seleccionar el botón **Guardar**.
{% endhint %}
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden data-search="false"><thead><tr><th width="190.7222900390625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>Identificador único del registro.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Nombre del producto registrado.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/plantillas/glosario#franquicia"><strong><code>Franquicia</code></strong></a></td><td>Nombre de la franquicia a la que se encuentra asociado el producto.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Imagen asociada al producto dentro de la franquicia.</td></tr><tr><td><strong><code>Abreviado</code></strong></td><td>Nombre abreviado o siglas con las que se identifica el producto.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del producto <em>(Activo o Inactivo)</em>.</td></tr></tbody></table>

***

### 6. Añadir Producto a [Franquicia](https://virtualsoft.gitbook.io/plantillas/glosario#franquicia)

Permite asignar un producto a una franquicia. Al seleccionar el botón **Añadir Producto a Franquicia**, se abre una ventana emergente con los siguientes campos:

<table><thead><tr><th width="157.3333740234375">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país al que corresponde la asignación.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Lista desplegable</td><td>Selecciona el producto que se desea asignar a la <a href="https://virtualsoft.gitbook.io/plantillas/glosario#franquicia">franquicia</a>.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/plantillas/glosario#franquicia"><strong><code>Franquicia</code></strong></a></td><td>Lista desplegable</td><td>Selecciona la franquicia a la que se asociará el producto.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Archivo</td><td>Permite cargar la imagen asociada al producto dentro de la <a href="https://virtualsoft.gitbook.io/plantillas/glosario#franquicia">franquicia</a>.</td></tr><tr><td><strong><code>Abreviado</code></strong></td><td>Campo de texto</td><td>Nombre abreviado o siglas con las que se identifica el producto.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Indica si el producto estará <em>Activado</em> o <em>Inactivado</em>.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Para finalizar la asignación y mantener organizada la estructura de productos y franquicias, es necesario seleccionar el botón **Guardar**.
{% endhint %}

***

### 7. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, no será visible en el sistema.
* El filtro **Estado** se encuentra dentro del apartado de filtros avanzados.
* La asignación de un producto a una franquicia requiere seleccionar el botón **Guardar** para completarse.
* Las modificaciones realizadas mediante la acción **Editar** requieren seleccionar el botón **Guardar** para aplicarse.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>01/07/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
