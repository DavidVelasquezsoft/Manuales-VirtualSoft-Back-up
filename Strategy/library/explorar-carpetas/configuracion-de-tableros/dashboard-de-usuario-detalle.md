---
description: >-
  Permite visualizar de forma centralizada la actividad de cada usuario,
  ofreciendo acceso rápido a métricas clave y comportamientos relevantes durante
  el periodo consultado.
---

# Dashboard de Usuario Detalle

#### 1. Acceso al Módulo

**Ruta de acceso:** Virtualsoft > Informes compartidos > Datas TI > Dashboard de Usuario Detalle

***

#### 2. Configuraciones Previas

Antes de ejecutar el dashboard, asegúrate de configurar los [parámetros](../../#id-2.-configuracion-previa) requeridos.\
Estos parámetros permiten que la información corresponda al período consultado.

***

#### 3. 🧩 Filtros del Dashboard

Los filtros permiten segmentar la información por partner, país, período o usuario específico.

<table><thead><tr><th width="165.66668701171875">Filtro</th><th width="161">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Selecciona el partner desde el cual se desea consultar información.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra la información por país.</td></tr><tr><td><strong><code>Año</code></strong></td><td>Lista desplegable</td><td>Muestra datos del año seleccionado.</td></tr><tr><td><strong><code>Mes</code></strong></td><td>Lista desplegable</td><td>Filtra los datos según el mes del año definido.</td></tr><tr><td><strong><code>Días del mes</code></strong></td><td>Lista desplegable</td><td>Permite consultar información de un día específico.</td></tr><tr><td><strong><code>Buscar ID Usuario</code></strong></td><td>Lista desplegable</td><td>Permite buscar un usuario directamente por su identificador.</td></tr></tbody></table>

***

### 4. Pestañas disponibles en el reporte.

Este dashboard se compone de **dos pestañas**, cada una orientada a un nivel de análisis distinto de la información. Ambas permiten consultar el comportamiento de los usuarios según los filtros aplicados, ya sea desde una vista detallada o desde un resumen consolidado.

{% tabs %}
{% tab title="4.1  Detalle general" %}
### 4.2. Visualización general

<figure><img src="../../../.gitbook/assets/image (26).png" alt=""><figcaption><p>Figura#1: Captura de pantalla detalle general.</p></figcaption></figure>

{% tabs %}
{% tab title="Usuario detalle" %}
Permite visualizar un resumen consolidado por usuario, mostrando sus principales métricas operativas, movimientos y actividad general según los filtros aplicados.

### 4.3. 📄Tabla de Datos del Usuario

La vista principal resume toda la actividad del usuario aplicando los filtros seleccionados, mostrando únicamente la información relevante para el periodo y criterios definidos.

<table><thead><tr><th width="209.66668701171875">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total</code></strong></td><td>Muestra el valor total de cada acción. Por ejemplo, en la columna “<em><strong>Cantidad de Depósitos</strong></em>” se visualizará el valor acumulado de todos los depósitos realizados, según los filtros aplicados.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador único del usuario.</td></tr><tr><td><strong><code>Cantidad Depósito</code></strong></td><td>Número total de depósitos realizados.</td></tr><tr><td><strong><code>Valor Depósito</code></strong></td><td>Valor total depositado.</td></tr><tr><td><strong><code>Cantidad Retiros</code></strong></td><td>Total de retiros realizados.</td></tr><tr><td><strong><code>Valor Retiros</code></strong></td><td>Valor total retirado.</td></tr><tr><td><strong><code>Valor Apuesta Cerrada</code></strong></td><td>Total apostado en <a href="https://virtualsoft.gitbook.io/untitled/glosario/#apuesta-cerrada">apuestas cerradas</a>.</td></tr><tr><td><strong><code>Valor Premio Cerrado</code></strong></td><td>Total ganado en apuestas cerradas.</td></tr><tr><td><strong><code>Valor Bonos Deportivas</code></strong></td><td>Total de bonos asignados en Deportivas.</td></tr><tr><td><strong><code>GGR Deportiva</code></strong></td><td>Ingreso neto de las apuestas realizadas en la vertical deportiva: <em>(Apuestas – Premios – Bonos).</em></td></tr><tr><td><strong><code>Valor Apuesta Casino</code></strong></td><td>Total apostado en Casino.</td></tr><tr><td><strong><code>Valor Saldo Gratis</code></strong></td><td>Total asignado de saldo proveniente de bonos o campañas.</td></tr><tr><td><strong><code>Valor Premio Casino</code></strong></td><td>Total en premios obtenidos en apuestas de Casino.</td></tr><tr><td><strong><code>Valor Premio Bono</code></strong></td><td>Total en premios provenientes de bonos.</td></tr><tr><td><strong><code>Valor Bono Casino</code></strong></td><td>Total de bonos otorgados en Casino.</td></tr><tr><td><strong><code>GGR Casino</code></strong></td><td>Ingreso neto de las apuestas realizadas en la vertical casino: <em>(Apuestas – Premios – Bonos).</em></td></tr></tbody></table>
{% endtab %}

{% tab title="PEP y Autoexclusiones " %}
Muestra el estado **PEP (Persona Políticamente Expuesta)** del usuario y las **fechas de autoexclusión por cada vertical**, permitiendo identificar restricciones **activas** o **históricas**.&#x20;

#### ¿Que es una Autoexclusi**ó**n?

La **autoexclusión** es una medida de juego responsable en la que el usuario solicita bloquear su acceso a una vertical por un tiempo definido o indefinido, limitando su operación mientras esté vigente.

<table><thead><tr><th width="209">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador único del usuario dentro de la plataforma. </td></tr><tr><td><strong><code>PEP</code></strong></td><td>Indicador categórico que señala si el usuario se declaró como Persona Políticamente Expuesta (SI / NO).</td></tr><tr><td><strong><code>Fecha Aceptación PEP</code></strong></td><td>Fecha en la que el usuario acepta su condición como PEP durante el registro u otro flujo habilitado.</td></tr><tr><td><strong><code>Fecha Autoexclusión Inicial Casino</code></strong></td><td>Fecha de inicio de la autoexclusión del usuario para la vertical Casino.</td></tr><tr><td><strong><code>Fecha Autoexclusión Final Casino</code></strong></td><td>Fecha de finalización de la autoexclusión del usuario para la vertical Casino.</td></tr><tr><td><strong><code>Fecha Autoexclusión Inicial Casinolive</code></strong></td><td>Fecha de inicio de la autoexclusión del usuario para la vertical Casino Live.</td></tr><tr><td><strong><code>Fecha Autoexclusión Final Casinolive</code></strong></td><td>Fecha de finalización de la autoexclusión del usuario para la vertical Casino Live.</td></tr><tr><td><strong><code>Fecha Autoexclusión Inicial Deportivas</code></strong></td><td>Fecha de inicio de la autoexclusión del usuario para la vertical Deportivas.</td></tr><tr><td><strong><code>Fecha Autoexclusión Final Deportivas</code></strong></td><td>Fecha de finalización de la autoexclusión del usuario para la vertical Deportivas.</td></tr><tr><td><strong><code>Fecha Autoexclusión Inicial Virtuales</code></strong></td><td>Fecha de inicio de la autoexclusión del usuario para la vertical Virtuales.</td></tr><tr><td><strong><code>Fecha Autoexclusión Final Virtuales</code></strong></td><td>Fecha de finalización de la autoexclusión del usuario para la vertical Virtuales.</td></tr><tr><td><strong><code>Fecha Autoexclusión Inicial Todas las Verticales</code></strong></td><td>Fecha de inicio de la autoexclusión global del usuario, aplicable a todas las verticales.</td></tr><tr><td><strong><code>Fecha Autoexclusión Final Todas las Verticales</code></strong></td><td>Fecha de finalización de la autoexclusión global del usuario, aplicable a todas las verticales.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="4.2 Análisis" %}
Permite visualizar el desempeño detallado de los usuarios a través de KPIs, tendencias comparaciones, facilitando la identificación de patrones y contribuciones por vertical.

### 4.2.1 Visualización

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FQmKZTicQqpll1rYovb6y%2Fimage.png?alt=media&#x26;token=a9b7b713-66f9-444c-904c-edaca5a9bfa5" alt=""><figcaption><p>Figura#1: Captura de pantalla Dashboard usuario análisis.</p></figcaption></figure>

***

### 4.2.2 Contenido del dashboard.

#### 4.2.2.1 KPI´s principales

<table><thead><tr><th width="184.3333740234375">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor Depósitos</code></strong></td><td>Total depositado por los usuarios dentro del periodo filtrado.</td></tr><tr><td><strong><code>Valor Retiros</code></strong></td><td>Total retirado por los usuarios en el periodo consultado.</td></tr><tr><td><strong><code>Apostado deportivas</code></strong></td><td>Total apostado en la vertical deportivas <em>(</em><a href="https://app.gitbook.com/o/QcwavWzh0dfIwPyknoIT/s/mbqa0WvDWam8G20QQoIZ/#apuesta-cerrada"><em>apuestas cerradas</em></a><em>).</em></td></tr><tr><td><strong><code>GGR deportivas</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr">GGR</a> total generado en apuestas deportivas.</td></tr><tr><td><strong><code>Apostado casino</code></strong></td><td>Total apostado en la vertical de casino <em>(slot, en vivo y virtuales).</em></td></tr><tr><td><strong><code>GGR casino</code></strong></td><td>GGR consolidado de todas las verticales de casino.</td></tr></tbody></table>

#### 4.2.2.2 Gráficos lineales

<table><thead><tr><th width="195.66668701171875">Visualización</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Apostado en casino por periodo</code></strong></td><td>Comparativa lineal del valor total apostado en el vertical casino correspondiente a todos los usuarios filtrados por día.</td></tr><tr><td><strong><code>Apostado deportivas por periodo</code></strong></td><td>Comparativa lineal del valor total apostado en el vertical deportivas correspondiente a todos los usuarios filtrados por día.</td></tr><tr><td><strong><code>Depósitos vs retiros por periodo</code></strong></td><td>Comparativa lineal del valor total de retiros vs depósitos realizados por los usuarios filtrados correspondientes a los días.</td></tr><tr><td><strong><code>GGR casino por periodo</code></strong></td><td>Comparativa lineal del GGR obtenido por la vertical casino de manera diaria.</td></tr><tr><td><strong><code>GGR deportiva por periodo</code></strong></td><td>Comparativa lineal del GGR obtenido por la vertical deportiva de manera diaria.</td></tr></tbody></table>

#### 4.2.2.3 Gráficos de barras&#x20;

<table><thead><tr><th width="138">Visualización</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Top 20 usuarios más apostadores en casino</code></strong></td><td><p>Muestra el ranking de los 20 usuarios con mayor monto apostado y una tabla con el detalle total de apostadores de casino.</p><div data-gb-custom-block data-tag="tabs"><div data-gb-custom-block data-tag="tab" data-title="Top 20"><p>Visualiza un top 20 de los usuarios con el valor total de apuestas más alto en casino.</p></div><div data-gb-custom-block data-tag="tab" data-title="Detalle total"><p>Obtiene un detalle de las apuestas realizadas por los usuarios en casino:</p><ul><li><strong><code>Id Usuario:</code></strong> Identificador único del usuario que realizó la apuesta.</li><li><strong><code>Vertical:</code></strong> Vertical en la que se realizó la apuesta (Casino o Live Casino).</li><li><strong><code>Valor apuesta casino:</code></strong> Valor total apostado por el usuario en la vertical Casino.</li></ul></div></div></td></tr><tr><td><strong><code>Top 20 usuarios más apostadores en deportiva</code></strong></td><td><p>Presenta el Top 20 de usuarios con mayor volumen apostado en deportivas y la tabla completa de todos los usuarios con apuestas cerradas.</p><div data-gb-custom-block data-tag="tabs"><div data-gb-custom-block data-tag="tab" data-title="Top 20"><p>Visualiza un top 20 de los usuarios con el valor total de apuestas más alto en deportiva.</p></div><div data-gb-custom-block data-tag="tab" data-title="Detalle total"><p>Obtiene un detalle de las apuestas realizadas por los usuarios en deportivas</p><ul><li><strong><code>Id Usuario:</code></strong> Identificador único del usuario que realizó la apuesta.</li><li><strong><code>Valor apuesta cerrada:</code></strong> Monto total correspondiente a las apuestas que ya fueron cerradas.</li></ul></div></div></td></tr><tr><td><strong><code>Top 20 usuarios que más depositan y retiran</code></strong></td><td><p>Incluye el Top 20 de usuarios con mayor movimiento transaccional y el detalle completo de todos los usuarios que realizaron depósitos o retiros.</p><div data-gb-custom-block data-tag="tabs"><div data-gb-custom-block data-tag="tab" data-title="Top 20"><p>Presenta una gráfica de barras comparativa con los 20 usuarios que registran los mayores volúmenes de depósitos y retiros.</p></div><div data-gb-custom-block data-tag="tab" data-title="Detalle total"><p>Obtiene un detalle de los usuarios que más movimientos transaccionales realizaron.</p><ul><li><strong><code>Id Usuario:</code></strong> Identificador único del usuario que realizó la apuesta.</li><li><strong><code>Valor depósito:</code></strong> Monto depositado por el usuario.</li><li><strong><code>Valor retiros:</code></strong> Monto retirado por el usuario</li></ul></div></div></td></tr><tr><td><strong><code>Top 20 usuario que más dejan GGR casino</code></strong></td><td><p>Muestra el Top 20 de usuarios que generan mayor GGR en casino y la tabla completa de contribuciones de todos los usuarios a esta vertical.</p><div data-gb-custom-block data-tag="tabs"><div data-gb-custom-block data-tag="tab" data-title="Top 20"><p>Gráfica de barras que muestra a los 20 usuarios con mayor aporte al GGR en la vertical de casino, permitiendo identificar rápidamente quiénes generan la mayor rentabilidad en este segmento.</p></div><div data-gb-custom-block data-tag="tab" data-title="Detalle total"><p>Obtiene un detalle de las apuestas realizadas por los usuarios en casino</p><ul><li><strong><code>Id Usuario:</code></strong> Identificador único del usuario que realizó la apuesta.</li><li><strong><code>Vertical:</code></strong> Vertical en la que se realizó la apuesta <em>(Casino o livecasino).</em></li><li><strong><code>GGR sub </code></strong><em><strong><code>(para detalle total):</code></strong></em> Valor total de<a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr"> GGR</a> generado por el usuario exclusivamente en la vertical de casino durante el periodo consultado.</li></ul></div></div></td></tr><tr><td><strong><code>Top 20 usuario que más dejan GGR deportiva</code></strong></td><td><p>Presenta el Top 20 de usuarios con mayor GGR en deportivas y el detalle total de todos los usuarios que generan GGR en esta vertical.</p><div data-gb-custom-block data-tag="tabs"><div data-gb-custom-block data-tag="tab" data-title="Top 20"><p>Gráfica de barras que muestra a los 20 usuarios con mayor aporte al <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr">GGR</a> en la vertical de deportiva, permitiendo identificar rápidamente quiénes generan la mayor rentabilidad en este segmento.</p></div><div data-gb-custom-block data-tag="tab" data-title="Detalle total"><p>Obtiene un detalle de las apuestas realizadas por los usuarios en deportiva.</p><ul><li><strong><code>Id Usuario:</code></strong> Identificador único del usuario que realizó la apuesta.</li><li><strong><code>GGR deportiva:</code></strong> Valor total del <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr">GGR</a> obtenido por el usuario en la vertical deportiva.</li></ul></div></div></td></tr></tbody></table>

#### 4.2.2.4 Detalle general por usuario

<table><thead><tr><th width="231">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Operador o marca a la que pertenece el usuario.</td></tr><tr><td><strong><code>País</code></strong></td><td>País registrado del usuario.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha asociada al movimiento dentro del periodo filtrado.</td></tr><tr><td><strong><code>ID usuario</code></strong></td><td>Identificador único del usuario dentro de la plataforma.</td></tr><tr><td><strong><code>Valor depósito</code></strong></td><td>Total depositado por el usuario en el periodo seleccionado.</td></tr><tr><td><strong><code>Valor retiros</code></strong></td><td>Total retirado por el usuario durante el periodo consultado.</td></tr><tr><td><strong><code>Valor cerradas deportiva</code></strong></td><td>Valor total apostado en apuestas deportivas cerradas.</td></tr><tr><td><strong><code>GGR deportiva</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr">GGR</a> generado por el usuario en la vertical deportiva.</td></tr><tr><td><strong><code>Apostado casino slot</code></strong></td><td>Total apostado por el usuario en juegos de casino.</td></tr><tr><td><strong><code>GGR casino slot</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr">GGR</a> generado por el usuario en juegos de slot.</td></tr><tr><td><strong><code>Apostado casino en vivo</code></strong></td><td>Total apostado en la vertical de casino en vivo.</td></tr><tr><td><strong><code>GGR casino en vivo</code></strong></td><td>GGR generado por el usuario en juegos de casino en vivo.</td></tr><tr><td><strong><code>Apostado casino virtuales</code></strong></td><td>Total apostado en juegos de casino virtuales.</td></tr><tr><td><strong><code>GGR casino virtuales</code></strong></td><td>GGR generado por el usuario en la vertical de casino virtuales.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}



***

#### 6. ✅ Validaciones y Reglas de Negocio

* La vista gráfica solo mostrará paneles si existe data relacionada al rango filtrado.
* Las gráficas muestran siempre la información activa: si aplicas filtros, muestran lo filtrado; si seleccionas un dato en una tabla, se actualizan según esa selección.
* Si no hay datos disponibles, los paneles no se mostrarán.

***

#### 7. 🕒 Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados            |
| ------- | ---------- | ------------- | ----------------------------- |
| **1.0** | 01/12/2025 | Karol Navia   | Documento inicial.            |
| 1.1     | 10/12/2025 | Ronald Peláez | Agregar hoja de análisis      |
| 1.2     | 29/01/2026 | Karol Navia   | Agregar PEP y Autoexclusiones |
