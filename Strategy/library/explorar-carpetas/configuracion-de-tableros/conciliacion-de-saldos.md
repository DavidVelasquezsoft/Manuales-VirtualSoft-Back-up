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

# Conciliación de Saldos

Permite realizar la conciliación diaria entre el **Histórico de Saldos** y los diferentes reportes oficiales del BackOffice, consolidando la información por **Fecha, Partner, País y Moneda**.

Su finalidad es validar que los valores operativos registrados en base de datos coincidan con los reportes financieros y gerenciales, identificando diferencias por cada concepto conciliado.

{% hint style="warning" %}
**Nota**: El dashboard es exclusivamente de monitoreo y no permite edición de información.
{% endhint %}

***

### 1. Acceso al Módulo

**Ruta de acceso:**\
BackOffice > Inteligencia de Negocios > Conciliación de Saldos

***

### 2. 🖼️Visualización

<figure><img src="../../../.gitbook/assets/image (138) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla – Dashboard Conciliación de Saldos.</p></figcaption></figure>

***

### 3. Acciones del Usuario

<table><thead><tr><th width="206">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/conciliacion-de-saldos#id-4.-filtros-disponibles"><strong>Aplicar filtros</strong></a></td><td>Permite segmentar la información del dashboard según las necesidades filtradas.</td></tr><tr><td><strong>Analizar diferencias</strong></td><td>Identifica variaciones mediante las columnas de diferencia por cada concepto.</td></tr></tbody></table>

***

### 4. Filtros Disponibles

El panel izquierdo permite aplicar los siguientes filtros:

<table><thead><tr><th width="205">Filtro</th><th width="170">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra la información por un partner específico.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente los registros correspondientes al país seleccionado.</td></tr><tr><td><strong><code>Fecha (Desde / Hasta)</code></strong></td><td>Calendario</td><td>Define el rango de fechas sobre el cual se visualizará la conciliación.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite visualizar registros según su estado <em>(Coincide, No coincide)</em>.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: La información se actualiza dinámicamente según los filtros aplicados.
{% endhint %}

***

### 5. Detalle Saldos

<table><thead><tr><th width="274">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Día correspondiente al registro conciliado.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado a la operación.</td></tr><tr><td><strong><code>País</code></strong></td><td>País en el cual se ejecuta la operación conciliada.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda en la que se realiza la conciliación.</td></tr><tr><td><strong><code>Apuesta Deportiva Histórico</code></strong></td><td>Valor de apuestas deportivas registrado en el Histórico de Saldos.</td></tr><tr><td><strong><code>Apuesta Deportiva Gerencial</code></strong></td><td>Valor de apuestas deportivas según el Informe Gerencial.</td></tr><tr><td><strong><code>Diferencia Deportiva</code></strong></td><td>Diferencia entre Apuesta Deportiva Histórico y Apuesta Deportiva Gerencial.</td></tr><tr><td><strong><code>Premios Deportivos Histórico</code></strong></td><td>Valor de premios deportivos registrado en el Histórico de Saldos.</td></tr><tr><td><strong><code>Premios Deportivos Gerencial</code></strong></td><td>Valor de premios deportivos según el Informe Gerencial.</td></tr><tr><td><strong><code>Diferencia Premios Deportivos</code></strong></td><td>Diferencia entre Premios Deportivos Histórico y Gerencial.</td></tr><tr><td><strong><code>Bonos Deportivos Histórico</code></strong></td><td>Valor de bonos deportivos registrado en el Histórico de Saldos.</td></tr><tr><td><strong><code>Bonos Gerencial</code></strong></td><td>Valor de bonos deportivos según el Informe Gerencial.</td></tr><tr><td><strong><code>Diferencia Bonos</code></strong></td><td>Diferencia entre Bonos Deportivos Histórico y Bonos Gerencial.</td></tr><tr><td><strong><code>Depósitos Histórico</code></strong></td><td>Valor de depósitos según el Histórico de Saldos.</td></tr><tr><td><strong><code>Depósitos Flujo</code></strong></td><td>Valor de depósitos según el Flujo de Caja Resumido.</td></tr><tr><td><strong><code>Diferencia Depósitos</code></strong></td><td>Diferencia entre Depósitos Histórico y Depósitos Flujo.</td></tr><tr><td><strong><code>Retiros Histórico</code></strong></td><td>Valor de retiros registrado en el Histórico de Saldos.</td></tr><tr><td><strong><code>Retiros Flujo</code></strong></td><td>Valor de retiros según el Flujo de Caja Resumido.</td></tr><tr><td><strong><code>Retiros Flujo Pagados</code></strong></td><td>Valor de retiros pagados según el Flujo de Caja Resumido.</td></tr><tr><td><strong><code>Diferencia Retiros</code></strong></td><td>Diferencia entre Retiros Histórico y Retiros Flujo.</td></tr><tr><td><strong><code>Diferencia Retiros Pagados</code></strong></td><td>Diferencia entre Retiros Histórico y Retiros Flujo Pagados.</td></tr><tr><td><strong><code>Apuesta Casino Histórico</code></strong></td><td>Valor de apuestas de casino registrado en el Histórico de Saldos.</td></tr><tr><td><strong><code>Apuesta Casino</code></strong></td><td>Valor de apuestas de casino según el Reporte de Productos No Deportivos.</td></tr><tr><td><strong><code>Diferencia Apuesta Casino</code></strong></td><td>Diferencia entre Apuesta Casino Histórico y Apuesta Casino Reporte.</td></tr><tr><td><strong><code>Premios Casino Histórico</code></strong></td><td>Valor de premios de casino registrado en el Histórico de Saldos.</td></tr><tr><td><strong><code>Premios Casino</code></strong></td><td>Valor de premios de casino según el Reporte de Productos No Deportivos <em>(incluye Premios + Premios Bonos).</em></td></tr><tr><td><strong><code>Diferencia Premios Casino</code></strong></td><td>Diferencia entre Premios Casino Histórico y Premios Casino Reporte.</td></tr><tr><td><strong><code>Saldo Gratis Histórico</code></strong></td><td>Valor de saldo gratis registrado en el Histórico de Saldos.</td></tr><tr><td><strong><code>Saldo Gratis</code></strong></td><td>Valor de saldo gratis según el Reporte de Productos No Deportivos.</td></tr><tr><td><strong><code>Diferencia Saldo Gratis</code></strong></td><td>Diferencia entre Saldo Gratis Histórico y Saldo Gratis Reporte.</td></tr><tr><td><strong><code>Bonos Casino Histórico</code></strong></td><td>Valor de bonos de casino registrado en el Histórico de Saldos.</td></tr><tr><td><strong><code>Bono Casino</code></strong></td><td>Valor de bonos de casino según el Reporte de Productos No Deportivos.</td></tr><tr><td><strong><code>Diferencia Bono Casino</code></strong></td><td>Diferencia entre Bonos Casino Histórico y Bono Casino Reporte.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Resultado de la conciliación según las diferencias calculadas <em>(Coincide / Diferencia).</em></td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: Las columnas **`Fecha`**, **`Partner`**, **`País`**, **`Moneda`**, estarán fijadas en el dashboard
{% endhint %}

***

### 6. Documentación Relacionada

La validación de la información puede contrastarse con los siguientes módulos del BackOffice:

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/flujo-de-caja-resumido" %}
[Flujo de Caja Resumido](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/flujo-de-caja-resumido)
{% endcontent-ref %}

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/historico-de-saldos" %}
[Histórico de Saldos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/historico-de-saldos)
{% endcontent-ref %}

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/informe-gerencial" %}
[Informe Gerencial](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/informe-gerencial)
{% endcontent-ref %}

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos" %}
[Reporte productos no deportivos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos)
{% endcontent-ref %}

***

### 8. ✅Reglas y Validaciones

* Si la diferencia es **0**, los valores coinciden.
* Si la diferencia es distinta de **0**, existe variación.
* Los valores con diferencia se visualizan en **color rojo**.
* Los registros sin movimiento o con valores en cero se consideran conciliados automáticamente.
* No se realizan cruces entre distintos tipos de operación.
* El dashboard no permite edición de valores.
* La información se actualiza según los filtros seleccionados.

***

### 9.🕛 Control de Versiones

<table><thead><tr><th width="99">Versión</th><th width="123">Fecha</th><th width="144">Autor</th><th>Cambios</th></tr></thead><tbody><tr><td>1.0</td><td>04/03/2026</td><td>Ronald Peláez</td><td>Documento inicial</td></tr></tbody></table>
