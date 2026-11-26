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

# Pateplay

<mark style="color:$info;">Permite la creación, configuración y gestión de bonos de giros gratuitos (FreeSpin) asociados a los juegos del proveedor Pateplay.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/pateplay.png" alt=""><figcaption><p>Figura #1: Captura de pantalla creación bono freeSpin.</p></figcaption></figure>

### 3. Formulario para creación de bonos Pateplay

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **Pateplay** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% content-ref url="https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}
[FreeSpin](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin)
{% endcontent-ref %}

<table><thead><tr><th width="124.44451904296875">Sección</th><th width="110">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón Agregar</td><td>Define la fecha de inicio y finalización en la que el bono estará activo.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Define el nombre que se asignará al bono.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Campo numérico</td><td><p>Permite definir la prioridad del bono, lo que determina el orden en que se asignarán los bonos a los usuarios. Un número más alto significa una mayor prioridad.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si hay tres bonos configurados con las siguientes prioridades: </p><ul><li><strong>Bono A</strong>: 1</li><li><strong>Bono B</strong>: 2</li><li><strong>Bono C</strong>: 3</li></ul><p>El sistema dará preferencia al B<strong>ono C</strong> al momento de la activación, ya que tiene la prioridad más alta. Esto asegura que los usuarios siempre reciban primero el bono con mayor relevancia según la configuración.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Breve explicación de las condiciones o características del bono.</td></tr><tr><td><strong><code>URL imagen principal</code></strong></td><td>URL</td><td>Inserta la URL de la imagen principal del bono.</td></tr><tr><td><strong><code>Cantidad de jugadores</code></strong></td><td>Numérico</td><td>Define el número total de usuarios que recibirán el bono.</td></tr><tr><td><strong><code>Cliente puede recibir otros bonos adicionales después del actual?</code></strong></td><td> Botón de selección</td><td>Indica si el usuario podrá acumular bonos adicionales al actual que se está creando.</td></tr><tr><td><strong><code>Cliente puede repetir bono?</code></strong></td><td> Botón de selección</td><td>Define si el usuario puede <a href="https://virtualsoft.gitbook.io/untitled/glosario#redimir">redimir</a> más de una vez el mismo bono.</td></tr><tr><td><strong><code>Tipo producto</code></strong></td><td> Botón de selección</td><td>Para el caso de "<strong>pateplay</strong>"<strong>,</strong> selecciona <strong>Casino</strong>.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td>Selecciona el proveedor del bono, en este caso "<strong>pateplay</strong>".</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td>Lista los juegos disponibles del proveedor seleccionado, se debe elegir el juego en el que estará disponible el bono.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td><p>Al seleccionar la moneda, se habilitarán las configuraciones correspondientes, las cuales variarán según el <strong><code>tipo de bono</code></strong> que se seleccione.</p><p><a href="pateplay.md#configuracion-de-moneda" class="button secondary">Configuraciones por moneda</a></p></td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

Al seleccionar la moneda se desplegarán las siguientes configuraciones:

<table><thead><tr><th width="117">Campo</th><th width="154">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Numérico</td><td>Indica el valor que tendrá el bono por cada ronda jugada.</td></tr><tr><td><strong><code>Tipo de bono</code></strong></td><td>Lista desplegable</td><td>Establece que tipo de bono, para desplegar las configuraciones correspondientes.<br><a href="pateplay.md#tipos-de-bonos-disponibles" class="button secondary">Tipos de bonos disponibles.</a></td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Archivo CSV</td><td>Ingresa un archivo <a href="https://virtualsoft.gitbook.io/untitled/glosario#csv">CSV</a> con los ID de los jugadores que tendrán acceso al bono.</td></tr></tbody></table>

</details>

<details>

<summary>🔽 Tipos de bonos disponibles</summary>

Cada tipo de bono desplegará un campo correspondiente para su configuración.

<table><thead><tr><th width="138">Tipo de bono</th><th width="293">Descripción</th><th>Campos a configurar</th></tr></thead><tbody><tr><td><strong><code>Bets</code></strong> </td><td>El bono se asignará al usuario con una cantidad predefinida de rondas gratuitas, conforme a la configuración establecida.</td><td><ul><li><strong><code>Rondas gratuitas</code></strong>: Establece la cantidad de rondas que tendrá el bono.</li></ul></td></tr><tr><td><strong><code>sure_win</code></strong></td><td>El bono otorgará rondas gratuitas de manera continua hasta que el usuario obtenga una ganancia en alguna de ellas.</td><td><ul><li><strong><code>Valor por ronda</code>:</strong> Indica el valor que tendrá el bono por cada ronda jugada. </li></ul></td></tr><tr><td><strong><code>Infinity</code></strong></td><td>El bono se asignará al usuario con giros ilimitados durante un período de tiempo previamente definido.</td><td><ul><li><strong><code>Duración</code></strong>: Define el tiempo, expresado en segundos, durante el cual estará activo el bono con giros ilimitados para el usuario.</li></ul></td></tr></tbody></table>

</details>

Para guardar y crear el bono se debe seleccionar el botón "**Guardar**"

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

* El bono se crea de forma inmediata, pero la asignación a jugadores puede tardar entre **2 y 3 minutos**.
* El bono solo se puede configurar para un único juego, en caso de seleccionar varios juegos simultáneamente, el sistema asignará el bono únicamente a uno de ellos de forma aleatoria.
* Si se ingresa un valor erróneo en el campo **`Valor por ronda`** el bono se creará, pero no se le asignará al usuario.

***

### 5. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>06/11/2025</td><td>David Ortiz</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>17/02/2026</td><td>Ronald Peláez</td><td>Refinamiento de manual por actualización con el partner.</td></tr><tr><td>1.2</td><td>26/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
