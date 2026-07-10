---
description: >-
  Permite visualizar, consultar y gestionar los bonos disponibles en el sistema
  mediante filtros, indicadores y diferentes acciones de administración.
---

# Bonos

### 1. Acceso al Módulo

**Ruta de Acceso**: Menú principal > Torneos y Bonos > Bonos

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (290).png" alt=""><figcaption><p>Figura #1: Sección principal de Bonos.</p></figcaption></figure>

***

### **3. Acciones del Usuario**

<table><thead><tr><th width="158">Sección</th><th width="159">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/~/changes/346/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono."><strong>Crear bono</strong></a></td><td>Botón</td><td>Permite crear un nuevo bono. Al hacer clic, redirige a la sección de creación de bonos.</td></tr><tr><td><strong>Bonos activos</strong></td><td>Visualizar</td><td>Muestra la cantidad de bonos activos disponibles en el sistema al momento de la consulta.</td></tr><tr><td><a href="bonos.md#id-4.-filtros-disponibles"><strong>Filtros</strong></a></td><td>Selección múltiple</td><td>Permite buscar y filtrar información según criterios específicos como tipo, estado, país, campaña o fechas.</td></tr><tr><td><a href="bonos.md#id-5.-lista-de-bonos"><strong>Lista de bonos</strong></a></td><td>Tabla interactiva</td><td>Permite visualizar los bonos existentes y realizar acciones sobre ellos como <em>(duplicar, inactivar o consultar detalles)</em>.</td></tr><tr><td><a href="bonos.md#id-6.-agregar-bono-de-cumpleanos"><strong>Agregar bono de cumpleaños</strong></a></td><td>Botón</td><td>Permite asignar un bono especial de cumpleaños a un usuario, según las condiciones preconfiguradas.</td></tr></tbody></table>

***

### 4. **Filtros disponibles**

<table><thead><tr><th width="175">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Bono</code></strong></td><td>Permite filtrar la información por el identificador único del bono.</td></tr><tr><td><strong><code>Tipo de Bono</code></strong></td><td>Filtra la información según el tipo de bono configurado (<em>FreeSpin, Bono no depósito, Bono depósito, etc...</em>).</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Permite establecer un rango de fechas para buscar bonos creados en un periodo determinado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Filtra según el estado del bono <em>(activo o inactivo)</em>.</td></tr><tr><td><strong><code>País</code></strong></td><td>Muestra únicamente los bonos creados para el país seleccionado.</td></tr><tr><td><strong><code>Tipo de Campaña</code></strong></td><td>Filtra los bonos según la campaña asociada.</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="149">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Adquisición</strong></td><td>Bono destinado a atraer nuevos usuarios.</td></tr><tr><td><strong>Retención</strong></td><td>Bono diseñado para mantener activos a los usuarios actuales.</td></tr><tr><td><strong>Reactivación</strong></td><td>Bono orientado a recuperar usuarios inactivos.</td></tr><tr><td><strong>Retención de saldo</strong></td><td>Bono para incentivar el uso del saldo existente y evitar retiros.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="175">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Detalle de la Campaña</code></strong></td><td>Permite buscar bonos con base en un detalle o motivo específico.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#programa-de-lealtad"><strong><code>Lealtad</code></strong></a></td><td>Filtra si el bono está asociado al programa de lealtad o no.</td></tr></tbody></table>

Una vez configurados los filtros, haz clic en el botón **“Buscar”** para aplicar la búsqueda, o en **“Limpiar”** para reiniciar los criterios seleccionados.

***

### 5. Lista de Bonos

La lista de bonos muestra la información filtrada y permite acceder a detalles o realizar acciones específicas sobre cada registro.

<table><thead><tr><th width="183.370361328125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td>Por cada bono se permiten realizar las siguientes acciones:</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="126.1112060546875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Editar (</strong><i class="fa-pencil">:pencil:</i><strong>)</strong></td><td>Abre un modal que permite actualizar únicamente el <strong>nombre</strong> del bono conservando la configuración y demás información previamente registrada. <a href="bonos.md#id-4.-validaciones-y-reglas-de-negocio">(Ver validaciones)</a></td></tr><tr><td><strong>Visualizar TyC (</strong><i class="fa-eye">:eye:</i><strong>)</strong></td><td>Permite visualizar información relevante del bono además de sus términos y condiciones.</td></tr><tr><td><a href="bonos.md#ver-detalle-del-bono-lupa"><strong>Lupa (🔍)</strong></a></td><td>Muestra información general del bono, incluyendo participantes y progreso. <a href="bonos.md#ver-detalle-del-bono-lupa" class="button secondary">Ver detalles</a></td></tr><tr><td> <strong>Inactivar sorteo (⏻)</strong></td><td>Abre un pop-up para confirmar la inactivación del bono.</td></tr><tr><td><strong>Agregar usuarios a torneo (</strong><i class="fa-user-plus">:user-plus:</i><strong>)</strong></td><td>Abre pop-up que permite agregar un archivo <a href="https://virtualsoft.gitbook.io/untitled/glosario/#csv">CSV</a> con IDs de jugadores que se van a agregar al bono.</td></tr><tr><td><strong>Duplicar bono (</strong><i class="fa-clone" style="color:yellow;">:clone:</i><strong>)</strong></td><td>Permite duplicar el bono conservando la <strong>misma configuración</strong> en una <strong>fecha diferente</strong>.</td></tr><tr><td><strong>Duplicar bono (</strong><i class="fa-clone">:clone:</i><strong>)</strong></td><td>Permite duplicar el bono conservando la <strong>misma configuración</strong> en un <strong>país diferente</strong>.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="183.11114501953125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Bono</code></strong></td><td>Muestra el identificador único asignado al bono.</td></tr><tr><td><strong><code>Nombre bono</code></strong></td><td>Indica el nombre del bono configurado.</td></tr><tr><td><strong><code>Descripción bono</code></strong></td><td>Presenta una breve descripción del bono.</td></tr><tr><td><strong><code>Tipo de bono</code></strong></td><td>Especifica la categoría del bono <em>(ej. depósito, freebet).</em></td></tr><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Fecha en la que el bono se habilitó o se habilitará.</td></tr><tr><td><strong><code>Fecha fin</code></strong></td><td>Fecha en que el bono expira, o expiró.</td></tr><tr><td><strong><code>Tipo</code></strong> <a href="https://virtualsoft.gitbook.io/plantillas/glosario#rollover"><strong><code>rollover</code></strong></a></td><td>Indica si el bono aplica condiciones de rollover.</td></tr><tr><td><strong><code>Bonos activos</code></strong></td><td>Permite evidenciar la cantidad de bonos que se activaron.</td></tr><tr><td><strong><code>Bonos redimidos</code></strong></td><td>Muestra la cantidad de bonos redimidos.</td></tr><tr><td><strong><code>Bonos Expirados</code></strong></td><td>Indica la cantidad de bonos expirados.</td></tr><tr><td><strong><code>Premios freebet</code></strong></td><td>Cantidad de premios entregados a través de bonos tipo freebet.</td></tr><tr><td><strong><code>Tipo de campaña</code></strong></td><td> Tipo de la campaña asociada al bono.</td></tr><tr><td><strong><code>Detalle de Campaña</code></strong></td><td>Información relacionada con la campaña asociada al bono.</td></tr><tr><td><strong><code>Total bonos</code></strong></td><td>Cantidad total de bonos emitidos.</td></tr></tbody></table>

<details>

<summary>🔽 Ver detalle del bono (<em>🔎 Lupa</em>)</summary>

Permite visualizar la información completa del bono, organizada en las siguientes secciones:

#### **Visualización**

<figure><img src="../../../.gitbook/assets/image (287).png" alt=""><figcaption><p>Figura #2: Captura de pantalla detalle de bono</p></figcaption></figure>

#### **Kpis generales**

Permiten visualizar un resumen general del estado y comportamiento del bono, a través de los siguientes indicadores:

<table><thead><tr><th width="174.11114501953125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Bonos Activos / Valor</code></strong></td><td>Indica la cantidad total de bonos que se encuentran activos y disponibles para los usuarios, junto con su valor monetario acumulado.</td></tr><tr><td><strong><code>Bonos Redimidos / Valor</code></strong></td><td>Muestra la cantidad total de bonos utilizados o redimidos por los usuarios, junto con el valor monetario acumulado de los bonos redimidos.</td></tr><tr><td><strong><code>Bonos Expirados / Valor</code></strong></td><td>Indica la cantidad total de bonos vencidos sin utilizar, junto con el valor monetario acumulado de los bonos expirados.</td></tr><tr><td><strong><code>Total Bonos / Valor</code></strong></td><td>Presenta la cantidad total de bonos generados y el valor monetario total asociado a los mismos.</td></tr><tr><td><strong><code>Total Valor Base</code></strong></td><td>Especifica el valor base total configurado para los bonos generados.</td></tr><tr><td><strong><code>Valor Base de Redimidos</code></strong></td><td>Muestra el valor base acumulado correspondiente a los bonos redimidos.</td></tr><tr><td><strong><code>Porcentaje Activación</code></strong></td><td>presenta el porcentaje de bonos activados respecto al total de bonos generados.</td></tr><tr><td><strong><code>Porcentaje Redención</code></strong></td><td>Muestra el porcentaje de bonos redimidos respecto al total de bonos generados.</td></tr></tbody></table>

#### **Filtros**

<table><thead><tr><th width="149.48138427734375">Campo</th><th width="127.62957763671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>Numérico</td><td>Filtra la información por el identificador único del bono.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Numérico</td><td>Filtra la información asociada a un usuario específico mediante su identificador único.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Rango de fechas</td><td>Permite filtrar los bonos según su fecha de creación.</td></tr><tr><td><strong><code>Fecha Redimió</code></strong></td><td>Rango de fechas</td><td>Permite filtrar los bonos según la fecha en que fueron redimidos.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Desplegable</td><td>Filtra los bonos según su estado actual (<em>Cancelado, expirado, pagado</em>).</td></tr><tr><td><strong><code>Externo Id</code></strong></td><td>Texto</td><td>Filtra la información mediante el identificador externo asociado al bono.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Texto</td><td>Permite filtrar los resultados según el código del bono.</td></tr></tbody></table>

#### **Usuarios afiliados al bono**

Permite visualizar los usuarios afiliados al bono y consultar el detalle de su estado, utilización e información asociada mediante los siguientes campos:

<table><thead><tr><th width="152.62957763671875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>Identificador único del registro asociado al bono.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha en la que fue generado o asignado el bono al usuario.</td></tr><tr><td><strong><code>Fecha Redimió</code></strong></td><td>Fecha en la que el usuario redimió el bono.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador único del usuario asociado al bono.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del bono para el usuario.</td></tr><tr><td><strong><code>Externo Id</code></strong></td><td>Identificador externo asociado al bono.</td></tr><tr><td><strong><code>Valor Bono</code></strong></td><td>Valor monetario asignado al bono.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Código único asociado al bono.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Permite <strong>visualizar el detalle</strong> completo de la información relacionada con el bono, del usuario asociado e información de todas las apuestas validas realizadas.</td></tr></tbody></table>

</details>

***

### 6. Agregar bono de Cumpleaños🎂

{% hint style="warning" %}
**Nota**:  Solo los usuarios con permisos específicos podrán acceder a la funcionalidad de **Bono de cumpleaños**.
{% endhint %}

Esta funcionalidad permite asignar de forma automática un **bono especial de cumpleaños** a los usuarios que cumplan con las condiciones del sistema preestablecidas.

Para hacerlo, ubica el botón <img src="../../../.gitbook/assets/image-removebg-preview (6) (1).png" alt="" data-size="line">, disponible en la parte superior de la sección de cumpleaños. Al hacer clic, el sistema mostrará un **pop-up** que solicita únicamente el **ID del usuario** para completar la asignación.

<table><thead><tr><th width="229.25921630859375">Sección</th><th>Descripción / Detalle</th></tr></thead><tbody><tr><td><strong><code>Aceptar</code></strong></td><td>Confirma la asignación del bono de cumpleaños al usuario una vez validadas las condiciones del sistema.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Cierra la ventana emergente sin realizar cambios ni asignar el bono.</td></tr><tr><td><strong><code>Condiciones automáticas</code></strong></td><td><ul><li>El usuario debe cumplir con todas las condiciones preconfiguradas para el bono de cumpleaños.</li><li>Debe haber iniciado sesión el día de su cumpleaños.</li><li>No debe haber recibido previamente un bono de cumpleaños en el mismo año.</li></ul></td></tr><tr><td><strong><code>Comportamiento del sistema</code></strong></td><td><ul><li>El bono de cumpleaños funciona de manera independiente de otros bonos activos o pendientes.</li><li>Su asignación o redención no interfiere con el uso de otros bonos promocionales.</li></ul></td></tr><tr><td><strong><code>Mensajes del sistema</code></strong></td><td>Al intentar asignar el bono de cumpleaños, el sistema mostrará un mensaje de confirmación si la asignación se realiza correctamente. En caso contrario, mostrará un mensaje indicando el motivo por el cual no fue posible asignar el bono al usuario.</td></tr></tbody></table>

***

### 7. Validaciones y Reglas de Negocio

* Los filtros aplican dinámicamente a los resultados de la lista de bonos.
* Solo los usuarios con permisos específicos podrán acceder a la funcionalidad de **Bono de cumpleaños**.
* Los bonos expirados no pueden ser reactivados.
* La carga de usuarios mediante CSV aplica exclusivamente para bonos de tipo depósito.
* Al momento de **editar** un bono, tenga en cuenta las siguientes validaciones:
  * El campo **Nombre** es obligatorio y no puede quedar vacío.
  * El botón **Editar** estará disponible únicamente para usuarios con rol administrador o con permisos específicos de edición en sorteos y torneos.
  * Al guardar exitosamente, el sistema mostrará el mensaje: **“El nombre del bono ha sido actualizado correctamente”**.
  * Después de guardar los cambios, el listado de bonos se actualizará automáticamente mostrando el nuevo nombre configurado.
  * El nuevo nombre del bono se reflejará automáticamente en todos los reportes, consultas y visualizaciones disponibles en la plataforma.
  * Si ocurre un error durante la actualización, el sistema mostrará un mensaje indicando la causa por la cual no fue posible actualizar el nombre del bono.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="95">Versión</th><th width="119.6666259765625">Fecha</th><th width="150">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>17/10/2025</td><td>Karol Navia</td><td>Adaptación del formato, agregar bono de cumpleaños</td></tr><tr><td>1.1</td><td>28/05/2025</td><td>David Velasquez</td><td>Refinamiento de la sección lista de bonos e incorporación de nuevas validaciones</td></tr></tbody></table>

</details>
