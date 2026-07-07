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

# Seguimientos caídas jackpot

Este tablero permite visualizar y analizar de forma integral todas las caídas del jackpot, es decir, los eventos en los que el monto acumulado alcanza el valor máximo configurado y se realiza el pago del premio.

{% hint style="warning" %}
**Nota**: El dashboard es exclusivamente de monitoreo y no permite edición de información.
{% endhint %}

***

**Ruta de Acceso:** Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Seguimientos caídas jackpot

{% hint style="warning" %}
**Nota:** La ruta de acceso aplica para usuarios administrativos. Los usuarios con permisos podrán acceder al dashboard desde su **Library personal**, según el equipo y los accesos asignados. Para más información, consulte la [guía disponible](../../../).
{% endhint %}

***

### **2. Configuraciones Previas**

Antes de visualizar el reporte, es necesario definir las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/tableros#id-2.-configuracion-previa) obligatorias.

***

### 3. 🖼️Visualización&#x20;

<figure><img src="../../../.gitbook/assets/image (8).png" alt=""><figcaption><p>Figura #1: captura de pantalla dashboard seguimiento caídas jackpot.</p></figcaption></figure>

***

### 4. Acciones del Usuario

<table><thead><tr><th width="256">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/seguimientos-caidas-jackpot#id-4.1.-filtros-disponibles"><strong>Aplicar filtros</strong></a></td><td>Permite segmentar la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/seguimientos-caidas-jackpot#id-5.-contenido-del-dashboard"><strong>Analizas jackpots caídos</strong></a></td><td>Utiliza las herramientas del dashboard, como tablas, gráficos y KPIs, para analizar de manera estructurada el comportamiento de los jackpots caídos y obtener conclusiones claras a partir de los datos.</td></tr><tr><td><strong>Visualizar datos en distintas monedas</strong></td><td><p>En la barra superior, donde se muestra el nombre del dashboard, se puede alternar la visualización de la información entre la moneda local y USD.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al cambiar entre moneda local y USD, los filtros pueden perder su configuración. Para restablecerlos, haz clic en el menú de tres puntos de cada filtro, donde aparecerá la opción <strong>“filtro sin definir”</strong>, permitiendo ajustar nuevamente el valor.</p></div></td></tr></tbody></table>

#### 4.1. Filtros Disponibles

El panel izquierdo permite aplicar los siguientes filtros:

<table><thead><tr><th width="222">Filtro</th><th width="133">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha </code></strong><em><strong><code>(Desde / Hasta)</code></strong></em></td><td>Calendario</td><td>Define el rango de fechas sobre el cual se visualizará la información en el dashboard.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra el dashboard por un partner en específico.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente los registros correspondientes al país seleccionado.</td></tr><tr><td><strong><code>Nombre del jackpot</code></strong></td><td>Lista despegable</td><td>Permite seleccionar y filtrar por un jackpot específico según su nombre.</td></tr><tr><td><strong><code>ID Jackpot</code></strong></td><td>Texto</td><td>Permite buscar un jackpot específico ingresando su identificador único.</td></tr><tr><td><strong><code>Jackpot padre</code></strong> </td><td>Texto</td><td>Filtra los registros asociados a un jackpot principal o agrupador.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#tamano-del-jackpot"><strong><code>Tamaño</code></strong></a></td><td>Lista desplegable</td><td>Permite filtrar los jackpots según su categoría o tamaño definido <em>(Grande, Mega, Pequeño).</em></td></tr></tbody></table>

***

### 5. Contenido del dashboard

#### 5.1. KPIs

<table><thead><tr><th width="196.6666259765625">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cant. caídas</code></strong></td><td>Total de veces que el jackpot se ha caído dentro del rango de fechas seleccionado.</td></tr><tr><td><strong><code>Cant. participantes</code></strong></td><td>Número total de usuarios que participaron en los jackpots durante el periodo analizado.</td></tr><tr><td><strong><code>Prom. participantes</code></strong></td><td>Promedio de participantes por cada caída de jackpot en el rango de fechas seleccionado.</td></tr><tr><td><strong><code>Valor Apostado</code></strong></td><td>Suma total del valor apostado por los usuarios en los eventos asociados a jackpots dentro del periodo filtrado.</td></tr><tr><td><strong><code>Valor Premio</code></strong></td><td>Valor total entregado en premios a los usuarios durante las caídas de jackpots en el periodo analizado.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a></td><td>Ingreso bruto generado, calculado como la diferencia entre el valor apostado y el valor entregado en premios.</td></tr><tr><td><strong><code>Premio Jackpot</code></strong></td><td>Valor total correspondiente a los premios de jackpot entregados en el periodo seleccionado.</td></tr><tr><td><strong><code>% Acumulación</code></strong></td><td>Porcentaje del valor apostado que se destina a la acumulación del jackpot.</td></tr></tbody></table>

#### 5.2. Gráficos

<table><thead><tr><th width="137.6666259765625">Gráfico</th><th width="151.3333740234375">Tipo de gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad participantes</code></strong></td><td>Lineal</td><td>Muestra la evolución en el tiempo de la cantidad de participantes en los jackpots según el rango de fechas seleccionado.</td></tr><tr><td><strong><code>Cantidad caída día vs valor premiado día</code></strong></td><td>Lineal</td><td>Permite comparar, por día, la cantidad de caídas de jackpot frente al valor total entregado en premios.</td></tr><tr><td><strong><code>Promedio tamaño valor caída</code></strong></td><td>Barras</td><td>Presenta el promedio del valor de las caídas de jackpot segmentado por tamaño o categoría.</td></tr><tr><td><strong><code>Promedio valor caída</code></strong></td><td>Lineal</td><td>Muestra la tendencia de la cantidad de caídas de jackpot a lo largo del tiempo establecido en los filtros.</td></tr><tr><td><strong><code>% acumulación</code></strong></td><td>Lineal</td><td>Visualiza la variación del porcentaje de acumulación del jackpot en el periodo seleccionado.</td></tr></tbody></table>

#### 5.2. Tablas

<table><thead><tr><th width="127">Nombre tabla</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ranking cantidad caída</code></strong></td><td>Presenta un ranking de las caídas de jackpot, permitiendo identificar la frecuencia y el valor premiado por país, partner y fecha dentro del periodo seleccionado.</td></tr></tbody></table>

{% columns %}
{% column width="16.666666666666664%" %}

{% endcolumn %}

{% column width="83.33333333333334%" %}
<table><thead><tr><th width="181">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País al que pertenece la operación donde se registró la caída del jackpot.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado a la operación en la que ocurrió la caída del jackpot.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se registraron las caídas del jackpot.</td></tr><tr><td><strong><code>Cantidad de caídas</code></strong></td><td>Número total de veces que el jackpot cayó en la fecha y contexto indicado.</td></tr><tr><td><strong><code>Valor premiado</code></strong></td><td>Suma total del valor entregado en premios por concepto de jackpot en el periodo agrupado.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="127">Nombre tabla</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Resumen Jackpot</code></strong></td><td>Muestra un resumen consolidado del comportamiento de los jackpots, integrando métricas de apuestas, premios, participación de usuarios y desempeño general por categoría.</td></tr></tbody></table>

{% columns %}
{% column width="16.666666666666664%" %}

{% endcolumn %}

{% column width="83.33333333333334%" %}
<table><thead><tr><th width="181">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País al que pertenecen los registros analizados.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado a la operación de los jackpots.</td></tr><tr><td><strong><code>Id jackpot padre</code></strong></td><td>Identificador del jackpot principal al que pertenecen los registros.</td></tr><tr><td><strong><code>Tamaño jackpot</code></strong></td><td>Categoría o tamaño del jackpo<em>t (pequeño, mediano, grande).</em></td></tr><tr><td><strong><code>Fecha inicio</code></strong></td><td>Fecha en la que inicio el jackpot que callo en la fecha consultada.</td></tr><tr><td><strong><code>Ticket deportiva</code></strong></td><td>Cantidad de tickets generados en apuestas deportivas asociadas al jackpot.</td></tr><tr><td><strong><code>Valor apuesta deportiva</code></strong></td><td>Valor total apostado en la categoría deportiva.</td></tr><tr><td><strong><code>Valor premio deportiva</code></strong></td><td>Valor total entregado en premios en la categoría deportiva.</td></tr><tr><td><strong><code>Ticket casino</code></strong></td><td>Cantidad de tickets generados en juegos de casino.</td></tr><tr><td><strong><code>Valor apuesta casino</code></strong></td><td>Valor total apostado en juegos de casino.</td></tr><tr><td><strong><code>Valor premio casino</code></strong></td><td>Valor total entregado en premios en juegos de casino.</td></tr><tr><td><strong><code>Ticket live casino</code></strong></td><td>Cantidad de tickets generados en juegos de casino en vivo.</td></tr><tr><td><strong><code>Valor apuesta live casino</code></strong></td><td>Valor total apostado en juegos de casino en vivo.</td></tr><tr><td><strong><code>Valor premio live casino</code></strong></td><td>Valor total entregado en premios en juegos de casino en vivo.</td></tr><tr><td><strong><code>Premio Jackpot</code></strong></td><td>Valor total entregado específicamente por concepto de jackpot.</td></tr><tr><td><strong><code>Total apuesta</code></strong> </td><td>Suma total de las apuestas realizadas en todas las categorías.</td></tr><tr><td><strong><code>Total premio</code></strong></td><td>Suma total de los premios entregados en todas las categorías.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a></td><td>Ingreso bruto generado, calculado como la diferencia entre el total apostado y el total entregado en premios.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

### 7. ✅Reglas y validaciones.

* El dashboard es dinámico: al seleccionar un registro en las tablas, las gráficas se actualizan automáticamente para reflejar la información correspondiente al contexto seleccionado.

***

### 8.🕛 Control de Versiones

<table><thead><tr><th width="98">Versión</th><th width="133">Fecha</th><th width="148">Autor</th><th>Cambios</th></tr></thead><tbody><tr><td>1.0</td><td>24/03/2026</td><td>Ronald Peláez</td><td>Documento inicial </td></tr></tbody></table>
