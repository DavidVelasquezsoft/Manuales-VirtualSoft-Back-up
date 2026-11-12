# Apuestas Deportivas

<mark style="color:$info;">Desde este módulo el usuario realiza sus apuestas deportivas en la plataforma de usuarios online: consulta los eventos disponibles, arma su boleto, confirma la apuesta y hace seguimiento a su resultado. También puede apostar con el saldo de sus bonos y, cuando el evento lo permite, cerrar una apuesta antes de que termine mediante el cashout.</mark>

{% hint style="warning" %}
**Nota**: Este módulo opera con uno de dos proveedores _(Altenar o Digitain)_ según el partner configurado. El proveedor se define desde el BackOffice y determina la apariencia del sportsbook, los mercados disponibles y las opciones habilitadas, como el cashout. [Más información](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion/proveedores-internos#id-3.1-configuraciones-disponibles).
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso:** Plataforma de usuarios online > Menú principal > **Deportivas**

***

### 2. Visualización

<figure><img src="https://699353801-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FyyrHDz69FZMnpZ9NBm8u%2Fuploads%2Fgit-blob-1884c4576d9c7023cdc2bfc9486b91bcd5facf09%2Fimage%20(189).png?alt=media" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Apuestas Deportivas.</p></figcaption></figure>

***

### 3. Acciones del usuario

<table><thead><tr><th width="212">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Seleccionar el deporte</strong></td><td>El usuario elige la disciplina de su interés <em>(fútbol, tenis, baloncesto, etc.)</em> desde el menú de categorías.</td></tr><tr><td><strong>Elegir el evento</strong></td><td>Dentro del deporte seleccionado se despliegan los partidos o encuentros disponibles, tanto los que aún no inician como los que están en curso.</td></tr><tr><td><strong>Seleccionar el mercado</strong></td><td>Al hacer clic sobre una cuota, el pronóstico se agrega al boleto. El mercado corresponde a aquello que se está pronosticando <em>(ganador del partido, total de goles, hándicap, etc.)</em>.</td></tr><tr><td><strong>Configurar el boleto</strong></td><td>El usuario define el monto que desea apostar. Si el boleto contiene una sola selección corresponde a una apuesta <strong>simple</strong>; si contiene varias, a una apuesta <strong>combinada</strong>.</td></tr><tr><td><strong>Confirmar la apuesta</strong></td><td>Con el botón <strong>Apostar</strong> se registra el boleto y se descuenta el monto del saldo disponible.</td></tr><tr><td><strong>Realizar cashout</strong></td><td>Cuando está disponible, permite cerrar una apuesta antes de que el evento finalice. Ver Cashout.</td></tr></tbody></table>

#### 3.1. Elementos del sportsbook

<table><thead><tr><th width="186">Elemento</th><th width="158">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Búsqueda de eventos</code></strong></td><td>Campo de texto</td><td>Localiza un equipo, torneo o país específico dentro de la oferta disponible.</td></tr><tr><td><strong><code>Mercados</code></strong></td><td>Listado dinámico</td><td>Opciones sobre las que se puede pronosticar <em>(resultado final, total de goles, doble oportunidad, hándicap, etc.)</em>. Varían según el deporte y el evento seleccionado.</td></tr><tr><td><strong><code>Cuotas</code></strong></td><td>Botones interactivos</td><td><p>Valor que multiplica el monto apostado para calcular la ganancia potencial.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Las cuotas se actualizan en tiempo real. Si una cuota cambia mientras el boleto está abierto, el sistema lo informa antes de confirmar la apuesta.</p></div></td></tr><tr><td><strong><code>Boletos combinados</code></strong></td><td>Opciones seleccionables</td><td>Permiten reunir varias selecciones en una sola apuesta. La ganancia potencial es mayor porque las cuotas se multiplican entre sí, pero basta con que una selección falle para perder la apuesta completa.</td></tr><tr><td><strong><code>Monto de apuesta</code></strong></td><td>Campo numérico</td><td>Valor que el usuario arriesga. Al ingresarlo, el sistema calcula y muestra automáticamente la ganancia potencial.</td></tr><tr><td><strong><code>Apostar</code></strong></td><td>Botón</td><td>Confirma el boleto y registra la apuesta.</td></tr><tr><td><strong><code>Mis apuestas</code></strong></td><td>Sección</td><td>Reúne las apuestas del usuario, tanto las que siguen abiertas como las ya resueltas. Desde el detalle de una apuesta abierta se accede al cashout cuando está disponible.</td></tr></tbody></table>

***

### 4. Apuestas con saldo bono

El usuario puede apostar con dos tipos de saldo, y la diferencia entre ambos determina si el dinero se puede retirar o no:

<table><thead><tr><th width="150">Tipo de saldo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Saldo real</strong></td><td>Dinero propio del usuario, proveniente de sus depósitos y de las ganancias ya liberadas. Puede utilizarse para apostar y también retirarse.</td></tr><tr><td><strong>Saldo bono</strong></td><td>Saldo entregado por un bono, acreditado dentro del sportsbook del proveedor. Únicamente puede utilizarse para apostar y <strong>no es retirable</strong> hasta cumplir las condiciones del bono.</td></tr></tbody></table>

El usuario consulta sus bonos activos y el estado de cada uno desde la sección [**Gestión > Mis bonos**.](gestion/mis-bonos..md)

**¿Cómo se convierte el saldo bono en saldo real?** Depende del tipo de bono que se haya entregado:

<table><thead><tr><th width="188">Tipo de bono</th><th>Funcionamiento</th></tr></thead><tbody><tr><td><strong>Bono con rollover</strong></td><td>El usuario debe apostar un monto total determinado <em>(el</em> <a href="https://virtualsoft.gitbook.io/untitled/glosario#rollover"><em>rollover</em></a><em>)</em> antes de que el saldo del bono se libere. El avance se contabiliza por el dinero apostado, sin importar si las apuestas se ganan o se pierden.</td></tr><tr><td><strong>Bono FreeBet</strong></td><td>No exige rollover. El usuario utiliza el saldo de inmediato y las ganancias obtenidas se acreditan como saldo real.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Cada bono tiene sus propias condiciones de uso _(cuota mínima y máxima, cantidad de selecciones, tipo de apuesta, y los deportes, ligas o partidos habilitados)_. Las apuestas que no cumplan esas condiciones no avanzan el bono. El usuario puede consultarlas en los términos y condiciones de cada bono desde **Mis bonos**.
{% endhint %}

{% hint style="danger" %}
**Importante:** Si el usuario agota su saldo bono sin completar las condiciones, o si el bono vence antes de utilizarlo, el saldo se pierde y no se convierte en saldo real.
{% endhint %}

***

### 5. Cashout

El [cashout](https://virtualsoft.gitbook.io/untitled/glosario#cashout) permite cerrar una apuesta antes de que el evento termine y recibir de inmediato el valor que ofrece el sportsbook en ese momento, sin esperar al resultado final. Es una forma de asegurar una ganancia parcial cuando la apuesta va bien, o de recuperar parte del monto apostado cuando va mal.

<table><thead><tr><th width="190">Aspecto</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Dónde se realiza</strong></td><td>Desde el detalle de la apuesta en la sección <strong>Mis apuestas</strong>. Cuando la opción está habilitada, se muestra el botón de cashout junto al valor ofrecido.</td></tr><tr><td><strong>Valor ofrecido</strong></td><td>No es fijo: se recalcula en tiempo real según cómo se desarrolla el evento y las cuotas vigentes. Puede ser mayor o menor al monto apostado.</td></tr><tr><td><strong>Disponibilidad</strong></td><td>No todas las apuestas lo permiten. Depende del proveedor configurado para el partner, del evento, del mercado y del tipo de apuesta. Si la apuesta no admite cashout, el botón no se muestra.</td></tr><tr><td><strong>Al aceptarlo</strong></td><td>La apuesta se cierra de inmediato por el valor mostrado y deja de depender del resultado del evento. La operación no puede deshacerse.</td></tr></tbody></table>

{% hint style="danger" %}
**Importante:** Cuando la apuesta se realizó con **saldo bono**, el valor del cashout **no se acredita como saldo real** ni queda disponible para retiro: regresa al **saldo bono** del proveedor, donde puede seguir utilizándose para apostar bajo las mismas condiciones del bono.

Además, el cashout solo está disponible si la apuesta se realizó con **una parte** del saldo bono. Si el usuario apostó la totalidad del saldo en una sola apuesta, esa apuesta no tendrá cashout.
{% endhint %}

{% hint style="warning" %}
**Nota:** El cashout no modifica el avance del rollover. El monto apostado ya se contabilizó al momento de realizar la apuesta, aunque esta se cierre anticipadamente.
{% endhint %}

***

### 6. Validaciones y reglas del negocio:

* El usuario solo puede apostar con el saldo disponible en su cuenta _(saldo depósito, saldo retiro o saldo bono)_.
* Una vez confirmada, una apuesta **no puede modificarse ni cancelarse**. La única forma de cerrarla antes del final del evento es mediante el cashout, cuando esté disponible.
* Las cuotas están sujetas a cambios hasta el momento de la confirmación. Si una cuota cambia mientras el boleto está abierto, el sistema lo informa antes de registrar la apuesta.
* Las ganancias se calculan y acreditan automáticamente al cierre del evento, según el mercado apostado.
* Las apuestas en vivo pueden presentar un leve retraso y una validación adicional del sistema antes de ser aceptadas.
* El saldo bono no es retirable: se convierte en saldo real únicamente cuando el usuario cumple las condiciones del bono. En los bonos FreeBet, las ganancias obtenidas se acreditan directamente como saldo real.
* Las apuestas que no cumplen las condiciones configuradas en el bono _(cuotas, cantidad de selecciones, tipo de apuesta, y deportes, ligas o partidos habilitados)_ no avanzan el bono.
* El valor obtenido por cashout en una apuesta realizada con saldo bono regresa al saldo bono y queda sujeto a las condiciones del bono; no se acredita como saldo real.
* El cashout únicamente está disponible cuando la apuesta se realizó con una parte del saldo bono. Si se utilizó la totalidad del saldo en una sola apuesta, la apuesta no admite cashout.
* Al cambiar el proveedor de este módulo, las apuestas y la información registradas con el proveedor anterior se conservan y vuelven a estar disponibles cuando ese proveedor se active nuevamente.
* Las opciones disponibles en el módulo, incluido el cashout, dependen del proveedor configurado para el partner.

{% hint style="warning" %}
**Nota:** Cuando existan torneos o sorteos activos, estos se muestran en los [banners](https://virtualsoft.gitbook.io/untitled/glosario/#banners) con la cantidad de usuarios participantes _(torneos)_ o inscritos _(sorteos)_. La información aparece en la parte inferior junto al cronómetro correspondiente y se actualiza automáticamente cada 120 segundos.
{% endhint %}

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>30/10/2025</td><td>Ronald Peláez</td><td>Formato inicial</td></tr><tr><td>1.1</td><td>04/11/2025</td><td>Karol Navia</td><td>Ajuste por cambio de proveedor.</td></tr><tr><td>1.2</td><td>13/10/2026</td><td>David Velasquez</td><td>Actualización del manual</td></tr></tbody></table>

</details>
