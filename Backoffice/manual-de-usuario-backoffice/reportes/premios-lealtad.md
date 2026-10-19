# Premios lealtad

<mark style="color:$info;">Consulta los premios que los usuarios han redimido con sus puntos de lealtad. Cada registro muestra qué premio se entregó, en qué estado se encuentra y qué nivel tenía el jugador frente al nivel que el premio exigía, lo que permite verificar que la redención cumplió las condiciones establecidas.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Premios Lealtad

**Acceso directo:** [https://admin.virtualsoft.tech/#/top/prizesLoyalty](https://admin.virtualsoft.tech/#/top/prizesLoyalty)

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FzAhzqIT2AZx1Ndg1eYM3%2Fimage.png?alt=media&#x26;token=cf0f82a6-1ced-4654-a4d0-5166239d7fa8" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte de Premios Lealtad.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="premios-lealtad.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los premios redimidos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="premios-lealtad.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los premios en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="212">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Campo numérico</td><td>Localiza un registro puntual a partir de su identificador.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Consulta los premios redimidos por un usuario específico.</td></tr><tr><td><strong><code>ID Casino</code></strong></td><td>Campo numérico</td><td>Acota la consulta al casino asociado al usuario.</td></tr><tr><td><strong><code>ID Regalo</code></strong></td><td>Campo numérico</td><td>Reúne todas las redenciones de un mismo premio, sin importar qué usuario lo reclamó.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra los registros según la situación en la que se encuentra la entrega del premio <em>(Comprado, Entregado)</em>.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Delimita los resultados según el rango de fechas en el que se entregaron los premios.</td></tr><tr><td><strong><code>Fecha Modificó</code></strong></td><td>Rango de fechas</td><td>Delimita los resultados según el rango de fechas en el que se actualizó el registro por última vez.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente las redenciones de los usuarios del país seleccionado.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Acota la consulta según la naturaleza del premio <em>(Online o Físico)</em>.</td></tr><tr><td><strong><code>Nivel del jugador</code></strong></td><td>Lista desplegable</td><td>Filtra por el nivel de lealtad que tenía el jugador en el momento de redimir el premio.</td></tr><tr><td><strong><code>Nivel requerido del regalo</code></strong></td><td>Lista desplegable</td><td>Filtra por el nivel mínimo de lealtad que exige el premio para poder reclamarse.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los premios que cumplen con los filtros aplicados.

<table><thead><tr><th width="252">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único del registro de redención.</td></tr><tr><td><strong><code>ID Regalo</code></strong></td><td>Numérico</td><td>Identificador del premio entregado.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha</td><td>Fecha en la que se entregó el premio.</td></tr><tr><td><strong><code>Fecha Modificó</code></strong></td><td>Fecha</td><td>Fecha del último cambio registrado sobre la redención, por ejemplo al pasar de <em>Comprado</em> a <em>Entregado</em>.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador del usuario que redimió el premio.</td></tr><tr><td><strong><code>ID Casino</code></strong></td><td>Numérico</td><td>Identificador del casino asociado al usuario.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Situación actual de la entrega del premio <em>(Comprado, Entregado)</em>.</td></tr><tr><td><strong><code>Descripción Premio</code></strong></td><td>Texto</td><td>Detalle del premio redimido <em>(por ejemplo: regalo por nivel 8)</em>.</td></tr><tr><td><strong><code>Tipo Premio</code></strong></td><td>Texto</td><td>Naturaleza del premio entregado <em>(Online o Físico)</em>.</td></tr><tr><td><strong><code>Nivel Jugador</code></strong></td><td>Texto</td><td>Nivel de lealtad que tenía el jugador en el momento de redimir el premio.</td></tr><tr><td><strong><code>Nivel Requerido del Regalo</code></strong></td><td>Texto</td><td>Nivel mínimo de lealtad que exige el premio para poder reclamarse.</td></tr><tr><td><strong><code>Observación</code></strong></td><td>Texto</td><td>Comentarios adicionales registrados sobre la redención.</td></tr></tbody></table>

{% hint style="info" %}
**Nota:** Los campos **`Nivel Jugador`** y **`Nivel Requerido del Regalo`** se presentan juntos porque permiten verificar la redención: el nivel del jugador debe ser igual o superior al nivel exigido por el premio. Un registro en el que el nivel del jugador sea inferior indica una redención que no debió realizarse y debe revisarse.
{% endhint %}

***

### 6. Validaciones y reglas del negocio:

* No es obligatorio diligenciar todos los filtros para ejecutar la consulta.
* Los resultados mostrados corresponden únicamente a los criterios seleccionados en los filtros.
* El nivel de lealtad del jugador debe ser igual o superior al nivel requerido por el premio para que la redención sea válida.
* El campo **`Nivel Jugador`** conserva el nivel que tenía el usuario **en el momento de redimir**, por lo que puede no coincidir con su nivel actual si este cambió después de la redención.
* El reporte es informativo: desde este módulo no es posible modificar el estado de una redención ni revertirla.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/07/2025</td><td>Karol Navia</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>22/10/2025</td><td>Ronald Peláez</td><td>Refinamiento del manual</td></tr><tr><td>1.2</td><td>19/10/2026</td><td>David Velasquez</td><td>Reorganización del documento</td></tr></tbody></table>

</details>
