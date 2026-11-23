# Lambda.

## Lambda en plataforma:

Realizaremos el ejemplo desde la plataforma Doradobet desde la siguiente ruta:&#x20;

* **Menú/ Casino/**&#x20;

Busca los juegos del proveedor Lambda haciendo clic en el ícono "+" ubicado en la esquina derecha. Esto te permitirá explorar más opciones y acceder a la lista completa de proveedores, donde podrás seleccionar **Lambda**.

<figure><img src="../../.gitbook/assets/image (35).png" alt=""><figcaption><p>Figura #1: Captura de pantalla filtros.</p></figcaption></figure>

Luego de seleccionar el proveedor se mostrarán los juegos activos para este.

<figure><img src="../../.gitbook/assets/image (36).png" alt=""><figcaption><p>Figura #2: Captura de pantalla Juegos LAMBDA</p></figcaption></figure>

## Reportes de LAMBDA:&#x20;

Podrás visualizar los reportes realizados por cada apuesta hecha por un usuario en la plataforma directamente desde el BackOffice desde la siguiente ruta:&#x20;

* **Menú/ Jugadores/ Perfil del jugador/ Reportes/ Reporte de Casino**.

Al elegir esta opción, se desplegarán una serie de filtros que te permitirán personalizar la consulta. Es importante destacar que estos filtros no son obligatorios; sin embargo, si deseas realizar una búsqueda más específica, puedes completar los campos según sea necesario.

<figure><img src="../../.gitbook/assets/image (48).png" alt=""><figcaption><p>Figura #3: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

En este caso se explicarán solo los filtros necesarios para visualizar el reporte de Lambda.

* **Proveedor**: En este filtro debes seleccionar el proveedor Lambda, esto para visualizar solo los reportes de dicho proveedor.
* **Tipo**: En este filtro debes seleccionar el campo "**Detallado**", esto para poder visualizar el reporte realizado por el proveedor.

Al presionar el botón "**Consultar**" se desplegará una tabla con la información del reporte.

Una vez realizada la consulta, se mostrará en la parte inferior una tabla con la información correspondiente.

<figure><img src="../../.gitbook/assets/image (50).png" alt=""><figcaption><p>Figura #4: Captura de pantalla de ejemplo.</p></figcaption></figure>

* **Lupa (🔍):** Esta columna tendrá la opción de ingresar a los detalles de la apuesta.
  * **Id**: Identificador único del registro de la transacción.
  * **Transacción Id**: Código único asociado a la transacción específica.
  * **Tipo**: Indica si la transacción es un _DEBIT_ (débito) o un _CREDIT_ (crédito).
  * **Valor**: Muestra el monto asociado a la transacción.
* **Id**: En esta casilla se encuentra el identificador único relacionado con el juego.
* **Fecha**: En esta columna se muestra la fecha y hora exacta.
* **Usuario**: Indica el identificador único del usuario que realizó la actividad.
* **Juego**: Muestra el nombre del juego asociado.
* **Identificador**: Contiene un código único asignado al juego, utilizado para su referencia dentro del sistema.
* **Proveedor**: Aquí se especifica el proveedor del juego.
* **Cantidad**: Muestra el número de veces que se realizó la actividad.
* **Impuesto Apuesta**: En esta casilla se detalla el monto del impuesto aplicado a las apuestas realizadas.
* **Impuesto Premios**: Indica el monto del impuesto asociado a los premios entregados.
* **Apuestas**: Muestra el valor total apostado en la transacción (en este ejemplo, aparece como 0.00, ya que fueron giros gratis otorgados del bono freespin).
* **Saldo Gratis**: Aquí se refleja la cantidad de saldo gratuito utilizado durante la transacción.
* **Premios**: En esta columna se encuentra el monto total de premios otorgados.
* **Bonos**: Indica el valor total de bonos utilizados.
* **GGR (Gross Gaming Revenue)**: Representa los ingresos brutos generados por el juego.&#x20;
* **Premios Bonos**: Muestra el monto de premios pagados utilizando bonos (en este caso, 0.80).
* **Beneficio %**: Indica el porcentaje de beneficio obtenido en esta transacción.

{% hint style="warning" %}
**Nota**: Esta captura de pantalla es solo un ejemplo, ya que la tabla contiene más casillas que se pueden visualizar al deslizar hacia la izquierda.
{% endhint %}

## Configuración de Bono FreeSpin para Lambda

La vista completa del bono es la siguiente:&#x20;

<figure><img src="../../.gitbook/assets/image (90).png" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla de la sección FreeSpin.</p></figcaption></figure>

En este caso nos céntratenos solo en las configuraciones necesarias para los nuevos juegos integrados por el proveedor **Lambda**.

* **Botón proveedores:** El botón "**Proveedores**", desplegará solo los proveedores que tienen el Bonus System activo, en este caso se debe visualizar y seleccionar la opción "**Lambda**".
* **Botón Productos:** El botón "**Productos**", despegará 2 listas para seleccionar un juego dependiendo el proveedor, en este caso, es necesario volver a seleccionar el proveedor "**Lambda**", para visualizar los juegos disponibles.

{% hint style="warning" %}
**Nota**: Al configurar los campos "**Proveedores**" y "**Productos**" se desplegará una tabla en la cual debes especificar el porcentaje del bono que asumirá el proveedor.
{% endhint %}

*   **Moneda**: para poder dar uso a los bonos FreeSpin con el proveedor Lambda, es necesario seleccionar la moneda del país con el que estamos generando el bono, esto activará las siguientes configuraciones.

    * **Rondas gratuitas:** En este campo podrás ingresar la cantidad de rondas gratuitas que el usuario podrá jugar con este bono.
    * **Jugadores:** En esta configuración, se debe ingresar el ID de cada usuario que tendrá el bono activo. Este proceso requiere cargar un archivo en formato **CSV** con los ID´s correspondientes. El sistema tomará los datos del archivo y activará automáticamente el bono para los jugadores especificados.

    <div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Con este proveedor el valor por ronda de los juegos se asignará por defecto en base al valor mínimo de los juegos seleccionados, por ende, este campo no será visible.</p></div>

Estas son las configuraciones principales y necesarias para generar un bono FreeSpin con los juegos del proveedor Lambda.

* Para más información sobre cómo crear un bono FreeSpin puedes ingresar a la siguiente página:

{% content-ref url="https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}
[FreeSpin](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin)
{% endcontent-ref %}
