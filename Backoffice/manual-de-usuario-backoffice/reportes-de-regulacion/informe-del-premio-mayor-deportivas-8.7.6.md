# Informe Del Premio Mayor - Deportivas (8.7.6)

<mark style="color:$info;">Esta sección presenta el</mark> <mark style="color:$info;"></mark><mark style="color:$info;">**Informe del Premio Mayor (Jackpot)**</mark> <mark style="color:$info;"></mark><mark style="color:$info;">de la</mark> [<mark style="color:$info;">vertical</mark>](https://virtualsoft.gitbook.io/plantillas/glosario#vertical) <mark style="color:$info;">Deportivas, elaborado conforme a la regulación de</mark> <mark style="color:$info;"></mark><mark style="color:$info;">**Mincetur - Perú**</mark><mark style="color:$info;">. Muestra la distribución de los premios entre los juegos que aportaron al Jackpot, garantizando transparencia y trazabilidad en cada pago.</mark>

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes de regulación > Informe del Premio Mayor - Deportivas

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (459).png" alt=""><figcaption><p>Figura #1: Captura de pantalla informe del premio mayor - Deportivas.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="informe-del-premio-mayor-deportivas-8.7.6.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Permite definir los criterios de búsqueda para consultar la información del reporte de forma más detallada.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="informe-del-premio-mayor-deportivas-8.7.6.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los pagos del Jackpot en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formato Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

En la parte superior de esta sección se encuentran disponibles los filtros que permiten ajustar la información según las necesidades de consulta.

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Ingresa el periodo de consulta seleccionando una fecha de inicio y una fecha de fin.</td></tr><tr><td><strong><code>ID jugador</code></strong></td><td>Numérico</td><td>Filtra por el identificador único de la cuenta del jugador.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre del jugador.</td></tr><tr><td><strong><code>Tipo Documento</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de documento de identidad del jugador.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Campo de texto</td><td>Filtra por el número de documento del jugador.</td></tr><tr><td><strong><code>ID Jackpot</code></strong></td><td>Numérico</td><td>Filtra por el identificador único del Jackpot creado.</td></tr><tr><td><strong><code>Nombre del juego</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre del juego que aportó al Jackpot.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los resultados del reporte según los filtros aplicados.

<table><thead><tr><th width="218.5">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en que se pagó el premio.</td></tr><tr><td><strong><code>Id del Jackpot</code></strong></td><td>Código único que identifica el Jackpot pagado.</td></tr><tr><td><strong><code>Identificación del jugador ganador</code></strong></td><td>Nombre completo del jugador que ganó el premio mayor.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Tipo de documento de identidad del jugador <em>(DNI, Pasaporte, etc.)</em>.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Número de documento del jugador ganador.</td></tr><tr><td><strong><code>Liga o evento deportivo</code></strong></td><td>Nombre de la liga o evento deportivo que contribuyó al Jackpot.</td></tr><tr><td><strong><code>Monto total ganado</code></strong></td><td>Cantidad exacta que el jugador recibió por ese evento.</td></tr><tr><td><strong><code>Modalidad del sistema progresivo</code></strong></td><td><p>Indica el tipo de Jackpot progresivo asociado al premio.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><em>Un sistema progresivo es un Jackpot cuyo premio crece de forma acumulada: una parte de cada apuesta se suma al pozo hasta que un jugador lo gana.</em></p><p><strong>Ejemplo:</strong> Apuestas Deportivas Múltiple.</p></div></td></tr><tr><td><strong><code>Fecha y hora del pago</code></strong></td><td>Fecha y hora en que se realizó el pago del Jackpot.</td></tr><tr><td><strong><code>Monto inicial del sistema progresivo</code></strong></td><td>Monto con el que se inició el Jackpot en esa liga o evento.</td></tr><tr><td><strong><code>Fecha de inicio del sistema progresivo</code></strong></td><td>Fecha en que se activó ese Jackpot en la <a href="https://virtualsoft.gitbook.io/plantillas/glosario#vertical">vertical</a> de apuestas deportivas.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* El reporte se elabora conforme a la regulación de Mincetur - Perú, lo que garantiza la transparencia y trazabilidad en la distribución de los premios del Jackpot.
* La información mostrada corresponde únicamente a los Jackpots de la [vertical](https://virtualsoft.gitbook.io/plantillas/glosario#vertical) de apuestas Deportivas.
* Cada registro corresponde a un premio efectivamente pagado, con el detalle del juego o evento deportivo que aportó al Jackpot.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>19/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
