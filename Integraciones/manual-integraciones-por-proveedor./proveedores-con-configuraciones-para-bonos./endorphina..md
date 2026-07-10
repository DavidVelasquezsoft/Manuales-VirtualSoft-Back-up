---
description: >-
  Aquí encontrarás información importante que se debe tener en cuenta al momento
  de la creación de un bono FreeSpin para ENDORPHINA.
---

# ENDORPHINA.

Esta es la visual completa del Bono FreeSpin

<figure><img src="../../.gitbook/assets/image (90).png" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla de la sección FreeSpin.</p></figcaption></figure>

En este caso nos céntratenos solo en las configuraciones necesarias para la configuración de los nuevos juegos integrados por el proveedor ENDORPHINA.

* **Rango de fechas:** El botón **"Agregar"**, desplegará una opción que te permitirá configurar las fechas durante las cuales el bono estará activo. Aquí deberás seleccionar tanto la **fecha inicial** como la **fecha final** para definir el período de vigencia del bono.
* **Botón proveedores:** Este botón Desplegará un listado solo con los proveedores que tienen el Bonus System activo, en este caso se debe visualizar y seleccionar la opción "**ENDORPHINA"**.
* **Botón Productos:** Este botón despegará 2 listas para seleccionar un juego dependiendo el proveedor, en este caso, es necesario volver a seleccionar el proveedor "**ENDORPHINA**", para visualizar los juegos disponibles.

{% hint style="warning" %}
**Nota**: Al configurar los campos "**Proveedores**" y "**Productos**" se desplegará una tabla en la cual debes especificar el porcentaje del bono que asumirá el proveedor.
{% endhint %}

* **Moneda**: Para poder dar uso a los bonos FreeSpin con el proveedor ENDORPHINA, es necesario seleccionar la moneda del país con el que estamos generando el bono, esto activará las siguientes configuraciones.
  * **Valor por ronda:** Este es el monto que tendrá el bono por cada ronda jugada. Al configurar esta opción, es crucial verificar previamente el monto de apuesta permitido en los juegos seleccionados, ya que este debe coincidir exactamente con el valor ingresado en este campo.

{% hint style="danger" %}
**Importante:**

El sistema utiliza una fórmula interna para convertir el monto ingresado a **céntimos**, sin importar la moneda local del país.\
Por defecto:

* **10 unidades internas = 1 céntimo = 0.01 EUR**

**Ejemplo:**

Si se configura el "Valor por ronda" en **20**:

1. El sistema lo multiplica por **100** → `20 × 100 = 2000`
2. Luego aplica la fórmula: `2000 ÷ 10 = 200 céntimos = 2.00 EUR`

Esto significa que cada ronda usará **2.00 EUR** del bono.

Este proceso se aplica igual en todos los países, ya que el sistema hace la conversión a céntimos de euro de forma automática.
{% endhint %}

* **Rondas gratuitas:** En este campo podrás ingresar la cantidad de rondas gratuitas que el usuario podrá jugar con este bono.
* **Jugadores:** En esta configuración, se debe ingresar el ID de cada usuario que tendrá el bono activo. Este proceso requiere cargar un archivo en formato **CSV** con los ID´s correspondientes. El sistema tomará los datos del archivo y activará automáticamente el bono para los jugadores especificados.

{% hint style="info" %}
**Ejemplo:** Si ingresamos un valor de 10 en el campo "**Valor por ronda**", pero el juego tiene una apuesta máxima permitida de 5, el bono no funcionará porque los valores no coinciden.
{% endhint %}

Estas son las configuraciones principales y necesarias para generar un bono FreeSpin con los juegos del proveedor ENDORPHINA, en caso de necesitar información más detallada sobre cómo crear el bono FreeSpin, puedes acceder a la siguiente página:

{% content-ref url="https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}
[FreeSpin](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin)
{% endcontent-ref %}
