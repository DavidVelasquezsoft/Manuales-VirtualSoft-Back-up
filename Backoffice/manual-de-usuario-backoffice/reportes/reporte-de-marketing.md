---
description: >-
  Permite consultar los movimientos relacionados con las actividades de
  marketing de manera organizada, proporcionando detalles clave como el tipo de
  movimiento, identificadores y valores registrados.
---

# Reporte de marketing

## Reporte de Marketing

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Marketing

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (603).png" alt=""><figcaption><p>Figura #1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### 3. Funcionalidades

<table><thead><tr><th width="163">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtrar movimientos</strong></td><td>Permite aplicar filtros de búsqueda por ID de movimiento, ID externo, fecha o tipo de movimiento.</td></tr><tr><td><strong>Visualizar tabla de resultados</strong></td><td>Presenta la información de los movimientos de marketing según los filtros aplicados.</td></tr><tr><td><strong>Exportar los resultados</strong></td><td>Exporta en formato Excel la tabla de resultados obtenida tras la búsqueda.</td></tr></tbody></table>

#### **🔎 3.1 Filtros principales**

<table><thead><tr><th width="124">Campo</th><th width="142">Tipo de Control</th><th width="480">Descripción</th></tr></thead><tbody><tr><td><code>ID Movimientos de Marketing</code></td><td>Campo de texto</td><td>Identificador único del movimiento registrado en el sistema de marketing.</td></tr><tr><td><code>ID Externo</code></td><td>Campo de texto</td><td>Identificador asignado por sistemas externos o integraciones relacionadas con la actividad de marketing.</td></tr><tr><td><code>Fecha de Creación</code></td><td>Calendario</td><td>Permite seleccionar el rango de fechas en el cual se generaron los movimientos de marketing que se desean consultar.</td></tr><tr><td><code>Tipo</code></td><td>Lista desplegable</td><td>Especifica el tipo de movimiento para filtrar los resultados según su categoría o naturaleza.</td></tr></tbody></table>

#### **📊 Tabla de Resultados**

Los resultados de la consulta se presentan en una tabla con las siguientes columnas:

<table><thead><tr><th width="171">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>ID</strong></td><td>Identificador único del movimiento de marketing registrado.</td></tr><tr><td><strong>Tipo</strong></td><td>Categoría o naturaleza del movimiento <em>(ejemplo: campaña, promoción, ajuste, etc.).</em></td></tr><tr><td><strong>ID Externo</strong></td><td>Identificador relacionado con sistemas o herramientas externas, usado para referencia cruzada.</td></tr><tr><td><strong>Fecha de Creación</strong></td><td>Fecha en la que se creó o registró el movimiento.</td></tr><tr><td><strong>Valor</strong></td><td>Monto asociado al movimiento de marketing, indicando el impacto económico del mismo.</td></tr></tbody></table>

***

### 4. Validaciones y Reglas de Negocio

* No es obligatorio completar todos los filtros para realizar una búsqueda.
* La información mostrada dependerá de los filtros seleccionados en la consulta.
* Los resultados reflejan únicamente los movimientos registrados dentro del rango de fechas seleccionado.

***

### 5. Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 21/10/2025 | Ronald Peláez | Documento inicial  |
