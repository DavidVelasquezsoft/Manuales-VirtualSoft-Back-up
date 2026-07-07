---
description: >-
  Podrás consultar, mediante filtros, la información de uno o varios productos
  asociados a partners y específicos de un país.
---

# Partners Productos País

### 1. Acceso al Módulo <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de Acceso**: BackOffice > Productos > Partners productos país

### 2. Visualización. <a href="#id-2.-visualizacion" id="id-2.-visualizacion"></a>

<figure><img src="../../.gitbook/assets/image (559).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección partners productos país.</p></figcaption></figure>

***

### 3.  Acciones disponibles

<table><thead><tr><th width="120.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Permiten filtrar la información para obtener resultados mas precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><strong>Consultar</strong></td><td>Aplica los filtros seleccionados y muestra los proveedores y subproveedores válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

### 4. ¿Cómo buscar un Tipo de Producto Partner?

<table><thead><tr><th width="150">Campo</th><th width="140">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>Campo de texto</td><td>Permite buscar por identificador único del producto del partner en un país.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Selección del producto asociado al partner.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Selección del partner registrado en el sistema.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra productos según su estado (Activo/Inactivo).</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Lista desplegable</td><td>Permite filtrar si el producto está verificado en el sistema.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selección del país asociado al producto del partner.</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Campo numérico</td><td>Valor máximo permitido por el producto en ese país.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Campo numérico</td><td>Valor mínimo permitido por el producto en ese país.</td></tr><tr><td><strong><code>Tiempo Procesamiento</code></strong></td><td>Campo de texto/número</td><td>Tiempo estimado para la ejecución de solicitudes del producto en ese país.</td></tr></tbody></table>

***

### 5. Resultados de la Consulta

Al ejecutar el botón **Consultar**, se despliega una tabla con los siguientes campos:

<table><thead><tr><th width="195">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>Identificador único del producto del partner para un país.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Nombre del producto asociado al partner.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner registrado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del producto del partner (Activo/Inactivo).</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Indica si el producto ha sido verificado por el sistema.</td></tr><tr><td><strong><code>Filtro País</code></strong></td><td>País asociado al producto del partner.</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Límite máximo permitido por el producto en ese país.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Límite mínimo permitido por el producto en ese país.</td></tr><tr><td><strong><code>Tiempo de Procesamiento</code></strong></td><td>Tiempo estimado para el procesamiento de solicitudes relacionadas.</td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* El **Id** es único y obligatorio en el sistema.
* El **Producto**, **Partner** y **País** deben existir previamente.
* El **Tiempo de Procesamiento** no puede ser negativo.

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de Versiones</summary>

<table><thead><tr><th width="101">Versión</th><th width="134">Fecha</th><th width="143">Autor</th><th>Descripción del cambio</th></tr></thead><tbody><tr><td>1.0</td><td>2025-08-28</td><td>Karol Navia</td><td>Creación del documento</td></tr></tbody></table>

</details>
