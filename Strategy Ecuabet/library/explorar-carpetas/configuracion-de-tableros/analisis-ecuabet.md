# Análisis Ecuabet

<mark style="color:$info;">Muestra el comportamiento de los depósitos, los retiros, los usuarios y las comisiones de los puntos de venta de Ecuabet, con su distribución por punto de venta y por día de la semana. La información se organiza en tres pestañas: PDV</mark> <mark style="color:$info;"></mark>_<mark style="color:$info;">(punto de venta)</mark>_<mark style="color:$info;">, Promocionales y Comisiones.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Análisis Ecuabet

***

### 2. Configuraciones previas

Antes de ingresar al tablero, es necesario completar los parámetros solicitados en las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-1.-configuraciones-previas).

***

### 3. Acciones disponibles

<table><thead><tr><th width="230">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="analisis-ecuabet.md#id-4.-filtros"><strong>Aplicar filtros</strong></a></td><td>Acota la información del tablero según los criterios del panel de filtros.</td></tr><tr><td><a href="analisis-ecuabet.md#id-6.-contenido-del-dashboard"><strong>Visualizar contenido del tablero</strong></a></td><td>Muestra los indicadores, gráficos y tablas del tablero, organizados en las pestañas PDV, Promocionales y Comisiones.</td></tr><tr><td><strong>Exportar contenido</strong></td><td>Descarga un componente o el tablero completo. El procedimiento se describe en la guía de <a href="https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-3.-exportar-contenido">exportación</a>.</td></tr></tbody></table>

***

### 4. Filtros

Los filtros se ubican en el panel de filtros, en el costado izquierdo del tablero, y se aplican a todos los indicadores, gráficos y tablas.

<table><thead><tr><th width="177.5">Filtro</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Calendario</td><td>Delimita el periodo de consulta según la fecha de creación de las transacciones, mediante los campos <strong>Desde</strong> y <strong>Hasta</strong>.</td></tr><tr><td><strong><code>Año</code></strong></td><td>Lista desplegable</td><td>Restringe la información al año seleccionado.</td></tr><tr><td><strong><code>Mes</code></strong></td><td>Lista desplegable</td><td>Acota la información al mes seleccionado.</td></tr><tr><td><strong><code>Día</code></strong></td><td>Lista desplegable</td><td>Muestra la información de un día específico.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Cuadro de búsqueda</td><td>Localiza las transacciones y comisiones de un usuario a partir de su identificador único.</td></tr><tr><td><strong><code>Pasarela de Pago</code></strong></td><td>Lista desplegable</td><td><p>Selecciona el <a href="https://virtualsoft.gitbook.io/untitled/glosario#punto-de-venta">punto de venta</a> en el que se realizaron las transacciones.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Aunque el nombre del filtro menciona la pasarela de pago, sus opciones corresponden a los puntos de venta.</p></div></td></tr><tr><td><strong><code>Tipo de Comisión</code></strong></td><td>Lista desplegable</td><td>Reúne las comisiones del concepto seleccionado. Los conceptos disponibles se describen en la tabla <strong>Totales</strong> de la pestaña Comisiones.</td></tr></tbody></table>

***

### 5. KPIs

Indicadores generales ubicados en la parte superior del tablero.

{% hint style="warning" %}
**Nota:** En el tablero, los términos **recarga** y **depósito** se usan como sinónimos.
{% endhint %}

<table><thead><tr><th width="228.33331298828125">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total Depósitos</code></strong></td><td><p>Muestra el valor total de los depósitos del periodo consultado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El tablero incluye únicamente depósitos aprobados.</p></div></td></tr><tr><td><strong><code>Total Retiros</code></strong></td><td>Muestra el valor total de los retiros del periodo consultado.</td></tr><tr><td><strong><code>Coincidencia TRX (%)</code></strong></td><td>Muestra la proporción de los retiros respecto a los depósitos, expresada en porcentaje.</td></tr><tr><td><strong><code>Cantidad de Usuarios que Recargan</code></strong></td><td>Indica la cantidad de usuarios que realizaron al menos un depósito en el periodo.</td></tr><tr><td><strong><code>Cantidad de Usuarios que Retiran</code></strong></td><td>Indica la cantidad de usuarios que realizaron al menos un retiro en el periodo.</td></tr><tr><td><strong><code>Monto de Comisiones</code></strong></td><td>Muestra el valor total de las comisiones generadas en el periodo, de todos los tipos de comisión.</td></tr><tr><td><strong><code>Cantidad de Depósitos</code></strong></td><td>Cuenta los depósitos realizados en el periodo.</td></tr><tr><td><strong><code>Cantidad de Retiros</code></strong></td><td>Cuenta los retiros realizados en el periodo.</td></tr><tr><td><strong><code>Ticket Promedio de Depósitos</code></strong></td><td><p>Muestra el valor promedio de cada depósito.</p><p><strong>Fórmula:</strong><br><em>Ticket Promedio de Depósitos = Total Depósitos ÷ Cantidad de Depósitos</em></p></td></tr><tr><td><strong><code>Ticket Promedio de Retiros</code></strong></td><td><p>Muestra el valor promedio de cada retiro.</p><p><strong>Fórmula:</strong><br><em>Ticket Promedio de Retiros = Total Retiros ÷ Cantidad de Retiros</em></p></td></tr></tbody></table>

***

### 6. Contenido del dashboard

El tablero se organiza en tres pestañas, ubicadas en la barra superior: PDV, Promocionales y Comisiones.

{% tabs %}
{% tab title="PDV" %}
Presenta el comportamiento diario de los depósitos, los retiros y los usuarios, con tablas de detalle por mes, por punto de venta y por usuario.

**Visualización**

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FwkRYf3SmzUV3Fd3xTey3%2Fimage.png?alt=media&#x26;token=f437799e-f5d6-4b65-a676-cf346fdba5c9" alt=""><figcaption><p>Figura #1: Captura de pantalla pestaña PDV.</p></figcaption></figure>

El contenido se organiza en tres subpestañas, ubicadas en la parte superior derecha: Competencia, Evolución y Detalle.

{% tabs %}
{% tab title="Competencia" %}
Compara el comportamiento diario de los depósitos y los retiros.

<table><thead><tr><th width="213.33331298828125">Gráfico</th><th width="116.5">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Comparativo diario Depósitos vs Retiros</code></strong></td><td>Gráfico de líneas</td><td>Compara, día a día, el valor de los depósitos frente al de los retiros.</td></tr><tr><td><strong><code>Comportamiento diario de Depósitos</code></strong></td><td>Gráfico de líneas</td><td>Muestra el valor de los depósitos de cada día del periodo consultado.</td></tr><tr><td><strong><code>Comportamiento diario de Retiros</code></strong></td><td>Gráfico de líneas</td><td>Muestra el valor de los retiros de cada día del periodo consultado.</td></tr></tbody></table>
{% endtab %}

{% tab title="Evolución" %}
Presenta la evolución de los usuarios y la participación diaria de los depósitos y los retiros.

<table><thead><tr><th width="215.83331298828125">Gráfico</th><th width="116.8333740234375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Evolución temporal de usuarios que recargan</code></strong></td><td>Gráfico de líneas</td><td>Presenta la cantidad de usuarios que realizaron depósitos a lo largo del periodo.</td></tr><tr><td><strong><code>Evolución temporal de usuarios que retiran</code></strong></td><td>Gráfico de líneas</td><td>Presenta la cantidad de usuarios que realizaron retiros a lo largo del periodo.</td></tr><tr><td><strong><code>Participación de valor Depósitos por día</code></strong></td><td>Gráfico de líneas</td><td>Indica el porcentaje que representa cada día en el valor total de los depósitos del periodo.</td></tr><tr><td><strong><code>Participación de valor Retiros por día</code></strong></td><td>Gráfico de líneas</td><td>Indica el porcentaje que representa cada día en el valor total de los retiros del periodo.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle" %}
Reúne las tablas de detalle por mes, por punto de venta, por día y por usuario.

**Resumen por Mes:** consolida los depósitos, los retiros y los usuarios de cada mes.

<table><thead><tr><th width="210">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mes</code></strong></td><td>Identifica el mes al que corresponden los valores.</td></tr><tr><td><strong><code>Monto Depósitos</code></strong></td><td>Muestra el valor total de los depósitos del mes.</td></tr><tr><td><strong><code>Monto Retiros</code></strong></td><td>Muestra el valor total de los retiros del mes.</td></tr><tr><td><strong><code>Coincidencia TRX</code></strong></td><td>Indica la proporción de los retiros respecto a los depósitos del mes, expresada en porcentaje.</td></tr><tr><td><strong><code>Cantidad de Depósitos</code></strong></td><td>Cuenta los depósitos realizados en el mes.</td></tr><tr><td><strong><code>Cantidad de Retiros</code></strong></td><td>Cuenta los retiros realizados en el mes.</td></tr><tr><td><strong><code>Cantidad de Usuarios</code></strong></td><td>Indica la cantidad de usuarios con transacciones en el mes.</td></tr></tbody></table>

**Resumen por Pasarela:** agrupa las transacciones por punto de venta.

<table><thead><tr><th width="210">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>pasarela de pago</code></strong></td><td><p>Identifica el punto de venta.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Aunque el nombre de la columna menciona la pasarela de pago, muestra el nombre del punto de venta.</p></div></td></tr><tr><td><strong><code>Depósitos</code></strong></td><td>Cuenta los depósitos realizados en el punto de venta.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Cuenta los retiros realizados en el punto de venta.</td></tr><tr><td><strong><code>Total Transacciones</code></strong></td><td><p>Suma los depósitos y los retiros del punto de venta.</p><p><strong>Fórmula:</strong><br><em>Total Transacciones = Depósitos + Retiros</em></p></td></tr><tr><td><strong><code>Cantidad de Usuarios</code></strong></td><td>Indica la cantidad de usuarios que realizaron transacciones en el punto de venta.</td></tr></tbody></table>

**Detalle Diario de Depósitos:** muestra los depósitos de cada día del periodo consultado.

<table><thead><tr><th width="137.5">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Día</code></strong></td><td>Identifica el día al que corresponden los valores.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Muestra el valor total de los depósitos del día.</td></tr><tr><td><strong><code>Usuarios</code></strong></td><td>Indica la cantidad de usuarios que realizaron depósitos en el día.</td></tr><tr><td><strong><code>Recargas</code></strong></td><td><p>Cuenta los depósitos realizados en el día.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Nota:</strong> Un usuario puede realizar varias recargas en un mismo día, por lo que <strong><code>Recargas</code></strong> puede ser mayor que <strong><code>Usuarios</code></strong>.</p></div></td></tr></tbody></table>

**Ranking de Usuarios por Depósitos:** ordena a los usuarios de mayor a menor valor depositado.

<table><thead><tr><th width="210">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Identifica al usuario.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Muestra el valor total depositado por el usuario en el periodo.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td><p>Calcula la comisión correspondiente al 3 % del valor depositado.</p><p><strong>Fórmula:</strong><br><em>Comisión = Monto × 3 %</em></p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Nota:</strong> Esta comisión se calcula en el tablero sobre el monto depositado. El KPI <strong><code>Monto de Comisiones</code></strong> y la pestaña Comisiones toman sus valores de los registros de comisiones del BackOffice.</p></div></td></tr><tr><td><strong><code>Recargas</code></strong></td><td>Cuenta los depósitos realizados por el usuario en el periodo.</td></tr></tbody></table>

**Detalle Diario de Retiros:** muestra los retiros de cada día del periodo consultado.

<table><thead><tr><th width="210">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Día</code></strong></td><td>Identifica el día al que corresponden los valores.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Muestra el valor total de los retiros del día.</td></tr><tr><td><strong><code>Usuarios</code></strong></td><td>Indica la cantidad de usuarios que realizaron retiros en el día.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Cuenta los retiros realizados en el día.</td></tr></tbody></table>

**Ranking de Usuarios por Retiros:** ordena a los usuarios de mayor a menor valor retirado.

<table><thead><tr><th width="210">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Identifica al usuario.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Muestra el valor total retirado por el usuario en el periodo.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td><p>Calcula la comisión correspondiente al 1 % del valor retirado.</p><p><strong>Fórmula:</strong><br><em>Comisión = Monto × 1 %</em></p></td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Cuenta los retiros realizados por el usuario en el periodo.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Promocionales" %}
Agrupa los depósitos, los retiros y los usuarios por día de la semana, lo que permite identificar los días de mayor actividad.

{% hint style="warning" %}
**Nota:** Cada día de la semana acumula los valores de todas las semanas del periodo consultado. Por ejemplo, **Lunes** suma los valores de todos los lunes del rango de fechas.
{% endhint %}

**Visualización**

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FFmZWUlby425VGaZ83qf7%2Fimage.png?alt=media&#x26;token=dc3bda24-add6-4b62-988b-b700f885e830" alt=""><figcaption><p>Figura #2: Captura de pantalla pestaña Promocionales.</p></figcaption></figure>

El contenido se organiza en dos subpestañas, ubicadas en la parte superior derecha: Comparativo y Detalle.

{% tabs %}
{% tab title="Comparativo" %}
Compara los depósitos, los retiros, las transacciones y los usuarios de cada día de la semana.

<table><thead><tr><th width="220.8333740234375">Gráfico</th><th width="114.0001220703125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Recargas por día de la semana</code></strong></td><td>Gráfico de barras</td><td>Muestra el valor de los depósitos de cada día de la semana.</td></tr><tr><td><strong><code>Retiros por día de la semana</code></strong></td><td>Gráfico de barras</td><td>Muestra el valor de los retiros de cada día de la semana.</td></tr><tr><td><strong><code>Distribución de transacciones por día de la semana</code></strong></td><td>Gráfico de líneas</td><td>Presenta la cantidad de transacciones de cada día de la semana.</td></tr><tr><td><strong><code>Participación porcentual de usuarios por día de la semana</code></strong></td><td>Gráfico de torta</td><td>Indica el porcentaje que representan los usuarios de cada día de la semana en el total de usuarios.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle" %}
Consolida los valores de cada día de la semana.

<table><thead><tr><th width="230">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Día de la semana</code></strong></td><td>Identifica el día de la semana al que corresponden los valores.</td></tr><tr><td><strong><code>Monto Recargas</code></strong></td><td>Muestra el valor total de los depósitos del día de la semana.</td></tr><tr><td><strong><code>Monto Retiros</code></strong></td><td>Muestra el valor total de los retiros del día de la semana.</td></tr><tr><td><strong><code>Cantidad de Usuarios</code></strong></td><td>Indica la cantidad de usuarios con transacciones en el día de la semana.</td></tr><tr><td><strong><code>Cantidad de Transacciones</code></strong></td><td>Cuenta los depósitos y retiros realizados en el día de la semana.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Comisiones" %}
Muestra la evolución mensual de las comisiones y su composición por tipo de comisión.

**Visualización**

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2F2QCLLEko4Fa9HMxrT9wR%2Fimage.png?alt=media&#x26;token=57a175b6-2659-4761-9067-773b992c0876" alt=""><figcaption><p>Figura #3: Captura de pantalla pestaña Comisiones.</p></figcaption></figure>

El contenido se organiza en dos subpestañas, ubicadas en la parte superior derecha: Comparativo y Detalle.

{% tabs %}
{% tab title="Comparativo" %}
Muestra la tendencia mensual de las comisiones, su distribución por tipo y los totales por concepto.

<table><thead><tr><th width="216.66668701171875">Gráfico</th><th width="126.666748046875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tendencia mensual</code></strong></td><td>Gráfico de líneas</td><td>Muestra el valor total de las comisiones de cada mes, para comparar cómo varían a lo largo del periodo consultado.</td></tr><tr><td><strong><code>Distribución de comisiones por tipo</code></strong></td><td>Gráfico de torta</td><td>Muestra el porcentaje que representa cada tipo de comisión sobre el total de comisiones del periodo consultado.</td></tr></tbody></table>

**Totales:** resume el valor acumulado de cada tipo de comisión en el periodo consultado.

<table><thead><tr><th width="260">Concepto</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total General de Comisiones</code></strong></td><td><p>Suma las comisiones de todos los conceptos que se listan a continuación.</p><p><strong>Fórmula:</strong><br><em>Total General de Comisiones = Suma de las comisiones de todos los conceptos</em></p></td></tr><tr><td><strong><code>Comisiones de Depósitos Punto de Venta</code></strong></td><td>Suma las comisiones generadas por los depósitos realizados en puntos de venta.</td></tr><tr><td><strong><code>Comisiones de Notas de Retiro Punto de Venta</code></strong></td><td>Suma las comisiones generadas por el pago de notas de retiro en puntos de venta <em>(documento con el que el usuario cobra un retiro en un punto de venta)</em>.</td></tr><tr><td><strong><code>Comisiones Sportbook GGR Punto de venta IP</code></strong></td><td>Suma las comisiones de los puntos de venta IP calculadas sobre el <a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">GGR</a> de las apuestas deportivas <em>(valor apostado menos premios pagados)</em>.</td></tr><tr><td><strong><code>Comisiones Sportbook GGR Afiliados</code></strong></td><td>Suma las comisiones de los afiliados calculadas sobre el <a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">GGR</a> de las apuestas deportivas <em>(valor apostado menos premios pagados)</em>.</td></tr><tr><td><strong><code>Comisiones Sportbook NGR Afiliados</code></strong></td><td>Suma las comisiones de los afiliados calculadas sobre el NGR de las apuestas deportivas <em>(GGR descontando el valor de los bonos otorgados)</em>.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle" %}
Reúne el resumen mensual y el detalle de las comisiones por usuario.

**Resumen de Comisiones por Mes:** consolida el valor de las comisiones de cada mes por tipo de comisión.

<table><thead><tr><th width="210">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mes</code></strong></td><td>Identifica el mes al que corresponden los valores.</td></tr><tr><td><strong><code>Tipo de Comisión</code></strong></td><td>Indica el concepto que genera la comisión. Los conceptos se describen en la tabla <strong>Totales</strong> de la subpestaña Comparativo.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Muestra el valor de las comisiones del mes para el tipo de comisión.</td></tr></tbody></table>

**Detalle de Comisiones:** detalla las comisiones por mes, tipo de comisión y usuario.

<table><thead><tr><th width="210">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mes</code></strong></td><td>Identifica el mes al que corresponden los valores.</td></tr><tr><td><strong><code>Tipo de Comisión</code></strong></td><td>Indica el concepto que genera la comisión.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identifica al usuario al que corresponde la comisión.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Muestra el valor de la comisión.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}

***

### 7. Validaciones y reglas del negocio:

* El tablero incluye únicamente depósitos aprobados.
* La comisión de los rankings de usuarios corresponde al 3 % del valor depositado y al 1 % del valor retirado.
* Los filtros se aplican de forma consistente a todos los indicadores, gráficos y tablas del tablero.
* Los filtros de fecha permiten consultar periodos anteriores y compararlos sin alterar el cálculo de los indicadores.
* El tablero consolida la información de todos los puntos de venta de Ecuabet. El filtro **`Nombre del Sistema de Pasarela de Pago`** permite consultar un punto de venta específico.
* La información del tablero coincide con los siguientes reportes del BackOffice:
  * Depósitos _(solo los aprobados)_: [Reporte de depósitos punto venta](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/reportes/reporte-de-depositos-punto-venta).
  * Retiros: [Reporte de Retiros](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/reportes/reporte-de-retiros).
  * Comisiones: [Reporte de comisiones](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/reportes/reporte-de-comisiones).

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>20/11/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33132">Documento inicial.</a></td></tr></tbody></table>

</details>
