# Reporte de las transacciones realizadas por cada jugador (Retiros)

<mark style="color:$info;">Este reporte permite visualizar y analizar las transacciones de retiro realizadas por cada jugador dentro de la plataforma. Su objetivo es brindar un registro detallado de las solicitudes de retiro, su estado y los métodos utilizados.</mark>

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes de regulación > Reporte de las transacciones realizadas por cada jugador (Retiros)

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (358).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección reporte de las transacciones realizadas por cada jugador.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-las-transacciones-realizadas-por-cada-jugador-retiros.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-las-transacciones-realizadas-por-cada-jugador-retiros.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las transacciones de retiro en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.<em>XLS</em>) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="190.59259033203125">Campo</th><th width="116.8148193359375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el periodo de consulta indicando una fecha de inicio y una fecha de fin.</td></tr><tr><td><strong><code>ID del jugador</code></strong></td><td>Numérico</td><td>Indica el código único asignado a cada jugador.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de identificación del jugador <em>(DNI, pasaporte, cédula, etc.)</em>.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Campo de texto</td><td>Corresponde al número del documento de identidad del jugador.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre completo del jugador.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con la información de las transacciones de retiro según los filtros aplicados.

<table><thead><tr><th width="208.870361328125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se registró la transacción.</td></tr><tr><td><strong><code>Identificador Único del Jugador</code></strong></td><td>Código único asignado a cada jugador dentro del sistema.</td></tr><tr><td><strong><code>Nombre del Jugador</code></strong></td><td>Nombre completo del jugador.</td></tr><tr><td><strong><code>Tipo de Documento</code></strong></td><td>Tipo de identificación registrado <em>(DNI, pasaporte, cédula, etc.)</em>.</td></tr><tr><td><strong><code>Número de Documento</code></strong></td><td>Número de identificación del jugador.</td></tr><tr><td><strong><code>Fecha de Solicitud</code></strong></td><td>Fecha en la que el jugador solicitó el retiro de fondos.</td></tr><tr><td><strong><code>Fecha de Resolución</code></strong></td><td>Fecha en la que se procesó y resolvió la solicitud de retiro.</td></tr><tr><td><strong><code>Monto del Retiro</code></strong></td><td>Cantidad retirada por el jugador.</td></tr><tr><td><strong><code>Forma de Retiro</code></strong></td><td>Método utilizado para retirar los fondos <em>(transferencia bancaria,</em> <a href="https://virtualsoft.gitbook.io/plantillas/glosario#billetera">billetera electrónica</a><em>, punto de venta, etc.)</em>.</td></tr><tr><td><strong><code>Estado del Retiro</code></strong></td><td>Indica el estado actual de la solicitud de retiro. Puede tomar uno de los siguientes valores:</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="116.22222900390625">Estado</th><th width="389.70526123046875">Descripción</th></tr></thead><tbody><tr><td><strong>Pendiente</strong></td><td>La solicitud de retiro fue registrada y está a la espera de revisión.</td></tr><tr><td><strong>En proceso</strong></td><td>La solicitud está siendo gestionada antes de su resolución final.</td></tr><tr><td><strong>Aprobado</strong></td><td>La solicitud fue aceptada y el retiro de fondos autorizado.</td></tr><tr><td><strong>Rechazado</strong></td><td>La solicitud no fue aprobada, por lo que el retiro no se procesó y los fondos fueron reintegrados al saldo del usuario.</td></tr><tr><td><strong>Eliminado</strong></td><td>La solicitud de retiro fue cancelada o anulada antes de resolverse generalmente a solicitud del propio jugador o por acción de un operador, por lo que no continuó el proceso y los fondos fueron reintegrados al saldo del usuario.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* Es obligatorio seleccionar un periodo de fechas para ejecutar la consulta.
* El reporte muestra únicamente las transacciones de retiro realizadas por los jugadores dentro de la plataforma.
* Cada registro detalla la solicitud de retiro, su estado y el método utilizado.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>19/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
