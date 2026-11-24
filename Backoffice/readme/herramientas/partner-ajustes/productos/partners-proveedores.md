# Partners Proveedores

<mark style="color:$info;">Asocia proveedores a un partner y consulta las asociaciones existentes, con su estado, verificación y límites de operación.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Herramientas > Partner Ajustes > Productos > Partners Proveedores

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (343).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección partners proveedores.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="partners-proveedores.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los proveedores asociados a los partners.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="partners-proveedores.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los proveedores en la tabla de resultados.</td></tr><tr><td><a href="partners-proveedores.md#id-6.-anadir-proveedor-partner"><strong>Añadir Proveedor Partner</strong></a></td><td>Abre el formulario para asociar un proveedor al partner.</td></tr><tr><td><strong>Editar</strong> <i class="fa-pencil">:pencil:</i></td><td>Modifica los datos de una asociación desde la tabla de resultados.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>Campo numérico</td><td>Localiza la asociación por su identificador único.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona el proveedor que se va a consultar.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Muestra las asociaciones según su estado <em>(Activo o Inactivo)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los proveedores asociados que cumplen con los filtros aplicados.

<table><thead><tr><th width="200">Campo</th><th width="120">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><i class="fa-pencil">:pencil:</i></td><td>Acción</td><td>Abre el formulario de la asociación para modificar sus datos. El sistema solicita una justificación del cambio.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Muestra el identificador único de la asociación.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Texto</td><td>Presenta el nombre del proveedor asociado al partner.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Texto</td><td>Identifica el partner de la asociación.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Indica si la asociación está activa o inactiva.</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Texto</td><td>Señala si el proveedor fue validado en el sistema.</td></tr><tr><td><strong><code>Filtro País</code></strong></td><td>Texto</td><td>Indica si el filtro país está activo para el proveedor.</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Numérico</td><td>Muestra el monto máximo permitido para operar con el proveedor.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Numérico</td><td>Muestra el monto mínimo permitido para operar con el proveedor.</td></tr><tr><td><strong><code>Detalle</code></strong></td><td>Texto</td><td>Contiene información adicional del proveedor.</td></tr></tbody></table>

***

### 6. Añadir Proveedor Partner

Al presionar **Añadir Proveedor Partner**, se despliega una ventana emergente para registrar la asociación. El mismo formulario se abre al editar una asociación existente.

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Selecciona el proveedor que se asocia al partner.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Define si la asociación queda activa o inactiva.</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Indica si el proveedor queda registrado como validado.</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Establece el monto máximo permitido para operar con el proveedor.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Establece el monto mínimo permitido para operar con el proveedor.</td></tr><tr><td><strong><code>Detalles</code></strong></td><td>Registra información adicional sobre el proveedor.</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* La asociación se registra al confirmar el formulario con los campos requeridos completos.
* Al editar una asociación, el sistema solicita una justificación del cambio.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>11/02/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
