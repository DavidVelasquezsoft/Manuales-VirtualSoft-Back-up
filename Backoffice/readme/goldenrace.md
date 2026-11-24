# GoldenRace

<mark style="color:$info;">Registra apuestas en los juegos virtuales de GoldenRace desde el punto de venta e imprime el comprobante con el que se cobra el premio. Los juegos virtuales son eventos deportivos simulados, cuyos resultados se generan de forma automática.</mark>

{% hint style="warning" %}
**Nota:** Este módulo está disponible únicamente para **Doradobet Perú** y para los usuarios de tipo punto de venta.
{% endhint %}

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Golden Race

***

### 2. Visualización

{% hint style="danger" %}
**IMAGEN PENDIENTE: Figura #1**

**Captura:** pantalla principal del módulo, donde se vean las categorías de deportes virtuales, el selector de proveedor y la lista de juegos.

**Pie de figura:** Figura #1: Captura de pantalla sección GoldenRace.
{% endhint %}

***

### 3. Identificación del usuario

Antes de apostar, el punto de venta identifica al usuario que realiza la apuesta con su número de documento _(DNI)_. El sistema muestra una ventana de confirmación con los datos del usuario para verificar su identidad. Al presionar **Continuar**, se habilita el registro de la apuesta.

{% hint style="warning" %}
**Nota:** El usuario debe estar registrado en la plataforma, excepto cuando el modo de **apuestas anónimas** _(apuestas sin una cuenta registrada)_ está habilitado. En ese caso, los datos solicitados, como el documento o el número de teléfono, dependen de la configuración del partner o del país en [Ajustes Generales](herramientas/partner-ajustes/configuracion-1.md).
{% endhint %}

***

### 4. Acciones disponibles

<table><thead><tr><th width="176">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Deportes Virtuales</strong></td><td>Muestra la lista completa de juegos virtuales disponibles.</td></tr><tr><td><strong>Filtros de deportes</strong></td><td><p>Agrupa los juegos por tipo de deporte virtual <em>(fútbol, carreras de caballos, entre otros)</em>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Las categorías disponibles varían según el proveedor y la configuración del partner.</p></div></td></tr><tr><td><strong>Proveedor</strong></td><td>Selecciona el proveedor de los juegos <em>(Ejemplo: GoldenRace)</em>.</td></tr><tr><td><strong>Cargar más</strong></td><td>Despliega más juegos en la lista.</td></tr><tr><td><a href="goldenrace.md#id-5.-flujo-de-apuesta-y-pago"><strong>Imprimir</strong></a></td><td>Genera en PDF el comprobante de la apuesta, con los datos necesarios para cobrar el premio. El botón se ubica en la esquina inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 5. Flujo de apuesta y pago

{% stepper %}
{% step %}
**Identificar al usuario**

El punto de venta ingresa el DNI del usuario, verifica sus datos en la ventana de confirmación y presiona **Continuar**.
{% endstep %}

{% step %}
**Registrar la apuesta**

El punto de venta selecciona la categoría y el juego virtual, y registra la apuesta del usuario. Cada evento se presenta como una animación corta, con el resultado generado automáticamente.
{% endstep %}

{% step %}
**Imprimir el comprobante**

Al presionar **Imprimir**, el sistema genera el comprobante en PDF para entregarlo al usuario. En la parte inferior del comprobante se encuentran dos códigos de barras:

* El **primer código de barras** corresponde al **No. Ticket**.
* El **segundo código de barras** corresponde a la **Clave Ticket**.

{% hint style="danger" %}
**IMAGEN PENDIENTE: Figura #2**

**Captura:** comprobante de la apuesta en PDF, donde se vean los dos códigos de barras de la parte inferior.

**Pie de figura:** Figura #2: Captura de pantalla comprobante de apuesta de GoldenRace.
{% endhint %}
{% endstep %}

{% step %}
**Pagar el premio**

Si la apuesta resulta ganadora, el premio se paga desde **Caja > Pago premio virtuales**. Al escanear los códigos de barras del comprobante, se completan los filtros del ticket; después se consulta el ticket y se paga el premio. El proceso se describe en el manual [Pago premio virtuales](caja/pago-premio-virtuales.md).
{% endstep %}
{% endstepper %}

***

### 6. Validaciones y reglas del negocio:

* El módulo está disponible únicamente para **Doradobet Perú** y para los usuarios de tipo punto de venta.
* La apuesta requiere identificar al usuario con su DNI, salvo que el modo de apuestas anónimas esté habilitado.
* Los eventos y sus resultados se generan de forma aleatoria mediante un sistema y no dependen de eventos reales.
* Los eventos inician cada pocos minutos y cada uno dura aproximadamente entre 2 y 3 minutos.
* Los juegos disponibles varían según el país o la configuración del operador.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>01/02/2025</td><td>David Ortiz</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
