---
description: >-
  El Bono No Depósito permite a los usuarios obtener un bono sin necesidad de un
  depósito previo, aquí podrás encontrar una explicación de todos los campos
  disponibles para dicho bono.
---

# Bono no Depósito.

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Torneos y Bonos > País> Bonos > Bono No Depósito.

***

### 2. Visualización

<figure><img src="../../../../../.gitbook/assets/image (4).png" alt=""><figcaption><p>Figura #1: Captura de pantalla creación de Bono No Depósito.</p></figcaption></figure>

***

### **3. Acciones disponibles en el módulo**

<table><thead><tr><th width="232">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./bono-no-deposito."><strong>Configurar bono no depósito</strong></a></td><td><p>Permite configurar un bono de tipo depósito mediante el formulario disponible en este módulo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Los campos que finalizan el nombre con un * son obligatorios para la creación del bono.</p></div></td></tr><tr><td><strong>Configurar términos y condiciones del bono</strong></td><td>En la parte final del formulario se encuentra el botón <strong>“</strong><em><strong>Ver términos y condiciones</strong></em><strong>”</strong>, el cual despliega un editor de texto donde se deben ingresar los términos y condiciones aplicables al bono que se va a crear.</td></tr><tr><td><strong>Crear bono</strong></td><td>Una vez completado el formulario, utilice el botón <strong>“</strong><em><strong>Crear bono</strong></em><strong>”</strong> para enviar la información registrada y generar el bono en el sistema.</td></tr></tbody></table>

#### 3.1. Formulario

<table><thead><tr><th width="152">Campo</th><th width="143">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Botón</td><td><p>Despliega los campos de fecha que permiten definir el período de vigencia del bono. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Es posible configurar múltiples rangos de fechas mediante el botón <strong>“</strong><em><strong>Agregar</strong></em><strong>”</strong>, una vez se haya establecido la <strong>fecha inicial</strong> y la <strong>fecha final</strong> de cada rango.</p></div></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre que identificará el bono en la plataforma.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Numérico</td><td><p>Define el orden de asignación de bonos a los usuarios, un número mayor indica mayor prioridad.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si hay tres bonos configurados con las siguientes prioridades:</p><ul><li><strong>Bono A:</strong> 1</li><li><strong>Bono B:</strong> 2</li><li><strong>Bono C:</strong> 3</li></ul><p>El sistema dará preferencia al <strong>Bono C</strong>, ya que tiene la prioridad más alta.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Detalles adicionales del bono que se visualizará en la plataforma usuarios online.</td></tr><tr><td><strong><code>URL Imagen principal</code></strong></td><td>Texto</td><td>Link de Imagen que se mostrará al usuario al visualizar el bono.</td></tr><tr><td><strong><code>Fecha de expiración</code></strong></td><td>Selector de fecha</td><td><p>Define el plazo para redimir el bono. Si se selecciona <strong>“Días”</strong>, se debe ingresar la cantidad de días hasta su vencimiento; si se elige <strong>“Fecha”</strong>, se debe indicar la fecha exacta en que expirará. Tras cumplirse el plazo, el bono quedará inactivo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Los campos <strong><code>Días</code></strong> y <strong><code>Fecha expiración</code></strong> son dinámicos, se visualizarán según la opción tomada.</p></div></td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Determina si el bono es público (<em>todos los usuarios</em>) o privado (<em>VIP</em>).</td></tr><tr><td><strong><code>Prefijo</code></strong></td><td>Texto</td><td>Identificador adicional para diferenciar el bono de otros.</td></tr><tr><td><strong><code>Cantidad de jugadores</code></strong></td><td>Numérico</td><td>Cantidad de usuarios que tendrán acceso al bono.</td></tr><tr><td><strong><code>¿Es para?</code></strong></td><td>Lista desplegable</td><td>Selecciona la sección o funcionalidad de la plataforma a la que estará orientado el bono <em>(ej: ruleta, sorteo, CRM, landing de registro, fidelización o cashback, bono de cumpleaños, tours).</em></td></tr><tr><td><strong><code>Tipo de bono</code></strong></td><td>Lista desplegable</td><td>Define si el bono se asignará automáticamente al momento del registro del usuario o si no se asignará de forma automática.</td></tr><tr><td><strong><code>¿Se dará un bono del proveedor</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#altenar"><strong><code>Altenar</code></strong></a><strong><code>?</code></strong></td><td>Botón de selección.</td><td>Al activar esta opción se podrán crear bonos asociados a Altenar, habilitando los campos:</td></tr></tbody></table>

{% columns %}
{% column width="41.66666666666667%" %}

{% endcolumn %}

{% column width="58.33333333333333%" %}
<table><thead><tr><th width="111">Campo</th><th width="97">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Bono plan Id</code></strong></td><td>Texto</td><td>Identificador único del bono altenar relacionado.</td></tr><tr><td><strong><code>Código del bono</code></strong></td><td>Texto</td><td>Código del bono altenar relacionado.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="156"></th><th width="140"></th><th></th></tr></thead><tbody><tr><td><strong><code>Eliminación por retiro?</code></strong></td><td>Selector</td><td>El bono se eliminará del usuario al generar una nota de retiro en su cuenta.</td></tr><tr><td><strong><code>Tipo de campaña</code></strong></td><td>Lista desplegable</td><td>Define el objetivo principal del bono dentro de la estrategia de campaña, según el tipo seleccionado:</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="149">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Adquisición</code></strong></td><td>Bono destinado a atraer nuevos usuarios.</td></tr><tr><td><strong><code>Retención</code></strong></td><td>Bono diseñado para mantener activos a los usuarios actuales.</td></tr><tr><td><strong><code>Reactivación</code></strong></td><td>Bono orientado a recuperar usuarios inactivos.</td></tr><tr><td><strong><code>Retención de saldo</code></strong></td><td>Bono para incentivar el uso del saldo existente y evitar retiros.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="128"></th><th width="119"></th><th></th></tr></thead><tbody><tr><td><strong><code>Detalle de Campaña</code></strong></td><td>Lista desplegable</td><td><p>Permite definir la <strong>clasificación especifica del bono</strong>, facilitando su identificación, trazabilidad y análisis desde la administración de bonos.</p><p>Este campo es <strong>obligatorio</strong> y requiere seleccionar una única categoría entre las opciones del sistema (<em>por ejemplo: Bono de registro, Referidos, CRM fidelización</em>). En caso de no seleccionarse, se mostrará un mensaje de error.</p></td></tr><tr><td><strong><code>¿se dará un bono con Digitain?</code></strong></td><td>Selector</td><td><p>Define si el bono estará vinculado a uno previamente creado por el proveedor <a href="https://virtualsoft.gitbook.io/untitled/glosario/#digitain">Digitain</a>. Al seleccionar la opción <strong>“</strong><em><strong>Sí</strong></em><strong>”</strong>, se habilitará el campo <strong>“<code>ID del bono en Digitain</code>”</strong>, donde deberá ingresarse el identificador correspondiente al bono proporcionado por el proveedor; si se selecciona <strong>“</strong><em><strong>No</strong></em><strong>”</strong>, dicho campo no será visible.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Notas:</strong> </p><ul><li>Este campo solo estará visible si el proveedor está activo desde el <a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos-2/partners-proveedores.">BackOffice</a>.</li><li>Por defecto, el campo estará configurado en la opción <strong>“No”</strong>.</li><li>El ID del bono digitan solo permite números al momento de crear el bono y no puede estar asociado a otro bono previamente creado.</li></ul></div></td></tr></tbody></table>

***

<details>

<summary><strong>3.2. Opciones avanzadas</strong></summary>

<table><thead><tr><th width="271">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Permisos</code></strong></td><td>Define si el código global es obligatorio.</td></tr><tr><td><strong><code>Código Global</code></strong></td><td>Código configurado en BackOffice que limita la cantidad máxima de usuarios.</td></tr><tr><td><strong><code>Códigos Promocionales</code></strong></td><td>Código promocional configurado en BackOffice para campañas específicas.</td></tr><tr><td><strong><code>¿Habilitar códigos únicos?</code></strong></td><td>Establece si se habilita la redención por medio de códigos únicos en el bono.</td></tr></tbody></table>

</details>

***

#### 3.3. Configuraciones de tipo de producto

<table><thead><tr><th width="184">Campo</th><th width="144">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Producto Rollover</code></strong></td><td>Lista desplegable</td><td>Define en qué producto se deben realizar las apuestas para liberar el bono <em>(Casino, Sportsbook, etc.).</em></td></tr><tr><td><strong><code>Todas las condiciones son obligatorias</code></strong></td><td>Botón de selección</td><td>Indica si todas las condiciones configuradas previamente deben cumplirse para acceder al bono.</td></tr><tr><td><strong><code>Valor del bono como máximo valor a sumar para rollover</code></strong></td><td>Botón de selección</td><td>Determina si el valor del bono se utilizará como el monto máximo a contabilizar en el cálculo del rollover.</td></tr></tbody></table>

***

#### 3.4. Configuraciones adicionales

<table><thead><tr><th width="185">Campo</th><th width="143">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Asignación de bono</code></strong></td><td>Lista desplegable</td><td>Permite elegir entre otorgar dinero directo o un bono previamente creado.</td></tr><tr><td><strong><code>Campaña de marketing</code></strong></td><td>Sección</td><td>Configura notificaciones que llegarán al inbox de la plataforma.</td></tr><tr><td><strong><code>Saldo a asignar</code></strong></td><td>Lista desplegable</td><td>Define el tipo de saldo que recibirá el usuario al <a href="https://virtualsoft.gitbook.io/untitled/glosario/?q=redimir#redimir">redimir </a>el bono.</td></tr></tbody></table>

***

#### 3.5. Configuraciones de moneda

<details>

<summary>Moneda</summary>

<table><thead><tr><th width="142">Campo</th><th width="119">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Monto de Bono Fijo</code></strong></td><td>Numérico</td><td>Establece el valor fijo del bono que recibirá el usuario.</td></tr><tr><td><strong><code>Máxima apuesta tomada para rollover</code></strong></td><td>Numérico</td><td>Define el valor máximo de la apuesta que será considerado para el rollover.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón</td><td>Permite cargar un archivo CSV con los ID de los usuarios que podrán acceder al bono.</td></tr></tbody></table>

</details>

***

#### 3.6. Otras configuraciones

<table><thead><tr><th width="169">Campo</th><th width="144">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cliente puede repetir bono</code></strong></td><td>Botón de selección</td><td>Indica si el usuario puede redimir varias veces el mismo bono.</td></tr><tr><td><strong><code>Programa de fidelización</code></strong></td><td>Botón de selección</td><td>Permite indicar si el bono pertenece a un esquema de fidelización.</td></tr><tr><td><strong><code>Cliente puede recibir otros bonos</code></strong></td><td>Botón de selección</td><td>Indica si el bono es compatible con otros bonos adicionales.</td></tr><tr><td><strong><code>Crear Bono</code></strong></td><td>Botón</td><td>Guarda las configuraciones y genera el bono.</td></tr></tbody></table>

***

### 4. Validaciones y Reglas de Negocio

* Si algún campo obligatorio no está configurado, el bono no se creará.
* El campo **`¿se dará un bono con Digitain?`** solo estará visible si el proveedor está activo desde el [BackOffice](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos-2/partners-proveedores.).
*   Una vez creado el bono, su activación y gestión se realizará en el módulo correspondiente según la opción seleccionada en el campo **“`Es para`”** (_por ejemplo: Referidos, CRM u otros_). Por lo tanto, después de crearlo, deberá configurarse y activarse desde el módulo asociado para que pueda utilizarse correctamente.

    <div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> <br>Para bonos de tipo <strong>Referidos</strong>, una vez creados y disponibles, podrán activarse y habilitarse desde el siguiente módulo de referidos: <a data-mention href="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#referidos">Configuración #🔽 Referidos</a></p></div>

***

### 5. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="107">Versión</th><th width="130">Fecha</th><th width="156.3333740234375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>29/08/2025</td><td>Karol Navia</td><td>Documento inicial. Adaptación a nueva plantilla.</td></tr><tr><td>1.1</td><td>19/02/2026</td><td>Ronald Peláez</td><td>Refinamiento de manual y ajustes en el campo <strong><code>es para?</code></strong> .</td></tr><tr><td>1.2</td><td>11/03/2026</td><td>David Velasquez</td><td>Ajuste en el campo <strong><code>es para?</code></strong> y validación.</td></tr><tr><td>1.3</td><td>17/03/2026</td><td>David velasquez</td><td>Ajuste en campo <strong><code>detalle de campaña</code></strong>.</td></tr><tr><td>1.4</td><td>24/03/2026</td><td>Ronald Peláez</td><td>Agregar campo <strong><code>¿se dará un bono con Digitain?</code></strong></td></tr><tr><td>1.5</td><td>16/07/2026</td><td>Karol Navia</td><td>Agregar la opción (<em>tours)</em> en el campo <strong><code>Es para?</code></strong></td></tr></tbody></table>

</details>
