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

# IESGAMES.

<mark style="color:$info;">Aquí encontrarás información importante que se debe tener en cuenta al momento de la creación de un bono FreeSpin para IESGAMES.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (95).png" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla de la sección FreeSpin.</p></figcaption></figure>

***

### 3. Formulario para creación de bonos IESGAMES

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **IESGAMES** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% content-ref url="https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}
[FreeSpin](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin)
{% endcontent-ref %}

<table><thead><tr><th width="140.5">Sección</th><th width="108.126220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td>El botón <strong>Agregar</strong> despliega una opción para configurar las fechas durante las cuales el bono estará activo. Se debe seleccionar tanto la <strong>fecha inicial</strong> como la <strong>fecha final</strong> para definir el período de vigencia del bono.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td>Despliega un listado solo con los proveedores que tienen el Bonus System activo. En este caso se debe visualizar y seleccionar la opción "<strong>IESGAMES</strong>".</td></tr><tr><td><strong><code>Prefijo</code></strong></td><td>Campo de texto</td><td>Al seleccionar el proveedor IESGAMES se despliega este campo, en el cual se deben ingresar dos dígitos, ya sean números o letras. Este será el inicio del código promocional.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td><p>Despliega 2 listas para seleccionar un juego dependiendo del proveedor. En este caso, es necesario volver a seleccionar el proveedor "<strong>IESGAMES</strong>" para visualizar los juegos disponibles.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al configurar los campos "<strong>Proveedores</strong>" y "<strong>Productos</strong>" se desplegará una tabla en la cual se debe especificar el porcentaje del bono que asumirá el proveedor.</p></div></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Para poder dar uso a los bonos FreeSpin con el proveedor IESGAMES, es necesario seleccionar la moneda del país con el que se genera el bono. Esto activará las siguientes configuraciones.<br><a href="iesgames..md#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

<table><thead><tr><th width="114">Campo</th><th width="129">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Número de cartones</code></strong></td><td>Numérico</td><td><p>Cantidad de cartones gratuitos que se darán a los usuarios.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Los cartones tienen el valor de 1/S por defecto (la moneda puede variar, pero el monto se mantiene fijo).</p></div></td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Se debe ingresar el ID de cada usuario que tendrá el bono activo. Este proceso requiere cargar un archivo en formato <strong>CSV</strong> con los ID correspondientes. El sistema tomará los datos del archivo y activará automáticamente el bono para los jugadores especificados.</td></tr></tbody></table>

<a href="iesgames..md#id-3.-formulario-para-creacion-de-bonos-iesgames" class="button secondary">Regresar</a>

</details>

Finaliza la configuración del bono guardando y aplicando las configuraciones realizadas desde el botón **`Crear Bono`**.

***

### 4. Validaciones y Reglas de Negocio

* Al crear el bono, se genera una lista de códigos promocionales con la cantidad de jugadores ingresada previamente en el apartado **`Jugadores`**. Es responsabilidad de la persona que crea el bono enviar estos códigos a los usuarios.
* Los códigos promocionales inician con el **`Prefijo`** de dos dígitos configurado al seleccionar el proveedor.

***

### 5. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual e incorporación del control de versiones.</td></tr></tbody></table>

</details>
