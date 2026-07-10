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

# Creación bono no deposito para Penka

<mark style="color:$info;">En este manual se describe el flujo de creación de un bono no deposito dirigido a usuarios que participen de una polla</mark> <mark style="color:$info;"></mark>_<mark style="color:$info;">(Penka)</mark>_<mark style="color:$info;">. Para la configuración general de bono no deposito, consultar el manual</mark> [<mark style="color:$info;">Crear bono no deposito</mark>](./)<mark style="color:$info;">.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Torneos y Bonos > País> Bonos > Bono No Depósito.

***

### 2. Resumen del Tipo de bono

El **Bono No Depósito para Penka** permite otorgar saldo promocional como premio a los participantes ganadores de una Penka previamente. Este tipo de bono se vincula a un **Código Penka** específico y se asigna automáticamente a los jugadores que resulten ganadores una vez finalizada la competencia y procesados los resultados.

{% hint style="warning" %}
**Nota:** La penka a la que se vincula este bono es creada y gestionada por un proveedor externo. Por lo tanto, la información y configuración de la competencia dependen de dicho proveedor.
{% endhint %}

***

### 3. Visualización

<figure><img src="../../../../../.gitbook/assets/image (4).png" alt=""><figcaption><p>Figura #1: Captura de pantalla creación de Bono No Depósito.</p></figcaption></figure>

***

### 4. Campos de Configuración

Los siguientes campos son obligatorios para la creación del bono que será otorgado como premio en la Penka. Estos bonos se asignarán al ganador o a los ganadores, según la configuración definida.

Para obtener información detallada sobre la configuración y creación de un bono no deposito, consulte la sección:

{% content-ref url="./" %}
[.](./)
{% endcontent-ref %}

<table><thead><tr><th width="152">Campo</th><th width="143">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Botón</td><td><p>Despliega los campos de fecha que permiten definir el período de vigencia del bono. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Es posible configurar múltiples rangos de fechas mediante el botón <strong>“</strong><em><strong>Agregar</strong></em><strong>”</strong>, una vez se haya establecido la <strong>fecha inicial</strong> y la <strong>fecha final</strong> de cada rango.</p></div></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre que identificará el bono en la plataforma.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Numérico</td><td><p>Define el orden de asignación de bonos a los usuarios, un número mayor indica mayor prioridad.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si hay tres bonos configurados con las siguientes prioridades:</p><ul><li><strong>Bono A:</strong> 1</li><li><strong>Bono B:</strong> 2</li><li><strong>Bono C:</strong> 3</li></ul><p>El sistema dará preferencia al <strong>Bono C</strong>, ya que tiene la prioridad más alta.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Detalles adicionales del bono que se visualizará en la plataforma usuarios online.</td></tr><tr><td><strong><code>Fecha de expiración</code></strong></td><td>Selector de fecha</td><td><p>Define el plazo para redimir el bono. Si se selecciona <strong>“Días”</strong>, se debe ingresar la cantidad de días hasta su vencimiento; si se elige <strong>“Fecha”</strong>, se debe indicar la fecha exacta en que expirará. Tras cumplirse el plazo, el bono quedará inactivo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Los campos <strong><code>Días</code></strong> y <strong><code>Fecha expiración</code></strong> son dinámicos, se visualizarán según la opción tomada.</p></div></td></tr><tr><td><strong><code>¿Es para?</code></strong></td><td>Lista desplegable</td><td>Ascia el bono a una campaña específica. Para la configuración de bonos destinados a Penkas, se selecciona la opción <strong>Penka</strong>, lo que habilita los campos y configuraciones necesarias para vincular el bono a una Penka determinada.</td></tr><tr><td><strong><code>Prefijo</code></strong></td><td>Texto</td><td>Identificador adicional para diferenciar el bono de otros.</td></tr><tr><td><strong><code>Cantidad de jugadores</code></strong></td><td>Numérico</td><td>Para los bonos asociados a una <strong>Penka</strong>, este campo debe configurarse con el valor <strong>1</strong>, ya que la cantidad de ganadores y la asignación del bono son gestionadas por el proveedor.</td></tr><tr><td><strong><code>Detalle de Campaña</code></strong></td><td>Botón de selección.</td><td>En este campo puede seleccionarse cualquiera de las opciones disponibles, ya que su función es únicamente informativa. La opción elegida actúa como una etiqueta para identificar la campaña y no afecta la configuración, el comportamiento ni la entrega del bono.</td></tr><tr><td><strong><code>Código Penka</code></strong></td><td>Texto</td><td><p>Ingrese el código único de la Penka a la que se asociará el bono. Este campo se habilita automáticamente al seleccionar la opción Penka en el campo <strong><code>¿Es para?</code></strong>.</p><p>El código debe corresponder a una Penka previamente creada y es proporcionado por un proveedor externo, responsable de la creación. La asociación correcta de este código es necesaria para que el bono pueda ser asignado a los ganadores de la Penka correspondiente.</p></td></tr></tbody></table>

{% hint style="danger" %}
**Importante:**

Una vez completada la configuración de todos los campos obligatorios y validadas las reglas correspondientes, haga clic en el botón **Crear** para registrar correctamente el bono en el sistema. Si la información ingresada cumple con todas las validaciones, el bono será creado y quedará disponible para su utilización según la configuración definida.
{% endhint %}

***

### 5. Reglas y validaciones.

* El campo **Código Penka** es obligatorio, admite únicamente caracteres alfanuméricos y permite un máximo de **100 caracteres**.
* El valor ingresado en el campo **Código Penka** no debe contener espacios al inicio ni al final.
* El sistema no permite la creación de un bono cuando existe otro bono activo asociado al mismo **Código Penka**.
* Si el **Código Penka** ingresado ya se encuentra asociado a otro bono activo, el sistema muestra un mensaje de error

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="100.33331298828125">Versión</th><th width="125">Fecha</th><th width="158.66668701171875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>11/06/206</td><td>Karol Navia</td><td>Documento inicial.</td></tr></tbody></table>

</details>
