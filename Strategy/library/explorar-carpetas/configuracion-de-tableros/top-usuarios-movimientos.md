# Top usuarios movimientos

<mark style="color:$info;">Consolida los usuarios con mayor actividad, volumen transaccional y rentabilidad en los productos de Casino y Apuestas Deportivas. Presenta rankings dinámicos que facilitan la segmentación de clientes, la ejecución de campañas de CRM, la definición de estrategias de fidelización y el seguimiento de usuarios de alto valor.</mark>

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Top Usuarios Movimientos

***

### 2. Configuraciones previas

Antes de visualizar el reporte, es necesario confirmar las [configuraciones previas](./#id-1.-configuraciones-previas).

***

### 3. Visualización

<figure><img src="../../../.gitbook/assets/image (228).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Dashboard top usuarios movimientos</p></figcaption></figure>

***

### 4. Acciones disponibles

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="top-usuarios-movimientos.md#id-4.-filtros"><strong>Aplicar filtros</strong></a></td><td>Filtra la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</td></tr><tr><td><a href="top-usuarios-movimientos.md#id-5.-visualizacion-de-informacion"><strong>Visualizar contenido del tablero</strong></a></td><td><p>Utiliza las herramientas del dashboard, tales como:</p><ul><li>Filtros dinámicos.</li><li>Tablas de rankings por indicador.</li></ul><p>Permite navegar e interactuar con los diferentes rankings del dashboard, manteniendo los filtros previamente aplicados.</p></td></tr><tr><td><strong>Exportar contenido</strong></td><td>El dashboard permite exportar su contenido. Para más información, consulte la guía de exportación <a data-mention href="./#id-3.-exportar-contenido">#id-3.-exportar-contenido</a>.</td></tr></tbody></table>

***

### 5. Filtros

Permiten visualizar la información del tablero según los criterios seleccionados. La información presentada corresponde al periodo y a los criterios definidos en estos filtros.

{% hint style="warning" %}
**Nota:** Estos filtros complementan las configuraciones previas y solo permiten refinar la búsqueda dentro del rango previamente definido.
{% endhint %}

<table><thead><tr><th width="151.3333740234375">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite delimitar el periodo de análisis indicando una fecha de inicio y una fecha de fin.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra por aliado o marca sobre el cual se desea analizar la información.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Segmenta la información según el país al que pertenece el usuario.</td></tr><tr><td><strong><code>Categorización de usuario</code></strong></td><td>Lista desplegable</td><td>Filtra los usuarios según su <a href="top-usuarios-movimientos.md#categorizacion-vip-del-usuario">categoría VIP</a> dentro de la plataforma <em>(Masa, Potencial, Bronce, Plata, Oro o Diamante)</em>.</td></tr></tbody></table>

***

### 6. Visualización de información

El dashboard presenta rankings que identifican a los usuarios con mayor actividad en cada indicador, ordenados de forma descendente según el valor analizado. Los rankings se agrupan en dos bloques: **Casino** y **Apuestas Deportivas**.

Todas las tablas comparten la misma estructura de columnas:

{% hint style="warning" %}
**Nota:** Cada tabla muestra los **10 primeros usuarios** del ranking. Sin embargo, cuando existen usuarios empatados con el mismo valor en la última posición, el tablero muestra a todos los usuarios en esa condición, por lo que el listado puede contener más de 10 registros.
{% endhint %}

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Posición</code></strong></td><td>Ubicación del usuario dentro del ranking, según el valor del indicador analizado.</td></tr><tr><td><strong><code>ID de Usuario</code></strong></td><td>Identificador único del usuario dentro de la plataforma.</td></tr><tr><td><strong><code>Categorización</code></strong></td><td>Categoría VIP asignada al usuario dentro de la plataforma, útil para los procesos de segmentación, retención y fidelización. Los niveles disponibles se detallan en <a data-mention href="top-usuarios-movimientos.md#categorizacion-vip-del-usuario">#categorizacion-vip-del-usuario</a>.</td></tr><tr><td><strong><code>Valor del indicador</code></strong></td><td>Monto correspondiente al indicador analizado en cada ranking durante el periodo consultado.</td></tr></tbody></table>

<details>

<summary>🔽 Categorización VIP del usuario</summary>

Un **usuario VIP** es un jugador seleccionado por el equipo de gestión VIP según su actividad y permanencia en la plataforma para acceder a beneficios exclusivos. La categoría se asigna y actualiza según su comportamiento.

La categorización corresponde al **nivel VIP** asignado al usuario, identificado en el tablero mediante un valor numérico según la siguiente equivalencia:

<table><thead><tr><th width="109.16668701171875">Valor</th><th width="127.5">Categoría</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>0</strong> <em>(o sin valor)</em></td><td><strong>Masa</strong></td><td>Usuario sin categoría VIP asignada. Corresponde al nivel base de la plataforma.</td></tr><tr><td><strong>1</strong></td><td><strong>Potencial</strong></td><td>Usuario identificado como candidato a ingresar al programa VIP.</td></tr><tr><td><strong>2</strong></td><td><strong>Bronce</strong></td><td>Primer nivel del programa VIP.</td></tr><tr><td><strong>3</strong></td><td><strong>Plata</strong></td><td>Segundo nivel del programa VIP.</td></tr><tr><td><strong>4</strong></td><td><strong>Oro</strong></td><td>Tercer nivel del programa VIP.</td></tr><tr><td><strong>5</strong></td><td><strong>Diamante</strong></td><td>Nivel más alto del programa VIP, con los mayores beneficios.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Cuando el usuario no tiene una categoría asignada, el campo se muestra con el valor **0** o vacío, lo que corresponde a la categoría **Masa**. A medida que el equipo de gestión VIP actualiza la categoría de un usuario, el valor reflejado en el tablero cambia al nivel correspondiente.
{% endhint %}

</details>

#### 6.1. Casino

<table><thead><tr><th width="226.66668701171875">Ranking</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Top 10 usuarios por Depósito Aprobado</code></strong></td><td>Ordena a los usuarios según el valor total de sus depósitos aprobados, permitiendo identificar quiénes aportan mayor volumen de ingreso.</td></tr><tr><td><strong><code>Top 10 usuarios por Apuesta Casino</code></strong></td><td>Clasifica a los usuarios según el valor total apostado en juegos de casino, reflejando su nivel de actividad en el producto.</td></tr><tr><td><strong><code>Top 10 usuarios por GGR Casino Positivo</code></strong></td><td>Muestra los usuarios que generaron mayor <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">ingreso bruto</a> para la operación en casino, es decir, aquellos cuyas apuestas superaron los premios obtenidos.</td></tr><tr><td><strong><code>Top 10 usuarios por GGR Casino Negativo</code></strong></td><td>Presenta a los usuarios con <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">ingreso bruto</a> negativo en casino, es decir, aquellos cuyos premios superaron el valor apostado.</td></tr><tr><td><strong><code>Top 10 usuarios por Retiro Creado</code></strong></td><td>Ordena a los usuarios según el valor total de los retiros solicitados durante el periodo consultado.</td></tr><tr><td><strong><code>Top 10 usuarios por Retiro Pagado</code></strong></td><td>Ordena a los usuarios según el valor total de los retiros efectivamente pagados durante el periodo consultado.</td></tr></tbody></table>

#### 6.2. Apuestas Deportivas

<table><thead><tr><th width="215.83331298828125">Ranking</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Top 10 usuarios por Apuesta Deportiva Cerrada</code></strong></td><td>Clasifica a los usuarios según el valor total de sus apuestas deportivas ya resueltas, reflejando su nivel de actividad en el producto.</td></tr><tr><td><strong><code>Top 10 usuarios por GGR Deportiva Positivo</code></strong></td><td>Muestra los usuarios que generaron mayor <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">ingreso bruto</a> para la operación en apuestas deportivas, es decir, aquellos cuyas apuestas superaron los premios obtenidos.</td></tr><tr><td><strong><code>Top 10 usuarios por GGR Deportiva Negativo</code></strong></td><td>Presenta a los usuarios con <a href="https://virtualsoft.gitbook.io/plantillas/glosario#ggr">ingreso bruto</a> negativo en apuestas deportivas, es decir, aquellos cuyos premios superaron el valor apostado.</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* La información presentada corresponde al periodo y a los criterios definidos en los filtros aplicados.
* Los rankings se ordenan de forma descendente según el valor del indicador analizado.
* Cada tabla muestra los 10 primeros usuarios; cuando existen empates en la última posición, se muestran todos los usuarios con ese mismo valor, por lo que el listado puede superar los 10 registros.
* Los indicadores de [GGR](https://virtualsoft.gitbook.io/plantillas/glosario#ggr) se presentan en rankings independientes para diferenciar los usuarios con resultados positivos y negativos.
* La información se actualiza conforme a la periodicidad establecida para las fuentes de datos de CRM.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>13/08/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-32431">Documento inicial</a></td></tr></tbody></table>

</details>
