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
---

# Crear Jackpot

<mark style="color:$info;">Crea y configura un jackpot, definiendo sus reglas, validaciones y condiciones de participación para los usuarios.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Backoffice > Torneos y Bonos > Crear Jackpot

***

### &#x20;2. visualización general

<figure><img src="../../../.gitbook/assets/image (283).png" alt=""><figcaption><p>Figura#1: Captura de pantalla creación de Jackpot.</p></figcaption></figure>

***

### 3. Formulario para la creación de un [jackpot](https://virtualsoft.gitbook.io/untitled/glosario#jackpot)

Configura todos los parámetros necesarios para crear un jackpot, definiendo su comportamiento, reglas de acumulación y criterios de activación.

<table><thead><tr><th width="139">Campo</th><th width="132.06671142578125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Establece el nombre que tendrá el jackpot.</td></tr><tr><td><strong><code>Fecha inicial</code></strong></td><td>Fecha y hora</td><td><p>Indica la fecha y la hora de inicio del jackpot. </p><p>Después de seleccionar la información, se debe hacer clic en el botón "<strong>set</strong>" para guardar la información.</p></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Ingresa la descripción del jackpot.</td></tr><tr><td><strong><code>Order</code></strong></td><td>Numérico</td><td><p>Indica el orden de prioridad que tendrá el jackpot para ser reclamado por los usuarios.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong>  Si tienes tres jackpots con los siguientes valores de orden:</p><ul><li><strong>Jackpot A</strong>: Orden 1</li><li><strong>Jackpot B</strong>: Orden 2</li><li><strong>Jackpot C</strong>: Orden 3</li></ul><p>Para reclamar el premio del <strong>Jackpot</strong> C, primero debes completar y reclamar los premios del <strong>Jackpot</strong> A y luego del <strong>Jackpot</strong> B.</p></div></td></tr><tr><td><strong><code>Destino de saldo</code></strong></td><td>Selección</td><td><p>Establece el tipo de saldo que otorgará el jackpot al jugador ganador. Los tipos de saldo disponibles son los siguientes:</p><ul><li><strong>Saldo recarga:</strong> el premio se acredita como saldo promocional o de recarga, el cual puede estar sujeto a condiciones de uso, apuestas mínimas o restricciones definidas.</li><li><strong>Saldo retiro:</strong> el premio se acredita como saldo disponible para retiro, permitiendo al usuario utilizarlo o retirarlo según las políticas y validaciones establecidas.</li></ul></td></tr><tr><td><strong><code>Tamaño del Jackpot</code></strong></td><td>Lista desplegable</td><td><p>Selecciona el tamaño del jackpot, eligiendo una de las siguientes opciones: <strong>Pequeño, Mediano, Grande o Mega</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Esta configuración es <strong>obligatoria</strong> y permite categorizar el jackpot. Su finalidad es únicamente clasificarlo, por lo que no influye en su funcionamiento ni en su operación.</p></div></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Selecciona la moneda correspondiente al país para el cual se está configurando el jackpot.</td></tr><tr><td><strong><code>Tipo de caída por cantidad de apuesta</code></strong></td><td>Configuración</td><td>Define la cantidad mínima y máxima de apuestas requeridas para habilitar la caída (<em>finalización y entrega</em>) normal del jackpot.</td></tr><tr><td><strong><code>Reiniciar</code></strong></td><td>Selección</td><td>Establece si el jackpot se reiniciará de manera automática tras caer el premio.</td></tr></tbody></table>

* **`Productos`**

Seleccionar una o varias [verticales](https://virtualsoft.gitbook.io/untitled/glosario#vertical) y definir los parámetros de participación, para posteriormente elegir los productos que aplicarán para el jackpot.

{% tabs %}
{% tab title="Deportivas" %}
Habilitar la participación de **apuestas deportivas** en el jackpot, configurando los parámetros de validación y seleccionando los segmentos correspondientes (_deportes, mercados, ligas y partidos_) que definirán los **productos incluidos**.

<table><thead><tr><th width="186.8887939453125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor inicial</code></strong></td><td>Monto base que esta vertical aporta al pozo del jackpot al activarla. Este valor se suma al monto total del jackpot.</td></tr><tr><td><strong><code>Apuesta mínima</code></strong></td><td>Define el valor mínimo que debe tener una apuesta deportiva para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Apuesta máxima</code></strong></td><td>Establece el valor máximo  permitido que debe tener una apuesta deportiva para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Porcentaje de acumulación</code></strong></td><td>Define el porcentaje de cada apuesta en deportivas que se destinará al fondo del jackpot.</td></tr></tbody></table>

#### **⚙️ Configuración de segmentos de deportivas**

Configura los segmentos de deportivas que serán válidos para la acumulación del jackpot

{% tabs %}
{% tab title="Deporte" %}
Define los deportes cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (11).png" alt=""><figcaption><p>Figura#2: Captura de Pantalla deportes.</p></figcaption></figure>

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="100.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Deportes</code></strong></td><td>Texto</td><td>Ingrese los IDs de los deportes que aportarán al acumulado del jackpot. Para registrar múltiples deportes, ingrese los identificadores separados por comas (,). Las apuestas realizadas en los deportes configurados sumarán automáticamente al valor acumulado del jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="Mercados" %}
Permite definir los mercados cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (12).png" alt=""><figcaption><p>Figura#3: Captura de Pantalla mercados.</p></figcaption></figure>

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="100.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mercados</code></strong></td><td>Texto</td><td>Ingrese los IDs de los mercados que aportarán al acumulado del jackpot. Para registrar múltiples mercados, ingrese los identificadores separados por comas (,). Las apuestas realizadas en los mercados configurados sumarán automáticamente al valor acumulado del jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="Ligas" %}
Permite definir las ligas cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (13).png" alt=""><figcaption><p>Figura#4: Captura de Pantalla ligas.</p></figcaption></figure>

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="100.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ligas</code></strong></td><td>Texto</td><td>Ingrese los IDs de las ligas que aportarán al acumulado del jackpot. Para registrar múltiples ligas, ingrese los identificadores separados por comas (,). Las apuestas realizadas en las ligas configuradas sumarán automáticamente al valor acumulado del jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="Partidos" %}
&#x20;Permite definir los partidos cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (14).png" alt=""><figcaption><p>Figura#5: Captura de Pantalla partidos.</p></figcaption></figure>

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="100.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partidos</code></strong></td><td>Texto</td><td>Ingrese los IDs de los partidos que aportarán al acumulado del jackpot. Para registrar múltiples partidos, ingrese los identificadores separados por comas (,). Las apuestas realizadas en los partidos configurados sumarán automáticamente al valor acumulado del jackpot.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Casino" %}
Permite habilitar la participación de **apuestas de casino** en el jackpot, configurando los parámetros de validación y seleccionando los segmentos correspondientes (_proveedores, categorías y juegos_) que definirán los productos incluidos.

<table><thead><tr><th width="186.8887939453125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor inicial</code></strong></td><td>Monto base que esta vertical aporta al pozo del jackpot al activarla. Este valor se suma al monto total del jackpot.</td></tr><tr><td><strong><code>Apuesta mínima</code></strong></td><td>Define el valor mínimo que debe tener una apuesta de casino para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Apuesta máxima</code></strong></td><td>Define el valor máximo  permitido que debe tener una apuesta de casino para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Porcentaje de acumulación</code></strong></td><td>Define el porcentaje de cada apuesta de casino que se destinará al fondo del jackpot.</td></tr></tbody></table>

#### **⚙️ Configuración de segmentos de casino**

Configura los segmentos de casino que serán validos para la acumulación del jackpot

{% tabs %}
{% tab title="Categorías" %}
Permite definir las categorías de casino cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (15).png" alt=""><figcaption><p>Figura #6: Captura de pantalla Categorias. </p></figcaption></figure>

<table><thead><tr><th width="117.03704833984375">Campo</th><th width="120.148193359375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varias categorias participantes en el jackpot</td></tr></tbody></table>
{% endtab %}

{% tab title="Proveedores" %}
Permite definir los proveedores cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (16).png" alt=""><figcaption><p>Figura #7: Captura de pantalla Proveedores. </p></figcaption></figure>

<table><thead><tr><th width="124.4444580078125">Campo</th><th width="116.44451904296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varios proveedores participantes cuyos juegos serán validos en el jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="Productos" %}
Permite definir los productos junto con su proveedor cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (17).png" alt=""><figcaption><p>Figura #8: Captura de pantalla Productos. </p></figcaption></figure>

<table><thead><tr><th width="119.25927734375">Campo</th><th width="124.5926513671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar uno o varios proveedores cuyos juegos estarán disponibles para participar en el jackpot.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Permite elegir los juegos específicos del proveedor seleccionado que serán válidos para acumular y participar en el jackpot.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Casino en vivo" %}
Permite habilitar la participación de **apuestas de casino en vivo** en el jackpot, configurando los parámetros de validación y seleccionando los segmentos correspondientes (_proveedores, categorías y juegos_) que definirán los productos incluidos.

<table><thead><tr><th width="186.8887939453125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor inicial</code></strong></td><td>Monto base que esta vertical aporta al pozo del jackpot al activarla. Este valor se suma al monto total del jackpot.</td></tr><tr><td><strong><code>Apuesta mínima</code></strong></td><td>Define el valor mínimo que debe tener una apuesta de casino en vivo para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Apuesta máxima</code></strong></td><td>Define el valor máximo  permitido que debe tener una apuesta de casino en vivo para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Porcentaje de acumulación</code></strong></td><td>Define el porcentaje de cada apuesta de casino en vivo que se destinará al fondo del jackpot.</td></tr></tbody></table>

#### **⚙️ Configuración de segmentos de casino en vivo**

Configura los segmentos de casino en vivo que serán validos para la acumulación del jackpot

{% tabs %}
{% tab title="Categorías" %}
Permite definir las categorías de casino cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (15).png" alt=""><figcaption><p>Figura #9: Captura de pantalla Categorias. </p></figcaption></figure>

<table><thead><tr><th width="117.03704833984375">Campo</th><th width="120.148193359375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varias categorias participantes en el jackpot</td></tr></tbody></table>
{% endtab %}

{% tab title="Proveedores" %}
Permite definir los proveedores cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (16).png" alt=""><figcaption><p>Figura #10: Captura de pantalla Proveedores. </p></figcaption></figure>

<table><thead><tr><th width="124.4444580078125">Campo</th><th width="116.44451904296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varios proveedores participantes cuyos juegos serán validos en el jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="Productos" %}
Permite definir los productos junto con su proveedor cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (17).png" alt=""><figcaption><p>Figura #11: Captura de pantalla Productos. </p></figcaption></figure>

<table><thead><tr><th width="119.25927734375">Campo</th><th width="124.5926513671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar uno o varios proveedores cuyos juegos estarán disponibles para participar en el jackpot.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Permite elegir los juegos específicos del proveedor seleccionado que serán válidos para acumular y participar en el jackpot.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Virtuales" %}
Permite habilitar la participación de **apuestas virtuales** en el jackpot, configurando los parámetros de validación y seleccionando los segmentos correspondientes (_proveedores, categorías y juegos_) que definirán los productos incluidos.

<table><thead><tr><th width="186.8887939453125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor inicial</code></strong></td><td>Monto base que esta vertical aporta al pozo del jackpot al activarla. Este valor se suma al monto total del jackpot.</td></tr><tr><td><strong><code>Apuesta mínima</code></strong></td><td>Define el valor mínimo que debe tener una apuesta virtual para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Apuesta máxima</code></strong></td><td>Define el valor máximo  permitido que debe tener una apuesta virtual para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Porcentaje de acumulación</code></strong></td><td>Define el porcentaje de cada apuesta virtual que se destinará al fondo del jackpot.</td></tr></tbody></table>

#### **⚙️ Configuración de segmentos de virtuales**

Configura los segmentos de virtuales que serán validos para la acumulación del jackpot

{% tabs %}
{% tab title="Categorías" %}
Permite definir las categorías de virtuales cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (15).png" alt=""><figcaption><p>Figura #12: Captura de pantalla Categorias. </p></figcaption></figure>

<table><thead><tr><th width="117.03704833984375">Campo</th><th width="120.148193359375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varias categorias participantes en el jackpot</td></tr></tbody></table>
{% endtab %}

{% tab title="Proveedores" %}
Permite definir los proveedores cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (16).png" alt=""><figcaption><p>Figura #13: Captura de pantalla Proveedores. </p></figcaption></figure>

<table><thead><tr><th width="124.4444580078125">Campo</th><th width="116.44451904296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varios proveedores participantes cuyos juegos serán validos en el jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="Productos" %}
Permite definir los productos junto con su proveedor cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (17).png" alt=""><figcaption><p>Figura #14: Captura de pantalla Productos. </p></figcaption></figure>

<table><thead><tr><th width="119.25927734375">Campo</th><th width="124.5926513671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar uno o varios proveedores cuyos juegos estarán disponibles para participar en el jackpot.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Permite elegir los juegos específicos del proveedor seleccionado que serán válidos para acumular y participar en el jackpot.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}

* **`Productos excluidos`**

Selecciona los productos por  [verticales](https://virtualsoft.gitbook.io/untitled/glosario#vertical) que serán excluidos de la participación en el jackpot. Las apuestas realizadas sobre los elementos configurados no sumarán al acumulado ni participarán en la dinámica del jackpot.

{% tabs %}
{% tab title="Deportivas" %}
Selecciona los productos de los segmentos en la sección de deportivas (_deportes, mercados, ligas y partidos_) que serán **excluidos** del jackpot.

{% tabs %}
{% tab title="Deporte" %}
Permite seleccionar los deportes que serán excluidos de la participación en el jackpot.

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="100.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Deportes</code></strong></td><td>Texto</td><td>Ingrese los IDs de los deportes que serán excluidos separados por comas ( <strong>,</strong> ).</td></tr></tbody></table>
{% endtab %}

{% tab title="Mercados" %}
Permite seleccionar los mercados que serán excluidos de la participación en el jackpot.

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="100.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mercados</code></strong></td><td>Texto</td><td>Ingrese los IDs de los mercados que serán excluidos separados por comas ( <strong>,</strong> ).</td></tr></tbody></table>
{% endtab %}

{% tab title="Ligas" %}
Permite seleccionar las ligas que serán excluidas de la participación en el jackpot.

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="100.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ligas</code></strong></td><td>Texto</td><td>Ingrese los IDs de las ligas que serán excluidas separados por comas ( <strong>,</strong> ).</td></tr></tbody></table>
{% endtab %}

{% tab title="Partidos" %}
Permite seleccionar los partidos que serán excluidos de la participación en el jackpot.

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="100.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partidos</code></strong></td><td>Texto</td><td>Ingrese los IDs de los partidos que serán excluidos separados por comas ( <strong>,</strong> ).</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Casino" %}
Selecciona los segmentos de casino (_proveedores, categorías y productos_) cuyos productos serán excluidos de la participación en el jackpot.

#### **⚙️ Configuración de segmentos de casino**

Configura los segmentos de casino que serán excluidos del jackpot

{% tabs %}
{% tab title="Categorías" %}
Permite definir las categorías de casino que no aplicarán para el jackpot.

<table><thead><tr><th width="117.03704833984375">Campo</th><th width="120.148193359375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varias categorias que serán excluidas en el jackpot</td></tr></tbody></table>
{% endtab %}

{% tab title="Proveedores" %}
Permite definir los proveedores de casino que no aplicarán para el jackpot.

<table><thead><tr><th width="124.4444580078125">Campo</th><th width="128.44451904296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar uno o varios proveedores cuyos juegos serán excluidos de la participación en el jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="Productos" %}
Define los productos junto con su proveedor que serán excluidos en el jackpot.

<table><thead><tr><th width="119.25927734375">Campo</th><th width="124.5926513671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona un proveedor específico del cual se excluirán juegos del jackpot.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Establece los juegos del proveedor elegido que serán excluidos de la participación en el jackpot.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Casino en vivo" %}
Permite seleccionar los segmentos de casino en vivo (_proveedores, categorías y productos_) cuyos productos serán excluidos de la participación en el jackpot.

#### **⚙️ Configuración de segmentos de casino en vivo**

Configura los segmentos de casino que serán excluidos del jackpot

{% tabs %}
{% tab title="Categorías" %}
Permite definir las categorías de casino en vivo que no aplicarán para el jackpot.

<table><thead><tr><th width="117.03704833984375">Campo</th><th width="120.148193359375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varias categorias que serán excluidas en el jackpot</td></tr></tbody></table>
{% endtab %}

{% tab title="Proveedores" %}
Permite definir los proveedores de casino en vivo que no aplicarán para el jackpot.

<table><thead><tr><th width="124.4444580078125">Campo</th><th width="116.44451904296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar uno o varios proveedores cuyos juegos serán excluidos de la participación en el jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="Productos" %}
Permite definir los productos junto con su proveedor que serán excluidos en el jackpot.

<table><thead><tr><th width="119.25927734375">Campo</th><th width="124.5926513671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona un proveedor específico del cual se excluirán juegos del jackpot.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Escoge los juegos del proveedor elegido que serán excluidos de la participación en el jackpot.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Virtuales" %}
Selecciona los segmentos de apuestas virtuales (_proveedores, categorías y productos_) cuyos productos serán excluidos del jackpot.

#### **⚙️ Configuración de segmentos de virtuales**

Configura los segmentos de virtuales que serán excluidos de participación en el jackpot

{% tabs %}
{% tab title="Categorías" %}
Permite definir las categorías virtuales que no aplicarán para el jackpot.

<table><thead><tr><th width="117.03704833984375">Campo</th><th width="120.148193359375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varias categorias que serán excluidas en el jackpot</td></tr></tbody></table>
{% endtab %}

{% tab title="Proveedores" %}
Permite definir los proveedores de virtuales que no aplicarán para el jackpot.

<table><thead><tr><th width="124.4444580078125">Campo</th><th width="116.44451904296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar uno o varios proveedores cuyos juegos serán excluidos de la participación en el jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="Productos" %}
Define los productos junto con su proveedor que serán excluidos en el jackpot.

<table><thead><tr><th width="119.25927734375">Campo</th><th width="124.5926513671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar un proveedor específico del cual se excluirán juegos del jackpot.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Selecciona los juegos del proveedor elegido que serán excluidos de la participación en el jackpot.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}

***

<details>

<summary><strong>Información del jackpot</strong></summary>

{% hint style="warning" %}
**Nota:** Este campo no permite el uso de emojis, ya que pueden generar errores en el sistema.
{% endhint %}

<table><thead><tr><th width="143.14813232421875">Campo</th><th width="83.8148193359375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Inserta HTML</code></strong></td><td>Texto </td><td>Ingresa y edita el contenido informativo que se mostrará en el pop-up del jackpot, permite agregar texto personalizado y aplicar formatos básicos como negrilla, cursiva, subrayado, alineación, listas y color de texto, sin necesidad de utilizar código HTML.</td></tr><tr><td><strong><code>Ver</code></strong></td><td>Botón</td><td>Previsualiza como se verá la información del jackpot.</td></tr></tbody></table>

</details>

<details>

<summary><strong>Opciones avanzadas</strong></summary>

Configura y personaliza opciones avanzadas para adaptar el jackpot a necesidades específicas.

<table><thead><tr><th width="174.00006103515625">Campo</th><th width="106.00006103515625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mostrar signo moneda contador</code></strong></td><td>Selector</td><td>Establece si el contador del jackpot se visualizará con el signo de la moneda correspondiente.</td></tr><tr><td><strong><code>Estilo contador</code></strong></td><td>Selector</td><td><p>Defina si el contador se mostrará en números <strong>enteros</strong> o <strong>decimales</strong>. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> la visualización del contador se actualizará automáticamente cada 30 segundos.</p></div></td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL</td><td>Ingresa la URL principal del jackpot.</td></tr><tr><td><strong><code>Imagen 2</code></strong></td><td>URL</td><td>Ingresa la URL de la imagen de fondo que tendrá el contador del jackpot.</td></tr><tr><td><strong><code>Gif</code></strong></td><td>URL</td><td>Ingresa la URL del GIF que se visualizará sobre las dos imágenes anteriores.</td></tr><tr><td><strong><code>Video desktop</code></strong></td><td>URL</td><td>Ingresa la URL del video que se mostrará al usuario cuando gane el jackpot desde un dispositivo de escritorio.</td></tr><tr><td><strong><code>Video mobile</code></strong></td><td>URL</td><td>Ingresa la URL del video que se mostrará al usuario cuando gane el jackpot desde un dispositivo móvil.</td></tr></tbody></table>

</details>

***

* **`Notificaciones automáticas`**

Configura la notificación automática que se enviará al usuario ganador del jackpot, seleccionando alguna de las siguientes opciones:

{% tabs %}
{% tab title="Email" %}
La notificación le llegará al usuario ganador por su correo electrónico.

<table><thead><tr><th width="140.66668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Asunto</code></strong></td><td>Agrega el asunto que tendrá el correo.</td></tr><tr><td><strong><code>Campo HTML</code></strong></td><td>Inserta el cuerpo del correo; puedes ingresar texto o un HTML indicándole al usuario que ha ganado el jackpot.</td></tr><tr><td><strong><code>Ver</code></strong></td><td>Previsualiza como se verá la información del jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="Pop up" %}
La notificación le llegará al usuario por medio de una ventana emergente en la plataforma.

<table><thead><tr><th width="139.83331298828125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Texto</code></strong></td><td>Ingresa el mensaje que verá el usuario en el pop-up.</td></tr><tr><td><strong><code>URL</code></strong></td><td>Establece la URL a la que deseas redirigir a los usuarios cuando hagan clic en el pop-up.</td></tr></tbody></table>
{% endtab %}

{% tab title="Inbox" %}
La notificación llegará al usuario por medio de la bandeja de entrada de la plataforma.

<table><thead><tr><th width="143.16668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Asunto</code></strong></td><td>Ingresa el asunto de la notificación.</td></tr><tr><td><strong><code>Campo HTML</code></strong></td><td>Establece el contenido del mensaje de notificación, ya sea en texto o HTML, que informará al usuario que ha ganado el jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="SMS" %}
La notificación llegará al usuario de manera automática por medio de SMS a su numero de telefono.

<table><thead><tr><th width="141.66668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mensaje</code></strong></td><td>Ingresa el mensaje que recibirá el usuario.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

<details>

<summary><strong>Ver términos y condiciones.</strong></summary>

Visualiza y edita toda la información y configuraciones definidas para el jackpot, incluyendo reglas, condiciones, restricciones y contenido informativo asociado.

</details>

Para finalizar el proceso debes dar clic en el botón **"Crear Jackpot"**. Esto guardará la configuración y activará el jackpot para los usuarios.

***

### 4. Validaciones y Reglas de Negocio

* Los campos que tengan un <mark style="color:red;">\*</mark> son obligatorios para la creación del Jackpot.
* Para visualizar la información relacionada con el jackpot, incluyendo configuraciones, reglas, términos y condiciones y el listado de usuarios participantes, accede a este reporte. [jackpot..md](../visualizar-eventos./jackpot..md "mention").

***

### 5. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="116">Versión</th><th width="125">Fecha</th><th width="159">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>23/07/2025</td><td>David Velasquez</td><td>Actualización de formato.</td></tr><tr><td>1.1</td><td>27/04/2026</td><td>Karol Navia</td><td>Añadir campo <strong><code>Tamaño del Jackpot</code></strong></td></tr><tr><td>1.2</td><td>27/05/2026</td><td>Karol Navia</td><td>Cambio de funcionamiento del campo <strong><code>Información del Jackpot</code></strong></td></tr></tbody></table>

</details>
