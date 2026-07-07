---
description: >-
  En esta sección, podrás activar o desactivar productos asociados. Para
  realizar esta acción, se deben aplicar filtros específicos que faciliten la
  búsqueda de los productos deseados.
---

# Activación Productos.

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Herramientas > partner ajustes > Productos 2 > Activación de Productos

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FvLSGYfAD5KENgjo5AODx%2Fimage.png?alt=media&#x26;token=4fb7d598-bd24-4c41-9830-f8591d8074a3" alt=""><figcaption><p>Figura#1: Captura de pantalla activación de productos.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="265">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="activacion-productos..md#id-4.-filtros-principales"><strong>Filtrar productos</strong></a></td><td>Permite buscar productos aplicando filtros <em>(Proveedor, Subproveedor, País, etc.).</em></td></tr><tr><td><a href="activacion-productos..md#id-4.-gestion-de-productos"><strong>Activar producto</strong></a></td><td>Mueve un producto desde "No Agregados" a "Agregados".</td></tr><tr><td><a href="activacion-productos..md#id-4.-gestion-de-productos"><strong>Desactivar producto</strong></a></td><td>Mueve un producto desde "Agregados" a "No Agregados".</td></tr></tbody></table>

### **4.  Filtros principales**

<table><thead><tr><th width="160">Campo</th><th width="160">Tipo de Control</th><th width="430">Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona el proveedor al que pertenece el producto.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Lista desplegable</td><td>Filtra productos de un subproveedor específico.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Permite buscar productos por nombre.</td></tr><tr><td><p><strong><code>Partner</code></strong> </p><p><strong><code>Referencia</code></strong></p></td><td>Lista desplegable</td><td>Selecciona un partner de referencia asociado al producto.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país correspondiente.</td></tr></tbody></table>

### **5. Resultados de consulta**

Una vez aplicados los filtros, los productos se visualizarán en dos listas diferenciadas según su estado: productos habilitados y productos no habilitados.

<table><thead><tr><th width="228">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Productos No Habilitados</strong></td><td>Lista de productos que no están habilitados para el partner seleccionado. Se visualiza en el panel izquierdo.</td></tr><tr><td><strong>Productos Habilitados</strong></td><td>Lista de productos que ya se encuentran habilitados para el partner seleccionado. Se visualiza en el panel derecho.</td></tr></tbody></table>

***

### 6. Gestión de Productos

{% hint style="warning" %}
**Nota:** Al intentar mover un producto aparecerá un pop-up que exige una **Observación** mínima de 10 caracteres. Si no se cumple, se mostrará un error y la acción no se completará.
{% endhint %}

Se visualizan dos secciones principales, en las cuales se pueden ejecutar las siguientes acciones:&#x20;

<table><thead><tr><th width="141">Acción</th><th width="102">Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Activar todos</code></strong></td><td>>></td><td>Mueve todos los productos desde la lista de no habilitados hacia la lista de productos habilitados, cambiando su estado de inactivo a activo.</td></tr><tr><td><strong><code>Desactivar todos</code></strong></td><td>&#x3C;&#x3C;</td><td>Mueve todos los productos desde la lista de productos habilitados hacia la lista de no habilitados, cambiando su estado de activo a inactivo.</td></tr><tr><td><strong><code>Desactivar un solo producto</code></strong></td><td>&#x3C;</td><td>Permite seleccionar un producto de la lista de productos habilitados y moverlo a la lista de productos no habilitados (cambio de estado: activo a inactivo).</td></tr><tr><td><strong><code>Activar un solo producto</code></strong></td><td>></td><td>Permite seleccionar un producto de la lista de productos no habilitados y moverlo a la lista de productos habilitados (cambio de estado: inactivo a activo).</td></tr><tr><td><strong><code>Mover un producto (Arrastrar)</code></strong></td><td>Arrastrar</td><td>Permite mover un producto específico entre listas. Para hacerlo, selecciona el producto y arrástralo hacia la lista destino según el estado que desees asignar.</td></tr></tbody></table>

***

### 7. Validaciones y Reglas de Negocio

* El campo **País** es obligatorio para ejecutar la consulta.
* El campo **Observación** debe contener al menos 10 caracteres para activar/desactivar productos.

***

### 8. Control de Versiones

<details>

<summary>🔽Historial de Versiones</summary>

<table><thead><tr><th width="99">Versión</th><th width="138">Fecha</th><th width="154">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/08/2025</td><td>Ronald Peláez</td><td>Documento inicial del manual</td></tr><tr><td>1.1</td><td>21/04/206</td><td>Karol Navia</td><td>Refinamiento del manual</td></tr></tbody></table>

</details>
