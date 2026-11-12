# Cambiar contraseña.

### 1. Acceso al Módulo

**Ruta de Acceso**:

1. Usuarios Online > Menú principal > Gestión > Cambiar Contraseña

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (193).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Cambiar Contraseña.</p></figcaption></figure>

***

### **3. Acciones del Usuario**

<table><thead><tr><th width="246">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/usuarios/usuarios-online/manual-de-plataforma/gestion/cambiar-contrasena.#id-6.-cambiar-contrasena"><strong><code>Cambiar contraseña</code></strong></a></td><td>Utiliza el formulario de cambio de contraseña para establecer una clave de acceso a la cuenta.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/usuarios/usuarios-online/manual-de-plataforma/gestion/cambiar-contrasena.#id-4.-configuracion-del-doble-factor-de-autenticacion-2fa"><strong><code>Activar doble factor de autenticación</code></strong></a></td><td>Despliega el pop-up para activar el doble factor de autenticación en caso de no haberlo activado luego del primer inicio de sesión.</td></tr></tbody></table>

***

***

### **4. Configuración del Doble factor de autenticación&#x20;**_**(2FA)**_

{% hint style="warning" %}
**Notas:**

* Solo aplica si la plataforma tiene configurado el proceso 2FA desde [BackOffice](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#seguridad).
* Una vez activado desde Usuarios Online _(Si no se activa con el primer inicio de sesión)_ no se podrá desactivar, solo se desactivará si se realiza el proceso desde [BackOffice](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/jugadores/configuracion-seccion-jugadores#id-2.2.-seguridad-y-cambios).
* También es posible marcar dispositivos como seguros al momento de [iniciar sesión](https://virtualsoft.gitbook.io/manuales/usuarios/usuarios-online/manual-de-plataforma/inicio-de-sesion#id-6.-doble-factor-de-autenticacion-2fa).
{% endhint %}

El doble factor de autenticación (2FA) refuerza la seguridad del inicio de sesión solicitando un código de verificación en cada acceso.

{% columns %}
{% column %}
✅ **Activado:** el sistema pedirá el código de verificación en cada inicio de sesión _(en los dispositivos que no estén marcados como seguros)._
{% endcolumn %}

{% column %}
❌ **Desactivado:** el usuario podrá ingresar únicamente con su usuario y contraseña.
{% endcolumn %}
{% endcolumns %}

<figure><img src="../../../.gitbook/assets/image (199) (1).png" alt=""><figcaption><p>Figura #2: Pop-up de activar el 2FA.</p></figcaption></figure>

Al iniciar sesión se mostrará un pop-up para activar y configurar el **2FA** en tu cuenta para mayor seguridad al inicio de sesión.

#### 4.1. Activación del doble factor de autenticación

{% stepper %}
{% step %}
**Escanear código QR**

Abre una aplicación de autenticación como _Google Authenticator_ o _Microsoft Authenticator_ y escanea el código QR mostrado en pantalla.

> En caso de no poder escanearlo, copia el código que aparece debajo del QR e insértalo manualmente en la aplicación.
{% endstep %}

{% step %}
**Generar código de verificación**

La aplicación generará un código temporal de seis dígitos.
{% endstep %}

{% step %}
**Ingresar código en la plataforma**

Ingresa el código de verificación en los cuadros, escribiendo un dígito en cada uno, ubicados debajo del mensaje:

> "_Ingresa el código de verificación generado por la aplicación"_
{% endstep %}

{% step %}
**Seleccionar dispositivo como seguro**

Marca el dispositivo actual como confiable mediante la selección del recuadro correspondiente. Al hacerlo, no se solicitará el código de verificación en futuros inicios de sesión desde este dispositivo durante el tiempo que esté configurado en [BackOffice](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#seguridad).

Si se inicia sesión desde un dispositivo diferente o no marcado como seguro, el sistema solicitará nuevamente el código de verificación del 2FA.
{% endstep %}

{% step %}
**Activar 2FA**

Haz clic en el botón **"Activar 2FA"** para finalizar la configuración.

* ✅ Si la activación fue **exitosa**, aparecerá un mensaje confirmando que el 2FA se creó correctamente.
* ❌ Si ocurre un **error**, se mostrará un mensaje indicando que no fue posible completar la activación.
{% endstep %}
{% endstepper %}

{% hint style="danger" %}
**Nota importante:** Al activar el 2FA, la plataforma solicitará un código de verificación en cada inicio de sesión, excepto cuando el dispositivo haya sido marcado como seguro. Una vez habilitado, el 2FA no podrá desactivarse desde la cuenta del usuario.
{% endhint %}

***

### **5. Cambiar contraseña**

Actualiza la contraseña de acceso a la plataforma.

<table><thead><tr><th width="222.88897705078125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ingrese la contraseña actual</code></strong></td><td>Clave actual de acceso a la cuenta.</td></tr><tr><td><strong><code>Ingrese la contraseña nueva</code></strong></td><td>Nueva clave de acceso que tendrá la cuenta.</td></tr><tr><td><strong><code>Confirme la contraseña nueva</code></strong></td><td>Confirmar la nueva clave de acceso.</td></tr></tbody></table>

Envía los datos ingresados y aplica el cambio de contraseña desde el botón "**`Guardar`**".

{% hint style="warning" %}
**Notas:**&#x20;

* Los 3 campos del formulario son obligatorios para poder cambiar la contraseña.
* Al solicitar el cambio de contraseña, se requerirá nuevamente la validación mediante doble factor de autenticación, incluso si esta ya fue realizada al iniciar sesión y el dispositivo se encuentra marcado como seguro. Esta validación solo aplica para las cuentas que tengan habilitado el doble factor de autenticación.
{% endhint %}

***

### **6. Validaciones y Reglas de Negocio**

* Todos los campos son obligatorios.
* La nueva contraseña debe tener al menos 8 caracteres.
* La nueva contraseña debe contener al menos:
  * Una letra minúscula.
  * Una letra mayúscula.
  * Un número.
* Las contraseñas nuevas deben coincidir en ambos campos.
* Si las validaciones no se cumplen, no se permite guardar la nueva contraseña.
* Si se intenta cambiar la contraseña y no se ingresa el código de seguridad correcto _(En caso de estar activo)_, se debe realizar nuevamente el proceso e ingresar otro código.

***

### **7. Control de Versiones**

<details>

<summary>🕛Historial de versiones</summary>

| Versión | Fecha      | Autor           | Cambios Realizados                         |
| ------- | ---------- | --------------- | ------------------------------------------ |
| 1.0     | 22/07/2025 | Ronald Pelaez   | Documento inicial                          |
| 2.0     | 16/09/2025 | David velasquez | Mejora de formato e incorporación del 2FA. |
| 2.1     | 08/05/2026 | Ronald Peláez   | Mejora en formato y ajuste en 2FA.         |
| 2.2     | 14/07/2026 | Ronald Peláez   | Ajuste en nota por cambio de contraseña.   |

</details>
