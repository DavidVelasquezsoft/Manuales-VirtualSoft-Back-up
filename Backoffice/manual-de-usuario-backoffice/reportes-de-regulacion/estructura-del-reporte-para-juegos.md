---
description: >-
  Este reporte proporciona un desglose detallado de las jugadas realizadas en
  casino, casino en vivo y juegos virtuales, permitiendo el seguimiento de las
  transacciones asociadas a cada jugador.
---

# Estructura del Reporte para Juegos

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes de regulación > Estructura del Reporte para Juegos

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (684).png" alt=""><figcaption><p>Figura#1: Captura de pantalla reporte estructura del reporte para juegos.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="estructura-del-reporte-para-juegos.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Permite definir los criterios de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="estructura-del-reporte-para-juegos.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td><p>Ejecuta la búsqueda según los filtros definidos y muestra las jugadas registradas en la tabla de resultados.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Para habilitar la consulta se debe ingresar primero el filtro ID del jugador obligatoriamente.</p></div></td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Periodo (</code></strong><em><strong><code>Fecha</code></strong></em><strong><code>)</code></strong></td><td>Rango de fechas</td><td><p>Permite delimitar el periodo de consulta seleccionando una fecha de inicio y una fecha de fin.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Solo se mostrarán las transacciones registradas dentro del rango definido.</p></div></td></tr><tr><td><strong><code>Nombre completo del jugador</code></strong></td><td>Campo de texto</td><td>Permite buscar las jugadas por el nombre completo del usuario, tal como está registrado en la plataforma.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Lista desplegable</td><td>Filtra por el tipo de documento de identidad asociado al jugador.</td></tr><tr><td><strong><code>Número del documento</code></strong></td><td>Campo de texto</td><td>Permite filtrar por el número de identificación del jugador.</td></tr><tr><td><strong><code>ID del jugador</code></strong></td><td>Campo de texto</td><td><p>Indica el identificador único del jugador dentro de la plataforma. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo es <strong>obligatorio</strong> para ejecutar la consulta.</p></div></td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior se despliega una tabla con el detalle de las jugadas que cumplen con los filtros aplicados. Cada fila corresponde a una transacción registrada.

<table><thead><tr><th width="190.22900390625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se generó la apuesta.</td></tr><tr><td><strong><code>ID del jugador</code></strong></td><td>Código único asignado al cliente dentro de la plataforma.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Nombre completo del usuario que realizó la jugada.</td></tr><tr><td><strong><code>Nombre del juego</code></strong></td><td>Nombre del juego asociado a la apuesta <em>(por ejemplo: Ruleta, Blackjack, etc.)</em>.</td></tr><tr><td><strong><code>Tipo de juego</code></strong></td><td>Categoría a la que pertenece el juego <em>(casino, casino en vivo o juegos virtuales)</em>.</td></tr><tr><td><strong><code>ID de apuesta</code></strong></td><td>Número único que identifica cada apuesta registrada.</td></tr><tr><td><strong><code>Fecha de la transacción</code></strong></td><td>Fecha y hora de la última modificación de la apuesta, según su estado.</td></tr><tr><td><strong><code>Tipo de transacción</code></strong></td><td>Clasificación de la transacción realizada.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Valor de la transacción, expresado en la moneda de la plataforma.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Indica la situación actual de la apuesta. Puede tomar uno de los siguientes valores:</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="121.40740966796875">Estado</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Abierta</strong></td><td>La apuesta ha sido registrada y se encuentra pendiente de resolución.</td></tr><tr><td><strong>Cerrada</strong></td><td>La apuesta ya fue procesada y cuenta con un resultado definitivo.</td></tr><tr><td><strong>Rechazada</strong></td><td>La apuesta no fue aceptada por el sistema y no participó en el proceso de juego.</td></tr><tr><td><strong>Devuelta</strong></td><td>El importe de la apuesta fue reembolsado al jugador.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, no será visible en el sistema.
* El campo **ID del jugador** es obligatorio para ejecutar la consulta.
* El reporte consolida las jugadas de casino, casino en vivo y juegos virtuales en una sola vista.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>19/06/2026</td><td>David velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
