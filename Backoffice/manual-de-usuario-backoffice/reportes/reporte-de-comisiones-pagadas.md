---
description: >-
  Permite visualizar información detallada sobre las comisiones que han sido
  pagadas, organizadas según los filtros seleccionados. Esta funcionalidad es
  clave para gestionar y verificar los pagos.
---

# Reporte de comisiones pagadas

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Comisiones Pagadas

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (606).png" alt=""><figcaption><p>Figura #1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### 3. Acciones de usuario

<table><thead><tr><th width="163">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-comisiones-pagadas.md#id-4.-filtros-principales"><strong>Filtrar comisiones</strong></a></td><td>Permite aplicar filtros de búsqueda por usuario, tipo de comisión, estado, concesionario o rango de fechas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-comisiones-pagadas.md#id-5.-resultados-de-consulta"><strong>Visualizar tabla de resultados</strong></a></td><td>Muestra la información de las comisiones pagadas o pendientes según los filtros seleccionados.</td></tr><tr><td><strong>Exportar resultados</strong></td><td>Genera un archivo en formato Excel con los datos obtenidos de la consulta.</td></tr></tbody></table>

***

### **4. Filtros principales**

<table><thead><tr><th width="123">Campo</th><th width="155">Tipo de Control</th><th width="484">Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Define el rango de fechas en el que se efectuaron los pagos de comisiones.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el estado de las comisiones (pagado, pendiente, rechazado).</td></tr><tr><td><strong><code>Mi Comisión</code></strong></td><td>Casilla de verificación</td><td>Filtra la consulta para mostrar únicamente las comisiones correspondientes al usuario actual.</td></tr><tr><td><strong><code>Por Fecha de Comisión Pagada</code></strong></td><td>Casilla de verificación</td><td>Filtra los resultados específicamente por la fecha en que se realizó el pago.</td></tr><tr><td><strong><code>Tipo de Comisión</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por tipo de comisión (todas, fija, variable, etc.).</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo de texto</td><td>Filtra los resultados por el identificador único del usuario.</td></tr><tr><td><strong><code>Tipo de Usuario</code></strong></td><td>Lista desplegable</td><td>Especifica el tipo de usuario dentro del sistema (Todos, Afiliador, Concesionario, Subconcesionario, Punto de Venta).</td></tr><tr><td><strong><code>ID Concesionario</code></strong></td><td>Campo de texto</td><td>Filtra los resultados por el concesionario asociado al usuario.</td></tr><tr><td><strong><code>Visualización Resumida</code></strong></td><td>Casilla de verificación</td><td>Permite alternar entre una vista resumida o detallada de la información del reporte.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Los resultados de la consulta se presentan en una tabla con las siguientes columnas:

<table><thead><tr><th width="181">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único de la comisión pagada.</td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Nombre o identificación del punto de venta asociado.</td></tr><tr><td><strong><code>Nombre Usuario</code></strong></td><td>Nombre del usuario receptor de la comisión.</td></tr><tr><td><strong><code>Tipo de Usuario</code></strong></td><td>Clasificación del usuario (Afiliador, Concesionario, Subconcesionario, Punto de Venta).</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto correspondiente a la comisión pagada.</td></tr><tr><td><strong><code>Fecha Inicio</code></strong></td><td>Fecha de inicio del periodo al que corresponde la comisión.</td></tr><tr><td><strong><code>Fecha Fin</code></strong></td><td>Fecha de finalización del periodo al que corresponde la comisión.</td></tr><tr><td><strong><code>Pago de Comisiones</code></strong></td><td>Indica si la comisión fue pagada.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Muestra el estado actual de la comisión (pagada, pendiente, etc.).</td></tr><tr><td><strong><code>Tipo de Comisión</code></strong></td><td>Clasificación de la comisión (fija, variable, etc.).</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha en que se generó el registro de la comisión.</td></tr></tbody></table>

### **6. Validaciones y Reglas de Negocio**

* No es obligatorio completar todos los filtros para realizar una búsqueda.
* La información mostrada dependerá de los filtros seleccionados en la consulta.
* Los valores y estados reflejados corresponden a los registros disponibles en el rango de fechas consultado.

***

### **7. Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 21/10/2025 | Ronald Peláez | Documento inicial  |
