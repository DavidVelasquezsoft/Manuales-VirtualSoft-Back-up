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

haEste tablero presenta información general consolidada de todas las [campañas](https://virtualsoft.gitbook.io/plantillas/glosario#campana) de los diferentes partners, centralizando la información en un solo lugar.

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Tablero de consultas TSR.

***

### 2. Configuraciones previas

Antes de ingresar a este tablero, es necesario completar los filtros que se visualizarán durante las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-1.-configuraciones-previas).

<table><thead><tr><th width="145">Filtro</th><th width="136">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Torneo</code></strong></td><td>Alfanuméricos</td><td>Identificador único del torneo a consultar.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Alfanuméricos</td><td><p>Identificador único del usuario asociado a las <a href="https://virtualsoft.gitbook.io/plantillas/glosario#campana">campañas</a> a consultar.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Este es el único filtro cuyo valor <strong>0</strong> no representa ausencia de información. Al ingresar <strong>0</strong>, se consultará la información correspondiente a <strong>todos los usuarios</strong>, en lugar de filtrar por un usuario específico.</p></div></td></tr><tr><td><strong><code>Id Sorteo</code></strong></td><td>Alfanuméricos</td><td>Identificador único del sorteo a consultar.</td></tr><tr><td><strong><code>ID Ruleta</code></strong></td><td>Alfanuméricos</td><td>Identificador único de la ruleta a consultar.</td></tr><tr><td><strong><code>Id Jackpot</code></strong></td><td>Alfanuméricos</td><td>Identificador único del jackpot <em>(local)</em> a consultar.</td></tr><tr><td><strong><code>Id Jackpot Internacional</code></strong></td><td>Alfanuméricos</td><td>Identificador único del jackpot internacional a consultar.</td></tr><tr><td><strong><code>ID Ronda</code></strong></td><td>Alfanuméricos</td><td>Identificador único de la ronda en la que el usuario ganó la campaña.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**:&#x20;

* Si no se ingresa un valor en un filtro, por defecto se asignará **0** y la pestaña correspondiente del tablero no mostrará información.
* Cada filtro aplica únicamente a su respectiva pestaña. El único filtro que aplica a todas las pestañas del tablero es **`Id Usuario`**.
{% endhint %}

***

### 3. Acciones disponibles

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros/tablero-de-consultas-tsr#id-2.-configuraciones-previas"><strong>Aplicar filtros</strong></a></td><td>Utiliza los filtros visualizados en las configuraciones previas para realizar la consulta directa antes de ingresar al tablero.</td></tr><tr><td><strong>Visualizar contenido del tablero</strong></td><td>Visualiza el contenido del tablero, el cual está compuesto por tablas y separado por <a href="https://virtualsoft.gitbook.io/plantillas/glosario#campana">campañas</a>.</td></tr><tr><td><strong>Exportar contenido</strong></td><td>El tablero permite exportar su contenido. Para más información, consulte la guía de exportación <a data-mention href="./#id-3.-exportar-contenido">#id-3.-exportar-contenido</a>.</td></tr></tbody></table>

***

### 4. Contenido del dashboard

El dashboard se compone de varias pestañas, cada una correspondiente a una de las [campañas](https://virtualsoft.gitbook.io/plantillas/glosario#campana) disponibles.

{% tabs %}
{% tab title="Rondas" %}
Presenta una tabla con los movimientos asociados a las rondas consultadas, incluyendo información de la transacción, el movimiento realizado, el monto y la respuesta obtenida.

#### Visualización

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FLVe5U0GYbswg3oIZxtRh%2Fimage.png?alt=media&#x26;token=49525d33-015b-4f63-88f0-6dbb879df2df" alt=""><figcaption><p>Figura #1: Captura de pantalla pestaña Rondas.</p></figcaption></figure>

***

<table><thead><tr><th width="151">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>IdRonda</code></strong></td><td>Identificador único de la ronda.</td></tr><tr><td><strong><code>FechaApi</code></strong></td><td>Fecha exacta en la que se realizó la ronda.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador único del usuario que jugo la ronda.</td></tr><tr><td><strong><code>IdTransaccion</code></strong></td><td>Identificador único relacionado con la transacción realizada por la ronda.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Tipo de movimiento realizado por la ronda <em>(debit, credit)</em>.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Valor por el cual se realizó el movimiento de la ronda.</td></tr><tr><td><strong><code>Respuesta</code></strong></td><td>Respuesta obtenida al realizar la apuesta <em>(Puede ser un código de respuesta o un Ok)</em>.</td></tr><tr><td><strong><code>Json</code></strong></td><td>Texto en formato JSON que contiene información asociada a la ronda.</td></tr></tbody></table>
{% endtab %}

{% tab title="Torneos" %}
Presenta información relacionada con la configuración de los torneos, su detalle, la información interna y las asignaciones realizadas a los usuarios.

#### Visualización

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FBHY1cqF1GNi8Ka69OAna%2Fimage.png?alt=media&#x26;token=0145658d-c9c1-454e-844c-c41a8420658c" alt=""><figcaption><p>Figura #2: Captura de pantalla pestaña Torneos.</p></figcaption></figure>

#### Detalle del torneo

Contiene la información de configuración y los valores asociados al detalle del torneo.

<table><thead><tr><th width="210">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Auto Detalle Torneo</code></strong></td><td>Identificador interno del detalle del torneo.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Descripción del detalle de tipo de torneo.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda asociada al registro.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Valor principal configurado para el registro.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha de creación del registro.</td></tr><tr><td><strong><code>Usuarios Crea</code></strong></td><td>Usuario asociado a la creación del torneo.</td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td>Fecha de la última modificación del torneo.</td></tr><tr><td><strong><code>Usuario Modificación</code></strong></td><td>Usuario que realizó la última modificación.</td></tr><tr><td><strong><code>Detalle</code></strong></td><td>Información adicional asociada al torneo.</td></tr><tr><td><strong><code>Valor2</code></strong></td><td>Valor adicional configurado al momento de crear el torneo.</td></tr><tr><td><strong><code>Valor3</code></strong></td><td>Valor adicional configurado al momento de crear el torneo.</td></tr></tbody></table>

#### Información interna del torneo

Contiene la información general, administrativa y de configuración del torneo.

<table><thead><tr><th width="176">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Torneo</code></strong></td><td>Identificador del torneo.</td></tr><tr><td><strong><code>Fecha inicio</code></strong></td><td>Fecha de inicio del torneo.</td></tr><tr><td><strong><code>Fecha Expiración</code></strong></td><td>Fecha de expiración del torneo.</td></tr><tr><td><strong><code>Detalle</code></strong></td><td>Información adicional asociada al torneo.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de torneo.</td></tr><tr><td><strong><code>Nombre Torneo</code></strong></td><td>Nombre asignado al torneo.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del torneo.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado al torneo.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha de creación del torneo.</td></tr><tr><td><strong><code>Usuario Crea</code></strong></td><td>Identificador del usuario que creó el torneo.</td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td>Fecha de la última modificación del torneo.</td></tr><tr><td><strong><code>Usuario Modificación</code></strong></td><td>Usuario que realizó la última modificación.</td></tr><tr><td><strong><code>TYC</code></strong></td><td>Términos y condiciones asociados al torneo.</td></tr><tr><td><strong><code>Json</code></strong></td><td>Información asociada al torneo en formato JSON.</td></tr></tbody></table>

#### Torneo asignado a usuario

Presenta la información de los torneos asignados a los usuarios y los valores relacionados con su participación.

<table><thead><tr><th width="172">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Auto Torneo</code></strong></td><td>Identificador interno de la asignación del torneo.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado al torneo.</td></tr><tr><td><strong><code>Torneo</code></strong></td><td>Identificador del torneo asignado.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador del usuario al que se asignó el torneo.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha de creación de la asignación.</td></tr><tr><td><strong><code>Usuario Crea</code></strong></td><td>Usuario que realizó la asignación.</td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td>Fecha de la última modificación de la asignación.</td></tr><tr><td><strong><code>Usuario Modificación</code></strong></td><td>Usuario que realizó la última modificación.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado de la asignación del torneo.</td></tr><tr><td><strong><code>Valor apostado</code></strong></td><td>Valor apostado por el usuario en el torneo.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Código asociado al registro del torneo.</td></tr><tr><td><strong><code>Valor Torneo</code></strong></td><td>Valor configurado para el torneo.</td></tr><tr><td><strong><code>Valor base</code></strong></td><td>Valor inicial con el que fue creado el torneo.</td></tr><tr><td><strong><code>Valor premio</code></strong></td><td>Valor total del premio brindado al usuario al momento de ganar el torneo</td></tr></tbody></table>
{% endtab %}

{% tab title="Sorteos" %}
Presenta información relacionada con la configuración de los sorteos, su detalle, las asignaciones a usuarios y la acumulación de stickers.

#### Visualización

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FGlVlTSbIUTOsNBB7vGBC%2Fimage.png?alt=media&#x26;token=6ef07a30-96c0-4a00-8ac0-8362a4d65829" alt=""><figcaption><p>Visualización #3: Captura de pantalla pestaña Sorteos.</p></figcaption></figure>

{% tabs %}
{% tab title="Información interna del sorteo" %}
Contiene la información general y de configuración del sorteo, incluyendo su vigencia, estado, cupos y condiciones de participación.

<table><thead><tr><th width="174">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mandante</code></strong></td><td>Partner asociado al sorteo.</td></tr><tr><td><strong><code>Sorteo</code></strong></td><td>Identificador único del sorteo.</td></tr><tr><td><strong><code>Fecha Inicio</code></strong></td><td>Fecha de inicio de vigencia del sorteo.</td></tr><tr><td><strong><code>Fecha Expiración</code></strong></td><td>Fecha de finalización de vigencia del sorteo.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Descripción del sorteo.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de sorteo configurado.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre asignado al sorteo.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del sorteo.</td></tr><tr><td><strong><code>Fecha creación</code></strong></td><td>Fecha de creación del sorteo.</td></tr><tr><td><strong><code>Usuario crea</code></strong></td><td>Usuario que creó el sorteo.</td></tr><tr><td><strong><code>usuario Modifica</code></strong></td><td>Usuario que realizó la última modificación del sorteo.</td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td>Fecha de la última modificación del sorteo.</td></tr><tr><td><strong><code>TYC</code></strong></td><td>Términos y condiciones asociados al sorteo.</td></tr><tr><td><strong><code>Cupo Actual</code></strong></td><td>Cantidad de cupos utilizados o disponibles según el registro del sorteo.</td></tr><tr><td><strong><code>Cupo Máximo</code></strong></td><td>Cantidad máxima de cupos configurados para el sorteo.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Código asociado al sorteo.</td></tr><tr><td><strong><code>Cantidad Sorteos</code></strong></td><td>Cantidad de sorteos configurados.</td></tr><tr><td><strong><code>Máximo sorteos</code></strong></td><td>Cantidad máxima de sorteos permitidos.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Orden asignado al sorteo.</td></tr><tr><td><strong><code>Pegatinas</code></strong></td><td>Configuración relacionada con las pegatinas o stickers asociados al sorteo.</td></tr><tr><td><strong><code>Habilita Deportivas</code></strong></td><td>Indica si el sorteo se encuentra habilitado para la vertical de deportivas.</td></tr><tr><td><strong><code>Habilita Casino</code></strong></td><td>Indica si el sorteo se encuentra habilitado para la vertical de casino.</td></tr><tr><td><strong><code>Habilita Depósito</code></strong></td><td>Indica si el sorteo se encuentra habilitado para actividades relacionadas con depósitos.</td></tr><tr><td><strong><code>Json Temp</code></strong></td><td>Información temporal asociada al sorteo en formato JSON.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle del sorteo" %}
Contiene el detalle de la configuración del sorteo, incluyendo valores, fechas, estado y condiciones relacionadas con la asignación de premios.

<table><thead><tr><th width="149">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Auto Sorteo</code></strong></td><td>Identificador incremental del registro del sorteo.</td></tr><tr><td><strong><code>sorteo</code></strong></td><td>Identificador del sorteo asociado.</td></tr><tr><td><strong><code>Fecha Sorteo</code></strong></td><td>Fecha programada para el sorteo.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de configuración del sorteo.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda asociada al registro.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Valor configurado para el registro.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha de creación del registro.</td></tr><tr><td><strong><code>Usuario crea</code></strong></td><td>Usuario que creó el registro.</td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td>Fecha de la última modificación del registro.</td></tr><tr><td><strong><code>Valor2</code></strong></td><td>Valor complementario asociado al registro.</td></tr><tr><td><strong><code>Valor3</code></strong></td><td>Valor complementario adicional asociado al registro.</td></tr><tr><td><strong><code>Usuario Modificación</code></strong></td><td>Usuario que realizó la última modificación del registro.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del registro.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Descripción asociada al detalle del sorteo.</td></tr><tr><td><strong><code>Permite Ganador</code></strong></td><td>Indica si la configuración permite registrar un ganador.</td></tr><tr><td><strong><code>Jugador excluido</code></strong></td><td>Indica si existe un jugador excluido de la participación o asignación correspondiente.</td></tr><tr><td><strong><code>Múltiple premio jugador</code></strong></td><td>Indica si un mismo jugador puede recibir múltiples premios.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL de la imagen asociada al sorteo.</td></tr></tbody></table>
{% endtab %}

{% tab title="Sorteo asignado a usuario" %}
Presenta la información del sorteo asignado a cada usuario, incluyendo valores, premios, estado y datos de trazabilidad de la asignación.

<table><thead><tr><th width="125">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mandante</code></strong></td><td>Partner asociado al sorteo.</td></tr><tr><td><strong><code>Sorteo</code></strong></td><td>Identificador del sorteo asignado.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador del usuario asociado al sorteo.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Valor asociado a la asignación.</td></tr><tr><td><strong><code>Valor Base</code></strong></td><td>Valor base utilizado para la asignación o cálculo del premio.</td></tr><tr><td><strong><code>Valor Premio</code></strong></td><td>Valor del premio asociado al usuario.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado de la asignación o participación del usuario.</td></tr><tr><td><strong><code>Premio</code></strong></td><td>Premio asociado al usuario.</td></tr><tr><td><strong><code>Premio ID</code></strong></td><td>Identificador del premio asociado.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha de creación de la asignación.</td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td>Fecha de la última modificación de la asignación.</td></tr><tr><td><strong><code>Usuario Crea</code></strong></td><td>Usuario que creó la asignación.</td></tr><tr><td><strong><code>Usuario Modifica</code></strong></td><td>Usuario que realizó la última modificación.</td></tr><tr><td><strong><code>Versión</code></strong></td><td>Versión asociada al registro de la asignación.</td></tr><tr><td><strong><code>Posición</code></strong></td><td>Posición obtenida por el usuario en el sorteo.</td></tr><tr><td><strong><code>Apostado</code></strong></td><td>Valor apostado asociado al usuario.</td></tr><tr><td><strong><code>Error</code></strong></td><td>Código o información del error generado durante el proceso, si aplica.</td></tr><tr><td><strong><code>Externo ID</code></strong></td><td>Identificador único del sorteo utilizado por proveedores externos.</td></tr><tr><td><strong><code>Id Externo</code></strong></td><td>Identificador único del sorteo utilizado internamente.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Código habilitado para inscribirse al sorteo.</td></tr></tbody></table>
{% endtab %}

{% tab title="Usuarios que acumulan stickers" %}
Presenta la información de los usuarios que acumulan stickers asociados a los sorteos, incluyendo los valores y premios relacionados.

{% hint style="warning" %}
**Nota**: La acumulación de stikers se establece al momento de la creación del sorteo.
{% endhint %}

<table><thead><tr><th width="128">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mandante</code></strong></td><td>Partner asociado al sticker obtenido por el usuario.</td></tr><tr><td><strong><code>Sorteo</code></strong></td><td>Identificador del sorteo asociado.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador del usuario que acumula el sticker.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Valor asociado al registro de acumulación.</td></tr><tr><td><strong><code>Valor Base</code></strong></td><td>Valor base asociado al registro.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de registro asociado a la acumulación.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado del registro de acumulación.</td></tr><tr><td><strong><code>Apostado</code></strong></td><td>Valor apostado asociado al usuario.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha de creación del registro.</td></tr><tr><td><strong>Usuario crea</strong></td><td>Usuario que creó el registro.</td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td>Fecha de la última modificación del registro.</td></tr><tr><td><strong><code>Usuario Modifica</code></strong></td><td>Usuario que realizó la última modificación.</td></tr><tr><td><strong><code>Premio</code></strong></td><td>Premio asociado al registro.</td></tr><tr><td><strong><code>Valor premio</code></strong></td><td>Valor del premio asociado.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Ruleta" %}
Presenta información relacionada con la configuración de las ruletas, su detalle y las asignaciones realizadas a los usuarios, cada tabla se presenta en una pestaña diferente.

#### Visualización

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FSzfn4HheR2apjTeIRLqA%2Fimage.png?alt=media&#x26;token=91db0aea-40eb-4ffe-85df-f0922e178e01" alt=""><figcaption><p>Visualización #4: Captura de pantalla pestaña Ruleta.</p></figcaption></figure>

{% tabs %}
{% tab title="Información interna de la ruleta" %}
Contiene la configuración general de la ruleta, sus fechas de vigencia, estado, cupos y condiciones.

<table><thead><tr><th width="208">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Ruleta</code></strong></td><td>Identificador único de la ruleta.</td></tr><tr><td><strong><code>Fecha inicio ruleta</code></strong></td><td>Fecha de inicio de la ruleta.</td></tr><tr><td><strong><code>Fecha fin ruleta</code></strong></td><td>Fecha de finalización de la ruleta.</td></tr><tr><td><strong><code>Nombre ruleta</code></strong></td><td>Nombre asignado a la ruleta.</td></tr><tr><td><strong><code>Tipo ruleta</code></strong></td><td>Tipo de ruleta configurada.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Descripción de la ruleta.</td></tr><tr><td><strong><code>Estado ruleta</code></strong></td><td>Estado actual de la ruleta.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado a la ruleta.</td></tr><tr><td><strong><code>Fecha cración</code></strong></td><td>Fecha de creación de la ruleta.</td></tr><tr><td><strong><code>Fecha modificación</code></strong></td><td>Fecha de la última modificación de la ruleta.</td></tr><tr><td><strong><code>Condicional</code></strong></td><td>Condición asociada a la participación o ejecución de la ruleta.</td></tr><tr><td><strong><code>Cupo Actual</code></strong></td><td>Cantidad de cupos registrada actualmente.</td></tr><tr><td><strong><code>Cupo Máximo</code></strong></td><td>Cantidad máxima de cupos configurados para la ruleta.</td></tr><tr><td><strong><code>Máximo ruleta</code></strong></td><td>Valor máximo configurado para la ruleta.</td></tr><tr><td><strong><code>Cantidad Ruletas</code></strong></td><td>Cantidad de ruletas asociadas al registro.</td></tr><tr><td><strong><code>Terminos y condiciones</code></strong></td><td>Términos y condiciones asociados a la ruleta.</td></tr></tbody></table>
{% endtab %}

{% tab title="Ruleta detalle" %}
Presenta la información de los elementos o premios configurados para la ruleta.

<table><thead><tr><th width="198">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Ruleta</code></strong></td><td>Identificador único de la ruleta.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Segmento para el cuál aplica la ruleta.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda asociada al valor configurado.</td></tr><tr><td><strong><code>Valor Tipo</code></strong></td><td>Valor asociado al tipo configurado.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha de creación del registro.</td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td>Fecha de la última modificación del registro.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Descripción del elemento o premio.</td></tr><tr><td><strong><code>Porcentaje</code></strong></td><td>Porcentaje configurado para el premio de la ruleta.</td></tr></tbody></table>
{% endtab %}

{% tab title="Ruleta asignada a usuario" %}
Presenta la información de la ruleta asignada al usuario y el resultado asociado a su ejecución.

<table><thead><tr><th width="184">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado a la asignación.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al registro.</td></tr><tr><td><strong><code>Id Ruleta</code></strong></td><td>Identificador único de la ruleta.</td></tr><tr><td><strong><code>usuario</code></strong></td><td>Identificador del usuario asociado.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Valor asociado a la ejecución de la ruleta.</td></tr><tr><td><strong><code>Posición</code></strong></td><td>Posición obtenida dentro de la ruleta.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha de creación de la asignación.</td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td>Fecha de la última modificación de la asignación.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado en el que se encuentra la ruleta con respecto al usuario <em>(ej: redimido, expirado)</em>.</td></tr><tr><td><strong><code>Error</code></strong></td><td>Código de error generado al momento de ejecutar la ruleta, si aplica.</td></tr><tr><td><strong><code>premio</code></strong></td><td>Premio que ofrece la ruleta.</td></tr><tr><td><strong><code>Valor base</code></strong></td><td>Valor inicial con el cuál fue creado la ruleta.</td></tr><tr><td><strong><code>Apostado</code></strong></td><td>Valor apostado por el usuario.</td></tr><tr><td><strong><code>Valor Premio</code></strong></td><td>Valor del premio obtenido por el usuario al girar la ruleta.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Jackpot" %}
Presenta información relacionada con los jackpots locales, incluyendo su configuración, detalle y usuarios ganadores.

#### Visualización

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FARCgIKMiWpV8GFPtJGG6%2Fimage.png?alt=media&#x26;token=a2632174-fb8d-4d00-ba90-e8f7e230d31a" alt=""><figcaption><p>Visualización #5: Captura de pantalla pestaña Jackpot.</p></figcaption></figure>

Esta pestaña se compone de tres tablas, cada una organizada en su respectiva pestaña.

{% tabs %}
{% tab title="Información interna del jackpot" %}
Contiene la información de configuración general del jackpot, sus valores, vigencia y estado.

<table><thead><tr><th width="159">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado al jackpot.</td></tr><tr><td><strong><code>Pais</code></strong></td><td>País asociado al jackpot.</td></tr><tr><td><strong><code>IdJackpot</code></strong></td><td>Identificador único del jackpot.</td></tr><tr><td><strong><code>JackpotPadre</code></strong></td><td>Identificador del jackpot padre asociado.</td></tr><tr><td><strong><code>FechaInicio</code></strong></td><td>Fecha de inicio de vigencia del jackpot.</td></tr><tr><td><strong><code>FechaFin</code></strong></td><td>Fecha de finalización de vigencia del jackpot.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Descripción del jackpot.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de jackpot.</td></tr><tr><td><strong><code>Reinicio</code></strong></td><td>Visualiza si se estableció que el jackpot se reiniciará automáticamente o no.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre asignado al jackpot.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del jackpot.</td></tr><tr><td><strong><code>Valor Actual</code></strong></td><td>Valor actual acumulado del jackpot.</td></tr><tr><td><strong><code>fechaCreación</code></strong></td><td>Fecha de creación del jackpot.</td></tr><tr><td><strong><code>FechaModificación</code></strong></td><td>Fecha de la última modificación del jackpot.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Orden asociado al jackpot respecto a los demás jackpots creados.</td></tr><tr><td><strong><code>ValorBase</code></strong></td><td>Valor base configurado para el jackpot.</td></tr><tr><td><strong><code>ValorMáximo</code></strong></td><td>Valor máximo configurado para el jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="jackpot detalle" %}
Presenta el detalle de configuración del jackpot.

<table><thead><tr><th width="155">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado al jackpot.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al jackpot.</td></tr><tr><td><strong><code>IdJackpot</code></strong></td><td>Identificador único del jackpot.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de configuración del jackpot.</td></tr><tr><td><strong><code>ValorTipo</code></strong></td><td>Valor asociado al tipo de configuración.</td></tr><tr><td><strong><code>FechaCreacion</code></strong></td><td>Fecha de creación del registro.</td></tr></tbody></table>
{% endtab %}

{% tab title="Jackpot detalle ganador" %}
Presenta la información relacionada con el usuario ganador del jackpot.

<table><thead><tr><th width="210">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado al jackpot.</td></tr><tr><td><strong><code>Pais</code></strong></td><td>País asociado al jackpot.</td></tr><tr><td><strong><code>Id Jackpot</code></strong></td><td>Identificador único del jackpot.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador del usuario relacionado con el jackpot.</td></tr><tr><td><strong><code>Estado Jackpot ganador</code></strong></td><td>Estado del jackpot asociado al ganador.</td></tr><tr><td><strong><code>Fecha Ganador Jackpot</code></strong></td><td>Fecha en la que se registró el ganador del jackpot.</td></tr><tr><td><strong><code>Fecha Time Ganador Jakcpot</code></strong></td><td>Fecha y hora asociadas al registro del ganador.</td></tr><tr><td><strong><code>Hay ganador jackpot?</code></strong></td><td>Indica si existe un usuario ganador registrado.</td></tr><tr><td><strong><code>Id Usujackpotganador</code></strong></td><td>Identificador del usuario ganador del jackpot.</td></tr><tr><td><strong><code>Ticket Ganador</code></strong></td><td>Ticket asociado al ganador del jackpot.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Jackpot internacional" %}
Presenta información relacionada con los [jackpots internacionales](https://virtualsoft.gitbook.io/plantillas/glosario#jackpot-internacional), incluyendo su configuración, detalle y usuarios ganadores.

#### Visualización

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2Fz5cYYBaJJWdRMFAjvkb2%2Fimage.png?alt=media&#x26;token=e005cd62-cba2-41de-8da3-b5f22db99875" alt=""><figcaption><p>Visualización #6: Captura de pantalla pestaña Jackpot internacional.</p></figcaption></figure>

{% tabs %}
{% tab title="Información interna del jackpot" %}
Contiene la información general de configuración del jackpot internacional.

<table><thead><tr><th width="299">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Jd Jacopot Internacional</code></strong></td><td>Identificador único del jackpot internacional.</td></tr><tr><td><strong><code>Id jackpor padre internacional</code></strong></td><td>Identificador del <a href="https://virtualsoft.gitbook.io/plantillas/glosario#jackpot-padre">jackpot padre</a> internacional asociado.</td></tr><tr><td><strong><code>Nombre jackpot intenacional</code></strong></td><td>Nombre asignado al jackpot internacional.</td></tr><tr><td><strong><code>Fecha inicio</code></strong></td><td>Fecha de inicio de vigencia del jackpot internacional.</td></tr><tr><td><strong><code>Fecha caída</code></strong></td><td>Fecha registrada para la caída del jackpot internacional.</td></tr><tr><td><strong><code>Moneda Base</code></strong></td><td>Moneda base asociada al jackpot internacional.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Descripción del jackpot internacional.</td></tr></tbody></table>
{% endtab %}

{% tab title="jackpot detalle" %}
Presenta el detalle de configuración del jackpot internacional.

<table><thead><tr><th width="238">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id jackpot internacional</code></strong></td><td>Identificador único del jackpot internacional.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de configuración del jackpot.</td></tr><tr><td><strong><code>Valor Tipo</code></strong></td><td>Valor asociado al tipo de configuración.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha de creación del registro.</td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td>Fecha de la última modificación del registro.</td></tr><tr><td><strong><code>Usuario Crea</code></strong></td><td>Usuario que realizó la creación del registro.</td></tr><tr><td><strong><code>Usuario Modificación</code></strong></td><td>Usuario que realizó la última modificación.</td></tr></tbody></table>
{% endtab %}

{% tab title="Usuario jackpot internacional ganador" %}
Presenta la información de los usuarios ganadores de jackpots internacionales.

<table><thead><tr><th width="246">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Jackpot Internacional</code></strong></td><td>Identificador único del jackpot internacional.</td></tr><tr><td><strong><code>Id Usuario Ganador</code></strong></td><td>Identificador del usuario ganador.</td></tr><tr><td><strong><code>Ticket Ganador</code></strong></td><td>Ticket asociado al usuario ganador.</td></tr><tr><td><strong><code>Vertical Ganadora</code></strong></td><td><a href="https://virtualsoft.gitbook.io/plantillas/glosario#vertical">Vertical </a>en la que se generó el jackpot ganador.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}

***

### 5. Reglas y validaciones.

* Se recomienda filtrar el tablero por una única [campaña](https://virtualsoft.gitbook.io/plantillas/glosario#campana) _(Se filtra desde las configuraciones previas)_, ya que consultar información de todas las [campañas ](https://virtualsoft.gitbook.io/plantillas/glosario#campana)puede aumentar el tiempo de respuesta de la consulta.

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="94.7037353515625">Versión</th><th width="133.25927734375">Fecha</th><th width="161.77777099609375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>05/10/2026</td><td>Ronald Pelaéz</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-34286#icft=VSFT-34286">Documento inicial</a></td></tr></tbody></table>

</details>
