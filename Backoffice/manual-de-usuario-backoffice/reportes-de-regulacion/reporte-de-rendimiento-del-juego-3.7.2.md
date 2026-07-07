# Reporte de rendimiento del juego (3.7.2)

<mark style="color:$info;">El Reporte de Rendimiento del Juego proporciona información detallada sobre el desempeño de los juegos de casino, permitiendo analizar su comportamiento dentro de un periodo determinado a partir de distintos criterios de búsqueda.</mark>

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes de regulación > Reporte de Rendimiento del Juego

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (371).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección reporte de rendimiento del juego.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-rendimiento-del-juego-3.7.2.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Permite definir los criterios de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-rendimiento-del-juego-3.7.2.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra el rendimiento de los juegos en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite <strong>exportar</strong> los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="180.9630126953125">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Ingresa el periodo de consulta seleccionando una fecha de inicio y una fecha de fin.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Campo de texto</td><td>Filtra por el identificador único del juego.</td></tr><tr><td><strong><code>Nombre del Juego</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre del juego.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país sobre el cual se realizará la consulta de los juegos.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con la información correspondiente a los juegos que cumplen con los filtros aplicados.

<table><thead><tr><th width="190.22900390625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Indica la fecha de los registros, siempre que exista un evento relacionado con el juego dentro del periodo seleccionado.</td></tr><tr><td><strong><code>Nombre del Juego</code></strong></td><td>Denominación del juego o modalidad específica.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Clasificación del juego <em>(Rodillo, Blackjack, Póker, Mesa, etc.)</em>.</td></tr><tr><td><strong><code>% Retorno Real</code></strong></td><td><p>Porcentaje del dinero apostado que se devuelve a los jugadores en forma de premios, calculado sobre los juegos que operan <strong>contra la casa</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><em>Un juego "contra la casa" es aquel en el que el jugador apuesta directamente frente al operador como la ruleta, las tragamonedas o el blackjack y no contra otros jugadores. En estos juegos los premios los paga el operador, por lo que este porcentaje muestra qué parte de lo apostado regresa al jugador.</em></p></div><p><strong>Fórmula:</strong><br><em>% Retorno Real = (Total de Premios / Total de Apuestas) × 100</em></p></td></tr><tr><td><strong><code>Total de Apuestas</code></strong></td><td>Monto total apostado, incluyendo apuestas con bonificaciones, comisiones y derechos de inscripción, según corresponda.</td></tr><tr><td><strong><code>Total de Apuestas por Bonificación</code></strong></td><td>Monto total de apuestas realizadas utilizando bonificaciones <em>(saldo promocional otorgado al jugador, no dinero propio)</em>.</td></tr><tr><td><strong><code>Total de Premios</code></strong></td><td>Monto total de premios pagados a los jugadores, incluyendo premios obtenidos por bonificaciones y/o premios progresivos, según corresponda.</td></tr><tr><td><strong><code>Total de Premios por Bonificación</code></strong></td><td>Monto total de premios otorgados a los jugadores a través de bonificaciones.</td></tr><tr><td><strong><code>Total de Devoluciones</code></strong></td><td>Monto total de las devoluciones realizadas a los jugadores.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, no será visible en el sistema.
* Este reporte presenta la información a día vencido, por lo que solo incluye datos de fechas ya cerradas; no se muestra información del día actual.
* El campo **% Retorno Real** aplica únicamente a los juegos que operan contra la casa y no contra otros jugadores.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>19/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
