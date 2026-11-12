# Reporte de limitaciones

<mark style="color:$info;">Consulta las limitaciones que los usuarios se han establecido a sí mismos desde la plataforma de usuarios online. Una limitación es un mecanismo de autocontrol con el que el jugador restringe su propia actividad. En este reporte se consulta el detalle de las limitaciones creadas, modificadas o finalizadas, junto con su vigencia y su estado actual.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Reporte de limitaciones

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FV5GsMvZIQnekrAze3EtL%2Fimage.png?alt=media&#x26;token=07feb575-aee8-41ec-b61c-e1f96116ef64" alt=""><figcaption><p>Figura #1: Captura de pantalla del Reporte de limitaciones.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-limitaciones.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar las limitaciones registradas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-limitaciones.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las limitaciones en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="212">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Limitación</code></strong></td><td>Campo numérico</td><td>Localiza una limitación puntual a partir de su identificador.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Consulta las limitaciones establecidas por un usuario específico.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Campo de texto</td><td>Localiza las limitaciones a partir del correo asociado a la cuenta del usuario.</td></tr><tr><td><strong><code>Tipo de limitación</code></strong></td><td>Lista desplegable</td><td>Acota la consulta según la clase de restricción que el usuario se estableció <em>(por ejemplo: depósito, sesión o apuesta)</em>.</td></tr><tr><td><strong><code>Fecha y hora</code></strong></td><td>Calendario</td><td>Delimita los resultados según el momento en el que el usuario creó la limitación.</td></tr><tr><td><strong><code>Fecha en que finaliza</code></strong></td><td>Calendario</td><td>Delimita los resultados según el momento en el que la limitación deja de estar vigente.</td></tr><tr><td><strong><code>Fecha modificó</code></strong></td><td>Calendario</td><td>Delimita los resultados según el momento en el que la limitación fue modificada por última vez.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra las limitaciones según su situación actual <em>(Activo, Inactivo o Cancelado)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las limitaciones que cumplen con los filtros aplicados.

{% hint style="warning" %}
**Nota:** Los campos **`Valor`** y **`Horas`** no se diligencian al tiempo: cuál de los dos se utiliza depende del **`Tipo`** de limitación. Las que restringen dinero _(como el límite de depósito)_ registran el monto en **`Valor`**, mientras que las que restringen tiempo _(como el límite de sesión)_ lo registran en **`Horas`**.
{% endhint %}

<table><thead><tr><th width="212">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único de la limitación.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador del usuario que estableció la limitación.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Texto</td><td>Correo electrónico asociado a la cuenta del usuario.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Texto</td><td>Clase de restricción establecida por el usuario <em>(por ejemplo: límite de depósito o límite de tiempo en sesión)</em>.</td></tr><tr><td><strong><code>Fecha y hora</code></strong></td><td>Fecha</td><td>Momento en el que el usuario creó la limitación.</td></tr><tr><td><strong><code>Fecha en que finaliza</code></strong></td><td>Fecha</td><td>Momento en el que la limitación deja de estar vigente.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Numérico</td><td>Monto configurado como límite, cuando la limitación restringe una cantidad de dinero.</td></tr><tr><td><strong><code>Horas</code></strong></td><td>Numérico</td><td>Cantidad de horas configuradas, cuando la limitación restringe un período de tiempo.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Situación actual de la limitación.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="150">Estado</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Activo</strong></td><td>La limitación está vigente y restringe la actividad del usuario según lo configurado.</td></tr><tr><td><strong>Inactivo</strong></td><td>La limitación cumplió su período de vigencia y dejó de aplicarse.</td></tr><tr><td><strong>Cancelado</strong></td><td>La limitación se dio por terminada antes de su fecha de finalización y ya no restringe la actividad del usuario.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="212">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha modificación</code></strong></td><td>Fecha</td><td>Momento del último cambio registrado sobre la limitación, ya sea realizado por el usuario o por el sistema.</td></tr><tr><td><strong><code>Observación</code></strong></td><td>Texto</td><td>Comentarios o notas registradas sobre la limitación, cuando aplique.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* No es obligatorio diligenciar todos los filtros para ejecutar la consulta.
* Los resultados mostrados corresponden únicamente a los criterios seleccionados en los filtros.
* Las limitaciones son creadas por el propio usuario desde la plataforma de usuarios online; no se generan desde el BackOffice.
* Una limitación creada no puede eliminarse: únicamente puede modificarse o cancelarse según las políticas establecidas, y en ambos casos el registro se conserva en el reporte.
* El sistema registra automáticamente las fechas de creación, modificación y finalización de cada limitación.
* Las limitaciones en estado **Activo** afectan directamente la operación del usuario, restringiendo sus depósitos, su tiempo de sesión o sus apuestas según el tipo configurado.
* El reporte es informativo: desde este módulo no es posible crear, modificar ni cancelar una limitación.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/10/2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>19/10/2026</td><td>David Velasquez</td><td>Actualización de formato</td></tr></tbody></table>

</details>
