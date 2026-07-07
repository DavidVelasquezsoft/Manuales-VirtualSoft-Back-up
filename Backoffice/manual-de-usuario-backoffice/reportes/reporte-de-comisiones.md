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

# Reporte de comisiones -

<mark style="color:$info;">Permite consultar y analizar de forma consolidada las comisiones generadas por afiliados y puntos de venta dentro de la plataforma. Logrando visualizar montos apostados, premios, bonos, impuestos y comisiones, facilitando el control financiero, la validación de cálculos y el seguimiento del desempeño comercial.</mark>

### 1. Acceso al Módulo

**Ruta de acceso:** BackOffice > Reportes > Reporte de Comisiones -

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (627).png" alt=""><figcaption><p>Figura #1: Vista general del Reporte Comisiones Global.</p></figcaption></figure>

***

### 3. Funcionalidades

<table><thead><tr><th width="163">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Filtrar comisiones</code></strong></td><td>Permite aplicar filtros de búsqueda para obtener información más detallada.</td></tr><tr><td><strong><code>Visualizar tabla de resultados</code></strong></td><td>Muestra la información de las comisiones pagadas o pendientes según los filtros seleccionados.</td></tr><tr><td><strong><code>Exportar resultados</code></strong></td><td>Genera un archivo en formato Excel con los datos obtenidos de la consulta.</td></tr></tbody></table>

***

#### **🔎 3.1 Filtros de búsqueda**

Los filtros permiten segmentar la información del reporte según distintos criterios operativos y comerciales.

<table><thead><tr><th width="120">Campo</th><th width="161">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Permite definir el rango de fechas sobre el cual se realizará la consulta del reporte.</td></tr><tr><td><strong><code>Tipo Usuario</code></strong></td><td>Lista desplegable</td><td>Permite filtrar la información según el tipo de usuario afiliador.</td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Lista desplegable</td><td>Filtra los resultados por un punto de venta específico.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selector </td><td>Define si el reporte se mostrará de forma consolidada o con el detalle por afiliado <em>(Totales / Detallado)</em>.</td></tr><tr><td><strong><code>Mi comisión</code></strong></td><td>Selector</td><td>Permite visualizar únicamente las comisiones asociadas al usuario autenticado (<em>Sí / No)</em>.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite consultar información correspondiente a un país determinado.</td></tr></tbody></table>

***

#### **🧾 3.2 Resultado de la Consulta**

La consulta generará una tabla basada en los filtros aplicados, la cual presenta columnas principales y secundarias que organizan la información de forma clara y estructurada.

<table><thead><tr><th width="142">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Click to configure</code></strong></td><td>Abre una ventana emergente que permite personalizar la visualización de la tabla, organizando la información mediante parámetros específicos, los cuales pueden configurarse como filtros, columnas, filas o valores, según las necesidades del usuario.</td></tr><tr><td><strong><code>Notas de retiro Punto Venta</code></strong></td><td>Esta columna agrupa la información correspondiente sobre las notas de retiro generadas por cada punto de venta.</td></tr><tr><td><strong><code>Depósitos afiliados</code></strong></td><td>Agrupa los reportes relacionados con las comisiones obtenidas por los depósitos realizados por medio de afiliados.</td></tr><tr><td><strong><code>(SC#) Casino NGR Afiliados</code></strong></td><td>Agrupa la información del <a href="https://virtualsoft.gitbook.io/untitled/glosario/#net-gaming-revenue-ngr">Net Gaming Revenue</a> (NGR) generado por los afiliados en juegos de casino.</td></tr><tr><td><strong><code>(SC#) Sportbook NGR Afiliados con impuesto del 12%</code></strong></td><td>Agrupa la información del <a href="https://virtualsoft.gitbook.io/untitled/glosario/#net-gaming-revenue-ngr">NGR</a> generado por afiliados en apuestas deportivas, considerando la deducción del 12% por impuestos, y mostrando las métricas correspondientes.</td></tr><tr><td><strong><code>(SC#) Sportbook NGR Afiliados</code></strong></td><td>Agrupa la información del <a href="https://virtualsoft.gitbook.io/untitled/glosario/#net-gaming-revenue-ngr">Net Gaming Revenue (NGR)</a> generado por afiliados en apuestas deportivas sin aplicar deducciones por impuestos, utilizando las métricas estándar del reporte.</td></tr><tr><td>(SC#) Sportbook GGR Afiliados</td><td>Agrupa la información del <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr">Gross Gaming Revenue (GGR)</a> generado por afiliados en apuestas deportivas, mostrando las métricas estándar del reporte.</td></tr><tr><td>Total</td><td>Consolida el total acumulado de todas las métricas mostradas en la tabla, de acuerdo con los filtros aplicados en la consulta.</td></tr></tbody></table>

En la parte inferior de la tabla se presenta una **fila de totales**, donde se consolidan todos los valores del período consultado de cada columna en el reporte.

***

### 5.✅ Validaciones y Reglas de Negocio

* El reporte muestra únicamente registros que **generan comisión**.
* Los valores negativos en la columna **Monto** indican escenarios donde los premios superan las apuestas.
* La fila **Total** consolida automáticamente los valores visibles según los filtros aplicados.
* El cálculo de impuestos y comisiones se ajusta según el país y la regulación vigente.

***

### 6. Documentación relacionada.

Los porcentajes de impuestos se configuran desde [esta sección del BackOffice](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion/impuesto-para-comisiones).

***

### 7.🕒 Control de Versiones

<table><thead><tr><th width="106">Versión</th><th width="129">Fecha</th><th width="149">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2025-12-22</td><td>Ronald Peláez</td><td>Documentación inicial.</td></tr></tbody></table>
