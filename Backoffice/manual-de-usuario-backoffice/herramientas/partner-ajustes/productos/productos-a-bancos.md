# Productos a Bancos

<mark style="color:$info;">Esta sección permite asociar los productos con los bancos disponibles para el partner y el país seleccionados. Esta asociación es la que habilita el banco como medio de pago o retiro dentro de la plataforma de usuarios online.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Herramientas > Partner ajustes > Partner > Productos > Productos a Bancos

***

### 2. Visualización general

<figure><img src="../../../../.gitbook/assets/image (541).png" alt=""><figcaption><p>Figura #1: Captura de pantalla productos a bancos.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="185">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="productos-a-bancos.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar las asociaciones existentes.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="productos-a-bancos.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las asociaciones en la tabla de resultados.</td></tr><tr><td><a href="productos-a-bancos.md#id-6.-anadir-producto-a-banco"><strong>Añadir Producto a Banco</strong></a></td><td>Permite vincular un producto con un banco mediante una ventana emergente.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** La relación entre el **producto** y la asociación [**Cripto + Red**](https://virtualsoft.gitbook.io/untitled/glosario#criptomoneda--red-blockchain) no es directa: se establece a través del banco, siguiendo el esquema **Producto ↔ Banco ↔ Cripto + Red**.
{% endhint %}

***

### 4. Filtros

<table><thead><tr><th width="114.00006103515625">Campo</th><th width="138.1666259765625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Productos</code></strong></td><td>Lista desplegable</td><td>Filtra por el producto asociado.</td></tr><tr><td><strong><code>Banco</code></strong></td><td>Lista desplegable</td><td>Filtra por el banco asociado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td><p>Selecciona el país en el que se encuentra el banco.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo es <strong>obligatorio</strong> para ejecutar la consulta.</p></div></td></tr><tr><td><p><strong><code>Estado</code></strong></p><p><em>(avanzado)</em></p></td><td>Lista desplegable</td><td>Filtra las asociaciones según su estado <em>(Activa o Inactiva)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las asociaciones que cumplen con los filtros aplicados.

<table><thead><tr><th width="140">Campo</th><th width="120">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td> <strong><code>Editar</code></strong></td><td>Acción</td><td>Permite visualizar la asociación y modificar únicamente su estado <em>(Activa o Inactiva)</em>.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único de la asociación.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Texto</td><td>Nombre del producto asociado, con su código de identificación entre paréntesis.</td></tr><tr><td><strong><code>Banco</code></strong></td><td>Texto</td><td>Nombre del banco asociado, con su código de identificación entre paréntesis.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Estado actual de la asociación <em>(Activa o Inactiva)</em>.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Texto</td><td>Nombre del partner al que pertenece la asociación.</td></tr></tbody></table>

***

### 6. Añadir Producto a Banco

Permite vincular un producto con un banco específico. Al seleccionar el botón **Añadir Producto a Banco**, se abre una ventana emergente con los siguientes campos, todos obligatorios:

<table><thead><tr><th width="128.5">Campo</th><th width="123">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Define el país en el que se encuentra el banco.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Lista desplegable</td><td><p>Define el producto que se asociará al banco.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El producto debe estar previamente habilitado y activo para el partner y el país; de lo contrario, no aparece disponible para asociar.</p></div></td></tr><tr><td><strong><code>Banco</code></strong></td><td>Lista desplegable</td><td>Define el banco al cual se asociará el producto seleccionado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Interruptor</td><td>Define si la asociación queda <em>Activa</em> o <em>Inactiva</em> desde su creación.</td></tr></tbody></table>

{% hint style="info" %}
Esta asociación es el paso que permite que un banco generado por una asociación Cripto + Red se visualice en la plataforma de usuarios online. Consultar el flujo completo para habilitar retiros en criptomonedas.
{% endhint %}

***

### 7. Validaciones y reglas del negocio:

* El campo **`País`** es obligatorio para ejecutar la consulta.
* Todos los campos del formulario **Añadir Producto a Banco** son obligatorios.
* El producto debe estar habilitado y activo para el partner y el país antes de poder asociarse a un banco.
* La relación entre el producto y una asociación Cripto + Red se establece a través del banco: **Producto ↔ Banco ↔ Cripto + Red**.
* Desde la acción **Editar** únicamente puede modificarse el estado de la asociación.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="102">Versión</th><th width="127">Fecha</th><th width="169">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>11/08/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>20/08/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-21110#icft=VSFT-21110">Actualización y nota del flujo por retiro en criptomonedas</a></td></tr></tbody></table>

</details>
