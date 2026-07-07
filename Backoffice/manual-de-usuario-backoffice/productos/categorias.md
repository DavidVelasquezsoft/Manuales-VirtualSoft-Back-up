---
description: >-
  En esta sección se podrán consultar, mediante filtros, la información de una o
  varias categorías, además se pueden añadir nuevas categorías.
---

# Categorías

### 1. Acceso al Módulo <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de Acceso**: Backoffice > Productos > Categorías.

***

### 2. Visualización <a href="#id-2.-visualizacion" id="id-2.-visualizacion"></a>

<figure><img src="../../.gitbook/assets/image (426).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección categorías.</p></figcaption></figure>

### 3.  Acciones disponibles

<table><thead><tr><th width="120.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Permiten filtrar la información para obtener resultados mas precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><strong>Consultar</strong></td><td>Aplica los filtros seleccionados y muestra los proveedores y subproveedores válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. ¿Cómo buscar una categoría? <a href="#id-3.1-como-buscar-un-tipo-de-producto-partner" id="id-3.1-como-buscar-un-tipo-de-producto-partner"></a>

#### 📌 Filtros disponibles

En esta sección se puede consultar información de categorías aplicando los siguientes filtros:

<table><thead><tr><th width="124">Campo</th><th width="184">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Campo de texto</td><td>Identificador único de la categoría.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Permite buscar por descripción de la categoría.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Selección del tipo de categoría.</td></tr></tbody></table>

### 5. Resultados de la consulta

Al realizar la búsqueda se muestran los siguientes datos en la tabla de resultados:

<table><thead><tr><th width="210">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único de la categoría.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Descripción detallada de la categoría.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de categoría.</td></tr><tr><td><strong><code>Slug</code></strong></td><td>Texto corto asociado a la categoría.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual de la categoría (Activo/Inactivo).</td></tr><tr><td><strong><code>Superior</code></strong></td><td>Categoría superior en caso de jerarquía.</td></tr></tbody></table>

***

### 6. Añadir Categoría

Para registrar una nueva categoría, ubica y haz clic en el botón **"Añadir Categoría"**.\
A continuación, completa los campos requeridos en el formulario.

<table><thead><tr><th width="152">Campo</th><th width="185">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Nombre o detalle de la categoría.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Campo de texto</td><td>Tipo de categoría a la que pertenece.</td></tr><tr><td><strong><code>Slug</code></strong></td><td>Campo de texto</td><td>Texto corto único que identifica la categoría.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Define si la categoría está Activa o Inactiva.</td></tr></tbody></table>

**Acciones disponibles:**

* **Guardar**: Almacena la categoría creada.
* **Cancelar**: Cierra la ventana sin guardar cambios.

***

### 7. Validaciones y Reglas de Negocio

* El campo **Slug** debe ser único, no admite duplicados.
* El campo **Estado** debe seleccionarse obligatoriamente (Activo/Inactivo).

***

### 8. Control de Versiones

<details>

<summary>🔽Historial de versiones </summary>

<table><thead><tr><th width="109">Versión</th><th width="142">Fecha</th><th width="188">Autor</th><th>Descripción del cambio</th></tr></thead><tbody><tr><td>1.0</td><td>2025-08-28</td><td>Karol Navia</td><td>Creación del documento.</td></tr></tbody></table>

</details>
