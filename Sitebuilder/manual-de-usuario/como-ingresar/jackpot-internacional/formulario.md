---
description: >-
  Permite crear un jackpot definiendo sus características, configuraciones,
  condiciones y contenido gráfico en diferentes secciones.
---

# Formulario

### **1. Acceso al Módulo**

**Ruta:** Site Builder > Jackpot > Formulario

***

### 2. Creación del [jackpot internacional](https://virtualsoft.gitbook.io/untitled/glosario#jackpot)

Permite crear un jackpot y configurarlo de forma estructurada mediante diferentes secciones.

{% tabs %}
{% tab title="Sección 1" %}
#### 2.1. Configuración general

Permite configurar los aspectos generales del jackpot definiendo los siguientes campos obligatorios:

#### Visualización

<figure><img src="../../../.gitbook/assets/image (359).png" alt=""><figcaption><p>Figura #1: captura de pantalla sección 1 formulario jackpot internacional</p></figcaption></figure>

<table><thead><tr><th width="181.5">Campo</th><th width="108.1666259765625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Permite ingresar el nombre del jackpot.</td></tr><tr><td><strong><code>Fecha Inicial</code></strong></td><td>Fecha</td><td>Selecciona la fecha en la que iniciará el jackpot para los usuarios.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Registra información interna del jackpot, como el objetivo de la campaña, su contexto o consideraciones operativas. Este contenido es solo de uso administrativo y <strong>no es visible para los usuarios</strong>.</td></tr><tr><td><strong><code>Operaciones</code></strong></td><td>Lista desplegable</td><td>Selecciona múltiples operaciones (<em><strong>Partners y países</strong></em>) donde el jackpot estará activo.</td></tr><tr><td><strong><code>Moneda Base</code></strong></td><td>Lista desplegable</td><td>Define la moneda en la que se registrarán todos los movimientos del jackpot. Este campo es de selección única (<em>Dólar o Euro</em>).</td></tr><tr><td><strong><code>Destino del Saldo</code></strong></td><td>Lista desplegable</td><td>Define si el saldo acumulado del jackpot será entregado al ganador como <a href="https://virtualsoft.gitbook.io/untitled/glosario#saldo-recarga">saldo recarga</a> o como <a href="https://virtualsoft.gitbook.io/untitled/glosario#saldo-retiro">saldo retiro</a>.</td></tr><tr><td><strong><code>Mínima Cantidad de Apuestas</code></strong></td><td>Numérico</td><td>Permite definir el numero <strong>mínimo de apuestas acumuladas</strong> necesarias para su caída (<em>Finalización y entrega del premio</em>).</td></tr><tr><td><strong><code>Máxima Cantidad de Apuestas</code></strong></td><td>Numérico</td><td><p>Define el número <strong>máximo de apuestas</strong> que puede acumular el jackpot.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al alcanzarse este tope, el sistema detiene la acumulación y ejecuta la acción configurada, como la caída del jackpot o la lógica establecida por la plataforma.</p></div></td></tr><tr><td><strong><code>Reiniciar</code></strong></td><td>Selección</td><td>Determina si el jackpot debe reiniciarse automáticamente después de caer el premio. Según la opción seleccionada, se habilitan campos adicionales que definen el comportamiento de caída del jackpot. <a data-mention href="formulario.md#opciones-del-campo-reiniciar">#opciones-del-campo-reiniciar</a></td></tr></tbody></table>

<details>

<summary>🔽 Opciones del campo <strong><code>Reiniciar</code></strong></summary>

* **Opción: Si**

El jackpot se reinicia automáticamente cada vez que cae, hasta alcanzar el número de series configurado.

<table><thead><tr><th width="100.148193359375">Campo</th><th width="103.11114501953125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Series</code></strong></td><td>Numérico</td><td><p>Número de veces que debe caer el jackpot antes de desactivarse automáticamente.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El valor <strong>0</strong> indica <strong>series infinitas</strong>: el jackpot se reiniciará sin límite hasta ser desactivado manualmente.</p></div></td></tr></tbody></table>

* **Opción: No**

El jackpot cae una única vez dentro del periodo configurado, sin reinicio.

<table><thead><tr><th width="140.888916015625">Campo</th><th width="108.29632568359375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha Final</code></strong></td><td>Calendario</td><td>Fecha límite de vigencia del jackpot, al alcanzarla el sistema ejecuta la caída del jackpot.</td></tr><tr><td><strong><code>Mínima cantidad de apuestas fecha limite</code></strong></td><td>Numérico</td><td>Cantidad mínima de apuestas acumuladas a partir de la cual el jackpot puede caer al llegar la fecha final.</td></tr><tr><td><strong><code>Máxima cantidad de apuestas fecha limite</code></strong></td><td>Numérico</td><td>Cantidad máxima de apuestas acumuladas dentro de la cual el jackpot debe caer al llegar la fecha final.</td></tr></tbody></table>

{% hint style="warning" %}
**Notas:**&#x20;

* Al llegar la Fecha Final, el sistema ejecuta la caída del jackpot aplicando las reglas del rango **Mínima - Máxima** configurado en _Caída en Fecha Límite por cantidad de apuestas_.
* La caída es **obligatoria** en la **`Fecha Final`**, incluso si las apuestas acumuladas no se encuentran dentro del **rango general**.
{% endhint %}

</details>

> ⚠️**Importante:** Después de completar todos los campos obligatorios, haz clic en el botón **“**<img src="../../../.gitbook/assets/image (31).png" alt="" data-size="line">**”** ubicado en la parte inferior derecha para avanzar a la **sección 2** del formulario.

<p align="center"><a href="formulario.md#seccion-2" class="button primary" data-icon="chevron-right">Continuar</a></p>
{% endtab %}

{% tab title="Sección 2" %}
#### 2.2. Información del jackpot

Permite gestionar la información del jackpot para cada operación (_Partner y país_), definiendo el contenido que verá el usuario al abrir el detalle del jackpot desde el ícono de información <img src="../../../.gitbook/assets/image (342).png" alt="" data-size="line">.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (358).png" alt=""><figcaption><p>Figura #2: captura de pantalla sección 2 formulario jackpot internacional</p></figcaption></figure>

<table><thead><tr><th width="190.66668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Agregar imágenes</code></strong></td><td>Incerta imágenes dentro del contenido del editor para complementar y enriquecer la descripción del jackpot mostrada al usuario.</td></tr><tr><td><strong><code>Agregar videos</code></strong></td><td>Agrega el enlace de un video en formato MP4, YouTube u otras plataformas compatibles para complementar la información del jackpot.</td></tr><tr><td><strong><code>Agregar links</code></strong></td><td>Añade enlaces a sitios externos o recursos internos desde el editor.</td></tr><tr><td><strong><code>Estilos de texto</code></strong></td><td>Aplica diferentes estilos al texto.</td></tr><tr><td><strong><code>Agregar viñetas</code></strong></td><td>Estructura información mediante listas con viñetas.</td></tr><tr><td><strong><code>Agregar emojis</code></strong></td><td>Incerta emojis dentro del contenido.</td></tr><tr><td><strong><code>Agregar tablas</code></strong></td><td>Permite construir y editar tablas directamente en el editor de texto.</td></tr></tbody></table>

#### 🔄 Navegación entre secciones

> Para **avanzar** a la siguiente sección, haz clic en el botón **“**<img src="../../../.gitbook/assets/image (32).png" alt="" data-size="line">**”** ubicado en la parte inferior derecha.\
> Si necesitas **regresar** a la sección anterior, utiliza el botón **“**<img src="../../../.gitbook/assets/image (27).png" alt="" data-size="line">**”** ubicado en la parte inferior izquierda.

<p align="right"><a href="formulario.md#seccion-3" class="button primary" data-icon="chevron-right">Continuar</a></p>
{% endtab %}

{% tab title="Sección 3" %}
#### 2.3. Configuración de productos participantes

Permite seleccionar una o varias [verticales](https://virtualsoft.gitbook.io/untitled/glosario#vertical) por operación (_partner y país_), configurar sus parámetros de participación y elegir los productos que aplicarán al jackpot según la vertical seleccionada.

{% hint style="warning" %}
**Nota:** La **selección de productos** es opcional. Si no se elige ninguno, el sistema asumirá que **todos los productos de la vertical participan automáticamente**. También podrás excluir productos específicos en la siguiente sección.
{% endhint %}

#### Visualización

<figure><img src="../../../.gitbook/assets/image (361).png" alt=""><figcaption><p>Figura #3: captura de pantalla sección 3 formulario </p></figcaption></figure>

{% tabs %}
{% tab title="Deportivas" %}
Permite habilitar la participación de **apuestas deportivas** en el jackpot, configurando los parámetros de validación y seleccionando los segmentos correspondientes (_deportes, mercados, ligas y partidos_) que definirán los **productos incluidos**.

{% hint style="warning" %}
**Nota:** Todos los campos numéricos permiten ingresar valores decimales positivos utilizando punto (.) como separador decimal, con un máximo de 2 decimales.
{% endhint %}

<table><thead><tr><th width="186.8887939453125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor inicial</code></strong></td><td>Indica el <strong>monto base</strong> que <strong>esta vertical</strong> aporta al pozo del jackpot al activarla. Este valor se suma al monto total del jackpot.</td></tr><tr><td><strong><code>Valor inicial repeticiones</code></strong></td><td><p>Campo numérico (<em>opcional</em>) que permite establecer el monto con el que comenzará el jackpot cada vez que se reinicie.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo es opcional y solo se muestra cuando la opción de <strong>Reiniciar</strong> está activada.</p></div></td></tr><tr><td><strong><code>Apuesta mínima</code></strong></td><td>Define el valor mínimo que debe tener una apuesta deportiva para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Apuesta máxima</code></strong></td><td>Define el valor máximo  permitido que debe tener una apuesta deportiva para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Porcentaje de acumulación</code></strong></td><td>Define el porcentaje de cada apuesta en deportivas que se destinará al fondo del jackpot.</td></tr></tbody></table>

#### **Configuración de segmentos de deportivas**

Configura los segmentos de deportivas que serán validos para la acumulación del jackpot

{% tabs %}
{% tab title="Deporte" %}
Permite definir los deportes cuyas apuestas serán consideradas para el jackpot.

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="100.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Deportes</code></strong></td><td>Texto</td><td>Ingrese los IDs de los deportes participantes separados por comas ( <strong>,</strong> ).</td></tr></tbody></table>
{% endtab %}

{% tab title="Mercados" %}
Permite definir los mercados cuyas apuestas serán consideradas para el jackpot.

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="100.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mercados</code></strong></td><td>Texto</td><td>Ingrese los IDs de los mercados participantes separados por comas ( <strong>,</strong> ).</td></tr></tbody></table>
{% endtab %}

{% tab title="Ligas" %}
Permite definir las ligas cuyas apuestas serán consideradas para el jackpot.

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="100.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ligas</code></strong></td><td>Texto</td><td>Ingrese los IDs de las ligas participantes separados por comas ( <strong>,</strong> ).</td></tr></tbody></table>
{% endtab %}

{% tab title="Partidos" %}
&#x20;Permite definir los partidos cuyas apuestas serán consideradas para el jackpot.

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="100.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partidos</code></strong></td><td>Texto</td><td>Ingrese los IDs de los partidos participantes separados por comas ( <strong>,</strong> ).</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Casino" %}
Permite habilitar la participación de **apuestas de casino** en el jackpot, configurando los parámetros de validación y seleccionando los segmentos correspondientes (_proveedores, categorías y juegos_) que definirán los productos incluidos.

{% hint style="warning" %}
**Nota:** Todos los campos numéricos permiten ingresar valores decimales positivos utilizando punto (.) como separador decimal, con un máximo de 2 decimales.
{% endhint %}

<table><thead><tr><th width="186.8887939453125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor inicial</code></strong></td><td>Indica el <strong>monto base</strong> que <strong>esta vertical</strong> aporta al pozo del jackpot al activarla. Este valor se suma al monto total del jackpot.</td></tr><tr><td><strong><code>Valor inicial repeticiones</code></strong></td><td><p>Campo numérico opcional que permite establecer el monto con el que comenzará el jackpot cada vez que se reinicie.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo es opcional y solo se muestra cuando la opción de <strong>Reiniciar</strong> está activada.</p></div></td></tr><tr><td><strong><code>Apuesta mínima</code></strong></td><td>Define el valor mínimo que debe tener una apuesta de casino para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Apuesta máxima</code></strong></td><td>Define el valor máximo  permitido que debe tener una apuesta de casino para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Porcentaje de acumulación</code></strong></td><td>Define el porcentaje de cada apuesta de casino que se destinará al fondo del jackpot.</td></tr></tbody></table>

#### **Configuración de segmentos de casino**

Configura los segmentos de casino que serán validos para la acumulación del jackpot

{% hint style="warning" %}
**Nota:** Si no existen categorías, proveedores o productos activos configurados para la operación, el selector se mostrará vacío junto con un **mensaje informativo** indicando la ausencia de elementos disponibles.

En este caso, será necesario **revisar y habilitar la configuración** correspondiente en el [**Backoffice**](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos-2) para que los elementos puedan **visualizarse en el selector**.
{% endhint %}

{% tabs %}
{% tab title="Categorías" %}
Permite definir las categorías de casino cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (343).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="117.03704833984375">Campo</th><th width="120.148193359375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varias categorias participantes en el jackpot</td></tr></tbody></table>
{% endtab %}

{% tab title="Proveedores" %}
Permite definir los proveedores cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (344).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="124.4444580078125">Campo</th><th width="116.44451904296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varios proveedores participantes cuyos juegos serán validos en el jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="Productos" %}
Permite definir los productos junto con su proveedor cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (345).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="119.25927734375">Campo</th><th width="124.5926513671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar uno o varios proveedores cuyos juegos estarán disponibles para participar en el jackpot.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Lista desplegable</td><td>Permite elegir los juegos específicos de los proveedores seleccionados que serán válidos para acumular y participar en el jackpot.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Casino en vivo" %}
Permite habilitar la participación de **apuestas de casino en vivo** en el jackpot, configurando los parámetros de validación y seleccionando los segmentos correspondientes (_proveedores, categorías y juegos_) que definirán los productos incluidos.

{% hint style="warning" %}
**Nota:** Todos los campos numéricos permiten ingresar valores decimales positivos utilizando punto (.) como separador decimal, con un máximo de 2 decimales.
{% endhint %}

<table><thead><tr><th width="186.8887939453125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor inicial</code></strong></td><td>Indica el <strong>monto base</strong> que <strong>esta vertical</strong> aporta al pozo del jackpot al activarla. Este valor se suma al monto total del jackpot.</td></tr><tr><td><strong><code>Valor inicial repeticiones</code></strong></td><td><p>Campo numérico opcional que permite establecer el monto con el que comenzará el jackpot cada vez que se reinicie.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo es opcional y solo se muestra cuando la opción de <strong>Reiniciar</strong> está activada.</p></div></td></tr><tr><td><strong><code>Apuesta mínima</code></strong></td><td>Define el valor mínimo que debe tener una apuesta de casino en vivo para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Apuesta máxima</code></strong></td><td>Define el valor máximo  permitido que debe tener una apuesta de casino en vivo para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Porcentaje de acumulación</code></strong></td><td>Define el porcentaje de cada apuesta de casino en vivo que se destinará al fondo del jackpot.</td></tr></tbody></table>

#### **Configuración de segmentos de casino en vivo**

Configura los segmentos de casino en vivo que serán validos para la acumulación del jackpot

{% hint style="warning" %}
**Nota:** Si no existen categorías, proveedores o productos activos configurados para la operación, el selector se mostrará vacío junto con un **mensaje informativo** indicando la ausencia de elementos disponibles.

En este caso, será necesario **revisar y habilitar la configuración** correspondiente en el [**Backoffice**](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos-2) para que los elementos puedan **visualizarse en el selector**.
{% endhint %}

{% tabs %}
{% tab title="Categorías" %}
Permite definir las categorías de casino cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (343).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="117.03704833984375">Campo</th><th width="120.148193359375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varias categorias participantes en el jackpot</td></tr></tbody></table>
{% endtab %}

{% tab title="Proveedores" %}
Permite definir los proveedores cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (344).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="124.4444580078125">Campo</th><th width="116.44451904296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varios proveedores participantes cuyos juegos serán validos en el jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="Productos" %}
Permite definir los productos junto con su proveedor cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (345).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="119.25927734375">Campo</th><th width="124.5926513671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar uno o varios proveedores cuyos juegos estarán disponibles para participar en el jackpot.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Lista desplegable</td><td>Permite elegir los juegos específicos de los proveedores seleccionados que serán válidos para acumular y participar en el jackpot.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Virtuales" %}
Permite habilitar la participación de **apuestas virtuales** en el jackpot, configurando los parámetros de validación y seleccionando los segmentos correspondientes (_proveedores, categorías y juegos_) que definirán los productos incluidos.

{% hint style="warning" %}
**Nota:** Todos los campos numéricos permiten ingresar valores decimales positivos utilizando punto (.) como separador decimal, con un máximo de 2 decimales.
{% endhint %}

<table><thead><tr><th width="186.8887939453125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor inicial</code></strong></td><td>Indica el <strong>monto base</strong> que <strong>esta vertical</strong> aporta al pozo del jackpot al activarla. Este valor se suma al monto total del jackpot.</td></tr><tr><td><strong><code>Valor inicial repeticiones</code></strong></td><td><p>Campo numérico opcional que permite establecer el monto con el que comenzará el jackpot cada vez que se reinicie.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo es opcional y solo se muestra cuando la opción de <strong>Reiniciar</strong> está activada.</p></div></td></tr><tr><td><strong><code>Apuesta mínima</code></strong></td><td>Define el valor mínimo que debe tener una apuesta virtual para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Apuesta máxima</code></strong></td><td>Define el valor máximo  permitido que debe tener una apuesta virtual para ser considerada en el jackpot.</td></tr><tr><td><strong><code>Porcentaje de acumulación</code></strong></td><td>Define el porcentaje de cada apuesta virtual que se destinará al fondo del jackpot.</td></tr></tbody></table>

#### **Configuración de segmentos de virtuales**

Configura los segmentos de virtuales que serán validos para la acumulación del jackpot.

{% hint style="warning" %}
**Nota:** Si no existen categorías, proveedores o productos activos configurados para la operación, el selector se mostrará vacío junto con un **mensaje informativo** indicando la ausencia de elementos disponibles.

En este caso, será necesario **revisar y habilitar la configuración** correspondiente en el [**Backoffice**](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos-2) para que los elementos puedan **visualizarse en el selector**.
{% endhint %}

{% tabs %}
{% tab title="Categorías" %}
Permite definir las categorías de casino cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (343).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="117.03704833984375">Campo</th><th width="120.148193359375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varias categorias participantes en el jackpot</td></tr></tbody></table>
{% endtab %}

{% tab title="Proveedores" %}
Permite definir los proveedores cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (344).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="124.4444580078125">Campo</th><th width="116.44451904296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varios proveedores participantes cuyos juegos serán validos en el jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="Productos" %}
Permite definir los productos junto con su proveedor cuyas apuestas serán consideradas para el jackpot.

<figure><img src="../../../.gitbook/assets/image (345).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="119.25927734375">Campo</th><th width="124.5926513671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar uno o varios proveedores cuyos juegos estarán disponibles para participar en el jackpot.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Lista desplegable</td><td>Permite elegir los juegos específicos de los proveedores seleccionados que serán válidos para acumular y participar en el jackpot.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}

#### Navegación entre secciones

> Para **avanzar** a la siguiente sección, haz clic en el botón **“**<img src="../../../.gitbook/assets/image (33).png" alt="" data-size="line">**”** ubicado en la parte inferior derecha.\
> Si necesitas **regresar** a la sección anterior, utiliza el botón **“**<img src="../../../.gitbook/assets/image (28).png" alt="" data-size="line">**”** situado en la parte inferior izquierda.

<p align="right"><a href="formulario.md#seccion-4" class="button primary" data-icon="chevron-right">Continuar</a></p>
{% endtab %}

{% tab title="Sección 4" %}
#### 2.4. Configuración de productos excluidos

Permite seleccionar los productos por [verticales](https://virtualsoft.gitbook.io/untitled/glosario#vertical) para cada operación (_partner y país_) que quedarán fuera del jackpot, incluso si pertenecen a las verticales o proveedores configurados como participantes.

{% hint style="warning" %}
**Nota:** Un mismo producto no puede estar configurado simultáneamente como **participante** y **excluido** en el jackpot internacional.
{% endhint %}

#### Visualización

<figure><img src="../../../.gitbook/assets/image (363).png" alt=""><figcaption><p>Figura #4: captura de pantalla sección 4 formulario jackpot internacional</p></figcaption></figure>

{% tabs %}
{% tab title="Deportivas" %}
Permite seleccionar los productos de los segmentos en la sección de deportivas (_deportes, mercados, ligas y partidos_) que serán **excluidos** del jackpot.

#### **Configuración de segmentos deportivos**

Configura los segmentos deportivos que serán excluidos del jackpot

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
Permite seleccionar los segmentos de casino (_proveedores, categorías y productos_) cuyos productos serán excluidos de la participación en el jackpot.

#### **Configuración de segmentos de casino**

Configura los segmentos de casino que serán excluidos del jackpot

{% tabs %}
{% tab title="Categorías" %}
Permite definir las categorías de casino que no aplicarán para el jackpot.

<table><thead><tr><th width="117.03704833984375">Campo</th><th width="120.148193359375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td>Seleccione una o varias categorias que serán excluidas en el jackpot</td></tr></tbody></table>
{% endtab %}

{% tab title="Proveedores" %}
Permite definir los proveedores de casino que no aplicarán para el jackpot.

<table><thead><tr><th width="124.4444580078125">Campo</th><th width="116.44451904296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar uno o varios proveedores cuyos juegos serán excluidos de la participación en el jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="Productos" %}
Permite definir los productos junto con su proveedor que serán excluidos en el jackpot.

<table><thead><tr><th width="119.25927734375">Campo</th><th width="124.5926513671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar uno o varios proveedores de los cuales se excluirán juegos del jackpot.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar los juegos de los proveedores elegidos que serán excluidos de la participación en el jackpot.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Casino en vivo" %}
Permite seleccionar los segmentos de casino en vivo (_proveedores, categorías y productos_) cuyos productos serán excluidos de la participación en el jackpot.

#### **Configuración de segmentos de casino en vivo**

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

<table><thead><tr><th width="119.25927734375">Campo</th><th width="124.5926513671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar uno o varios proveedores de los cuales se excluirán juegos del jackpot.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar los juegos de los proveedores elegidos que serán excluidos de la participación en el jackpot.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Virtuales" %}
Permite seleccionar los segmentos de apuestas virtuales (_proveedores, categorías y productos_) cuyos productos serán excluidos del jackpot.

#### **Configuración de segmentos de virtuales**

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
Permite definir los productos junto con su proveedor que serán excluidos en el jackpot.

<table><thead><tr><th width="119.25927734375">Campo</th><th width="124.5926513671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar uno o varios proveedores de los cuales se excluirán juegos del jackpot.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar los juegos de los proveedores elegidos que serán excluidos de la participación en el jackpot.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}

#### Navegación entre secciones

> Para **avanzar** a la siguiente sección, haz clic en el botón **“**<img src="../../../.gitbook/assets/image (32).png" alt="" data-size="line">**”** ubicado en la parte inferior derecha.\
> Si necesitas **regresar** a la sección anterior, utiliza el botón **“**<img src="../../../.gitbook/assets/image (27).png" alt="" data-size="line">**”** ubicado en la parte inferior izquierda.

<p align="right"><a href="formulario.md#seccion-5" class="button primary" data-icon="chevron-right">Continuar</a></p>
{% endtab %}

{% tab title="Sección 5" %}
#### 2.5. Contenido grafico

**Permite configurar los elementos gráficos del Jackpot Internacional**, definiendo recursos visuales que se aplicarán a todas las operaciones participantes. Esta sección garantiza una presentación coherente y centralizada del jackpot en la plataforma.

{% hint style="warning" %}
**Nota:** Los recursos gráficos (_imágenes, GIFs, videos y demás elementos visuales_) son opcionales. Al cargar imágenes o cualquier recurso visual, **asegúrate de cumplir con las especificaciones recomendadas** (_formato, tamaño y dimensiones_) para garantizar una visualización óptima dentro de la plataforma.
{% endhint %}

#### Visualización

<figure><img src="../../../.gitbook/assets/image (364).png" alt=""><figcaption><p>Figura #5: captura de pantalla sección 5 formulario jackpot internacional</p></figcaption></figure>

<table><thead><tr><th width="161.50006103515625">Campo</th><th width="94.75006103515625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mostrar signo moneda contador</code></strong></td><td>Selector</td><td>Define si el contador del total acumulado del jackpot mostrará el signo de la moneda correspondiente a cada operación, ajustándose <strong>automáticamente según el país</strong> en el que se visualice.</td></tr><tr><td><strong><code>Estilo contador</code></strong></td><td>Selector</td><td><p>Permite definir si el contador del total acumulado se mostrará en números <strong>enteros</strong> o <strong>decimales con dos cifras</strong>. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El contador del acumulado se actualiza en tiempo real, reflejando el incremento del jackpot de manera continua.</p></div></td></tr><tr><td><strong><code>Nombre del jackpot</code></strong></td><td>Imagen</td><td>Inserta la imagen del nombre del jackpot.</td></tr><tr><td><strong><code>Contenedor</code></strong></td><td>Imagen</td><td>Inserta la imagen de fondo que tendrá el contador del jackpot.</td></tr><tr><td><strong><code>Animación</code></strong></td><td>GIF</td><td>Inserta el GIF de la animación que se verá en el contenedor del jackpot.</td></tr><tr><td><strong><code>Video para escritorio</code></strong></td><td>Video</td><td>Inserta el video que se mostrará al usuario cuando gane el jackpot desde un dispositivo de escritorio.</td></tr><tr><td><strong><code>Video para mobile</code></strong></td><td>Video</td><td>Inserta el video que se mostrará al usuario cuando gane el jackpot desde un dispositivo móvil.</td></tr></tbody></table>

#### **Guardar y crear jackpot**

Para crear el jackpot, haz clic en **“Guardar”**.\
Al hacerlo, el sistema solicitará el **token de autenticación** para validar la acción.\
Ingresa el token y confirma nuevamente con **“Guardar”** para finalizar y activar el jackpot.
{% endtab %}
{% endtabs %}

***

### 3. Funcionamiento del jackpot

{% stepper %}
{% step %}
#### Validación de apuestas participantes

El sistema evalúa cada apuesta realizada en operaciones participantes (_partner y país_) y valida los requisitos necesarios para incluirla en el Jackpot.

<details>

<summary>Requisitos de participación</summary>

1. Corresponde a una [**vertical**](https://virtualsoft.gitbook.io/untitled/glosario/#vertical)**, categoría, proveedor y producto** configurado como **participante**.
2. Cumple los **montos mínimos y máximos permitidos** por operación y vertical.
3. No pertenece a **productos excluidos** definidos en el jackpot.
4. Valida la **existencia de una** [**TRM**](https://virtualsoft.gitbook.io/untitled/glosario/#trm) **válida y activa** para convertir el porcentaje acumulable de la apuesta desde la moneda local a la moneda base del jackpot (_USD/EUR_) cuando aplica.&#x20;

</details>
{% endstep %}

{% step %}
#### Convertir y acumular el monto

Una vez la apuesta **cumple los requisitos de participación** y el sistema **verifica la existencia de una TRM válida** en el reporte [**TRM Virtualsoft**](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/trm-virtual-soft), se procede de la siguiente manera:

<table><thead><tr><th width="188.00006103515625">Situación</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>La moneda local es diferente a la moneda base del jackpot</strong></td><td><p>Convierte el porcentaje acumulable de la apuesta desde la moneda local a la moneda base.</p><ol><li>Aplica la fórmula:<br><strong>Valor acumulable (</strong><em><strong>USD</strong></em><strong>)</strong> = (Monto de la apuesta × % de acumulación) / TRM</li><li>Redondea el resultado a <strong>4 decimales</strong>.</li><li>Acumula el valor convertido en el pozo central del jackpot.</li></ol></td></tr><tr><td><strong>La moneda local es igual a la moneda base del jackpot</strong></td><td>El sistema calcula el <strong>porcentaje de acumulación</strong> y lo suma directamente al pozo del jackpot, sin realizar conversión de moneda.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Si la moneda local es diferente a la moneda base y no existe una TRM válida para la conversión, la apuesta no será considerada válida para el jackpot.
{% endhint %}
{% endstep %}

{% step %}
#### Condiciones de caída del Jackpot

El sistema monitorea en **tiempo real** la cantidad total de apuestas válidas **acumuladas**.\
Cuando este total se encuentra dentro del r**ango mínimo** y **máximo** configurado para la caída del jackpot, el sistema selecciona **aleatoriamente** una apuesta válida como **ganadora**.

* [x] Si se alcanza el número **máximo de apuestas** sin que se haya seleccionado una ganadora, el sistema asigna la última apuesta registrada como ganadora.
* [x] Si existe una **fecha límite** configurada y el jackpot no ha caído, el sistema ejecuta la caída automáticamente en dicha fecha, aplicando las reglas definidas en el rango de _**Caída en Fecha Límite por cantidad de apuestas**_.
* [x] Si el jackpot tiene series configuradas, una vez ocurrida la caída se **genera automáticamente la siguiente serie**, manteniendo la misma lógica de acumulación y caída hasta completar el total de series definidas.
{% endstep %}

{% step %}
#### **Conversión y entrega del premio**

Una vez determinada la apuesta ganadora, el sistema identifica la operación (_Partner y país_) de origen, consulta la [**TRM**](https://virtualsoft.gitbook.io/untitled/glosario/#trm) **vigente** y convierte el monto acumulado desde la moneda base a la moneda local aplicando la fórmula:\
**Valor del premio** (_moneda local_) = **Monto acumulado** (_moneda base_) × **TRM**.\
Posteriormente, el sistema **acredita automáticamente** el premio en la cuenta del jugador en el **tipo de saldo** configurado, siempre que exista una **TRM** válida.
{% endstep %}

{% step %}
#### Logica de reinicio del jackpot

Si el jackpot está configurado con reinicio, el sistema **crea automáticamente un nuevo jackpot hijo** una vez ocurre la caída.

* [x] El nuevo jackpot **hereda la configuración del** [**jackpot padre**](https://virtualsoft.gitbook.io/untitled/glosario/#jackpot-padre), lo que permite repetir todo el **ciclo de funcionamiento** y puede iniciar con un **valor inicial** diferente, según la configuración establecida.
* [x] El sistema **mantiene la referencia al ID del** [**jackpot padre**](https://virtualsoft.gitbook.io/untitled/glosario/#jackpot-padre) y **controla el número máximo de reinicios permitidos** desde el formulario de configuración.
* [x] Al alcanzar dicho límite, el sistema **cierra definitivamente el último jackpot** una vez se produzca su caída.
{% endstep %}
{% endstepper %}

***

### 4. Validaciones y Reglas de Negocio

* Los campos que tengan un <mark style="color:red;">\*</mark> son obligatorios para la creación del Jackpot.
* La cantidad máxima de apuestas requerida para la caída del jackpot debe ser mayor que la cantidad mínima establecida.
* El sistema muestra automáticamente el **valor acumulado del Jackpot Internacional**, convertido desde la moneda base a la **moneda local de cada operación (**_**Partner y pais**_**) participante.**
* La información en tiempo real de los jackpots internacionales, incluyendo datos generales y el desglose de aportes por partner y país, se presenta en el reporte [**Jackpot internacional**](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/jackpot-internacional).

***

### &#x35;**. Control de versiones**

<details>

<summary>Historial de versiones</summary>

| Versión | Fecha      | Autor       | Cambios realizados                |
| ------- | ---------- | ----------- | --------------------------------- |
| 1.0     | 03/12/2025 | David Ortiz | Documento inicial                 |
| 1.1     | 18/12/2025 | David Ortiz | Incorporación del funcionamiento. |

</details>
