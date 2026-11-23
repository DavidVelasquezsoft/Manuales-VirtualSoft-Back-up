---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
---

# Análisis Diario de Puntos de Venta y Afiliados de Ecuabet



### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Análisis Diario de Puntos de Venta y Afiliados de Ecuabet

***

### 2. Configuraciones previas

Antes de ingresar a este tablero, es necesario completar los filtros que se visualizarán durante las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-1.-configuraciones-previas).

***

### 3. Acciones disponibles

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros/analisis-diario-de-puntos-de-venta-y-afiliados-de-ecuabet#id-4.-filtros"><strong>Aplicar filtros</strong></a></td><td>Permite filtrar la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros/analisis-diario-de-puntos-de-venta-y-afiliados-de-ecuabet#id-6.-contenido-del-dashboard"><strong>Visualizar contenido del tablero</strong></a></td><td>Visualiza el contenido del tablero, organizado en métricas principales y pestañas de análisis.</td></tr><tr><td><strong>Exportar contenido</strong></td><td>Permite exportar el contenido del tablero. Para más información, consulte la guía de <a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-3.2.-dashboard-completo">exportación</a>.</td></tr></tbody></table>

***

### 4. Filtros

Los filtros se encuentran en el Panel de filtros, ubicado en el costado izquierdo del tablero.

<table><thead><tr><th width="150">Filtro</th><th width="123">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Rango de fechas de la información, definido con los campos <strong>Desde</strong> y <strong>Hasta</strong>.</td></tr><tr><td><strong><code>Día</code></strong></td><td>Lista desplegable</td><td>Día específico a consultar.</td></tr><tr><td><strong><code>Provincia</code></strong></td><td>Lista desplegable</td><td>Provincia de los puntos de venta.</td></tr><tr><td><strong><code>Punto de venta</code></strong></td><td>Cuadro de búsqueda</td><td>Nombre del punto de venta.</td></tr><tr><td><strong><code>Id Punto Venta</code></strong></td><td>Cuadro de búsqueda</td><td>Identificador único del punto de venta.</td></tr><tr><td><strong><code>Concesionario</code></strong></td><td>Lista desplegable</td><td>Nombre del concesionario.</td></tr></tbody></table>

***

### 5. KPIs

Indicadores generales ubicados en la parte superior del tablero, visibles en las tres pestañas.

<table><thead><tr><th width="205">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor total de recarga</code></strong></td><td>Valor total de las recargas <em>(depósitos)</em> registradas por los puntos de venta.</td></tr><tr><td><strong><code>Valor total de retiros</code></strong></td><td>Valor total de los retiros registrados por los puntos de venta.</td></tr><tr><td><strong><code>Balance</code></strong></td><td>Resultado neto de las recargas y los retiros.</td></tr><tr><td><strong><code>Relación TRX (%)</code></strong></td><td>Proporción de los retiros respecto a las recargas, expresada en porcentaje.</td></tr><tr><td><strong><code>Cantidad puntos de venta</code></strong></td><td>Cantidad de puntos de venta incluidos según los filtros aplicados.</td></tr><tr><td><strong><code>Cantidad de afiliados</code></strong></td><td>Cantidad de afiliados, es decir, usuarios registrados en un punto de venta.</td></tr><tr><td><strong><code>Comisiones depósitos</code></strong></td><td>Comisiones por depósitos que percibe los puntos de venta o el concesionario.</td></tr><tr><td><strong><code>Comisiones retiros</code></strong></td><td>Comisiones por retiros que percibe los puntos de venta o el concesionario.</td></tr></tbody></table>

Indicador adicional visible solo en las pestañas General PDV y Estadísticas.

<table><thead><tr><th width="165.33331298828125">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Recargas/retiros</code></strong></td><td>Cantidad de recargas y cantidad de retiros realizados, presentadas lado a lado para su comparación.</td></tr></tbody></table>

***

### 6. Contenido del dashboard

El tablero se organiza en tres pestañas principales, ubicadas en la barra superior: General PDV, Estadísticas y Afiliados. A la derecha de las pestañas se muestra la fecha y hora de la última actualización del reporte.

{% tabs %}
{% tab title="General PDV" %}
Vista general de los puntos de venta según los filtros aplicados.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (279).png" alt=""><figcaption><p>Figura #1: Captura de pantalla vista General PDV.</p></figcaption></figure>

El contenido se organiza en tres subpestañas, ubicadas en la parte superior derecha: Evolución, Detalle PDV y Tablas de detalle.

{% tabs %}
{% tab title="Evolución" %}
Comportamiento diario del balance, las recargas y los retiros, presentado en gráficos lineales.

#### Gráficos

<table><thead><tr><th width="181">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Evolución diaria del balance</code></strong></td><td>Balance de cada día dentro del rango de fechas seleccionado, calculado como la diferencia entre las recargas y los retiros del día. Muestra los días en el eje horizontal y el valor del balance en el eje vertical, y refleja cómo cambia de un día a otro.</td></tr><tr><td><strong><code>Evolución diaria de recargas</code></strong></td><td>Valor total de las recargas <em>(depósitos)</em> de cada día dentro del rango de fechas seleccionado. Su comportamiento diario puede compararse con el de los retiros.</td></tr><tr><td><strong><code>Evolución diaria de retiros</code></strong></td><td>Valor total de los retiros de cada día dentro del rango de fechas seleccionado. Su comportamiento diario puede compararse con el de las recargas.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle PDV" %}
Ranking y distribución de los puntos de venta por balance, recargas y retiros, y balance por provincia.&#x20;

#### Gráficos

<table><thead><tr><th width="170">Gráfico</th><th width="465">Descripción</th></tr></thead><tbody><tr><td><strong><code>Distribución PDV con balance positivo y negativo</code></strong></td><td>Distribución de los puntos de venta según el signo de su balance <em>(positivo o negativo)</em>.</td></tr><tr><td><strong><code>Top 10 PDV por balance</code></strong></td><td><p>Los 10 puntos de venta con mayor balance.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Los puntos de venta se identifican por su Identificador único y en frente se visualizará el monto total de recargas.</p></div></td></tr><tr><td><strong><code>Balance por provincia</code></strong></td><td>Balance de cada provincia.</td></tr><tr><td><strong><code>Top 10 PDV por recargas</code></strong></td><td>Los 10 puntos de venta con mayor valor de recargas.</td></tr><tr><td><strong><code>Top 10 PDV por retiros</code></strong></td><td>Los 10 puntos de venta con mayor valor de retiros.</td></tr></tbody></table>
{% endtab %}

{% tab title="Tablas de detalle" %}
Detalle numérico de los indicadores en cuatro tablas.

* **Resumen por provincia**

Valores consolidados por provincia y punto de venta, con la participación de cada provincia en los totales.

<table><thead><tr><th width="162.33331298828125">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Provincia</code></strong></td><td>Provincia a la que pertenecen los puntos de venta.</td></tr><tr><td><strong><code>PDV</code></strong></td><td>Nombre del punto de venta.</td></tr><tr><td><strong><code>Recargas</code></strong></td><td>Valor total de las recargas <em>(depósitos)</em> registradas en el punto de venta.</td></tr><tr><td><strong><code>% participación recargas</code></strong></td><td>Porcentaje que representan las recargas de la provincia respecto al total de recargas.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Valor total de los retiros registrados en el punto de venta.</td></tr><tr><td><strong><code>% participación retiros</code></strong></td><td>Porcentaje que representan los retiros de la provincia respecto al total de retiros.</td></tr><tr><td><strong><code>Balance</code></strong></td><td>Diferencia entre las recargas y los retiros del punto de venta. Un valor positivo indica que las recargas superan a los retiros; un valor negativo, que los retiros superan a las recargas.</td></tr><tr><td><strong><code>% participación balance</code></strong></td><td>Porcentaje que representa el balance de la provincia respecto al balance total.</td></tr><tr><td><strong><code>Relación TRX</code></strong></td><td>Porcentaje que representan los retiros respecto a las recargas de la provincia.</td></tr><tr><td><strong><code>% participación relación TRX</code></strong></td><td>Porcentaje de participación de la provincia en la Relación TRX.</td></tr></tbody></table>

* **Resumen diario**

Balance de cada día dentro del rango de fechas seleccionado y su variación frente al día anterior.

<table><thead><tr><th width="151.66668701171875">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Día</code></strong></td><td>Día del rango de fechas seleccionado al que corresponden los valores.</td></tr><tr><td><strong><code>Balance</code></strong></td><td>Diferencia entre las recargas y los retiros del día.</td></tr><tr><td><strong><code>Variación respecto al día anterior</code></strong></td><td>Diferencia entre el balance del día y el del día anterior. Un valor positivo indica que el balance aumentó; un valor negativo, que disminuyó.</td></tr><tr><td><strong><code>% Variación respecto al día anterior</code></strong></td><td>Variación del balance del día frente al del día anterior, expresada en porcentaje.</td></tr></tbody></table>

* **Resumen por concesionario**

Valores consolidados de cada concesionario, incluidas las comisiones que percibe.

<table><thead><tr><th width="145">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id concesionario</code></strong></td><td>Identificador del concesionario.</td></tr><tr><td><strong><code>Concesionario</code></strong></td><td>Nombre del concesionario.</td></tr><tr><td><strong><code>Recargas</code></strong></td><td>Valor total de las recargas <em>(depósitos)</em> del concesionario.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Valor total de los retiros del concesionario.</td></tr><tr><td><strong><code>Balance</code></strong></td><td>Diferencia entre las recargas y los retiros del concesionario.</td></tr><tr><td><strong><code>Comisiones concesionarios</code></strong></td><td>Comisiones que percibe el concesionario por depósitos y retiros.</td></tr><tr><td><strong><code>Relación TRX</code></strong></td><td>Porcentaje que representan los retiros respecto a las recargas del concesionario.</td></tr></tbody></table>

* **Detalle por punto de venta**

Valores consolidados de cada punto de venta, identificado por su ID.

<table><thead><tr><th width="145.66668701171875">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id punto de venta</code></strong></td><td>Identificador del punto de venta.</td></tr><tr><td><strong><code>Monto recargas</code></strong></td><td>Valor total de las recargas (depósitos) del punto de venta.</td></tr><tr><td><strong><code>Monto retiros</code></strong></td><td>Valor total de los retiros del punto de venta.</td></tr><tr><td><strong><code>Valor retiros creados</code></strong></td><td>Valor de los retiros creados en el punto de venta.</td></tr><tr><td><strong><code>Balance</code></strong></td><td>Diferencia entre las recargas y los retiros del punto de venta.</td></tr><tr><td><strong><code>Comisiones PDV</code></strong></td><td>Comisiones que percibe el punto de venta por depósitos y retiros.</td></tr><tr><td><strong><code>Relación TRX</code></strong></td><td>Porcentaje que representan los retiros respecto a las recargas del punto de venta.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Estadísticas" %}
Comportamiento agregado de los puntos de venta por provincia.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (277).png" alt=""><figcaption><p>Figura #2: Captura de pantalla vista estadísticas.</p></figcaption></figure>

El contenido se organiza en dos subpestañas, ubicadas en la parte superior derecha: Visualizaciones y Tablas de detalle.

{% tabs %}
{% tab title="Visualizaciones" %}
Gráficos del balance, las recargas y los retiros por provincia, la concentración de puntos de venta y el ranking de puntos de venta por balance.

<table><thead><tr><th width="178">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ranking de provincias por balance</code></strong></td><td>Provincias ordenadas de mayor a menor balance.</td></tr><tr><td><strong><code>Top 10 puntos de venta por balance</code></strong></td><td>Los 10 puntos de venta con mayor balance, identificados por su ID.</td></tr><tr><td><strong><code>Distribución de balance por provincia</code></strong></td><td>Balance positivo y balance negativo de cada provincia.</td></tr><tr><td><strong><code>Comparativo de recargas vs retiros por provincia</code></strong></td><td>Valor de las recargas (depósitos) y de los retiros de cada provincia, para su comparación.</td></tr><tr><td><strong><code>Participación de balance por provincia</code></strong></td><td>Porcentaje que representa el balance de cada provincia en el balance total.</td></tr><tr><td><strong><code>Concentración de PDV por provincia</code></strong></td><td>Distribución de los puntos de venta por provincia.</td></tr></tbody></table>
{% endtab %}

{% tab title="Tablas de detalle " %}
Tabla con el detalle por provincia. Mantiene las mismas columnas del Resumen por provincia de la pestaña General PDV.

<table><thead><tr><th width="128">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Provincia</code></strong></td><td>Provincia de los puntos de venta.</td></tr><tr><td><strong><code>PDV</code></strong></td><td>Cantidad de puntos de venta de la provincia.</td></tr><tr><td><strong><code>Recargas</code></strong></td><td>Valor total de las recargas de la provincia.</td></tr><tr><td><strong><code>% participación recargas</code></strong></td><td>Porcentaje que representa la provincia en el total de recargas.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Valor total de los retiros de la provincia.</td></tr><tr><td><strong><code>% participación retiros</code></strong></td><td>Porcentaje que representa la provincia en el total de retiros.</td></tr><tr><td><strong><code>Balance</code></strong></td><td>Diferencia entre recargas y retiros de la provincia.</td></tr><tr><td><strong><code>% participación balance</code></strong></td><td>Porcentaje que representa la provincia en el balance total.</td></tr><tr><td><strong><code>Relación TRX</code></strong></td><td>Porcentaje de retiros respecto a recargas de la provincia.</td></tr><tr><td><strong><code>% participación relación TRX</code></strong></td><td>Porcentaje de participación de la provincia en la Relación TRX.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Afiliados" %}
Cantidad de afiliados generados por concesionario y por punto de venta.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (278).png" alt=""><figcaption><p>Figura #3: Captura de pantalla vista Afiliados.</p></figcaption></figure>

En esta pestaña, el indicador **`Recargas/retiros`** se reemplaza este KPI:

<table><thead><tr><th width="256">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total afiliados │Cantidad de puntos de venta con afiliaciones │ promedio de afiliados por punto de venta</code></strong></td><td>Total de afiliados, cantidad de puntos de venta con afiliaciones y promedio de afiliados por punto de venta, presentados lado a lado.</td></tr></tbody></table>

El contenido se organiza en dos subpestañas, ubicadas en la parte superior derecha _(Visualizaciones y Tablas de detalle)._

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

***

### 7. Validaciones y reglas del negocio

* El balance corresponde a la diferencia entre recargas y retiros.
* Todos los filtros afectan de manera consistente a la totalidad de indicadores, gráficos y tablas del tablero.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="94.7037353515625">Versión</th><th width="133.25927734375">Fecha</th><th width="161.77777099609375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>05/10/2026</td><td>Ronald Peláez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33129">Documento inicial.</a></td></tr></tbody></table>

</details>
