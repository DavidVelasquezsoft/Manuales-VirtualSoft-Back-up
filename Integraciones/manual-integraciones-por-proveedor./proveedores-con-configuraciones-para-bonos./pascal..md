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
  anchors:
    visible: true
---

# PASCAL.

<mark style="color:$info;">Aquí encontrarás información importante que se debe tener en cuenta al momento de la creación de un bono FreeSpin para PASCAL.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (95).png" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla de la sección FreeSpin.</p></figcaption></figure>

***

### 3. Formulario para creación de bonos PASCAL

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **PASCAL** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% content-ref url="https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}
[FreeSpin](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin)
{% endcontent-ref %}

<table><thead><tr><th width="140.5">Sección</th><th width="108.126220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td><p>El botón <strong>Agregar</strong> despliega una opción para configurar las fechas durante las cuales el bono estará activo. Se debe seleccionar tanto la <strong>fecha inicial</strong> como la <strong>fecha final</strong> para definir el período de vigencia del bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La fecha de inicio no puede ser superior a dos meses desde el momento de creación.</p></div></td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td>Despliega un listado solo con los proveedores que tienen el Bonus System activo. En este caso se debe visualizar y seleccionar la opción "<strong>PASCAL</strong>".</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td><p>Despliega 2 listas para seleccionar un juego dependiendo del proveedor. En este caso, es necesario volver a seleccionar el proveedor "<strong>PASCAL</strong>" para visualizar los juegos disponibles.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al configurar los campos "<strong>Proveedores</strong>" y "<strong>Productos</strong>" se desplegará una tabla en la cual se debe especificar el porcentaje del bono que asumirá el proveedor.</p></div></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Para poder dar uso a los bonos FreeSpin con el proveedor PASCAL, es necesario seleccionar la moneda del país con el que se genera el bono. Esto activará las siguientes configuraciones.<br><a href="pascal..md#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

<table><thead><tr><th width="114">Campo</th><th width="129">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Numérico</td><td><p>Monto que tendrá el bono por cada ronda jugada. Al configurar esta opción, es crucial verificar previamente el monto de apuesta permitido en los juegos seleccionados, ya que este debe coincidir exactamente con el valor ingresado en este campo.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si se ingresa un valor de 10 en el campo "<strong>Valor por ronda</strong>", pero el juego tiene una apuesta máxima permitida de 5, el bono no funcionará porque los valores no coinciden.</p></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Cantidad de rondas gratuitas que el usuario podrá jugar con este bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Se debe ingresar el ID de cada usuario que tendrá el bono activo. Este proceso requiere cargar un archivo en formato <strong>CSV</strong> con los ID correspondientes. El sistema tomará los datos del archivo y activará automáticamente el bono para los jugadores especificados.</td></tr></tbody></table>

<a href="pascal..md#id-3.-formulario-para-creacion-de-bonos-pascal" class="button secondary">Regresar</a>

</details>

Finaliza la configuración del bono guardando y aplicando las configuraciones realizadas desde el botón **`Crear Bono`**.

***

### 4. Validaciones y Reglas de Negocio

* El bono se crea de manera inmediata, pero se asigna entre **2 y 3 minutos**.
* La fecha de inicio no puede ser superior a dos meses desde el momento de creación.
* El valor ingresado en **`Valor por ronda`** debe coincidir exactamente con un monto de apuesta permitido en los juegos seleccionados; de lo contrario, el bono no funcionará.

***

### 5. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual e incorporación del control de versiones.</td></tr></tbody></table>

</details>
