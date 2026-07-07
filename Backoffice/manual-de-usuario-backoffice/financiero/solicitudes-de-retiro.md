---
description: >-
  El módulo Solicitudes de Retiro permite consultar, aprobar y procesar pagos de
  retiros, incluyendo retiros en criptomonedas con flujo manual o automático
  según configuración.
---

# Solicitudes de Retiro

### 1. Acceso al Módulo

**Ruta de navegación**:  BackOffice > Financiero > Solicitudes de Retiro

***

### 2. Visualización del Reporte

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption><p>Imagen #1 Captura de pantalla reporte solicitud de retiros</p></figcaption></figure>

### &#x20;3. Acciones del Usuario

<table><thead><tr><th width="237.76654052734375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Consultar</strong></td><td>Ejecuta la búsqueda y muestra los resultados según los filtros seleccionados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Reestablece los filtros por defecto.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/financiero/solicitudes-de-retiro#id-5.-columnas-del-reporte"><strong>Consultar solicitudes de retiro</strong></a></td><td>Filtrar y visualizar retiros aplicando múltiples criterios de búsqueda.</td></tr><tr><td><strong>Aprobar o rechazar solicitudes</strong></td><td>Usar los íconos ✔ y ✖ ubicados en la tabla del reporte para cambiar el estado del retiro.</td></tr><tr><td><strong>Aprobar o rechazar solicitudes masivas</strong></td><td>Despliega un pop-up en el que se debe cargar un archivo .CSV que contenga los</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/financiero/solicitudes-de-retiro#id-6.-flujo-de-retiros-en-criptomonedas"><strong>Generar QR para criptomonedas</strong></a></td><td>Crear un código QR para retiros en criptomonedas y confirmar el pago manual.</td></tr><tr><td><strong>Exportar información</strong></td><td>Descargar los datos del reporte en el formato disponible.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/financiero/solicitudes-de-retiro#ver-detalles-avanzados-lupa"><strong>Visualizar detalles avanzados</strong></a></td><td>Permite visualizar el detalle de cada registro, incluyendo sus movimientos y los usuarios que han interactuado con este, accediendo mediante el ícono de lupa 🔎.</td></tr></tbody></table>

***

### 4. Filtros de Búsqueda

<table><thead><tr><th width="148.5">Filtro</th><th width="150.83331298828125">Tipo</th><th width="443.666748046875">Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fecha</td><td>Filtra por fecha de creación del retiro.</td></tr><tr><td><strong><code>ID Cliente</code></strong></td><td>Numérico</td><td>Identificador único del cliente.</td></tr><tr><td><strong><code>ID Retiro</code></strong></td><td>Numérico</td><td>Identificador único del retiro.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra por estado del retiro (<em>Activo, Pendiente, Pagado, Rechazado, etc.</em>).</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Texto</td><td>IP registrada en la creación del retiro.</td></tr><tr><td><strong><code>Por fecha de retiro pagado</code></strong></td><td>Checkbox</td><td>Filtra usando la fecha de pago.</td></tr><tr><td><strong><code>Formas de Pago</code></strong></td><td>Lista desplegable</td><td>Filtra por forma de pago (<em>Todos, Efectivo, Cuenta Bancaria, Giro Bancario o Criptomonedas</em>).</td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Lista desplegable</td><td>Filtra por el punto de venta asociado.</td></tr><tr><td><strong><code>Método de pago</code></strong></td><td>Lista desplegable</td><td>Método de Pago (<em>Todos, Pagado físicamente o Pagado por sistema</em>).</td></tr><tr><td><strong><code>Valor Mínimo</code></strong></td><td>Numérico</td><td>Filtra retiros con valor mínimo establecido.</td></tr><tr><td><strong><code>Valor Máximo</code></strong></td><td>Numérico</td><td>Filtra retiros con valor máximo establecido.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País del usuario que realizó la transacción.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Botón opción</td><td>Muestra resultados en modo Detallado o Totales.</td></tr><tr><td><strong><code>Categorización</code></strong></td><td>Lista desplegable</td><td>Clasificación del retiro según la configuración del sistema</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>proveedor de pagos que procesará la transacción (<em>por ejemplo: PayU, Transferencia Bancaria</em>).</td></tr><tr><td><strong><code>Canal de pago</code></strong></td><td>Campo de texto</td><td><strong>canal específico de pago</strong> utilizado (<em>por ejemplo: web, cajero físico</em>)</td></tr><tr><td><strong><code>ID Sistema</code></strong></td><td>Numérico</td><td>Identificador interno del sistema.</td></tr><tr><td><strong><code>Banco</code></strong></td><td>Lista desplegable</td><td>Banco asociado al retiro.</td></tr><tr><td><strong><code>Nivel de Riesgo</code></strong></td><td>Lista desplegable</td><td><p>Filtra según nivel de riesgo asignado al retiro en la configuración del sistema.<br>los cuales son:</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El nivel de riesgo se configura desde el módulo <a data-mention href="https://app.gitbook.com/s/Ojl0Z2z0C78jMb0KvTb8/manual-de-usuario/como-ingresar/configuracion/configuracion-de-seon">Configuración de SEON</a> de <strong>Site Builder</strong>.</p></div></td></tr></tbody></table>

{% columns %}
{% column width="41.66666666666667%" %}

{% endcolumn %}

{% column width="58.33333333333333%" %}
<table><thead><tr><th width="125">Nivel de riesgo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>No clasificado</code></strong></td><td>Corresponde a retiros asociados a usuarios que no cuentan con un score de riesgo asignado. .</td></tr><tr><td><strong><code>Bajo</code></strong></td><td>Retiros asociados a usuarios con comportamiento normal dentro de la plataforma. </td></tr><tr><td><strong><code>Medio</code></strong></td><td>Retiros que presentan alertas o comportamientos irregulares. </td></tr><tr><td><strong><code>Alto</code></strong></td><td>Retiros asociados a usuarios con comportamientos sospechosos o inconsistencias relevantes. </td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="149">Filtro</th><th width="151.5">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha Modificado</code></strong></td><td>Fecha</td><td>Permite filtrar los registros según la última fecha de modificación.</td></tr><tr><td><strong><code>ID Gestor</code></strong></td><td>Numérico</td><td>Identificador del usuario gestor responsable de la solicitud.</td></tr><tr><td><strong><code>Fecha de Eliminación</code></strong></td><td>Rango de fecha</td><td>Permite filtrar las solicitudes según la fecha y hora en que fueron eliminadas del sistema.</td></tr><tr><td><strong><code>Fecha de Pago</code></strong></td><td>Rango de fecha</td><td>Permite filtrar las solicitudes según la fecha y hora en que se completó el pago.</td></tr></tbody></table>

***

### 5. Columnas del reporte

<table><thead><tr><th width="179.8333740234375">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><code>🔎</code></td><td>Permite visualizar información detallada de los usuarios y de los movimientos asociados al retiro. <br><a href="solicitudes-de-retiro.md#ver-detalles-avanzados-lupa" class="button secondary">Ver detalles</a></td></tr><tr><td><strong><code>StateId</code></strong></td><td>Estado interno de la solicitud.</td></tr><tr><td>✔ / ✖</td><td>Aprueba o rechaza la solicitud. Al aprobar, el estado pasa a Pendiente.</td></tr><tr><td><code>💳</code></td><td>Botón de acciones de formas de pago:</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="151">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Pagar por Sistema</code></strong></td><td>Ejecuta el pago del retiro mediante integraciones automáticas con el sistema o proveedor de pagos, registrando la transacción y actualizando el estado del retiro.</td></tr><tr><td><strong><code>Pagar Físicamente</code></strong></td><td>Permite gestionar el pago manual del retiro fuera del sistema, incluyendo la generación de un código QR para pagos con criptomonedas cuando aplique.</td></tr><tr><td><strong><code>Rechazar nota de retiro</code></strong></td><td>Rechaza la solicitud de retiro, registrando la acción y evitando que el proceso de pago continúe.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Cancela la solicitud de retiro antes de su procesamiento, deteniendo cualquier acción asociada y actualizando su estado.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="191.53338623046875">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>RiskStatus</code></strong></td><td>Estado de riesgo asociado al usuario.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha y hora de creación del retiro.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td><p>Indica el nombre del proveedor con el cual se realizo el retiro.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Aplica únicamente para retiros realizados mediante cuenta bancaria a través de un proveedor de pasarela de pago. El proveedor se visualizará únicamente cuando el retiro haya sido procesado, aprobado y pagado.</p></div></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual (<em>Activo, Pendiente, Pagado, Rechazado</em>).</td></tr><tr><td><strong><code>Fecha Pagado</code></strong></td><td>Fecha de confirmación de pago.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto bruto del retiro.</td></tr><tr><td><strong><code>Impuesto / Impuesto 2</code></strong></td><td>Descuentos aplicados por impuestos.</td></tr><tr><td><strong><code>Valor final</code></strong></td><td>Valor neto después de impuestos.</td></tr><tr><td><strong><code>Id</code></strong></td><td>Identificador único del retiro.</td></tr><tr><td><strong><code>External Id</code></strong></td><td>Identificador del proveedor externo.</td></tr><tr><td><strong><code>ID Cliente</code></strong></td><td>Identificador único del cliente.</td></tr><tr><td><strong><code>Forma de pago</code></strong></td><td>Canal de pago (<em>Bancaria, Criptomonedas, etc.</em>).</td></tr><tr><td><strong><code>Método de pago</code></strong></td><td>Forma en la que se realizó el pago (<em>Todos</em>, <em>Pagado físicamente</em> o <em>Pagado por sistema</em>.)</td></tr><tr><td><strong><code>Canal de pago</code></strong></td><td>Canal usado para procesar el pago.</td></tr><tr><td><strong><code>Tipo de cuenta</code></strong></td><td>Tipo de cuenta por la que se solicitó el retiro.</td></tr><tr><td><strong><code>Cuenta Bancaria</code></strong></td><td>Muestra el nombre de la cuenta utilizada para solicitar el retiro.</td></tr><tr><td><strong><code>Sucursal bancaria</code></strong></td><td>Sucursal asociada al banco.</td></tr><tr><td><strong><code>Código Interbancario</code></strong></td><td>Código de transacción interbancaria (<em>si aplica</em>).</td></tr><tr><td><strong><code>DNI</code></strong></td><td>Indica si el usuario cuenta con DNI, EJ (<em>S</em>).</td></tr><tr><td><strong><code>Tipo Documento</code></strong></td><td>Muestra el tipo del documento del usuario ej:(<em>DNI</em>).</td></tr><tr><td><strong><code>Cédula</code></strong></td><td>Numero de la cedula del usuario.</td></tr><tr><td><strong><code>Nombre Cliente</code></strong></td><td>Nombre completo del usuario.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Correo electrónico registrado por el usuario.</td></tr><tr><td><strong><code>Celular</code></strong> </td><td>Numero de celular del usuario.</td></tr><tr><td><strong><code>Dirección</code></strong></td><td>Muestra la dirección registrada por el usuario en su perfil.</td></tr><tr><td><strong><code>Departamento / Ciudad</code></strong></td><td>Ubicación del usuario.</td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Nombre del punto de venta asociado.</td></tr><tr><td><strong><code>IP</code></strong></td><td>Dirección IP registrada.</td></tr><tr><td><strong><code>Fecha Cambio</code></strong> </td><td>Fecha en que se registraron las modificaciones.</td></tr><tr><td><strong><code>IP de Cambio</code></strong></td><td>Muestra la IP desde la cual se realizaron los cambios en la solicitud.</td></tr><tr><td><strong><code>Fecha Acción</code></strong></td><td>Indica la fecha en que se ejecutó una operación sobre la solicitud, como aprobar, rechazar etc.</td></tr><tr><td><strong><code>IP Acción</code></strong></td><td>Muestra la dirección IP desde la cual se realizó la operación sobre la solicitud.</td></tr><tr><td><strong><code>Id Sistema</code></strong></td><td>Identificador interno del sistema.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de transacción.</td></tr><tr><td><strong><code>TRM utilizada</code></strong></td><td>Tasa de cambio usada en retiros.</td></tr><tr><td><strong><code>Monto en cripto</code></strong></td><td>Valor convertido a criptomoneda.</td></tr><tr><td><strong><code>Observación</code></strong></td><td>Notas asociadas al retiro.</td></tr><tr><td><strong><code>Modificado</code></strong></td><td>Última modificación registrada.</td></tr><tr><td><strong><code>Categorización</code></strong></td><td>Clasificación del retiro según la configuración del sistema</td></tr><tr><td><strong><code>Nivel de Riesgo</code></strong></td><td>Muestra el nivel de riesgo asignado al retiro mediante un código de color: <em><mark style="color:$success;">verde=riesgo bajo</mark>, <mark style="color:$warning;">amarillo=medio</mark>, <mark style="color:$danger;">rojo=alto</mark> , <mark style="color:$info;">Gris=No clasificado</mark>.</em></td></tr></tbody></table>

<details>

<summary>🔽 Ver detalles avanzados (<em>🔎 Lupa</em>)</summary>

Presenta el historial detallado de movimientos asociados a los retiros, permitiendo identificar cada acción realizada sobre un registro.

<table><thead><tr><th width="176.3333740234375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del registro en la tabla de resultados del detalle de retiros.</td></tr><tr><td><strong><code>Modificó</code></strong></td><td>Identificador único del usuario que realizó la modificación del registro.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha y hora en la que se registró el movimiento en la tabla de resultados.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Indica el tipo de movimiento registrado (<em>creación, aprobación o rechazo</em>).</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Valor monetario asociado al movimiento de retiro registrado.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Describe de forma específica el cambio o acción realizada sobre el retiro.</td></tr></tbody></table>

</details>

***

### 6. Flujo de retiros en criptomonedas

Este flujo describe de manera general las etapas que sigue un retiro en criptomonedas dentro de la plataforma, desde su creación hasta su pago.

{% stepper %}
{% step %}
**Creación del retiro:**

&#x20;Se crea el retiro y queda en estado inicial **Activo**.
{% endstep %}

{% step %}
**Aprobación**

Mediante los íconos ✔ se aprueban o ✖ se rechazan las solicitudes. Al aprobar, el estado cambia a "_Pendiente"_.

{% hint style="warning" %}
**Nota:** Es necesario actualizar la página para que el estado se actualice correctamente y se refleje el método de aprobación.
{% endhint %}
{% endstep %}

{% step %}
**Métodos de aprobación** �&#xDCB3;**:**

Para continuar con el pago del retiro solicitado por el usuario, ubique el botón con el ícono 💳.\
Al hacer clic, se desplegará un pop-up con las siguientes opciones:

> * **Pagar por Sistema**
> * **Rechazar nota de retiro**
> * **Cancelar**
> * **Pagado físicamente**

{% tabs %}
{% tab title="Pagar por sistema" %}
### **Flujo de pago:**

{% stepper %}
{% step %}
**Haz clic en la opción Pagar Nota de Retiro.**

Se abrirá un **pop up** en pantalla solicitando que elijas una **pasarela de pago**.
{% endstep %}

{% step %}
**Selecciona la pasarela de pago de tu preferencia.**

Automáticamente aparecerá un **segundo pop up** con la advertencia: _¿Desea pagar la nota de retiro?_
{% endstep %}

{% step %}
**Revisa la advertencia y selecciona una opción:**

&#x20;• Haz clic en **Pagar nota** para continuar, el sistema procesará la solicitud de pago.\
• Haz clic en **Salir** si no deseas continuar, el proceso se cancelará.
{% endstep %}

{% step %}
**Espera la confirmación del sistema.**

El pago quedará registrado y pasará a estado **pendiente de aprobación** por parte del proveedor.
{% endstep %}
{% endstepper %}
{% endtab %}

{% tab title="Pagado físicamente" %}
* Aparecerá el botón _Generar QR_ o la opción _Cancelar_
*   Al hacer clic en _Generar QR_, se despliega un modal que contiene la siguiente información.

    <table><thead><tr><th width="250">Campo</th><th>Fuente / lógica</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#wallet-cripto">Dirección Wallet</a></td><td>dirección de la wallet asociada al retiro.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#red-blockchain">Red Blockchain</a></td><td>Configurada en la wallet seleccionada.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#criptomoneda">Criptomoneda</a></td><td>Asociada al retiro.</td></tr><tr><td>Monto en Fiat</td><td>Valor en moneda local.</td></tr><tr><td>Código QR</td><td>Dirección de la Wallet.</td></tr></tbody></table>



* **Botones:**

<table><thead><tr><th width="210">Botón </th><th>Descripcion</th></tr></thead><tbody><tr><td><strong>Confirmar Pago Manual</strong></td><td>Estado pasa a <strong>Pagado</strong>, se cierra el modal y se desactiva el botón QR.</td></tr><tr><td><strong>Cancelar</strong></td><td>Cierra modal sin cambios.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endstep %}
{% endstepper %}

### 7. Estados de las notas de retiro

<details>

<summary>🔽 Estados disponibles notas de retiro</summary>

<table><thead><tr><th width="220">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Pagar nota de retiro</code></strong></td><td>Ejecuta el pago de la solicitud. Una vez realizado, el retiro queda pendiente de aprobación por parte del proveedor.</td></tr><tr><td><strong><code>Rechazar nota de retiro</code></strong></td><td>Cambia el estado de la solicitud a <strong>Rechazado</strong>. La solicitud no podrá ser procesada nuevamente y, si el usuario desea retirar, deberá generar una nueva.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Cierra el pop-up sin realizar cambios. El estado del retiro permanece igual (ejemplo: <em>Activo</em> o <em>Pendiente</em>).</td></tr></tbody></table>

</details>

***

### 8. Validaciones y reglas de negocio

* No se puede pagar sin aprobar primero.
* Si la criptomoneda no está activa, se muestra mensaje de error.
* Los retiros **deben ser aprobados antes** de poder pagarse.
* El botón **Generar QR** solo aparece en retiros en estado Pendiente y con método “Criptomonedas”.
* El sistema valida que la criptomoneda esté activa antes de generar QR.
* En caso de error o falta de datos en QR, se muestra mensaje genérico.

***

### 9. Flujos relacionados con este módulo

* Creación de notas de retiro se realizan desde la siguiente sección [Retirar Usuarios online](https://app.gitbook.com/s/yyrHDz69FZMnpZ9NBm8u/usuarios-online/manual-de-plataforma/gestion/retirar).

***

### 10. Control de versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="105.1666259765625">Versión</th><th width="138.3333740234375">Fecha</th><th width="152.8665771484375">Autor</th><th>Descripción del cambio</th></tr></thead><tbody><tr><td>1.0</td><td>14-08-2025</td><td>Karol Navia</td><td>Ajuste completo con flujo de criptomonedas según HU.</td></tr><tr><td>1.1</td><td>22-09-2025</td><td>Karol Navia</td><td>Añadir flujo de pagado por sistema</td></tr><tr><td>1.2</td><td>24-03-2025</td><td>David Velasquez</td><td>Incorporación de nuevo campo <strong><code>Proveedor,</code></strong> flujos relacionados y detalles avanzados</td></tr><tr><td>1.3</td><td>06-04-2026</td><td>Karol Navia</td><td>Incorporación del campo <code>"Nivel de Riesgo"</code></td></tr></tbody></table>

</details>
