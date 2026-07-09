# Dashboard Historial de Movimiento usuario

<mark style="color:$info;">Permite analizar en detalle los movimientos financieros asociados a los usuarios y puntos de venta, clasificándolos en entradas</mark> <mark style="color:$info;"></mark>_<mark style="color:$info;">(por ejemplo: depósitos, premios, bonos)</mark>_<mark style="color:$info;">, salidas</mark> <mark style="color:$info;"></mark>_<mark style="color:$info;">(por ejemplo: apuestas, retiros)</mark>_ <mark style="color:$info;"></mark><mark style="color:$info;">y cancelaciones. Ofrece visibilidad del comportamiento transaccional y visualizaciones que facilitan identificar tendencias y validar inconsistencias reportadas por los equipos de negocio e incidentes.</mark>

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Historial de Movimiento usuario

***

### 2. Configuraciones previas

Antes de visualizar el reporte, es necesario confirmar las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/tableros#id-2.-configuracion-previa) obligatorias.

{% hint style="danger" %}
**Notas importantes:**&#x20;

* Los filtros son obligatorios para la correcta ejecución del tablero. Al basarse en un alto volumen de datos transaccionales, si no se aplican los filtros adecuados el tablero puede presentar problemas de carga o rendimiento.
* Para marcas de alto volumen como **Ecuabet**, es obligatorio filtrar por un **Id Usuario** específico. Esto evita tiempos de carga elevados o fallos en la visualización, y garantiza un análisis eficiente y enfocado.
{% endhint %}

Aparte, también cuenta con el siguiente parámetro de búsqueda:

<table><thead><tr><th width="142">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Usuario</code></strong></td><td>Configura los parámetros indicando el identificador único del usuario o punto de venta del cual se mostrarán los movimientos, para garantizar un análisis eficiente y enfocado.</td></tr></tbody></table>

***

### 3. Acciones disponibles

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="dashboard-historial-de-movimiento-usuario.md#id-4.-filtros"><strong>Aplicar filtros</strong></a></td><td><p>Permite filtrar la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Estos filtros funcionan dentro de los filtros principales de configuraciones  previas.</p></div></td></tr><tr><td><a href="dashboard-historial-de-movimiento-usuario.md#id-6.-tabla-matriz-movimientos-y-valores"><strong>Visualizar contenido del tablero</strong></a></td><td><p>Utiliza las herramientas del dashboard, tales como:</p><ul><li>Filtros dinámicos.</li><li>KPIs generales.</li><li>Gráficas de barras.</li><li>Matriz con el detalle de los movimientos.</li></ul><p>Permite navegar e interactuar con los diferentes contenidos del dashboard, manteniendo los filtros previamente aplicados.</p></td></tr><tr><td><strong>Exportar contenido</strong></td><td>El dashboard permite exportar su contenido. Para más información, consulte la guía de exportación <a data-mention href="./#id-3.-exportar-contenido">#id-3.-exportar-contenido</a>.</td></tr></tbody></table>

***

### 4. Filtros

Permiten visualizar la información del tablero según los criterios seleccionados. Su uso es obligatorio para garantizar un rendimiento y un análisis adecuados.

{% hint style="warning" %}
**Nota:** Estos filtros dependen de los filtros de configuraciones previas y solo permiten acotar la búsqueda a un rango más específico dentro del que se definió en dichas configuraciones.
{% endhint %}

<table><thead><tr><th width="125.5">Campo</th><th width="127.83331298828125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha Calendario</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar un rango o una fecha específica de análisis.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra por aliado o marca <em>(por ejemplo: Doradobet, Ganaplay, etc.)</em>.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Segmenta la información según el país desde el cual se registró el movimiento del usuario o punto de venta.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Numérico</td><td>Permite consultar el detalle de los movimientos de un usuario o punto de venta específico por su identificador único.</td></tr><tr><td><strong><code>Movimiento</code></strong></td><td>Lista desplegable</td><td>Filtra por el tipo de movimiento realizado por el usuario o punto de venta. Los disponibles son: <br><a href="dashboard-historial-de-movimiento-usuario.md#tipos-de-movimientos" class="button secondary">Ver tipos de Movimientos</a></td></tr></tbody></table>

{% hint style="info" %}
**Buenas prácticas:** combinar varios filtros (_por ejemplo, un rango de fechas acotado junto con un Partner o un Id Usuario_) mejora el rendimiento del tablero y agiliza el análisis, especialmente en marcas con alto volumen de movimientos.
{% endhint %}

***

### 6. **Tabla Matriz Movimientos y Valores**

Presenta el detalle de los movimientos según los filtros aplicados. Cada fila corresponde a un movimiento agrupado por partner, país y tipo de un usuario o punto de venta, sirviendo como base para el análisis y la validación de inconsistencias.

{% hint style="warning" %}
**Nota:** En la primera fila de la matriz se muestran los totales de los valores numéricos, es decir, la suma de los campos **`Valor Movimiento`**, **`Saldo Recarga`** y **`Saldo Retiro`**.
{% endhint %}

<table><thead><tr><th width="176.66668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Aliado o marca al que corresponde el movimiento.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al usuario o punto de venta que realizó el movimiento.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador único del usuario o punto de venta en la plataforma.</td></tr><tr><td><strong><code>Perfil usuario</code></strong></td><td>Tipo de perfil del usuario en el sistema. (<em>ejemplo: Punto de venta, Usuario, etc...</em>)</td></tr><tr><td><strong><code>Tipo Movimiento</code></strong></td><td>Clasificación del movimiento según su naturaleza <em>(Entrada, Salida o Cancelación)</em>.</td></tr><tr><td><strong><code>Movimiento</code></strong></td><td>Tipo específico de movimiento realizado por el usuario o punto de venta. Los disponibles son:<br><a href="dashboard-historial-de-movimiento-usuario.md#tipos-de-movimientos" class="button secondary">Ver tipos de Movimientos</a></td></tr><tr><td><strong><code>Fecha creación Movimiento</code></strong></td><td>Indica la fecha y hora exacta en la cual se registró el movimiento en el sistema.</td></tr><tr><td><strong><code>Valor Movimiento</code></strong></td><td>Valor del movimiento registrado.</td></tr><tr><td><strong><code>Saldo Recarga</code></strong></td><td><a href="https://virtualsoft.gitbook.io/plantillas/glosario#saldo-recarga">Saldo de recarga</a> con el que quedó el usuario o punto de venta después de realizar el movimiento.</td></tr><tr><td><strong><code>Saldo Retiro</code></strong></td><td><a href="https://virtualsoft.gitbook.io/plantillas/glosario#saldo-retiro">Saldo de retiro</a> con el que quedó el usuario después de realizar el movimiento.</td></tr></tbody></table>

{% hint style="info" %}
**Sobre el consumo de saldo:** el usuario siempre consume primero su **saldo recarga**; una vez agotado o cuando este no alcanza a cubrir el movimiento, se comienza a consumir el **saldo retiro**. Esto explica cómo se reflejan ambos saldos tras cada movimiento.
{% endhint %}

<details>

<summary>🔽 Tipos de Movimientos</summary>

Los movimientos disponibles por un usuario o punto de venta son:

<table><thead><tr><th width="161.6666259765625">Movimiento</th><th width="135">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Apuesta Casino</code></strong></td><td>Salida</td><td>Registra una jugada del usuario en el casino. Al realizarla se descuenta de su saldo el valor apostado.</td></tr><tr><td><strong><code>Apuesta Deportiva</code></strong></td><td>Salida</td><td>Registra una apuesta del usuario sobre un evento deportivo. Al realizarla se descuenta de su saldo el valor apostado.</td></tr><tr><td><strong><code>Aumento de Cupo</code></strong></td><td>Entrada / Salida</td><td>Ajuste sobre el cupo o saldo disponible. Es una <strong>entrada</strong> cuando se incrementa el cupo del usuario o punto de venta, y una <strong>salida</strong> cuando ese cupo se reduce o se traslada.</td></tr><tr><td><strong><code>Bono Redimido</code></strong></td><td>Entrada</td><td>Bono o promoción que el usuario hace efectivo. El valor del bono se abona a su saldo.</td></tr><tr><td><strong><code>Cancelación Casino</code></strong></td><td>Cancelación</td><td>Anula o revierte una operación de casino registrada previamente, dejando sin efecto el movimiento original.</td></tr><tr><td><strong><code>Cancelación Deportiva</code></strong></td><td>Cancelación</td><td>Anula o revierte una operación de apuesta deportiva registrada previamente, dejando sin efecto el movimiento original.</td></tr><tr><td><strong><code>Depósito</code></strong></td><td>Entrada / Salida</td><td>Recarga de fondos. Es una <strong>entrada</strong> para el usuario, ya que aumenta su saldo, y una <strong>salida</strong> para el punto de venta cuando realiza depósitos a otros usuarios.</td></tr><tr><td><strong><code>evolución de una apuesta deportiva parcial</code></strong></td><td>Entrada</td><td>Reintegro de una parte del valor de una apuesta deportiva. Ocurre cuando una porción de la apuesta no se concreta o queda sin efecto, por lo que ese monto regresa al saldo del usuario.</td></tr><tr><td><strong><code>Entrada</code></strong></td><td>Entrada</td><td>Movimiento general que aumenta el saldo del usuario o punto de venta y no corresponde a una categoría específica.</td></tr><tr><td><strong><code>Nota de Retiro Creada</code></strong></td><td>Salida</td><td>Solicitud de retiro generada por el usuario. Reserva el monto solicitado, descontándolo temporalmente de su saldo hasta que el retiro se procese.</td></tr><tr><td><strong><code>Nota de Retiro Eliminada</code></strong></td><td>Entrada</td><td>Anulación de una solicitud de retiro previamente creada. El monto que había sido reservado regresa al saldo del usuario.</td></tr><tr><td><strong><code>Premio Casino</code></strong></td><td>Entrada</td><td>Ganancia que obtiene el usuario en juegos de casino. El valor del premio se abona a su saldo.</td></tr><tr><td><strong><code>Premio Deportivo</code></strong></td><td>Entrada</td><td>Ganancia que obtiene el usuario en apuestas deportivas. El valor del premio se abona a su saldo.</td></tr><tr><td><strong><code>Salida</code></strong></td><td>Salida</td><td>Movimiento general que disminuye el saldo del usuario o punto de venta y no corresponde a una categoría específica.</td></tr></tbody></table>

<p align="center"><a href="dashboard-historial-de-movimiento-usuario.md#id-6.-tabla-matriz-movimientos-y-valores" class="button secondary" data-icon="backward-fast">Volver</a></p>

</details>

***

### 7. Graficas

Las gráficas resumen visualmente el comportamiento de los movimientos según los filtros aplicados, facilitando la identificación de tendencias y la comparación entre categorías.

<table><thead><tr><th width="175">Nombre</th><th width="105">Tipo de gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por movimiento</code></strong></td><td>Barras Vertical</td><td>Representa el valor total agrupado por cada tipo de movimiento, permitiendo comparar rápidamente qué movimientos concentran mayor valor dentro del periodo consultado.</td></tr><tr><td><strong><code>Valor por tipo de movimiento</code></strong></td><td>Barras Horizontal</td><td>Agrupa el valor de los movimientos según su clasificación <em>(Entrada, Salida y Cancelación)</em>, ofreciendo una lectura consolidada del balance entre lo que ingresa, lo que sale y lo que se cancela.</td></tr></tbody></table>

***

### 8. Validaciones y reglas del negocio:

* Los filtros son obligatorios para la correcta ejecución del tablero.
* Al basarse en un alto volumen de datos transaccionales, la ausencia de filtros adecuados puede ocasionar problemas de carga o rendimiento.
* Para marcas de alto volumen como Ecuabet, es obligatorio filtrar por un Id Usuario específico.
* Los filtros del tablero dependen de los definidos en las configuraciones previas y solo permiten acotar dentro de ese rango.
* Los movimientos se clasifican en Entrada, Salida y Cancelación.
* El usuario consume primero el saldo recarga y, una vez agotado, el saldo retiro.
* Combinar filtros mejora el rendimiento y la precisión del análisis.

***

### 9. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="94.7037353515625">Versión</th><th width="133.25927734375">Fecha</th><th width="161.77777099609375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>08/07/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
