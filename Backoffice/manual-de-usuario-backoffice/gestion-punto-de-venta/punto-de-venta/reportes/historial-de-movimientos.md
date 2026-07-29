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

# Historial de movimientos

<mark style="color:$info;">Visualiza el detalle de todos los movimientos económicos registrados por el punto de venta, incluyendo apuestas, retiros, depósitos y demás transacciones realizadas.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Gestión punto de venta > 🔍 Ingresar a punto de venta > Reportes > Historial de Movimientos.

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (710).png" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte Historial de Movimientos.</p></figcaption></figure>

***

### 3. Acciones de usuario

<table><thead><tr><th width="168">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Permite consultar el historial de movimientos del punto de venta mediante diferentes criterios de búsqueda.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros por defecto.</td></tr><tr><td><strong>Consultar</strong></td><td>Aplica los filtros configurados y obtiene los resultados de la consulta.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="134">Campo</th><th width="157">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de creación</code></strong></td><td>Calendario</td><td>Rango de fechas en el que fueron registrados los movimientos.</td></tr><tr><td><strong><code>ID Externo</code></strong></td><td>Numérico</td><td>Permite consultar un movimiento mediante su identificador externo.</td></tr><tr><td><strong><code>Movimiento</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los registros según el tipo de movimiento realizado.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los movimientos según su categoría o clasificación.</td></tr></tbody></table>

### 5. Resultado de Consulta

El reporte de **Historial de Movimientos** permite consultar el registro detallado de las operaciones realizadas en el punto de venta durante el período seleccionado. Cada registro corresponde a un movimiento individual y presenta la información necesaria para identificar, consultar y realizar el seguimiento de la transacción.

La información se visualizará en una tabla con las siguientes columnas:

<table><thead><tr><th width="175">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del movimiento.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador del usuario asociado al movimiento.</td></tr><tr><td><strong><code>Movimiento</code></strong></td><td>Tipo de movimiento registrado <em>(apuesta, retiro, depósito).</em></td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Categoría o clasificación del movimiento.</td></tr><tr><td><strong><code>ID Externo</code></strong></td><td>Identificador externo relacionado con la transacción.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha y hora en la que se registró el movimiento.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Valor correspondiente al movimiento registrado.</td></tr><tr><td><strong><code>Saldo</code></strong></td><td>Saldo disponible después de aplicar el movimiento.</td></tr></tbody></table>

***

### 6. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 2026-07-23 | Ronald Peláez | Documento inicial. |

</details>
