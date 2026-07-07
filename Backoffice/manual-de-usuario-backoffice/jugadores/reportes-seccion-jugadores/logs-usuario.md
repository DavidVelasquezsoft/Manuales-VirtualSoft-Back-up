---
description: >-
  Permite visualizar los registros de actividad del usuario en la plataforma,
  incluyendo inicios de sesión, verificaciones y otras acciones relevantes
  registradas por el sistema.
---

# Logs usuario

### 1. Acceso al módulo

**Ruta de acceso**: Backoffice > Jugadores > 🔎 > Reportes > Logs de usuario

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (592).png" alt=""><figcaption></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="119.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Permiten filtrar la información para obtener resultados más precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="logs-usuario.md#id-3.1.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="115.11102294921875">Campo</th><th width="119.66668701171875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>fecha</code></strong></td><td>Fecha Inicio / Fin</td><td>Permite filtrar las acciones según la fecha en que fueron registrados en el sistema.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Permite buscar una acción especifica utilizando su identificador único de <a href="https://virtualsoft.gitbook.io/untitled/glosario#logs">log</a>.</td></tr><tr><td><strong><code>tipo</code></strong></td><td>Lista desplegable</td><td>Filtra según el tipo de actividad realizada por el usuario.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Numérico</td><td>Permite buscar acciones hechas por el usuario desde una dirección IP en especifico.</td></tr></tbody></table>

### 5. Resultados de Consulta

Aplica los filtros seleccionados y muestra los [logs](https://virtualsoft.gitbook.io/untitled/glosario#logs) válidos del usuario.

<table><thead><tr><th width="179.99993896484375">Campo</th><th width="117.99993896484375">Tipo de control</th><th width="447.0001220703125">Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único de el reporte.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Calendario y hora</td><td>Fecha exacta de la acción.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Texto</td><td>Indica el tipo de acción registrada.</td></tr><tr><td><strong><code>Elemento</code></strong></td><td>Texto</td><td>Nombre del evento o acción ejecutada.</td></tr><tr><td><strong><code>Valor antes</code></strong></td><td>Numérico</td><td>Identificador del dispositivo que ejecutó la acción.</td></tr><tr><td><strong><code>Valor despues</code></strong></td><td>Numérico</td><td>Token o IP de después de la acción.</td></tr><tr><td><strong><code>Usuario Modificó</code></strong></td><td>Numérico</td><td>identificador único del usuario que hizo la acción.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Numérico</td><td>Indica el identificador único del dispositivo que ejecutó la acción.</td></tr><tr><td><strong><code>Sistema operativo</code></strong></td><td>Texto</td><td>Nombre sistema operativo del dispositivo usado en la acción.</td></tr></tbody></table>

***

### 6. Control de versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="105.22216796875" align="right">Versión</th><th width="132">Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td align="right">1.0</td><td>2025-10-02</td><td>David velasquez</td><td>Actualización de formato</td></tr></tbody></table>

</details>
