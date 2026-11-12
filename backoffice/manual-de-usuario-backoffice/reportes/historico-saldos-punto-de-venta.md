# Histórico saldos punto de venta

<mark style="color:$info;">Consulta el movimiento de los saldos y cupos de cada punto de venta durante un período determinado. Muestra con qué saldo inició, qué operaciones registró (recargas, apuestas, premios, transferencias, retiros e impuestos) y con qué saldo cerró, además de contrastar el saldo registrado contra el saldo calculado por el sistema para detectar inconsistencias.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Histórico saldos punto de venta

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FB6ImDtKPoWhFjmX771FA%2Fimage.png?alt=media&#x26;token=ec846a20-e903-4f89-9255-ce49eed46984" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Histórico saldos punto de venta.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="historico-saldos-punto-de-venta.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los registros.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="historico-saldos-punto-de-venta.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los registros en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Consulta los registros de un punto de venta específico mediante su identificador.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Calendario</td><td>Delimita el período de tiempo sobre el cual se realiza la consulta.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td><p>Muestra únicamente los registros del país seleccionado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Admite un único país por consulta.</p></div></td></tr><tr><td><strong><code>Punto de venta propio?</code></strong></td><td>Interruptor</td><td>Restringe la consulta a los puntos de venta propios de la operación, excluyendo los de terceros.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selector</td><td><p>Determina el nivel de detalle con el que se presenta el reporte.</p><ul><li><strong>Totales:</strong> muestra la información consolidada del período.</li><li><strong>Detallado:</strong> muestra el desglose de cada registro.</li></ul></td></tr><tr><td><strong><code>Ordenar por</code></strong></td><td>Lista desplegable</td><td><p>Define el criterio con el que se organizan los resultados:</p><ul><li><strong>Calc. Desfase</strong></li><li><strong>GGR. Deportivas</strong></li><li><strong>GGR. Casino</strong></li><li><strong>Fecha de Creación</strong></li></ul></td></tr><tr><td><strong><code>Orden</code></strong></td><td>Lista desplegable</td><td>Indica si los resultados se presentan de forma ascendente o descendente según el criterio seleccionado en <strong><code>Ordenar por</code></strong>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los registros que cumplen con los filtros aplicados.

{% hint style="warning" %}
**Notas:**&#x20;

* Los campos que inician con **Saldo Bruto** incluyen las apuestas y premios **pendientes de liquidar o pagar**, mientras que **`Apuestas Virtuales`** y **`Premios Virtuales`** reflejan únicamente lo ya liquidado. Por esta razón, los valores de ambos pares no necesariamente coinciden.
* En los campos de transferencias, la letra **E** corresponde a las de **entrada** _(recibidas)_ y la letra **S** a las de **salida** _(enviadas)_.
{% endhint %}

{% hint style="danger" %}
**Importante:** Cuando el campo **`Calc. Desfase`** presenta un valor diferente de cero, el sistema resalta el registro en color <mark style="color:$danger;">**rojo**</mark>. Esto advierte una posible inconsistencia entre el saldo registrado y el saldo calculado, que debe revisarse para determinar su origen.
{% endhint %}

<table><thead><tr><th width="268">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Texto</td><td>Nombre del partner al que pertenece el punto de venta.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha</td><td>Fecha a la que corresponde el corte de información del registro.</td></tr><tr><td><strong><code>País</code></strong></td><td>Texto</td><td>País en el que opera el punto de venta.</td></tr><tr><td><strong><code>Saldo Inicial</code></strong></td><td>Numérico</td><td>Saldo con el que el punto de venta inició el período consultado.</td></tr><tr><td><strong><code>Cupo recargas inicial</code></strong></td><td>Numérico</td><td>Cupo disponible al inicio del período para realizar recargas a usuarios.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador del punto de venta al que corresponde el registro.</td></tr><tr><td><strong><code>Nombre Usuario</code></strong></td><td>Texto</td><td>Nombre del punto de venta vinculado al movimiento.</td></tr><tr><td><strong><code>Cupo juego inicial</code></strong></td><td>Numérico</td><td>Cupo disponible al inicio del período para operaciones de juego.</td></tr><tr><td><strong><code>Depósitos</code></strong></td><td>Numérico</td><td>Total de recargas realizadas por el punto de venta a usuarios de la plataforma online.</td></tr><tr><td><strong><code>Apuestas Virtuales</code></strong></td><td>Numérico</td><td>Monto total de apuestas virtuales vendidas en el punto de venta que ya fueron liquidadas.</td></tr><tr><td><strong><code>Premios Virtuales</code></strong></td><td>Numérico</td><td>Monto total pagado en premios de apuestas virtuales en el punto de venta.</td></tr><tr><td><strong><code>Saldo Bruto Apuestas Virtuales</code></strong></td><td>Numérico</td><td>Total apostado en juegos virtuales <em>(GoldenRace)</em> por el punto de venta, incluyendo las apuestas que aún no han sido liquidadas.</td></tr><tr><td><strong><code>Saldo Bruto Premios Virtuales</code></strong></td><td>Numérico</td><td>Total de premios generados en juegos virtuales <em>(GoldenRace)</em>, incluyendo aquellos que aún no han sido pagados.</td></tr><tr><td><strong><code>Ap. Deportivas</code></strong></td><td>Numérico</td><td>Monto total apostado en eventos deportivos desde el punto de venta.</td></tr><tr><td><strong><code>Pr. Deportivas</code></strong></td><td>Numérico</td><td>Monto total pagado en premios de apuestas deportivas.</td></tr><tr><td><strong><code>Transf Apuesta E</code></strong></td><td>Numérico</td><td>Total de transferencias de apuesta recibidas por el punto de venta.</td></tr><tr><td><strong><code>Transf Apuesta S</code></strong></td><td>Numérico</td><td>Total de transferencias de apuesta enviadas a otros puntos de venta.</td></tr><tr><td><strong><code>Transf Recarga E</code></strong></td><td>Numérico</td><td>Total de transferencias de recarga recibidas por el punto de venta.</td></tr><tr><td><strong><code>Transf Recarga S</code></strong></td><td>Numérico</td><td>Total de transferencias de recarga enviadas a otros puntos de venta.</td></tr><tr><td><strong><code>Retiros Pagados</code></strong></td><td>Numérico</td><td>Total pagado en retiros desde el punto de venta.</td></tr><tr><td><strong><code>Recargas Eliminadas</code></strong></td><td>Numérico</td><td>Valor total de las recargas anuladas durante el período.</td></tr><tr><td><strong><code>Saldo Final</code></strong></td><td>Numérico</td><td>Saldo registrado en el sistema al cierre del período consultado.</td></tr><tr><td><strong><code>Saldo Final Calc.</code></strong></td><td>Numérico</td><td>Saldo que debería tener el punto de venta al cierre, calculado por el sistema a partir de los movimientos registrados durante el período.</td></tr><tr><td><strong><code>Calc. Desfase</code></strong></td><td>Numérico</td><td><p>Diferencia entre el saldo registrado y el saldo calculado por el sistema. Permite identificar si los movimientos del período explican por completo el saldo de cierre.</p><p><strong>Fórmula:</strong><br><em>Calc. Desfase = Saldo Final − Saldo Final Calc.</em></p></td></tr><tr><td><strong><code>Impuesto Deposito</code></strong></td><td>Numérico</td><td>Valor retenido por concepto de impuesto sobre los depósitos realizados.</td></tr><tr><td><strong><code>Impuesto Apuesta</code></strong></td><td>Numérico</td><td>Valor retenido por impuesto sobre el monto apostado.</td></tr><tr><td><strong><code>Impuesto Apuesta Casino</code></strong></td><td>Numérico</td><td>Valor retenido por impuesto sobre el monto apostado en casino.</td></tr><tr><td><strong><code>Cupo</code></strong></td><td>Numérico</td><td>Cupo disponible al cierre del período consultado.</td></tr><tr><td><strong><code>Cupo Calc.</code></strong></td><td>Numérico</td><td>Cupo que debería tener el punto de venta al cierre, calculado por el sistema a partir de las operaciones registradas.</td></tr><tr><td><strong><code>Total Depósitos a agentes</code></strong></td><td>Numérico</td><td>Monto total depositado a un <a href="https://virtualsoft.gitbook.io/untitled/glosario/#agente">agente</a> o punto de venta.</td></tr><tr><td><strong><code>Total Depósitos Usuarios Online</code></strong></td><td>Numérico</td><td>Monto total depositado por el punto de venta a usuarios de la plataforma online.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* Únicamente los usuarios con el permiso asignado pueden acceder al módulo y ejecutar consultas.
* No es obligatorio diligenciar todos los filtros para ejecutar la consulta.
* Los resultados mostrados corresponden únicamente a los criterios seleccionados en los filtros.
* El filtro **`País`** admite un único país por consulta.
* Cuando no existe información de apuestas o premios para una fecha o punto de venta determinado, la consulta muestra el valor **0.00**.
* Los campos terminados en **Calc.** no corresponden a un valor registrado: el sistema los calcula a partir de los movimientos del período para contrastarlos con los valores reales y permitir la conciliación.
* Un valor diferente de cero en **`Calc. Desfase`** indica una diferencia entre el saldo registrado y el calculado; el registro se resalta en rojo para su revisión.
* El reporte es informativo: desde este módulo no es posible modificar saldos ni cupos.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="107.81478881835938">Versión</th><th width="127">Fecha</th><th width="153">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>07/07/2025</td><td>David Velásquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>03/09/2025</td><td>Karol Navia</td><td>Agregar nuevas columnas</td></tr><tr><td>1.2</td><td>01/12/2025</td><td>Ronald Peláez</td><td>Nuevas columnas Depósitos por agente y usuarios online.</td></tr><tr><td>1.3</td><td>19/01/2026</td><td>David Velásquez</td><td>Refinamiento del manual y de algunas columnas.</td></tr><tr><td>1.4</td><td>26/01/2026</td><td>Ronald Peláez</td><td>Ajuste en el campo <strong><code>Depósitos</code></strong> y <strong><code>Total Depósitos a agentes</code></strong></td></tr><tr><td>1.5</td><td>13/10/2026</td><td>David Velásquez</td><td>Actualización de formato.</td></tr></tbody></table>

</details>
