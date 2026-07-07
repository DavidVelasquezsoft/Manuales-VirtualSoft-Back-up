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

# Dashboard Depósitos NTC

<mark style="color:$info;">El Dashboard de Depósitos NTC permite consultar y analizar la información relacionada con los depósitos realizados, las comisiones generadas, las comisiones potenciales y depósitos sin comisión</mark> <mark style="color:$info;"></mark>_<mark style="color:$info;">(NTC).</mark>_

### 1. Acceso al Módulo

**Ruta de Acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Dashboard Depositos NTC

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (165).png" alt=""><figcaption></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="196">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="dashboard-depositos-ntc.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Permite segmentar la información del dashboard según fechas, concesionario, subconcesionario, punto de venta, jugador y tipo de depósito.</td></tr><tr><td><a href="dashboard-depositos-ntc.md#vista-detallada"><strong>Vista Detallada</strong></a></td><td>Visualiza el detalle individual de cada depósito realizado.</td></tr><tr><td><a href="dashboard-depositos-ntc.md#vista-resumida"><strong>Vista Resumida</strong></a></td><td>Permite visualizar la información agrupada jerárquicamente y consolidada por niveles operativos.</td></tr><tr><td><strong>Exportar</strong></td><td>Exporta la información del dashboard en formato Excel o CSV respetando la vista activa.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="176">Campo</th><th width="133">Tipo</th><th width="411.800048828125">Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Consulta información según la fecha de creación del depósito.</td></tr><tr><td><strong><code>Id Concesionario</code></strong></td><td>Lista desplegable</td><td>Filtra la información por <a href="https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#concesionario">concesionario</a>.</td></tr><tr><td><strong><code>Id Subconcesionario</code></strong></td><td>Lista desplegable</td><td>Permite filtrar la información por <a href="https://virtualsoft.gitbook.io/plantillas/glosario#subconcesionario">subconcesionario</a>.</td></tr><tr><td><strong><code>Id Punto Venta</code></strong></td><td>Lista desplegable</td><td>Consulta la información asociada a un punto de venta específico.</td></tr><tr><td><strong><code>ID Jugador</code></strong></td><td>Campo búsqueda</td><td>Busca depósitos realizados por un jugador específico.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra la información según el partner asociado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Visualiza información correspondiente a un país específico.</td></tr><tr><td><strong><code>Tipo de depósito</code></strong></td><td>Lista desplegable</td><td>Permite consulta depósitos con comisión, sin comisión o todos los depósitos.</td></tr></tbody></table>

***

### 5. Componentes del Tablero

Este tablero cuenta con dos vistas de consulta, las cuales son:

{% tabs %}
{% tab title="Vista Detallada" %}
La vista detallada presenta la información en una tabla que permite consultar de forma individual cada depósito realizado, mostrando el detalle completo de la transacción.

<table><thead><tr><th width="192">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Indica el partner asociado al depósito.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado a la operación.</td></tr><tr><td><strong><code>Id Concesionario</code></strong></td><td>Identificador del <a href="https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#concesionario">concesionario</a> relacionado con el depósito.</td></tr><tr><td><strong><code>Id Subconcesionario</code></strong></td><td>Identificador del subconcesionario asociado.</td></tr><tr><td><strong><code>Id Punto Venta</code></strong></td><td>Identificador del punto de venta donde se realizó el depósito.</td></tr><tr><td><strong><code>Nombre Punto Venta</code></strong></td><td>Nombre configurado para el punto de venta.</td></tr><tr><td><strong><code>ID Jugador</code></strong></td><td>Identificador del jugador que realizó el depósito.</td></tr><tr><td><strong><code>Id Depósito</code></strong></td><td>Número identificador único del depósito.</td></tr><tr><td><strong><code>Fecha Creación Deposito Time</code></strong></td><td>Fecha y hora en la que se creó el depósito.</td></tr><tr><td><strong><code>¿Generó Comisión?</code></strong></td><td>Indica si el depósito generó una comisión,  asignada automáticamente por el sistema. Esta comisión es asumida por la operación de la marca correspondiente <em>(Ejemplo: Ecuabet)</em>.</td></tr><tr><td><strong><code>Valor Depósito</code></strong></td><td>Valor monetario correspondiente al depósito realizado.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Valor real de comisión generado por el depósito.</td></tr><tr><td><strong><code>Comisión potencial</code></strong></td><td>Valor de la comisión que se habría generado si el depósito no estuviera marcado como NTC. Este valor se calcula con base en el porcentaje de comisión configurado para el concesionario. En caso de que el depósito haya generado comisión, se mostrará el mismo valor registrado en el campo Comisión.</td></tr><tr><td><strong><code>Ahorro Comisión PV</code></strong></td><td>Diferencia entre la comisión potencial y la comisión real.</td></tr></tbody></table>
{% endtab %}

{% tab title="Vista Resumida" %}
Muestra la información organizada por categorías operativas, facilitando la consulta de los datos en tablas separadas.

{% tabs %}
{% tab title="Concesionario" %}
Muestra la información consolidada de depósitos y comisiones agrupada por concesionario.

<table><thead><tr><th width="216">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad Depósito</code></strong></td><td>Cantidad total de depósitos asociados.</td></tr><tr><td><strong><code>Valor Depósito</code></strong></td><td>Valor acumulado de los depósitos.</td></tr><tr><td><strong><code>Cantidad de Depósitos sin Comisión</code></strong></td><td>Cantidad de depósitos marcados como NTC.</td></tr><tr><td><strong><code>Valor Depósitos sin Comisión</code></strong></td><td>Valor acumulado de depósitos sin comisión.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Total de comisión correspondiente </td></tr><tr><td><strong><code>Comisión Potencial</code></strong></td><td>Comisión que se habría generado sin aplicación NTC.</td></tr><tr><td><strong><code>Ahorro Comisión</code></strong></td><td>Diferencia entre comisión potencial y comisión real.</td></tr></tbody></table>
{% endtab %}

{% tab title="Subconcesionario" %}
La información mostrada en esta vista depende directamente del concesionario seleccionado o expandido. Al seleccionar el ícono **(+)** sobre un concesionario, el sistema despliega los subconcesionarios relacionados con dicho registro.

De igual forma, al seleccionar el ícono **(-)**, la información de subconcesionarios se contrae nuevamente, mostrando únicamente el nivel del concesionario.

<table><thead><tr><th width="220">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Concesionario</code></strong></td><td>Identificador único del concesionario principal al que pertenece el subconcesionario visualizado. En las filas agrupadas se muestra el ícono (+) para expandir y visualizar el detalle de los subconcesionarios asociados, o el ícono (-) para contraer la información y ocultar el detalle mostrado.</td></tr><tr><td><strong><code>Id Subconcesionario</code></strong></td><td>Identificador único del subconcesionario asociado al concesionario seleccionado.</td></tr><tr><td><strong><code>Cantidad Depósito</code></strong></td><td>Cantidad total de depósitos asociados al subconcesionario.</td></tr><tr><td><strong><code>Valor Depósito</code></strong></td><td>Valor acumulado de depósitos registrados en el subconcesionario.</td></tr><tr><td><strong><code>Cantidad de Depósitos sin Comisión</code></strong></td><td>Cantidad de depósitos marcados como NTC dentro del subconcesionario.</td></tr><tr><td><strong><code>Valor Depósitos sin Comisión</code></strong></td><td>Valor acumulado de depósitos que no generaron comisión.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Total de comisión correspondiente a la red del subconcesionario.</td></tr><tr><td><strong><code>Comisión Potencial</code></strong></td><td>Valor de comisión que se habría generado si no se aplicara NTC.</td></tr><tr><td><strong><code>Ahorro Comisión</code></strong></td><td>Diferencia entre la comisión potencial y la comisión real del subconcesionario.</td></tr></tbody></table>
{% endtab %}

{% tab title="Punto de venta" %}
La vista de punto de venta permite visualizar la información consolidada de los depósitos y comisiones asociados a cada punto de venta.

La información se despliega jerárquicamente a partir del concesionario seleccionado.

Para visualizar los registros asociados, el usuario debe expandir cada nivel utilizando el ícono **(+)**, permitiendo visualizar la siguiente jerarquía:

* Concesionario
* Subconcesionario
* Subconcesionario 2
* Punto de venta

Al seleccionar el ícono **(-)**, el sistema contrae nuevamente la información del nivel correspondiente, mostrando únicamente el registro principal.

<table><thead><tr><th width="188.39996337890625">Campo</th><th width="453.5970458984375">Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Concesionario</code></strong></td><td>Identificador único del concesionario principal al que pertenece el subconcesionario visualizado. En las filas agrupadas se muestra el ícono (+) para expandir y visualizar el detalle de los subconcesionarios asociados, o el ícono (-) para contraer la información y ocultar el detalle mostrado.</td></tr><tr><td><strong><code>Id Subconcesionario</code></strong></td><td>Identificador del subconcesionario relacionado con el punto de venta.</td></tr><tr><td><strong><code>Id Subconcesionario2</code></strong></td><td>Identificador del segundo nivel de subconcesionario, en caso de existir dentro de la jerarquía.</td></tr><tr><td><strong><code>Id Punto Venta</code></strong></td><td>Identificador del punto de venta donde se realizaron los depósitos.</td></tr><tr><td><strong><code>Cantidad Depósito</code></strong></td><td>Cantidad total de depósitos realizados en el punto de venta.</td></tr><tr><td><strong><code>Valor Depósito</code></strong></td><td>Valor acumulado de depósitos registrados en el punto de venta.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Valor total de comisión generada por el punto de venta.</td></tr><tr><td><strong><code>Cantidad de Depósitos sin Comisión</code></strong></td><td>Cantidad de depósitos marcados como NTC que no generaron comisión.</td></tr><tr><td><strong><code>Valor Depósitos sin Comisión</code></strong></td><td>Valor acumulado de depósitos sin comisión asociados al punto de venta.</td></tr><tr><td><strong><code>Comisión Potencial</code></strong></td><td>Valor de comisión que se habría generado si no aplicara la regla NTC.</td></tr><tr><td><strong><code>Ahorro Comisión</code></strong></td><td>Diferencia entre la comisión potencial y la comisión real generada por el punto de venta.</td></tr></tbody></table>
{% endtab %}

{% tab title="Red" %}
La vista **Red** permite consultar la información consolidada de depósitos NTC mediante una visualización agrupada por concesionario, subconcesionario y punto de venta.

<table><thead><tr><th width="243.20001220703125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad Depósito</code></strong></td><td>Total de depósitos realizados.</td></tr><tr><td><strong><code>Valor Depósito</code></strong></td><td>Suma total del valor depositado.</td></tr><tr><td><strong><code>Comisiones</code></strong></td><td>Total de comisiones generadas.</td></tr><tr><td><strong><code>Cantidad de Depósitos sin Comisión</code></strong></td><td>Número de depósitos que no generaron comisión por aplicación del beneficio NTC.</td></tr><tr><td><strong><code>Valor Depósitos sin Comisión</code></strong></td><td>Valor acumulado de los depósitos sin comisión.</td></tr><tr><td><strong><code>Comisión Potencial</code></strong></td><td>Valor de comisión que se habría generado si el depósito no aplicaba para NTC.</td></tr><tr><td><strong><code>Ahorro Comisión Red</code></strong></td><td>Diferencia entre la comisión potencial y la comisión generada.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}

***

### 6. Validaciones y reglas del negocio

* El dashboard incluye depósitos con y sin comisión.
* Los depósitos marcados como NTC no generan comisión.
* La comisión potencial se calcula utilizando las mismas reglas de cálculo de la comisión real.
* El ahorro corresponde a la diferencia entre comisión potencial y comisión real.
* La información del dashboard se visualiza con corte a día vencido.&#x20;
* La vista detallada se ordena por la fecha de creación del depósito, de forma descendente.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="103.79998779296875">Versión</th><th width="132.4000244140625">Fecha</th><th width="123.4000244140625">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>14/05/2026</td><td>Karol Navia</td><td>Creación inicial del manual Dashboard Depósitos NTC.</td></tr></tbody></table>

</details>
