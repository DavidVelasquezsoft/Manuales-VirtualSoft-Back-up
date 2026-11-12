---
description: >-
  Esta funcionalidad le permite tanto recuperar su clave en caso de haberla
  olvidado como también desbloquear su usuario cuando usted ha sobrepasado el
  máximo número de intentos fallidos de acceso
---

# Restaurar contraseña

## Configuración general

**1. Acceso al Módulo**

**Ruta de acceso**: En la página de inicio de sesión, haz clic en el enlace **"¿Olvidaste tu contraseña?"** ubicado debajo del botón **Iniciar sesión**.

***

**2. Visualización**

<figure><img src="../../../.gitbook/assets/image (21) (1).png" alt="" width="563"><figcaption><p>Figura#1: Captura de pantalla restaurar contraseña.</p></figcaption></figure>

**🔐 2.1. Acciones del Usuario**

| Sección                              | Acción             | Descripción                                                      | Validaciones                                                   |
| ------------------------------------ | ------------------ | ---------------------------------------------------------------- | -------------------------------------------------------------- |
| `Enlace "¿Olvidaste tu contraseña?"` | Clic en enlace     | Redirige al formulario de recuperación de cuenta.                | El usuario debe haber registrado previamente un correo válido. |
| `Ingreso de correo`                  | Escribir texto     | Se solicita ingresar el correo electrónico asociado a la cuenta. | Debe tener formato válido (ej: usuario@correo.com).            |
| `Enviar solicitud`                   | Botón              | Envía un correo con el enlace de recuperación.                   | El sistema valida que el correo esté registrado.               |
| `Verificación del enlace`            | Acceso desde email | El usuario debe abrir el enlace enviado a su correo electrónico. | El enlace tiene un tiempo de expiración por seguridad.         |
| `Crear nueva contraseña`             | Escribir texto     | El usuario debe ingresar y confirmar su nueva contraseña.        | Mínimo 4 caracteres, debe coincidir en ambos campos.           |
| `Confirmar recuperación`             | Botón              | Guarda la nueva contraseña y permite volver al inicio de sesión. | Se muestra mensaje de éxito si todo es correcto.               |

***

**⚙️ 2.2. Otras configuraciones**

| Campo                          | Tipo de control | Descripción                                                     | Observaciones                                                  |
| ------------------------------ | --------------- | --------------------------------------------------------------- | -------------------------------------------------------------- |
| `Tiempo de validez del enlace` | Sistema         | Define cuánto tiempo estará activo el enlace enviado al correo. | Generalmente entre 15 y 30 minutos.                            |
| `Seguridad del proceso`        | Interna         | Validación de identidad del usuario mediante correo registrado. | Asegura que solo el titular del correo pueda cambiar la clave. |

***

**✅ 3. Validaciones y Reglas de Negocio**

* El correo ingresado debe estar registrado.
* El enlace de recuperación es de un solo uso y tiene expiración por tiempo.
* Las nuevas contraseñas deben cumplir con los criterios mínimos de seguridad.
* El proceso de recuperación solo se puede completar si el usuario accede al enlace desde su correo electrónico.
* Tras la restauración, el usuario puede iniciar sesión con la nueva contraseña inmediatamente.

***

**🕒 4. Control de Versiones**

| Versión | Fecha      | Autor       | Cambios Realizados                                                        |
| ------- | ---------- | ----------- | ------------------------------------------------------------------------- |
| 1.0     | 2025-07-25 | Karol Navia | Creación inicial del manual de recuperación de contraseña para DoradoBet. |
