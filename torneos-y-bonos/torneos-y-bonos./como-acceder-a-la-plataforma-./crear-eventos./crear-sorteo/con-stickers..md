---
description: >-
  Permite configurar todos los campos necesarios cuando el sorteo utiliza
  stickers como método de participación.
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: false
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# Con Stickers.

### 🏷️ Tipo de condición:

Selecciona cómo los usuarios participarán en el sorteo según cada vertical disponible. Cada opción **activa una vertical** _(como apuestas deportivas, casino o depósitos)_. y mostrará configuraciones específicas. En esta sección puedes seleccionar **todas** las verticales sin restricciones.

{% hint style="warning" %}
**Nota**: Las configuraciones se ajustan automáticamente según la vertical seleccionada, aunque su lógica de funcionamiento sea similar.
{% endhint %}

{% tabs %}
{% tab title="Deportivas" %}
Configura que segmento de deportivas estarán disponibles para el sorteo. Según la opción elegida, se mostrarán diferentes configuraciones.

<figure><img src="../../../../.gitbook/assets/image (257).png" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla configuraciones deportivas.</p></figcaption></figure>

<table><thead><tr><th width="152.8887939453125">Campo</th><th width="93.33343505859375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de Ranking</code></strong></td><td>Selector</td><td><p>Permite seleccionar el criterio para ordenar a los participantes del sorteo.</p><ul><li><strong>Monto dinero:</strong> Ordena a los participantes según la cantidad de dinero apostado.</li><li><strong>Líneas apuesta</strong>: Ordena a los participantes según la cantidad de líneas apostadas.</li></ul></td></tr><tr><td><strong><code>Todas las condiciones son obligatorias</code></strong></td><td>Selector</td><td>Establece si las configuraciones realizadas anteriormente serán obligatorias para participar en el sorteo.</td></tr></tbody></table>

#### **⚙️ Configuración de segmentos de deportivas**

Configura los segmentos de deportivas disponibles para el sorteo. Según la opción elegida, se mostrarán configuraciones específicas para cada segmento.

{% tabs %}
{% tab title="Deporte" %}
Configura los deportes en los que estará disponible el sorteo.

<figure><img src="../../../../.gitbook/assets/image (264).png" alt=""><figcaption><p>Figura #2: Captura de pantalla configuración deportes.</p></figcaption></figure>

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="83.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Añadir manual</code></strong></td><td>Botón</td><td><p>Despliega una tabla en la cual podrás agregar los deportes que sumarán stickers en el sorteo.<br></p><ul><li><strong>ID</strong>: Identificador único del deporte.</li><li><strong>Deportes seleccionados</strong>: Nombre del deporte.</li><li><strong>Imagen</strong>: URL de la imagen representativa.</li><li><strong>Acción</strong>: Elimina el deporte correspondiente a la fila.</li></ul></td></tr><tr><td><strong><code>Deportes</code></strong></td><td>Texto</td><td>Ingrese los IDs separados por comas <em>(,)</em> para agregar los deportes al sorteo rápidamente.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**:

* Los deportes pueden agregarse al sorteo desde las opciones **`Añadir manual`** o **`Deportes`**. No es necesario completar ambos campos; basta con utilizar una de las dos opciones disponibles.
* La lista desplegable **`Deportes`** con el botón **`Seleccionar`**, se encuentran en el formulario, pero actualmente no está activo este método
{% endhint %}
{% endtab %}

{% tab title="Mercados" %}
Configura los mercados en los que estará activo el sorteo.

<figure><img src="../../../../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="83.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td> <strong><code>Añadir manual</code></strong></td><td>Botón</td><td><p>Despliega una tabla en la cual podrás agregar los mercados que sumarán stickers en el sorteo.<br></p><ul><li><strong>ID</strong>: Identificador único del mercado.</li><li><strong>Deportes seleccionados</strong>: Nombre del mercado.</li><li><strong>Imagen</strong>: URL de la imagen representativa.</li><li><strong>Acción</strong>: Elimina el mercado correspondiente a la fila.</li></ul></td></tr><tr><td><strong><code>Mercados</code></strong></td><td>Texto</td><td>Ingrese los IDs separados por comas <em>(,)</em> para agregar los mercados al sorteo rápidamente.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**:&#x20;

* Los mercados pueden agregarse al sorteo desde las opciones **`Añadir manual`** o **`Mercados`**. No es necesario completar ambos campos; basta con utilizar una de las dos opciones disponibles.
* La lista desplegable **`Deporte`** con el botón **`buscar`**, se encuentran en el formulario, pero actualmente no está activo este método.
{% endhint %}
{% endtab %}

{% tab title="Ligas" %}
Define las ligas en las que estará disponible el sorteo.

<figure><img src="../../../../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="83.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td> <strong><code>Añadir manual</code></strong></td><td>Botón</td><td><p>Despliega una tabla en la cual podrás agregar las ligas que sumarán stickers en el sorteo.<br></p><ul><li><strong>ID</strong>: Identificador único de las ligas.</li><li><strong>Deportes seleccionados</strong>: Nombre de las ligas.</li><li><strong>Imagen</strong>: URL de la imagen representativa.</li><li><strong>Acción</strong>: Elimina la liga correspondiente a la fila.</li></ul></td></tr><tr><td><strong><code>Ligas</code></strong></td><td>Texto</td><td>Ingrese los IDs separados por comas <em>(,)</em> para agregar las ligas al sorteo rápidamente.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**:&#x20;

* Los mercados pueden agregarse al sorteo desde las opciones **`Añadir manual`** o **`ligas`**. No es necesario completar ambos campos; basta con utilizar una de las dos opciones disponibles.
* La lista desplegable **`Deporte`** , **`País`** con el botón **`buscar`**, se encuentran en el formulario, pero actualmente no está activo este método.
{% endhint %}
{% endtab %}

{% tab title="Partidos" %}
&#x20;Define los partidos que aplicarán para el sorteo.

<figure><img src="../../../../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="83.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td> <strong><code>Añadir manual</code></strong></td><td>Botón</td><td><p>Despliega una tabla en la cual podrás agregar los partidos que sumarán stickers en el sorteo.<br></p><ul><li><strong>ID</strong>: Identificador único del partido.</li><li><strong>Deportes seleccionados</strong>: Nombre del partido.</li><li><strong>Imagen</strong>: URL de la imagen representativa.</li><li><strong>Acción</strong>: Elimina el partido correspondiente a la fila.</li></ul></td></tr><tr><td><strong><code>Partidos</code></strong></td><td>Texto</td><td>Ingrese los IDs separados por comas <em>(,)</em> para agregar los partidos al sorteo rápidamente.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**:&#x20;

* Los mercados pueden agregarse al sorteo desde las opciones **`Añadir manual`** o **`partidos`**. No es necesario completar ambos campos; basta con utilizar una de las dos opciones disponibles.
* La lista desplegable **`Deporte` , `País`, `Campeonato`** con el botón **`buscar`**, se encuentran en el formulario, pero actualmente no está activo este método.
{% endhint %}
{% endtab %}
{% endtabs %}

<table><thead><tr><th width="180.4444580078125">Campo</th><th width="104.9998779296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de apuestas</code></strong></td><td>opción múltiple</td><td>Tipos de apuestas deportivas que aplicarán para el sorteo.</td></tr><tr><td><strong><code>Tipo de evento</code></strong></td><td>opción única</td><td>Elige que tipo de eventos estarán disponibles para el sorteo.</td></tr><tr><td><strong><code>Mínima cuota en selecciones</code></strong></td><td>Numérico</td><td>Indica la cantidad mínima de selecciones que puede tener un usuario en apuestas múltiples.</td></tr><tr><td><strong><code>Mínima cuota en selecciones</code></strong></td><td>Numérico</td><td>Indica las cuotas mínimas para cada selección.</td></tr><tr><td><strong><code>Mínima cuota total</code></strong></td><td>Numérico</td><td>Indica las cuotas mínimas en total para aplicar para el sorteo.</td></tr><tr><td><strong><code>Botón repetir partidos</code></strong></td><td>Botón</td><td>Habilitar la repetición de apuestas en los mismos partidos para participar en el sorteo.</td></tr><tr><td><strong><code>Botón Repetir mercados</code></strong></td><td>Botón</td><td>Establece que se puedan repetir mercados para entrar al sorteo.</td></tr></tbody></table>
{% endtab %}

{% tab title="Casino" %}
Añade los juegos de casino que podrán dar stickers para participar para participar en el torneo.&#x20;

<table><thead><tr><th width="150.22222900390625">Sección</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Selecciona una o varias categorías que podrán ser utilizadas para participar en el sorteo.</td></tr><tr><td><strong><code>Proveedores</code></strong></td><td>Selecciona los proveedores que podrán ser utilizados para participar en el sorteo.</td></tr><tr><td><strong><code>Productos</code></strong></td><td><p>Permite agregar uno o más productos junto con su proveedor correspondiente.</p><ul><li><strong>Proveedor</strong>: Selecciona proveedor a participar en el sorteo.</li><li><strong>Producto</strong>:  Selecciona uno o varios productos disponibles del proveedor.</li></ul></td></tr></tbody></table>
{% endtab %}

{% tab title="Depósitos" %}
Define las pasarelas de pago que podrían dar stickers por realizar depósitos con ellas.

<table><thead><tr><th width="155.4443359375">Campo</th><th width="123.77777099609375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Pasarelas de pago</code></strong></td><td>Lista desplegable</td><td>Selecciona una o varias pasarelas disponibles para el deposito</td></tr></tbody></table>
{% endtab %}

{% tab title="Casino en vivo" %}
Añade los juegos de casino en vivo que podrán dar stickers para participar para participar en el torneo.&#x20;

<table><thead><tr><th width="150.22222900390625">Sección</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Selecciona una o varias categorías que podrán ser utilizadas para participar en el sorteo.</td></tr><tr><td><strong><code>Proveedores</code></strong></td><td>Selecciona los proveedores que podrán ser utilizados para participar en el sorteo.</td></tr><tr><td><strong><code>Productos</code></strong></td><td><p>Permite agregar uno o más productos junto con su proveedor correspondiente.</p><ul><li><strong>Proveedor</strong>: Selecciona proveedor a participar en el sorteo.</li><li><strong>Producto</strong>:  Selecciona uno o varios productos disponibles del proveedor.</li></ul></td></tr></tbody></table>
{% endtab %}

{% tab title="Virtuales" %}
Añade los juegos de la vertical virtuales que podrán dar stickers para participar para participar en el torneo.&#x20;

<table><thead><tr><th width="150.22222900390625">Sección</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Selecciona una o varias categorías que podrán ser utilizadas para participar en el sorteo.</td></tr><tr><td><strong><code>Proveedores</code></strong></td><td>Selecciona los proveedores que podrán ser utilizados para participar en el sorteo.</td></tr><tr><td><strong><code>Productos</code></strong></td><td><p>Permite agregar uno o más productos junto con su proveedor correspondiente.</p><ul><li><strong>Proveedor</strong>: Selecciona proveedor a participar en el sorteo.</li><li><strong>Producto</strong>:  Selecciona uno o varios productos disponibles del proveedor.</li></ul></td></tr></tbody></table>
{% endtab %}
{% endtabs %}



{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<a href="./#id-4.-moneda" class="button primary" data-icon="forward">Continuar  →  En flujo principal</a>
{% endcolumn %}
{% endcolumns %}
