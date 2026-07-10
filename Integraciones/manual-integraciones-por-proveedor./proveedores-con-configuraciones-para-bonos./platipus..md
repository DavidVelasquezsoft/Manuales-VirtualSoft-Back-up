---
description: >-
  Aquí encontrarás información importante que se debe tener en cuenta al momento
  de la creación de un bono FreeSpin para PLATIPUS.
---

# PLATIPUS.

### 1. Acceso al Módulo:

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización:

<figure><img src="../../.gitbook/assets/platipus.png" alt=""><figcaption><p>Figura#1: Captura de pantalla creación bono Free Spin.</p></figcaption></figure>

### **3. Formulario para creación de bonos** PLATIPUS

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **PLATIPUS** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% embed url="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}

<table><thead><tr><th width="127.90740966796875">Sección</th><th width="108.126220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td><p>Define la fecha de inicio y finalización en la que el bono estará disponible.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Notas:</strong> </p><ul><li>La fecha de finalización debe ser siempre posterior a la fecha de inicio. Se recomienda configurar algunos minutos de holgura en la fecha de inicio para asegurar la correcta creación y activación del bono.</li></ul></div></td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td><p>Selecciona el proveedor del bono, en este caso "<strong>PLATIPUS</strong>".</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al seleccionar el juego correspondiente se desplegará una tabla en la que se indicará que porcentaje del bono será asumido por el proveedor <strong>PLATIPUS.</strong></p></div></td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td><p>Selecciona uno o múltiples juegos a los cuales aplicará el bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Los giros gratis solo podrán utilizarse en uno de los juegos seleccionados, a elección del usuario. Una vez se utilice el primer giro en un juego, la totalidad de los giros quedará asociada a ese juego y no podrá utilizarse en los demás.</p></div><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si el bono tiene <strong>6 giros</strong> y se seleccionan varios juegos, el usuario podrá elegir cualquiera de ellos para utilizarlos. Sin embargo, al realizar el primer giro en un juego, los <strong>6 giros</strong> quedarán disponibles únicamente para ese juego hasta ser consumidos.</p></div></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Al seleccionar la moneda, se activarán las siguientes configuraciones.<br><a href="platipus..md#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

<table><thead><tr><th width="112.5185546875">Campo</th><th width="126.0369873046875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Campo numérico</td><td><p>Defina el <strong>valor base</strong> que desea asignar a cada ronda del juego. Para calcularlo, <strong>divida entre 5</strong> el <strong>valor final</strong> que desea otorgar al jugador, ya que el proveedor multiplica automáticamente el monto configurado por las <strong>5</strong> líneas del juego.</p><div data-gb-custom-block data-tag="hint" data-style="danger" class="hint hint-danger"><p><strong>Nota:</strong> El valor final que recibirá el jugador, es decir, el resultado obtenido después de <strong>multiplicar por 5</strong> el <strong>valor base</strong> configurado en <strong>este campo.</strong> El <strong>valor base</strong> configurado debe corresponder a uno de los valores permitidos por el juego seleccionado. Si el valor ingresado no coincide con un valor válido del juego, el bono no podrá ser asignado.</p></div><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si desea entregar <strong>10</strong> al usuario por ronda, debe ingresar un <strong>valor base de 2</strong> en este campo, ya que el proveedor multiplicará automáticamente ese valor por las <strong>5</strong> líneas del juego <strong>(2 × 5 = 10)</strong>. Ese <strong>valor base de 2</strong> debe estar entre los valores disponibles permitidos por el juego.</p></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Establece la cantidad de giros gratis que tendrá este bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td><p>Permite cargar un archivo en formato <a href="https://virtualsoft.gitbook.io/plantillas/glosario#csv">CSV</a> con los IDs de los jugadores que recibirán el bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El archivo debe contener únicamente una columna con los IDs de los jugadores. Si el archivo incluye columnas adicionales o un formato diferente, será rechazado.</p></div></td></tr></tbody></table>

<a href="platipus..md#id-3.-formulario-para-creacion-de-bonos-skywind" class="button secondary">Regresar</a>

</details>

Finaliza la configuración del bono guardando y aplicando las configuraciones realizadas desde el botón "**`Crear Bono`**".

***

* La información de este bono estará disponible en la reportería de _Productos No Deportivos_.

{% hint style="warning" %}
**Nota:** Si se realiza una compra de giros en la tienda del proveedor, las ganancias de estos giros se reportarán como "**Premios**" y no como "**Premios bonos**"
{% endhint %}

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos" %}
[Reporte productos no deportivos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos)
{% endcontent-ref %}

* La información sobre los movimientos realizados por el usuario con este bono estará disponible en la reportería _Historial de movimientos._

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/historial-de-movimientos" %}
[Historial de movimientos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/historial-de-movimientos)
{% endcontent-ref %}

***

### **4. Validaciones y Reglas de Negocio**

* El bono se crea de forma inmediata, pero la asignación a jugadores puede tardar entre **2 y 3 minutos**.
* El bono puede configurarse para múltiples juegos. Sin embargo, la cantidad de tiradas configuradas es única y compartida entre todos los juegos seleccionados, por lo que las tiradas podrán utilizarse en cualquiera de los juegos disponibles, pero no se asignarán de forma individual a cada uno.
* Este bono una vez creado quedará disponible para **CRM optimove**.
* Si el valor final por ronda configurado se encuentra dentro del rango de cuotas permitido por el juego, el bono podrá asignarse correctamente, aunque el valor no exista explícitamente en la lista de cuotas disponibles.
* Si el valor configurado está fuera del rango permitido por el juego, el bono se creará, pero no podrá ser asignado a los usuarios.

***

### &#x20;**5. Control de Versiones**

<details>

<summary>🔽 Historial de versiones.</summary>

| Versión | Fecha      | Autor           | Cambios Realizados |
| ------- | ---------- | --------------- | ------------------ |
| 1.0     | 24/06/2025 | David Velásquez | Documento inicial  |

</details>
