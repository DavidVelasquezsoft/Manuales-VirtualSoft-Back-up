# Programa de lealtad.

Este manual describe el funcionamiento del dashboard del Programa de Lealtad en Strategy, orientado a la visualización y análisis del comportamiento de puntos, redenciones, usuarios activos y regalos, facilitando la toma de decisiones operativas y gerenciales.

***

### 1. Acceso al Módulo

**Ruta de acceso:**\
Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales

***

### **2. Configuraciones Previas**

Antes de visualizar el reporte, es necesario establecer las [configuraciones previas.](https://virtualsoft.gitbook.io/manuales/microstrategy/tableros#id-2.-configuracion-previa)

***

### 3. Visualización General

<figure><img src="../../../.gitbook/assets/image (27) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla dashboard programa de lealtad.</p></figcaption></figure>

***

### 4. 🔍 Filtros Disponibles

<table><thead><tr><th width="89.66668701171875">Filtro</th><th width="126.33331298828125">Tipo de control</th><th width="514">Descripción</th></tr></thead><tbody><tr><td><strong><code>Mensual</code></strong></td><td>Botón</td><td>Establece si toda la información visualizada en el dashboard será de manera mensual.</td></tr><tr><td><strong><code>Diario</code></strong></td><td>Botón</td><td>Establece si toda la información visualizada en el dashboard será de manera diaria <em>(día a día)</em>.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra la información por operador o marca.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite visualizar la información por país.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Establece el rango de fechas con el que se generará el reporte</td></tr><tr><td><strong><code>Año</code></strong></td><td>Lista desplegable</td><td>Permite filtrar la información correspondiente a un año específico.</td></tr><tr><td><strong><code>Mes</code></strong></td><td>Lista desplegable</td><td>Permite filtrar la información correspondiente a un mes específico dentro del año seleccionado.</td></tr><tr><td><strong><code>Día</code></strong></td><td>Lista desplegable</td><td>Permite filtrar la información correspondiente a un día específico, según el rango o mes seleccionado.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Los filtros de fecha definen el alcance temporal de todos los gráficos y tablas del tablero.
{% endhint %}

***

### 5. Componentes del Dashboard

#### 5.1. KPI´s

Los KPI se muestran en la parte superior del dashboard y presentan **indicadores generales** calculados sobre todos los movimientos en el programa de lealtad, **según los filtros aplicados**.

<table><thead><tr><th width="309.50006103515625">Indicador (KPI)</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>% Puntos Activos</code></strong></td><td>Indica el porcentaje de puntos activos respecto al total de puntos generados, calculado a partir de la relación entre los puntos activos, redimidos y expirados.</td></tr><tr><td><strong><code>% Redención puntos</code></strong></td><td>Mide el porcentaje de puntos acumulados que han sido efectivamente redimidos por los usuarios frente al total de puntos generados en el programa de lealtad.</td></tr><tr><td><strong><code>% Redención usuario</code></strong></td><td>Representa el porcentaje de usuarios que redimieron al menos un beneficio del programa de lealtad sobre el total de usuarios con puntos acumulados.</td></tr><tr><td><strong><code>% Expiración puntos</code></strong></td><td>Indica el porcentaje de puntos que expiraron sin ser utilizados por los usuarios dentro del periodo analizado.</td></tr></tbody></table>

#### **5.2. Gráficos generales**

<table><thead><tr><th width="155.3333740234375">Gráfica</th><th width="112">Tipo de gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Puntos activos</code></strong></td><td>Barras</td><td>Análisis comparativo de los puntos activos obtenidos por vertical.</td></tr><tr><td><strong><code>Puntos redimidos</code></strong></td><td>Barras</td><td>Muestra la cantidad de puntos redimidos por mes o día, según el filtro aplicado.</td></tr><tr><td><strong><code>Puntos expirados</code></strong></td><td>Barras</td><td>Compara la cantidad de puntos expirados por mes o día, según el filtro aplicado.</td></tr><tr><td><strong><code>Activos - redimidos - Expirados</code></strong></td><td>Barras</td><td>Comparativa de la cantidad de puntos activos, redimidos y expirados.</td></tr><tr><td><strong><code>Clientes con puntos activos</code></strong></td><td>Barras</td><td><p>Presenta el número de usuarios únicos que poseen puntos activos en Casino, Deportivas y Total.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La información de este gráfico se muestra únicamente después de aplicar los filtros de <strong>Fecha, Partner y País</strong> en las <a href="programa-de-lealtad..md#id-2.-configuraciones-previas">configuraciones previas</a>.</p></div></td></tr><tr><td><strong><code>Clientes con puntos redimidos</code></strong></td><td>Barras</td><td>Muestra el número de usuarios únicos que han redimido puntos en Casino, Deportivas y Total.</td></tr><tr><td><strong><code>% vertical redimido</code></strong></td><td>Torta</td><td>Visualiza el porcentaje de puntos redimidos asociados a cada vertical.</td></tr></tbody></table>

***

#### **5.3 Gráficos de Usuarios Destacados**

<table><thead><tr><th width="240">Gráfica</th><th width="126">Tipo de gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Top usuarios puntos gastados</code></strong></td><td>Barras</td><td>Ranking de usuarios ordenado por la mayor cantidad de puntos lealtad <a href="https://app.gitbook.com/s/mbqa0WvDWam8G20QQoIZ/#redimido">redimidos</a>.</td></tr><tr><td><strong><code>Top usuarios con más puntos lealtad acumulados</code></strong></td><td>Barras</td><td>Ranking de usuarios con el mayor total de puntos de lealtad vigentes <em>(activos).</em></td></tr><tr><td><strong><code>Top usuarios con más compras</code></strong></td><td>Barras</td><td>Ranking de usuarios según el número de compras realizadas en la tienda de regalos.</td></tr></tbody></table>

***

#### 5.4. Tablas de [Redenciones](https://virtualsoft.gitbook.io/untitled/glosario/#redimido)

**5.4.1. Regalos redimidos casino.**

<table><thead><tr><th width="160">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Descripción lealtad</code></strong></td><td>Descripción del regalo redimido asociado a la vertical casino</td></tr><tr><td><strong><code>Cantidad</code></strong></td><td>Cantidad de usuario que redimieron este regalo lealtad.</td></tr><tr><td><strong><code>% uso regalo casino</code></strong></td><td>Indica el porcentaje de usuarios que redimieron el regalo lealtad y lo utilizaron</td></tr></tbody></table>

**5.4.2. Regalos redimidos deportivas.**

<table><thead><tr><th width="160">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Descripción lealtad</code></strong></td><td>Descripción del regalo redimido asociado a la vertical deportivas</td></tr><tr><td><strong><code>Cantidad</code></strong></td><td>Cantidad de usuario que redimieron este regalo lealtad.</td></tr><tr><td><strong><code>% uso regalo deportivas</code></strong></td><td>Indica el porcentaje de usuarios que redimieron el regalo lealtad y lo utilizaron</td></tr></tbody></table>

**5.4.3. Detalle redenciones**

<table><thead><tr><th width="179">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Indica la fecha en la que se redimió el premio lealtad</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner en el que se redimieron los puntos.</td></tr><tr><td><strong><code>País</code></strong></td><td>País del usuario que realizó la redención.</td></tr><tr><td><strong><code>ID lealtad</code></strong></td><td>Identificador único del regalo redimido.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Descripción del regalo redimido por el usuario.</td></tr><tr><td><strong><code>ID Bono</code></strong></td><td>Identificador del bono asociado a la redención.</td></tr><tr><td><strong><code>Puntos requeridos</code></strong></td><td>Cantidad de puntos necesarios para redimir el regalo.</td></tr><tr><td><strong><code>Usuarios redimieron regalos</code></strong></td><td>Número de usuarios únicos que realizaron la redención de este regalo.</td></tr><tr><td><strong><code>Cantidad compras</code></strong></td><td>Cantidad de veces que se redimió el premio lealtad.</td></tr></tbody></table>

***

### 6.✅ Validaciones y Reglas de Negocio

* El tablero está disponible únicamente para usuarios con permisos autorizados.
* La información presentada depende directamente de los filtros aplicados.

***

### 7.🕛 Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados                                    |
| ------- | ---------- | ------------- | ----------------------------------------------------- |
| 1.0     | 18/12/2025 | Ronald Peláez | Documento inicial                                     |
| 2.0     | 19/01/2026 | Ronald Peláez | Reestructuración de manual por cambio en el dashboard |
