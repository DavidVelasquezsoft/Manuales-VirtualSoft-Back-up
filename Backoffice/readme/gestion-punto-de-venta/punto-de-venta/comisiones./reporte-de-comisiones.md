---
description: >-
  Permite consultar las comisiones generadas por punto de venta y gestionar su
  aprobación y pago.
---

# Reporte de comisiones

### 1. Acceso al Módulo

**Ruta de Acceso:**  **Ruta de acceso**: Backoffice > Gestión punto de venta > punto de venta >buscar un punto de venta > 📁> 📁 > 🔎 > Comisiones > reporte de comisiones

{% @guideflow/guideflow-embed requestedUrl="https://app.guideflow.com/player/zpel63wa3k" %}

***

### 2.  Acciones disponibles

<table><thead><tr><th width="102.00006103515625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-comisiones.md#id-4.-filtros"><strong>Filtrar</strong></a></td><td>Permite definir los criterios de búsqueda del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros a su estado inicial.</td></tr><tr><td><a href="reporte-de-comisiones.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros seleccionados.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 3. Filtros

<table><thead><tr><th width="117.6363525390625">Campo</th><th width="171">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el período del reporte.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Define el tipo de reporte (<em>Ejemplo: Mensual o diario</em>).</td></tr></tbody></table>

***

### 4. Resultados de Consulta

Al ejecutar la búsqueda, el sistema muestra la siguiente información:

<table><thead><tr><th width="143.00006103515625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>TypeName</code></strong></td><td>indicador de tipo de comisión generada (<em>Ej: Deposito por transacción, nota retiro, deposito punto de venta</em>)</td></tr><tr><td><strong><code>Acciones</code></strong></td><td>Por cada registro de comisión, el sistema permite aprobarla mediante el botón ✔️.<br>Una vez aprobada, <strong>se habilitará el botón</strong> 💳 para seleccionar el <strong>tipo de saldo</strong> <em>(saldo deposito o saldo retiro)</em> con el que se realizará el abono. Finalmente, deberá <strong>confirmar la operación</strong> para <strong>acreditar la comisión al punto de venta</strong> según el saldo seleccionado.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del registro de comisión.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador del usuario asociado al punto de venta.</td></tr><tr><td><strong><code>Usuario REF</code></strong></td><td>Referencia del usuario en el sistema.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha en la que se generó el registro.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Tipo de moneda del registro.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Valor total de apuestas realizadas en el período.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Valor total de premios pagados.</td></tr><tr><td><strong><code>Bonos</code></strong></td><td>Valor correspondiente a bonos aplicados.</td></tr><tr><td><strong><code>Valor Base</code></strong></td><td>Base utilizada para el cálculo de la comisión.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Valor calculado de la comisión.</td></tr><tr><td><strong><code>Valor Pagado</code></strong></td><td>Monto efectivamente pagado al punto de venta.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del registro. (<em>Pendiente, Activo, Inactivo</em>)</td></tr><tr><td><strong><code>Modificado</code></strong></td><td>Indica si el registro ha sido modificado.</td></tr></tbody></table>

***

### 5. **Validaciones y reglas del negocio**

* El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el módulo no será visible.
* Es obligatorio seleccionar al menos un **rango de fechas** para poder realizar la consulta.
* El botón **Consultar** ejecuta la búsqueda únicamente cuando existen criterios definidos.

***

### 6. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="111.88885498046875">Versión</th><th width="151.272705078125">Fecha</th><th width="168.727294921875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/02/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>20/04/2026</td><td>Karol Navia</td><td>Refinamiento manual</td></tr></tbody></table>

</details>
