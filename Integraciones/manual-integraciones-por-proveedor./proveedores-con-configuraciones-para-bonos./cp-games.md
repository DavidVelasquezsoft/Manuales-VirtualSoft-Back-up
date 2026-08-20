---
description: >-
  Aquí encontrarás información importante que se debe tener en cuenta al momento
  de la creación de un bono FreeSpin para CP Games.
---

# CP Games

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Torneos y Bonos > Bono FreeSpin

***

### 2. Visualización:

<figure><img src="../../.gitbook/assets/image (127).png" alt=""><figcaption><p>Figura#1: Captura de pantalla creación bono FreeSpin.</p></figcaption></figure>

***

### **3.  Formulario para creación de bonos** CP GAMES

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor CP GAMES dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% embed url="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}

<table><thead><tr><th width="105">Sección</th><th width="124">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha</td><td>Define la fecha de inicio y finalización durante las cuales el bono permanecerá activo.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td><p>Selecciona el proveedor del bono, en este caso CP GAMES.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al configurar los campos <strong>Proveedor</strong> y <strong>Productos</strong>, se desplegará una tabla donde se deberá especificar el porcentaje del bono que será asumido por el proveedor.</p></div></td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td>Permite seleccionar el juego para el cual aplicará el bono. Al seleccionar esta opción se mostrarán dos listas; es necesario volver a seleccionar el proveedor CP GAMES para visualizar los juegos disponibles.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Selecciona la moneda correspondiente al país para el cual se creará el bono. Al hacerlo se habilitarán las configuraciones adicionales disponibles.<br><a href="pragmatic..md#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

<table><thead><tr><th width="112">Campo</th><th width="146">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Numérico</td><td><p>Monto asignado a cada giro del juego, al configurar esta opción, es crucial verificar previamente el monto de apuesta permitido en los juegos seleccionados, ya que este debe coincidir exactamente con el valor ingresado en este campo.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si se configura un valor por ronda de <strong>10</strong>, pero el juego únicamente permite una apuesta máxima de <strong>5</strong>, el bono no funcionará debido a que los valores no coinciden.</p></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Define la cantidad de rondas gratuitas que recibirá el usuario con este bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Permite cargar un archivo en formato <strong>CSV</strong> con los ID de los jugadores que recibirán el bono. El sistema procesará automáticamente el archivo y asignará el bono a los usuarios incluidos.</td></tr></tbody></table>

<a href="pragmatic..md#id-3.-formulario-para-creacion-de-bonos-pragmatic" class="button secondary">Regresar</a>

</details>

Finaliza la configuración del bono guardando y aplicando los cambios realizados desde el botón **`Crear Bono`**.

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
* El bono solo se puede configurar para un único juego. En caso de seleccionar varios juegos simultáneamente, el sistema asignará el bono únicamente a uno de ellos de forma aleatoria.
* Este bono una vez creado quedará disponible para **CRM**.

***

### &#x20;**5. Control de Versiones**

<details>

<summary>🔽Historial de versiones </summary>

<table><thead><tr><th width="106.1817626953125">Versión</th><th width="129.0908203125">Fecha</th><th width="133.54541015625">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>29/01/2026</td><td>David velasquez</td><td>Documento inicial </td></tr><tr><td>1.1</td><td>20/08/2026</td><td>Karol Navia</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-32144">Reestructuraciondel manual</a></td></tr></tbody></table>

</details>
