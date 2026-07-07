# Reporte de eventos significativos y alteraciones (Deportivas) (8.7.5)

<mark style="color:$info;">Este reporte permite registrar y monitorear los eventos significativos y las alteraciones ocurridas en la plataforma de apuestas deportivas. Su propósito es facilitar el seguimiento de incidencias críticas, errores de configuración y modificaciones relevantes que puedan afectar la operatividad del sistema.</mark>

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes de regulación > Reporte de eventos significativos y alteraciones (Deportivas) (8.7.5)

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (253).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección Reporte de eventos significativos y alteraciones</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-eventos-significativos-y-alteraciones-deportivas-8.7.5.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Define el criterio de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-eventos-significativos-y-alteraciones-deportivas-8.7.5.md#id-6.-anadir-evento"><strong>Añadir evento</strong></a></td><td>Permite documentar eventos y cambios relevantes de la plataforma para fines de auditoría y seguimiento.</td></tr><tr><td><a href="reporte-de-eventos-significativos-y-alteraciones-deportivas-8.7.5.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según el filtro definido y muestra los eventos registrados en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el periodo de consulta indicando una fecha de inicio y una fecha de fin.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con la información de los eventos registrados según el periodo seleccionado.

<table><thead><tr><th width="221.5">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha y Hora</code></strong></td><td><p>Indica la fecha y hora exacta en la que ocurrió el evento significativo o alteración.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Se genera al menos un registro por día, según la información disponible en el periodo seleccionado.</p></div></td></tr><tr><td><strong><code>Identificación del Evento</code></strong></td><td>Código o nombre que permite identificar el evento registrado.</td></tr><tr><td><strong><code>Usuario(s) Involucrado(s)</code></strong></td><td>Identificación del usuario o usuarios que realizaron y/o autorizaron la acción que generó el evento significativo o alteración.</td></tr><tr><td><strong><code>Motivo/Descripción</code></strong></td><td>Explicación detallada del evento, incluyendo el motivo que lo originó y su impacto en la plataforma.</td></tr><tr><td><strong><code>Valor Antes de la Alteración</code></strong></td><td>Estado o valor de los datos o parámetros antes de la alteración registrada.</td></tr><tr><td><strong><code>Valor Después de la Alteración</code></strong></td><td>Estado o valor de los datos o parámetros después de la alteración registrada.</td></tr></tbody></table>

***

### 6. Añadir evento

Permite registrar manualmente eventos significativos, incidencias o alteraciones identificadas en la plataforma. Al seleccionar el botón **Añadir Evento**, se abrirá un formulario para diligenciar los campos

<table><thead><tr><th width="151.962890625">Campo</th><th width="103.888916015625">Tipo</th><th width="464.72528076171875">Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha y Hora</code></strong></td><td>Fecha y hora</td><td>Indica la fecha y hora en la que ocurrió el evento significativo o la alteración que se desea registrar.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Texto / Numérico</td><td>Identificador único del usuario que ejecutó, realizó o autorizó la acción que generó el evento o la alteración.</td></tr><tr><td><strong><code>Valor Antes de la Alteración</code></strong></td><td>Texto</td><td>Registra el valor, configuración o estado existente antes de realizar la modificación.</td></tr><tr><td><strong><code>Valor Después de la Alteración</code></strong></td><td>Texto</td><td>Registra el valor, configuración o estado resultante después de aplicar la modificación.</td></tr><tr><td><strong><code>Motivo / Descripción</code></strong></td><td>Texto largo</td><td>Permite describir el evento o alteración realizada, indicando su causa, alcance o cualquier información relevante para su seguimiento y auditoría.</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* Es obligatorio seleccionar un periodo de fechas para ejecutar la consulta.
* El reporte registra los eventos significativos y alteraciones de la plataforma de apuestas deportivas, conservando el detalle de los valores antes y después de cada cambio.
* Cada registro identifica el evento, el usuario involucrado y el motivo o impacto de la alteración.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>19/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
