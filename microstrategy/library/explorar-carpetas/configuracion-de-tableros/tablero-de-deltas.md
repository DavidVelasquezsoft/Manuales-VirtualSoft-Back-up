# Tablero de Deltas

#### 1. Acceso al Módulo

**Ruta de Acceso**:

***

#### 🖼️ 2. Visualización

***

#### 🧑‍💻 3. Acciones de usuario

<table><thead><tr><th width="180">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Visualizar KPIs</strong></td><td>Permite observar los KPIs operativos de Deltas con comportamiento acumulado por hora.</td></tr><tr><td><strong>Aplicar filtros</strong></td><td>El usuario puede filtrar la información por partner, país, fecha y hora.</td></tr><tr><td><strong>Analizar tendencias</strong></td><td>Facilita la detección de incrementos atípicos mediante el acumulado horario.</td></tr><tr><td><strong>Comparar periodos</strong></td><td>Permite analizar el comportamiento por hora, día o mes según el filtro seleccionado.</td></tr></tbody></table>

***

#### 🔎 4. Filtros del Dashboard

| Filtro  | Tipo                   | Descripción                                                      |
| ------- | ---------------------- | ---------------------------------------------------------------- |
| Partner | Lista desplegable      | Filtra la información por partner.                               |
| País    | Lista desplegable      | Filtra los datos por país.                                       |
| Fecha   | Selector de fecha      | Permite consultar información diaria o histórica.                |
| Hora    | Selector horario (24h) | Permite analizar el acumulado hasta una hora específica del día. |

***

#### 📘‍5. Contenido del Dashboard

El tablero presenta indicadores operativos de Deltas con una lógica de **acumulado horario diario**, permitiendo identificar incrementos atípicos y analizar el comportamiento operativo por hora, día o mes.

**5.1 📊 Componentes Visuales**

<table><thead><tr><th width="171">Campo</th><th width="149.33331298828125">Tipo de gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td>KPIs Operativos</td><td>KPI / Indicador</td><td>Muestra los valores acumulados por hora de cada KPI operativo.</td></tr><tr><td>Tabla Operativa de Deltas</td><td>Tabla</td><td>Presenta el detalle horario acumulado de los KPIs, replicando exactamente la estructura del tablero en Power BI.</td></tr><tr><td>Filtros Globales</td><td>Filtros</td><td>Permiten segmentar la información por partner, país, fecha y hora.</td></tr></tbody></table>

***

**5.2 📌 KPIs incluidos**

Todos los KPIs se calculan con **lógica de acumulado horario**, reiniciando diariamente a las 00:00 y calculándose de forma independiente por país y partner.

<table><thead><tr><th width="242.6666259765625">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Registros</code></strong></td><td>Total acumulado de registros generados durante el día.</td></tr><tr><td><strong><code>Bonos deportivos</code></strong></td><td>Monto acumulado de bonos deportivos otorgados.</td></tr><tr><td><strong><code>Premios bonos</code></strong></td><td>Total acumulado de premios asociados a bonos.</td></tr><tr><td><strong><code>Bonos casino</code></strong></td><td>Monto acumulado de bonos de casino.</td></tr><tr><td><strong><code>Primer depósito</code></strong></td><td>Total acumulado de primeros depósitos realizados.</td></tr><tr><td><strong><code>Apuestas casino</code></strong></td><td>Monto acumulado de apuestas realizadas en casino.</td></tr><tr><td><strong><code>Apuestas deportivas</code></strong></td><td>Monto acumulado de apuestas deportivas realizadas.</td></tr></tbody></table>

***

**5.3 📋 Tabla Operativa de Deltas**

La tabla replica exactamente la visualización existente en Power BI, incluyendo columnas, orden, formatos, colores y alertas.

<table><thead><tr><th width="208.33331298828125">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Día al que corresponde el acumulado.</td></tr><tr><td><strong><code>Hora</code></strong></td><td>Hora del día en formato 24 horas.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado a la operación.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner correspondiente al registro.</td></tr><tr><td><strong><code>Registros</code></strong></td><td>Valor acumulado de registros hasta la hora indicada.</td></tr><tr><td><strong><code>Bonos deportivos</code></strong></td><td>Valor acumulado de bonos deportivos.</td></tr><tr><td><strong><code>Premios bonos</code></strong></td><td>Valor acumulado de premios de bonos.</td></tr><tr><td><strong><code>Bonos casino</code></strong></td><td>Valor acumulado de bonos de casino.</td></tr><tr><td><strong><code>Primer depósito</code></strong></td><td>Valor acumulado de primeros depósitos.</td></tr><tr><td><strong><code>Apuestas casino</code></strong></td><td>Valor acumulado de apuestas de casino.</td></tr><tr><td><strong><code>Apuestas deportivas</code></strong></td><td>Valor acumulado de apuestas deportivas.</td></tr></tbody></table>

***

***

#### ✅ 6. Validaciones y reglas de negocio

* Todos los KPIs siguen una lógica de acumulado horario diario.
* El acumulado se reinicia automáticamente a las 00:00 de cada día.
* El cálculo del acumulado es independiente por:
  * País
  * Partner
  * KPI
* En horas sin movimientos, el valor se hereda de la hora anterior.
* No se muestran ceros por ausencia de movimiento, salvo que el valor real del KPI sea cero.
* El cambio de fecha reinicia correctamente el acumulado diario.
* No se mezclan acumulados entre países, partners o KPIs.
* La información se actualiza automáticamente cada hora desde la base de datos.
* El tablero permite consultar información histórica.

***

#### 🕒 7. Control de Versiones

<table><thead><tr><th width="99.66665649414062">Versión</th><th width="150.6666259765625">Fecha</th><th width="180">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td></td><td>Ronald Peláez</td><td>Documento inicial</td></tr></tbody></table>
