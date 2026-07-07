---
description: >-
  Permite visualizar un historial detallado de las comisiones generadas por
  operaciones realizadas en la plataforma
---

# Reporte de Comisiones detallado

### 1. Acceso al Módulo

**Ruta de acceso**: Agentes > Lista de Agentes > Consultar > 🔍 > comisiones > Reporte de comisiones detallado.

***

### 2. Visualización:

<figure><img src="../../../.gitbook/assets/image (530).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección reporte de comisiones.</p></figcaption></figure>

### 3. Funcionalidades

#### 3.1 Filtros de Búsqueda

<table><thead><tr><th width="121">Campo</th><th width="196.199951171875">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Permite seleccionar el rango de fechas a consultar.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el tipo de comisión a consultar.</td></tr></tbody></table>

#### 3.2 Resultado de la Consulta

Una vez aplicada la búsqueda, se despliega una tabla con los siguientes campos:

<table><thead><tr><th width="135.5999755859375">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>TypeName</code></strong></td><td>Tipo de comisión u operación (ej. Sportbook NGR).</td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del registro.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>ID del usuario relacionado con la operación.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha en que se registró la operación.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del registro (ej. Activo, Inactivo).</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda utilizada en la operación (ej. PEN).</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Monto total apostado.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Valor total de premios pagados.</td></tr><tr><td><strong><code>Bonos</code></strong></td><td>Valor de los Bonos otorgados durante el periodo.</td></tr><tr><td><strong><code>Valor Base</code></strong></td><td>Monto base utilizado para el cálculo de la comisión.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Valor total de comisión generada.</td></tr><tr><td><strong><code>Valor Pagado</code></strong></td><td>Monto final pagado al afiliado o usuario.</td></tr><tr><td><strong><code>Modificado</code></strong></td><td>Indica si el registro ha sido editado desde su creación.</td></tr></tbody></table>

### 4. Reglas de Negocio

* El reporte se actualiza en tiempo real con base en las fechas y tipo seleccionados...
* En casos especiales como el modelo de Perú (impuesto del 12%), el valor base se calcula como NGR Neto.
* Cuando un registro no se visualiza en este reporte es porque no aplica para comisión. Un ejemplo de flujo en el que no aplica es: **Depósito → Retiro → Depósito** según los parámetros configurados.
* Para acceder a este módulo es necesario tener previamente el permiso correspondiente.

### 5. Control de Versiones

<table><thead><tr><th>Versión</th><th>Fecha</th><th>Autor</th><th width="185">Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2025-08-01</td><td>Karol Navia</td><td>Documento inicial.</td></tr></tbody></table>
