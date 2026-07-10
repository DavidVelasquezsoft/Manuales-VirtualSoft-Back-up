---
description: >-
  Permite crear y gestionar competencias en las que los usuarios participan por
  premios. En esta sección encontrarás información detallada sobre los campos
  disponibles para su configuración.
---

# Crear Torneo

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Torneos y bonos > Crear Torneo

***

### &#x20;2. visualización general

<figure><img src="../../../../.gitbook/assets/image (294).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección crear torneo.</p></figcaption></figure>

***

### 3. Formulario para creación de torneos

<table><thead><tr><th width="133.111083984375">Campo</th><th width="104.1851806640625">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha inicial</code></strong></td><td>Fecha</td><td>Fecha en la que el torneo va a iniciar.</td></tr><tr><td><strong><code>Fecha final</code></strong></td><td>Fecha</td><td>Fecha en la que finalizará el torneo.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre que tendrá el torneo.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Numérico</td><td><p>Orden de prioridad que tendrá el torneo para ser reclamado.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p> <strong>Ejemplo</strong>: <em>Si Torneo A (1), B (2), C (3); para reclamar C, primero se deben completar A y B.</em></p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Descripción breve del torneo.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selector</td><td><p>Define la accesibilidad del torneo y los usuarios que podrán visualizarlo y participar en él.<br></p><ul><li><strong>Público</strong>: Todos los usuarios de la plataforma podrán visualizar y participar en el torneo <em>(siempre que cumplan las condiciones configuradas)</em>.</li><li><p><strong>Privado</strong>: Solo podrán participar los usuarios definidos manualmente mediante configuraciones adicionales.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al seleccionar el tipo <strong>“Privado”</strong>, se habilitarán los siguientes campos:</p><ul><li><strong><code>Jugadores</code>:</strong> Carga un archivo <strong>.CSV</strong> con los ID de los usuarios autorizados para participar en el torneo <em>(El funcionamiento de este campo es con el</em><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/reportes/relacion-usuario-aggregato"> <em>ID agregador de los usuarios</em></a><em>)</em>.</li><li><strong><code>Visto para todos los jugadores</code>:</strong> Define si el torneo será visible únicamente para los usuarios incluidos en el listado o para todos los usuarios de la plataforma.</li></ul></div></li></ul></td></tr><tr><td><strong><code>¿Usuario debe inscribirse?</code></strong></td><td>Selector</td><td><p>Define si el jugador debe inscribirse explícitamente en el torneo para que sus apuestas sumen puntos.<br>Si está <strong>habilitado</strong>, únicamente los usuarios suscritos acumulan puntos; si no, las <strong>apuestas cuentan automáticamente a todos</strong> los usuarios participantes.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo aplica tanto para torneos <strong>públicos</strong> como <strong>privados</strong>.</p></div></td></tr><tr><td><strong><code>Es para?</code></strong> </td><td>Selector</td><td><p>Define la campaña a la cual estará asociado el sorteo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong>  Cada campaña puede incluir reglas y validaciones específicas que condicionan los campos requeridos para la creación del torneo. Se recomienda revisar la sección <a href="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-torneo/flujos-de-creacion-de-torneos"><strong>Flujos de creación de torneos</strong></a> para conocer las particularidades de cada caso.</p></div></td></tr></tbody></table>

* #### **`Tipo de producto`**

Establece las condiciones para que apliquen las apuestas al torneo según la vertical a la que va dirigido.

{% tabs %}
{% tab title="Sportsbook " %}
Las apuestas realizadas desde Sportsbook contarán para dar puntos en el torneo, esta vertical puede combinarse con el resto de las verticales. Al seleccionar verticales adicionales, el formulario desplegará dinámicamente los campos de configuración correspondientes para cada una, incluyendo los asociados a esta misma vertical.

<table><thead><tr><th width="139.59262084960938">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><p><strong><code>Permitir</code></strong> </p><p><strong><code>repetir</code></strong> </p><p><strong><code>apuestas en:</code></strong></p></td><td><p>Establece en que segmentos podrán repetir apuestas y aplicarán para el torneo.</p><ul><li><em><strong>Deportes</strong>: Se podrán repetir apuestas en deportes.</em> </li><li><em><strong>Mercados</strong>: Se podrán repetir apuestas en mercados.</em></li><li><em><strong>Ligas</strong>: Se podrán repetir apuestas en ligas.</em><br><br>En frente de cada configuración es necesario ingresar los id´s de los segmentos en los que se podrán repetir apuestas separados por (,)</li></ul></td></tr><tr><td><strong><code>Tipo de Ranking</code></strong></td><td><p></p><p>Establece como se medirá el ranking para dar los premios en el torneo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota: La sección</strong> <strong><code>Ranking</code> en</strong> <a href="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-torneo#id-3.1-moneda"><strong>configuraciones de moneda</strong></a> no se muestra si el Tipo de Ranking es <strong>Ganancia neta</strong> o <strong>Cuotas</strong>.</p></div></td></tr><tr><td><strong><code>Multiplicar líneas por puntos</code></strong></td><td>Multiplica puntos por cada línea de apuesta.<br><em>(Solo para Sportsbook.)</em></td></tr><tr><td><strong><code>Todas las condiciones son obligatorias</code></strong></td><td>Si se activa, el jugador debe cumplir con cada una de las configuraciones realizadas en este torneo para poder sumar puntos</td></tr><tr><td><strong><code>Mostrar contador</code></strong></td><td><p>Indica si se visualizará un contador en las siguientes secciones:</p><ul><li><strong>Visualizar torneos</strong>: Se visualizarán la cantidad de usuarios registrados y usuarios participando en el torneo.</li><li><strong>Usuarios online</strong>: En cada torneo se verá un pop-up indicando la cantidad de jugadores participando en el torneo.</li></ul></td></tr></tbody></table>

* **`Configuraciones de segmentos en Sportsbook`**

Configura el comportamiento de cada segmento en las apuestas deportivas

{% tabs %}
{% tab title="Deporte" %}
* **Visualización**

<figure><img src="../../../../.gitbook/assets/image (26).png" alt=""><figcaption><p>Figura #2: Captura de pantalla configuraciones deporte.</p></figcaption></figure>

* **Acciones del usuario**

<table><thead><tr><th width="214.888916015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Añadir deportes</strong></td><td>Añade deportes específicos para que apliquen con este bono</td></tr><tr><td><strong>Eliminar deportes agregados</strong></td><td>Elimina algún deporte agregado al bono.</td></tr></tbody></table>

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

<table><thead><tr><th width="211.77783203125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Id del mercado a añadir.</td></tr><tr><td> <strong><code>Mercados seleccionados</code></strong></td><td>Nombre del mercado a añadir, solo se acepta un nombre por mercado añadido.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL representativa del mercado.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Elimina el mercado añadido.</td></tr><tr><td><strong><code>Mercados</code></strong></td><td>Añade los mercados por ID, separados por comas (,).</td></tr></tbody></table>
{% endtab %}

{% tab title="Ligas" %}


* **Visualización**

<figure><img src="../../../../.gitbook/assets/image (28).png" alt=""><figcaption><p>Figura #4: Captura de pantalla configuraciones ligas.</p></figcaption></figure>

* **Acciones del usuario**

<table><thead><tr><th width="245.111083984375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Añadir ligas</strong></td><td>Añade ligas específicas para que apliquen con este bono</td></tr><tr><td><strong>Eliminar ligas agregados</strong></td><td>Elimina alguna ligas agregadas al bono.</td></tr></tbody></table>

* **¿Cómo añadir una liga?**\
  Utiliza el botón "**Añadir**" y completa los siguientes campos

<table><thead><tr><th width="211.77783203125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Id del la liga a añadir.</td></tr><tr><td><strong><code>ligas seleccionados</code></strong></td><td>Nombre de la liga a añadir, solo se acepta un nombre por liga añadido.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL representativa de la liga.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Elimina la liga añadida.</td></tr><tr><td><strong><code>Ligas</code></strong></td><td>Añade las ligas por ID, separados por comas (,).</td></tr></tbody></table>
{% endtab %}

{% tab title="Partidos" %}


* **Visualización**

<figure><img src="../../../../.gitbook/assets/image (29).png" alt=""><figcaption><p>Figura #4: Captura de pantalla configuraciones partidos.</p></figcaption></figure>

* **Acciones del usuario**

<table><thead><tr><th width="245.111083984375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Añadir partidos</strong></td><td>Añade partidos específicos para que apliquen con este bono</td></tr><tr><td><strong>Eliminar partidos agregados</strong></td><td>Elimina algún partidos agregados al bono.</td></tr></tbody></table>

* **¿Cómo añadir un partido?**\
  Utiliza el botón "**Añadir**" y completa los siguientes campos.

<table><thead><tr><th width="211.77783203125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Id del partido a añadir.</td></tr><tr><td><strong><code>partido seleccionados</code></strong></td><td>Nombre del partido a añadir, solo se acepta un nombre por partido añadido.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL representativa del partido.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Elimina el partido añadido.</td></tr><tr><td><strong><code>Partidos</code></strong></td><td>Añade los partidos por ID, separados por comas (,).</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

<table><thead><tr><th width="165.6666259765625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de apuesta</code></strong></td><td><p>Tipo de apuesta que aplicará para la devolución de saldo:</p><ul><li><strong>Single</strong>: Apuesta simple a un único pronóstico con un monto definido <em>(Ejemplo: Apostar $10 a que gana Real Madrid).</em></li><li><strong>Múltiple</strong>: Combina varias selecciones en una sola apuesta <em>(Ejemplo: Apostar $10 a que gana Real Madrid y Barcelona en sus respectivos partidos).</em></li><li><strong>System</strong>: Combina pronósticos permitiendo ganar incluso si falla uno <em>(Ejemplo: Apostar $10 a un sistema 2/3 entre Real Madrid, Barcelona y Juventus).</em></li></ul></td></tr><tr><td><strong><code>Tipo de evento</code></strong></td><td><p>Tipo de evento que aplicará para la devolución de saldo:</p><ul><li><strong>Both</strong>: Combina ambos mercados <em>(Ejemplo: Apostar $10 en un partido disponible tanto en pre-match como en live).</em></li><li><strong>Pre-match</strong>: Eventos que se pronostican antes de iniciar <em>(Ejemplo: Apostar $10 a que gana Real Madrid antes del inicio del partido).</em></li><li><strong>Live</strong>: Eventos en juego que solo se pueden apostar mientras se desarrollan <em>(Ejemplo: Apostar $10 a que habrá gol en el segundo tiempo mientras el partido está en curso).</em></li></ul></td></tr><tr><td><p><strong><code>Minima cantidad en</code></strong> </p><p><strong><code>selecciones</code></strong></p></td><td>Indica la cantidad mínima de selecciones que puede tener un usuario en apuestas múltiples y así aplique para el bono cashback.</td></tr><tr><td><p><strong><code>Mínima cuota</code></strong> </p><p><strong><code>en selecciones</code></strong></p></td><td>Indica la cuota mínima de apuestas en cada selección para aplicar a la devolución de saldo.</td></tr><tr><td><strong><code>Mínima cuota total</code></strong></td><td>Cantidad mínima de la cuota en el total de la apuesta para que aplique a la devolución de saldo.</td></tr></tbody></table>
{% endtab %}

{% tab title="Casino, Casino en Vivo y Virtuales " %}
Según la vertical seleccionada, solo se tendrán en cuenta para el torneo las apuestas realizadas en esa misma vertical. No es posible combinar verticales entre sí \
(Ejemplo: ✅ Sportsbook + Casino / ❌ Casino + Virtuales).

<table><thead><tr><th width="171.59262084960938">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de Ranking</code></strong></td><td><p></p><p>Establece cómo se medirá el ranking del torneo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota: La sección</strong> <strong>Ranking en configuraciones de moneda</strong> no se muestra si el Tipo de Ranking es <strong>Ganancia neta</strong> o <strong>Cuotas</strong>.</p></div></td></tr><tr><td><strong><code>Multiplicar líneas por puntos</code></strong></td><td>Multiplica puntos por cada línea de apuesta. <em>(Solo para Sportsbook.)</em></td></tr><tr><td><strong><code>Todas las condiciones son obligatorias</code></strong></td><td>Si se activa, el jugador debe cumplir con cada una de las configuraciones realizadas en este torneo para poder sumar puntos</td></tr><tr><td><strong><code>Mostrar contador</code></strong></td><td><p>Indica si se visualizará un contador en las siguientes secciones:</p><ul><li><strong>Visualizar torneos</strong>: Se visualizarán la cantidad de usuarios registrados y usuarios participando en el torneo.</li><li> <strong>Usuarios online</strong>: En cada torneo se verá un pop-up indicando la cantidad de jugadores participando en el torneo.</li></ul></td></tr></tbody></table>

* **`Configuraciones de segmentos`**&#x20;

Configura los criterios de participación del segmento, permitiendo seleccionar una o varias categorías, proveedores y productos que serán válidos para el torneo.

{% tabs %}
{% tab title="Categorías " %}
Permite seleccionar una o varias categorías en las que los participantes podrán competir y sumar puntos durante el torneo. Solo las categorías configuradas serán válidas para la participación.

* **Visualización**

<figure><img src="../../../../.gitbook/assets/image (295).png" alt=""><figcaption><p>Figura #5: Captura de pantalla configuración de categorías</p></figcaption></figure>

* **Configuración de categorías**

<table><thead><tr><th width="114.88885498046875">Campo</th><th width="169.3333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td>Selecciona en que categorías de casino el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Permite cargar una imagen para cada categoría seleccionada, la cual será utilizada para su representación dentro del torneo.
{% endhint %}
{% endtab %}

{% tab title="Proveedores" %}
Permite seleccionar uno o varios proveedores en los que los participantes podrán competir y sumar puntos durante el torneo. Solo las categorías configuradas serán válidas para la participación.

* **Visualización**

<figure><img src="../../../../.gitbook/assets/image (296).png" alt=""><figcaption><p>Figura #6:Captura de pantalla configuración de proveedores</p></figcaption></figure>

* **Configuración de Proveedores**

<table><thead><tr><th width="114.88885498046875">Campo</th><th width="169.3333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona con que proveedores el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Permite cargar una imagen para cada proveedor seleccionado, la cual será utilizada para su representación dentro del torneo.
{% endhint %}
{% endtab %}

{% tab title="Productos" %}
Permite seleccionar uno o varios productos en los que los participantes podrán competir y sumar puntos durante el torneo. Solo las categorías configuradas serán válidas para la participación.

* **Visualización**

<figure><img src="../../../../.gitbook/assets/image (297).png" alt=""><figcaption><p>Captura de pantalla configuración productos</p></figcaption></figure>

* **Configuración productos**

<table><thead><tr><th width="114.88885498046875">Campo</th><th width="169.3333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona con que proveedores el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Selecciona con que juegos el bono podrá retornar saldo al usuario en caso de perder la apuesta.</td></tr></tbody></table>

Por cada producto seleccionado es posible editar los siguientes campos:

<table><thead><tr><th width="145">Campo</th><th width="117">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Productos Seleccionados</code></strong></td><td>Selector múltiple</td><td>Muestra el nombre de todos los productos seleccionados en el torneo</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL</td><td>Permite ingresar la URL de la imagen que representará el producto dentro del torneo.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Numérico</td><td>Define el orden en que se visualizará el producto dentro del torneo.</td></tr><tr><td><strong><code>Eliminar</code></strong></td><td>Acción</td><td>Permite eliminar el producto de la configuración del torneo.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Depósitos" %}
{% hint style="warning" %}
**Nota:**  Al seleccionar la opción **`Depósito`** en el campo **`Tipo de producto`**, se muestran los parámetros de configuración específicos para los torneos basados en depósitos.
{% endhint %}

Este tipo de torneo asigna puntos a los jugadores según los depósitos realizados durante la vigencia del torneo. Solo se tendrán en cuenta los depósitos que cumplan con la configuración definida, y los puntos acumulados determinarán la posición de cada jugador en el ranking para la premiación.

* **`Tipo de depósitos que participan`**

<table><thead><tr><th width="195">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Primer depósito</code></strong></td><td>Solo contabiliza el primer depósito realizado por el jugador en la plataforma. Esta opción aplica a jugadores que aún no han efectuado depósitos previamente.</td></tr><tr><td><strong><code>Próximo depósito</code></strong></td><td>Participan todos los depósitos efectuados después del primer depósito del jugador.</td></tr><tr><td><strong><code>Todos los depósitos</code></strong></td><td>Participa cualquier depósito realizado por el jugador durante la vigencia del torneo.</td></tr></tbody></table>

* **`Origen de depósitos participantes`**

{% hint style="warning" %}
**Nota:** Si no se selecciona ningún punto de venta ni ninguna pasarela de pago, se tendrán en cuenta todos los depósitos realizados por los jugadores, independientemente del medio utilizado.
{% endhint %}

<table><thead><tr><th width="195">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Puntos de venta</code></strong></td><td>Selecciona uno o varios puntos de venta que participarán en el torneo. Únicamente se tendrán en cuenta los depósitos realizados a través de los puntos de venta seleccionados para la acumulación de puntos.</td></tr><tr><td><strong><code>Pasarelas de pago</code></strong></td><td>Elige una o varias pasarelas de pago que participarán en el torneo. Únicamente se tendrán en cuenta los depósitos realizados mediante las pasarelas seleccionadas para la acumulación de puntos.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Los puntos se asignan según la configuración definida en el campo **Ranking**. Se suman los depósitos que cumplen las condiciones del torneo y asigna los puntos de acuerdo a las configuraciones establecidas.
{% endhint %}
{% endtab %}
{% endtabs %}

#### 3.1 Moneda

Al seleccionar la moneda correspondiente al país, se muestran estas configuraciones:

<table><thead><tr><th width="151.22216796875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mínimo valor de la apuesta</code></strong></td><td>Monto mínimo para que la apuesta sume puntos en el torneo.</td></tr><tr><td><strong><code>Tipo de Premio</code></strong></td><td>Selecciona y agrega diferentes premios y tipos de premios al torneo.</td></tr></tbody></table>

#### 3.2 Ranking

{% hint style="warning" %}
**Nota:** La sección **Ranking** no aparece cuando el Tipo de Ranking es **Ganancia neta** o **Cuotas**.
{% endhint %}

Esta sección permite configurar el rango de puntos que se otorgarán según el monto apostado. Si un usuario realiza una apuesta dentro del rango, suma los puntos correspondientes.

<table><thead><tr><th width="170.66668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango inicial</code></strong></td><td>Monto mínimo apostado para empezar a otorgar puntos.</td></tr><tr><td><strong><code>Rango final</code></strong></td><td>Monto máximo apostado que delimita el rango.</td></tr><tr><td><strong><code>Puntos</code></strong></td><td>Cantidad de puntos que recibe el usuario si apuesta dentro del rango.</td></tr></tbody></table>

Para agregar más rangos, da clic en el botón "**Agregar**".

**Casos de uso para Ranking:**

* Si el tipo de ranking es **Montó Dinero** o **Líneas de apuestas**, esta sección se usa para definir cómo se traducen las apuestas o líneas en puntos según rangos.
* Si es **Ganancia neta** o **Cuotas**, no se usan rangos externos y esta sección queda oculta.

#### 3.3 Opciones avanzadas

<table><thead><tr><th width="270.111083984375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Código Global</code></strong></td><td>Código configurado desde BackOffice, asociado al bono, con límite máximo de usuarios.</td></tr><tr><td><strong><code>URL imagen principal</code></strong></td><td>URL de la imagen principal visible para todos los usuarios.</td></tr><tr><td><strong><code>Máximo de jugadores</code></strong></td><td>Cantidad máxima de jugadores permitidos en el torneo.</td></tr><tr><td><strong><code>Mínimo de jugadores</code></strong></td><td>Cantidad mínima de jugadores requerida para iniciar el torneo.</td></tr><tr><td><strong><code>Regiones de usuario</code></strong></td><td>Regiones donde el torneo estará disponible.</td></tr><tr><td><strong><code>Departamentos de usuario</code></strong></td><td>Departamentos donde estará habilitado el torneo.</td></tr><tr><td><strong><code>Ciudades de usuario</code></strong></td><td>Ciudades donde el torneo estará disponible.</td></tr><tr><td><strong><code>URL fondo</code></strong></td><td>URL de la imagen de fondo para el torneo.</td></tr><tr><td><strong><code>URL imagen central</code></strong></td><td>URL de la imagen central del torneo.</td></tr><tr><td><strong><code>URL imagen derecha</code></strong></td><td>URL de la imagen del lado derecho del torneo.</td></tr><tr><td><strong><code>URL fondo detallado</code></strong></td><td>URL del fondo interno del torneo.</td></tr><tr><td><strong><code>URL imagen central detallada</code></strong></td><td>URL de la imagen central detallada del torneo.</td></tr><tr><td><strong><code>URL imagen premios</code></strong></td><td>URL de la imagen que representa los premios del torneo.</td></tr></tbody></table>

***

### 4. Validaciones y Reglas de Negocio

* La selección de verticales afecta dinámicamente los campos del formulario.
* El orden define el flujo obligatorio de torneos; Un usuario no podrá reclamar un torneo de orden superior sin haber reclamado los anteriores.
* Si se selecciona **Cuotas**, se debe ingresar un **Valor Punto**, obligatorio, mayor a 0 _(se permiten decimales)._
* No se deben asignar puntos si la apuesta no es ganadora.
* La configuración de **tipo de ranking Cuotas** y **Valor Punto** se guarda si el torneo se almacena como plantilla.
* Si no se selecciona ningún **Punto de venta** ni ninguna **Pasarela de pago**, se tendrán en cuenta los depósitos realizados por cualquier medio disponible.
* Solo se tendrán en cuenta para el ranking los depósitos con estado **PAGADO** que hayan sido realizados durante el período de vigencia del torneo.

***

### 5. Glosario

<table><thead><tr><th width="150">Término</th><th>Definición</th></tr></thead><tbody><tr><td><strong>Tipo Producto</strong></td><td>Categoría de juegos que aportan puntos en el torneo <em>(ej. Sportsbook, Casino, Virtuales).</em></td></tr><tr><td><strong>Ranking</strong></td><td>Mecanismo de puntuación que define cómo se otorgan los premios.</td></tr><tr><td><strong>Cuotas</strong></td><td>Nuevo tipo de ranking exclusivo para Sportsbook. Calcula puntos en base a las cuotas ganadas.</td></tr><tr><td><strong>Valor Punto</strong></td><td>Factor de multiplicación aplicado a la cuota para determinar los puntos ganados en torneos tipo "<strong>Cuotas</strong>".</td></tr></tbody></table>

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="107">Versión</th><th width="141">Fecha</th><th width="157">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>07/07/2025</td><td>Ronald Peláez</td><td>Documento inicial unificado y ajustado a plantilla</td></tr><tr><td>1.1</td><td>08/09/2025</td><td>Ronald Peláez</td><td>Refinamiento de manual y nuevo campo de contador.</td></tr><tr><td>1.2</td><td>26/01/2026</td><td>David Velásquez</td><td>Ajuste en las configuraciones para crear torneo.</td></tr><tr><td>1.3</td><td>12/06/2026</td><td>Karol Navia</td><td>Agregar la opción depósito en el campo <strong><code>tipo producto</code></strong>.</td></tr></tbody></table>

</details>
