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

# Galaxys

<mark style="color:$info;">Aquí encontrarás información importante que se debe tener en cuenta al momento de la creación de un bono FreeSpin para Galaxys.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (95).png" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla de la sección FreeSpin.</p></figcaption></figure>

***

### 3. Formulario para creación de bonos Galaxys

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **Galaxys** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% content-ref url="https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}
[FreeSpin](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin)
{% endcontent-ref %}

<table><thead><tr><th width="140.5">Sección</th><th width="108.126220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td><p>Mediante el botón <strong>Agregar</strong> se configuran las fechas durante las cuales el bono estará activo, seleccionando la <strong>fecha inicial</strong> y la <strong>fecha final</strong> que definen el período de vigencia del bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El bono inicia un minuto después de la fecha inicial establecida.</p></div></td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td>Despliega un listado solo con los proveedores que tienen el Bonus System activo; en este caso se debe seleccionar la opción <strong>Galaxys</strong>.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td><p>Despliega dos listas para seleccionar un juego según el proveedor; es necesario volver a seleccionar el proveedor <strong>Galaxys</strong> para visualizar los juegos disponibles.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al configurar los campos <strong>Proveedores</strong> y <strong>Productos</strong> se despliega una tabla en la cual se debe especificar el porcentaje del bono que asumirá el proveedor.</p></div></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Para usar los bonos FreeSpin con el proveedor Galaxys es necesario seleccionar la moneda del país para el que se genera el bono; esto activa las siguientes configuraciones.<br><a href="galaxys.md#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

<table><thead><tr><th width="114">Campo</th><th width="129">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Numérico</td><td><p>Monto que tendrá el bono por cada ronda jugada. Al configurar esta opción, es crucial verificar previamente el monto de apuesta permitido en los juegos seleccionados, ya que este debe coincidir exactamente con el valor ingresado en este campo.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si se ingresa un valor de <strong>10</strong> en el campo <strong>Valor por ronda</strong>, pero el juego en el que se usará el bono tiene una <strong>apuesta máxima permitida de 5</strong>, el bono <strong>se podrá crear</strong>, pero <strong>no se podrá utilizar</strong>, ya que el valor ingresado excede el límite permitido por el juego.</p><p>Para garantizar que el bono funcione correctamente, se debe verificar que el <strong>Valor por ronda</strong> no supere la <strong>apuesta máxima permitida</strong> del juego seleccionado.</p></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Cantidad de rondas gratuitas que el usuario podrá jugar con este bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Permite cargar un archivo en formato <a href="https://virtualsoft.gitbook.io/untitled/glosario#csv"><strong>CSV</strong></a> con los ID de cada usuario que tendrá el bono activo. El sistema toma los datos del archivo y activa automáticamente el bono para los jugadores especificados.</td></tr></tbody></table>

<a href="galaxys.md#id-3.-formulario-para-creacion-de-bonos-galaxys" class="button secondary">Regresar</a>

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

* El bono inicia un minuto después de la fecha inicial establecida.
* Si el **`Valor por ronda`** supera la apuesta máxima permitida del juego seleccionado, el bono se crea, pero no se puede utilizar.

***

### 5. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual e incorporación del control de versiones.</td></tr></tbody></table>

</details>
