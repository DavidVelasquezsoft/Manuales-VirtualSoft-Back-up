# Banco País

<mark style="color:$info;">Agrega o retira los bancos disponibles para cada país. En este módulo también aparecen las criptomonedas creadas, que se gestionan como bancos.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Herramientas > Partner Ajustes > Productos 2 > Banco País

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FiFiAg0FvDB5UZmJ97HF9%2Fimage.png?alt=media&#x26;token=cae63efd-1cbb-4380-8720-c4c2db789590" alt=""><figcaption><p>Figura #1: Captura de pantalla sección banco país.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="banco-pais.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen el país y el banco que se van a consultar.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="banco-pais.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los bancos en los paneles de gestión.</td></tr><tr><td><a href="banco-pais.md#id-6.-agregar-o-retirar-bancos"><strong>Agregar / Retirar</strong></a></td><td>Agrega bancos al país o los retira mediante los botones ubicados entre los paneles.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país cuyos bancos se van a consultar.</td></tr><tr><td><strong><code>Banco</code></strong></td><td>Lista desplegable</td><td><p>Acota la consulta a un banco específico.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este filtro es opcional; la consulta puede hacerse solo con el país.</p></div></td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, los bancos se muestran en dos paneles.

<table><thead><tr><th width="200">Campo</th><th width="120">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Bancos no agregados</code></strong></td><td>Lista</td><td>Muestra, en el panel izquierdo, los bancos disponibles que aún no están agregados al país.</td></tr><tr><td><strong><code>Bancos agregados</code></strong></td><td>Lista</td><td>Reúne, en el panel derecho, los bancos ya agregados al país.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** En los paneles también aparecen las criptomonedas creadas. Para que una criptomoneda se muestre en la plataforma de Usuarios Online, debe estar agregada como banco.
{% endhint %}

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2Fx9RFfAr3PU8H3ObsUsQh%2Fimage.png?alt=media&#x26;token=79bf2f25-7ba7-4cb6-ac0d-8f5564e5b5de" alt=""><figcaption><p>Figura #2: Captura de pantalla panel de gestión de bancos.</p></figcaption></figure>

***

### 6. Agregar o retirar bancos

Para agregar o retirar un banco, se selecciona en el panel correspondiente y se usan los botones ubicados entre los dos paneles.

<table><thead><tr><th width="120">Botón</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>&#x3E;</code></strong></td><td>Agrega al país el banco seleccionado en <strong>Bancos no agregados</strong>.</td></tr><tr><td><strong><code>&#x3C;</code></strong></td><td>Retira del país el banco seleccionado en <strong>Bancos agregados</strong>.</td></tr><tr><td><strong><code>&#x3E;&#x3E;</code></strong></td><td>Agrega al país todos los bancos disponibles.</td></tr><tr><td><strong><code>&#x3C;&#x3C;</code></strong></td><td>Retira del país todos los bancos agregados.</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* La consulta requiere seleccionar el país; el banco es opcional.
* Para mover un banco de forma individual, primero se debe seleccionar en su panel.
* Una criptomoneda solo se muestra en la plataforma de Usuarios Online si está agregada como banco.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>06/08/2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
