---
description: >-
  Permite crear un bono asignado a los usuarios por los depósitos realizados en
  la plataforma, sumando saldo a sus cuentas.
---

# Bono Depósito.

### 1. Acceso al Módulo

**Ruta de Acceso**: Torneos y bonos > Crear bono > País > Bono Depósito

***

### 2. Visualización general

<figure><img src="../../../../.gitbook/assets/BONO DEPOSITO.png" alt=""><figcaption><p>Figura #1: Captura de pantalla creación de Bono Depósito.</p></figcaption></figure>

***

### **3. Acciones disponibles en el módulo**

<table><thead><tr><th width="232">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="bono-deposito..md#id-4.-configuraciones-del-bono"><strong>Configurar bono depósito</strong></a></td><td><p>Permite configurar un bono de tipo depósito mediante el formulario disponible en este módulo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Los campos que finalizan el nombre con un * son obligatorios para la creación del bono.</p></div></td></tr><tr><td><strong>Configurar términos y condiciones del bono</strong></td><td>En la parte final del formulario se encuentra el botón <strong>“</strong><em><strong>Ver términos y condiciones</strong></em><strong>”</strong>, el cual despliega un editor de texto donde se deben ingresar los términos y condiciones aplicables al bono que se va a crear.</td></tr><tr><td><strong>Crear bono</strong></td><td>Una vez completado el formulario, utilice el botón <strong>“Crear bono”</strong> para enviar la información registrada y generar el bono en el sistema.</td></tr></tbody></table>

### 4. Configuraciones del bono

<table><thead><tr><th width="128.00006103515625">Campo</th><th width="119.4444580078125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Botón</td><td><p>Despliega los campos de fecha que permiten definir el período de vigencia del bono. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Es posible configurar múltiples rangos de fechas mediante el botón <strong>“</strong><em><strong>Agregar</strong></em><strong>”</strong>, una vez se haya establecido la <strong>fecha inicial</strong> y la <strong>fecha final</strong> de cada rango.</p></div></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre que identificará el bono en la plataforma.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Numérico</td><td><p>Define el orden de asignación de bonos a los usuarios, un número mayor indica mayor prioridad. </p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si hay tres bonos configurados con las siguientes prioridades:</p><ul><li><strong>Bono A:</strong> 1</li><li><strong>Bono B:</strong> 2</li><li><strong>Bono C:</strong> 3</li></ul><p>El sistema dará preferencia al <strong>Bono C</strong>, ya que tiene la prioridad más alta. </p></div><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Todos los bonos de bienvenida pueden configurarse con la prioridad que se requiera, siempre que sea la misma para todos.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Detalles adicionales del bono que se visualizará en la plataforma usuarios online.</td></tr><tr><td><strong><code>URL Imagen principal</code></strong></td><td>URL</td><td>Link de Imagen que se mostrará al usuario al visualizar el bono.</td></tr><tr><td><strong><code>Fecha de expiración o Días</code></strong></td><td>Selector</td><td><p>Define el plazo para redimir el bono. Si se selecciona <strong>“</strong><em><strong>Días</strong></em><strong>”</strong>, se debe ingresar la cantidad de días hasta su vencimiento; si se elige <strong>“</strong><em><strong>Fecha</strong></em><strong>”</strong>, se debe indicar la fecha exacta en que expirará. Tras cumplirse el plazo, el bono quedará inactivo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Los campos <strong><code>Días</code></strong> y <strong><code>Fecha expiración</code></strong> son dinámicos, se visualizarán según la opción tomada.</p></div></td></tr><tr><td><strong><code>Fecha de expiración o Días - Bonos pendientes</code></strong></td><td>Selector</td><td>Define el plazo para que un bono en estado pendiente pase a <strong>“</strong><em><strong>Expirado</strong></em><strong>”</strong>. Si se selecciona <strong>“<code>Días</code>”</strong>, se debe ingresar la cantidad de días tras los cuales expirará; si se elige <strong>“<code>Fecha</code>”</strong>, se debe indicar la fecha exacta en que cambiará a estado expirado. Una vez cumplido el plazo, el bono pendiente se marcará automáticamente como <strong>“</strong><em><strong>Expirado</strong></em><strong>”</strong>.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selector</td><td>Define el acceso al bono <em>(público para todos los jugadores o privado solo para jugadores VIP)</em>.</td></tr><tr><td><strong><code>Abierto para todos los jugadores</code></strong></td><td>Selector</td><td>Indica si el bono aplica para todos; en caso contrario, habilita el campo "<strong><code>Cantidad de jugadores</code></strong>" para definir cuántos podrán acceder.</td></tr><tr><td><strong><code>¿Es para?</code></strong></td><td>Lista desplegable</td><td>Selecciona la sección o funcionalidad de la plataforma a la que estará orientado el bono <em>(ej:  Ruleta, sorteo, CRM, landing de registro, fidelización, Cashback,  bono de cumpleaños, referidos, Beneficios)</em>.</td></tr><tr><td><strong><code>Acción para selector de bono</code></strong></td><td>Lista desplegable</td><td>Define si el bono se asignará automáticamente al momento del registro del usuario o si no se asignará de forma automática.</td></tr><tr><td><strong><code>Tipo de Campaña</code></strong></td><td>Lista desplegable</td><td>Define el objetivo principal del bono dentro de la estrategia de campaña, según el tipo seleccionado:</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="149">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Adquisición</code></strong></td><td>Bono destinado a atraer nuevos usuarios.</td></tr><tr><td><strong><code>Retención</code></strong></td><td>Bono diseñado para mantener activos a los usuarios actuales.</td></tr><tr><td><strong><code>Reactivación</code></strong></td><td>Bono orientado a recuperar usuarios inactivos.</td></tr><tr><td><strong><code>Retención de saldo</code></strong></td><td>Bono para incentivar el uso del saldo existente y evitar retiros.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="128"></th><th width="119"></th><th></th></tr></thead><tbody><tr><td><strong><code>Detalle de Campaña</code></strong></td><td>Lista desplegable</td><td><p>Permite definir la <strong>clasificación especifica del bono</strong>, facilitando su identificación, trazabilidad y análisis desde la administración de bonos.</p><p>Este campo es <strong>obligatorio</strong> y requiere seleccionar una única categoría entre las opciones del sistema (<em>por ejemplo: Bono de registro, Referidos, CRM fidelización</em>). En caso de no seleccionarse, se mostrará un mensaje de error.</p></td></tr></tbody></table>

***

<details>

<summary>Opciones avanzadas</summary>

<table><thead><tr><th width="191.3333740234375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Código Global</code></strong></td><td>Ingresa código configurado desde el BackOffice, en el cual el bono tendrá una cantidad máxima de usuarios.</td></tr><tr><td><strong><code>Códigos Promocionales</code></strong></td><td>Ingresar código promocional configurado desde el BackOffice que se va a utilizar para guiar las campañas promocionales.</td></tr><tr><td><strong><code>¿Habilitar códigos únicos?</code></strong></td><td><p>Definir si el bono podrá ser <a href="https://open-2c.gitbook.com/url/preview/site_E7EPL/glosario/~/revisions/lyO9OIXttMrjpQGurqj2#redimir">redimido</a> mediante códigos únicos generados automáticamente por el sistema.</p><ul><li><strong>Si:</strong> Activa la redención con códigos únicos aleatorios generados por la plataforma.</li><li><strong>No:</strong> no se generarán códigos para este bono.</li></ul></td></tr></tbody></table>

</details>

***

<table data-header-hidden><thead><tr><th width="131.5">Campo</th><th width="118.33343505859375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Pasarelas de pago</code></strong></td><td>Lista desplegable</td><td>Elige una o varias pasarelas de pago las cuales el usuario debe utilizar para adquirir el bono.</td></tr><tr><td><strong><code>Puntos de venta es permitido</code></strong></td><td>Selector</td><td>Permite habilitar el uso del bono para depósitos realizados en puntos de venta. Al seleccionar esta opción, se desplegarán las siguientes configuraciones.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="169">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Regiones punto de venta</code></strong></td><td>Selecciona las regiones donde se aplicará el bono. <em>(El bono solo aplicará en la zona seleccionada)</em>.</td></tr><tr><td><strong><code>Departamentos punto de venta</code></strong></td><td>Selecciona los departamentos donde se aplicará el bono.</td></tr><tr><td><strong><code>Ciudades punto de venta</code></strong></td><td>Selecciona las ciudad donde se aplicará el bono.</td></tr><tr><td><strong><code>Puntos de venta</code></strong></td><td>Selecciona los puntos de venta donde se aplicará el bono.</td></tr><tr><td><strong><code>Puntos de venta no permitidos</code></strong></td><td>Selecciona los puntos de venta donde no se aplicará el bono.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="131.5">Campo</th><th width="118.33343505859375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Producto Rollover</code></strong></td><td>Lista desplegable</td><td><p>Permite seleccionar el tipo de producto sobre el cual se aplicará la configuración de rollover. Las opciones disponibles incluyen: Directo, Casino, Sportsbook, Live Casino y Virtual.</p><p>Las configuraciones varían según el producto seleccionado: para <strong>Casino, Live Casino y Virtual</strong> las configuraciones son similares; para <strong>Directo</strong> no se presentan cambios en la configuración; y para <strong>Sportsbook</strong> se manejan configuraciones específicas, las cuales se detallan a continuación.</p></td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<details>

<summary><strong>Configuraciones: Casino, Live Casino y Virtual</strong></summary>

<table><thead><tr><th width="130">Sección</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Selecciona la categoría general sobre la cual se aplicará la configuración. Al elegir una categoría, se define el grupo principal de productos al que aplicarán las condiciones configuradas.</td></tr><tr><td><strong><code>Proveedores</code></strong></td><td>Selecciona uno o varios proveedores asociados a la categoría elegida.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Selecciona los productos específicos sobre los cuales se aplicará la configuración. Esta selección es más detallada y depende de la categoría y proveedor previamente seleccionados.</td></tr></tbody></table>

</details>

<details>

<summary><strong>Configuraciones: Sportsbook</strong> </summary>

Las secciones **Deporte, Mercados, Ligas y Partidos** comparten la misma estructura y configuración.\
Esto significa que, independientemente de la opción seleccionada, los campos y condiciones a configurar serán los mismos, variando únicamente el nivel al que se aplican _(deporte, mercado, liga o partido)._

<table><thead><tr><th width="122.66650390625">Campo</th><th width="258.0103759765625">Descripción</th></tr></thead><tbody><tr><td><strong><code>¿Todas las condiciones son obligatorias?</code></strong></td><td>Define si las condiciones configuradas al momento de crear este bono deben cumplirse todas o no. Al seleccionar “<em><strong>Sí</strong></em>”, se revisan una a una y todas deben cumplirse para aplicar la regla. Al seleccionar “<em><strong>No</strong></em>”, cada condición se evalúa de forma independiente, por lo que basta con que alguna se cumpla.</td></tr><tr><td><strong><code>¿Se dará un bono del proveedor Altenar?</code></strong></td><td>Indica si se otorgará un bono proveniente del proveedor Altenar. Al seleccionar la opción “<em><strong>Sí</strong></em>”, se habilitan los campos <strong><code>Bono plan Id</code></strong> <em>(identificador del plan de bono definido por el proveedor)</em> y <strong><code>Código del bono</code></strong><em>(código único del bono asignado por el proveedor)</em>, los cuales son obligatorios y deben ser diligenciados con la información proporcionada por el proveedor; en caso de seleccionar “<em><strong>No</strong></em>”, no se otorgará este beneficio y dichos campos no serán requeridos.</td></tr><tr><td><strong><code>Deporte, Mercados, Ligas o Partidos</code></strong></td><td>Permite ingresar los identificadores <em>(ID)</em> de los elementos seleccionados <em>(deportes, mercados, ligas o partidos</em>) a los que se aplicará la configuración. Se pueden ingresar múltiples IDs separados por comas.</td></tr><tr><td><strong><code>Tipo de apuesta</code></strong></td><td>Permite seleccionar el tipo de apuesta al que aplicará la configuración. Las opciones disponibles son: <strong>Single</strong> <em>(apuesta simple)</em>, <strong>Multiple</strong> <em>(apuesta combinada)</em> y <strong>System</strong> <em>(apuestas de sistema).</em></td></tr><tr><td><strong><code>Tipo de evento</code></strong></td><td>Permite definir el tipo de evento al que aplicará la configuración: <strong>Both</strong> <em>(pre-match y en vivo)</em>, <strong>Pre-match</strong> <em>(antes del evento)</em> o <strong>Live</strong> (<em>en vivo)</em>.</td></tr><tr><td><strong><code>Mínima cantidad en selecciones</code></strong></td><td>Define el número mínimo de selecciones que debe tener una apuesta para que aplique la configuración.</td></tr><tr><td><strong><code>Mínima cuota en selecciones</code></strong></td><td>Define la cuota mínima que debe tener cada selección dentro de la apuesta.</td></tr><tr><td><strong><code>Mínima cuota total</code></strong></td><td>Define la cuota mínima total que debe cumplir la apuesta.</td></tr><tr><td><strong><code>Repetir Partidos</code></strong></td><td>Permite definir si se permite incluir el mismo partido más de una vez dentro de una apuesta.</td></tr><tr><td><strong><code>Repetir Mercados</code></strong></td><td>Permite definir si se permite incluir el mismo mercado más de una vez dentro de una apuesta.</td></tr></tbody></table>

</details>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="131.5">Campo</th><th width="118.33343505859375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Numero de depósitos</code></strong></td><td>Lista desplegable</td><td>Permite definir en cuál o cuáles depósitos se asignará el bono al usuario: <em>(primer depósito, Próximo depósito o depósito específico)</em>. Si se selecciona la opción <strong>“</strong><em><strong>Específico</strong></em><strong>”</strong>, se habilitará el campo <strong>“<code>Orden depósito</code>”</strong>, donde se deberá indicar el número de depósitos exactos al que se aplicará el bono.</td></tr><tr><td><strong><code>Valor del bono como máximo valor a sumar para</code> </strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#rollover"><strong><code>rollover</code></strong></a></td><td>Selector</td><td><p>Indica si el valor del bono se usará como el monto máximo a sumar al <a href="https://virtualsoft.gitbook.io/untitled/glosario/#rollover">rollover</a>.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong></p><ul><li>Depósito: <strong>$200</strong></li><li>Bono: <strong>$500</strong></li><li>Rollover: x5</li></ul><ol><li><p><strong>Si seleccionas “Sí”:</strong></p><ul><li>El sistema solo tomará el valor del bono hasta el máximo permitido, por ejemplo <strong>$300</strong>.</li><li>Cálculo → (200 + 300) × 5 = <strong>$2500</strong> en apuestas requeridas.</li></ul></li><li><p><strong>Si seleccionas “No”:</strong></p><ul><li>El sistema tomará el valor real del bono, es decir <strong>$500</strong>.</li><li>Cálculo → (200 + 500) × 5 = <strong>$3500</strong> en apuestas requeridas.</li></ul></li></ol></div></td></tr><tr><td><strong><code>¿se dará un bono con Digitain?</code></strong></td><td>Selector</td><td><p>Define si el bono estará vinculado a uno previamente creado por el proveedor <a href="https://virtualsoft.gitbook.io/untitled/glosario/#digitain">Digitain</a>. Al seleccionar la opción <strong>“</strong><em><strong>Sí</strong></em><strong>”</strong>, se habilitará el campo <strong>“<code>ID del bono en Digitain</code>”</strong>, donde deberá ingresarse el identificador correspondiente al bono proporcionado por el proveedor; si se selecciona <strong>“</strong><em><strong>No</strong></em><strong>”</strong>, dicho campo no será visible.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Notas:</strong> </p><ul><li>Este campo sólo estará visible si el proveedor está activo desde el <a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos-2/partners-proveedores.">BackOffice</a>.</li><li>Por defecto, el campo estará configurado en la opción <strong>“</strong><em><strong>No</strong></em><strong>”</strong>.</li><li>El ID del bono digitan sólo permite números al momento de crear el bono y no puede estar asociado a otro bono previamente creado.</li></ul></div></td></tr><tr><td><strong><code>Asignación de bono</code></strong></td><td>Lista desplegable</td><td><p>Permite definir si se otorgará <strong>dinero</strong> o un <strong>bono previamente creado</strong>. En caso de seleccionar la opción de bono, el usuario recibirá un bono adicional al ya configurado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> En esta sección también se puede asignar el bono creado por el proveedor Altenar.</p></div></td></tr><tr><td><strong><code>Campaña de Marketing</code></strong></td><td>Lista desplegable</td><td>Elige una o varias campañas para asignarle al bono.</td></tr><tr><td><strong><code>Saldo a asignar</code></strong></td><td>Lista desplegable</td><td> Tipo de saldo que se le otorgará al usuario al <a href="https://open-2c.gitbook.com/url/preview/site_E7EPL/glosario/~/revisions/lyO9OIXttMrjpQGurqj2#redimir">redimir</a> el bono.</td></tr><tr><td><strong><code>Cálculo de bonificación</code></strong></td><td>Selector</td><td>Define la modalidad con la que se calculará el bono por depósito. Puede configurarse como <strong>Monto fijo</strong>, otorgando un valor previamente establecido, o como <strong>Porcentaje</strong>, aplicando un % sobre el monto del depósito realizado por el usuario.</td></tr></tbody></table>

***

<details>

<summary><a href="bono-deposito..md#undefined" class="button primary">MONEDA</a></summary>

Al dar clic en la moneda correspondiente al país con el que se ingresó a la plataforma, se desplegarán las siguientes configuraciones:

<figure><img src="../../../../.gitbook/assets/image (32).png" alt=""><figcaption><p>Figura #2: Captura de pantalla configuración moneda.</p></figcaption></figure>

<table><thead><tr><th width="138.77777099609375">Campo</th><th width="125.888916015625">Tipo</th><th width="420.44439697265625">Descripción</th></tr></thead><tbody><tr><td><strong><code>Monto de bono fijo</code></strong></td><td>Numérico</td><td><p>Indica el monto que se le dará al usuario con este bono por realizar un depósito.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo solo estará disponible si en el campo "<strong><code>Calculo de bonificación</code></strong>" se selecciona "<strong>Bono Fijo</strong>"</p></div></td></tr><tr><td><strong><code>Mínimo depósito</code></strong></td><td>Numérico</td><td>Indica el valor mínimo que debe depositar el usuario para acceder al bono.</td></tr><tr><td><strong><code>Máxima apuesta tomada para rollover</code></strong></td><td>Numérico</td><td>Indicar la cantidad máxima de la apuesta para el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#rollover">rollover</a>.</td></tr><tr><td><strong><code>Cupo máximo</code></strong></td><td>Numérico</td><td>Cantidad máximas de usuarios que podrán acceder a este bono.</td></tr><tr><td><strong><code>Máximo depósito</code></strong></td><td>Numérico</td><td>Cantidad máxima en valor depositado para acceder al bono.</td></tr><tr><td><strong><code>Pago máximo</code></strong></td><td>Numérico</td><td>Establecer el monto máximo a pagar al usuario con este bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Archivo CSV</td><td>Cargar un archivo <a href="https://virtualsoft.gitbook.io/untitled/glosario#csv">CSV</a> con los ID de los usuarios que pueden acceder al bono.</td></tr></tbody></table>

</details>

***

<table data-header-hidden><thead><tr><th width="232.99993896484375">Campo</th><th width="92.9998779296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>¿Cliente puede repetir bono?</code></strong></td><td>Selector</td><td>Establecer si un mismo usuario puede redimir el bono.</td></tr><tr><td><strong><code>¿Cliente puede recibir otros bonos adicionales después del actual?</code></strong></td><td>Selector</td><td>Establecer si el usuario podrá recibir bonos adicionales al actual que se está creando.</td></tr></tbody></table>

***

### 5. Validaciones y reglas.

* Si se configura un bono de depósito de tipo **privado** y los usuarios se cargan mediante archivo **.CSV**, el bono se asignará únicamente a los usuarios incluidos en ese archivo y, aunque posteriormente realicen un nuevo depósito cumpliendo las condiciones establecidas, no recibirán un nuevo cupo, ya que este tipo de bono no permite reasignaciones una vez otorgado por carga masiva.
* El campo **`¿se dará un bono con Digitain?`** solo estará visible si el proveedor está activo desde el [BackOffice](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos-2/partners-proveedores.).
* Si alguno campos obligatorios no está configurado, el bono no se creará.
*   Una vez creado el bono, su activación y gestión se realizará en el módulo correspondiente según la opción seleccionada en el campo **“`Es para`”** (_por ejemplo: Referidos, CRM u otros_). Por lo tanto, después de crearlo, deberá configurarse y activarse desde el módulo asociado para que pueda utilizarse correctamente.

    <div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> <br>Para bonos de tipo <strong>Referidos</strong>, una vez creados y disponibles, podrán activarse y habilitarse desde el siguiente módulo de referidos: <a data-mention href="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#referidos">Configuración #🔽 Referidos</a></p></div>

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99">Versión</th><th width="152.3333740234375">Fecha</th><th width="166.666748046875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2025-08-15</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>2026-02-18</td><td>Ronald Peláez</td><td>Refinamiento de manual y ajuste en el campo <strong><code>Es para?</code></strong></td></tr><tr><td>1.2</td><td>2026-03-11</td><td>David Velasquez</td><td>Ajuste en el campo <strong><code>es para?</code></strong>  y validación.</td></tr><tr><td>1.3</td><td>2026-03-17</td><td>David Velasquez</td><td>Ajuste en campo <strong><code>detalle de campaña</code></strong>.</td></tr><tr><td>1.4</td><td>2026-03-24</td><td>Ronald Peláez</td><td>Agregar campo <strong><code>¿se dará un bono con Digitan?</code></strong></td></tr><tr><td>1.5</td><td>2026-04-2025</td><td>Karol Navia</td><td>Reestructuración del manual</td></tr></tbody></table>

</details>
