---
description: >-
  Esta sección permite a los usuarios verificar su identidad cargando documentos
  oficiales y completar el proceso de verificación mediante proveedores
  integrados como Jumio y Sumsub.
---

# Verificar cuenta.

\
Al acceder a esta sección, el usuario encontrará la opción para iniciar el proceso de verificación de identidad.Figura #1: Captura de pantalla Verificar cuenta.En caso de que el usuario no esté verificado, se desplegará un pop-up al iniciar sesión que lo dirigirá directamente al flujo de verificación.![](https://www.gitbook.com/cdn-cgi/image/dpr=2,width=760,onerror=redirect,format=auto/https%3A%2F%2Ffiles.gitbook.com%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%2FI1JHf1oqcL4UapE69pFw%2Fuploads%2Fu56rlDPCSIsDQ3pMSvAo%2Fimage.png%3Falt%3Dmedia%26token%3D1e3f9a68-9a8a-43b3-b410-17cee6566a6b)Figura #2: Captura de pantalla pop-up Verificar cuenta.

***

#### 3. Acciones del Usuario <a href="#id-3.-acciones-del-usuario" id="id-3.-acciones-del-usuario"></a>

| Resultado               | Descripción       | Descripcion                                                           |
| ----------------------- | ----------------- | --------------------------------------------------------------------- |
| Verificar cuenta        | Botón             | Inicia el proceso de verificación con el proveedor correspondiente.   |
| Reintentar verificación | Botón (si aplica) | Se habilita si el usuario tiene intentos disponibles para reintentar. |

***

#### 4. Proveedores disponibles <a href="#id-4.-proveedores-disponibles" id="id-4.-proveedores-disponibles"></a>

Actualmente, el sistema permite realizar la verificación mediante los siguientes proveedores:

* **Jumio**
* **Sumsub**

Al iniciar el proceso, el usuario será redirigido automáticamente al proveedor correspondiente.**Nota**: Se recomienda tener a la mano el documento oficial y acceso a la cámara para completar el proceso sin interrupciones.

***

#### 5. Validaciones y Reglas de Negocio <a href="#id-5.-validaciones-y-reglas-de-negocio" id="id-5.-validaciones-y-reglas-de-negocio"></a>

* Si el usuario ya ha sido verificado, no podrá volver a realizar el proceso.
* Si el usuario es **rechazado de forma final por Sumsub**, no podrá intentar nuevamente a menos que:
  * Se verifique manualmente desde el BackOffice.
  * Se reinicie su proceso en el BackOffice de Sumsub.
* El usuario tiene un **máximo de 5 intentos de reenvío (resubmission)**, que permiten:
  * Volver a subir el documento de identidad.
  * Volver a tomarse una selfie.
  * Hacer ambas acciones.

**Nota:** La notificación de rechazo le llegará al usuario por el medio configurado en el BackOffice (correo, mensaje, etc.) y lo redirigirá nuevamente a la plataforma de Doradobet para que pueda repetir el proceso si aún tiene intentos disponibles.

***

#### 6. Flujo de verificación <a href="#id-6.-flujo-de-verificacion" id="id-6.-flujo-de-verificacion"></a>

**Proceso detallado:**

1. El usuario accede a la sección **Verificar cuenta** desde el menú Gestión.
2. Si ya está verificado, el proceso finaliza.
3. Si no está verificado:
   * Es redirigido a Sumsub.
   * Carga foto del documento de identidad.
   * Se toma una selfie.
4. Posibles resultados del proceso de verificación

A continuación, se detallan los posibles resultados del proceso de verificación de cuenta:

| ✅ Verificación exitosa    | La identidad fue validada correctamente.                               | No se requiere ninguna acción adicional.                                                                                                                                                                                 |
| ------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ⚠️ Verificación rechazada | La verificación no fue aprobada, pero aún tienes intentos disponibles. | <ul><li><strong>Documento no válido:</strong> Sube nuevamente tu documento.</li><li><strong>Selfie no válida:</strong> Tómate una nueva selfie.</li><li><strong>Ambos no válidos:</strong> Repite ambos pasos.</li></ul> |
| ❌ Rechazo final           | Se alcanzó el límite de 5 intentos de verificación sin éxito.          | Contacta con soporte para una revisión manual.                                                                                                                                                                           |

***

#### 7. Control de Versiones <a href="#id-7.-control-de-versiones" id="id-7.-control-de-versiones"></a>

| 1.0 | 09/07/2025 | Ronald Pelaez | Manual inicial |
| --- | ---------- | ------------- | -------------- |
