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

# UPGAMES

<mark style="color:$info;">Aquí encontrarás información importante que se debe tener en cuenta al momento de la creación de un bono FreeSpin para el proveedor UPGAMES.</mark>

### 1. Acceso al Módulo:

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (134).png" alt=""><figcaption><p>Figura#1: Captura de pantalla creación bono Free Spin.</p></figcaption></figure>

### **3. Formulario para creación de bonos UPGAMES**

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **UPGAMES** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% embed url="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}

<table><thead><tr><th width="140.5">Sección</th><th width="108.126220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td><p>Define la fecha de inicio y finalización en la que el bono estará disponible.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Notas:</strong> </p><ul><li>La fecha de finalización debe ser siempre posterior a la fecha de inicio. Se recomienda configurar algunos minutos de holgura en la fecha de inicio para asegurar la correcta creación y activación del bono.</li><li>El rango de fecha máximo para la vigencia de un bono con este proveedor es de 30 días.</li></ul></div></td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td><p>Selecciona el proveedor del bono, en este caso "<strong>UPGAMES</strong>".</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al seleccionar el juego correspondiente se desplegará una tabla en la que se indicará que porcentaje del bono será asumido por el proveedor <strong>UPGAMES.</strong></p></div></td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td>Selecciona el juego <em>(producto)</em> para el cual aplicará el bono.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Al seleccionar la moneda, se activarán las siguientes configuraciones.<br><a href="https://virtualsoft.gitbook.io/manuales/integraciones./manual-integraciones-por-proveedor./proveedores-con-configuraciones-para-bonos./upgames#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

El FreeSpin con este proveedor funciona con un valor total asignado, que el usuario puede utilizar en varias apuestas dentro de un mismo juego, hasta agotar el monto otorgado.

<table><thead><tr><th width="114">Campo</th><th width="129">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Monto total</code></strong></td><td>Numérico</td><td>Cantidad total disponible para realizar apuestas con este bono.</td></tr><tr><td><strong><code>Apuesta Máxima</code></strong></td><td>Numérico</td><td>Valor máximo que puede utilizarse en una apuesta con este bono.</td></tr><tr><td><strong><code>Apuesta Mínima</code></strong></td><td>Numérico</td><td>Valor mínimo requerido para realizar una apuesta con este bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Permite cargar un archivo en formato CSV con los ID de los jugadores que recibirán el bono.</td></tr></tbody></table>

<a href="https://virtualsoft.gitbook.io/manuales/integraciones./manual-integraciones-por-proveedor./proveedores-con-configuraciones-para-bonos./upgames#id-3.-formulario-para-creacion-de-bonos-upgames" class="button secondary">Regresar</a>

</details>

Finaliza la configuración del bono guardando y aplicando las configuraciones realizadas desde el botón "**`Crear Bono`**".

***

* La información de este bono estará disponible en la reportería de _Productos No Deportivos_.

{% hint style="warning" %}
Nota: Si se realiza una compra de giros en la tienda del proveedor, las ganancias de estos giros se reportarán como "**Premios**" y no como "**Premios bonos**"
{% endhint %}

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos" %}
[Reporte productos no deportivos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos)
{% endcontent-ref %}

* La información sobre los movimientos realizados por el usuario con este bono estará disponible en la reportería _Historial de movimientos._

{% hint style="warning" %}
**Nota:** El historial de movimientos mostrará un registro independiente por cada jugada gratuita realizada.
{% endhint %}

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/historial-de-movimientos" %}
[Historial de movimientos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/historial-de-movimientos)
{% endcontent-ref %}

***

### **4. Validaciones y Reglas de Negocio**

* El bono se crea de forma inmediata, pero la asignación a jugadores puede tardar entre **2 y 3 minutos**.
* Este bono podrá crearse para varios juegos, pero solo podrá ser utilizado en un juego.
* Este bono una vez creado quedará disponible para **CRM optimove**.
* Si se crea un bono con un valor por ronda diferente a los permitidos en la lista de cuotas por juego, el sistema no asignará el bono a los usuarios.

***

### &#x20;**5. Control de Versiones**

<details>

<summary>🔽 Historial de versiones.</summary>

<table><thead><tr><th width="105.8148193359375">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>09/11/2026</td><td>Ronald Peláez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-32130">Documento inicial </a></td></tr></tbody></table>

</details>
