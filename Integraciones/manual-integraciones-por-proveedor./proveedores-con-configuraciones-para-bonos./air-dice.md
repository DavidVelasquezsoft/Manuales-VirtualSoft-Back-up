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

# AIR DICE

<mark style="color:$info;">Aquí encontrarás información importante que se debe tener en cuenta al momento de la creación de un bono FreeSpin para el proveedor AIR DICE.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (95).png" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla de la sección FreeSpin.</p></figcaption></figure>

### 3. Formulario para creación de bonos AIR DICE

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **AIR DICE** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% content-ref url="https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}
[FreeSpin](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin)
{% endcontent-ref %}

<table><thead><tr><th width="113">Sección</th><th width="133">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td>Define la fecha de inicio y finalización durante las cuales el bono permanecerá activo.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td><p>Selecciona el proveedor del bono, en este caso <strong>AIR DICE</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al configurar los campos <strong>Proveedor</strong> y <strong>Productos</strong>, se desplegará una tabla donde se deberá especificar el porcentaje del bono que será asumido por el proveedor.</p></div></td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td><p>Permite seleccionar el juego para el cual aplicará el bono. Al seleccionar esta opción se mostrarán dos listas; es necesario volver a seleccionar el proveedor <strong>AIR DICE</strong> para visualizar los juegos disponibles.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Solo se puede crear un bono por juego, si se seleccionan varios juegos el bono se creará, pero no se asignará.</p></div></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Selecciona la moneda correspondiente al país para el cual se creará el bono. Al hacerlo se habilitarán las configuraciones adicionales disponibles.<br><a href="air-dice.md#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

<table><thead><tr><th width="104">Campo</th><th width="145">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Numérico</td><td><p>Monto asignado a cada giro del juego, al configurar esta opción, es crucial verificar previamente el monto de apuesta permitido en los juegos seleccionados, ya que este debe coincidir con el valor ingresado en este campo.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si se configura un valor por ronda de <strong>10</strong>, pero el juego únicamente permite una apuesta máxima de <strong>5</strong>, el bono no funcionará debido a que los valores no coinciden.</p></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Define la cantidad de rondas gratuitas que recibirá el usuario con este bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Permite cargar un archivo en formato <a href="https://virtualsoft.gitbook.io/untitled/glosario#csv"><strong>CSV</strong></a> con los ID de los jugadores que recibirán el bono. El sistema procesará automáticamente el archivo y asignará el bono a los usuarios incluidos.</td></tr></tbody></table>

<a href="air-dice.md#id-3.-formulario-para-creacion-de-bonos-air-dice" class="button secondary">Regresar</a>

</details>

Finaliza la configuración del bono guardando y aplicando los cambios realizados desde el botón **`Crear Bono`**.

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

* El proveedor seleccionado debe ser **AIR DICE** para visualizar los juegos compatibles con este tipo de bono.
* La asignación de jugadores se realiza mediante la carga de un archivo [**CSV**](https://virtualsoft.gitbook.io/untitled/glosario#csv) que contenga los ID de los usuarios que recibirán el bono.

***

### 5. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>05/08/2026</td><td>Ronald Peláez</td><td>Documento inicial.</td></tr><tr><td>1.1</td><td>26/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
