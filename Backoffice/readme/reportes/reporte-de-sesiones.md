---
description: >-
  Consulta las sesiones abiertas por los usuarios en la plataforma. Permitiendo
  hacer seguimiento a la actividad de conexión de los usuarios y apoyar la
  revisión de incidencias.
---

# Reporte de Sesiónes

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Sesiones

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FM2ZZPtepfuOg7XyPsCrR%2Fimage.png?alt=media&#x26;token=f2d5fa73-0235-4d68-8c62-ff773be86ed1" alt=""><figcaption><p>Figura #1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-sesiones.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar las sesiones registradas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-sesiones.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las sesiones en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="152">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo de texto</td><td>Consulta las sesiones asociadas a un usuario específico mediante su identificador.</td></tr><tr><td><strong><code>ID Sesión</code></strong></td><td>Campo de texto</td><td>Localiza una sesión puntual a partir de su identificador.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Delimita los resultados según el rango de fechas en el que se registraron las sesiones.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Acota la búsqueda a las sesiones que continúan abiertas <em>(Activo)</em> o a las que ya finalizaron <em>(Inactivo)</em>.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Restringe la consulta a las sesiones generadas con un proveedor determinado.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las sesiones que cumplen con los filtros aplicados.

<table><thead><tr><th width="149.3333740234375">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Sesión</code></strong></td><td>Numérico</td><td>Identificador único de la sesión registrada.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador del usuario al que pertenece la sesión.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha</td><td>Fecha en la que se abrió la sesión.</td></tr><tr><td><strong><code>Fecha de Modificación</code></strong></td><td>Fecha</td><td>Fecha del último cambio registrado sobre la sesión. En las sesiones finalizadas corresponde al momento en que se cerró.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Texto</td><td>Proveedor con el que se generó la sesión.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Situación actual de la sesión.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="132">Estado</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Activo</strong></td><td>La sesión continúa abierta y el usuario puede operar con ella.</td></tr><tr><td><strong>Inactivo</strong></td><td>La sesión finalizó, ya sea porque el usuario cerró sesión o porque el sistema la dio por terminada. El usuario debe iniciar una nueva sesión para volver a operar.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

### 6. Validaciones y reglas del negocio:

* No es obligatorio diligenciar todos los filtros para ejecutar la consulta.
* Los resultados mostrados corresponden únicamente a los criterios seleccionados en los filtros.
* Un mismo usuario puede tener varias sesiones registradas, por lo que la consulta por **`ID Usuario`** puede devolver más de un resultado.
* El reporte es informativo: desde este módulo no es posible cerrar ni modificar una sesión.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21/10/2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>16/10/2026</td><td>David Velasquez</td><td>Actualización del manual</td></tr></tbody></table>

</details>
