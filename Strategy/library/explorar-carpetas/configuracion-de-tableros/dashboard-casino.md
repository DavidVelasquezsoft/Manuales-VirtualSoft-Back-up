---
description: >-
  El dashboard de Casino permite analizar el comportamiento de la vertical de
  Apuestas Casino a nivel general, por proveedor y por juego, con KPIs clave
  como giros, apuestas, premios, GGR y más.
---

# Dashboard Casino

### 1. Acceso al Módulo:

**Ruta de Acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Dashboard Casino

***

### **2. Configuraciones Previas**

Antes de visualizar el reporte, es necesario definir las [configuraciones previas](./#id-1.-configuraciones-previas) obligatorias.

***

### 3. Acciones disponibles

<table><thead><tr><th width="188.77777099609375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Aplicar filtros</strong></td><td>Permite filtrar la información según los criterios disponibles en cada vista. Las opciones de filtrado pueden variar o no estar disponibles, según la vista seleccionada. Esto facilita un análisis más específico de los datos cuando aplica.</td></tr><tr><td><strong>Cambiar de pestaña</strong></td><td>Permite alternar entre las diferentes pestañas del dashboard para visualizar distintas versiones del contenido según la opción seleccionada. <a href="../../#id-3.-cambio-de-pestana">Guía para cambiar de pestañas</a></td></tr><tr><td><a href="dashboard-casino.md#id-5.-contenido-del-dashboard"><strong>Visualizar contenido del tablero</strong></a></td><td>Utiliza las herramientas del dashboard, como tablas, gráficos y KPIs, para analizar de manera estructurada el comportamiento de la facturación de la vertical de deportivas, facilitando la interpretación de los ingresos generados y la toma de decisiones basadas en datos.</td></tr><tr><td><strong>Cambio tipo de moneda</strong></td><td>Permite alternar la visualización de los valores monetarios del dashboard entre moneda local y USD.</td></tr><tr><td><strong>Exportar contenido</strong></td><td>El dashboard permite exportar su contenido en el <strong>tipo de moneda</strong> que se encuentre activo. Para más información, consulte la guía de exportación <a data-mention href="../../#id-4.-exportar-contenido">#id-4.-exportar-contenido</a>.</td></tr></tbody></table>

***

### 5. Contenido del dashboard

El dashboard está compuesto por **tres vistas**, entre las cuales puede navegar mediante las opciones disponibles en el menú lateral izquierdo. En cualquiera de ellas, es posible alternar la visualización de los valores monetarios entre **moneda local y USD** mediante los botones <img src="../../../.gitbook/assets/image (187).png" alt="" data-size="line"> ubicados en la esquina superior izquierda. Al realizar el cambio, toda la información monetaria se actualizará automáticamente **sin afectar los filtros aplicados**. Este dashboard cuenta con las siguientes vistas:

{% tabs %}
{% tab title="Casino General" %}
Presenta información general de casino mediante diferentes tipos de gráficas e indicadores. No incluye filtros adicionales a los definidos en la [configuración previa](../../#id-2.-configuracion-previa), por lo que su contenido corresponde únicamente a información general del casino.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (189).png" alt=""><figcaption><p>Figura#1: Captura de pantalla dashboard vista Casino general.</p></figcaption></figure>

#### Indicadores

<table><thead><tr><th width="184.33331298828125">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cant. Spins</code></strong> </td><td>Total de giros realizados por los usuarios en los juegos de casino.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Valor acumulado de todas las apuestas realizadas.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Suma de todos los premios entregados a los usuarios.</td></tr><tr><td><strong><code>Premios Bonos</code></strong></td><td>Suma de los premios otorgados en forma de bonos.</td></tr><tr><td><strong><code>Bonos</code></strong></td><td>Monto total de bonos utilizados en juegos de casino.</td></tr><tr><td><strong><code>Usuarios Activos</code></strong></td><td>Cantidad total de usuarios con actividad en casino.</td></tr><tr><td><strong><code>Promedio apuesta</code></strong></td><td>Promedio del valor apostado entre todos los usuarios.</td></tr><tr><td><strong><code>Saldo gratis</code></strong></td><td>Valor total apostado utilizando saldo gratuito otorgado por la plataforma.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr"><strong><code>GGR</code></strong></a></td><td>Ingreso neto del Juego, calculado como Total Apostado - Total Premios - Total bonos.</td></tr><tr><td><strong><code>% Margen</code></strong></td><td>Porcentaje del GGR sobre el total apostado. Fórmula: GGR / Total Apostado.</td></tr></tbody></table>

#### Graficas

<table><thead><tr><th width="152">Gráfico</th><th width="108.40740966796875">Tipo de gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>GGR Mensual</code></strong></td><td>Barras</td><td>Muestra el total del <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">GGR neto</a> generado en cada mes y permite comparar su variación mensual.</td></tr><tr><td><strong><code>(Mes) Val. Apostado Vs Val. Premios.</code></strong></td><td>Barras</td><td>Compara, por mes, el valor total apostado frente al valor total pagado en premios.</td></tr><tr><td><strong><code>GGR Diario</code></strong></td><td>Lineal</td><td>Evolución diaria del <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">GGR neto</a> dentro del periodo filtrado.</td></tr><tr><td><strong><code>(Diario) Val.Apostado Vs Val.Premios</code></strong></td><td>Lineal</td><td>Compara el total apostado vs el total en premios cada mes.</td></tr><tr><td><strong><code>GGR por Partner</code></strong></td><td>Tabla</td><td>Tabla comparativa del <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">GGR neto</a> por cada partner filtrado.</td></tr><tr><td><strong><code>(Diario) Spins(Giros</code>)</strong></td><td>Lineal</td><td>Muestra la evolución en una gráfica en línea de los spins (giros) realizados en el período seleccionado.</td></tr><tr><td><strong><code>Giros x día de la semana</code></strong> </td><td>Lineal</td><td>Representa la cantidad total de giros realizados por día durante la semana.</td></tr><tr><td><strong><code>Apuesta x día de la semana</code></strong></td><td>Lineal</td><td>Muestra la cantidad total de apuestas realizados por día durante la semana.</td></tr><tr><td><strong><code>GGR semanal</code></strong></td><td>Lineal</td><td>Muestra el comportamiento del GGR correspondiente a cada día de la semana.</td></tr></tbody></table>
{% endtab %}

{% tab title="proveedor" %}
Permite visualizar el comportamiento de los usuarios en la sección de casino por proveedor, utilizando gráficos, filtros y tablas para facilitar el análisis.

{% hint style="warning" %}
**Nota:** Las gráficas muestran la información correspondiente al registro seleccionado en la tabla. Al seleccionar un resultado diferente, las gráficas se actualizarán automáticamente para reflejar los datos asociados a dicha selección.
{% endhint %}

#### Visualización

<figure><img src="../../../.gitbook/assets/image (190).png" alt=""><figcaption><p>Figura#2: Captura de pantalla Vista proveedor.</p></figcaption></figure>

#### Filtros

<table><thead><tr><th width="181.5">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Proveedor</code></strong></td><td>Permite filtrar por el identificador único del proveedor.</td></tr><tr><td><strong><code>Nombre Proveedor</code></strong></td><td>Busca por nombre del proveedor.</td></tr><tr><td><strong><code>Tipo Proveedor</code></strong></td><td>Clasifica los proveedores según su categoría o tipo <em>(Ejemplo: Casino, live casino).</em></td></tr></tbody></table>

#### Indicadores

<table><thead><tr><th width="172.70367431640625">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cant. Spins</code></strong></td><td>Total de giros realizados en los juegos de los proveedores visualizados.</td></tr><tr><td><strong><code>Usuarios Activos</code></strong></td><td>Cantidad total de usuarios con actividad en los juegos de los proveedores visualizados.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Valor acumulado de las apuestas realizadas en los juegos de los proveedores visualizados.</td></tr><tr><td><strong><code>Promedio apuesta</code></strong></td><td>Promedio del valor apostado en los juegos de los proveedores visualizados.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Suma de los premios entregados en los juegos de los proveedores visualizados.</td></tr><tr><td><strong><code>Saldo Gratis</code></strong></td><td>Valor total apostado utilizando saldo gratuito en los juegos de los proveedores visualizados.</td></tr><tr><td><strong><code>Premios Bonos</code></strong></td><td>Suma de los premios obtenidos mediante bonos en los juegos de los proveedores visualizados.</td></tr><tr><td><strong><code>GGR</code></strong></td><td><a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">Ingreso neto</a> del Juego generado por los proveedores visualizados, calculado como (<em>Apuestas - Premios - Bonos</em>).</td></tr><tr><td><strong><code>Bonos</code></strong></td><td>Valor total de bonos utilizados en los juegos de los proveedores visualizados.</td></tr><tr><td><strong><code>% Margen</code></strong></td><td><p>Porcentaje de margen generado por los proveedores, calculado como la relación entre el <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">GGR neto</a> y el valor total apostado.</p><p><strong>Fórmula:</strong> % Margen = (<em>GGR ÷ Total Apostado</em>) × 100</p></td></tr></tbody></table>

#### Tabla detalle Proveedor

<table><thead><tr><th width="234.33331298828125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Partner en el que está el proveedor.</td></tr><tr><td><strong><code>País</code></strong></td><td>País en el que está habilitado el proveedor.</td></tr><tr><td><strong><code>ID del Proveedor</code></strong></td><td>Identificador único del proveedor.</td></tr><tr><td><strong><code>Nombre del Proveedor</code></strong></td><td>Nombre del proveedor de juegos.</td></tr><tr><td><strong><code>Cantidad de Jugadores Únicos casino</code></strong></td><td>Número de usuarios únicos que interactuaron con el proveedor.</td></tr><tr><td><strong><code>Cantidad de Spins</code></strong></td><td>Total de giros realizados en los juegos del proveedor.</td></tr><tr><td><strong><code>Promedio de Spins</code></strong></td><td>promedio de giros por jugador.</td></tr><tr><td><strong><code>Promedio apuesta</code></strong></td><td>Promedio de apuestas por jugador en los juegos correspondientes de dicho partner.</td></tr><tr><td><strong><code>Valor Apuestas Casino</code></strong></td><td>Monto total apostado en juegos de ese proveedor.</td></tr><tr><td><strong><code>Valor Saldo Gratis</code></strong></td><td>Suma del saldo gratuito consumido en esos juegos.</td></tr><tr><td><strong><code>Valor Premios Casino</code></strong></td><td>Total de premios otorgados en dinero real.</td></tr><tr><td><strong><code>Valor Premios Bonos</code></strong></td><td>Total de premios entregados en forma de bonos.</td></tr><tr><td><strong><code>GGR</code></strong></td><td><a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">Ingreso neto</a> del Juego para ese proveedor.</td></tr><tr><td><strong><code>%Margen casino</code></strong>  </td><td><p>Porcentaje de margen generado por los proveedores, calculado como la relación entre el <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">GGR neto</a> y el valor total apostado.</p><p><strong>Fórmula:</strong> % Margen = (<em>GGR ÷ Total Apostado</em>) × 100</p></td></tr></tbody></table>

#### Gráficos de proveedor (_pastel_)

<table><thead><tr><th width="226.33331298828125">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Apuesta por tipo proveedor</code></strong></td><td>Visualiza la cantidad de apuestas realizadas en cada tipo de proveedor <em>(Casino, casino en vivo)</em></td></tr><tr><td><strong><code>GGR por tipo proveedor</code></strong></td><td>Visualiza el <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">ingreso neto</a> <em>(GGR)</em> de cada uno de los proveedores <em>(Casino, casino en vivo)</em></td></tr></tbody></table>

#### **Gráficos de Pastel (**_**Top 10**_**)**

<table><thead><tr><th width="282">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>TOP 10 giros</code></strong></td><td>Muestra los 10 proveedores con mayor cantidad de giros.</td></tr><tr><td><strong><code>TOP 10 Apostado</code></strong></td><td>Proveedores con los valores apostados más altos.</td></tr><tr><td><strong><code>TOP 10 GGR</code></strong></td><td>Proveedores que generaron el mayor <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">ingreso neto</a> (GGR).</td></tr></tbody></table>

#### **Gráficos de Línea**

<table><thead><tr><th width="282">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor con más giros x día de la semana</code></strong></td><td>Muestra la evolución de giros por proveedor en la semana.</td></tr><tr><td><strong><code>Proveedor con más v. apostado x día de la semana</code></strong></td><td>Evolución del valor apostado semanalmente por proveedor.</td></tr><tr><td><strong><code>Proveedor con más GGR x día de la semana</code></strong></td><td>Evolución del <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">GGR neto</a> semanal de los principales proveedores.</td></tr></tbody></table>
{% endtab %}

{% tab title="Juego" %}
Permite visualizar el comportamiento de los usuarios en la sección de casino dentro de cada uno de los juegos disponibles, utilizando gráficos, filtros y tablas para facilitar el análisis.

{% hint style="warning" %}
**Nota:** Las gráficas muestran la información correspondiente al registro seleccionado en la tabla. Al seleccionar un resultado diferente, las gráficas se actualizarán automáticamente para reflejar los datos asociados a dicha selección.
{% endhint %}

#### Visualización

<figure><img src="../../../.gitbook/assets/image (191).png" alt=""><figcaption><p>Figura #3: Captura de pantalla vista juegos</p></figcaption></figure>

#### Filtros

<table><thead><tr><th width="201">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre Juego</code></strong></td><td>Permite buscar un juego por su nombre.</td></tr><tr><td><strong><code>Tipo Juego</code></strong></td><td>Clasificación del juego según su categoría.</td></tr><tr><td><strong><code>Nombre Subproveedor</code></strong></td><td>Filtra por el nombre del proveedor correspondiente al juego.</td></tr></tbody></table>

#### Indicadores

<table><thead><tr><th width="169.00006103515625">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cant. Spins</code></strong></td><td>Total de giros realizados en los juegos visualizados.</td></tr><tr><td><strong><code>Usuarios Activos</code></strong></td><td>Cantidad total de usuarios con actividad en los juegos visualizados.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Valor acumulado de las apuestas realizadas en los juegos visualizados.</td></tr><tr><td><strong><code>Promedio apuesta</code></strong></td><td>Valor monetario promedio apostado en el juego visualizado.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Suma de los premios entregados en los juegos visualizados.</td></tr><tr><td><strong><code>Saldo Gratis</code></strong></td><td>Valor total apostado utilizando saldo gratuito en los juegos visualizados.</td></tr><tr><td><strong><code>Premios Bonos</code></strong></td><td>Suma de los premios obtenidos mediante bonos en los juegos visualizados.</td></tr><tr><td><strong><code>GGR</code></strong></td><td>Ingreso Bruto del Juego generado por los juegos visualizados, calculado como Apuestas - Premios.</td></tr><tr><td><strong><code>Bonos</code></strong></td><td>Valor total de bonos utilizados en los juegos visualizados.</td></tr><tr><td><strong><code>% Margen</code></strong></td><td><p>Porcentaje de margen generado por los proveedores, calculado como la relación entre el <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">GGR neto</a> y el valor total apostado en juegos de casino.</p><p><strong>Fórmula:</strong> % Margen = (<em>GGR ÷ Total Apostado</em>) × 100</p></td></tr></tbody></table>

#### Tabla Detalle producto (_Juego_)

<table><thead><tr><th width="272">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del socio asociado.</td></tr><tr><td><strong><code>País</code></strong></td><td>País al que pertenece la información.</td></tr><tr><td><strong><code>Nombre proveedor</code></strong></td><td>Nombre del proveedor correspondiente al juego.</td></tr><tr><td><strong><code>Nombre Juego</code></strong></td><td>Nombre del juego evaluado.</td></tr><tr><td><strong><code>Cantidad de Jugadores Únicos casino</code></strong></td><td>Número de usuarios distintos que interactuaron con ese juego.</td></tr><tr><td><strong><code>Cantidad de Spins</code></strong></td><td>Total de giros realizados en ese juego.</td></tr><tr><td><strong><code>Promedio apuesta</code></strong></td><td>Promedio de las apuestas realizadas en el juego.</td></tr><tr><td><strong><code>Valor Apuestas Casino</code></strong></td><td>Suma total de las apuestas realizadas en el juego.</td></tr><tr><td><strong><code>Valor Saldo Gratis</code></strong></td><td>Valor total  del saldo gratuito consumido en el juego.</td></tr><tr><td><strong><code>Valor Premios Casino</code></strong></td><td>Total de premios pagados a los usuarios mediante este juego.</td></tr><tr><td><strong><code>Valor Premios Bonos</code></strong></td><td>Total de premios entregados en forma de bonos en el juego.</td></tr><tr><td><strong><code>GGR</code></strong></td><td><a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">Ingreso neto</a> generado por ese juego (Apuestas - Premios).</td></tr><tr><td><strong><code>% Margen casino</code></strong></td><td><p>Porcentaje de margen generado por los proveedores, calculado como la relación entre el <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">GGR neto</a> y el valor total apostado en juegos de casino.</p><p><strong>Fórmula:</strong> % Margen = (<em>GGR ÷ Total Apostado</em>) × 100</p></td></tr></tbody></table>

#### **Gráficos de Pastel (**_**Top 10**_**)**

<table><thead><tr><th width="282">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>TOP 10 Giros</code></strong></td><td>Ranking de los juegos con mayor cantidad de giros.</td></tr><tr><td><strong><code>TOP 10 Apostado</code></strong></td><td>Juegos donde se realizaron las mayores apuestas.</td></tr><tr><td><strong><code>TOP 10 GGR</code></strong></td><td>Juegos que generaron el mayor ingreso bruto.</td></tr></tbody></table>

#### **Gráficos de Barras**

<table><thead><tr><th width="282">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Top 10 Juegos GGR Negativo</code></strong></td><td>Juegos con pérdidas para la plataforma (GGR negativo).</td></tr><tr><td><strong><code>Top 10 Juego GGR Positivo</code></strong></td><td>Juegos que generaron mayor ganancia para la plataforma.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 6. Validaciones y Reglas de Negocio

* Los filtros de cada tablero siempre dependerán de las [configuraciones previas](./#id-1.-configuraciones-previas) .

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="114.7037353515625">Versión</th><th width="145.5555419921875">Fecha</th><th width="160.4073486328125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>29/07/2025</td><td>Karol Navia</td><td>Creación de manual inicial</td></tr><tr><td>1.1</td><td>19/11/2025</td><td>Ronald Peláez</td><td>Refinamiento de manual.</td></tr><tr><td>1.2</td><td>04/06/2026</td><td>David Velasquez</td><td>Incorpotación de Vista en USD</td></tr></tbody></table>

</details>
