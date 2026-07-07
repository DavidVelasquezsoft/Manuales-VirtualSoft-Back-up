---
description: >-
  Permite consultar y visualizar las credenciales asociadas a integraciones de
  proveedores y subproveedores. A través de filtros dinámicos, el usuario puede
  acceder a información detallada.
---

# Credenciales Por SubProveedor

### Configuración general

### 1. Acceso al Módulo:

**Ruta de acceso:** Herramientas > Partner ajustes > Seleccionar partner > Productos 2 > Credenciales Por SubProveedor

***

### 2. Visualización general

<figure><img src="../../../../.gitbook/assets/image (607).png" alt=""><figcaption><p>Figura#1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### 🧑‍💻 3. Acciones del Usuario

<table><thead><tr><th width="108">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Consultar</strong></td><td>Permite aplicar los filtros disponibles <em>(Proveedor, SubProveedor, País, Tipo, Estado)</em>.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados y deja los campos vacíos para realizar una nueva búsqueda.</td></tr><tr><td><a href="credenciales-por-subproveedor.md#id-3.2.1-editar"><strong>Editar ✏️</strong></a></td><td>Abre un pop-up con la información detallada de la credencial seleccionada (ID, Proveedor, SubProveedor, Partner, Estado, País).</td></tr></tbody></table>

***

#### 🧭 3.1. Filtros disponibles

Estos filtros permiten acotar la consulta y localizar la credencial deseada. Ninguno es obligatorio.

<table><thead><tr><th width="130">Filtro</th><th width="136">Tipo</th><th>Descripción</th><th width="129">Obligatorio?</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona el proveedor principal <em>(ej.: Jumio, Spinomenal, Pragmatic, etc.).</em></td><td>❌No</td></tr><tr><td><strong><code>SubProveedor</code></strong></td><td>Lista desplegable</td><td>Filtra por el subproveedor específico <em>(ej: SPINOMENAL(SPINOMENAL), SPINBERRY(PARIPLAY), SPINZA(ONLYPLAY), etc.).</em></td><td>❌No</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra por el socio/comercial (partner) donde está asociada la credencial.</td><td>❌No</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Restringe la búsqueda a un país en particular.</td><td>❌No</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Filtra según el tipo de integración <em>(Casino, CPF, CRM, General, etc.).</em></td><td>❌No</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra por estado <em>(Activo / Inactivo).</em></td><td>❌No</td></tr></tbody></table>

***

#### ⚙️ 3.2. Resultados de la consulta

Al ejecutar la búsqueda, el sistema mostrará una tabla en la parte inferior de la pantalla con los resultados correspondientes.

<table><thead><tr><th width="146">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="credenciales-por-subproveedor.md#id-2.2.1-editar"><code>✏️ </code><strong><code>(Editar)</code></strong><code>.</code></a></td><td>Al hacer clic en este ícono, se abrirá un pop-up que permite editar la información correspondiente a la credencial seleccionada.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Código único que identifica la credencial dentro del sistema.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor principal.</td></tr><tr><td><strong><code>SubProveedor</code></strong></td><td>Nombre asignado al subproveedor. </td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#partner"><strong><code>Partner</code></strong></a></td><td>Nombre del partner asociado al subproveedor.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Indica si la credencial está activa o inactiva.</td></tr><tr><td><strong><code>País</code></strong></td><td>País en el que se encuentra operativo  subproveedor, o donde se aplicará la credencial.</td></tr></tbody></table>

***

#### 🪟 3.2.1 Editar

El pop-up muestra la información detallada de la credencial seleccionada, permitiendo editar algunos datos.

<table><thead><tr><th width="166">Campo</th><th width="454">Descripción</th><th>Editable?</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador de la credencial único en el sistema.</td><td>❌No</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor principal asociado.</td><td>❌No</td></tr><tr><td><strong><code>SubProveedor</code></strong></td><td>Nombre asignado al subproveedor.</td><td>❌No</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner en el cual se realizó la integración.</td><td>❌No</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Indica si la credencial está activa o inactiva.</td><td>❌No</td></tr><tr><td><strong><code>País</code></strong></td><td>País al que se asocia la integración.</td><td>❌No</td></tr><tr><td><strong><code>API_PASSWORD</code></strong></td><td>Contraseña asignada para la integración entre sistemas a través de la API del proveedor.</td><td>✅Sí</td></tr><tr><td><strong><code>API_LOGIN</code></strong></td><td>clave de acceso utilizada para autenticar la integración.</td><td>✅Sí</td></tr><tr><td><strong><code>URL</code></strong></td><td>Dirección utilizada para establecer la conexión con el servicio del proveedor.</td><td>✅Si</td></tr></tbody></table>

***

### ✅ 4. Validaciones y Reglas de Negocio

* Ninguno de los filtros es obligatorio; sin embargo, su uso permite acotar la búsqueda.
* Las credenciales se muestran únicamente si están registradas correctamente en el sistema.

***

### 🕒 5. Control de Versiones

<table><thead><tr><th>Versión</th><th>Fecha</th><th width="159">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>29/10/2025</td><td>Karol Navia</td><td>Documento inicial adaptado a la plantilla</td></tr></tbody></table>
