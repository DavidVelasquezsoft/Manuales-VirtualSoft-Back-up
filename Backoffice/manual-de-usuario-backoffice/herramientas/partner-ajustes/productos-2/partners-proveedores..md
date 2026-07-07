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

# Partners Proveedores.

Desde este módulo se visualizan todos los [proveedores previamente creados](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos/partners-proveedores). La información se organiza en dos listas: **Proveedores No Agregados** y **Proveedores Agregados**, según estén o no asociados al partner seleccionado.

Este módulo permite gestionar esa asociación de forma directa, es decir, agregar proveedores al partner o retirarlos de este.

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Herramientas > Partner ajustes > Seleccionar partner > Configuraciones > Productos 2 > Partner proveedores.

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (652).png" alt=""><figcaption><p>Figura#1: Captura de pantalla activación de partners.</p></figcaption></figure>

***

### 3. Acciones disponibles en el módulo.

<table><thead><tr><th width="240">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos-2/partners-proveedores.#id-4.-filtros-principales"><strong>Filtrar proveedores</strong></a></td><td>Despliega los filtros y permite realizar búsquedas de proveedores creados según criterios específicos.</td></tr><tr><td><strong>Modificar estado del proveedor en la plataforma.</strong></td><td>Permite asociar o retirar un proveedor, controlando su visibilidad dentro del <em>partner</em> seleccionado.</td></tr><tr><td><strong>Ejecutar búsqueda</strong></td><td>Utiliza el botón "<strong><code>Buscar</code></strong>" para ejecutar la búsqueda con los filtros seleccionados o el botón "<strong><code>Limpiar</code></strong>" y restablecer los filtros.</td></tr></tbody></table>

***

### **4. 🔍 Filtros principales**

<table><thead><tr><th width="160">Campo</th><th width="160">Tipo de Control</th><th width="426">Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por proveedores previamente creados.</td></tr><tr><td><strong><code>Partner Referencia</code></strong></td><td>Lista desplegable</td><td><p>Permite seleccionar el <em>partner</em> sobre el cual se realizará la gestión. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>:  Al aplicarlo, se filtran los proveedores y, en la lista de asociados, se visualizarán únicamente los vinculados a ese <em>partner</em>. Adicionalmente, cualquier acción realizada ejecutará sobre este <em>partner</em> seleccionado.</p></div></td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Campo obligatorio requerido para habilitar la ejecución de la consulta. Su selección no afecta los resultados mostrados ni las acciones realizadas sobre los proveedores; únicamente activa el botón <strong>Consultar</strong>.</td></tr></tbody></table>

#### **4.1. 📊Resultados**

Las listas de proveedores se construyen en función de los filtros aplicados, los cuales permiten tanto consultar el estado actual como facilitar la gestión de asociación o retiro.

<table><thead><tr><th width="244">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores No Agregados</code></strong></td><td>Lista de proveedores disponibles, aún no asociados al partner.</td></tr><tr><td><strong><code>Proveedores Agregados</code></strong></td><td>Lista de proveedores que ya están asociados al partner.</td></tr></tbody></table>

***

### 5. Flujo para la gestión de proveedores.

Selecciona uno o varios proveedores y utiliza los botones disponibles para gestionar su estado, ya sea para asociarlos o retirarlos del partner seleccionado.

<table><thead><tr><th width="157">Acción</th><th width="89" align="center">Botón</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Retirar / Asociar todos los proveedores</code></strong></td><td align="center"><strong>« »</strong></td><td>Traslada la totalidad de los proveedores de una lista a la otra, aplicando la acción de asociación o retiro de forma masiva.</td></tr><tr><td><strong><code>Retirar proveedor</code></strong></td><td align="center"><strong>&#x3C;</strong></td><td>Permite retirar únicamente los proveedores seleccionados de la lista <strong><code>Proveedores Agregados</code></strong>.</td></tr><tr><td><strong><code>Agregar proveedor</code></strong></td><td align="center"><strong>></strong></td><td>Permite asociar únicamente los proveedores seleccionados desde la lista <strong><code>Proveedores No Agregados</code></strong>.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: Al intentar asociar o retirar un proveedor aparecerá un pop-up que exige una **`Observación`** obligatoria. Si no se completa y se confirma con el botón **`Guardar`**, se mostrará un error y la acción no se ejecutará.
{% endhint %}

***

### 6. Validaciones y Reglas de Negocio

* El campo **Observación** es obligatorio para confirmar la asociación o retiro de proveedores.
* Es necesario hacer clic en **Guardar** en el pop-up para aplicar los cambios.
* Para que un proveedor aparezca en este módulo, es necesario haberlo creado previamente desde el módulo [Partners Proveedores](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos/partners-proveedores).

***

### 7. Control de Versiones

<table><thead><tr><th width="105">Versión</th><th width="141">Fecha</th><th width="185">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2026-03-18</td><td>Ronald Peláez</td><td>Documento inicial</td></tr></tbody></table>
