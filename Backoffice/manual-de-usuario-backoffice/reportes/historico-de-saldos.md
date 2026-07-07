---
description: >-
  El Histórico de Saldos es una herramienta que permite analizar el
  comportamiento y las operaciones de los saldos asociados a los usuarios en su
  cuenta de usuarios online.
---

# Histórico de Saldos

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Histórico de Saldos

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (46).png" alt=""><figcaption><p>Figura #1: Captura de pantalla de los filtros de búsqueda.</p></figcaption></figure>

***

### 3. Acciones del usuario

<table><thead><tr><th width="201.33331298828125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="historico-de-saldos.md#id-4.-filtros"><strong>Filtrar histórico de saldos</strong></a></td><td>Permite aplicar filtros de búsqueda según usuario, fecha, país, tipo u orden.</td></tr><tr><td><strong>Seleccionar criterio de orden</strong></td><td>Opción para ordenar resultados por Fecha de Creación, Saldo Inicial u otras columnas disponibles.</td></tr><tr><td><a href="historico-de-saldos.md#id-4.-resultados-del-reporte"><strong>Visualizar tabla de resultados</strong></a></td><td>Presenta el detalle de los movimientos y saldos del usuario según los filtros aplicados.</td></tr><tr><td><strong>Exportar los resultados</strong></td><td>Exporta en formato Excel la tabla de los resultados según los filtros seleccionados.</td></tr></tbody></table>

### **4. Filtros**

<table><thead><tr><th width="128.6666259765625">Campo</th><th width="147.33331298828125">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo de texto</td><td>Identificador único del usuario cuyo histórico se desea consultar.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Calendario</td><td>Especifica un rango de fechas para filtrar transacciones.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite filtrar resultados por país.</td></tr><tr><td><strong><code>Ordenar por</code></strong></td><td>Lista desplegable</td><td>Define el criterio de orden <em>(ejemplo: Fecha de Creación).</em></td></tr><tr><td><strong><code>Orden</code></strong></td><td>Lista desplegable</td><td>Define el orden de los resultados: <em>(Ascendente o Descendente)</em></td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selector.</td><td>Clasifica el reporte según categorías específicas.<br>- <strong>Detallado</strong>: Despliega la información por usuario.<br>- <strong>Totales</strong>: Despliega la información total por la fecha generada.</td></tr></tbody></table>

***

### 5. Resultados del Reporte

La tabla de resultados presenta la siguiente información:

<table data-full-width="true"><thead><tr><th width="187">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner asociado al registro.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha y hora en la que se generó el registro correspondiente al histórico.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al usuario o al registro del histórico.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario.</td></tr><tr><td><strong><code>Nombre Usuario</code></strong></td><td>Nombre del usuario correspondiente al registro.</td></tr><tr><td><strong><code>Saldo Inicial</code></strong></td><td>Monto disponible al inicio del período consultado.</td></tr><tr><td><strong><code>Depósitos</code></strong></td><td>Total de depósitos realizados durante el período.</td></tr><tr><td><strong><code>Ap. Deportivas</code></strong></td><td>Total apostado en eventos deportivos.</td></tr><tr><td><strong><code>Impuesto Apuesta</code></strong></td><td>Monto retenido por concepto de impuesto a las apuestas deportivas.</td></tr><tr><td><strong><code>Pr. Deportivas</code></strong></td><td>Total de premios obtenidos en apuestas deportivas.</td></tr><tr><td><strong><code>GGR Deportivas</code></strong></td><td>Ganancia bruta generada en apuestas deportivas.</td></tr><tr><td><strong><code>Retenciones Premios Deportivas</code></strong></td><td>Total retenido por impuestos sobre los premios deportivos.</td></tr><tr><td><strong><code>Ap. Casino</code></strong></td><td>Total apostado en juegos de casino.</td></tr><tr><td><strong><code>Impuesto Apuesta Casino</code></strong></td><td>Impuesto aplicado a las apuestas en juegos de casino.</td></tr><tr><td><strong><code>Pr. Casino</code></strong></td><td>Total de premios obtenidos en juegos de casino (incluye <em>free spins</em>).</td></tr><tr><td><strong><code>GGR Casino</code></strong></td><td>Ganancia bruta generada en juegos de casino.</td></tr><tr><td><strong><code>Retenciones a las Apuestas</code></strong></td><td>Monto retenido por impuestos aplicados a las apuestas de casino.</td></tr><tr><td><strong><code>Retiros Creados</code></strong></td><td>Total de retiros registrados durante el período.</td></tr><tr><td><strong><code>Retiros Eliminados</code></strong></td><td>Total de retiros cancelados o anulados.</td></tr><tr><td><strong><code>Ajustes E</code></strong></td><td>Total de ajustes entrantes que aumentaron el saldo.</td></tr><tr><td><strong><code>Ajustes S</code></strong></td><td>Total de ajustes salientes que disminuyeron el saldo.</td></tr><tr><td><strong><code>Bonos</code></strong></td><td>Total de bonos otorgados al usuario.</td></tr><tr><td><strong><code>Bonos Casino</code></strong></td><td>Bonos específicos otorgados para juegos de casino.</td></tr><tr><td><strong><code>Bonos Virtuales</code></strong></td><td>Bonos otorgados para juegos virtuales.</td></tr><tr><td><strong><code>Bonos Casino en Vivo</code></strong></td><td>Bonos otorgados para juegos de casino en vivo.</td></tr><tr><td><strong><code>Premios Jackpot Casino</code></strong></td><td>Total de premios ganados en jackpots de casino.</td></tr><tr><td><strong><code>Premios Jackpot Deportivas</code></strong></td><td>Total de premios ganados en jackpots de apuestas deportivas.</td></tr><tr><td><strong><code>Saldo Final</code></strong></td><td>Monto total disponible del usuario al finalizar el período consultado.</td></tr><tr><td><strong><code>Saldo Final Calc.</code></strong></td><td>Saldo calculado automáticamente según las transacciones registradas.</td></tr><tr><td><strong><code>Calc. Desfase</code></strong></td><td>Diferencia entre el saldo final real y el saldo calculado.</td></tr><tr><td><strong><code>Retiros Pagados</code></strong></td><td>Total de retiros efectivamente pagados al usuario.</td></tr><tr><td><strong><code>Retiros Pendientes</code></strong></td><td>Total de retiros en proceso o pendientes de pago.</td></tr><tr><td><strong><code>Bonos Free Ganados</code></strong></td><td>Cantidad de bonos gratuitos obtenidos por el usuario.</td></tr><tr><td><strong><code>Impuesto Depósito</code></strong></td><td>Total de impuestos aplicados a los depósitos.</td></tr><tr><td><strong><code>Usuarios Depositantes</code></strong></td><td>Número de usuarios que realizaron depósitos durante el período.</td></tr><tr><td><strong><code>Cantidad Depósitos</code></strong></td><td>Cantidad total de depósitos registrados.</td></tr><tr><td><strong><code>Venta Loterías</code></strong></td><td>Total de ventas registradas en juegos de lotería.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#rollback"><strong><code>Rollbacks</code></strong></a> <strong><code>de Lotería</code></strong></td><td>Total de rollbacks aplicados a las operaciones de lotería.</td></tr><tr><td><strong><code>Entradas Gamificación</code></strong></td><td>Movimientos o créditos generados por actividades de gamificación.</td></tr><tr><td><strong><code>Salidas Gamificación</code></strong></td><td>Movimientos o débitos generados por actividades de gamificación.</td></tr></tbody></table>

> **Nota:** Al final de la tabla se muestra una fila resumen con el texto **“Total:”**, donde se reflejan los valores sumados de las columnas numéricas correspondientes.

***

### 6. Validaciones y Reglas de Negocio

* No es necesario completar todos los filtros para realizar una búsqueda.
* El saldo final registrado debe coincidir con el saldo final calculado; en caso contrario, se visualizará el desfase.
* Los resultados se ajustarán según el criterio de orden y tipo de reporte seleccionado.
* El reporte se genera por día vencido.
* Este reporte utiliza información de las apuestas realizadas por los usuarios, en el módulo "[Reporte productos no deportivos](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/reporte-productos-no-deportivos-por-usuario)".
* La información del reporte Histórico de Saldo debe coincidir con el dashboard [**Desfaces Jugadores**](https://app.gitbook.com/s/qV6PKDTPGEG39u2whMHJ/library/explorar-carpetas/configuracion-de-tableros/desfases-jugadores), considerando la misma vista de comparación (_detallada o por totales_). Pueden presentarse diferencias únicamente por criterios de redondeo, sin afectar el valor total de los resultados.

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="106.45452880859375">Versión</th><th width="143.9091796875">Fecha</th><th width="158.8182373046875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>25/09/2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>29/01/2025</td><td>Ronald Peláez</td><td>Refinamiento de manual</td></tr><tr><td>1.2</td><td>20/04/2025</td><td>Karol Navia</td><td>Refinamiento de manual</td></tr></tbody></table>

</details>
