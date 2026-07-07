---
description: >-
  Permite visualizar y analizar información de los desfases de saldo de los
  puntos de venta de manera detallada y resumida.
---

# Desfases puntos de venta

### **1. Acceso al Módulo**

**Ruta de Acceso:** Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales}

{% hint style="warning" %}
**Nota:** La ruta de acceso aplica para usuarios administrativos. Los usuarios con permisos podrán acceder al dashboard desde su **Library personal**, según el equipo y los accesos asignados.
{% endhint %}

***

### **2. Configuraciones Previas**

Antes de visualizar el reporte, es necesario definir las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/tableros#id-2.-configuracion-previa) obligatorias.

***

### 3. Vistas disponibles

Este reporte permite consultar la información en dos vistas: resumida y detallada.\
Mediante el **botón de cambio de vista**, el usuario puede alternar entre ambos modos de consulta de los desfases según su necesidad.

* [**Vista detallada**](desfases-puntos-de-venta.md#detallado)**:** muestra información mas detallada por punto de venta.
* [**Vista resumida**](desfases-puntos-de-venta.md#resumido)**:** muestra información acumulada agrupada por operación _(Partner y país_).

A continuación, se describe el funcionamiento de cada vista.

{% tabs fullWidth="false" %}
{% tab title="📈 Resumido" %}
#### 3.1. 🖼️ Visualización

<figure><img src="../../../.gitbook/assets/image (136).png" alt=""><figcaption><p>Figura #1: Captura de pantalla vista resumida reporte desfases puntos de venta</p></figcaption></figure>

#### 3.2. 🔍 Filtros Disponibles

<table><thead><tr><th width="159.99993896484375">Filtro</th><th width="127">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Calendario</td><td>Permite seleccionar un rango de fechas mediante un calendario para consultar información dentro de ese periodo.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>permite filtrar por un <a href="https://virtualsoft.gitbook.io/untitled/glosario/#partner">partner</a> en especifico.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el país en el que ocurrió el desfase.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Lista desplegable</td><td>Filtra por la moneda en la que opera la plataforma.</td></tr></tbody></table>

#### 3.3. KP&#x49;**´s**

Los KPI se muestran en la parte superior del dashboard y presentan **indicadores generales** calculados sobre todos las operaciones (_Partner / País_) consultadas.

<table><thead><tr><th width="159">Kpi</th><th>Descripción</th></tr></thead><tbody><tr><td><p></p><p><strong><code>Cantidad de puntos de venta con desfase</code></strong></p></td><td>Cantidad total de puntos de venta que presentan un desfase en el sistema, considerando todas las operaciones consultadas (<em>Partner / País</em>).</td></tr><tr><td><strong><code>Cantidad desfase operación</code></strong></td><td>Muestra la cantidad de desfases totales que tienen los puntos de venta en el periodo de tiempo seleccionado.</td></tr></tbody></table>

#### 3.4. Resultados de consulta

Permite visualizar una tabla con la información consolidada en formato **"resumido"**, actualizada dinámicamente en tiempo real según los filtros aplicados.

<table><thead><tr><th width="180">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Indica la fecha en que se registraron los desfase en el sistema para la plataforma y país correspondientes.</td></tr><tr><td><strong><code>Operación</code></strong></td><td>Indica el partner y el país en el que se registrarón los desfases.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda en la cual se registraron los desfases en la plataforma. </td></tr><tr><td><strong><code>Valor desfase</code></strong></td><td><p>Indica el valor acumulado de desfases por operación.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El valor se muestra en rojo cuando es distinto de cero y no se consolida entre monedas diferentes.</p></div></td></tr><tr><td><strong><code>Cantidad puntos de venta con desfase</code></strong></td><td>Muestra la cantidad de puntos de venta dentro de la operación que presentan desfase en esa fecha, operación y moneda.</td></tr></tbody></table>

> ⚠️**Nota:** Este es el reporte **Resumido**, para ver la documentación relacionada al reporte **Detallado** clic aquí 🔽

<p align="center"><a href="desfases-puntos-de-venta.md#detallado" class="button primary" data-icon="clipboard-list-check">Reporte detallado</a></p>
{% endtab %}

{% tab title="🗂️ Detallado" %}
#### 3.1. 🖼️ Visualización

<figure><img src="../../../.gitbook/assets/image (137).png" alt=""><figcaption><p>Figura #2: Captura de pantalla vista detallada reporte desfases puntos de venta</p></figcaption></figure>

#### 3.2. 🔍 Filtros Disponibles

<table><thead><tr><th width="159.99993896484375">Filtro</th><th width="127">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Calendario</td><td>Permite seleccionar un rango de fechas mediante un calendario para consultar información dentro de ese periodo.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>permite filtrar por un <a href="https://virtualsoft.gitbook.io/untitled/glosario/#partner">partner</a> en especifico.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el país en el que ocurrió el desfase.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Lista desplegable</td><td>Filtra por la moneda en la que opera la plataforma.</td></tr><tr><td><strong><code>Punto de venta</code></strong></td><td>Numérico</td><td>Permite filtrar por el identificador único del punto de venta únicamente en la <strong>vista detallada</strong>.</td></tr><tr><td><strong><code>Filtro desfase</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los movimientos que coinciden correctamente y aquellos que presentan diferencias o desfase en la conciliación en la <strong>vista detallada.</strong></td></tr><tr><td><strong><code>Valor desfase</code></strong></td><td>Lista desplegable + Numérico</td><td>Permite filtrar los registros según la diferencia detectada, aplicando una condición de comparación (<em>igual, mayor, menor, entre, etc.</em>) e ingresando el <strong>valor numérico</strong> deseado en la <strong>vista detallada</strong>.</td></tr></tbody></table>

#### 3.3. KP&#x49;**´s**

Los KPI se muestran en la parte superior del dashboard y presentan **indicadores generales** calculados sobre todos las operaciones (_Partner / País_) consultadas.

<table><thead><tr><th width="159">Kpi</th><th>Descripción</th></tr></thead><tbody><tr><td><p></p><p><strong><code>Cantidad de puntos de venta con desfase</code></strong></p></td><td>Cantidad total de puntos de venta que presentan un desfase en el sistema, considerando todas las operaciones consultadas (<em>Partner / País</em>).</td></tr><tr><td><strong><code>Cantidad desfase operación</code></strong></td><td>Muestra la cantidad de desfases totales que tienen los puntos de venta en el periodo de tiempo seleccionado.</td></tr></tbody></table>

#### 3.4. Resultados de consulta

Permite visualizar una tabla **por punto de venta** con el detalle de la información, la cual se actualiza automáticamente según los filtros aplicados al seleccionar el tipo de visualización **“Detallado”**.

<table><thead><tr><th width="184">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>punto de venta</code></strong></td><td>Identificador único del punto de venta al que corresponde el registro del desfase.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Indica el partner en el que se registró el desfase.</td></tr><tr><td><strong><code>País</code></strong></td><td>Indica el país en el que se registró el desfase.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha y hora en que se registró el desfase en la operación.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda en la que se realizó el desfase y se calculó el saldo.</td></tr><tr><td><strong><code>Saldo inicial del día</code></strong></td><td>Saldo con el que el punto de venta inició el día antes de registrar movimientos.</td></tr><tr><td><strong><code>Saldo final calculado</code></strong></td><td>Saldo final calculado automáticamente según las transacciones registradas en la plataforma.</td></tr><tr><td><strong><code>Saldo final en plataforma</code></strong></td><td>Saldo real registrado en la plataforma al cierre del período consultado, correspondiente al monto total efectivamente disponible el punto de venta.</td></tr><tr><td><strong><code>Valor del desfase</code></strong></td><td>Diferencia entre el saldo final calculado y el saldo final en plataforma. Indica si existe inconsistencia.</td></tr></tbody></table>

> ⚠️**Nota:** Este es el reporte **detallado**, para ver la documentación relacionada al reporte **resumido** clic aquí 🔽

<p align="center"><a href="desfases-puntos-de-venta.md#resumido" class="button primary" data-icon="clipboard-list-check">Reporte resumido</a></p>
{% endtab %}
{% endtabs %}

***

### 4.  Validaciones y Reglas de Negocio

* El dashboard está disponible únicamente para perfiles con permisos autorizados.
* El desfase corresponde a la diferencia entre el saldo final calculado y el saldo final registrado en la plataforma, y considera:
  * Saldo inicial del día
  * Movimientos de entrada
  * Movimientos de salida
  * Ajustes manuales del equipo de Riesgos
* Este dashboard presenta la misma información que el reporte [**Histórico de Saldo puntos de venta**](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/historico-de-saldos) del **backoffice**. La única diferencia es que utiliza un criterio de redondeo distinto, sin afectar el valor total de los resultados.

***

### 5. Control de Versiones

| Versión | Fecha      | Autor           | Cambios Realizados |
| ------- | ---------- | --------------- | ------------------ |
| 1.0     | 26/02/2026 | David Velasquez | Documento inicial  |
