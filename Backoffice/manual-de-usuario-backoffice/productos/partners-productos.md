---
description: >-
  Permite consultar mediante filtros la información de uno o varios productos
  asociados a partners, además de añadir nuevos.
---

# Partners Productos

### 1. Acceso al Módulo

**Ruta de Acceso**: Backoffice > Productos > Partner productos.

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (560).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección partners productos.</p></figcaption></figure>

***

### 3.  Acciones disponibles

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="partners-productos.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="partners-productos.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los proveedores y subproveedores válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="132.90374755859375">Campo</th><th width="104.74078369140625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>Numérico</td><td>Identificador único del registro del producto.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Dropdown</td><td>Selecciona nombre del <a href="https://virtualsoft.gitbook.io/untitled/glosario#partner">Partner</a> vinculado al producto.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Dropdown</td><td>Selecciona nombre de la empresa o entidad proveedora del producto.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Dropdown</td><td>Nombre del distribuidor o proveedor secundario asociado al producto.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Dropdown</td><td>Indica el producto en especifico</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Ingresa el nombre del producto.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Dropdown</td><td>Estado actual del producto: (Activo/Inactivo/Todos).</td></tr></tbody></table>

#### 🔍 3.1. Filtros avanzados

<table><thead><tr><th width="140.51849365234375">Campo</th><th width="120.92572021484375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Verificado</code></strong></td><td>Lista desplegable</td><td>Filtra según el producto asignado al partner (Ej: Casino, Apuestas).</td></tr><tr><td><strong><code>Filtro País</code></strong></td><td>Lista desplegable</td><td>País o región asociada al producto.</td></tr><tr><td><strong><code>Orden Destacado</code></strong></td><td>Numérico</td><td>Prioridad de visualización del producto en la lista destacada.</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Numérico</td><td>Valor máximo permitido por ese producto.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Numérico</td><td>Valor mínimo permitido por ese producto.</td></tr><tr><td><strong><code>Tiempo de Procesamiento</code></strong></td><td>Numérico</td><td>Filtra según el tiempo de procesamiento configurado.</td></tr><tr><td><strong><code>Dispositivo</code></strong></td><td>Botón de opción</td><td>Tipo de dispositivo compatible con el producto (móvil, escritorio, ambos).</td></tr></tbody></table>

***

### 5. Resultado de Consulta

Aplica los filtros seleccionados y muestra los registros válidos.

<table><thead><tr><th width="136.60736083984375">Campo</th><th width="119.370361328125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único del producto del partner.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Texto</td><td>Nombre del producto asociado al partner.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Texto</td><td>Nombre del proveedor del producto.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Texto</td><td>Nombre del partner registrado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Estado actual del producto del partner (Activo/Inactivo).</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Texto</td><td>Indica si el producto ha sido verificado por el sistema.</td></tr><tr><td><strong><code>Filtro País</code></strong></td><td>Texto</td><td>País asociado al producto del partner.</td></tr><tr><td><strong><code>Mobile</code></strong></td><td>Texto</td><td>Indica si el producto es compatible con dispositivos móviles.</td></tr><tr><td><strong><code>Escritorio</code></strong></td><td>Texto</td><td>Indica si el producto es compatible con computadoras de escritorio.</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Numérico</td><td>Límite máximo permitido por el producto.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Numérico</td><td>Límite mínimo permitido por el producto.</td></tr><tr><td><strong><code>Tiempo de Procesamiento</code></strong></td><td>Texto</td><td>Tiempo estimado para el procesamiento de solicitudes relacionadas con el producto.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Numérico</td><td>Orden de visualización del producto.</td></tr><tr><td><strong><code>Orden Destacado</code></strong></td><td>Texto</td><td>Indica si el producto tiene una posición destacada en el orden de visualización.</td></tr><tr><td><strong><code>Filas</code></strong></td><td>Numérico</td><td>Número de filas utilizadas para la visualización del producto.</td></tr><tr><td><strong><code>Columnas</code></strong></td><td>Numérico</td><td>Número de columnas utilizadas para la visualización del producto.</td></tr><tr><td><strong><code>¿Es nuevo?</code></strong></td><td>Texto</td><td>Indica si el producto es reciente o ha sido actualizado recientemente.</td></tr></tbody></table>

***

### 6. Añadir producto partner

Permite agregar un producto partner

<table><thead><tr><th width="137.17031860351562">Campo</th><th width="119.40740966796875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Productos</code></strong></td><td>Lista desplegable</td><td>Nombre o referencia comercial de los productos registrados.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Nombre del <a href="https://virtualsoft.gitbook.io/untitled/glosario#partner">Partner</a> vinculado a los productos.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Estado actual del producto (Activo/Inactivo).</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Lista desplegable</td><td>Indica el estado de la verificación del producto.</td></tr><tr><td><strong><code>Filtro País</code></strong></td><td>Lista desplegable</td><td>Indica el estado del filtro pais en el producto.</td></tr><tr><td><strong><code>Tiempo Procesamiento</code></strong></td><td>Numérico</td><td>Tiempo de procesamiento configurado.</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Numérico</td><td>Valor máximo permitido para operaciones asociadas al producto.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Numérico</td><td>Valor mínimo permitido para operaciones asociadas al producto.</td></tr><tr><td><strong><code>¿Es nuevo?</code></strong></td><td>Lista desplegable</td><td>Indica si el producto es reciente o ha sido actualizado recientemente.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Numérico</td><td>Posición asignada para mostrar el producto en la lista.</td></tr><tr><td><strong><code>Orden Destacado</code></strong></td><td>Texto</td><td>Indica el orden de prioridad que tiene el producto.</td></tr><tr><td><strong><code>Filas</code></strong></td><td>Numérico</td><td>Número de filas utilizadas para mostrar el producto en pantalla.</td></tr><tr><td><strong><code>Columnas</code></strong></td><td>Numérico</td><td>Número de columnas utilizadas para mostrar el producto en pantalla.</td></tr></tbody></table>

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de Versiones</summary>

<table><thead><tr><th width="99.4000244140625">Versión</th><th width="147.79998779296875">Fecha</th><th data-type="users" data-multiple>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/08/2025</td><td><a href="https://app.gitbook.com/u/QNLawjQjAmOHwajEjd48cer1Xpq2">david.velasquez</a></td><td>Documento inicial</td></tr></tbody></table>

</details>
