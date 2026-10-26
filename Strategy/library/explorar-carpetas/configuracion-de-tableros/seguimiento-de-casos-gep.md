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

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Aplicar filtros</strong></td><td>Permite filtrar la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</td></tr><tr><td><strong>Visualizar contenido del tablero</strong></td><td>Visualiza el contenido del tablero, organizado en métricas principales y pestañas de análisis.</td></tr><tr><td><strong>Exportar contenido</strong></td><td>Permite exportar el contenido del tablero. Para más información, consulte la guía de <a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-3.2.-dashboard-completo">exportación</a>.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="150">Filtro</th><th width="123">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Creada</code></strong></td><td>Calendario</td><td></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td></td></tr><tr><td><strong><code>Categoría</code></strong></td><td>Lista desplegable</td><td></td></tr><tr><td><strong><code>Escalado a</code></strong></td><td>Lista desplegable</td><td></td></tr><tr><td><strong><code>Tipificaciones</code></strong></td><td>Lista desplegable</td><td></td></tr></tbody></table>

***

### 5. KPIs

El dashboard muestra un KPI el cuál es general, no cambia según la vista seleccionada.

<table><thead><tr><th width="205">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total de casos</code></strong></td><td>Valor total de todos los casos que se han enviado al GEP <em>(Gestión Equipo Plataformas)</em>.</td></tr></tbody></table>

***

### 6. Contenido del dashboard

El dashboard se compone de dos pestañas que permiten analizar la información desde diferentes perspectivas:

{% tabs %}
{% tab title="Análisis General" %}
Visualiza la información de los GEP mediante gráficas.

Visualización

<figure><img src="../../../.gitbook/assets/image (267).png" alt=""><figcaption></figcaption></figure>

Gráficos

<table><thead><tr><th width="134">Gráfico</th><th width="173">Tipo de gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Incidentes vs consultas</code></strong></td><td>Torta</td><td></td></tr><tr><td><strong><code>Distribución por categoría</code></strong> </td><td>Torta</td><td></td></tr><tr><td><strong><code>Distribución por estado</code></strong></td><td>Barras laterales</td><td></td></tr><tr><td><strong><code>Distribución por escalamiento</code></strong></td><td>Barras laterales</td><td></td></tr><tr><td><strong><code>Cantidad de casos por fecha</code></strong></td><td>Lineal</td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle de casos" %}
Presenta la información más detallada con la ayuda de una tabla

Visualización

<figure><img src="../../../.gitbook/assets/image (268).png" alt=""><figcaption></figcaption></figure>

Tabla

<table><thead><tr><th width="147">Column</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Clave</code></strong></td><td></td></tr><tr><td><strong><code>Resumen</code></strong></td><td></td></tr><tr><td><strong><code>Estado</code></strong></td><td></td></tr><tr><td><strong><code>Categoría</code></strong></td><td></td></tr><tr><td><strong><code>Tipificaciones</code></strong></td><td></td></tr><tr><td><strong><code>Escalado a</code></strong></td><td></td></tr><tr><td><strong><code>Creada</code></strong></td><td></td></tr><tr><td><strong><code>Fecha cierre</code></strong></td><td></td></tr><tr><td><strong><code>Comentario consulta</code></strong></td><td></td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 7. Validaciones y reglas del negocio

* Los indicadores y visualizaciones se actualizan de acuerdo con los filtros seleccionados en el dashboard.
* Todos los valores mostrados corresponden a la misma selección de filtros.
* Las métricas principales presentan la información de Retail, su participación porcentual frente al total y el resultado consolidado de la operación.
* Cuando una métrica no presenta resultados para la selección realizada, el valor se muestra como **0**.
* Las cantidades se presentan como números enteros, los valores monetarios utilizan el formato de moneda definido para el dashboard y los porcentajes incluyen el símbolo **%**.
* La información presentada en las métricas principales mantiene correspondencia con la información utilizada en los gráficos, rankings y tablas de detalle del dashboard.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="94.7037353515625">Versión</th><th width="133.25927734375">Fecha</th><th width="161.77777099609375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>05/10/2026</td><td>Ronald Peláez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33889#icft=VSFT-33889">Documento inicial.</a></td></tr></tbody></table>

</details>
