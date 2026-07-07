---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# SubProveedores

Permite **asociar o desasociar subproveedores a un partner**, estableciendo qué subproveedores estarán disponibles para su configuración general dentro del sistema.

{% hint style="warning" %}
**Nota**: Esta gestión no depende del país ni del orden de visualización.
{% endhint %}

***

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Productos > SubProveedores.

***

### 2. Visualización:

<figure><img src="../../.gitbook/assets/image (608).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección SubProveedores.</p></figcaption></figure>

### **3. Acciones del Usuario**

<table><thead><tr><th width="227">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros de búsqueda</strong></td><td>Permite consultar información de usuarios online según criterios básicos.</td></tr><tr><td><strong>Exportar información</strong></td><td>Descarga los resultados de una consulta en un formato de Excel o PDF.</td></tr><tr><td><a href="subproveedores.md#id-2.3-anadir-sub-proveedor"><strong>Añadir subproveedor</strong></a></td><td>Añade nuevos subproveedores a la plataforma de usuarios online.</td></tr></tbody></table>

***

### 4. Filtros de Búsqueda

<table><thead><tr><th width="118">Filtro</th><th width="140">Tipo de Control</th><th width="481">Descripción</th></tr></thead><tbody><tr><td><strong><code>SubProveedor ID</code></strong></td><td>Texto</td><td>Permite buscar un subproveedor específico ingresando su identificador único.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista despegable</td><td>Selecciona un proveedor específico para realizar una búsqueda de los subproveedores asociados a el.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Filtra subproveedores según el nombre registrado en el sistema.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Filtra subproveedores por categoría <em>(ejemplo: Casino, depósitos).</em></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra los subproveedores según su estado actual en la plataforma <em>(Activo, Inactivo).</em></td></tr></tbody></table>

#### 4.1 Filtros avanzados

Utiliza los filtros para obtener resultados de búsqueda más precisos.

<table><thead><tr><th width="117">Filtro</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Verificado</code></strong></td><td>Lista desplegable</td><td>Estado de verificación actual del subproveedor <em>(activo, inactivo o todos).</em></td></tr><tr><td><strong><code>Abreviado</code></strong></td><td>Texto</td><td>Abreviatura asignada al subproveedor.</td></tr></tbody></table>

***

### 5. Resultados de la Consulta

<table><thead><tr><th width="152">Campo</th><th width="592">Descripción</th></tr></thead><tbody><tr><td><strong><code>SubProveedor ID</code></strong></td><td>Identificador único asignado al subproveedor en el sistema.</td></tr><tr><td><strong><code>Proveedor ID</code></strong></td><td>Identificador único del proveedor.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre del subproveedor registrado.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Clasificación del subproveedor según el servicio ofrecido <em>(ej.casino).</em></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del subproveedor dentro de la plataforma.</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Indica si el subproveedor esta en estado activo o inactivo.</td></tr><tr><td><strong><code>Abreviado</code></strong></td><td>Abreviatura asignada al subproveedor para referencias rápidas.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>url de la imagen representativa del subproveedor.</td></tr></tbody></table>

***

### 6. Añadir SubProveedor

Al presionar el botón **"Añadir SubProveedor"** se despliega un formulario en el cual deben completarse los siguientes campos:

<table><thead><tr><th width="133">Campo</th><th width="118">Tipo de Control</th><th width="479">Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre del subproveedor a registrar.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Proveedor principal al que se asociará el subproveedor.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Clasificación del subproveedor según el servicio ofrecido <em>(ej. Sport, casino).</em></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Define el estado en que quedara el subproveedor.</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Selector</td><td><p>Permite definir si el proveedor está habilitado para aprobación manual en operaciones como depósitos o retiros. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Se recomienda mantener este campo en <strong>Inactivo</strong>, ya que establecerlo en <strong>Activo</strong> puede generar errores en el funcionamiento del sistema.</p></div></td></tr><tr><td><strong><code>Abreviado</code></strong></td><td>Texto</td><td>Indica el nombre abreviado que tendrá este subproveedor.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL</td><td>Permite asignar una URL para la imagen asociada al subproveedor.</td></tr><tr><td><strong><code>Credenciales</code></strong></td><td>Texto</td><td>Credenciales internas del subproveedor. Esta información es de uso interno; en caso de requerirla, deberá solicitarla directamente al equipo de soporte.</td></tr></tbody></table>

Una vez completados los campos, se debe presionar **Guardar** para registrar la información o **Cancelar** para descartar la operación.

***

### **7. Validaciones y Reglas de Negocio**

* El **Nombre** debe ser único y no duplicarse entre subproveedores.
* Las **Credenciales** son confidenciales y visibles solo para usuarios con permisos de administración.

***

### **8. Control de Versiones**

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="111">Versión</th><th width="149">Fecha</th><th width="188">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/08/2025</td><td>Karol Navia</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>09/10/2025</td><td>Ronald Pelaez</td><td>Refinamiento de manual.</td></tr><tr><td>1.2</td><td>29/10/2025</td><td>Karol Navia</td><td>Refinamiento en descripciones</td></tr><tr><td>1.3</td><td>31/10/2025</td><td>Karol Navia</td><td>Agregar filtro proveedores</td></tr></tbody></table>

</details>
