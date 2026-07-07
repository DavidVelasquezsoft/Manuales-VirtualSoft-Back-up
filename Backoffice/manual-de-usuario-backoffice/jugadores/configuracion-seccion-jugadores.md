---
description: >-
  Permite realizar la configuración de la cuenta del usuario en cada una de las
  secciones disponibles.
---

# Configuración sección Jugadores

### 1. Acceso al módulo

**Ruta de acceso**: Backoffice > Jugadores > Configuración

***

### 2. Secciones de configuración

{% tabs %}
{% tab title="2.1. Cambio de contraseña" %}
### 2.1. Cambio de contraseña

Permite actualizar la contraseña del usuario diligenciando los siguientes campos:

#### 🖼️ Visualización

<figure><img src="../../.gitbook/assets/image (434).png" alt=""><figcaption><p>Figura#2: Captura de pantalla de la sección cambiar contraseña.</p></figcaption></figure>

#### 📑 Descripción de campos&#x20;

<table><thead><tr><th width="199.33343505859375">Campo</th><th width="129">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nueva Contraseña</code></strong></td><td>Contraseña</td><td>Ingrese la nueva clave de acceso.</td></tr><tr><td><strong><code>Confirmar Contraseña</code></strong></td><td>Contraseña</td><td>Vuelva a ingresar la contraseña para validarla.</td></tr><tr><td><strong><code>Limpiar</code></strong></td><td>Botón</td><td>Elimina los datos ingresados en los campos anteriores.</td></tr></tbody></table>

Para guardar los cambios haga clic en el botón **"Guardar"**.
{% endtab %}

{% tab title="2.2. Seguridad y Cambios" %}
### 2.2. Seguridad y Cambios

Sección con diversas configuraciones relacionadas con la seguridad del usuario y la plataforma.

#### 🖼️ Visualización

<figure><img src="../../.gitbook/assets/image (621).png" alt=""><figcaption><p>Figura #2: Captura de pantalla sección seguridad y cambios</p></figcaption></figure>

#### 📑 Descripción de campos&#x20;

{% hint style="warning" %}
**Nota:** Al modificar una opción, el sistema aplica el cambio de manera inmediata.
{% endhint %}

<table><thead><tr><th width="134.22216796875">Campo</th><th width="107.33334350585938">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Desbloquear Usuario por Clave</code></strong></td><td>Interruptor</td><td>Permite desbloquear la cuenta del usuario en caso de que haya sido bloqueada.</td></tr><tr><td><strong><code>Generar Contraseña</code></strong></td><td>Interruptor</td><td>Permite generar una nueva contraseña automática para la cuenta del usuario. y la envía al correo registrado.</td></tr><tr><td><strong><code>Estado del Usuario</code></strong></td><td>Interruptor</td><td><strong>Activo:</strong> La cuenta está habilitada, permitiendo el acceso completo.<br><strong>Inactivo:</strong> La cuenta está deshabilitada, bloqueando el acceso a la plataforma.</td></tr><tr><td><strong><code>Estado de Contingencia</code></strong></td><td>Interruptor</td><td><strong>Activo:</strong> El usuario no puede ingresar a la cuenta ni operar.<br><strong>Inactivo:</strong> El usuario puede acceder y utilizar la plataforma sin restricciones.</td></tr><tr><td><strong><code>Contingencia Casino</code></strong> </td><td>Interruptor</td><td><strong>Activo:</strong> Restringe el acceso del usuario a juegos de casino.<br><strong>Inactivo:</strong> El usuario tiene acceso  a los juegos de casino</td></tr><tr><td><strong><code>Contingencia Retiros Retail</code></strong></td><td>Interruptor</td><td><p><strong>Activo:</strong> El usuario no podrá retirar en puntos físicos ni redes aliadas.<br><strong>Inactivo:</strong> El usuario podrá retirar en puntos físicos/redes aliadas y web.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si un usuario intenta realizar un retiro en un punto de venta o red aliada mientras la <a href="https://virtualsoft.gitbook.io/untitled/glosario#contingencia">contingencia</a> está activa, se mostrará un mensaje de error.</p></div></td></tr><tr><td><strong><code>Contingencia Casino en Vivo</code></strong></td><td>Interruptor</td><td><strong>Activo:</strong> Restringe el acceso del usuario al casino en vivo.<br><strong>Inactivo:</strong> El usuario puede participar en juegos de casino en vivo.</td></tr><tr><td><strong><code>Estado de Contingencia Deportivas</code></strong></td><td>Interruptor</td><td><strong>Activo:</strong> Restringe el acceso del usuario a las apuestas deportivas.<br><strong>Inactivo:</strong> El usuario puede realizar apuestas deportivas.</td></tr><tr><td><strong><code>Estado de Contingencia Virtuales</code></strong></td><td>Interruptor</td><td><strong>Activo:</strong> Restringe el acceso del usuario a los juegos virtuales<br><strong>Inactivo:</strong> El usuario puede acceder a juegos virtuales y realizar apuestas.</td></tr><tr><td><strong><code>Estado de Contingencia Póker</code></strong></td><td>Interruptor</td><td><strong>Activo:</strong> Restringe el acceso del usuario a los juegos de póker.<br><strong>Inactivo:</strong> El usuario puede participar en juegos de póker.</td></tr><tr><td><strong><code>Recibir publicidad</code></strong></td><td>Interruptor</td><td>Indica si el usuario autoriza recibir comunicaciones publicitarias.</td></tr><tr><td><strong><code>Estado de Registro del Usuario</code></strong></td><td>Interruptor</td><td><strong>Activo:</strong> Registro completo y verificado permitiendo acceso completo.<br><strong>Inactivo:</strong> Registro del usuario incompleto o suspendido con acceso limitado.</td></tr><tr><td><strong><code>Verificó DNI anterior</code></strong></td><td>Interruptor</td><td>Marca si se verificó correctamente la imagen anterior del documento (DNI).</td></tr><tr><td><strong><code>Verificó DNI posterior</code></strong></td><td>Interruptor</td><td>Marca si se verificó correctamente la imagen posterior del documento (DNI).</td></tr><tr><td><strong><code>Foto con documento</code></strong></td><td>Interruptor</td><td>Indica si el usuario subió la foto con el documento para verificación.</td></tr><tr><td><strong><code>Cancelar Cuenta</code></strong></td><td>Botón</td><td>Ejecuta la cancelación de la cuenta del usuario en la plataforma.</td></tr><tr><td><strong><code>Enviar SMS</code></strong></td><td>Interruptor</td><td><strong>Activo:</strong> Se habilita el envío automático de SMS al usuario para comunicados o marketing.<br><strong>Inactivo:</strong> No se enviarán SMS al usuario.</td></tr><tr><td><strong><code>Enviar Email</code></strong></td><td>Interruptor</td><td><strong>Activo:</strong> Permite el envío de correos electrónicos al usuario.<br><strong>Inactivo:</strong> Se bloquea el envío de correos electrónicos al usuario.</td></tr><tr><td><strong><code>Enviar Celular</code></strong></td><td>Interruptor</td><td><strong>Activo:</strong> Habilita el envío de notificaciones directas al dispositivo móvil.<br><strong>Inactivo:</strong> Se desactiva el envío de notificaciones móviles al usuario.</td></tr><tr><td><strong><code>Enviar Notificaciones Push</code></strong></td><td>Interruptor</td><td><strong>Activo:</strong> Se habilitan notificaciones de alertas y mensajes en tiempo real.<br><strong>Inactivo:</strong> Se bloquean este tipo de  notificaciones al usuario.</td></tr><tr><td><strong><code>Abusador de Bonos</code></strong></td><td>Interruptor</td><td><p>Clasifica al usuario según su adherencia a las políticas de bonos de la plataforma.<br></p><p><strong>Sí:</strong> Marca al usuario como alguien que ha infringido las políticas de bonos, utilizándolos de manera irregular o en contra de los términos establecidos.<br><strong>No:</strong> Indica que el usuario no ha incurrido en actividades que violen las reglas de bonificación, permitiendo el uso normal de las ofertas y promociones.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Esta contingencia activa la configuración para bonos, jackpot, torneos, sorteos y ruleta.</p><ul><li>Si la contingencia está activa, bloqueará completamente la ruleta, aunque ya tenga ruletas asignadas.</li></ul></div></td></tr><tr><td><strong><code>Enviar Código al Celular</code></strong></td><td>Interruptor</td><td>Habilita el envío de códigos de verificación al número de celular del usuario.</td></tr><tr><td><strong><code>Verificó Celular</code></strong></td><td>Interruptor</td><td>Marca si el usuario completó el proceso de validación de su número de celular.</td></tr><tr><td><strong><code>Contingencia Retail</code></strong></td><td>Interruptor</td><td><p><strong>Activo:</strong> Bloquea depósitos en puntos físicos/redes aliadas/corresponsales.<br><strong>Inactivo:</strong> Permite depósitos en puntos físicos/redes aliadas.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> No afecta depósitos por canales electrónicos.</p></div></td></tr><tr><td><strong><code>Contingencia Depósitos Retail</code></strong></td><td>Interruptor</td><td><p>Permite restringir los depósitos de los jugadores por medio de los puntos de venta.</p><p></p><p><strong>Activo:</strong> El jugador no podrá realizar depósitos en puntos físicos, redes aliadas, corresponsales o agentes autorizados.<br><strong>Inactivo:</strong> El jugador podrá realizar depósitos en puntos físicos, redes aliadas, corresponsales o agentes autorizados.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si se intenta depositar en la cuenta del usuario, aparecerá un mensaje indicando que tiene una restricción activa y debe contactar a soporte.</p><ul><li>Esta contingencia no afecta los depósitos por canales electrónicos.</li></ul></div></td></tr><tr><td><strong><code>Contingencia Depósitos Pasarela</code></strong></td><td>Interruptor</td><td><p>Permite restringir los depósitos de los jugadores por medio de los canales electrónicos.</p><p></p><p><strong>Activo</strong>: El jugador no podrá realizar depósitos por canales electrónicos como <a href="https://virtualsoft.gitbook.io/untitled/glosario#pasarela-de-pago">pasarelas de pago</a>, tarjetas o <a href="https://virtualsoft.gitbook.io/untitled/glosario#billetera">billeteras digitales</a>.<br><strong>Inactivo</strong>: El Jugador podrá realizar depósitos sin restricciones por medio de los canales electrónicos.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Si se intenta realizar un depósito con la contingencia activa, saldrá un pop-up de bloqueo indicando que no es posible realizar la transacción.</p><ul><li>Esta contingencia no afecta los depósitos por puntos de venta.</li></ul></div></td></tr><tr><td><strong><code>Doble factor de autenticación (</code></strong><em><strong><code>2FA</code></strong></em><strong><code>)</code></strong><br></td><td>Interruptor</td><td><p>Permite gestionar el doble factor de autenticación (2FA) del usuario seleccionado, reforzando la seguridad en el inicio de sesión.</p><ul><li><p><strong>Activo</strong>: El usuario recibirá un correo con el código QR para configurar la autenticación en su cuenta.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Notas</strong>: </p><ul><li>Si el partner no tiene habilitado el doble factor de autenticación desde <a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#seguridad">partner ajustes</a>, esta configuración no será visible.</li><li>Si esta configuración está activa y el usuario ha marcado su navegador como dispositivo seguro desde <a href="https://virtualsoft.gitbook.io/manuales/usuarios/usuarios-online/manual-de-plataforma/gestion/cambiar-contrasena.#id-3.2-configuracion-del-doble-factor-de-autenticacion-2fa#id-4.-configuracion-del-doble-factor-de-autenticacion-2fa"><strong>Usuarios Online</strong></a><strong>,</strong> no se solicitará el token de validación en los inicios de sesión durante el período definido en <a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#seguridad"><strong>Partner ajustes</strong></a>.</li></ul></div></li><li><strong>Inactivo</strong>: El usuario podrá iniciar sesión sin 2FA, pero tendrá la opción de activarlo manualmente si el <strong>partner</strong> lo tiene habilitado.</li></ul></td></tr><tr><td><strong><code>Registrado en Stradacarte</code></strong></td><td>Botón</td><td><p>Permite conocer si el usuario ya está registrado en la <a href="https://virtualsoft.gitbook.io/untitled/glosario/#pasarela-de-pago">pasarela de pago</a> Stradacarte.</p><ul><li><strong>Sí:</strong> El registro fue confirmado exitosamente por Stradacarte. El botón de registro ya no se muestra, pues no se requiere ninguna acción adicional.</li><li><strong>No:</strong> El usuario aún no está registrado. Se mostrará un botón que permite <strong>enviar los datos del usuario a Stradacarte para realizar el registro</strong>. Una vez el proveedor confirme el registro, el estado cambiará automáticamente a <em>“Sí”</em> y el botón no estará habilitado.</li></ul><blockquote><p>La visualización del estado y el uso del botón dependen de los permisos configurados para el usuario.</p></blockquote></td></tr></tbody></table>

#### ✅ Validaciones y reglas de negocio

* El **`2FA`** de un usuario solo podrá activarse si el partner lo habilitó en la sección [partner ajustes](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#seguridad); en caso de intentar activarlo sin estar habilitado a nivel de partner, se mostrará un mensaje de error.
* Al activar el **`2FA`** al usuario, recibirá un correo de notificación que la funcionalidad ha sido habilitada en su cuenta.
* Si se desactiva el **`2FA`** a un usuario, pero este está habilitado en el **partner**, el acceso será permitido sin **2FA**. No obstante, el usuario podrá **activarlo** nuevamente desde el pop-up o en la sección “**Cambiar contraseña**”.
* Al realizar el registro de un usuario en Stradacarte se enviará un correo al usuario notificándole el registro, con una URL de acceso e información del usuario.
{% endtab %}

{% tab title="2.3. Contingencia" %}
### 2.3. Contingencia

Permite establecer restricciones o bloqueos a un usuario según diferentes criterios.

#### 🖼️ Visualización

<figure><img src="../../.gitbook/assets/image (435).png" alt=""><figcaption><p>Figura#3: Captura de pantalla sección contingencia.</p></figcaption></figure>

#### 📑 Descripción de campos&#x20;

<table><thead><tr><th width="142.99993896484375">Campo</th><th width="117.00006103515625">Tipo de Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de bloqueo</code></strong></td><td>selección única</td><td>Permite seleccionar el motivo del bloqueo. (<em>Ejemplo:</em> <a href="https://virtualsoft.gitbook.io/untitled/glosario#autoexclusion"><em>Autoexclusión</em></a><em>, Contra Cargos, Bajo Revisión</em>)</td></tr><tr><td><strong><code>Tipo de contingencia</code></strong></td><td>selección múltiple</td><td>Define las <a href="https://virtualsoft.gitbook.io/untitled/glosario#vertical">verticales</a>  y áreas en las que se aplicará la <a href="https://virtualsoft.gitbook.io/untitled/glosario#contingencia">Contingencia</a>, (<em>Ejemplo: Deportivas, General, Casino, Retiro y Depósito.</em>)</td></tr><tr><td><strong><code>Selecciona un período</code></strong></td><td>Calendario</td><td>Permite definir la duración que tendrá la contingencia.</td></tr><tr><td><strong><code>Comentario </code></strong><mark style="color:red;"><strong><code>*</code></strong></mark></td><td>Texto </td><td>Campo obligatorio donde se debe ingresar una justificación o información relevante sobre la restricción aplicada.</td></tr></tbody></table>

Para guardar los cambios haga clic en el botón **"Guardar"**.
{% endtab %}

{% tab title="2.4. Límites" %}
### 2.4. Límites

Permite establecer límites de apuestas y transacciones para el usuario en diferentes [verticales](https://virtualsoft.gitbook.io/untitled/glosario#vertical).

#### 🖼️ Visualización

<figure><img src="../../.gitbook/assets/image (437).png" alt=""><figcaption><p>Figura#4: Captura de pantalla sección límites.</p></figcaption></figure>

#### 📑 Descripción de campos&#x20;

<table><thead><tr><th width="127.99993896484375">Campo</th><th width="131.00006103515625">Tipo de Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Casino</code></strong></td><td>Numérico</td><td>Indica el monto máximo de apuestas en juegos de casino.</td></tr><tr><td><strong><code>Live Casino</code></strong></td><td>Numérico</td><td>Indica el valor límite de las apuestas en juegos de casino en vivo.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#sportsbook"><strong><code>Sportbook</code></strong></a></td><td>Numérico</td><td>Define el límite de apuestas en eventos deportivos.</td></tr><tr><td><strong><code>Virtuales</code></strong></td><td>Numérico</td><td>Establece el valor máximo permitido en juegos virtuales.</td></tr><tr><td><strong><code>Depósitos</code></strong></td><td>Numérico</td><td>Establece el monto máximo que un usuario puede depositar.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Numérico</td><td>Fija el límite de retiro permitido para el usuario.</td></tr></tbody></table>

Para guardar los cambios haga clic en el botón "**Guardar**".
{% endtab %}
{% endtabs %}

***

### 3. Control de versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="106.99993896484375" align="right">Versión</th><th width="130.22222900390625">Fecha</th><th width="157.4444580078125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td align="right">1.0</td><td>08/092025</td><td>David velasquez</td><td>Actualización de formato</td></tr><tr><td align="right">1.1</td><td>26/09/2025</td><td>David velasquez</td><td>Incorporación del 2FA.</td></tr><tr><td align="right">1.2</td><td>02/12/2025</td><td>Ronald Peláez</td><td>Incorporación registro automático para Stradacarte</td></tr><tr><td align="right">1.3</td><td>12/05/2026</td><td>Ronald Peláez</td><td>Ajsutes 2FA de seguridad y cambios</td></tr></tbody></table>

</details>
