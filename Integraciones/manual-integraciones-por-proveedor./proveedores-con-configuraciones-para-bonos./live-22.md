---
description: >-
  Aquí encontrarás información importante que se debe tener en cuenta al momento
  de la creación de un bono FreeSpin para el proveedor Live 22.
---

# Live 22

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Torneos y Bonos > Bono FreeSpin

***

### 2. Visualización:

<figure><img src="../../.gitbook/assets/image (103).png" alt=""><figcaption><p>Figura#1: Captura de pantalla creación bono Free Spin.</p></figcaption></figure>

### **3. Acciones del Usuario**

Estas son las configuraciones principales y necesarias para generar un bono FreeSpin con los juegos del proveedor **Live 22**, en caso de necesitar información más detallada sobre cómo crear el bono FreeSpin, puedes acceder a la siguiente página:

{% embed url="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}

#### 3.1 Filtros

<table><thead><tr><th width="140.5">Sección</th><th width="108.126220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td>Define la fecha de inicio y finalización en la que el bono estará activo.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Define el nombre que se asignará al bono.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Campo numérico</td><td><p>Define la prioridad del bono frente a otros activos. En caso de que existan varios bonos activos, el sistema dará preferencia al bono con el valor de prioridad más alto.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> si se configuran dos bonos con prioridad 10 y 1 respectivamente, el sistema aplicará primero el bono con prioridad <strong>10</strong>.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Breve explicación de las condiciones o características del bono.</td></tr><tr><td><strong><code>Cantidad de jugadores</code></strong></td><td>Numérico</td><td>Define el número total de usuarios que recibirán el bono.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td><p>Selecciona el proveedor del bono, en este caso "Live 22".</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong>  Al seleccionar el juego correspondiente se desplegará una tabla en la que se indicará que porcentaje del bono será asumido por el proveedor Live 22<strong>.</strong></p></div></td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td><p>Lista los juegos disponibles del proveedor seleccionado. Se debe elegir el título específico por bono creado <a href="live-22.md#id-4.-validaciones-y-reglas-de-negocio"><sub>(Más información)</sub></a>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Para este proveedor solo se permite seleccionar <strong>un juego</strong> para cada bono freeSpin.</p></div></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Al seleccionar la moneda, se activarán las siguientes configuraciones.<br><a href="live-22.md#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr><tr><td><strong><code>Cliente puede recibir otros bonos adicionales</code></strong></td><td>Selector</td><td>Permite definir si el cliente podrá acumular más bonos, aparte del actual.</td></tr><tr><td><strong><code>Cliente puede repetir bono</code></strong></td><td>Selector</td><td>Define si el mismo bono se puede asignar más de una vez al mismo usuario.</td></tr><tr><td><strong><code>Crear Bono</code></strong></td><td>Botón</td><td>Guarda la configuración y activa el bono.</td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

{% hint style="warning" %}
**Nota:**&#x20;

El Total bet Corresponde al valor total que se apuesta en cada giro otorgado por el bono.

Este valor no es configurable directamente, ya que se calcula automáticamente con base en la configuración del juego y los parámetros definidos en el bono. En los juegos de este proveedor, el **Total Bet** (apuesta total) se obtiene mediante la siguiente fórmula:

> **Total Bet = Valor por línea × Valor por ronda × Total de líneas del juego**

Este resultado representa el monto que se consume del bono en cada giro realizado.
{% endhint %}

<table><thead><tr><th width="114">Campo</th><th width="121">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Campo numérico</td><td><p>Valor que tendrá el bono por cada ronda jugada, este debe ser configurado obligatoriamente, aunque el valor que realmente se utiliza dentro del juego es el <strong>Total Bet</strong>. Sin embargo, su configuración es necesaria, ya que hace parte de la fórmula de cálculo previamente definida.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El valor ingresado en este campo debe ser igual a los valores disponibles en apuestas dentro del juego.</p></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Establece la cantidad de giros gratis que tendrá este bono.</td></tr><tr><td><strong><code>Limite de ganancia</code></strong></td><td>Numérico</td><td><p>Define monto máximo que un usuario puede ganar en una apuesta.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong></p><p>Se realiza una apuesta cuya ganancia potencial es de <strong>$500.000</strong>.<br>Sin embargo, el sistema tiene configurado un <strong>límite de ganancia de $300.000</strong>. Aunque la apuesta genere una ganancia mayor, el usuario <strong>sólo recibirá $300.000</strong>, ya que este valor corresponde al límite máximo permitido.</p></div></td></tr><tr><td><strong><code>valor por línea</code></strong></td><td>Numérico</td><td>Corresponde al valor que se asigna a cada línea o línea de pago dentro del juego, el cual se utiliza como base para el cálculo de la apuesta total.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Permite cargar un archivo en formato CSV con los ID de los jugadores que recibirán el bono.</td></tr></tbody></table>

<a href="live-22.md#id-3.-acciones-del-usuario" class="button secondary">Regresar</a>

</details>

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
* El bono solo se puede crear para un único juego, en caso de crearlo para distintos juegos, escogerá uno al azar.

***

### &#x20;**5. Control de Versiones**

| Versión | Fecha      | Autor       | Cambios Realizados |
| ------- | ---------- | ----------- | ------------------ |
| 1.0     | 31/03/2026 | Karol Navia | Documento inicial  |
