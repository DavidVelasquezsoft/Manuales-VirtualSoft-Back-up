---
description: >-
  Permite gestionar y consultar información de los jackpots internacionales,
  incluyendo montos acumulados y detalles de ganadores, con valores consolidados
  en la moneda base.
---

# Gestión

### **1. Acceso al Módulo**

**Ruta:** Site Builder > Jackpot > Gestión

{% hint style="warning" %}
**Nota:** Solo usuarios con rol “**Administrador**” o con permisos específicos podrán realizar la gestión de jackpots.
{% endhint %}

***

### **2. Visualización**

<figure><img src="../../../.gitbook/assets/image (407).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Gestión</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="gestion.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="gestion.md#id-4.1.-visualizar-kpis"><strong>Visualizar KPIs</strong></a></td><td>Permite visualizar indicadores generales de los registros validos que se muestran en la tabla.</td></tr><tr><td><strong>Consultar</strong></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><a href="gestion.md#id-5.-agregar-operacion"><strong>Agregar operación</strong></a></td><td>Permite agregar una nueva operación (<em>Partner y país</em>) a un jackpot internacional en cualquier momento de su duración.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Descargar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en el formato <strong>Excel (.XLSX).</strong></td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="159">Campo</th><th width="134.99993896484375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Calendario</td><td>Define la fecha inicial a partir de la cual se realizará la consulta de jackpots</td></tr><tr><td><strong><code>Fecha fin</code></strong></td><td>Calendario</td><td>Define la fecha final hasta la cual se realizará la consulta de jackpots</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por el estado en el cual se encuentra el jackpot actualmente. (<em>Activo, Inactivo, Ganado, Todos</em>)</td></tr><tr><td><strong><code>ID del Jackpot</code></strong></td><td>Numérico</td><td>busca por el identificador único específico de un jackpot.</td></tr><tr><td><strong><code>ID Padre del Jackpot</code></strong></td><td>Numérico</td><td>Filtra por el identificador único del <a href="https://virtualsoft.gitbook.io/untitled/glosario/#jackpot-padre">Jackpot Padre</a> que corresponde al jackpot principal creado inicialmente. Permite visualizar todas las series (<em>jackpots hijos</em>) asociadas a este.</td></tr><tr><td><strong><code>Operaciones</code></strong></td><td>Lista desplegable</td><td>Selecciona múltiples operaciones (<em>Partners y países</em>) para consultar únicamente los jackpots asociados a esas operaciones específicas.</td></tr><tr><td><strong><code>Moneda base</code></strong></td><td>Lista desplegable</td><td>Filtra por los jackpots según la moneda definida como base en su configuración (<em>por ejemplo: <strong>USD</strong>, <strong>EUR</strong></em>)</td></tr></tbody></table>

#### 4.1. Visualizar KPIs

Permiten visualizar de forma inmediata el rendimiento general del Jackpot Internacional, mostrando indicadores que resumen la actividad, el crecimiento y la participación de los usuarios. Estos valores se **actualizan automáticamente cada que se realiza una consulta** y reflejan los cambios según los **filtros** **aplicados**.

{% hint style="warning" %}
**Nota:** Los KPIs se agrupan según la **moneda base** configurada en cada jackpot. La moneda base es la moneda estándar con la que el jackpot unifica y calcula todos sus valores (_USD o EUR_), permitiendo consolidar los montos de operaciones con diferentes monedas locales.
{% endhint %}

<table><thead><tr><th width="197.7962646484375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad de Jackpots</code></strong></td><td>Muestra el total de jackpots creados (<em>activos, inactivos y ganados</em>), segmentados por moneda base.</td></tr><tr><td><strong><code>Monto Acumulado</code></strong></td><td>Presenta el monto total acumulado en el jackpot internacional a partir de las apuestas registradas, expresado en la moneda base configurada (<em>USD, EUR</em>).</td></tr><tr><td><strong><code>Jugadores Participantes</code></strong></td><td>Muestra la cantidad de jugadores únicos que han participado en el jackpot internacional, agrupados según la moneda base configurada en cada jackpot (<em>USD o EUR</em>)</td></tr><tr><td><strong><code>Valor de caídas del jackpot</code></strong></td><td>Indica el valor total pagado en jackpots ganados, este valor esta agrupado por moneda base (<em>USD, EUR</em>).</td></tr><tr><td><strong><code>Apuestas al Jackpot</code></strong></td><td>Valor total de Apuestas que sumaron a todos los jackpots <em>(Valor neto)</em> <em>(se deben diferenciar por moneda, es decir, valor de las apuestas que sumaron al Jackpot en USD y valor apuestas que sumaron jackpot en EUR)</em></td></tr></tbody></table>

#### 4.2. Resultados de consulta

Presenta el listado de jackpots que cumplen con los criterios de búsqueda definidos, mostrando la información segmentada **por operación** (_partner y país_).

<table><thead><tr><th width="170.037109375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td>Cada jackpot dispone de un conjunto de acciones que <strong>permiten gestionarlo</strong> y realizar seguimiento a su comportamiento dentro de la plataforma. La disponibilidad de cada acción depende del <strong>estado actual del jackpot</strong>.</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="94.74078369140625" align="center">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><img src="../../../.gitbook/assets/icon_do_not_disturb.png" alt="" data-size="line"></td><td><p>Al inactivar un jackpot, la acción se aplicará únicamente sobre la operación seleccionada, sin afectar las demás operaciones asociadas. Al seleccionar la opción de inactivación, el sistema mostrará una ventana de confirmación y, para completar el proceso, el usuario deberá validar la acción mediante el ingreso del token de autenticación correspondiente al utilizado en BackOffice.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Para desactivar completamente un jackpot internacional padre, será necesario inactivar de manera individual cada uno de los jackpots creados a partir de este.</p><p><a href="gestion.md#id-7.-validaciones-y-reglas-del-negocio">Validaciones de inactivación.</a></p></div></td></tr><tr><td align="center"><img src="../../../.gitbook/assets/icon_edit.png" alt="" data-size="line"></td><td>Permite modificar los recursos visuales del jackpot, como imágenes, contador y signo de moneda. Los demás campos de la configuración no pueden editarse desde esta acción. <a href="formulario.md#id-2.5.-contenido-grafico">Ver detalles</a></td></tr><tr><td align="center"><img src="../../../.gitbook/assets/icon_info.png" alt="" data-size="line"></td><td>Muestra la información completa del jackpot registrada durante su creación. <a href="formulario.md#id-2.-creacion-del-jackpot-internacional">ver detalles de campos</a></td></tr><tr><td align="center"><img src="../../../.gitbook/assets/icon_search.png" alt="" data-size="line"></td><td>Consulta el listado de jugadores que participaron en el jackpot junto con la información de su participación, y permite exportar los datos.<br><a href="gestion.md#contenido-de-detalle-de-jugadores">Ver información</a></td></tr></tbody></table>

<details>

<summary>🔽Contenido de detalle de jugadores</summary>

Al presionar en el botón <img src="../../../.gitbook/assets/icon_search.png" alt="" data-size="original"> de un jackpot, el sistema muestra la información de todos los jugadores participantes, permitiendo filtrar los resultados por **`ID del jugador`**.

<table><thead><tr><th width="156.33331298828125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID jugador</code></strong></td><td>Identifica de forma única al jugador dentro del sistema.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Muestra el nombre o alias asociado al jugador.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Indica el total de apuestas realizadas por el jugador en el jackpot.</td></tr><tr><td><strong><code>Apuestas locales</code></strong></td><td>Muestra el valor de las apuestas realizadas en la moneda local del jugador.</td></tr><tr><td><strong><code>Apuestas Base</code></strong></td><td>Representa el valor de las apuestas convertido a la moneda base del jackpot.</td></tr><tr><td><strong><code>Marca país</code></strong></td><td>Indica el país y la marca a la que pertenece el jugador.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Los resultados mostrados se permiten exportar en formato **.XLSX**
{% endhint %}

</details>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="170.11114501953125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Jackpot</code></strong></td><td>Identificador único del jackpot dentro del sistema.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre asignado al jackpot internacional.</td></tr><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Fecha en la que comenzó la acumulación o campaña del jackpot internacional.</td></tr><tr><td><strong><code>Fecha fin</code></strong></td><td>Especifica la fecha en la que ocurrió la caída del jackpot.</td></tr><tr><td><strong><code>Moneda Base</code></strong></td><td>Moneda base estándar utilizada para unificar los valores del jackpot internacional (<em>Ej: USD o EUR</em>).</td></tr><tr><td><strong><code>Monto acumulado</code></strong></td><td>Monto acumulado en el pozo del jackpot a partir de las apuestas registradas en la operación mostrada, expresado en la moneda base configurada.</td></tr><tr><td><strong><code>Operaciones</code></strong></td><td><p>Muestra la operación (<em>partner y país</em>) en la que el jackpot se encuentra vigente, estuvo activo o fue creado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Cada operación del jackpot internacional genera un registro independiente; por lo tanto, un mismo jackpot internacional puede aparecer en múltiples registros, uno por cada operación asociada.</p></div></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Muestra el estado actual del jackpot (<em>Activo, Inactivo o Ganado</em>).</td></tr></tbody></table>

***

### 5. Agregar operación

Permite incorporar una nueva operación (_Partner y país_) a un jackpot en cualquier momento de su duración, mediante el siguiente flujo:

{% stepper %}
{% step %}
#### Iniciar proceso

Al hacer clic en el botón <img src="../../../.gitbook/assets/Button (1) (2).png" alt="" data-size="line"> el sistema mostrará un modal para iniciar la configuración.
{% endstep %}

{% step %}
#### Seleccionar la operación

En el modal desplegado, busque y seleccione la operación en el listado desplegable, presentado en formato **Marca - País**.

{% hint style="warning" %}
**Nota:** Únicamente se permite seleccionar **una operación a la vez**.
{% endhint %}

Haga clic en **Continuar**.
{% endstep %}

{% step %}
#### Seleccionar el jackpot

Seleccione el [jackpot padre](https://virtualsoft.gitbook.io/untitled/glosario#jackpot-padre) al cual desea vincular la operación. El listado muestra los jackpots **activos** y los **programados** para activarse próximamente.

{% hint style="warning" %}
**Nota:** Si el jackpot seleccionado no tiene series (_Reinicios_) configuradas en el momento de su creación, en el listado se mostrará el nombre del jackpot acompañado de la indicación **“0 series”**. Al seleccionarlo, el sistema avanza directamente al formulario de configuración.
{% endhint %}
{% endstep %}

{% step %}
#### Seleccionar la serie de inicio (_si aplica_)

Si el jackpot está configurado para reiniciarse, se mostrará el listado de series disponibles. Seleccione la serie desde la cual la operación comenzará a participar.

{% hint style="info" %}
**Visualización de series:**

* Se muestran la **serie actual** y las **8 siguientes, siendo la serie 1 la actual**.
* Si el jackpot tiene menos de 8 series configuradas al momento de su creación, se muestran únicamente las disponibles.
* La operación participará desde la serie seleccionada en adelante.

_**Ejemplo:** si selecciona la Serie 1, la operación participará desde Serie 1 hasta Serie Infinita._
{% endhint %}

{% hint style="success" %}
Si el jackpot al momento de su creación **no** se configuró para reiniciarse, este paso se omite y el sistema avanza directamente al formulario de configuración
{% endhint %}
{% endstep %}

{% step %}
#### Completar el formulario de configuración

El formulario presenta las siguientes secciones, para configurar correctamente el jackpot:

> **Configuración general**

Define los siguientes campos obligatorios del jackpot:

{% hint style="warning" %}
**Nota:** Los cambios realizados en esta sección **aplican a todas las operaciones participantes**, no solo a la operación que se está agregando.
{% endhint %}

<table><thead><tr><th width="181.5">Campo</th><th width="122.9814453125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Permite ingresar el nombre del jackpot.</td></tr><tr><td><strong><code>Serie del jackpot</code></strong></td><td>Visualización</td><td><p>Muestra la serie previamente seleccionada desde la cual se incorpora la nueva operación.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Se muestra únicamente si el jackpot está configurado para reiniciarse y no se permite su edición.</p></div></td></tr><tr><td><strong><code>Rango mínimo de apuesta</code></strong></td><td>Numérico</td><td>Permite definir el numero <strong>mínimo de apuestas acumuladas</strong> necesarias para su caída (<em>Finalización y entrega del premio</em>).</td></tr><tr><td><strong><code>Rango máximo de apuesta</code></strong></td><td>Numérico</td><td><p>Define el número <strong>máximo de apuestas</strong> que puede acumular el jackpot.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al alcanzarse este tope, el sistema detiene la acumulación y ejecuta la acción configurada, como la caída del jackpot o la lógica establecida por la plataforma.</p></div></td></tr><tr><td><strong><code>Rango mínimo por caída</code></strong></td><td>Numérico</td><td><p>Define el número mínimo de apuestas acumuladas a partir del cual el jackpot puede caer al llegar a la fecha límite. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Aplica únicamente para jackpots sin reinicio.</p></div></td></tr><tr><td><strong><code>Rango máximo por caída</code></strong></td><td>Numérico</td><td><p>Define el número máximo de apuestas acumuladas dentro del cual el jackpot debe caer al llegar a la fecha límite. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Aplica únicamente para jackpots sin reinicio.</p></div></td></tr></tbody></table>

> **Información del Jackpot**

Muestra la información general del [jackpot padre](https://virtualsoft.gitbook.io/untitled/glosario#jackpot-padre) en modo consulta. **No permite edición.**

<table><thead><tr><th width="157.81488037109375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del jackpot</code></strong></td><td>Muestra el nombre del jackpot padre.</td></tr><tr><td><strong><code>Moneda base</code></strong></td><td>Muestra la moneda base en la que se configuró el jackpot padre al momento de su creación.</td></tr><tr><td><strong><code>Tipo de Jackpot</code></strong></td><td>Muestra el tipo de jackpot: por <strong>Fecha Fin</strong> (<em>finaliza en una fecha definida</em>) o por <strong>Series</strong> (<em>se reinicia automáticamente segun lo configurado en su creación</em>).</td></tr></tbody></table>

> **Productos participantes**

Permite seleccionar una o varias [verticales](https://virtualsoft.gitbook.io/untitled/glosario#vertical), configurar sus parámetros de participación y definir los productos que aplicarán al jackpot según la vertical seleccionada en esta operación. Para conocer el detalle de configuración, consulte la guía: [#id-2.3.-configuracion-de-productos-participantes](formulario.md#id-2.3.-configuracion-de-productos-participantes "mention")

> **Productos excluidos**

Permite seleccionar los productos por [vertical](https://virtualsoft.gitbook.io/untitled/glosario#vertical) que quedarán excluidos del jackpot, incluso si pertenecen a las verticales o proveedores configurados como participantes en esta operación. Para conocer el detalle de configuración, consulte la guía: [#id-2.4.-configuracion-de-productos-excluidos](formulario.md#id-2.4.-configuracion-de-productos-excluidos "mention")

> **Configuración visual**

Permite configurar los elementos gráficos del jackpot, definiendo los recursos visuales que se aplicarán en la plataforma. Consulte la guía de configuración: [#id-2.5.-contenido-grafico](formulario.md#id-2.5.-contenido-grafico "mention")

{% hint style="warning" %}
**Nota:** Los cambios realizados en esta sección **aplican a todas las operaciones participantes** del jackpot.
{% endhint %}
{% endstep %}

{% step %}
#### Confirmar con token

Para agregar correctamente la operación al jackpot, haz clic en **“Guardar Operación”**.

Al hacerlo, el sistema solicitará el **token de autenticación** para validar la acción.\
Ingresa el token y confirma nuevamente con **“Guardar”** para finalizar y agregar la operación al jackpot.
{% endstep %}
{% endstepper %}

***

### 6. Guardar cambios

Para guardar los cambios hechos haz clic en el botón **"guardar"**.\
Al hacerlo el sistema solicitará el **token de autenticación** para validar la acción. Ingresa el token y confirma nuevamente con **“Guardar”** para guardar los cambios hechos.

***

### 7. Validaciones y reglas del negocio

* Validaciones al agregar una operación:
  * La operación comienza a aportar al jackpot desde el momento en que se confirma la integración, a partir de la serie seleccionada y siguiendo la configuración establecida.
  * Al editar el rango mínimo y máximo de apuestas para la caída, el sistema muestra un mensaje informativo con la cantidad de apuestas acumuladas por el jackpot en ese momento.
  * Los aportes de la operación se acumulan en el jackpot internacional desde el momento en que se confirma la integración.
  * Si la nueva operación modifica el rango de apuestas y el jackpot se encuentra próximo a caer, el sistema ajusta la fecha de caída según la nueva configuración, respetando los parámetros vigentes y evitando que el jackpot caiga antes de lo previsto.
  * La operación se registra en el [reporte de jackpots internacionales](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/jackpot-internacional) del Backoffice, donde queda visible como parte de la serie desde la que fue agregada junto con la trazabilidad de la acción.
* La información en tiempo real de los jackpots internacionales, incluyendo datos generales y el desglose de aportes por partner y país, se presenta en el reporte [**Jackpot internacional**](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/jackpot-internacional).
* Una vez inactivada la operación:
  * El jackpot dejará de estar disponible para esa operación.
  * Los jugadores de la operación ya no podrán visualizar ni participar en el jackpot.
  * La operación dejará de aportar al pozo acumulado del jackpot.
  * La acumulación de apuestas para esa operación se detendrá.
  * La operación dejará de sumar información a los indicadores y reportes del jackpot internacional.
  * El saldo acumulado previamente por la operación continuará haciendo parte del premio del jackpot en curso, incluso si la operación es inactivada posteriormente.&#x20;
  * Si el jackpot hace parte de una serie y una operación es inactivada, esta dejará de participar a partir de la siguiente serie configurada.
  * Las siguientes series de jackpots no deberán considerar la operación inactivada para cálculos de acumulación, aportes ni participación.
  * La operación dejará de visualizarse en las configuraciones de las siguientes series del jackpot internacional.

***

### **8. Control de versiones**

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="110">Versión</th><th width="131">Fecha</th><th width="165">Autor</th><th>Cambios realizados</th></tr></thead><tbody><tr><td>1.0</td><td>23/12/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>20/04/2026</td><td>David Velasquez</td><td>Incorporación de la acción <strong><code>Agregar operación</code></strong></td></tr><tr><td>1.2</td><td>07/05/2026</td><td>Karol Navia</td><td>Mejoramiento del flujo de inactivación </td></tr><tr><td>1.3</td><td>20/02/2026</td><td>Ronald Peláez</td><td>Nuevos KPIs</td></tr></tbody></table>

</details>
