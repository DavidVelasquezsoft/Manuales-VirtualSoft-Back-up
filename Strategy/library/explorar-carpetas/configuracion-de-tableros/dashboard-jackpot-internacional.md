# Dashboard Jackpot internacional

<mark style="color:$info;">Este dashboard presenta información de los</mark> [<mark style="color:$info;">jackpots internacionales</mark>](https://virtualsoft.gitbook.io/plantillas/glosario#jackpot-internacional)<mark style="color:$info;">, permitiendo analizar el comportamiento del pozo acumulado, los aportes por partner y país, y el detalle de los ganadores. Cuenta con una vista resumida para el análisis general por</mark>[ <mark style="color:$info;">jackpot padre</mark>](https://virtualsoft.gitbook.io/plantillas/glosario#jackpot-padre) <mark style="color:$info;">y una vista detallada para el análisis por operación participante.</mark>

{% hint style="warning" %}
**Nota:** Este reporte está disponible únicamente para operadores con permisos habilitados.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Jackpot Internacional

***

### 2. Acciones disponibles

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Aplicar filtros</strong></td><td>Permite filtrar la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</td></tr><tr><td><a href="dashboard-jackpot-internacional.md#id-3.-visualizacion-del-dashboard"><strong>Visualizar contenido del tablero</strong></a></td><td><p>Utiliza las herramientas del dashboard, tales como:</p><ul><li>Filtros dinámicos.</li><li>Tablas de resultados con <a href="https://virtualsoft.gitbook.io/plantillas/glosario#jackpot-internacional">Jackpots internacionales</a> validos</li></ul><p>Permite navegar e interactuar con los diferentes contenidos y vistas del dashboard entre la resumida y la detallada.</p></td></tr><tr><td><strong>Exportar contenido</strong></td><td>El dashboard permite exportar su contenido. Para más información, consulte la guía de exportación <a data-mention href="./#id-3.-exportar-contenido">#id-3.-exportar-contenido</a>.</td></tr></tbody></table>

***

### 3. Contenido del dashboard

Al ejecutar la consulta, se despliega la información de los [jackpots internacionales](https://virtualsoft.gitbook.io/plantillas/glosario#jackpot-internacional) según los filtros aplicados. El dashboard cuenta con dos vistas que pueden seleccionarse según el nivel de análisis requerido: una vista general por [jackpot padre](https://virtualsoft.gitbook.io/plantillas/glosario#jackpot-padre) y una vista con el desglose por operación participante.

{% tabs %}
{% tab title="Resumida" %}
La vista resumida presenta la información consolidada por jackpot padre. Cada registro corresponde a un jackpot internacional y agrupa el pozo acumulado de todas sus operaciones asociadas.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (222).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Vista resumida Jackpot internacional</p></figcaption></figure>

#### Filtros

Permiten visualizar la información de la vista resumida según los criterios seleccionados. Los filtros disponibles son:

<table><thead><tr><th width="150">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Rango de fechas</td><td>Filtra por el rango de fechas correspondiente al inicio del jackpot.</td></tr><tr><td><strong><code>ID</code></strong> <a href="https://virtualsoft.gitbook.io/plantillas/glosario#jackpot-padre"><strong><code>Padre Jackpot</code></strong></a></td><td>Numérico</td><td>Identificador único del jackpot principal, que permite consultar la información general de los jackpots asociados a este.</td></tr><tr><td><strong><code>Nombre del Jackpot</code></strong></td><td>Campo de texto</td><td>Indica el nombre asignado al jackpot.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra según el estado del jackpot <em>(Activo, Inactivo o Ganado)</em>.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra por el partner en el que se creó el jackpot.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país donde se encuentra el partner o donde se originó la apuesta.</td></tr><tr><td><strong><code>Moneda base</code></strong></td><td>Lista desplegable</td><td>Filtra según la moneda base configurada para el jackpot.</td></tr></tbody></table>

#### Tabla de resultados

La información se presenta agrupada por[ **jackpot padre**](https://virtualsoft.gitbook.io/plantillas/glosario#jackpot-padre), de modo que cada fila consolida los valores de todas las operaciones y series asociadas a ese jackpot. Los valores monetarios se expresan en la moneda base configurada.

{% hint style="warning" %}
**Nota:** En la parte superior de la tabla se muestra una fila de totales que consolida la suma de los valores de las columnas numéricas mostradas en el reporte.
{% endhint %}

<table><thead><tr><th width="220">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Padre Jackpot</code></strong></td><td>Muestra el identificador único del Jackpot Principal al que pertenece la serie (<em>Si aplica</em>).</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre asignado al jackpot internacional.</td></tr><tr><td><strong><code>Fecha Inicio</code></strong></td><td>Fecha en la que comenzó la acumulación o campaña del jackpot internacional.</td></tr><tr><td><strong><code>Valor Acum. Base</code></strong></td><td>Monto total acumulado que aportaron todas las operaciones al pozo del jackpot internacional convertido a la moneda base configurada <em>(por ejemplo: USD)</em>.</td></tr><tr><td><strong><code>Jugadores Participantes</code></strong></td><td>Número de jugadores únicos que realizaron apuestas que aportaron al jackpot.</td></tr><tr><td><strong><code>Operaciones Participantes</code></strong></td><td>Número de operaciones (<em>Partner y país</em>) en las que está presente el jackpot internacional.</td></tr><tr><td><strong><code>Series</code></strong></td><td>Cantidad de repeticiones configuradas del jackpot internacional.</td></tr><tr><td><strong><code>Cantidad de caídas</code></strong></td><td>Número de veces que las series del jackpot que ha sido ganado y entregado a lo largo de su ciclo de operación, contabilizando todas sus series finalizadas.</td></tr><tr><td><strong><code>Cantidad de Apuestas</code></strong></td><td>Número total de apuestas que aportaron al jackpot en todas sus series, considerando únicamente las jugadas válidas para su acumulación.</td></tr><tr><td><strong><code>Valor Apostado Jackpot</code></strong></td><td>Valor total apostado en las jugadas que aportaron al jackpot en todas sus series, expresado en su moneda base.</td></tr><tr><td><strong><code>Valor Premios Jackpot</code></strong></td><td>Valor total de los premios entregados en las series del jackpot padre que ya han caído, expresado en su moneda base.</td></tr><tr><td><strong><code>GGR Jackpot</code></strong></td><td><p><a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">Ingreso bruto</a> generado por las jugadas asociadas al jackpot, es decir, lo que la operación retiene una vez descontados los premios entregados.</p><p><strong>Fórmula:</strong> <em>Valor Apostado Jackpot − Valor Premios Jackpot</em></p></td></tr></tbody></table>
{% endtab %}

{% tab title="Detallada" %}
La vista detallada desglosa la información por cada operación participante del jackpot y presenta, en una tabla independiente, la información del ganador.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (224).png" alt=""><figcaption><p>Figura #2: Captura de pantalla Vista detallada Jackpot internacional</p></figcaption></figure>

#### Filtros

Al seleccionar la vista **Detallada**, se habilitan los siguientes filtros adicionales:

<table><thead><tr><th width="150">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha inicio</code></strong></td><td>Rango de fechas</td><td>Filtra por el rango de fechas correspondiente al inicio del jackpot.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra por el partner en el que se creó el jackpot.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país donde se encuentra el partner o donde se originó la apuesta.</td></tr><tr><td><strong><code>ID Jugador Ganador</code></strong></td><td>Numérico</td><td>Indica el identificador único del usuario ganador del jackpot.</td></tr><tr><td><strong><code>ID Apuesta Ganadora</code></strong></td><td>Numérico</td><td>Filtra por el identificador de la apuesta que disparó el jackpot.</td></tr><tr><td><strong><code>Moneda Base</code></strong></td><td>Selector</td><td>Selecciona la moneda base con la que está configurado el jackpot internacional.</td></tr></tbody></table>

#### **Tablas de resultados**

Esta vista presenta dos tablas complementarias: la **tabla de detalle**, que desglosa cada operación participante del jackpot, y la **tabla de Información Ganador**, ubicada en la parte inferior, que reúne los datos del jugador y la apuesta con los que se ganó el jackpot.

{% hint style="warning" %}
**Nota:** Los valores monetarios de esta vista se presentan en moneda local.
{% endhint %}

* **Tabla de detalle**

Cada registro corresponde a una operación participante de un [Jackpot internacional](https://virtualsoft.gitbook.io/plantillas/glosario#jackpot-internacional), permitiendo identificar el comportamiento del pozo en cada **partner** y **país**.

<table><thead><tr><th width="214.66668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong> <a href="https://virtualsoft.gitbook.io/plantillas/glosario#jackpot-padre"><strong><code>Padre Jackpot</code></strong></a></td><td>Muestra el identificador único del Jackpot Principal al que pertenece la serie (<em>Si aplica</em>).</td></tr><tr><td><strong><code>Id Jackpot Internacional</code></strong></td><td>Identificador único del jackpot individual asociado a un ID <a href="https://virtualsoft.gitbook.io/plantillas/glosario#jackpot-padre">Padre</a>.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre comercial asignado al jackpot.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Nombre de la operación donde se generó el jackpot internacional.</td></tr><tr><td><strong><code>País</code></strong></td><td>Muestra el país del partner al que pertenece el jackpot internacional.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del jackpot <em>(Activo, Inactivo o Ganado)</em>.</td></tr><tr><td><strong><code>Fecha Inicio</code></strong></td><td>Fecha y hora en la que comenzó el conteo del jackpot.</td></tr><tr><td><strong><code>Moneda Base</code></strong></td><td>Moneda base configurada para el jackpot.</td></tr><tr><td><strong><code>Valor Acum. Local</code></strong></td><td><p>Monto acumulado del jackpot en la moneda local del partner.</p><p><strong>Fórmula:</strong> <em>Monto apuesta × % de acumulación</em></p></td></tr><tr><td><strong><code>Valor Acum. Base</code></strong></td><td><p>Monto acumulado del jackpot convertido a la moneda base de la compañía <em>(por ejemplo: USD)</em>.</p><p><strong>Fórmula:</strong> <em>(Monto apuesta × % de acumulación) / TRM</em></p></td></tr><tr><td><strong><code>Cantidad Participantes</code></strong></td><td>Número de jugadores únicos que realizaron apuestas que aportaron al jackpot.</td></tr><tr><td><strong><code>Cantidad Apuestas</code></strong></td><td>Número total de apuestas que aportaron al jackpot, considerando únicamente las jugadas válidas para su acumulación.</td></tr><tr><td><strong><code>Valor Apostado Jackpot</code></strong></td><td>Valor total apostado en las jugadas que aportaron al jackpot, expresado en moneda local.</td></tr><tr><td><strong><code>Valor Premios Jackpot</code></strong></td><td><p>Valor total de los premios entregados por las jugadas que aportaron al jackpot, expresado en moneda local.</p><p><strong>Fórmula:</strong> <em>Monto acumulado (en moneda base) × TRM</em></p></td></tr><tr><td><strong><code>GGR Jackpot</code></strong></td><td><p><a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">Ingreso bruto</a> generado por las jugadas asociadas al jackpot en esa operación, es decir, lo que retiene una vez descontados los premios entregados.</p><p><strong>Fórmula:</strong> <em>Valor Apostado Jackpot − Valor Premios Jackpot</em></p></td></tr></tbody></table>

* **Tabla de Información Ganador**

Presenta, de forma independiente, los datos del jugador y la apuesta con los que se ganó el jackpot.

<table><thead><tr><th width="220">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Jackpot Internacional</code></strong></td><td>Identificador único del jackpot individual que fue ganado.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner en el cual se pagó el jackpot ganador.</td></tr><tr><td><strong><code>País</code></strong></td><td>País del partner donde se pagó el jackpot.</td></tr><tr><td><strong><code>ID Jugador Ganador</code></strong></td><td>Identificador interno del jugador ganador del jackpot.</td></tr><tr><td><strong><code>Fecha Caída</code></strong></td><td>Fecha y hora exacta en la que el jackpot se disparó y fue ganado.</td></tr><tr><td><strong><code>ID Apuesta Ganadora</code></strong></td><td>Identificador de la apuesta que disparó el jackpot.</td></tr><tr><td><strong><code>Vertical Ganadora</code></strong></td><td>Vertical a la que pertenece la apuesta con la que el jugador ganó el jackpot <em>(por ejemplo: Casino, Deportivas, etc.)</em>.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/plantillas/glosario#trm"><strong><code>TRM</code></strong></a> <strong><code>Pago</code></strong></td><td>Tasa de cambio utilizada por el sistema para convertir el premio del jackpot de moneda base a moneda local al momento del pago.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 4. Validaciones y reglas del negocio:

* El reporte solo está disponible para operadores con permisos habilitados y muestra únicamente la información de los partners habilitados en el perfil.
* Los valores correspondientes a montos acumulados, premios y porcentajes se muestran con hasta dos decimales.
* La información del jugador ganador se presenta en una tabla independiente de la tabla de detalle.
* Si algunas columnas se muestran vacías, es porque el reporte no dispone de esa información para ese registro.

***

### 5. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21/07/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
