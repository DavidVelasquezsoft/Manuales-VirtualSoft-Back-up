# Gestión de monedas

<mark style="color:$info;">Consulta las monedas registradas en la plataforma y activa o inactiva su disponibilidad para crear partners en Sitebuilder.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Herramientas > Gestión de Monedas

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FbIiWcsnYV0PiRcuoTQp5%2Fimage.png?alt=media&#x26;token=78f98d87-a936-481c-baa8-45c2d3f0d752" alt=""><figcaption><p>Figura #1: Captura de pantalla sección gestión de monedas.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="gestion-de-monedas.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar las monedas registradas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="gestion-de-monedas.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las monedas en la tabla de resultados.</td></tr><tr><td><a href="gestion-de-monedas.md#id-6.-editar-moneda"><strong>Editar estado</strong></a> <i class="fa-pencil">:pencil:</i></td><td>Abre el detalle de la moneda para activarla o inactivarla.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

{% hint style="warning" %}
**Nota:** No es obligatorio completar los filtros. Si no se aplica ninguno, el sistema muestra todas las monedas disponibles.
{% endhint %}

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Moneda</code></strong></td><td>Campo de texto</td><td>Busca la moneda por su código ISO, el código de tres letras que la identifica a nivel mundial <em>(Ejemplo: COP o USD)</em>.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Campo numérico</td><td>Localiza la moneda por su identificador único en el sistema.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Muestra las monedas según su estado <em>(Activo o Inactivo)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las monedas que cumplen con los filtros aplicados.

<table><thead><tr><th width="200">Campo</th><th width="120">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><i class="fa-pencil">:pencil:</i></td><td>Acción</td><td>Abre el detalle de la moneda para consultar su información y modificar su estado.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Texto</td><td>Muestra el código ISO de la moneda.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Numérico</td><td>Indica el identificador único de la moneda en el sistema.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Presenta el nombre completo de la moneda.</td></tr><tr><td><strong><code>Estatus</code></strong></td><td>Texto</td><td>Señala si la moneda está habilitada o deshabilitada para crear partners.</td></tr><tr><td><strong><code>Símbolo</code></strong></td><td>Texto</td><td>Contiene el símbolo de la moneda.</td></tr></tbody></table>

***

### 6. Editar moneda

El ícono <i class="fa-pencil">:pencil:</i> de la tabla de resultados abre una ventana emergente con el detalle de la moneda. Todos los campos son informativos, excepto **`Estado`**, que es el único editable.

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Moneda</code></strong></td><td>Muestra el código ISO de la moneda.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Presenta el nombre completo de la moneda.</td></tr><tr><td><strong><code>Símbolo</code></strong></td><td>Contiene el símbolo de la moneda.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Indica el identificador único de la moneda en el sistema.</td></tr><tr><td><strong><code>Estado</code></strong></td><td><p>Define si la moneda está disponible para crear partners en Sitebuilder.</p><ul><li><strong>Activo:</strong> la moneda se puede usar al crear un partner.</li><li><strong>Inactivo:</strong> la moneda no está disponible al crear un partner.</li></ul></td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Aplica el cambio de estado de la moneda.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Cierra la ventana sin guardar cambios.</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* Los filtros no son obligatorios para ejecutar la consulta.
* El campo **`Estado`** es el único editable en el detalle de la moneda.
* Solo las monedas activas están disponibles al crear partners en [Sitebuilder](https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar#id-3.2.-crear-nuevo-partner).

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>03/02/2026</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
