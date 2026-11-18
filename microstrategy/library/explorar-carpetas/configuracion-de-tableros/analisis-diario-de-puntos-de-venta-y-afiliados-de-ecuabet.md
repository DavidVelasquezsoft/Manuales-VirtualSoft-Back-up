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

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Aplicar filtros</strong></td><td>Permite filtrar la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</td></tr><tr><td><strong>Visualizar contenido del tablero</strong></td><td>Visualiza el contenido del tablero, organizado en métricas principales y pestañas de análisis.</td></tr><tr><td><strong>Exportar contenido</strong></td><td>Permite exportar el contenido del tablero. Para más información, consulte la guía de <a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-3.2.-dashboard-completo">exportación</a>.</td></tr></tbody></table>

***

### 4. Filtros

(poner descripción)

<table><thead><tr><th width="150">Filtro</th><th width="123">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td></td></tr><tr><td><strong><code>Día</code></strong></td><td>Lista desplegable</td><td></td></tr><tr><td><strong><code>Provincia</code></strong></td><td>Lista desplegable</td><td></td></tr><tr><td><strong><code>Punto de venta</code></strong></td><td>Lista desplegable</td><td></td></tr><tr><td><strong><code>ID punto de venta</code></strong></td><td>Lista desplegable</td><td></td></tr><tr><td>Concesionario</td><td>Lista desplegable</td><td>Nombre del concesionario</td></tr></tbody></table>

***

### 5. KPIs

El dashboard presenta unos indicadores generales (completar descripción)&#x20;

<table><thead><tr><th width="205">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td>Valor total de recarga</td><td></td></tr><tr><td>Valor total de retiros</td><td></td></tr><tr><td>Balance</td><td></td></tr><tr><td>Relación TRX (%)</td><td></td></tr><tr><td>Cantidad puntos de venta</td><td></td></tr><tr><td>Cantidad afiliados</td><td></td></tr><tr><td>Comisiones depósitos</td><td></td></tr><tr><td>Comisiones retiros</td><td></td></tr></tbody></table>

KIP de pestaña General PDV y estadísticas (este KPI solo aparece en esas 2 pestañas, en la otra, no)

<table><thead><tr><th width="165.33331298828125">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Recargas/retiros</code></strong></td><td>Comparación de total de recargas frente a los retiros realizados</td></tr></tbody></table>



***

### 6. Contenido del dashboard

(poner descripción con el contexto y relacionada a la estructura del manual (las pestañas que complementan este manual, las principales, están en la barra superior, analiza cada una de las imágenes que están en el manual para que tengas un mejor contexto, al lado de esas pestañas está la fecha de actualización del reporte)



{% tabs %}
{% tab title="General PDV" %}
(mejorar esta descripción) Visualiza información general del punto de venta filtrado con la ayuda de 3 pestañas (evolución, Detalle PDV, Tablas de detalle)

Visualización

<figure><img src="../../../.gitbook/assets/image (276).png" alt=""><figcaption><p>Figura #1: Captura de pantalla vista General PDV.</p></figcaption></figure>

cada pestaña segmenta la información del punto de venta (mejorar descripción y ponerle un título)

{% tabs %}
{% tab title="Evolución" %}
(poner descripción relacionada al contexto de esta pestaña)

esta pestaña se compone con gráficos lineales

<table><thead><tr><th width="181">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Evolución diaria del balance</code></strong></td><td></td></tr><tr><td>Evolución diaria de recargas</td><td></td></tr><tr><td>Evolución diaria de retiros</td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="Tablas de detalle" %}
(poner descripción relacionada al contexto de esta pestaña)

Esta pestaña se compone con la información de gráficos verticales&#x20;

#### Gráficos

<table><thead><tr><th width="170">Gráfico</th><th width="465">Descripción</th></tr></thead><tbody><tr><td><strong><code>Distribución PDV con balance positivo y negativo</code></strong></td><td></td></tr><tr><td>Top 10 PDV por balance</td><td></td></tr><tr><td>Balance por provincia</td><td></td></tr><tr><td>Top 10 PDV por recargas</td><td></td></tr><tr><td>Top 10 PDV por retiros</td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="Tablas de detalle" %}
(poner descripción relacionada al contexto de esta pestaña y cada tabla también)

(todas las columnas todas estas tablas deben estar con este **`formato`**, esto es una orden para claude)

* **Resumen por provincia**

<table><thead><tr><th width="152.33331298828125">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Provincia</code></strong></td><td></td></tr><tr><td>PDV</td><td></td></tr><tr><td>Recargas</td><td></td></tr><tr><td>% participación recargas </td><td></td></tr><tr><td>Retiros</td><td></td></tr><tr><td>% participación retiros</td><td></td></tr><tr><td>Balance</td><td></td></tr><tr><td>% participación balance</td><td></td></tr><tr><td>Relación TRX</td><td></td></tr><tr><td>% participación relación TRX</td><td></td></tr></tbody></table>

* **Resumen diario**

<table><thead><tr><th width="151.66668701171875">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td>Día</td><td></td></tr><tr><td>Balance</td><td></td></tr><tr><td>Variación respecto al día anterior</td><td></td></tr></tbody></table>

* Resumen por concesionario

<table><thead><tr><th width="145">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td>Id concesionario </td><td></td></tr><tr><td>concesionario</td><td></td></tr><tr><td>Recargas</td><td></td></tr><tr><td>Retiro</td><td></td></tr><tr><td>Balance</td><td></td></tr><tr><td>Comisiones concesionarios</td><td></td></tr><tr><td>Relación TRX</td><td></td></tr></tbody></table>

* Detalle por punto de venta&#x20;

<table><thead><tr><th width="145.66668701171875">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td>Id punto de venta</td><td></td></tr><tr><td>Monto recargas</td><td></td></tr><tr><td>Monto retiros</td><td></td></tr><tr><td>Valor retiros creados</td><td></td></tr><tr><td>Balance</td><td></td></tr><tr><td>Comisiones PDV</td><td></td></tr><tr><td>Relación TRX</td><td></td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Estadísticas" %}
(poner descripción con el contexto de esta pestaña, se compone de 2 sub pestañas llamada visualizaciones y tablas de detalle)

Visualización

<figure><img src="../../../.gitbook/assets/image (277).png" alt=""><figcaption><p>Figura #2: Captura de pantalla vista estadísticas.</p></figcaption></figure>

pestañas

(mejorar título y poner descripción con el contexto)

{% tabs %}
{% tab title="Visualizaciones" %}
Presenta la información de manera visual con la ayuda de gráficos de barras verticales

<table><thead><tr><th width="178">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td>Ranking de provincias por balance</td><td></td></tr><tr><td>Top 10 puntos de venta por balance</td><td></td></tr><tr><td>Distribución de balance por provincia</td><td></td></tr><tr><td>Comparativo de recargas vs retiros por provincia</td><td></td></tr><tr><td>Participación de balance por provincia</td><td></td></tr><tr><td>Concentración de PDV por provincia</td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="Tablas de detalle " %}
(mejorar descripción)

esta se complementa de una tabla con la información detallada

<table><thead><tr><th width="128">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Provincia</code></strong></td><td></td></tr><tr><td>PDV</td><td></td></tr><tr><td>Recargas</td><td></td></tr><tr><td>% participación recargas</td><td></td></tr><tr><td>Retiros</td><td></td></tr><tr><td>%participación retiros</td><td></td></tr><tr><td>Balance</td><td></td></tr><tr><td>% participación balance</td><td></td></tr><tr><td>Relación TRX</td><td></td></tr><tr><td>% participación relación TRX</td><td></td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Afiliados" %}
(poner descripción con el contexto)

Visualización

<figure><img src="../../../.gitbook/assets/image (278).png" alt=""><figcaption><p>Figura #3: Captura de pantalla vista Afiliados.</p></figcaption></figure>

Esta pestaña en específico tiene un KPI diferente a los demás

<table><thead><tr><th width="256">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total afiliados │Cantidad de puntos de venta con afiliaciones │ promedio de afiliados por punto de venta</code></strong></td><td></td></tr></tbody></table>

Esta pestaña se complementa de 2 tipos de visualizaciones

{% tabs %}
{% tab title="First Tab" %}
(mejorar descripción)

la información se visualiza por medio de gráficos de barras verticales

Gráficos

<table><thead><tr><th width="180">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td>Top PDV con mayor cantidad de afiliados</td><td></td></tr><tr><td>Afiliados por concesionario</td><td></td></tr><tr><td>Participación de afiliados por concesionario</td><td></td></tr><tr><td>Distribución de afiliados por PDV</td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="Tablas de detalle" %}
(mejorar descricpión con el contexto)&#x20;

Esta vista se complementa con una tabla

<table><thead><tr><th width="198">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td>Concesionario</td><td></td></tr><tr><td>ID punto de venta</td><td></td></tr><tr><td>Centidad de registros</td><td></td></tr><tr><td>% participación</td><td></td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}

***

### 7. Validaciones y reglas del negocio



***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="94.7037353515625">Versión</th><th width="133.25927734375">Fecha</th><th width="161.77777099609375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>05/10/2026</td><td>Ronald Peláez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33129">Documento inicial.</a></td></tr></tbody></table>

</details>
