---
description: >-
  Permite monitorear, analizar y auditar las operaciones de retiro en punto de
  venta.
---

# Reporte de Retiros

## Reporte de Retiros Punto de Venta

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Reporte de Retiros

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2F5n3Ibeu8CCGmkSgBIV3V%2Fimage.png?alt=media&#x26;token=bcacc04d-bed9-45fc-b67a-41934b1bfec4" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte de retiros punto de venta.</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-retiros.md#id-4.-filtros-principales"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="reporte-de-retiros.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. **Filtros principales**

<table><thead><tr><th width="168">Campo</th><th width="170">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Selecciona un rango de fechas para mostrar retiros realizados en ese periodo.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra los retiros según su estado <em>(pendiente, pagado, rechazado, etc.).</em></td></tr><tr><td><strong><code>Fecha de Retiro Pagado</code></strong></td><td>Calendario</td><td>Filtra retiros que fueron pagados en una fecha específica.</td></tr></tbody></table>

***

### **5. Resultados de consulta**

<table><thead><tr><th width="199">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Punto de Venta</code></strong></td><td>Nombre o identificador del punto de venta asociado al retiro.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del retiro.</td></tr><tr><td><strong><code>ID Cliente</code></strong></td><td>Identificador único del cliente que realizó el retiro.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto del retiro realizado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual de la transacción <em>(pendiente, pagado, rechazado, etc.).</em></td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha en la que se registró la solicitud de retiro.</td></tr><tr><td><strong><code>Fecha Pagado</code></strong></td><td>Fecha en la que el retiro fue procesado y pagado.</td></tr><tr><td><strong><code>Por Fecha de Retiro Pagado</code></strong></td><td>Identifica y agrupa los retiros según la fecha en que fueron pagados.</td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* No es obligatorio aplicar todos los filtros para ejecutar una búsqueda.
* Si se selecciona "**Fecha de Retiro Pagado**", los resultados estarán limitados a retiros ya procesados y pagados.

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="122">Versión</th><th width="141">Fecha</th><th width="159">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>27/08/2025</td><td>Ronald Peláez</td><td>Documento inicial del manual</td></tr></tbody></table>

</details>
