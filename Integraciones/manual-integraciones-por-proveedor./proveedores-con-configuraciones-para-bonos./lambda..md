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

# Lambda.

<mark style="color:$info;">Aquí encontrarás información importante que se debe tener en cuenta al momento de la creación de un bono FreeSpin para el proveedor Lambda.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (95).png" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla de la sección FreeSpin.</p></figcaption></figure>

***

### 3. Formulario para creación de bonos Lambda

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **Lambda** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% content-ref url="https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}
[FreeSpin](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin)
{% endcontent-ref %}

<table><thead><tr><th width="140.5">Sección</th><th width="108.126220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td>El botón <strong>Proveedores</strong> despliega solo los proveedores que tienen el Bonus System activo. En este caso se debe visualizar y seleccionar la opción "<strong>Lambda</strong>".</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td><p>El botón <strong>Productos</strong> despliega 2 listas para seleccionar un juego dependiendo del proveedor. En este caso, es necesario volver a seleccionar el proveedor "<strong>Lambda</strong>" para visualizar los juegos disponibles.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al configurar los campos "<strong>Proveedores</strong>" y "<strong>Productos</strong>" se desplegará una tabla en la cual se debe especificar el porcentaje del bono que asumirá el proveedor.</p></div></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Para poder dar uso a los bonos FreeSpin con el proveedor Lambda, es necesario seleccionar la moneda del país con el que se genera el bono. Esto activará las siguientes configuraciones.<br><a href="lambda..md#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

<table><thead><tr><th width="114">Campo</th><th width="129">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Cantidad de rondas gratuitas que el usuario podrá jugar con este bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td><p>Se debe ingresar el ID de cada usuario que tendrá el bono activo. Este proceso requiere cargar un archivo en formato <strong>CSV</strong> con los ID correspondientes. El sistema tomará los datos del archivo y activará automáticamente el bono para los jugadores especificados.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Con este proveedor el valor por ronda de los juegos se asignará por defecto con base en el valor mínimo de los juegos seleccionados; por ende, el campo <strong>Valor por ronda</strong> no será visible.</p></div></td></tr></tbody></table>

<a href="lambda..md#id-3.-formulario-para-creacion-de-bonos-lambda" class="button secondary">Regresar</a>

</details>

Finaliza la configuración del bono guardando y aplicando las configuraciones realizadas desde el botón **`Crear Bono`**.

***

### 4. Validaciones y Reglas de Negocio

* Con este proveedor, el valor por ronda se asigna por defecto con base en el valor mínimo de los juegos seleccionados, por lo que el campo **`Valor por ronda`** no se muestra en el formulario.

***

### 5. Lambda en plataforma

El ejemplo se realiza desde la plataforma Doradobet, desde la siguiente ruta:

* **Menú/ Casino/**

Los juegos del proveedor Lambda se buscan haciendo clic en el ícono "**+**" ubicado en la esquina derecha. Esto permite explorar más opciones y acceder a la lista completa de proveedores, donde se puede seleccionar **Lambda**.

<figure><img src="../../.gitbook/assets/image (40).png" alt=""><figcaption><p>Figura #2: Captura de pantalla filtros.</p></figcaption></figure>

Luego de seleccionar el proveedor se mostrarán los juegos activos para este.

<figure><img src="../../.gitbook/assets/image (41).png" alt=""><figcaption><p>Figura #3: Captura de pantalla Juegos LAMBDA</p></figcaption></figure>

***

### 6. Reportes de Lambda

Los reportes de cada apuesta realizada por un usuario en la plataforma se pueden visualizar directamente desde el BackOffice, desde la siguiente ruta:

* **Menú/ Jugadores/ Perfil del jugador/ Reportes/ Reporte de Casino**.

Al elegir esta opción, se despliega una serie de filtros que permiten personalizar la consulta. Estos filtros no son obligatorios; sin embargo, para realizar una búsqueda más específica, se pueden completar los campos según sea necesario.

<figure><img src="../../.gitbook/assets/image (53).png" alt=""><figcaption><p>Figura #4: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

En este caso se explican solo los filtros necesarios para visualizar el reporte de Lambda:

<table><thead><tr><th width="160">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Se debe seleccionar el proveedor Lambda, para visualizar solo los reportes de dicho proveedor.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Se debe seleccionar la opción "<strong>Detallado</strong>", para poder visualizar el reporte realizado por el proveedor.</td></tr></tbody></table>

Al presionar el botón "**Consultar**", se muestra en la parte inferior una tabla con la información del reporte.

<figure><img src="../../.gitbook/assets/image (55).png" alt=""><figcaption><p>Figura #5: Captura de pantalla de ejemplo.</p></figcaption></figure>

<table><thead><tr><th width="190">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Lupa (🔍)</code></strong></td><td><p>Permite ingresar a los detalles de la apuesta:</p><ul><li><strong>Id</strong>: Identificador único del registro de la transacción.</li><li><strong>Transacción Id</strong>: Código único asociado a la transacción específica.</li><li><strong>Tipo</strong>: Indica si la transacción es un <em>DEBIT</em> (débito) o un <em>CREDIT</em> (crédito).</li><li><strong>Valor</strong>: Muestra el monto asociado a la transacción.</li></ul></td></tr><tr><td><strong><code>Id</code></strong></td><td>Identificador único relacionado con el juego.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha y hora exacta.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador único del usuario que realizó la actividad.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego asociado.</td></tr><tr><td><strong><code>Identificador</code></strong></td><td>Código único asignado al juego, utilizado para su referencia dentro del sistema.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Proveedor del juego.</td></tr><tr><td><strong><code>Cantidad</code></strong></td><td>Número de veces que se realizó la actividad.</td></tr><tr><td><strong><code>Impuesto Apuesta</code></strong></td><td>Monto del impuesto aplicado a las apuestas realizadas.</td></tr><tr><td><strong><code>Impuesto Premios</code></strong></td><td>Monto del impuesto asociado a los premios entregados.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Valor total apostado en la transacción <em>(en este ejemplo, aparece como 0.00, ya que fueron giros gratis otorgados del bono FreeSpin)</em>.</td></tr><tr><td><strong><code>Saldo Gratis</code></strong></td><td>Cantidad de saldo gratuito utilizado durante la transacción.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Monto total de premios otorgados.</td></tr><tr><td><strong><code>Bonos</code></strong></td><td>Valor total de bonos utilizados.</td></tr><tr><td><strong><code>GGR (Gross Gaming Revenue)</code></strong></td><td>Ingresos brutos generados por el juego.</td></tr><tr><td><strong><code>Premios Bonos</code></strong></td><td>Monto de premios pagados utilizando bonos <em>(en este caso, 0.80)</em>.</td></tr><tr><td><strong><code>Beneficio %</code></strong></td><td>Porcentaje de beneficio obtenido en esta transacción.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Esta captura de pantalla es solo un ejemplo, ya que la tabla contiene más casillas que se pueden visualizar al deslizar hacia la izquierda.
{% endhint %}

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual e incorporación del control de versiones.</td></tr></tbody></table>

</details>
