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
  anchors:
    visible: true
---

# Merkur.

<mark style="color:$info;">En este documento se detallan únicamente los campos y consideraciones particulares que aplican al momento de crear un bono FreeSpin específicamente para el proveedor Merkur.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización

<figure><img src="https://2840730235-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FpVk1Kqoe0aInaa5Ofl6i%2Fuploads%2FFUlicOkqx8uXklhf4Ref%2Fimage.png?alt=media&#x26;token=56f20060-ef27-4750-a5e2-995f108717a7" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla de la sección FreeSpin.</p></figcaption></figure>

***

### 3. Formulario para creación de bonos Merkur

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **Merkur** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% content-ref url="https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}
[FreeSpin](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin)
{% endcontent-ref %}

<table><thead><tr><th width="140.5">Sección</th><th width="108.126220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Botón "Agregar"</td><td>Permite seleccionar la fecha inicial y final de vigencia del bono.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td><p>Despliega los proveedores con Bonus System activo. Se debe seleccionar "<strong>Merkur</strong>".</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al seleccionar <strong>Proveedores</strong> y <strong>Productos</strong>, se mostrará una tabla donde se debe definir el porcentaje del bono que asumirá el proveedor.</p></div></td></tr><tr><td><strong><code>Productos</code></strong></td><td>Lista desplegable</td><td>Se debe seleccionar nuevamente "<strong>Merkur</strong>" para ver los juegos disponibles. Solo se podrán seleccionar juegos disponibles del proveedor <strong>Merkur</strong>.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>La selección de moneda es obligatoria para habilitar los campos del bono.<br><a href="merkur..md#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Los campos marcados con un asterisco (\*) en el formulario son obligatorios.
{% endhint %}

<details>

<summary>🔽 Configuración de moneda</summary>

<table><thead><tr><th width="114">Campo</th><th width="129">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Campo numérico</td><td><p>Define el monto del bono por cada jugada gratuita.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El valor ingresado debe coincidir exactamente con el permitido por el juego. En caso de que no coincida, el bono no se activará.</p></div><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si el juego permite máximo 5 y se configura 10, el bono no funcionará.</p></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Campo numérico</td><td>Cantidad de rondas gratuitas que se asignarán al bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Permite cargar el archivo en formato <a href="https://virtualsoft.gitbook.io/untitled/glosario#csv">CSV</a> con los ID de usuarios que recibirán el bono.</td></tr></tbody></table>

<a href="merkur..md#id-3.-formulario-para-creacion-de-bonos-merkur" class="button secondary">Regresar</a>

</details>

Finaliza la configuración del bono guardando y aplicando las configuraciones realizadas desde el botón **`Crear Bono`**.

***

* La información de este bono estará disponible en la reportería de _Productos No Deportivos_.

{% hint style="warning" %}
**Nota:** Si se realiza una compra de giros en la tienda del proveedor, las ganancias de estos giros se reportarán como "**Premios**" y no como "**Premios bonos**"
{% endhint %}

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/readme/reportes/reporte-productos-no-deportivos" %}
[Reporte productos no deportivos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/readme/reportes/reporte-productos-no-deportivos)
{% endcontent-ref %}

* La información sobre los movimientos realizados por el usuario con este bono estará disponible en la reportería _Historial de movimientos._

{% hint style="warning" %}
**Nota:** El historial de movimientos mostrará un registro independiente por cada jugada gratuita realizada.
{% endhint %}

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/readme/jugadores/reportes-seccion-jugadores/historial-de-movimientos" %}
[Historial de movimientos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/readme/jugadores/reportes-seccion-jugadores/historial-de-movimientos)
{% endcontent-ref %}

***

### 4. Validaciones y Reglas de Negocio

* Al seleccionar **Proveedores** y **Productos**, se mostrará una tabla donde se debe definir el porcentaje del bono que asumirá el proveedor.
*   El valor ingresado en el campo **`Valor por ronda`** debe coincidir exactamente con el permitido por el juego. En caso de que no coincida, el bono no se activará.

    <div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si el juego permite máximo 5 y se configura 10, el bono no funcionará.</p></div>
* Los ID de los jugadores deben estar correctamente estructurados en el archivo .CSV, ya que el sistema activa automáticamente los bonos según este archivo.
* Solo se podrán seleccionar juegos disponibles del proveedor **Merkur**.
* La selección de moneda es obligatoria para habilitar los campos del bono.
* Si ocurre un error durante la ejecución del juego, se mostrará un mensaje emergente (pop-up) y se redireccionará al lobby.

***

### 5. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>18/07/2025</td><td>Ronald Peláez</td><td>Aplicación inicial de formato</td></tr><tr><td>1.1</td><td>26/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
