# Partners Sub Proveedores

<mark style="color:$info;">Consulta los subproveedores asociados a cada partner y configura su estado, límites, imagen y disponibilidad para bonos y usuarios de prueba. Un subproveedor es una línea de producto o una marca de juegos que llega a través de un proveedor principal.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Herramientas > Partner Ajustes > Productos > Partners Sub Proveedores

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (344).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección partners sub proveedores.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="partners-sub-proveedores.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los subproveedores asociados a los partners.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="partners-sub-proveedores.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los subproveedores en la tabla de resultados.</td></tr><tr><td><strong>Añadir Sub Proveedor Partner</strong></td><td>Abre el formulario para asociar un subproveedor al partner.</td></tr><tr><td><a href="partners-sub-proveedores.md#id-6.-editar-subproveedor"><strong>Editar</strong></a> <i class="fa-pencil">:pencil:</i></td><td>Modifica la configuración de un subproveedor desde la tabla de resultados.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>Campo numérico</td><td>Localiza el subproveedor por su identificador único.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Acota los resultados a los subproveedores del proveedor principal seleccionado.</td></tr><tr><td><strong><code>Sub Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona un subproveedor específico.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Muestra los subproveedores según su estado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Delimita la consulta al país seleccionado.</td></tr><tr><td><strong><code>Bonus System</code></strong></td><td>Lista desplegable</td><td>Separa los subproveedores según estén habilitados o no para torneos y bonos.</td></tr></tbody></table>

#### 4.1. Filtros avanzados

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Verificado</code></strong></td><td>Lista desplegable</td><td>Consulta los subproveedores según su estado de validación en el sistema.</td></tr><tr><td><strong><code>Filtro País</code></strong></td><td>Lista desplegable</td><td>Filtra por el estado del filtro país del subproveedor.</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Campo numérico</td><td>Localiza los subproveedores por su monto máximo permitido.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Campo numérico</td><td>Restringe la búsqueda por el monto mínimo permitido.</td></tr><tr><td><strong><code>Tiempo de Procesamiento</code></strong></td><td>Campo numérico</td><td>Indica el tiempo estimado de procesamiento de las operaciones del subproveedor.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los subproveedores que cumplen con los filtros aplicados.

<table><thead><tr><th width="200">Campo</th><th width="120">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><i class="fa-pencil">:pencil:</i></td><td>Acción</td><td>Abre el formulario para editar la configuración del subproveedor.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Muestra el identificador único del subproveedor.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Texto</td><td>Presenta el nombre del proveedor principal.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Texto</td><td>Identifica el partner asociado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Indica si el subproveedor está activo o inactivo.</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Texto</td><td>Señala si el subproveedor fue validado en el sistema.</td></tr><tr><td><strong><code>Filtro País</code></strong></td><td>Texto</td><td>Indica el estado del filtro país del subproveedor.</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Numérico</td><td>Muestra el monto máximo permitido.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Numérico</td><td>Muestra el monto mínimo permitido.</td></tr><tr><td><strong><code>Bonus System</code></strong></td><td>Texto</td><td>Indica si el subproveedor está habilitado para torneos y bonos <em>(S: activo, N: inactivo)</em>.</td></tr><tr><td><strong><code>Test Users</code></strong></td><td>Texto</td><td>Señala si el subproveedor es exclusivo para usuarios de prueba.</td></tr><tr><td><strong><code>Detalle</code></strong></td><td>Texto</td><td>Contiene información adicional del subproveedor.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Texto</td><td>Presenta el logotipo del subproveedor.</td></tr></tbody></table>

***

### 6. Editar subproveedor

El ícono <i class="fa-pencil">:pencil:</i> de la tabla de resultados abre una ventana emergente con la configuración del subproveedor.

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Muestra el identificador único del subproveedor. No es editable.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Presenta el proveedor principal asociado. No es editable.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Activa o inactiva el subproveedor.</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Modifica el estado de verificación.</td></tr><tr><td><strong><code>Filtro País</code></strong></td><td>Ajusta el filtro país del subproveedor.</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Establece el monto máximo permitido.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Establece el monto mínimo permitido.</td></tr><tr><td><strong><code>Detalle</code></strong></td><td>Registra información adicional.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Carga o actualiza el logotipo del subproveedor.</td></tr><tr><td><strong><code>Bonus System</code></strong></td><td>Habilita o deshabilita los juegos del subproveedor en torneos y bonos.</td></tr><tr><td><strong><code>Usuarios de Prueba</code></strong></td><td><p>Define si el subproveedor es exclusivo para usuarios de prueba.</p><ul><li><strong>Marcado:</strong> el subproveedor solo es visible para los usuarios de prueba.</li><li><strong>Sin marcar:</strong> el subproveedor es visible para todos los usuarios de la plataforma.</li></ul></td></tr><tr><td><strong><code>Explicación</code></strong></td><td>Registra la justificación del cambio.</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Aplica los cambios realizados.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Cierra el formulario sin modificar la información.</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* Si el subproveedor está marcado como de prueba y el usuario no está habilitado como usuario de prueba, la plataforma le muestra un mensaje indicando que los juegos no están disponibles.
* Los campos **`ID`** y **`Proveedor`** no se pueden editar.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>11/02/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
