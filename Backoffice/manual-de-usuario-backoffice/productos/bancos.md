# Bancos

<mark style="color:$info;">Esta sección permite consultar y registrar los bancos disponibles en el sistema. Un banco representa la entidad o el medio a través del cual se procesan los retiros de los usuarios, y puede crearse manualmente o generarse de forma automática al asociar una criptomoneda con una red blockchain.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Productos > Bancos

***

### 2. Visualización general

<figure><img src="../../.gitbook/assets/image (543).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Bancos</p></figcaption></figure>

***

### 3. Origen de los bancos

Los bancos registrados en el sistema pueden tener dos orígenes, según la forma en que fueron creados:

<table><thead><tr><th width="213.33331298828125">Origen</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Creación manual</strong></td><td>Bancos registrados directamente desde este módulo mediante la acción <strong>Añadir banco</strong>, correspondientes a entidades bancarias tradicionales.</td></tr><tr><td><strong>Asociación Cripto + Red</strong></td><td>Bancos generados automáticamente al asociar una criptomoneda con una red blockchain. Su nombre y estado dependen de dicha asociación.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Los bancos generados por una asociación [Cripto + Red](https://virtualsoft.gitbook.io/untitled/glosario/#criptomoneda--red-blockchain) son registros **internos** que representan esa combinación dentro del sistema. No se utilizan para el registro de cuentas bancarias ni son visibles para el jugador. Para habilitarlos como medio de retiro, consultar el flujo completo para habilitar retiros en criptomonedas.
{% endhint %}

***

### 4. Acciones disponibles

<table><thead><tr><th width="118">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="bancos.md#id-5.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los bancos registrados en el sistema.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="bancos.md#id-6.-resultados-de-busqueda"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los bancos en la tabla de resultados.</td></tr><tr><td><a href="bancos.md#id-7.-anadir-banco"><strong>Añadir banco</strong></a></td><td>Permite registrar un nuevo banco mediante una ventana emergente.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formato Excel mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 5. Filtros

<table><thead><tr><th width="113.16668701171875">Campo</th><th width="147.8333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Banco ID</code></strong></td><td>Numérico</td><td>Indica el identificador único asignado al banco.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Filtra por el nombre del banco.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra los registros según su estado <em>(Activa, Inactiva o Todos)</em>.</td></tr></tbody></table>

***

### 6. Resultados de búsqueda

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los bancos que cumplen con los filtros aplicados.

<table><thead><tr><th width="140.5556640625">Campo</th><th width="115.44439697265625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td>Columna de acciones</td><td>Permite ejecutar acciones directas sobre el registro seleccionado.</td></tr><tr><td><strong><code>Banco ID</code></strong></td><td>Numérico</td><td>Identificador único del banco.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td><p>Nombre del banco registrado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Cuando el banco proviene de una asociación <a href="https://virtualsoft.gitbook.io/untitled/glosario/#criptomoneda--red-blockchain">Cripto + Red</a>, el sistema lo nombra automáticamente con las iniciales de la criptomoneda y de la <a href="https://virtualsoft.gitbook.io/untitled/glosario/#red-blockchain">red blockchain</a> asociadas.</p></div></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td><p>Estado actual del banco <em>(Activa o Inactiva)</em>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Cuando el banco proviene de una asociación <a href="https://virtualsoft.gitbook.io/untitled/glosario/#criptomoneda--red-blockchain">Cripto + Red</a>, su estado depende directamente del estado de dicha asociación y no se gestiona desde este módulo.</p></div></td></tr></tbody></table>

***

### 7. Añadir banco

Permite registrar un nuevo banco en el sistema. Al seleccionar el botón **Añadir banco**, se abre una ventana emergente con los siguientes campos:

<table><thead><tr><th width="117.6666259765625">Campo</th><th width="123">Tipo</th><th width="462.111083984375">Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre del banco que se muestra en la plataforma.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Interruptor</td><td>Define si el banco queda <em>Activo</em> o <em>Inactivo</em> desde su creación.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Una vez guardado el registro, el campo **`Nombre`** no puede modificarse.
{% endhint %}

***

### 8. Validaciones y reglas del negocio:

* Los bancos pueden crearse manualmente desde este módulo o generarse automáticamente al asociar una criptomoneda con una red blockchain.
* El nombre del banco no puede modificarse una vez registrado.
* Los bancos generados por una asociación Cripto + Red toman su nombre y su estado de dicha asociación, por lo que no se gestionan desde este módulo.
* Los bancos generados por una asociación Cripto + Red no están disponibles para el registro de cuentas bancarias en la plataforma de usuarios online.
* Para que un banco se visualice como medio de retiro en la plataforma, debe asociarse previamente a un producto habilitado y activo para el partner y el país.

***

### 9. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="102">Versión</th><th width="127">Fecha</th><th width="169">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>08/11/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>27/08/2025</td><td>Karol Navia</td><td>Mejora en estructura</td></tr><tr><td>1.2</td><td>16/12/2025</td><td>Ronald Peláez</td><td>Refinamiento de manual</td></tr><tr><td>1.3</td><td>13/08/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-21110#icft=VSFT-21110">Se agrega el origen de los bancos y su relación con el flujo de retiros en criptomonedas.</a></td></tr></tbody></table>

</details>
