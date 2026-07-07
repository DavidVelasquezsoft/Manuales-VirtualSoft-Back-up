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

# Conciliación de Ventas

Este dashboard permite realizar la conciliación diaria entre el **Histórico de Saldos de Punto de Venta&#x20;**_**(H.S)**_ y el **Flujo de Caja Resumido&#x20;**_**(F.C)**_, mostrando de forma comparativa los valores por concepto y su respectivo desfase.

Su finalidad es validar que las ventas registradas impacten correctamente los saldos de los puntos de venta a nivel de **Fecha, Partner y País.**

{% hint style="warning" %}
**Nota**: El dashboard es exclusivamente de monitoreo y no permite edición de información.
{% endhint %}

***

### 1. Acceso al Módulo

**Ruta de acceso:**<br>

***

### 2. 🖼️Visualización

<figure><img src="../../../.gitbook/assets/image (9) (1).png" alt=""><figcaption><p>Figura #1: captura de pantalla conciliación de ventas</p></figcaption></figure>

### 3. Acciones del Usuario

<table><thead><tr><th width="256">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/conciliacion-de-ventas#id-4.-filtros-disponibles"><strong>Aplicar filtros</strong></a></td><td>Permite segmentar la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</td></tr><tr><td><strong>Analizar desfases</strong></td><td>Identifica diferencias mediante los valores resaltados en rojo y valida los montos que no coinciden.</td></tr><tr><td><strong>Consultar detalle</strong></td><td>Revisa la sección “Desface Detalle” para profundizar en los conceptos que presentan variaciones.</td></tr><tr><td><strong>Realizar validación operativa</strong></td><td>Contrasta la información con los reportes de Backoffice cuando se detecten diferencias.</td></tr></tbody></table>

***

#### 3.1. Filtros Disponibles

El panel izquierdo permite aplicar los siguientes filtros:

<table><thead><tr><th width="222">Filtro</th><th width="133">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra el dashboard por un partner en específico.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente los registros del país elegido.</td></tr><tr><td><strong><code>Fecha </code></strong><em><strong><code>(Desde / Hasta)</code></strong></em></td><td>Calendario</td><td>Define el rango de fechas sobre se visualizará la información en el dashboard.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista despegable</td><td>Filtra registros que coinciden o presentan diferencia.</td></tr></tbody></table>

### 4. Contenido del dashboard

#### 4.1. Histórico Saldo Punto de Venta vs Flujo Caja Resumido

La tabla muestra, por cada combinación de Fecha, Partner y País, los valores comparados entre **Histórico de Saldos de Punto de Venta** _**(H.S)**_ y **Flujo de Caja Resumido&#x20;**_**(F.C)**_ para cada concepto conciliado.

<table><thead><tr><th width="214">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha correspondiente al registro conciliado.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado al reporte.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al partner del reporte.</td></tr><tr><td><strong><code>Depósitos H.S</code></strong></td><td>Valor de depósitos según Histórico de Saldos punto de venta.</td></tr><tr><td><strong><code>Depósitos F.C</code></strong></td><td>Valor de depósitos según Flujo de Caja Resumido.</td></tr><tr><td><strong><code>Desface Depósitos</code></strong></td><td>Diferencia entre Depósitos <strong>H.S</strong> y Depósitos <strong>F.C</strong>.</td></tr><tr><td><strong><code>Apuestas Creadas H.S</code></strong></td><td>Valor de apuestas creadas según Histórico de Saldos punto de venta <em><strong>(H.S)</strong></em>.</td></tr><tr><td><strong><code>Apuestas Creadas F.C</code></strong></td><td>Valor de apuestas creadas según Flujo de Caja Resumido <em><strong>(F.C)</strong></em>.</td></tr><tr><td><strong><code>Desface Apuestas D.</code></strong></td><td>Diferencia entre Apuestas deportivas Creadas <strong>H.S</strong> y <strong>F.C.</strong></td></tr><tr><td><strong><code>Premios Deportivos H.S</code></strong></td><td>Valor de premios deportivos según Histórico de Saldos.</td></tr><tr><td><strong><code>Premios Deportivos F.C</code></strong></td><td>Valor de premios deportivos según Flujo de Caja Resumido.</td></tr><tr><td><strong><code>Desface Premios D.</code></strong></td><td>Diferencia entre Premios Deportivos <strong>H.S</strong> y <strong>F.C</strong>.</td></tr><tr><td><strong><code>Retiros Pagados H.S</code></strong></td><td>Valor de retiros según Histórico de Saldos.</td></tr><tr><td><strong><code>Retiros Pagados F.C</code></strong></td><td>Valor de retiros según Flujo de Caja Resumido.</td></tr><tr><td><strong><code>Desface Retiros</code></strong></td><td>Diferencia entre Retiros <strong>H.S</strong> y <strong>F.C</strong>.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Resultado de la conciliación según el desfase calculado <em>(Coincide / No coincide).</em></td></tr></tbody></table>

Cada fila representa el resultado consolidado por Fecha, Partner y País.

***

#### 4.2. Desface Detalle

Esta tabla contiene información más detallada sobre los desfaces reportados.

<table><thead><tr><th width="235">Columnas</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha correspondiente al registro conciliado.</td></tr><tr><td><strong><code>Desface Depósitos</code></strong></td><td>Diferencia entre Depósitos <strong>H.S</strong> y Depósitos <strong>F.C</strong> para la fecha indicada.</td></tr><tr><td><strong><code>Desface Apuestas D.</code></strong></td><td>Diferencia entre Apuestas deportivas Creadas <strong>H.S</strong> y <strong>F.C</strong> para la fecha indicada.</td></tr><tr><td><strong><code>Desface Premios D.</code></strong></td><td>Diferencia entre Premios Deportivos <strong>H.S</strong> y <strong>F.C</strong> para la fecha indicada.</td></tr><tr><td><strong><code>Desface Retiros</code></strong></td><td>Diferencia entre Retiros <strong>H.S</strong> y Retiros <strong>F.C</strong> para la fecha indicada.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Resultado consolidado de la fecha según los desfases calculados <em>(Coincide / No coincide).</em></td></tr></tbody></table>

***

### 5. Documentación relacionada

* La información sobre el flujo de caja está disponible desde el BackOffice en el siguiente módulo:

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/flujo-de-caja-resumido" %}
[Flujo de Caja Resumido](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/flujo-de-caja-resumido)
{% endcontent-ref %}

* La información sobre el histórico de saldo punto de venta está disponible desde el BackOffice en el siguiente módulo:

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/historico-saldos-punto-de-venta" %}
[Histórico saldos punto de venta](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/historico-saldos-punto-de-venta)
{% endcontent-ref %}

***

### 6. ✅Reglas y validaciones.

* Si el resultado es **0**, los valores coinciden, en caso de ser distinto, no coinciden.
* El desfase puede mostrarse con signo positivo o negativo.
* Los valores menores a cero visualizan en **color rojo**.
* Registros sin movimiento o con valores en cero se consideran conciliados.
* La información de la tabla se actualiza dinámicamente según los filtros seleccionados.

***

### 7.🕛 Control de Versiones

<table><thead><tr><th width="98">Versión</th><th width="133">Fecha</th><th width="148">Autor</th><th>Cambios</th></tr></thead><tbody><tr><td>1.0</td><td>27/02/2026</td><td>Ronald Peláez</td><td>Documento inicial</td></tr></tbody></table>
