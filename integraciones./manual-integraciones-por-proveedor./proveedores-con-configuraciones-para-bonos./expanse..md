---
description: >-
  Aquí encontrarás información importante que se debe tener en cuenta al momento
  de la creación de un bono FreeSpin para EXPANSE.
---

# EXPANSE.

Esta es la visual completa del Bono FreeSpin

<figure><img src="../../.gitbook/assets/image (90).png" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla de la sección FreeSpin.</p></figcaption></figure>

En este caso nos céntratenos solo en las configuraciones necesarias para la configuración de los nuevos juegos integrados por el proveedor EXPANSE.

* **Rango de fechas:** El botón **"Agregar"**, desplegará una opción que te permitirá configurar las fechas durante las cuales el bono estará activo. Aquí deberás seleccionar tanto la **fecha inicial** como la **fecha final** para definir el período de vigencia del bono.
* **Botón proveedores:** Este botón Desplegará un listado solo con los proveedores que tienen el Bonus System activo, en este caso se debe visualizar y seleccionar la opción "**EXPANSE"**.
* **Botón Productos:** Este botón despegará 2 listas para seleccionar un juego dependiendo el proveedor, en este caso, es necesario volver a seleccionar el proveedor "**EXPANSE**", para visualizar los juegos disponibles.

{% hint style="warning" %}
**Nota**: Al configurar los campos "**Proveedores**" y "**Productos**" se desplegará una tabla en la cual debes especificar el porcentaje del bono que asumirá el proveedor.
{% endhint %}

*   **Moneda**: Para poder dar uso a los bonos FreeSpin con el proveedor EXPANSE, es necesario seleccionar la moneda del país con el que estamos generando el bono, esto activará las siguientes configuraciones.

    * **Valor por ronda:** Este es el monto que tendrá el bono por cada ronda jugada. Al configurar esta opción, es crucial verificar previamente el monto de apuesta permitido en los juegos seleccionados, ya que este debe coincidir exactamente con el valor ingresado en este campo.

    <div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si ingresamos un valor de 10 en el campo "<strong>Valor por ronda</strong>", pero el juego tiene una apuesta máxima permitida de 5, el bono no funcionará porque los valores no coinciden.</p></div>

    * **Rondas gratuitas:** En este campo podrás ingresar la cantidad de rondas gratuitas que el usuario podrá jugar con este bono.
    *   **Multiplicador**: Este campo se usa para calcular el **premio máximo que puede ganar el usuario con el bono**. Debes ingresar un **número entero**, ya que este valor se utilizará en las siguientes fórmulas para el cálculo:

        * **Paso 1**: (valor por ronda) × (rondas gratuitas) = valor base
        *   **Paso 2**: (valor base) × (multiplicador) = **premio máximo**<br>

            <div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo</strong>:</p><ul><li>Valor por ronda: 0.20</li><li>Rondas gratuitas: 10</li><li>Multiplicador: 20</li><li><p>Cálculo:</p><ul><li>Paso 1: 0.20 × 10 = 2</li><li>Paso 2: 2 × 20 = 40</li></ul></li></ul><p>El resultado "40" será el <strong>premio máximo</strong> que puede ganar el usuario con este bono.</p></div>


    * **Jugadores:** En esta configuración, se debe ingresar el ID de cada usuario que tendrá el bono activo. Este proceso requiere cargar un archivo en formato **CSV** con los ID´s correspondientes. El sistema tomará los datos del archivo y activará automáticamente el bono para los jugadores especificados.

Estas son las configuraciones principales y necesarias para generar un bono FreeSpin con los juegos del proveedor EXPANSE, en caso de necesitar información más detallada sobre cómo crear el bono FreeSpin, puedes acceder a la siguiente página:

{% content-ref url="https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}
[FreeSpin](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin)
{% endcontent-ref %}

{% hint style="warning" %}
**Nota**: El bono se crea de manera inmediata, pero se asigna entre 2 a 3 minutos.
{% endhint %}

## EXPANSE en plataforma:

Realizaremos el ejemplo desde la plataforma Doradobet desde la siguiente ruta:&#x20;

* **Menú/ Casino/** EXPANS&#x45;**.**

Al seguir esta ruta podrás filtrar solo los juegos disponibles por el proveedor EXPANSE.

<figure><img src="../../.gitbook/assets/image (61).png" alt=""><figcaption><p>Figura #2: Captura de pantalla filtro proveedores.</p></figcaption></figure>
