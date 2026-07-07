---
description: >-
  Este reporte permite consultar el historial y estado actual de la cuenta de un
  jugador dentro de la plataforma, proporcionando información detallada sobre su
  registro, estado, restricciones.
---

# Reporte de la cuenta del jugador (Deportivas) (8.7.8)

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes de regulación > Reporte de la cuenta del jugador (Deportivas) (8.7.8)

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (360).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección Reporte de la cuenta del jugador </p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-la-cuenta-del-jugador-deportivas-8.7.8.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-la-cuenta-del-jugador-deportivas-8.7.8.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra la información de la cuenta en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="192.81488037109375">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el periodo de consulta indicando una fecha de inicio y una fecha de fin.</td></tr><tr><td><strong><code>ID del jugador</code></strong></td><td>Numérico</td><td>Indica el código único asignado a cada jugador.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de identificación del jugador <em>(DNI, pasaporte, cédula, etc.)</em>.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Campo de texto</td><td>Corresponde al número del documento de identidad del jugador.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre completo del jugador.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con la información de la cuenta del jugador según los filtros aplicados.

<table><thead><tr><th width="190.7222900390625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td><p>Fecha en la que se registró un cambio en la cuenta del jugador.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Se genera uno o más registros siempre que exista un evento relacionado con el estado de la cuenta dentro del periodo seleccionado.</p></div></td></tr><tr><td><strong><code>Identificador único del jugador</code></strong></td><td>Código único asignado a cada jugador dentro del sistema.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Nombre completo del jugador.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Tipo de identificación del jugador <em>(DNI, pasaporte, cédula, etc.)</em>.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Número del documento de identidad del jugador.</td></tr><tr><td><strong><code>Fecha de registro</code></strong></td><td>Fecha y hora en la que se creó la cuenta de juego.</td></tr><tr><td><strong><code>Fecha de términos y condiciones</code></strong></td><td>Fecha en la que el jugador aceptó los términos y condiciones del titular y la política de privacidad.</td></tr><tr><td><strong><code>Estado de la cuenta</code></strong></td><td>Indica el estado actual de la cuenta de juego. Puede ser:</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="93.111083984375">Estado</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Activa</strong></td><td>La cuenta se encuentra habilitada y el jugador puede acceder y operar con normalidad.</td></tr><tr><td><strong>Inactiva</strong></td><td>La cuenta no registra actividad reciente, pero permanece habilitada para el jugador.</td></tr><tr><td><strong>Cerrada</strong></td><td>La cuenta fue cerrada por solicitud del jugador o por decisión del operador.</td></tr><tr><td><strong>Excluida</strong></td><td>La cuenta se encuentra restringida temporal o permanentemente de acuerdo con las políticas aplicables.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="190.72222900390625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Fecha y hora en la que se estableció el estado actual de la cuenta.</td></tr><tr><td><strong><code>Fecha de fin</code></strong></td><td>Fecha y hora en la que finalizó el estado actual de la cuenta.</td></tr><tr><td><strong><code>Motivo</code></strong></td><td>Descripción y razón por la cual la cuenta presenta el estado actual.</td></tr><tr><td><strong><code>Tipo de Exclusión/limitación</code></strong></td><td>En caso de que la cuenta esté restringida, indica el tipo de exclusión o limitación aplicada.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* Es obligatorio seleccionar un periodo de fechas para ejecutar la consulta.
* El reporte muestra el historial y el estado actual de la cuenta del jugador dentro de la plataforma de apuestas deportivas.
* Se genera uno o más registros por cada evento relacionado con el estado de la cuenta dentro del periodo consultado.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>19/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
