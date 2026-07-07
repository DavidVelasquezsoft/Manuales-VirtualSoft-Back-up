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

# Partner sub proveedores Orden

Permite **activar, desactivar los subproveedores previamente asociados a un partner**, definiendo su disponibilidad específica por país.

***

### 1. Acceso al Módulo:

**Ruta de acceso:** Herramientas > Partner ajustes > Seleccionar partner > Productos 2 > Partner Sub Proveedores Orden

***

### 2. Visualización general

{% hint style="warning" %}
**Nota:** Los cambios efectuados en este módulo se aplican automáticamente al ejecutar cualquiera de las acciones disponibles.
{% endhint %}

<figure><img src="../../../../.gitbook/assets/image (512).png" alt=""><figcaption><p>Figura #1: Captura de pantalla partner sub proveedores orden.</p></figcaption></figure>

***

### 3. Acciones disponibles en el módulo

<table><thead><tr><th width="158">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos-2/partner-sub-proveedores-orden#id-4.-filtros-disponibles"><strong>Filtrar proveedores</strong></a></td><td>Utiliza los filtros establecidos para la búsqueda de sub proveedores y edición de proveedores.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos-2/partner-sub-proveedores-orden#id-5.-gestion-de-sub-proveedores"><strong>Editar estado de sub proveedores</strong></a></td><td><p>Establece el estado de los <a href="https://virtualsoft.gitbook.io/untitled/glosario#subproveedor">sub proveedores</a> en el partner y el país seleccionado <em>(activar o desactivar)</em>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Los proveedores que se modifiquen se realizará por partner, es decir, si se desactiva un <a href="https://virtualsoft.gitbook.io/untitled/glosario#subproveedor">sub proveedor</a>, se desactivará para todos los países correspondientes del partner.</p></div></td></tr></tbody></table>

***

### 4. Filtros disponibles

<table><thead><tr><th width="138">Campo</th><th width="163">Tipo de control</th><th width="446">Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el proveedor principal sobre el cual se realizará la consulta de sub proveedores.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#subproveedor"><strong><code>Sub Proveedor</code></strong></a></td><td>Lista desplegable</td><td>Filtra un sub proveedor específico dentro del proveedor seleccionado, facilitando su localización en las listas disponibles.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td><p>Define el país sobre el cual se consultarán los sub proveedores asociados, mostrando su estado correspondiente <em>(agregados o no agregados).</em></p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Este es el único filtro obligatorio para realizar la consulta y los cambios realizados aplicarán en el país seleccionado.</p></div></td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los sub proveedores según el tipo o categoría de contenido <em>(Casino, Live Casino, entre otros).</em></td></tr></tbody></table>

***

### 5. Gestión de Sub Proveedores

Una vez aplicados los filtros, los [sub proveedores](https://virtualsoft.gitbook.io/untitled/glosario#subproveedor) se visualizarán en dos listas diferenciadas según su estado:

<table><thead><tr><th width="257">Sección</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores no agregados</code></strong></td><td>Contiene los sub proveedores que se encuentran inactivos para el país seleccionado.</td></tr><tr><td><strong><code>Proveedores agregados</code></strong></td><td>Contiene los sub proveedores que se encuentran activos para el país seleccionado.</td></tr></tbody></table>

Estas listas permiten gestionar de forma visual el estado de cada sub proveedor, facilitando su activación o desactivación según sea necesario.

#### ¿Como alternar el estado de un sub proveedor?

<table><thead><tr><th width="173">Acción</th><th width="122">Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Activar todos</code></strong></td><td>Flechas dobles (>>)</td><td>Mueve todos los sub proveedores desde la lista de no agregados hacia la lista de agregados, cambiando su estado de <strong>inactivo a activo.</strong></td></tr><tr><td><strong><code>Desactivar todos</code></strong></td><td>Flechas dobles (&#x3C;&#x3C;)</td><td>Mueve todos los sub proveedores desde la lista de agregados hacia la lista de no agregados, cambiando su estado de <strong>activo a inactivo</strong>.</td></tr><tr><td><strong><code>Agregar un sólo un</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario#subproveedor"><strong><code>sub proveedor</code></strong></a><strong><code>.</code></strong></td><td>Arrastrar</td><td>Permite mover un sub proveedor específico entre listas. Para hacerlo, selecciona el sub proveedor y arrástralo hacia la lista destino según el estado que desees asignar.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**:  Al realizar un cambio de estado en algún [sub proveedor](https://virtualsoft.gitbook.io/untitled/glosario#subproveedor) se desplegará un pop-up con la opción de cancelar los cambios realizados o confirmar los cambios luego de agregar una observación.
{% endhint %}

***

### 6. Validaciones y Reglas de Negocio

* Los cambios aplicados sobre sub proveedores aplican al país seleccionado en los filtros.
* Solo permite activar sub proveedores que estén asociados a un proveedor específico.
* Los cambios realizados en este módulo registran logs internos.
* Para que un sub proveedor aparezca en este módulo, es necesario que se encuentre activo para el partner desde el módulo [Partners Sub proveedores](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos-2/partners-subproveedores).
* Los sub proveedores se crean desde el módulo [**productos**](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/productos/subproveedores).

***

### 7. Control de Versiones

<table><thead><tr><th width="161">Versión</th><th width="167">Fecha</th><th width="126">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>29/10/2025</td><td>Karol Navia</td><td>Documento inicial adaptado a la plantilla</td></tr><tr><td>1.1</td><td>25/03/2026</td><td>Ronald Peláez</td><td>Refinamiento de manual y ajuste en validaciones y reglas del negocio.</td></tr></tbody></table>
