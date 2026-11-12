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

# Creación Bono FreeBet para penka

<mark style="color:$info;">En este manual se describe el flujo de creación de un bono Freebet dirigido a usuarios que realicen una polla deportiva</mark> <mark style="color:$info;"></mark>_<mark style="color:$info;">(Penka)</mark>_<mark style="color:$info;">. Para la configuración general de bono Freebet, consultar el manual Crear bono Freebet.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: Torneos y bonos > Crear bono > País > FreeBet.

***

### 2. Resumen del Tipo de bono

El **Bono Penka Freebet** permite otorgar apuestas gratuitas en eventos deportivos como premio a los participantes ganadores de una penka previamente creada. Este bono se asocia a una penka específica y se acredita automáticamente a los jugadores que ocupen las posiciones premiadas una vez finalizada la competencia y definidos los resultados.

{% hint style="warning" %}
**Nota:** La penka a la que se vincula este bono es creada y gestionada por un proveedor externo. Por lo tanto, la información y configuración de la competencia dependen de dicho proveedor.
{% endhint %}

***

### 3. Visualización:&#x20;

<figure><img src="../../../../../.gitbook/assets/image (293).png" alt=""><figcaption><p>Figura #1: Captura de pantalla crear bono freeBet</p></figcaption></figure>

### 4. Campos de Configuración&#x20;

Los siguientes campos son obligatorios para la creación del bono que será otorgado como premio en la Penka. Estos bonos se asignarán al ganador o a los ganadores, según la configuración definida.

Para obtener información detallada sobre la configuración y creación de un bono Freebet, consulte la sección:

{% content-ref url="./" %}
[.](./)
{% endcontent-ref %}

<table><thead><tr><th width="200">Campo</th><th width="535">Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Define el período de vigencia del bono mediante la <strong>Fecha inicial</strong> y la <strong>Fecha final</strong>.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre identificador del bono.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td><p>Define el orden de asignación de bonos a los usuarios, un número mayor indica mayor prioridad.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si hay tres bonos configurados con las siguientes prioridades:</p><ul><li><strong>Bono A:</strong> 1</li><li><strong>Bono B:</strong> 2</li><li><strong>Bono C:</strong> 3</li></ul><p>El sistema dará preferencia al <strong>Bono C</strong>, ya que tiene la prioridad más alta.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Información descriptiva del bono.</td></tr><tr><td><strong><code>Fecha de expiración o Días</code></strong></td><td><p>Permite definir el período de validez del bono. La vigencia puede configurarse de dos formas:</p><ul><li><strong>Fecha:</strong> El bono expirará en una fecha y hora específicas. Al seleccionar esta opción, se habilitará el campo <strong><code>Fecha de expiración</code></strong>, donde deberá indicarse la fecha límite hasta la cual el bono podrá ser utilizado.</li><li><strong>Días:</strong> El bono expirará después de un número determinado de días. Al seleccionar esta opción, se habilitará el campo <strong><code>Días</code></strong>, donde deberá definirse la cantidad de días de vigencia del bono a partir de su acreditación al jugador.</li></ul><p>Este campo es obligatorio<strong>.</strong> Si la vigencia no es configurada, el bono no podrá ser asignado ni entregado a los ganadores de la penka.</p></td></tr><tr><td><strong><code>Es para?</code></strong></td><td><p>Define la campaña a la que estará asociado el bono. </p><div data-gb-custom-block data-tag="hint" data-style="danger" class="hint hint-danger"><p><strong>Importante:</strong><br>Para este tipo de bono debe seleccionarse la opción <strong>Penka</strong>.</p></div></td></tr><tr><td><strong><code>Prefijo</code></strong></td><td>Establezca el identificador utilizado para diferenciar los bonos relacionados.</td></tr><tr><td><strong><code>Cantidad de jugadores</code></strong></td><td>Define la cantidad de usuarios ganadores que recibirán el bono al finalizar la Penka. Por ejemplo, si se configura <strong>3</strong>, el bono será otorgado a los usuarios que ocupen los <strong>tres primeros lugares</strong> en la clasificación final.</td></tr><tr><td><strong><code>Detalle de Campaña</code></strong></td><td>Define el detalle de la campaña asociada al bono. En este campo puede seleccionarse cualquiera de las opciones disponibles, ya que su función es únicamente informativa. La opción elegida actúa como una etiqueta para identificar la campaña y no afecta la configuración, el comportamiento ni la entrega del bono.</td></tr><tr><td><strong><code>Código Penka</code></strong></td><td><p>Ingrese el código único de la Penka a la que se asociará el bono. Este campo se habilita automáticamente al seleccionar la opción Penka en el campo <strong><code>¿Es para?</code></strong>.</p><p>El código debe corresponder a una Penka previamente creada y es proporcionado por un proveedor externo, responsable de la creación. La asociación correcta de este código es necesaria para que el bono pueda ser asignado a los ganadores de la Penka correspondiente.</p></td></tr><tr><td><strong><code>El valor del bono lo enviará el proveedor</code></strong></td><td><p></p><p>Permite definir si el valor del bono será proporcionado por el proveedor al momento de la entrega. Este campo ofrece las opciones <strong>Sí</strong> y <strong>No</strong>:</p><ul><li><strong>Sí:</strong> El valor del bono será enviado por el proveedor. Al seleccionar esta opción, el campo <strong>Mínimo valor fijo</strong> permanecerá inhabilitado y no será obligatorio.</li><li><strong>No:</strong> El valor del bono será definido manualmente durante la configuración. Al seleccionar esta opción, el campo <strong>Mínimo valor fijo</strong> se habilitará para permitir el ingreso del monto correspondiente.</li></ul></td></tr><tr><td><strong><code>Tipo producto</code></strong></td><td><p>Define el segmento al que aplica el bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Para FreeBet, la única opción disponible es <strong>Sportsbook</strong>, al seleccionarla se habilitan sus configuraciones correspondientes.</p></div></td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="98">Campo</th><th width="401.34375">Descripción</th></tr></thead><tbody><tr><td><strong><code>Deporte</code></strong></td><td>Registra los deportes aplicables al bono. Al presionar <strong><code>Añadir</code></strong>, se habilita la fila en la tabla para ingresar el ID correspondiente.</td></tr><tr><td><strong><code>Mercados</code></strong></td><td>Registra los mercados permitidos. El botón <strong><code>Añadir</code></strong> habilita la fila para ingresar el identificador del mercado.</td></tr><tr><td><strong><code>Ligas</code></strong></td><td>Registra las ligas asociadas al bono. Al seleccionar <strong><code>Añadir</code></strong>, se habilita el campo en la tabla para ingresar uno o varios ID, separados por coma.</td></tr><tr><td><strong><code>Partidos</code></strong></td><td>Registra eventos específicos. El botón <strong><code>Añadir</code></strong> habilita la fila para ingresar el ID del partido correspondiente.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="200"></th><th></th></tr></thead><tbody><tr><td><strong><code>Mínimo valor Fijo</code></strong></td><td>Valor mínimo de apuesta requerido para que el bono pueda ser aplicado.</td></tr><tr><td><strong><code>Máximo Valor fijo</code></strong></td><td>Monto fijo que recibirá cada ganador en forma de Freebet. El valor configurado será acreditado individualmente a cada posición ganadora definida.</td></tr></tbody></table>

{% hint style="danger" %}
**Importante:**

Una vez completada la configuración de todos los campos obligatorios y validadas las reglas correspondientes, haga clic en el botón **Crear** para registrar correctamente el bono en el sistema. Si la información ingresada cumple con todas las validaciones, el bono será creado y quedará disponible para su utilización según la configuración definida.
{% endhint %}

***

### 5. Validaciones y reglas de negocio

* El campo **Código Penka** es obligatorio, admite únicamente caracteres alfanuméricos y permite un máximo de **100 caracteres**.
* El valor ingresado en el campo **Código Penka** no debe contener espacios al inicio ni al final.
* El sistema no permite la creación de un bono cuando existe otro bono activo asociado al mismo **Código Penka**.
* Si el **Código Penka** ingresado ya se encuentra asociado a otro bono activo, el sistema muestra un mensaje de error.
* Cuando la opción **Sí** se encuentra seleccionada en el campo **¿El valor del bono lo enviará el proveedor?**, el campo **Mínimo valor fijo** permanece inhabilitado y no es obligatorio.
* Cuando la opción **No** se encuentra seleccionada, el campo **Mínimo valor fijo** permanece habilitado y su diligenciamiento es obligatorio para completar la configuración del bono.

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="108">Versión</th><th width="133">Fecha</th><th>Autor</th><th width="271">Descripción del Cambio</th></tr></thead><tbody><tr><td>1.0</td><td>11/06/2026</td><td>Karol Navia</td><td>Documento inicial</td></tr></tbody></table>

</details>
