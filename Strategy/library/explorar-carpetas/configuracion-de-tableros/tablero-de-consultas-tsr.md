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

haEste tablero presenta información general consolidada de todas las campañas y verticales de los diferentes partners, centralizando la información en un solo lugar.

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

El dashboard se compone de varias pestañas, cada una correspondiente a una de las campañas o verticales disponibles.

{% tabs %}
{% tab title="Rondas" %}
Presenta una tabla con los movimientos asociados a las rondas consultadas, incluyendo información de la transacción, el movimiento realizado, el monto y la respuesta obtenida.

#### Visualización

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FLVe5U0GYbswg3oIZxtRh%2Fimage.png?alt=media&#x26;token=49525d33-015b-4f63-88f0-6dbb879df2df" alt=""><figcaption><p>Figura #1: Captura de pantalla pestaña Rondas.</p></figcaption></figure>

| Columna             | Descripción                                                                |
| ------------------- | -------------------------------------------------------------------------- |
| **`IdRonda`**       | Identificador único de la ronda.                                           |
| **`FechaApi`**      | Fecha exacta en la que se realizó la ronda.                                |
| **`IdTransaccion`** | Identificador único relacionado con la transacción realizada por la ronda. |
| **`Estado`**        | Tipo de movimiento realizado por la ronda _(debit, credit)_.               |
| **`Monto`**         | Valor por el cual se realizó el movimiento de la ronda.                    |
| **`Respuesta`**     | Respuesta obtenida al realizar la apuesta.                                 |
| **`Json`**          | Texto en formato JSON que contiene información asociada a la ronda.        |
{% endtab %}

{% tab title="Torneos" %}
Presenta información relacionada con la configuración de los torneos, su detalle, la información interna y las asignaciones realizadas a los usuarios.

#### Visualización

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FBHY1cqF1GNi8Ka69OAna%2Fimage.png?alt=media&#x26;token=0145658d-c9c1-454e-844c-c41a8420658c" alt=""><figcaption><p>Figura #2: Captura de pantalla pestaña Torneos.</p></figcaption></figure>

* Detalle del torneo

Contiene la información de configuración y los valores asociados al detalle del torneo.

| Columna                    | Descripción                                   |
| -------------------------- | --------------------------------------------- |
| **`Auto Detalle Torneo`**  | Identificador interno del detalle del torneo. |
| **`Tipo`**                 | Tipo asociado al detalle del torneo.          |
| **`Moneda`**               | Moneda asociada al registro.                  |
| **`Valor`**                | Valor principal configurado para el registro. |
| **`Fecha Creación`**       | Fecha de creación del registro.               |
| **`Usuarios Crea`**        | Usuario asociado a la creación del registro.  |
| **`Fecha Modificación`**   | Fecha de la última modificación del registro. |
| **`Usuario Modificación`** | Usuario que realizó la última modificación.   |
| **`Detalle`**              | Información adicional asociada al registro.   |
| **`Valor2`**               | Valor complementario del registro.            |
| **`Valor3`**               | Valor complementario adicional del registro.  |

* Información interna del torneo

Contiene la información general, administrativa y de configuración del torneo.

| Columna                    | Descripción                                     |
| -------------------------- | ----------------------------------------------- |
| **`Torneo`**               | Identificador del torneo.                       |
| **`Fecha inicio`**         | Fecha de inicio del torneo.                     |
| **`Fecha Expiración`**     | Fecha de expiración del torneo.                 |
| **`Detalle`**              | Información adicional asociada al torneo.       |
| **`Tipo`**                 | Tipo de torneo.                                 |
| **`Nombre Torneo`**        | Nombre asignado al torneo.                      |
| **`Estado`**               | Estado actual del torneo.                       |
| **`Partner`**              | Partner asociado al torneo.                     |
| **`Fecha Creación`**       | Fecha de creación del torneo.                   |
| **`Usuario Crea`**         | Identificador del usuario que creó el torneo.   |
| **`Fecha Modificación`**   | Fecha de la última modificación del torneo.     |
| **`Usuario Modificación`** | Usuario que realizó la última modificación.     |
| **`TYC`**                  | Términos y condiciones asociados al torneo.     |
| **`Json`**                 | Información asociada al torneo en formato JSON. |

* Torneo asignado a usuario

Presenta la información de los torneos asignados a los usuarios y los valores relacionados con su participación.

| Columna                    | Descripción                                           |
| -------------------------- | ----------------------------------------------------- |
| **`Auto Torneo`**          | Identificador interno de la asignación del torneo.    |
| **`Partner`**              | Partner asociado al torneo.                           |
| **`Torneo`**               | Identificador del torneo asignado.                    |
| **`Usuario`**              | Identificador del usuario al que se asignó el torneo. |
| **`Fecha Creación`**       | Fecha de creación de la asignación.                   |
| **`Usuario Crea`**         | Usuario que realizó la asignación.                    |
| **`Fecha Modificación`**   | Fecha de la última modificación de la asignación.     |
| **`Usuario Modificación`** | Usuario que realizó la última modificación.           |
| **`Estado`**               | Estado de la asignación del torneo.                   |
| **`Valor apostado`**       | Valor apostado por el usuario en el torneo.           |
| **`Código`**               | Código asociado al registro del torneo.               |
| **`Valor Torneo`**         | Valor configurado para el torneo.                     |
| **`Valor base`**           | Valor base asociado al torneo.                        |
| **`Valor premio`**         | Valor del premio asociado al usuario.                 |
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

<table><thead><tr><th width="128">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mandante</code></strong></td><td>Partner asociado al sticker obtenido por el usuario.</td></tr><tr><td><strong><code>Sorteo</code></strong></td><td>Identificador del sorteo asociado.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador del usuario que acumula el sticker.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Valor asociado al registro de acumulación.</td></tr><tr><td><strong><code>Valor Base</code></strong></td><td>Valor base asociado al registro.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de registro asociado a la acumulación.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado del registro de acumulación.</td></tr><tr><td><strong><code>Apostado</code></strong></td><td>Valor apostado asociado al usuario.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha de creación del registro.</td></tr><tr><td><strong>Usuario crea</strong></td><td>Usuario que creó el registro.</td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td>Fecha de la última modificación del registro.</td></tr><tr><td><strong><code>Usuario Modifica</code></strong></td><td>Usuario que realizó la última modificación.</td></tr><tr><td><strong><code>Premio</code></strong></td><td>Premio asociado al registro.</td></tr><tr><td><strong><code>Valor premio</code></strong></td><td>Valor del premio asociado.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Ruleta" %}
Presenta información relacionada con la configuración de las ruletas, su detalle y las asignaciones realizadas a los usuarios.

#### Visualización

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FSzfn4HheR2apjTeIRLqA%2Fimage.png?alt=media&#x26;token=91db0aea-40eb-4ffe-85df-f0922e178e01" alt=""><figcaption><p>Visualización #4: Captura de pantalla pestaña Ruleta.</p></figcaption></figure>

{% tabs %}
{% tab title="Información interna de la ruleta" %}
Contiene la configuración general de la ruleta, sus fechas de vigencia, estado, cupos y condiciones.

| Columna                      | Descripción                                                     |
| ---------------------------- | --------------------------------------------------------------- |
| **`Id Ruleta`**              | Identificador único de la ruleta.                               |
| **`Fecha inicio ruleta`**    | Fecha de inicio de la ruleta.                                   |
| **`Fecha fin ruleta`**       | Fecha de finalización de la ruleta.                             |
| **`Nombre ruleta`**          | Nombre asignado a la ruleta.                                    |
| **`Tipo ruleta`**            | Tipo de ruleta configurada.                                     |
| **`Descripción`**            | Descripción de la ruleta.                                       |
| **`Estado ruleta`**          | Estado actual de la ruleta.                                     |
| **`Partner`**                | Partner asociado a la ruleta.                                   |
| **`Fecha cración`**          | Fecha de creación de la ruleta.                                 |
| **`Fecha modificación`**     | Fecha de la última modificación de la ruleta.                   |
| **`Condicional`**            | Condición asociada a la participación o ejecución de la ruleta. |
| **`Cupo Actual`**            | Cantidad de cupos registrada actualmente.                       |
| **`Cupo Máximo`**            | Cantidad máxima de cupos configurados para la ruleta.           |
| **`Máximo ruleta`**          | Valor máximo configurado para la ruleta.                        |
| **`Cantidad Ruletas`**       | Cantidad de ruletas asociadas al registro.                      |
| **`Terminos y condiciones`** | Términos y condiciones asociados a la ruleta.                   |
{% endtab %}

{% tab title="Ruleta detalle" %}
Presenta la información de los elementos o premios configurados para la ruleta.

| Columna                  | Descripción                                       |
| ------------------------ | ------------------------------------------------- |
| **`Id Ruleta`**          | Identificador único de la ruleta.                 |
| **`Tipo`**               | Tipo de elemento o premio configurado.            |
| **`Moneda`**             | Moneda asociada al valor configurado.             |
| **`Valor Tipo`**         | Valor asociado al tipo configurado.               |
| **`Fecha Creación`**     | Fecha de creación del registro.                   |
| **`Fecha Modificación`** | Fecha de la última modificación del registro.     |
| **`Descripción`**        | Descripción del elemento o premio.                |
| **`Porcentaje`**         | Porcentaje configurado para el elemento o premio. |
{% endtab %}

{% tab title="Ruleta asignada a usuario" %}
Presenta la información de la ruleta asignada al usuario y el resultado asociado a su ejecución.

<table><thead><tr><th width="184">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado a la asignación.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al registro.</td></tr><tr><td><strong><code>Id Ruleta</code></strong></td><td>Identificador único de la ruleta.</td></tr><tr><td><strong><code>usuario</code></strong></td><td>Identificador del usuario asociado.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Valor asociado a la ejecución de la ruleta.</td></tr><tr><td><strong><code>Posición</code></strong></td><td>Posición obtenida dentro de la ruleta.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha de creación de la asignación.</td></tr><tr><td><strong><code>Fecha Modificación</code></strong></td><td>Fecha de la última modificación de la asignación.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado de la asignación o ejecución.</td></tr><tr><td><strong><code>Error</code></strong></td><td>Código de error generado al momento de ejecutar la ruleta, si aplica.</td></tr><tr><td><strong><code>premio</code></strong></td><td>Premio obtenido por el usuario.</td></tr><tr><td><strong><code>Valor base</code></strong></td><td>Valor base asociado al resultado.</td></tr><tr><td><strong><code>Apostado</code></strong></td><td>Valor apostado por el usuario.</td></tr><tr><td><strong><code>Valor Premio</code></strong></td><td>Valor del premio obtenido.</td></tr></tbody></table>
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

| Columna                 | Descripción                                            |
| ----------------------- | ------------------------------------------------------ |
| **`Partner`**           | Partner asociado al jackpot.                           |
| **`Pais`**              | País asociado al jackpot.                              |
| **`IdJackpot`**         | Identificador único del jackpot.                       |
| **`JackpotPadre`**      | Identificador del jackpot padre asociado.              |
| **`FechaInicio`**       | Fecha de inicio de vigencia del jackpot.               |
| **`FechaFin`**          | Fecha de finalización de vigencia del jackpot.         |
| **`Descripción`**       | Descripción del jackpot.                               |
| **`Tipo`**              | Tipo de jackpot.                                       |
| **`Reinicio`**          | Configuración relacionada con el reinicio del jackpot. |
| **`Nombre`**            | Nombre asignado al jackpot.                            |
| **`Estado`**            | Estado actual del jackpot.                             |
| **`ValorAvtual`**       | Valor actual acumulado del jackpot.                    |
| **`fechaCreación`**     | Fecha de creación del jackpot.                         |
| **`FechaModificación`** | Fecha de la última modificación del jackpot.           |
| **`Orden`**             | Orden asociado al jackpot.                             |
| **`ValorBase`**         | Valor base configurado para el jackpot.                |
| **`ValorMáximo`**       | Valor máximo configurado para el jackpot.              |
{% endtab %}

{% tab title="jackpot detalle" %}
Presenta el detalle de configuración del jackpot.

| Columna             | Descripción                              |
| ------------------- | ---------------------------------------- |
| **`Partner`**       | Partner asociado al jackpot.             |
| **`País`**          | País asociado al jackpot.                |
| **`IdJackpot`**     | Identificador único del jackpot.         |
| **`Tipo`**          | Tipo de configuración del jackpot.       |
| **`ValorTipo`**     | Valor asociado al tipo de configuración. |
| **`FechaCreacion`** | Fecha de creación del registro.          |
{% endtab %}

{% tab title="Jackpot detalle ganador" %}
Presenta la información relacionada con el usuario ganador del jackpot.

| Columna                          | Descripción                                           |
| -------------------------------- | ----------------------------------------------------- |
| **`Partner`**                    | Partner asociado al jackpot.                          |
| **`Pais`**                       | País asociado al jackpot.                             |
| **`Id Jackpot`**                 | Identificador único del jackpot.                      |
| **`ID Usuario`**                 | Identificador del usuario relacionado con el jackpot. |
| **`Estado Jackpot ganador`**     | Estado del jackpot asociado al ganador.               |
| **`Fecha Ganador Jackpot`**      | Fecha en la que se registró el ganador del jackpot.   |
| **`Fecha Time Ganador Jakcpot`** | Fecha y hora asociadas al registro del ganador.       |
| **`Hay ganador jackpot?`**       | Indica si existe un usuario ganador registrado.       |
| **`Id Usujackpotganador`**       | Identificador del usuario ganador del jackpot.        |
| **`Ticket Ganador`**             | Ticket asociado al ganador del jackpot.               |
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Jackpot internacional" %}
Presenta información relacionada con los jackpots internacionales, incluyendo su configuración, detalle y usuarios ganadores.

#### Visualización

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2Fz5cYYBaJJWdRMFAjvkb2%2Fimage.png?alt=media&#x26;token=e005cd62-cba2-41de-8da3-b5f22db99875" alt=""><figcaption><p>Visualización #6: Captura de pantalla pestaña Jackpot internacional.</p></figcaption></figure>

{% tabs %}
{% tab title="Información interna del jackpot" %}
Contiene la información general de configuración del jackpot internacional.

| Columna                              | Descripción                                               |
| ------------------------------------ | --------------------------------------------------------- |
| **`Jd Jacopot Internacional`**       | Identificador único del jackpot internacional.            |
| **`Id jackpor padre internacional`** | Identificador del jackpot padre internacional asociado.   |
| **`Nombre jackpot intenacional`**    | Nombre asignado al jackpot internacional.                 |
| **`Fecha inicio`**                   | Fecha de inicio de vigencia del jackpot internacional.    |
| **`Fecha caída`**                    | Fecha registrada para la caída del jackpot internacional. |
| **`Moneda Base`**                    | Moneda base asociada al jackpot internacional.            |
| **`Descripción`**                    | Descripción del jackpot internacional.                    |
{% endtab %}

{% tab title="jackpot detalle" %}
Presenta el detalle de configuración del jackpot internacional.

| Columna                        | Descripción                                    |
| ------------------------------ | ---------------------------------------------- |
| **`Id jackpot internacional`** | Identificador único del jackpot internacional. |
| **`Tipo`**                     | Tipo de configuración del jackpot.             |
| **`Valor Tipo`**               | Valor asociado al tipo de configuración.       |
| **`Fecha Creación`**           | Fecha de creación del registro.                |
| **`Fecha Modificación`**       | Fecha de la última modificación del registro.  |
| **`Usuario Crea`**             | Usuario que realizó la creación del registro.  |
| **`Usuario Modificación`**     | Usuario que realizó la última modificación.    |
{% endtab %}

{% tab title="Usuario jackpot internacional ganador" %}
Presenta la información de los usuarios ganadores de jackpots internacionales.

| Columna                        | Descripción                                      |
| ------------------------------ | ------------------------------------------------ |
| **`Id Jackpot Internacional`** | Identificador único del jackpot internacional.   |
| **`Id Usuario Ganador`**       | Identificador del usuario ganador.               |
| **`Ticket Ganador`**           | Ticket asociado al usuario ganador.              |
| **`Vertical Ganadora`**        | Vertical en la que se generó el jackpot ganador. |
{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}

***

### 5. Reglas y validaciones.

* Se recomienda filtrar el tablero solo por una vertical, ya que al traer toda la información, filtrar por todas las verticales hace que la consulta sea más pesada.

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="94.7037353515625">Versión</th><th width="133.25927734375">Fecha</th><th width="161.77777099609375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/06/2026</td><td>David velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
