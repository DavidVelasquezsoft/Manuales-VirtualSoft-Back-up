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

# Habilitación productos

<mark style="color:$info;">En esta sección, puedes gestionar la habilitación de productos para un Partner y sus proveedores asociados. Utiliza los filtros disponibles para buscar y seleccionar los productos que deseas habilitar</mark>

### **1. Acceso al Módulo**

**Ruta de Acceso**: BackOffice > Herramientas > Partner Ajustes> Seleccionar partner > Productos 2 > Habilitación de Productos

***

### **2. Visualización**

<figure><img src="../../../../.gitbook/assets/image (301).png" alt=""><figcaption><p>Figura#1: Captura de pantalla habilitación de productos.</p></figcaption></figure>

***

### **3. Acciones disponibles**

<table><thead><tr><th width="135">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="habilitacion-productos.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Permite definir criterios de búsqueda para ubicar productos específicos según proveedor, nombre, partner o país.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="habilitacion-productos.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda con base en los filtros seleccionados y muestra los resultados en pantalla.</td></tr></tbody></table>

***

### **4. Filtros**

<table><thead><tr><th width="181">Campo</th><th width="177">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los productos según el proveedor seleccionado.</td></tr><tr><td><strong><code>Sub Proveedor</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por un subproveedor específico.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Permite buscar productos por nombre.</td></tr><tr><td><strong><code>Partner Referencia</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los productos según el partner de referencia.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el país para la consulta. Es obligatorio.</td></tr></tbody></table>

***

### **5. Resultados de consulta**

Una vez aplicados los filtros, los productos se visualizarán en dos listas diferenciadas según su estado: productos habilitados y productos no habilitados.

<table><thead><tr><th width="228">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Productos No Habilitados</strong></td><td>Lista de productos que no están habilitados para el partner seleccionado. Se visualiza en el panel izquierdo.</td></tr><tr><td><strong>Productos Habilitados</strong></td><td>Lista de productos que ya se encuentran habilitados para el partner seleccionado. Se visualiza en el panel derecho.</td></tr></tbody></table>

***

### **6. Cómo habilitar e inhabilitar productos**

{% hint style="warning" %}
**Nota**:

* Los cambios realizados en la habilitación de productos afectan directamente la disponibilidad de los mismos para el partner seleccionado.
* Al intentar mover un producto aparecerá un pop-up que exige una **Observación** mínima de 10 caracteres. Si no se cumple, se mostrará un error y la acción no se completará.
{% endhint %}

Se visualizan dos secciones principales, en las cuales se pueden ejecutar las siguientes acciones:&#x20;

<table><thead><tr><th width="141">Acción</th><th width="102">Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Activar todos</code></strong></td><td>>></td><td>Mueve todos los productos desde la lista de no habilitados hacia la lista de productos habilitados, cambiando su estado de inactivo a activo.</td></tr><tr><td><strong><code>Desactivar todos</code></strong></td><td>&#x3C;&#x3C;</td><td>Mueve todos los productos desde la lista de productos habilitados hacia la lista de no habilitados, cambiando su estado de activo a inactivo.</td></tr><tr><td><strong><code>Desactivar un solo producto</code></strong></td><td>&#x3C;</td><td>Permite seleccionar un producto de la lista de productos habilitados y moverlo a la lista de productos no habilitados (cambio de estado: activo a inactivo).</td></tr><tr><td><strong><code>Activar un solo producto</code></strong></td><td>></td><td>Permite seleccionar un producto de la lista de productos no habilitados y moverlo a la lista de productos habilitados (cambio de estado: inactivo a activo).</td></tr><tr><td><strong><code>Mover un producto (Arrastrar)</code></strong></td><td>Arrastrar</td><td>Permite mover un producto específico entre listas. Para hacerlo, selecciona el producto y arrástralo hacia la lista destino según el estado que desees asignar.</td></tr></tbody></table>

***

### **7. Validaciones y reglas del negocio:**

* El campo **País** es obligatorio para realizar la consulta.
* Los productos habilitados y no habilitados se gestionan de forma independiente por partner y país.
* Los cambios de habilitación se reflejan inmediatamente en la configuración del partner.
* Se pueden seleccionar uno o múltiples productos para realizar acciones de habilitación o deshabilitación.

***

### **8. Control de Versiones**

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="104">Versión</th><th width="129">Fecha</th><th width="136">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21/04/2026</td><td>Karol Navia</td><td>Creación del manual de Habilitación de Productos</td></tr></tbody></table>

</details>
