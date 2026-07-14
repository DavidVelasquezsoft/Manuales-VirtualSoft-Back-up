---
description: >-
  Establece las configuraciones por defecto del comportamiento de cada Partner y
  cada país en la plataforma de usuarios online.
---

# Configuración

### 1. Acceso al Módulo

**Ruta de Acceso:** BackOffice > Herramientas > Partner ajustes > Configuración.

{% hint style="warning" %}
**Nota:**

Siempre se debe seleccionar un país en el filtro de país, ya que de esta selección dependerá a qué país quedará asociada la configuración.
{% endhint %}

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (623).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección configuraciones.</p></figcaption></figure>

***

### 3. Configuraciones previas

Antes de realizar las configuraciones es necesario establecer en que país aplicarán dichas configuraciones.

***

### 4. Módulos de configuraciones

Selecciona una categoría para ajustar o administrar sus configuraciones correspondientes.

<details>

<summary><strong>🔽General</strong></summary>

Este módulo permite configurar y actualizar la información general del partner necesaria para su operación en la plataforma usuarios online.

### 1. Acceso al Módulo

**Ruta de Acceso:** BackOffice > Herramientas > Partner ajustes > Configuración. > General

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FcnMQO3KUP1tZZTd9eP9a%2Fimage.png?alt=media&#x26;token=2d2519ab-17ca-46c5-9f23-1159df8a679d" alt=""><figcaption><p>Figura #2: Captura de pantalla de la sección General.</p></figcaption></figure>

***

### 3. Configuraciones disponibles

<table><thead><tr><th width="198">Campo</th><th width="136">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre de la compañía</code></strong></td><td>Texto</td><td>Establece el nombre del partner.</td></tr><tr><td><strong><code>Dirección</code></strong></td><td>Texto</td><td>Establece la dirección registrada por el partner.</td></tr><tr><td><strong><code>Teléfono</code></strong></td><td>Numérico</td><td>Indica el número de teléfono de contacto del partner.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Texto</td><td>Establece el Email de contacto del partner.</td></tr><tr><td><strong><code>Código de plataforma de Mincetur</code></strong></td><td>Numérico</td><td>Establece el código asignado por el ministerio de comercio exterior y turismo (Mincetur).</td></tr></tbody></table>

&#x20;                          <a href="configuracion-1.md#general" class="button secondary">Volver</a>                                    <a href="configuracion-1.md#seguridad" class="button secondary">Siguiente Modulo</a>

</details>

<details>

<summary><strong>🔽Seguridad</strong></summary>

Permite definir y ajustar distintos parámetros de seguridad relacionados con la plataforma de usuarios online.

### 1. Acceso al módulo

**Ruta de acceso**: BackOffice > herramientas > partner ajustes > Configuración > Seguridad

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (696).png" alt=""><figcaption><p>Figura #3: Captura de pantalla sección Seguridad.</p></figcaption></figure>

***

### 3. Acciones del usuario

El usuario con permisos podrá configurar los siguientes parámetros:

<table><thead><tr><th width="153">Campo</th><th width="122">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Días de expiración de la contraseña</code></strong></td><td>Numérico</td><td>Número de días tras los cuales la contraseña del usuario caduca y debe ser cambiada.</td></tr><tr><td><strong><code>Días de expiración de la contraseña temporal</code></strong></td><td>Numérico</td><td>Define la cantidad de días de validez de una contraseña temporal (<em>por ejemplo, generada para recuperación o acceso inicial</em>). Al expirar este periodo, el usuario deberá establecer una nueva contraseña para continuar</td></tr><tr><td><strong><code>Mínima longitud de la contraseña</code></strong></td><td>Numérico</td><td>Define la cantidad mínima de caracteres que debe tener una contraseña válida.</td></tr><tr><td><strong><code>Regular Expresión contraseña usuario</code></strong></td><td>Lista desplegable / Selector</td><td>Permite definir una expresión regular para validar la contraseña del usuario, estableciendo reglas como longitud, formato y caracteres permitidos.</td></tr><tr><td><strong><code>Máximo intentos inicio sesión</code></strong></td><td>Numérico</td><td>Número de intentos de acceso incorrectos permitidos antes de bloquear la cuenta temporalmente.</td></tr><tr><td><strong><code>Días antes de notificación de expiración</code></strong></td><td>Numérico</td><td>Días de anticipación con los que se notifica al usuario que su contraseña está próxima a caducar.</td></tr><tr><td><strong><code>Email máximo intentos inicio sesión</code></strong></td><td><p>Interruptor</p><p>(<em>Sí / No</em>)</p></td><td>Activa o desactiva el envío de correos de alerta cuando se alcanza el número máximo de intentos fallidos de inicio de sesión.</td></tr><tr><td><strong><code>Enviar datos de verificados a</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario#compliance"><strong><code>Compliance</code></strong></a></td><td><p>Interruptor</p><p>(<em>Sí / No</em>)</p></td><td><p>Opción para habilitar o deshabilitar la verificación con el proveedor Compliance.</p><ul><li><strong>Activo (Sí):</strong> los datos de verificación se envían automáticamente al área de Compliance.</li><li><strong>Inactivo (No):</strong> no se envía información de verificación al área de Compliance.</li></ul></td></tr><tr><td><strong><code>Doble Factor De Autenticación (2FA)</code></strong></td><td>Interruptor<br>(<em>Activo / Inactivo</em>)</td><td><p>Permite habilitar o deshabilitar el <strong>doble factor de autenticación</strong> (<em>token de seguridad</em>) para los usuarios del partner seleccionado, asegurando mayor protección en el inicio de sesión.</p><ul><li><p><strong>Activo:</strong> Al iniciar sesión, se mostrará un pop-up invitando a activar el <strong>2FA</strong>. También podrá activarlo de forma voluntaria desde la sección <strong>“</strong><a href="https://virtualsoft.gitbook.io/manuales/usuarios/usuarios-online/manual-de-plataforma/gestion/cambiar-contrasena.#id-3.2-configuracion-del-doble-factor-de-autenticacion-2fa#id-4.-configuracion-del-doble-factor-de-autenticacion-2fa"><strong>Cambiar contraseña</strong></a><strong>”.</strong></p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al activar esta configuración, se habilitará el campo <strong>“<code>Periodicidad de verificación en dispositivos seguros (días)</code>”</strong>, donde se debe definir el número de días durante los cuales un dispositivo marcado como seguro por el usuario desde la plataforma <a href="https://virtualsoft.gitbook.io/manuales/usuarios/usuarios-online/manual-de-plataforma/inicio-de-sesion#id-6.-doble-factor-de-autenticacion-2fa">Usuarios Online</a>, no volverá a solicitar el token de validación. Transcurrido ese plazo, el sistema requerirá nuevamente el token.</p></div></li><li><strong>Inactivo:</strong> Ningún usuario podrá activar el <strong>2FA</strong> y el inicio de sesión se realizará sin token de seguridad.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Solo aplica para los partners <strong>(</strong><em><strong>Paniplay, Ecuabet y Doradobet</strong></em><strong>).</strong></p></div></td></tr><tr><td><strong><code>Inactivación por regla automática</code></strong></td><td>Interruptor<br>(<em>Activo / Inactivo</em>)</td><td><ul><li><strong>Activo</strong>: Los usuarios que realicen un registro serán validados en la <a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/seguridad/reporte-de-listas-de-observados">Lista de observados</a>, en caso de estar en dicha lista el usuario será inactivado de manera automática.</li><li><strong>Inactivo</strong>: Los usuarios <strong>NO</strong> se inactivarán de manera automática, aunque aparezcan en la lista de observados.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Notas</strong>: </p><ul><li>El usuario puede ser activado nuevamente de <a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/seguridad/reporte-de-listas-de-observados">manera manual</a>, la inactivación automática solo aplica para el registro.</li><li>Cuando se desactive de manera automática un usuario, se visualizará un comentario indicando el motivo en la <a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/jugadores/informacion-seccion-jugadores">información del jugador</a>.</li></ul><p></p></div></td></tr></tbody></table>

***

### 4. Validaciones y Reglas de Negocio

* Los valores configurados se aplican a todos los usuarios de la plataforma.
* El sistema bloqueará automáticamente la cuenta después de superar el máximo de intentos de inicio de sesión configurados.
* La notificación de expiración de contraseña se envía únicamente si se configura un valor mayor a 0.
* Al reactivar el **`2FA`**, se habilitará automáticamente para los usuarios que ya lo tenían activo, sin necesidad de generar un nuevo token.
* Cuando el **`2FA`** está habilitado, puede gestionarse individualmente para cada usuario desde la sección **“**[**Jugadores**](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/jugadores/configuracion-seccion-jugadores#id-2.2.-seguridad-y-cambios)**”.**
* Para aplicar los cambios, selecciona “**Guardar**” y confirma la operación con el código QR del Autenticador de Google.
* Algunas acciones de este módulo dependen de los permisos disponibles para el usuario.

<table data-view="cards"><thead><tr><th align="center"></th></tr></thead><tbody><tr><td align="center"><a href="configuracion-1.md#general" class="button secondary">Módulo anterior</a></td></tr><tr><td align="center"><a href="configuracion-1.md#id-4.-modulos-de-configuraciones" class="button secondary">Volver</a></td></tr><tr><td align="center"><a href="configuracion-1.md#solicitud-de-retiro-de-clientes" class="button secondary">Siguiente módulo</a></td></tr></tbody></table>

</details>

<details>

<summary><strong>🔽Solicitud de retiro de clientes</strong></summary>

En esta sección se permite configurar los parámetros relacionados con las solicitudes de retiro realizadas por los usuarios en la plataforma.

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Herramientas > Partner ajustes > Configuración > Solicitudes de retiro de clientes.

***

### 2. Visualización:

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FQpDQkASS3XEZhXkVff0g%2Fimage.png?alt=media&#x26;token=eba4a90b-71ee-48d8-a1a3-667d611bd9e9" alt=""><figcaption><p>Figura #4: Captura de pantalla sección seguridad.</p></figcaption></figure>

### **3. Acciones del Usuario**

<table><thead><tr><th width="105">Sección</th><th width="96">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Guardar</code></strong></td><td>Botón</td><td>Aplica las configuraciones realizadas en la sección de retiros.</td></tr></tbody></table>

### **4. Configuraciones:**

Esta sección permite definir las condiciones y restricciones para que los usuarios puedan realizar solicitudes de retiro.

<table><thead><tr><th width="146.79998779296875">Campo</th><th width="122">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Máximo solicitudes por día</code></strong></td><td>Numérico</td><td>Define la cantidad máxima de solicitudes de retiro que un usuario puede realizar en un solo día.</td></tr><tr><td><strong><code>Mínimo monto en solicitud de retiro</code></strong></td><td>Numérico</td><td>Establece el monto mínimo requerido para solicitar un retiro.</td></tr><tr><td><strong><code>Máximo monto en solicitud de retiro</code></strong></td><td>Numérico</td><td>Configura el monto máximo permitido para las solicitudes de retiro.</td></tr><tr><td><strong><code>Porcentaje mínimo apostado/depositado</code></strong></td><td>Numérico</td><td>Porcentaje que el usuario debe apostar respecto a su depósito antes de retirar.</td></tr><tr><td><strong><code>Mínimo retiros punto</code></strong></td><td>Numérico</td><td>Monto mínimo que se puede retirar en puntos de venta.</td></tr><tr><td><strong><code>Requiere registro activo para retirar</code></strong></td><td><strong>Interruptor</strong></td><td>Indica si el usuario debe tener un registro activo para retirar.</td></tr><tr><td><strong><code>Mínimo monto solicitud de retiro Cuenta bancaria</code></strong></td><td>Numérico</td><td>Defina el monto mínimo requerido para que el usuario pueda realizar una solicitud de retiro a través de cuenta bancaria.</td></tr><tr><td><strong><code>Máxima cantidad de solicitudes activas</code></strong></td><td>Numérico</td><td>Establece el límite de solicitudes activas de retiro por usuario.</td></tr><tr><td><strong><code>Requiere verificación de cuenta para retirar?</code></strong></td><td><strong>Interruptor</strong></td><td>Define si la cuenta del usuario debe estar verificada antes de permitir el retiro.</td></tr><tr><td><strong><code>Máximo monto retiro por punto de venta</code></strong></td><td>Numérico</td><td>Defina el monto máximo permitido que un usuario puede retirar a través de un punto de venta.</td></tr><tr><td><strong><code>Mínimo monto en retiro Kasnet</code></strong></td><td>Numérico</td><td>Monto mínimo para retiros en el sistema Kasnet.</td></tr><tr><td><strong><code>Monto límite de retiro cliente final</code></strong></td><td>Numérico</td><td>Define el monto total que un cliente puede retirar.</td></tr><tr><td><strong><code>Máximo monto en retiro Kasnet</code></strong></td><td>Numérico</td><td>Monto máximo para retiros en Kasnet.</td></tr><tr><td><strong><code>Todos los retiros por puntos de venta pasan a estado por aprobación</code></strong></td><td><strong>Interruptor</strong></td><td><p>Cuando la opción está</p><ul><li><strong>Activa:</strong> todas las solicitudes de retiro hechas en puntos de venta pasarán automáticamente a un estado de aprobación antes de ser procesadas.</li><li><strong>Inactiva:</strong> las solicitudes se procesarán directamente sin necesidad de aprobación previa.</li></ul></td></tr><tr><td><strong><code>Requiere primer depósito para retirar?</code></strong></td><td><strong>Interruptor</strong></td><td>Especifique si el usuario debe haber realizado un primer depósito como requisito para poder efectuar un retiro.</td></tr><tr><td><strong><code>Requiere correo verificado para retirar?</code></strong></td><td><strong>Interruptor</strong></td><td>Indica si el usuario debe verificar su correo electrónico como requisito para poder realizar un retiro.</td></tr><tr><td><strong><code>Requiere celular verificado para retirar?</code></strong></td><td><strong>Interruptor</strong></td><td>Define si el usuario debe tener su número de celular verificado como requisito para poder realizar un retiro.</td></tr><tr><td><strong><code>Retiros en punto de venta (OTP)</code></strong></td><td><strong>Interruptor</strong></td><td><p>Habilita validación OTP en retiros por PV.<br></p><ul><li>Switch OTP por Email: Envía código OTP al correo.</li><li>Switch OTP por SMS: Envía código OTP por SMS.</li><li>Duración del token: Tiempo en milisegundos que estará activo el código OTP.</li></ul></td></tr><tr><td><strong><code>Retiros por transferencia bancaria (OTP)</code></strong></td><td><strong>Interruptor</strong></td><td><p>Permite activar o desactivar la validación con código OTP para los retiros realizados mediante transferencia bancaria.</p><p>Cuando la opción está <strong>activa</strong>, se habilitan los siguientes campos de configuración:</p><ul><li><strong>Switch OTP por Email</strong>: Envía el código OTP al correo electrónico del usuario.</li><li><strong>Switch OTP por SMS</strong>: Envía el código OTP al número de celular del usuario.</li><li><strong>Duración del token en milisegundos</strong>: Define el tiempo de validez del código OTP antes de que expire.</li></ul><p>Cuando la opción está <strong>inactiva</strong>, los retiros se procesan directamente sin requerir validación OTP.<br></p></td></tr><tr><td><strong><code>Activar tiempo de expiración</code></strong></td><td><strong>Interruptor</strong></td><td><p>Permite configurar un tiempo de caducidad para las solicitudes de retiro.<br>Al habilitar esta opción, se activa el campo:</p><ul><li><strong>Tiempo de caducidad de retiros:</strong> Define el plazo máximo en días durante el cual una solicitud puede permanecer vigente antes de expirar automáticamente.</li></ul></td></tr></tbody></table>

***

### **5. Validaciones y Reglas de Negocio**

* Si se habilita OTP, el usuario deberá ingresar el código recibido por Email o SMS antes de que expire el tiempo configurado.
* Cuando la opción **Todos los retiros por puntos de venta pasan a estado por aprobación** está activa, ningún retiro en PV se procesará automáticamente.
* Los montos configurados en mínimo, máximo y límite de retiro prevalecerán sobre cualquier condición de usuario.

***

<table data-view="cards"><thead><tr><th align="center"></th></tr></thead><tbody><tr><td align="center"><a href="configuracion-1.md#seguridad" class="button secondary">Módulo anterior</a></td></tr><tr><td align="center"><a href="configuracion-1.md#id-4.-modulos-de-configuraciones" class="button secondary">Volver</a></td></tr><tr><td align="center"><a href="configuracion-1.md#solicitud-de-deposito-de-clientes-pendiente" class="button secondary">Siguiente módulo</a></td></tr></tbody></table>

</details>

<details>

<summary><strong>🔽Solicitud de depósito de clientes</strong></summary>

Este módulo permite configurar el comportamiento del partner con los depósitos realizados.

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Herramientas > Partner ajustes > Configuración > Solicitudes de depósito de clientes.

***

### 2. Visualización:

<figure><img src="../../../.gitbook/assets/image (638).png" alt=""><figcaption><p>Figura #5: Captura de pantalla sección solicitud de depósito de clientes.</p></figcaption></figure>

### **3. Acciones del Usuario por módulo**

<table><thead><tr><th width="197">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Configurar depósitos</strong></td><td>Configura el comportamiento de los depósitos realizados por los clientes en el partner.</td></tr></tbody></table>

### **4. Configuraciones:**

En esta sección se definen los parámetros y restricciones aplicables a las solicitudes de depósito.

<table><thead><tr><th width="182.800048828125">Campo</th><th width="106.60009765625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mínimo monto de solicitud de depósito</code></strong></td><td>Numérico</td><td>Define el monto mínimo que un usuario puede solicitar en un depósito.</td></tr><tr><td><strong><code>Máximo monto de solicitud de depósito</code></strong></td><td>Numérico</td><td>Establece el monto máximo permitido para una solicitud de depósito.</td></tr><tr><td><strong><code>Requiere registro activo para depositar</code></strong></td><td>Interruptor</td><td>Define si el usuario debe tener un registro activo para poder realizar depósitos.</td></tr><tr><td><strong><code>Límite depósito día global</code></strong></td><td>Numérico</td><td>Fija el monto máximo total de depósitos que pueden realizarse en un solo día.</td></tr><tr><td><strong><code>Límite depósito semana global</code></strong></td><td>Numérico</td><td>Determina el monto máximo de depósitos permitidos durante una semana.</td></tr><tr><td><strong><code>Límite depósito mes global</code></strong></td><td>Numérico</td><td>Establece el monto máximo de depósitos permitidos en un mes.</td></tr><tr><td><strong><code>Límite de cancelaciones por día por PV</code></strong></td><td>Numérico</td><td>Configura el número máximo de cancelaciones de depósitos permitidas por día en un <a href="https://virtualsoft.gitbook.io/untitled/glosario#punto-de-venta">punto de venta (PV)</a>.</td></tr><tr><td><strong><code>Límite de horas anulación depósito</code></strong></td><td>Numérico</td><td>Especifica el tiempo máximo, en horas, dentro del cual un usuario puede anular un depósito realizado.</td></tr><tr><td><strong><code>Requiere verificación de cuenta para depositar</code></strong></td><td>Interruptor</td><td><p>Si esta opción está:</p><ul><li><strong>Activa:</strong> solo se permitirán depósitos en cuentas previamente verificadas</li><li><strong>Inactiva:</strong> los depósitos podrán realizarse sin necesidad de verificación.</li></ul><p>Esta configuración aplica tanto para usuarios online como para puntos de venta.</p></td></tr><tr><td><strong><code>Monto de depósitos por defecto</code></strong></td><td>Numérico</td><td>Define un valor predeterminado que se asignará automáticamente en las solicitudes de depósito.</td></tr><tr><td><strong><code>¿Activación tiempo de recarga por PDV?</code></strong></td><td>Interruptor</td><td><ul><li><strong>Activa:</strong> Se habilita el campo <strong>“<code>Límite de tiempo de recarga por PDV</code>”</strong>, donde se define el intervalo mínimo que debe esperar el usuario antes de realizar un nuevo depósito en un punto de venta.</li><li><strong>Inactiva:</strong> Los depósitos pueden realizarse sin restricción de tiempo entre recargas.</li></ul></td></tr><tr><td><strong><code>Límite tiempo de recarga por PDV</code></strong></td><td>Numérico</td><td>Define, en segundos, el intervalo mínimo que debe esperar un usuario en un punto de venta antes de poder realizar un nuevo depósito.</td></tr></tbody></table>

***

### **5. Validaciones internas por módulo.**

*   Los límites diarios, semanales y mensuales se aplican de forma acumulativa sobre las solicitudes de depósito de cada usuario.

    <div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p>Supongamos estos valores configurados:</p><ul><li>Límite diario: <strong>100 USD</strong></li><li>Límite semanal: <strong>300 USD</strong></li><li>Límite mensual: <strong>1.000 USD</strong></li></ul><p>📌 Cómo funciona:</p><ul><li>Si un usuario deposita <strong>100 USD en un día</strong>, ya alcanzó su límite diario y no podrá hacer más depósitos hasta el día siguiente.</li><li>Si a lo largo de la semana acumula <strong>300 USD</strong>, no podrá depositar más aunque todavía no haya alcanzado el mensual.</li><li>Si en el mes llega a <strong>1.000 USD</strong>, ya no podrá seguir depositando hasta el mes siguiente.</li></ul><p>Es decir, <strong>los límites se van acumulando y cada periodo (día, semana, mes) tiene su propio tope</strong>.</p><ul><li>Si la opción está activa en <strong><code>Requiere verificación de cuenta para depositar</code></strong> , el usuario debe estar verificado antes de poder realizar su primer depósito.</li></ul></div>

***

<table data-view="cards"><thead><tr><th align="center"></th></tr></thead><tbody><tr><td align="center"><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#solicitud-de-retiro-de-clientes" class="button secondary">Módulo anterior</a></td></tr><tr><td align="center"><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#id-4.-modulos-de-configuraciones" class="button secondary">Inicio</a></td></tr><tr><td align="center"><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#ajustes-generales" class="button secondary">Siguiente módulo</a></td></tr></tbody></table>

</details>

<details>

<summary><strong>🔽Ajustes Generales</strong></summary>

Este manual describe la configuración del módulo **Ajustes Generales**, el cual permite administrar los parámetros operativos, fiscales y de seguridad de un partner. Desde este módulo se definen impuestos, reglas de retiro, validaciones, saldos, sesiones y controles clave que impactan el comportamiento de los usuarios y el funcionamiento general de la plataforma.

### 1. Acceso al Módulo

**Ruta de Acceso**: Backoffice > Herramientas > Partner Ajustes > Configuración > Ajustes Generales

***

### 2.Visualización general

<figure><img src="../../../.gitbook/assets/image (14).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección ajustes generales.</p></figcaption></figure>

***

### 3. Configuraciones generales

Permite Gestionar condiciones, permisos y parámetros del partner seleccionado.

<table><thead><tr><th width="137">Campo</th><th width="121.45458984375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Impuesto Retiro Saldo Depósito</code></strong></td><td>Numérico</td><td>Establece el porcentaje de descuento que será aplicado al usuario retirar dinero que proviene directamente de un depósito que no ha sido apostados.</td></tr><tr><td><strong><code>Impuesto Retiro Saldo Depósito a partir de</code></strong></td><td>Numérico</td><td>Monto mínimo a partir del cual se aplica el impuesto al retiro de depósitos.</td></tr><tr><td><strong><code>Impuesto Retiro Saldo Premios</code></strong></td><td>Numérico</td><td>Porcentaje de impuesto aplicado al retiro del saldo de premios.</td></tr><tr><td><strong><code>Impuesto Retiro Saldo Premios a partir de</code></strong></td><td>Numérico</td><td>Monto mínimo a partir del cual se aplica el impuesto al retiro de premios.</td></tr><tr><td><strong><code>Impuesto Retiro Saldo Premios 2</code></strong></td><td>Numérico</td><td>Segundo porcentaje de impuesto aplicado al retiro de premios.</td></tr><tr><td><strong><code>Impuesto sobre apuesta al pagar premio</code></strong></td><td>Numérico</td><td>Porcentaje de impuesto aplicado a la apuesta en el momento de pagar el premio.</td></tr><tr><td><strong><code>Impuesto al</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario#ente-regulador"><strong><code>ente regulador</code></strong></a></td><td>Numérico</td><td>Establece el cargo obligatorio definido por el<a href="https://virtualsoft.gitbook.io/untitled/glosario#ente-regulador"> ente regulador</a> para los retiros realizados en la plataforma.</td></tr><tr><td><strong><code>Impuesto apuesta por punto de venta físico</code></strong></td><td>Numérico</td><td>Porcentaje que se debe pagar por apuestas realizadas en puntos de venta físicos.</td></tr><tr><td><strong><code>Impuesto del GGR de la apuesta al momento de pagar</code></strong></td><td>Numérico</td><td>Porcentaje de impuesto sobre el <a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">GGR</a> aplicado al pagar una apuesta.</td></tr><tr><td><strong><code>Impuesto al ente regulador a partir de</code></strong></td><td>Numérico</td><td>Monto mínimo para aplicar el impuesto del ente regulador.</td></tr><tr><td><strong><code>Aprobar cuentas bancarias</code></strong></td><td>interruptor</td><td>Habilita la aprobación manual o automática de cuentas bancarias registradas por los usuarios.</td></tr><tr><td><strong><code>Máximo cuentas bancarias</code></strong></td><td>Numérico</td><td>Número máximo de cuentas bancarias que un usuario puede registrar.</td></tr><tr><td><strong><code>Porcentaje Penalidad Retiro Saldo Retiros</code></strong></td><td>Numérico</td><td>Establece el porcentaje de penalidad que sera aplicado cuando el usuario retire dinero sin cumplir los requisitos de apuesta.</td></tr><tr><td><strong><code>Porcentaje Penalidad Retiro Saldo Recargas</code></strong></td><td>Numérico</td><td>Porcentaje de penalidad al retirar saldo proveniente de recargas.</td></tr><tr><td><strong><code>Días para alerta de actualización de datos</code></strong></td><td>Numérico</td><td>Días transcurridos antes de notificar al usuario la actualización de sus datos.</td></tr><tr><td><strong><code>Días para alerta de cambio de contraseña</code></strong></td><td>Numérico</td><td>Días antes de enviar al usuario una alerta para cambiar su contraseña.</td></tr><tr><td><strong><code>Tipo de comisión puntos de venta</code></strong></td><td>Lista desplegable</td><td>Selecciona el esquema de comisión aplicado a puntos de venta.</td></tr><tr><td><strong><code>Tipo de liquidaciones comisiones</code></strong></td><td>Lista desplegable</td><td>Selecciona si las comisiones se liquidan automáticamente o manualmente.</td></tr><tr><td><strong><code>URL fondo casino</code></strong></td><td>Texto</td><td>URL de imagen de fondo para la sección de casino.</td></tr><tr><td><strong><code>Requiere registro activo para iniciar sesión</code></strong></td><td>Lista desplegable</td><td>Determina si el usuario debe tener sesión activa para poder iniciar sesión.</td></tr><tr><td><strong><code>Inactividad de sesión en minutos</code></strong></td><td>Numérico</td><td>Tiempo de inactividad antes de cerrar sesión automáticamente.</td></tr><tr><td><strong><code>Duración de la sesión en minutos</code></strong></td><td>Numérico</td><td>Tiempo total que puede durar la sesión activa del usuario.</td></tr><tr><td><strong><code>Mínimo Retiro de Saldos Retiros para Penalizar</code></strong></td><td>Numérico</td><td>Monto mínimo para aplicar penalización al retiro de saldo proveniente de retiros.</td></tr><tr><td><strong><code>Mínimo Retiro de Recargas para Penalizar</code></strong></td><td>Numérico</td><td>Monto mínimo para aplicar penalización al retiro de saldo proveniente de recargas.</td></tr><tr><td><strong><code>Costo Plataforma</code></strong></td><td>Numérico</td><td>Porsentaje del costo que se aplicara a las comisiones de los afiliados.</td></tr><tr><td><strong><code>Aprobar cambios de información personal</code></strong></td><td>Interruptor</td><td>Habilita o deshabilita la opción de aprobar solicitudes de cambio de información personal del usuario.</td></tr><tr><td><strong><code>Saldo bonos</code></strong></td><td>Interruptor</td><td>Habilita el uso y gestión de saldo proveniente de bonos.</td></tr><tr><td><strong><code>Saldo recargas</code></strong></td><td>Interruptor</td><td>Habilita el uso y gestión del saldo proveniente de recargas.</td></tr><tr><td><strong><code>Saldo freebet</code></strong></td><td>Interruptor</td><td>Habilita el uso y gestión de saldo proveniente de apuestas gratuitas.</td></tr><tr><td><strong><code>Saldo freecasino</code></strong></td><td>Interruptor</td><td>Habilita el uso y gestión de saldo para juegos de casino gratuitos.</td></tr><tr><td><strong><code>Saldo retiros</code></strong></td><td>Interruptor</td><td>Habilita el uso y gestión del saldo proveniente de retiros.</td></tr><tr><td><strong><code>Liquidaciones generadas</code></strong></td><td>Interruptor</td><td>Define si las liquidaciones son generadas automáticamente o manualmente.</td></tr><tr><td><strong><code>Contingencia Total</code></strong></td><td>Interruptor</td><td>Permite activar el modo de contingencia en toda la plataforma.</td></tr><tr><td><strong><code>Transacciones sin comisión</code></strong></td><td>Interruptor</td><td><strong>Permite activar o desactivar la opción de aplicar comisiones a las transacciones. Al habilitar esta opción, se despliega el siguiente campo para su configuración: 🔽 arreglaaaaaaaaaaaaar</strong></td></tr><tr><td><strong><code>Tiempo de Restricción</code></strong></td><td>Numérico</td><td>Permite definir el tiempo, en minutos, durante el cual se restringe la generación de comisiones asociadas a transacciones, como depósitos</td></tr><tr><td><strong><code>Requiere verificación para comprar en Lealtad</code></strong></td><td>Interruptor</td><td>Define si el usuario requiere estar verificado para realizar la compra en la tienda de lealtad.</td></tr><tr><td><strong><code>Activación de Nivel de Riesgo</code></strong></td><td>Interruptor</td><td>Habilita la configuración de niveles de riesgo para usuarios o apuestas.</td></tr><tr><td><strong><code>Venta de Apuestas Anónimas</code></strong></td><td>Interruptor</td><td><p>Habilita la opción para puntos de venta de realizar apuestas a usuarios sin estar registrados. Al activarse, se despliegan campos adicionales que pueden activarse para solicitar información del usuario que realiza la apuesta, los disponibles son:</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Es obligatorio mantener habilitado al menos uno de los campos <strong>Documento</strong> o <strong>Número de teléfono</strong> para permitir el funcionamiento correcto de las apuestas anónimas.</p></div></td></tr><tr><td><strong><code>Documento de identidad</code></strong></td><td>Interruptor</td><td>Solicita el número de documento para identificación en apuestas anónimas.</td></tr><tr><td><strong><code>Número de celular</code></strong></td><td>Interruptor</td><td>Solicita el número de cédula para identificación en apuestas anónimas.</td></tr><tr><td><strong><code>Configuración de selección de bono.</code></strong></td><td>Interruptor</td><td>Habilita la selección de bonos por parte del usuario, como el bono por primer depósito u otras promociones aplicables.</td></tr><tr><td><strong><code>Validar cuentas bancarias únicas por usuario</code></strong></td><td>Interruptor</td><td><p>Permite <strong>activar o desactivar la validación de cuentas bancarias duplicadas</strong> dentro del sistema.</p><ul><li><strong>Cuando está activado</strong>, el sistema se asegura de que <strong>una misma cuenta bancaria no pueda estar registrada por más de un usuario</strong> dentro del mismo partner y país.</li><li><strong>Cuando está desactivado</strong>, el sistema <strong>no realiza esta validación</strong>, por lo que una misma cuenta bancaria podría ser usada por varios usuarios.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si una cuenta bancaria es eliminada por un jugador o si el usuario propietario fue eliminado, esa cuenta podrá volver a registrarse por otro usuario.</p></div></td></tr><tr><td><strong><code>Actualiza tipo de documento</code></strong></td><td>Interruptor</td><td><p>Permite activar o desactivar la actualización automática del <strong>tipo de documento</strong> del usuario.</p><ul><li><strong>Activo:</strong> Permite actualizar el tipo de documento del usuario. La actualización puede realizarse de forma <strong>automática</strong> (<em>por medio de la verificación con <strong>Jumio</strong></em>) o de manera <strong>manual</strong>.</li><li><strong>Inactivo:</strong> No permite modificar el tipo de documento del usuario. En este estado, el tipo de documento permanece <strong>sin cambios</strong>, conservando la información registrada inicialmente.</li></ul></td></tr><tr><td><strong><code>¿La marca permite registro Multipais?</code></strong></td><td>Interruptor</td><td><p>Permite habilitar o deshabilitar la funcionalidad de <strong>registro simplificado entre países</strong> para usuarios que acceden a un país diferente dentro del mismo partner.</p><ul><li><strong>Activo:</strong> Habilita el registro multipaís.<br>Al iniciar sesión en un país distinto al de origen, el sistema <strong>valida al usuario mediante su correo electrónico</strong>.<br>Si se detecta que el correo ya se encuentra registrado en otro país del mismo partner, se muestra un <strong>modal de invitación</strong> para crear una cuenta local mediante registro simplificado.</li><li><strong>Inactivo:</strong> Deshabilita el registro multipaís. El sistema <strong>no mostrará la invitación</strong> para crear cuentas en otros países y el usuario continuará utilizando su cuenta del país de origen.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Esta opción solo está disponible para partners que operan en <strong>más de un país</strong>.</p></div></td></tr></tbody></table>

***

### 4. Validaciones y Reglas de Negocio

* Presione el botón "**Guardar"** ubicado al final de la página para aplicar los cambios.
* Los cambios aplican exclusivamente al **partner y marca país** seleccionados.
* No es posible guardar la configuración si existe algún error, en las configuraciones.

***

<table data-view="cards"><thead><tr><th align="center"></th></tr></thead><tbody><tr><td align="center"><a href="configuracion-1.md#solicitud-de-deposito-de-clientes-pendiente" class="button secondary">Módulo anterior</a></td></tr><tr><td align="center"><a href="configuracion-1.md#id-4.-modulos-de-configuraciones" class="button secondary">Volver</a></td></tr><tr><td align="center"><a href="configuracion-1.md#contabilidad" class="button secondary">Siguiente modulo</a></td></tr></tbody></table>

</details>

<details>

<summary><strong>🔽Contabilidad</strong></summary>

En este módulo se configuran los planes de cuentas utilizados para registrar y clasificar los diferentes tipos de transacciones dentro de la plataforma.

### 1. Acceso al Módulo

**Ruta de Acceso:** BackOffice > Herramientas > Partner ajustes > Configuración. > Contabilidad

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (647).png" alt=""><figcaption><p>Figura #6: Captura de pantalla módulo contabilidad.</p></figcaption></figure>

***

### 3. Configuraciones disponibles

<table><thead><tr><th width="213">Campo</th><th width="130">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Plan cuentas Apuestas</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ticket"><strong><code>Tickets</code></strong></a> <strong><code>Tiendas</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar la cuenta contable en la que se registrarán las apuestas realizadas mediante tickets en tiendas físicas.</td></tr><tr><td><strong><code>Plan cuentas Premios</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ticket"><strong><code>Tickets</code></strong></a> <strong><code>Tiendas</code></strong></td><td> Lista desplegable</td><td>Define la cuenta contable en la que se registrarán los pagos de premios asociados a tickets emitidos en tiendas físicas.</td></tr><tr><td><strong><code>Plan cuentas Pagos notas de retiro</code></strong></td><td>Lista desplegable</td><td>Especifica la cuenta contable en la que se registrarán los pagos asociados a las notas de retiro.</td></tr><tr><td><strong><code>Plan de cuentas Recargas</code></strong></td><td>Lista desplegable</td><td>Permite definir la cuenta contable en la que se registrarán las recargas de saldo realizadas por los usuarios.</td></tr></tbody></table>

<table data-view="cards"><thead><tr><th align="center"></th></tr></thead><tbody><tr><td align="center"><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#id-4.-modulos-de-configuraciones" class="button secondary">Volver</a></td></tr><tr><td align="center"><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#ajustes-generales" class="button secondary">Módulo anterior</a></td></tr><tr><td align="center"><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#tipos-de-movimientos-nota-por-cada-monto-en-xxx-va-a-obtener-z-puntos-base" class="button secondary">Siguiente módulo</a></td></tr></tbody></table>

</details>

<details>

<summary><strong>🔽Impuesto</strong></summary>

Desde este módulo se configuran los porcentajes de impuestos que se aplicarán a los depósitos y a las apuestas realizadas dentro de la plataforma.

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice → Configuración → Impuestos

***

### 2. Visualización:

En esta sección se permite configurar los porcentajes de impuestos que se aplicarán a las transacciones realizadas por los usuarios dentro de la plataforma.

<figure><img src="../../../.gitbook/assets/image (648).png" alt=""><figcaption><p>Figura #7: Captura de pantalla apartado Impuesto.</p></figcaption></figure>

***

### **3. Acciones del Usuario**

Estas son las configuraciones disponibles dentro del módulo de impuestos.

<table><thead><tr><th width="184">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Impuesto a la apuesta</code></strong></td><td>Campo numérico</td><td>Permite definir el porcentaje de impuesto que se aplicará sobre el valor total de cada apuesta realizada por el usuario.</td></tr><tr><td><strong><code>Impuesto de depósito</code></strong></td><td>Campo numérico</td><td>Permite definir el porcentaje de impuesto que se cobrará sobre cada depósito realizado por el usuario.</td></tr><tr><td><strong><code>Impuesto de premios Guatemala</code></strong></td><td>Campo numérico</td><td>Indica el porcentaje que se le descontará al usuario en cada premio obtenido.</td></tr></tbody></table>

***

#### **4. Validaciones y Reglas de Negocio**

* Los impuestos se aplicarán automáticamente según los porcentajes configurados.
* Los valores ingresados deben corresponder a porcentajes válidos.
* Los cambios realizados en la configuración impactarán las transacciones realizadas posteriormente a su actualización.
* El campo **`Impuesto de premios Guatemala`** solo aplica para el partner Doradobet Guatemala.

***

<table data-view="cards"><thead><tr><th align="center"></th></tr></thead><tbody><tr><td align="center"><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#contabilidad" class="button secondary">Módulo anterior</a></td></tr><tr><td align="center"><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#id-4.-modulos-de-configuraciones" class="button secondary">Volver</a></td></tr><tr><td align="center"><a class="button secondary">Siguiente módulo</a></td></tr></tbody></table>

</details>

<details>

<summary><strong>🔽Impuesto para comisiones</strong> </summary>

Este módulo permite configurar y gestionar los impuestos aplicables a las comisiones, según el tipo de transacción y tipo de comisión, segmentados por marca y país. Su objetivo es asegurar el cálculo correcto de impuestos y comisiones en las operaciones y reportes, adaptándose a distintos contextos fiscales y regulatorios.

***

### 1. Acceso al Módulo

**Ruta de acceso:** BackOffice > Herramientas > Partner Ajustes > Configuración > Impuestos para Comisiones

***

### 2. Visualización General

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FB8gQHOUgRAHlwk7vOPrf%2Fimage.png?alt=media&#x26;token=148dc072-a3ff-4949-8304-df0ba319fb9e" alt=""><figcaption><p>Figura #1: Captura de pantalla impuestos para comisiones.</p></figcaption></figure>

***

### 3. Funcionalidades

<table><thead><tr><th width="253">Función</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Configuración de Impuestos</strong></td><td>Permite definir el porcentaje de impuesto aplicable a cada sección del partner, según el país seleccionado, asegurando una correcta parametrización de los valores fiscales asociados a las comisiones.</td></tr></tbody></table>

#### **3.1.🧾  Tipos de Comisión Disponibles**

El sistema permite configurar impuestos para los siguientes tipos de comisión:

<table><thead><tr><th width="212">Tipo de Comisión</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Sportbook NGR Afiliados</code></strong></td><td>Comisión calculada sobre el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#net-gaming-revenue-ngr">Net Gaming Revenue (NGR) </a>generado por los afiliados en apuestas deportivas, considerando apuestas, premios y bonos.</td></tr><tr><td><strong><code>Depósito Afiliados</code></strong></td><td>Comisión generada a partir de los depósitos realizados por afiliadores.</td></tr><tr><td><strong><code>Sportbook GGR Punto venta IP</code></strong></td><td>Comisión basada en el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr">Gross Gaming Revenue (GGR)</a> generado por apuestas deportivas realizadas desde un punto de venta.</td></tr><tr><td><strong><code>Sportbook GGR Punto venta</code></strong></td><td>Comisión calculada sobre el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr">Gross Gaming Revenue (GGR)</a> generado por las apuestas deportivas de un punto de venta.</td></tr><tr><td><strong><code>Depósito Punto venta</code></strong></td><td>Comisión asociada a los depósitos realizados en un punto de venta.</td></tr><tr><td><strong><code>Apuesta Sport Punto venta</code></strong></td><td>Comisión generada por las apuestas deportivas realizadas desde un punto de venta.</td></tr><tr><td><strong><code>Notas de retiro Punto venta</code></strong></td><td>Comisión aplicada sobre las solicitudes de retiro realizadas por un punto de venta.</td></tr><tr><td><strong><code>Sportbook GGR Afiliados</code></strong></td><td>Comisión calculada sobre el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr">Gross Gaming Revenue (GGR)</a> generado por los afiliados en apuestas deportivas.</td></tr><tr><td><strong><code>Casino NGR Afiliados</code></strong></td><td>Comisión calculada sobre el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#net-gaming-revenue-ngr">Net Gaming Revenue (NGR)</a> generado por los afiliados en juegos de casino.</td></tr><tr><td><strong><code>Depósito Comisión por Transacción</code></strong></td><td>Comisión aplicada individualmente a cada transacción de depósito realizada en la plataforma.</td></tr></tbody></table>

***

### 4. Reglas de Cálculo

El valor del impuesto se calcula según el tipo de transacción asociado a la comisión:

<table><thead><tr><th width="193">Tipo</th><th>Fórmula</th></tr></thead><tbody><tr><td><strong><code>GGR</code></strong></td><td>(Apuestas − Premios) × (Impuesto %)</td></tr><tr><td><strong><code>NGR</code></strong></td><td>(Apuestas − Premios − Bonos) × (Impuesto %)</td></tr><tr><td><strong><code>Depósitos</code></strong></td><td>Depósitos × (Impuesto %)</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Retiros × (Impuesto %)</td></tr></tbody></table>

***

#### **4.2 📊 Cálculo de la Comisión**

Una vez aplicado el impuesto, la comisión se calcula sobre el valor neto resultante:

<table><thead><tr><th width="231">Tipo</th><th>Fórmula</th></tr></thead><tbody><tr><td><strong><code>Depósitos</code></strong></td><td>(Depósitos − Valor Impuesto) × (% Comisión)</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>(Retiros − Valor Impuesto) × (% Comisión)</td></tr><tr><td><strong><code>GGR</code></strong></td><td>(GGR − Valor Impuesto) × (% Comisión)</td></tr><tr><td><strong><code>NGR</code></strong></td><td>(NGR − Valor Impuesto) × (% Comisión)</td></tr></tbody></table>

***

### 5. ✅ Validaciones y Reglas de Negocio

* El impuesto se configura de forma independiente por **marca, país y tipo de comisión**.
* El porcentaje de impuesto debe ser un valor numérico entre **0 y 100**.
* Si no existe un impuesto configurado para un tipo de comisión, **no se aplica ningún impuesto**.
* Los cálculos de impuestos y comisiones se reflejan automáticamente en las operaciones y reportes correspondientes.
* Los cambios en la configuración de impuestos impactan únicamente las operaciones y reportes posteriores a su aplicación.

***



</details>

<details>

<summary><strong>🔽 Registro</strong></summary>

Permite configurar los parámetros predeterminados relacionados con el proceso de registro de usuarios y los límites de depósito.

### 1. Acceso al módulo

**Ruta de acceso**: BackOffice > herramientas > partner ajustes > Configuración > Registro

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FDLltANuwbKJCS1CY09jU%2Fimage.png?alt=media&#x26;token=7d8ffd7b-0bff-4aa2-ade0-f0058b50a192" alt=""><figcaption><p>Figura #9: Captura de pantalla sección registro.</p></figcaption></figure>

***

### 3. Acciones del usuario

El usuario con permisos podrá configurar los siguientes parámetros:

<table><thead><tr><th width="184.83331298828125">Campo</th><th width="111.5">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Límite depósito día por defecto</code></strong></td><td>Numérico</td><td>Define el monto máximo que un usuario puede depositar en un solo día.</td></tr><tr><td><strong><code>Límite depósito semana por defecto</code></strong></td><td>Numérico</td><td>Especifica el límite de depósito que se puede realizar en el transcurso de una semana.</td></tr><tr><td><strong><code>Límite depósito mes por defecto</code></strong></td><td>Numérico</td><td>Determina el monto máximo permitido para depósitos dentro de un mes.</td></tr><tr><td><strong><code>Tipo de registro</code></strong></td><td>Interruptor</td><td>Permite seleccionar la modalidad de registro del usuario (<em>Larga o corta</em>).</td></tr><tr><td><strong><code>Usuario automáticamente activado</code></strong></td><td>Interruptor</td><td>Define si los usuarios registrados serán activados automáticamente.</td></tr></tbody></table>

***

### 4. ✅Reglas y validaciones

* El **registro largo** solicita una mayor cantidad de información al momento en que el usuario se registra en la plataforma de usuarios online, mientras que el **registro corto** permite completar el proceso solicitando únicamente los datos mínimos requeridos.

### 5.🕛 Control de Versiones

<table><thead><tr><th width="128">Versión</th><th>Fecha</th><th>Autor</th><th>Descripción del cambio</th></tr></thead><tbody><tr><td>1.0</td><td>15/12/2025</td><td>David velasquez</td><td>Actualización de formato.</td></tr><tr><td>1.1</td><td>11/02/2026</td><td>Ronald Peláez</td><td>Refinamiento por nuevo formato del módulo.</td></tr></tbody></table>

</details>

<details>

<summary><strong>🔽</strong> Proveedores internos </summary>

Permite configurar los proveedores encargados de diferentes servicios dentro de la plataforma, así como los parámetros relacionados con la verificación de usuarios y la gestión de rechazos.

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Herramientas > Partner ajustes > Partner a configurar > Configuración > Proveedores internos.

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (612).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección Proveedores internos.</p></figcaption></figure>

***

### **3. Configuraciones disponibles**

<table><thead><tr><th width="146.66668701171875">Configuración</th><th width="158.6666259765625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor de SMS</code></strong></td><td>Lista desplegable</td><td>Permite configurar el proveedor encargado del envío de mensajes de texto a los usuarios <em>(Ej: NIKITA)</em>.</td></tr><tr><td><strong><code>Proveedor de verificación</code></strong></td><td>Lista desplegable</td><td>Define el proveedor responsable de validar la identidad de los usuarios durante el proceso de registro o autenticación <em>(Ej: JUMIO)</em>.</td></tr><tr><td><strong><code>Proveedor de CRM</code></strong></td><td>Lista desplegable</td><td>Configura el proveedor utilizado para la gestión de relaciones y comunicaciones con los usuarios <em>(Ej: OPTIMOVE)</em>.</td></tr><tr><td><strong><code>Proveedor de Email</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el proveedor encargado del envío de correos electrónicos y notificaciones automáticas.</td></tr><tr><td><strong><code>Proveedor de Firmas</code></strong></td><td>Lista desplegable</td><td>Configura el proveedor que gestiona la firma digital de documentos o contratos dentro de la plataforma.</td></tr><tr><td><strong><code>Proveedor CPF</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el proveedor encargado de validar la autenticidad del número CPF <em>(documento de identificación fiscal en Brasil)</em> ingresado por los usuarios.</td></tr><tr><td><strong><code>Tiempo de verificación</code></strong></td><td>Numérico</td><td>Define el tiempo máximo permitido para completar la validación de la información del usuario antes de que expire el proceso.</td></tr><tr><td><strong><code>Proveedor de Tarjeta de Crédito</code></strong></td><td>Lista desplegable</td><td>Permite elegir el proveedor que gestionará los pagos con tarjeta de crédito dentro del flujo de depósitos.<br><em>(Ejemplo: N1CO, Greenpay, etc).</em><br>El proveedor que se establezca será el que procese los depósitos con tarjeta en la plataforma de usuarios online.  </td></tr><tr><td><strong><code>Usuario Online</code></strong></td><td>Botón</td><td>Activa o desactiva la verificación de identidad para usuarios que acceden desde la plataforma online.</td></tr><tr><td><strong><code>Retail</code></strong></td><td>Botón</td><td>Habilita o deshabilita la verificación de identidad para usuarios del segmento minorista <em>(tiendas físicas o puntos de venta).</em></td></tr><tr><td><strong><code>Número de rechazos permitidos</code></strong></td><td>Numérico</td><td>Establece la cantidad máxima de rechazos permitidos antes de bloquear temporalmente nuevas solicitudes de validación.</td></tr><tr><td><strong><code>Número de rechazos por documento</code></strong></td><td>Numérico</td><td>Determina el número máximo de intentos de verificación permitidos por tipo de documento.</td></tr><tr><td><strong><code>Nivel Sumsub</code></strong></td><td>Texto</td><td>Permite definir el nivel de verificación configurado en el proveedor Sumsub para los procesos de identificación de usuarios.</td></tr><tr><td><strong><code>SMS</code></strong></td><td>Botón</td><td>Activa o desactiva el envío de códigos de verificación mediante mensajes SMS.</td></tr><tr><td><strong><code>Pop Up</code></strong></td><td>Botón</td><td>Permite habilitar o deshabilitar las notificaciones emergentes utilizadas durante el proceso de verificación.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Botón</td><td>Activa o desactiva la verificación de identidad a través de correos electrónicos enviados al usuario.</td></tr><tr><td><strong><code>Inbox</code></strong></td><td>Botón</td><td>Permite recibir y gestionar los mensajes de verificación directamente desde la bandeja de entrada interna de la plataforma.</td></tr><tr><td><strong><code>Proveedores de Sportsbook</code></strong></td><td>Lista desplegable</td><td>Configura el proveedor responsable de ofrecer los servicios de apuestas deportivas dentro de la plataforma.</td></tr></tbody></table>

***

### 4. Validaciones y Reglas de Negocio

* El proveedor para Sportsbook por defecto debe ser Altenar, pero se podrá editar.
* Cuando se establece un proveedor de Sportbooks se cambiará para el partner, tanto en Usuarios online, como en puntos de venta en la sección de apuestas deportivas.

</details>

<details>

<summary><strong>🔽</strong>Puntos equivalentes por nivel </summary>

Desde esta sección podrás configurar los puntos necesarios que determinarán el nivel de lealtad que tendrá un usuario, según su acumulado de puntos.

***

### 1. Acceso al módulo

**Ruta de Acceso**: Menú principal > Herramientas > Partner ajustes > Seleccionar Partner > seleccionar pais > Configuración > Puntos equivalentes por nivel

***

### 2. Visualización general

<figure><img src="../../../.gitbook/assets/image (661).png" alt=""><figcaption><p>Figura 1: Captura de pantalla de la sección Puntos equivalentes por nivel.</p></figcaption></figure>

***

### 3. Configuración de niveles

{% hint style="warning" %}
**Nota:** Los niveles se asignan automáticamente cuando el usuario alcanza la cantidad mínima de puntos definida para cada nivel; este cambio se aplica de forma inmediata. Si los puntos disminuyen, el nivel puede recalcularse de acuerdo con la lógica de negocio establecida.
{% endhint %}

<table><thead><tr><th width="198.77783203125">Campo</th><th width="116.5555419921875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Puntos requeridos para el Nivel 1</code></strong></td><td>Numérico</td><td>Define el número mínimo de puntos que debe tener un usuario para pertenecer al Nivel 1.</td></tr><tr><td><strong><code>Puntos requeridos para el Nivel 2</code></strong></td><td>Numérico</td><td>Define el número mínimo de puntos que debe tener un usuario para pertenecer al Nivel 2.</td></tr><tr><td><strong><code>Puntos requeridos para el Nivel 3</code></strong></td><td>Numérico</td><td>Define el número mínimo de puntos para que un usuario ascienda al Nivel 3, Debe ser mayor al valor configurado para el Nivel 2.</td></tr><tr><td><strong><code>Puntos requeridos para el Nivel 4</code></strong></td><td>Numérico</td><td>Define el número mínimo de puntos para que un usuario ascienda al Nivel 4, Debe ser mayor al valor configurado para el Nivel 3.</td></tr><tr><td><strong><code>Puntos requeridos para el Nivel 5</code></strong></td><td>Numérico</td><td>Define el número mínimo de puntos para que un usuario ascienda al Nivel 5, Debe ser mayor al valor configurado para el Nivel 4.</td></tr><tr><td><strong><code>Puntos requeridos para el Nivel 6</code></strong></td><td>Numérico</td><td>Define el número mínimo de puntos para que un usuario ascienda al Nivel 6, Debe ser mayor al valor configurado para el Nivel 5.</td></tr><tr><td><strong><code>Puntos requeridos para el Nivel 7</code></strong></td><td>Numérico</td><td>Define el número mínimo de puntos para que un usuario ascienda al Nivel 7, Debe ser mayor al valor configurado para el Nivel 6.</td></tr><tr><td><strong><code>Puntos requeridos para el Nivel 8</code></strong></td><td>Numérico</td><td>Define el número mínimo de puntos para que un usuario ascienda al Nivel 8, Debe ser mayor al valor configurado para el Nivel 7.</td></tr><tr><td><strong><code>Puntos requeridos para el Nivel 9</code></strong></td><td>Numérico</td><td>Define el número mínimo de puntos para que un usuario ascienda al Nivel 9, Debe ser mayor al valor configurado para el Nivel 8.</td></tr><tr><td><strong><code>Puntos requeridos para el Nivel 10</code></strong></td><td>Numérico</td><td>Define el número mínimo de puntos para que un usuario ascienda al Nivel 10, Debe ser mayor al valor configurado para el Nivel 9.</td></tr><tr><td><strong><code>Frecuencia de expiración de puntos calificables</code></strong></td><td>Lista desplegable/ numérico</td><td><p>En este campo se define cada cuántos meses (de 1 a 12) se reinician los puntos calificables del jugador, definiendo el ciclo de acumulación dentro del programa de lealtad.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong><br>Se debe tener en cuenta que el cálculo se realiza con base en meses calendario, por lo que no cuenta desde el día exacto en que se configura o se generan los puntos, sino que siempre toma como referencia el cierre del mes.</p><p>Por ejemplo, si hoy es 13 de abril y se configura en 1 mes, el sistema no contará hasta el 13 de mayo, sino que el ciclo irá hasta el 30 de abril (fin de mes). Al día siguiente, 1 de mayo, los puntos se reinician a 0 y comienza un nuevo ciclo.</p></div><div data-gb-custom-block data-tag="hint" data-style="danger" class="hint hint-danger"><p><strong>Importante:</strong> </p><ul><li>Si no se establece un valor en este campo, el sistema tomará por defecto <strong>1 mes</strong>.</li><li>Este campo solo permite valores numéricos entre <strong>1 y 12, e</strong>n caso de ingresar un valor fuera de este rango <em>(por ejemplo, 13)</em>, el sistema lo ajustará automáticamente al valor máximo permitido (<em><strong>12</strong></em>).</li></ul></div></td></tr></tbody></table>

***

### 4. Flujo de funcionamiento

> #### 1️⃣ **Obtención de puntos**
>
> El usuario obtiene puntos, a partir de las apuestas realizadas que sean válidas. Estos puntos se generan automáticamente por el sistema según las configuraciones definidas.
>
> #### **2️⃣ Acumulación de puntos**
>
> El jugador acumula puntos durante el periodo activo hasta alcanzar los umbrales definidos para cada nivel (por ejemplo, Oro).
>
> #### **3️⃣ Asignación de nivel**
>
> Al alcanzar la cantidad mínima de puntos requerida, el nivel se asigna automáticamente de forma inmediata.
>
> #### **4️⃣Activación de permanencia**
>
> Al subir de nivel, se activa un periodo de permanencia durante el cual el jugador conserva su nivel.
>
> #### **5️⃣Cierre del ciclo**
>
> Al finalizar el periodo (por ejemplo, mensual), el sistema registra los puntos obtenidos durante ese ciclo.
>
> #### **6️⃣Reinicio de puntos**
>
> Al iniciar un nuevo ciclo, los puntos se reinician a 0; sin embargo, el nivel del jugador se mantiene durante la permanencia.
>
> #### **7️⃣Nuevo ciclo de acumulación**
>
> El jugador comienza nuevamente a acumular puntos en el siguiente periodo.
>
> #### **8️⃣Evaluación del nivel**
>
> Al finalizar el periodo de permanencia, el sistema evalúa si el jugador alcanzó el umbral requerido.
>
> #### **9️⃣Actualización de nivel**
>
> Según los puntos obtenidos:
>
> * Se mantiene el nivel si cumple el umbral.
> * Desciende al nivel correspondiente si no lo alcanza.

***

### 5. Glosario

<table><thead><tr><th width="164">Término</th><th>Definición</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#nivel-lealtad"><strong>Nivel de lealtad</strong></a></td><td>Es la categoría que tiene un jugador dentro del programa de lealtad, definida según los puntos que acumula. Este nivel indica su grado de actividad y puede cambiar con el tiempo según sus puntos y las reglas del sistema.</td></tr></tbody></table>

***

### 6. Reglas del negocio:

* En el campo **Frecuencia de expiración de puntos calificables** no se permiten valores en **0**, negativos ni vacíos.
* La expiración aplica únicamente a los **puntos calificables**; los **puntos canjeables** no se ven afectados por esta configuración.

<table data-view="cards"><thead><tr><th align="center"></th></tr></thead><tbody><tr><td align="center"><a href="configuracion-1.md#proveedores-internos" class="button secondary">Módulo anterior</a></td></tr><tr><td align="center"><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#id-4.-modulos-de-configuraciones" class="button secondary">Inicio</a></td></tr><tr><td align="center"><a href="configuracion-1.md#tipos-de-movimientos-nota-por-cada-monto-en-xxx-va-a-obtener-z-puntos-base" class="button secondary">Siguiente módulo</a></td></tr></tbody></table>

</details>

<details>

<summary>🔽Tipos de movimientos <em>(Nota: Por cada monto en XXX va a obtener Z puntos base)</em></summary>

En esta sección se permite configurar la habilitación del conteo de puntos de lealtad canjeables por vertical de juego. Cada vertical puede activarse o desactivarse mediante interruptores, los cuales determinan si las apuestas realizadas generan puntos de lealtad de acuerdo con las configuraciones establecidas.

### **1. Acceso al Módulo:**

**Ruta de Acceso:** Menú principal > Herramientas > Partner ajustes > Configuración > Tipos de movimientos _(Nota: Por cada monto en XXX va a obtener Z puntos base)_

***

### **2. Visualización:**

<figure><img src="../../../.gitbook/assets/image (645).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección tipos de movimientos.</p></figcaption></figure>

***

### **3. Acciones disponibles**

<table><thead><tr><th width="181">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Establecer criterios para adquirir puntos lealtad</strong></td><td>Aplica las configuraciones realizadas para el conteo de puntos de lealtad por vertical.</td></tr></tbody></table>

***

### **4. Configuraciones Disponibles**

{% hint style="danger" %}
**Nota Importante**

Para todos los campos configurables, el cálculo de puntos se realiza utilizando la siguiente fórmula:

> Apuesta realizada por el usuario × Valor base× Valor configurado en el campo = Puntos obtenidos por el usuario

Esto significa que los puntos se asignan de forma proporcional al monto apostado o depositado.
{% endhint %}

<table><thead><tr><th width="111">Campo</th><th width="120">Tipo</th><th width="223">Descripción</th><th>Ejemplo</th></tr></thead><tbody><tr><td><strong><code>Sportbook</code></strong></td><td>Interruptor</td><td>Permite habilitar o deshabilitar la acumulación de puntos en apuestas deportivas.</td><td>Si está activado, cuando el usuario realice apuestas deportivas acumulará puntos según la configuración. Si está desactivado, no recibirá puntos por este tipo de apuestas.</td></tr><tr><td><strong><code>Casino</code></strong></td><td>Interruptor</td><td>Permite habilitar o deshabilitar la acumulación de puntos en juegos de casino.</td><td>Si está activado, las apuestas en casino generarán puntos. Si está desactivado, no se asignarán puntos.</td></tr><tr><td><strong><code>Live Casino</code></strong></td><td>Interruptor</td><td>Permite habilitar o deshabilitar la acumulación de puntos en juegos de casino en vivo.</td><td>Si está activado, las apuestas en vivo acumularán puntos. Si está desactivado, no generarán puntos.</td></tr><tr><td><strong><code>Virtual</code></strong></td><td>Interruptor</td><td>Permite habilitar o deshabilitar la acumulación de puntos en juegos virtuales.</td><td>Si está activado, las apuestas virtuales generarán puntos. Si está desactivado, no se otorgarán puntos.</td></tr><tr><td><strong><code>Puntos Base</code></strong></td><td>Numérico</td><td>Define la cantidad base de puntos utilizada en el cálculo proporcional de puntos.</td><td>Por ejemplo, si se establece en 1, este será el valor base que se usará en todos los cálculos de puntos.</td></tr><tr><td><strong><code>Deportiva Simple</code></strong></td><td>Numérico</td><td>Valor de conversión para apuestas simples. Se usa como divisor en la fórmula de puntos.</td><td>Por ejemplo, si en este campo se establece 1.5 y el usuario realiza una apuesta de 3, el sistema calcula los puntos así: <em>(3 × 1)</em> / 1.5 = 2 puntos. Es decir, el usuario obtendrá 2 puntos.</td></tr><tr><td><strong><code>Deportiva combinada de 2</code></strong></td><td>Numérico</td><td>Valor de conversión para apuestas combinadas de 2 selecciones.</td><td>Por ejemplo, si en este campo se establece 2 y el usuario apuesta 4, se realiza el cálculo: <em>(4 × 1)</em> / 2 = 2 puntos. El usuario obtiene 2 puntos.</td></tr><tr><td><strong><code>Deportiva combinada de 3</code></strong></td><td>Numérico</td><td>Valor de conversión para apuestas combinadas de 3 selecciones.</td><td>Por ejemplo, si se establece 3 y el usuario apuesta 6, el cálculo será: <em>(6 × 1)</em> / 3 = 2 puntos.</td></tr><tr><td><strong><code>Deportiva combinada de 4</code></strong></td><td>Numérico</td><td>Valor de conversión para apuestas combinadas de 4 selecciones.</td><td>Por ejemplo, si se establece 4 y el usuario apuesta 8, el cálculo será: <em>(8 × 1)</em> / 4 = 2 puntos.</td></tr><tr><td><strong><code>Deportiva combinada de 5</code></strong></td><td>Numérico</td><td>Valor de conversión para apuestas combinadas de 5 selecciones.</td><td>Por ejemplo, si se establece 5 y el usuario apuesta 10, el cálculo será: <em>(10 × 1)</em> / 5 = 2 puntos.</td></tr><tr><td><strong><code>Deportiva combinada de 6</code></strong></td><td>Numérico</td><td>Valor de conversión para apuestas combinadas de 6 selecciones.</td><td>Por ejemplo, si se establece 6 y el usuario apuesta 12, el cálculo será: <em>(12 × 1)</em> / 6 = 2 puntos.</td></tr><tr><td><strong><code>Deportiva combinada de 7</code></strong></td><td>Numérico</td><td>Valor de conversión para apuestas combinadas de 7 selecciones.</td><td>Por ejemplo, si se establece 7 y el usuario apuesta 14, el cálculo será: <em>(14 × 1)</em> / 7 = 2 puntos.</td></tr><tr><td><strong><code>Deportiva combinada de 8</code></strong></td><td>Numérico</td><td>Valor de conversión para apuestas combinadas de 8 selecciones.</td><td>Por ejemplo, si se establece 8 y el usuario apuesta 16, el cálculo será: <em>(16 × 1)</em> / 8 = 2 puntos.</td></tr><tr><td><strong><code>Deportiva combinada de 9</code></strong></td><td>Numérico</td><td>Valor de conversión para apuestas combinadas de 9 selecciones.</td><td>Por ejemplo, si se establece 9 y el usuario apuesta 18, el cálculo será: <em>(18 × 1)</em> / 9 = 2 puntos.</td></tr><tr><td><strong><code>Deportiva combinada de 10</code></strong></td><td>Numérico</td><td>Valor de conversión para apuestas combinadas de 10 selecciones.</td><td>Por ejemplo, si se establece 10 y el usuario apuesta 20, el cálculo será: <em>(20 × 1)</em> / 10 = 2 puntos.</td></tr><tr><td><strong><code>Monto Depósito</code></strong></td><td>Numérico</td><td>Valor de conversión para asignación de puntos según depósitos realizados.</td><td>Por ejemplo, si se establece 20 y el usuario deposita 40, el cálculo será: (<em>40 × 1)</em> / 20 = 2 puntos.</td></tr><tr><td><strong><code>Apuestas de Casino</code></strong></td><td>Numérico</td><td>Valor de conversión para apuestas en juegos de casino.</td><td>Por ejemplo, si se establece 10 y el usuario apuesta 50, el cálculo será: <em>(50 × 1)</em> / 10 = 5 puntos.</td></tr><tr><td><strong><code>Monto requerido de retiros</code></strong></td><td>Numérico</td><td>Valor de referencia para condiciones de retiro que pueden afectar el cálculo o acumulación de puntos.</td><td>Por ejemplo, si se establece 50, este valor se usa como referencia para aplicar las reglas de puntos en los retiros.</td></tr><tr><td><strong><code>Días de expiración de puntos</code></strong></td><td>Numérico</td><td><p>Cantidad de días en los que los puntos acumulados son válidos antes de expirar.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo aplica únicamente para los puntos de lealtad, los cuales se utilizan para la redención de regalos. La configuración de expiración de los puntos calificables se define en <a data-mention href="configuracion-1.md#puntos-equivalentes-por-nivel">#puntos-equivalentes-por-nivel</a></p></div></td><td>Por ejemplo, si se configuran 30 días, los puntos vencerán después de ese tiempo si no se utilizan.</td></tr><tr><td><strong><code>Apuestas Virtuales</code></strong></td><td>Numérico</td><td>Valor de conversión para apuestas en juegos virtuales.</td><td>Por ejemplo, si se establece 5 y el usuario apuesta 25, el cálculo será: <em>(25 × 1)</em> / 5 = 5 puntos.</td></tr><tr><td><strong><code>Apuestas de Casino en Vivo</code></strong></td><td>Numérico</td><td>Valor de conversión para apuestas en casino en vivo.</td><td>Por ejemplo, si se establece 15 y el usuario apuesta 30, el cálculo será: <em>(30 × 1)</em> / 15 = 2 puntos.</td></tr></tbody></table>

***

### 5. Validaciones del negocio:

* Los puntos se calculan de forma proporcional para todos los tipos de movimiento utilizando la fórmula definida en el sistema.
* El valor configurado en cada campo debe ser mayor a **0**, ya que no se permite división por cero en el cálculo de puntos.
* Los puntos base deben estar configurados para que el sistema pueda realizar el cálculo correctamente.
* Si un interruptor se encuentra activo y alguno de sus campos obligatorios es eliminado o se configura con valores menores o iguales a cero, el sistema mostrará un modal de alerta al intentar guardar.
* Cuando un interruptor está activo, las apuestas de la vertical correspondiente generarán puntos de lealtad según la configuración definida.
* Cuando un interruptor está inactivo, las apuestas de esa vertical no generarán puntos de lealtad en la plataforma de usuarios online.
* La configuración aplica de forma independiente por partner y país.
* Las configuraciones **`Puntos Base`**  y **`Días de expiración de puntos`** son generales para todas las verticales.

<table data-view="cards"><thead><tr><th align="center"></th></tr></thead><tbody><tr><td align="center"><a href="configuracion-1.md#puntos-equivalentes-por-nivel" class="button secondary">Módulo anterior</a></td></tr><tr><td align="center"><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#id-4.-modulos-de-configuraciones" class="button secondary">Inicio</a></td></tr><tr><td align="center"><a href="configuracion-1.md#lealtad" class="button secondary">Siguiente módulo</a></td></tr></tbody></table>

</details>

<details>

<summary><strong>🔽</strong> Lealtad </summary>

Configura las restricciones de tiempo aplicables a la redención de regalos dentro del programa de lealtad. Mediante estas opciones es posible controlar la frecuencia con la que un jugador puede realizar canjes, ya sea para un mismo regalo o entre diferentes regalos disponibles en la tienda.

### **1. Acceso al Módulo:**

**Ruta de Acceso:** Menú principal > Herramientas > Partner ajustes > Configuración > Lealtad

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (687).png" alt=""><figcaption><p>Figura #1. Configuración de restricciones de canje en el módulo de Lealtad.</p></figcaption></figure>

### **3. Configuraciones**

<table><thead><tr><th width="192">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Puede repetir el canje del mismo regalo cada X tiempo</code></strong></td><td><p>Permite habilitar o deshabilitar una restricción para que un usuario pueda volver a canjear el mismo regalo después de un período determinado.</p><ul><li><p><strong>Si está activado</strong> (posición "Sí"), se habilitan dos configuraciones adicionales:</p><ul><li><strong>Tiempo de espera</strong>: Define el tiempo que debe transcurrir para que el usuario pueda volver a canjear el mismo regalo.</li><li><strong>Unidad de tiempo</strong>: Permite seleccionar entre minutos, horas o días como unidad para el tiempo de espera.</li></ul></li><li><strong>Si está desactivado</strong> (posición "No"), el jugador podrá volver a canjear el mismo regalo sin restricciones de tiempo.</li></ul></td></tr><tr><td><strong><code>Tiempo mínimo entre cualquier canje (campo opcional)</code></strong></td><td><p>Permite establecer un tiempo mínimo que debe transcurrir entre cualquier redención realizada por el usuario, independientemente del regalo seleccionado.</p><ul><li><p><strong>Si está activado</strong>, se despliegan los siguientes parámetros:</p><ul><li><strong>Tiempo de espera</strong>: establece el tiempo mínimo que debe transcurrir entre un canje y otro, independientemente del tipo de regalo.</li><li><strong>Unidad de tiempo</strong>: permite seleccionar si el tiempo se medirá en minutos, horas o días.</li></ul></li><li><strong>Si está desactivado</strong>, el jugador podrá realizar canjes consecutivos sin una restricción de tiempo entre ellos.</li></ul></td></tr></tbody></table>

{% hint style="warning" %}
**Nota importante:**\
En caso de que ambas configuraciones estén activadas **"Puede repetir el canje del mismo regalo cada X tiempo"** y **"Tiempo mínimo entre cualquier canje"**, la condición que prevalece es la de **"Tiempo mínimo entre cualquier canje".**\
Esto significa que el sistema aplicará el tiempo de espera definido en esta última opción, incluso si el regalo es el mismo.
{% endhint %}

### 4. Validaciones y Reglas de Negocio

* Al activar la opción **"Puede repetir el canje del mismo regalo cada X tiempo"**, los campos **Tiempo de espera** y **Unidad de tiempo** serán obligatorios.
* Al activar la opción **"Tiempo mínimo entre cualquier canje"**, los campos **Tiempo de espera** y **Unidad de tiempo** asociados a esta configuración serán obligatorios.
* El valor configurado en el campo **Tiempo de espera** debe ser mayor a cero.
* Las unidades de tiempo permitidas para ambas configuraciones son **Minutos**, **Horas** y **Días**.
* Si el tiempo configurado aún no se ha cumplido, el sistema no permitirá realizar la redención.

</details>

<details>

<summary><strong>🔽</strong> Referidos</summary>

Permite configurar todas las opciones relacionadas con el programa de referidos.

### 1. Acceso al Módulo:

**Ruta de Acceso**: Herramientas > Partner ajustes > Configuración > Referidos

***

### 2. Visualización:

<figure><img src="../../../.gitbook/assets/image (620).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección referidos.</p></figcaption></figure>

### **3. Acciones disponibles**

<table><thead><tr><th width="178">Sección</th><th width="94.16668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Activar Referidos</code></strong></td><td>Botón</td><td>Permite activar o desactivar el programa de referidos.</td></tr><tr><td><strong><code>URL de la Landing Page</code></strong></td><td>Texto</td><td>Configura la URL de registro por cada partner, ajustándose a la página de destino deseada.</td></tr><tr><td><strong><code>Cuota mínima en apuestas deportivas para el desbloqueo de la recompensa</code></strong></td><td>numérico</td><td>Especifica la cuota mínima válida en apuestas de sportsbook para que sean consideradas dentro del programa.</td></tr><tr><td><strong><code>Límite de días para selección de recompensa - Referente</code></strong></td><td>numérico</td><td>Define el número máximo de días que tiene el <strong>referente</strong> para seleccionar la recompensa disponible una vez que el referido haya cumplido con las condiciones establecidas.</td></tr><tr><td><strong><code>Límite de días para cumplimiento de condiciones - Referido</code></strong></td><td>numérico</td><td>Establece el plazo en días que tiene el <strong>referido</strong> para cumplir con los requisitos (depósito mínimo, apuestas o verificación), con el fin de que el referente pueda recibir la recompensa correspondiente.</td></tr><tr><td><strong><code>Exclusión de categorías</code></strong></td><td>Botón</td><td><p>define qué categorías  <strong>no serán tenidas en cuenta</strong> para el desbloqueo de las recompensas dentro del programa de referidos.</p><p>Entre ambos recuadros se encuentran los siguientes botones:</p><ul><li><code>>></code> Mueve todas las categorías de la columna <strong>Todas</strong> hacia <strong>Excluidas</strong>.</li><li><code>&#x3C;&#x3C;</code> Retorna todas las categorías desde <strong>Excluidas</strong> hacia <strong>Todas</strong>.</li><li><code>></code> Mueve solo la categoría seleccionada desde <strong>Todas</strong> hacia <strong>Excluidas</strong>.</li><li><code>&#x3C;</code> Retorna únicamente la categoría seleccionada desde <strong>Excluidas</strong> hacia <strong>Todas</strong>.</li></ul></td></tr><tr><td><strong><code>Canales de envío permitidos</code></strong></td><td>Switch</td><td><p>En esta sección hay dos configuraciones disponibles, las cuales afectarán usuarios online:</p><p></p></td></tr></tbody></table>

***

### 4. Agregar recompensas

Permite agregar recompensas de referidos según dos modalidades: por primer depósito o por apuestas, utilizando los botones disponibles en la parte inferior.

{% hint style="warning" %}
**Notas**:&#x20;

* Si no se ha agregado ningún premio, se mostrará el mensaje: _“No hay premios agregados”_.
* Solo se pueden agregar **tres premios en total** entre todas las categorías.
{% endhint %}

**4.1. Agregar recompensa por primer deposito**

Esta opción permite configurar un premio que los usuarios recibirán tras realizar su primer depósito.

<table><thead><tr><th width="139">Campo</th><th width="114">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre de la Recompensa</code></strong></td><td>Texto</td><td>Nombre de la recompensa otorgada al usuario.</td></tr><tr><td><strong><code>Mínimo Primer Depósito</code></strong></td><td>Numérico</td><td>Define el monto mínimo que el usuario debe depositar para que el referente reciba la recompensa.</td></tr><tr><td><strong><code>Cuenta Verificada</code></strong></td><td>Checkbox</td><td>Indica si la cuenta debe estar verificada para recibir la recompensa.</td></tr><tr><td><strong><code>Eliminar</code></strong></td><td>Botón</td><td>Permite eliminar la recompensa configurada.</td></tr><tr><td><strong><code>categoría requerida.</code></strong></td><td></td><td><ul><li><strong>Bonos Disponibles</strong>: Muestra los bonos previamente creados que pueden agregarse.</li><li><strong>Bonos Seleccionados:</strong> Indica los bonos aplicados a la recompensa.</li></ul><p>Entre ambos recuadros se encuentran los siguientes botones:</p><ul><li><code>>></code> Mueve todas las categorías de la columna <strong>disponibles</strong> hacia <strong>seleccionados</strong>.</li><li><code>&#x3C;&#x3C;</code> Retorna todas las categorías desde <strong>disponibles</strong> hacia <strong>seleccionados</strong>.</li><li><code>></code> Mueve solo la categoría seleccionada desde <strong>disponibles</strong> hacia <strong>seleccionados</strong>.</li><li><code>&#x3C;</code> Retorna únicamente la categoría seleccionada desde <strong>seleccionados</strong> hacia <strong>disponibles</strong>.</li></ul></td></tr></tbody></table>

#### 4.2. Agregar recompensa por apuesta

Esta opción permite configurar un premio para los usuarios que realicen apuestas dentro de la plataforma.

<table><thead><tr><th width="134">Campo</th><th width="125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre de la Recompensa</code></strong></td><td>Texto</td><td>Nombre de la recompensa otorgada al usuario.</td></tr><tr><td><strong><code>Mínimo de Apuestas</code></strong></td><td>Campo numérico</td><td>Define el número mínimo de apuestas requeridas.</td></tr><tr><td><strong><code>Cuenta Verificada</code></strong></td><td>Checkbox</td><td>Indica si la cuenta debe estar verificada para recibir la recompensa.</td></tr><tr><td><strong><code>Eliminar Recompensa</code></strong></td><td>Botón</td><td>Elimina la recompensa configurada.</td></tr><tr><td><strong><code>categoría requerida.</code></strong></td><td>Botón</td><td><p></p><ul><li><strong>Bonos Disponibles</strong>: Muestra los bonos previamente creados que pueden agregarse.</li><li><strong>Bonos Seleccionados:</strong> Indica los bonos aplicados a la recompensa.</li></ul><p>Entre ambos recuadros se encuentran los siguientes botones:</p><ul><li><code>>></code> Mueve todas las categorías de la columna <strong>disponibles</strong> hacia <strong>seleccionados</strong>.</li><li><code>&#x3C;&#x3C;</code> Retorna todas las categorías desde <strong>disponibles</strong> hacia <strong>seleccionados</strong>.</li><li><code>></code> Mueve solo la categoría seleccionada desde <strong>disponibles</strong> hacia <strong>seleccionados</strong>.</li><li><code>&#x3C;</code> Retorna únicamente la categoría seleccionada desde <strong>seleccionados</strong> hacia <strong>disponibles</strong>.</li></ul></td></tr></tbody></table>

***

### **6. Validaciones y Reglas de Negocio**

* Solo se permiten **tres premios en total** entre todas las categorías.
* Las recompensas requieren validación de depósitos, apuestas o verificación de cuenta, según configuración.
* Si no se agregan premios, se mostrará el mensaje: _“No hay premios agregados”_.
* Para aplicar los cambios realizados, haz clic en el botón **Guardar** ubicado en la parte inferior.\
  Si deseas descartar la información ingresada, utiliza el botón **Limpiar** para restablecer los campos a su estado inicial.
* Solo se mostrarán los bonos disponibles en esta sección que se encuentren vigentes, activos en la plataforma y hayan sido creados desde el módulo de bonos. [Crear Bono.](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono. "mention")

### **6. Control de Versiones**

<table><thead><tr><th width="107">Versión</th><th width="117">Fecha</th><th width="161">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21/08/2025</td><td>Karol Navia</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>1/12/2025</td><td>Karol Navia</td><td>Agregar el campo <em>(<strong>Canales de envío permitidos)</strong></em></td></tr><tr><td>1.2</td><td>27/03/2026</td><td>David velasquez</td><td>Actualización de información</td></tr></tbody></table>

</details>

<details>

<summary><strong>🔽</strong> Verticales</summary>

<mark style="color:$info;">Configura las funcionalidades específicas de la plataforma para cada tipo de perfil. Desde esta sección es posible habilitar o deshabilitar el acceso a los diferentes módulos de la plataforma de Usuarios Online, de acuerdo con la configuración definida para la operación.</mark>

***

### 1. Acceso al Módulo <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de Acceso**: Backoffice > Herramientas > Partner ajustes > Partner > Configuración > Verticales

***

### 2. Visualización <a href="#id-4.-visualizacion" id="id-4.-visualizacion"></a>

<figure><img src="../../../.gitbook/assets/image (547).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Verticales</p></figcaption></figure>

***

### 3. Tipo de perfil

Selecciona el tipo de perfil para configurar las verticales. Cada opción disponible ofrece un modo distinto de configuración.

{% hint style="danger" %}
**Nota importante:** El funcionamiento de los campos se define de la siguiente manera:



* Si el valor es **“Sí”**, la sección permanecerá desactivada con la [contingencia](https://virtualsoft.gitbook.io/untitled/glosario/#contingencia) activa para esa sección.
* Si el valor es **“No”**, la sección estará disponible en la plataforma sin [contigencia](https://virtualsoft.gitbook.io/untitled/glosario/#contingencia).
{% endhint %}

***

### 4. Verificar celular

Define para qué acciones se debe verificar el número de teléfono celular.

<table><thead><tr><th width="163.58331298828125">Campo</th><th width="514.4323120117188">Descripción</th></tr></thead><tbody><tr><td><strong><code>DEPOSITAR</code></strong></td><td>Define si el usuario debe verificar su número de celular para realizar depósitos.</td></tr><tr><td><strong><code>APUESTAS_DEPORTIVAS</code></strong></td><td>Configura si es necesario verificar el celular para realizar apuestas deportivas.</td></tr><tr><td><strong><code>APUESTAS_CASINO</code></strong></td><td>Configura si los usuarios deben verificar su celular para apostar en juegos de casino.</td></tr><tr><td><strong><code>RETIROS</code></strong></td><td>Determina si la verificación de celular es necesaria para realizar retiros.</td></tr><tr><td><strong><code>CASINO_EN_VIVO</code></strong></td><td>Establece si la verificación de celular es obligatoria para participar en juegos de casino en vivo.</td></tr><tr><td><strong><code>VIRTUALES</code></strong></td><td>Configura si se necesita verificación para acceder a apuestas virtuales.</td></tr></tbody></table>

</details>

<details>

<summary><strong>🔽</strong>Bonos landing de registro </summary>

Esta sección permite configurar los bonos que estarán disponibles para los usuarios en la landing de registro. Los bonos seleccionados serán mostrados durante el proceso de registro, permitiendo destacar las promociones disponibles para nuevos usuarios.

### 1. Acceso al Módulo:

**Ruta de Acceso**: Herramientas > Partner ajustes > Configuración > Bonos landing de registro&#x20;

***

### 2. Visualización:

<figure><img src="../../../.gitbook/assets/image (688).png" alt=""><figcaption><p>Figura #1. Configuración de Bonos Landing de Registro.</p></figcaption></figure>

***

### **3.Configuraciones**

La pantalla se encuentra compuesta por dos listas que permiten administrar los bonos disponibles y los bonos seleccionados para la landing de registro.

<table><thead><tr><th width="177">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Todos los bonos</code></strong></td><td>Muestra el listado de bonos disponibles que pueden ser agregados para la landing de registro.</td></tr><tr><td><strong><code>Bono seleccionado</code></strong></td><td>Muestra los bonos que serán visualizados en la landing de registro.</td></tr><tr><td><strong><code>Select</code></strong></td><td>Agrega el bono seleccionado desde la lista de bonos disponibles a la lista de bonos configurados para la landing.</td></tr><tr><td><strong><code>Remove</code></strong></td><td>Retira un bono de la lista de bonos configurados para la landing de registro.</td></tr></tbody></table>

### 4. Funcionamiento

Para agregar un bono a la landing de registro:

1. Seleccione el bono deseado en la sección **Todos los bonos**.
2. Haga clic en el botón **Select**.
3. El bono será trasladado a la sección **Bono seleccionado**.

Para retirar un bono de la landing de registro:

1. Seleccione el bono que desea eliminar en la sección **Bono seleccionado**.
2. Haga clic en el botón **Remove**.
3. El bono dejará de estar disponible en la landing de registro.

### 5. Validaciones y Reglas de Negocio

* Solo los bonos disponibles en el sistema podrán ser seleccionados para la landing de registro.
* Un mismo bono no podrá agregarse más de una vez a la lista de bonos seleccionados.
* Los bonos configurados en la sección **Bono seleccionado** serán los únicos que se mostrarán en la landing de registro.
* Al retirar un bono mediante la opción **Remove**, este dejará de visualizarse en la landing de registro una vez se guarden los cambios.
* Los cambios realizados en esta configuración aplicarán únicamente después de guardar la información.

</details>

<details>

<summary><strong>🔽</strong> Bonos de cumpleaños</summary>

<mark style="color:$info;">Asigna a los usuarios bonos Freebet o Freecasino por campaña en la fecha de su cumpleaños.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Herramientas > Partner Ajustes > Configuración > Bono cumpleaños

***

### 2. Visualización general

<figure><img src="../../../.gitbook/assets/image (49).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección bonos de cumpleaños.</p></figcaption></figure>

***

### 3. Acciones disponibles.

<table><thead><tr><th width="154">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="configuracion-1.md#id-4.-como-agregar-un-bono-de-cumpleanos">A<strong>signar bono de cumpleaños</strong></a></td><td>Permite otorgar un bono de cumpleaños a todos los jugadores cuyo cumpleaños coincida con la fecha en que se aplica el bono.</td></tr></tbody></table>

#### 4. ¿Cómo agregar un bono de cumpleaños?&#x20;

{% @guideflow/guideflow-embed requestedUrl="https://app.guideflow.com/player/8koonnlh5k" %}

***

### 4. Validaciones y Reglas de Negocio

* En el apartado “**Todos los bonos**” se mostrarán únicamente los bonos creados que no estén asignados a los usuarios.
* En el apartado **“Bono seleccionado”** se listarán los bonos que estén siendo asignados a los usuarios.
* Solo estarán disponibles los bonos de tipo **Freebet** y **Freecasino**.
* Para que un bono se muestre, debe haber sido creado desde **Torneos y Bonos** con una campaña de marketing asociada y estado activo.
* El bono será entregado automáticamente al usuario el día de su cumpleaños sin interferir con algún otro tipo de bonos.
* Únicamente podrá asignarse un bono por tipo _(por ejemplo: Un bono Freebet y un bono Freecasino, pero no dos bonos Freebet)_.
* Este proceso podrá ser realizado por los usuarios que tengan permisos en la sección **Partner Ajustes**.

</details>

<details>

<summary><strong>🔽</strong> Límites de Comisión</summary>

<mark style="color:$info;">Configura los porcentajes de comisión aplicables a las diferentes verticales y tipos de transacción disponibles dentro del programa de afiliados. Las configuraciones se realizan según el perfil seleccionado y determinan las condiciones bajo las cuales se generarán las comisiones.</mark>

### 1. Acceso al Módulo:

**Ruta de Acceso**: Herramientas > Partner ajustes > Configuración > Límites de Comisión

***

### 2. Visualización:

<figure><img src="../../../.gitbook/assets/image (689).png" alt=""><figcaption><p><strong>Figura #1. Configuración de Límites de Comisión.</strong></p></figcaption></figure>

***

### 3. Configuraciones Disponibles

<table><thead><tr><th width="140">Configuración</th><th width="153">Tipo de Control</th><th width="389">Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de Perfil</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el perfil sobre el cual se configurarán las comisiones. Las opciones disponibles son: Concesionario, Operadores, Punto de Venta y Afiliador.</td></tr><tr><td><strong><code>Sportbook GGR Punto de Venta IP</code></strong></td><td>Interruptor </td><td>Al activar esta opción, se habilita el campo <strong>% Comisión</strong>, donde se define el porcentaje de comisión que recibirá el punto de venta sobre el GGR generado por apuestas deportivas identificadas mediante la dirección IP del punto de venta.</td></tr><tr><td><strong><code>Depósito Punto de Venta</code></strong></td><td>Interruptor </td><td>Al activar esta opción, se habilita el campo <strong>% Comisión</strong>, donde se configura el porcentaje de comisión que recibirá el punto de venta por cada depósito realizado.</td></tr><tr><td><strong><code>Notas de Retiro Punto de Venta</code></strong></td><td>Interruptor </td><td>Al activar esta opción, se habilita el campo <strong>% Comisión</strong>, donde se define el porcentaje de comisión que recibirá el punto de venta por las operaciones de retiro realizadas por los usuarios.</td></tr><tr><td><strong><code>Sportbook GGR Afiliados</code></strong></td><td>Interruptor </td><td>Al activar esta opción, se habilita el campo <strong>% Comisión</strong>, donde se configura el porcentaje de comisión que recibirá el afiliado sobre el GGR generado por sus usuarios referidos.</td></tr><tr><td><strong><code>Sportbook NGR Afiliados</code></strong></td><td>Interruptor </td><td>Al activar esta opción, se habilita el campo <strong>% Comisión</strong>, donde se define el porcentaje de comisión que recibirá el afiliado sobre el NGR generado por sus usuarios referidos.</td></tr><tr><td><strong><code>Sportbook GGR Punto de Venta</code></strong></td><td>Interruptor </td><td>Al activar esta opción, se habilita el campo <strong>% Comisión</strong>, donde se configura el porcentaje de comisión que recibirá el punto de venta sobre el GGR generado por las apuestas deportivas.</td></tr><tr><td><strong><code>Apuestas Sport Punto de Venta</code></strong></td><td>Interruptor </td><td>Al activar esta opción, se habilita el campo <strong>% Comisión</strong>, donde se define el porcentaje de comisión que recibirá el punto de venta sobre el volumen de apuestas deportivas realizadas.</td></tr><tr><td><strong><code>Casino NGR Afiliados</code></strong></td><td>Interruptor </td><td>Al activar esta opción, se habilita el campo <strong>% Comisión</strong>, donde se configura el porcentaje de comisión que recibirá el afiliado sobre el NGR generado por los juegos de casino de sus usuarios referidos.</td></tr><tr><td><strong><code>Depósito Comisión por Transacción</code></strong></td><td>Interruptor </td><td>Al activar esta opción, se habilita el campo <strong>% Comisión</strong>, donde se define el porcentaje de comisión que será aplicado a cada transacción de depósito realizada por los usuarios.</td></tr><tr><td><strong><code>Depósito Afiliados</code></strong></td><td>Interruptor </td><td>Al activar esta opción, se habilita el campo <strong>% Comisión</strong>, donde se configura el porcentaje de comisión que recibirá el afiliado por los depósitos realizados por sus usuarios referidos.</td></tr></tbody></table>

***

### 4. Validaciones y Reglas de Negocio

* El campo **Comisión (%)** solo estará disponible cuando la configuración correspondiente se encuentre habilitada.
* El porcentaje de comisión será obligatorio cuando una configuración se encuentre activa.
* El valor ingresado en el campo **Comisión (%)** debe ser numérico.
* No será posible guardar una configuración activa sin haber definido un porcentaje de comisión.
* Las configuraciones de comisión aplican únicamente para el tipo de perfil seleccionado.
* Una configuración deshabilitada no generará comisiones, aunque tenga un porcentaje previamente configurado.
* Los cambios realizados entrarán en vigencia una vez la configuración sea guardada correctamente.

</details>

***

### 5. Control de Versiones general.

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="101">Versión</th><th width="131">Fecha</th><th width="156">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2025-12-12</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>2026-04-01</td><td>David Velasquez</td><td>Ajuste en sección seguridad</td></tr><tr><td>1.2</td><td>2026-04-15</td><td>Karol Navia</td><td><p>Incorporación de los manuales:</p><ul><li>Puntos equivalentes por nivel </li><li>Tipos de movimientos <em>(Nota: Por cada monto en XXX va a obtener Z puntos base)</em></li></ul></td></tr><tr><td>1.3</td><td>2026-04-20</td><td>Karol Navia</td><td>Mejoras en <strong><code>Ajustes Generales</code></strong></td></tr><tr><td>1.4</td><td>2026-05-08</td><td>Ronald Peláez</td><td>Ajuste en el campo <strong><code>verificación en dos pasos</code></strong> del módulo seguridad.</td></tr><tr><td>1.5</td><td>2026-07-01</td><td>Ronald Peláez</td><td>Nueva funcionalidad en seguridad "<strong><code>Inactivación por regla automática</code></strong>"</td></tr></tbody></table>

</details>
