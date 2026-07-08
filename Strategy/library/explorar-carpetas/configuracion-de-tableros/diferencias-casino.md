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

# Diferencias Casino

<mark style="color:$info;">Este dashboard centraliza y presenta de forma más clara, rápida y directa la información del proceso de</mark> [<mark style="color:$info;">conciliación de saldos</mark>](https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros/conciliacion-de-saldos)<mark style="color:$info;">. Su objetivo es facilitar la identificación de diferencias entre los valores registrados en las apuestas realizadas por los usuarios y el histórico de saldos del usuario, permitiendo visualizar de manera inmediata cualquier inconsistencia detectada durante la conciliación.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Diferencias Casino

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (214).png" alt=""><figcaption><p>Figura #1: Captura de pantalla dashboard transferencia de saldo.</p></figcaption></figure>

***

### 3. Filtros

<table><thead><tr><th width="121">Campo</th><th width="619">Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong> </td><td>Rango de fechas en las que se visualizarán los reportes de diferencias casino</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado a la diferencia reportada</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado a la diferencia reportada</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Id del usuario al que pertenece la diferencia</td></tr></tbody></table>

***

### 4. Contenido del dashboard

#### 4.1. Indicadores

Los indicadores muestran información resumida de acuerdo con los filtros seleccionados.

<table><thead><tr><th width="159.5999755859375">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Diferencia Apuesta</code></strong></td><td>Valor total de diferencias de apuestas realizadas.</td></tr><tr><td><strong><code>Diferencia premios</code></strong></td><td>Valor total de diferencias reportadas en premios.</td></tr></tbody></table>

#### 4.2. Tablas

<table><thead><tr><th width="128">Campo</th><th width="617.4000244140625">Descripción</th></tr></thead><tbody><tr><td><strong><code>Diferencia apuesta</code></strong></td><td>Visualiza el reporte de las diferencias de apuestas casino reportadas con el reporte de histórico de saldos.</td></tr></tbody></table>

{% columns %}
{% column width="16.666666666666664%" %}





{% endcolumn %}

{% column width="83.33333333333334%" %}
<table><thead><tr><th width="125">Columna</th><th width="438.671875">Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se generó el reporte de la diferencia.</td></tr><tr><td><strong><code>Parner</code></strong></td><td>Partner asociado a la diferencia.</td></tr><tr><td><strong><code>País</code></strong></td><td>País en el cual se generó la diferencia.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador único del usuario correspondiente a la diferencia reportada.</td></tr><tr><td><strong><code>Apuesta Casino</code></strong></td><td>Valor de apuesta realizada por el usuario en casino</td></tr><tr><td><strong><code>Apuesta Casino H</code></strong></td><td>Valor reportado en el histórico de saldo correspondiente a la apuesta.</td></tr><tr><td><strong><code>Diferencia Apuesta</code></strong></td><td>Diferencia correspondiente a el valor de la apuesta reportado y el histórico de saldos del usuario</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="128"></th><th></th></tr></thead><tbody><tr><td><strong><code>Diferencia Premio</code></strong></td><td>Visualiza el reporte de las diferencias de premios casino reportadas con el reporte de histórico de saldos.</td></tr></tbody></table>

{% columns %}
{% column width="16.666666666666664%" %}

{% endcolumn %}

{% column width="83.33333333333334%" %}
<table><thead><tr><th width="125">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se generó el reporte de la diferencia.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado a la diferencia.</td></tr><tr><td><strong><code>País</code></strong></td><td>País en el cual se generó la diferencia.</td></tr><tr><td><strong><code>Id usuario</code></strong></td><td>Identificador único del usuario correspondiente a la diferencia reportada.</td></tr><tr><td><strong><code>Premios casino</code></strong></td><td>Valor de apuesta realizada por el usuario en casino</td></tr><tr><td><strong><code>Premios Casino H</code></strong></td><td>Valor reportado en el histórico de saldo correspondiente a la apuesta.</td></tr><tr><td><strong><code>Diferencia premios</code></strong></td><td>Diferencia correspondiente a el valor de la apuesta reportado y el histórico de saldos del usuario</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

### 5. Validaciones y reglas del Negocio

*

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="108">Versión</th><th width="132">Fecha</th><th width="171">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>09/06/2026</td><td>Ronald Peláez</td><td>Creación inicial del manual</td></tr></tbody></table>

</details>
