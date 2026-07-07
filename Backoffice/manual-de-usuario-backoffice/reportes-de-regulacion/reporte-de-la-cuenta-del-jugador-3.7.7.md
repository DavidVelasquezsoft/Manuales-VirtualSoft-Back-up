# Reporte de la cuenta del jugador (3.7.7)

<mark style="color:$info;">Este reporte permite visualizar el estado y la actividad de la cuenta de un jugador dentro de la plataforma de casino, proporcionando información detallada sobre su registro, estado y restricciones.</mark>

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes de regulación > Reporte de la cuenta del jugador (3.7.7)

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (204).png" alt=""><figcaption><p>Figura#1: Captura de pantalla reporte de la cuenta del jugador.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-la-cuenta-del-jugador-3.7.7.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-la-cuenta-del-jugador-3.7.7.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra la información de la cuenta en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el periodo en el que se desea consultar la información de la cuenta.</td></tr><tr><td><strong><code>ID del jugador</code></strong></td><td>Numérico</td><td>Indica el código único asignado al usuario dentro de la plataforma.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de identificación del jugador <em>(DNI, cédula de extranjería, pasaporte, etc.)</em>.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Campo de texto</td><td>Corresponde al número de identificación del jugador, utilizado para verificar su identidad.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre completo del usuario registrado en la plataforma.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con la información de la cuenta del jugador según los filtros aplicados.

<table><thead><tr><th width="190.7222900390625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Día en el que se registró la transacción o evento asociado a la cuenta.</td></tr><tr><td><strong><code>Identificador único del jugador</code></strong></td><td>Código exclusivo asignado a cada usuario dentro de la plataforma.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Nombre completo del usuario.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Tipo de identificación utilizada por el jugador.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Número de identificación personal del jugador.</td></tr><tr><td><strong><code>Fecha de registro</code></strong></td><td>Día en que el jugador creó su cuenta en la plataforma.</td></tr><tr><td><strong><code>Fecha de términos y condiciones</code></strong></td><td>Fecha en la que el jugador aceptó los términos y condiciones del servicio.</td></tr><tr><td><strong><code>Estado de la cuenta</code></strong></td><td>Indica la condición actual de la cuenta. Puede ser:</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="121.40740966796875">Estado</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Activa</strong></td><td>La cuenta se encuentra habilitada y el jugador puede acceder y operar con normalidad.</td></tr><tr><td><strong>Suspendida</strong></td><td>La cuenta se encuentra temporalmente inhabilitada, por lo que el jugador no puede operar mientras dure la suspensión.</td></tr><tr><td><strong>Cerrada</strong></td><td>La cuenta fue cerrada por solicitud del jugador o por decisión del operador.</td></tr><tr><td><strong>Limitada</strong></td><td>La cuenta presenta restricciones parciales que condicionan algunas de sus operaciones.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="190.72222900390625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Día en el que se aplicó una exclusión o limitación en la cuenta.</td></tr><tr><td><strong><code>Fecha de fin</code></strong></td><td>Día en el que finaliza la exclusión o limitación aplicada.</td></tr><tr><td><strong><code>Motivo</code></strong></td><td>Razón por la cual la cuenta presenta restricciones o cambios en su estado.</td></tr><tr><td><strong><code>Tipo de exclusión/limitación</code></strong></td><td>Clasificación de la restricción impuesta al usuario <em>(ejemplo:</em> <a href="https://virtualsoft.gitbook.io/plantillas/glosario#autoexclusion">autoexclusión</a><em>)</em>.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* Es obligatorio seleccionar un periodo de fechas para ejecutar la consulta.
* El reporte muestra el estado y la actividad de la cuenta del jugador dentro de la plataforma de casino.
* Cada registro corresponde a un evento o cambio asociado al estado de la cuenta dentro del periodo consultado.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
