# Creación bono no depósito para Digitain

## Creación bono no depósito para Digitain

<mark style="color:$info;">Permite crear un bono no depósito asociado al proveedor Digitain, el cual se entrega al usuario sin necesidad de que realice un depósito previo. El bono puede asignarse directamente a usuarios específicos o entregarse mediante códigos únicos, y se libera cuando el usuario cumple el rollover y las reglas de apuesta configuradas.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Torneos y Bonos > País > Bonos > Bono No Depósito

***

### 2. Visualización

***

### 3. ¿Cómo funciona este bono?

El bono no depósito para Digitain **no requiere que el usuario realice un depósito** para obtenerlo. Su comportamiento se define con dos configuraciones del formulario que se combinan según el objetivo de la campaña:

* **Cómo se entrega:** por asignación directa mediante archivo CSV o mediante códigos únicos.
* **Si requiere rollover:** disponible de inmediato o sujeto a que el usuario apueste para liberarlo.

#### 3.1. Conceptos clave

{% hint style="warning" %}
**Nota:** Comprender estos conceptos es fundamental para configurar correctamente el bono, ya que cada uno determina cómo se entrega el saldo al usuario, qué debe cumplir para liberarlo y en qué momento se convierte en saldo real.
{% endhint %}

<table><thead><tr><th width="141.6666259765625">Concepto</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Saldo bono</strong></td><td>Saldo que recibe el usuario al obtener el bono. Su disponibilidad depende de si el bono requiere rollover.</td></tr><tr><td><strong>Rollover</strong></td><td><p>Monto total que el usuario debe apostar para liberar el bono. Se calcula multiplicando el valor del bono por el factor de rollover configurado, y contabiliza el dinero apostado, no las ganancias obtenidas.</p><p><strong>Fórmula:</strong><br><em>Rollover = Valor del bono × Factor de rollover</em></p></td></tr><tr><td><strong>Apuesta válida</strong></td><td>Apuesta que cumple las condiciones configuradas <em>(producto, cuotas, selecciones y eventos habilitados)</em>. Únicamente estas apuestas descuentan del rollover pendiente.</td></tr><tr><td><strong>Saldo real</strong></td><td>Saldo disponible del usuario, el cual puede retirar o utilizar libremente.</td></tr></tbody></table>

#### 3.2. Formas de entrega

<table><thead><tr><th width="158.33331298828125">Forma de entrega</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Asignación directa</strong><br><em>(archivo CSV)</em></td><td>El bono se asigna automáticamente a los usuarios incluidos en el archivo CSV cargado en el campo <strong><code>Jugadores</code></strong>, sin que estos realicen ninguna acción adicional.</td></tr><tr><td><strong>Códigos únicos</strong></td><td>El sistema genera un código único por cada usuario definido en el campo <strong><code>Cantidad de jugadores</code></strong>. El usuario redime el bono ingresando su código en la sección <strong>Mis bonos</strong> de la plataforma de usuarios online. Por ejemplo, con el valor <strong>5</strong> se generan <strong>5 códigos únicos</strong>, uno por usuario.</td></tr></tbody></table>

{% hint style="danger" %}
**Nota importante:** Para entregar el bono mediante códigos únicos es obligatorio habilitar el campo **`¿Habilitar códigos únicos?`** en las opciones avanzadas. De lo contrario, los códigos generados no funcionarán y los usuarios no podrán redimir el bono.
{% endhint %}

#### 3.3. Ciclo del bono, paso a paso

En cualquiera de las dos formas de entrega, el usuario debe completar el rollover con apuestas válidas para liberar el saldo del bono.

{% stepper %}
{% step %}
**El usuario obtiene el bono**

El usuario recibe el bono por asignación directa, al estar incluido en el archivo CSV cargado, o al redimir su código único en la sección **Mis bonos** de la plataforma. El sistema le acredita el saldo bono configurado.
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

***

### 4. Acciones disponibles en el módulo

<table><thead><tr><th width="200.3333740234375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Configurar bono no depósito</strong></td><td><p>Permite configurar un bono de tipo no depósito mediante el formulario disponible en este módulo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Los campos cuyo nombre finaliza con un asterisco (<mark style="color:$danger;">*</mark>) son obligatorios para la creación del bono.</p></div></td></tr><tr><td><strong>Configurar términos y condiciones del bono</strong></td><td>En la parte final del formulario se encuentra el botón <strong>"</strong><em><strong>Ver términos y condiciones</strong></em><strong>"</strong>, el cual despliega un editor de texto donde se ingresan los términos y condiciones aplicables al bono.</td></tr><tr><td><strong>Crear bono</strong></td><td>Envía la información registrada en el formulario y genera el bono en el sistema.</td></tr></tbody></table>

***

### 5. Configuraciones del bono

<table><thead><tr><th width="130.33343505859375">Campo</th><th width="116.33331298828125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Botón</td><td><p>Despliega los campos de fecha que definen el período de vigencia del bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Es posible configurar múltiples rangos de fechas mediante el botón <strong>"</strong><em><strong>Agregar</strong></em><strong>"</strong>, una vez establecidas la <strong>fecha inicial</strong> y la <strong>fecha final</strong> de cada rango.</p></div></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre que identifica el bono en la plataforma.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Numérico</td><td><p>Define el orden de asignación de bonos a los usuarios. Un número mayor indica mayor prioridad.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Con tres bonos configurados así:</p><ul><li><strong>Bono A:</strong> 1</li><li><strong>Bono B:</strong> 2</li><li><strong>Bono C:</strong> 3</li></ul><p>El sistema da preferencia al <strong>Bono C</strong>, por tener la prioridad más alta.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Detalles adicionales del bono que se visualizan en la plataforma de usuarios online.</td></tr><tr><td><strong><code>URL Imagen principal</code></strong></td><td>Texto</td><td>Enlace de la imagen que se muestra al usuario al visualizar el bono.</td></tr><tr><td><strong><code>Fecha de expiración</code></strong></td><td>Selector de fecha</td><td><p>Define el plazo para redimir el bono. Con la opción <strong>"</strong><em><strong>Días</strong></em><strong>"</strong> se ingresa la cantidad de días hasta su vencimiento; con la opción <strong>"</strong><em><strong>Fecha</strong></em><strong>"</strong> se indica la fecha exacta de expiración. Cumplido el plazo, el bono queda inactivo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Los campos <strong><code>Días</code></strong> y <strong><code>Fecha expiración</code></strong> son dinámicos y se visualizan según la opción seleccionada.</p></div></td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Determina si el bono es público <em>(todos los usuarios)</em> o privado <em>(VIP)</em>.</td></tr><tr><td><strong><code>Prefijo</code></strong></td><td>Texto</td><td>Identificador adicional que diferencia el bono de otros.</td></tr><tr><td><strong><code>Cantidad de jugadores</code></strong></td><td>Numérico</td><td><p>Cantidad de usuarios que pueden acceder al bono. Este campo es <strong>obligatorio</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Cuando el bono se entrega mediante códigos únicos, el sistema genera un código por cada usuario definido en este campo. Por ejemplo, con el valor <strong>5</strong> se generan <strong>5 códigos únicos</strong>.</p></div></td></tr><tr><td><strong><code>Tipo de bono</code></strong></td><td>Lista desplegable</td><td>Define si el bono se asigna automáticamente al momento del registro del usuario o si no se asigna de forma automática.</td></tr><tr><td><strong><code>¿Eliminación por retiro?</code></strong></td><td>Selector</td><td>Define si el bono se elimina de la cuenta del usuario al generarse una nota de retiro.</td></tr><tr><td><strong><code>¿Se dará bono con algún proveedor?</code></strong></td><td>Selector</td><td>Indica si el bono se otorga a través de un proveedor externo. Al seleccionar <strong>"</strong><em><strong>Sí</strong></em><strong>"</strong>, se habilita el campo <strong><code>Seleccione el proveedor</code></strong>.</td></tr><tr><td><strong><code>Seleccione el proveedor</code></strong></td><td>Selector</td><td>Define el proveedor al que aplica el bono. Para este tipo de bono corresponde seleccionar <strong>Digitain</strong>.</td></tr><tr><td><strong><code>¿El jugador debe usar el bono en una sola apuesta?</code></strong></td><td>Selector</td><td><p>Define si el usuario puede distribuir su saldo bono en varias apuestas o si debe utilizarlo en una única apuesta.</p><ul><li><strong>Sí:</strong> el usuario apuesta la totalidad del saldo bono en una sola apuesta.</li><li><strong>No:</strong> el usuario puede realizar tantas apuestas como desee mientras disponga de saldo bono.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> En ambos casos el usuario debe completar el rollover configurado para liberar el bono.</p></div></td></tr><tr><td><strong><code>¿El jugador puede hacer cashout con apuestas del bono?</code></strong></td><td>Selector</td><td><p>Define si el usuario puede realizar <a href="https://virtualsoft.gitbook.io/untitled/glosario#cashout">cashout</a> en las apuestas efectuadas con el saldo bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El cashout no afecta el avance del rollover. El monto apostado se descuenta del rollover pendiente en el momento de realizar la apuesta, independientemente de que esta se cierre anticipadamente mediante cashout.</p></div></td></tr><tr><td><strong><code>¿El jugador puede cancelar su bono?</code></strong></td><td>Selector</td><td><p>Define si el usuario puede renunciar al bono antes de completar el rollover.</p><ul><li><strong>Sí:</strong> el usuario puede cancelar el bono desde la plataforma. Al hacerlo, pierde el saldo bono y las condiciones asociadas quedan sin efecto.</li><li><strong>No:</strong> el bono permanece activo hasta que el usuario complete el rollover, agote el saldo bono o el bono expire.</li></ul></td></tr><tr><td><strong><code>Factor de rollover del BONO</code></strong></td><td>Numérico</td><td><p>Número por el cual se multiplica el valor del bono para determinar el monto total que el usuario debe apostar antes de liberarlo.</p><p><strong>Fórmula:</strong><br><em>Rollover = Valor del bono × Factor de rollover</em></p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Con un bono de <strong>$50</strong> y un factor de rollover de <strong>2</strong>, el rollover es de <strong>$100</strong>. El usuario debe apostar $100 en total para liberar el bono; hasta alcanzar ese monto, el saldo bono no se convierte en saldo real.</p></div></td></tr><tr><td><strong><code>¿Cuota por?</code></strong></td><td>Selector</td><td><p>Define cómo se evalúan las cuotas de las apuestas realizadas con el saldo bono. Determina cuáles apuestas son válidas para el bono y, por lo tanto, cuáles descuentan del rollover.</p><ul><li><strong>Por selecciones:</strong> la cuota se evalúa de forma individual, por cada selección que compone la apuesta.</li><li><strong>Por totales:</strong> la cuota se evalúa de forma conjunta, sobre el resultado total de todas las selecciones.</li></ul></td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<details>

<summary>🔽 Cuota por: Selecciones</summary>

Define las cuotas que debe cumplir cada selección de una apuesta para que esta sea válida con el saldo bono. Las apuestas que no cumplan estos valores no se aceptan ni descuentan del rollover.

<table><thead><tr><th width="141.2962646484375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mínima cuota por selecciones</code></strong></td><td>Cuota mínima que debe tener cada selección incluida en la apuesta.</td></tr><tr><td><strong><code>Máxima cuota por selecciones</code></strong></td><td>Cuota máxima permitida para cada selección incluida en la apuesta.</td></tr><tr><td><strong><code>Mínima cantidad en selecciones</code></strong></td><td>Número mínimo de selecciones que debe contener la apuesta.</td></tr><tr><td><p><strong><code>Mínima cuota total</code></strong></p><p><em>(no editable)</em></p></td><td><p>Cuota total mínima que debe alcanzar la apuesta. El sistema la calcula elevando la cuota mínima por selección al número de selecciones mínimas requeridas.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si la cuota mínima por selección es <strong>2</strong> y se requieren <strong>3 selecciones</strong>, la cuota total mínima será <strong>8</strong> <em>(2 × 2 × 2 = 8)</em>.</p></div></td></tr></tbody></table>

</details>

<details>

<summary>🔽 Cuota por: Totales</summary>

Define las cuotas que debe cumplir la apuesta en su conjunto para ser válida con el saldo bono. Las apuestas que no cumplan estos valores no se aceptan ni descuentan del rollover.

<table><thead><tr><th width="133.333251953125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mínima cuota por totales</code></strong></td><td>Cuota mínima que debe alcanzar la apuesta considerando todas sus selecciones.</td></tr><tr><td><strong><code>Máxima cuota por totales</code></strong></td><td>Cuota máxima permitida para la apuesta considerando todas sus selecciones.</td></tr><tr><td><strong><code>Mínima cantidad en selecciones</code></strong></td><td>Número mínimo de selecciones que debe contener la apuesta.</td></tr><tr><td><p><strong><code>Mínima cuota total</code></strong></p><p><em>(no editable)</em></p></td><td><p>Cuota total mínima que debe alcanzar la apuesta. El sistema la calcula elevando la cuota mínima por totales a la cantidad mínima de selecciones requeridas.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si la cuota mínima por totales es <strong>2</strong> y se requieren <strong>3 selecciones</strong>, la cuota total mínima será <strong>8</strong> <em>(2 × 2 × 2 = 8)</em>.</p></div></td></tr></tbody></table>

</details>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden data-search="false"><thead><tr><th width="130.33343505859375">Campo</th><th width="116.33331298828125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de campaña</code></strong></td><td>Lista desplegable</td><td>Define el objetivo principal del bono dentro de la estrategia de campaña. Las opciones disponibles son:</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="149">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Adquisición</code></strong></td><td>Bono destinado a atraer nuevos usuarios.</td></tr><tr><td><strong><code>Retención</code></strong></td><td>Bono diseñado para mantener activos a los usuarios actuales.</td></tr><tr><td><strong><code>Reactivación</code></strong></td><td>Bono orientado a recuperar usuarios inactivos.</td></tr><tr><td><strong><code>Retención de saldo</code></strong></td><td>Bono para incentivar el uso del saldo existente y evitar retiros.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden data-search="false"><thead><tr><th width="122.8333740234375">Campo</th><th width="121.33331298828125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Detalle de Campaña</code></strong></td><td>Lista desplegable</td><td><p>Define la clasificación específica del bono, facilitando su identificación, trazabilidad y análisis desde la administración de bonos.</p><p>Este campo es <strong>obligatorio</strong> y admite una única categoría entre las opciones del sistema <em>(por ejemplo: Bono de registro, Referidos, CRM fidelización)</em>. Si no se selecciona, el sistema muestra un mensaje de error.</p></td></tr></tbody></table>

***

<details>

<summary><strong>5.1. Opciones avanzadas</strong></summary>

Configuraciones complementarias que definen cómo se controla el acceso al bono y su redención mediante códigos.

<table><thead><tr><th width="163.50006103515625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Permisos</code></strong></td><td>Define si el código global es obligatorio para acceder al bono.</td></tr><tr><td><strong><code>Código Global</code></strong></td><td>Código configurado en BackOffice que limita la cantidad máxima de usuarios que pueden acceder al bono.</td></tr><tr><td><strong><code>Códigos Promocionales</code></strong></td><td>Código promocional configurado en BackOffice, utilizado para campañas específicas.</td></tr><tr><td><strong><code>¿Habilitar códigos únicos?</code></strong></td><td><p>Define si el bono puede redimirse mediante códigos únicos generados automáticamente por el sistema, uno por cada usuario definido en el campo <strong><code>Cantidad de jugadores</code></strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo debe habilitarse obligatoriamente para entregar el bono mediante códigos únicos.</p></div></td></tr></tbody></table>

</details>

***

<table data-header-hidden><thead><tr><th width="129.83331298828125">Campo</th><th width="117.33331298828125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Producto Rollover</code></strong></td><td>Lista desplegable</td><td><p>Define si el bono requiere que el usuario realice apuestas para liberarlo y, en caso de requerirlo, en qué producto deben realizarse. Las opciones recomendadas para este caso son:</p><ul><li><strong>Directo:</strong> el bono no requiere rollover; el saldo queda disponible para el usuario sin necesidad de apostar.</li><li><strong>Sportsbook:</strong> el bono requiere rollover y habilita las configuraciones correspondientes al producto seleccionado, las cuales determinan qué apuestas son válidas para liberarlo.</li></ul></td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<details>

<summary><strong>Configuraciones: Sportsbook</strong></summary>

Definen las apuestas deportivas que son válidas para descontar del rollover. Las secciones **Deporte, Mercados, Ligas y Partidos** comparten la misma estructura y configuración: los campos y condiciones son los mismos en todas, variando únicamente el nivel al que se aplican _(deporte, mercado, liga o partido)_.

<table data-search="false"><thead><tr><th width="122.66650390625">Campo</th><th width="258.0103759765625">Descripción</th></tr></thead><tbody><tr><td><strong><code>¿Todas las condiciones son obligatorias?</code></strong></td><td>Define si las condiciones configuradas deben cumplirse en su totalidad. Con la opción "<em><strong>Sí</strong></em>", se revisan una a una y todas deben cumplirse para aplicar la regla. Con la opción "<em><strong>No</strong></em>", cada condición se evalúa de forma independiente y basta con que alguna se cumpla.</td></tr><tr><td><strong><code>¿Se dará un bono del proveedor Altenar?</code></strong></td><td>Indica si se otorga un bono proveniente del proveedor Altenar. Con la opción "<em><strong>Sí</strong></em>", se habilitan los campos <strong><code>Bono plan Id</code></strong> <em>(identificador del plan de bono definido por el proveedor)</em> y <strong><code>Código del bono</code></strong> <em>(código único del bono asignado por el proveedor)</em>, ambos obligatorios y diligenciados con la información proporcionada por el proveedor. Con la opción "<em><strong>No</strong></em>", no se otorga este beneficio y dichos campos no son requeridos.</td></tr><tr><td><strong><code>Deporte, Mercados, Ligas o Partidos</code></strong></td><td>Define los identificadores <em>(ID)</em> de los elementos a los que aplica la configuración <em>(deportes, mercados, ligas o partidos)</em>. Admite múltiples ID separados por comas.</td></tr><tr><td><strong><code>Tipo de apuesta</code></strong></td><td>Define el tipo de apuesta al que aplica la configuración: <strong>Single</strong> <em>(apuesta simple)</em>, <strong>Multiple</strong> <em>(apuesta combinada)</em> o <strong>System</strong> <em>(apuestas de sistema)</em>.</td></tr><tr><td><strong><code>Tipo de evento</code></strong></td><td>Define el tipo de evento al que aplica la configuración: <strong>Both</strong> <em>(pre-match y en vivo)</em>, <strong>Pre-match</strong> <em>(antes del evento)</em> o <strong>Live</strong> <em>(en vivo)</em>.</td></tr><tr><td><strong><code>Mínima cantidad en selecciones</code></strong></td><td>Número mínimo de selecciones que debe tener una apuesta para que aplique la configuración.</td></tr><tr><td><strong><code>Mínima cuota en selecciones</code></strong></td><td>Cuota mínima que debe tener cada selección dentro de la apuesta.</td></tr><tr><td><strong><code>Mínima cuota total</code></strong></td><td>Cuota mínima total que debe cumplir la apuesta.</td></tr><tr><td><strong><code>Repetir Partidos</code></strong></td><td>Define si se permite incluir el mismo partido más de una vez dentro de una apuesta.</td></tr><tr><td><strong><code>Repetir Mercados</code></strong></td><td>Define si se permite incluir el mismo mercado más de una vez dentro de una apuesta.</td></tr></tbody></table>

</details>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden data-search="false"><thead><tr><th width="134.166748046875">Campo</th><th width="120.5">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Asignación de bono</code></strong></td><td>Lista desplegable</td><td>Define si se otorga dinero directo o un bono previamente creado.</td></tr><tr><td><strong><code>Todas las condiciones son obligatorias</code></strong></td><td>Botón de selección</td><td>Define si todas las condiciones configuradas previamente deben cumplirse para que la apuesta sea válida y descuente del rollover.</td></tr><tr><td><strong><code>Campaña de marketing</code></strong></td><td>Sección</td><td>Configura las notificaciones que llegan al inbox de la plataforma.</td></tr><tr><td><strong><code>Saldo a asignar</code></strong></td><td>Lista desplegable</td><td>Define el tipo de saldo que recibe el usuario al redimir el bono.</td></tr><tr><td><strong><code>Tipo de máximo monto para rollover</code></strong></td><td>Lista desplegable</td><td><p>Define cómo se determina el tope máximo aplicado al cálculo del rollover:</p><ul><li><strong>Depende del bono redimido:</strong> el tope se calcula a partir del valor del bono que recibió el usuario.</li><li><strong>No depende del bono redimido:</strong> el tope corresponde a un valor fijo, independiente del monto del bono entregado.</li></ul></td></tr><tr><td><strong><code>Valor del bono como máximo valor a sumar para rollover</code></strong></td><td>Botón de selección</td><td>Define si el valor del bono se toma hasta un tope máximo al calcular el monto que el usuario debe apostar, en lugar de considerar su valor total.</td></tr></tbody></table>

***

<details>

<summary>Moneda</summary>

Al dar clic en la moneda correspondiente al país con el que se ingresó a la plataforma, se despliegan las siguientes configuraciones:

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

{% hint style="info" %}
**Ejemplo:**\
Los bonos de tipo **Referidos**, una vez creados y disponibles, se activan y habilitan desde el módulo de referidos: [Configuración #🔽 Referidos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#referidos "mention")
{% endhint %}

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="107">Versión</th><th width="130">Fecha</th><th width="156.3333740234375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>12/08/2026</td><td>David Velasquez</td><td>Documento inicial.</td></tr></tbody></table>

</details>
