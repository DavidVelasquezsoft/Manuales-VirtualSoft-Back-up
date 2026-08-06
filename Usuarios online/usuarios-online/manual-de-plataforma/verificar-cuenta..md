# Verificar cuenta.

<mark style="color:$info;">Permite al usuario verificar su identidad para habilitar su cuenta en la plataforma. El proceso valida el documento de identidad y la identidad del titular a través de un proveedor externo especializado.</mark>

{% hint style="warning" %}
**Nota:** El proceso requiere el documento oficial de identidad y el acceso a la cámara del dispositivo para completarse sin interrupciones.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: Plataforma de usuarios online > Gestión > Verificar cuenta

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (210).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Verificar cuenta</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="200">Acción</th><th width="150">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Verificar cuenta</code></strong></td><td>Botón</td><td>Inicia el proceso de verificación con el proveedor correspondiente.</td></tr><tr><td><strong><code>Reintentar verificación</code></strong></td><td>Botón (si aplica)</td><td>Se habilita cuando el usuario dispone de intentos disponibles para repetir la verificación.</td></tr></tbody></table>

***

### 4. Proveedores disponibles

La verificación de identidad se realiza a través de un proveedor externo. El sistema admite los siguientes proveedores:

* **Jumio**
* **Sumsub**

{% hint style="warning" %}
**Nota:** Al iniciar el proceso, el sistema redirige automáticamente al usuario al proveedor de verificación correspondiente, el cual se determina según la configuración del **partner** y el **país** de la operación.
{% endhint %}

{% hint style="info" %}
En Doradobet Ecuador, el proveedor Jumio captura además información del **dispositivo** utilizado durante la verificación _(análisis de dispositivo o Device Risk)_. Esta información es complementaria: no agrega pasos al proceso ni modifica las condiciones con las que una verificación se aprueba o rechaza.
{% endhint %}

***

### 5. Flujo de verificación

{% stepper %}
{% step %}
**Acceso a la verificación de cuenta**

El usuario ingresa a la sección **Verificar cuenta** desde el menú **Gestión** de su cuenta.

{% hint style="info" %}
**Nota:** Si la cuenta ya se encuentra verificada, el proceso finaliza automáticamente y no continúa.
{% endhint %}
{% endstep %}

{% step %}
**Redirección al proveedor**

Cuando la cuenta no está verificada, el sistema redirige automáticamente al usuario al proveedor de verificación configurado para la plataforma y el país _(Jumio o Sumsub)_.
{% endstep %}

{% step %}
**Carga del documento de identidad**

El proveedor solicita la captura o carga del documento de identidad por ambos lados, el cual debe presentarse de forma clara y legible, siguiendo las indicaciones del proveedor.
{% endstep %}

{% step %}
**Captura de la selfie**

El proveedor solicita una selfie del usuario, siguiendo las indicaciones en pantalla, con el fin de confirmar su identidad.
{% endstep %}

{% step %}
**Resultado de la verificación**

Al finalizar el proceso, el proveedor analiza la información y la plataforma muestra uno de los siguientes resultados:

{% hint style="warning" %}
**Nota:** La notificación de rechazo se envía al usuario por el medio configurado en el BackOffice _(correo, mensaje, etc.)_ y lo redirige nuevamente a la plataforma para repetir el proceso, siempre que disponga de intentos.
{% endhint %}

<table><thead><tr><th width="164">Resultado</th><th width="278.2222900390625">Descripción</th><th>Acción requerida</th></tr></thead><tbody><tr><td>✅ <strong>Verificación exitosa</strong></td><td>La identidad se validó correctamente.</td><td>No requiere ninguna acción adicional.</td></tr><tr><td>⚠️ <strong>Verificación rechazada</strong></td><td>La verificación no fue aprobada, pero el usuario aún dispone de intentos.</td><td><ul><li><strong>Documento no válido:</strong> el usuario carga nuevamente su documento.</li><li><strong>Selfie no válida:</strong> el usuario captura una nueva selfie.</li><li><strong>Ambos no válidos:</strong> el usuario repite ambos pasos.</li></ul></td></tr><tr><td>❌ <strong>Rechazo final</strong></td><td>Se alcanzó el límite de 5 intentos de verificación sin éxito.</td><td>El usuario contacta con soporte para una revisión manual.</td></tr></tbody></table>
{% endstep %}

{% step %}
**Reintentar verificación** _(si aplica)_

Cuando la verificación es rechazada y el usuario aún dispone de intentos, el sistema habilita la opción de reintentar. El usuario repite el proceso corrigiendo lo indicado en el resultado hasta obtener una verificación exitosa o alcanzar el límite de intentos.
{% endstep %}
{% endstepper %}

***

### 6. Validaciones y reglas del negocio:

* La verificación de identidad se realiza a través de un proveedor externo (Jumio o Sumsub), según la configuración de la operación.
* Los proveedores de verificación varían según el partner y el país.
* Si el usuario ya se encuentra verificado, el proceso finaliza automáticamente y no puede repetirse.
* El usuario cuenta con un máximo de **5 intentos** de reenvío _(resubmission)_, que permiten cargar nuevamente el documento, capturar una nueva selfie o realizar ambas acciones.
* Si el usuario es **rechazado de forma final por Sumsub**, no puede intentar nuevamente, a menos que:
  * Se verifique manualmente desde el BackOffice.
  * Se reinicie su proceso en el BackOffice de Sumsub.
* Cuando aplica para la plataforma y el país, el proveedor captura de forma complementaria información del dispositivo utilizado durante la verificación.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>09/07/2025</td><td>Ronald Pelaez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>10/07/2026</td><td>David Velasquez</td><td>Se agrega la captura de información del dispositivo (Device Risk) al proceso de validación con JUMIO.</td></tr></tbody></table>

</details>
