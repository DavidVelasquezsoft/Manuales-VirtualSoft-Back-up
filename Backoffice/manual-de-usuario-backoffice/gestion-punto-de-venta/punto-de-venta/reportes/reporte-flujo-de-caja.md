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

# Reporte Flujo de Caja

<mark style="color:$info;">Visualiza el consolidado de los movimientos económicos realizados por el punto de venta durante un período determinado, incluyendo apuestas, retiros, depósitos y demás operaciones que afectan el flujo de caja.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Gestión punto de venta > 🔍 Ingresar a punto de venta > Reportes > Reporte Flujo de Caja.

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (709).png" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte flujo de caja.</p></figcaption></figure>

***

### 3. Acciones de usuario

<table><thead><tr><th width="136">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/gestion-punto-de-venta/punto-de-venta/reportes/reporte-flujo-de-caja#id-4.-filtros"><strong>Filtros</strong></a></td><td>Permite consultar el flujo de caja del punto de venta mediante diferentes criterios de búsqueda.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros por defecto.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/gestion-punto-de-venta/punto-de-venta/reportes/reporte-flujo-de-caja#id-5.-resultado-de-consulta"><strong>Consultar</strong></a></td><td>Aplica los filtros configurados y obtiene los resultados de la consulta.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="135">Campo</th><th width="146">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Rango de fechas sobre el cual se consolidarán los movimientos económicos del punto de venta.</td></tr><tr><td><strong><code>No. Ticket</code></strong></td><td>Numérico</td><td>Permite consultar la información asociada a un ticket específico.</td></tr></tbody></table>

### 5. Resultado de Consulta

El reporte de **Flujo de Caja** consolida los movimientos económicos realizados por el punto de venta durante el período consultado, incluyendo apuestas, retiros, depósitos y demás operaciones que afectan el saldo de caja.

A diferencia del [**Historial de Movimientos**](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/gestion-punto-de-venta/punto-de-venta/reportes/historial-de-movimientos), este reporte presenta la información de forma consolidada, mostrando los valores totales por cada concepto para facilitar la conciliación y el control del flujo de caja.

La información se visualizará en una tabla con las siguientes columnas:

<table><thead><tr><th width="201">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se registró el movimiento.</td></tr><tr><td><strong><code>Hora</code></strong></td><td>Hora en la que se registró el movimiento.</td></tr><tr><td><strong><code>No. Ticket</code></strong></td><td>Número del ticket asociado al movimiento.</td></tr><tr><td><strong><code>Forma Pago 1</code></strong></td><td>Medio de pago utilizado para registrar el movimiento.</td></tr><tr><td><strong><code>Pago Bono / T.C.</code></strong></td><td>Valor correspondiente a pagos realizados mediante bono o tarjeta, según la configuración de la operación.</td></tr><tr><td><strong><code>Valor Entradas efectivo</code></strong></td><td>Total de ingresos en efectivo registrados durante el período consultado.</td></tr><tr><td><strong><code>Recargas Anuladas</code></strong></td><td>Total correspondiente a las recargas anuladas.</td></tr><tr><td><strong><code>Valor Entradas Bono / T.C.</code></strong></td><td>Total de ingresos registrados mediante bono o tarjeta.</td></tr><tr><td><strong><code>Valor Entradas Traslados</code></strong></td><td>Total de ingresos provenientes de traslados.</td></tr><tr><td><strong><code>Valor Entradas recargas</code></strong></td><td>Total de ingresos correspondientes a recargas.</td></tr><tr><td><strong><code>Valor Entradas Recargas Agentes</code></strong></td><td>Total de ingresos generados por recargas realizadas por agentes.</td></tr><tr><td><strong><code>Valor Salidas Efectivo</code></strong></td><td>Total de egresos realizados en efectivo.</td></tr><tr><td><strong><code>Valor Salidas Traslados</code></strong></td><td>Total de egresos correspondientes a traslados.</td></tr><tr><td><strong><code>Valor Salidas Notas de Retiro</code></strong></td><td>Total de egresos generados mediante notas de retiro.</td></tr><tr><td><strong><code>Saldo</code></strong></td><td>Saldo consolidado del flujo de caja para el período consultado.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda en la que se expresan los valores del reporte.</td></tr></tbody></table>

***

### 6. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 2026-07-23 | Ronald Peláez | Documento inicial. |

</details>
