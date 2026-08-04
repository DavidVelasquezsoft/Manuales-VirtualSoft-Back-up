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

***

### 3. Tipo de deposito:

Selecciona la opción de depósito que deseas utilizar.

{% tabs %}
{% tab title="Pasarela de Pago / Franquicia" %}
Realiza un depósito seleccionando una [franquicia](https://virtualsoft.gitbook.io/untitled/glosario#franquicia) de las disponibles para tu país. Al elegir una franquicia, el sistema selecciona automáticamente la [pasarela de pago](https://virtualsoft.gitbook.io/untitled/glosario#pasarela-de-pago) adecuada para procesar tu depósito.

**Pasos para realizar un depósito:**

{% stepper %}
{% step %}
Ingresa  a la sección **Depósitos** desde tu cuenta. Se mostrarán todas las franquicias disponibles y habilitadas para realizar el depósito.
{% endstep %}

{% step %}
Ingresa un monto a depositar en el campo correspondiente, respetando los valores mínimos y máximos permitidos.
{% endstep %}

{% step %}
Selecciona la franquicia de tu preferencia y haz clic en el botón **"Depositar"**. El sistema seleccionará automáticamente la pasarela de pago que procesará la transacción, de acuerdo con el monto ingresado y el orden de prioridad configurado en la sección [Depósitos #Gestión de franquicias](https://app.gitbook.com/s/Ojl0Z2z0C78jMb0KvTb8/manual-de-usuario/como-ingresar/productos/depositos#gestion-de-franquicias "mention") del SiteBuilder para las pasarelas asociadas a la franquicia.

{% hint style="warning" %}
**Nota:** En caso de que el método de **criptomonedas** esté disponible para el Partner o país, deberás seleccionar la criptomoneda habilitada en la cual deseas realizar el depósito.
{% endhint %}
{% endstep %}

{% step %}
El sistema redirige automáticamente al usuario a la pasarela de pago seleccionada según la configuración definida en [**SiteBuilder**](https://app.gitbook.com/s/Ojl0Z2z0C78jMb0KvTb8/manual-de-usuario/como-ingresar/productos/depositos#gestion-de-franquicias), donde podrá completar el proceso siguiendo las instrucciones proporcionadas. En caso de ser un método informativo, se mostrará la forma de realizar el depósito con el proveedor, utilizando tu ID de usuario.

{% hint style="warning" %}
**Nota:** Si en ese momento la franquicia seleccionada no cuenta con ninguna pasarela de pago disponible para procesar depósitos, deberás seleccionar una franquicia diferente o comunicarte con soporte.
{% endhint %}
{% endstep %}

{% step %}
Una vez finalizada la transacción, la plataforma mostrará el resultado del depósito:

* Si el pago es exitoso, el saldo se acreditará en tu cuenta.
* Si el depósito es rechazado o presenta un error, se mostrará el motivo y será necesario seleccionar **Reintentar**. El sistema intentará procesar la transacción con otra pasarela disponible dentro de la misma franquicia. La pasarela rechazada podrá quedar temporalmente no disponible, según su configuración.
{% endstep %}

{% step %}
Posteriormente verificar el saldo acreditado en tu cuenta desde el panel principal o en el historial de transacciones.
{% endstep %}
{% endstepper %}

<details>

<summary>🔽 Funcionamiento de franquicias y pasarelas</summary>

Durante el proceso de depósito, el usuario selecciona una **franquicia** y no una pasarela de pago específica. Cada franquicia agrupa una o varias pasarelas de pago, y el sistema selecciona automáticamente la más adecuada para procesar la transacción según la configuración establecida en [Depósitos #Gestión de franquicias](https://app.gitbook.com/s/Ojl0Z2z0C78jMb0KvTb8/manual-de-usuario/como-ingresar/productos/depositos#gestion-de-franquicias "mention").

El funcionamiento de las franquicias se basa en las siguientes reglas:

* **Selección automática de la pasarela:** Al seleccionar una franquicia e ingresar el monto del depósito, el sistema determina automáticamente la pasarela de pago que procesará la transacción.
* **Orden de visualización:** Las franquicias se presentan al usuario según el orden de prioridad definido en la configuración del sistema, mostrando primero aquellas con mayor prioridad.
* **Reintento automático ante rechazo:** Si una pasarela rechaza el depósito, el sistema intentará procesar la transacción utilizando otra pasarela disponible perteneciente a la misma franquicia. Como medida de control, la pasarela que rechazó la operación podrá permanecer temporalmente inhabilitada antes de volver a estar disponible.
* **Gestión de depósitos en proceso:** Cuando existen múltiples solicitudes de depósito pendientes asociadas a una misma pasarela, el sistema puede priorizar otra pasarela disponible dentro de la misma franquicia para evitar la acumulación de transacciones en proceso.
* **Depósitos con tiempo de procesamiento prolongado:** Si una solicitud de depósito permanece en estado de procesamiento durante un tiempo superior al esperado, la plataforma mostrará un mensaje indicando al usuario que se comunique con el servicio de atención al cliente para recibir asistencia.

</details>
{% endtab %}

{% tab title="Tarjeta" %}
{% hint style="warning" %}
**Nota:** El sistema solo permite agregar tarjetas cuando la operación (_Partner y país_) tiene un proveedor activo desde [BackOffice](/broken/spaces/UadX6RX6l8fMhEZxOqcT/pages/P6ejQH7j6cNHXnY74jAZ). De lo contrario, el botón **"Añadir tarjeta"** no se mostrará.
{% endhint %}

#### Añadir tarjeta

Al seleccionar este método de deposito el sistema mostrará los siguientes campos para añadir una tarjeta de crédito.

<table><thead><tr><th width="190">Campo</th><th width="160.66668701171875">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Número de tarjeta</code></strong></td><td>Numérico</td><td>Ingresa el número de la tarjeta con la que se realizará el depósito.</td></tr><tr><td><strong><code>Titular</code></strong></td><td>Texto</td><td>Muestra el nombre del usuario. (<em>Este debe coincidir con tu nombre en la paltaforma por lo cual no es editable</em>)</td></tr><tr><td><strong><code>Fecha de expiración</code></strong></td><td>Selector de fecha</td><td>Selecciona la fecha de caducidad de la tarjeta.</td></tr><tr><td><strong><code>CVV</code></strong></td><td>Numérico</td><td>Ingresa el código de seguridad de la tarjeta.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Numérico</td><td>Establece el monto a depositar.</td></tr></tbody></table>

Una vez completado el formulario, presiona el botón **“Depositar”** para validar la tarjeta.

#### Resultados de la validación

* **✅Si la validación es exitosa**, se mostrará un mensaje de confirmación con los siguientes datos:

<table><thead><tr><th width="192">Campos</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Monto depositado</code></strong></td><td>Valor del dinero ingresado por el usuario en la transacción de depósito.</td></tr><tr><td><strong><code>Método</code></strong></td><td>Medio de pago utilizado para realizar el depósito (<em>tarjeta, transferencia, billetera, efectivo, entre otros</em>).</td></tr><tr><td><strong><code>Tienda / Entidad procesadora</code></strong></td><td>Plataforma, tienda o entidad financiera que procesó el depósito.</td></tr><tr><td><strong><code>ID de transacción</code></strong></td><td>Identificador único asignado a la operación de depósito para fines de trazabilidad.</td></tr><tr><td><strong><code>Fecha y hora</code></strong></td><td>Fecha y hora exacta en la que se registró el depósito en el sistema.</td></tr><tr><td><strong><code>Monto actual en la cuenta</code></strong></td><td>Saldo disponible del usuario en su cuenta después de aplicar el depósito.</td></tr></tbody></table>

* **❌Si la validación falla**, aparecerá un mensaje de error indicando que la tarjeta no pudo ser registrada.

#### Validaciones y funcionamiento del sistema

* El sistema mostrará únicamente las tarjetas que estén habilitadas según la configuración del **país y proveedor**, pueden ser:
  * Tarjetas asignadas automáticamente por un proveedor.
  * Tarjetas asignadas manualmente desde BackOffice.
  * Tarjetas agregadas por el usuario, **solo cuando el proveedor lo permita**.
* La disponibilidad del botón **“Agregar tarjeta”** depende del proveedor configurado:
  * Si el proveedor **no permite el registro de tarjetas por parte del usuario**, el botón **no se visualizará**.
  * En proveedores con asignación desde BackOffice (_por ejemplo, Stradacarte_), las tarjetas se asignan automáticamente y el usuario no puede agregar nuevas tarjetas.

#### **Depósitos posteriores**

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

{% tab title="Transferencia bancaria" %}
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
* El reporte del backOffice [Reporte Depósitos por franquicias](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-depositos-por-franquicias "mention") permite visualizar la información de los depósitos procesados mediante franquicias, facilitando su análisis de forma independiente.

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

<summary>🔽 Historial de versiones</summary>

| Versión      | Fecha      | Autor           | Cambios Realizados                                                                                                   |
| ------------ | ---------- | --------------- | -------------------------------------------------------------------------------------------------------------------- |
| **1.0**      | 17/07/2025 | Karol Navia     | Sección de depósitos documentada                                                                                     |
| **2.0**      | 29/09/2025 | David Velásquez | Reestructuración del módulo                                                                                          |
| &#x32;**.1** | 06/11/2025 | Ronald Peláez   | Refinamiento del manual                                                                                              |
| 2.2          | 24/11/2025 | Karol Navia     | Agregar deposito con tarjetas                                                                                        |
| 2.3          | 16/12/2025 | David velasquez | Incorporación de tarjeta de credito.                                                                                 |
| 2.4          | 18/12/2025 | Ronald Peláez   | Nota de tarjetas de crédito y débito.                                                                                |
| 2.5          | 01/04/2026 | David Velasquez | Incorporación de notas, y sección de transferencias bancarias.                                                       |
| 2.6          | 03/08/2026 | David Velasquez | [Ajustes en sección de depósito por pasarela o franquicia](https://virtualsoftlatam.atlassian.net/browse/VSFT-31464) |

</details>
