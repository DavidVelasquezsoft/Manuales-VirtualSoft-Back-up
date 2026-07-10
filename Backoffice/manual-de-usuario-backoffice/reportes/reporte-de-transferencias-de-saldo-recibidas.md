---
description: >-
  Este reporte permite consultar las transferencias de saldo que ha recibido un
  usuario, mostrando el detalle de cada transacción o su información consolidada
  según el tipo de vista seleccionado.
---

# Reporte de transferencias de saldo Recibidas

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Transferencias de Saldo Recibidas

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (600).png" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte de transferencias de saldo recibidas.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-transferencias-de-saldo-recibidas.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información del reporte y permiten seleccionar el nivel de detalle de los resultados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-transferencias-de-saldo-recibidas.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las transferencias en la vista seleccionada.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formato Excel mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="150">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Indica el identificador único del usuario que recibió la transferencia.</td></tr><tr><td><strong><code>Nombre del Usuario</code></strong></td><td>Campo de texto</td><td>Permite buscar por el nombre del usuario receptor de la transferencia.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Filtra las transferencias realizadas dentro del periodo seleccionado.</td></tr><tr><td><strong><code>ID Concesionario</code></strong></td><td>Numérico</td><td>Indica el identificador del concesionario asociado a la transferencia.</td></tr><tr><td><strong><code>Subconcesionario</code></strong></td><td>Campo de texto</td><td>Filtra por el subconcesionario relacionado con la transferencia.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país donde se efectuó la transferencia.</td></tr><tr><td><strong><code>Tipo de Usuario</code></strong></td><td>Lista desplegable</td><td>Clasifica al usuario según su perfil o rol dentro del sistema.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Define de qué forma se visualizará el reporte, en modo <a href="reporte-de-transferencias-de-saldo-recibidas.md#detallado-1"><strong>Detallado</strong></a> o <a href="reporte-de-transferencias-de-saldo-recibidas.md#totales-1"><strong>Totales</strong></a>.</td></tr><tr><td><strong><code>Asignado Por</code></strong></td><td>Campo de texto</td><td>Permite buscar las transferencias según el usuario que asignó el saldo.</td></tr><tr><td><strong><code>Id transacción</code></strong></td><td>Numérico</td><td>Indica el identificador de la transacción que se desea consultar.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega la información de las transferencias según los filtros aplicados. El reporte cuenta con dos vistas que pueden seleccionarse mediante el filtro **Tipo**, según el nivel de detalle requerido.

{% tabs %}
{% tab title="Detallado" %}
La vista detallada presenta una fila por cada transferencia recibida, con las siguientes columnas:

<table><thead><tr><th width="201">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Número único que identifica cada transferencia de saldo.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha y hora en la que se realizó la transferencia.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario receptor de la transferencia.</td></tr><tr><td><strong><code>Nombre del Usuario</code></strong></td><td>Nombre del usuario que recibió el saldo.</td></tr><tr><td><strong><code>Tipo Cupo</code></strong></td><td>Clasificación del cupo transferido <em>(por ejemplo: recarga, juego, apuestas, etc.)</em>.</td></tr><tr><td><strong><code>Tipo Transacción</code></strong></td><td>Tipo de transacción realizada <em>(por ejemplo: depósito, retiro, etc.)</em>.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto total transferido en la transacción.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Tipo de moneda utilizada en la transferencia.</td></tr><tr><td><strong><code>Información de banco</code></strong></td><td>Información del banco con el que se generó la transacción.</td></tr><tr><td><strong><code>Id transacción</code></strong></td><td>Identificador de la transacción realizada.</td></tr></tbody></table>
{% endtab %}

{% tab title="Totales" %}
La vista de totales presenta la información consolidada, agrupando los resultados por usuario según los criterios de búsqueda seleccionados. Muestra las siguientes columnas:

<table><thead><tr><th width="155">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Asignado por</code></strong></td><td>Usuario que asignó o realizó la transferencia del saldo.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha correspondiente a las transferencias consolidadas.</td></tr><tr><td><strong><code>Tipo cupo</code></strong></td><td>Clasificación del cupo transferido <em>(por ejemplo: recarga, juego, apuestas, etc.)</em>.</td></tr><tr><td><strong><code>Tipo transacción</code></strong></td><td>Tipo de transacción realizada <em>(por ejemplo: entrada, salida, etc.)</em>.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto total consolidado de las transferencias.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Tipo de moneda utilizada en las transferencias.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* No es obligatorio completar todos los filtros para realizar una búsqueda.
* La información mostrada depende de los filtros seleccionados y del tipo de vista (_**Detallado** o **Totales**_).
* Solo los usuarios con permisos adecuados pueden acceder o exportar los datos.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="98.3333740234375">Versión</th><th width="137.16668701171875">Fecha</th><th width="148">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>08/10/2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>10/07/2026</td><td>David Velasquez</td><td>Actualización y refinamiento del manual</td></tr></tbody></table>

</details>
