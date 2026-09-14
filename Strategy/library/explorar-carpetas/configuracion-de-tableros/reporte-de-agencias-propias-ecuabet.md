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
---

# Reporte de agencias propias Ecuabet

Este reporte permite visualziar el comportamiento general de los depósitos y retiros mediante indicadores, tendencias históricas y ranking de puntos de venta.

***

### 1. Acceso al Módulo

**Ruta de Acceso:** Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Dashboard de Ruletas

***

### 2.Configuraciones Previas

Antes de visualizar el reporte, establece las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-1.-configuraciones-previas) requeridas para la consulta.

***

### 3. Filtros

El reporte se divide en tres pestañas que responden a los mismos filtros ubicados en el panel izquierdo

<table><thead><tr><th width="171">Filtro</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Año</code></strong></td><td>Selector / lista desplegable</td><td>Año correspondiente a la búsqueda ejecutada.</td></tr><tr><td><strong><code>Mes</code></strong></td><td>Selector / lista desplegable</td><td>Mes correspondiente a la búsqueda ejecutada.</td></tr><tr><td><strong><code>Nombre PV</code></strong></td><td>Selector / Buscador</td><td>Nombre del punto de venta al cual se desea consultar.</td></tr><tr><td><strong><code>Id usuario</code></strong></td><td>Selector / Buscador</td><td>Identificador único del usuario al cual se desea consultar.</td></tr></tbody></table>

***

### 4. Contenido del Dashboard

Este dashboard consta de tres pestañas: [**General**](https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros/reporte-de-agencias-propias-ecuabet#general), [**Comparación**](https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros/reporte-de-agencias-propias-ecuabet#comparacion) y [**Detalle histórico**](https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros/reporte-de-agencias-propias-ecuabet#detalle-historico). Las pestañas **General** y **Comparación** contienen los mismos KPI. La pestaña **Detalle histórico** no incluye KPI.

#### 4.1 kips&#x20;

<table><thead><tr><th width="176">Nombre</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Depósitos</code></strong></td><td>Monto total de los depósitos realizados en el ralgo de fechas consultado.</td></tr><tr><td><strong><code>Cantidad depósitos</code></strong></td><td>Cantidad total de depósitos realizados en el rango de fechas consultado.</td></tr><tr><td><strong><code>Valor promedio depósitos</code></strong></td><td>Valor promedio de depósitos correspondientes al valor total de depósitos realizados.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Monto total de los retiros realizados en el rango de fechas consultado.</td></tr><tr><td><strong><code>Cantidad retiros</code></strong></td><td>Cantidad total de retiros realizados en el rango de fechas consultado.</td></tr><tr><td><strong><code>Valor promedio retiros</code></strong></td><td>Valor promedio de retiros correspondientes al valor total de retiros realizados.</td></tr></tbody></table>

#### 4.2. Pestañas

Estas son las pestañas disponibles para visualizar la información del dashboard.

{% tabs %}
{% tab title="General" %}
La pestaña **General** presenta un resumen de los depósitos y retiros realizados por los puntos de venta. La información se puede consultar en dos modos, seleccionables desde la esquina superior derecha: **Gráficas** y **Detalle**.

{% tabs %}
{% tab title="Gráficas" %}
Visualiza la información correspondiente a los depósitos, retiros y puntos de venta con ayuda de gráficos.

***

#### Visualización

<figure><img src="../../../.gitbook/assets/image (246).png" alt=""><figcaption></figcaption></figure>

***

#### Gráficos

<table><thead><tr><th width="129">Nombre</th><th width="137">Tipo de gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Depósitos y retiros a travésdel tiempo</code></strong></td><td>Lineal</td><td>Comparación lineal de los depósitos y retiros realizados correspondiente al tiempo configurado en los filtros.</td></tr><tr><td><strong><code>Top 10 puntos de ventas</code></strong></td><td>Barras</td><td>Top 10 puntos de ventas en los que más se han realizado depósitos y retiros, comparando la cantidad de depósitos realizados con la cantidad de retiros.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle" %}
La vista Detalle se complementa de una tabla con la información de los depósitos y los retiros.

***

#### Visualización

<figure><img src="../../../.gitbook/assets/vsft ecuabet.jpg" alt=""><figcaption></figcaption></figure>

**Tabla Depósitos y retiro por punto de venta.**

<table><thead><tr><th width="163">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador único del punto de venta.</td></tr><tr><td><strong><code>Nombre punto venta</code></strong></td><td>Nombre correspondiente al punto de venta.</td></tr><tr><td><strong><code>Depósito</code></strong></td><td>Monto total de depósitos realizados en el punto de venta.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Monto total de retiros realizados en el punto de venta.</td></tr><tr><td><strong><code>Coincidencia TRX</code></strong></td><td>porcentaje de proporción del valor de los retiros realizados contra los depósitos.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Comparación" %}
Esta pestaña presenta la información en 2 gráficos lineales, comparando los depósitos realizados con los retiros.

{% hint style="warning" %}
**Nota**: Aunque esta pestaña también contenga 3 vistas diferentes, todas las vistas contienen la misma infornación, lo único que cambia es el tiempo de comparación _(Diario, Mensual y anual)_.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (248).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="171">Gráfico</th><th width="154">Tipo de gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>% variación diaria de depósitos</code></strong></td><td>Lineal</td><td>Comparativa diaria de los depósitos realizados según las fechas establecidas en los filtros.</td></tr><tr><td><strong><code>% variación diaria de retiros</code></strong></td><td>Lineal</td><td>Comparativa diaria de los retiros realizados según las fechas establecidas en los filtros.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle histórico" %}
Presenta 2 tablas detalladas en las que compara los depósitos y los retiros según la vista seleccionada.

{% tabs %}
{% tab title="Gráficas" %}
La tabla de depósitos compara los depósitos realizados del mes anterior y el año anterior.

***

#### Visualización

<figure><img src="../../../.gitbook/assets/image (250).png" alt=""><figcaption></figcaption></figure>

#### Tabla Comparación del valor de depósito vs mes anterior y vs año pasado.

<table><thead><tr><th width="163">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Año</code></strong></td><td>Año en el que se está realizando la comparativa.</td></tr><tr><td><strong><code>Mes</code></strong></td><td>Mes en el que se está realizando la comparativa.</td></tr><tr><td><strong><code>Depósitos</code></strong></td><td>Monto total de depósitos realizados en ese mes.</td></tr><tr><td><strong><code>Depósitos mes anterior</code></strong></td><td>Monto total de depósitos realizados el mes anterior al mes comparado.</td></tr><tr><td><strong><code>% variación respecto al mes anterior</code></strong></td><td>Porcentaje de variación entre el mes inicial y el mes anterior.</td></tr><tr><td><strong><code>Depósitos mismo mes año anterior</code></strong></td><td>Monto total de depósitos realizados ese mismo mes, pero del año aneterior.</td></tr><tr><td><strong><code>% variación respecto al mismo mes año anterior</code></strong></td><td>Porcentaje de variación entre el mes inicial de el año comparado, con el año anterior.</td></tr></tbody></table>

.
{% endtab %}

{% tab title="Retiros" %}
La tabla de depósitos compara los depósitos realizados del mes anterior y el año anterior.

***

#### Visualización

<figure><img src="../../../.gitbook/assets/image (250).png" alt=""><figcaption></figcaption></figure>

#### Tabla Comparación del valor de retiros vs mes anterior y vs año pasado

<table><thead><tr><th width="163">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Año</code></strong></td><td>Año en el que se está realizando la comparativa.</td></tr><tr><td><strong><code>Mes</code></strong></td><td>Mes en el que se está realizando la comparativa.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Monto total de retiros realizados en ese mes.</td></tr><tr><td><strong><code>Retiros mes anterior</code></strong></td><td>Monto total de retiros realizados el mes anterior al mes comparado.</td></tr><tr><td><strong><code>% variación respecto al mes anterior</code></strong></td><td>Porcentaje de variación entre el mes inicial y el mes anterior.</td></tr><tr><td><strong><code>Retiros mismo mes año anterior</code></strong></td><td>Monto total de retiros realizados ese mismo mes, pero del año aneterior.</td></tr><tr><td><strong><code>% variación respecto al mismo mes año anterior</code></strong></td><td>Porcentaje de variación entre el mes inicial de el año comparado, con el año anterior.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}

***

### 5 Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="106.77777099609375">Versión</th><th width="112.444580078125">Fecha</th><th width="160.44439697265625">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>14/08/2029</td><td>Ronald Peláez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33122">Documento inicial</a></td></tr></tbody></table>

</details>

