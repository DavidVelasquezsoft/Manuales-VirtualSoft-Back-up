---
description: >-
  Permite visualizar y analizar la información relacionada con la facturación
  generada por la vertical de casino, con el fin de facilitar el seguimiento,
  control y toma de decisiones.
---

# Dashboard Facturación Casino

### **1. Acceso al Módulo**

**Ruta de Acceso:** Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Dashboard Facturación Casino

{% hint style="warning" %}
**Nota:** La ruta de acceso aplica para usuarios administrativos. Los usuarios con permisos podrán acceder al dashboard desde su **Library personal**, según el equipo y los accesos asignados. Para más información, consulte la [guía disponible](/broken/pages/uHkd7vNw5RDLHzelCEFz).
{% endhint %}

***

### **2. Configuraciones Previas**

Antes de visualizar el reporte, es necesario definir las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/tableros#id-2.-configuracion-previa) obligatorias.

***

### 3. Acciones disponibles

<table><thead><tr><th width="204.333251953125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="dashboard-facturacion-casino.md#id-4.1.-filtros-disponibles"><strong>Aplicar filtros</strong></a></td><td>Permite filtrar la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</td></tr><tr><td><strong>Cambiar de pestaña</strong></td><td>Permite alternar entre las diferentes pestañas del dashboard para visualizar distintas versiones del contenido según la opción seleccionada. <a href="https://github.com/DavidVelasquezsoft/BackUp-Manuales-de-usuario/tree/main/Strategy/library/README.md#id-3.-cambio-de-pestana">Guía para cambiar de pestañas</a></td></tr><tr><td><a href="dashboard-facturacion-casino.md#id-5.-contenido-del-dashboard"><strong>Visualizar contenido del tablero</strong></a></td><td>Utiliza las herramientas del dashboard, como tablas, gráficos y KPIs, para analizar de manera estructurada el comportamiento de la facturación de la vertical de casino, facilitando la interpretación de los ingresos generados y la toma de decisiones basadas en datos.</td></tr></tbody></table>

***

### 4. Filtros Disponibles

El panel izquierdo permite aplicar los siguientes filtros:

<table><thead><tr><th width="148.99993896484375">Campo</th><th width="172.8333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>permite filtrar por un <a href="https://virtualsoft.gitbook.io/untitled/glosario/#partner">partner</a> en especifico.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra por el país en el que se registran las facturaciones.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Selector de fechas</td><td><p>Rango de fechas para consultar la información de facturación dentro de un período específico.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este filtro depende del rango configurado en las configuraciones previas. Por lo tanto, el rango seleccionado debe estar dentro de los límites definidos anteriormente.</p></div></td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los datos según el subproveedor o proveedor específico de los juegos de casino.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Lista desplegable / búsqueda</td><td>Permite filtrar la información por un juego específico dentro del catálogo disponible.</td></tr><tr><td><strong><code>Tipo Casino</code></strong></td><td>Lista desplegable</td><td>Permite segmentar la información según el tipo de casino (<em>por ejemplo: slots, mesa, casino en vivo, entre otros</em>).</td></tr></tbody></table>

***

### 5. Contenido del dashboard

El contenido del dashboard se basa en la misma información, la cual se presenta de diferentes formas según la **pestaña** seleccionada, permitiendo visualizar distintas perspectivas y enfoques de los datos.

Para conocer cómo cambiar de pestaña o acceder a más información, consulte la [guía de Library](https://github.com/DavidVelasquezsoft/BackUp-Manuales-de-usuario/tree/main/Strategy/library/README.md).

Las pestañas disponibles en este dashboard son las siguientes:

{% tabs %}
{% tab title="Moneda Local" %}
Esta pestaña presenta la información en moneda local, mostrando los valores correspondientes sin conversión a otras divisas.

#### 5.1. Visualización

<figure><img src="../../../.gitbook/assets/image (142) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Dashboard Facturación Casino Pestaña Moneda local</p></figcaption></figure>

#### 5.2. KPIs

<table><thead><tr><th width="186.50006103515625">Kpi</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad Spins</code></strong></td><td>Número total de giros realizados por los usuarios en los juegos de casino durante el período analizado.</td></tr><tr><td><strong><code>Valor apuesta casino</code></strong></td><td>Monto total apostado por los usuarios dentro del período seleccionado.</td></tr><tr><td><strong><code>Valor premio casino</code></strong></td><td>Valor total de premios pagados a los usuarios, correspondiente a ganancias generadas por apuestas.</td></tr><tr><td><strong><code>Valor premio bono</code></strong></td><td>Monto total de premios ganados que provienen de bonos.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a> <strong><code>Bruto</code></strong></td><td>Ingreso bruto del juego, calculado como la diferencia entre el total apostado y los premios pagados.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a> <strong><code>Neto</code></strong></td><td>Ingreso neto del juego, calculado como el valor total de las apuestas menos los premios pagados y los bonos otorgados.</td></tr></tbody></table>

#### 5.3. Tabla de facturación

Muestra la facturación generada por cada juego de casino, donde cada registro corresponde a un juego específico en un día determinado, reflejando su comportamiento diario mediante los campos siguientes campos:

<table><thead><tr><th width="193.16668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Dia en la que se registró la facturación del juego.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner en el que se realizó la facturación.</td></tr><tr><td><strong><code>País</code></strong></td><td>País en el que se generó la facturación del juego.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda local en la que se generó la facturación.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Subproveedor o proveedor al que pertenece el juego.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego de casino sobre el cual se registra facturación.</td></tr><tr><td><strong><code>Cantidad Spins</code></strong></td><td>Número total de giros realizados en el juego durante el día.</td></tr><tr><td><strong><code>Valor apuesta casino</code></strong></td><td>Monto total apostado por los usuarios.</td></tr><tr><td><strong><code>Valor premio casino</code></strong></td><td>Valor total de premios pagados por las apuestas realizadas.</td></tr><tr><td><strong><code>Valor premio Bono</code></strong></td><td>Monto total de premios otorgados utilizando saldo de bonos.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR Bruto</code></strong></a></td><td>Ingreso GGR bruto del juego, calculado como la diferencia entre apuestas y premios pagados.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR Neto</code></strong></a></td><td>Ingreso neto del juego, resultante de descontar bonos al GGR bruto.</td></tr></tbody></table>

#### 5.4. Graficas

<table><thead><tr><th width="150.33331298828125">Nombre de la grafica</th><th width="134.83331298828125">Tipo de grafica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>TOP 5 SUBPROVEEDOR POR APUESTA</code></strong></td><td>Grafico de tortas</td><td>Indica los 5 subproveedores con mayor volumen de apuestas durante el período consultado, mostrando el porcentaje que representa cada uno sobre el total de apuestas.</td></tr><tr><td><strong><code>TENDENCIA DE APUESTAS POR AÑO / MES</code></strong></td><td>Grafico de barras</td><td>Muestra la evolución del valor total de apuestas a lo largo del tiempo, segmentado por año y mes, permitiendo identificar variaciones, crecimientos o disminuciones en el comportamiento de las apuestas.</td></tr><tr><td><strong><code>TENDENCIA</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a> <strong><code>NETO POR AÑO / MES</code></strong></td><td>Grafico de barras</td><td>Presenta la evolución del <a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">GGR</a> Neto a lo largo del tiempo, segmentado por año y mes, facilitando el análisis del rendimiento real del negocio y su comportamiento en diferentes períodos.</td></tr></tbody></table>
{% endtab %}

{% tab title="USD" %}
Esta pestaña presenta la información en dólares (_USD_), calculada con base en la [TRM](https://virtualsoft.gitbook.io/untitled/glosario#trm) vigente en el tiempo consultado.

#### 5.1. Visualización

<figure><img src="../../../.gitbook/assets/image (140) (1).png" alt=""><figcaption><p>Figura #2: Captura de pantalla Dashboard Facturación Casino Pestaña USD</p></figcaption></figure>

#### 5.2. KPIs

<table><thead><tr><th width="186.50006103515625">Kpi</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad Spins</code></strong></td><td>Número total de giros realizados por los usuarios en los juegos de casino durante el período analizado.</td></tr><tr><td><strong><code>Apuestas USD</code></strong></td><td>Monto total apostado por los usuarios en dólares (<em>USD</em>) dentro del período seleccionado.</td></tr><tr><td><strong><code>Premios USD</code></strong></td><td>Valor total de premios pagados a los usuarios en dólares (<em>USD</em>), correspondiente a ganancias generadas por apuestas.</td></tr><tr><td><strong><code>Premios Bonos USD</code></strong></td><td>Monto total de premios ganados que provienen de bonos en dólares (<em>USD</em>).</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a> <strong><code>Bruto USD</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso bruto</a> del juego en dólares (<em>USD</em>), calculado como la diferencia entre el total apostado y los premios pagados.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a> <strong><code>Neto USD</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso neto</a> del juego en dólares (<em>USD</em>), calculado como el valor total de las apuestas menos los premios pagados y los bonos otorgados.</td></tr></tbody></table>

#### 5.3. Tabla de facturación

Muestra la facturación generada por cada juego de casino, donde cada registro corresponde a un juego específico en un día determinado, reflejando su comportamiento diario mediante los campos siguientes campos:

<table><thead><tr><th width="193.16668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Dia en la que se registró la facturación del juego.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner en el que se realizó la facturación.</td></tr><tr><td><strong><code>País</code></strong></td><td>País en el que se generó la facturación del juego.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Subproveedor o proveedor al que pertenece el juego.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego de casino sobre el cual se registra facturación.</td></tr><tr><td><strong><code>TRM USD</code></strong></td><td>Tasa representativa de mercado utilizada para la conversión de valores a dólares (<em>USD</em>).</td></tr><tr><td><strong><code>Cantidad Spins</code></strong></td><td>Número total de giros realizados en el juego durante el día.</td></tr><tr><td><strong><code>Apuestas USD</code></strong></td><td>Monto total apostado por los usuarios en dólares (<em>USD</em>).</td></tr><tr><td><strong><code>Premios USD</code></strong></td><td>Valor total de premios pagados en dólares (<em>USD</em>) por las apuestas realizadas.</td></tr><tr><td><strong><code>Premios bonos USD</code></strong></td><td>Monto total de premios otorgados utilizando saldo de bonos, expresado en dólares (<em>USD</em>).</td></tr><tr><td><strong><code>GGR Bruto USD</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso bruto</a> del juego en dólares (<em>USD</em>), calculado como la diferencia entre apuestas y premios pagados.</td></tr><tr><td><strong><code>GGR Neto USD</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso neto</a> del juego en dólares (<em>USD</em>), resultante de descontar bonos al GGR bruto.</td></tr></tbody></table>

#### 5.4. Graficas

<table><thead><tr><th width="150.33331298828125">Nombre de la grafica</th><th width="134.83331298828125">Tipo de grafica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>TOP 5 SUBPROVEEDOR POR APUESTA</code></strong></td><td>Grafico de tortas</td><td>Indica los 5 subproveedores con mayor volumen de apuestas durante el período consultado, mostrando el porcentaje que representa cada uno sobre el total de apuestas.</td></tr><tr><td><strong><code>TENDENCIA DE APUESTAS POR AÑO / MES</code></strong></td><td>Grafico de barras</td><td>Muestra la evolución del valor total de apuestas en dólares (<em>USD</em>) a lo largo del tiempo, segmentado por año y mes, permitiendo identificar variaciones, crecimientos o disminuciones en el comportamiento de las apuestas.</td></tr><tr><td><strong><code>TENDENCIA</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a> <strong><code>NETO POR AÑO / MES</code></strong></td><td>Grafico de barras</td><td>Presenta la evolución del <a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">GGR</a> Neto a lo largo del tiempo en dólares (<em>USD</em>), segmentado por año y mes, facilitando el análisis del rendimiento real del negocio y su comportamiento en diferentes períodos.</td></tr></tbody></table>
{% endtab %}

{% tab title="USD Consolidado" %}
Esta pestaña presenta la información en dólares (_USD_) de forma consolidada, es decir, agrupando y sumando la facturación total en un solo resultado por el periodo de tiempo consultado, y calculada con base en la [TRM](https://virtualsoft.gitbook.io/untitled/glosario#trm) vigente en el tiempo consultado.

#### 5.1. Visualización

<figure><img src="../../../.gitbook/assets/image (143) (1).png" alt=""><figcaption><p>Figura #3: Captura de pantalla Dashboard Facturación Casino Pestaña USD consolidado</p></figcaption></figure>

#### 5.2. KPIs

<table><thead><tr><th width="186.50006103515625">Kpi</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad Spins</code></strong></td><td>Número total de giros realizados por los usuarios en los juegos de casino durante el período analizado.</td></tr><tr><td><strong><code>Apuestas USD</code></strong></td><td>Monto total apostado por los usuarios en dólares (<em>USD</em>) dentro del período seleccionado.</td></tr><tr><td><strong><code>Premios USD</code></strong></td><td>Valor total de premios pagados a los usuarios en dólares (<em>USD</em>), correspondiente a ganancias generadas por apuestas.</td></tr><tr><td><strong><code>Premios Bonos USD</code></strong></td><td>Monto total de premios ganados que provienen de bonos en dólares (<em>USD</em>).</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a> <strong><code>Bruto USD</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso bruto</a> del juego en dólares (<em>USD</em>), calculado como la diferencia entre el total apostado y los premios pagados.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a> <strong><code>Neto USD</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso neto</a> del juego en dólares (<em>USD</em>), calculado como el valor total de las apuestas menos los premios pagados y los bonos otorgados.</td></tr></tbody></table>

#### 5.3. Tabla de facturación

Muestra la facturación generada por cada juego de casino, donde cada registro corresponde a un juego específico consolidado en el periodo de tiempo consultado, reflejando su comportamiento general mediante los siguientes campos.

<table><thead><tr><th width="180.66668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Partner en el que se realizo la facturación.</td></tr><tr><td><strong><code>País</code></strong></td><td>País en el que se generó la facturación del juego.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Subproveedor o proveedor al que pertenece el juego.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego de casino sobre el cual se registra facturación.</td></tr><tr><td><strong><code>Cantidad Spins</code></strong></td><td>Número total de giros realizados en el juego durante el el periodo de tiempo consultado.</td></tr><tr><td><strong><code>Apuestas USD</code></strong></td><td>Monto total apostado por los usuarios en dólares (<em>USD</em>).</td></tr><tr><td><strong><code>Premios USD</code></strong></td><td>Valor total de premios pagados en dólares (<em>USD</em>) por las apuestas realizadas.</td></tr><tr><td><strong><code>Premios bonos USD</code></strong></td><td>Monto total de premios otorgados utilizando saldo de bonos, expresado en dólares (<em>USD</em>).</td></tr><tr><td><strong><code>GGR Bruto USD</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso bruto</a> del juego en dólares (<em>USD</em>), calculado como la diferencia entre apuestas y premios pagados.</td></tr><tr><td><strong><code>GGR Neto USD</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso neto</a> del juego en dólares (<em>USD</em>), resultante de descontar bonos al GGR bruto.</td></tr></tbody></table>

#### 5.4. Graficas

<table><thead><tr><th width="150.33331298828125">Nombre de la grafica</th><th width="134.83331298828125">Tipo de grafica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>TOP 5 SUBPROVEEDOR POR APUESTA USD</code></strong></td><td>Grafico de tortas</td><td>Indica los 5 subproveedores con mayor volumen de apuestas durante el período consultado, mostrando el porcentaje que representa cada uno sobre el total de apuestas.</td></tr><tr><td><strong><code>TOP 5 JUEGOS POR APUESTA USD</code></strong></td><td>Grafico de tortas</td><td>Indica los 5 juegos con mayor volumen de apuestas durante el período consultado, mostrando el porcentaje que representa cada uno sobre el total de apuestas.</td></tr><tr><td><strong><code>TENDENCIA DE APUESTAS POR AÑO / MES</code></strong></td><td>Grafico de barras</td><td>Muestra la evolución del valor total de apuestas en dólares (<em>USD</em>) a lo largo del tiempo, segmentado por año y mes, permitiendo identificar variaciones, crecimientos o disminuciones en el comportamiento de las apuestas.</td></tr><tr><td><strong><code>TENDENCIA</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a> <strong><code>NETO POR AÑO / MES</code></strong></td><td>Grafico de barras</td><td>Presenta la evolución del <a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">GGR</a> Neto a lo largo del tiempo en dólares (<em>USD</em>), segmentado por año y mes, facilitando el análisis del rendimiento real del negocio y su comportamiento en diferentes períodos.</td></tr></tbody></table>
{% endtab %}

{% tab title="EUR" %}
Esta pestaña presenta la información en euros (_EUR_), calculada con base en la [TRM](https://virtualsoft.gitbook.io/untitled/glosario#trm) vigente en el tiempo consultado.

#### 5.1. Visualización general

<figure><img src="../../../.gitbook/assets/image (140) (1).png" alt=""><figcaption><p>Figura #4: Captura de pantalla Dashboard Facturación Casino Pestaña EUR</p></figcaption></figure>

#### 5.2. KPIs

<table><thead><tr><th width="186.50006103515625">Kpi</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad Spins</code></strong></td><td>Número total de giros realizados por los usuarios en los juegos de casino durante el período analizado.</td></tr><tr><td><strong><code>Apuestas EUR</code></strong></td><td>Monto total apostado por los usuarios en euros (<em>EUR</em>) dentro del período seleccionado.</td></tr><tr><td><strong><code>Premios EUR</code></strong></td><td>Valor total de premios pagados a los usuarios en euros (<em>EUR</em>), correspondiente a ganancias generadas por apuestas.</td></tr><tr><td><strong><code>Premios Bonos EUR</code></strong></td><td>Monto total de premios ganados que provienen de bonos en euros (<em>EUR</em>).</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a> <strong><code>Bruto EUR</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso bruto</a> del juego en euros (<em>EUR</em>), calculado como la diferencia entre el total apostado y los premios pagados.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a> <strong><code>Neto EUR</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso neto</a> del juego en euros (<em>EUR</em>), calculado como el valor total de las apuestas menos los premios pagados y los bonos otorgados.</td></tr></tbody></table>

#### 5.3. Tabla de facturación

Muestra la facturación generada por cada juego de casino, donde cada registro corresponde a un juego específico en un día determinado, reflejando su comportamiento diario mediante los campos siguientes campos:

<table><thead><tr><th width="193.16668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Dia en la que se registró la facturación del juego.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner en el que se realizó la facturación.</td></tr><tr><td><strong><code>País</code></strong></td><td>País en el que se generó la facturación del juego.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Subproveedor o proveedor al que pertenece el juego.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego de casino sobre el cual se registra facturación.</td></tr><tr><td><strong><code>TRM EUR</code></strong></td><td>Tasa representativa de mercado utilizada para la conversión de valores a euros (<em>EUR</em>).</td></tr><tr><td><strong><code>Cantidad Spins</code></strong></td><td>Número total de giros realizados en el juego durante el día.</td></tr><tr><td><strong><code>Apuestas EUR</code></strong></td><td>Monto total apostado por los usuarios en euros (<em>EUR</em>).</td></tr><tr><td><strong><code>Premios EUR</code></strong></td><td>Valor total de premios pagados en euros (<em>EUR</em>) por las apuestas realizadas.</td></tr><tr><td><strong><code>Premios bonos EUR</code></strong></td><td>Monto total de premios otorgados utilizando saldo de bonos, expresado en euros (<em>EUR</em>).</td></tr><tr><td><strong><code>GGR Bruto EUR</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso bruto</a> del juego en euros (<em>EUR</em>), calculado como la diferencia entre apuestas y premios pagados.</td></tr><tr><td><strong><code>GGR Neto EUR</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso neto</a> del juego en euros (<em>EUR</em>), resultante de descontar bonos al GGR bruto.</td></tr></tbody></table>

#### 5.4. Graficas

<table><thead><tr><th width="150.33331298828125">Nombre de la grafica</th><th width="134.83331298828125">Tipo de grafica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>TOP 5 SUBPROVEEDOR POR APUESTA</code></strong></td><td>Grafico de tortas</td><td>Indica los 5 subproveedores con mayor volumen de apuestas durante el período consultado, mostrando el porcentaje que representa cada uno sobre el total de apuestas.</td></tr><tr><td><strong><code>TENDENCIA DE APUESTAS EUR POR AÑO / MES</code></strong></td><td>Grafico de barras</td><td>Muestra la evolución del valor total de apuestas en euros (<em>EUR</em>) a lo largo del tiempo, segmentado por año y mes, permitiendo identificar variaciones, crecimientos o disminuciones en el comportamiento de las apuestas.</td></tr><tr><td><strong><code>TENDENCIA</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a> <strong><code>NETO EUR POR AÑO / MES</code></strong></td><td>Grafico de barras</td><td>Presenta la evolución del <a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">GGR</a> Neto a lo largo del tiempo en euros (<em>EUR</em>), segmentado por año y mes, facilitando el análisis del rendimiento real del negocio y su comportamiento en diferentes períodos.</td></tr></tbody></table>
{% endtab %}

{% tab title="Consolidado" %}
Presenta la facturación de casino consolidada por subproveedor, agrupando los valores totales según el período consultado. Los montos se muestran en USD, EUR y moneda local, aplicando la [TRM](https://virtualsoft.gitbook.io/untitled/glosario#trm) correspondiente para facilitar el análisis financiero de cada proveedor.

#### 5.1. Visualización

<figure><img src="../../../.gitbook/assets/image (148) (1).png" alt=""><figcaption><p>Figura #5: Captura de pantalla Dashboard Facturación Casino Pestaña Consolidados</p></figcaption></figure>

#### **5.2. Tabla de** facturación **EUROS**

Muestra la **facturación total consolidada por subproveedor** durante el mes consultado, permitiendo analizar el desempeño general de cada proveedor dentro de la plataforma en euros (_EUR_).

<table><thead><tr><th width="181.5">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Partner en el que se registró la facturación.</td></tr><tr><td><strong><code>País</code></strong></td><td>País en el que se generó la facturación.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Subproveedor o proveedor al que pertenecen los juegos incluidos en la facturación.</td></tr><tr><td><strong><code>TRM EUR</code></strong></td><td>Tasa representativa de mercado utilizada para la conversión de valores a euros (<em>EUR</em>).</td></tr><tr><td><strong><code>Cantidad Spins</code></strong></td><td>Número total de giros realizados en los juegos del subproveedor durante el periodo de tiempo consultado.</td></tr><tr><td><strong><code>Apuestas EUR</code></strong></td><td>Monto total apostado por los usuarios en euros (<em>EUR</em>) durante el período.</td></tr><tr><td><strong><code>Premios EUR</code></strong></td><td>Valor total de premios pagados en euros (<em>EUR</em>) durante el período.</td></tr><tr><td><strong><code>Premios bonos EUR</code></strong></td><td>Monto total de premios otorgados utilizando saldo de bonos, expresado en euros (<em>EUR</em>).</td></tr><tr><td><strong><code>GGR Bruto EUR</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso bruto</a> generado, calculado como la diferencia entre apuestas y premios pagados en euros (<em>EUR</em>).</td></tr><tr><td><strong><code>GGR Neto EUR</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso neto</a> generado en euros (<em>EUR</em>), resultante de descontar bonos al GGR bruto.</td></tr></tbody></table>

#### **5.3. Tabla de** facturación **USD**

Muestra la **facturación total consolidada por subproveedor** durante el período consultado en dólares (USD), reflejando el comportamiento general de cada proveedor.

<table><thead><tr><th width="187.33331298828125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Partner en el que se registró la facturación.</td></tr><tr><td><strong><code>País</code></strong></td><td>País en el que se generó la facturación.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Subproveedor o proveedor al que pertenecen los juegos incluidos en la facturación.</td></tr><tr><td><strong><code>Cantidad Spins</code></strong></td><td>Número total de giros realizados en los juegos del subproveedor durante el período consultado.</td></tr><tr><td><strong><code>Apuestas USD</code></strong></td><td>Monto total apostado por los usuarios en dólares (<em>USD</em>).</td></tr><tr><td><strong><code>Premios USD</code></strong></td><td>Valor total de premios pagados en dólares (USD).</td></tr><tr><td><strong><code>Premios bonos USD</code></strong></td><td>Monto total de premios otorgados utilizando saldo de bonos en dólares (<em>USD</em>).</td></tr><tr><td><strong><code>GGR Bruto USD</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso bruto</a> generado en dólares (<em>USD</em>), calculado como la diferencia entre apuestas y premios pagados.</td></tr><tr><td><strong><code>GGR Neto USD</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso neto</a> generado en dólares (<em>USD</em>), resultante de descontar bonos al GGR bruto.</td></tr></tbody></table>

#### **5.4. Tabla de** facturación **Moneda LOCAL**

Muestra la **facturación total consolidada por subproveedor** en moneda local durante el período consultado.

<table><thead><tr><th width="189.00006103515625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Partner en el que se registró la facturación.</td></tr><tr><td><strong><code>País</code></strong></td><td>País en el que se generó la facturación.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda local en la que se registran los valores de facturación.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Subproveedor o proveedor al que pertenecen los juegos incluidos en la facturación.</td></tr><tr><td><strong><code>Cantidad Spins</code></strong></td><td>Número total de giros realizados en los juegos del subproveedor durante el período consultado.</td></tr><tr><td><strong><code>Valor apuesta casino</code></strong></td><td>Monto total apostado por los usuarios en la moneda local.</td></tr><tr><td><strong><code>Valor premio casino</code></strong></td><td>Valor total de premios pagados en la moneda local.</td></tr><tr><td><strong><code>Valor premio Bono</code></strong></td><td>Monto total de premios otorgados utilizando saldo de bonos en la moneda local.</td></tr><tr><td><strong><code>GGR Bruto</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso bruto</a> generado, calculado como la diferencia entre apuestas y premios pagados.</td></tr><tr><td><strong><code>GGR Neto</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">Ingreso neto</a> generado, resultante de descontar bonos al GGR bruto.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 6. Validaciones y Reglas de Negocio

* El dashboard está disponible únicamente para perfiles con permisos autorizados.
* Este dashboard presenta la misma información que el reporte [**Productos no deportivos**](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos) del backoffice. La única diferencia es que utiliza un criterio de redondeo distinto, sin afectar el valor total de los resultados.
* El dashboard permite exportar los datos de las tablas de contenido y graficas en formato **Excel,** [**CSV**](https://virtualsoft.gitbook.io/untitled/glosario#csv) **o PDF**. [**Guia de exportación**](https://github.com/DavidVelasquezsoft/BackUp-Manuales-de-usuario/tree/main/Strategy/library/README.md#id-4.-exportacion-de-contenido)

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

| Versión | Fecha      | Autor           | Cambios Realizados |
| ------- | ---------- | --------------- | ------------------ |
| 1.0     | 26/03/2026 | David Velasquez | Documento inicial  |

</details>
