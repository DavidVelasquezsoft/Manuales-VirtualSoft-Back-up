---
description: >-
  Permite visualizar información detallada sobre las comisiones que han sido
  pagadas, organizadas según los filtros seleccionados. Esta funcionalidad es
  clave para gestionar y verificar los pagos.
---

# Reporte de comisiones pagadas

#### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Comisiones Pagadas

***

#### 2. Visualización

<figure><img src="../../.gitbook/assets/image (606).png" alt=""><figcaption><p>Figura #1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

#### 3. Funcionalidades

<table><thead><tr><th width="163">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtrar comisiones</strong></td><td>Permite aplicar filtros de búsqueda por usuario, tipo de comisión, estado, concesionario o rango de fechas.</td></tr><tr><td><strong>Visualizar tabla de resultados</strong></td><td>Muestra la información de las comisiones pagadas o pendientes según los filtros seleccionados.</td></tr><tr><td><strong>Exportar resultados</strong></td><td>Genera un archivo en formato Excel con los datos obtenidos de la consulta.</td></tr></tbody></table>

**🔎 3.1 Filtros principales**

<table><thead><tr><th width="123">Campo</th><th width="155">Tipo de Control</th><th width="484">Descripción</th></tr></thead><tbody><tr><td><code>Fecha</code></td><td>Calendario</td><td>Define el rango de fechas en el que se efectuaron los pagos de comisiones.</td></tr><tr><td><code>Estado</code></td><td>Lista desplegable</td><td>Permite seleccionar el estado de las comisiones (pagado, pendiente, rechazado).</td></tr><tr><td><code>Mi Comisión</code></td><td>Casilla de verificación</td><td>Filtra la consulta para mostrar únicamente las comisiones correspondientes al usuario actual.</td></tr><tr><td><code>Por Fecha de Comisión Pagada</code></td><td>Casilla de verificación</td><td>Filtra los resultados específicamente por la fecha en que se realizó el pago.</td></tr><tr><td><code>Tipo de Comisión</code></td><td>Lista desplegable</td><td>Permite filtrar por tipo de comisión (todas, fija, variable, etc.).</td></tr><tr><td><code>ID Usuario</code></td><td>Campo de texto</td><td>Filtra los resultados por el identificador único del usuario.</td></tr><tr><td><code>Tipo de Usuario</code></td><td>Lista desplegable</td><td>Especifica el tipo de usuario dentro del sistema (Todos, Afiliador, Concesionario, Subconcesionario, Punto de Venta).</td></tr><tr><td><code>ID Concesionario</code></td><td>Campo de texto</td><td>Filtra los resultados por el concesionario asociado al usuario.</td></tr><tr><td><code>Visualización Resumida</code></td><td>Casilla de verificación</td><td>Permite alternar entre una vista resumida o detallada de la información del reporte.</td></tr></tbody></table>

**📊 Tabla de Resultados**\
Los resultados de la consulta se presentan en una tabla con las siguientes columnas:

<table><thead><tr><th width="181">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>ID</strong></td><td>Identificador único de la comisión pagada.</td></tr><tr><td><strong>Punto de Venta</strong></td><td>Nombre o identificación del punto de venta asociado.</td></tr><tr><td><strong>Nombre Usuario</strong></td><td>Nombre del usuario receptor de la comisión.</td></tr><tr><td><strong>Tipo de Usuario</strong></td><td>Clasificación del usuario (Afiliador, Concesionario, Subconcesionario, Punto de Venta).</td></tr><tr><td><strong>Valor</strong></td><td>Monto correspondiente a la comisión pagada.</td></tr><tr><td><strong>Fecha Inicio</strong></td><td>Fecha de inicio del periodo al que corresponde la comisión.</td></tr><tr><td><strong>Fecha Fin</strong></td><td>Fecha de finalización del periodo al que corresponde la comisión.</td></tr><tr><td><strong>Pago de Comisiones</strong></td><td>Indica si la comisión fue pagada.</td></tr><tr><td><strong>Estado</strong></td><td>Muestra el estado actual de la comisión (pagada, pendiente, etc.).</td></tr><tr><td><strong>Tipo de Comisión</strong></td><td>Clasificación de la comisión (fija, variable, etc.).</td></tr><tr><td><strong>Fecha Creación</strong></td><td>Fecha en que se generó el registro de la comisión.</td></tr></tbody></table>

***

**4. Validaciones y Reglas de Negocio**

* No es obligatorio completar todos los filtros para realizar una búsqueda.
* La información mostrada dependerá de los filtros seleccionados en la consulta.
* Los valores y estados reflejados corresponden a los registros disponibles en el rango de fechas consultado.

***

**5. Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 21/10/2025 | Ronald Peláez | Documento inicial  |
