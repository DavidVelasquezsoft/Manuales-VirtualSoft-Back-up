# Creación bono depósito para Digitain

<mark style="color:$info;">Permite crear un bono de tipo depósito asociado al proveedor Digitain. El bono se otorga al usuario cuando realiza un depósito que cumple las condiciones definidas en el formulario, y se acredita como saldo bono, el cual debe utilizarse en apuestas bajo las reglas configuradas para poder convertirse en saldo real.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Torneos y bonos > Crear bono > País > Bono Depósito

***

### 2. Visualización general

<figure><img src="../../../../../.gitbook/assets/BONO DEPOSITO.png" alt=""><figcaption><p>Figura #1: Captura de pantalla creación de Bono Depósito.</p></figcaption></figure>

***

### 3. ¿Cómo funciona este bono para Digitain?

El bono depósito para Digitain entrega al usuario un **saldo bono** cuando realiza un depósito que cumple las condiciones configuradas. Ese saldo no es retirable, para convertirlo en saldo real, el usuario debe apostarlo cumpliendo el **rollover** y las reglas definidas en este formulario.

#### **3.1. Conceptos clave**

{% hint style="warning" %}
**Nota:** Estos conceptos son la base del funcionamiento del bono y se utilizan a lo largo de todo el manual, por lo que conocerlos facilita la comprensión de cada configuración del formulario.
{% endhint %}

<table><thead><tr><th width="118.4259033203125">Concepto</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Saldo bono</strong></td><td>Saldo que recibe el usuario al obtener el bono. Puede utilizarse únicamente para apostar y no es retirable hasta cumplir las condiciones del bono.</td></tr><tr><td><strong>Factor de rollover</strong></td><td>Número por el cual se multiplica el valor del bono para obtener el rollover. Un factor mayor exige apostar más veces el valor entregado.</td></tr><tr><td><strong>Rollover</strong></td><td>Monto total que el usuario debe apostar para liberar el bono. Se calcula multiplicando el valor del bono por el factor de rollover configurado. Contabiliza el dinero apostado, no las ganancias obtenidas.</td></tr><tr><td><strong>Saldo real</strong></td><td>Saldo disponible del usuario, el cual puede retirar o utilizar libremente.</td></tr></tbody></table>

#### **3.2. Ciclo del bono, paso a paso**

{% stepper %}
{% step %}
**El usuario obtiene el bono**

El usuario realiza un depósito que cumple las condiciones configuradas _(monto mínimo, pasarela de pago habilitada, número de depósito, etc...)_ y el sistema le acredita el saldo bono correspondiente.
{% endstep %}

{% step %}
**El sistema calcula el rollover**

Al entregarse el bono, el sistema calcula el monto que el usuario debe apostar para liberarlo:

_Rollover = Valor del bono × Factor de rollover_
{% endstep %}

{% step %}
**El usuario apuesta con el saldo bono**

El usuario realiza apuestas utilizando el saldo bono, respetando las reglas configuradas _(cuotas mínimas y máximas, cantidad de selecciones, productos y eventos habilitados)_. Cada apuesta válida el monto apostado descuenta del rollover pendiente.
{% endstep %}

{% step %}
**El rollover se completa**

Cuando el monto apostado alcanza el rollover requerido, la condición queda cumplida. El saldo bono restante en ese momento se acredita automáticamente como saldo real y queda disponible para el usuario.
{% endstep %}

{% step %}
**El bono no se cumple**

Si el usuario agota su saldo bono antes de completar el rollover, o si el bono expira, el saldo bono se pierde y no se convierte en saldo real.
{% endstep %}
{% endstepper %}

{% hint style="info" %}
**Ejemplo del ciclo completo**

Un bono de **$10** con factor de rollover **x5** genera un rollover de **$50** _(10 × 5)_. Es decir, el usuario debe apostar $50 en total con saldo bono para liberar el bono.

**Al recibir el bono:** cuenta con $10 de saldo bono y le faltan $50 por apostar.

**Apuesta sus $10 y gana.** Como apostó $10, ahora le faltan $40 por apostar. Su saldo bono sube a $25 gracias a la ganancia.

**Apuesta esos $25 y vuelve a ganar.** Le faltan $15 por apostar y su saldo bono sube a $35.

**Apuesta $20.** Con esta apuesta supera los $15 que le faltaban, por lo que el rollover queda **cumplido**. Su saldo bono restante es de $15.

**Resultado:** Una vez completado el rollover, el saldo restante del bono se convierte en saldo real. El saldo con el que finalice la última apuesta, gane o pierda, será el saldo real final disponible para retirar.
{% endhint %}

{% hint style="warning" %}
**Nota:** El rollover contabiliza únicamente el dinero apostado, sin importar si las apuestas resultan ganadoras o perdedoras. Las ganancias obtenidas incrementan el saldo bono disponible, pero no reducen el rollover pendiente.
{% endhint %}

***

### 4. Acciones disponibles en el módulo

<table><thead><tr><th width="232">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="creacion-bono-deposito-para-digitain.md#id-5.-configuraciones-del-bono"><strong>Configurar bono depósito</strong></a></td><td><p>Permite configurar un bono de tipo depósito mediante el formulario disponible en este módulo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Los campos cuyo nombre finaliza con un asterisco (<mark style="color:$danger;">*</mark>) son obligatorios para la creación del bono.</p></div></td></tr><tr><td><strong>Configurar términos y condiciones del bono</strong></td><td>En la parte final del formulario se encuentra el botón <strong>"</strong><em><strong>Ver términos y condiciones</strong></em><strong>"</strong>, el cual despliega un editor de texto donde se ingresan los términos y condiciones aplicables al bono.</td></tr><tr><td><strong>Crear bono</strong></td><td>Envía la información registrada en el formulario y genera el bono en el sistema.</td></tr></tbody></table>

***

### 5. Configuraciones del bono

<table><thead><tr><th width="128.00006103515625">Campo</th><th width="119.4444580078125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Botón</td><td><p>Despliega los campos de fecha que definen el período de vigencia del bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Es posible configurar múltiples rangos de fechas mediante el botón <strong>"</strong><em><strong>Agregar</strong></em><strong>"</strong>, una vez establecidas la <strong>fecha inicial</strong> y la <strong>fecha final</strong> de cada rango.</p></div></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre que identifica el bono en la plataforma.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Numérico</td><td><p>Define el orden de asignación de bonos a los usuarios. Un número mayor indica mayor prioridad.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Con tres bonos configurados así:</p><ul><li><strong>Bono A:</strong> 1</li><li><strong>Bono B:</strong> 2</li><li><strong>Bono C:</strong> 3</li></ul><p>El sistema da preferencia al <strong>Bono C</strong>, por tener la prioridad más alta.</p></div><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Los bonos de bienvenida pueden configurarse con la prioridad que se requiera, siempre que sea la misma para todos.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Detalles adicionales del bono que se visualizan en la plataforma de usuarios online.</td></tr><tr><td><strong><code>URL Imagen principal</code></strong></td><td>URL</td><td>Enlace de la imagen que se muestra al usuario al visualizar el bono.</td></tr><tr><td><strong><code>Fecha de expiración o Días</code></strong></td><td>Selector</td><td><p>Define el plazo para redimir el bono. Con la opción <strong>"</strong><em><strong>Días</strong></em><strong>"</strong> se ingresa la cantidad de días hasta su vencimiento; con la opción <strong>"</strong><em><strong>Fecha</strong></em><strong>"</strong> se indica la fecha exacta de expiración. Cumplido el plazo, el bono queda inactivo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Los campos <strong><code>Días</code></strong> y <strong><code>Fecha expiración</code></strong> son dinámicos y se visualizan según la opción seleccionada.</p></div></td></tr><tr><td><strong><code>Fecha de expiración o Días - Bonos pendientes</code></strong></td><td>Selector</td><td>Define el plazo para que un bono en estado pendiente pase a <strong>"</strong><em><strong>Expirado</strong></em><strong>"</strong>. Con la opción <strong>"<code>Días</code>"</strong> se ingresa la cantidad de días tras los cuales expira; con la opción <strong>"<code>Fecha</code>"</strong> se indica la fecha exacta del cambio de estado. Cumplido el plazo, el bono pendiente se marca automáticamente como <strong>"</strong><em><strong>Expirado</strong></em><strong>"</strong>.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selector</td><td>Define el acceso al bono <em>(público para todos los jugadores o privado solo para jugadores VIP)</em>.</td></tr><tr><td><strong><code>Abierto para todos los jugadores</code></strong></td><td>Selector</td><td>Indica si el bono aplica para todos los jugadores. En caso contrario, habilita el campo <strong><code>Cantidad de jugadores</code></strong> para definir cuántos pueden acceder.</td></tr><tr><td><strong><code>Detalle de Campaña</code></strong></td><td>Lista desplegable</td><td><p>Define la clasificación específica del bono, facilitando su identificación, trazabilidad y análisis desde la administración de bonos.</p><p>Este campo es <strong>obligatorio</strong> y admite una única categoría entre las opciones del sistema <em>(por ejemplo: Bono de registro, Referidos, CRM fidelización)</em>. Si no se selecciona, el sistema muestra un mensaje de error.</p></td></tr><tr><td><strong><code>¿Se dará bono con algún proveedor?</code></strong></td><td>Selector</td><td>Indica si el bono se otorga a través de un proveedor externo. Al seleccionar <strong>"</strong><em><strong>Sí</strong></em><strong>"</strong>, se habilita el campo <strong><code>Seleccione el proveedor</code></strong>.</td></tr><tr><td><strong><code>Seleccione el proveedor</code></strong></td><td>Selector</td><td>Define el proveedor al que aplica el bono. Para este tipo de bono corresponde seleccionar <strong>Digitain</strong>.</td></tr><tr><td><strong><code>¿El jugador debe usar el bono en una sola apuesta?</code></strong></td><td>Selector</td><td><p>Define si el usuario puede distribuir su saldo bono en varias apuestas o si debe utilizarlo en una única apuesta.</p><ul><li><strong>Sí:</strong> el usuario apuesta la totalidad del saldo bono en una sola apuesta.</li><li><strong>No:</strong> el usuario puede realizar tantas apuestas como desee mientras disponga de saldo bono.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> En ambos casos el usuario debe completar el rollover configurado para liberar el bono.</p></div></td></tr><tr><td><strong><code>¿El jugador puede hacer cashout con apuestas del bono?</code></strong></td><td>Selector</td><td><p>Define si el usuario puede realizar <a href="https://virtualsoft.gitbook.io/untitled/glosario#cashout">cashout</a> en las apuestas efectuadas con el saldo bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El cashout no afecta el avance del rollover. El monto apostado se descuenta del rollover pendiente en el momento de realizar la apuesta, independientemente de que esta se cierre anticipadamente mediante cashout.</p></div></td></tr><tr><td><strong><code>¿El jugador puede cancelar su bono?</code></strong></td><td>Selector</td><td><p>Define si el usuario puede renunciar al bono antes de completar el rollover.</p><ul><li><strong>Sí:</strong> el usuario puede cancelar el bono desde la plataforma. Al hacerlo, pierde el saldo bono y las condiciones asociadas quedan sin efecto.</li><li><strong>No:</strong> el bono permanece activo hasta que el usuario complete el rollover, agote el saldo bono o el bono expire.</li></ul></td></tr><tr><td><strong><code>Factor de rollover del BONO</code></strong></td><td>Numérico</td><td><p>Número por el cual se multiplica el valor del bono para determinar el monto total que el usuario debe apostar antes de liberarlo.</p><p><strong>Fórmula:</strong><br><em>Rollover = Valor del bono × Factor de rollover</em></p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Con un bono de <strong>$50</strong> y un factor de rollover de <strong>2</strong>, el rollover es de <strong>$100</strong>. El usuario debe apostar $100 en total para liberar el bono; hasta alcanzar ese monto, el saldo bono no se convierte en saldo real.</p></div></td></tr><tr><td><strong><code>¿Cuota por?</code></strong></td><td>Selector</td><td><p>Define cómo se evalúan las cuotas de las apuestas realizadas con el saldo bono. Determina cuáles apuestas son válidas para el bono y, por lo tanto, cuáles descuentan del rollover.</p><ul><li><strong>Por selecciones:</strong> la cuota se evalúa de forma individual, por cada selección que compone la apuesta.</li><li><strong>Por totales:</strong> la cuota se evalúa de forma conjunta, sobre el resultado total de todas las selecciones.</li></ul></td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<details>

<summary>🔽 Cuota por: Selecciones</summary>

Define las cuotas que debe cumplir cada selección de una apuesta para que esta sea válida con el saldo bono. Las apuestas que no cumplan estos valores no se aceptan ni descuentan del rollover.

<table><thead><tr><th width="141.2962646484375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mínima cuota por selecciones</code></strong></td><td>Cuota mínima que debe tener cada selección incluida en la apuesta.</td></tr><tr><td><strong><code>Máxima cuota por selecciones</code></strong></td><td>Cuota máxima permitida para cada selección incluida en la apuesta.</td></tr><tr><td><strong><code>Mínima cantidad en selecciones</code></strong></td><td>Número mínimo de selecciones que debe contener la apuesta.</td></tr><tr><td><p><strong><code>Mínima cuota total</code></strong> </p><p><em>(no editable)</em></p></td><td><p>Cuota total mínima que debe alcanzar la apuesta. El sistema la calcula elevando la cuota mínima por selección al número de selecciones mínimas requeridas.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si la cuota mínima por selección es <strong>2</strong> y se requieren <strong>3 selecciones</strong>, la cuota total mínima será <strong>8</strong> <em>(2 × 2 × 2 = 8)</em>.</p></div></td></tr></tbody></table>

</details>

<details>

<summary>🔽 Cuota por: Totales</summary>

Define las cuotas que debe cumplir la apuesta en su conjunto para ser válida con el saldo bono. Las apuestas que no cumplan estos valores no se aceptan ni descuentan del rollover.

<table><thead><tr><th width="133.333251953125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mínima cuota por totales</code></strong></td><td>Cuota mínima que debe alcanzar la apuesta considerando todas sus selecciones.</td></tr><tr><td><strong><code>Máxima cuota por totales</code></strong></td><td>Cuota máxima permitida para la apuesta considerando todas sus selecciones.</td></tr><tr><td><strong><code>Mínima cantidad en selecciones</code></strong></td><td>Número mínimo de selecciones que debe contener la apuesta.</td></tr><tr><td><p><strong><code>Mínima cuota total</code></strong> </p><p><em>(no editable)</em></p></td><td><p>Cuota total mínima que debe alcanzar la apuesta. El sistema la calcula elevando la cuota mínima por totales a la cantidad mínima de selecciones requeridas.</p><p></p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si la cuota mínima por totales es <strong>2</strong> y se requieren <strong>3 selecciones</strong>, la cuota total mínima será <strong>8</strong> <em>(2 × 2 × 2 = 8)</em>.</p></div></td></tr></tbody></table>

</details>
{% endcolumn %}
{% endcolumns %}

***

<details>

<summary>Opciones avanzadas</summary>

<table><thead><tr><th width="191.3333740234375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Código Global</code></strong></td><td>Código configurado desde el BackOffice con el cual el bono cuenta con una cantidad máxima de usuarios.</td></tr><tr><td><strong><code>Códigos Promocionales</code></strong></td><td>Código promocional configurado desde el BackOffice, utilizado para guiar las campañas promocionales.</td></tr><tr><td><strong><code>¿Habilitar códigos únicos?</code></strong></td><td><p>Define si el bono puede ser <a href="https://open-2c.gitbook.com/url/preview/site_E7EPL/glosario/~/revisions/lyO9OIXttMrjpQGurqj2#redimir">redimido</a> mediante códigos únicos generados automáticamente por el sistema.</p><ul><li><strong>Sí:</strong> activa la redención con códigos únicos aleatorios generados por la plataforma.</li><li><strong>No:</strong> no se generan códigos para este bono.</li></ul></td></tr></tbody></table>

</details>

***

<table data-header-hidden><thead><tr><th width="131.5">Campo</th><th width="118.33343505859375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Pasarelas de pago</code></strong></td><td>Lista desplegable</td><td><p>Define una, varias o todas las pasarelas de pago habilitadas para que el depósito del usuario dé acceso al bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si no se selecciona ninguna pasarela, el bono no puede entregarse.</p></div></td></tr><tr><td><strong><code>Puntos de venta es permitido</code></strong></td><td>Selector</td><td>Habilita el uso del bono para depósitos realizados en puntos de venta. Al activarse, se despliegan las siguientes configuraciones.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="169">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Regiones punto de venta</code></strong></td><td>Define las regiones en las que aplica el bono. <em>(El bono aplica únicamente en la zona seleccionada)</em>.</td></tr><tr><td><strong><code>Departamentos punto de venta</code></strong></td><td>Define los departamentos en los que aplica el bono.</td></tr><tr><td><strong><code>Ciudades punto de venta</code></strong></td><td>Define las ciudades en las que aplica el bono.</td></tr><tr><td><strong><code>Puntos de venta</code></strong></td><td>Define los puntos de venta en los que aplica el bono.</td></tr><tr><td><strong><code>Puntos de venta no permitidos</code></strong></td><td>Define los puntos de venta en los que no aplica el bono.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="129.27783203125">Campo</th><th width="118.33343505859375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Producto Rollover</code></strong></td><td>Lista desplegable</td><td><p>Define el producto en el que el usuario debe apostar para que sus apuestas descuenten del rollover. Las opciones disponibles son: <strong>Directo</strong>, <strong>Casino</strong>, <strong>Sportsbook</strong>, <strong>Live Casino</strong> y <strong>Virtual</strong>.</p><ul><li><strong>Directo</strong> <em>(opción por defecto)</em><strong>:</strong> el bono no requiere configuraciones adicionales y las apuestas descuentan del rollover sin restricciones por producto.</li><li><strong>Sportsbook:</strong> habilita configuraciones específicas de apuestas deportivas, detalladas a continuación.</li></ul></td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<details>

<summary><strong>Configuraciones: Sportsbook</strong></summary>

Las secciones **Deporte, Mercados, Ligas y Partidos** comparten la misma estructura y configuración. Los campos y condiciones son los mismos en todas, variando únicamente el nivel al que se aplican _(deporte, mercado, liga o partido)_.

<table data-search="false"><thead><tr><th width="122.66650390625">Campo</th><th width="258.0103759765625">Descripción</th></tr></thead><tbody><tr><td><strong><code>¿Todas las condiciones son obligatorias?</code></strong></td><td>Define si las condiciones configuradas deben cumplirse en su totalidad. Con la opción "<em><strong>Sí</strong></em>", se revisan una a una y todas deben cumplirse para aplicar la regla. Con la opción "<em><strong>No</strong></em>", cada condición se evalúa de forma independiente y basta con que alguna se cumpla.</td></tr><tr><td><strong><code>¿Se dará un bono del proveedor Altenar?</code></strong></td><td>Indica si se otorga un bono proveniente del proveedor Altenar. Con la opción "<em><strong>Sí</strong></em>", se habilitan los campos <strong><code>Bono plan Id</code></strong> <em>(identificador del plan de bono definido por el proveedor)</em> y <strong><code>Código del bono</code></strong> <em>(código único del bono asignado por el proveedor)</em>, ambos obligatorios y diligenciados con la información proporcionada por el proveedor. Con la opción "<em><strong>No</strong></em>", no se otorga este beneficio y dichos campos no son requeridos.</td></tr><tr><td><strong><code>Deporte, Mercados, Ligas o Partidos</code></strong></td><td>Define los identificadores <em>(ID)</em> de los elementos a los que aplica la configuración <em>(deportes, mercados, ligas o partidos)</em>. Admite múltiples ID separados por comas.</td></tr><tr><td><strong><code>Tipo de apuesta</code></strong></td><td>Define el tipo de apuesta al que aplica la configuración: <strong>Single</strong> <em>(apuesta simple)</em>, <strong>Multiple</strong> <em>(apuesta combinada)</em> o <strong>System</strong> <em>(apuestas de sistema)</em>.</td></tr><tr><td><strong><code>Tipo de evento</code></strong></td><td>Define el tipo de evento al que aplica la configuración: <strong>Both</strong> <em>(pre-match y en vivo)</em>, <strong>Pre-match</strong> <em>(antes del evento)</em> o <strong>Live</strong> <em>(en vivo)</em>.</td></tr><tr><td><strong><code>Mínima cantidad en selecciones</code></strong></td><td>Número mínimo de selecciones que debe tener una apuesta para que aplique la configuración.</td></tr><tr><td><strong><code>Mínima cuota en selecciones</code></strong></td><td>Cuota mínima que debe tener cada selección dentro de la apuesta.</td></tr><tr><td><strong><code>Mínima cuota total</code></strong></td><td>Cuota mínima total que debe cumplir la apuesta.</td></tr><tr><td><strong><code>Repetir Partidos</code></strong></td><td>Define si se permite incluir el mismo partido más de una vez dentro de una apuesta.</td></tr><tr><td><strong><code>Repetir Mercados</code></strong></td><td>Define si se permite incluir el mismo mercado más de una vez dentro de una apuesta.</td></tr></tbody></table>

</details>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="131.5">Campo</th><th width="118.33343505859375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Número de depósitos</code></strong></td><td>Lista desplegable</td><td>Define en cuál o cuáles depósitos se asigna el bono al usuario <em>(primer depósito, próximo depósito o depósito específico)</em>. Con la opción <strong>"</strong><em><strong>Específico</strong></em><strong>"</strong>, se habilita el campo <strong><code>Orden depósito</code></strong>, donde se indica el número exacto de depósito al que aplica el bono.</td></tr><tr><td><strong><code>Valor del bono como máximo valor a sumar para</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#rollover"><strong><code>rollover</code></strong></a></td><td>Selector</td><td><p>Define si el valor del bono se toma en su totalidad o hasta un tope máximo al calcular el monto que el usuario debe apostar.</p><ul><li><strong>Sí:</strong> el cálculo del rollover considera el valor del bono hasta el máximo permitido configurado.</li><li><strong>No:</strong> el cálculo del rollover considera el valor total del bono entregado.</li></ul><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Depósito de <strong>$200</strong>, bono de <strong>$500</strong> y factor de rollover <strong>x5</strong>.</p><ul><li><strong>Sí</strong> <em>(con un máximo permitido de $300)</em>: (200 + 300) × 5 = <strong>$2.500</strong> en apuestas requeridas.</li><li><strong>No:</strong> (200 + 500) × 5 = <strong>$3.500</strong> en apuestas requeridas.</li></ul></div></td></tr><tr><td><strong><code>Asignación de bono</code></strong></td><td>Lista desplegable</td><td><p>Define si se otorga <strong>dinero</strong> o un <strong>bono previamente creado</strong>. Con la opción de bono, el usuario recibe un bono adicional al ya configurado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> En esta sección también puede asignarse el bono creado por el proveedor Altenar.</p></div></td></tr><tr><td><strong><code>Campaña de Marketing</code></strong></td><td>Lista desplegable</td><td>Define una o varias campañas asociadas al bono.</td></tr><tr><td><strong><code>Saldo a asignar</code></strong></td><td>Lista desplegable</td><td><p>Tipo de saldo que recibe el usuario al <a href="https://open-2c.gitbook.com/url/preview/site_E7EPL/glosario/~/revisions/lyO9OIXttMrjpQGurqj2#redimir">redimir</a> el bono <em>(saldo créditos o puntos lealtad)</em>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La opción <strong>puntos de lealtad</strong> admite únicamente el cálculo de bonificación con <strong>Bono fijo</strong>.</p></div></td></tr><tr><td><strong><code>Cálculo de bonificación</code></strong></td><td>Selector</td><td>Define la modalidad con la que se calcula el bono por depósito: <strong>Monto fijo</strong>, que otorga un valor previamente establecido, o <strong>Porcentaje</strong>, que aplica un porcentaje sobre el monto depositado por el usuario.</td></tr></tbody></table>

***

<details>

<summary>Moneda</summary>

Al seleccionar la moneda correspondiente al país con el que se ingresó a la plataforma, se despliegan las siguientes configuraciones:

<figure><img src="../../../../../.gitbook/assets/image (299).png" alt=""><figcaption><p>Figura #2: Captura de pantalla configuración moneda.</p></figcaption></figure>

<table data-search="false"><thead><tr><th width="122.9444580078125">Campo</th><th width="125.888916015625">Tipo</th><th width="344.61114501953125">Descripción</th></tr></thead><tbody><tr><td><strong><code>Monto de bono fijo</code></strong></td><td>Numérico</td><td><p>Monto que recibe el usuario como saldo bono al realizar un depósito.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo está disponible únicamente cuando el campo <strong><code>Cálculo de bonificación</code></strong> tiene seleccionada la opción <strong>Bono Fijo</strong>.</p></div></td></tr><tr><td><strong><code>Mínimo depósito</code></strong></td><td>Numérico</td><td>Valor mínimo que debe depositar el usuario para acceder al bono.</td></tr><tr><td><strong><code>Máxima apuesta tomada para rollover</code></strong></td><td>Numérico</td><td><p>Monto máximo de una apuesta que se contabiliza para el rollover. Si el usuario apuesta un valor superior, el excedente no descuenta del rollover pendiente.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Con una máxima apuesta de <strong>$20</strong>, si el usuario realiza una apuesta de <strong>$50</strong>, solo se descuentan <strong>$20</strong> del rollover pendiente.</p></div></td></tr><tr><td><strong><code>Cupo máximo</code></strong></td><td>Numérico</td><td>Cantidad máxima de usuarios que pueden acceder a este bono.</td></tr><tr><td><strong><code>Máximo depósito</code></strong></td><td>Numérico</td><td>Valor máximo depositado que se considera para acceder al bono.</td></tr><tr><td><strong><code>Pago máximo</code></strong></td><td>Numérico</td><td>Monto máximo que puede recibir el usuario como saldo real al liberar este bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Archivo CSV</td><td>Archivo <a href="https://virtualsoft.gitbook.io/untitled/glosario#csv">CSV</a> con los ID de los usuarios que pueden acceder al bono.</td></tr></tbody></table>

</details>

***

<table data-header-hidden><thead><tr><th width="232.99993896484375">Campo</th><th width="92.9998779296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>¿Cliente puede repetir bono?</code></strong></td><td>Selector</td><td>Define si un mismo usuario puede redimir este bono en más de una ocasión.</td></tr><tr><td><strong><code>¿Cliente puede recibir otros bonos adicionales después del actual?</code></strong></td><td>Selector</td><td>Define si el usuario puede recibir bonos adicionales al que se está creando.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* Si algún campo obligatorio no está configurado, el bono no se crea.
* El saldo bono no es retirable: se convierte en saldo real únicamente cuando el usuario completa el rollover configurado.
* El rollover contabiliza el monto apostado, sin importar el resultado de las apuestas. Las ganancias incrementan el saldo bono, pero no reducen el rollover pendiente.
* Solo las apuestas que cumplen las reglas configuradas _(cuotas, cantidad de selecciones, producto y tipo de evento)_ descuentan del rollover.
* Si el usuario agota su saldo bono antes de completar el rollover, o si el bono expira, el saldo bono se pierde.
* Si no se selecciona ninguna pasarela de pago, el bono no puede entregarse.
* Si se configura un bono de depósito de tipo **privado** y los usuarios se cargan mediante archivo **.CSV**, el bono se asigna únicamente a los usuarios incluidos en ese archivo. Aunque posteriormente realicen un nuevo depósito cumpliendo las condiciones establecidas, no reciben un nuevo cupo, ya que este tipo de bono no permite reasignaciones una vez otorgado por carga masiva.

{% hint style="info" %}
**Ejemplo:**\
Los bonos de tipo **Referidos**, una vez creados y disponibles, se activan y habilitan desde el módulo de referidos: [Configuración #🔽 Referidos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#referidos "mention")
{% endhint %}

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>11/08/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
