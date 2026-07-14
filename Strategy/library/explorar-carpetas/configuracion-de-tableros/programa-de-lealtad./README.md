# Programa de lealtad.

Este manual describe el funcionamiento del dashboard del Programa de Lealtad en Strategy, orientado a la visualización y análisis del comportamiento de puntos, redenciones, usuarios activos y regalos, facilitando la toma de decisiones operativas y gerenciales.

***

### 1. Acceso al Módulo

**Ruta de acceso:**\
Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales

***

### **2. Configuraciones Previas**

Antes de visualizar el reporte, es necesario establecer las [configuraciones previas.](https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-1.-configuraciones-previas)

***

### 3. Filtros Disponibles

{% hint style="warning" %}
**Nota:** Los filtros de fecha definen el alcance temporal de todos los gráficos y tablas del tablero.
{% endhint %}

<table><thead><tr><th width="89.66668701171875">Filtro</th><th width="126.33331298828125">Tipo de control</th><th width="514">Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra la información por operador o marca. </td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite visualizar la información por país. </td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Establece el rango de fechas con el que se generará el reporte</td></tr><tr><td><strong><code>Año</code></strong></td><td>Lista desplegable</td><td>Filtra la información correspondiente a un año específico.</td></tr><tr><td><strong><code>Mes</code></strong></td><td>Lista desplegable</td><td>Permite filtrar la información correspondiente a un mes específico dentro del año seleccionado.</td></tr><tr><td><strong><code>Día</code></strong></td><td>Lista desplegable</td><td>Filtra la información correspondiente a un día específico, según el rango o mes seleccionado.</td></tr><tr><td><strong><code>Id usuario</code></strong></td><td>Texto</td><td><p>buscar un usuario específico mediante su identificador. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> este filtro solo está disponible en la vista <strong>Puntos Calificables</strong>.</p></div></td></tr></tbody></table>

***

### 4. Componentes del Dashboard

Este Dashboard cuenta con diferentes  vistas de información estas son:

{% tabs %}
{% tab title="Mensual" %}
{% hint style="warning" %}
**Nota:** Todos los indicadores, gráficos y tablas presentan información consolidada por mes, de acuerdo con los filtros aplicados.
{% endhint %}

#### KPI´s

<table><thead><tr><th width="180">Indicador (KPI)</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Puntos Activos</code></strong></td><td>Muestra la cantidad total de puntos de lealtad activos durante el período consultado.</td></tr><tr><td><strong><code>Puntos Redimidos</code></strong></td><td>Cantidad total de puntos de lealtad que han sido redimidos por los usuarios.</td></tr><tr><td><strong><code>Redimidos usuario</code></strong></td><td>Muestra la cantidad de usuarios que han realizado al menos una redención de puntos durante el período consultado.</td></tr><tr><td><strong><code>Puntos Expirados</code></strong></td><td>Cantidad total de puntos de lealtad que expiraron durante el período seleccionado.</td></tr></tbody></table>

***

### Gráficas

<table><thead><tr><th width="155.3333740234375">Gráfica</th><th width="112">Tipo de gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Puntos activos</code></strong></td><td>Barras</td><td>Análisis comparativo de los puntos activos obtenidos por vertical.</td></tr><tr><td><strong><code>Puntos redimidos</code></strong></td><td>Barras</td><td>Muestra la cantidad de puntos redimidos por mes, según el filtro aplicado.</td></tr><tr><td><strong><code>Puntos expirados</code></strong></td><td>Barras</td><td>Muestra la cantidad de puntos expirados, según el filtro aplicado.</td></tr><tr><td><strong><code>Activos - redimidos - Expirados</code></strong></td><td>Barras</td><td>Cantidad de puntos activos, redimidos y expirados, por el mes consultado .</td></tr><tr><td><strong><code>Clientes con puntos activos</code></strong></td><td>Barras</td><td><p>Presenta el número de usuarios únicos que poseen puntos activos en Casino, Deportivas y Total.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La información de este gráfico se muestra únicamente después de aplicar los filtros de <strong>Fecha, Partner y País</strong> en las <a href="./#id-2.-configuraciones-previas">configuraciones previas</a>.</p></div></td></tr><tr><td><strong><code>Clientes con puntos redimidos</code></strong></td><td>Barras</td><td>Muestra el número de usuarios únicos que han redimido puntos en Casino, Deportivas y Total.</td></tr><tr><td><strong><code>% vertical redimido</code></strong></td><td>Torta</td><td>Visualiza el porcentaje de puntos redimidos asociados a cada vertical.</td></tr><tr><td><strong><code>Top usuarios puntos gastados</code></strong></td><td>Barras</td><td>Ranking de los usuarios con la mayor cantidad de puntos de lealtad redimidos.</td></tr><tr><td><strong><code>Top usuarios con más compras</code></strong></td><td>Barras</td><td>Ranking de los usuarios con mayor cantidad de compras realizadas mediante el programa de lealtad.</td></tr><tr><td><strong><code>Usuarios con más puntos de lealtad acumulados</code></strong></td><td>Barras</td><td>Ranking de los usuarios con la mayor cantidad de puntos de lealtad acumulados.</td></tr></tbody></table>

***

### **Gráficos de Usuarios Destacados**

<table><thead><tr><th width="240">Gráfica</th><th width="126">Tipo de gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Top usuarios puntos gastados</code></strong></td><td>Barras</td><td>Ranking de usuarios ordenado por la mayor cantidad de puntos lealtad <a href="https://app.gitbook.com/o/QcwavWzh0dfIwPyknoIT/s/mbqa0WvDWam8G20QQoIZ/#redimido">redimidos</a>.</td></tr><tr><td><strong><code>Top usuarios con más puntos lealtad acumulados</code></strong></td><td>Barras</td><td>Ranking de usuarios con el mayor total de puntos de lealtad vigentes <em>(activos).</em></td></tr><tr><td><strong><code>Top usuarios con más compras</code></strong></td><td>Barras</td><td>Ranking de usuarios según el número de compras realizadas en la tienda de regalos.</td></tr></tbody></table>

***

#### Tablas de [Redenciones](https://virtualsoft.gitbook.io/untitled/glosario/#redimido)

* **Regalos redimidos casino.**

<table><thead><tr><th width="160">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Descripción lealtad</code></strong></td><td>Descripción del regalo redimido asociado a la vertical casino</td></tr><tr><td><strong><code>Cantidad</code></strong> </td><td>Cantidad de usuario que redimieron este regalo lealtad.</td></tr><tr><td><strong><code>% uso regalo casino</code></strong></td><td>Indica el porcentaje de usuarios que redimieron el regalo lealtad y lo utilizaron</td></tr></tbody></table>

* &#x20;**Regalos redimidos deportivas.**

<table><thead><tr><th width="160">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Descripción lealtad</code></strong></td><td>Descripción del regalo redimido asociado a la vertical deportivas</td></tr><tr><td><strong><code>Cantidad</code></strong> </td><td>Cantidad de usuario que redimieron este regalo lealtad.</td></tr><tr><td><strong><code>% uso regalo deportivas</code></strong></td><td>Indica el porcentaje de usuarios que redimieron el regalo lealtad y lo utilizaron</td></tr></tbody></table>

* **Detalle redenciones**

<table><thead><tr><th width="179">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Indica la fecha en la que se redimió el premio lealtad</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner en el que se redimieron los puntos.</td></tr><tr><td><strong><code>País</code></strong></td><td>País del usuario que realizó la redención.</td></tr><tr><td><strong><code>ID lealtad</code></strong></td><td>Identificador único del regalo redimido.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Descripción del regalo redimido por el usuario.</td></tr><tr><td><strong><code>ID Bono</code></strong></td><td>Identificador del bono asociado a la redención.</td></tr><tr><td><strong><code>Puntos requeridos</code></strong></td><td>Cantidad de puntos necesarios para redimir el regalo.</td></tr><tr><td><strong><code>Usuarios redimieron regalos</code></strong></td><td>Número de usuarios únicos que realizaron la redención de este regalo.</td></tr><tr><td><strong><code>Cantidad compras</code></strong></td><td>Cantidad de veces que se redimió el premio lealtad.</td></tr></tbody></table>
{% endtab %}

{% tab title="Diario" %}
{% hint style="warning" %}
**Nota:** Todos los indicadores, gráficos y tablas presentan información consolidada por día, de acuerdo con los filtros aplicados.
{% endhint %}

#### KPI´s

Los KPI se muestran en la parte superior del dashboard y presentan **indicadores generales** calculados sobre todos los movimientos en el programa de lealtad, **según los filtros aplicados**.

<table><thead><tr><th width="215.50006103515625">Indicador (KPI)</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>% Puntos Activos</code></strong></td><td>Indica el porcentaje de puntos activos respecto al total de puntos generados, calculado a partir de la relación entre los puntos activos, redimidos y expirados.</td></tr><tr><td><strong><code>% Redención puntos</code></strong></td><td>Mide el porcentaje de puntos acumulados que han sido efectivamente redimidos por los usuarios frente al total de puntos generados en el programa de lealtad.</td></tr><tr><td><strong><code>% Redención usuario</code></strong></td><td>Representa el porcentaje de usuarios que redimieron al menos un beneficio del programa de lealtad sobre el total de usuarios con puntos acumulados.</td></tr><tr><td><strong><code>% Expiración puntos</code></strong></td><td>Indica el porcentaje de puntos que expiraron sin ser utilizados por los usuarios dentro del periodo analizado.</td></tr></tbody></table>

### **Gráficos generales**

<table><thead><tr><th width="155.3333740234375">Gráfica</th><th width="112">Tipo de gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Puntos activos</code></strong></td><td>Barras</td><td>Análisis diario comparativo de los puntos activos obtenidos por vertical.</td></tr><tr><td><strong><code>Puntos redimidos</code></strong></td><td>Barras</td><td>Muestra la cantidad de puntos redimidos por día, según el filtro aplicado.</td></tr><tr><td><strong><code>Puntos expirados</code></strong></td><td>Barras</td><td>Muestra la cantidad de puntos expirados, según el filtro aplicado.</td></tr><tr><td><strong><code>Activos - redimidos - Expirados</code></strong></td><td>Barras</td><td>Cantidad de puntos activos, redimidos y expirados, por dia.</td></tr><tr><td><strong><code>Clientes con puntos activos</code></strong></td><td>Barras</td><td><p>Presenta el número de usuarios únicos que poseen puntos activos en Casino, Deportivas y Total.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La información de este gráfico se muestra únicamente después de aplicar los filtros de <strong>Fecha, Partner y País</strong> en las <a href="./#id-2.-configuraciones-previas">configuraciones previas</a>.</p></div></td></tr><tr><td><strong><code>Clientes con puntos redimidos</code></strong></td><td>Barras</td><td>Muestra el número de usuarios únicos que han redimido puntos en Casino, Deportivas y Total.</td></tr><tr><td><strong><code>% vertical redimido</code></strong></td><td>Torta</td><td>Visualiza el porcentaje de puntos redimidos asociados a cada vertical.</td></tr><tr><td><strong><code>Top usuarios puntos gastados</code></strong></td><td>Barras</td><td>Ranking de los usuarios con la mayor cantidad de puntos de lealtad redimidos.</td></tr><tr><td><strong><code>Top usuarios con más compras</code></strong></td><td>Barras</td><td>Ranking de los usuarios con mayor cantidad de compras realizadas mediante el programa de lealtad.</td></tr><tr><td><strong><code>Usuarios con más puntos de lealtad acumulados</code></strong></td><td>Barras</td><td>Ranking de los usuarios con la mayor cantidad de puntos de lealtad acumulados.</td></tr></tbody></table>

***

#### **Gráficos de Usuarios Destacados**

<table><thead><tr><th width="240">Gráfica</th><th width="126">Tipo de gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Top usuarios puntos gastados</code></strong></td><td>Barras</td><td>Ranking de usuarios ordenado por la mayor cantidad de puntos lealtad <a href="https://app.gitbook.com/o/QcwavWzh0dfIwPyknoIT/s/mbqa0WvDWam8G20QQoIZ/#redimido">redimidos</a>.</td></tr><tr><td><strong><code>Top usuarios con más puntos lealtad acumulados</code></strong></td><td>Barras</td><td>Ranking de usuarios con el mayor total de puntos de lealtad vigentes <em>(activos).</em></td></tr><tr><td><strong><code>Top usuarios con más compras</code></strong></td><td>Barras</td><td>Ranking de usuarios según el número de compras realizadas en la tienda de regalos.</td></tr></tbody></table>

***

#### Tablas de [Redenciones](https://virtualsoft.gitbook.io/untitled/glosario/#redimido)

* **Regalos redimidos casino.**

<table><thead><tr><th width="160">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Descripción lealtad</code></strong></td><td>Descripción del regalo redimido asociado a la vertical casino</td></tr><tr><td><strong><code>Cantidad</code></strong> </td><td>Cantidad de usuario que redimieron este regalo lealtad.</td></tr><tr><td><strong><code>% uso regalo casino</code></strong></td><td>Indica el porcentaje de usuarios que redimieron el regalo lealtad y lo utilizaron</td></tr></tbody></table>

* &#x20;**Regalos redimidos deportivas.**

<table><thead><tr><th width="160">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Descripción lealtad</code></strong></td><td>Descripción del regalo redimido asociado a la vertical deportivas</td></tr><tr><td><strong><code>Cantidad</code></strong> </td><td>Cantidad de usuario que redimieron este regalo lealtad.</td></tr><tr><td><strong><code>% uso regalo deportivas</code></strong></td><td>Indica el porcentaje de usuarios que redimieron el regalo lealtad y lo utilizaron</td></tr></tbody></table>

* **Detalle redenciones**

<table><thead><tr><th width="179">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Indica la fecha en la que se redimió el premio lealtad</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner en el que se redimieron los puntos.</td></tr><tr><td><strong><code>País</code></strong></td><td>País del usuario que realizó la redención.</td></tr><tr><td><strong><code>ID lealtad</code></strong></td><td>Identificador único del regalo redimido.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Descripción del regalo redimido por el usuario.</td></tr><tr><td><strong><code>ID Bono</code></strong></td><td>Identificador del bono asociado a la redención.</td></tr><tr><td><strong><code>Puntos requeridos</code></strong></td><td>Cantidad de puntos necesarios para redimir el regalo.</td></tr><tr><td><strong><code>Usuarios redimieron regalos</code></strong></td><td>Número de usuarios únicos que realizaron la redención de este regalo.</td></tr><tr><td><strong><code>Cantidad compras</code></strong></td><td>Cantidad de veces que se redimió el premio lealtad.</td></tr></tbody></table>
{% endtab %}

{% tab title="Puntos calificables" %}
La sección de Puntos calificables se encuentra dividida en cuatro vistas, cada una con información específica para el análisis y seguimiento del programa de lealtad.

{% tabs %}
{% tab title="General" %}


> **Nota:** La información de las tablas y la gráfica se actualiza de acuerdo con los filtros aplicados en el dashboard.

### Tablas

* **Visualización General del Programa de Niveles**

<table><thead><tr><th width="185">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner al que pertenece la información.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al programa de lealtad.</td></tr><tr><td><strong><code>Nivel Lealtad</code></strong></td><td>Nivel de lealtad configurado dentro del programa.</td></tr><tr><td><strong><code>Cantidad usuario General</code></strong></td><td>Cantidad de usuarios asociados a cada nivel de lealtad.</td></tr><tr><td><strong><code>Valor Puntos Lealtad Calificable</code></strong></td><td>Total de puntos calificables acumulados por cada nivel de lealtad.</td></tr></tbody></table>

* **Detalle Programa de Niveles**

<table><thead><tr><th width="209">Campo</th><th>Descripcion</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner al que pertenece el registro.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al usuario.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario.</td></tr><tr><td><strong><code>Nivel Lealtad</code></strong></td><td>Nivel de lealtad asignado al usuario.</td></tr><tr><td><strong><code>Valor Requerido Nivel Actual</code></strong></td><td>Cantidad de puntos requerida para el nivel de lealtad actual.</td></tr><tr><td><strong><code>Valor requerido siguiente nivel</code></strong></td><td>Cantidad de puntos necesaria para alcanzar el siguiente nivel de lealtad.</td></tr><tr><td><strong><code>Valor Puntos Lealtad Calificable</code></strong></td><td>Cantidad de puntos calificables acumulados por el usuario.</td></tr></tbody></table>

### Gráfica

<table><thead><tr><th width="210">Gráfica</th><th width="121">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tendencia valor punto calificable por nivel</code></strong></td><td>Gráfica de líneas</td><td>Comportamiento del valor de los puntos calificables para cada nivel de lealtad configurado.</td></tr></tbody></table>
{% endtab %}

{% tab title="Movimiento" %}


### Filtros

| **Campo**           | **Tipo**           | **Descripción**                                                                   |
| ------------------- | ------------------ | --------------------------------------------------------------------------------- |
| **Desde**           | Selector de fecha  | Fecha inicial utilizada para consultar los movimientos de puntos calificables.    |
| **Hasta**           | Selector de fecha  | Fecha final utilizada para consultar los movimientos de puntos calificables.      |
| **Tipo Movimiento** | Botón de selección | Tipo de movimiento a consultar (**Todos**, **Entrada** o **Salida**).             |
| **Movimiento**      | Lista desplegable  | Movimiento específico de puntos calificables utilizado como criterio de búsqueda. |

***

### Tabla: Historial Movimientos Punt Calificable

| **Campo**                                       | **Descripción**                                                           |
| ----------------------------------------------- | ------------------------------------------------------------------------- |
| **Partner**                                     | Nombre del partner al que pertenece el registro.                          |
| **País**                                        | País asociado al registro.                                                |
| **Fecha**                                       | Fecha en la que se registró el movimiento de puntos calificables.         |
| **ID Usuario**                                  | Identificador único del usuario.                                          |
| **ID Externo**                                  | Identificador externo asociado al movimiento.                             |
| **Tipo Movimiento Lealtad Calificable**         | Tipo de movimiento registrado (**Entrada** o **Salida**).                 |
| **Movimiento Lealtad Calificable**              | Motivo o concepto asociado al movimiento de puntos calificables.          |
| **Valor Movimiento Puntos Lealtad Calificable** | Cantidad de puntos calificables correspondiente al movimiento registrado. |

> **Nota:** La información mostrada en esta vista se actualiza de acuerdo con los filtros seleccionados (**Fecha**, **Tipo de movimiento** y **Movimiento**).
{% endtab %}

{% tab title="Ciclos" %}
<br>

> **Nota:** La información de la gráfica y la tabla corresponde a los ciclos de puntos calificables y se actualiza de acuerdo con los filtros seleccionados en el dashboard.&#x20;

### Gráfica

* Visualización de Expiración de Puntos Calificables

**Tipo de gráfica:**&#x20;

<table><thead><tr><th width="193">Gráfica</th><th width="93">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Visualización de Expiración de Puntos Calificables</code></strong></td><td>Barras</td><td>Comparativo del valor de los puntos calificables por ciclo, clasificados según su estado (<strong>Activos</strong> o <strong>Expirados</strong>).</td></tr></tbody></table>

***

### Tabla:&#x20;

* Detalle Ciclos

<table><thead><tr><th width="189">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner al que pertenece el registro.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al registro.</td></tr><tr><td><strong><code>ID Ciclo</code></strong></td><td>Identificador único del ciclo de lealtad.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario.</td></tr><tr><td><strong><code>Estado Ciclo Lealtad Calificable</code></strong></td><td>Estado actual del ciclo de lealtad (<strong>Activo</strong> o <strong>Expirado</strong>).</td></tr><tr><td><strong><code>Duración Ciclo Lealtad Calificable</code></strong></td><td>Tiempo de vigencia configurado para el ciclo de puntos calificables.</td></tr><tr><td><strong><code>Valor Puntos por Ciclos</code></strong></td><td>Cantidad de puntos calificables acumulados dentro del ciclo correspondiente.</td></tr></tbody></table>
{% endtab %}

{% tab title="Evolución" %}
<br>

{% tabs %}
{% tab title="Evolución" %}

{% endtab %}

{% tab title="Detalle Evolución" %}

{% endtab %}
{% endtabs %}

<br>
{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}







#### .✅ Validaciones y Reglas de Negocio

* El tablero está disponible únicamente para usuarios con permisos autorizados.
* La información presentada depende directamente de los filtros aplicados.

***

### 7.🕛 Control de Versiones

| Versión | Fecha      | Autor          | Cambios Realizados                                    |
| ------- | ---------- | -------------- | ----------------------------------------------------- |
| 1.0     | 18/12/2025 | Ronald Peláez  | Documento inicial                                     |
| 2.0     | 19/01/2026 | Ronald Peláez  | Reestructuración de manual por cambio en el dashboard |
