---
description: >-
  Permite aprobar o rechazar cambios solicitados por los usuarios en el sistema,
  así como filtrar y consultar la información deseada.
---

# Aprobación Logs

***

### 1. Acceso al Módulo <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de Acceso**: Backoffice > Seguridad > Aprobación de logs

***

### 🖼️ 2. Visualización general <a href="#id-4.-visualizacion" id="id-4.-visualizacion"></a>

<figure><img src="../../.gitbook/assets/image (551).png" alt=""><figcaption><p>Figura#1: Captura de pantalla aprobación de logs.</p></figcaption></figure>

***

### 🔍 3. Filtro

<table><thead><tr><th width="116.49993896484375">Campo</th><th width="122.166748046875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td> Permite seleccionar el rango de fechas en el que se registro el <a href="https://virtualsoft.gitbook.io/untitled/glosario#logs">log</a>.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Filtra los resultados según el identificador único del usuario.</td></tr><tr><td><strong><code>Usuario (Correo electrónico)</code></strong></td><td>Email</td><td>Permite buscar por el correo electrónico del usuario.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra los resultados según la ubicación.</td></tr></tbody></table>

#### 🔍 3.1. Filtros avanzados

<table><thead><tr><th width="96.5">Campo</th><th width="117.1666259765625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Selección del estado del cambio (<em>Ejemplo: Aprobado, Pendiente, Rechazado, etc.</em>).</td></tr><tr><td><strong><code>Campo</code></strong></td><td>Texto</td><td>Nombre del campo del que se realiza el <a href="https://virtualsoft.gitbook.io/untitled/glosario#logs">log</a>.</td></tr><tr><td><strong><code>Usuario Solicita</code></strong></td><td>Numérico</td><td>Identificador único del usuario que solicita el cambio.</td></tr></tbody></table>

***

### 🧑‍💻 4. Acciones de usuario

#### 🔄 4.1.  Limpiar

Restablece los filtros por defecto.

#### 🚀 4.2.  Consultar

Aplica los filtros seleccionados y muestra los registros válidos.

<table><thead><tr><th width="150.66668701171875">Campo</th><th width="113.00006103515625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Accion</code></strong></td><td>Columna de acciones</td><td><p>Permite aprobar / rechazar el <a href="https://virtualsoft.gitbook.io/untitled/glosario#logs">log</a> correspondiente cuando esta <strong>pendiente</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al aprobar un log de cambio de documento, el sistema validará la ausencia de <strong>duplicados</strong>; de existir en la misma marca y pais, se mostrará mensaje de error y el cambio será rechazado.</p></div></td></tr><tr><td><strong><code>País</code></strong></td><td>Bandera</td><td>País relacionado con la solicitud o el cambio registrado.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único del <a href="https://virtualsoft.gitbook.io/untitled/glosario#logs">log</a>.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha/Hora</td><td>Fecha en la que se solicito el cambio</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador único del usuario involucrado en la acción.</td></tr><tr><td><strong><code>Usuario Solicita</code></strong></td><td>Numérico</td><td>Identificador único usuario que inició la solicitud del cambio.</td></tr><tr><td><strong><code>Usuario Aprueba</code></strong></td><td>Numérico / Texto</td><td>Identificador único y nombre del usuario que aprobó la solicitud.</td></tr><tr><td><strong><code>Campo</code></strong></td><td>Texto</td><td>Especifica el campo del sistema que fue modificado.</td></tr><tr><td><strong><code>Antiguo</code></strong></td><td>Numérico</td><td>Valor anterior del campo modificado.</td></tr><tr><td><strong><code>Nuevo</code></strong></td><td>Numérico</td><td>Valor actualizado del campo modificado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Estado actual del registro (<em>Ejemplo: Aprobado, Rechazado, Pendiente.</em>).</td></tr></tbody></table>

***

### 🕒 5. Control de Versiones

| Versión | Fecha      | Autor           | Cambios Realizados |
| ------- | ---------- | --------------- | ------------------ |
| 1.0     | 2025/12/10 | David Velasquez | Documento inicial  |
