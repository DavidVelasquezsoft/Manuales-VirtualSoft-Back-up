---
description: >-
  Permite crear sorteos definiendo premios, reglas y fechas. Los usuarios
  acumulan participaciones según las condiciones establecidas y, al finalizar,
  se eligen los ganadores de forma aleatoria.
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

# Crear Sorteo

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Torneos y Bonos > Crear sorteo

***

### 2. visualización general

<figure><img src="../../../../.gitbook/assets/image (280).png" alt=""><figcaption><p>Figura #1: Captura de pantalla formulario para la creación de un sorteo.</p></figcaption></figure>

***

### **3. Acciones de usuario**

<table><thead><tr><th width="176">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Crear sorteo</strong></td><td>Completa el formulario con los campos requeridos y haz clic en el botón <strong>“<code>Crear Sorteo</code>”</strong> para registrar el sorteo con la configuración establecida.</td></tr><tr><td><strong>Establecer términos y condiciones del sorteo</strong></td><td>Desde el botón "<strong><code>Ver términos y condiciones</code></strong>" desplegará un editor de texto que permitirá ingresar la información sobre los términos y condiciones que tendrá este sorteo.</td></tr></tbody></table>

### 4. Formulario para la creación de un sorteo.

{% hint style="warning" %}
**Nota**: Los campos que finalizan el nombre con un <mark style="color:red;">\*</mark> son obligatorios para la creación del sorteo.
{% endhint %}

<table><thead><tr><th width="194.77777099609375">Campo</th><th width="137.11114501953125">Tipo</th><th width="418.77777099609375">Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha inicial</code></strong></td><td>Calendario</td><td>Fecha a partir de la cual el sorteo estará activo y disponible para la participación de los usuarios.</td></tr><tr><td><strong><code>Fecha final</code></strong></td><td>Calendario</td><td><p>Fecha hasta la cual el sorteo estará activo y disponible para la participación de los usuarios.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La fecha final debe ser posterior a la fecha inicial.</p></div></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre que tendrá el sorteo.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Numérico</td><td><p>Define la prioridad de evaluación del sorteo frente a otros sorteos activos en simultáneo. A mayor número, mayor prioridad.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si existen tres sorteos configurados al mismo tiempo con los siguientes valores:</p><ul><li><strong>Sorteo A</strong>: 1</li><li><strong>Sorteo B</strong>: 2</li><li><strong>Sorteo C</strong>: 3</li></ul><p>Primero se evaluará la participación en el <strong>Sorteo C</strong>, ya que tiene la prioridad más alta.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Detalles adicionales del sorteo que se visualizará en la plataforma usuarios online.</td></tr><tr><td><strong><code>Usuario puede inscribirse varias veces?</code></strong></td><td>Interruptor </td><td>Especifica si el usuario puede participar en el sorteo más de una vez.</td></tr><tr><td><strong><code>Es para</code></strong></td><td>Lista desplegable</td><td><p>Define la campaña a la cual estará asociado el sorteo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Cada campaña puede incluir reglas y validaciones específicas que condicionan los campos requeridos para la creación del sorteo. Se recomienda revisar la sección <a href="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-sorteo/flujos-de-creacion-de-sorteos"><strong>Flujos de creación de sorteos</strong></a> para conocer las particularidades de cada caso.</p></div></td></tr></tbody></table>

{% columns %}
{% column width="41.66666666666667%" %}

{% endcolumn %}

{% column width="58.33333333333333%" %}
Según la opción tomada en el campo "**`Es para`**" se visualizará una de estas configuraciones.

<table><thead><tr><th width="120">Campo</th><th width="262.171875">Descripción</th></tr></thead><tbody><tr><td><strong><code>Jugadores</code></strong></td><td>Carga un archivo .csv con los id´s de los usuarios que tendrán acceso directo al sorteo.</td></tr><tr><td><strong><code>Niveles disponibles</code></strong></td><td><p>Selecciona los niveles de lealtad que tendrán acceso y podrán participar en el sorteo</p><p><em>(Ver manual de</em> <a href="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-sorteo/flujos-de-creacion-de-sorteos/flujo-de-creacion-sorteo-para-usuarios-lealtad."><em>creación de sorteos para usuarios por niveles de lealtad</em></a><em>).</em></p></td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="194"></th><th width="137"></th><th></th></tr></thead><tbody><tr><td><strong><code>¿Visible para todos los jugadores?</code></strong></td><td>Interruptor </td><td>Permite mostrar u ocultar el sorteo para todos los usuarios en la plataforma Usuarios Online.</td></tr><tr><td><strong><code>¿El usuario debe suscribirse?</code></strong></td><td>Interruptor </td><td>Define si es necesario que el usuario se suscriba al sorteo para participar.</td></tr><tr><td><strong><code>¿Es con Stickers?</code></strong></td><td>Interruptor</td><td><p>Establece si la participación del sorteo será recaudando Stickers o puntos</p><div data-gb-custom-block data-tag="hint" data-style="danger" class="hint hint-danger"><p><strong>Nota importante:</strong> Actualmente no existe lógica funcional para sorteos sin stickers, por lo que esta opción debe configurarse en <strong>“Sí”</strong>. La selección de esta opción determina los campos disponibles en el formulario: si se selecciona <strong>“Sí”</strong>, se habilitan las configuraciones correspondientes a <a href="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-sorteo/con-stickers.">sorteos con stickers</a>; si se selecciona <strong>“No”</strong>, se muestran configuraciones alternativas que no aplican al flujo actual y no funcionaría el sorteo creado.</p></div></td></tr><tr><td><strong><code>Mostrar contador</code></strong></td><td>Interruptor</td><td><p>Habilita o deshabilita la visualización de contadores de participación en las siguientes secciones.</p><ul><li><a href="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./visualizar-eventos./sorteos.#ver-detalle-de-sorteo-lupa"><strong>Visualizar sorteos</strong></a><strong>:</strong> Se muestra la cantidad de usuarios registrados y usuarios participando en el sorteo.</li><li><a href="https://virtualsoft.gitbook.io/manuales/usuarios/usuarios-online/manual-de-plataforma/sorteos#id-2.1.-otras-configuraciones"><strong>Usuarios online</strong></a><strong>:</strong> En cada sorteo se muestra un pop-up con la cantidad de jugadores inscritos.</li></ul></td></tr></tbody></table>

***

#### 4.1. Configuración por moneda

Al dar clic en la moneda correspondiente al país con el que se ingresó a la plataforma, se desplegarán las configuraciones asociadas al contexto monetario del sorteo, las cuales determinan las reglas de acumulación de stickers y la asignación de premios.

<details>

<summary><strong>Configuración de acumulación y premios.</strong></summary>

{% hint style="warning" %}
**Nota**: Algunos campos se mostrarán únicamente si el sorteo utiliza stickers. Además, el nombre de cada campo se adapta automáticamente según la vertical seleccionada. Si se eligen varias verticales, se desplegarán los campos correspondientes para cada una, aunque compartan la misma configuración.
{% endhint %}

<figure><img src="../../../../.gitbook/assets/image (1).png" alt=""><figcaption><p>Figura #2: Captura de pantalla configuraciones moneda.</p></figcaption></figure>

<table><thead><tr><th width="138">Campo</th><th width="98">Tipo</th><th width="445">Descripción</th></tr></thead><tbody><tr><td><strong><code>Mínimo valor para sumar un sticker</code></strong></td><td>Numérico</td><td><p>Define el umbral acumulativo requerido para generar stickers. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Una vez la suma de los depósitos o apuestas válidas alcanza este valor, se cumple la condición para otorgar los stickers configurados.</p></div></td></tr><tr><td><strong><code>Mínimo valor de depósito</code></strong></td><td>Numérico</td><td><p>Establece el valor mínimo que debe tener cada depósito o apuesta individual para que sea considerado dentro del acumulado. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si el valor es inferior al configurado, no se tendrá en cuenta para el cumplimiento del umbral.</p></div></td></tr><tr><td><strong><code>Cantidad de stickers necesarios por depósitos</code></strong></td><td>Numérico</td><td>Indica la cantidad de stickers que se otorgarán cada vez que el monto acumulado alcance el umbral definido.</td></tr></tbody></table>

#### Lógica de funcionamiento para obtener stikers

* Se valida que el depósito o apuesta cumpla el valor mínimo configurado.
* Si cumple, el monto apostado o depositado se acumula.
* Cuando el acumulado alcanza el umbral establecido, se asigna la cantidad de stickers definida.
* El proceso se repite conforme a la configuración aplicada.

#### 4.1.1.  Tipo de premio

Configura el tipo de premio que recibirá el ganador o los ganadores del sorteo.

<table><thead><tr><th width="131.22222900390625">Tipo de premio</th><th width="532.3333129882812">Descripción</th></tr></thead><tbody><tr><td><strong>Físico</strong></td><td>Al seleccionar esta opción, el premio será físico</td></tr><tr><td><strong>Dinero</strong></td><td>Al seleccionar esta opción, el premio del sorteo será dinero, </td></tr><tr><td><strong>Bono</strong></td><td>Al seleccionar esta opción, el premio del sorteo será en bonos.</td></tr></tbody></table>

**4.2.1. Campos generales**

Todos los premios comparten los campos generales, pero algunos incluyen campos específicos según su tipo.

<table><thead><tr><th width="137.66650390625">Campo</th><th width="115.22222900390625">Tipo</th><th width="503.00006103515625">Descripción</th></tr></thead><tbody><tr><td><strong><code>Posición</code></strong></td><td>Numérico</td><td>Posición en la tabla de premiaciones donde se asignará el premio <em>(Debe ser mayor a <strong>0</strong>).</em> </td></tr><tr><td><strong><code>URL imagen del premio</code></strong></td><td>URL</td><td>URL de la imagen que verá el usuario al ganar el sorteo <em>(En caso de ser dinero)</em>.</td></tr><tr><td><strong><code>Cupones ganadores</code></strong></td><td>Interruptor </td><td>Indica si los cupones previamente ganadores pueden participar o no en este premio.</td></tr><tr><td><strong><code>Jugadores ganadores</code></strong></td><td>Interruptor </td><td>Define si los jugadores ya ganadores pueden volver a participar.</td></tr><tr><td><strong><code>Hora</code></strong></td><td>Calendario</td><td>Hora exacta en la que se realizará el sorteo.</td></tr><tr><td><strong><code>¿El premio es para un mismo usuario?</code></strong></td><td>Interruptor </td><td><p>Define si el premio se asignará al mismo jugador o a jugadores distintos, Según la opción seleccionada, el sistema agrupa o separa los premios.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo activa reglas específicas según la hora y otras configuraciones. Consulta más abajo las Reglas de asignación de premios</p></div></td></tr><tr><td><strong><code>Importar CSV</code></strong></td><td>Archivo .CSV</td><td><p>Para agregar un premio rápidamente, con un CSV válido como el que se ve en el ejemplo: <a href="https://images.virtualsoft.tech/m/msj0212T1721147815.png">Ejemplo</a>.</p><p><em>(Tipo = 0 para <strong>Físico</strong>)</em></p><p><em>(Tipo = 1 para <strong>Dinero</strong>)</em><br><em>(Tipo = 3 para <strong>Bono</strong>)</em></p></td></tr></tbody></table>

Después de ingresar los datos, haz clic en el botón **"`Agregar`"** para registrar el premio.

Una vez agregado, los datos aparecerán en una tabla ubicada justo debajo, donde podrás:

<table><thead><tr><th width="128.88897705078125">Acción</th><th>Descrición</th></tr></thead><tbody><tr><td><strong>👁️ Visualizar</strong> </td><td>todos los campos registrados del premio.</td></tr><tr><td><strong>🗑️ Eliminar</strong></td><td>Al final de cada registro se muestra un botón <strong>"Eliminar"</strong>, que permite borrar ese premio.</td></tr><tr><td><strong>🖊️️ Editar</strong></td><td>Únicamente la <strong>URL de la imagen</strong> del bono directamente desde el campo correspondiente.</td></tr></tbody></table>

</details>

#### 4.3. Opciones avanzadas.

<details>

<summary>⚙️Detalles de configuración avanzada</summary>

Configura y personaliza opciones adicionales para adaptar el sorteo a necesidades específicas.

<figure><img src="../../../../.gitbook/assets/image (244).png" alt=""><figcaption><p>Figura #3: Captura de pantalla configuraciones avanzadas.</p></figcaption></figure>

<table><thead><tr><th width="153.33331298828125">Campo</th><th width="101.99993896484375">Tipo</th><th width="425.66668701171875">Descripción</th></tr></thead><tbody><tr><td><strong><code>Código global</code></strong></td><td>Numérico</td><td>Código configurado desde el <strong>BackOffice</strong> para este sorteo.</td></tr><tr><td><strong><code>URL imagen principal</code></strong></td><td>URL</td><td>URL de la imagen principal del sorteo, visible para todos los usuarios.</td></tr><tr><td><strong><code>URL fondo</code></strong></td><td>URL</td><td>URL de la imagen que se usará como fondo del sorteo, visible para todos los usuarios.</td></tr><tr><td><strong><code>URL fondo card</code></strong></td><td>URL</td><td>URL de la imagen de fondo de la tarjeta del sorteo, visible para todos los usuarios.</td></tr><tr><td><strong><code>Cantidad de sorteos</code></strong></td><td>Numérico</td><td>Cantidad de sorteos que se realizarán en la campaña.</td></tr><tr><td><strong><code>Máximo de jugadores ganadores</code></strong></td><td>Numérico</td><td>Cantidad máxima de jugadores que podrán ganar el sorteo.</td></tr><tr><td><strong><code>Mínimo de jugadores para sortear</code></strong></td><td>Numérico</td><td>Cantidad mínima de jugadores necesaria para realizar el sorteo.</td></tr><tr><td><strong><code>Regiones de usuario</code></strong></td><td>Lista desplegable</td><td>Selecciona las regiones donde estará disponible el sorteo.</td></tr><tr><td><strong><code>Departamentos de usuario</code></strong></td><td>Lista desplegable</td><td>Elige los departamentos en los que se habilitará el sorteo.</td></tr><tr><td><strong><code>Ciudades de usuario</code></strong></td><td>Lista desplegable</td><td>Define las ciudades donde estará disponible el sorteo.</td></tr><tr><td><strong><code>Periodicidad</code></strong></td><td>Lista desplegable</td><td>Define en <strong>horas</strong> la frecuencia con la que se realizará el sorteo</td></tr></tbody></table>

</details>

Para finalizar el proceso debes dar clic en el botón **"`Crear Sorteo`"**. Esto guardará la configuración y activará el sorteo para los usuarios.

***

### 5. Reglas de asignación de premios

* Si varios premios tienen la **misma hora** y **`¿El premio es para un mismo usuario?`** = **“Sí”**, se asignarán todos al mismo usuario sin límite.
* Si los premios tienen la **misma hora**, pero **`¿El premio es para un mismo usuario?`** = **“No”**, se asignarán a usuarios diferentes.
* El campo **`posición`** ya no define agrupación ni ganadores compartidos. Solo indica el lugar en la tabla de premiación.
* La única forma de que un jugador reciba varios premios es:
  * Que todos los premios tengan la **misma `hora`**.
  * **`¿El premio es para un mismo usuario?`** = "Sí”.

{% hint style="info" %}
**Ejemplo:** Se crean los siguientes premios para un sorteo:

* **Premio 1** — Hora: 15:00 — **`¿El premio es para un mismo usuario?`**: **Sí**
* **Premio 2** — Hora: 15:00 — **`¿El premio es para un mismo usuario?`**: **Sí**
* **Premio 3** — Hora: 15:00 — **`¿El premio es para un mismo usuario?`**: **No**

**Resultado:**

* Los **Premios 1 y 2** se asignan juntos al **mismo** usuario.
* El **Premio 3** se asigna a otro usuario **distinto**, aunque tenga la misma hora.
{% endhint %}

***

### 6. Control de Versiones

<details>

<summary>🕛Historial de versiones</summary>

<table><thead><tr><th width="100">Versión</th><th width="129">Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2025-07-23</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>2025-09-09</td><td>Ronald Pelaez</td><td>Nuevo campo de contador.</td></tr><tr><td>1.2</td><td>2026-03-31</td><td>Ronald Peláez</td><td>Nota sobre el funcionamiento de sorteo sin stickers</td></tr><tr><td>1.3</td><td>2026-15-05</td><td>Ronald Peláez</td><td>Mejora en formato completo del manual y agregar sorteo para usuarios lealtad.</td></tr></tbody></table>

</details>
