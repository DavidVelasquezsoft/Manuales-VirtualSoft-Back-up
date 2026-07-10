---
description: >-
  Permite configurar todos los campos necesarios cuando el sorteo no utiliza
  stickers como método de participación.
hidden: true
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

# Sin stickers.

{% hint style="danger" %}
**Nota Importante**: Actualmente los sorteos creados sin stickers no se visualizan en la plataforma Usuarios Online, adicional, esta configuración para los sorteos no aplica a ningún flujo o lógica funcional.
{% endhint %}

### 🏷️ Tipo Producto:

Selecciona los productos con los que el usuario podrá sumar puntos en el sorteo. Se pueden elegir varias opciones, pero con las siguientes restricciones:

> Sportsbook es compatible con cualquiera de las otras opciones. Sin embargo, Casino, Casino en Vivo y Virtuales no pueden combinarse entre sí.
>
> {% hint style="info" %}
> **Ejemplo válido:** Sportsbook + Casino o Sportsbook + Virtuales.\
> **Ejemplo no válido:** Casino + Virtuales.
> {% endhint %}

{% tabs %}
{% tab title="Sportsbook" %}
Permite configurar que segmento de deportivas estarán disponibles para el sorteo. Según la opción elegida, se mostrarán diferentes configuraciones.

<figure><img src="../../../../.gitbook/assets/image (257).png" alt="" width="563"><figcaption></figcaption></figure>

<table><thead><tr><th width="152.8887939453125">Campo</th><th width="93.33343505859375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Tipo de Ranking</code></td><td>Toggle switch</td><td>Permite seleccionar el criterio para ordenar a los participantes del sorteo.</td></tr><tr><td><code>Todas las condiciones son obligatorias</code></td><td>Toggle switch</td><td>Establece si las configuraciones realizadas anteriormente serán obligatorias para participar en el sorteo.</td></tr></tbody></table>

**Configuración de segmentos de deportivas**: Debes configurar el segmento de deportivas disponible para el sorteo. Según la opción elegida, las configuraciones variarán. A continuación, se detallan las de cada segmento.

{% tabs %}
{% tab title="Deporte" %}
Permite seleccionar los deportes en los que estará disponible el sorteo.

<figure><img src="../../../../.gitbook/assets/image (264).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="133.33331298828125">Campo</th><th width="100.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Deportes</code></td><td>Dropdown</td><td></td></tr><tr><td><code>Seleccionar</code></td><td>Button</td><td></td></tr><tr><td> <code>Añadir manual</code></td><td>Button</td><td>Permite agregar deportes de forma manual y muestra los siguientes campos:</td></tr><tr><td><code>Deportes</code></td><td>Texto</td><td>Ingrese los IDs separados por comas ( <strong>,</strong> ) para agregar los deportes al sorteo rapidamente.</td></tr></tbody></table>

<table><thead><tr><th width="180.4444580078125">Campo</th><th width="96.9998779296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Tipo de apuestas</code></td><td></td><td>Elige uno o varios tipos de apuestas deportivas que aplicarán para el sorteo.</td></tr><tr><td><code>Tipo de evento</code></td><td></td><td>Elige que tipo de eventos estarán disponibles para el sorteo.</td></tr><tr><td><code>Mínima cuota en selecciones</code></td><td>Numerico</td><td>Indica la cantidad mínima de selecciones que puede tener un usuario en apuestas múltiples.</td></tr><tr><td><code>Mínima cuota en selecciones</code></td><td>Numerico</td><td>Indica las cuotas mínimas para cada selección.</td></tr><tr><td><code>Mínima cuota total</code></td><td>Numerico</td><td>Indica las cuotas mínimas en total para aplicar para el sorteo.</td></tr><tr><td><code>Botón repetir partidos</code></td><td>Button</td><td>Habilitar la repetición de apuestas en los mismos partidos para participar en el sorteo.</td></tr><tr><td><code>Botón Repetir mercados</code></td><td>Button</td><td>Establece que se puedan repetir mercados para entrar al sorteo.</td></tr></tbody></table>


{% endtab %}

{% tab title="Mercados" %}
Permite seleccionar los mercados en los que estará activo el sorteo.

<figure><img src="../../../../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="127.11114501953125">Campo</th><th width="102.4443359375">Tipo</th><th>Descripcio</th></tr></thead><tbody><tr><td><code>Deporte</code></td><td>Dropdown</td><td>Deporte disponible en el mercado.</td></tr><tr><td><code>Buscar</code></td><td>Button</td><td></td></tr><tr><td><code>Seleccionar</code></td><td>Button</td><td></td></tr><tr><td><code>Añadir manual</code></td><td>Button</td><td>Permite agregar mercados de forma manual y muestra los siguientes campos:</td></tr><tr><td><code>Mercados</code></td><td>Texto</td><td>Ingrese los IDs de los mercados separados por comas ( <strong>,</strong> ) para agregar al sorteo rapidamente.</td></tr></tbody></table>
{% endtab %}

{% tab title="Ligas" %}
Define las ligas en las que estará disponible el sorteo.

<figure><img src="../../../../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="127.11114501953125">Campo</th><th width="102.4443359375">Tipo</th><th>Descripcio</th></tr></thead><tbody><tr><td><code>Deporte</code></td><td>Dropdown</td><td>Deporte disponible en la liga.</td></tr><tr><td><code>Pais</code></td><td>Dropdown</td><td>Selecciona el país donde estará disponible la liga.</td></tr><tr><td><code>Buscar</code></td><td>Button</td><td></td></tr><tr><td><code>Añadir manual</code></td><td>Button</td><td>Permite agregar ligas de forma manual y muestra los siguientes campos:</td></tr><tr><td><code>Ligas</code></td><td>Texto</td><td>Ingrese los IDs de las ligas separados por comas ( <strong>,</strong> ) para agregar al sorteo rapidamente.</td></tr></tbody></table>
{% endtab %}

{% tab title="Partidos" %}
&#x20;Define los partidos que aplicarán para el sorteo.

<figure><img src="../../../../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="127.11114501953125">Campo</th><th width="102.4443359375">Tipo</th><th>Descripcio</th></tr></thead><tbody><tr><td><code>Deporte</code></td><td>Dropdown</td><td>Deporte en el que se juegan los partidos.</td></tr><tr><td><code>Pais</code></td><td>Dropdown</td><td></td></tr><tr><td><code>Campeonato</code></td><td>Dropdown</td><td></td></tr><tr><td><code>Buscar</code></td><td>Button</td><td></td></tr><tr><td><code>Añadir manual</code></td><td>Button</td><td>Permite agregar partidos de forma manual y muestra los siguientes campos:</td></tr><tr><td><code>Partidos</code></td><td>Texto</td><td>Ingrese los IDs de los partidos separados por comas   ( <strong>,</strong> ) para agregar al sorteo rapidamente.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Casino" %}
Permite añadir los juegos de casino que estarán disponibles en el sorteo.&#x20;

<table><thead><tr><th width="150.22222900390625">Sección</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Categorías</code></td><td>Selecciona una o varias categorías que podrán ser utilizadas para participar en el sorteo.</td></tr><tr><td><code>Proveedores</code></td><td>Selecciona los proveedores que podrán ser utilizados para participar en el sorteo.</td></tr><tr><td><code>Productos</code></td><td>Permite agregar uno o más productos junto con su proveedor correspondiente.</td></tr></tbody></table>
{% endtab %}

{% tab title="Depósitos" %}
Permite definir las pasarelas de pago en las que se podra hacer un depocito en el sorteo.

<table><thead><tr><th width="172.4443359375">Campo</th><th width="105.77777099609375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Pasarelas de pago</code></td><td>Dropdown</td><td>Selecciona una o varias pasarelas disponibles para el deposito</td></tr></tbody></table>
{% endtab %}

{% tab title="Casino en vivo" %}
Permite añadir los juegos de casino en vivo que estaran disponibles en el sorteo.&#x20;

<table><thead><tr><th width="150.22222900390625">Sección</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Categorías</code></td><td>Selecciona una o varias categorías que podrán ser utilizadas para participar en el sorteo.</td></tr><tr><td><code>Proveedores</code></td><td>Selecciona los proveedores que podrán ser utilizados para participar en el sorteo.</td></tr><tr><td><code>Productos</code></td><td>Permite agregar uno o más productos junto con su proveedor correspondiente.</td></tr></tbody></table>
{% endtab %}

{% tab title="Virtuales" %}
Permite añadir los juegos de virtuales que estarán disponibles en el sorteo.&#x20;

<table><thead><tr><th width="150.22222900390625">Sección</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Categorías</code></td><td>Selecciona una o varias categorías que podrán ser utilizadas para participar en el sorteo.</td></tr><tr><td><code>Proveedores</code></td><td>Selecciona los proveedores que podrán ser utilizados para participar en el sorteo.</td></tr><tr><td><code>Productos</code></td><td>Permite agregar uno o más productos junto con su proveedor correspondiente.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

## ⏭️ Continuar:

{% columns %}
{% column %}
<a href="con-stickers..md" class="button secondary" data-icon="swap">Ver configuración →  Con stickers</a>
{% endcolumn %}

{% column %}
<a href="./#id-4.-moneda" class="button primary" data-icon="forward">Continuación del flujo →  Volver al flujo principal</a>
{% endcolumn %}
{% endcolumns %}
