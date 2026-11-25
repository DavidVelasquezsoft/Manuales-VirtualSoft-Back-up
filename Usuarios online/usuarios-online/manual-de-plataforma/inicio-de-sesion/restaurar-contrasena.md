# Restaurar contraseña

<mark style="color:$info;">Permite al usuario recuperar su contraseña en caso de haberla olvidado, así como desbloquear su usuario cuando ha sobrepasado el número máximo de intentos fallidos de acceso.</mark>

***

### 1. Acceso al Módulo

**Ruta de acceso**: En la página de inicio de sesión, se hace clic en el enlace **"¿Olvidaste tu contraseña?"** ubicado debajo del botón **Iniciar sesión**.

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (21) (1).png" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla restaurar contraseña.</p></figcaption></figure>

***

### 3. Acciones del Usuario

<table><thead><tr><th width="200">Sección</th><th width="150">Acción</th><th>Descripción</th><th>Validaciones</th></tr></thead><tbody><tr><td><strong>Enlace "¿Olvidaste tu contraseña?"</strong></td><td>Clic en enlace</td><td>Redirige al formulario de recuperación de cuenta.</td><td>El usuario debe haber registrado previamente un correo válido.</td></tr><tr><td><strong>Ingreso de correo</strong></td><td>Escribir texto</td><td>Se solicita ingresar el correo electrónico asociado a la cuenta.</td><td>Debe tener formato válido (ej: usuario@correo.com).</td></tr><tr><td><strong>Enviar solicitud</strong></td><td>Botón</td><td>Envía un correo con el enlace de recuperación.</td><td>El sistema valida que el correo esté registrado.</td></tr><tr><td><strong>Verificación del enlace</strong></td><td>Acceso desde email</td><td>El usuario debe abrir el enlace enviado a su correo electrónico.</td><td>El enlace tiene un tiempo de expiración por seguridad.</td></tr><tr><td><strong>Crear nueva contraseña</strong></td><td>Escribir texto</td><td>El usuario debe ingresar y confirmar su nueva contraseña.</td><td>Mínimo 4 caracteres, debe coincidir en ambos campos.</td></tr><tr><td><strong>Confirmar recuperación</strong></td><td>Botón</td><td>Guarda la nueva contraseña y permite volver al inicio de sesión.</td><td>Se muestra mensaje de éxito si todo es correcto.</td></tr></tbody></table>

***

### 4. Otras configuraciones

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th><th>Observaciones</th></tr></thead><tbody><tr><td><strong><code>Tiempo de validez del enlace</code></strong></td><td>Sistema</td><td>Define cuánto tiempo estará activo el enlace enviado al correo.</td><td>Generalmente entre 15 y 30 minutos.</td></tr><tr><td><strong><code>Seguridad del proceso</code></strong></td><td>Interna</td><td>Validación de identidad del usuario mediante correo registrado.</td><td>Asegura que solo el titular del correo pueda cambiar la clave.</td></tr></tbody></table>

***

### 5. Validaciones y Reglas de Negocio

* El correo ingresado debe estar registrado.
* El enlace de recuperación es de un solo uso y tiene expiración por tiempo.
* Las nuevas contraseñas deben cumplir con los criterios mínimos de seguridad.
* El proceso de recuperación solo se puede completar si el usuario accede al enlace desde su correo electrónico.
* Tras la restauración, el usuario puede iniciar sesión con la nueva contraseña inmediatamente.

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>25/07/2025</td><td>Karol Navia</td><td>Creación inicial del manual de recuperación de contraseña para DoradoBet.</td></tr><tr><td>1.1</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
