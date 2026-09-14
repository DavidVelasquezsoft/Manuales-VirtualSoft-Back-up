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

Este dashboard consta de tres pestañas: **General**, **Comparación** y **Detalle histórico**. Las pestañas **General** y **Comparación** contienen los mismos KPI. La pestaña **Detalle histórico** no incluye KPI.

#### 4.1 kips&#x20;

<table><thead><tr><th width="176">Nombre</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Depósitos</code></strong></td><td>Monto total de los depósitos realizados en el ralgo de fechas consultado.</td></tr><tr><td><strong><code>Cantidad depósitos</code></strong></td><td>Cantidad total de depósitos realizados en el rango de fechas consultado.</td></tr><tr><td><strong><code>Valor promedio depósitos</code></strong></td><td>Valor promedio de depósitos correspondientes al valor total de depósitos realizados.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Monto total de los retiros realizados en el rango de fechas consultado.</td></tr><tr><td><strong><code>Cantidad retiros</code></strong></td><td>Cantidad total de retiros realizados en el rango de fechas consultado.</td></tr><tr><td><strong><code>Valor promedio retiros</code></strong></td><td>Valor promedio de retiros correspondientes al valor total de retiros realizados.</td></tr></tbody></table>

{% tabs %}
{% tab title="General" %}
La pestaña **General** presenta un resumen de los depósitos y retiros realizados por los puntos de venta. La información se puede consultar en dos modos, seleccionables desde la esquina superior derecha: **Gráficas** y **Detalle**.

{% tabs %}
{% tab title="Gráficas" %}
Visualiza la información correspondiente a los depósitos, retiros y puntos de venta con ayuda de gráficos.

***

#### Visualización

<figure><img src="../../../.gitbook/assets/image (246).png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Detalle" %}
La vista Detalle se complementa de una tabla con la información de los depósitos y los retiros.

***

#### Visualización

<figure><img src="../../../.gitbook/assets/vsft ecuabet.jpg" alt=""><figcaption></figcaption></figure>

***

<table><thead><tr><th width="163">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Usuario</code></strong></td><td></td></tr><tr><td><strong><code>Nombre punto venta</code></strong></td><td></td></tr><tr><td><strong><code>Depósito</code></strong></td><td></td></tr><tr><td><strong><code>Retiros</code></strong></td><td></td></tr><tr><td><strong><code>Coincidencia TRX</code></strong></td><td></td></tr></tbody></table>
{% endtab %}
{% endtabs %}

.
{% endtab %}

{% tab title="Comparación" %}
.

<figure><img src="../../../.gitbook/assets/image (248).png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Detalle histórico" %}
.

{% tabs %}
{% tab title="Gráficas" %}
Visualiza la información correspondiente a los depósitos, retiros y puntos de venta con ayuda de gráficos.

***

#### Visualización

<figure><img src="../../../.gitbook/assets/image (250).png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Retiros" %}
La vista Detalle se complementa de una tabla con la información de los depósitos y los retiros.

***

#### Visualización

<figure><img src="../../../.gitbook/assets/image (251).png" alt=""><figcaption></figcaption></figure>

***

<table><thead><tr><th width="163">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Usuario</code></strong></td><td></td></tr><tr><td><strong><code>Nombre punto venta</code></strong></td><td></td></tr><tr><td><strong><code>Depósito</code></strong></td><td></td></tr><tr><td><strong><code>Retiros</code></strong></td><td></td></tr><tr><td><strong><code>Coincidencia TRX</code></strong></td><td></td></tr></tbody></table>


{% endtab %}
{% endtabs %}

.
{% endtab %}
{% endtabs %}



***



### 5. Validaciones y reglas del negocio

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="106.77777099609375">Versión</th><th width="112.444580078125">Fecha</th><th width="160.44439697265625">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21/08/2026</td><td>Ronald Peláez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33122">Documento inicial</a></td></tr></tbody></table>

</details>

