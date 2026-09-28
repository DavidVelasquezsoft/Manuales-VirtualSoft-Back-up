# Dashboard Referidos

<mark style="color:$info;">Consolida la información del programa de referidos, permitiendo hacer seguimiento a su desempeño, medir la captación y conversión de los referidos y monitorear el cumplimiento de las condiciones que generan recompensas a los</mark> [<mark style="color:$info;">referentes</mark>](https://virtualsoft.gitbook.io/plantillas/glosario#referente)<mark style="color:$info;">. Ofrece una vista ejecutiva con indicadores y gráficas, y vistas detalladas por referente y por referido.</mark>

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Dashboard Referidos

***

### 2. Acciones disponibles

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="dashboard-referidos.md#id-3.-filtros"><strong>Aplicar filtros</strong></a></td><td><p>Permite filtrar la información según los criterios disponibles en el panel de filtros. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Todos los indicadores, gráficas y tablas se actualizan automáticamente al aplicarlos, y los filtros pueden combinarse entre sí.</p></div></td></tr><tr><td><a href="dashboard-referidos.md#id-5.-contenido-del-dashboard"><strong>Visualizar contenido del tablero</strong></a></td><td><p>Utiliza las herramientas disponibles en el dashboard, incluyendo:</p><ul><li>Filtros dinámicos.</li><li>KPIs generales.</li><li>Gráficas de barras y embudo de conversión.</li><li>Tablas con información detallada por <a href="https://virtualsoft.gitbook.io/plantillas/glosario#referente">referente</a> y referido.</li></ul><p>Permite navegar e interactuar con la información mediante las vistas disponibles: <strong>Dashboard</strong>, <strong>Detalle referente</strong> y <strong>Detalle referido</strong>.</p></td></tr><tr><td><strong>Exportar contenido</strong></td><td>El dashboard permite exportar su contenido en formatos Excel, CSV y PDF, respetando los filtros activos. Para más información, consulte la guía de exportación  <a data-mention href="./#id-3.-exportar-contenido">#id-3.-exportar-contenido</a>.</td></tr></tbody></table>

***

### 3. Filtros

Permite visualizar la información del tablero de acuerdo con los criterios seleccionados en los siguientes filtros:

<table><thead><tr><th width="148.3333740234375">Campo</th><th width="130">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra la información por partner.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Segmenta la información según el país.</td></tr><tr><td><strong><code>Desde / Hasta</code></strong></td><td>Rango de fechas</td><td><p>Define el periodo de análisis.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El rango de fechas filtra según la <strong>fecha de registro del referido</strong>.</p></div></td></tr><tr><td><strong><code>Id Referente</code></strong></td><td>Numérico</td><td>Consulta la información de un <a href="https://virtualsoft.gitbook.io/plantillas/glosario#referente">referente</a> específico por su identificador único.</td></tr><tr><td><strong><code>ID Referido</code></strong></td><td>Numérico</td><td>Consulta la información de un referido específico por su identificador único.</td></tr><tr><td><strong><code>Tipo Condición</code></strong></td><td>Lista desplegable</td><td>Tipo de condición del programa de referidos <em>(condición de depósito, condición de primera apuesta o de verificado)</em>.</td></tr><tr><td><strong><code>Estado Global</code></strong></td><td>Lista desplegable</td><td>Filtra según el estado general del premio generado por el referido. Las opciones disponibles son:</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="161.6666259765625">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Cumplido</strong></td><td>Muestra los referidos que cumplieron la condición configurada y generaron la recompensa correspondiente al referente.</td></tr><tr><td><strong>Fallido</strong></td><td>Muestra los referidos que no cumplieron la condición configurada dentro del plazo establecido.</td></tr><tr><td><strong>Pendiente</strong></td><td>Muestra los referidos que aún no han cumplido la condición configurada y cuyo plazo continúa vigente.</td></tr><tr><td><strong>Premio Cancelado</strong></td><td>Muestra los referidos cuya recompensa fue cancelada, por lo que no puede ser redimida por el referente.</td></tr><tr><td><strong>Premio expirado - Causado por el referente</strong></td><td>Muestra los referidos cuya recompensa expiró sin ser redimida dentro del plazo de vigencia por parte del referente.</td></tr><tr><td><strong>Redimido - Causado por el referente</strong></td><td>Muestra los referidos cuya recompensa ya fue redimida por el referente.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="124.16668701171875">Campo</th><th width="130">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado Condición</code></strong></td><td>Lista desplegable</td><td>Filtra según el estado de la condición <em>(Pendiente, Cumplida o Vencida)</em>.</td></tr><tr><td><strong><code>Estado Bono</code></strong></td><td>Lista desplegable</td><td>Filtra según el estado del bono o recompensa <em>(Pendiente, Disponible, Redimida, sin bono o Vencida)</em>.</td></tr></tbody></table>

***

### 4. Contenido del dashboard

El dashboard se organiza en tres vistas que se seleccionan desde las pestañas ubicadas debajo de los KPIs. Cada vista ofrece un nivel distinto de análisis, desde el resumen ejecutivo hasta el detalle de cada referido.

#### 4.1. KPIs generales

En la parte superior del dashboard se muestran los indicadores clave del programa de referidos según los filtros aplicados.

<table><thead><tr><th width="200">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Referentes</code></strong></td><td>Cantidad de referentes únicos, es decir, usuarios que invitaron a otros a registrarse en la plataforma.</td></tr><tr><td><strong><code>Referidos</code></strong></td><td>Cantidad de referidos únicos registrados mediante un link de referido.</td></tr><tr><td><strong><code>Referidos Depósito</code></strong></td><td>Cantidad de referidos que cumplieron la condición de depósito.</td></tr><tr><td><strong><code>Referidos Apuesta</code></strong></td><td>Cantidad de referidos que cumplieron la condición de apuesta.</td></tr><tr><td><strong><code>Bonos Entregados</code></strong></td><td>Cantidad total de bonos entregados a los referentes como recompensa.</td></tr><tr><td><strong><code>Conversión Depósito</code></strong></td><td><p>Porcentaje de referidos registrados que cumplieron la condición de depósito.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Se calcula mediante la siguiente formula:<br><em><strong>Conversión Depósito</strong> = (Referidos Depósito / Referidos) × 100</em></p></div></td></tr><tr><td><strong><code>Promedio Referidos</code></strong></td><td><p>Cantidad promedio de referidos que registra cada referente.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Se calcula mediante la siguiente formula:<br><em><strong>Promedio Referidos</strong> = Referidos / Referentes</em></p></div></td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Los indicadores de referidos toman como referencia la **fecha de registro del referido**, mientras que los indicadores de cumplimiento de condiciones _(depósito y apuesta)_ consideran la **fecha en la que el referido cumplió cada condición**.
{% endhint %}

#### 4.2. Información del dashboard

{% tabs %}
{% tab title="Dashboard" %}
Vista ejecutiva orientada al análisis gerencial y al monitoreo del desempeño del programa.

#### **Visualización**

<figure><img src="../../../.gitbook/assets/image (253).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Dashboard referidos</p></figcaption></figure>

#### **Gráficas**

<table><thead><tr><th width="180">Nombre</th><th width="130">Tipo de gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Evolución Mensual Referidos Registrados</code></strong></td><td>Barras verticales</td><td>Representa la cantidad de referidos registrados en cada mes, agrupados por año, lo que permite identificar la tendencia de captación del programa a lo largo del tiempo.</td></tr><tr><td><strong><code>Top 10 Referente</code></strong></td><td>Barras verticales</td><td>Presenta los diez <a href="https://virtualsoft.gitbook.io/plantillas/glosario#referente">referentes</a> con mayor cantidad de referidos, identificados por su ID, lo que permite reconocer a los usuarios que más aportan a la captación del programa.</td></tr><tr><td><strong><code>Cumplimiento Por Condición</code></strong></td><td>Barras horizontales</td><td>Compara la cantidad de referidos que cumplieron cada etapa o condición del programa <em>(verificación, depósito y apuesta)</em>, facilitando identificar cuál concentra mayor cumplimiento.</td></tr><tr><td><strong><code>Funnel de conversión</code></strong></td><td>Embudo</td><td><p>Representa el avance de los referidos a través de las etapas del programa: <strong>Registrados</strong>, <strong>Verificados</strong>, <strong>Primer depósito</strong> y <strong>Primera apuesta</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Cada etapa muestra cuántos referidos avanzan desde la anterior: del total de registrados, cuántos verifican su cuenta; de los verificados, cuántos realizan su primer depósito; y de estos, cuántos realizan su primera apuesta.</p></div></td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle Referente" %}
Vista operativa que presenta la información individual de cada [referente](https://virtualsoft.gitbook.io/plantillas/glosario#referente), permitiendo consultar su actividad dentro del programa, la cantidad de [referidos](https://virtualsoft.gitbook.io/plantillas/glosario#referido) que ha generado y las recompensas obtenidas.

#### **Visualización**

<figure><img src="../../../.gitbook/assets/image (254).png" alt=""><figcaption><p>Figura #2: Captura de pantalla Detalle referente</p></figcaption></figure>

#### **Tabla de referentes**

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Referente</code></strong></td><td>Identificador único del referente.</td></tr><tr><td><strong><code>Estado del referente</code></strong></td><td>Estado actual del referente <em>(Activo, Inactivo o Bloqueado)</em>.</td></tr><tr><td><strong><code>Fecha de ingreso al programa</code></strong></td><td>Fecha en la que el referente ingresó al programa de referidos.</td></tr><tr><td><strong><code>Cantidad total de referidos</code></strong></td><td>Número total de referidos registrados por el referente.</td></tr><tr><td><strong><code>Cantidad de referidos efectivos</code></strong></td><td>Número de referidos que han generado alguna recompensa al referente.</td></tr><tr><td><strong><code>Última fecha de bono entregado</code></strong></td><td>Fecha del último bono entregado al referente.</td></tr><tr><td><strong><code>Cantidad Bonos entregados</code></strong></td><td><p>Número total de bonos entregados al referente como recompensa.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo presenta únicamente la cantidad. El detalle de cada bono, con su identificador y nombre, se consulta en <a href="dashboard-referidos.md#detalle-premios-entregados">Detalle premios entregados</a>.</p></div></td></tr></tbody></table>

#### **Detalle premios entregados**

Muestra los bonos unicos entregados al referente

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Referente</code></strong></td><td>Identificador único del referente.</td></tr><tr><td><strong><code>ID bono</code></strong></td><td>Identificador único del bono entregado al referente.</td></tr><tr><td><strong><code>Nombre bono</code></strong></td><td>Nombre del bono entregado al referente</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle Referido" %}
Vista que presenta el detalle de los [referidos](https://virtualsoft.gitbook.io/plantillas/glosario#referido) y el cumplimiento de cada una de las condiciones del programa.

#### **Visualización**

<figure><img src="../../../.gitbook/assets/image (255).png" alt=""><figcaption><p>Figura #3: Captura de pantalla Detalle referido</p></figcaption></figure>

#### **¿Cómo se organiza la información?**

Una **condición** es un requisito que el [referido](https://virtualsoft.gitbook.io/plantillas/glosario#referido) debe cumplir para que el referente obtenga su recompensa _(verificación de cuenta, primer depósito o primera apuesta)_.

La tabla muestra **una fila por cada condición** asociada al referido, por lo que un mismo referido puede aparecer en varios registros, cada uno con su fecha de cumplimiento y su estado.

{% hint style="warning" %}
**Notas:**&#x20;

* El premio se entrega una sola vez al referente cuando el referido cumple **todas** las condiciones configuradas. Por esa razón, el **ID y el nombre del premio se repiten en todas las filas del referido**, sin que ello signifique que se haya entregado un premio por cada condición.
* Un referido puede no generar el premio por distintos motivos: porque su depósito fue rechazado, porque no cumplió las condiciones dentro del plazo establecido o porque el referente dejó expirar el bono sin redimirlo.
{% endhint %}

#### **Tabla de** [**referidos**](https://virtualsoft.gitbook.io/plantillas/glosario#referido)

<table><thead><tr><th width="192.5">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Referido</code></strong></td><td>Identificador único del referido.</td></tr><tr><td><strong><code>Fecha de registro</code></strong></td><td>Fecha en la que el referido se registró mediante el link de referido.</td></tr><tr><td><strong><code>Verificación cuenta</code></strong></td><td>Indica si el referido verificó su cuenta.</td></tr><tr><td><strong><code>Estado actual Referido</code></strong></td><td>Condición a la que corresponde el registro <em>(Registrado, Verificado, Depositó o Apostó)</em>.</td></tr><tr><td><strong><code>Fecha cumplimiento Condición</code></strong></td><td>Fecha en la que el referido cumplió la condición correspondiente al registro.</td></tr><tr><td><strong><code>Estado</code></strong></td><td><p>Estado de cumplimiento de la condición:</p><ul><li><strong>Pendiente:</strong> el referido aún no ha cumplido la condición y el plazo continúa vigente.</li><li><strong>Cumplido:</strong> el referido cumplió la condición dentro del plazo establecido.</li><li><strong>Fallido:</strong> el referido no cumplió la condición.</li><li><strong>Condición Expirada:</strong> el plazo para cumplir la condición finalizó sin que el referido la completara.</li><li><strong>Redimido:</strong> el referido cumplió todas las condiciones y el referente redimió el premio generado.</li></ul></td></tr><tr><td><strong><code>Estado Global</code></strong></td><td><p>Estado general del premio generado por el referido:</p><ul><li><strong>Pendiente:</strong> el referido aún no ha completado todas las condiciones, por lo que el premio no ha sido generado.</li><li><strong>Cumplido:</strong> el referido cumplió todas las condiciones y el premio quedó disponible para el referente.</li><li><strong>Fallido:</strong> el referido no completó todas las condiciones, por lo que no se generó premio para el referente.</li><li><strong>Premio Cancelado:</strong> el premio generado fue cancelado, por lo que no puede ser redimido por el referente.</li><li><strong>Premio expirado - Causado por el referente:</strong> el premio expiró sin que el referente lo redimiera dentro del plazo de vigencia.</li><li><strong>Redimido - Causado por el referente:</strong> el referente redimió el premio generado por el referido.</li></ul></td></tr><tr><td><strong><code>ID premio</code></strong></td><td>Identificador único del bono generado como recompensa para el referente.</td></tr><tr><td><strong><code>Nombre recompensa</code></strong></td><td>Nombre del bono generado como recompensa para el referente.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 5. Validaciones y reglas del negocio:

* Todos los indicadores, gráficas y tablas se actualizan automáticamente al aplicar los filtros, sin necesidad de recargar el dashboard.
* Los filtros pueden combinarse entre sí.
* El rango de fechas filtra según la fecha de registro del referido.
* Los indicadores de cumplimiento de condiciones consideran la fecha en la que el referido cumplió cada condición, por lo que sus valores pueden diferir de las cifras basadas en la fecha de registro.
* El dashboard admite múltiples condiciones configurables del programa, no limitadas únicamente a primer depósito y primera apuesta.
* Las exportaciones en Excel, CSV y PDF respetan los filtros activos.
* La información se actualiza de forma automática según la periodicidad definida por BI, como mínimo una vez al día.
* En la vista **Detalle Referido**, cada fila corresponde a una condición del programa, por lo que un mismo referido puede aparecer en varios registros.
* El premio se entrega una sola vez al referente cuando el referido cumple todas las condiciones configuradas, aunque el ID y el nombre del premio se muestren en todas las filas del referido.

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/09/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-30044#icft=VSFT-30044">Documento inicial</a></td></tr></tbody></table>

</details>
