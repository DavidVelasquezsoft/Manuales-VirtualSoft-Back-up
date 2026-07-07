---
description: >-
  Permite visualizar y analizar información de los desfases de saldo de los
  jugadores de manera detallada y resumida.
---

# Desfases jugadores

### **1. Acceso al Módulo**

**Ruta de Acceso:** Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > desfases jugadores

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

* [**Vista detallada**](desfases-jugadores.md#detallado)**:** muestra información mas detallada por jugador
* [**Vista resumida**](desfases-jugadores.md#resumido)**:** muestra información acumulada agrupada por operación _(Partner y país_)

A continuación, se describe el funcionamiento de cada vista.

{% tabs fullWidth="false" %}
{% tab title="📈 Resumido" %}
#### 3.1. 🖼️ Visualización

<figure><img src="../../../.gitbook/assets/image (10) (1).png" alt=""><figcaption><p>Figura #1: captura de pantalla vista resumida</p></figcaption></figure>

#### 3.2. 🔍 Filtros Disponibles

<table><thead><tr><th width="159.99993896484375">Filtro</th><th width="127">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Calendario</td><td>Permite seleccionar un rango de fechas mediante un calendario para consultar información dentro de ese periodo.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>permite filtrar por un <a href="https://virtualsoft.gitbook.io/untitled/glosario/#partner">partner</a> en especifico.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el país en el que ocurrió el desfase.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Lista desplegable</td><td>Filtra por la moneda en la que opera la plataforma.</td></tr></tbody></table>

#### 3.3. KP&#x49;**´s**

Los KPI se muestran en la parte superior del dashboard y presentan **indicadores generales** calculados sobre todos las operaciones (_Partner / País_) consultadas.

<table><thead><tr><th width="159">Kpi</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad desfase operación</code></strong></td><td>Muestra la cantidad total de desfases que tienen los usuarios en el periodo de tiempo seleccionado.</td></tr><tr><td><strong><code>Cantidad de jugadores con desface</code></strong></td><td>Cantidad total de jugadores unicos que presentan un desfase en el sistema, considerando todas las operaciones consultadas (<em>Partner / País</em>).</td></tr></tbody></table>

#### 3.4. Resultados de consulta vista resumida

Permite visualizar una tabla con la información consolidada en formato **"resumido"**, actualizada dinámicamente en tiempo real según los filtros aplicados.

<table><thead><tr><th width="180">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Indica la fecha en que se registraron los desfase en el sistema para la plataforma y país correspondientes.</td></tr><tr><td><strong><code>Operación</code></strong></td><td>Indica el partner y el país en el que se registraron los desfases.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda en la cual se registraron los desfases en la plataforma.</td></tr><tr><td><strong><code>Valor desfase</code></strong></td><td><p>Indica el valor acumulado de desfases por operación.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El valor se muestra en rojo cuando es distinto de cero y no se consolida entre monedas diferentes.</p></div></td></tr><tr><td><strong><code>Jugadores con desfase</code></strong></td><td>Muestra la cantidad de jugadores dentro de la operación que presentan desfase en esa fecha, operación y moneda.</td></tr></tbody></table>

> ⚠️**Nota:** Este es el reporte **Resumido**, para ver la documentación relacionada al reporte **Detallado** clic aquí 🔽

<p align="center"><a href="desfases-jugadores.md#detallado" class="button primary" data-icon="clipboard-list-check">Reporte detallado</a></p>
{% endtab %}

{% tab title="🗂️ Detallado" %}
#### 3.1. 🖼️ Visualización

<figure><img src="../../../.gitbook/assets/image (11) (1).png" alt=""><figcaption><p>Figura #2: Captura de pantalla vista detallada</p></figcaption></figure>

#### 3.2. 🔍 Filtros Disponibles

<table><thead><tr><th width="159.99993896484375">Filtro</th><th width="127">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Calendario</td><td>Permite seleccionar un rango de fechas mediante un calendario para consultar información dentro de ese periodo.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>permite filtrar por un <a href="https://virtualsoft.gitbook.io/untitled/glosario/#partner">partner</a> en especifico.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el país en el que ocurrió el desfase.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Lista desplegable</td><td>Filtra por la moneda en la que opera la plataforma.</td></tr><tr><td><strong><code>Jugador</code></strong></td><td>Numérico</td><td>Permite filtrar por el identificador único del usuario únicamente en la <strong>vista detallada</strong>.</td></tr><tr><td><strong><code>Filtro desfase</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los movimientos que coinciden correctamente y aquellos que presentan diferencias o desfase en la conciliación en la <strong>vista detallada.</strong></td></tr><tr><td><strong><code>Valor desfase</code></strong></td><td>Lista desplegable + Numérico</td><td>Permite filtrar los registros según la diferencia detectada, aplicando una condición de comparación (<em>igual, mayor, menor, entre, etc.</em>) e ingresando el <strong>valor numérico</strong> deseado en la <strong>vista detallada</strong>.</td></tr></tbody></table>

#### 3.3. KP&#x49;**´s**

Los KPI se muestran en la parte superior del dashboard y presentan **indicadores generales** calculados sobre todos las operaciones (_Partner / País_) consultadas.

<table><thead><tr><th width="159">Kpi</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad de jugadores con desfase</code></strong></td><td>Muestra la cantidad de jugadores unicos que tienen desfases en el periodo de tiempo seleccionado.</td></tr><tr><td><strong><code>Cantidad desfase operación</code></strong></td><td>Cantidad total de desfases en el sistema, considerando todas las operaciones consultadas (<em>Partner / País</em>).</td></tr></tbody></table>

#### 3.4. Resultados de consulta vista detallada

Permite visualizar una tabla con la información consolidada en formato **"Detallado"**, actualizada dinámicamente en tiempo real según los filtros aplicados.

<table><thead><tr><th width="184">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario</code></strong></td><td>Identificador único del jugador al que corresponde el registro del desfase.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Indica el partner en el que se registró el desfase.</td></tr><tr><td><strong><code>País</code></strong></td><td>Indica el país en el que se registró el desfase.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha y hora en que se registró el desfase en la operación.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda en la que se realizó el desfase y se calculó el saldo.</td></tr><tr><td><strong><code>Saldo inicial del día</code></strong></td><td>Saldo con el que el jugador inició el día antes de registrar movimientos.</td></tr><tr><td><strong><code>Saldo final calculado</code></strong></td><td>Saldo final calculado automáticamente según las transacciones registradas en la plataforma.</td></tr><tr><td><strong><code>Saldo final en plataforma</code></strong></td><td>Saldo real registrado en la plataforma al cierre del período consultado, correspondiente al monto total efectivamente disponible en la cuenta del usuario.</td></tr><tr><td><strong><code>Valor del desfase</code></strong></td><td>Diferencia entre el saldo final calculado y el saldo final en plataforma. Indica si existe inconsistencia.</td></tr></tbody></table>

> ⚠️**Nota:** Este es el reporte **detallado**, para ver la documentación relacionada al reporte **resumido** clic aquí 🔽

<p align="center"><a href="desfases-jugadores.md#resumido" class="button primary" data-icon="clipboard-list-check">Reporte resumido</a></p>
{% endtab %}
{% endtabs %}

***

### 4. Validaciones y Reglas de Negocio

* El dashboard está disponible únicamente para perfiles con permisos autorizados.
* El desfase corresponde a la diferencia entre el saldo final calculado y el saldo final registrado en la plataforma, y considera:
  * Saldo inicial del día
  * Movimientos de entrada
  * Movimientos de salida
  * Ajustes manuales del equipo de Riesgos
* Este dashboard presenta la misma información que el reporte [**Histórico de Saldo**](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/historico-de-saldos) del backoffice. La única diferencia es que utiliza un criterio de redondeo distinto, sin afectar el valor total de los resultados; sin embargo, es importante considerar la vista en la que se realiza la comparación (_detallada o por totales_).

***

### 5. Control de Versiones

| Versión | Fecha      | Autor           | Cambios Realizados |
| ------- | ---------- | --------------- | ------------------ |
| 1.0     | 17/02/2026 | David Velasquez | Documento inicial  |
