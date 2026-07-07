---
description: >-
  Permite consultar las comisiones generadas por punto de venta y gestionar su
  aprobación y pago.
---

# Reporte de comisiones detallado

### 1. Acceso al Módulo

**Ruta de Acceso:**  Backoffice > Gestión punto de venta > Punto de venta >🔎 > Comisiones > Reporte de comisiones detallado

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (660).png" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte detallado de comisiones por punto de venta</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="104.00006103515625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-comisiones-detallado.md#id-3.1.-filtros"><strong>Filtrar</strong></a></td><td>Permite definir los criterios de búsqueda del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros a su estado inicial.</td></tr><tr><td><a href="reporte-de-comisiones-detallado.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros seleccionados.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="160">Campo</th><th width="171">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el período del reporte.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Indica el nombre exacto del tipo de comisión que se aplica al punto de venta.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selección única</td><td>Permite definir si los registros de comisión se mostrarán de manera resumida o detallada.</td></tr></tbody></table>

### 5. Resultados de Consulta

Al ejecutar la búsqueda, el sistema muestra la siguiente información:

<table><thead><tr><th width="207">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>TypeName</code></strong></td><td>indicador de tipo de comisión generada (<em>Ej: Deposito por transacción, nota retiro, deposito punto de venta</em>)</td></tr><tr><td><strong><code>Acciones</code></strong></td><td>Por cada registro de comisión, el sistema permite aprobarla mediante el botón ✔️.<br>Una vez aprobada, <strong>se habilitará el botón</strong> 💳 para seleccionar el <strong>tipo de saldo</strong> con el que se realizará el abono.<br>Finalmente, deberá <strong>confirmar la operación</strong> para <strong>acreditar la comisión al punto de venta</strong> según el saldo seleccionado.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del registro de comisión generado en el sistema.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador del usuario o punto de venta al que corresponde la comisión.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha y hora en que se generó el registro de la comisión.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda en la que se calcularon los valores de apuestas, premios y comisión.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Monto total apostado dentro del período evaluado para el cálculo de la comisión.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Monto total pagado en premios dentro del período correspondiente.</td></tr><tr><td><strong><code>Bonos</code></strong></td><td>Valor total de bonos aplicados que pueden influir en la base de cálculo.</td></tr><tr><td><strong><code>Valor Base</code></strong></td><td>Monto sobre el cual se calcula la comisión, según las reglas configuradas.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Valor final de la comisión generada para el punto de venta.</td></tr><tr><td><strong><code>Modificado</code></strong></td><td>Indica la fecha en que el registro de comisión tuvo su última modificación después de su generación automática.</td></tr><tr><td><strong><code>¿Generó comisión?</code></strong></td><td><p>Identifica si un depósito fue clasificado como una <strong>transacción sin comisión</strong>.</p><ul><li><strong>No:</strong> Indica que el depósito <strong>no generó comisión</strong>, porque cumplió las condiciones configuradas <em>(depósito realizado dentro del tiempo de exclusión después de un retiro en el mismo punto de venta y por el mismo usuario)</em>.</li><li><strong>Si:</strong> Indica que el depósito <strong>sí generó comisión</strong>, ya que <strong>no</strong> cumplió las condiciones establecidas para ser considerado como una transacción sin comisión.</li></ul></td></tr><tr><td><strong><code>External ID</code></strong></td><td>Identificador externo asociado al punto de venta o usuario en sistemas integrados.</td></tr></tbody></table>

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="102.88885498046875">Versión</th><th width="133">Fecha</th><th width="161">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/02/2026</td><td>David Velásquez</td><td>Documento inicial</td></tr><tr><td>1.2</td><td>07/04/2026</td><td>Ronald Peláez</td><td>Cambio en la columna <strong><code>NTC</code></strong> por <strong><code>¿Generó comisión?</code></strong> </td></tr></tbody></table>

</details>
