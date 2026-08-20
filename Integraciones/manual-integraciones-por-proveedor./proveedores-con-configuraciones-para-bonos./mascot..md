---
description: >-
  Aquí encontrarás información importante que se debe tener en cuenta al momento
  de la creación de un bono FreeSpin para MASCOT.
---

# MASCOT.

***

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Torneos y Bonos > Bono FreeSpin

***

### 2. Visualización:

<figure><img src="../../.gitbook/assets/image (126).png" alt=""><figcaption><p>Figura#1: Captura de pantalla creación bono FreeSpin.</p></figcaption></figure>

***

### **3. Formulario para creación de bonos MASCOT.**

Estas son las configuraciones principales y necesarias para generar un bono FreeSpin con los juegos del proveedor MASCOT, en caso de necesitar información más detallada sobre cómo crear el bono FreeSpin, puedes acceder a la siguiente página:

{% embed url="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}

<table><thead><tr><th width="123">Sección</th><th width="103.18182373046875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha </td><td><p>Define la fecha de inicio y finalización en la que el bono estará activo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El rango máximo desde Fecha Inicio a Fecha Fin es de 30 días.</p></div></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Define el nombre que se asignará al bono.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Campo numérico</td><td><p>Define la prioridad del bono frente a otros activos. En caso de que existan varios bonos activos, el sistema dará preferencia al bono con el valor de prioridad más alto.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> si se configuran dos bonos con prioridad 10 y 1 respectivamente, el sistema aplicará primero el bono con prioridad <strong>10</strong>.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Breve explicación de las condiciones o características del bono.</td></tr><tr><td><strong><code>Cantidad de jugadores</code></strong></td><td>Numérico</td><td>Define el número total de usuarios que recibirán el bono.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td>Selecciona el proveedor del bono, en este caso "MASCOT".</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td>Lista los juegos disponibles del proveedor seleccionado, se pueden seleccionar varios juegos.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Al seleccionar la moneda, se activarán las siguientes configuraciones.<br><a href="mascot..md#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

<details>

<summary>Configuración de moneda</summary>

<table><thead><tr><th width="114">Campo</th><th width="129">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda (</code></strong><em><strong><code>Linea</code></strong></em><strong><code>)</code></strong></td><td>Campo numérico</td><td><p>Define el <strong>valor base</strong> de la apuesta por ronda o línea.<br>Este valor se multiplica por la cantidad de líneas del juego y debe coincidir con uno de los montos de apuesta permitidos por el juego.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> </p><ul><li>El juego tiene <strong>10 líneas activas</strong>.</li><li>El juego permite apuestas totales de <strong>2.0</strong>, <strong>5.0</strong> y <strong>10.0</strong>.</li><li>Si se configura un <strong>valor por línea de 0.5</strong>:<br>→ 0.5 × 10 líneas = <strong>5.0</strong> (apuesta válida).</li></ul></div><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si el valor por línea multiplicado por la cantidad de líneas <strong>no coincide</strong> con los montos de apuesta <strong>permitidos por el juego</strong>, el sistema tomará por defecto la apuesta mínima del juego.</p><ul><li><a href="https://onedrive.live.com/:x:/g/personal/4227d1406a17f2f9/IQCCUDUzNLPcRIRo9MyBJz7uAVYgDNwknAV4nP-HpWzyHu4?rtime=AhfHIWL93kg&#x26;redeem=aHR0cHM6Ly8xZHJ2Lm1zL3gvYy80MjI3ZDE0MDZhMTdmMmY5L0lRQ0NVRFV6TkxQY1JJUm85TXlCSno3dUFWWWdETndrbkFWNG5QLUhwV3p5SHU0P09SPVRFQU1TLU1BR0xFVi5wMnBfbnMucndjJndkRXhwPVRFQU1TLUNPTlRST0wmQ1Q9MTc4NzA4MjcwMzE4MSZ3ZWI9MSZUZWFtc0NJRD02MGM2NmE1ZC0yOTliLTRmZWUtOTgyMi0wZWVlNTZiOGEwOWImbGlua09wZW5UaW1lPTE3ODcwODI3MDMyMDY">Cuotas </a></li></ul></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Establece la cantidad de giros gratis que tendrá este bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Permite cargar un archivo en formato CSV con los ID de los jugadores que recibirán el bono.</td></tr></tbody></table>

<a href="mascot..md#id-3.-formulario-para-creacion-de-bonos-mascot" class="button secondary">Regresar</a>

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
* Si se ingresa un valor erróneo en el campo **`Valor por ronda`** el bono se creará, pero no se le asignará al usuario.
* Cada jugada gratuita otorgada a través del **Bonus System** debe registrarse de manera individual en la reportería; no está permitido consolidar múltiples jugadas en un solo registro.

***

### &#x20;**5. Control de Versiones**

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="104">Versión</th><th width="125">Fecha</th><th width="155.272705078125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21/01/2026</td><td>David velasquez</td><td>Documento inicial </td></tr><tr><td>1.1</td><td>18/08/2026</td><td>Karol Navia</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-32145">Mejora del manual en general.</a></td></tr></tbody></table>

</details>
