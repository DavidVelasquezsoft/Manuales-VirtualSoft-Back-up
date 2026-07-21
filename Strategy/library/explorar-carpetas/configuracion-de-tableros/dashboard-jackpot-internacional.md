# Dashboard Jackpot internacional

<mark style="color:$info;">Este dashboard presenta información de los jackpots internacionales, permitiendo analizar el comportamiento del pozo acumulado, los aportes por partner y país, y el detalle de los ganadores. Ofrece una vista resumida para el análisis general por jackpot padre y una vista detallada para el análisis por operación participante, apoyando la toma de decisiones comerciales.</mark>

{% hint style="warning" %}
**Nota:** Este reporte está disponible únicamente para operadores con permisos habilitados.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Jackpot Internacional

***

### 2. Acciones disponibles

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Aplicar filtros</strong></td><td>Permite filtrar la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</td></tr><tr><td><strong>Visualizar contenido del tablero</strong></td><td><p>Utiliza las herramientas del dashboard, tales como:</p><ul><li>Filtros dinámicos.</li><li>Tablas de resultados con Jackpots internacionales validos</li></ul><p>Permite navegar e interactuar con los diferentes contenidos y vistas del dashboard entre la resumida y la detallada.</p></td></tr><tr><td><strong>Exportar contenido</strong></td><td>El dashboard permite exportar su contenido. Para más información, consulte la guía de exportación <a data-mention href="./#id-3.-exportar-contenido">#id-3.-exportar-contenido</a>.</td></tr></tbody></table>

***

### 3. Visualización del dashboard

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega la información de los jackpots internacionales según los filtros aplicados. El reporte cuenta con dos vistas que pueden seleccionarse según el nivel de análisis requerido.

{% tabs %}
{% tab title="Resumida" %}
La vista resumida presenta la información consolidada por jackpot padre. Cada registro corresponde a un jackpot internacional y agrupa el pozo acumulado de todas sus operaciones asociadas.

#### Visualización



#### Filtros

Permiten visualizar la información del tablero según los criterios seleccionados. Los filtros disponibles varían según la vista seleccionada.

<table><thead><tr><th width="150">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Padre Jackpot</code></strong></td><td>Numérico</td><td>Identificador único del jackpot principal, que permite consultar todas las series (jackpots hijos) generadas a partir de sus reinicios.</td></tr><tr><td><strong><code>Nombre del Jackpot</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre asignado al jackpot.</td></tr><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Rango de fechas</td><td>Filtra por el rango de fechas correspondiente al inicio del jackpot.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra según el estado del jackpot <em>(Activo, Inactivo o Ganado)</em>.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra por el partner u operación en la que se creó el jackpot.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra por el país donde se encuentra el partner o donde se originó la apuesta.</td></tr><tr><td><strong><code>Moneda base</code></strong></td><td>Lista desplegable</td><td>Filtra según la moneda base configurada para el jackpot.</td></tr></tbody></table>

#### Tabla de resultados



<table><thead><tr><th width="220">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Padre Jackpot</code></strong></td><td>Código que agrupa varios jackpots relacionados dentro de una misma campaña o jackpot maestro.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre comercial asignado al jackpot.</td></tr><tr><td><strong><code>Fecha Inicio</code></strong></td><td>Fecha y hora en la que comenzó el conteo del jackpot.</td></tr><tr><td><strong><code>Valor Acum. Base</code></strong></td><td>Monto acumulado del jackpot convertido a la moneda base de la compañía <em>(por ejemplo: USD)</em>.</td></tr><tr><td><strong><code>Jugadores Participantes</code></strong></td><td>Número de jugadores únicos que realizaron apuestas que aportaron al jackpot.</td></tr><tr><td><strong><code>Operaciones Participantes</code></strong></td><td>Número de operaciones en las que está presente el jackpot.</td></tr><tr><td><strong><code>Series</code></strong></td><td>Cantidad de series configuradas o repeticiones del jackpot padre.</td></tr><tr><td><strong><code>Cantidad de caídas</code></strong></td><td>Cantidad de jackpots individuales que ya fueron ganados dentro del jackpot padre.</td></tr><tr><td><strong><code>Cantidad de Apuestas</code></strong></td><td>Número total de apuestas que aportaron al jackpot, considerando únicamente las jugadas válidas para su acumulación.</td></tr><tr><td><strong><code>Valor Apostado Jackpot</code></strong></td><td>Valor total apostado de las jugadas que contaron al jackpot.</td></tr><tr><td><strong><code>Valor Premios Jackpot</code></strong></td><td>Valor de los premios de las jugadas que contaron al jackpot.</td></tr><tr><td><strong><code>GGR Jackpot</code></strong></td><td>Ingreso bruto generado por las apuestas asociadas al jackpot <em>(apuestas menos premios)</em>.</td></tr></tbody></table>

{% hint style="info" %}
En la parte inferior de la tabla se muestra una fila de totales, que consolida la suma de las columnas numéricas del reporte.
{% endhint %}
{% endtab %}

{% tab title="Detallada" %}
La vista detallada desglosa la información por cada operación participante del jackpot y presenta, en una tabla independiente, la información del ganador. Los valores de esta vista se expresan en moneda local.

#### Visualización



#### Filtros

Al seleccionar la vista **Detallada**, se habilitan los siguientes filtros adicionales:

<table><thead><tr><th width="150">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Jackpot</code></strong></td><td>Numérico</td><td>Indica el identificador único del jackpot individual.</td></tr><tr><td><strong><code>Fecha de caída</code></strong></td><td>Rango de fechas</td><td>Especifica la fecha o el periodo en el que ocurrió la caída del jackpot.</td></tr><tr><td><strong><code>ID Jugador Ganador</code></strong></td><td>Numérico</td><td>Filtra por el identificador único del usuario ganador del jackpot.</td></tr><tr><td><strong><code>ID Apuesta Ganadora</code></strong></td><td>Numérico</td><td>Filtra por el identificador de la apuesta que disparó el jackpot.</td></tr></tbody></table>

#### **Tablas de resultados**

**Se prensentan 2 tablas de resultados la tabla detalle y la información ganador en lla parte inferior (Aqui nose como poner una buena descripción para que se sepa que hay 2 tablas y la otra se explica mas abajo)**

<table><thead><tr><th width="220">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Padre Jackpot</code></strong></td><td>Código que agrupa varios jackpots relacionados dentro de una misma campaña o jackpot maestro.</td></tr><tr><td><strong><code>Id Jackpot Internacional</code></strong></td><td>Identificador único de cada jackpot individual asociado a un ID Padre Jackpot.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre comercial asignado al jackpot.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Nombre de la operación u operador donde se generó el jackpot.</td></tr><tr><td><strong><code>País</code></strong></td><td>País donde se encuentra el partner o donde se originó la apuesta.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del jackpot <em>(Activo, Inactivo o Ganado)</em>.</td></tr><tr><td><strong><code>Fecha Inicio</code></strong></td><td>Fecha y hora en la que comenzó el conteo del jackpot.</td></tr><tr><td><strong><code>Moneda Base</code></strong></td><td>Moneda base configurada para el jackpot.</td></tr><tr><td><strong><code>Valor Acum. Local</code></strong></td><td>Monto acumulado del jackpot en la moneda local del partner.</td></tr><tr><td><strong><code>Valor Acum. Base</code></strong></td><td>Monto acumulado del jackpot convertido a la moneda base de la compañía <em>(por ejemplo: USD)</em>.</td></tr><tr><td><strong><code>Cantidad Participantes</code></strong></td><td>Número de jugadores únicos que realizaron apuestas que aportaron al jackpot.</td></tr><tr><td><strong><code>Cantidad Apuestas</code></strong></td><td>Número total de apuestas que aportaron al jackpot, considerando únicamente las jugadas válidas para su acumulación.</td></tr><tr><td><strong><code>Valor Apostado Jackpot</code></strong></td><td>Valor total apostado de las jugadas que contaron al jackpot.</td></tr><tr><td><strong><code>Valor Premios Jackpot</code></strong></td><td>Valor de los premios de las jugadas que contaron al jackpot.</td></tr><tr><td><strong><code>GGR Jackpot</code></strong></td><td>Ingreso bruto generado por las apuestas asociadas al jackpot <em>(apuestas menos premios)</em>.</td></tr></tbody></table>

**Tabla de Información Ganador**

Presenta, de forma independiente, los datos del jugador y la apuesta con los que se ganó el jackpot.

<table><thead><tr><th width="220">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Jackpot Internacional</code></strong></td><td>Identificador único del jackpot individual que fue ganado.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner en el cual se pagó el jackpot ganador.</td></tr><tr><td><strong><code>País</code></strong></td><td>País del partner donde se pagó el jackpot.</td></tr><tr><td><strong><code>ID Jugador Ganador</code></strong></td><td>Identificador interno del jugador ganador del jackpot.</td></tr><tr><td><strong><code>Fecha Caída</code></strong></td><td>Fecha y hora exacta en la que el jackpot se disparó y fue ganado.</td></tr><tr><td><strong><code>ID Apuesta Ganadora</code></strong></td><td>Identificador de la apuesta que disparó el jackpot.</td></tr><tr><td><strong><code>Vertical Ganadora</code></strong></td><td>Vertical a la que pertenece la apuesta con la que el jugador ganó el jackpot <em>(por ejemplo: Casino, Deportivas, etc.)</em>.</td></tr><tr><td><strong><code>TRM Pago</code></strong></td><td>Tasa de cambio utilizada por el sistema para convertir el premio del jackpot de moneda base a moneda local al momento del pago.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 6. Fórmulas del jackpot internacional

<details>

<summary>🔽 Fórmulas de acumulación y pago</summary>

**Acumulación**

* _Valor acumulable base (USD) = (Monto apuesta × % de acumulación) / TRM_
* _Valor acumulable local = (Monto apuesta × % de acumulación)_

**Conversión y entrega**

* _Valor premio (moneda local) = Monto acumulado (en moneda base) × TRM_

</details>

***

### 7. Validaciones y reglas del negocio:

* El reporte solo está disponible para operadores con permisos habilitados y muestra únicamente la información de los partners habilitados en el perfil.
* En la vista resumida, el valor acumulado corresponde a la suma de los jackpots agrupados por jackpot padre.
* La TRM de pago es la tasa con la que el sistema convirtió el premio de moneda base a moneda local al momento de pagar el jackpot.
* Los valores de la vista detallada se expresan en moneda local.
* Las fechas se muestran con formato de día, fecha y hora.
* Los valores correspondientes a montos acumulados, premios y porcentajes se muestran con hasta dos decimales.
* La información del usuario ganador se presenta en una tabla independiente de la tabla de operaciones participantes.
* Si algunas columnas se muestran vacías, es porque el reporte no dispone de esa información para ese registro.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>18/07/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
