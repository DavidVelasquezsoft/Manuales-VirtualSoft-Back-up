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

# Dashboard Conciliación de pasarelas

<mark style="color:$info;">Visualiza y analiza la información de</mark> [<mark style="color:$info;">conciliación</mark>](https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion) <mark style="color:$info;">entre VirtualSoft y las pasarelas de pago integradas en el</mark> [<mark style="color:$info;">Data Warehouse</mark>](https://virtualsoft.gitbook.io/plantillas/glosario#data-warehouse)<mark style="color:$info;">, comparando las transacciones registradas en ambas plataformas para identificar coincidencias, inconsistencias y facilitar el seguimiento operativo de las transacciones.</mark>

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Dashboard Conciliación de pasarelas

***

### 2. Configuraciones previas

Antes de visualizar el reporte, es necesario confirmar las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/tableros#id-2.-configuracion-previa).

***

### 3. Acciones disponibles

<table><thead><tr><th width="149.25909423828125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="dashboard-conciliacion-de-pasarelas.md#id-4.-filtros"><strong>Aplicar filtros</strong></a></td><td>Permite filtrar la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</td></tr><tr><td><a href="dashboard-conciliacion-de-pasarelas.md#id-6.-informacion-del-tablero"><strong>Visualizar contenido del tablero</strong></a></td><td><p>Visualiza la información del tablero mediante las siguientes funcionalidades:</p><ul><li>KPIs generales.</li><li>Tablas con información resumida y detallada por partner.</li></ul><p>Permite navegar e interactuar con los diferentes componentes del dashboard, accediendo a distintas vistas y niveles de detalle según las opciones seleccionadas, manteniendo los filtros previamente aplicados.</p></td></tr><tr><td><strong>Exportar contenido</strong></td><td>El dashboard permite exportar su contenido. Para más información, consulte la guía de exportación <a data-mention href="../../#id-4.-exportar-contenido">#id-4.-exportar-contenido</a>.</td></tr></tbody></table>

***

### 4. Filtros

Estos son los filtros disponibles en el dashboard, que permiten visualizar la información del tablero según los criterios seleccionados. Cada filtro es dinámico y actualiza la información en tiempo real conforme se aplican nuevas selecciones.

<table><thead><tr><th width="166.66668701171875">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Delimita el periodo de la información consultada mediante los campos <strong>Desde</strong> y <strong>Hasta</strong>.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Selecciona uno o varios partners.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Acota los resultados a uno o varios países.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Campo de texto</td><td>Busca las transacciones de un usuario por su identificador único.</td></tr><tr><td><strong><code>Estado de conciliación</code></strong></td><td>Lista desplegable</td><td>Filtra las transacciones según el resultado de la <a href="https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion">conciliación</a> <em>(Coincide o No coincide)</em>.</td></tr><tr><td><strong><code>Pasarela</code></strong></td><td>Lista desplegable</td><td><p>Restringe la información a la pasarela de pago seleccionada. Las pasarelas disponibles son:</p><ul><li><strong>PayPhone</strong></li><li><strong>Unlimit</strong></li><li><strong>PagoEfectivo</strong></li><li><strong>Payvalida</strong></li><li><strong>Safetypay</strong></li><li><strong>EUKAPAY</strong> <em>(pagos con criptomonedas)</em></li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> EUKAPAY está disponible para Camanbet – Venezuela, Paniplay – Honduras, Doradobet – Honduras, Ecuador y El Salvador, y GanaPlay – El Salvador y Guatemala.</p></div></td></tr><tr><td><strong><code>Detalle de la inconsistencia</code></strong></td><td>Lista desplegable</td><td>Muestra las transacciones según el tipo de inconsistencia detectada en la <a href="https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion">conciliación</a>.</td></tr><tr><td><strong><code>Estado Virtual</code></strong></td><td>Lista desplegable</td><td>Separa las transacciones según el estado registrado en VirtualSoft.</td></tr><tr><td><strong><code>Estado Proveedor</code></strong></td><td>Lista desplegable</td><td><p>Consulta las transacciones según el estado reportado por la pasarela de pago. Cada pasarela informa sus estados con sus propios nombres, los disponibles son:</p><ul><li><strong>Approved</strong> / <strong>Aprobada:</strong> la pasarela aprobó el pago.</li><li><strong>Captured:</strong> la pasarela confirmó el cobro del dinero después de autorizar el pago.</li><li><strong>Chargeback:</strong> el titular del medio de pago reclamó el cobro ante su banco y el pago fue reversado <em>(contracargo)</em>.</li><li><strong>Chargeback resolved:</strong> el reclamo del contracargo fue resuelto.</li></ul></td></tr></tbody></table>

***

### 5. KPIs generales

Indicadores generales de [conciliación](https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion), calculados según los filtros aplicados en el dashboard.

{% hint style="warning" %}
**Nota:** Los KPIs se visualizan de la misma manera tanto en la vista resumida como en la vista detallada.
{% endhint %}

<table><thead><tr><th width="230">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total transacciones procesadas</code></strong></td><td>Cantidad de transacciones evaluadas en el proceso de conciliación.</td></tr><tr><td><strong><code>Total transacciones conciliadas</code></strong></td><td>Cantidad de transacciones cuya información coincide entre VirtualSoft y la pasarela de pago.</td></tr><tr><td><strong><code>Total transacciones con inconsistencia</code></strong></td><td>Cantidad de transacciones que presentan alguna diferencia entre VirtualSoft y la pasarela de pago.</td></tr><tr><td><strong><code>% Porcentaje de conciliación</code></strong></td><td><p>Porcentaje de transacciones conciliadas respecto al total de transacciones procesadas.</p><p><strong>Fórmula:</strong><br><em>(Total transacciones conciliadas / Total transacciones procesadas) × 100</em></p></td></tr><tr><td><strong><code>Cantidad de transacciones aprobadas</code></strong></td><td>Cantidad de transacciones en estado <strong>Aprobado</strong>. Solo estas transacciones se evalúan como conciliadas o con inconsistencia.</td></tr><tr><td><strong><code>Cantidad de transacciones rechazadas</code></strong></td><td>Cantidad de transacciones en estado <strong>Rechazado</strong>. No se cuentan como inconsistencias.</td></tr><tr><td><strong><code>Cantidad de transacciones pendientes</code></strong></td><td>Cantidad de transacciones en estado <strong>Pendiente</strong>. No se cuentan como inconsistencias.</td></tr><tr><td><strong><code>Cantidad de transacciones enviadas</code></strong></td><td>Cantidad de transacciones en estado <strong>Enviado</strong>. No se cuentan como inconsistencias.</td></tr><tr><td><strong><code>Usuarios depositando</code></strong></td><td>Cantidad de usuarios únicos que realizaron al menos una solicitud de depósito en el periodo consultado.</td></tr><tr><td><strong><code>Promedio depósitos aprobados por usuario</code></strong></td><td><p>Promedio de depósitos aprobados por cada usuario que depositó.</p><p><strong>Fórmula:</strong><br><em>Cantidad de transacciones aprobadas / Usuarios depositando</em></p></td></tr><tr><td><strong><code>Promedio depósitos rechazados por usuario</code></strong></td><td><p>Promedio de depósitos rechazados por cada usuario que depositó.</p><p><strong>Fórmula:</strong><br><em>Cantidad de transacciones rechazadas / Usuarios depositando</em></p></td></tr><tr><td><strong><code>Promedio depósitos pendientes por usuario</code></strong></td><td><p>Promedio de depósitos pendientes por cada usuario que depositó.</p><p><strong>Fórmula:</strong><br><em>Cantidad de transacciones pendientes / Usuarios depositando</em></p></td></tr><tr><td><strong><code>Promedio depósitos enviados por usuario</code></strong></td><td><p>Promedio de depósitos enviados por cada usuario que depositó.</p><p><strong>Fórmula:</strong><br><em>Cantidad de transacciones enviadas / Usuarios depositando</em></p></td></tr></tbody></table>

***

### 6. **Información del tablero**

Permite visualizar y analizar la información de [conciliación](https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion) entre VirtualSoft y las pasarelas de pago, identificando transacciones coincidentes e inconsistencias mediante vistas resumidas y detalladas según los filtros seleccionados. El dashboard cuenta con 2 vistas, las cuales pueden seleccionarse desde la parte superior derecha:

{% tabs %}
{% tab title="Resumida" %}
Visualiza un resumen general de las [conciliaciones](https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion) agrupadas por pasarela, partner y país, mostrando transacciones conciliadas, con inconsistencias y sus valores asociados.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (203) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla vista resumida.</p></figcaption></figure>

#### Tabla de información resumida

Visualizar las [conciliaciones](https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion) de manera resumida según los filtros seleccionados, agrupando la información por pasarela, partner y país. Además, permite alternar los valores monetarios entre moneda original y USD mediante el selector de moneda ubicado en la parte superior.

<table><thead><tr><th width="184.92596435546875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner al que corresponden las transacciones mostradas en la fila.</td></tr><tr><td><strong><code>País</code></strong></td><td>País al que corresponden las transacciones mostradas en la fila.</td></tr><tr><td><strong><code>Pasarela</code></strong></td><td>Nombre de la pasarela de pago a la que corresponden las transacciones mostradas en la fila.</td></tr><tr><td><strong><code>Transacciones procesadas</code></strong></td><td>Cantidad total de transacciones evaluadas en el proceso de conciliación para la pasarela, partner y país correspondientes.</td></tr><tr><td><strong><code>Transacciones conciliadas</code></strong></td><td>Cantidad de transacciones conciliadas correctamente para la pasarela, partner y país correspondientes.</td></tr><tr><td><strong><code>Transacciones con inconsistencia</code></strong></td><td>Cantidad de transacciones que presentan inconsistencias para la pasarela, partner y país correspondientes.</td></tr><tr><td><strong><code>Valor conciliadas</code></strong></td><td>Suma total de los valores monetarios de las transacciones conciliadas para la pasarela, partner y país correspondientes.</td></tr><tr><td><strong><code>Valor inconsistencia</code></strong></td><td>Suma total de los valores monetarios de las transacciones con inconsistencias para la pasarela, partner y país correspondientes.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle" %}
Permite visualizar el detalle de las transacciones [conciliadas](https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion) e inconsistencias registradas entre VirtualSoft y las pasarelas de pago, mostrando la información específica de cada transacción según los filtros seleccionados.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (285).png" alt=""><figcaption><p>Figura #2: Captura de pantalla vista detallada.</p></figcaption></figure>

#### Tabla de información detallada

Visualiza el detalle de las transacciones [conciliadas](https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#conciliacion) e inconsistencias según los filtros seleccionados, mostrando la información específica de cada transacción registrada entre VirtualSoft y las pasarelas de pago. Además, permite alternar los valores monetarios entre moneda original y USD mediante el selector de moneda ubicado en la parte superior.

<table><thead><tr><th width="230">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha conciliación</code></strong></td><td>Indica la fecha del proceso de conciliación en el que se evaluó la transacción.</td></tr><tr><td><strong><code>Fecha Transacción Virtual</code></strong></td><td>Registra la fecha y hora de la transacción en VirtualSoft.</td></tr><tr><td><strong><code>Fecha Transacción Proveedor</code></strong></td><td><p>Registra la fecha y hora de la transacción en la pasarela de pago.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Se lee junto con <strong><code>Fecha Transacción Virtual</code></strong>. Si ambas fechas no corresponden al mismo día conciliado, la transacción se marca con diferencia de fecha/hora.</p></div></td></tr><tr><td><strong><code>Partner</code></strong></td><td>Identifica el partner asociado a la transacción.</td></tr><tr><td><strong><code>País</code></strong></td><td>Muestra el país asociado a la transacción.</td></tr><tr><td><strong><code>Pasarela</code></strong></td><td>Presenta la pasarela de pago que procesó la transacción.</td></tr><tr><td><strong><code>ID Solicitud Deposito</code></strong></td><td>Contiene el identificador de la solicitud de depósito en VirtualSoft.</td></tr><tr><td><strong><code>External ID</code></strong></td><td>Corresponde al identificador único que genera la pasarela de pago para rastrear la transacción y relacionarla con el registro de VirtualSoft.</td></tr><tr><td><strong><code>ID Transacción proveedor</code></strong></td><td>Indica el identificador que asigna la pasarela de pago a la transacción.</td></tr><tr><td><strong><code>Estado Transacción Virtual</code></strong></td><td>Muestra el estado de la transacción en VirtualSoft <em>(Aprobado, Rechazado, Pendiente o Enviado)</em>.</td></tr><tr><td><strong><code>Estado Transacción Proveedor</code></strong></td><td><p>Presenta el estado de la transacción tal como lo reporta la pasarela de pago, las opciones disponibles son:</p><ul><li><strong>Approved</strong> / <strong>Aprobada:</strong> la pasarela aprobó el pago.</li><li><strong>Captured:</strong> la pasarela confirmó el cobro del dinero después de autorizar el pago.</li><li><strong>Chargeback:</strong> el titular del medio de pago reclamó el cobro ante su banco y el pago fue reversado <em>(contracargo)</em>.</li><li><strong>Chargeback resolved:</strong> el reclamo del contracargo fue resuelto.</li></ul></td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identifica al usuario que realizó la transacción.</td></tr><tr><td><strong><code>Estado de conciliación</code></strong></td><td>Señala el resultado de la conciliación de la transacción <em>(Coincide o No coincide)</em>.</td></tr><tr><td><strong><code>Valor Virtual</code></strong></td><td>Muestra el valor de la transacción registrado en VirtualSoft, en la moneda elegida en el selector de moneda.</td></tr><tr><td><strong><code>Valor Proveedor</code></strong></td><td>Presenta el valor de la transacción reportado por la pasarela de pago, en la moneda elegida en el selector de moneda.</td></tr><tr><td><strong><code>Diferencia valor</code></strong></td><td><p>Indica la diferencia entre <strong><code>Valor Virtual</code></strong> y <strong><code>Valor Proveedor</code></strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Un valor distinto de cero indica una diferencia de monto entre VirtualSoft y la pasarela de pago.</p></div></td></tr><tr><td><strong><code>Detalle de la inconsistencia</code></strong></td><td>Describe el tipo de inconsistencia detectada cuando la transacción no coincide <em>(Ejemplo: diferencia de monto)</em>.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 7. Validaciones y reglas del negocio:

* Solo los perfiles autorizados pueden acceder al tablero.
* La información se actualiza a día vencido, según la última carga disponible en el Data Warehouse. La fecha y hora de la última actualización se muestra en la parte superior del tablero.
* El tablero permite consultar información histórica según el rango de fechas seleccionado y la disponibilidad de datos en el Data Warehouse.
* Solo las transacciones en estado **Aprobado** se evalúan como conciliadas o con inconsistencia. Las transacciones en estado **Rechazado**, **Pendiente** o **Enviado** no se cuentan como inconsistencias.
* Una transacción se considera conciliada cuando existe en VirtualSoft y en la pasarela de pago, dentro del mismo día conciliado, y su información coincide.
* El proceso identifica los siguientes tipos de inconsistencia: existe en VirtualSoft pero no en la pasarela, existe en la pasarela pero no en VirtualSoft, diferencia de monto, diferencia de estado y diferencia de fecha/hora.
* Los valores monetarios se pueden ver en moneda original o en USD. La conversión a USD usa la TRM definida por el área financiera.
* Los conteos se muestran como números enteros y los promedios con máximo dos decimales. Si no hay datos para un indicador, se muestra **0**.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="101.3704833984375">Versión</th><th width="133.25927734375">Fecha</th><th width="161.77777099609375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>17/09/2025</td><td>David velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>19/11/2025</td><td>Ronald Peláez</td><td>Refinamiento de manual.</td></tr><tr><td>2.0</td><td>15/05/2026</td><td>David velasquez</td><td>Reestructuración del manual e incorporación de nuevas secciones</td></tr><tr><td>2.1</td><td>01/06/2026</td><td>Karol Navia</td><td>Agregar pasarela "<strong><code>Unlimit</code></strong>"</td></tr><tr><td>2.2</td><td>24/06/2026</td><td>Karol Navia</td><td>Reestructuracion del manual</td></tr><tr><td>2.3</td><td>14/07/2026</td><td>David Velasquez</td><td>Agregar pasarela "<strong><code>PagoEfectivo</code></strong>"</td></tr><tr><td>2.4</td><td>24/11/026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-35151">Agregar pasarela "<strong><code>EUKAPAY</code></strong>" y corrección de filtros, KPIs y validaciones.</a></td></tr></tbody></table>

</details>
