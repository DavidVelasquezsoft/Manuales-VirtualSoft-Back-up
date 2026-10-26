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

# Seguimiento de casos GEP

<mark style="color:$info;">Permite consultar, analizar y realizar seguimiento a los casos registrados para el equipo Gestión Equipo de Plataformas (GEP). Incluye búsquedas por fecha o rango de fechas, consulta del detalle de los casos y visualizaciones para analizar la distribución entre Incidentes y Consultas, así como su comportamiento según el estado, la categoría, la tipificación y el equipo al que fueron escalados.</mark>

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Seguimiento de casos GEP

***

### 2. Configuraciones previas

Antes de ingresar a este tablero, es necesario completar los filtros que se visualizarán durante las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-1.-configuraciones-previas).

***

### 3. Acciones disponibles

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros/seguimiento-de-casos-gep#id-4.-filtros"><strong>Aplicar filtros</strong></a></td><td>Permite filtrar la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros/seguimiento-de-casos-gep#id-6.-contenido-del-dashboard"><strong>Visualizar contenido del tablero</strong></a></td><td>Visualiza el contenido del tablero, organizado en métricas principales y pestañas de análisis.</td></tr><tr><td><strong>Exportar contenido</strong></td><td>Permite exportar el contenido del tablero. Para más información, consulte la guía de <a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-3.2.-dashboard-completo">exportación</a>.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="150">Filtro</th><th width="123">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Creada</code></strong></td><td>Calendario</td><td>Selecciona una fecha específica o un rango de fechas para consultar los casos según su fecha de creación en JIRA.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Consulta los casos según uno o varios estados registrados en JIRA.</td></tr><tr><td><strong><code>Categoría</code></strong></td><td>Lista desplegable</td><td>Consulta los casos según la categoría asignada en JIRA.</td></tr><tr><td><strong><code>Escalado a</code></strong></td><td>Lista desplegable</td><td>Consulta los casos según el equipo, área o responsable al que fueron escalados.</td></tr><tr><td><strong><code>Tipificaciones</code></strong></td><td>Lista desplegable</td><td>Consulta los casos según una o varias tipificaciones registradas.</td></tr></tbody></table>

***

### 5. KPIs

El dashboard presenta un indicador general con la cantidad de casos que cumplen los criterios de consulta seleccionados.

<table><thead><tr><th width="205">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total de casos</code></strong></td><td>Cantidad total de casos registrados en el portal GEP durante el período seleccionado y de acuerdo con los filtros aplicados. <em>(Excluye los casos identificados como AR)</em>.</td></tr></tbody></table>

***

### 6. Contenido del dashboard

El dashboard se compone de dos pestañas que permiten analizar la información de los casos registrados en el portal GEP mediante visualizaciones gráficas y una tabla de detalle.

{% tabs %}
{% tab title="Análisis General" %}
Presenta la distribución de los casos mediante gráficos que permiten analizar su clasificación, estado, categoría, tipificación y escalamiento, así como su comportamiento a lo largo del tiempo según la fecha de creación.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (267).png" alt=""><figcaption><p>Figura #1: Captura de pantalla pestaña Análisis general.</p></figcaption></figure>

Gráficos

<table><thead><tr><th width="134">Gráfico</th><th width="147">Tipo de gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Incidentes vs consultas</code></strong></td><td>Torta</td><td>Muestra la distribución de los casos clasificados como incidentes y consultas, según los filtros aplicados.</td></tr><tr><td><strong><code>Distribución por categoría</code></strong> </td><td>Torta</td><td>Presenta la distribución de los casos según la categoría registrada en JIRA.</td></tr><tr><td><strong><code>Distribución por estado</code></strong></td><td>Barras laterales</td><td>Muestra la cantidad de casos agrupados según su estado en JIRA.</td></tr><tr><td><strong><code>Distribución por escalamiento</code></strong></td><td>Barras laterales</td><td>Presenta la cantidad de casos agrupados según el equipo, área o responsable registrado en el campo de escalamiento.</td></tr><tr><td><strong><code>Cantidad de casos por fecha</code></strong></td><td>Lineal</td><td>Muestra la evolución de la cantidad de casos creados por fecha dentro del período consultado.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle de casos" %}
Presenta una tabla con los datos individuales de los casos que cumplen los criterios de consulta seleccionados, facilitando la revisión de su información, clasificación, estado y fechas asociadas.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (268).png" alt=""><figcaption><p>Figura #2: Captura de pantalla pestaña Detalle de casos.</p></figcaption></figure>

Tabla

<table><thead><tr><th width="147">Column</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Clave</code></strong></td><td>Identificador único del caso en JIRA.</td></tr><tr><td><strong><code>Resumen</code></strong></td><td>Título o descripción breve registrada para el caso.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del caso en JIRA.</td></tr><tr><td><strong><code>Categoría</code></strong></td><td>Categoría asignada al caso.</td></tr><tr><td><strong><code>Tipificaciones</code></strong></td><td>Tipificación registrada para el caso.</td></tr><tr><td><strong><code>Escalado a</code></strong></td><td>Equipo, área o responsable al cual fue escalado el caso.</td></tr><tr><td><strong><code>Creada</code></strong></td><td>Fecha y hora de creación del caso en JIRA <em>(Es la referencia temporal utilizada para determinar su inclusión en el período consultado)</em>.</td></tr><tr><td><strong><code>Fecha cierre</code></strong></td><td>Fecha y hora de cierre del caso <em>(Se presenta como información complementaria y no determina su inclusión en el período consultado)</em>.</td></tr><tr><td><strong><code>Comentario consulta</code></strong></td><td>Comentarios o información registrada en el caso relacionada con la consulta realizada.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 7. Validaciones y reglas del negocio

* Los filtros, indicadores, gráficos y tablas se actualizan de acuerdo con los criterios de consulta seleccionados.
* El campo Creada es la única referencia temporal para determinar los casos incluidos en una consulta. La fecha de cierre se presenta únicamente como información del caso.
* Los casos identificados como AR se excluyen permanentemente del dashboard, tanto de los indicadores y gráficos como de la tabla de detalle, independientemente de los filtros seleccionados.
* La información presentada corresponde a los casos registrados en JIRA asociados al portal GEP, aplicando las condiciones de fecha y exclusión definidas para el tablero.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="94.7037353515625">Versión</th><th width="133.25927734375">Fecha</th><th width="161.77777099609375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>05/10/2026</td><td>Ronald Peláez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-34283#icft=VSFT-34283">Documento inicial.</a></td></tr></tbody></table>

</details>
