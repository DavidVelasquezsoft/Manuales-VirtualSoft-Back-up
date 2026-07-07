---
description: >-
  Permite visualizar todas las pollas deportivas realizadas en penka de forma
  detallada y especifica.
---

# Reporte de pollas deportivas

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú > Reportes > Reporte de pollas deportivas

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (674).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección reporte de pollas deportivas</p></figcaption></figure>

***

### 3. Acciones disponibles

Desde este módulo de [pollas](https://virtualsoft.gitbook.io/untitled/glosario#polla-deportiva) deportivas cuenta con las siguientes acciones.&#x20;

<table><thead><tr><th width="112.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-pollas-deportivas.md#id-5.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información, ya sea en la vista resumida o detallada para obtener resultados más precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><strong>Consultar</strong></td><td>Aplica los filtros seleccionados y muestra los registros válidos ya sea en vista resumida o detallada.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr><tr><td><a href="reporte-de-pollas-deportivas.md#reporte-detallado"><strong>Ver reporte detallado</strong></a></td><td>Visualiza el reporte con información y filtros más detalladas.</td></tr></tbody></table>

***

### 4. Información del reporte

Permite visualizar la información en dos vistas:

{% tabs %}
{% tab title="Reporte resumido" %}
Muestra la información general de las pollas deportivas registradas en el sistema, de acuerdo con los filtros aplicados.

#### 4.1. Filtros

<table><thead><tr><th width="157.9814453125">Campo</th><th width="137.98138427734375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Calendario</td><td>Selecciona el periodo de tiempo en el que se consultarán las pollas deportivas según su fecha de creación en el sistema.</td></tr><tr><td><strong><code>Fecha inicio</code></strong></td><td>Calendario</td><td><p>Selecciona el rango de fechas correspondiente al inicio de la polla deportiva.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La fecha corresponde al inicio del primer partido asociado a la polla deportiva enviado por el proveedor y no a la fecha de creación en el sistema. Si no se selecciona este filtro, el reporte utilizará el rango de fechas definido en el filtro <strong><code>Rango de fechas</code></strong>.</p></div></td></tr><tr><td><strong><code>Ordenar por</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el criterio de ordenamiento de la información mostrada en el reporte (<em>Ej: Fecha inicio</em>).</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Lista desplegable</td><td>Permite definir el tipo de ordenamiento de la información seleccionada, ya sea ascendente o descendente.</td></tr><tr><td><strong><code>ID de polla</code></strong></td><td>Texto / Numérico</td><td>Identificador único de la polla utilizado de manera interna.</td></tr><tr><td><strong><code>Código de la polla</code></strong></td><td>Numérico.</td><td>Identificador externo de la polla utilizado por PENKA.</td></tr></tbody></table>

#### **4.2. Resultados de Consulta**

Consulta y muestra los registros válidos de las [pollas deportivas](https://virtualsoft.gitbook.io/untitled/glosario#polla-deportiva), también llamadas **Penkas**, según los filtros seleccionados.

<table><thead><tr><th width="183.2222900390625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>🔎 (Ver detalle)</code></strong></td><td>Despliega barra lateral con la información de todas las apuestas realizadas en la polla. <a href="reporte-de-pollas-deportivas.md#reporte-detallado">Ver detalle</a></td></tr><tr><td><strong><code>ID polla</code></strong></td><td>Identificador único de la polla.</td></tr><tr><td><strong><code>Código de la polla</code></strong></td><td>Identificador único de la polla que se utiliza de forma externa por PENKA.</td></tr><tr><td><strong><code>Fecha inicio</code></strong></td><td><p>Indica la fecha desde la cual inicio el primer partido de la polla deportiva.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Esta fecha es diferente a la fecha de creación, ya que corresponde al inicio de la polla enviado por el proveedor y no al momento en que fue registrada en el sistema.</p></div></td></tr><tr><td><strong><code>Cantidad de apuestas</code></strong></td><td>Numero de apuestas realizadas en la polla.</td></tr><tr><td><strong><code>Nombre de la Penka</code></strong></td><td>Nombre de la polla definido por el operador.</td></tr><tr><td><strong><code>¿Penka gratuita o pagada?</code></strong></td><td><p>Indica si la participación en la polla deportiva requiere pago o si puede realizarse de forma gratuita.</p><ul><li><strong>Gratuita:</strong> El jugador puede participar sin realizar ningún pago.</li><li><strong>Pagada:</strong> El jugador debe pagar el valor de entrada configurado para poder participar.</li></ul></td></tr><tr><td><strong><code>Valor de entrada a la penka</code></strong></td><td>Muestra el monto que el jugador debe pagar para participar en la polla.  Si la polla es gratuita, este valor será <strong>$0</strong>.</td></tr><tr><td><strong><code>Porcentaje de la casa</code></strong></td><td>Indica el porcentaje del pozo acumulado que corresponde a la casa u operador, según la configuración definida para la polla deportiva. Este porcentaje representa el valor retenido sobre el total recaudado antes de la distribución de premios.</td></tr><tr><td><strong><code>Comisión de la casa</code></strong></td><td><p>Muestra el valor monetario que la casa u operador retiene del pozo acumulado de la polla deportiva, calculado automáticamente a partir del porcentaje configurado sobre el total apostado.<br></p><p><strong>Fórmula:</strong> <em>(Pozo total × Porcentaje de la casa)</em></p></td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr"><strong><code>GGR</code></strong></a> <strong><code>(Gross Gaming Revenue)</code></strong></td><td>Indica la ganancia bruta de la casa, calculada como la diferencia entre el total apostado y el total de premios pagados en la polla.</td></tr><tr><td><strong><code>Total aposado</code></strong></td><td>Muestra el valor total apostado por todos los participantes en la polla deportiva. Este valor corresponde al pozo acumulado utilizado para la distribución de premios y cálculos de comisión.</td></tr><tr><td><strong><code>Comisión facturable</code></strong></td><td><p>Muestra el valor generado por cada polla deportiva que será tomado en cuenta para la facturación del proveedor Penka.</p><p>El valor se calcula automáticamente según el tipo de premios configurado para la polla:</p><ul><li><strong>Premios fijos:</strong> Los premios entregan valores definidos previamente, independientemente del total recaudado en la polla. En este caso, la comisión corresponde a la diferencia entre el valor total recaudado y los premios pagados. <strong>Fórmula:</strong> (<em>Comisión = Recaudado - Premios)</em></li><li><strong>Premios variables (</strong><em><strong>por porcentaje del pozo</strong></em><strong>):</strong> Los premios se calculan como un porcentaje del pozo acumulado de la polla. En este caso, la comisión corresponde al valor restante del pozo después de distribuir los premios.<br><strong>Fórmula:</strong> (<em>Comisión = Pozo total - Premios distribuidos)</em></li></ul><p>El campo mostrará <strong>$0</strong> cuando la polla no genere utilidad, no aplique para facturación o no cuente con información suficiente para realizar el cálculo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El cálculo se realiza automáticamente y permite identificar los valores considerados para conciliación y facturación con el proveedor Penka.</p></div></td></tr><tr><td><strong><code>Total de premios</code></strong></td><td><p>Monto total de premios otorgados a los participantes en la polla.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> En pollas privadas, si no se alcanza el <strong>mínimo de 4 participantes</strong>, la polla se cancela automáticamente. En este caso, el valor total recaudado por las inscripciones se devuelve a los usuarios y se refleja en este campo como <strong><code>total de premios</code></strong>, siendo <strong>igual</strong> al total apostado. Para identificar si el valor corresponde a premios o a una devolución por cancelación, debe consultar el detalle de la polla y validar el estado de los jugadores.</p></div></td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha exacta en la cual se creó la polla en el sistema.</td></tr><tr><td><strong><code>Fecha Última Modificación</code></strong></td><td>Fecha en la que se registró el último movimiento, actualización o cambio relacionado con la polla deportiva dentro del sistema.</td></tr></tbody></table>

* En la parte inferior se muestra una **fila** con el total de cada columna, calculando la suma de los valores de todos los registros.
{% endtab %}

{% tab title="🔎 Reporte detallado" %}
Permite visualizar el detalle de los usuarios participantes de la polla deportiva seleccionada. Esta vista puede abrirse desde la barra lateral derecha o mediante el ícono de 🔎 (lupa) disponible en cada registro del reporte general para ver el detalle de la [polla deportiva](https://virtualsoft.gitbook.io/untitled/glosario#polla-deportiva).

#### 4.2.1. Filtros

<table><thead><tr><th width="156.5">Campo</th><th width="163.16656494140625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Fecha Inicio / Fin</td><td>Selecciona el periodo de tiempo en el que se generará el reporte.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra por el estado de la apuesta del usuario (<em>Ganada/ Perdida</em>).</td></tr><tr><td><strong><code>ID de Usuario</code></strong></td><td>Numérico</td><td>Permite ver todas las pollas en las que participó un usuario específico.</td></tr></tbody></table>

#### 4.2.2. Consultar

Aplica los filtros seleccionados y muestra los registros válidos de los usuarios en las [pollas deportivas](https://virtualsoft.gitbook.io/untitled/glosario#polla-deportiva).

<table><thead><tr><th width="183.2222900390625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario.</td></tr><tr><td><strong><code>ID polla</code></strong></td><td>Identificador único de la polla.</td></tr><tr><td><strong><code>Estado</code></strong></td><td><p>Indica el estado de la participación del usuario en la polla deportiva (<em>penka</em>), según el resultado obtenido:</p><ul><li><strong>Ganador:</strong> Recibe una acreditación mayor a 0 como resultado de su desempeño en la polla.</li><li><strong>Perdedor:</strong> No obtiene acreditación, debido a que no alcanzó un resultado ganador.</li><li><strong>Cancelado:</strong> En el caso de penkas privadas, si al iniciar el primer evento no se alcanza el mínimo de 4 integrantes, la polla se cancela automáticamente y se realiza la devolución de los valores apostados a todos los jugadores.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> En caso de cancelación, el valor devuelto se registrará y visualizará en el campo <strong>Premios obtenidos</strong>.</p></div></td></tr><tr><td><strong><code>ID Aggregator</code></strong></td><td>Identificador único interno utilizado por el proveedor (<em>Ej: Penka</em>) para identificar al usuario, diferente al ID asignado por la plataforma.</td></tr><tr><td><strong><code>Monto aposado</code></strong></td><td>Monto pagado por el jugador para participar en la polla deportiva.</td></tr><tr><td><strong><code>premios obtenidos</code></strong></td><td><p>Monto total de premios otorgados a los participantes en la polla, según los resultados obtenidos.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> En caso de cancelación, el valor devuelto a los usuarios se reflejará en este campo como premios obtenidos.</p></div></td></tr><tr><td><strong><code>Fecha primer registro</code></strong></td><td>Fecha del primer movimiento o registro realizado por el usuario en la polla deportiva.</td></tr><tr><td><strong><code>Fecha Última Modificación</code></strong></td><td>Fecha en la que se registró el último movimiento, actualización o cambio relacionado con la polla deportiva dentro del sistema.</td></tr></tbody></table>

* En la parte inferior se muestra una **fila** con el total de cada columna, calculando la suma de los valores de todos los registros.
{% endtab %}
{% endtabs %}

***

### 5. Validaciones y reglas del negocio.

* Cada identificador único interno de una polla deportiva debe tener un identificador único externo _(Código de polla)_ asociado.
* La participación y creación de pollas deportivas (_penkas_) se realiza exclusivamente desde la sección correspondiente de la plataforma. Para más información sobre su funcionamiento, consulte el manual en la siguiente sección: [Pollas deportivas](https://app.gitbook.com/s/yyrHDz69FZMnpZ9NBm8u/usuarios-online/manual-de-plataforma/pollas-deportivas "mention")
* Para el filtro **`Fecha inicio`** debes tener en cuenta las siguientes validaciones:
  * El campo **Desde** no puede ser mayor que el campo **Hasta**.
  * Si el usuario ingresa un rango inválido, el sistema mostrará el mensaje:\
    &#xNAN;**“La fecha inicial no puede ser mayor que la fecha final.”**

***

### 6. Control de Versiones

<details>

<summary>🔽 <strong>Historial de versiones</strong></summary>

<table><thead><tr><th width="105.88885498046875">Versión</th><th width="132">Fecha</th><th width="160">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>25/09/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>19/01/2026</td><td>David Velasquez</td><td>Incorporación de nuevos campos</td></tr><tr><td>1.2</td><td>25/03/2026</td><td>Ronald Peláez</td><td>Incorporación de Código de la polla</td></tr><tr><td>1.3</td><td>31/03/2026</td><td>David Velasquez</td><td>Incorporación de notas</td></tr><tr><td>1.4</td><td>13/05/2026</td><td>David Velasquez</td><td>Nueva columna <strong><code>comisión facturable</code></strong></td></tr><tr><td>1.5</td><td>27/05/2026</td><td>David Velasquez</td><td>Nuevos filtros y nuevo campo <strong><code>Fecha inicio</code></strong></td></tr></tbody></table>

</details>
