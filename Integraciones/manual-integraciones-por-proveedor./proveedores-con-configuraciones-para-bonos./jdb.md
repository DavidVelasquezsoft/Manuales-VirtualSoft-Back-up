---
description: >-
  Aquí encontrarás información importante que se debe tener en cuenta al momento
  de la creación de un bono FreeSpin para el proveedor JDB.
---

# JDB

### 1. Acceso al Módulo:

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización:

<figure><img src="../../.gitbook/assets/image (114).png" alt=""><figcaption><p>Figura#1: Captura de pantalla creación bono Free Spin.</p></figcaption></figure>

### **3. Formulario para creación de bono JDB**

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **JDB** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% embed url="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}

<table><thead><tr><th width="140.5">Sección</th><th width="108.126220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td><p>Define la fecha de inicio y finalización en la que el bono estará activo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La fecha de finalización debe ser siempre posterior a la fecha de inicio, adicional, se recomienda configurar algunos minutos de holgura en la fecha de inicio para asegurar la correcta creación y activación del bono.</p></div></td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td><p>Selecciona el proveedor del bono, en este caso "<strong>JDB</strong>".</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong>  Al seleccionar el proveedor se desplegará una tabla en la que se indicará que porcentaje del bono será asumido por el proveedor <strong>JDB.</strong></p></div></td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td><p>Selecciona el juego <em>(producto)</em> para el cual aplicará el bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> </p><ul><li>Durante la configuración es posible seleccionar varios juegos simultáneamente. Sin embargo, el usuario únicamente podrá redimir el bono en uno de ellos.<br>Para usarlo en un juego específico, deberá ingresar desde <strong>Usuarios Online</strong>, acceder al juego correspondiente y realizar la activación del bono dentro del mismo.</li><li>No todos los juegos que están en esta lista tienen FreeSpin, se recomienda validar la lista en <a href="https://virtualsoft.gitbook.io/manuales/integraciones./manual-integraciones-por-proveedor./proveedores-con-configuraciones-para-bonos./jdb#id-4.-validaciones-y-reglas-de-negocio">reglas y validaciones.</a></li></ul></div></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Al seleccionar la moneda, se activarán las siguientes configuraciones.<br><a href="https://virtualsoft.gitbook.io/manuales/integraciones./manual-integraciones-por-proveedor./proveedores-con-configuraciones-para-bonos./jdb#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

<table><thead><tr><th width="114">Campo</th><th width="129">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Campo numérico</td><td><p>Define el monto de apuesta que se utilizará en cada giro del bono. Se recomienda configurar un valor que coincida con las opciones de apuesta disponibles en el juego; si se ingresa un monto distinto, el sistema ajustará automáticamente la apuesta al valor disponible más cercano por debajo del configurado.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo</strong>: Si el juego permite apuestas de 2, 2.5, 4 y el bono se crea con un valor por ronda de 3, el sistema aplicará 2.5, ya que es el valor disponible más cercano sin superar el monto definido.</p></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td><p>Establece la cantidad de giros gratis que tendrá este bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La cantidad máxima de giros gratis con este proveedor es de <strong>999</strong>, en caso de crear el bono con más giros gratis, se creará, pero no se asignará a los usuarios.</p></div></td></tr><tr><td><strong><code>Límite de ganancia</code></strong></td><td>Numérico</td><td><p>Define el monto máximo de ganancia total que el usuario podrá obtener a través de este bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si las ganancias generadas superan el valor configurado en este campo, el sistema acreditará únicamente el monto máximo establecido.</p></div></td></tr><tr><td><strong><code>Límite mínimo de ganancia</code></strong></td><td>Numérico</td><td>Define el monto mínimo que el usuario debe alcanzar en ganancias para poder recibir el premio del bono; en caso de no llegar a este valor, no se realizará ninguna acreditación.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Permite cargar un archivo en formato CSV con los ID de los jugadores que recibirán el bono.</td></tr></tbody></table>

<a href="https://virtualsoft.gitbook.io/manuales/integraciones./manual-integraciones-por-proveedor./proveedores-con-configuraciones-para-bonos./jdb#id-3.-formulario-para-creacion-de-bono-jdb" class="button secondary">Regresar</a>

</details>

Finaliza la configuración del bono guardando y aplicando las configuraciones realizadas desde el botón "**`Crear Bono`**".

***

La información de este bono estará disponible en la reportería de _Productos No Deportivos_.

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
* Este bono una vez creado quedará disponible para **CRM optimove**.
* En la lista de juegos se visualizan los que tienen y los que no tienen FreeSpin, se recomienda validar en esta lista el juego seleccionado.

{% file src="../../.gitbook/assets/juegoConFreeSpinJDBGAMES 4.pdf" %}

***

### **5. Control de Versiones**

<details>

<summary>🕛Historial de versiones.</summary>

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 16/04/2026 | Ronald Peláez | Documento inicial  |

</details>
