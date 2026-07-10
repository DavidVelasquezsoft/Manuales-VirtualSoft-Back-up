---
description: >-
  El módulo Depósitos permite a los usuarios agregar fondos a su cuenta mediante
  diversos métodos de pago.
---

# Depósitos

{% hint style="warning" %}
**Nota:** Para realizar un depósito se puede requerir una verificación previa o posterior.
{% endhint %}

### 1. Acceso al Módulo:

**Ruta de Acceso**: Botón **"Depósito"** ubicada en el menú superior o página inicial una vez iniciada la sesión.

***

### **2. Acciones del Usuario**

Desde este módulo el usuario podrá realizar la siguientes acciones.

<table><thead><tr><th width="267">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Depósitos saldo a su cuenta.</strong></td><td>Deposita saldo a la cuenta para poder realizar apuestas en las diferentes secciones disponibles por la plataforma.</td></tr><tr><td><strong>Elegir métodos de depósito.</strong></td><td>Elige entre los diferentes métodos de depósitos disponibles en la plataforma <em>(Tarjeta, pasarela de pago, SPEI, OXXO, Pay, STP, etc.…)</em></td></tr></tbody></table>

#### 2.1. Tipo de deposito:

Selecciona la opción de depósito que deseas utilizar.

{% tabs %}
{% tab title="2.2. Pasarela de Pago" %}
Permite elegir una [pasarela de pago](https://virtualsoft.gitbook.io/untitled/glosario#pasarela-de-pago) disponible para realizar el depósito.

**Pasos para realizar un depósito:**

{% stepper %}
{% step %}
#### Ingresa al **módulo de depósitos**

Accede a la sección **Depósitos** desde tu cuenta. Se mostrarán todas las pasarelas de pago disponibles y habilitadas para realizar el depósito.
{% endstep %}

{% step %}
#### Ingresa un monto a depositar

En el campo correspondiente, digita el monto que deseas depositar, respetando los valores mínimos y máximos permitidos por la pasarela de pago.
{% endstep %}

{% step %}
#### **Selecciona la pasarela de pago**

Ubica la pasarela de tu preferencia y haz clic en el botón **“Depositar”**.

{% hint style="warning" %}
**Nota:** En caso de que el método de **criptomonedas** esté disponible para el Partner o país, deberá seleccionar la criptomoneda habilitada en la cual desea realizar el depósito.
{% endhint %}
{% endstep %}

{% step %}
#### Completa el pago en la pasarela

El sistema redirige automáticamente a la pasarela seleccionada para completar el pago siguiendo sus instrucciones. En caso de ser un método informativo, se mostrará la forma de realizar el depósito con el proveedor, utilizando su ID de usuario.
{% endstep %}

{% step %}
#### Confirmación del depósito

Una vez finalizada la transacción, la plataforma mostrará el resultado del depósito.

* Si el pago es exitoso, el saldo se acreditará en tu cuenta.
* Si ocurre un error, se mostrará un mensaje indicando el motivo.
{% endstep %}

{% step %}
#### **Verificación del saldo**

Puedes verificar el saldo acreditado en tu cuenta desde el panel principal o en el historial de transacciones.
{% endstep %}
{% endstepper %}
{% endtab %}

{% tab title="2.3. Tarjeta de Crédito" %}
{% hint style="warning" %}
**Nota:** El sistema solo permite agregar tarjetas cuando la operación (_Partner y país_) tiene un proveedor activo desde [BackOffice](/broken/spaces/UadX6RX6l8fMhEZxOqcT/pages/P6ejQH7j6cNHXnY74jAZ). De lo contrario, el botón **"Añadir tarjeta"** no se mostrará.
{% endhint %}

#### 2.3.1. Añadir tarjeta

Al seleccionar este método de deposito el sistema mostrará los siguientes campos para añadir una tarjeta de crédito.

<table><thead><tr><th width="190">Campo</th><th width="160.66668701171875">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Número de tarjeta</code></strong></td><td>Numérico</td><td>Ingresa el número de la tarjeta con la que se realizará el depósito.</td></tr><tr><td><strong><code>Titular</code></strong></td><td>Texto</td><td>Muestra el nombre del usuario. (<em>Este debe coincidir con tu nombre en la paltaforma por lo cual no es editable</em>)</td></tr><tr><td><strong><code>Fecha de expiración</code></strong></td><td>Selector de fecha</td><td>Selecciona la fecha de caducidad de la tarjeta.</td></tr><tr><td><strong><code>CVV</code></strong></td><td>Numérico</td><td>Ingresa el código de seguridad de la tarjeta.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Numérico</td><td>Establece el monto a depositar.</td></tr></tbody></table>

Una vez completado el formulario, presiona el botón **“Depositar”** para validar la tarjeta.

#### 2.3.2. Resultados de la validación

* **✅Si la validación es exitosa**, se mostrará un mensaje de confirmación con los siguientes datos:

<table><thead><tr><th width="192">Campos</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Monto depositado</code></strong></td><td>Valor del dinero ingresado por el usuario en la transacción de depósito.</td></tr><tr><td><strong><code>Método</code></strong></td><td>Medio de pago utilizado para realizar el depósito (<em>tarjeta, transferencia, billetera, efectivo, entre otros</em>).</td></tr><tr><td><strong><code>Tienda / Entidad procesadora</code></strong></td><td>Plataforma, tienda o entidad financiera que procesó el depósito.</td></tr><tr><td><strong><code>ID de transacción</code></strong></td><td>Identificador único asignado a la operación de depósito para fines de trazabilidad.</td></tr><tr><td><strong><code>Fecha y hora</code></strong></td><td>Fecha y hora exacta en la que se registró el depósito en el sistema.</td></tr><tr><td><strong><code>Monto actual en la cuenta</code></strong></td><td>Saldo disponible del usuario en su cuenta después de aplicar el depósito.</td></tr></tbody></table>

* **❌Si la validación falla**, aparecerá un mensaje de error indicando que la tarjeta no pudo ser registrada.

#### 2.3.3. Validaciones y funcionamiento del sistema

* El sistema mostrará únicamente las tarjetas que estén habilitadas según la configuración del **país y proveedor**, pueden ser:
  * Tarjetas asignadas automáticamente por un proveedor.
  * Tarjetas asignadas manualmente desde BackOffice.
  * Tarjetas agregadas por el usuario, **solo cuando el proveedor lo permita**.
* La disponibilidad del botón **“Agregar tarjeta”** depende del proveedor configurado:
  * Si el proveedor **no permite el registro de tarjetas por parte del usuario**, el botón **no se visualizará**.
  * En proveedores con asignación desde BackOffice (_por ejemplo, Stradacarte_), las tarjetas se asignan automáticamente y el usuario no puede agregar nuevas tarjetas.

#### 2.3.4. **Depósitos posteriores**

Para realizar nuevos depósitos, solo debes:

1. Seleccionar una tarjeta disponible.
2. Ingresar el monto.
3. Presionar **“Depositar”**.

{% hint style="warning" %}
**Nota:** Las tarjetas pueden **ocultarse automáticamente** si:

* El proveedor asociado es deshabilitado.
* La configuración del partner o país no permite el uso de tarjetas.

En estos casos, el sistema mostrará únicamente las tarjetas que ya estén asociadas y sean válidas según la configuración activa.
{% endhint %}
{% endtab %}

{% tab title="2.4. Transferencia bancaria" %}
Permite realizar un depósito mediante una transferencia bancaria.

{% hint style="warning" %}
**Nota:** Este tipo de deposito únicamente esta disponible para los partners **Camanbet**, **Ganaplay** y **Paniplay**.
{% endhint %}

**Pasos para realizar un depósito:**

{% stepper %}
{% step %}
#### Ingresa al **módulo de depósitos**

Accede a la sección **Depósitos** desde tu cuenta. Se mostrarán los diferentes metodos de pago disponibles y habilitados para realizar el depósito.
{% endstep %}

{% step %}
#### Realizar transferencia bancaria

Se mostrarán los datos del banco destino y el número de cuenta al cual debe realizar el depósito. Ingrese a su entidad bancaria y complete la transferencia con la información proporcionada.

{% hint style="warning" %}
**Nota:** Guarde o capture el comprobante de la transacción para su posterior validación.
{% endhint %}
{% endstep %}

{% step %}
#### Ingrese los datos de la transferencia bancaria

Ingrese la siguiente información de la transferencia bancaria:

<table><thead><tr><th width="147.5555419921875">Campo</th><th width="111.40740966796875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Monto</code></strong></td><td>Numérico</td><td>Ingresa valor del depósito previamente realizado mediante transferencia bancaria.</td></tr><tr><td><strong><code>Número de referencia</code></strong></td><td>Texto</td><td>Registra el número de referencia generado por la entidad bancaria para identificar la transacción realizada.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha</td><td>Registrar la fecha en la que se efectuó la transferencia bancaria.</td></tr><tr><td><strong><code>Comprobante de pago</code></strong></td><td>Archivo</td><td>Adjunta el soporte del depósito realizado, como evidencia de la transferencia bancaria. (<em>imagen o documento</em>).</td></tr></tbody></table>

Una vez finalizados todos los campos presiona el botón "**Continuar**" para generar la solicitud de depósito.
{% endstep %}

{% step %}
#### Confirmación del depósito

Posteriormente, se mostrará el resumen de la transacción, la cual quedará en estado de revisión mientras se valida la transferencia bancaria.

Una vez Validada la solicitud de depósito, se presentarán los siguientes escenarios:

* **Pago exitoso:** el saldo se acreditará en su cuenta.
* **Error en la transacción:** se mostrará un mensaje indicando el motivo.
{% endstep %}

{% step %}
#### **Verificación del saldo**

Puedes verificar el saldo acreditado en tu cuenta desde el panel principal o en el historial de transacciones.
{% endstep %}
{% endstepper %}
{% endtab %}
{% endtabs %}

{% hint style="warning" %}
**Nota:** Si la solicitud de depósito se genera correctamente, el sistema mostrará un mensaje de confirmación y la transacción quedará en estado pendiente de aprobación. En caso de que no se genere correctamente, se mostrará un mensaje de error indicando el motivo.
{% endhint %}

***

### 3. Validaciones y Reglas de Negocio

* El monto mínimo de depósito puede variar según el método _(ejemplo: $100 MXN para tarjeta, $200 MXN en OXXO)._
* Algunos métodos generan una referencia de pago con tiempo limitado de vigencia.
* No se permiten depósitos realizados desde cuentas de terceros.
* El sistema puede aplicar bonos automáticamente si se cumplen las condiciones.
* Los fondos pueden acreditarse en tiempo real o tras validar un comprobante, según el método utilizado.

***

### 4. Flujos relacionados

* Los depósitos realizados se visualizarán en la siguiente reportería

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/reporte-de-deposito" %}
[Reporte de depósito](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/reporte-de-deposito)
{% endcontent-ref %}

* ¿Cómo gestionar solicitudes de depósitos desde el BackOffice?

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/financiero/solicitudes-de-deposito" %}
[Solicitudes de depósito](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/financiero/solicitudes-de-deposito)
{% endcontent-ref %}

***

### 5. Control de Versiones

<details>

<summary>Control de versiones</summary>

| Versión      | Fecha      | Autor           | Cambios Realizados                                             |
| ------------ | ---------- | --------------- | -------------------------------------------------------------- |
| **1.0**      | 17/07/2025 | Karol Navia     | Sección de depósitos documentada                               |
| **2.0**      | 29/09/2025 | David Velásquez | Reestructuración del módulo                                    |
| &#x32;**.1** | 06/11/2025 | Ronald Peláez   | Refinamiento del manual                                        |
| 2.2          | 24/11/2025 | Karol Navia     | Agregar deposito con tarjetas                                  |
| 2.3          | 16/12/2025 | David velasquez | Incorporación de tarjeta de credito.                           |
| 2.4          | 18/12/2025 | Ronald Peláez   | Nota de tarjetas de crédito y débito.                          |
| 2.5          | 01/04/2026 | David Velasquez | Incorporación de notas, y sección de transferencias bancarias. |

</details>
