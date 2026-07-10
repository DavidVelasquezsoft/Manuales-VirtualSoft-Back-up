---
description: >-
  Permite a los usuarios solicitar retiros desde su cuenta y consultar el
  historial de transacciones realizadas.
---

# Retirar

### 1. Acceso al Módulo

**Rutas de Acceso**:

1. Usuarios Online > Menú > Servicios > Gestión > Retirar.
2. Usuarios Online > Saldo del usuario > Retirar.

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (166) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Retirar.</p></figcaption></figure>

***

### **3. ¿Qué es una nota de retiro?**

Una **nota de retiro** es el comprobante digital que se genera cuando un usuario solicita retirar fondos de su cuenta.\
Registra la información principal del retiro: monto, tipo de método, fecha, estado y destino del pago.\
Cada nota tiene un ciclo de vida con diferentes **estados**, que reflejan su avance o resolución.

#### **3.1. Relación entre saldos**

La plataforma gestiona dos tipos de saldo:

<table><thead><tr><th width="185.199951171875">Tipo de saldo</th><th>Descripción</th><th>Permite retiros</th></tr></thead><tbody><tr><td><strong>Saldo Depósitos</strong></td><td>Monto total de dinero recargado por el usuario mediante depósitos o transacciones directas.</td><td>❌ No se puede retirar directamente.</td></tr><tr><td><strong>Saldo Retiros</strong></td><td>Fondos disponibles para solicitar retiros, generalmente provenientes de ganancias.</td><td>✅ Sí, solo se puede retirar desde este saldo.</td></tr></tbody></table>

> **Importante:** Solo se puede retirar desde **saldo retiros**.\
> Cuando se crea una nota, el sistema **descuenta automáticamente** el monto del saldo retiros.\
> Si la nota se **anula o rechaza**, el monto se **devuelve al mismo saldo** (saldo retiros).

***

### **4**. Retirar

Al ingresar se presentan dos opciones principales:

{% tabs %}
{% tab title="4.1. 💸 Solicitar retiro" %}
{% hint style="warning" %}
**Nota**: Para poder realizar un retiro, es necesario tener saldo disponible en **Saldo retiro.**
{% endhint %}

{% stepper %}
{% step %}
### Información

Se muestra información importante y términos de uso que deben ser aceptados obligatoriamente para proceder con la operación.

{% hint style="warning" %}
**Nota**: En el partner **Camanbet**, este paso difiere del flujo estándar. En lugar de visualizar la información del retiro, se presenta la selección de la moneda con la que se realizará la operación (VES o USD).
{% endhint %}
{% endstep %}

{% step %}
### Tipo de Retiro

Permite elegir y crear una opción para hacer el retiro (_ej. Criptomonedas, tarjeta, etc.…)_ e ingresar el monto a retirar.

<details>

<summary>Retiro cuenta bancaria</summary>

<table><thead><tr><th width="129.09088134765625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Agregar cuenta bancaria</code></strong></td><td><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Estas configuraciones aplican para la <strong>nueva visual</strong>.</p></div><p>Para agregar una cuenta bancaria, ubica el botón <strong>“+”</strong>.<br>Al seleccionarlo, se mostrará una ventana emergente (<em>pop-up</em>) con los siguientes campos:</p><p>Los campos de este formulario pueden modificarse desde el Site Builder, desde el apartado <a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/apariencia/formularios"><strong>Formularios.</strong></a></p></td></tr><tr><td><strong><code>Retirar</code></strong></td><td><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong><br>Esta configuración aplica únicamente cuando se utiliza la <strong>visual antigua</strong> del sistema, pueden variar según las configuraciones establecidas, desde el <a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/apariencia/formularios">sitebuilder</a>.</p></div></td></tr></tbody></table>

<table><thead><tr><th width="149.09088134765625">Campo</th><th width="120.20001220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cuenta bancaria</code></strong></td><td>Lista desplegable</td><td>Selecciona la cuenta bancaria desde la cual se realizará el retiro.</td></tr><tr><td><strong><code>Cantidad</code></strong></td><td>Campo numérico</td><td>Permite ingresar el monto a retirar. El valor debe ser mayor a 50.</td></tr><tr><td><strong><code>Retirar</code></strong></td><td>Botón</td><td>Al dar clic se ejecuta la solicitud de retiro y se muestra un mensaje de confirmación.</td></tr></tbody></table>

<table><thead><tr><th width="136">Campo</th><th width="146">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre de usuario</code></strong></td><td>Campo de texto (no editable)</td><td>Muestra el nombre del usuario.</td></tr><tr><td><strong><code>Banco</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el banco asociado a la cuenta bancaria.</td></tr><tr><td><strong><code>Confirmar banco</code></strong></td><td>Lista desplegable</td><td>Se debe volver a seleccionar el banco para confirmar que la información es correcta.</td></tr><tr><td><strong><code>Tipo de cuenta</code></strong></td><td>Lista desplegable</td><td>Define el tipo de cuenta bancaria <em>(Ejemplo: Ahorros)</em>.</td></tr><tr><td><strong><code>Tipo de cliente</code></strong></td><td>Campo de texto (no editable)</td><td>Indica el tipo de cliente registrado.</td></tr><tr><td><strong><code>Número de cuenta</code></strong></td><td>Numérico</td><td>Permite ingresar el número de cuenta bancaria.</td></tr><tr><td><strong><code>Confirmar número de cuenta</code></strong></td><td>Numérico</td><td>Se debe volver a ingresar el número de cuenta para validarlo y evitar errores.</td></tr></tbody></table>

</details>

<details>

<summary>Retiro a tarjeta crédito</summary>

{% hint style="warning" %}
**Notas:**

* El retiro con tarjeta aplica solo para usuarios **verificados** y cuya tarjeta esté **registrada y activa** en la plataforma. En el caso de tarjetas gestionadas por Stradacarte, la tarjeta debe estar **activa también en ese servicio**.
* Este tipo de retiro y las opciones de retiro pueden variar según la regulación y los proveedores disponibles en cada operación (_Partner y país_).
{% endhint %}

Al seleccionar **Tarjeta de crédito** como tipo de retiro:

* Se mostrará el listado de tarjetas **activas** asociadas al usuario, incluyendo:
  * Tarjetas asignadas automáticamente por un **proveedor autorizado**.
  * Tarjetas asignadas manualmente desde **Backoffice** (_por ejemplo, Stradacarte_).
* Selecciona la tarjeta e indica el monto a retirar.
* Confirma el retiro para que sea procesado.
*   **Esperar aprobación:**

    <table><thead><tr><th width="167.5">Estado del retiro</th><th>Descripción</th></tr></thead><tbody><tr><td>✅ <strong>Aprobado</strong></td><td>el dinero será enviado a tu tarjeta correctamente.</td></tr><tr><td>❌ <strong>Rechazado</strong></td><td>el monto se devolverá automáticamente a tu saldo y recibirás una notificación.</td></tr></tbody></table>

</details>

<details>

<summary>Retiro a Yape</summary>

{% hint style="warning" %}
**Nota:** Este método de retiro solo estará disponible en Doradobet Peru.
{% endhint %}

Permite realizar un retiro directamente a una cuenta de **Yape** completando los campos del formulario.

<table><thead><tr><th width="101">Campo</th><th width="124">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Retiro a Yape</code></strong></td><td>Numérico</td><td><p>Muestra el número de teléfono que el usuario tiene registrado en la plataforma <strong>Usuarios Online</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong></p><p>Este campo es únicamente informativo y no es editable desde esta sección. Para modificar el número, debe actualizarse previamente en el módulo <a href="https://virtualsoft.gitbook.io/manuales/usuarios/usuarios-online/manual-de-plataforma/gestion/mi-cuenta."><strong>Mi cuenta</strong></a>.</p><p>El número registrado debe coincidir con el número asociado a la cuenta de Yape</p></div></td></tr><tr><td><strong><code>Valor</code></strong></td><td>Numérico</td><td>Monto por el cual se generará la solicitud de retiro.</td></tr></tbody></table>

</details>

<details>

<summary>Retiro con Criptomonedas</summary>

Al seleccionar **Criptomonedas** como tipo de retiro:

* El campo “**Cuenta bancaria**” se reemplaza por **Wallet registrada**.
* Se muestra una lista con las wallets activas del jugador en el siguiente formato:

📌 Si no hay [wallets](https://virtualsoft.gitbook.io/untitled/glosario#wallet-cripto) activas:

> “No tienes wallets activas registradas para realizar retiros. Agrega una desde tu perfil.”

**Campos mostrados al jugador**

<table><thead><tr><th width="160.1666259765625">Campo</th><th width="104.1666259765625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Monto a retirar</code></strong></td><td>Numérico</td><td>Valor en moneda local (ej: PEN)</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** La conversión a cripto se calcula en el momento del pago, no se muestra en pantalla.
{% endhint %}

</details>

<details>

<summary>Retiro a tarjeta <em>(Débito)</em></summary>

Gestiona el retiro del saldo disponible en **“Saldo Retiro”** hacia una tarjeta débito registrada en la cuenta del jugador.

**Elementos del módulo**

* Botón **“`Registrar nueva tarjeta`”**
* Listado de tarjetas registradas _(si existen)_
* Selección de tarjeta para realizar el retiro
* Opción para eliminar tarjeta

Las tarjetas se muestran en formato enmascarado, dejando visibles únicamente los últimos cuatro dígitos:

`**** **** **** 1234`

Si no existen tarjetas registradas, se visualizará únicamente el botón **“`Registrar nueva tarjeta`”**.

**Acciones disponibles en módulo**

<table><thead><tr><th width="142">Acción</th><th width="428">Descripción</th></tr></thead><tbody><tr><td><strong>Agregar una nueva tarjeta</strong></td><td>Abre un pop-up con el formulario para registrar una nueva tarjeta débito. Una vez creada, podrá utilizarse como medio de retiro.</td></tr><tr><td><strong>Utilizar tarjeta previamente creada</strong></td><td>Selecciona una tarjeta registrada. Al seleccionarla, se habilita el campo <strong>“<code>Valor</code>”</strong>, donde se debe indicar el monto a retirar.</td></tr><tr><td><strong>Eliminar tarjeta</strong></td><td><p>Al posicionar el cursor sobre la tarjeta registrada, se habilita el ícono de eliminación <em>(🗑️)</em>, el cual permite eliminar la tarjeta del listado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>:</p><ul><li>Antes de eliminar la tarjeta se desplegará un pop-up para confirmar la eliminación de la tarjeta.</li><li>Si se intenta eliminar una tarjeta con algún retiro asociado en estado <strong>Activo</strong> o <strong>Pendiente</strong>, no se permitirá su eliminación.</li></ul></div></td></tr></tbody></table>

**Formulario para crear una tarjeta**

Desde el pop-up, se presenta un formulario junto a una vista previa de la tarjeta. A medida que se diligencian los campos, la información ingresada se refleja dinámicamente en la tarjeta de ejemplo.

{% hint style="warning" %}
**Nota**:

* Cuando la tarjeta ya está creada, en el listado de tarjetas se visualizará en formato enmascarado, permitiendo visualizar solo los últimos cuatro números de la tarjeta
* Debajo del formulario están las condiciones y los tiempos de gestión para los retiros por medio de la tarjeta que se está creando.
{% endhint %}

<table><thead><tr><th width="142">Campo</th><th width="104">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del titular</code></strong></td><td>Texto</td><td>Nombre completo del titular de la tarjeta, tal como aparece impreso en la misma.</td></tr><tr><td><strong><code>Número de la tarjeta</code></strong></td><td>Numérico</td><td><p>Número completo de la tarjeta débito.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Si el número no es válido, no se habilitará el botón "<strong><code>Agregar tarjeta</code></strong>"</p></div></td></tr><tr><td><strong><code>Mes de vencimiento</code></strong></td><td>Numérico</td><td>Mes de expiración de la tarjeta <em>(formato MM).</em></td></tr><tr><td><strong><code>Año vencimiento</code></strong></td><td>Numérico</td><td>Año de expiración de la tarjeta <em>(formato AA o AAAA, según configuración).</em></td></tr><tr><td><strong><code>Código de seguridad CVC</code></strong></td><td>Numérico</td><td>Código de verificación de la tarjeta <em>(CVC/CVV)</em>, ubicado generalmente en la parte posterior.</td></tr></tbody></table>

Una vez guardada correctamente, la tarjeta quedará asociada a la cuenta y se mostrará en el listado en formato enmascarado.

</details>

<details>

<summary>Retiro Red Kasnet</summary>

Al seleccionar **Retiro Red Kasnet** como tipo de retiro:

* Se mostrará un listado con las **cuentas activas** registradas.
* Selecciona la cuenta y indica el monto a retirar.
* Confirma el retiro para que sea procesado.
*   **Esperar aprobación:**

    <table><thead><tr><th width="167.5">Estado del retiro</th><th>Descripción</th></tr></thead><tbody><tr><td>✅ <strong>Aprobado</strong></td><td>el dinero será enviado a tu cuenta correctamente.</td></tr><tr><td>❌ <strong>Rechazado</strong></td><td>el monto se devolverá automáticamente a tu saldo y recibirás una notificación.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** solo aplica para usuarios **verificados** en la plataforma y tengan la cuenta registrada y activa en la plataforma.
{% endhint %}

#### **¿No tienes cuentas registradas?**

Al no tener cuentas registradas se mostrará un mensaje de ayuda con la opción de agregar una cuenta o punto retiro.

</details>

<details>

<summary>Pago Móvil</summary>

Al seleccionar este método de retiro, se desplegará un pop-up con la información registrada de la cuenta de Pago Móvil, incluyendo el número de celular y el documento del titular.

{% hint style="warning" %}
**Nota**: El retiro solo podrá procesarse cuando los datos registrados en la cuenta del usuario coincidan con los datos de la cuenta de Pago Móvil.
{% endhint %}

#### **Acciones disponibles en el pop-up**

<table><thead><tr><th width="180">Botón</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Actualizar los datos</code></strong></td><td>Abre el chat para realizar el proceso de actualización de los datos de Pago Móvil.</td></tr><tr><td><strong><code>Continuar</code></strong></td><td>Confirma la información mostrada y permite continuar con el proceso de retiro.</td></tr></tbody></table>

#### Ingreso del monto

Ingresa el valor que se desea retirar mediante Pago Móvil.

#### Confirmación de la operación

Se mostrará un resumen con la información de la solicitud de retiro.

Verifica que los datos sean correctos y selecciona **Retirar** para generar la solicitud.

</details>

{% hint style="warning" %}
**Nota:** El botón "**Retirar**" se habilitará únicamente después de seleccionar el tipo de retiro deseado.
{% endhint %}
{% endstep %}

{% step %}
### ¿Estás seguro de que quieres realizar tu retiro?

Para procesar tu retiro exitosamente, verifica que todos tus datos estén completos y sean correctos, esto evitará demoras innecesarias.

Haz clic en "**Crear Retiro**" para continuar.

{% hint style="warning" %}
**Nota:** Al crear el retiro, el sistema **descuenta** automáticamente el saldo de la cuenta del usuario y la solicitud pasa a estado "**pendiente**" para su verificación.
{% endhint %}
{% endstep %}

{% step %}
### Detalles

Una vez validada toda la información, la solicitud de retiro se **envia** exitosamente. Podrás consultar los detalles completos de la transacción incluyendo ID, monto, fecha y hora de procesamiento, etc...

Desde esta sección también tienes la opción de [**cancelar el retiro**](retirar.md#id-4.-anulacion-de-retiros) si es necesario, y acceder al historial de retiros para monitorear el estado de todas tus solicitudes.
{% endstep %}
{% endstepper %}
{% endtab %}

{% tab title="4.2. 📖 Consultar histórico" %}
Desde el botón **Consultar histórico**, el jugador accede al registro de sus retiros.

Permite:

* Filtrar por fecha y estado
* Acceder a juegos desde esta sección
* Visualizar información clave de cada nota de retiro
* [Anular la solicitud de retiro.](retirar.md#id-4.-anulacion-de-retiros)

**Retiros cripto en historial**

* Columna **Tipo**: muestra "Criptomoneda"
* Nuevas columnas al momento del pago:

<table><thead><tr><th width="172.70367431640625">Columna nueva</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#trm">TRM</a> utilizada</td><td>Tasa de conversión aplicada según proveedor o configuración</td></tr><tr><td>Monto en cripto</td><td>Valor resultante de la conversión al momento del pago</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 5. Flujo y comportamiento de la nota de retiro

#### **5.1. Estados de una nota de retiro**

<table><thead><tr><th width="143.39996337890625">Estado</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Pendiente</code></strong></td><td>Solicitud creada; en espera de validación.</td></tr><tr><td><strong><code>Activo</code></strong></td><td>Retiro aprobado, es espera de ser pagado.</td></tr><tr><td><strong><code>Enviado</code></strong></td><td>La solicitud fue validada y enviada al proveedor de pago.</td></tr><tr><td><strong><code>Pagado</code></strong></td><td>Retiro completado exitosamente.</td></tr><tr><td><strong><code>Anulado</code></strong></td><td>El usuario canceló la nota mientras estaba pendiente; el monto se devuelve.</td></tr><tr><td><strong><code>Rechazado</code></strong></td><td>La solicitud fue rechazada por validaciones o inconsistencias; se devuelve el monto.</td></tr><tr><td><strong><code>Expirada</code></strong></td><td>La solicitud superó el tiempo máximo configurado y se marca como vencida.</td></tr></tbody></table>

> El tiempo máximo de expiración se configura desde **BackOffice → Partner Ajustes → Configuración → Solicitud de Retiro de Clientes →** [**Activar tiempo de expiración.**](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion/solicitud-de-retiro-de-clientes#id-3.1.-configuraciones)

#### **5.2. Movimiento del saldo**

<table><thead><tr><th width="177">Acción</th><th>Descripción</th><th>Efecto en el saldo</th></tr></thead><tbody><tr><td><strong><code>Crear nota</code></strong></td><td>El usuario confirma el retiro.</td><td>🔻 Se descuenta del <strong>saldo retiros</strong>.</td></tr><tr><td><strong><code>Anular retiro</code></strong></td><td>El usuario cancela la nota pendiente.</td><td>🔄 Se devuelve al <strong>saldo retiros</strong>.</td></tr><tr><td><strong><code>Rechazar retiro</code></strong></td><td>El sistema invalida la solicitud.</td><td>🔄 Se devuelve al <strong>saldo retiros</strong>.</td></tr><tr><td><strong><code>Expiración</code></strong></td><td>El retiro no se procesó en el tiempo límite.</td><td>🔄 Se devuelve al <strong>saldo retiros</strong>.</td></tr><tr><td><strong><code>Pagada</code></strong></td><td>Retiro completado correctamente.</td><td>✅ No hay devolución; operación finalizada.</td></tr></tbody></table>

#### 5.3. Flujo de anulación de un retiro

{% stepper %}
{% step %}
**Paso 1:**

El usuario anula un retiro con estado **pendiente**.
{% endstep %}

{% step %}
**Paso 2:**

Se muestra el siguiente mensaje de confirmación:

* “¿Estás seguro que deseas eliminar la nota de retiro **N° \[número de nota]**?”
{% endstep %}

{% step %}
**Paso 3:**

* **Si el usuario confirma la anulación:**
  * El estado del retiro cambia automáticamente a **“Anulado”**.
  * El sistema bloquea cualquier acción adicional sobre la nota _(no podrá ser procesada)._
  * La nota se Muestra como **anulada**.
* **Si el usuario cancela la anulación:**
  * La acción se interrumpe y el retiro permanece en estado **“**_**Pendiente**_**”**.
  * El modal de confirmación se cierra automáticamente y la nota sigue vigente.
  * El sistema continúa con el proceso de retiro y el pago se ejecuta normalmente, de acuerdo con el método seleccionado.
{% endstep %}
{% endstepper %}

***

### 6. Retiro por medio de Wallet _(Criptomonedas)_

Esta modalidad permite a los jugadores realizar retiros a través de **wallets digitales** o **redes de criptomonedas**.\
El sistema valida la disponibilidad de fondos, la información de la wallet y las condiciones configuradas por el operador antes de procesar la solicitud.

#### 6.1. Validaciones al confirmar solicitud de retiro por medio de wallet

Durante la creación de una nota de retiro con este método, el sistema ejecuta las siguientes validaciones para garantizar que la solicitud sea correcta y segura:

<table><thead><tr><th width="218.6666259765625">Validación</th><th>Mensaje de error</th></tr></thead><tbody><tr><td><strong>No seleccionó</strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario#wallet-cripto"><strong>wallet</strong></a></td><td>“Ingresa todos los campos requeridos.”</td></tr><tr><td><strong>Monto vacío</strong></td><td>“Ingresa todos los campos requeridos.”</td></tr><tr><td><strong>Valor fuera de rango</strong></td><td>“Valor menor al mínimo permitido para retirar."</td></tr><tr><td><strong>Fondos insuficientes</strong></td><td>“No tienes saldo suficiente para realizar este retiro.”</td></tr></tbody></table>

#### 6.2. Datos registrados

Esta tabla muestra la fuente de información que se visualizará al realizar un retiro.

<table><thead><tr><th width="219.03704833984375">Dato</th><th>Fuente</th></tr></thead><tbody><tr><td><strong>Criptomoneda / Red</strong></td><td>Desde la <a href="https://virtualsoft.gitbook.io/untitled/glosario#wallet-cripto">wallet</a> seleccionada</td></tr><tr><td><strong>Wallet destino</strong></td><td>Seleccionada desde la lista de <a href="https://virtualsoft.gitbook.io/untitled/glosario#wallet-cripto">wallets</a></td></tr><tr><td><strong>Monto en moneda local</strong></td><td>Ingresado por el jugador</td></tr><tr><td><strong>Estado inicial</strong></td><td>Activo</td></tr><tr><td><strong>Fecha y hora</strong></td><td>Automática</td></tr></tbody></table>

#### 6.3 Control de Accesos

<table><thead><tr><th width="227">Acción</th><th>Requisito</th></tr></thead><tbody><tr><td><strong>Ver opción Criptomonedas</strong></td><td>Jugador con retiros habilitados</td></tr><tr><td><strong>Confirmar retiro</strong></td><td>Jugador logueado y activo</td></tr><tr><td><strong>Anular nota</strong></td><td>Solo si el retiro está “Activo”</td></tr></tbody></table>

***

### 7. Validaciones y Reglas de Negocio

* El botón **Retirar** se habilita solo tras seleccionar el tipo de retiro.
* Solo los **usuarios verificados** pueden realizar retiros.
* Si el tiempo máximo de procesamiento vence, el retiro pasa a estado **Expirada**, configurado desde el **BackOffice**.
* Cada retiro registra automáticamente la **fecha, hora, estado inicial y monto ingresado**.

***

### 8. Documentación relacionada

* ¿Cómo gestionar una solicitud de retiro desde Backoffice?

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/financiero/solicitudes-de-retiro" %}
[Solicitudes de Retiro](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/financiero/solicitudes-de-retiro)
{% endcontent-ref %}

* ¿Desde donde se configuran los textos?

{% content-ref url="https://app.gitbook.com/s/Ojl0Z2z0C78jMb0KvTb8/manual-de-usuario/como-ingresar/acuerdos/lenguajes" %}
[Lenguajes](https://app.gitbook.com/s/Ojl0Z2z0C78jMb0KvTb8/manual-de-usuario/como-ingresar/acuerdos/lenguajes)
{% endcontent-ref %}

***

### 9. Control de Versiones

<details>

<summary>Control de Versiones</summary>

<table><thead><tr><th width="108.111083984375">Versión</th><th width="135.77777099609375">Fecha</th><th width="152.3333740234375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/07/2025</td><td>Ronald Pelaez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>09/09/2025</td><td>David velasquez</td><td>Mejora formato e incorporación de stradacarte.</td></tr><tr><td>1.2</td><td>15/09/2025</td><td>David velasquez</td><td>Incorporación de tipo de retiro Red Kasnet.</td></tr><tr><td>1.3</td><td>22/09/2025</td><td>Karol Navia</td><td>Incorporación de método de retiro por medio de cuentas bancarias</td></tr><tr><td>1.4</td><td>09/10/2025</td><td>Karol Navia</td><td>Agregar cuenta bancaria.</td></tr><tr><td>1.5</td><td>16/12/2025</td><td>David velasquez</td><td>Incorporación de nuevas notas de retiro por tarjeta.</td></tr><tr><td>1.6</td><td>06/05/2025</td><td>Ronald Peáez</td><td>Ajustes en los tipos de retiro</td></tr><tr><td>1.7</td><td>01/07/2026</td><td>Ronald Pelláez</td><td>Nuevo tipo de retiro "PagoMovil"</td></tr></tbody></table>

</details>
