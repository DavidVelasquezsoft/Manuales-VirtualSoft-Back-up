---
description: >-
  Permite visualizar, organizar, agregar y remover los juegos en las categorías
  disponibles del partner y país previamente seleccionado. Los cambios se
  reflejan en tiempo real en la plataforma online.
---

# Orden y gestión de juegos

### 1. Acceso al Módulo

**Ruta de Acceso**: Site Builder > Partner > Productos > Orden y gestión de juegos

***

### 2. 🖼️ Visualización

***

### 3. ⏮️ Configuraciones previas

Para modificar y acceder a la configuración visual hay 3 ambientes disponibles en los cuales antes de realizar alguna acción,  es necesario contar con las siguientes configuraciones:

<table><thead><tr><th width="207.55560302734375">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País para el cual se realizará la configuración</td></tr></tbody></table>

### 4. 🧑‍💻 Acciones del Usuario

<table><thead><tr><th width="170.85174560546875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="orden-y-gestion-de-juegos.md#id-4.1.-filtros"><strong>Filtrar</strong></a></td><td>Permite filtrar juegos <strong>por categoría</strong> (<em>o todas</em>) y aplicar filtros avanzados para búsquedas más específicas.</td></tr><tr><td><strong>Gestionar juegos</strong></td><td>Permite gestionar uno o varios juegos aplicando diferentes acciones según la categoría filtrada (<em>categoría específica o todas las categorías</em>).</td></tr><tr><td><strong>Organizar juegos</strong></td><td>Permite cambiar el orden de visualización de los juegos <strong>mediante arrastrar y soltar</strong>, utilizando el botón ( <img src="../../../.gitbook/assets/Vector (1).png" alt=""> ) ubicado en la esquina superior derecha de cada carta de juego.</td></tr><tr><td><strong>Vaciar categoría</strong> </td><td>Permite quitar todos los juegos de la categoría seleccionada sin eliminarlos del sistema mediante el botón <img src="../../../.gitbook/assets/Button (5).png" alt="" data-size="line">.</td></tr><tr><td><strong>Organización masiva por CSV</strong></td><td>Permite <strong>agregar o reorganizar juegos de forma masiva dentro de una categoría</strong> mediante un archivo CSV utilizando el botón <img src="../../../.gitbook/assets/Button (3).png" alt="" data-size="line">.</td></tr><tr><td><strong>Guardar cambios</strong></td><td>Aplica los cambios realizados en la organización o categorización de los juegos.</td></tr></tbody></table>

#### 4.1. 🔎 Filtros

Permite aplicar filtros detallados para encontrar juegos según criterios específicos.

<table><thead><tr><th width="125.29620361328125">Filtro</th><th width="126">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categoría</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar todas las categorías o una categoría específica para filtrar, visualizar y gestionar los juegos según su categoría.</td></tr><tr><td><strong><code>Filtros avanzados</code></strong></td><td>Botón</td><td>Permite filtrar para obtener resultados mas detallados con los siguientes campos:</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}


<table><thead><tr><th width="128.51849365234375">Campo</th><th width="121.14813232421875">Tipo </th><th width="197.185302734375">Descripción</th></tr></thead><tbody><tr><td><strong><code>Limpiar</code></strong></td><td>Botón</td><td>Reestablece valores de los filtros.</td></tr><tr><td><strong><code>Nombre de juego</code></strong></td><td>Texto</td><td>Permite buscar juegos por su nombre.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Filtra los juegos por proveedor.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Lista desplegable</td><td>Filtra los juegos por subproveedor.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

#### 4.2. Gestionar juegos

Permite gestionar uno o varios juegos aplicando diferentes acciones según la **vista seleccionada en el filtro de categoría**.

A continuación se describen las funcionalidades disponibles para administrar los juegos dentro del lobby. Cada acción indica **en qué vista puede realizarse**:

* **Vista general (**_**Todas las categorías**_**):** permite gestionar juegos de todas las categorías y asignarlos a una o varias categorías.
* **Vista de categoría:** permite administrar los juegos dentro de una categoría específica, como agregar juegos, cambiar su orden o quitarlos de la categoría.

<table><thead><tr><th width="137.8887939453125">Acción</th><th width="112.1480712890625">Vista disponible</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Cambiar orden de juegos</strong></td><td>General / Categoría</td><td>Abre modal que permite reorganizar la posición de uno o varios juegos ya sea dentro de una categoría o generalmente mediante los siguientes campos:</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}


<table><thead><tr><th width="117.629638671875">Campo</th><th width="102.74078369140625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Posición</code></strong></td><td>Numérico</td><td>Permite indicar la posición desde la cual se iniciará el reordenamiento de los juegos seleccionados. Los juegos se ubicarán consecutivamente a partir de la posición indicada. Solo acepta valores entre <strong>1 y 999</strong>.</td></tr><tr><td><strong><code>Comentario</code></strong></td><td>Texto</td><td>Permite registrar el motivo o justificación del reordenamiento de los juegos. Este comentario queda asociado al cambio realizado para fines de control y auditoría.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="137.88897705078125">Acción</th><th width="112.148193359375">Vista disponible</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Eliminar juego de la categoría</strong></td><td>Categoría</td><td>Al <strong>seleccionar</strong> uno o varios juegos, permite <strong>quitarlos</strong> de la categoría seleccionada <strong>sin eliminarlos</strong> del sistema, por lo que seguirán disponibles en <strong>"Vista general(</strong><em><strong>Todas las categorías</strong></em><strong>)”</strong>. Posteriormente, se deberá confirmar la acción.</td></tr><tr><td><strong>Agregar categorías a juegos</strong></td><td>General</td><td>Abre modal que permite asignar una o varias categorías a los juegos seleccionados en la <strong>Vista general(</strong><em><strong>Todas las categorías</strong></em><strong>)</strong>, para agregar esos juegos a las categorías. se mostraran los siguientes componentes:</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}


<table><thead><tr><th width="125.77777099609375">Componente</th><th width="102.66668701171875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista de selección</td><td>Muestra las categorías disponibles a las que se pueden agregar los juegos seleccionados. Permite seleccionar una o varias categorías.</td></tr><tr><td><strong><code>Seleccionar todas</code></strong></td><td>Selección</td><td>Permite seleccionar todas las categorías disponibles de forma rápida.</td></tr><tr><td><strong><code>Agregar juegos</code></strong></td><td>Botón</td><td>Confirma la acción y agrega los juegos seleccionados a las categorías elegidas.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Botón</td><td>Cierra el modal sin aplicar cambios.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="137.88897705078125">Acción</th><th width="112.148193359375">Vista disponible</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Agregar juegos</strong></td><td>Categoría</td><td>Permite agregar uno o varios juegos a la categoría previamente seleccionada, mediante un modal con los siguientes elementos:</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}


<table><thead><tr><th width="122.0740966796875">Componente</th><th width="107.629638671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Buscador de juegos</code></strong></td><td>Texto</td><td>Permite buscar juegos mediante <strong>nombre</strong>, su <strong>ID</strong> o la <strong>categoría a la que pertenece</strong>.</td></tr><tr><td><strong><code>Seleccionar todos los disponibles</code></strong></td><td>Selección</td><td>Permite seleccionar automáticamente todos los juegos que coinciden con la búsqueda actual.</td></tr><tr><td><strong><code>Juegos</code></strong></td><td>Lista de selección</td><td>Muestra los juegos disponibles que se pueden agregar a la categoría seleccionada. Permite visualizar su información principal y seleccionar uno o varios juegos para agregarlos.</td></tr><tr><td><strong><code>Contador de selección</code></strong></td><td>Indicador</td><td>Muestra la cantidad de juegos seleccionados que serán agregados a la categoría.</td></tr><tr><td><strong><code>Agregar juegos</code></strong></td><td>Botón</td><td>Confirma la acción y agrega los juegos seleccionados a la categoría.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Botón</td><td>Cierra el modal sin realizar cambios.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

#### 4.3. Subir CSV

Permite **agregar o reorganizar juegos dentro de una categoría de forma masiva** mediante la carga de un archivo **CSV** con los siguientes parametros:

<table><thead><tr><th width="201.88873291015625">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID del juego</code></strong></td><td>Identificador único del juego que se desea agregar o reorganizar dentro de la categoría.</td></tr><tr><td><strong><code>Posición</code></strong></td><td>Número que define la posición en la que se ubicará el juego dentro de la categoría.</td></tr></tbody></table>

Al cargar el archivo, el sistema procesa cada registro aplicando las siguientes reglas:

* Si el **juego ya existe en la categoría**, el sistema **actualiza su posición** según la indicada en el archivo.
* Si el **juego no pertenece a la categoría**, el sistema **lo agrega automáticamente en la posición indicada**.
* Si el **ID del juego no existe o el juego se encuentra inactivo**, el sistema **registra el error y continúa procesando los demás registros**.

***

### ✅ 5. Validaciones y Reglas de Negocio

* No se permite guardar los cambios sin una observación.
* El cambio se aplica de forma inmediata y se empieza a visualizar en tiempo real en la plataforma online.
* Todos los cambios realizados son solo visuales hasta presionar el botón **“Guardar cambios”**. Una vez guardados, se reflejarán en la plataforma.

***

### 🕒 6. Control de Versiones

| Versión | Fecha      | Autor                 | Cambios Realizados                          |
| ------- | ---------- | --------------------- | ------------------------------------------- |
| 1.0     | 8/07/2025  | David Velasquez ortiz | Documento inicial                           |
| 2.0     | 12/03/2026 | David velasquez ortiz | Reestructuración y actualización de módulo. |
