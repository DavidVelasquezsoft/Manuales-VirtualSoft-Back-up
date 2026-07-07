# Dashboard Retail

<mark style="color:$info;">El</mark> <mark style="color:$info;">**Dashboard Retail**</mark> <mark style="color:$info;">ofrece una vista analítica del desempeño de la red de puntos de venta físicos de cada partner por país. Permite medir y dar seguimiento a los principales KPIs, analizando la información por partner, país y estructura territorial para apoyar la toma de decisiones sobre la gestión de la red.</mark>

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Dashboard Retail

***

### 2. Configuraciones previas

Antes de visualizar el reporte, es necesario confirmar las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/tableros#id-2.-configuracion-previa).

***

### 3. Acciones disponibles

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="dashboard-retail.md#id-5.-kpis-generales"><strong>Aplicar filtros</strong></a></td><td>Permite filtrar la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</td></tr><tr><td><strong>Visualizar contenido del tablero</strong></td><td><p>Utiliza las herramientas del dashboard, tales como:</p><ul><li>Filtros dinámicos.</li><li>KPIs generales</li><li>Gráficas de barras horizontales (<em><strong>Rankings Top 10</strong></em>)</li><li>Gráficos de torta (<em>porcentaje de participación</em>)</li><li>Tablas con detalle por cada <a href="https://virtualsoft.gitbook.io/plantillas/glosario#punto-de-venta">punto de venta</a>.</li></ul><p>Permite navegar e interactuar con los diferentes contenidos del dashboard, visualizando distintas métricas, vistas y niveles de detalle de la información según las opciones seleccionadas, manteniendo los filtros previamente aplicados.</p></td></tr><tr><td><strong>Exportar contenido</strong></td><td>El dashboard permite exportar su contenido. Para más información, consulte la guía de exportación <a data-mention href="https://github.com/DavidVelasquezsoft/BackUp-Manuales-de-usuario/tree/main/Strategy/library/README.md#id-4.-exportar-contenido">https://github.com/DavidVelasquezsoft/BackUp-Manuales-de-usuario/tree/main/Strategy/library/README.md#id-4.-exportar-contenido</a>.</td></tr></tbody></table>

***

### 4. Filtros

Estos son los filtros disponibles del dashboard, los cuales permiten visualizar la información del tablero según los criterios seleccionados.

<table><thead><tr><th width="151.3333740234375">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha calendario transaccional</code></strong></td><td>Rango de fechas</td><td>Permite delimitar el periodo de análisis según el calendario transaccional, es decir, la fecha en que se registraron las transacciones en la plataforma.</td></tr><tr><td><strong><code>Fecha registro PV</code></strong></td><td>Rango de fechas</td><td>Filtra los puntos de venta según su fecha de registro o creación en el sistema.</td></tr><tr><td><strong><code>Estado PV</code></strong></td><td>Lista desplegable</td><td>Filtra los puntos de venta según su estado <em>(activo o inactivo)</em>.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Selecciona los partners sobre los cuales desea analizar la información.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona los países sobre los cuales se muestra la información del dashboard.</td></tr><tr><td><strong><code>Ciudad</code></strong></td><td>Lista desplegable</td><td>Filtra los puntos de venta según la ciudad a la que pertenecen.</td></tr><tr><td><strong><code>ID Punto de venta</code></strong></td><td>Numérico</td><td>Filtra por el identificador único del punto de venta.</td></tr></tbody></table>

***

### 5. KPIs generales

En la parte superior del dashboard se muestran los indicadores clave que resumen el desempeño de la red de puntos de venta según los filtros aplicados.

<table><thead><tr><th width="231.4630126953125">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total puntos de venta</code></strong></td><td>Cantidad total de puntos de venta registrados, sumando activos e inactivos.</td></tr><tr><td><strong><code>Puntos de venta activos</code></strong></td><td>Cantidad de puntos de venta que se encuentran activos.</td></tr><tr><td><strong><code>Puntos de venta inactivos</code></strong></td><td>Cantidad de puntos de venta que se encuentran inactivos.</td></tr><tr><td><strong><code>Registros</code></strong></td><td>Cantidad de usuarios registrados a través de los puntos de venta.</td></tr><tr><td><strong><code>Cantidad depósitos</code></strong></td><td>Número total de depósitos realizados en los puntos de venta.</td></tr><tr><td><strong><code>Valor depósitos</code></strong></td><td>Monto total de los depósitos realizados en los puntos de venta.</td></tr><tr><td><strong><code>Cantidad retiros</code></strong></td><td>Número total de retiros pagados en los puntos de venta.</td></tr><tr><td><strong><code>Valor retiros</code></strong></td><td>Monto total de los retiros pagados en los puntos de venta.</td></tr><tr><td><strong><code>Usuarios depositando</code></strong></td><td>Cantidad de usuarios únicos que realizaron al menos un depósito en el periodo consultado.</td></tr><tr><td><strong><code>Usuarios retirando</code></strong></td><td>Cantidad de usuarios únicos que realizaron al menos un retiro en el periodo consultado.</td></tr></tbody></table>

***

### 6. **Visualización de información**

El dashboard está organizado en cuatro vistas principales, seleccionables desde la parte superior derecha de la pantalla. Cada vista presenta una perspectiva diferente de la red de puntos de venta, desde el comportamiento histórico general hasta el detalle de las transacciones, permitiendo analizar distintas métricas y niveles de detalle según los filtros aplicados.

{% tabs %}
{% tab title="Historico" %}
Presenta gráficos generales de los puntos de venta organizados por meses, permitiendo observar la evolución de la red a lo largo del tiempo. Es la única vista que incorpora métricas _(total o máximo mensual)_ aplicables a sus gráficos.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (213) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Vista Historico</p></figcaption></figure>

#### Métricas

Las gráficas del dashboard permiten cambiar la información visualizada según la métrica seleccionada, actualizando automáticamente las graficas y resultados mostrados. Las métricas disponibles son:

<table><thead><tr><th width="118.62957763671875">Metrica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total</code></strong></td><td>Muestra los gráficos utilizando la suma total de los valores registrados por mes durante el período seleccionado.</td></tr><tr><td><strong><code>Maximo mensual</code></strong></td><td>Muestra los gráficos según el valor máximo registrado en un día de cada mes del período consultado.</td></tr></tbody></table>

#### Graficas

Las gráficas presentan la evolución mensual de los principales indicadores de la red de puntos de venta según la [métrica](dashboard-retail.md#metricas) seleccionada. Cada gráfico muestra un punto por mes, unido mediante una línea que permite visualizar la tendencia durante el período consultado, actualizando automáticamente la información.

<table><thead><tr><th width="127.4073486328125">Nombre</th><th width="119.25927734375">Tipo de gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado puntos de venta</code></strong></td><td>Gráfico de líneas</td><td><p>Representa la evolución de la red de puntos de venta según su estado a lo largo del periodo consultado. Cada estado <em>(activos e inactivos)</em> cuenta con una línea independiente, lo que permite comparar su comportamiento mes a mes e identificar el crecimiento o la disminución de la red.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Es la única gráfica de la vista que no se ve afectada por la métrica seleccionada; siempre refleja la cantidad de puntos de venta por estado.</p></div></td></tr><tr><td><strong><code>Registros</code></strong></td><td>Gráfico de líneas</td><td>Refleja la cantidad de usuarios registrados a través de los puntos de venta en cada mes del periodo consultado, lo que permite observar el ritmo de captación de la red. Según la métrica seleccionada, el valor de cada mes corresponde a la suma total de registros <em>(Total)</em> o el día con mayor número de registros del mes <em>(Máximo mensual)</em>.</td></tr><tr><td><strong><code>Usuarios depositando</code></strong></td><td>Gráfico de líneas</td><td>Ilustra la cantidad de usuarios únicos que realizaron depósitos en cada mes, útil para evaluar la base activa de jugadores que aporta a la operación. El valor mensual varía según la métrica: la suma total del mes <em>(Total)</em> o el día de mayor actividad <em>(Máximo mensual)</em>.</td></tr><tr><td><strong><code>Usuarios retirando</code></strong></td><td>Gráfico de líneas</td><td>Representa la cantidad de usuarios únicos que efectuaron retiros en cada mes, permitiendo analizar la demanda de pagos a lo largo del tiempo. De acuerdo con la métrica seleccionada, cada mes refleja el acumulado total <em>(Total)</em> o el valor del día más alto del mes <em>(Máximo mensual)</em>.</td></tr><tr><td><strong><code>Cantidad de depósitos</code></strong></td><td>Gráfico de líneas</td><td>Expone el número de depósitos efectuados en los puntos de venta durante cada mes, lo que permite dimensionar el volumen transaccional de la red. El valor representado responde a la métrica: el total acumulado del mes <em>(Total)</em> o el día con mayor cantidad de depósitos <em>(Máximo mensual)</em>.</td></tr><tr><td><strong><code>Valor de depósitos</code></strong></td><td>Gráfico de líneas</td><td>Representa el monto total depositado en los puntos de venta en cada mes, indicador clave del ingreso generado por la red. Según la métrica, cada mes corresponde a la suma total depositada <em>(Total)</em> o al día de mayor recaudación <em>(Máximo mensual)</em>.</td></tr><tr><td><strong><code>Cantidad de retiros</code></strong></td><td>Gráfico de líneas</td><td>Refleja el número de retiros pagados en los puntos de venta durante cada mes, lo que permite seguir el comportamiento de los pagos a los jugadores. El valor de cada mes depende de la métrica: el acumulado total <em>(Total)</em> o el día con mayor cantidad de retiros <em>(Máximo mensual)</em>.</td></tr><tr><td><strong><code>Valor de retiros</code></strong></td><td>Gráfico de líneas</td><td>Ilustra el monto total pagado por concepto de retiros en cada mes, complementando el análisis financiero frente a los depósitos. De acuerdo con la métrica seleccionada, representa la suma total del mes <em>(Total)</em> o el día de mayor valor pagado <em>(Máximo mensual)</em>.</td></tr></tbody></table>
{% endtab %}

{% tab title="Desempeño provincia" %}
Muestra rankings comparativos según la provincia en la que se ubican los puntos de venta, facilitando la identificación de las provincias con mayor o menor desempeño.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (212) (1).png" alt=""><figcaption><p>Figura #2: Captura de pantalla Vista desempeño provincia</p></figcaption></figure>

#### Rankings

Esta vista presenta un conjunto de rankings que ordenan las provincias según su desempeño en cada indicador de la red de puntos de venta. Cada ranking se representa mediante un gráfico de barras horizontales, donde cada barra corresponde a una provincia.

<table><thead><tr><th width="154.6666259765625">Nombre</th><th width="123.33331298828125">Tipo de gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad de puntos de ventas</code></strong></td><td>Barras horizontales</td><td>Ordena las provincias según el número de puntos de venta que concentran, permitiendo identificar dónde se ubica la mayor densidad de la red y qué territorios tienen menor presencia.</td></tr><tr><td><strong><code>Cantidad de registros</code></strong></td><td>Barras horizontales</td><td>Clasifica las provincias por la cantidad de usuarios registrados a través de sus puntos de venta, útil para reconocer las zonas con mayor captación de jugadores.</td></tr><tr><td><strong><code>Cantidad de usuarios depositando</code></strong></td><td>Barras horizontales</td><td>Muestra las provincias según el número de usuarios únicos que realizaron depósitos, reflejando dónde se concentra la base activa de jugadores que aporta a la operación.</td></tr><tr><td><strong><code>Cantidad de usuarios retirando</code></strong></td><td>Barras horizontales</td><td>Ordena las provincias por la cantidad de usuarios únicos que efectuaron retiros, lo que permite dimensionar la demanda de pagos en cada territorio.</td></tr><tr><td><strong><code>Cantidad de depósitos</code></strong></td><td>Barras horizontales</td><td>Clasifica las provincias según el número de depósitos realizados en sus puntos de venta, indicador del volumen transaccional de cada zona.</td></tr><tr><td><strong><code>Valor depósitos</code></strong></td><td>Barras horizontales</td><td>Ordena las provincias por el monto total depositado, destacando los territorios que generan mayor ingreso para la red.</td></tr><tr><td><strong><code>Cantidad de retiros</code></strong></td><td>Barras horizontales</td><td>Muestra las provincias según el número de retiros pagados en sus puntos de venta, permitiendo seguir el comportamiento de los pagos por territorio.</td></tr><tr><td><strong><code>Valor retiros</code></strong></td><td>Barras horizontales</td><td>Clasifica las provincias por el monto total pagado en retiros, complemento clave para el análisis financiero frente al valor de los depósitos.</td></tr></tbody></table>
{% endtab %}

{% tab title="Desempeño por PV" %}
Muestra rankings comparativos de los puntos de venta, permitiendo evaluar y analizar el rendimiento individual de cada uno frente al resto de la red.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (211) (1).png" alt=""><figcaption><p>Figura #3: Captura de pantalla Vista Desempeño por PV</p></figcaption></figure>

#### Graficas

Los rankings presentan, mediante gráficos de barras horizontales, el Top 10 de los puntos de venta ordenados de mayor a menor, lo que facilita identificar los puntos de venta más productivos de la red. La vista incluye además un gráfico de torta que distribuye los puntos de venta según su categoría.

<table><thead><tr><th width="191.33331298828125">Nombre</th><th width="124.66668701171875">Tipo de gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad de puntos de venta por categoria</code></strong></td><td>Gráfico de torta</td><td>Distribuye los puntos de venta según su categoría <em>(Bronce, Plata o Oro)</em>, representando la proporción que cada una ocupa dentro del total. Permite dimensionar la composición de la red según la clasificación de sus puntos de venta.</td></tr><tr><td><strong><code>Top 10 por cantidad de registros</code></strong></td><td>Barras horizontales</td><td>Ordena los diez puntos de venta con mayor cantidad de usuarios registrados a través de ellos, permitiendo reconocer los puntos con mayor capacidad de captación.</td></tr><tr><td><strong><code>Top 10 por cantidad de usuarios depositando</code></strong></td><td>Barras horizontales</td><td>Presenta los diez puntos de venta con más usuarios únicos que realizaron depósitos, reflejando dónde se concentra la base activa de jugadores que aporta a la operación.</td></tr><tr><td><strong><code>Top 10 por cantidad de usuarios retirando</code></strong></td><td>Barras horizontales</td><td>Clasifica los diez puntos de venta con mayor cantidad de usuarios únicos que efectuaron retiros, útil para dimensionar la demanda de pagos en cada punto.</td></tr><tr><td><strong><code>Top 10 por cantidad de depósitos</code></strong></td><td>Barras horizontales</td><td>Ordena los diez puntos de venta con mayor número de depósitos realizados, indicador del volumen transaccional de cada uno.</td></tr><tr><td><strong><code>Top 10 por valor depósitos</code></strong></td><td>Barras horizontales</td><td>Clasifica los diez puntos de venta con mayor monto total depositado, destacando los que generan mayor ingreso para la red.</td></tr><tr><td><strong><code>Top 10 por cantidad de retiros</code></strong></td><td>Barras horizontales</td><td>Presenta los diez puntos de venta con mayor número de retiros pagados, permitiendo seguir el comportamiento de los pagos en cada punto.</td></tr><tr><td><strong><code>Top 10 por valor retiros</code></strong></td><td>Barras horizontales</td><td>Ordena los diez puntos de venta con mayor monto total pagado en retiros, complemento clave para el análisis financiero frente al valor de los depósitos.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle" %}
Presenta la matriz detallada con la información completa por punto de venta, sirviendo como base para el análisis a nivel transaccional y para la exportación de datos.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (205) (1).png" alt=""><figcaption><p>Figura #4: Captura de pantalla Vista detalle</p></figcaption></figure>

#### Tabla de información

Esta tabla presenta la información completa de cada punto de venta según los filtros aplicados. Cada fila corresponde a un punto de venta dentro del periodo consultado y constituye la base para el análisis a nivel transaccional y para la exportación de la información a Excel.

<table><thead><tr><th width="180.5">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Periodo</code></strong></td><td>Periodo de tiempo desde el cual se registro la información en el sistema.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner al que pertenece el punto de venta.</td></tr><tr><td><strong><code>Pais</code></strong></td><td>País en el que opera el punto de venta.</td></tr><tr><td><strong><code>Id PV</code></strong></td><td>Identificador único del punto de venta.</td></tr><tr><td><strong><code>Nombre PV</code></strong></td><td>Nombre del punto de venta.</td></tr><tr><td><strong><code>Fecha registro PV</code></strong></td><td>Fecha de registro del punto de venta en el sistema.</td></tr><tr><td><strong><code>Estado PV</code></strong></td><td>Estado actual del punto de venta <em>(activo o inactivo)</em>.</td></tr><tr><td><strong><code>Ciudad PV</code></strong></td><td>Ciudad en la que se ubica el punto de venta.</td></tr><tr><td><strong><code>Provincia PV</code></strong></td><td>Provincia en la que se ubica el punto de venta.</td></tr><tr><td><strong><code>Id Concesionario</code></strong></td><td>Identificador único del concesionario asociado al punto de venta.</td></tr><tr><td><strong><code>Detalle</code></strong></td><td>Permite acceder al detalle ampliado del punto de venta.</td></tr><tr><td><strong><code>Id Subconcesionario</code></strong></td><td>Identificador único del subconcesionario asociado al punto de venta.</td></tr><tr><td><strong><code>Id Subconcesionario2</code></strong></td><td>Identificador único del segundo nivel de subconcesionario asociado al punto de venta.</td></tr><tr><td><strong><code>Premium</code></strong></td><td>Indica si el punto de venta corresponde a la categoría premium.</td></tr><tr><td><strong><code>Registrados</code></strong></td><td>Cantidad de usuarios registrados a través del punto de venta.</td></tr><tr><td><strong><code>Cantidad depositos</code></strong></td><td>Número total de depósitos realizados en el punto de venta.</td></tr><tr><td><strong><code>Valor depositos</code></strong></td><td>Valor total de los depósitos realizados en el punto de venta.</td></tr><tr><td><strong><code>Usuarios depositando</code></strong></td><td>Cantidad de usuarios únicos que realizaron al menos un depósito en el punto de venta.</td></tr><tr><td><strong><code>Cantidad retiros</code></strong></td><td>Número total de retiros pagados en el punto de venta.</td></tr><tr><td><strong><code>Valor retiros</code></strong></td><td>Valor total de los retiros pagados en el punto de venta.</td></tr><tr><td><strong><code>Usuarios retirando</code></strong></td><td>Cantidad de usuarios únicos que realizaron al menos un retiro en el punto de venta.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="94.7037353515625">Versión</th><th width="133.25927734375">Fecha</th><th width="161.77777099609375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/06/2026</td><td>David velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
