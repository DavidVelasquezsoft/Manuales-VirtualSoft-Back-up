---
description: >-
  Permite consultar los reportes de las apuestas realizadas en loterías por los
  usuarios.
---

# Reporte productos no deportivos (Por usuario)

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Menú principal > Jugadores > 🔍 (_Detalles de jugadores)_ > Reportes > Reporte de productos no deportivos.

***

### 2. Visualización:

<figure><img src="../../../.gitbook/assets/image (634).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Reporte de productos no deportivos <em>(Usuario).</em></p></figcaption></figure>

***

### **3. Acciones del Usuario**

<table><thead><tr><th width="163">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/reporte-productos-no-deportivos-por-usuario#id-4.-filtros-de-busqueda"><strong>Filtrar</strong> </a></td><td>Utiliza los filtros disponibles para realizar búsquedas más precisas. </td></tr><tr><td><strong>Exportar los resultados</strong></td><td>Exporta en formato Excel la tabla de resultados según los filtros seleccionados desde la opción "<strong><code>Exportar</code></strong>" úbicada en la parte inferior derecha de la tabla.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/reporte-productos-no-deportivos-por-usuario#id-5.-tabla-de-resultados"><strong>Consultar información</strong></a></td><td>Ejecuta la búsqueda y muestra un reporte de las apuestas realizadas por el usuario en una tabla.</td></tr><tr><td><strong>Limpiar</strong></td><td>Reinicia todos los filtros aplicados.</td></tr><tr><td><a href="reporte-productos-no-deportivos-por-usuario.md#detallado"><strong>Ver detalle</strong></a></td><td>Permite visualizar el detalle de la jugada mediante una imagen o un video, dependiendo del proveedor.</td></tr></tbody></table>

***

### **4.  Filtros de búsqueda**

<table><thead><tr><th width="145.09088134765625">Sección</th><th width="136">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Selector de rango</td><td>Selecciona el rango de fechas de las apuestas que deseas consultar.</td></tr><tr><td><strong><code>Identificador</code></strong></td><td>Texto</td><td>Filtra el reporte mediante el identificador único asociado a la apuesta realizada <em>(Este mismo identificador también puede consultarse en el</em><a href="https://sites.gitbook.com/preview/site_U8bCN/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos"> <em>reporte de productos no deportivos general</em></a><em>).</em></td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona el proveedor con el que se realizó la apuesta.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Filtra por el producto <em>(Juego)</em> en el que se realizó la apuesta.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selector</td><td><p>Selecciona que tipo de reporte se va a visualizar en la tabla.</p><ul><li><a href="https://sites.gitbook.com/preview/site_U8bCN/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/reporte-productos-no-deportivos-por-usuario#detallado"><strong>Detallado</strong></a>: Muestra el reporte de forma individual, presentando cada apuesta en una fila independiente junto con su información asociada.</li><li><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/reporte-productos-no-deportivos-por-usuario#totales"><strong>Totales</strong></a>: Muestra el reporte de forma agrupada, presentando los valores consolidados de las apuestas organizados por proveedor.</li></ul></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td><p>Filtra las apuestas según su estado:</p><ul><li><strong>Cerradas:</strong> apuestas que ya finalizaron y tienen un resultado definido.</li><li><strong>Abiertas:</strong> apuestas que fueron registradas, pero aún están pendientes de finalizar.</li></ul></td></tr><tr><td><strong><code>Vertical</code></strong></td><td>Lista desplegable</td><td>Selecciona la categoría correspondiente a la apuesta realizada <em>(Casino, casino en vivo, virtuales... etc.).</em></td></tr></tbody></table>

***

### **5. Tabla de resultados**

Los resultados mostrados en este reporte se visualizarán de acuerdo con la opción seleccionada en el filtro **`Tipo`**, ya que este determina la estructura y el nivel de agrupación de la información presentada.

{% tabs %}
{% tab title="Totales" %}
Cada proveedor contará con un ícono 📁 que permite expandir o contraer el detalle asociado.

* La fila principal _(donde se visualiza el ícono 📁)_ presenta los valores **totales agrupados** por proveedor.
* Al desplegar el grupo, se visualizarán filas adicionales con el **detalle individual de las apuestas** correspondientes a ese proveedor.

<table><thead><tr><th width="151">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>En la fila agrupada muestra el ícono 📁 junto al nombre del proveedor, permitiendo expandir o contraer el detalle asociado. En las filas detalladas también muestra el nombre del proveedor correspondiente a cada registro.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego en el que se realizó la apuesta <em>(Se visualiza solo en las filas detalladas).</em></td></tr><tr><td><strong><code>Identificador</code></strong></td><td>Código interno único que identifica el juego asociado a la apuesta.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Muestra únicamente el nombre del proveedor sin el ícono de agrupación. El valor corresponde al mismo proveedor indicado en la columna principal, visualizándose de forma individual en cada fila detallada.</td></tr><tr><td><strong><code>Cantidad</code></strong></td><td>Número de apuestas registradas. En la fila agrupada se muestra el total acumulado por proveedor; en las filas detalladas se muestra el valor correspondiente a cada registro individual.</td></tr><tr><td><strong><code>Impuesto Apuesta</code></strong></td><td>Monto total descontado por concepto de impuesto aplicado a la apuesta realizada.</td></tr><tr><td><strong><code>Impuesto premios</code></strong></td><td>Monto descontado por concepto de impuesto aplicado al premio obtenido.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Monto apostado. En la fila agrupada se presenta el total consolidado por proveedor; en el detalle corresponde al valor individual de cada apuesta.</td></tr><tr><td><strong><code>Saldo gratis</code></strong></td><td>Monto apostado utilizando saldo promocional o saldo gratis.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Monto total de premios obtenidos por la apuesta <em>(Incluye los premios generados por dinámicas internas del juego, como bonos o recompensas propias del proveedor).</em></td></tr><tr><td><strong><code>Bonos</code></strong> </td><td>Monto de premios otorgados a partir de bonos concedidos directamente desde la plataforma <em>(por ejemplo, torneos o campañas promocionales)</em>.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a></td><td>Ingreso bruto generado, calculado como la diferencia entre el monto apostado y los premios otorgados.</td></tr><tr><td><strong><code>Beneficio %</code></strong></td><td>Porcentaje de beneficio obtenido, calculado como ((Apuestas - Ganancias - Ganancias obtenidas de los bonos) / Total apostado) × 100.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detallado" %}
El reporte detallado se presenta a nivel de apuesta; cada fila corresponde a una apuesta individual realizada por el usuario.

<table><thead><tr><th width="146.09088134765625">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><code>🔍</code></td><td>Accede a información más detallada sobre la apuesta realizada.<br><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/reporte-productos-no-deportivos-por-usuario#detalles-avanzados" class="button secondary">Detalles Avanzados</a></td></tr><tr><td><strong><code>Id</code></strong></td><td>Identificador único del registro.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha exacta en la que se realizó la apuesta.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Nombre o ID del usuario que hizo la apuesta.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego en la que se realizó la apuesta.</td></tr><tr><td><strong><code>Identificador</code></strong></td><td>Identificador único específico del ticket generado.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor del en el que se realizó la apuesta.</td></tr><tr><td><strong><code>Cantidad</code></strong></td><td>Monto total apostado en la jugada.</td></tr><tr><td><strong><code>Impuesto Apuesta</code></strong></td><td>Monto del impuesto aplicado sobre la apuesta.</td></tr><tr><td><strong><code>Impuesto Premios</code></strong></td><td>Impuesto descontado al usuario sobre los premios obtenidos.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Total de apuestas realizadas.</td></tr><tr><td><strong><code>Saldo Gratis</code></strong></td><td>Monto usado en saldo promocional.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Valor total de premios ganados por la apuesta realizada.</td></tr><tr><td><strong><code>Bonos</code></strong></td><td>Cantidad de bonos otorgados.</td></tr><tr><td><strong><code>GGR</code></strong></td><td>Ingreso bruto generado (apuesta - premios).</td></tr><tr><td><strong><code>Premios Bonos</code></strong></td><td>Total de premios obtenidos utilizando bonos.</td></tr><tr><td><strong><code>Beneficio %</code></strong></td><td>Porcentaje de beneficio obtenido, calculado como ((Apuestas - Ganancias - Ganancias obtenidas de los bonos) / Total apostado) × 100.</td></tr><tr><td><strong><code>Detalle de jugada</code></strong></td><td><p>Permite visualizar el detalle de la apuesta registrada. Al seleccionar esta opción, se abrirá una nueva pestaña donde se reproducirá el video o se mostrará una imagen, según el proveedor asociado a la ronda específica de la jugada realizada.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: La opción <strong>"Ver detalle"</strong> está disponible en todos los reportes. Sin embargo, la disponibilidad del video o imagen depende de las condiciones definidas por cada proveedor. En caso de que el proveedor no disponga del video para la jugada consultada, no se realizará la redirección ni se abrirá una nueva pestaña.</p></div></td></tr></tbody></table>

<details>

<summary><strong>Detalles Avanzados</strong></summary>

Permite visualizar una tabla con información detallada de la apuesta, incluyendo las ganancias obtenidas y las apuestas realizadas, con la posibilidad de aprobar o anular la apuesta.

<table><thead><tr><th width="135">Columna </th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td><p>Cada ronda registrada en la plataforma <strong>Usuarios Online</strong> puede ser gestionada manualmente una vez el usuario la haya realizado y se hayan generado las ganancias correspondientes.</p><ul><li>🔍: Confirma de forma manual el movimiento asociado a la apuesta seleccionada.</li><li>✖️: Rechaza la transacción asociada a la apuesta seleccionada y reintegra al usuario el monto apostado.</li></ul></td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del movimiento.</td></tr><tr><td><strong><code>Transacción id</code></strong></td><td>Identificador único del movimiento que se realizó con la transacción.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de movimiento realizado <em>(Debit:</em> Saldo descontado por apuestas realizadas<em>. / Credit:</em> Saldo acreditado correspondiente a premios<em>).</em></td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto correspondiente al movimiento realizado.</td></tr></tbody></table>

</details>
{% endtab %}
{% endtabs %}

***

### **6. Validaciones y Reglas de Negocio**

* El tipo de vista **Detallado** mostrará cada apuesta individual, mientras que **Totales** consolida los datos.
* Los impuestos se calculan automáticamente según la normativa vigente para cada país.
* La información en la pestaña "**Detalles avanzados**" corresponde a la apuesta seleccionada luego de realizar una consulta.
* Las condiciones establecidas por cada proveedor para habilitar la visualización del detalle de la jugada son de carácter interno. Por lo tanto, en caso de requerir validación o mayor información, se recomienda gestionarlo directamente con el proveedor correspondiente.
* Si no se cuenta con la URL para visualizar la jugada desde la opción "**ver detalles**" se mostrará el mensaje "**Detalle no disponible para esta jugada**".
* Si ocurre un error al consultar la jugada, se mostrará un error indicando "No fue posible obtener el detalle en este momento".
* Los errores por la opción de "**ver detalles**" no bloquean las acciones ni otras funciones del BackOffice, son solo informativos y se puede volver a intentar dándole clic nuevamente a la opción.

***

### **7. Control de Versiones**

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="103.39996337890625">Versión</th><th width="132">Fecha</th><th width="141">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>16/09/2025</td><td>Karol Navia</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>28/01/2026</td><td>Ronald Peláez</td><td>Refinamiento de manual</td></tr><tr><td>1.2</td><td>05/05/2026</td><td>Ronald Peláez</td><td>Restructuración de manual y nueva columna <strong><code>Detalle de jugada</code></strong> en reporte detallado </td></tr><tr><td>1.3</td><td>15/05/2026</td><td>Karol Navia</td><td>Restructuración del campo <strong><code>Detalle de jugada</code></strong> en reporte detallado </td></tr><tr><td>1.4</td><td>03/06/2026</td><td>Karol Navia</td><td>Mejoramiento del campo <strong><code>Detalle de jugada</code></strong> en reporte detallado </td></tr></tbody></table>

</details>
