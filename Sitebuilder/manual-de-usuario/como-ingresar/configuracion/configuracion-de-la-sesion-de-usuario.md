---
description: >-
  Permite gestionar los parámetros de inicio de sesión, seguridad y ajustes de
  sesión, garantizando una experiencia coherente, clara y funcional para el
  usuario.
---

# Configuración de la sesión de usuario

### 1. Acceso al Módulo

**Ruta de acceso**: Site Builder > Partner > Configuración > Configuración de la sesión de usuario

***

### 2. Visualización General.

<figure><img src="../../../.gitbook/assets/image (328).png" alt=""><figcaption><p>Figura #1: Captura de pantalla de la sección Configuración de inicio de sesión del usuario</p></figcaption></figure>

***

### **3. Configuraciones previas.**

Para modificar y acceder a la configuración de la sesión del usuario es necesario contar con la siguiente configuración:

<table><thead><tr><th width="207.55560302734375">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País para el cual se realizará la configuración.</td></tr></tbody></table>

***

### 4. Acciones de usuario

Permiten gestionar la información de usuario y configuración de la contraseña para el acceso a la plataforma.

<table><thead><tr><th width="192.44439697265625">Acción</th><th width="118.44439697265625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="configuracion-de-la-sesion-de-usuario.md#id-4.1.-inicio-de-sesion-de-usuario"><strong><code>Inicio de sesión de usuario</code></strong></a></td><td>Sección</td><td>Permite activar o desactivar los requerimientos que debe tener el usuario para iniciar sesión.</td></tr><tr><td><a href="configuracion-de-la-sesion-de-usuario.md#id-4.2.-parametros-de-seguridad-para-contrasenas"><strong><code>Parámetros de seguridad para contraseñas</code></strong></a></td><td>Sección</td><td>Permite configurar los parámetros de seguridad relacionados con la vigencia y renovación de las contraseñas de los usuarios.</td></tr><tr><td><a href="configuracion-de-la-sesion-de-usuario.md#id-4.3-ajustes-de-sesion-de-usuario"><strong><code>Ajustes de sesión de usuar</code></strong></a></td><td>Sección</td><td>Permite configurar los parámetros de seguridad relacionados con la sesión del usuario.</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Botón</td><td>Abre pop-up que permite guardar los cambios realizados.</td></tr></tbody></table>

<details>

<summary>4.1. Inicio de sesión de usuario</summary>

<figure><img src="../../../.gitbook/assets/image (330).png" alt=""><figcaption><p>Figura #2: Captura de pantalla sección Inicio de sesión de usuario</p></figcaption></figure>

Permite activar o desactivar los requerimientos que debe tener el usuario para iniciar sesión.

<table><thead><tr><th width="261.3333740234375">Campo</th><th width="109.8333740234375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Requiere aprobación del registro antes de permitir el inicio de sesión</code></strong></td><td>Interruptor</td><td>Indica si es necesario aprobar el registro de un usuario antes de permitirle iniciar sesión.</td></tr><tr><td><strong><code>Activar automáticamente al usuario después del registro</code></strong></td><td>Interruptor</td><td>Permite que el sistema active de forma automática la cuenta del usuario una vez completado su registro.</td></tr><tr><td><strong><code>Requiere aprobación para cambios en la información personal</code></strong></td><td>Interruptor</td><td>Define si las modificaciones realizadas por el usuario en su información personal deben ser revisada y aprobada antes de actualizarse.</td></tr></tbody></table>

</details>

<details>

<summary>4.2. Parámetros de seguridad para contraseñas</summary>

<figure><img src="../../../.gitbook/assets/image (331).png" alt=""><figcaption><p>Figura #3: Captura de pantalla sección Parámetros de seguridad para contraseñas</p></figcaption></figure>

Configura los parámetros de seguridad relacionados con la vigencia y renovación de las contraseñas de los usuarios.

<table><thead><tr><th width="275.75">Campo</th><th width="111.5">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cada cuántos días el usuario deberá actualizar la contraseña?</code></strong></td><td>Numérico</td><td>Define el período máximo en días tras el cual el usuario debe actualizar su contraseña obligatoriamente.</td></tr><tr><td><strong><code>¿Cuántos días antes de la expiración de la contraseña se debe notificar al usuario?</code></strong></td><td> Numérico</td><td>Especifica cuántos días antes del vencimiento de la contraseña el sistema debe enviar una alerta de recordatorio al usuario.</td></tr></tbody></table>

</details>

<details>

<summary>4.3 Ajustes de sesión de usuario</summary>

<figure><img src="../../../.gitbook/assets/image (333).png" alt=""><figcaption><p>Figura #4: Captura de pantalla sección Ajustes de sesión de usuario</p></figcaption></figure>

Configura los parámetros de seguridad relacionados con la sesión del usuario.

<table><thead><tr><th width="254.4166259765625">Campo</th><th width="126.77783203125">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tiempo de actividad en minutos para que la sesión se cierre automáticamente.</code></strong></td><td>Numérico</td><td>Define el tiempo máximo en minutos que una sesión puede permanecer activa antes de cerrarse automáticamente por inactividad.</td></tr><tr><td><strong><code>¿Cuántos días antes de la expiración de la sesión se debe notificar al usuario?</code></strong></td><td>Numérico</td><td>Indica con cuántos días de anticipación se debe enviar una notificación al usuario sobre la próxima expiración de su sesión.</td></tr><tr><td><strong><code>Cantidad máxima de intentos de inicio de sesión</code></strong></td><td>Numérico</td><td>Establece el número máximo de intentos de inicio de sesión permitidos antes de bloquear temporalmente la cuenta por seguridad.</td></tr></tbody></table>

</details>

***

### 5. Validaciones y Reglas de Negocio

* Al dar clic en el botón guardar los cambios pueden tardar unos minutos en aplicarse en la plataforma.
* En caso de presentarse un error, se mostrará un pop-up informando que los datos no se guardaron correctamente e indicando al usuario que intente nuevamente más tarde.

***

### 6. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="139.5">Versión</th><th width="150.5">Fecha</th><th width="152">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/10/2025</td><td>David Ortiz</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>27/11/2025</td><td>Ronald Peláez</td><td>Refinamiento</td></tr></tbody></table>

</details>
