# Reporte de ruleta

<mark style="color:$info;">Consulta los giros de las ruletas promocionales asignados a los usuarios. Cada registro muestra a qué jugador y a qué ruleta pertenece el giro, cuándo se le asignó, si llegó a utilizarlo y qué premio obtuvo, lo que permite auditar la entrega de premios de cada campaña.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Reporte Ruleta

{% hint style="warning" %}
**Nota:** Únicamente los usuarios con el permiso asignado pueden acceder al módulo y ejecutar consultas. Si no cuenta con este permiso, debe comunicarse con el equipo de soporte.
{% endhint %}

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FVH7cgdwcHbhSCP0d0aJQ%2Fimage.png?alt=media&#x26;token=0b41d6fd-4967-4e8e-bf90-48a23f4430b5" alt=""><figcaption><p>Figura #1: Captura de pantalla Reporte de ruleta.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-ruleta.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los giros registrados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-ruleta.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los giros en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="212">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de Activación</code></strong></td><td>Calendario</td><td>Delimita los resultados según el período en el que se asignó el giro al usuario.</td></tr><tr><td><strong><code>Fecha de Redención</code></strong></td><td>Calendario</td><td>Delimita los resultados según el período en el que el usuario utilizó su giro.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Calendario</td><td>Delimita los resultados según el período en el que vence el giro.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo de texto</td><td>Consulta los giros asignados a un jugador específico mediante su identificador.</td></tr><tr><td><strong><code>ID Ruleta</code></strong></td><td>Campo numérico</td><td>Acota la consulta a una ruleta determinada mediante su identificador interno.</td></tr><tr><td><strong><code>Nombre Ruleta</code></strong></td><td>Campo de texto</td><td>Localiza los giros a partir del nombre con el que se configuró la ruleta.</td></tr><tr><td><strong><code>Estado del Giro</code></strong></td><td>Lista desplegable</td><td>Filtra los giros según la situación en la que se encuentran <em>(Pendiente, Pendiente Rollback, Activa, Redimido o Expirado)</em>. El detalle de cada estado se describe en la tabla de resultados.</td></tr><tr><td><strong><code>Tipo de Premio</code></strong></td><td>Lista desplegable</td><td>Acota la consulta según la clase de premio obtenido <em>(Freebet, Freespin, Bono, Dinero, Premio físico o Giro Extra)</em>.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente los giros del operador seleccionado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente los giros de los usuarios del país seleccionado.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** El uso de filtros es opcional. Si ningún registro cumple los criterios aplicados, la tabla de resultados aparece vacía; para volver a consultar la totalidad de los registros debe presionarse el botón **Limpiar** y ejecutar la búsqueda nuevamente.
{% endhint %}

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los giros que cumplen con los filtros aplicados.

<table><thead><tr><th width="169.33331298828125">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador del jugador al que se asignó el giro.</td></tr><tr><td><strong><code>Nombre Usuario</code></strong></td><td>Texto</td><td>Nombre o alias del jugador.</td></tr><tr><td><strong><code>ID Ruleta</code></strong></td><td>Numérico</td><td>Identificador interno de la ruleta promocional.</td></tr><tr><td><strong><code>Nombre Ruleta</code></strong></td><td>Texto</td><td>Nombre con el que la ruleta se muestra al jugador.</td></tr><tr><td><strong><code>Fecha Activación</code></strong></td><td>Fecha</td><td>Fecha y hora en la que se asignó el giro al jugador.</td></tr><tr><td><strong><code>Fecha Redención</code></strong></td><td>Fecha</td><td>Fecha y hora en la que el jugador utilizó su giro. Aparece vacía mientras el giro no se haya redimido.</td></tr><tr><td><strong><code>Estado del Giro</code></strong></td><td>Texto</td><td>Situación actual del giro dentro de su ciclo de vida.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="186">Estado del Giro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Pendiente</strong></td><td>El giro aún no está disponible para el jugador porque no se ha cumplido la condición configurada para habilitarlo.</td></tr><tr><td><strong>Pendiente Rollback</strong></td><td>El jugador ya realizó el giro, pero este se encuentra en validación y el premio todavía no se confirma.</td></tr><tr><td><strong>Activa</strong></td><td>El giro está habilitado y disponible para que el jugador lo utilice.</td></tr><tr><td><strong>Redimido</strong></td><td>El jugador utilizó el giro. El resultado puede haber entregado un premio o no, según lo que haya caído en la ruleta.</td></tr><tr><td><strong>Expirado</strong></td><td>El giro venció sin que el jugador lo utilizara y ya no puede redimirse.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="174.6666259765625">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Premio Entregado</code></strong></td><td>Texto</td><td>Nombre del premio que obtuvo el jugador con el giro.</td></tr><tr><td><strong><code>Tipo de Premio</code></strong></td><td>Texto</td><td>Clase de beneficio otorgado <em>(Freebet, Freespin, Bono, Dinero, Premio físico o Giro Extra)</em>.</td></tr><tr><td><strong><code>Detalle Premio</code></strong></td><td>Texto</td><td>Información concreta de lo entregado: el ID del bono, el monto o saldo acreditado, o la descripción del premio físico, según corresponda al tipo de premio.</td></tr><tr><td><strong><code>Fecha Expiración</code></strong></td><td>Fecha</td><td>Fecha y hora en la que el giro vence si el jugador no lo utiliza.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Texto</td><td>Operador al que pertenece la ruleta.</td></tr><tr><td><strong><code>País</code></strong></td><td>Texto</td><td>País registrado por el usuario.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Los tres campos de premio se complementan y deben leerse en conjunto: **`Tipo de Premio`** indica de qué clase de beneficio se trata, **`Premio Entregado`** el nombre con el que se configuró en la ruleta, y **`Detalle Premio`** el valor concreto que recibió el jugador.
{% endhint %}

***

### 6. Validaciones y reglas del negocio:

* Únicamente los usuarios con el permiso asignado pueden acceder al módulo y ejecutar consultas.
* No es obligatorio diligenciar ningún filtro para ejecutar la consulta.
* Los resultados mostrados corresponden únicamente a los criterios seleccionados en los filtros.
* Un giro en estado **Redimido** indica que el jugador lo utilizó, no necesariamente que haya obtenido un premio.
* Un giro en estado **Expirado** no puede redimirse ni reactivarse desde este módulo.
* El reporte es informativo: desde este módulo no es posible asignar, anular ni modificar giros ni premios.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>25/08/2025</td><td>Karol Navia</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>19/10/2026</td><td>David Velasquez</td><td>Actualización de formato</td></tr></tbody></table>

</details>
