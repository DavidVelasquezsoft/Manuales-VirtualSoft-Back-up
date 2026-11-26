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

# BELATRA.

<mark style="color:$info;">Aquí encontrarás información importante que se debe tener en cuenta al momento de la creación de un bono FreeSpin para BELATRA.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (95).png" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla de la sección FreeSpin.</p></figcaption></figure>

***

### 3. Formulario para creación de bonos BELATRA

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **BELATRA** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% content-ref url="https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}
[FreeSpin](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin)
{% endcontent-ref %}

<table><thead><tr><th width="140.5">Sección</th><th width="108.126220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td><p>Mediante el botón <strong>Agregar</strong> se configuran las fechas durante las cuales el bono estará activo, seleccionando la <strong>fecha inicial</strong> y la <strong>fecha final</strong> que definen el período de vigencia del bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La fecha final no puede exceder los 30 días a partir de la fecha inicial.</p></div></td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td><p>Despliega un listado solo con los proveedores que tienen el Bonus System activo; en este caso se debe seleccionar la opción <strong>BELATRA</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La creación de bonos FreeSpin permite únicamente un producto <em>(juego)</em> por bono con este proveedor.</p></div></td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td><p>Despliega dos listas para seleccionar un juego según el proveedor; es necesario volver a seleccionar el proveedor <strong>BELATRA</strong> para visualizar los juegos disponibles.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al configurar los campos <strong>Proveedores</strong> y <strong>Productos</strong> se despliega una tabla en la cual se debe especificar el porcentaje del bono que asumirá el proveedor.</p></div></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Para usar los bonos FreeSpin con el proveedor BELATRA es necesario seleccionar la moneda del país para el que se genera el bono; esto activa las siguientes configuraciones.<br><a href="belatra..md#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

<table><thead><tr><th width="114">Campo</th><th width="129">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Numérico</td><td><p>El valor por ronda no corresponde al monto de apuesta del juego, sino al número de orden en el que se encuentra dicho valor.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si los montos disponibles en el juego son:</p><ol><li>20/S</li><li>15/S</li><li>30/S</li></ol><p>Para seleccionar el valor 15 se debe ingresar <strong>2</strong>, ya que corresponde a su posición en la lista.</p></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Cantidad de rondas gratuitas que el usuario podrá jugar con este bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Permite cargar un archivo en formato <a href="https://virtualsoft.gitbook.io/untitled/glosario#csv"><strong>CSV</strong></a> con los ID de cada usuario que tendrá el bono activo. El sistema toma los datos del archivo y activa automáticamente el bono para los jugadores especificados.</td></tr></tbody></table>

<a href="belatra..md#id-3.-formulario-para-creacion-de-bonos-belatra" class="button secondary">Regresar</a>

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

* La fecha final del bono no puede exceder los 30 días a partir de la fecha inicial.
* Con este proveedor solo se permite un producto *(juego)* por bono FreeSpin.
* Si se seleccionan 2 o más juegos, el valor seleccionado se descuenta de todos los juegos al mismo tiempo. Es decir, si se configuran 10 rondas gratuitas y se empieza a jugar en un juego, en el otro también se descuentan al mismo tiempo.

***

### 5. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual e incorporación del control de versiones.</td></tr></tbody></table>

</details>
