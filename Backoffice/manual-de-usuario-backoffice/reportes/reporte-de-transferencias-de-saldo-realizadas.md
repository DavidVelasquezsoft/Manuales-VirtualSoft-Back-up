---
description: >-
  Este reporte permite consultar las transferencias de saldo realizadas,
  aplicando diversos filtros para obtener la información deseada de manera
  precisa.
---

# Reporte de transferencias de saldo Realizadas

#### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Transferencias de Saldo Realizadas

***

#### 2. Visualización

<figure><img src="../../.gitbook/assets/image (38).png" alt=""><figcaption><p>Figura #1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

#### 3. **Acciones disponibles**

<table><thead><tr><th width="163">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td>Filtrar transferencias</td><td>Permite aplicar filtros de búsqueda por usuario, fecha, concesionario, país o tipo de reporte.</td></tr><tr><td>Visualizar tabla de resultados</td><td>Muestra la información de las transferencias según los filtros aplicados.</td></tr><tr><td>Exportar los resultados</td><td>Permite descargar en formato Excel los resultados obtenidos en la consulta.</td></tr></tbody></table>

**🔎 3.1. Filtros principales**

<table><thead><tr><th width="123">Campo</th><th width="155">Tipo de Control</th><th width="484">Descripción</th></tr></thead><tbody><tr><td><code>ID Usuario</code></td><td>Campo de texto</td><td>Identificador único del usuario que realizó la transferencia.</td></tr><tr><td><code>Nombre del Usuario</code></td><td>Campo de texto</td><td>Permite buscar por el nombre del usuario que efectuó la transferencia.</td></tr><tr><td><code>Fecha</code></td><td>Calendario</td><td>Filtra las transferencias realizadas dentro de un rango de fechas específico.</td></tr><tr><td><code>ID Concesionario</code></td><td>Campo de texto</td><td>Identificador del concesionario asociado a la transferencia.</td></tr><tr><td><code>Subconcesionario</code></td><td>Campo de texto</td><td>Permite filtrar por el subconcesionario relacionado a la transferencia.</td></tr><tr><td><code>País</code></td><td>Lista desplegable</td><td>Selecciona el país donde se realizó la transferencia.</td></tr><tr><td><code>Tipo de Usuario</code></td><td>Lista desplegable</td><td>Clasifica al usuario según su rol o perfil dentro del sistema.</td></tr><tr><td><code>Tipo</code></td><td>Lista desplegable</td><td><p>Selecciona el tipo de reporte a generar:</p><ul><li><strong>Detallado</strong>: Muestra información específica de cada transferencia.</li><li><strong>Totales</strong>: Presenta un resumen general de las transferencias realizadas.</li></ul></td></tr><tr><td><code>Asignado Por</code></td><td>Campo de texto</td><td>Permite buscar las transferencias realizadas por un usuario específico que asignó el saldo.</td></tr></tbody></table>

**📊 Tabla de Resultados**\
Los resultados de la consulta se presentan en una tabla con las siguientes columnas:

<table><thead><tr><th width="177">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>ID</strong></td><td>Identificador único que distingue cada transferencia realizada.</td></tr><tr><td><strong>Fecha</strong></td><td>Fecha y hora en que se efectuó la transferencia.</td></tr><tr><td><strong>ID Usuario</strong></td><td>Identificador del usuario que realizó la transferencia.</td></tr><tr><td><strong>Nombre del Usuario</strong></td><td>Nombre del usuario responsable de la transferencia.</td></tr><tr><td><strong>Tipo Cupo</strong></td><td>Clasificación del cupo transferido (por ejemplo: apuestas, recargas, etc.).</td></tr><tr><td><strong>Tipo Transacción</strong></td><td>Tipo de operación realizada (por ejemplo: salida, entrada, etc.).</td></tr><tr><td><strong>Valor</strong></td><td>Monto total transferido en la operación.</td></tr><tr><td><strong>Moneda</strong></td><td>Tipo de moneda utilizada en la transacción.</td></tr><tr><td><strong>Asignado Por</strong></td><td>Nombre o identificador del usuario que asignó o procesó el saldo transferido.</td></tr></tbody></table>

***

**4. Validaciones y Reglas de Negocio**

* No es obligatorio completar todos los filtros para realizar una búsqueda.
* La información mostrada dependerá de los filtros seleccionados en la consulta.
* Solo los usuarios con los permisos correspondientes pueden visualizar o exportar la información.

***

**5. Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 08/10/2025 | Ronald Peláez | Documento inicial  |
