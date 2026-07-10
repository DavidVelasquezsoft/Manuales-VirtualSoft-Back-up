---
description: >-
  Esta sección permite a los usuarios verificar su identidad cargando
  documentos   oficiales y completar el proceso de verificación mediante
  proveedores   integrados como Jumio y Sumsub.
---

# Verificar cuenta.

## Verificar cuenta

### 1. Acceso al módulo

**Ruta de acceso**: Menú → Verificar cuenta

***

### 🖼️ 2. Visualización

Al acceder a esta sección, el usuario encontrará la opción para iniciar el proceso de verificación de identidad.

<figure><img src="../../../.gitbook/assets/image (168) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Verificar cuenta.</p></figcaption></figure>

En caso de que el usuario no esté verificado, se desplegará un pop-up al iniciar sesión que lo dirigirá directamente al flujo de verificación.

<figure><img src="../../../.gitbook/assets/image (169) (1).png" alt="" width="272"><figcaption><p>Figura #2: Captura de pantalla pop-up Verificar cuenta.</p></figcaption></figure>

***

### **🧑‍💻** 3. Acciones del Usuario

<table><thead><tr><th width="218.77783203125">Sección</th><th width="148.44451904296875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td>Verificar cuenta</td><td>Botón</td><td>Inicia el proceso de verificación con el proveedor correspondiente.</td></tr><tr><td>Reintentar verificación</td><td>Botón (si aplica)</td><td>Se habilita si el usuario tiene intentos disponibles para reintentar.</td></tr></tbody></table>

***

### 4. Proveedores disponibles

Actualmente, el sistema permite realizar la verificación mediante los siguientes proveedores:

* **Jumio**
* **Sumsub**

Al iniciar el proceso, el usuario será redirigido automáticamente al proveedor correspondiente.

{% hint style="warning" %}
**Nota**: Se recomienda tener a la mano el documento oficial y acceso a la cámara para completar el proceso sin interrupciones.
{% endhint %}

***

### 5. Validaciones y Reglas de Negocio

* Si el usuario ya ha sido verificado, no podrá volver a realizar el proceso.
* Si el usuario es **rechazado de forma final por Sumsub**, no podrá intentar nuevamente a menos que:
  * Se verifique manualmente desde el BackOffice.
  * Se reinicie su proceso en el BackOffice de Sumsub.
* El usuario tiene un **máximo de 5 intentos de reenvío (resubmission)**, que permiten:
  * Volver a subir el documento de identidad.
  * Volver a tomarse una selfie.
  * Hacer ambas acciones.

{% hint style="warning" %}
**Nota:** La notificación de rechazo le llegará al usuario por el medio configurado en el BackOffice (correo, mensaje, etc.) y lo redirigirá nuevamente a la plataforma de Doradobet para que pueda repetir el proceso si aún tiene intentos disponibles.
{% endhint %}

***

### 6. Flujo de verificación

#### Proceso detallado:

1. El usuario accede a la sección **Verificar cuenta** desde el menú Gestión.
2. Si ya está verificado, el proceso finaliza.
3. Si no está verificado:
   * Es redirigido a Sumsub.
   * Carga foto del documento de identidad.
   * Se toma una selfie.
4. Posibles resultados del proceso de verificación

A continuación, se detallan los posibles resultados del proceso de verificación de cuenta:

<table><thead><tr><th width="204.5555419921875">Resultado</th><th width="271.88885498046875">Descripción</th><th>Acción requerida</th></tr></thead><tbody><tr><td>✅ Verificación exitosa</td><td>La identidad fue validada correctamente.</td><td>No se requiere ninguna acción adicional.</td></tr><tr><td>⚠️ Verificación rechazada</td><td>La verificación no fue aprobada, pero aún tienes intentos disponibles.</td><td><ul><li><strong>Documento no válido:</strong> Sube nuevamente tu documento.</li><li><strong>Selfie no válida:</strong> Tómate una nueva selfie.</li><li><strong>Ambos no válidos:</strong> Repite ambos pasos.</li></ul></td></tr><tr><td>❌ Rechazo final</td><td>Se alcanzó el límite de 5 intentos de verificación sin éxito.</td><td>Contacta con soporte para una revisión manual.</td></tr></tbody></table>

***

### 7. Desverificación

Proceso por el cual una cuenta verificada pierde su estado de validación, quedando restringida en ciertas funcionalidades. Esto puede ocurrir por motivos de seguridad o normativos, y siempre será notificado al usuario mediante mensajes en la plataforma.

**Causas comunes de desverificación:**

* Vencimiento del documento de identidad registrado (la cuenta se desverificará automáticamente).
* Inconsistencias detectadas en la información del usuario.
* Incumplimiento de políticas internas de seguridad o requisitos regulatorios.

{% hint style="warning" %}
**Nota:** Para recuperar la verificación, el usuario deberá subsanar la causa que originó la desverificación y, una vez validada, la cuenta volverá a estar verificada.
{% endhint %}

***

### 8. Control de Versiones

| Versión | Fecha      | Autor           | Cambios Realizados                   |
| ------- | ---------- | --------------- | ------------------------------------ |
| 1.0     | 09/07/2025 | Ronald Pelaez   | Manual inicial                       |
| 1.1     | 09/16/2025 | David velasquez | incorporación de la desverificación. |
