# Dashboard Referidos

<mark style="color:$info;">Consolida la información del programa de referidos, permitiendo hacer seguimiento a su desempeño, medir la captación y conversión de los referidos y monitorear el cumplimiento de las condiciones que generan recompensas a los referentes. Ofrece una vista ejecutiva con indicadores y gráficas, y vistas detalladas por referente y por referido.</mark>

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Dashboard Referidos

***

### 2. Configuraciones previas

Antes de visualizar el reporte, es necesario confirmar las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/tableros#id-2.-configuracion-previa).

***

### 3. Acciones disponibles

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Aplicar filtros</strong></td><td>Permite filtrar la información según los criterios disponibles en el panel de filtros. Todos los indicadores, gráficas y tablas se actualizan automáticamente al aplicarlos, y los filtros pueden combinarse entre sí.</td></tr><tr><td><strong>Visualizar contenido del tablero</strong></td><td><p>Utiliza las herramientas del dashboard, tales como:</p><ul><li>Filtros dinámicos.</li><li>KPIs generales.</li><li>Gráficas de barras y embudo de conversión.</li><li>Tablas con el detalle por referente y por referido.</li></ul><p>Permite navegar entre las vistas del dashboard, manteniendo los filtros previamente aplicados.</p></td></tr><tr><td><strong>Exportar contenido</strong></td><td>El dashboard permite exportar su contenido en formatos Excel, CSV y PDF, respetando los filtros activos. Para más información, consulte la guía de exportación  <a data-mention href="./#id-3.-exportar-contenido">#id-3.-exportar-contenido</a>.</td></tr></tbody></table>

***

### 4. Filtros

Ubicados en el **Panel de filtros** a la izquierda de la pantalla, permiten visualizar la información del tablero según los criterios seleccionados.

<table><thead><tr><th width="160">Campo</th><th width="130">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra la información por partner.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Segmenta la información según el país.</td></tr><tr><td><strong><code>Desde / Hasta</code></strong></td><td>Rango de fechas</td><td><p>Define el periodo de análisis.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El rango de fechas filtra según la <strong>fecha de registro del referido</strong>.</p></div></td></tr><tr><td><strong><code>Id Referente</code></strong></td><td>Numérico</td><td>Permite consultar la información de un referente específico por su identificador.</td></tr><tr><td><strong><code>ID Referido</code></strong></td><td>Numérico</td><td>Permite consultar la información de un referido específico por su identificador.</td></tr><tr><td><strong><code>Tipo Condición</code></strong></td><td>Lista desplegable</td><td>Filtra según el tipo de condición del programa <em>(condición de depósito, condición de primera apuesta u otras configuradas)</em>.</td></tr><tr><td><strong><code>Estado Global</code></strong></td><td>Lista desplegable</td><td>Filtra según el estado actual del referido <em>(Registrado, Verificado, Depositó o Apostó)</em>.</td></tr><tr><td><strong><code>Estado Condición</code></strong></td><td>Lista desplegable</td><td>Filtra según el estado de la condición <em>(Pendiente, Cumplida o Vencida)</em>.</td></tr><tr><td><strong><code>Estado Bono</code></strong></td><td>Lista desplegable</td><td>Filtra según el estado del bono o recompensa <em>(Pendiente, Disponible, Redimida o Vencida)</em>.</td></tr></tbody></table>

***

### 5. KPIs generales

En la parte superior del dashboard se muestran los indicadores clave del programa de referidos según los filtros aplicados.

<table><thead><tr><th width="200">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Referentes</code></strong></td><td>Cantidad de referentes únicos, es decir, usuarios que invitaron a otros a registrarse en la plataforma.</td></tr><tr><td><strong><code>Referidos</code></strong></td><td>Cantidad de referidos únicos registrados mediante un link de referido.</td></tr><tr><td><strong><code>Referidos Depósito</code></strong></td><td>Cantidad de referidos que cumplieron la condición de depósito.</td></tr><tr><td><strong><code>Referidos Apuesta</code></strong></td><td>Cantidad de referidos que cumplieron la condición de apuesta.</td></tr><tr><td><strong><code>Bonos Entregados</code></strong></td><td>Cantidad total de bonos entregados a los referentes como recompensa.</td></tr><tr><td><strong><code>Conversión Depósito</code></strong></td><td><p>Porcentaje de referidos registrados que cumplieron la condición de depósito.</p><p><strong>Fórmula:</strong><br><em>Conversión Depósito = (Referidos Depósito / Referidos) × 100</em></p></td></tr><tr><td><strong><code>Promedio Referidos</code></strong></td><td><p>Cantidad promedio de referidos que registra cada referente.</p><p><strong>Fórmula:</strong><br><em>Promedio Referidos = Referidos / Referentes</em></p></td></tr></tbody></table>

{% hint style="info" %}
Los indicadores de referidos toman como referencia la **fecha de registro del referido**, mientras que los indicadores de cumplimiento de condiciones _(depósito y apuesta)_ consideran la **fecha en la que el referido cumplió cada condición**.
{% endhint %}

***

### 6. Visualización de información

El dashboard se organiza en tres vistas que se seleccionan desde las pestañas ubicadas debajo de los KPIs. Cada vista ofrece un nivel distinto de análisis, desde el resumen ejecutivo hasta el detalle de cada referido.

{% tabs %}
{% tab title="Dashboard" %}
Vista ejecutiva orientada al análisis gerencial y al monitoreo del desempeño del programa.

**Visualización**

**Gráficas**

<table><thead><tr><th width="180">Nombre</th><th width="130">Tipo de gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Evolución Mensual Referidos Registrados</code></strong></td><td>Barras verticales</td><td>Representa la cantidad de referidos registrados en cada mes, agrupados por año, lo que permite identificar la tendencia de captación del programa a lo largo del tiempo.</td></tr><tr><td><strong><code>Top 10 Referente</code></strong></td><td>Barras verticales</td><td>Presenta los diez referentes con mayor cantidad de referidos, identificados por su ID, lo que permite reconocer a los usuarios que más aportan a la captación del programa.</td></tr><tr><td><strong><code>Cumplimiento Por Condición</code></strong></td><td>Barras horizontales</td><td>Compara la cantidad de referidos que cumplieron cada etapa o condición del programa <em>(verificación, depósito y apuesta)</em>, facilitando identificar cuál concentra mayor cumplimiento.</td></tr><tr><td><strong><code>Funnel de conversión</code></strong></td><td>Embudo</td><td><p>Representa el avance de los referidos a través de las etapas del programa: <strong>Registrados</strong>, <strong>Verificados</strong>, <strong>Primer depósito</strong> y <strong>Primera apuesta</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p>Cada etapa muestra cuántos referidos avanzan desde la anterior: del total de registrados, cuántos verifican su cuenta; de los verificados, cuántos realizan su primer depósito; y de estos, cuántos realizan su primera apuesta.</p></div></td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle Referente" %}
Vista operativa orientada a la trazabilidad individual de cada referente. Presenta dos tablas ordenables, con paginación y búsqueda rápida.

**Visualización**

**Tabla de referentes**

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Referente</code></strong></td><td>Identificador único del referente.</td></tr><tr><td><strong><code>Fecha de ingreso al programa</code></strong></td><td>Fecha en la que el referente ingresó al programa de referidos.</td></tr><tr><td><strong><code>Cantidad total de referidos</code></strong></td><td>Número total de referidos registrados por el referente.</td></tr><tr><td><strong><code>Cantidad de referidos efectivos</code></strong></td><td>Número de referidos que han generado alguna recompensa al referente.</td></tr><tr><td><strong><code>Última fecha de bono entregado</code></strong></td><td>Fecha del último bono entregado al referente.</td></tr><tr><td><strong><code>ID Bono</code></strong></td><td>Identificador del bono seleccionado por el referente.</td></tr><tr><td><strong><code>Estado del referente</code></strong></td><td>Estado actual del referente <em>(Activo, Inactivo o Bloqueado)</em>.</td></tr></tbody></table>

**Tabla de condiciones**

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de condición</code></strong></td><td>Condición del programa asociada <em>(por ejemplo: primer depósito o primera apuesta)</em>.</td></tr><tr><td><strong><code>Fecha de cumplimiento</code></strong></td><td>Fecha en la que se cumplió la condición.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado de la condición <em>(Pendiente, Cumplida o Vencida)</em>.</td></tr><tr><td><strong><code>Bono asociado</code></strong></td><td>Bono que se entrega al referente al cumplirse la condición.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle Referido" %}
Vista que presenta el detalle de los referidos, con información no sensible, en una tabla ordenable, con paginación y búsqueda rápida.

**Visualización**

**Tabla de referidos**

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Referido</code></strong></td><td>Identificador único del referido.</td></tr><tr><td><strong><code>Fecha de registro</code></strong></td><td>Fecha en la que el referido se registró mediante el link de referido.</td></tr><tr><td><strong><code>Estado de verificación</code></strong></td><td>Indica si el referido verificó su cuenta.</td></tr><tr><td><strong><code>Fecha condición depósito</code></strong></td><td>Fecha en la que el referido cumplió la condición de depósito.</td></tr><tr><td><strong><code>Fecha condición apuesta</code></strong></td><td>Fecha en la que el referido cumplió la condición de apuesta.</td></tr><tr><td><strong><code>Estado actual</code></strong></td><td>Etapa en la que se encuentra el referido <em>(Registrado, Verificado, Depositó o Apostó)</em>.</td></tr><tr><td><strong><code>Recompensas generadas</code></strong></td><td>Recompensas que el referido ha generado al referente.</td></tr><tr><td><strong><code>Estado de la recompensa</code></strong></td><td>Estado de la recompensa generada <em>(Pendiente, Disponible, Redimida o Vencida)</em>.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 7. Validaciones y reglas del negocio:

* Todos los indicadores, gráficas y tablas se actualizan automáticamente al aplicar los filtros, sin necesidad de recargar el dashboard.
* Los filtros pueden combinarse entre sí.
* El rango de fechas filtra según la fecha de registro del referido.
* Los indicadores de cumplimiento de condiciones consideran la fecha en la que el referido cumplió cada condición, por lo que sus valores pueden diferir de las cifras basadas en la fecha de registro.
* El dashboard admite múltiples condiciones configurables del programa, no limitadas únicamente a primer depósito y primera apuesta.
* Las exportaciones en Excel, CSV y PDF respetan los filtros activos.
* La información se actualiza de forma automática según la periodicidad definida por BI, como mínimo una vez al día.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>dd/mm/aaaa</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
