---
description: >-
  El objetivo de este reporte facilitar la consulta individual de los premios
  que ha recibido un jugador específico.
---

# Premios de lealtad

### 1. Acceso al módulo

**Ruta de acceso**: BackOffice > Perfil del Jugador > reportes > Premios de Lealtad

{% hint style="warning" %}
**Nota:** Solo los usuarios con permisos para visualizar este reporte podrán acceder a esta pestaña y utilizar las funciones descritas.
{% endhint %}

***

### 2. Visualización:

<figure><img src="../../../.gitbook/assets/image (545).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección premios de lealtad.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="141">Funcionalidad</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Consultar premios entregados</code></strong></td><td>Permite consultar los premios entregados a un jugador en un rango de fechas específico.</td></tr><tr><td><strong><code>Filtrar registros</code></strong></td><td>Posibilidad de filtrar por ID de regalo, fecha, estado y tipo de premio.</td></tr><tr><td><strong><code>Exportar resultados</code></strong></td><td>Posibilidad de exportar los resultados obtenidos en formato Excel.</td></tr><tr><td><strong><code>Consultar</code></strong></td><td>Ejecuta la búsqueda y <strong>carga la tabla</strong> con los filtros seleccionados.</td></tr><tr><td><strong><code>Limpiar</code></strong></td><td>Restablece todos los filtros a sus valores por defecto y <strong>vacía</strong> la tabla para una nueva consulta.</td></tr></tbody></table>

***

### 4. Filtros disponibles

<table><thead><tr><th width="137">Filtro</th><th width="168">Tipo de campo</th><th width="441">Descripción</th></tr></thead><tbody><tr><td><strong><code>ID regalo</code></strong></td><td>Numérico</td><td>Identificador único asignado al regalo. Permite buscar un premio específico recibido por el jugador.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Calendario (rango)</td><td>Rango de fechas en que se otorgó el premio.</td></tr><tr><td><strong><code>Fecha de modificación</code></strong></td><td>Calendario (rango)</td><td>Rango de fechas en que el premio fue modificado (por ejemplo: cambios de estado o ajustes administrativos).</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Estado actual del premio (por ejemplo: <em>Comprado</em>, <em>Entregado</em>).</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td> Tipo por el cual se otorgó el premio (por ejemplo: <em>Online</em>, <em>Presencial</em>).</td></tr></tbody></table>

***

### 5. Tabla de resultados

#### 📋 Detalle de Premios por Jugador

<table><thead><tr><th width="190">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador interno único del registro del premio.</td></tr><tr><td><strong><code>ID Regalo</code></strong></td><td>Identificador único del regalo otorgado al jugador.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha y hora en que se otorgó el premio.</td></tr><tr><td><strong><code>Fecha Modificó</code></strong></td><td>Fecha y hora de la última modificación realizada al registro del premio.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador interno único del jugador que recibió el premio.</td></tr><tr><td><strong><code>ID Casino</code></strong></td><td>Identificador del casino o entidad que gestionó el premio.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del premio (<em>Comprado</em>, <em>Entregado</em>, <em>Cancelado</em>, etc.).</td></tr><tr><td><strong><code>Descripción Premio</code></strong></td><td>Texto descriptivo del premio recibido (por ejemplo: “Mega verano”).</td></tr><tr><td><strong><code>Tipo Premio</code></strong></td><td>Modalidad o categoría del premio (por ejemplo: <em>Online</em>, <em>Físico</em>).</td></tr><tr><td><strong><code>Nivel Jugador</code></strong></td><td>Nivel que tenía el jugador en el momento de redimir el regalo.</td></tr><tr><td><strong><code>Nivel Requerido del Regalo</code></strong></td><td>Nivel mínimo que debía tener el jugador para poder acceder al premio.</td></tr><tr><td><strong><code>Observación</code></strong></td><td>Comentarios o notas adicionales relacionadas con el premio.</td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* Los filtros pueden combinarse para refinar la búsqueda.
* Los datos mostrados corresponden únicamente a jugadores con premios asignados.
* La exportación de datos respeta los filtros aplicados en la búsqueda.

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="101">Versión</th><th width="129">Fecha</th><th width="154">Autor</th><th>Descripción del cambio</th></tr></thead><tbody><tr><td>1.0</td><td>15/08/2025</td><td>Karol Navia</td><td>Creación inicial del manual.</td></tr></tbody></table>

</details>
