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

# Cashback

Permite crear bonos Cashback que reembolsan al usuario un porcentaje de sus pérdidas o del neto de sus transacciones durante un periodo determinado. Desde aquí puedes configurar el tipo de bono, sus condiciones, criterios y porcentaje de devolución.

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Torneos y Bonos > Crear Bono > País > Bono Cashback

***

### 2. Visualización general

<figure><img src="../../../../.gitbook/assets/cashback (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla bono Cashback.</p></figcaption></figure>

***

### 3.  Crear Bono [cashback](https://virtualsoft.gitbook.io/untitled/glosario/#cashback)

Permite configurar los campos necesarios para crear un bono cashback y definir sus características, condiciones y limitaciones.

{% hint style="warning" %}
**Nota**: Los campos que finalizan el nombre con un <mark style="color:red;">\*</mark> son obligatorios para la creación del bono.
{% endhint %}

#### **3.1. Campos principales**

<table><thead><tr><th width="154.4444580078125">Campo</th><th width="124.4444580078125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Botón</td><td><p>Despliega los campos de fecha que permiten definir el período de vigencia del bono. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Es posible configurar múltiples rangos de fechas mediante el botón <strong>“Agregar”</strong>, una vez se haya establecido la <strong>fecha inicial</strong> y la <strong>fecha final</strong> de cada rango.</p></div></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre que identificará el bono.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Numérico</td><td><p>Define el orden de asignación de bonos a los usuarios, un número mayor indica mayor prioridad. </p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si hay tres bonos configurados con las siguientes prioridades:</p><ul><li><strong>Bono A:</strong> 1</li><li><strong>Bono B:</strong> 2</li><li><strong>Bono C:</strong> 3</li></ul><p>El sistema dará preferencia al <strong>Bono C</strong>, ya que tiene la prioridad más alta. </p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Detalle explicativo del bono.</td></tr><tr><td><p><strong><code>URL Imagen</code></strong> </p><p><strong><code>principal</code></strong></p></td><td>URL</td><td>Imagen que visualizará el usuario al redimir el bono, configurada mediante enlace URL.</td></tr><tr><td><p><strong><code>Fecha de</code></strong> </p><p><strong><code>expiración o</code></strong> </p><p><strong><code>Días</code></strong></p></td><td>Interruptor</td><td>Define el tiempo de redención del bono. Al elegir días se mostrará el campo de días, y al elegir fechas se mostrará el campo de fechas.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Interruptor</td><td>Define si el bono es público (<em>todos los jugadores</em>) o privado (<em>usuarios VIP</em>).</td></tr><tr><td><strong><code>Cantidad mínima de depósitos</code></strong></td><td>Numérico</td><td><p>Indica la cantidad mínima de depósitos que un usuario debe haber realizado dentro del rango de fechas configurado para el cashback, como requisito para poder realizar la redención.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo es <strong>opcional</strong> y solo aplica a cashback basados en <strong>transacciones</strong>.</p></div></td></tr><tr><td><strong><code>Prefijo</code></strong></td><td>Texto</td><td>Identificador para diferenciar el bono frente a otros.</td></tr><tr><td><p><strong><code>Cantidad de</code></strong> </p><p><strong><code>jugadores</code></strong></p></td><td>Numérico</td><td>Número máximo de jugadores que podrán acceder al bono.</td></tr><tr><td><strong><code>¿Es para?</code></strong></td><td>Lista desplegable</td><td><p>Define <strong>el propósito</strong> del bono cashback opcionalmente, indicando en qué <strong>módulo</strong> o <strong>funcionalidad</strong> del sistema quedará disponible para su uso <em>(ej:  Ruleta, sorteo, CRM, landing de registro, fidelización, Cashback,  bono de cumpleaños, referidos, Beneficios)</em>. <br><br>La opción seleccionada <strong>habilita el bono dentro del módulo correspondiente</strong>, permitiendo que posteriormente pueda ser <strong>asignado a campañas o activado</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Una vez creado el bono, será necesario realizar <strong>configuraciones adicionales</strong> dentro del módulo seleccionado para completar su uso.</p><p><a href="cashback.md#id-4.-validaciones-y-reglas-de-negocio" class="button secondary">Ver detalles</a></p></div></td></tr><tr><td><strong><code>Tipo de Campaña</code></strong></td><td>Lista desplegable</td><td>Tipo de campaña a la que va dirigida el bono. <em>(ej: Retención, Reactivación)</em></td></tr><tr><td><p><strong><code>Detalle de</code></strong> </p><p><strong><code>Campaña</code></strong></p></td><td>Lista desplegable</td><td>Detalle específico de la campaña asociada <em>(ej: Lealtad, Activación).</em></td></tr><tr><td><strong><code>Asignacion de bono</code></strong></td><td>Lista desplegable</td><td>Se debe seleccionar el bono correspondiente. En caso de que la campaña sea para Altenar, se debe asignar un bono previamente creado como bono no depósito.</td></tr></tbody></table>

#### **3.2. Opciones avanzadas**

Parámetros adicionales para personalizar el bono.

<details>

<summary>Opciones avanzadas</summary>

<table><thead><tr><th width="215.50006103515625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Permisos</code></strong></td><td>Define si el código global es obligatorio.</td></tr><tr><td><strong><code>Código Global</code></strong></td><td>Código configurado en BackOffice que limita la cantidad máxima de usuarios.</td></tr><tr><td><strong><code>Códigos Promocionales</code></strong></td><td>Código promocional configurado en BackOffice para campañas específicas.</td></tr></tbody></table>

</details>

#### **3.3. Configuraciones de tipo de producto**

Indica hacía que vertical irá dirigido este bono

{% tabs %}
{% tab title="Sportsbook" %}
Estas son las configuraciones disponibles para el comportamiento del bono en todas las apuestas deportivas

<table><thead><tr><th width="236.77777099609375">Campo</th><th width="117.666748046875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>¿Todas las condiciones son obligatorias?</code></strong></td><td>Interruptor</td><td>Si está en “Sí”, el usuario deberá cumplir todas las configuraciones definidas para el bono; si está en “No”, solo serán obligatorias las principales.</td></tr></tbody></table>

* **Configuración segmento deportivas**

{% tabs %}
{% tab title="Deporte" %}
- **Visualización**

<figure><img src="../../../../.gitbook/assets/image (26).png" alt=""><figcaption><p>Figura #2: Captura de pantalla configuraciones deporte.</p></figcaption></figure>

* **Acciones del usuario**

<table><thead><tr><th width="245.111083984375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Añadir deportes</strong></td><td>Añade deportes específicos para que apliquen con este bono</td></tr><tr><td><strong>Eliminar deportes agregados</strong></td><td>Elimina algún deporte agregado al bono.</td></tr></tbody></table>

* **¿Cómo añadir un deporte?**\
  Utiliza el botón "**Añadir**" y completa los siguientes campos

<table><thead><tr><th width="211.77783203125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Id del deporte a añadir.</td></tr><tr><td><strong><code>Deportes seleccionados</code></strong></td><td>Nombre del deporte a añadir, solo se acepta un nombre por deporte añadido.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL representativa del deporte.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Elimina el deporte añadido.</td></tr><tr><td><strong><code>Deportes</code></strong></td><td>Añade los deportes por ID, separados por comas (,).</td></tr></tbody></table>
{% endtab %}

{% tab title="Mercados" %}
* **Visualización**

<figure><img src="../../../../.gitbook/assets/image (27).png" alt=""><figcaption><p>Figura #3: Captura de pantalla configuraciones mercados.</p></figcaption></figure>

* **Acciones del usuario**

<table><thead><tr><th width="245.111083984375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Añadir mercado</strong></td><td>Añade mercados específicos para que apliquen con este bono</td></tr><tr><td><strong>Eliminar mercados agregados</strong></td><td>Elimina algún mercado agregado al bono.</td></tr></tbody></table>

* **¿Cómo añadir un mercado?**\
  Utiliza el botón "**Añadir**" y completa los siguientes campos

<table><thead><tr><th width="211.77783203125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Id del mercado a añadir.</td></tr><tr><td> <strong><code>Mercados seleccionados</code></strong></td><td>Nombre del mercado a añadir, solo se acepta un nombre por mercado añadido.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL representativa del mercado.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Elimina el mercado añadido.</td></tr><tr><td><strong><code>Deportes</code></strong></td><td>Añade los mercados por ID, separados por comas (,).</td></tr></tbody></table>
{% endtab %}

{% tab title="Ligas" %}


* **Visualización**

<figure><img src="../../../../.gitbook/assets/image (28).png" alt=""><figcaption><p>Figura #4: Captura de pantalla configuraciones ligas.</p></figcaption></figure>

* **Acciones del usuario**

<table><thead><tr><th width="245.111083984375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Añadir ligas</strong></td><td>Añade ligas específicas para que apliquen con este bono</td></tr><tr><td><strong>Eliminar ligas agregados</strong></td><td>Elimina alguna ligas agregadas al bono.</td></tr></tbody></table>

* **¿Cómo añadir una liga?**\
  Utiliza el botón "**Añadir**" y completa los siguientes campos

<table><thead><tr><th width="211.77783203125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Id del la liga a añadir.</td></tr><tr><td> <strong><code>ligas seleccionados</code></strong></td><td>Nombre de la liga a añadir, solo se acepta un nombre por liga añadido.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL representativa de la liga.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Elimina la liga añadida.</td></tr><tr><td><strong><code>Deportes</code></strong></td><td>Añade las ligas por ID, separados por comas (,).</td></tr></tbody></table>
{% endtab %}

{% tab title="Partidos" %}


* **Visualización**

<figure><img src="../../../../.gitbook/assets/image (29).png" alt=""><figcaption><p>Figura #5: Captura de pantalla configuraciones partidos.</p></figcaption></figure>

* **Acciones del usuario**

<table><thead><tr><th width="245.111083984375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Añadir partidos</strong></td><td>Añade partidos específicos para que apliquen con este bono</td></tr><tr><td><strong>Eliminar partidos agregados</strong></td><td>Elimina algún partidos agregados al bono.</td></tr></tbody></table>

*   **¿Cómo añadir un partido?**\
    Utiliza el botón "**Añadir**" y completa los siguientes campos

    <table><thead><tr><th width="211.77783203125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Id del partido a añadir.</td></tr><tr><td> <strong><code>Partidos seleccionados</code></strong></td><td>Nombre del partido a añadir, solo se acepta un nombre por partido añadido.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL representativa del partido.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Elimina el partido añadido.</td></tr><tr><td><strong><code>Deportes</code></strong></td><td>Añade los partidos por ID, separados por comas (,).</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

* **Configuraciones generales del tipo de producto**

<table><thead><tr><th width="176.77777099609375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de apuesta</code></strong></td><td><p>Tipo de apuesta que aplicará para la devolución de saldo:</p><ul><li><strong>Single</strong>: Apuesta simple a un único pronóstico con un monto definido <em>(Ejemplo: Apostar $10 a que gana Real Madrid).</em></li><li><strong>Múltiple</strong>: Combina varias selecciones en una sola apuesta <em>(Ejemplo: Apostar $10 a que gana Real Madrid y Barcelona en sus respectivos partidos).</em></li><li><strong>System</strong>: Combina pronósticos permitiendo ganar incluso si falla uno <em>(Ejemplo: Apostar $10 a un sistema 2/3 entre Real Madrid, Barcelona y Juventus).</em></li></ul></td></tr><tr><td><strong><code>Tipo de evento</code></strong></td><td><p>Tipo de evento que aplicará para la devolución de saldo:</p><ul><li><strong>Both</strong>: Combina ambos mercados <em>(Ejemplo: Apostar $10 en un partido disponible tanto en pre-match como en live).</em></li><li><strong>Pre-match</strong>: Eventos que se pronostican antes de iniciar <em>(Ejemplo: Apostar $10 a que gana Real Madrid antes del inicio del partido).</em></li><li><strong>Live</strong>: Eventos en juego que solo se pueden apostar mientras se desarrollan <em>(Ejemplo: Apostar $10 a que habrá gol en el segundo tiempo mientras el partido está en curso).</em></li></ul></td></tr><tr><td><p><strong><code>Minima cantidad en</code></strong> </p><p><strong><code>selecciones</code></strong></p></td><td>Indica la cantidad mínima de selecciones que puede tener un usuario en apuestas múltiples y así aplique para el bono cashback.</td></tr><tr><td><p><strong><code>Mínima cuota</code></strong> </p><p><strong><code>en selecciones</code></strong></p></td><td>Indica la cuota mínima de apuestas en cada selección para aplicar a la devolución de saldo.</td></tr><tr><td><strong><code>Mínima cuota total</code></strong></td><td>Cantidad mínima de la cuota en el total de la apuesta para que aplique a la devolución de saldo.</td></tr><tr><td><strong><code>Repetir partidos</code></strong></td><td>Se podrán repetir apuestas en partidos y aplicará la devolución de saldo.</td></tr><tr><td><strong><code>Repetir mercados</code></strong></td><td>Se podrán repetir mercados en apuestas y aplicará la devolución de saldo.</td></tr></tbody></table>
{% endtab %}

{% tab title="Casino" %}
Estas son las configuraciones disponibles para el comportamiento del bono en todos los apartados de casino. &#x20;

{% tabs %}
{% tab title="Categorías " %}
<table><thead><tr><th width="114.88885498046875">Campo</th><th width="169.3333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td>Selecciona en que categorías de casino el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr></tbody></table>
{% endtab %}

{% tab title="Proveedores" %}
<table><thead><tr><th width="114.88885498046875">Campo</th><th width="169.3333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona con que proveedores el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr></tbody></table>
{% endtab %}

{% tab title="Productos" %}
<table><thead><tr><th width="114.88885498046875">Campo</th><th width="169.3333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona con que proveedores el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Selecciona con que juegos el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Casino en vivo" %}
Estas son las configuraciones disponibles para el comportamiento del bono en todos los apartados casino en vivo. &#x20;

{% tabs %}
{% tab title="Categorías " %}
<table><thead><tr><th width="114.88885498046875">Campo</th><th width="169.3333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td>Selecciona en que categorías de casino en vivio el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr></tbody></table>
{% endtab %}

{% tab title="Proveedores" %}
<table><thead><tr><th width="114.88885498046875">Campo</th><th width="169.3333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona con que proveedores el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr></tbody></table>
{% endtab %}

{% tab title="Productos" %}
<table><thead><tr><th width="114.88885498046875">Campo</th><th width="169.3333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona con que proveedores el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Selecciona con que juegos el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Virtuales" %}
Estas son las configuraciones disponibles para el comportamiento del bono en todos los apartados de apuestas virtuales. &#x20;

{% tabs %}
{% tab title="Categorías " %}
<table><thead><tr><th width="114.88885498046875">Campo</th><th width="169.3333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td>Selecciona en que categorías el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr></tbody></table>
{% endtab %}

{% tab title="Proveedores" %}
<table><thead><tr><th width="114.88885498046875">Campo</th><th width="169.3333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona con que proveedores el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr></tbody></table>
{% endtab %}

{% tab title="Productos" %}
<table><thead><tr><th width="114.88885498046875">Campo</th><th width="169.3333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona con que proveedores el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Selecciona con que juegos el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Transacciones" %}
Estas configuraciones determinan el comportamiento del bono según el **neto transaccional del jugador**, calculado mediante la fórmula (**depósitos – retiros)** dentro del período promocional.

<table><thead><tr><th width="162.3887939453125">Campo</th><th width="130.1666259765625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Monto mínimo neto para pagar el cashback</code></strong></td><td>Numérico</td><td><p>Define el valor mínimo de neto (<strong>depósitos – retiros</strong>) que el usuario debe alcanzar para que el bono cashback aplique.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Una vez cumplido este mínimo, el sistema multiplica el neto por el <strong>porcentaje de devolución</strong> para calcular el monto que será <strong>retornado</strong> al usuario.</p></div></td></tr><tr><td><strong><code>Monto mínimo de depósito</code></strong></td><td>Numérico</td><td>Define el valor mínimo de depósito requerido para que el bono cashback aplique.</td></tr><tr><td><strong><code>Métodos de pago aplicables para el depósito</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar los métodos de pago autorizados, los cuales serán considerados válidos para los depósitos y retiros efectuados por el usuario.</td></tr></tbody></table>

Solo se consideran válidas las transacciones **completadas** para calcular y aplicar a este tipo de bono cashback. [<sub>(</sub><sub>_Mas información_</sub><sub>)</sub>](cashback.md#id-4.-validaciones-y-reglas-de-negocio)

{% hint style="info" %}
**Ejemplo:**&#x20;

1. Porcentaje cashback: **10%**
2. Métodos válidos: **Tarjeta de crédito**
3. Monto mínimo neto: **$50.000**

**Jugador A:**

* Deposita $200.000 con tarjeta de crédito.
* Retira $100.000.
* Neto = $200.000 - $100.000 = **$100.000**

> Si supera el mínimo, se aplica:\
> **Cashback =** (**$100.000 \* 10%) = $10.000**

**Jugador B:**

* Deposita $100.000 con un método **no válido**.
* Retira $50.000.
* Neto = $0 - $50.000 = **$-50.000**&#x20;

> No supera el mínimo, porque el depósito **no** se considera por el método\
> ❌**No se entrega cashback**
{% endhint %}
{% endtab %}
{% endtabs %}

#### **3.4. Validaciones para el pago**

Permite definir las condiciones que los usuarios deben cumplir para que el bono cashback sea [redimido](https://virtualsoft.gitbook.io/untitled/glosario/#redimido), asegurando que el bono se entregue únicamente a los usuarios que cumplen con las validaciones configuradas.

<table><thead><tr><th width="139">Campo</th><th width="115">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cuenta verificada</code></strong></td><td>Interruptor</td><td><p>Permite definir si el cashback se acreditará únicamente a usuarios verificados.</p><blockquote><p>Esta condición se valida en el momento de la <strong>acreditación del cashback</strong>.</p></blockquote></td></tr><tr><td><strong><code>Retiros pendientes</code></strong></td><td>Interruptor</td><td><p>Excluye a usuarios que tengan retiros en estado activo o pendiente de aprobación. </p><blockquote><p>Esta condición se evalúa en el momento de la <strong>acreditación del cashback.</strong></p></blockquote></td></tr><tr><td><strong><code>Bonos activos</code></strong></td><td>Interruptor</td><td><p>Excluye a usuarios que tengan bonos activos. Al activarlo mostrará una lista con los tipos de bonos, es necesario seleccionar para que bonos aplicará.</p><blockquote><p>Solo se consideran bonos en estado <strong>activo</strong>. Esta condición se evalúa en el momento de la <strong>redención del cashback</strong>.</p></blockquote></td></tr><tr><td><strong><code>Saldo en cuenta</code></strong></td><td>Interruptor</td><td><p>Limita el cashback a usuarios que únicamente tengan saldo disponible en su cuenta. </p><blockquote><p>Esta condición se evalúa en el momento de la <strong>redención del cashback</strong>.</p></blockquote></td></tr><tr><td><strong><code>Apuestas abiertas</code></strong></td><td>Interruptor</td><td><p>Excluye a los usuarios que tengan apuestas abiertas en la vertical de deportivas.</p><blockquote><p>Esta validación se realiza al momento de la <strong>redención del cashback</strong> y, de cumplirse, el usuario queda <strong>excluido del beneficio en todas las verticales</strong>.</p></blockquote></td></tr></tbody></table>

#### 3.5. Configuraciones moneda

<table><thead><tr><th width="154.5555419921875">Campo </th><th width="152.6666259765625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><p><strong><code>Porcentaje de</code></strong> </p><p><strong><code>devolución</code></strong></p></td><td>Numérico </td><td>Indica el porcentaje usado para calcular el monto a retornar, ya sea sobre la apuesta perdida o sobre el valor neto (<strong>depósitos – retiros</strong>) del periodo.</td></tr><tr><td><strong><code>Pago máximo</code></strong></td><td>Numérico</td><td>Define el monto máximo que el sistema podrá retornar al usuario, ya sea por apuestas perdidas o por su neto de transacciones.</td></tr><tr><td><strong><code>Pago mínimo</code></strong></td><td>Numérico</td><td>Define el monto mínimo que el sistema podrá retornar al usuario, ya sea por apuestas perdidas o por su neto de transacciones.</td></tr><tr><td><p><strong><code>Seleccionar</code></strong> </p><p><strong><code>archivo</code></strong></p></td><td>Botón </td><td>Carga un archivo en formato CSV con el ID de los usuarios que tendrán acceso a este bono</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón</td><td>Utiliza este botón para validar el ID de los jugadores que se cargaron en el archivo CSV</td></tr></tbody></table>

#### 3.6. Configuraciones finales.

<table><thead><tr><th width="192.33331298828125">Campo</th><th width="150.3333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><p><strong><code>¿Cliente puede</code></strong> </p><p><strong><code>repetir bono?</code></strong></p></td><td>Botón selector </td><td>Define si el usuario podrá recibir el bono más de una vez dentro de la misma campaña.</td></tr><tr><td><p><strong><code>¿Es para programa</code></strong> </p><p><strong><code>de fidelización?</code></strong></p></td><td>Botón selector</td><td>Indica si el bono está destinada al programa de fidelización de usuarios.</td></tr><tr><td><p><strong><code>¿Cliente puede</code></strong> </p><p><strong><code>recibir otros bonos</code></strong> </p><p><strong><code>adicionales</code></strong> </p><p><strong><code>después del actual?</code></strong></p></td><td>Botón selector</td><td>Si está en "Sí", el sistema asignará al usuario el bono más compatible disponible; si no existe otro, se aplicará el bono actual.</td></tr><tr><td><strong><code>Tipo de bono</code></strong></td><td>Lista desplegable </td><td>Especifica si este bono se asignará únicamente a los usuarios que se registren en la plataforma.</td></tr></tbody></table>

***

### 4.  Validaciones y Reglas de negocio

* Para que este bono se active y se retorne el saldo al usuario la apuesta debe estar en estado cerrada y perdida.
* Si algún campo obligatorio no está configurado el bono no se creará.
* Los valores ingresados para **monto**, **monto mínimo, mínima cantidad de selecciones**, **cuota mínima por selección**, y **cuota total mínima** deben ser **mayores a 0**.
* Si los retiros del usuario superan sus depósitos, el neto resulta negativo y el bono Cashback de tipo transacciones en este caso no aplica.
* Solo perfiles con permiso de crear cashback podrán ver y editar en este módulo.
* El campo **`¿Es para?`** determina **en qué módulo del sistema** quedará disponible el bono cashback.
  * Al seleccionar una opción, el bono **solo podrá utilizarse dentro de la funcionalidad seleccionada**.
  * Una vez habilitado, el bono deberá **asignarse a una campaña o activarse** desde el módulo correspondiente (_por ejemplo, CRM_).
* El bono solo se le pagará al usuario cuando esté cerca de su fecha de finalización.
* Para que un bono de cashback se le asigne a un usuario es necesario que este tenga su cuenta verificada.

***

### 5. Control de Versiones

<details>

<summary>Historial de versiones</summary>

<table><thead><tr><th>Versión</th><th>Fecha</th><th width="165">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>08/09/2025</td><td>Ronald Peláez</td><td>Documento inicial </td></tr><tr><td>1.1</td><td>08/09/2025</td><td>Karol Navia</td><td>Agregar columna asignación de bono</td></tr><tr><td>1.2</td><td>14/11/2025</td><td>David Velasquez</td><td>Incorporación del tipo de producto "<strong>Transacciones</strong>"</td></tr><tr><td>1.3</td><td>06/01/2026</td><td>David Velasquez</td><td>Incorporación de la sección <strong>validaciones para el pago</strong></td></tr><tr><td>1.4</td><td>20/01/2026</td><td>David Velasquez</td><td>Incorporación del campo "<strong><code>¿Es para?</code>"</strong></td></tr><tr><td>1.5</td><td>20/01/2026</td><td>Ronald Peláez</td><td>Actualización en la sección "<strong>validaciones para el pago"</strong></td></tr><tr><td>1.5</td><td>04/03/2026</td><td>Ronald Peláez</td><td>Ajuste en el campo <strong><code>¿Es para?</code></strong></td></tr></tbody></table>

</details>
