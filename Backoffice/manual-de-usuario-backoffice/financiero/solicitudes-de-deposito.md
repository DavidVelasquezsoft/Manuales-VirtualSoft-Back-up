---
description: >-
  Permite visualizar y gestionar las solicitudes de depósito realizadas por los
  usuarios en la plataforma Usuarios Online.
---

# Solicitudes de depósito

### **1. Acceso al módulo**

**Ruta de navegación**: BackOffice > Financiero > Solicitudes de depósito

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (649).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección solicitudes de depósitos.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="152">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/financiero/solicitudes-de-deposito#id-3.1.-filtros-de-busqueda"><strong>Filtros</strong></a></td><td>Permiten filtrar la información de manera resumida o detallada para obtener resultados más precisos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha de la tabla permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/financiero/solicitudes-de-deposito#id-3.2.-aprobacion-masiva"><strong>Aprobación masiva</strong></a></td><td>Aprueba solicitudes de depósito de manera masiva.</td></tr><tr><td><a href="solicitudes-de-deposito.md#id-6.-contracargos"><strong>Contracargos</strong></a></td><td>Permite generar un informe detallado de <a href="https://virtualsoft.gitbook.io/untitled/glosario#contracargo">contracargos</a> para uno o múltiples usuarios, facilitando su envío al área de gestión de riesgo para su análisis y seguimiento.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><strong>Consultar</strong></td><td>Aplica los filtros seleccionados y muestra los registros válidos ya sea en vista resumida o detallada.</td></tr></tbody></table>

***

### 4. Filtros de búsqueda

<table><thead><tr><th width="146.77777099609375">Campo</th><th width="113.3333740234375">Tipo de Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Periodo en el que se realizó la solicitud de depósito.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador único del usuario que realizó la solicitud.</td></tr><tr><td><strong><code>ID Final</code></strong></td><td>Numérico</td><td>Identificador asociado a la transacción final.</td></tr><tr><td><strong><code>País</code></strong></td><td>Texto</td><td>País desde donde se realizó la solicitud.</td></tr><tr><td><strong><code>Tipo de Pasarela de Pago</code></strong></td><td>Lista desplegable</td><td>Selecciona el nombre de la <a href="https://virtualsoft.gitbook.io/untitled/glosario#pasarela-de-pago">pasarela</a> desde la cual se realiza la solicitud.</td></tr><tr><td><strong><code>Recepción de Efectivo</code></strong>  </td><td>Texto</td><td>Opción seleccionada por el usuario para recibir los fondos.</td></tr><tr><td><strong><code>Agente</code></strong></td><td>Texto / Numérico</td><td>Nombre o identificación del agente asociado a la transacción.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Numérico</td><td>Dirección IP desde la cual se realizó la solicitud.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificación única de la solicitud de depósito.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#external-id"><strong><code>External ID</code></strong></a></td><td>Texto / Numérico</td><td>Identificador externo vinculado a la solicitud.</td></tr><tr><td><strong><code>Fecha de Modificación</code></strong></td><td>Fecha Inicio/Fin</td><td>Última fecha en la que se modificó el estado de la solicitud.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto </td><td>Estado actual de la solicitud (<em>Pagada, Enviada, rechazada, etc.</em>).</td></tr></tbody></table>

### 5. Resultados de consulta

Aplica los filtros seleccionados y muestra los registros válidos en una tabla

<table><thead><tr><th width="136">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>🔍</code></strong></td><td>Permite ver una tabla con detalles avanzados de la solicitud de depósito realizada.</td></tr></tbody></table>

{% columns %}
{% column width="16.666666666666664%" %}

{% endcolumn %}

{% column width="83.33333333333334%" %}
<table><thead><tr><th width="149.55560302734375">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td><p>Indica la <strong>fecha y hora exactas</strong> en que se generó la solicitud de depósito. En este caso, la descripción mostrará <strong>“Envío solicitud de depósito”</strong>.</p><p>Cuando el depósito haya sido realizado mediante <strong>transferencia bancaria</strong>, se mostrará la <strong>fecha en que se efectuó el pago</strong>, y en la descripción <strong>“Fecha de pago”</strong>.</p></td></tr><tr><td><strong><code>ID usuario</code></strong></td><td>Identificador único del usuario que realizó la solicitud.</td></tr><tr><td><strong><code>Transacción ID</code></strong></td><td>Identificador único de la solicitud de depósito.</td></tr><tr><td><strong><code>Descripcion</code></strong></td><td>Muestra una breve descripción de la acción realizada sobre el depósito.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Correo electrónico o nombre del usuario que realizó la acción sobre el depósito, como <strong>aprobar o rechazar</strong> la solicitud.</td></tr><tr><td><strong><code>Fecha acción</code></strong></td><td>Indica la fecha y hora en que se realizó la acción sobre el depósito, ya sea su <strong>aprobación o rechazo</strong>.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Acción realizada sobre la solicitud de depósito, especificando si fue <strong>aprobada o rechazada</strong>.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="142.6666259765625"></th><th></th></tr></thead><tbody><tr><td><img src="../../.gitbook/assets/image (717).png" alt="" data-size="original"></td><td>Despliega un pop-up que permite aprobar o rechazar una solicitud de depósito.</td></tr></tbody></table>

{% columns %}
{% column width="16.666666666666664%" %}

{% endcolumn %}

{% column width="83.33333333333334%" %}
Al seleccionar la opción de aprobar, el sistema muestra un modal con la información de la transacción para su revisión antes de confirmar la acción:

<table><thead><tr><th width="150">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Comprobante de pago</code></strong></td><td>Imagen del comprobante adjuntado por el usuario, cuando el depósito se realizó mediante transferencia bancaria.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#external-id"><strong><code>External ID</code></strong></a></td><td><p>Número de referencia externo del depósito registrado por el usuario al generar la solicitud.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo es editable únicamente para los operadores que cuenten con el permiso correspondiente, con el fin de corregir errores de digitación identificados durante la revisión. Los operadores sin el permiso lo visualizan bloqueado.</p></div></td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se realizó la transacción.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto del depósito solicitado.</td></tr></tbody></table>

Una vez revisada la información, se selecciona el botón **Aprobar** para continuar con el proceso.

{% hint style="danger" %}
**Validación de External ID:** antes de aprobar, el sistema verifica que el External ID no haya sido utilizado en otra solicitud de depósito **previamente aprobada**. Si ya fue utilizado, la solicitud no se aprueba y se muestra el mensaje de error.

Si el operador corrige el External ID desde esta vista, el sistema ejecuta nuevamente la validación antes de permitir la aprobación.
{% endhint %}

{% hint style="warning" %}
**Nota:** Tanto la aprobación como el rechazo requieren confirmarse mediante el **token de autenticación**. Si la opción de autorización temporal está activa, el token se solicita únicamente en la primera operación y mantiene una validez de **30 minutos** para las siguientes; si está inactiva, el sistema lo exige en cada transacción.
{% endhint %}
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="136.7777099609375" align="center"></th><th></th></tr></thead><tbody><tr><td align="center"><img src="../../.gitbook/assets/image (715).png" alt="" data-size="line"></td><td><p>Despliega un pop-up con la factura generada por el pago del pago del depósito por transferencia bancaria.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: </p><ul><li>Esta acción solo estará visible en reportes de solicitudes de depósitos que fueron generados por transferencia bancaria.</li><li>Dentro de este pop-up estará la opción de descargar el comprobante y poder cerrar el pop-up.</li></ul></div></td></tr><tr><td align="center"><strong><code>ID</code></strong></td><td>Identificación única de la solicitud de depósito.</td></tr><tr><td align="center"><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario que realizó la solicitud.</td></tr><tr><td align="center"><strong><code>ID Final</code></strong></td><td>Identificador asociado a la transacción final de depósito.</td></tr><tr><td align="center"><strong><code>Fecha de Creación</code></strong></td><td>Fecha en la que se generó la solicitud de depósito.</td></tr><tr><td align="center"><strong><code>Proveedor</code></strong></td><td>Entidad encargada de procesar la solicitud.</td></tr><tr><td align="center"><strong><code>Nombre del Sistema de Pasarela de Pago</code></strong></td><td>Nombre de la <a href="https://virtualsoft.gitbook.io/untitled/glosario#pasarela-de-pago">pasarela de pago</a> utilizada para la transacción.</td></tr><tr><td align="center"><strong><code>Tipo</code></strong></td><td>Categoría de la solicitud de depósito.</td></tr><tr><td align="center"><strong><code>Moneda</code></strong></td><td>Tipo de moneda utilizada en la transacción.</td></tr><tr><td align="center"><strong><code>Valor</code></strong></td><td>Monto total solicitado para el depósito.</td></tr><tr><td align="center"><strong><code>Impuesto Depósito</code></strong></td><td><p>Monto total de impuesto aplicado al depósito.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si el usuario deposita <code>100</code> y el impuesto es <code>10%</code>, se descontarán <code>110</code> en total; <code>100</code> para el depósito y <code>10</code> de impuesto.</p></div></td></tr><tr><td align="center"><strong><code>Modificado</code></strong></td><td>Fecha exacta de la última modificación en la solicitud.</td></tr><tr><td align="center"><strong><code>Estado</code></strong></td><td>Estado actual de la solicitud (<em>Pagada, Enviada, rechazada, etc</em>.).</td></tr><tr><td align="center"><a href="https://virtualsoft.gitbook.io/untitled/glosario#external-id"><strong><code>External ID</code></strong></a></td><td>Identificador externo vinculado a la solicitud.</td></tr><tr><td align="center"><strong><code>Cuenta digital</code></strong></td><td>Correo electrónico o celular registrado de la cuenta desde la cual se realizó la solicitud.</td></tr><tr><td align="center"><strong><code>IP</code></strong></td><td>Dirección IP desde la cual se realizó la transacción.</td></tr><tr><td align="center"><strong><code>Motivo de rechazo</code></strong></td><td>Especifica la razón informada por la pasarela de pago para el rechazo del depósito, cuando aplique.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: En la parte inferior de la tabla se muestra una **fila** con el total de cada columna, calculando la suma de los valores de todos los registros.
{% endhint %}

***

### 6. Aprobación masiva

Abre una pop-up que permite procesar y aprobar múltiples solicitudes de depósito de forma simultánea.

<table><thead><tr><th width="173.11114501953125">Acción </th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cargar archivo</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario#csv"><strong><code>CSV</code></strong></a></td><td>Permite adjuntar un archivo <a href="https://virtualsoft.gitbook.io/untitled/glosario#csv">CSV</a> con formato compatible.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Cierra la ventana emergente cancela la aprobación masiva.</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Valida el formato de los datos ingresados y ejecuta la aprobación masiva</td></tr></tbody></table>

***

### 7. Contracargos

Abre una ventana emergente para generar un informe detallado de uno o múltiples usuarios en caso de [contracargo](https://virtualsoft.gitbook.io/untitled/glosario#contracargo), y enviarlo al correo de gestión de riesgo.

<table><thead><tr><th width="146.7777099609375">Campo</th><th width="125.77777099609375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#external-id"><strong><code>EXTERNAL ID</code></strong></a></td><td>Numérico</td><td>Ingresar identificador externo del depósito y haz clic en "<strong>Guardar</strong>"</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#csv"><strong><code>Archivo CSV</code></strong></a></td><td>Archivo</td><td>Adjuntar archivo CSV con máximo <strong>40</strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario#external-id">EXTERNAL ID</a> para generarlos simultáneamente.</td></tr></tbody></table>

***

### 8. Reglas y validaciones

* La columna "**`Motivo de rechazo`**" en caso de no tener registro, quedará en blanco.
* En caso de no visualizar este módulo o alguna de las acciones indicadas, se recomienda validar los permisos.
* En caso de presentarse un error que impida la previsualización del comprobante por medio de transferencia bancaria, el sistema deberá habilitar únicamente la opción de descarga del archivo.
* Para la **aprobación o rechazo de una solicitud de depósito**, los **30 minutos** de autorización del **token** comienzan a contar desde la primera validación exitosa, manteniéndose vigentes únicamente mientras la sesión permanezca activa, y no se reinician ni extienden al realizar nuevas solicitudes.
* Esta función de validación de token depende de la configuración del _partner_ en [#solicitud-de-deposito-de-clientes](../herramientas/partner-ajustes/configuracion-1.md#solicitud-de-deposito-de-clientes "mention")

### 9. Flujos relacionados

* Los depósitos realizados se visualizarán en la siguiente reportería [**Reporte de depósito**](../reportes/reporte-de-depositos.md).
* Los depósitos se crean en la plataforma de usuarios online en el módulo de [**Depositos**](https://app.gitbook.com/s/yyrHDz69FZMnpZ9NBm8u/usuarios-online/manual-de-plataforma/depositos).

***

### 10. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="100.77777099609375">Versión </th><th width="137.2222900390625">Fecha</th><th width="163">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/08/2025</td><td>David velasquez</td><td>Actualización de formato e incorporación de nuevas secciones.</td></tr><tr><td>1.1</td><td>26/02/2026</td><td>Ronald Peláez</td><td>Nueva columna "<strong><code>motivo de rechazo</code></strong>" y ajuste en formato del manual.</td></tr><tr><td>1.2</td><td>25/03/2026</td><td>David velasquez</td><td>Refinamiento de estructura del manual</td></tr><tr><td>1.3</td><td>26/03/2026</td><td>Ronald Peláez</td><td>Nueva acción para visualizar comprobante por cuenta bancaria</td></tr><tr><td>1.4</td><td>10/09/2026</td><td>Karol Navia</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33147">Refinar el funcionamiento del campo “<strong><code>Fecha</code></strong>” dentro del detalle.</a></td></tr><tr><td>1.5</td><td>11/09/2026</td><td>David velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33148">Validación y nota en la aprobación y rechazo de solicitudes de depósito.</a></td></tr><tr><td>1.6</td><td>14/09/2026</td><td>Karol Navia</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33145">Añadir los campos <code>Descripción, Email, Fecha de acción y Acción</code> en el detalle del depósito.</a></td></tr></tbody></table>

</details>
