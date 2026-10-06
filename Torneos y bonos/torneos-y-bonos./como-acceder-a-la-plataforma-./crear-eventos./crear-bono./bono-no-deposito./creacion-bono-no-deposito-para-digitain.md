# Creación bono no depósito para Digitain

<mark style="color:$info;">Crea un bono no depósito asociado al proveedor Digitain, el cual se entrega al usuario sin necesidad de que realice un depósito previo. El bono puede asignarse directamente a usuarios específicos o entregarse mediante códigos únicos, y se libera cuando el usuario cumple el rollover y las reglas de apuesta configuradas.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Torneos y Bonos > País > Bonos > Bono No Depósito

***

### 2. Visualización

<figure><img src="../../../../../.gitbook/assets/nodepo digi.png" alt=""><figcaption><p>Figura #1: Captura de pantalla creación de Bono No Depósito.</p></figcaption></figure>

***

### 3. ¿Cómo funciona este bono para Digitain?

El bono no depósito para Digitain **no requiere que el usuario realice un depósito** para obtenerlo: se entrega por asignación directa mediante archivo CSV o mediante códigos únicos. El saldo se acredita dentro del **sportsbook de Digitain**, donde el usuario lo utiliza para realizar apuestas deportivas respetando las reglas definidas _(cuotas, selecciones, tipo de apuesta y evento)_ y cuando se configuran, los deportes, ligas o partidos habilitados para el bono.

El campo **`¿Se dará bono freebet?`** determina cómo se libera ese saldo:

<table><thead><tr><th width="220">Configuración</th><th>Funcionamiento</th></tr></thead><tbody><tr><td><strong>Bono con rollover</strong><br><em>(<strong><code>¿Se dará bono freebet?</code></strong> = No)</em></td><td>El usuario debe apostar el monto del <a href="https://virtualsoft.gitbook.io/plantillas/glosario#rollover">rollover</a> configurado para que el saldo del bono se convierta en saldo real.</td></tr><tr><td><strong>Bono FreeBet</strong><br><em>(<strong><code>¿Se dará bono freebet?</code></strong> = Sí)</em></td><td>El bono no exige <a href="https://virtualsoft.gitbook.io/plantillas/glosario#rollover">rollover</a>. El usuario utiliza el saldo de inmediato y las ganancias obtenidas se acreditan como saldo real.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** El **FreeBet** corresponde a la denominación que utiliza el proveedor Digitain. Internamente el bono se crea y se gestiona igual que cualquier bono no depósito: la única diferencia es que no exige rollover, por lo que los campos relacionados dejan de ser obligatorios y no se tienen en cuenta.
{% endhint %}

#### **3.1. Conceptos clave**

{% hint style="warning" %}
**Nota:** Comprender estos conceptos es fundamental para configurar correctamente el bono, ya que cada uno determina cómo se entrega el saldo al usuario, qué debe cumplir para liberarlo y en qué momento se convierte en saldo real.
{% endhint %}

<table><thead><tr><th width="141.6666259765625">Concepto</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Saldo bono</strong></td><td>Saldo que recibe el usuario al obtener el bono, acreditado dentro del sportsbook de Digitain. Su disponibilidad depende de si el bono requiere rollover.</td></tr><tr><td><strong>Rollover</strong></td><td><p>Monto total que el usuario debe apostar para liberar el bono. Se calcula multiplicando el valor del bono por el factor de rollover configurado, y contabiliza el dinero apostado, no las ganancias obtenidas.</p><p><strong>Fórmula:</strong><br><em>Rollover = Valor del bono × Factor de rollover</em></p></td></tr><tr><td><strong>Apuesta válida</strong></td><td>Apuesta que cumple las condiciones configuradas en el bono <em>(cuotas, cantidad de selecciones, tipo de apuesta y evento, y los deportes, ligas o partidos habilitados)</em>. Únicamente estas apuestas descuentan del rollover pendiente.</td></tr><tr><td><strong>Saldo real</strong></td><td>Saldo disponible del usuario, el cual puede retirar o utilizar libremente.</td></tr></tbody></table>

#### **3.2. Formas de entrega**

<table><thead><tr><th width="158.33331298828125">Forma de entrega</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Asignación directa</strong><br><em>(archivo CSV)</em></td><td>El bono se asigna automáticamente a los usuarios incluidos en el archivo CSV cargado en el campo <strong><code>Jugadores</code></strong>, sin que estos realicen ninguna acción adicional.</td></tr><tr><td><strong>Códigos únicos</strong></td><td>El sistema genera un código único por cada usuario definido en el campo <strong><code>Cantidad de jugadores</code></strong>. El usuario redime el bono ingresando su código en la sección <strong>Mis bonos</strong> de la plataforma de usuarios online. Por ejemplo, con el valor <strong>5</strong> se generan <strong>5 códigos únicos</strong>, uno por usuario.</td></tr><tr><td><strong>Asignación desde CRM</strong></td><td>El CRM define el público objetivo y envía los usuarios a los que debe otorgarse el bono.</td></tr></tbody></table>

{% hint style="danger" %}
**Nota importante:** Para entregar el bono mediante códigos únicos es obligatorio habilitar el campo **`¿Habilitar códigos únicos?`** en las opciones avanzadas. De lo contrario, los códigos generados no funcionarán y los usuarios no podrán redimir el bono.
{% endhint %}

#### **3.3. Ciclo del bono, paso a paso**

El ciclo varía según la configuración del campo **`¿Se dará bono freebet?`**:

{% tabs %}
{% tab title="Bono con rollover" %}
{% stepper %}
{% step %}
**El usuario obtiene el bono**

El usuario recibe el bono por asignación directa, al estar incluido en el archivo CSV cargado, o al redimir su código único en la sección **Mis bonos** de la plataforma. El sistema le acredita el saldo bono dentro del sportsbook de Digitain.
{% endstep %}

{% step %}
**El sistema calcula el rollover**

Al entregarse el bono, el sistema calcula el monto que el usuario debe apostar para liberarlo:

_Rollover = Valor del bono × Factor de rollover_
{% endstep %}

{% step %}
**El usuario apuesta con el saldo bono**

El usuario realiza apuestas utilizando el saldo bono, respetando las reglas configuradas _(cuotas mínimas y máximas, cantidad de selecciones, productos y eventos habilitados)_. Por cada apuesta válida, el monto apostado descuenta del rollover pendiente.
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

Un bono de **$10** con factor de rollover **x5** genera un rollover de **$50** _(10 × 5)_. Es decir, el usuario debe apostar $50 en total con saldo bono para liberarlo.

**Al recibir el bono:** cuenta con $10 de saldo bono y le faltan $50 por apostar.

**Apuesta sus $10 y gana.** Como apostó $10, ahora le faltan $40 por apostar. Su saldo bono sube a $25 gracias a la ganancia.

**Apuesta esos $25 y vuelve a ganar.** Le faltan $15 por apostar y su saldo bono sube a $35.

**Apuesta $20.** Con esta apuesta supera los $15 que le faltaban, por lo que el rollover queda **cumplido**. Su saldo bono restante es de $15.

**Resultado:** una vez completado el rollover, el saldo restante del bono se convierte en saldo real. El saldo con el que finalice la última apuesta, gane o pierda, será el saldo real final disponible para retirar.
{% endhint %}

{% hint style="warning" %}
**Nota:** El rollover contabiliza únicamente el dinero apostado, sin importar si las apuestas resultan ganadoras o perdedoras. Las ganancias obtenidas incrementan el saldo bono disponible, pero no reducen el rollover pendiente.
{% endhint %}
{% endtab %}

{% tab title="Bono FreeBet" %}
{% stepper %}
{% step %}
**El usuario obtiene el bono**

El usuario recibe el bono por asignación directa, al estar incluido en el archivo CSV cargado, o al redimir su código único en la sección **Mis bonos** de la plataforma. El sistema le acredita el saldo bono dentro del sportsbook de Digitain, disponible de inmediato.
{% endstep %}

{% step %}
**El usuario apuesta con el saldo bono**

El usuario realiza apuestas utilizando el saldo bono, respetando las reglas configuradas _(cuotas mínimas y máximas, cantidad de selecciones, tipo de apuesta y evento)_. No debe completar un rollover para poder utilizarlo.
{% endstep %}

{% step %}
**Las ganancias se acreditan como saldo real**

Las ganancias obtenidas con las apuestas realizadas mediante el saldo bono se acreditan como saldo real y quedan disponibles para el usuario.
{% endstep %}

{% step %}
**El bono no se utiliza**

Si el usuario agota su saldo bono sin obtener ganancias, o si el bono expira antes de ser utilizado, el saldo bono se pierde.
{% endstep %}
{% endstepper %}

{% hint style="warning" %}
**Nota:** En esta modalidad los campos relacionados con el rollover no son obligatorios y no se tienen en cuenta en la configuración del bono.
{% endhint %}
{% endtab %}
{% endtabs %}

#### **3.4. Estados del bono**

Una vez entregado, el bono del usuario puede encontrarse en los siguientes estados:

<table><thead><tr><th width="160">Estado</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Activo</strong></td><td>El bono está disponible para que el usuario lo utilice.</td></tr><tr><td><strong>Inactivo</strong></td><td>El bono fue deshabilitado desde el BackOffice.</td></tr><tr><td><strong>Expirado</strong></td><td>El bono superó su fecha de vigencia o el tiempo de uso permitido tras su activación, configurado en el campo <strong><code>Fecha de expiración</code></strong>.</td></tr><tr><td><strong>Cancelado</strong></td><td>El usuario canceló el bono desde la vista del proveedor en la plataforma de usuarios online. Este estado solo es posible cuando el campo <strong><code>¿El jugador puede cancelar su bono?</code></strong> se configura en <strong>Sí</strong>.</td></tr></tbody></table>

***

***

### 4. Acciones disponibles en el módulo

<table><thead><tr><th width="200.3333740234375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="creacion-bono-no-deposito-para-digitain.md#id-5.-configuraciones-del-bono"><strong>Configurar bono no depósito</strong></a></td><td><p>Permite configurar un bono de tipo no depósito mediante el formulario disponible en este módulo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Los campos cuyo nombre finaliza con un asterisco (<mark style="color:$danger;">*</mark>) son obligatorios para la creación del bono.</p></div></td></tr><tr><td><strong>Configurar términos y condiciones del bono</strong></td><td>En la parte final del formulario se encuentra el botón <strong>"</strong><em><strong>Ver términos y condiciones</strong></em><strong>"</strong>, el cual despliega un editor de texto donde se ingresan los términos y condiciones aplicables al bono.</td></tr><tr><td><strong>Crear bono</strong></td><td>Envía la información registrada en el formulario y genera el bono en el sistema.</td></tr></tbody></table>

***

### 5. Configuraciones del bono

<table><thead><tr><th width="130.33343505859375">Campo</th><th width="116.33331298828125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Botón</td><td><p>Despliega los campos de fecha que definen el período de vigencia del bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Es posible configurar múltiples rangos de fechas mediante el botón <strong>"</strong><em><strong>Agregar</strong></em><strong>"</strong>, una vez establecidas la <strong>fecha inicial</strong> y la <strong>fecha final</strong> de cada rango.</p></div></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre que identifica el bono en la plataforma.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Numérico</td><td><p>Define el orden de asignación de bonos a los usuarios. Un número mayor indica mayor prioridad.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Con tres bonos configurados así:</p><ul><li><strong>Bono A:</strong> 1</li><li><strong>Bono B:</strong> 2</li><li><strong>Bono C:</strong> 3</li></ul><p>El sistema da preferencia al <strong>Bono C</strong>, por tener la prioridad más alta.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Detalles adicionales del bono que se visualizan en la plataforma de usuarios online.</td></tr><tr><td><strong><code>URL Imagen principal</code></strong></td><td>Texto</td><td>Enlace de la imagen que se muestra al usuario al visualizar el bono.</td></tr><tr><td><strong><code>Fecha de expiración</code></strong></td><td>Selector de fecha</td><td><p>Define el plazo para redimir el bono. Con la opción <strong>"</strong><em><strong>Días</strong></em><strong>"</strong> se ingresa la cantidad de días hasta su vencimiento; con la opción <strong>"</strong><em><strong>Fecha</strong></em><strong>"</strong> se indica la fecha exacta de expiración. Cumplido el plazo, el bono queda inactivo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Los campos <strong><code>Días</code></strong> y <strong><code>Fecha expiración</code></strong> son dinámicos y se visualizan según la opción seleccionada.</p></div></td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Determina si el bono es público <em>(todos los usuarios)</em> o privado <em>(VIP)</em>.</td></tr><tr><td><strong><code>Prefijo</code></strong></td><td>Texto</td><td><p>Utilizado como base para generar los códigos únicos de redención del bono, permitiendo identificarlo y diferenciarlo de los demás bonos registrados.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Cuando el bono se redime mediante códigos únicos, estos se generan utilizando el prefijo configurado.</p></div></td></tr><tr><td><strong><code>Cantidad de jugadores</code></strong></td><td>Numérico</td><td><p>Cantidad de usuarios que pueden acceder al bono. Este campo es <strong>obligatorio</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Cuando el bono se entrega mediante códigos únicos, el sistema genera un código por cada usuario definido en este campo. Por ejemplo, con el valor <strong>5</strong> se generan <strong>5 códigos únicos</strong>.</p></div></td></tr><tr><td><strong><code>Tipo de bono</code></strong></td><td>Lista desplegable</td><td>Define si el bono se asigna automáticamente al momento del registro del usuario o si no se asigna de forma automática.</td></tr><tr><td><strong><code>¿Eliminación por retiro?</code></strong></td><td>Selector</td><td>Define si el bono se elimina de la cuenta del usuario al generarse una nota de retiro.</td></tr><tr><td><strong><code>¿Se dará bono con algún proveedor?</code></strong></td><td>Selector</td><td>Indica si el bono se otorga a través de un proveedor externo. Al seleccionar <strong>"</strong><em><strong>Sí</strong></em><strong>"</strong>, se habilita el campo <strong><code>Seleccione el proveedor</code></strong>.</td></tr><tr><td><strong><code>Seleccione el proveedor</code></strong></td><td>Selector</td><td>Define el proveedor al que aplica el bono. Para este tipo de bono corresponde seleccionar <strong>Digitain</strong>.</td></tr><tr><td><strong><code>¿El jugador debe usar el bono en una sola apuesta?</code></strong></td><td>Selector</td><td><p>Define si el usuario puede distribuir su saldo bono en varias apuestas o si debe utilizarlo en una única apuesta.</p><ul><li><strong>Sí:</strong> el usuario apuesta la totalidad del saldo bono en una sola apuesta.</li><li><strong>No:</strong> el usuario puede realizar tantas apuestas como desee mientras disponga de saldo bono.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> En ambos casos el usuario debe completar el rollover configurado para liberar el bono.</p></div></td></tr><tr><td><strong><code>¿El jugador puede hacer cashout con apuestas del bono?</code></strong></td><td>Selector</td><td><p>Define si el usuario puede realizar <a href="https://virtualsoft.gitbook.io/untitled/glosario#cashout">cashout</a> en las apuestas efectuadas con el saldo bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El cashout no afecta el avance del rollover. El monto apostado se descuenta del rollover pendiente en el momento de realizar la apuesta, independientemente de que esta se cierre anticipadamente mediante cashout.</p></div></td></tr><tr><td><strong><code>¿El jugador puede cancelar su bono?</code></strong></td><td>Selector</td><td><p>Define si el usuario puede renunciar al bono antes de completar el rollover.</p><ul><li><strong>Sí:</strong> Permite al usuario cancelar el bono desde la plataforma. Al cancelarlo, pierde el saldo del bono, las condiciones asociadas quedan sin efecto y el estado del bono cambia a <strong>Cancelado</strong>.</li><li><strong>No:</strong> el bono permanece activo hasta que el usuario complete el rollover, agote el saldo bono o el bono expire.</li></ul></td></tr><tr><td><strong><code>¿Se dará bono freebet?</code></strong></td><td>Selector</td><td><p>Define si el bono se entrega como <strong>FreeBet</strong> en Digitain, es decir, sin exigir rollover para su uso.</p><ul><li><strong>Sí:</strong> el usuario utiliza el saldo del bono de inmediato, sin necesidad de completar un rollover. Los campos relacionados con el rollover dejan de ser obligatorios y no se tienen en cuenta en la configuración.</li><li><strong>No:</strong> el bono funciona con rollover; el usuario debe apostar el monto configurado para liberarlo.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> En ambos casos el usuario debe cumplir las condiciones de apuesta configuradas <em>(cuotas, selecciones, tipo de apuesta y evento)</em> para poder utilizar el saldo del bono.</p></div></td></tr><tr><td><strong><code>Factor de rollover del BONO</code></strong></td><td>Numérico</td><td><p>Número por el cual se multiplica el valor del bono para determinar el monto total que el usuario debe apostar antes de liberarlo.</p><p><strong>Fórmula:</strong><br><em>Rollover = Valor del bono × Factor de rollover</em></p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Con un bono de <strong>$50</strong> y un factor de rollover de <strong>2</strong>, el rollover es de <strong>$100</strong>. El usuario debe apostar $100 en total para liberar el bono; hasta alcanzar ese monto, el saldo bono no se convierte en saldo real.</p></div></td></tr><tr><td><strong><code>¿Cuota por?</code></strong></td><td>Selector</td><td><p>Define cómo se evalúan las cuotas de las apuestas realizadas con el saldo bono. Determina cuáles apuestas son válidas para el bono y, por lo tanto, cuáles descuentan del rollover.</p><ul><li><strong>Por selecciones:</strong> la cuota se evalúa de forma individual, por cada selección que compone la apuesta.</li><li><strong>Por totales:</strong> la cuota se evalúa de forma conjunta, sobre el resultado total de todas las selecciones.</li></ul></td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<details>

<summary>🔽 Cuota por: Selecciones</summary>

Define las cuotas que debe cumplir cada selección de una apuesta para que esta sea válida con el saldo bono. Las apuestas que no cumplan estos valores no se aceptan ni descuentan del rollover.

<table><thead><tr><th width="141.2962646484375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mínima cuota por selecciones</code></strong></td><td>Cuota mínima que debe tener cada selección incluida en la apuesta.</td></tr><tr><td><strong><code>Máxima cuota por selecciones</code></strong></td><td>Cuota máxima permitida para cada selección incluida en la apuesta.</td></tr><tr><td><strong><code>Mínima cantidad en selecciones</code></strong></td><td><p>Número mínimo de selecciones que debe contener la apuesta.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este mínimo aplica únicamente a las apuestas múltiples. Si el bono admite apuestas simples, el usuario puede utilizarlo con una sola selección.</p></div></td></tr><tr><td><p><strong><code>Mínima cuota total</code></strong></p><p><em>(no editable)</em></p></td><td><p>Cuota total mínima que debe alcanzar la apuesta. El sistema la calcula elevando la cuota mínima por selección al número de selecciones mínimas requeridas.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si la cuota mínima por selección es <strong>2</strong> y se requieren <strong>3 selecciones</strong>, la cuota total mínima será <strong>8</strong> <em>(2 × 2 × 2 = 8)</em>.</p></div></td></tr></tbody></table>

</details>

<details>

<summary>🔽 Cuota por: Totales</summary>

Define las cuotas que debe cumplir la apuesta en su conjunto para ser válida con el saldo bono. Las apuestas que no cumplan estos valores no se aceptan ni descuentan del rollover.

<table><thead><tr><th width="133.333251953125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mínima cuota por totales</code></strong></td><td>Cuota mínima que debe alcanzar la apuesta considerando todas sus selecciones.</td></tr><tr><td><strong><code>Máxima cuota por totales</code></strong></td><td>Cuota máxima permitida para la apuesta considerando todas sus selecciones.</td></tr><tr><td><strong><code>Mínima cantidad en selecciones</code></strong></td><td>Número mínimo de selecciones que debe contener la apuesta.</td></tr><tr><td><p><strong><code>Mínima cuota total</code></strong></p><p><em>(no editable)</em></p></td><td><p>Cuota total mínima que debe alcanzar la apuesta. El sistema la calcula elevando la cuota mínima por totales a la cantidad mínima de selecciones requeridas.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si la cuota mínima por totales es <strong>2</strong> y se requieren <strong>3 selecciones</strong>, la cuota total mínima será <strong>8</strong> <em>(2 × 2 × 2 = 8)</em>.</p></div></td></tr></tbody></table>

</details>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden data-search="false"><thead><tr><th width="130.33343505859375">Campo</th><th width="119.88885498046875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de campaña</code></strong></td><td>Lista desplegable</td><td>Define el objetivo principal del bono dentro de la estrategia de campaña. Las opciones disponibles son:</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="149">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Adquisición</code></strong></td><td>Bono destinado a atraer nuevos usuarios.</td></tr><tr><td><strong><code>Retención</code></strong></td><td>Bono diseñado para mantener activos a los usuarios actuales.</td></tr><tr><td><strong><code>Reactivación</code></strong></td><td>Bono orientado a recuperar usuarios inactivos.</td></tr><tr><td><strong><code>Retención de saldo</code></strong></td><td>Bono para incentivar el uso del saldo existente y evitar retiros.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="128.00006103515625">Campo</th><th width="119.4444580078125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Detalle de Campaña</code></strong></td><td>Lista desplegable</td><td><p>Define la clasificación específica del bono, facilitando su identificación, trazabilidad y análisis desde la administración de bonos.</p><p>Este campo es <strong>obligatorio</strong> y admite una única categoría entre las opciones del sistema <em>(por ejemplo: Bono de registro, Referidos, CRM fidelización)</em>. Si no se selecciona, el sistema muestra un mensaje de error.</p></td></tr><tr><td><strong><code>Deportes, Ligas y Partidos</code></strong></td><td>Secciones</td><td><p>Definen en qué eventos deportivos puede utilizarse el saldo del bono dentro del sportsbook de Digitain:</p><ul><li><strong>Sin configurar</strong> <em>(Directo)</em><strong>:</strong> al no agregar ningún deporte, liga ni partido, el usuario puede utilizar el bono en cualquier evento disponible en la plataforma.</li><li><strong>Configurado:</strong> al agregar uno o varios deportes, ligas o partidos, el usuario únicamente puede utilizar el saldo del bono en las apuestas que correspondan a los elementos configurados.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Esta configuración aplica en ambas modalidades del bono, con rollover y FreeBet, ya que determina dónde puede utilizarse el saldo, independientemente de si debe completarse un rollover para liberarlo.</p></div></td></tr></tbody></table>

{% tabs %}
{% tab title="Deporte" %}
Permite limitar el uso del bono a uno o varios deportes específicos _(por ejemplo: fútbol, tenis o baloncesto)_.

**Visualización**

<figure><img src="https://1957026231-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FrLdGx9JdTz3uLoquKvJw%2Fuploads%2FSL5jL9ZNqq9pUKPSjznO%2Fimage.png?alt=media&#x26;token=bde76d19-691e-4536-bbf7-8ec293034596" alt=""><figcaption><p>Figura #2: Captura de pantalla configuraciones deporte.</p></figcaption></figure>

**Acciones del usuario**

<table><thead><tr><th width="245.111083984375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Añadir deportes</strong></td><td>Agrega los deportes en los que podrá utilizarse el bono.</td></tr><tr><td><strong>Eliminar deportes agregados</strong></td><td>Retira un deporte previamente agregado al bono.</td></tr></tbody></table>

**¿Cómo añadir un deporte?**

Al seleccionar el botón **Añadir**, se habilita un registro en la tabla con los siguientes campos:

<table><thead><tr><th width="211.77783203125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del deporte que se desea agregar.</td></tr><tr><td><strong><code>Deportes seleccionados</code></strong></td><td>Nombre del deporte agregado. Admite un único nombre por registro.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Permite eliminar el deporte agregado.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Adicionalmente, el campo **`Deportes`**, ubicado debajo del botón **Añadir**, permite registrar varios deportes a la vez ingresando sus **ID separados por comas (,)**.
{% endhint %}
{% endtab %}

{% tab title="Partidos" %}
Permite limitar el uso del bono a uno o varios partidos o eventos específicos.

**Visualización**

<figure><img src="https://1957026231-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FrLdGx9JdTz3uLoquKvJw%2Fuploads%2FcB3AofBf5bo5l1UnOpiG%2Fimage.png?alt=media&#x26;token=137fe70a-f793-49a7-bf02-b80cea9f0728" alt=""><figcaption><p>Figura #3: Captura de pantalla configuraciones partidos.</p></figcaption></figure>

**Acciones del usuario**

<table><thead><tr><th width="245.111083984375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Añadir partidos</strong></td><td>Agrega los partidos en los que podrá utilizarse el bono.</td></tr><tr><td><strong>Eliminar partidos agregados</strong></td><td>Retira un partido previamente agregado al bono.</td></tr></tbody></table>

**¿Cómo añadir un partido?**

Al seleccionar el botón **Añadir**, se habilita un registro en la tabla con los siguientes campos:

<table><thead><tr><th width="211.77783203125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del partido que se desea agregar.</td></tr><tr><td><strong><code>Partidos seleccionados</code></strong></td><td>Nombre del partido agregado. Admite un único nombre por registro.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Permite eliminar el partido agregado.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Adicionalmente, el campo **`Partidos`**, ubicado debajo del botón **Añadir**, permite registrar varios partidos a la vez ingresando sus **ID separados por comas (,)**.
{% endhint %}
{% endtab %}

{% tab title="Ligas" %}
Permite limitar el uso del bono a una o varias ligas o torneos específicos _(por ejemplo: LaLiga o Champions League)_.

**Visualización**

<figure><img src="https://1957026231-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FrLdGx9JdTz3uLoquKvJw%2Fuploads%2FT6ayAYOqvd2IthM7UhP2%2Fimage.png?alt=media&#x26;token=b0ea0948-cbc2-4edf-8e18-ce41418d4134" alt=""><figcaption><p>Figura #4: Captura de pantalla configuraciones ligas.</p></figcaption></figure>

**Acciones del usuario**

<table><thead><tr><th width="245.111083984375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Añadir ligas</strong></td><td>Agrega las ligas en las que podrá utilizarse el bono.</td></tr><tr><td><strong>Eliminar ligas agregadas</strong></td><td>Retira una liga previamente agregada al bono.</td></tr></tbody></table>

**¿Cómo añadir una liga?**

Al seleccionar el botón **Añadir**, se habilita un registro en la tabla con los siguientes campos:

<table><thead><tr><th width="211.77783203125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único de la liga que se desea agregar.</td></tr><tr><td><strong><code>Ligas seleccionadas</code></strong></td><td>Nombre de la liga agregada. Admite un único nombre por registro.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL de la imagen representativa de la liga.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Permite eliminar la liga agregada.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Adicionalmente, el campo **`Ligas`**, ubicado debajo del botón **Añadir**, permite registrar varias ligas a la vez ingresando sus **ID separados por comas (,)**.
{% endhint %}
{% endtab %}
{% endtabs %}

<table data-header-hidden><thead><tr><th width="125.22222900390625">Campo</th><th width="122.00006103515625"></th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de apuesta</code></strong></td><td>Selector</td><td><p>Define el tipo de apuesta en el que puede utilizarse el saldo del bono:</p><ul><li><strong>Single:</strong> apuesta simple a un único pronóstico con un monto definido <em>(ejemplo: apostar $10 a que gana Real Madrid)</em>.</li><li><strong>Múltiple:</strong> combina varias selecciones en una sola apuesta <em>(ejemplo: apostar $10 a que ganan Real Madrid y Barcelona en sus respectivos partidos)</em>.</li><li><strong>All:</strong> el bono puede utilizarse en cualquiera de los tipos de apuesta disponibles, sin restricción. <em>(ejemplo: apostar $10 a que gana Real Madrid en una apuesta simple, o combinar varios partidos en una múltiple; ambas opciones son válidas para el bono)</em>.</li></ul></td></tr><tr><td><strong><code>Tipo de evento</code></strong></td><td>Selector</td><td><p>Define el tipo de evento en el que puede utilizarse el saldo del bono:</p><ul><li><strong>Both:</strong> aplica tanto a eventos pre-match como en vivo <em>(ejemplo: apostar $10 en un partido disponible en ambas modalidades)</em>.</li><li><strong>Pre-match:</strong> eventos que se pronostican antes de iniciar <em>(ejemplo: apostar $10 a que gana Real Madrid antes del inicio del partido)</em>.</li><li><strong>Live:</strong> eventos en curso, que solo pueden apostarse mientras se desarrollan <em>(ejemplo: apostar $10 a que habrá gol en el segundo tiempo mientras el partido está en juego)</em>.</li></ul></td></tr></tbody></table>

{% hint style="danger" %}
**Nota importante:** En el campo **`Mínima cantidad en selecciones`** solo se exige en las apuestas múltiples, porque son las únicas que combinan varios eventos. Una apuesta simple tiene una sola selección por definición, por lo que este mínimo no puede aplicarse sobre ella.

Esto significa que, si el campo **`Tipo de apuesta`** permite apuestas simples _(opciones Single o All)_, el usuario podrá utilizar el bono con una sola selección aunque se haya configurado un mínimo mayor.

Para que el bono exija siempre la cantidad mínima configurada en **`Mínima cantidad en selecciones`**, el campo **`Tipo de apuesta`** debe configurarse como **Múltiple**.
{% endhint %}

{% hint style="info" %}
**Ejemplo:** Un bono con **Mínima cantidad en selecciones = 3** y **Tipo de apuesta = All**:

* Si el usuario realiza una apuesta **simple**, puede usar el bono con un solo evento.
* Si el usuario realiza una apuesta **múltiple**, esta deberá incluir al menos **3 eventos** para que el bono aplique.
{% endhint %}

***

<details>

<summary><strong>Opciones avanzadas</strong></summary>

Configuraciones complementarias que definen cómo se controla el acceso al bono y su redención mediante códigos.

<table><thead><tr><th width="163.50006103515625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Permisos</code></strong></td><td>Define si el código global es obligatorio para acceder al bono.</td></tr><tr><td><strong><code>Código Global</code></strong></td><td>Código configurado en BackOffice que limita la cantidad máxima de usuarios que pueden acceder al bono.</td></tr><tr><td><strong><code>Códigos Promocionales</code></strong></td><td>Código promocional configurado en BackOffice, utilizado para campañas específicas.</td></tr><tr><td><strong><code>¿Habilitar códigos únicos?</code></strong></td><td><p>Define si el bono puede redimirse mediante códigos únicos generados automáticamente por el sistema, uno por cada usuario definido en el campo <strong><code>Cantidad de jugadores</code></strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo debe habilitarse obligatoriamente para entregar el bono mediante códigos únicos.</p></div></td></tr></tbody></table>

</details>

***

<table data-header-hidden data-search="false"><thead><tr><th width="134.166748046875">Campo</th><th width="120.5">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Todas las condiciones son obligatorias</code></strong></td><td>Botón de selección</td><td>Define si todas las condiciones configuradas previamente deben cumplirse para que la apuesta sea válida y descuente del rollover.</td></tr><tr><td><strong><code>Valor del bono como máximo valor a sumar para rollover</code></strong></td><td>Botón de selección</td><td><p>Define si el valor del bono se toma en su totalidad o hasta un tope máximo al calcular el monto que el usuario debe apostar.</p><ul><li><strong>Sí:</strong> el cálculo del rollover considera el valor del bono hasta el máximo permitido configurado.</li><li><strong>No:</strong> el cálculo del rollover considera el valor total del bono entregado.</li></ul><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Depósito de <strong>$200</strong>, bono de <strong>$500</strong> y factor de rollover <strong>x5</strong>.</p><ul><li><strong>Sí</strong> <em>(con un máximo permitido de $300)</em>: (200 + 300) × 5 = <strong>$2.500</strong> en apuestas requeridas.</li><li><strong>No:</strong> (<em>200 + 500</em>) × 5 = <strong>$3.500</strong> en apuestas requeridas.</li></ul></div></td></tr><tr><td><strong><code>Asignación de bono</code></strong></td><td>Lista desplegable</td><td>Define si se otorga dinero directo o un bono previamente creado.</td></tr><tr><td><strong><code>Campaña de marketing</code></strong></td><td>Sección</td><td>Configura las notificaciones que llegan al inbox de la plataforma.</td></tr><tr><td><strong><code>Saldo a asignar</code></strong></td><td>Lista desplegable</td><td>Define el tipo de saldo que recibe el usuario al <a href="https://virtualsoft.gitbook.io/plantillas/glosario#redimir">redimir</a> el bono.</td></tr><tr><td><strong><code>Tipo de máximo monto para rollover</code></strong></td><td>Lista desplegable</td><td><p>Define cómo se determina el tope máximo aplicado al cálculo del rollover:</p><ul><li><strong>Depende del bono redimido:</strong> el tope se calcula a partir del valor del bono que recibió el usuario.</li><li><strong>No depende del bono redimido:</strong> el tope corresponde a un valor fijo, independiente del monto del bono entregado.</li></ul></td></tr></tbody></table>

***

<details>

<summary>Moneda</summary>

Al dar clic en la moneda correspondiente al país con el que se ingresó a la plataforma, se despliegan las siguientes configuraciones:

<figure><img src="../../../../../.gitbook/assets/image (306).png" alt=""><figcaption><p>Figura #5: Captura de pantalla configuración de moneda</p></figcaption></figure>

<table><thead><tr><th width="142">Campo</th><th width="119">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Monto de Bono Fijo</code></strong></td><td>Numérico</td><td>Valor fijo del bono que recibe el usuario.</td></tr><tr><td><strong><code>Máxima apuesta tomada para rollover</code></strong></td><td>Numérico</td><td><p>Monto máximo de una apuesta que se contabiliza para el rollover. Si el usuario apuesta un valor superior, el excedente no descuenta del rollover pendiente.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Con una máxima apuesta de <strong>$20</strong>, si el usuario realiza una apuesta de <strong>$50</strong>, solo se descuentan <strong>$20</strong> del rollover pendiente.</p></div></td></tr><tr><td><strong><code>Pago máximo</code></strong></td><td>Numérico</td><td>Monto máximo que puede recibir el usuario como saldo real al liberar este bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón</td><td><p>Permite cargar un archivo CSV con los ID de los usuarios que reciben el bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo se utiliza cuando el bono se entrega mediante asignación directa. Los usuarios incluidos en el archivo reciben el bono sin necesidad de redimir un código.</p></div></td></tr></tbody></table>

</details>

***

<table data-header-hidden><thead><tr><th width="154.83331298828125">Campo</th><th width="108.16668701171875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cliente puede repetir bono</code></strong></td><td>Botón de selección</td><td>Define si el usuario puede redimir varias veces el mismo bono.</td></tr><tr><td><strong><code>Programa de fidelización</code></strong></td><td>Botón de selección</td><td>Define si el bono pertenece a un esquema de fidelización.</td></tr><tr><td><strong><code>Cliente puede recibir otros bonos</code></strong></td><td>Botón de selección</td><td>Define si el bono es compatible con otros bonos adicionales.</td></tr><tr><td><strong><code>Crear Bono</code></strong></td><td>Botón</td><td>Guarda las configuraciones y genera el bono en el sistema.</td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* Si algún campo obligatorio no está configurado, el bono no se crea.
* Para entregar el bono mediante códigos únicos, es obligatorio habilitar el campo **`¿Habilitar códigos únicos?`** en las opciones avanzadas; de lo contrario, los códigos generados no funcionan.
* El sistema genera un código único por cada usuario definido en el campo **`Cantidad de jugadores`**.
* El saldo bono no es retirable: se convierte en saldo real únicamente cuando el usuario completa el rollover configurado.
* Los usuarios incluidos en el archivo CSV del campo **`Jugadores`** reciben el bono de forma directa, sin necesidad de redimir un código.
* El usuario debe completar el rollover mediante apuestas válidas para que el saldo bono se convierta en saldo real. Con la opción **Directo**, las apuestas descuentan del rollover sin restricciones por producto; con los demás productos, solo descuentan las apuestas que cumplen las configuraciones definidas.
* El rollover contabiliza el monto apostado, sin importar el resultado de las apuestas. Las ganancias incrementan el saldo bono, pero no reducen el rollover pendiente.
* Solo las apuestas que cumplen las condiciones configuradas _(cuotas, cantidad de selecciones, producto y tipo de evento)_ descuentan del rollover pendiente.
* Si el usuario agota su saldo bono antes de completar el rollover, o si el bono expira, el saldo bono se pierde.
* El campo **`¿Se dará bono freebet?`** define si el bono exige rollover. Con la opción **Sí**, los campos relacionados con el rollover dejan de ser obligatorios y no se tienen en cuenta.
* En la modalidad **FreeBet**, el saldo queda disponible de inmediato y las ganancias obtenidas se acreditan como saldo real, sin necesidad de completar un rollover.
* En ambas modalidades, el usuario debe cumplir las condiciones de apuesta configuradas _(cuotas, cantidad de selecciones, tipo de apuesta y evento)_ para poder utilizar el saldo del bono.
* El saldo del bono se acredita dentro del sportsbook de Digitain.
* Si en el campo **`¿Se dará bono con algún proveedor?`** se selecciona **No**, el formulario continúa con el flujo habitual de creación de bono, sin configuraciones asociadas a un proveedor externo.
* La **`Mínima cantidad en selecciones`** aplica únicamente a las apuestas múltiples. Si el bono admite apuestas simples _(Tipo de apuesta en Single o All)_, el usuario puede utilizarlo con una sola selección.
* Para que el bono exija siempre la cantidad mínima de selecciones configurada, el campo **`Tipo de apuesta`** debe configurarse como **Múltiple**.
* Las cuotas mínimas admiten valores decimales mayores a cero, y la cantidad mínima de selecciones debe ser un número entero mayor o igual a uno.
* El bono se crea primero en la plataforma y luego se envía automáticamente a Digitain. Si el bono se crea en la plataforma pero no logra crearse en Digitain, queda en estado **Inactivo.**
* La asignación de bonos de Digitain mediante CRM solo está disponible en ambiente productivo.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>11/08/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-26895">Documento inicial</a></td></tr><tr><td>1.1</td><td>28/09/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-26895">Ajuste en incorporación de campos Deportes, partidos, ligas, tipo de evento y tipo de apuesta en el formulario</a></td></tr></tbody></table>

</details>
