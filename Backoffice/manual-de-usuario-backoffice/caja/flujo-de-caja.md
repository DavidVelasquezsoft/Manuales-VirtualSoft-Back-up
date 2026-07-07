---
description: >-
  Permite visualizar todas las transacciones realizadas por un usuario o los
  movimientos registrados en un punto de venta.
---

# Flujo de Caja

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Caja > Flujo de caja.

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (611).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección flujo de caja.</p></figcaption></figure>

***

### 3. Acciones de usuario

<table><thead><tr><th width="170.4444580078125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="flujo-de-caja.md#id-4.1-filtros"><strong>Filtros</strong></a></td><td>Permite filtrar la información para obtener resultados mas precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros por defecto.</td></tr><tr><td><a href="flujo-de-caja.md#id-4.2.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="140.6666259765625">Campo</th><th width="120.5">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha Inicio/Fin</td><td>Filtra los resultados dentro de un rango de fechas en específico.</td></tr><tr><td><strong><code>país</code></strong></td><td>Lista desplegable</td><td>Limita los resultados a puntos de ventas o usuarios asociados a un país específico.</td></tr><tr><td><strong><code>No. Ticket</code></strong></td><td>Numérico</td><td>Permite buscar una transacción específica ingresando su número de identificación.</td></tr></tbody></table>

### 5. Resultados de Consulta

Aplica los filtros seleccionados y muestra los registros válidos.

{% hint style="warning" %}
**Nota:** Los totales por cada punto de venta o usuario son la suma de las columnas numéricas de las transacciones asociadas al punto de venta. Estos totales se actualizan según los filtros o el rango de fechas aplicados.
{% endhint %}

<table><thead><tr><th width="253.11114501953125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Indica el día en que se realizó la transacción.</td></tr><tr><td><strong><code>Hora</code></strong></td><td>Muestra la hora exacta en que se registró la transacción.</td></tr><tr><td><strong><code>Número de Ticket</code></strong></td><td>Identificador único asignado a cada transacción.</td></tr><tr><td><strong><code>ID cliente</code></strong></td><td>Indica el identificador único del usuario que realizó la apuesta.</td></tr><tr><td><strong><code>Forma de Pago 1</code></strong></td><td>Especifica el método de pago utilizado (<em>por ejemplo: Pago Nota Cobro, Recarga Crédito, etc.</em>).</td></tr><tr><td><strong><code>Pago con Bono/T.C.</code></strong></td><td>Indica el valor pagado mediante bono o tarjeta de crédito.</td></tr><tr><td><strong><code>Valor de Entradas en Efectivo</code></strong></td><td>Monto total recibido en efectivo por apuestas o recargas.</td></tr><tr><td><strong><code>Valor de Entradas con Bono/Tarjeta de Crédito</code></strong></td><td>Monto total recibido mediante bonos o tarjetas de crédito.</td></tr><tr><td><strong><code>Valor de Entradas por Traslados</code></strong></td><td>Muestra los registros de los montos ingresados por movimientos entre puntos de venta.</td></tr><tr><td><strong><code>Valor de Entradas por Recargas</code></strong></td><td>Monto total ingresado por recargas de saldo realizadas por los usuarios.</td></tr><tr><td><strong><code>Valor de Entradas por Recargas de Agentes</code></strong></td><td>Muestra el valor de las recargas realizadas a través de agentes autorizados.</td></tr><tr><td><strong><code>Recargas Anuladas</code></strong></td><td>Indica el valor total de las recargas que fueron canceladas o anuladas.</td></tr><tr><td><strong><code>Valor de Salidas en Efectivo</code></strong></td><td>Monto total retirado en efectivo, ya sea por pagos o retiros de caja.</td></tr><tr><td><strong><code>Valor de Salidas por Traslados</code></strong></td><td>Registra los montos transferidos a otras cuentas o puntos de venta.</td></tr><tr><td><strong><code>Valor de Salidas por Notas de Retiro</code></strong></td><td>Muestra los montos retirados bajo el concepto de notas de retiro.</td></tr><tr><td><strong><code>Saldo</code></strong></td><td>Indica el saldo total después de realizar los ingresos y egresos correspondientes.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Especifica la moneda en la que se realizaron las transacciones.</td></tr></tbody></table>

***

### 6. Validaciones y reglas de negocio

* Una consulta de máximo 31 días debe completarse en un máximo de 60 segundos. Si el proceso tarda más de lo esperado, aparecerá el mensaje: **“Error: la consulta supera el tiempo máximo permitido.”.**
* Para una consulta con rango de fecha personalizado mayor a 1 mes los datos se cargarán, sin importar la cantidad de información.

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="106.14813232421875">Versión</th><th width="116.77777099609375">Fecha</th><th width="164.5555419921875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2025-11-10</td><td>David Velasquez</td><td>Actualización de formato e incorporación de validaciones.</td></tr></tbody></table>



</details>
