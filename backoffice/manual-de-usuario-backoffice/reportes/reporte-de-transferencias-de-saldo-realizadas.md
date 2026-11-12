# Reporte de transferencias de saldo Realizadas

<mark style="color:$info;">Consulta las transferencias de saldo y cupo efectuadas entre los usuarios de la red comercial. Cada registro indica quién realizó la transferencia, sobre qué cupo se aplicó, en qué sentido se movió el dinero y por qué valor, lo que permite hacer seguimiento a la distribución de saldo entre concesionarios, subconcesionarios y puntos de venta.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Transferencias de Saldo Realizadas

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2F7h1fxtKmbEJc5tYWgGCX%2Fimage.png?alt=media&#x26;token=46603cc1-14db-4cb9-8a62-e499a5f973da" alt=""><figcaption><p>Figura #1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-transferencias-de-saldo-realizadas.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar las transferencias registradas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-transferencias-de-saldo-realizadas.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las transferencias en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formato Excel <em>(.XLS)</em> mediante el botón <strong>Exportar</strong>.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo de texto</td><td>Consulta las transferencias asociadas a un usuario específico mediante su identificador.</td></tr><tr><td><strong><code>Nombre del Usuario</code></strong></td><td>Campo de texto</td><td>Localiza las transferencias a partir del nombre del usuario.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Delimita los resultados según el rango de fechas en el que se realizaron las transferencias.</td></tr><tr><td><strong><code>ID Concesionario</code></strong></td><td>Campo de texto</td><td>Acota la consulta al concesionario asociado a la transferencia.</td></tr><tr><td><strong><code>Subconcesionario</code></strong></td><td>Campo de texto</td><td>Restringe la consulta al subconcesionario vinculado a la transferencia.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente las transferencias realizadas en el país seleccionado.</td></tr><tr><td><strong><code>Tipo de Usuario</code></strong></td><td>Lista desplegable</td><td>Filtra los resultados según el perfil del usuario dentro de la red comercial.</td></tr><tr><td><strong><code>Asignado Por</code></strong></td><td>Campo de texto</td><td>Reúne las transferencias ejecutadas por un usuario determinado.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td><p>Determina el nivel de detalle con el que se presenta el reporte.</p><ul><li><strong>Detallado:</strong> muestra cada transferencia de forma individual.</li><li><strong>Totales:</strong> muestra la información consolidada de las transferencias realizadas.</li></ul></td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las transferencias que cumplen con los filtros aplicados.

<table><thead><tr><th width="196">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único de la transferencia.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha</td><td>Fecha y hora en la que se registró la transferencia.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador del usuario cuyo saldo o cupo se vio afectado por la transferencia.</td></tr><tr><td><strong><code>Nombre del Usuario</code></strong></td><td>Texto</td><td>Nombre del usuario correspondiente a la transferencia.</td></tr><tr><td><strong><code>Tipo Cupo</code></strong></td><td>Texto</td><td>Cupo sobre el que se aplicó la transferencia <em>(por ejemplo: apuestas o recargas)</em>.</td></tr><tr><td><strong><code>Tipo Transacción</code></strong></td><td>Texto</td><td>Sentido en el que se movió el saldo para el usuario del registro.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="150">Tipo Transacción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Entrada</strong></td><td>El usuario <strong>recibió</strong> el saldo o cupo. El valor de la transferencia incrementa su disponible.</td></tr><tr><td><strong>Salida</strong></td><td>El usuario <strong>entregó</strong> el saldo o cupo a otro usuario de la red. El valor de la transferencia disminuye su disponible.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="196">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor</code></strong></td><td>Numérico</td><td>Monto transferido en la operación.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Texto</td><td>Moneda en la que se realizó la transferencia.</td></tr><tr><td><strong><code>Asignado Por</code></strong></td><td>Texto</td><td>Usuario que ejecutó la transferencia y asignó el saldo.</td></tr></tbody></table>

{% hint style="info" %}
**Nota:** Una misma transferencia se registra desde la perspectiva del usuario de cada fila. Por esta razón, el campo **`Tipo Transacción`** indica si ese usuario recibió o entregó el saldo, mientras que el campo **`Asignado Por`** identifica siempre a quien ejecutó la operación.
{% endhint %}

{% hint style="warning" %}
**Nota:** Las columnas mostradas corresponden a la vista **Detallado**. Al seleccionar la opción **Totales** en el filtro **`Tipo`**, el reporte presenta la información consolidada y no el detalle de cada transferencia.
{% endhint %}

***

### 6. Validaciones y reglas del negocio:

* No es obligatorio diligenciar todos los filtros para ejecutar la consulta.
* Los resultados mostrados corresponden únicamente a los criterios seleccionados en los filtros.
* Únicamente los usuarios con el permiso asignado pueden consultar y exportar la información de este reporte.
* El contenido de la tabla de resultados varía según la opción seleccionada en el filtro **`Tipo`** _(Detallado o Totales)_.
* El reporte es informativo: las transferencias no pueden modificarse, revertirse ni eliminarse desde este módulo.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>08/10/2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>16/10/2026</td><td>David Velasquez</td><td>Actualización del manual</td></tr></tbody></table>

</details>
