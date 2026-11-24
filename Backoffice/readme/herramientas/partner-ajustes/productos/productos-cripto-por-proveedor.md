# Productos Cripto por Proveedor

<mark style="color:$info;">Asocia un producto de un proveedor con una criptomoneda y la red blockchain en la que opera, para cada país. La red blockchain es la red sobre la que se transfiere la criptomoneda.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Herramientas > Partner Ajustes > Productos > Productos Cripto por Proveedor

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (489).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección productos cripto por proveedor.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="productos-cripto-por-proveedor.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar las asociaciones registradas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="productos-cripto-por-proveedor.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las asociaciones en la tabla de resultados.</td></tr><tr><td><a href="productos-cripto-por-proveedor.md#id-6.-asociar-producto"><strong>Asociar Producto</strong></a></td><td>Abre el formulario para vincular un producto con una criptomoneda y su red blockchain.</td></tr><tr><td><strong>Ver detalle</strong> <i class="fa-magnifying-glass">:magnifying-glass:</i></td><td>Muestra la información completa de una asociación.</td></tr><tr><td><strong>Editar</strong> <i class="fa-pencil">:pencil:</i></td><td>Modifica el estado de una asociación.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona el proveedor de las asociaciones.</td></tr><tr><td><strong><code>Criptomoneda</code></strong></td><td>Lista desplegable</td><td>Acota los resultados a la criptomoneda seleccionada.</td></tr><tr><td><strong><code>Red Blockchain</code></strong></td><td>Lista desplegable</td><td>Restringe la búsqueda a la red blockchain seleccionada.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td><p>Delimita la consulta al país seleccionado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo es obligatorio para ejecutar la consulta.</p></div></td></tr></tbody></table>

#### 4.1. Filtros avanzados

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Muestra las asociaciones según su estado <em>(Activa, Inactiva o Todos)</em>. Por defecto está seleccionada la opción <strong>Todos</strong>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las asociaciones que cumplen con los filtros aplicados.

<table><thead><tr><th width="200">Campo</th><th width="120">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td>Acción</td><td><p>Reúne las acciones disponibles para cada asociación:</p><ul><li><i class="fa-magnifying-glass">:magnifying-glass:</i> <strong>Ver detalle:</strong> muestra la información completa de la asociación.</li><li><i class="fa-pencil">:pencil:</i> <strong>Editar:</strong> modifica únicamente el estado de la asociación <em>(Activa o Inactiva)</em>.</li></ul></td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Muestra el identificador único de la asociación.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Texto</td><td>Presenta el nombre del proveedor asociado.</td></tr><tr><td><strong><code>Producto Técnico</code></strong></td><td>Texto</td><td>Indica el nombre del producto asociado.</td></tr><tr><td><strong><code>Cripto</code></strong></td><td>Texto</td><td>Identifica la criptomoneda de la asociación.</td></tr><tr><td><strong><code>Red</code></strong></td><td>Texto</td><td>Señala la red blockchain de la asociación.</td></tr><tr><td><strong><code>Código de Red</code></strong></td><td>Texto</td><td>Muestra el código que identifica la red blockchain.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Indica si la asociación está activa o inactiva.</td></tr><tr><td><strong><code>Partner/País</code></strong></td><td>Texto</td><td>Presenta el partner y el país del registro.</td></tr></tbody></table>

***

### 6. Asociar Producto

Al presionar **Asociar Producto**, se despliega una ventana emergente para vincular un producto con una criptomoneda, su red blockchain y un proveedor. Todos los campos son obligatorios.

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Define el país de la asociación.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona el proveedor.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Indica el producto que se asocia.</td></tr><tr><td><strong><code>Criptomoneda + Red blockchain</code></strong></td><td>Lista desplegable</td><td><p>Asigna la combinación de criptomoneda y red blockchain.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La combinación debe estar creada previamente en el módulo <strong>Productos &#x3E; Asociación Cripto + Redes</strong>.</p></div></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Interruptor</td><td>Establece si la asociación queda activa o inactiva.</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* El filtro **`País`** es obligatorio para ejecutar la consulta.
* Todos los campos del formulario **Asociar Producto** son obligatorios.
* Para crear la asociación, la combinación de criptomoneda y red blockchain debe existir previamente en [Asociación Cripto + Redes](../../../productos/asociacion-cripto-+-redes.md).
* Desde la acción **Editar** únicamente se modifica el estado de la asociación.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>08/07/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
