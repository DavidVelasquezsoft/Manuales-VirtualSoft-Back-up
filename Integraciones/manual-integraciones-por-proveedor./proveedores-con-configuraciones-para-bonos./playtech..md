---
description: >-
  Aquí encontrarás información importante que se debe tener en cuenta al momento
  de la creación de un bono FreeSpin para PLAYTECH.
---

# PLAYTECH.

### 1. Acceso al Módulo:

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (122).png" alt=""><figcaption><p>Figura#1: Captura de pantalla creación bono Free Spin.</p></figcaption></figure>

### **3. Formulario para creación de bonos** PLAYTECH

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor PLAYTECH dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% embed url="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}

<table><thead><tr><th width="140.5">Sección</th><th width="108.126220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td><p>Define la fecha de inicio y finalización en la que el bono estará disponible.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Notas:</strong> </p><ul><li>La fecha de finalización debe ser siempre posterior a la fecha de inicio. Se recomienda configurar algunos minutos de holgura en la fecha de inicio para asegurar la correcta creación y activación del bono.</li><li>El rango de fecha máximo para la vigencia de un bono con este proveedor es de 30 días.</li></ul></div></td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td><p>Selecciona el proveedor del bono, en este caso "<strong>PLAYTECH</strong>".</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al seleccionar el juego correspondiente se desplegará una tabla en la que se indicará que porcentaje del bono será asumido por el proveedor PLAYTECH<strong>.</strong></p></div></td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td>Selecciona el juego <em>(producto)</em> para el cual aplicará el bono.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Al seleccionar la moneda, se activarán las siguientes configuraciones.<br><a href="playtech..md#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

<table><thead><tr><th width="114">Campo</th><th width="129">Tipo de control</th><th width="437.2569580078125">Descripción</th></tr></thead><tbody><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Establece la cantidad de giros gratis que tendrá este bono.</td></tr><tr><td><strong><code>Código de plantilla</code></strong></td><td>Numérico</td><td><p>Ingrese el código de plantilla proporcionado por el equipo de CRM. </p><p></p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Este código se genera automáticamente al crear una campaña de bonos en el BackOffice del proveedor PLAYTECH y funciona como el identificador único de la plantilla dentro de la plataforma.</p><p>Durante la creación de la campaña, el equipo de CRM también configura el <strong>valor por ronda del bono</strong>, el cual queda asociado a este código de plantilla. Por lo tanto, para realizar esta configuración es indispensable contar con el código suministrado por CRM.</p></div></td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Permite cargar un archivo en formato CSV con los ID de los jugadores que recibirán el bono.</td></tr></tbody></table>

<a href="playtech..md#id-3.-formulario-para-creacion-de-bonos-playtech" class="button secondary">Regresar</a>

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
* El **Código de plantilla** debe existir y encontrarse configurado previamente en el BackOffice del proveedor **PLAYTECH**. Si el código no existe o es inválido, el bono no podrá ser creado.
* El rango máximo de vigencia permitido para un bono de este proveedor es de **30 días**.
* Cada Free Spin consumido por el jugador generará un registro independiente en el **Historial de movimientos**.

***

### &#x20;**5. Control de Versiones**

<details>

<summary>🔽Historial de versiones.</summary>

<table><thead><tr><th width="102.4814453125">Versión</th><th width="123">Fecha</th><th width="124.2220458984375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>13/06/2026</td><td>Karol Navia</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-32244">Reestructuración del manual conforme a la plantilla.</a></td></tr></tbody></table>

</details>
