# Dashboard Bonos

Este dashboard contiene información sobre los bonos creados para la plataforma Usuarios online.

### 1. Acceso al Módulo

**Ruta de acceso**: [URL](https://reporting.virtualsoft.tech/MicroStrategyLibrary/app/3394329B42569ED3E0CDD1AABE6F7740/057E86A249AAAB095A66B491C9C95952/W6E684F240A58418DBAF3C3DA0DB0A31A--K46)

***

### 2. 🖼️️ Visualización

<figure><img src="../../../.gitbook/assets/image (33) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla dashboard bonos.</p></figcaption></figure>

***

### 3. Filtros

<table><thead><tr><th width="162">Campo</th><th width="147">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Desplegable</td><td>Filtra por los bonos generados para ese partner</td></tr><tr><td><strong><code>País</code></strong></td><td>Desplegable</td><td>Filtra por los bonos generados para ese país</td></tr><tr><td><strong><code>ID Bono</code></strong></td><td>Numérico / Buscador</td><td>Filtra por el id del bono creado</td></tr><tr><td><strong><code>Tipo de Bono</code></strong></td><td>Desplegable</td><td>Filtra por tipo de bono y agrupa por verticales.</td></tr><tr><td><strong><code>Estado general bono</code></strong></td><td>Desplegable</td><td>Filtra según estado actual del bono (activo, inactivo).</td></tr><tr><td><strong><code>Nombre bono</code></strong></td><td>Texto / Buscador</td><td>La información del tablero se visualizará solo por el nombre del bono.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Desplegable</td><td>Filtra la información reflejada en el tablero según un rango de fechas establecido.</td></tr></tbody></table>

***

#### 3.1 Indicadores KPI’s

<table><thead><tr><th width="289">Nombre del campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cant Redimido Vertical</code></strong></td><td>Total de bonos que se redimieron en todas las verticales.</td></tr><tr><td><strong><code>Usuarios redimieron</code></strong></td><td>Cantidad de usuarios que redimieron bonos.</td></tr><tr><td><strong><code>Valor total bonos</code></strong></td><td>Suma del valor total de todos los bonos.</td></tr><tr><td><strong><code>Valor total bonos deportivas</code></strong></td><td>Total del valor de bonos categoría deportivas.</td></tr><tr><td><strong><code>Valor total bonos casino</code></strong></td><td>Total del valor de bonos categoría casino.</td></tr></tbody></table>

***

#### 3.2 Gráficas

<table><thead><tr><th width="149.77783203125">Gráfica</th><th width="133">Tipo de gráfica</th><th width="500.77783203125">Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad bonos redimidos por mes</code></strong></td><td>Barras</td><td>Cantidad total de bonos redimidos en cada mes.</td></tr><tr><td><strong><code>Cantidad bonos redimidos por día</code></strong></td><td>Barras</td><td>Cantidad total de bonos redimidos en cada día.</td></tr><tr><td><strong><code>Top 7 cantidad por tipo bono</code></strong></td><td>Barras</td><td>Ranking de tipos de bono por cantidad emitida.</td></tr><tr><td><strong><code>Top 7 valor por tipo bono</code></strong></td><td>Barras</td><td>Ranking de tipos de bono por valor emitido.</td></tr><tr><td><strong><code>Cantidad de bono por CRM</code></strong></td><td>Torta</td><td>Comparativa de cantidad de bonos asociados o no a CRM.</td></tr></tbody></table>

***

**3.3 Matriz de Detalle de Bonos**

| Columna                        | Descripción                                                       |
| ------------------------------ | ----------------------------------------------------------------- |
| **`Partner`**                  | Partner para el cual se generaron los bonos.                      |
| **`País`**                     | País correspondiente al reporte generado                          |
| **`Id Bono`**                  | Identificador único del bono.                                     |
| **`Estado Bono`**              | Estado en el que se encuentra el bono al momento del reporte.     |
| **`Tipo bono`**                | Tipo de bono redimido.                                            |
| **`Nombre bono`**              | Nombre asignado al bono.                                          |
| **`Categoría campaña`**        | Clasificación general del bono.                                   |
| **`Detalle campaña`**          | Descripción del bono.                                             |
| **`Cantidad bonos otorgados`** | Cantidad total de bonos que se asignaron a un usuario.            |
| **`Valor bonos otorgados`**    | Valor total de los bonos asignados a los usuarios.                |
| **`Usuarios redimieron bono`** | Número total de usuarios distintos que han redimido el bono.      |
| **`Cantidad bono redimidos`**  | Total de bonos que fueron asignados y redimidos por los usuarios. |
| **`Valor bono redimidos`**     | Valor total de todos los bonos que fueron redimidos.              |

***

#### 3.4 Detalle por categoría.

<table><thead><tr><th width="239">Columna</th><th>Descripción.</th></tr></thead><tbody><tr><td><strong><code>Categoría campaña</code></strong></td><td>Campaña a la que pertenecen los bonos a analizar.</td></tr><tr><td><strong><code>Detalle campaña</code></strong></td><td>A que pertenece la campaña para la que fueron creados los bonos <em>(fidelización, lealtad).</em></td></tr><tr><td><strong><code>Usuarios</code></strong></td><td>Cantidad de usuarios que redimieron los bonos asignados.</td></tr><tr><td><strong><code>Valor bono</code></strong></td><td>Suma de todos los bonos que se redimieron por campaña.</td></tr><tr><td><strong><code>%bono</code></strong></td><td>Porcentaje de impacto generado por todos los bonos de esa categoría, calculado a partir de las ganancias obtenidas en las apuestas realizadas con dichos bonos.</td></tr></tbody></table>

***

### 4. Reglas y validaciones

* Las gráficas muestran siempre la información activa: si aplicas filtros, muestran lo filtrado; si seleccionas un dato en una tabla, se actualizan según esa selección.

***

### 5. 🕒Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados     |
| ------- | ---------- | ------------- | ---------------------- |
| 1.0     | 08/08/2025 | Ronald Peláez | Documento inicial      |
| 1.1     | 20/11/2025 | Ronald Peláez | Refinamiento de manual |

***
