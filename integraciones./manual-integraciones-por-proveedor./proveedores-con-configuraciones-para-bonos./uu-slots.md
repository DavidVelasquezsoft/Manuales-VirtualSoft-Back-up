---
description: >-
  Aquí encontrarás información importante que se debe tener en cuenta al momento
  de la creación de un bono FreeSpin para el proveedor UU Slots.
---

# UU Slots

#### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Torneos y Bonos > Bono FreeSpin

***

#### 2. Visualización:

<figure><img src="https://2840730235-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FpVk1Kqoe0aInaa5Ofl6i%2Fuploads%2Fd8eTDDmwLdFjT3eQanUz%2Fimage.png?alt=media&#x26;token=6a75d10d-f5f3-448d-97e9-3be2b6bd6b5f" alt=""><figcaption><p>Figura#1: Captura de pantalla creación bono FreeSpin.</p></figcaption></figure>

#### **3. Acciones del Usuario**

Estas son las configuraciones principales y necesarias para generar un bono FreeSpin con los juegos del proveedor **UU Slots**, en caso de necesitar información más detallada sobre cómo crear el bono FreeSpin, puedes acceder a la siguiente página:

<table><thead><tr><th width="123">Sección</th><th width="96.18182373046875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td><p>Define la fecha de inicio y finalización en la que el bono estará activo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El rango máximo desde Fecha Inicio a Fecha Fin es de 30 días.</p></div></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Define el nombre que se asignará al bono.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Campo numérico</td><td><p>Define la prioridad del bono frente a otros activos. En caso de que existan varios bonos activos, el sistema dará preferencia al bono con el valor de prioridad más alto.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> si se configuran dos bonos con prioridad 10 y 1 respectivamente, el sistema aplicará primero el bono con prioridad <strong>10</strong>.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Breve explicación de las condiciones o características del bono.</td></tr><tr><td><strong><code>Cantidad de jugadores</code></strong></td><td>Numérico</td><td>Define el número total de usuarios que recibirán el bono.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td>Selecciona el proveedor del bono, en este caso "<strong>UU Slots</strong>".</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td><p>En este campo se debe seleccionar el título específico al cual se asociará el bono. Solo es posible crear un bono por cada juego.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong>  Al seleccionar el juego correspondiente se desplegará una tabla en la que se indicará que porcentaje del bono será asumido por el proveedor <strong>UU Slots.</strong></p></div></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Al seleccionar la moneda, se activarán las siguientes configuraciones.<br><a href="https://virtualsoft.gitbook.io/manuales/integraciones./manual-integraciones-por-proveedor./proveedores-con-configuraciones-para-bonos./uu-slots#configuraciones-por-moneda" class="button secondary">Configuraciones por moneda</a></td></tr><tr><td><strong><code>Cliente puede recibir otros bonos adicionales</code></strong></td><td>Selector</td><td>Permite definir si el cliente podrá acumular más bonos, aparte del actual.</td></tr><tr><td><strong><code>Cliente puede repetir bono</code></strong></td><td>Selector</td><td>Define si el mismo bono se puede asignar más de una vez al mismo usuario.</td></tr><tr><td><strong><code>Crear Bono</code></strong></td><td>Botón</td><td>Guarda la configuración y activa el bono.</td></tr></tbody></table>

<details>

<summary><strong>Configuraciones por moneda</strong></summary>

Al seleccionar la moneda será necesario configurar los siguientes campos:

<table><thead><tr><th width="171">Campo</th><th width="147">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Numérico</td><td>Valor total de cada giro gratuito.<br>Se calcula multiplicando el <strong><code>Valor de línea</code></strong> por el total de líneas del juego <a href="https://virtualsoft.gitbook.io/manuales/integraciones./manual-integraciones-por-proveedor./proveedores-con-configuraciones-para-bonos./uu-slots#configuraciones-por-cada-juego"><em>(ver tabla de configuraciones por juego)</em></a> <em>(Ej: 0.01 [Valor de línea] × 40 [Total de líneas] = 0.40 [Valor por ronda]).</em></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Determina la cantidad total de giros gratuitos que recibirá el usuario.</td></tr><tr><td><strong><code>Límite de ganancia</code></strong></td><td>Numérico</td><td>Establece el monto máximo que el usuario podrá ganar con el bono.<br>El valor ingresado no puede superar el resultado de multiplicar el Valor por ronda por 1000.</td></tr><tr><td><strong><code>Valor de línea</code></strong></td><td>Numérico</td><td>Valor que se apuesta por cada línea del juego. Solo se pueden ingresar los valores permitidos para el juego seleccionado <a href="https://virtualsoft.gitbook.io/manuales/integraciones./manual-integraciones-por-proveedor./proveedores-con-configuraciones-para-bonos./uu-slots#configuraciones-por-cada-juego"><em>(consultar la tabla de configuraciones por juego)</em></a>.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Archivo CSV</td><td>Permite cargar un archivo en formato CSV con los ID de los jugadores que recibirán el bono.</td></tr></tbody></table>

</details>

<details>

<summary>🎰 Configuraciones por cada juego</summary>

Antes de configurar el bono, es importante tener en cuenta que cada juego tiene:

* Un **total de líneas fijo** (propio del juego).
* Valores específicos permitidos para el **Valor de línea**.

El **`Valor por ronda`** se obtiene multiplicando el **`Valor de línea`** por el total de líneas del juego.\
Por ello, primero debes validar qué valores están disponibles para el juego seleccionado.

<table><thead><tr><th width="176" align="center">Juego</th><th width="169" align="center">Total de líneas</th><th align="center">Valores permitidos en Valor de línea (USD)</th></tr></thead><tbody><tr><td align="center"><strong>Blessing of Tu</strong></td><td align="center">40</td><td align="center">0.005 – 5</td></tr><tr><td align="center"><strong>The Silver Tiger</strong></td><td align="center">50</td><td align="center">0.01 – 4</td></tr><tr><td align="center"><strong>Legend of Thor</strong></td><td align="center">20</td><td align="center">0.01 – 10</td></tr><tr><td align="center"><strong>Devil's Hand</strong></td><td align="center">20</td><td align="center">0.01 – 10</td></tr><tr><td align="center"><strong>Happy Buddha</strong></td><td align="center">9</td><td align="center">0.01 – 20</td></tr><tr><td align="center"><strong>Mahjong Wilds</strong></td><td align="center">20</td><td align="center">0.01 – 10</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: No se puede ingresar cualquier valor dentro del rango.\
El Valor de línea debe coincidir exactamente con uno de los valores permitidos por el juego.
{% endhint %}

</details>

***

* La información de este bono estará disponible en la reportería de _Productos No Deportivos_.

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos" %}
[Reporte productos no deportivos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos)
{% endcontent-ref %}

* La información sobre los movimientos realizados en el usuario con este bono estará disponible en la reportería Historial de movimientos

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/historial-de-movimientos" %}
[Historial de movimientos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/historial-de-movimientos)
{% endcontent-ref %}

{% hint style="warning" %}
**Nota:** En el historial de movimientos, las transacciones correspondientes a este proveedor se visualizarán de forma agrupada. Si se asigna un bono con, por ejemplo, 10 giros, no se reflejará cada giro de manera individual; en su lugar, se mostrará un único movimiento que consolidará todas las ganancias generadas por el bono.
{% endhint %}

***

#### **4. Validaciones y Reglas de Negocio**

* El bono se crea de forma inmediata, pero la asignación a jugadores puede tardar entre **2 y 3 minutos**.
* El bono solo se puede configurar para un único juego. En caso de seleccionar varios juegos simultáneamente, el sistema asignará el bono únicamente a uno de ellos de forma aleatoria.
* Si se ingresa un valor erróneo en el campo **`Valor por ronda`** el bono se creará, pero no se le asignará al usuario.
* Una vez creado el bono, este estará disponible para CRM.

***

#### **5. Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 24/02/2026 | Ronald Peláez | Documento inicial  |
