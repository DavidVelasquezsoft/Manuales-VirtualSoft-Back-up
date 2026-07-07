---
description: >-
  Permite consultar los registros relacionados con la gestión de puntos de venta
  en el sistema. Esta funcionalidad proporciona un registro detallado de los
  cambios realizados.
---

# Aprobación Logs Puntos

### 1. Acceso al Módulo <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de Acceso**: Backoffice > Seguridad > Aprobación Logs Puntos

***

### 🖼️ 2. Visualización general <a href="#id-4.-visualizacion" id="id-4.-visualizacion"></a>

<figure><img src="../../.gitbook/assets/image (164).png" alt=""><figcaption><p>Figura#1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### 🧑‍💻 3. Acciones de usuario

<table><thead><tr><th width="189">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="aprobacion-logs-puntos.md#id-3.1.-filtros"><strong>Filtrar</strong></a></td><td>Permite filtrar los resultados para obtener resultados mas específicos.</td></tr><tr><td><a href="aprobacion-logs-puntos.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td><p>Aplica los filtros seleccionados y muestra los registros válidos.</p><h4 id="id-4.-filtros-disponibles"><br></h4></td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite descargar la información <em>(filtrada o completa)</em> en formato Excel o PDF. Para ello, ubica el botón <strong>Exportar</strong> en la parte inferior derecha de la página y selecciona el formato deseado para iniciar la descarga.</td></tr></tbody></table>

### 🔎 3.1. Filtros

Los filtros disponibles para realizar las consultas son:

<table><thead><tr><th width="176.5">Campos</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Permite seleccionar un rango de fechas para acotar los registros mostrados en la consulta.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Filtra los resultados según el identificador único asociado al usuario.</td></tr><tr><td><strong><code>Usuario (Correo electrónico)</code></strong></td><td>Permite buscar registros utilizando el correo electrónico del usuario.</td></tr><tr><td><strong><code>País</code></strong></td><td>Filtra los registros según el país seleccionado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Permite filtrar los resultados según el estado del cambio, como <em>Aprobado</em>, <em>Pendiente</em>, entre otros.</td></tr><tr><td><strong><code>Campo</code></strong></td><td>Define el campo específico dentro de los registros sobre el que se desea realizar la búsqueda.</td></tr><tr><td><strong><code>Usuario Solicita</code></strong></td><td>Filtra los registros según el usuario que realizó la solicitud.</td></tr></tbody></table>

### 🚀 3.2. Consultar

Los resultados de la consulta se presentan en una tabla que organiza la información de manera clara y estructurada. Las columnas incluidas son:

<table><thead><tr><th width="194.00006103515625">Campos</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>Indica el país asociado al registro del log.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del registro generado en los <a href="https://app.gitbook.com/o/QcwavWzh0dfIwPyknoIT/s/mbqa0WvDWam8G20QQoIZ/#logs">logs</a>.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha exacta en la que se realizó el cambio o acción registrada.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario involucrado en la modificación o evento.</td></tr><tr><td><strong><code>Usuario Solicita</code></strong></td><td>Usuario que inició la solicitud del cambio o acción registrada.</td></tr><tr><td><strong><code>Usuario Aprueba</code></strong></td><td>Usuario responsable de aprobar la solicitud o acción realizada.</td></tr><tr><td><strong><code>Campo</code></strong></td><td>Campo específico del sistema que fue modificado durante la acción.</td></tr><tr><td><strong><code>Antiguo</code></strong></td><td>Valor previo que tenía el campo antes de la modificación.</td></tr><tr><td><strong><code>Nuevo</code></strong></td><td>Valor actualizado que adquiere el campo después del cambio.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del registro, como <em>Aprobado</em>, <em>Pendiente</em> o <em>Rechazado</em>.</td></tr></tbody></table>

***

### 🕒 5. Control de Versiones

| Versión | Fecha      | Autor           | Cambios Realizados |
| ------- | ---------- | --------------- | ------------------ |
| 1.0     | 2025/12/10 | David velasquez | Documento inicial  |
