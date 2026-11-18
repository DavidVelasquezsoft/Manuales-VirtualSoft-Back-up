# Page 1



1. Acceso al Módulo

Ruta de acceso: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Análisis Diario de Puntos de Venta y Afiliados de Ecuabet

2. Configuraciones previas

Antes de ingresar a este tablero, es necesario completar los filtros que se visualizarán durante las configuraciones previas.

3. Acciones disponibles

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Aplicar filtros</strong></td><td>Permite filtrar la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</td></tr><tr><td><strong>Visualizar contenido del tablero</strong></td><td>Visualiza el contenido del tablero, organizado en métricas principales y pestañas de análisis.</td></tr><tr><td><strong>Exportar contenido</strong></td><td>Permite exportar el contenido del tablero. Para más información, consulte la guía de <a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-3.2.-dashboard-completo">exportación</a>.</td></tr></tbody></table>

4\. Filtros

Los filtros se encuentran en el Panel de filtros, ubicado en el costado izquierdo del tablero.

<table><thead><tr><th width="150">Filtro</th><th width="123">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Rango de fechas de la información, definido con los campos <strong>Desde</strong> y <strong>Hasta</strong>.</td></tr><tr><td><strong><code>Día</code></strong></td><td>Lista desplegable</td><td>Día específico a consultar.</td></tr><tr><td><strong><code>Provincia</code></strong></td><td>Lista desplegable</td><td>Provincia de los puntos de venta.</td></tr><tr><td><strong><code>Punto de venta</code></strong></td><td>Cuadro de búsqueda</td><td>Nombre del punto de venta.</td></tr><tr><td><strong><code>Id Punto Venta</code></strong></td><td>Cuadro de búsqueda</td><td>Identificador del punto de venta.</td></tr><tr><td><strong><code>Concesionario</code></strong></td><td>Lista desplegable</td><td>Nombre del concesionario.</td></tr></tbody></table>

5\. KPIs

Indicadores generales ubicados en la parte superior del tablero, visibles en las tres pestañas.

<table><thead><tr><th width="205">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor total de recarga</code></strong></td><td>Valor total de las recargas (depósitos) registradas.</td></tr><tr><td><strong><code>Valor total de retiros</code></strong></td><td>Valor total de los retiros registrados.</td></tr><tr><td><strong><code>Balance</code></strong></td><td>Resultado neto de las recargas y los retiros.</td></tr><tr><td><strong><code>Relación TRX (%)</code></strong></td><td>Proporción de los retiros respecto a las recargas, expresada en porcentaje.</td></tr><tr><td><strong><code>Cantidad puntos de venta</code></strong></td><td>Cantidad de puntos de venta incluidos según los filtros aplicados.</td></tr><tr><td><strong><code>Cantidad de afiliados</code></strong></td><td>Cantidad de afiliados, es decir, usuarios registrados en un punto de venta.</td></tr><tr><td><strong><code>Comisiones depósitos</code></strong></td><td>Comisiones por depósitos que percibe el punto de venta o el concesionario.</td></tr><tr><td><strong><code>Comisiones retiros</code></strong></td><td>Comisiones por retiros que percibe el punto de venta o el concesionario.</td></tr></tbody></table>

Indicador adicional visible solo en las pestañas General PDV y Estadísticas.

<table><thead><tr><th width="165.33331298828125">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Recargas/retiros</code></strong></td><td>Cantidad de recargas y cantidad de retiros realizados, presentadas lado a lado para su comparación.</td></tr></tbody></table>

6\. Contenido del dashboard

El tablero se organiza en tres pestañas principales, ubicadas en la barra superior: General PDV, Estadísticas y Afiliados. A la derecha de las pestañas se muestra la fecha y hora de la última actualización del reporte.

{% tabs %}
{% tab title="General PDV" %}
Vista general de los puntos de venta según los filtros aplicados: KPIs ejecutivos, gráficos operativos, análisis geográfico y ranking de puntos de venta.

Visualización

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2Fyzcb70CevSKT94aqYMTW%2Fimage.png?alt=media&#x26;token=c2e054d4-1bcd-46cd-8e49-245a1721b19b" alt=""><figcaption><p>Figura #1: Captura de pantalla vista General PDV.</p></figcaption></figure>

Subpestañas

El contenido se organiza en tres subpestañas, ubicadas en la parte superior derecha: Evolución, Detalle PDV y Tablas de detalle.

{% tabs %}
{% tab title="Evolución" %}
Comportamiento diario del balance, las recargas y los retiros, presentado en gráficos lineales.

<table><thead><tr><th width="181">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Evolución diaria del balance</code></strong></td><td>Diferencia diaria entre recargas y retiros.</td></tr><tr><td><strong><code>Evolución diaria de recargas</code></strong></td><td>Valor diario de las recargas (depósitos).</td></tr><tr><td><strong><code>Evolución diaria de retiros</code></strong></td><td>Valor diario de los retiros.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle PDV" %}
Ranking y distribución de los puntos de venta por balance, recargas y retiros, y balance por provincia.

Gráficos

<table><thead><tr><th width="170">Gráfico</th><th width="465">Descripción</th></tr></thead><tbody><tr><td><strong><code>Distribución PDV con balance positivo y negativo</code></strong></td><td>Distribución de los puntos de venta según el signo de su balance: positivo o negativo.</td></tr><tr><td><strong><code>Top 10 PDV por balance</code></strong></td><td>Los 10 puntos de venta con mayor balance.</td></tr><tr><td><strong><code>Balance por provincia</code></strong></td><td>Balance de cada provincia.</td></tr><tr><td><strong><code>Top 10 PDV por recargas</code></strong></td><td>Los 10 puntos de venta con mayor valor de recargas.</td></tr><tr><td><strong><code>Top 10 PDV por retiros</code></strong></td><td>Los 10 puntos de venta con mayor valor de retiros.</td></tr></tbody></table>
{% endtab %}

{% tab title="Tablas de detalle" %}
Detalle numérico de los indicadores en cuatro tablas.

Resumen por provincia: consolidado por provincia, con la participación de cada una en los totales.

<table><thead><tr><th width="152.33331298828125">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Provincia</code></strong></td><td>Provincia de los puntos de venta.</td></tr><tr><td><strong><code>PDV</code></strong></td><td>Cantidad de puntos de venta de la provincia.</td></tr><tr><td><strong><code>Recargas</code></strong></td><td>Valor total de las recargas de la provincia.</td></tr><tr><td><strong><code>% participación recargas</code></strong></td><td>Porcentaje que representa la provincia en el total de recargas.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Valor total de los retiros de la provincia.</td></tr><tr><td><strong><code>% participación retiros</code></strong></td><td>Porcentaje que representa la provincia en el total de retiros.</td></tr><tr><td><strong><code>Balance</code></strong></td><td>Diferencia entre recargas y retiros de la provincia.</td></tr><tr><td><strong><code>% participación balance</code></strong></td><td>Porcentaje que representa la provincia en el balance total.</td></tr><tr><td><strong><code>Relación TRX</code></strong></td><td>Porcentaje de retiros respecto a recargas de la provincia.</td></tr><tr><td><strong><code>% participación relación TRX</code></strong></td><td>Porcentaje de participación de la provincia en la Relación TRX.</td></tr></tbody></table>

Resumen diario: seguimiento del balance día a día.

<table><thead><tr><th width="151.66668701171875">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Día</code></strong></td><td>Día al que corresponden los valores.</td></tr><tr><td><strong><code>Balance</code></strong></td><td>Balance del día.</td></tr><tr><td><strong><code>Variación respecto al día anterior</code></strong></td><td>Diferencia del balance frente al del día anterior.</td></tr><tr><td><strong><code>% Variación respecto al día anterior</code></strong></td><td>Variación porcentual del balance frente al del día anterior.</td></tr></tbody></table>

Resumen por concesionario: consolidado por concesionario, incluidas sus comisiones.

<table><thead><tr><th width="145">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id concesionario</code></strong></td><td>Identificador del concesionario.</td></tr><tr><td><strong><code>Concesionario</code></strong></td><td>Nombre del concesionario.</td></tr><tr><td><strong><code>Recargas</code></strong></td><td>Valor total de las recargas del concesionario.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Valor total de los retiros del concesionario.</td></tr><tr><td><strong><code>Balance</code></strong></td><td>Diferencia entre recargas y retiros del concesionario.</td></tr><tr><td><strong><code>Comisiones concesionarios</code></strong></td><td>Comisiones que percibe el concesionario.</td></tr><tr><td><strong><code>Relación TRX</code></strong></td><td>Porcentaje de retiros respecto a recargas del concesionario.</td></tr></tbody></table>

Detalle por punto de venta: consolidado por punto de venta, identificado por su ID.

<table><thead><tr><th width="145.66668701171875">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id punto de venta</code></strong></td><td>Identificador del punto de venta.</td></tr><tr><td><strong><code>Monto recargas</code></strong></td><td>Valor total de las recargas del punto de venta.</td></tr><tr><td><strong><code>Monto retiros</code></strong></td><td>Valor total de los retiros del punto de venta.</td></tr><tr><td><strong><code>Valor retiros creados</code></strong></td><td>Valor de los retiros creados en el punto de venta.</td></tr><tr><td><strong><code>Balance</code></strong></td><td>Diferencia entre recargas y retiros del punto de venta.</td></tr><tr><td><strong><code>Comisiones PDV</code></strong></td><td>Comisiones que percibe el punto de venta.</td></tr><tr><td><strong><code>Relación TRX</code></strong></td><td>Porcentaje de retiros respecto a recargas del punto de venta.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Estadísticas" %}
Comportamiento agregado de los puntos de venta por provincia.

Visualización

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2Fz2D1W2KAGReLJ9LcinJp%2Fimage.png?alt=media&#x26;token=f9ca7da7-57ea-4252-ac81-010acbce2f4c" alt=""><figcaption><p>Figura #2: Captura de pantalla vista estadísticas.</p></figcaption></figure>

Subpestañas

El contenido se organiza en dos subpestañas, ubicadas en la parte superior derecha: Visualizaciones y Tablas de detalle.

{% tabs %}
{% tab title="Visualizaciones" %}
Gráficos del balance, las recargas y los retiros por provincia, la concentración de puntos de venta y el ranking de puntos de venta por balance.

<table><thead><tr><th width="178">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ranking de provincias por balance</code></strong></td><td>Provincias ordenadas de mayor a menor balance.</td></tr><tr><td><strong><code>Top 10 puntos de venta por balance</code></strong></td><td>Los 10 puntos de venta con mayor balance, identificados por su ID.</td></tr><tr><td><strong><code>Distribución de balance por provincia</code></strong></td><td>Balance positivo y balance negativo de cada provincia.</td></tr><tr><td><strong><code>Comparativo de recargas vs retiros por provincia</code></strong></td><td>Valor de las recargas (depósitos) y de los retiros de cada provincia, para su comparación.</td></tr><tr><td><strong><code>Participación de balance por provincia</code></strong></td><td>Porcentaje que representa el balance de cada provincia en el balance total.</td></tr><tr><td><strong><code>Concentración de PDV por provincia</code></strong></td><td>Distribución de los puntos de venta por provincia.</td></tr></tbody></table>
{% endtab %}

{% tab title="Tablas de detalle" %}
Tabla con el detalle por provincia. Mantiene las mismas columnas del Resumen por provincia de la pestaña General PDV.

<table><thead><tr><th width="128">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Provincia</code></strong></td><td>Provincia de los puntos de venta.</td></tr><tr><td><strong><code>PDV</code></strong></td><td>Cantidad de puntos de venta de la provincia.</td></tr><tr><td><strong><code>Recargas</code></strong></td><td>Valor total de las recargas de la provincia.</td></tr><tr><td><strong><code>% participación recargas</code></strong></td><td>Porcentaje que representa la provincia en el total de recargas.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Valor total de los retiros de la provincia.</td></tr><tr><td><strong><code>% participación retiros</code></strong></td><td>Porcentaje que representa la provincia en el total de retiros.</td></tr><tr><td><strong><code>Balance</code></strong></td><td>Diferencia entre recargas y retiros de la provincia.</td></tr><tr><td><strong><code>% participación balance</code></strong></td><td>Porcentaje que representa la provincia en el balance total.</td></tr><tr><td><strong><code>Relación TRX</code></strong></td><td>Porcentaje de retiros respecto a recargas de la provincia.</td></tr><tr><td><strong><code>% participación relación TRX</code></strong></td><td>Porcentaje de participación de la provincia en la Relación TRX.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Afiliados" %}
Cantidad de afiliados generados por concesionario y por punto de venta.

Visualización

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FqXhTSCBazaatVtOyzy2m%2Fimage.png?alt=media&#x26;token=b0f256b7-d763-4125-af70-484685be756d" alt=""><figcaption><p>Figura #3: Captura de pantalla vista Afiliados.</p></figcaption></figure>

En esta pestaña, el indicador Recargas/retiros se reemplaza por los siguientes KPIs:

<table><thead><tr><th width="256">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total afiliados</code></strong></td><td>Total de afiliados registrados según los filtros aplicados.</td></tr><tr><td><strong><code>Cantidad de puntos de venta con afiliaciones</code></strong></td><td>Cantidad de puntos de venta que tienen afiliados registrados.</td></tr><tr><td><strong><code>Promedio de afiliados por punto de venta</code></strong></td><td>Total de afiliados dividido entre la cantidad de puntos de venta con afiliaciones.</td></tr></tbody></table>

Subpestañas

El contenido se organiza en dos subpestañas, ubicadas en la parte superior derecha: Visualizaciones y Tablas de detalle.

{% tabs %}
{% tab title="Visualizaciones" %}
Gráficos de cantidad, participación y distribución de afiliados por punto de venta y por concesionario.

<table><thead><tr><th width="180">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Top PDV con mayor cantidad de afiliados</code></strong></td><td>Puntos de venta ordenados de mayor a menor cantidad de afiliados, identificados por su ID.</td></tr><tr><td><strong><code>Afiliados por concesionario</code></strong></td><td>Cantidad de afiliados de cada concesionario, ordenados de mayor a menor.</td></tr><tr><td><strong><code>Participación de afiliados por concesionario</code></strong></td><td>Porcentaje que representa cada concesionario en el total de afiliados.</td></tr><tr><td><strong><code>Distribución de afiliados por PDV</code></strong></td><td>Distribución de los afiliados entre los puntos de venta.</td></tr></tbody></table>
{% endtab %}

{% tab title="Tablas de detalle" %}
Tabla con la cantidad de afiliados registrados por concesionario y punto de venta, y su participación.

<table><thead><tr><th width="198">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Concesionario</code></strong></td><td>Nombre del concesionario.</td></tr><tr><td><strong><code>ID punto de venta</code></strong></td><td>Identificador del punto de venta.</td></tr><tr><td><strong><code>Cantidad de registros</code></strong></td><td>Cantidad de afiliados registrados en el punto de venta.</td></tr><tr><td><strong><code>% participación</code></strong></td><td>Porcentaje que representan los registros en el total de afiliados.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}

7\. Validaciones y reglas del negocio

<table><thead><tr><th width="205">Regla</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Cálculo del balance</strong></td><td>Balance = Recargas − Retiros.</td></tr><tr><td><strong>Cálculo de la Relación TRX (%)</strong></td><td>Relación TRX (%) = Retiros ÷ Recargas.</td></tr><tr><td><strong>Cálculo del promedio de afiliados</strong></td><td>Promedio de afiliados por punto de venta = Total afiliados ÷ Cantidad de puntos de venta con afiliaciones.</td></tr><tr><td><strong>Aplicación de filtros</strong></td><td>Los filtros se aplican a todos los indicadores, gráficos y tablas del tablero.</td></tr></tbody></table>

8\. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="94.7037353515625">Versión</th><th width="133.25927734375">Fecha</th><th width="161.77777099609375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>05/10/2026</td><td>Ronald Peláez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33129">Documento inicial.</a></td></tr></tbody></table>

</details>
