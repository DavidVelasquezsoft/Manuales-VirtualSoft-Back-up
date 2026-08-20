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

# Dashboard Afiliados Interno

<mark style="color:$info;">Consulta y analiza la información relacionada con los afiliados, usuarios registrados, depósitos, apuestas, NGR y comisiones generadas durante el período seleccionado.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso:** Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Dashboard seguimiento del programa de lealtad

***

### 2. Configuraciones Previas

Antes de visualizar el reporte, establece las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-1.-configuraciones-previas) requeridas para la consulta.

***

### 3. Filtros

Los filtros generales permiten establecer el período que será consultado en el dashboard.

<table><thead><tr><th width="123.1817626953125">Campo</th><th width="94.181884765625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Desde</code></strong></td><td>Fecha</td><td>Establece la fecha inicial del período que será consultado.</td></tr><tr><td><strong><code>Hasta</code></strong></td><td>Fecha</td><td>Establece la fecha final del período que será consultado.</td></tr></tbody></table>

***

### 4. Contenido del Dashboard

La información del dashboard se encuentra organizada mediante las siguientes pestañas:

{% tabs %}
{% tab title="Detalle" %}
Presenta la información detallada del afiliador, sus links, códigos promocionales, registros, primeros depósitos, usuarios activos, NGR y comisiones.

#### Visualización :

<figure><img src="../../../.gitbook/assets/image (230).png" alt=""><figcaption><p>Figura #1: Captura de ejemplo del dashboard.</p></figcaption></figure>

#### **Filtros de consulta**

<table><thead><tr><th width="137.63641357421875">Campo</th><th width="118">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Afiliador</code></strong></td><td>Numérico </td><td>Consulta la información asociada a un afiliador específico.</td></tr><tr><td><strong><code>ID Link</code></strong></td><td>Texto</td><td>Consulta la información asociada a un link específico.</td></tr><tr><td><strong><code>Código promocional</code></strong></td><td>Numérico </td><td>Consulta la información relacionada con un código promocional específico.</td></tr></tbody></table>

#### **Indicadores**

<table><thead><tr><th width="147.54547119140625">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>NGR</code></strong></td><td>Presenta el valor correspondiente al NGR <em>(Ingreso Neto del Juego).</em></td></tr><tr><td><strong><code>Total Comisión</code></strong></td><td>Presenta el valor total de las comisiones generadas.</td></tr></tbody></table>

#### **Tabla de información**&#x20;

<table><thead><tr><th width="198.45458984375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Afiliador</code></strong></td><td>Identificador del afiliador.</td></tr><tr><td><strong><code>ID Link</code></strong></td><td>Identificador del link asociado al afiliador.</td></tr><tr><td><strong><code>Nombre o código promocional</code></strong></td><td>Nombre o código promocional asociado al registro.</td></tr><tr><td><strong><code>Cantidad de registros</code></strong></td><td>Cantidad de registros asociados al afiliador, link o código promocional consultado.</td></tr><tr><td><strong><code>Cantidad de primeros depósitos</code></strong></td><td>Cantidad de usuarios que realizaron su primer depósito.</td></tr><tr><td><strong><code>Valor de primeros depósitos</code></strong></td><td>Valor correspondiente a los primeros depósitos realizados.</td></tr><tr><td><strong><code>Valor de depósitos generales</code></strong></td><td>Valor correspondiente a los depósitos generales realizados por los usuarios asociados.</td></tr><tr><td><strong><code>Cantidad de usuarios activos</code></strong></td><td>Cantidad de usuarios activos asociados al afiliador.</td></tr><tr><td><strong><code>Sportsbook NGR afiliados</code></strong></td><td>NGR generado por los afiliados en la vertical Sportsbook.</td></tr><tr><td><strong><code>Casino NGR afiliados</code></strong></td><td>NGR generado por los afiliados en la vertical Casino.</td></tr><tr><td><strong><code>Total Comisión</code></strong></td><td>Valor total de la comisión correspondiente al registro.</td></tr></tbody></table>
{% endtab %}

{% tab title="General" %}
Presenta la información general de los afiliadores de acuerdo con el período seleccionado.

#### Visualización :

<figure><img src="../../../.gitbook/assets/image (232).png" alt=""><figcaption><p>Figura #2: Captura de ejemplo del dashboard.</p></figcaption></figure>

#### **Filtros de consulta**

<table><thead><tr><th width="129.8182373046875">Campo</th><th width="117.0909423828125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Afiliador</code></strong></td><td>Numérico</td><td>Consulta la información asociada a un Identificador de afiliador específico.</td></tr></tbody></table>

#### **Indicadores**

<table><thead><tr><th width="152.0909423828125">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>NGR</code></strong></td><td>Presenta el ingreso neto generado por la actividad de juego.</td></tr><tr><td><strong><code>Total Comisión</code></strong></td><td>Presenta el valor total de las comisiones generadas.</td></tr></tbody></table>

#### **Tabla de información**&#x20;

<table><thead><tr><th width="183.00006103515625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha correspondiente al registro consultado.</td></tr><tr><td><strong><code>ID Afiliador</code></strong></td><td>Identificador del afiliador.</td></tr><tr><td><strong><code>Cantidad de registros</code></strong></td><td>Cantidad de registros asociados al afiliador.</td></tr><tr><td><strong><code>Primeros depósitos</code></strong></td><td>Cantidad de primeros depósitos realizados por los usuarios asociados.</td></tr><tr><td><strong><code>Sportsbook NGR afiliados</code></strong></td><td>NGR generado por los afiliados en Sportsbook.</td></tr><tr><td><strong><code>Casino NGR afiliados</code></strong></td><td>NGR generado por los afiliados en Casino.</td></tr><tr><td><strong><code>NGR</code></strong></td><td>Ingreso neto generado por la actividad de juego.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Valor de la comisión correspondiente al afiliador.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle Usuarios" %}
Presenta la información de los usuarios registrados bajo un afiliador.

#### Visualización&#x20;

<figure><img src="../../../.gitbook/assets/image (235).png" alt=""><figcaption><p>Figura #3: Captura de ejemplo del dashboard.</p></figcaption></figure>

#### **Tabla de información**&#x20;

<table><thead><tr><th width="208.45458984375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador del usuario registrado.</td></tr><tr><td><strong><code>Fecha Registro</code></strong></td><td>Fecha en la que se realizó el registro del usuario.</td></tr><tr><td><strong><code>Fecha Primer Depósito</code></strong></td><td>Fecha en la que el usuario realizó su primer depósito.</td></tr><tr><td><strong><code>ID Afiliador</code></strong></td><td>Identificador del afiliador asociado al usuario.</td></tr><tr><td><strong><code>Código Promocional</code></strong></td><td>Código promocional utilizado durante el registro.</td></tr><tr><td><strong><code>Link Registro</code></strong></td><td>Link asociado al registro del usuario.</td></tr><tr><td><strong><code>Valor Primer Depósito</code></strong></td><td>Valor correspondiente al primer depósito realizado por el usuario.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle apuestas" %}
Presenta la información consolidada de las apuestas, premios, bonos y GGR generados por los afiliados en las verticales Sportsbook y Casino.

#### Visualización&#x20;

<figure><img src="../../../.gitbook/assets/image (236).png" alt=""><figcaption><p>Figura #4: Captura de ejemplo del dashboard.</p></figcaption></figure>

#### **Tabla de información**&#x20;

<table><thead><tr><th width="232.0909423828125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Afiliador</code></strong></td><td>Identificador del afiliador.</td></tr><tr><td><strong><code>Valor apuestas deportivas de afiliado</code></strong></td><td>Valor total apostado en deportes por los afiliados.</td></tr><tr><td><strong><code>Valor de premios en deportivas de afiliados</code></strong></td><td>Valor total de premios pagados en apuestas deportivas de los afiliados.</td></tr><tr><td><strong><code>Valor de bonos en deportivas de afiliados</code></strong></td><td>Valor total de bonos utilizados en apuestas deportivas de los afiliados.</td></tr><tr><td><strong><code>GGR en deportivas de afiliados</code></strong></td><td>GGR generado por las apuestas deportivas de los afiliados.</td></tr><tr><td><strong><code>Valor apuestas casino de afiliados</code></strong></td><td>Valor total apostado en Casino por los afiliados.</td></tr><tr><td><strong><code>Valor de premios en casino de afiliados</code></strong></td><td>Valor total de premios pagados en Casino a los afiliados.</td></tr><tr><td><strong><code>Valor de bonos en casino de afiliados</code></strong></td><td>Valor total de bonos utilizados en Casino por los afiliados.</td></tr><tr><td><strong><code>GGR en casino de afiliados</code></strong></td><td>GGR generado por las apuestas de Casino de los afiliados.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 5. Validaciones y reglas del negocio

* La información del dashboard corresponde al período definido mediante los filtros **Desde** y **Hasta**.
* Los indicadores y tablas presentan la información correspondiente a los filtros aplicados.
* Los valores de NGR y comisión se presentan de acuerdo con la información generada por los afiliados en el período consultado.

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="100.727294921875">Versión</th><th width="117.3636474609375">Fecha</th><th width="117.0908203125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>20/08/2026</td><td>Karol Navia</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-32318">Creación documento inicial</a></td></tr></tbody></table>

</details>
