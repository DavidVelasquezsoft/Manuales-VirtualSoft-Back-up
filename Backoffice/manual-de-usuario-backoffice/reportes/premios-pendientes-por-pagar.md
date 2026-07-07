---
description: >-
  Este reporte permite realizar consultas específicas sobre los datos de
  apuestas mediante la aplicación de diversos filtros.
---

# Premios pendientes por pagar

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Premios pendientes por pagar

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (579).png" alt=""><figcaption></figcaption></figure>

***

### 3. Funcionalidades

**📋 3.1 Acciones disponibles**

| Acción                         | Descripción                                                           |
| ------------------------------ | --------------------------------------------------------------------- |
| Filtrar premios                | Permite aplicar filtros de búsqueda según fecha, país, estado y tipo. |
| Seleccionar nivel de detalle   | Opción para mostrar resultados resumidos o detallados.                |
| Visualizar tabla de resultados | Presenta la información de los premios según los filtros aplicados.   |

**🔎 3.2 Filtros principales**

<table><thead><tr><th width="84.4444580078125">Campo</th><th width="112.22222900390625">Tipo de Control</th><th width="557.77783203125">Descripción</th></tr></thead><tbody><tr><td><code>Fecha</code></td><td>Calendario</td><td>Selecciona un rango de fechas para la consulta.</td></tr><tr><td><code>País</code></td><td>Lista desplegable</td><td>Permite escoger el país a consultar.</td></tr><tr><td><code>Estado</code></td><td>Lista desplegable</td><td>Filtra premios según estado.</td></tr><tr><td><code>Tipo</code></td><td>Lista desplegable</td><td><p>Define si la información se mostrará en modo <strong>Resumido</strong> o <strong>Detallado</strong>.</p><div data-gb-custom-block data-tag="tabs"><div data-gb-custom-block data-tag="tab" data-title="Resumido"><p><strong>🔹 Tipo Resumido</strong></p><p>Muestra resultados generales en una tabla con las siguientes columnas:</p></div><div data-gb-custom-block data-tag="tab" data-title="Detallado"><p><strong>📊 🔹 Tipo Detallado</strong></p><p>Muestra resultados específicos con mayor nivel de información:</p></div></div></td></tr></tbody></table>

| Columna                  | Descripción                                       |
| ------------------------ | ------------------------------------------------- |
| **No. Ticket**           | Identificador único del ticket de la apuesta.     |
| **Fecha Creación**       | Fecha en que se creó la apuesta.                  |
| **Hora de Creación**     | Hora exacta en que se generó la apuesta.          |
| **Fecha Premio**         | Fecha en la que se otorgó el premio.              |
| **Hora Premio**          | Hora específica en que se concedió el premio.     |
| **Valor Apostado**       | Monto total apostado.                             |
| **Valor Premio**         | Monto total recibido como premio.                 |
| **Moneda**               | Moneda utilizada en la transacción.               |
| **Punto de Venta**       | Terminal o ubicación donde se realizó la apuesta. |
| **Fecha Caducidad Pago** | Fecha límite para reclamar el premio.             |
| **Caduco**               | Indica si el premio está caducado.                |

| Columna            | Descripción                        |
| ------------------ | ---------------------------------- |
| **Fecha Creación** | Fecha en que se generó la apuesta. |
| **Valor Apostado** | Monto total apostado.              |
| **Valor Premio**   | Monto total de premios obtenidos.  |

***

### 4. Validaciones y Reglas de Negocio

* No es necesario completar todos los filtros para realizar una búsqueda.
* Los resultados dependerán del tipo de vista seleccionado (**Resumido** o **Detallado**).

***

### 5. Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 10/09/2025 | Ronald Peláez | Documento inicial  |
