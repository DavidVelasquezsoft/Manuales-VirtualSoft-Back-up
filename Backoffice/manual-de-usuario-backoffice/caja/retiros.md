---
description: >-
  Permite generar un retiro por un punto de venta, y visualizar los retiros
  previamente realizados.
---

# Retiros

### 1. Acceso al Módulo

Ruta de Acceso: Backoffice > Caja > Retiros

### 2. 🖼️ Visualización

<figure><img src="../../.gitbook/assets/image (363).png" alt=""><figcaption><p>Figura #1: Captura de pantalla retiros.</p></figcaption></figure>

### 3. 🧑‍💻 Acciones disponibles

<table><thead><tr><th width="150.888916015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="retiros.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten buscar retiros realizados anteriormente por un punto de venta.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="retiros.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los retiros que cumplen con los criterios definidos.</td></tr><tr><td><a href="retiros.md#id-3.3.-retirar"><strong>Retirar</strong></a></td><td>Permite crear un nuevo retiro mediante un formulario.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

#### 3.1. 🔎 Filtros

<table><thead><tr><th width="118.3333740234375">Campo</th><th width="137.11114501953125">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar un rango de fechas para visualizar los retiros realizados.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Texto / Numérico</td><td>Permite filtrar los retiros por el identificador del retiro.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los retiros según el estado en el que se encuentren.</td></tr></tbody></table>

#### 3.2. 🚀 Consultar

Muestra en la parte inferior la lista de retiros que cumplen con los filtros aplicados.

<table><thead><tr><th width="190.888916015625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>Identificador único del retiro.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Nombre del usuario que realizó el retiro.</td></tr><tr><td><strong><code>Número de cuenta</code></strong></td><td>Número de la cuenta bancaria a la que se realizó el retiro.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha en la que se creó el retiro.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto solicitado para el retiro.</td></tr><tr><td><strong><code>Impuesto</code></strong></td><td>Monto de impuesto aplicado al retiro.</td></tr><tr><td><strong><code>Valor final</code></strong></td><td>Monto final que recibirá el usuario después de impuestos.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del retiro.</td></tr><tr><td><strong><code>Fecha de pago</code></strong></td><td>Fecha en la que se realizó el pago del retiro.</td></tr></tbody></table>

#### 3.3.  Retirar

Permite crear un nuevo retiro desplegando un pop-up donde se deben completar los siguientes campos:

<table><thead><tr><th width="158.33331298828125">Campo</th><th width="147.33331298828125">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor</code></strong></td><td>Numérico</td><td>Permite indicar el monto que se desea retirar.</td></tr><tr><td><strong><code>Cuenta</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar la cuenta bancaria a la cual se enviará el monto del retiro.</td></tr><tr><td><strong><code>Saldo a retirar</code></strong></td><td>Lista desplegable</td><td>Permite especificar el tipo de saldo que se va a retirar.</td></tr><tr><td><strong><code>Cupo de venta</code></strong></td><td>Lista desplegable</td><td><p>Indica que el retiro corresponde a saldo generado por cupo de venta. Al seleccionar esta opción, se habilita el siguiente campo:.</p><ul><li><strong><code>¿Es para reembolso?</code></strong>: Permite indicar si el retiro corresponde a un saldo para reembolso o no.</li></ul></td></tr><tr><td><strong><code>Comisiones</code></strong></td><td>Lista desplegable</td><td><p>Indica que el retiro corresponde al saldo por concepto de comisiones. Al seleccionar esta opción, se habilita el siguiente campo:.</p><ul><li><strong><code>Cargar factura PDF</code></strong>: Permite cargar la factura correspondiente a las comisiones indicadas.</li></ul></td></tr></tbody></table>

### 4. 🕓 Control de Versiones

<table><thead><tr><th width="141.88885498046875">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>23/01/2026</td><td>David Velásquez</td><td>Actualización de formato.</td></tr></tbody></table>
