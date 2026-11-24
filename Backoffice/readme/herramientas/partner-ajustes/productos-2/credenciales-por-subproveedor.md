# Credenciales Por SubProveedor

<mark style="color:$info;">Consulta las credenciales de integración de cada subproveedor por partner y país, y actualiza los datos de conexión con la API del proveedor. Las credenciales son el usuario, la contraseña y la URL que usa la plataforma para conectarse con el proveedor.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Herramientas > Partner Ajustes > Productos 2 > Credenciales Por Sub Proveedor

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (563).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección credenciales por subproveedor.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="credenciales-por-subproveedor.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar las credenciales registradas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="credenciales-por-subproveedor.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las credenciales en la tabla de resultados.</td></tr><tr><td><a href="credenciales-por-subproveedor.md#id-6.-editar-credencial"><strong>Editar</strong></a> <i class="fa-pencil">:pencil:</i></td><td>Abre el detalle de una credencial para actualizar sus datos de conexión.</td></tr></tbody></table>

***

### 4. Filtros

{% hint style="warning" %}
**Nota:** No es obligatorio completar los filtros. Su uso permite acotar la búsqueda.
{% endhint %}

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona el proveedor principal <em>(Ejemplo: Jumio, Spinomenal o Pragmatic)</em>.</td></tr><tr><td><strong><code>Sub Proveedor</code></strong></td><td>Lista desplegable</td><td>Acota los resultados a un subproveedor específico.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Restringe la búsqueda al país seleccionado.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Muestra las credenciales según el tipo de integración <em>(Ejemplo: Casino, CPF, CRM o General)</em>.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Separa las credenciales según su estado <em>(Activo o Inactivo)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las credenciales que cumplen con los filtros aplicados.

<table><thead><tr><th width="200">Campo</th><th width="120">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><i class="fa-pencil">:pencil:</i></td><td>Acción</td><td>Abre el detalle de la credencial para editar sus datos de conexión.</td></tr><tr><td><strong><code>Id</code></strong></td><td>Numérico</td><td>Muestra el identificador único de la credencial.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Texto</td><td>Presenta el nombre del proveedor principal.</td></tr><tr><td><strong><code>Sub Proveedor</code></strong></td><td>Texto</td><td>Indica el nombre del subproveedor.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Texto</td><td>Identifica el partner asociado al subproveedor.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Señala si la credencial está activa o inactiva.</td></tr><tr><td><strong><code>Pais</code></strong></td><td>Texto</td><td>Corresponde al país donde se aplica la credencial.</td></tr></tbody></table>

***

### 6. Editar credencial

El ícono <i class="fa-pencil">:pencil:</i> de la tabla de resultados abre una ventana emergente con el detalle de la credencial.

<table><thead><tr><th width="200">Campo</th><th>Descripción</th><th width="110">¿Editable?</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Muestra el identificador único de la credencial.</td><td>No</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Presenta el proveedor principal asociado.</td><td>No</td></tr><tr><td><strong><code>SubProveedor</code></strong></td><td>Indica el nombre del subproveedor.</td><td>No</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Identifica el partner en el que se realizó la integración.</td><td>No</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Señala si la credencial está activa o inactiva.</td><td>No</td></tr><tr><td><strong><code>País</code></strong></td><td>Corresponde al país de la integración.</td><td>No</td></tr><tr><td><strong><code>API_PASSWORD</code></strong></td><td>Define la contraseña de la integración con la API del proveedor.</td><td>Sí</td></tr><tr><td><strong><code>API_LOGIN</code></strong></td><td>Establece el usuario con el que se autentica la integración.</td><td>Sí</td></tr><tr><td><strong><code>URL</code></strong></td><td>Especifica la dirección para conectarse con el servicio del proveedor.</td><td>Sí</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* Los filtros no son obligatorios para ejecutar la consulta.
* Solo se muestran las credenciales registradas correctamente en el sistema.
* Solo los campos de conexión con la API del proveedor se pueden editar.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>29/10/2025</td><td>Karol Navia</td><td>Documento inicial adaptado a la plantilla</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
