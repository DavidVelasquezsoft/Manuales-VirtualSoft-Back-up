---
description: >-
  Aquí encontrarás información importante que se debe tener en cuenta al momento
  de la creación de un bono FreeSpin para el proveedor Aviatrix.
---

# Aviatrix

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Torneos y Bonos > Bono FreeSpin

***

### 2. Visualización:

<figure><img src="../../.gitbook/assets/image (132).png" alt=""><figcaption><p>Figura#1: Captura de pantalla creación bono FreeSpin.</p></figcaption></figure>

### **3. Acciones del Usuario**

Estas son las configuraciones principales y necesarias para generar un bono FreeSpin con los juegos del proveedor **Aviatrix**, en caso de necesitar información más detallada sobre cómo crear el bono FreeSpin, puedes acceder a la siguiente página:

{% embed url="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}

<table><thead><tr><th width="140.5">Sección</th><th width="108.126220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td><p>Define la fecha de inicio y finalización en la que el bono estará disponible.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Notas:</strong> </p><ul><li>La fecha de finalización debe ser siempre posterior a la fecha de inicio. Se recomienda configurar algunos minutos de holgura en la fecha de inicio para asegurar la correcta creación y activación del bono.</li><li>El rango de fecha máximo para la vigencia de un bono con este proveedor es de 30 días.</li></ul></div></td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td><p>Selecciona el proveedor del bono, en este caso "<strong>Aviatrix</strong>".</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong>  Al seleccionar el juego correspondiente se desplegará una tabla en la que se indicará que porcentaje del bono será asumido por el proveedor <strong>Aviatrix.</strong></p></div></td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td><p>Lista los juegos disponibles del proveedor seleccionado. Se debe elegir el título específico por bono creado <a href="aviatrix.md#id-4.-validaciones-y-reglas-de-negocio"><sub>(Más información)</sub></a>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Para este proveedor solo se permite seleccionar <strong>un juego</strong> para cada bono freeSpin.</p></div></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Al seleccionar la moneda, se activarán las siguientes configuraciones.<br><a href="https://virtualsoft.gitbook.io/manuales/integraciones./manual-integraciones-por-proveedor./proveedores-con-configuraciones-para-bonos./aviatrix#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

Los bonos de&#x20;

<table><thead><tr><th width="114">Campo</th><th width="129">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Campo numérico</td><td><p>Valor que tendrá el bono por cada ronda jugada.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> </p><ul><li>El valor máximo a ingresar es de 10.000.</li></ul></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Establece la cantidad de giros gratis que tendrá este bono.</td></tr><tr><td><strong><code>Cuota mínima rollover</code></strong></td><td>Numérico</td><td>Valor mínimo de una apuesta que contará para el <a href="https://virtualsoft.gitbook.io/plantillas/glosario#rollover">rollover</a>.</td></tr><tr><td><strong><code>Cuota máxima rollover</code></strong></td><td>Numérico</td><td>límite de cuota, define hasta qué cuota una apuesta ganadora puede ayudarte a completar el <a href="https://virtualsoft.gitbook.io/plantillas/glosario#rollover">rollover</a>.</td></tr><tr><td><strong><code>Multiplicador rollover</code></strong></td><td>Numérico</td><td>Valor por el cual se multiplicará el valor por roda para establecer el valor necesario del <a href="https://virtualsoft.gitbook.io/plantillas/glosario#rollover">rollover</a>.</td></tr><tr><td><strong><code>Apuesta máxima rollover</code></strong></td><td>Numérico</td><td>límite de dinero apostado, define cuánto dinero de una apuesta como máximo puede contar para el <a href="https://virtualsoft.gitbook.io/plantillas/glosario#rollover">rollover</a>.</td></tr><tr><td><strong><code>¿Permitir usar saldo de bono?</code></strong></td><td>Selector</td><td>Permite utilizar el saldo obtenido con el bono para realizar otras apuestas</td></tr><tr><td><strong><code>¿Usar saldo de bono para rollover?</code></strong></td><td>Selector</td><td>Permite que las apuestas realizadas con el saldo del bono cuenten para el rollover </td></tr><tr><td><strong><code>Límite de ganancia</code></strong></td><td>Numérico</td><td><p>Valor máximo que podrá ganar el usuario por el bono.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si el límite de ganancia ingresado es 10 y el usuario gana 20 con este bono, solo se le asignarán 10.</p></div><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El valor máximo permitido por este proveedor es de <strong>100 USD</strong>. Si el bono supera este límite, no podrá ser entregado.</p></div></td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td><p>Permite cargar un archivo en formato CSV con los ID de los jugadores que recibirán el bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Para este proveedor, el número máximo de jugadores a los que se les puede asignar el bono es 100. Si se carga un archivo con más de 100 registros, la carga no será permitida.</p></div></td></tr></tbody></table>

<a href="https://virtualsoft.gitbook.io/manuales/integraciones./manual-integraciones-por-proveedor./proveedores-con-configuraciones-para-bonos./aviatrix#id-3.-acciones-del-usuario" class="button secondary">Regresar</a>

</details>

***

La información de este bono estará disponible en la reportería de _Productos No Deportivos_.

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos" %}
[Reporte productos no deportivos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos)
{% endcontent-ref %}

* La información sobre los movimientos realizados por el usuario con este bono estará disponible en la reportería _Historial de movimientos.(Para este proveedor, los registros se Visualizan por apuesta)_

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/historial-de-movimientos" %}
[Historial de movimientos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/historial-de-movimientos)
{% endcontent-ref %}

***

### **4. Validaciones y Reglas de Negocio**

* El bono se crea de forma inmediata, pero la asignación a jugadores puede tardar entre **2 y 3 minutos**.
* El bono solo se puede configurar para un único juego. En caso de seleccionar varios juegos simultáneamente, el sistema asignará el bono únicamente a uno de ellos de forma aleatoria.
* Este bono una vez creado quedará disponible para **CRM optimove**.
*   Al momento de asignar un bono, en la plataforma de **Usuarios Online**, el usuario visualizará un **pop-up informativo** antes de realizar la redención del bono. En este mensaje se mostrará **el valor total del bono**, y no el valor correspondiente a cada ronda individual<br>

    <div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> si se configura un bono de <strong>10 giros gratis</strong> con un <strong>valor de 10 por cada ronda</strong>, el sistema mostrará al usuario un <strong>valor total de 100</strong>, que corresponde a la suma de todas las rondas incluidas en el bono.</p></div>

***

### &#x20;**5. Control de Versiones**

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="109">Versión</th><th width="149">Fecha</th><th width="175">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>04/03/2026</td><td>David velasquez</td><td>Documento inicial </td></tr><tr><td>1.1</td><td>11/03/2026</td><td>Ronald Peláez</td><td>Refinamiento en notas.</td></tr><tr><td>1.2</td><td>03/06/2026</td><td>Karol Navia</td><td>Reestructuración del manual</td></tr><tr><td>1.3</td><td>09/09/2026</td><td>Ronald Peláez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33032">Ajustes en la configuración de Moneda.</a></td></tr></tbody></table>

</details>
