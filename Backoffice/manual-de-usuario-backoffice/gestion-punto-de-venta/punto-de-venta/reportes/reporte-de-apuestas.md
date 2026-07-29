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

# Reporte de Apuestas

<mark style="color:$info;">En este módulo es posible visualizar el historial de las apuestas deportivas realizadas por medio del punto de venta.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Gestión punto de venta > 🔍 Ingresar a punto de venta > Reportes > Reporte de Apuestas.

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (700).png" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte de Apuestas.</p></figcaption></figure>

***

### 3.  Acciones de usuario

<table><thead><tr><th width="170.4444580078125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/gestion-punto-de-venta/punto-de-venta/reportes/reporte-de-apuestas#id-4.-filtros"><strong>Filtros</strong></a></td><td>Permite buscar el historial de las apuestas realizadas por el punto de venta con la ayuda de filtros.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros por defecto.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/gestion-punto-de-venta/punto-de-venta/reportes/reporte-de-apuestas#id-5.-resultado-de-consulta"><strong>Consultar</strong></a></td><td>Aplica los filtros configurados y obtén los resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="122">Campo</th><th width="148">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Rango de fechas en el que fueron registradas las apuestas.</td></tr><tr><td><strong><code>Tiket Id</code></strong></td><td>Texto</td><td>Identificador único de la apuesta generada.</td></tr><tr><td><strong><code>Tipo de apuesta</code></strong></td><td>Lista desplegable</td><td>Permite filtrar las apuestas según su tipo.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite filtrar las apuestas según su estado actual.</td></tr><tr><td><strong><code>Con Eliminadas?</code></strong></td><td>Selector</td><td>Incluye o excluye de la consulta las apuestas eliminadas.</td></tr></tbody></table>

### 5. Resultado de Consulta

El reporte de apuestas se visualizará en una tabla que contiene las siguientes columnas:

<table><thead><tr><th width="144">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/gestion-punto-de-venta/punto-de-venta/reportes/reporte-de-apuestas#detalles-avanzados"><strong><code>🔍</code></strong></a></td><td>Permite visualizar el detalle completo de la apuesta seleccionada.</td></tr><tr><td><strong><code>Ticket Id</code></strong></td><td>Identificador único de la apuesta.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Nombre o identificación del usuario que realizó la apuesta.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual de la apuesta.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha y hora en la que se registró la apuesta.</td></tr><tr><td><strong><code>Fecha de pago</code></strong></td><td>Fecha y hora en la que fue pagado el premio, si aplica.</td></tr><tr><td><strong><code>Punto de venta pagó</code></strong></td><td>Punto de venta que realizó el pago del premio.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Valor apostado.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Valor del premio obtenido antes de impuestos.</td></tr><tr><td><strong><code>Impuesto Premios</code></strong></td><td>Valor del impuesto aplicado al premio.</td></tr><tr><td><strong><code>Impuesto Apuesta</code></strong></td><td>Valor del impuesto aplicado a la apuesta.</td></tr><tr><td><strong><code>Premio Total</code></strong></td><td>Valor total del premio después de aplicar los impuestos correspondientes.</td></tr><tr><td><strong><code>Odds</code></strong></td><td>Cuota total asociada a la apuesta.</td></tr><tr><td><strong><code>Ip</code></strong></td><td>Dirección IP desde la que fue registrada la apuesta.</td></tr><tr><td><strong><code>Billetera</code></strong></td><td>Billetera utilizada para realizar la apuesta o recibir el premio.</td></tr><tr><td><strong><code>Total</code></strong></td><td>Debajo de cada columna del reporte se visualizará una fila con el total de la suma de los valores a la respectiva columna.</td></tr></tbody></table>

<details>

<summary><strong>Detalles Avanzados</strong></summary>

**Detalles del ticket**

<table><thead><tr><th width="142">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ticket Det ID</code></strong></td><td>Identificador único del detalle de la apuesta.</td></tr><tr><td><strong><code>Ticket ID</code></strong></td><td>Identificador del ticket al que pertenece el detalle.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Información detallada correspondiente a la selección o evento asociado a la apuesta.</td></tr></tbody></table>

**Historial de transacciones**

<table><thead><tr><th width="147">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ticket Det ID</code></strong></td><td>Identificador del detalle de la apuesta relacionado con la transacción.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de transacción registrada.</td></tr><tr><td><strong><code>Ticket ID</code></strong></td><td>Identificador del ticket asociado a la transacción.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha y hora en la que se registró la transacción.</td></tr><tr><td><strong><code>Transacción Id</code></strong></td><td>Identificador único de la transacción.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Valor correspondiente a la transacción registrada.</td></tr></tbody></table>

</details>

***

### 6. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="119.14813232421875">Versión</th><th width="130.77777099609375">Fecha</th><th width="164.5555419921875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2026-07-23</td><td>Ronald Peláez</td><td>Documento inicial</td></tr></tbody></table>

</details>
