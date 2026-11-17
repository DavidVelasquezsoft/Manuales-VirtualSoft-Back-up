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

***

### 6. Contenido del dashboard

El dashboard se compone de dos pestañas que permiten analizar la información de los casos registrados en el portal GEP mediante visualizaciones gráficas y una tabla de detalle.

{% hint style="warning" %}
**Nota**: Los casos identificados como **AR** no afectan en este tablero.
{% endhint %}

{% tabs %}
{% tab title="General PDV" %}
(mejorar esta descripción ) Visualiza información general del punto de venta filtrado con la ayuda de 3 pestañas (evolución, Detalle PDV, Tablas de detalle)

Visualización

<figure><img src="../../../.gitbook/assets/image (275).png" alt=""><figcaption><p>Figura #1: Captura de pantalla vista General PDV.</p></figcaption></figure>

KIP de esta pestaña (mejora este título)

<table><thead><tr><th width="165.33331298828125">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Recargas/retiros</code></strong></td><td>Comparación de total de recargas frente a los retiros realizados</td></tr></tbody></table>

cada pestaña segmenta la información del punto de venta&#x20;

{% tabs %}
{% tab title="Evolución" %}
(poner descripción relacionada al contexto de esta pestaña)

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

{% tab title="Detalle PDV" %}
(poner descripción relacionada al contexto de esta pestaña)
{% endtab %}

{% tab title="Tablas de detalle" %}
(poner descripción relacionada al contexto de esta pestaña)
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Estadísticas" %}

{% endtab %}

{% tab title="Afiliados" %}

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
