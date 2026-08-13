# Creación bono Freebet para Digitain

## Creación bono FreeBet para Digitain

<mark style="color:$info;">Permite crear un bono FreeBet asociado al proveedor Digitain. Este bono entrega al usuario un saldo destinado exclusivamente a realizar apuestas deportivas, el cual queda disponible de inmediato y se utiliza en las apuestas que cumplan las condiciones configuradas.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Torneos y bonos > Crear bono > País > FreeBet

***

### 2. Visualización general

***

### 3. ¿Cómo funciona este bono?

El bono FreeBet entrega al usuario un **saldo FreeBet** destinado exclusivamente a realizar apuestas deportivas. A diferencia de otros bonos, queda disponible de inmediato y **no requiere rollover**: el usuario no debe cumplir un monto de apuestas para poder utilizarlo.

Su comportamiento se define con tres elementos del formulario:

* **Cómo se entrega:** por asignación directa mediante archivo CSV o mediante códigos únicos.
* **Dónde puede usarse:** las condiciones de apuesta configuradas _(cuotas, selecciones, tipo de apuesta y evento, y opcionalmente deportes, ligas, mercados o partidos específicos)_.
* **Cuánto cubre:** los valores mínimo y máximo definidos por moneda establecen qué parte de cada apuesta se cubre con el bono.

#### 3.1. Conceptos clave

{% hint style="warning" %}
**Nota:** Comprender estos conceptos es fundamental para configurar correctamente el bono, ya que determinan cómo se entrega el saldo al usuario, en qué apuestas puede utilizarse y qué parte del monto apostado cubre.
{% endhint %}

<table><thead><tr><th width="145.833251953125">Concepto</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Saldo Bono</strong></td><td>Saldo que recibe el usuario al obtener el bono, destinado exclusivamente a realizar apuestas dentro de Digitain.</td></tr><tr><td><strong>Apuesta válida</strong></td><td>Apuesta que cumple las condiciones configuradas <em>(cuotas, cantidad de selecciones, tipo de apuesta y evento habilitados)</em>. Únicamente en estas apuestas se utiliza el saldo FreeBet.</td></tr></tbody></table>

#### 3.2. Formas de entrega

<table><thead><tr><th width="145.83331298828125">Forma de entrega</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Asignación directa</strong><br><em>(archivo CSV)</em></td><td>El bono se asigna automáticamente a los usuarios incluidos en el archivo CSV cargado en el campo <strong><code>Jugadores</code></strong>. El saldo FreeBet se acredita directamente, sin que estos realicen ninguna acción adicional.</td></tr><tr><td><strong>Códigos únicos</strong></td><td>El sistema genera un código único por cada usuario definido en el campo <strong><code>Cantidad de jugadores</code></strong>. El usuario redime el bono ingresando su código en la sección <strong>Mis bonos</strong> de la plataforma de usuarios online. Por ejemplo, con el valor <strong>5</strong> se generan <strong>5 códigos únicos</strong>, uno por usuario.</td></tr></tbody></table>

{% hint style="danger" %}
**Nota importante:** Para entregar el bono mediante códigos únicos es obligatorio habilitar el campo **`¿Habilitar códigos únicos?`** en las opciones avanzadas. De lo contrario, los códigos generados no funcionarán y los usuarios no podrán redimir el bono.
{% endhint %}

#### 3.3. Uso y cobertura del bono

En cualquiera de las dos formas de entrega, el saldo FreeBet queda disponible de inmediato para apostar. Al realizar una apuesta que cumpla las condiciones configuradas, el sistema aplica el bono según los valores mínimo y máximo definidos por moneda:

<table><thead><tr><th width="200">Monto de la apuesta</th><th>Comportamiento</th></tr></thead><tbody><tr><td><strong>Menor al mínimo valor fijo</strong></td><td>El sistema no utiliza el bono; el valor se descuenta del <strong>saldo apuestas</strong> del usuario.</td></tr><tr><td><strong>Entre el mínimo y el máximo</strong></td><td>El sistema utiliza el saldo FreeBet para cubrir la apuesta.</td></tr><tr><td><strong>Superior al máximo valor fijo</strong></td><td>El sistema aplica únicamente el valor máximo configurado del bono y el excedente se descuenta del <strong>saldo apuestas</strong> del usuario.</td></tr></tbody></table>

{% hint style="info" %}
**Ejemplo:** Con un bono configurado entre un mínimo de **$10** y un máximo de **$50**:

* Una apuesta de **$5** no utiliza el bono; se descuenta por completo del saldo apuestas del usuario.
* Una apuesta de **$30** se cubre en su totalidad con el saldo FreeBet.
* Una apuesta de **$80** se cubre con **$50** del saldo FreeBet y los **$30** restantes se descuentan del saldo apuestas del usuario.
* **Resultado de la apuesta:** si la apuesta realizada con saldo FreeBet resulta ganadora, la ganancia obtenida se acredita como **saldo real** del usuario, quedando disponible para retirar o utilizar libremente. Si la apuesta resulta perdedora, el saldo FreeBet utilizado se consume sin generar retorno.
{% endhint %}

***

### 4. Acciones disponibles en el módulo

<table><thead><tr><th width="232">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Configurar bono FreeBet</strong></td><td><p>Permite configurar un bono de tipo FreeBet mediante el formulario disponible en este módulo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Los campos cuyo nombre finaliza con un asterisco (<mark style="color:$danger;">*</mark>) son obligatorios para la creación del bono.</p></div></td></tr><tr><td><strong>Configurar términos y condiciones del bono</strong></td><td>En la parte final del formulario se encuentra el botón <strong>"</strong><em><strong>Ver términos y condiciones</strong></em><strong>"</strong>, el cual despliega un editor de texto donde se ingresan los términos y condiciones aplicables al bono.</td></tr><tr><td><strong>Crear bono</strong></td><td>Envía la información registrada en el formulario y genera el bono en el sistema.</td></tr></tbody></table>

***

### 5. Formulario creación del bono FreeBet

<table><thead><tr><th width="132.00006103515625">Campo</th><th width="126.111083984375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Botón</td><td><p>Despliega los campos de fecha que definen el período de vigencia del bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Es posible configurar múltiples rangos de fechas mediante el botón <strong>"</strong><em><strong>Agregar</strong></em><strong>"</strong>, una vez establecidas la <strong>fecha inicial</strong> y la <strong>fecha final</strong> de cada rango.</p></div></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre que identifica el bono en la plataforma.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Numérico</td><td><p>Define el orden de asignación de bonos a los usuarios. Un número mayor indica mayor prioridad.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Con tres bonos configurados así:</p><ul><li><strong>Bono A:</strong> 1</li><li><strong>Bono B:</strong> 2</li><li><strong>Bono C:</strong> 3</li></ul><p>El sistema da preferencia al <strong>Bono C</strong>, por tener la prioridad más alta.</p></div><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Los bonos de bienvenida pueden configurarse con la prioridad que se requiera, siempre que sea la misma para todos.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Información adicional del bono que visualiza el usuario desde la plataforma de usuarios online.</td></tr><tr><td><strong><code>URL Imagen principal</code></strong></td><td>URL</td><td>Enlace de la imagen que se muestra al usuario al visualizar el bono.</td></tr><tr><td><strong><code>Fecha de expiración o Días</code></strong></td><td>Selector</td><td><p>Define el plazo para redimir el bono. Con la opción <strong>"</strong><em><strong>Días</strong></em><strong>"</strong> se ingresa la cantidad de días hasta su vencimiento; con la opción <strong>"</strong><em><strong>Fecha</strong></em><strong>"</strong> se indica la fecha exacta de expiración. Cumplido el plazo, el bono queda inactivo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Los campos <strong><code>Días</code></strong> y <strong><code>Fecha expiración</code></strong> son dinámicos y se visualizan según la opción seleccionada.</p></div></td></tr><tr><td><strong><code>¿Cliente puede repetir bono?</code></strong></td><td>Selector</td><td>Define si el mismo usuario puede volver a redimir este bono.</td></tr><tr><td><strong><code>¿Es para?</code></strong></td><td>Lista desplegable</td><td>Asocia el bono a una campaña, módulo o funcionalidad específica de la plataforma <em>(por ejemplo: ruleta, sorteo, CRM, landing de registro, fidelización, cashback, bono de cumpleaños, referidos, beneficios, tours)</em>, definiendo el contexto en el que será gestionado y ejecutado.</td></tr><tr><td><strong><code>Tipo de bono</code></strong></td><td>Lista desplegable</td><td>Define si el bono se asigna automáticamente al momento del registro del usuario o si no se asigna de forma automática.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selector</td><td>Determina quiénes pueden acceder al bono. Con la opción pública, está disponible para todos los jugadores; con la opción privada, solo pueden obtenerlo los usuarios VIP.</td></tr><tr><td><strong><code>Prefijo</code></strong></td><td>Texto</td><td>Código único que identifica y diferencia el bono creado de los demás registrados en el sistema.</td></tr><tr><td><strong><code>Cantidad de jugadores</code></strong></td><td>Numérico</td><td>Determina la cantidad de jugadores que pueden acceder a este bono.</td></tr><tr><td><strong><code>¿Se dará bono con algún proveedor?</code></strong></td><td>Selector</td><td>Indica si el bono se otorga a través de un proveedor externo. Al seleccionar <strong>"</strong><em><strong>Sí</strong></em><strong>"</strong>, se habilita el campo <strong><code>Proveedor</code></strong>.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Selector</td><td>Define el proveedor al que aplica el bono. Para este tipo de bono corresponde seleccionar <strong>Digitain</strong>.</td></tr><tr><td><strong><code>¿El jugador puede hacer cashout con apuestas del bono?</code></strong></td><td>Selector</td><td>Define si el usuario puede realizar <a href="https://virtualsoft.gitbook.io/untitled/glosario#cashout">cashout</a> en las apuestas efectuadas con el saldo FreeBet.</td></tr><tr><td><strong><code>¿Cuota por?</code></strong></td><td>Selector</td><td><p>Define cómo se evalúan las cuotas de las apuestas realizadas con el saldo FreeBet, determinando en cuáles apuestas puede utilizarse el bono.</p><ul><li><strong>Por selecciones:</strong> la cuota se evalúa de forma individual, por cada selección que compone la apuesta.</li><li><strong>Por totales:</strong> la cuota se evalúa de forma conjunta, sobre el resultado total de todas las selecciones.</li></ul></td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<details>

<summary>🔽 Cuota por: Selecciones</summary>

Define las cuotas que debe cumplir cada selección de una apuesta para que el saldo FreeBet pueda utilizarse en ella. Las apuestas que no cumplan estos valores no se cubren con el bono.

<table><thead><tr><th width="141.2962646484375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mínima cuota por selecciones</code></strong></td><td>Cuota mínima que debe tener cada selección incluida en la apuesta.</td></tr><tr><td><strong><code>Máxima cuota por selecciones</code></strong></td><td>Cuota máxima permitida para cada selección incluida en la apuesta.</td></tr><tr><td><strong><code>Mínima cantidad en selecciones</code></strong></td><td>Número mínimo de selecciones que debe contener la apuesta.</td></tr><tr><td><p><strong><code>Mínima cuota total</code></strong></p><p><em>(no editable)</em></p></td><td><p>Cuota total mínima que debe alcanzar la apuesta. El sistema la calcula elevando la cuota mínima por selección al número de selecciones mínimas requeridas.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si la cuota mínima por selección es <strong>2</strong> y se requieren <strong>3 selecciones</strong>, la cuota total mínima será <strong>8</strong> <em>(2 × 2 × 2 = 8)</em>.</p></div></td></tr></tbody></table>

</details>

<details>

<summary>🔽 Cuota por: Totales</summary>

Define las cuotas que debe cumplir la apuesta en su conjunto para que el saldo FreeBet pueda utilizarse en ella. Las apuestas que no cumplan estos valores no se cubren con el bono.

<table><thead><tr><th width="133.333251953125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mínima cuota por totales</code></strong></td><td>Cuota mínima que debe alcanzar la apuesta considerando todas sus selecciones.</td></tr><tr><td><strong><code>Máxima cuota por totales</code></strong></td><td>Cuota máxima permitida para la apuesta considerando todas sus selecciones.</td></tr><tr><td><strong><code>Mínima cantidad en selecciones</code></strong></td><td>Número mínimo de selecciones que debe contener la apuesta.</td></tr><tr><td><p><strong><code>Mínima cuota total</code></strong></p><p><em>(no editable)</em></p></td><td><p>Cuota total mínima que debe alcanzar la apuesta. El sistema la calcula elevando la cuota mínima por totales a la cantidad mínima de selecciones requeridas.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si la cuota mínima por totales es <strong>2</strong> y se requieren <strong>3 selecciones</strong>, la cuota total mínima será <strong>8</strong> <em>(2 × 2 × 2 = 8)</em>.</p></div></td></tr></tbody></table>

</details>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden data-search="false"><thead><tr><th width="132.00006103515625">Campo</th><th width="126.111083984375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Campaña de Marketing</code></strong></td><td>Lista desplegable</td><td>Asocia el bono a una campaña de marketing previamente creada.</td></tr><tr><td><strong><code>Tipo campaña</code></strong></td><td>Lista desplegable</td><td>Define el objetivo principal del bono dentro de la estrategia de campaña. Las opciones disponibles son:</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="149">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Adquisición</code></strong></td><td>Bono destinado a atraer nuevos usuarios.</td></tr><tr><td><strong><code>Retención</code></strong></td><td>Bono diseñado para mantener activos a los usuarios actuales.</td></tr><tr><td><strong><code>Reactivación</code></strong></td><td>Bono orientado a recuperar usuarios inactivos.</td></tr><tr><td><strong><code>Retención de saldo</code></strong></td><td>Bono para incentivar el uso del saldo existente y evitar retiros.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden data-search="false"><thead><tr><th width="128"></th><th width="119"></th><th></th></tr></thead><tbody><tr><td><strong><code>Detalle de Campaña</code></strong></td><td>Lista desplegable</td><td><p>Define la clasificación específica del bono, facilitando su identificación, trazabilidad y análisis desde la administración de bonos.</p><p>Este campo es <strong>obligatorio</strong> y admite una única categoría entre las opciones del sistema <em>(por ejemplo: Bono de registro, Referidos, CRM fidelización)</em>. Si no se selecciona, el sistema muestra un mensaje de error.</p></td></tr><tr><td><strong><code>Asignación de bono</code></strong></td><td>Lista desplegable</td><td>Determina si este bono asigna otro bono previamente creado.</td></tr></tbody></table>

***

#### 5.1. Opciones avanzadas

Parámetros adicionales que personalizan el comportamiento del bono.

<details>

<summary>🔽 Opciones avanzadas</summary>

<table><thead><tr><th width="191.3333740234375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Permisos</code></strong></td><td>Define si se otorga dinero directamente al usuario o si se asigna un bono previamente creado en el sistema.</td></tr><tr><td><strong><code>Código Global</code></strong></td><td>Código configurado en BackOffice que limita la cantidad máxima de usuarios que pueden acceder al bono.</td></tr><tr><td><strong><code>Códigos Promocionales</code></strong></td><td>Código promocional configurado en BackOffice, utilizado para guiar las campañas promocionales.</td></tr><tr><td><strong><code>¿Habilitar códigos únicos?</code></strong></td><td>Define si el bono puede ser <a href="https://open-2c.gitbook.com/url/preview/site_E7EPL/glosario/~/revisions/lyO9OIXttMrjpQGurqj2#redimir">redimido</a> mediante códigos únicos generados automáticamente por el sistema.</td></tr></tbody></table>

</details>

***

#### 5.2. Campos adicionales

<table><thead><tr><th width="151.5">Campo</th><th width="106.33343505859375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>¿Todas las condiciones son obligatorias?</code></strong></td><td>Selector</td><td>Define si todas las condiciones configuradas previamente deben cumplirse para que el saldo FreeBet pueda utilizarse en la apuesta.</td></tr><tr><td><strong><code>¿Es obligatorio el saldo en cero?</code></strong></td><td>Selector</td><td>Define si el usuario debe tener el saldo de su cuenta en cero para poder acceder al bono FreeBet.</td></tr><tr><td><strong><code>Tipo producto</code></strong></td><td>Selector</td><td><p>Define el segmento al que aplica el bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Para FreeBet, la única opción disponible es <strong>Sportsbook</strong>. Al seleccionarla se habilitan las configuraciones que permiten delimitar los deportes, ligas, mercados o partidos en los que aplica el bono.</p></div></td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="98">Campo</th><th width="97">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Deporte</code></strong></td><td>Botón</td><td>Registra los deportes aplicables al bono. Al presionar <strong>Añadir</strong>, se habilita la fila en la tabla para ingresar el ID correspondiente.</td></tr><tr><td><strong><code>Mercados</code></strong></td><td>Botón</td><td>Registra los mercados permitidos. El botón <strong>Añadir</strong> habilita la fila para ingresar el identificador del mercado.</td></tr><tr><td><strong><code>Ligas</code></strong></td><td>Botón</td><td>Registra las ligas asociadas al bono. Al seleccionar <strong>Añadir</strong>, se habilita el campo en la tabla para ingresar uno o varios ID, separados por coma.</td></tr><tr><td><strong><code>Partidos</code></strong></td><td>Botón</td><td>Registra eventos específicos. El botón <strong>Añadir</strong> habilita la fila para ingresar el ID del partido correspondiente.</td></tr></tbody></table>

{% hint style="info" %}
Estas configuraciones son opcionales y sirven para restringir el uso del bono a deportes, mercados, ligas o partidos determinados. Si no se especifican, el bono aplica a las apuestas deportivas que cumplan el resto de condiciones configuradas.
{% endhint %}
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="152"></th><th width="106"></th><th></th></tr></thead><tbody><tr><td><strong><code>Tipo de apuesta</code></strong></td><td>Selector múltiple</td><td><p>Define las modalidades en las que el bono está habilitado.</p><ul><li><strong>Single:</strong> apuesta simple sobre un único evento.</li><li><strong>Multiple:</strong> combinación de varios eventos en un mismo cupón; requiere acierto total.</li><li><strong>System:</strong> combinación estructurada en múltiples apuestas internas, con posibilidad de retorno parcial.</li></ul></td></tr><tr><td><strong><code>Tipo de evento</code></strong></td><td>Selector único</td><td><p>Define el estado del evento en el que el bono está habilitado.</p><ul><li><strong>Both:</strong> aplica para eventos <em>Pre-match</em> y <em>Live</em>.</li><li><strong>Pre-match:</strong> eventos programados, antes de iniciar.</li><li><strong>Live:</strong> eventos en curso <em>(apuestas en vivo)</em>.</li></ul></td></tr><tr><td><strong><code>Mínima cantidad de selecciones</code></strong></td><td>Numérico</td><td>Número mínimo de eventos que debe contener una apuesta múltiple para que el bono sea válido.</td></tr><tr><td><strong><code>Mínima cuota en selecciones</code></strong></td><td>Numérico</td><td>Cuota mínima requerida para cada selección incluida en la apuesta.</td></tr><tr><td><strong><code>Mínima cuota total</code></strong></td><td>Numérico</td><td>Cuota mínima acumulada que debe alcanzar la apuesta para que el bono aplique.</td></tr><tr><td><strong><code>Repetir partidos</code></strong></td><td>Botón</td><td><p>Controla si el bono puede utilizarse más de una vez sobre el mismo partido.</p><ul><li><strong>Activado:</strong> el usuario puede realizar varias apuestas en el mismo partido utilizando el mismo bono, siempre que disponga de saldo FreeBet.</li><li><strong>Desactivado:</strong> el bono solo puede aplicarse una vez por partido, aunque el usuario tenga saldo restante.</li></ul></td></tr><tr><td><strong><code>Repetir mercados</code></strong></td><td>Botón</td><td><p>Define si el bono puede utilizarse más de una vez en el mismo tipo de apuesta dentro de un partido.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> en un partido se puede apostar al ganador, al total de goles, al primer gol, etc. Cada uno de estos corresponde a un tipo de apuesta diferente.</p></div><ul><li><strong>Activado:</strong> el usuario puede repetir el bono en el mismo tipo de apuesta.</li><li><strong>Desactivado:</strong> el usuario solo puede usar el bono una vez por cada tipo de apuesta dentro del partido.</li></ul></td></tr></tbody></table>

***

#### 5.3. Moneda

<details>

<summary>🔽 Parámetros de configuración por moneda</summary>

Al dar clic en la moneda correspondiente al país con el que se ingresó a la plataforma, se despliegan las siguientes configuraciones:

<table><thead><tr><th width="135.77777099609375">Campo</th><th width="118.888916015625">Tipo</th><th width="431.44439697265625">Descripción</th></tr></thead><tbody><tr><td><strong><code>Mínimo valor fijo</code></strong></td><td>Numérico</td><td>Especifique un valor minimo para un FREEBET que se puede otorgar a un jugador.</td></tr><tr><td><strong><code>Máximo valor fijo</code></strong></td><td>Numérico</td><td>Especifique un valor maximo para un FREEBET que se puede otorgar a un jugador.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Archivo CSV</td><td>Archivo CSV con los ID de los usuarios habilitados para recibir el bono.</td></tr></tbody></table>

</details>

***

### 6. Reglas y validaciones

* Si algún campo obligatorio no está configurado, el bono no se crea.
* El bono FreeBet no requiere rollover: el saldo entregado queda disponible de inmediato para realizar apuestas.
* Para este bono, el campo **`Tipo producto`** admite únicamente la opción **Sportsbook**.
* El bono se asigna únicamente a los usuarios que cumplen los criterios definidos _(tipo, campaña, cantidad de jugadores, códigos o carga de archivo CSV)_.
* Cuando un bono FreeBet está asignado y activo, el usuario visualiza un apartado de **Saldo FreeBet** en la plataforma. Al realizar una apuesta que cumpla las condiciones configuradas, el valor correspondiente se descuenta de este saldo.
* En la plataforma de usuarios online siempre se visualiza el saldo mínimo configurado.
* Si la apuesta es inferior al mínimo valor fijo, el bono no se aplica y el monto se descuenta del saldo apuestas del usuario.
* Si la apuesta supera el máximo valor fijo, el bono cubre únicamente ese valor máximo y el excedente se descuenta del saldo apuestas del usuario.
* La configuración del campo **`¿Cliente puede recibir otros bonos adicionales después del actual?`** solo aplica mientras el bono está activo.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="105">Versión</th><th width="140">Fecha</th><th width="157">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>15/08/2025</td><td>David Velasquez</td><td>Documento inicial.</td></tr></tbody></table>

</details>
