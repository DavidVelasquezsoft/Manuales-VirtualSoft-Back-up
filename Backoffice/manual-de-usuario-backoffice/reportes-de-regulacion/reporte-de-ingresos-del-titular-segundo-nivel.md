# Reporte de ingresos del titular (Segundo Nivel)

<mark style="color:$info;">Este reporte permite visualizar de manera detallada los ingresos generados a partir de las apuestas deportivas realizadas por los jugadores dentro de la plataforma. Al ser un reporte de segundo nivel, proporciona un desglose específico de cada transacción, permitiendo un análisis más preciso de la actividad de los usuarios.</mark>

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes de regulación > Reporte de ingresos del titular (Deportivas) — Segundo Nivel

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (386).png" alt=""><figcaption><p>Figura#1: Captura de pantalla reporte de ingresos del titular (Segundo Nivel).</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-ingresos-del-titular-segundo-nivel.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-ingresos-del-titular-segundo-nivel.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra el detalle de las transacciones en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el periodo de consulta indicando una fecha de inicio y una fecha de fin.</td></tr><tr><td><strong><code>ID del jugador</code></strong></td><td>Numérico</td><td>Indica el código único asignado a cada jugador dentro de la plataforma para su identificación.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de documento de identidad del jugador <em>(DNI, pasaporte, etc.)</em>.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Campo de texto</td><td>Corresponde al número del documento de identidad del jugador, utilizado para verificar su identidad dentro del sistema.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre completo del usuario registrado en la plataforma.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con la información detallada de las transacciones según los filtros aplicados.

<table><thead><tr><th width="248.5">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se registró la transacción.</td></tr><tr><td><strong><code>Identificador único de la transacción</code></strong></td><td>Código único que identifica cada transacción dentro del sistema.</td></tr><tr><td><strong><code>Identificador único del jugador</code></strong></td><td>Código único asignado a cada jugador dentro de la plataforma.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Nombre completo del usuario.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Tipo de documento de identidad del jugador <em>(DNI, pasaporte, etc.)</em>.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Número del documento de identidad del jugador.</td></tr><tr><td><strong><code>Nombre del deporte</code></strong></td><td><p>Deporte en el que se realizó la apuesta.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo muestra el identificador único del deporte y no su nombre textual.</p></div></td></tr><tr><td><strong><code>Nombre de la competencia</code></strong></td><td>Nombre del torneo o liga en la que se llevó a cabo el evento deportivo.</td></tr><tr><td><strong><code>Nombre del evento</code></strong></td><td>Descripción del evento específico en el que se realizó la apuesta.</td></tr><tr><td><strong><code>Nombre del mercado</code></strong></td><td>Tipo de apuesta realizada dentro del evento.</td></tr><tr><td><strong><code>Selección</code></strong></td><td>Elección específica del jugador dentro del mercado de apuesta.</td></tr><tr><td><strong><code>Apuesta</code></strong></td><td>Monto total apostado por el jugador en el evento.</td></tr><tr><td><strong><code>Premio</code></strong></td><td>Monto total ganado por el jugador en caso de que la apuesta haya resultado acertada.</td></tr><tr><td><strong><code>Cuota</code></strong></td><td><p>Factor multiplicador de la apuesta según el mercado seleccionado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La cuota actúa como un multiplicador del monto apostado: a mayor cuota, mayor es el premio potencial.</p></div></td></tr><tr><td><strong><code>Fecha de ticket</code></strong></td><td>Fecha y hora en la que se registró la apuesta dentro del sistema.</td></tr><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Fecha y hora de inicio del evento deportivo.</td></tr><tr><td><strong><code>Fecha de fin</code></strong></td><td>Fecha y hora de finalización del evento deportivo.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* Es obligatorio seleccionar un periodo de fechas para ejecutar la consulta.
* El reporte presenta el detalle de los ingresos generados por las apuestas deportivas de cada jugador, desglosado por evento, mercado y selección.
* Cada registro corresponde a una selección dentro de un evento deportivo apostado.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
