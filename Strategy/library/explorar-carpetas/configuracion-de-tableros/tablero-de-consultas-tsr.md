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

# Tablero de consultas TSR

Este tablero presenta información general consolidada de todas las campañas y verticales de los diferentes partners, centralizando la información en un solo lugar.

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Tablero de consultas TSR.

***

### 2. Configuraciones previas

Antes de ingresar a este tablero, es necesario completar los filtros que se visualizarán durante las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-1.-configuraciones-previas).

<table><thead><tr><th width="145">Filtro</th><th width="136">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Torneo</code></strong></td><td>Alfanuméricos</td><td>Identificador único del torneo a consultar.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Alfanuméricos</td><td><p>Identificador único del usuario asociado a las campañas a consultar.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Este es el único filtro cuyo valor <strong>0</strong> no representa ausencia de información. Al ingresar <strong>0</strong>, se consultará la información correspondiente a <strong>todos los usuarios</strong>, en lugar de filtrar por un usuario específico.</p></div></td></tr><tr><td><strong><code>Id Sorteo</code></strong></td><td>Alfanuméricos</td><td>Identificador único del sorteo a consultar.</td></tr><tr><td><strong><code>ID Ruleta</code></strong></td><td>Alfanuméricos</td><td>Identificador único de la ruleta a consultar.</td></tr><tr><td><strong><code>Id Jackpot</code></strong></td><td>Alfanuméricos</td><td>Identificador único del jackpot <em>(local)</em> a consultar.</td></tr><tr><td><strong><code>Id Jackpot Internacional</code></strong></td><td>Alfanuméricos</td><td>Identificador único del jackpot internacional a consultar.</td></tr><tr><td><strong><code>ID Ronda</code></strong></td><td>Alfanuméricos</td><td>Identificador único de la ronda en la que el usuario ganó la campaña.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**:&#x20;

* Si no se ingresa un valor en un filtro, por defecto se asignará **0** y la pestaña correspondiente del tablero no mostrará información.
* Cada filtro aplica únicamente a su respectiva pestaña. El único filtro que aplica a todas las pestañas del tablero es **`Id Usuario`**.
{% endhint %}

***

### 3. Acciones disponibles

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros/tablero-de-consultas-tsr#id-2.-configuraciones-previas"><strong>Aplicar filtros</strong></a></td><td>Utiliza los filtros visualizados en las configuraciones previas para realizar la consulta directa antes de ingresar al tablero.</td></tr><tr><td><strong>Visualizar contenido del tablero</strong></td><td>Visualiza el contenido del tablero, el cual está compuesto por tablas y separado por verticales.</td></tr><tr><td><strong>Exportar contenido</strong></td><td>El tablero permite exportar su contenido. Para más información, consulte la guía de exportación <a data-mention href="./#id-3.-exportar-contenido">#id-3.-exportar-contenido</a>.</td></tr></tbody></table>

***

### 4. Contenido del dashboard

El dashboard se compone de varias pestañas, cada pestaña es una de las campañas disponibles.

{% tabs %}
{% tab title="Rondas" %}
Visualiza una tabla con los movimientos asociados a las rondas filtradas o el usuario.

### Visualización&#x20;

<figure><img src="../../../.gitbook/assets/image (256).png" alt=""><figcaption><p>Figura #1: Captura de pantalla pestaña Rondas.</p></figcaption></figure>

<table><thead><tr><th width="147">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>IdRonda</code></strong></td><td>Identificador único de la ronda.</td></tr><tr><td><strong><code>FechaApi</code></strong></td><td>Fecha exacta en la que se realizó la ronda.</td></tr><tr><td><strong><code>IdTransaccion</code></strong></td><td>Identificador único relaiconado a la transacción realizada por la ronda.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Tipo de movimiento que realizó la ronda <em>(debit, credit)</em>.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Valor por el cuál fue realizado el movimiento de la ronda.</td></tr><tr><td><strong><code>Respuesta</code></strong></td><td>Respuesta obtenida al realizar la apuesta.</td></tr><tr><td><strong><code>Json</code></strong></td><td>Texto en formato Json que contiene información asociada a la ronda.</td></tr></tbody></table>
{% endtab %}

{% tab title="Torneos" %}
(Descripción)&#x20;

### Visualización&#x20;

<figure><img src="../../../.gitbook/assets/image (257).png" alt=""><figcaption><p>Figura #2: Captura de pantalla pestaña torneos.</p></figcaption></figure>

* Detalle del torneo

(Descripción)&#x20;

<table><thead><tr><th width="151">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Auto Detalle Torneo</code></strong></td><td></td></tr><tr><td><strong><code>Tipo</code></strong></td><td></td></tr><tr><td><strong><code>Moneda</code></strong></td><td></td></tr><tr><td><strong><code>Valor</code></strong></td><td></td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td></td></tr><tr><td><strong><code>Usuarios Crea</code></strong></td><td></td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td></td></tr><tr><td><strong><code>Usuario Modificación</code></strong></td><td></td></tr><tr><td><strong><code>Detalle</code></strong></td><td></td></tr><tr><td><strong><code>Valor2</code></strong></td><td></td></tr><tr><td><strong><code>Valor3</code></strong></td><td></td></tr></tbody></table>

* Información interna del torneo

(Descripción)&#x20;

<table><thead><tr><th width="148">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Torneo</code></strong></td><td></td></tr><tr><td><strong><code>Fecha inicio</code></strong></td><td></td></tr><tr><td><strong><code>Fecha Expiración</code></strong></td><td></td></tr><tr><td><strong><code>Detalle</code></strong></td><td></td></tr><tr><td><strong><code>Tipo</code></strong></td><td></td></tr><tr><td><strong><code>Nombre Torneo</code></strong></td><td></td></tr><tr><td><strong><code>Estado</code></strong></td><td></td></tr><tr><td><strong><code>Partner</code></strong></td><td></td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td></td></tr><tr><td><strong><code>Usuario Crea</code></strong></td><td>Id usuario que creó el torneo</td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td></td></tr><tr><td><strong><code>Usuario Modificación</code></strong></td><td></td></tr><tr><td><strong><code>TYC</code></strong></td><td></td></tr><tr><td><strong><code>Json</code></strong></td><td></td></tr></tbody></table>

* Torneo Asignado a usuario

(Descripción)&#x20;

<table><thead><tr><th width="143">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Auto Torneo</code></strong></td><td></td></tr><tr><td><strong><code>Partner</code></strong></td><td></td></tr><tr><td><strong><code>Torneo</code></strong></td><td></td></tr><tr><td><strong><code>Usuario</code></strong></td><td></td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td></td></tr><tr><td><strong><code>Usuario Crea</code></strong></td><td></td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td></td></tr><tr><td><strong><code>Usuario Modificación</code></strong></td><td></td></tr><tr><td><strong><code>Estado</code></strong></td><td></td></tr><tr><td><strong><code>Valor apostado</code></strong></td><td></td></tr><tr><td><strong><code>Código</code></strong></td><td></td></tr><tr><td><strong><code>Valor Torneo</code></strong></td><td></td></tr><tr><td><strong><code>Valor base</code></strong></td><td></td></tr><tr><td><strong><code>Valor premio</code></strong></td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="Sorteos" %}
(Descripción)&#x20;

#### Visualización

<figure><img src="../../../.gitbook/assets/image (258).png" alt=""><figcaption><p>Visualización #3: Captura de pantalla pestaña sorteos.</p></figcaption></figure>



{% tabs %}
{% tab title="Iinformación interna del sorteo" %}
(Descripción)&#x20;

<table><thead><tr><th width="174">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle del sorteo" %}
(Descripción)&#x20;

<table><thead><tr><th width="149">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="Sorteo asignado a usuario" %}
(Descripción)&#x20;

<table><thead><tr><th width="125">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr><tr><td></td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="Usuario que acumulan stikers" %}
(Descripción)&#x20;
{% endtab %}
{% endtabs %}


{% endtab %}

{% tab title="Ruleta" %}
(Descripción)&#x20;

### Visualización&#x20;

<figure><img src="../../../.gitbook/assets/image (259).png" alt=""><figcaption><p>Visualización #4: Captura de pantalla pestaña ruleta.</p></figcaption></figure>



{% tabs %}
{% tab title="Información interna de la ruleta" %}
(Descripción)&#x20;

<table><thead><tr><th width="174">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Ruleta</code></strong></td><td></td></tr><tr><td><strong><code>Fecha inicio ruleta</code></strong></td><td></td></tr><tr><td><strong><code>Fecha fin ruleta</code></strong></td><td></td></tr><tr><td><strong><code>Nombre ruleta</code></strong></td><td></td></tr><tr><td><strong><code>Tipo ruleta</code></strong></td><td></td></tr><tr><td><strong><code>Descripción</code></strong></td><td></td></tr><tr><td><strong><code>Estado ruleta</code></strong></td><td></td></tr><tr><td><strong><code>Partner</code></strong></td><td></td></tr><tr><td><strong><code>Fecha cración</code></strong></td><td></td></tr><tr><td><strong><code>Fecha modificación</code></strong></td><td></td></tr><tr><td><strong><code>Condicional</code></strong></td><td></td></tr><tr><td><strong><code>Cupo Actual</code></strong></td><td></td></tr><tr><td><strong><code>Cupo Máximo</code></strong></td><td></td></tr><tr><td><strong><code>Máximo ruleta</code></strong></td><td></td></tr><tr><td><strong><code>Cantidad Ruletas</code></strong></td><td></td></tr><tr><td><strong><code>Terminos y condiciones</code></strong> </td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="Ruleta detalle" %}
(Descripción)&#x20;

<table><thead><tr><th width="149">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Ruleta</code></strong></td><td></td></tr><tr><td><strong><code>Tipo</code></strong></td><td></td></tr><tr><td><strong><code>Moneda</code></strong></td><td></td></tr><tr><td><strong><code>Valor Tipo</code></strong></td><td></td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td></td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td></td></tr><tr><td><strong><code>Descripción</code></strong></td><td></td></tr><tr><td><strong><code>Porcentaje</code></strong></td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="Ruleta asignada a usuario" %}
(Descripción)&#x20;

<table><thead><tr><th width="151">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td></td></tr><tr><td><strong><code>País</code></strong></td><td></td></tr><tr><td><strong><code>Id Ruleta</code></strong></td><td>Identificador único de la ruleta.</td></tr><tr><td><strong><code>usuario</code></strong></td><td></td></tr><tr><td><strong><code>Valor</code></strong></td><td></td></tr><tr><td><strong><code>Posición</code></strong></td><td></td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td></td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td></td></tr><tr><td><strong><code>Estado</code></strong></td><td></td></tr><tr><td><strong><code>Error</code></strong></td><td>Código de error al momento de ejecutar la ruleta (si aplica) </td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td></td></tr><tr><td><strong><code>premio</code></strong></td><td></td></tr><tr><td><strong><code>Valor base</code></strong></td><td></td></tr><tr><td><strong><code>Apostado</code></strong></td><td></td></tr><tr><td><strong><code>Valor Premio</code></strong></td><td></td></tr></tbody></table>
{% endtab %}
{% endtabs %}


{% endtab %}

{% tab title="Jackpot" %}
(Descripción)&#x20;

Visualización

<figure><img src="../../../.gitbook/assets/image (260).png" alt=""><figcaption><p>Visualización #5: Captura de pantalla pestaña jackpot.</p></figcaption></figure>

Esta pestaña se compone de 3 tablas, cada tabla está en su respectiva pestaña.

{% tabs %}
{% tab title="Información interna del jackpot" %}
(Descripción)&#x20;

<table><thead><tr><th width="174">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td></td></tr><tr><td><strong><code>Pais</code></strong></td><td></td></tr><tr><td><strong><code>IdJackpot</code></strong></td><td></td></tr><tr><td><strong><code>JackpotPadre</code></strong></td><td></td></tr><tr><td><strong><code>FechaInicio</code></strong></td><td></td></tr><tr><td><strong><code>FechaFin</code></strong></td><td></td></tr><tr><td><strong><code>Descripción</code></strong></td><td></td></tr><tr><td><strong><code>Tipo</code></strong></td><td></td></tr><tr><td><strong><code>Reinicio</code></strong></td><td></td></tr><tr><td><strong><code>Nombre</code></strong></td><td></td></tr><tr><td><strong><code>Estado</code></strong></td><td></td></tr><tr><td><strong><code>ValorAvtual</code></strong></td><td></td></tr><tr><td><strong><code>fechaCreación</code></strong></td><td></td></tr><tr><td><strong><code>FechaModificación</code></strong></td><td></td></tr><tr><td><strong><code>Orden</code></strong></td><td></td></tr><tr><td><strong><code>ValorBase</code></strong></td><td></td></tr><tr><td><strong><code>ValorMáximo</code></strong></td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="jackpot detalle" %}
(Descripción)&#x20;

<table><thead><tr><th width="149">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td></td></tr><tr><td><strong><code>País</code></strong></td><td></td></tr><tr><td><strong><code>IdJackpot</code></strong></td><td></td></tr><tr><td><strong><code>Tipo</code></strong></td><td></td></tr><tr><td><strong><code>ValorTipo</code></strong></td><td></td></tr><tr><td><strong><code>FechaCreacion</code></strong></td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="Jackpot detalle ganador" %}
(Descripción)&#x20;

<table><thead><tr><th width="125">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td></td></tr><tr><td><strong><code>Pais</code></strong></td><td></td></tr><tr><td><strong><code>Id Jackpot</code></strong></td><td></td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td></td></tr><tr><td><strong><code>Estado Jackpot ganador</code></strong></td><td></td></tr><tr><td><strong><code>Fecha Ganador Jackpot</code></strong></td><td></td></tr><tr><td><strong><code>Fecha Time Ganador Jakcpot</code></strong></td><td></td></tr><tr><td><strong><code>Hay ganador jackpot?</code></strong></td><td></td></tr><tr><td><strong><code>Id Usujackpotganador</code></strong></td><td></td></tr><tr><td><strong><code>Ticket Ganador</code></strong></td><td></td></tr></tbody></table>
{% endtab %}
{% endtabs %}

.
{% endtab %}

{% tab title="Jackpot internacional" %}
(Descripción)&#x20;

Visualización

<figure><img src="../../../.gitbook/assets/image (261).png" alt=""><figcaption><p>Visualización #6: Captura de pantalla pestaña jackpot internacional.</p></figcaption></figure>

.

{% tabs %}
{% tab title="Información interna del jackpot" %}
(Descripción)&#x20;

<table><thead><tr><th width="174">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Jd Jacopot Internacional</code></strong></td><td></td></tr><tr><td><strong><code>Id jackpor padre internacional</code></strong></td><td></td></tr><tr><td><strong><code>Nombre jackpot intenacional</code></strong></td><td></td></tr><tr><td><strong><code>Fecha inicio</code></strong></td><td></td></tr><tr><td>Fecha caída</td><td></td></tr><tr><td><strong><code>Moneda Base</code></strong></td><td></td></tr><tr><td><strong><code>Descripción</code></strong></td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="jackpot detalle" %}
(Descripción)&#x20;

<table><thead><tr><th width="149">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id jackpot internacional</code></strong></td><td></td></tr><tr><td><strong><code>Tipo</code></strong></td><td></td></tr><tr><td><strong><code>Valor Tipo</code></strong></td><td></td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td></td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td></td></tr><tr><td><strong><code>Usuario Crea</code></strong></td><td></td></tr><tr><td><strong><code>Usuario Modificación</code></strong></td><td></td></tr></tbody></table>
{% endtab %}

{% tab title="Usuario jackpot internacional ganador" %}
(Descripción)&#x20;

<table><thead><tr><th width="123">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Jackpot Internacional</code></strong></td><td></td></tr><tr><td><strong><code>Id Usuario Ganador</code></strong></td><td></td></tr><tr><td><strong><code>Ticket Ganador</code></strong></td><td></td></tr><tr><td><strong><code>Vertical Ganadora</code></strong></td><td></td></tr></tbody></table>


{% endtab %}
{% endtabs %}

.
{% endtab %}
{% endtabs %}



### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="94.7037353515625">Versión</th><th width="133.25927734375">Fecha</th><th width="161.77777099609375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/06/2026</td><td>David velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
