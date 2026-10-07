# Verificación de usuarios

<mark style="color:$info;">Permite consultar y analizar la información relacionada con el proceso de validación de identidad de los usuarios registrados en la plataforma, identificando el proveedor utilizado en cada verificación y su resultado.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso:** BackOffice (BO) > Seguridad > Verificación de Usuario

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2Fz8z6qdULWcjJTFDzr7oD%2Fimage.png?alt=media&#x26;token=a758c11e-3861-4028-b892-68f98f471bc2" alt=""><figcaption><p>Figura #1: Captura de pantalla Verificación de usuarios.</p></figcaption></figure>

***

### 3. Acciones del usuario

<table><thead><tr><th width="153">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="verificacion-de-usuarios.md#id-4.-filtros"><strong>Filtrar</strong></a></td><td>Definen los criterios de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="verificacion-de-usuarios.md#id-5.-resultados-de-la-busqueda"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los registros en la vista detallada o totalizada.</td></tr><tr><td><a href="verificacion-de-usuarios.md#id-6.-agregar-verificacion"><strong>Agregar</strong></a></td><td>Permite registrar manualmente la verificación de un usuario existente.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="150">Filtro</th><th width="130">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Define el periodo en el que se desean visualizar los resultados.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Filtra por el identificador único del usuario, asignado automáticamente al crear su cuenta en la plataforma de usuarios online.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra según el estado del proceso de verificación <em>(Todos, Pendiente, Aprobada, Rechazada, etc.)</em>.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra los resultados según el país del usuario.</td></tr><tr><td><strong><code>Origen</code></strong></td><td>Lista desplegable</td><td>Filtra según el origen del registro <em>(manual o por proveedor)</em>.</td></tr><tr><td><strong><code>Tipo reporte</code></strong></td><td>Lista desplegable</td><td>Clasifica los registros según hayan sido creados mediante <strong>verificación de datos</strong> o a través de una <strong>actualización de información</strong>.</td></tr><tr><td><strong><code>Tipo decisión</code></strong></td><td>Lista desplegable</td><td>Identifica si la decisión asociada al registro fue tomada automáticamente por el sistema o de forma manual por un operador.</td></tr><tr><td><strong><code>Motivo de rechazo</code></strong></td><td>Lista desplegable</td><td>Filtra por el motivo del rechazo de la verificación, cuando aplique.</td></tr><tr><td><strong><code>Proveedor de verificación</code></strong></td><td>Lista desplegable</td><td><p>Filtra por el proveedor mediante el cual se realizó la verificación <em>(Jumio, SEON, Sumsub, entre otros)</em>. Admite la selección de uno o varios proveedores.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este filtro se visualiza únicamente para los usuarios que cuenten con el permiso correspondiente.</p></div></td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selector</td><td>Define el formato de salida del reporte <em>(Detallado o Totalizado)</em>.</td></tr></tbody></table>

***

### 5. Resultados de la búsqueda

{% tabs %}
{% tab title="Visualización Detallada" %}
Con la opción **Detallado**, el sistema muestra una tabla con la información completa de cada proceso de verificación.

<table><thead><tr><th width="145">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>🔍</code></strong></td><td>Despliega una ventana emergente desde la cual es posible consultar la información del usuario y aprobar o rechazar manualmente la solicitud de verificación.<br><a href="verificacion-de-usuarios.md#informacion-detallada-por-usuario" class="button secondary">Información de ventana emergente</a></td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al usuario.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del proceso de verificación.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se realizó la verificación.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario verificado.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td><p>Proveedor mediante el cual se realizó la verificación <em>(Jumio, SEON, Sumsub, entre otros)</em>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Esta columna se visualiza únicamente para los usuarios que cuenten con el permiso correspondiente.</p></div></td></tr><tr><td><strong><code>Usuario Aprueba</code></strong></td><td>Usuario que realizó la aprobación de la verificación, cuando esta se efectuó de forma manual.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del proceso de verificación. Los estados disponibles se detallan en Estados de la verificación.</td></tr><tr><td><strong><code>Usuario Genera</code></strong></td><td>Usuario que inició el proceso de verificación.</td></tr><tr><td><strong><code>Nota</code></strong></td><td>Observaciones asociadas al proceso, las cuales indican cómo se resolvió la verificación. Los mensajes posibles se detallan en Mensajes de la columna Nota.</td></tr></tbody></table>
{% endtab %}

{% tab title="Visualización Totalizada" %}
Con la opción **Totalizado**, el sistema muestra un resumen con los totales de cada estado del proceso de verificación.

<table><thead><tr><th width="200">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Iniciadas</code></strong></td><td>Cantidad total de verificaciones iniciadas.</td></tr><tr><td><strong><code>Pendientes</code></strong></td><td>Cantidad total de verificaciones pendientes.</td></tr><tr><td><strong><code>Aprobadas</code></strong></td><td>Cantidad total de verificaciones aprobadas.</td></tr><tr><td><strong><code>Rechazadas</code></strong></td><td>Cantidad total de verificaciones rechazadas.</td></tr><tr><td><strong><code>No Ejecutadas</code></strong></td><td>Cantidad total de verificaciones no ejecutadas.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

<details>

<summary>🔽 Información detallada por usuario</summary>

Desde la ventana emergente que se despliega al consultar el detalle del usuario, se visualizan los siguientes campos:

<table><thead><tr><th width="245">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único de la cuenta verificada del usuario.</td></tr><tr><td><strong><code>Primer nombre</code></strong></td><td>Primer nombre del usuario.</td></tr><tr><td><strong><code>Segundo nombre</code></strong></td><td>Segundo nombre del usuario, si aplica.</td></tr><tr><td><strong><code>Apellido</code></strong></td><td>Primer apellido del usuario.</td></tr><tr><td><strong><code>Segundo apellido</code></strong></td><td>Segundo apellido del usuario.</td></tr><tr><td><strong><code>Género</code></strong></td><td>Género registrado por el usuario.</td></tr><tr><td><strong><code>Fecha de nacimiento</code></strong></td><td>Fecha de nacimiento del usuario.</td></tr><tr><td><strong><code>Celular</code></strong></td><td>Número de celular registrado por el usuario.</td></tr><tr><td><strong><code>País residencia</code></strong></td><td>País de residencia del usuario.</td></tr><tr><td><strong><code>Provincia / Región residencia</code></strong></td><td>Provincia o región en la que reside el usuario.</td></tr><tr><td><strong><code>Ciudad Residencia</code></strong></td><td>Ciudad en la que reside el usuario.</td></tr><tr><td><strong><code>Dirección</code></strong></td><td>Dirección registrada por el usuario.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Tipo de documento de identidad con el que el usuario realizó el registro.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Número de documento de identidad del usuario.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Correo electrónico del usuario.</td></tr></tbody></table>

Adicionalmente, se muestran los campos enviados por el proveedor una vez el usuario completa el proceso de verificación:

<table><thead><tr><th width="235">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nuevo primer nombre</code></strong></td><td>Primer nombre actualizado tras el proceso de verificación.</td></tr><tr><td><strong><code>Nuevo segundo nombre</code></strong></td><td>Segundo nombre actualizado tras el proceso de verificación.</td></tr><tr><td><strong><code>Nuevo primer apellido</code></strong></td><td>Primer apellido actualizado tras el proceso de verificación.</td></tr><tr><td><strong><code>Nuevo segundo apellido</code></strong></td><td>Segundo apellido actualizado tras el proceso de verificación.</td></tr><tr><td><strong><code>Nueva fecha de nacimiento</code></strong></td><td>Fecha de nacimiento actualizada tras el proceso de verificación.</td></tr><tr><td><strong><code>DNI Anterior</code></strong></td><td>Imagen de la parte frontal del documento de identidad.</td></tr><tr><td><strong><code>DNI Posterior</code></strong></td><td>Imagen de la parte trasera del documento de identidad.</td></tr><tr><td><strong><code>Imagen verificación</code></strong></td><td>Imagen del usuario capturada al momento de realizar la verificación con el proveedor.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Desde esta ventana emergente es posible aprobar o rechazar manualmente la verificación de la cuenta del usuario.
{% endhint %}

</details>

#### 5.1. Estados de la verificación

Los estados reflejan el resultado del proceso, independientemente del proveedor utilizado:

<table><thead><tr><th width="220">Estado</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Validación iniciada / En proceso</strong></td><td>La verificación fue creada y continúa en ejecución por parte del proveedor.</td></tr><tr><td><strong>Aprobada</strong></td><td>La verificación fue aprobada y continúa con las validaciones internas de la plataforma.</td></tr><tr><td><strong>Rechazada</strong></td><td>La verificación no fue aprobada por el proveedor o no superó las validaciones internas.</td></tr><tr><td><strong>Pendiente</strong></td><td>La verificación requiere revisión manual por parte de un operador.</td></tr><tr><td><strong>No completada / No ejecutada</strong></td><td>El usuario abandonó el proceso de verificación sin finalizarlo.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Cuando el proveedor aprueba la verificación, el sistema compara el número de documento retornado con el registrado por el usuario. Si ambos coinciden, la verificación se aprueba; si no coinciden, se rechaza con el motivo **Número de documento incorrecto**.
{% endhint %}

***

### 6. Agregar verificación

Permite verificar manualmente a un usuario previamente registrado en la plataforma mediante el ingreso de la siguiente información obligatoria:

<table data-full-width="false"><thead><tr><th width="194.05548095703125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID usuario</code></strong></td><td><p>Identificador único del usuario a verificar.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Es necesario seleccionar el botón <strong>Consultar</strong> para que el sistema verifique si el usuario existe y muestre automáticamente la información asociada.</p></div></td></tr><tr><td><strong><code>Fecha de nacimiento</code></strong></td><td>Fecha de nacimiento del usuario.</td></tr><tr><td><strong><code>Segundo nombre</code></strong></td><td>Segundo nombre del usuario.</td></tr><tr><td><strong><code>Segundo apellido</code></strong></td><td>Segundo apellido del usuario.</td></tr><tr><td><strong><code>DNI anterior</code></strong></td><td>Imagen de la parte frontal del documento de identidad del usuario.</td></tr><tr><td><strong><code>DNI posterior</code></strong></td><td>Imagen de la parte trasera del documento de identidad del usuario.</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* Los filtros pueden combinarse entre sí para refinar la búsqueda.
* Si no se define ningún filtro, el sistema muestra todos los registros disponibles dentro del rango de fechas seleccionado.
* El tipo de visualización _(Detallado o Totalizado)_ determina el formato de salida del reporte.
* Todas las verificaciones quedan registradas con el proveedor utilizado, conservando esta información en los registros históricos.
* La visualización de la columna y el filtro **`Proveedor`** está controlada por permisos; los usuarios que no cuenten con el permiso correspondiente no los visualizan.
* La visualización de imágenes faciales y de documentos está controlada por un permiso.
* Cuando el proveedor aprueba una verificación, el sistema compara el número de documento retornado con el registrado por el usuario. Si no coinciden, la verificación se rechaza con el motivo **Número de documento incorrecto**.
* El proveedor de verificación se configura desde el módulo de Configuración de proveedores internos.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="109">Versión</th><th width="148">Fecha</th><th width="178">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>12/11/2025</td><td>Karol Navia</td><td>Documento inicial.</td></tr><tr><td>1.1</td><td>10/12/2025</td><td>David Velasquez</td><td>Actualización y reestructuración del manual.</td></tr><tr><td>1.2</td><td>06/01/2026</td><td>David Velasquez</td><td>Incorporación del campo <strong><code>Imagen facial</code></strong>.</td></tr><tr><td>1.3</td><td>15/01/2026</td><td>Ronald Peláez</td><td>Ajuste en formato y campo <strong><code>Imagen verificación</code></strong>.</td></tr><tr><td>1.4</td><td>06/10/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33140">Incorporación del proveedor SEON, la columna y el filtro <strong><code>Proveedor</code></strong>, y los estados y mensajes de la verificación.</a></td></tr></tbody></table>

</details>
