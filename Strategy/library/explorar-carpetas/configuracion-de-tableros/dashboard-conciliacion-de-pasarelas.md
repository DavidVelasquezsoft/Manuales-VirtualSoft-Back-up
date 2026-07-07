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
---

# Dashboard Conciliación de pasarelas

<mark style="color:$info;">Visualizar y analizar la información de</mark> [<mark style="color:$info;">conciliación</mark>](https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion) <mark style="color:$info;">entre VirtualSoft y las pasarelas de pago integradas en el</mark> [<mark style="color:$info;">Data Warehouse</mark>](https://virtualsoft.gitbook.io/plantillas/glosario#data-warehouse)<mark style="color:$info;">, comparando las transacciones registradas en ambas plataformas para identificar coincidencias, inconsistencias y facilitar el seguimiento operativo de las transacciones.</mark>

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Dashboard Conciliación de pasarelas

***

### 2. Configuraciones previas

Antes de visualizar el reporte, es necesario confirmar las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/tableros#id-2.-configuracion-previa).

***

### 3. Acciones disponibles

<table><thead><tr><th width="149.25909423828125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="dashboard-conciliacion-de-pasarelas.md#id-4.-filtros"><strong>Aplicar filtros</strong></a></td><td>Permite filtrar la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</td></tr><tr><td><a href="dashboard-conciliacion-de-pasarelas.md#id-6.-informacion-del-tablero"><strong>Visualizar contenido del tablero</strong></a></td><td><p>Visualiza la información del tablero mediante las siguientes funcionalidades:</p><ul><li>KPIs generales.</li><li>Tablas con información resumida y detallada por partner.</li></ul><p>Permite navegar e interactuar con los diferentes componentes del dashboard, accediendo a distintas vistas y niveles de detalle según las opciones seleccionadas, manteniendo los filtros previamente aplicados.</p></td></tr><tr><td><strong>Exportar contenido</strong></td><td>El dashboard permite exportar su contenido. Para más información, consulte la guía de exportación <a data-mention href="../../#id-4.-exportar-contenido">#id-4.-exportar-contenido</a>.</td></tr></tbody></table>

***

### 4. Filtros&#x20;

Estos son los filtros disponibles en el dashboard, que permiten visualizar la información del tablero según los criterios seleccionados. Cada filtro es dinámico y actualiza la información en tiempo real conforme se aplican nuevas selecciones.

<table><thead><tr><th width="145.2962646484375">Campo</th><th width="155">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el rango de fechas  desde las cuales se muestra la información.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Desplegable</td><td>Selecciona uno o varios partners configurados en el reporte.</td></tr><tr><td><strong><code>País</code></strong></td><td>Desplegable</td><td>Permite seleccionar uno o varios países disponibles en el reporte.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Desplegable</td><td>Filtra la información según el identificador único del usuario el cual realizó la transacción.</td></tr><tr><td><strong><code>Resultado de conciliación</code></strong></td><td>Desplegable</td><td>Filtra las transacciones según el resultado de la <a href="https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion">conciliación</a> entre VirtualSoft y la pasarela de pago (<em>coincide o no coincide</em>).</td></tr><tr><td><strong><code>Pasarela</code></strong></td><td>Desplegable</td><td><p>Permite filtrar las transacciones según la pasarela de pago utilizada. Actualmente, este dashboard incluye información de las siguientes pasarelas:</p><ul><li><strong>PayPhone</strong></li><li><strong>Unlimit</strong></li><li><strong>Safetypay</strong></li></ul><p>Al seleccionar una pasarela, se mostrarán únicamente las transacciones procesadas a través de ella.</p></td></tr><tr><td><strong><code>Detalle de la coincidencia</code></strong></td><td>Desplegable</td><td>Filtra las transacciones según el tipo de inconsistencia detectada durante la <a href="https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion">conciliación</a>, como diferencias de información, fecha/hora o registros existentes únicamente en uno de los sistemas.</td></tr><tr><td><strong><code>Estado Virtual</code></strong></td><td>Desplegable</td><td>Filtra la información según el estado de la transacción registrado en <strong>VirtualSoft</strong>, mostrando únicamente los registros que coincidan con el estado seleccionado.</td></tr><tr><td><strong><code>Estado Proveedor</code></strong></td><td>Desplegable</td><td>Permite filtrar la información según el estado de la transacción reportado por la <strong>pasarela de pago (proveedor)</strong>, mostrando únicamente los registros que correspondan al estado seleccionado.</td></tr></tbody></table>

***

### 5. KPIs generales

Indicadores generales de apuestas deportivas calculados según los filtros aplicados en el dashboard.

{% hint style="warning" %}
**Nota:** Los KPIs se visualizan de la misma manera tanto en la vista resumida como en la vista detallada.
{% endhint %}

<table><thead><tr><th width="194.6666259765625">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total Transacciones procesadas</code></strong></td><td>Cantidad total de transacciones evaluadas en el proceso de <a href="https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion">conciliación</a> según los filtros aplicados.</td></tr><tr><td><strong><code>Total Transacciones conciliadas</code></strong></td><td>Muestra la cantidad de transacciones cuya información coincide correctamente entre VirtualSoft y la pasarela de pago.</td></tr><tr><td><strong><code>Total Transacciones con inconsistencia</code></strong></td><td>Cantidad de transacciones que presentan diferencias o inconsistencias durante el proceso de conciliación.</td></tr><tr><td><strong><code>% Porcentaje de conciliación</code></strong></td><td>Porcentaje de transacciones <a href="https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion">conciliadas</a> correctamente respecto al total de transacciones procesadas. El cálculo se realiza mediante la fórmula: <em>(Transacciones conciliadas / Total de transacciones procesadas) × 100</em>.</td></tr><tr><td><strong><code>Cantidad de transacciones rechazadas</code></strong></td><td>Total de transacciones que fueron rechazadas durante el proceso de conciliación, según los filtros aplicados.</td></tr><tr><td><strong><code>Cantidad de transacciones pendientes</code></strong></td><td>Cantidad de transacciones que se encuentran pendientes de validación o conciliación entre VirtualSoft y la pasarela de pago.</td></tr><tr><td><strong><code>Cantidad de transacciones enviadas</code></strong></td><td>Cantidad total de transacciones enviadas por la plataforma para su procesamiento y conciliación.</td></tr><tr><td><strong><code>Usuarios depositando</code></strong></td><td>Cantidad de usuarios únicos que realizaron al menos un depósito durante el período consultado.</td></tr><tr><td><strong><code>Promedio depósitos aprobados por usuario</code></strong></td><td>Indica el promedio de depósitos aprobados realizados por cada usuario. El cálculo se realiza mediante la fórmula: <em>(Cantidad de transacciones aprobadas / Usuarios depositando)</em>.</td></tr><tr><td><strong><code>Promedio depósitos rechazados por usuario</code></strong></td><td>Promedio de depósitos rechazados por cada usuario que realizó depósitos. El cálculo se realiza mediante la fórmula: <em>(Cantidad de transacciones rechazadas / Usuarios depositando)</em>.</td></tr><tr><td><strong><code>Promedio depósitos pendientes por usuario</code></strong></td><td>Indica el promedio de depósitos que permanecen pendientes por cada usuario que realizó depósitos. El cálculo se realiza mediante la fórmula: <em>(Cantidad de transacciones pendientes / Usuarios depositando)</em>.</td></tr><tr><td><strong><code>Promedio depósitos enviados por usuario</code></strong></td><td>Promedio de depósitos enviados por cada usuario que realizó transacciones. El cálculo se realiza mediante la fórmula: <em>(Cantidad de transacciones enviadas / Usuarios depositando)</em>.</td></tr></tbody></table>

***

### 6. **Información del tablero**

Permite visualizar y analizar la información de [conciliación](https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion) entre VirtualSoft y las pasarelas de pago, identificando transacciones coincidentes e inconsistencias mediante vistas resumidas y detalladas según los filtros seleccionados. El dashboard cuenta con 2 vistas, las cuales pueden seleccionarse desde la parte superior derecha:

{% tabs %}
{% tab title="Resumida" %}
Visualiza un resumen general de las [conciliaciones](https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion) agrupadas por pasarela, partner y país, mostrando transacciones conciliadas, con inconsistencias y sus valores asociados.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (192).png" alt=""><figcaption><p>Figura #1: Captura de pantalla vista resumida.</p></figcaption></figure>

#### Tabla de información resumida

Visualizar las [conciliaciones](https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion) de manera resumida según los filtros seleccionados, agrupando la información por pasarela, partner y país. Además, permite alternar los valores monetarios entre moneda original y USD mediante el selector de moneda ubicado en la parte superior.&#x20;

<table><thead><tr><th width="184.92596435546875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner al que corresponden las transacciones mostradas en la fila.</td></tr><tr><td><strong><code>País</code></strong></td><td>País al que corresponden las transacciones mostradas en la fila.</td></tr><tr><td><strong><code>Pasarela</code></strong></td><td>Nombre de la pasarela de pago a la que corresponden las transacciones mostradas en la fila.</td></tr><tr><td><strong><code>Transacciones procesadas</code></strong></td><td>Cantidad total de transacciones evaluadas en el proceso de conciliación para la pasarela, partner y país correspondientes.</td></tr><tr><td><strong><code>Transacciones conciliadas</code></strong></td><td>Cantidad de transacciones conciliadas correctamente para la pasarela, partner y país correspondientes.</td></tr><tr><td><strong><code>Transacciones con inconsistencia</code></strong></td><td>Cantidad de transacciones que presentan inconsistencias para la pasarela, partner y país correspondientes.</td></tr><tr><td><strong><code>Valor conciliadas</code></strong></td><td>Suma total de los valores monetarios de las transacciones conciliadas para la pasarela, partner y país correspondientes.</td></tr><tr><td><strong><code>Valor inconsistencia</code></strong></td><td>Suma total de los valores monetarios de las transacciones con inconsistencias para la pasarela, partner y país correspondientes.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle" %}
Permite visualizar el detalle de las transacciones [conciliadas](https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion) e inconsistencias registradas entre VirtualSoft y las pasarelas de pago, mostrando la información específica de cada transacción según los filtros seleccionados.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (194).png" alt=""><figcaption><p>Figura #2: Captura de pantalla vista resumida.</p></figcaption></figure>

#### Tabla de información detallada

Visualiza el detalle de las transacciones [conciliadas](https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion) e inconsistencias según los filtros seleccionados, mostrando la información específica de cada transacción registrada entre VirtualSoft y las pasarelas de pago. Además, permite alternar los valores monetarios entre moneda original y USD mediante el selector de moneda ubicado en la parte superior.

<table><thead><tr><th width="241.59259033203125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se realizó el proceso de conciliación de la transacción.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner asociado a la transacción.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado a la transacción.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador único del usuario relacionado con la transacción.</td></tr><tr><td><strong><code>Pasarela</code></strong></td><td>Nombre de la pasarela de pago asociada a la transacción.</td></tr><tr><td><strong><code>Estado VirtualSoft</code></strong></td><td>Estado registrado en VirtualSoft para la transacción.</td></tr><tr><td><strong><code>Estado proveedor</code></strong></td><td>Estado registrado por la pasarela de pago para la transacción.</td></tr><tr><td><strong><code>Resultado de conciliación</code></strong></td><td>Resultado del proceso de conciliación de la transacción (<em>coincide o no coincide</em>).</td></tr><tr><td><strong><code>Detalle de la inconsistencia</code></strong></td><td>Describe el tipo de inconsistencia detectada durante la conciliación cuando la transacción presenta diferencias.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 7. Reglas y validaciones

* Solo los perfiles autorizados podrán acceder al tablero.
* La información del dashboard se actualiza a día vencido, según la última carga disponible en el Data Warehouse.
* El dashboard permite consultar información histórica de conciliaciones según el rango de fechas seleccionado y la disponibilidad de datos en el Data Warehouse.
* Una transacción se considera conciliada cuando existe tanto en VirtualSoft como en la pasarela de pago y la información relacionada coincide correctamente según las reglas de validación del sistema.
* Para que una transacción pueda conciliase correctamente, debe existir tanto en VirtualSoft como en la pasarela de pago y encontrarse dentro del mismo rango de fecha correspondiente al día conciliado.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="101.3704833984375">Versión</th><th width="133.25927734375">Fecha</th><th width="161.77777099609375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>17/09/2025</td><td>David velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>19/11/2025</td><td>Ronald Peláez</td><td>Refinamiento de manual.</td></tr><tr><td>2.0</td><td>15/05/2026</td><td>David velasquez</td><td>Reestructuración del manual e incorporación de nuevas secciones</td></tr><tr><td>2.1</td><td>01/06/2026</td><td>Karol Navia</td><td>Agregar pasarela "<strong><code>Unlimit</code></strong>"</td></tr><tr><td>2.2</td><td>24/06/2025</td><td>Karol Navia</td><td>Reestructuracion del manual</td></tr></tbody></table>

</details>
