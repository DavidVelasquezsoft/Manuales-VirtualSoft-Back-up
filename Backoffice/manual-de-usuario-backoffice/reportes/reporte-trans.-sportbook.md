---
description: >-
  El Reporte de Transacciones Sportbook permite conocer y analizar información
  detallada sobre las transacciones deportivas realizadas en la plataforma.
---

# Reporte Trans. Sportbook

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Trans. Sportbook

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (48).png" alt=""><figcaption><p>Figura #1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### 3. Funcionalidades

#### **📋 3.1 Acciones disponibles**

<table><thead><tr><th width="163">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td>Filtrar transacciones</td><td>Permite aplicar filtros de búsqueda por usuario, fecha, tipo, transacción o ticket.</td></tr><tr><td>Visualizar tabla de resultados</td><td>Presenta la información de las transacciones según los filtros aplicados.</td></tr><tr><td>Exportar los resultados</td><td>Exporta en formato Excel la tabla de los resultados según los filtros seleccionados.</td></tr></tbody></table>

#### **🔎 3.2 Filtros principales**

<table><thead><tr><th width="123">Campo</th><th width="155">Tipo de Control</th><th width="484">Descripción</th></tr></thead><tbody><tr><td><code>ID Usuario</code></td><td>Campo de texto</td><td>Permite buscar las transacciones asociadas a un usuario específico mediante su identificador único.</td></tr><tr><td><code>Fecha de Creación</code></td><td>Calendario</td><td>Filtra las transacciones realizadas dentro de un rango de fechas específico.</td></tr><tr><td><code>Tipo</code></td><td>Lista desplegable</td><td>Selecciona el tipo de transacción que se desea consultar.</td></tr><tr><td><code>Transacción Id</code></td><td>Campo de texto</td><td>Busca una transacción en particular utilizando su identificador único.</td></tr><tr><td><code>Ticked Id</code></td><td>Campo de texto</td><td>Filtra las transacciones relacionadas con un ticket específico usando su identificador.</td></tr></tbody></table>

**📊 Tabla de Resultados**

Los resultados de la consulta se presentan en una tabla con las siguientes columnas:

| Columna              | Descripción                                                          |
| -------------------- | -------------------------------------------------------------------- |
| **`ID`**             | Identificador único de la transacción.                               |
| **`ID Usuario`**     | Identificador del usuario que realizó la transacción.                |
| **`Fecha`**          | Fecha en la que se registró la transacción.                          |
| **`Transacción ID`** | Código único que identifica la transacción en el sistema.            |
| **`Ticket ID`**      | Número único del ticket relacionado con la transacción.              |
| **`Tipo`**           | Clasificación de la transacción (ejemplo: apuesta, recarga, retiro). |
| **`Valor`**          | Monto asociado con la transacción.                                   |

***

#### 4. Validaciones y Reglas de Negocio

* No es obligatorio completar todos los filtros para realizar una búsqueda.
* La información mostrada dependerá de los filtros seleccionados en la consulta.

***

#### 5. Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 24/09/2025 | Ronald Peláez | Documento inicial  |
