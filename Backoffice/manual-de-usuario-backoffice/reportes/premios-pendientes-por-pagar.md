# Premios pendientes por pagar

<mark style="color:$info;">Este reporte permite consultar los premios que se encuentran pendientes por pagar, mostrando el valor apostado y el valor de los premios según el país, la moneda y el punto de venta, con la posibilidad de analizarlos en una vista resumida o detallada.</mark>

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Premios pendientes por pagar

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (579).png" alt=""><figcaption></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="premios-pendientes-por-pagar.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información del reporte y permiten seleccionar el nivel de detalle de los resultados entre vista <a href="premios-pendientes-por-pagar.md#resumido">resumida</a> o <a href="premios-pendientes-por-pagar.md#detallado">detallada</a>.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="premios-pendientes-por-pagar.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los premios en la vista seleccionada.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="118.54541015625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td><p>Permite seleccionar el periodo de consulta.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La vista detallada solo permite consultar un día específico, mientras que la vista resumida permite consultar por un rango de fechas.</p></div></td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país a consultar.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra los premios según su estado <em>(Todas, Expiradas o No expiradas)</em>.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Define si la información se mostrará en modo <a href="premios-pendientes-por-pagar.md#resumido"><strong>Resumido</strong></a> o <a href="premios-pendientes-por-pagar.md#detallado"><strong>Detallado</strong></a>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega la información de los premios pendientes por pagar según los filtros aplicados. El reporte cuenta con dos vistas que pueden seleccionarse mediante el filtro **Tipo**, según el nivel de detalle requerido.

{% hint style="info" %}
En la parte inferior de la tabla se muestran las filas de totales, que consolidan la suma de cada columna numérica del reporte.
{% endhint %}

{% tabs %}
{% tab title="Resumido" %}
La vista resumida presenta los resultados de forma consolidada, agrupados por diferentes niveles: primero por moneda y luego por punto de venta. Ofrece una visión general de los montos pendientes con las siguientes columnas:

<table><thead><tr><th width="212.00006103515625">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha en la que se generó la apuesta asociada a los premios pendientes.</td></tr><tr><td><strong><code>Valor Apostado</code></strong></td><td>Monto total apostado en las apuestas cuyos premios se encuentran pendientes por pagar.</td></tr><tr><td><strong><code>Valor Premio</code></strong></td><td>Monto total de los premios que permanecen pendientes por pagar.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detallado" %}
La vista detallada presenta los resultados con mayor nivel de información, mostrando una fila por cada premio pendiente con las siguientes columnas:

<table><thead><tr><th width="206.166748046875">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>No. Ticket</code></strong></td><td>Identificador único del ticket asociado a la apuesta.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha en la que se creó la apuesta.</td></tr><tr><td><strong><code>Hora de Creación</code></strong></td><td>Hora exacta en la que se generó la apuesta.</td></tr><tr><td><strong><code>Fecha Premio</code></strong></td><td>Fecha en la que se otorgó el premio.</td></tr><tr><td><strong><code>Hora Premio</code></strong></td><td>Hora exacta en la que se concedió el premio.</td></tr><tr><td><strong><code>Valor Apostado</code></strong></td><td>Monto apostado en la apuesta cuyo premio se encuentra pendiente por pagar.</td></tr><tr><td><strong><code>Valor Premio</code></strong></td><td>Monto del premio que se encuentra pendiente por pagar.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda en la que se registró la apuesta y su respectivo premio.</td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Terminal o ubicación física donde se realizó la apuesta.</td></tr><tr><td><strong><code>Fecha Caducidad Pago</code></strong></td><td>Fecha límite hasta la cual el usuario puede reclamar el premio antes de que caduque.</td></tr><tr><td><strong><code>Caducó</code></strong></td><td>Indica si el premio superó su fecha límite de pago y ya no puede ser reclamado.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* No es necesario completar todos los filtros para realizar una búsqueda.
* Los resultados dependen del tipo de vista seleccionado (_**Resumido** o **Detallado**_).
* En la vista **detallada** solo es posible consultar un día específico; en la vista **resumida** se puede consultar por un rango de fechas.
* En la parte inferior de la tabla se muestran las filas con los totales de cada columna numérica.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="98.3333740234375">Versión</th><th width="137.16668701171875">Fecha</th><th width="148">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>10/09/2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>10/07/2026</td><td>David Velasquez</td><td>Actualización y refinamiento del manual</td></tr></tbody></table>

</details>
