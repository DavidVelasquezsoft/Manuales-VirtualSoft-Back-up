---
description: >-
  Permite analizar las transacciones de un punto de venta, facilitando el
  control de ingresos, salidas y el cálculo del saldo disponible.
---

# Flujo de Caja Resumido

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Flujo de Caja Resumido

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FAiun1fE4QUmCbXmATO5u%2Fimage.png?alt=media&#x26;token=71dc5319-479d-48f1-a7a7-a78e698cead0" alt=""><figcaption><p>figura#1: Captura de pantalla filtros sección Flujo de Caja Resumido.</p></figcaption></figure>

***

### 3. Acciones de usuario

<table><thead><tr><th width="152">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="flujo-de-caja-resumido.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información de manera resumida o detallada para obtener resultados mas precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="flujo-de-caja-resumido.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos ya sea en vista resumida o detallada.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

### **4. Filtros**&#x20;

<table><thead><tr><th width="164.5926513671875">Campo</th><th width="155">Tipo de Control</th><th width="421.6666259765625">Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Define el rango de fechas a consultar.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra las transacciones asociadas a un país en particular.</td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el punto de venta específico.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identifica las transacciones realizadas por un usuario en particular.</td></tr><tr><td><p><strong><code>¿Con apuestas</code></strong> </p><p><strong><code>anuladas?</code></strong></p></td><td>Selección única</td><td>Incluye o excluye las apuestas anuladas.</td></tr><tr><td><p><strong><code>¿Con premios</code></strong> </p><p><strong><code>pendientes?</code></strong></p></td><td>Selección única</td><td>Determina si se deben incluir los premios pendientes en los reportes.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selección única</td><td>Permite elegir la forma de visualización del reporte: <strong>Detallado</strong> <em>(cada transacción individual)</em> o <strong>Totales</strong> <em>(resumen acumulado)</em>.</td></tr><tr><td><p><strong><code>¿Con pasarelas</code></strong> </p><p><strong><code>de pago?</code></strong></p></td><td>Selección única</td><td>Filtra las operaciones realizadas mediante pasarelas de pago.</td></tr><tr><td><strong><code>Subconcesionario</code></strong></td><td>Lista desplegable</td><td>Filtra las transacciones por subconcesionario.</td></tr></tbody></table>

### 5. Resultado de Consulta

Aplica los filtros seleccionados y presenta los resultados válidos.

<table><thead><tr><th width="270.22216796875">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Día en el que se registraron las transacciones.</td></tr><tr><td><i class="fa-ticket" style="color:$success;">:ticket:</i></td><td>Permite imprimir la factura de la transacción seleccionada.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificación del usuario asociado a la transacción.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda en la que se realizó la operación <em>(ejemplo: USD, PEN, CLP).</em></td></tr><tr><td><strong><code>Cantidad de Tickets</code></strong></td><td>Total de tickets generados en el período.</td></tr><tr><td><strong><code>Entradas en efectivo - apuestas deportivas</code></strong></td><td>Valor total ingresado en efectivo de apuestas vendidas por el punto de venta en la <a href="https://virtualsoft.gitbook.io/untitled/glosario/#vertical">vertical</a> de deportivas.</td></tr><tr><td><strong><code>Entradas en efectivo - apuestas virtuales</code></strong></td><td>Valor total ingresado en efectivo de apuestas vendidas por el punto de venta en la <a href="https://virtualsoft.gitbook.io/untitled/glosario/#vertical">vertical</a> de virtuales.</td></tr><tr><td><strong><code>Apuestas Anuladas</code></strong></td><td>Monto total de apuestas anuladas.</td></tr><tr><td><strong><code>Valor de Entradas Efectivo Neto</code></strong></td><td>Total ingresado en efectivo descontando apuestas anuladas y ajustes.</td></tr><tr><td><strong><code>Valor de Entradas Bono/T.C.</code></strong></td><td>Total de entradas con bonos o transferencias bancarias.</td></tr><tr><td><strong><code>Valor de Entradas Traslados</code></strong></td><td>Monto trasladado desde otros puntos o cuentas.</td></tr><tr><td><strong><code>Recargas Anuladas</code></strong></td><td>Total de recargas anuladas.</td></tr><tr><td><strong><code>Impuestos</code></strong></td><td>Valor total de impuestos aplicados.</td></tr><tr><td><strong><code>Salidas en efectivo - apuestas deportivas</code></strong></td><td>Valor total retirado en efectivo por premios ganados y pagados por el punto de venta en la <a href="https://virtualsoft.gitbook.io/untitled/glosario/#vertical">vertical</a> de deportivas.</td></tr><tr><td><strong><code>Salidas en efectivo - apuestas virtuales</code></strong></td><td>Valor total retirado en efectivo por premios ganados y pagados por el punto de venta en la <a href="https://virtualsoft.gitbook.io/untitled/glosario/#vertical">vertical</a> de virtuales.</td></tr><tr><td><strong><code>Apuestas Pagadas Anuladas</code></strong></td><td>Total de apuestas pagadas, pero luego anuladas.</td></tr><tr><td><strong><code>Valor de Salidas Efectivo Neto</code></strong></td><td>Valor total de salidas en efectivo descontando ajustes o anulaciones.</td></tr><tr><td><strong><code>Valor de Salidas Traslados</code></strong></td><td>Total transferido a otros puntos o cuentas.</td></tr><tr><td><strong><code>Valor de Salidas Notas de Retiro</code></strong></td><td>Monto retirado mediante notas de retiro.</td></tr><tr><td><strong><code>Saldo</code></strong></td><td>Monto final calculado como diferencia entre entradas y salidas.</td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* No es necesario completar todos los filtros para ejecutar la búsqueda.

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="102">Versión</th><th width="128.6666259765625">Fecha</th><th width="155.3333740234375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/08/2025</td><td>Ronald Peláez</td><td>Documento inicial del manual</td></tr><tr><td>2.0</td><td>19/01/2026</td><td>David velasquez</td><td>Reestructuración del módulo e incorporación de nuevos campos</td></tr></tbody></table>

</details>
