---
description: >-
  Permite consultar los movimientos de saldo del usuario en un día en
  especifico.
---

# Historial de saldo

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Jugadores > Reportes > Historial de saldo

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (2).png" alt=""><figcaption><p>Figura #1: Captura de pantalla de reporte historial de saldo</p></figcaption></figure>

***

### 3. Acciones del usuario

<table><thead><tr><th width="201.33331298828125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="historial-de-saldo.md#id-4.-filtros"><strong>Filtrar histórico de saldos</strong></a></td><td>Permite aplicar filtros de búsqueda según usuario, fecha, país, tipo u orden.</td></tr><tr><td><a href="historial-de-saldo.md#id-4.-resultados-del-reporte"><strong>Visualizar tabla de resultados</strong></a></td><td>Presenta el detalle de los movimientos y saldos del usuario según los filtros aplicados.</td></tr><tr><td><strong>Exportar los resultados</strong></td><td>Exporta en formato Excel la tabla de los resultados según los filtros seleccionados.</td></tr></tbody></table>

***

### **4. Filtros**

<table><thead><tr><th width="128.6666259765625">Campo</th><th width="147.33331298828125">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Calendario</td><td><p>Especifica un rango de fechas para filtrar los movimientos de saldo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La consulta solo permite seleccionar un único día en especifico.</p></div></td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite filtrar resultados por país.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selector.</td><td>Clasifica el reporte según categorías específicas.<br>- <strong>Detallado</strong>: Despliega la información por usuario.<br>- <strong>Totales</strong>: Despliega la información total por la fecha generada.</td></tr></tbody></table>

***

### 5. Resultados del Reporte

La tabla de resultados presenta la siguiente información:

<table data-full-width="false"><thead><tr><th width="187">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha y hora en la que se generó el registro correspondiente al histórico.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al usuario o al registro del histórico.</td></tr><tr><td><strong><code>ID usuario</code></strong></td><td>Identificador único del usuario previamente seleccionado.</td></tr><tr><td><strong><code>Nombre Usuario</code></strong></td><td>Nombre del usuario correspondiente al registro.</td></tr><tr><td><strong><code>Saldo Inicial</code></strong></td><td>Monto disponible al inicio del período consultado.</td></tr><tr><td><strong><code>Depósitos</code></strong></td><td>Total de depósitos realizados durante el período.</td></tr><tr><td><strong><code>Ap. Deportivas</code></strong></td><td>Total apostado en eventos deportivos.</td></tr><tr><td><strong><code>Pr. Deportivas</code></strong></td><td>Total de premios obtenidos en apuestas deportivas.</td></tr><tr><td><strong><code>Ap. Casino</code></strong></td><td>Total apostado en juegos de casino.</td></tr><tr><td><strong><code>Pr. Casino</code></strong></td><td>Total de premios obtenidos en juegos de casino (incluye <em>free spins</em>).</td></tr><tr><td><strong><code>Retiros Creados</code></strong></td><td>Total de retiros registrados durante el período.</td></tr><tr><td><strong><code>Retiros Eliminados</code></strong></td><td>Total de retiros cancelados o anulados.</td></tr><tr><td><strong><code>Ajustes E</code></strong></td><td>Total de ajustes entrantes que aumentaron el saldo.</td></tr><tr><td><strong><code>Ajustes S</code></strong></td><td>Total de ajustes salientes que disminuyeron el saldo.</td></tr><tr><td><strong><code>Bonos</code></strong></td><td>Total de bonos otorgados al usuario.</td></tr><tr><td><strong><code>Saldo Final</code></strong></td><td>Monto total disponible del usuario al finalizar el período consultado.</td></tr><tr><td><strong><code>Saldo Final Calc.</code></strong></td><td>Saldo calculado automáticamente según las transacciones registradas.</td></tr><tr><td><strong><code>Retiros Pagados</code></strong></td><td>Total de retiros efectivamente pagados al usuario.</td></tr><tr><td><strong><code>Retiros Pendientes</code></strong></td><td>Total de retiros en proceso o pendientes de pago.</td></tr><tr><td><strong><code>Bonos Free Ganados</code></strong></td><td>Cantidad de bonos gratuitos obtenidos por el usuario.</td></tr></tbody></table>

> **Nota:** Al final de la tabla se muestra una fila resumen con el texto **“Total:”**, donde se reflejan los valores sumados de las columnas numéricas correspondientes.

***

### 6. Validaciones y Reglas de Negocio

* No es necesario completar todos los filtros para realizar una búsqueda.
* El saldo final registrado debe coincidir con el saldo final calculado; en caso contrario, se visualizará el desfase.
* Los resultados se ajustarán según el criterio de orden y tipo de reporte seleccionado.
* El reporte se genera por día vencido.
* El reporte se debe validar un dia a la vez, seleccionando el el campo **`Fecha de creación`** solo el día en el que se quiere consultar.
* Este reporte utiliza información de las apuestas realizadas por el usuario, en el módulo "[Reporte productos no deportivos (Por usuario)](reporte-productos-no-deportivos-por-usuario.md)".

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="106.45452880859375">Versión</th><th width="143.9091796875">Fecha</th><th width="158.8182373046875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>27/04/2026</td><td>David velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
