---
description: >-
  Esta funcionalidad permite reimprimir comprobantes de pago generados en los
  puntos de venta, ya sea en formato de cheque o depósito. Su uso es
  especialmente frecuente en Nicaragua.
---

# Reimprimir cheque

### 1. Acceso al Módulo

**Ruta de Acceso**: Backoffice > Gestión > Reimprimir cheque

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (16).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección reimprimir cheque</p></figcaption></figure>

***

### &#x33;**.** **Acciones disponibles**

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reimprimir-cheque.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados más precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="reimprimir-cheque.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="148">Campo</th><th width="134">Tipo </th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Permite seleccionar un rango de fechas para ubicar el comprobante a reimprimir.</td></tr><tr><td><strong><code>Número de Cheque</code></strong></td><td>Texto / Numérico</td><td>Permite filtrar los resultados ingresando el número de cheque específico.</td></tr><tr><td><strong><code>Cliente</code></strong></td><td>Texto</td><td>Permite buscar comprobantes asociados a un cliente en particular.</td></tr><tr><td><strong><code>Origen</code></strong></td><td>Lista desplegable</td><td>Define la fuente del pago, ya sea mediante una Nota de Retiro o un Ticket.</td></tr><tr><td><strong><code>Documento Referente</code></strong></td><td>Texto</td><td>Permite identificar el documento asociado al pago, como facturas o recibos.</td></tr><tr><td><strong><code>Documento del Cliente</code></strong></td><td>Texto / Numérico</td><td>Permite buscar el comprobante utilizando el número de documento del cliente.</td></tr></tbody></table>

### 5. Resultados de Consulta

Muestra en la parte inferior los resultados correspondientes según los filtros aplicados.

<table><thead><tr><th width="172.75">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><i class="fa-money-bill-wave" style="color:green;">:money-bill-wave:</i></td><td>Permite imprimir el cheque seleccionado.</td></tr><tr><td><strong><code>Número de Cheque</code></strong></td><td>Identificador único del cheque o comprobante de pago.</td></tr><tr><td><strong><code>Cliente</code></strong></td><td>Nombre del cliente asociado a la transacción.</td></tr><tr><td><strong><code>Documento del Cliente</code></strong></td><td>Número de identificación del cliente.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Día en que se emitió el comprobante.</td></tr><tr><td><strong><code>Origen</code></strong></td><td>Indica si la transacción proviene de una Nota de Retiro o un Ticket.</td></tr><tr><td><strong><code>Documento Referente</code></strong></td><td>Documento vinculado a la operación, como facturas o recibos.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto total del pago realizado.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Tipo de moneda en la que se realizó la transacción.</td></tr></tbody></table>

***

### 6.  Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="104.88885498046875">Versión</th><th width="124">Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>07/01/2026</td><td>David Velasquez</td><td>Actualización de formato</td></tr></tbody></table>

</details>
