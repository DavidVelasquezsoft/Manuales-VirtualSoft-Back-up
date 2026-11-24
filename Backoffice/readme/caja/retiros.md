# Retiros

<mark style="color:$info;">Solicita retiros del saldo del punto de venta hacia sus cuentas bancarias y consulta el estado de los retiros realizados.</mark>

{% hint style="warning" %}
**Nota:** El menú **Caja** está disponible únicamente para los usuarios de tipo punto de venta.
{% endhint %}

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Caja > Retiros

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (338) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección retiros.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="retiros.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los retiros registrados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="retiros.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los retiros en la tabla de resultados.</td></tr><tr><td><a href="retiros.md#id-6.-retirar"><strong>Retirar</strong></a></td><td>Abre el formulario para solicitar un nuevo retiro.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Delimita el rango de fechas de los retiros que se consultan.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Campo numérico</td><td>Localiza un retiro por su identificador único.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Muestra los retiros según la etapa en la que se encuentran.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los retiros que cumplen con los filtros aplicados.

<table><thead><tr><th width="176">Campo</th><th width="120">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>Numérico</td><td>Muestra el identificador único del retiro.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Texto</td><td>Presenta el nombre del usuario que solicitó el retiro.</td></tr><tr><td><strong><code>Número de cuenta</code></strong></td><td>Numérico</td><td>Indica la cuenta bancaria a la que se envía el dinero del retiro.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha</td><td>Registra el momento en que se solicitó el retiro.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Numérico</td><td>Corresponde al monto solicitado, antes de descontar impuestos.</td></tr><tr><td><strong><code>Impuesto</code></strong></td><td>Numérico</td><td>Muestra el valor de impuesto aplicado al retiro.</td></tr><tr><td><strong><code>Valor final</code></strong></td><td>Numérico</td><td>Señala el monto que recibe el usuario después de descontar el impuesto.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Indica la etapa en la que se encuentra el retiro.</td></tr><tr><td><strong><code>Fecha de pago</code></strong></td><td>Fecha</td><td>Registra el momento en que se pagó el retiro.</td></tr></tbody></table>

***

### 6. Retirar

Al presionar **Retirar**, se despliega una ventana emergente con el formulario para solicitar el retiro.

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor</code></strong></td><td>Campo numérico</td><td>Define el monto que se va a retirar.</td></tr><tr><td><strong><code>Cuenta</code></strong></td><td>Lista desplegable</td><td>Selecciona la cuenta bancaria que recibe el dinero del retiro. La lista muestra las cuentas registradas en <strong>Caja &#x3E; Cuentas bancarias</strong>.</td></tr><tr><td><strong><code>Saldo a retirar</code></strong></td><td>Lista desplegable</td><td>Indica de cuál saldo del punto de venta se descuenta el retiro. Las dos opciones disponibles se describen a continuación.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
**Opciones del campo Saldo a retirar**

<table><thead><tr><th width="150">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Cupo de venta</strong></td><td>Descuenta el retiro del cupo de venta, que es el saldo con el que el punto de venta realiza sus operaciones. Habilita el campo <strong><code>¿Es para reembolso?</code></strong>.</td></tr><tr><td><strong>Comisiones</strong></td><td>Descuenta el retiro del saldo de comisiones ganadas por el punto de venta. Habilita el campo <strong><code>Cargar factura PDF</code></strong>.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>¿Es para reembolso?</code></strong></td><td>Selector</td><td><p>Indica si el retiro corresponde a un reembolso <em>(Sí o No)</em>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Se muestra solo cuando <strong><code>Saldo a retirar</code></strong> es <strong>Cupo de venta</strong>.</p></div></td></tr><tr><td><strong><code>Cargar factura PDF</code></strong></td><td>Carga de archivo</td><td><p>Adjunta la factura que respalda el cobro de las comisiones.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Se muestra solo cuando <strong><code>Saldo a retirar</code></strong> es <strong>Comisiones</strong>.</p></div></td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* El campo **`¿Es para reembolso?`** se habilita solo con la opción **Cupo de venta**.
* El campo **`Cargar factura PDF`** se habilita solo con la opción **Comisiones**.
* La lista **`Cuenta`** muestra únicamente las cuentas registradas en **Caja > Cuentas bancarias**.
* Al retiro se le descuenta el impuesto. **`Valor final`** corresponde al monto que recibe el usuario.
* **Exportar** descarga únicamente los resultados mostrados tras aplicar los filtros.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>23/01/2026</td><td>David Velasquez</td><td>Actualización de formato.</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
