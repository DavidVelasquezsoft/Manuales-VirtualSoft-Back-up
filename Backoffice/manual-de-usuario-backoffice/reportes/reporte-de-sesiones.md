---
description: >-
  Permite consultar y analizar información detallada sobre las sesiones de los
  usuarios, proporcionando datos esenciales para el seguimiento y la gestión de
  actividad en la plataforma.
---

# Reporte de Sesiónes

#### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Sesiones

***

#### 2. Visualización

<figure><img src="../../.gitbook/assets/image (36).png" alt=""><figcaption><p>Figura #1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

#### 3. Funcionalidades

<table><thead><tr><th width="163">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtrar sesiones</strong></td><td>Permite aplicar filtros de búsqueda por usuario, sesión, fecha, estado o proveedor.</td></tr><tr><td><strong>Visualizar tabla de resultados</strong></td><td>Presenta la información de las sesiones según los filtros aplicados.</td></tr><tr><td><strong>Exportar los resultados</strong></td><td>Exporta en formato Excel la tabla de los resultados según los filtros seleccionados.</td></tr></tbody></table>

**🔎 3.1 Filtros principales**

<table><thead><tr><th width="123">Campo</th><th width="155">Tipo de Control</th><th width="484">Descripción</th></tr></thead><tbody><tr><td><code>ID Usuario</code></td><td>Campo de texto</td><td>Permite buscar las sesiones asociadas a un usuario específico mediante su identificador único.</td></tr><tr><td><code>ID Sesión</code></td><td>Campo de texto</td><td>Busca una sesión específica utilizando su identificador único.</td></tr><tr><td><code>Fecha</code></td><td>Calendario</td><td>Filtra las sesiones creadas o modificadas dentro de un rango de fechas determinado.</td></tr><tr><td><code>Estado</code></td><td>Lista desplegable</td><td>Selecciona el estado de las sesiones: <strong>Activo</strong> o <strong>Inactivo</strong>.</td></tr><tr><td><code>Proveedor</code></td><td>Lista desplegable</td><td>Selecciona el proveedor relacionado con la sesión (por ejemplo, el sistema o plataforma que gestionó la sesión).</td></tr></tbody></table>

**📊 Tabla de Resultados**\
Los resultados de la consulta se presentan en una tabla con las siguientes columnas:

<table><thead><tr><th width="199">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>ID Sesión</strong></td><td>Identificador único asignado a cada sesión registrada.</td></tr><tr><td><strong>ID Usuario</strong></td><td>Identificador del usuario al que corresponde la sesión.</td></tr><tr><td><strong>Fecha de Creación</strong></td><td>Fecha en la que se creó la sesión en el sistema.</td></tr><tr><td><strong>Fecha de Modificación</strong></td><td>Fecha de la última actualización o cambio en la información de la sesión.</td></tr><tr><td><strong>Proveedor</strong></td><td>Nombre del proveedor responsable de la sesión.</td></tr><tr><td><strong>Estado</strong></td><td>Indica si la sesión está activa o inactiva.</td></tr></tbody></table>

***

**4. Validaciones y Reglas de Negocio**

* No es obligatorio completar todos los filtros para realizar una búsqueda.
* La información mostrada dependerá de los filtros seleccionados en la consulta.
* Las sesiones se presentan según el rango de fechas y los criterios definidos por el usuario.

***

**5. Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 21/10/2025 | Ronald Peláez | Documento inicial  |
