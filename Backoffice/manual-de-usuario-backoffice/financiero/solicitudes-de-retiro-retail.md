---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# Solicitudes de Retiro Retail

Este manual describe el funcionamiento del módulo **Solicitudes de Retiro Retail**, el cual permite consultar, aprobar, rechazar y pagar las solicitudes de retiro generadas desde los puntos de venta, asegurando el control y seguimiento de cada operación.

### 1. Acceso al Módulo

**Ruta de navegación**: BackOffice > Financiero > Solicitudes de Retiro Retail

***

### 2. Visualización del Reporte

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption><p>Imagen #1: Captura de pantalla del módulo Solicitudes de Retiro Retail.</p></figcaption></figure>

***

### 3. Acciones del Usuario

<table><thead><tr><th width="175">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Consultar</strong></td><td>Ejecuta la búsqueda y muestra los resultados según los filtros seleccionados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros a su estado inicial.</td></tr><tr><td><strong>Seleccionar</strong></td><td>Permite marcar una o varias solicitudes para ejecutar acciones masivas.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/financiero/solicitudes-de-retiro-retail#id-5.-columnas-del-reporte"><strong>Aprobar (✔️)</strong></a></td><td>Cambia el estado de la solicitud a aprobada, habilitando su posterior pago.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/financiero/solicitudes-de-retiro-retail#id-5.-columnas-del-reporte"><strong>Rechazar (✖️)</strong></a></td><td>Cambia el estado de la solicitud a rechazada e impide su procesamiento.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/financiero/solicitudes-de-retiro-retail#id-5.-columnas-del-reporte"><strong>Pagar (💳)</strong></a></td><td>Permite realizar el pago de la solicitud, seleccionando el método correspondiente e ingresando el número de comprobante.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/financiero/solicitudes-de-retiro-retail#id-5.-columnas-del-reporte"><strong>Visualizar detalles (🔎)</strong></a></td><td>Permite consultar el historial y la información detallada de la solicitud.</td></tr><tr><td>Rechazo masivo</td><td>Utiliza el botón <strong>“<code>Rechazo masivo</code>”</strong> para abrir una ventana emergente donde se deberá cargar un archivo .CSV con los ID de los retiros que se desean rechazar y diligenciar el motivo correspondiente en el campo <em>Descripción</em>.</td></tr></tbody></table>

***

### 4. Filtros de Búsqueda

<table><thead><tr><th width="137">Filtro</th><th width="121">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha creación</code></strong></td><td>Rango de fecha</td><td>Filtra las solicitudes según su fecha de creación.</td></tr><tr><td><strong><code>ID Cliente</code></strong></td><td>Numérico</td><td>Identificador único del cliente que generó la solicitud.</td></tr><tr><td><strong><code>ID Retiro</code></strong></td><td>Numérico</td><td>Identificador único del retiro.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra según el estado actual de la solicitud.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Texto</td><td>IP registrada al momento de generar la solicitud.</td></tr><tr><td><strong><code>Por fecha de retiro pagado</code></strong></td><td>Selector</td><td>Filtra únicamente solicitudes que ya fueron pagadas.</td></tr><tr><td><strong><code>Formas de pago</code></strong></td><td>Lista desplegable</td><td>Filtra según la forma de pago seleccionada.</td></tr><tr><td><strong><code>Punto de venta</code></strong></td><td>Lista desplegable</td><td>Filtra por el punto de venta asociado al retiro.</td></tr><tr><td><strong><code>Método de pago cuentas bancarias</code></strong></td><td>Lista desplegable</td><td>Filtra según el método de pago utilizado.</td></tr><tr><td><strong><code>Valor mínimo</code></strong></td><td>Numérico</td><td>Filtra solicitudes con un monto igual o superior al valor indicado.</td></tr><tr><td><strong><code>Valor máximo</code></strong></td><td>Numérico</td><td>Filtra solicitudes con un monto igual o inferior al valor indicado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País en el que se generó la solicitud.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Botón opción</td><td>Permite visualizar resultados en modo total o detallado.</td></tr><tr><td><strong><code>ID Sistema</code></strong></td><td>Numérico</td><td>Identificador generado por el banco para la aprobación del retiro.</td></tr><tr><td><strong><code>Banco</code></strong></td><td>Lista desplegable</td><td>Filtra por el banco seleccionado para el pago.</td></tr></tbody></table>

<details>

<summary>Filtros detallados</summary>

<table><thead><tr><th width="126">Filtro</th><th width="162">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de eliminación</code></strong></td><td>Lista desplegable</td><td>Filtra solicitudes eliminadas según su fecha.</td></tr><tr><td><strong><code>Fecha de pago</code></strong></td><td>Lista desplegable</td><td>Filtra solicitudes según la fecha en que fueron pagadas.</td></tr></tbody></table>

</details>

***

### 5. Columnas del reporte

<table><thead><tr><th width="173">Columna</th><th width="569">Descripción</th></tr></thead><tbody><tr><td><strong>🔎/</strong><img src="../../.gitbook/assets/image (4).png" alt="" data-size="line"></td><td><ul><li><img src="../../.gitbook/assets/image (4).png" alt="" data-size="line">: Permite descargar la factura del depósito en diferentes formatos.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Esta acción solo estará disponible con las solicitudes que tengan cargada la factura.</p></div><ul><li><strong>🔎:</strong> Despliega un módulo de detalles avanzados sobre la solicitud seleccionada.<br><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/financiero/solicitudes-de-retiro-retail#detalles-avanzados" class="button secondary">Detalles Avanzados</a></li></ul></td></tr><tr><td><strong><code>Seleccionar</code></strong></td><td>Permite elegir una o varias solicitudes para ejecutar acciones masivas.</td></tr><tr><td><strong><code>✔️ / ✖️</code></strong></td><td>Permite aprobar o rechazar la solicitud.</td></tr><tr><td><strong><code>💳</code></strong></td><td>Permite ejecutar el pago de la solicitud, seleccionando el método e ingresando el comprobante.</td></tr><tr><td><strong><code>Fecha Pagado</code></strong></td><td>Fecha en la que se realizó el pago.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto bruto solicitado para retiro.</td></tr><tr><td><strong><code>Impuesto</code></strong></td><td>Valor correspondiente al impuesto aplicado.</td></tr><tr><td><strong><code>Valor final</code></strong></td><td>Monto neto recibido por el usuario después de impuestos.</td></tr><tr><td><strong><code>Tipo de cuenta</code></strong></td><td>Tipo de cuenta a la que se realizó el pago.</td></tr><tr><td><strong><code>Sucursal bancaria</code></strong></td><td>Sucursal utilizada para procesar el pago.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Tipo de documento del usuario.</td></tr><tr><td><strong><code>Cédula</code></strong></td><td>Número de identificación del usuario.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Correo electrónico registrado.</td></tr><tr><td><strong><code>Celular</code></strong></td><td>Número de contacto del usuario.</td></tr><tr><td><strong><code>Dirección</code></strong></td><td>Dirección registrada en el perfil del usuario.</td></tr><tr><td><strong><code>País</code></strong></td><td>País de registro del usuario.</td></tr><tr><td><strong><code>Punto de venta</code></strong></td><td>Punto de venta asociado al retiro.</td></tr><tr><td><strong><code>Fecha cambio</code></strong></td><td>Fecha en la que se realizó la última modificación.</td></tr><tr><td><strong><code>IP de cambio</code></strong></td><td>Dirección IP desde la cual se modificó la solicitud.</td></tr><tr><td><strong><code>Observaciones</code></strong></td><td>Comentarios o notas registradas sobre la solicitud.</td></tr></tbody></table>

<details>

<summary>Detalles Avanzados.</summary>

Presenta el historial completo de movimientos asociados a la solicitud de retiro.

<table><thead><tr><th width="187">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único de la solicitud.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Estado registrado en el movimiento.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se generó o modificó la solicitud.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Valor solicitado para retiro.</td></tr><tr><td><strong><code>Nombre sistema de pago</code></strong></td><td>Método por el cual se realizará el pago.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Detalle descriptivo del movimiento realizado.</td></tr><tr><td><strong><code>Modificó</code></strong></td><td>Usuario o registro que efectuó la modificación.</td></tr></tbody></table>

</details>

***

### 6. Estados de las solicitudes

<table><thead><tr><th width="150">Estado / Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Aprobado</strong></td><td>La solicitud fue validada y puede proceder a pago.</td></tr><tr><td><strong>Rechazado</strong></td><td>La solicitud fue denegada y no podrá procesarse.</td></tr><tr><td><strong>Pagado</strong></td><td>El pago fue ejecutado correctamente y cuenta con comprobante registrado.</td></tr></tbody></table>

***

### 7. Validaciones y reglas de negocio

* No es posible pagar una solicitud sin haberla aprobado previamente.
* Para ejecutar el pago es obligatorio seleccionar el método de pago.
* El sistema exige el ingreso del número de comprobante al momento de pagar.
* Las solicitudes rechazadas no pueden volver a procesarse.
* Las acciones masivas aplican únicamente a solicitudes seleccionadas.

***

### 8. Control de versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="106">Versión</th><th width="123">Fecha</th><th width="137">Autor</th><th>Descripción del cambio</th></tr></thead><tbody><tr><td>1.0</td><td>16-04-2026</td><td>Ronald Peláez </td><td>Documento inicial</td></tr></tbody></table>

</details>
