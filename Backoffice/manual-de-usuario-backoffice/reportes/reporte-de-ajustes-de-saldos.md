---
description: >-
  Este Reporte es una herramienta diseñada para consultar y analizar los ajustes
  realizados en los saldos de los usuarios. Proporciona información detallada
  sobre los cambios efectuados.
---

# Reporte de Ajustes de Saldos

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Ajustes de Saldos

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (585).png" alt=""><figcaption><p>Figura #1: Captura de pantalla de filtros de búsqueda.</p></figcaption></figure>

***

### 3. Funcionalidades

#### **📋 3.1 Acciones disponibles**

| Acción                         | Descripción                                                                       |
| ------------------------------ | --------------------------------------------------------------------------------- |
| Filtrar ajustes                | Permite aplicar filtros de búsqueda por ID, usuario, fecha, tipo de saldo y país. |
| Visualizar tabla de resultados | Presenta la información de los ajustes según los filtros aplicados.               |
| Ajustar saldo a los usuarios.  | Ajusta el saldo del usuario según la necesidad.                                   |

&#x20;**¿Como ajustar saldo?**

Es posible realizar 2 tipos de ajustes de saldo.

<table><thead><tr><th width="110">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td>Sumar saldo</td><td>Despliega un pop-up con el formulario para sumarle saldo al usuario. <em>(Todos los campos son obligatorios para guardar el ajuste.)</em></td></tr><tr><td>Restar saldo</td><td>Despliega un pop-up con un formulario para restarle saldo al usuario. <em>(Todos los campos son obligatorios para guardar el ajuste.)</em></td></tr></tbody></table>

<table><thead><tr><th width="154">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Usuario Id</code></td><td>ID del usuario al que se le realizará el ajuste.</td></tr><tr><td><code>Tipo saldo</code></td><td>Tipo de saldo que se le sumará al usuario. <em>(saldo de recargas o retiro).</em></td></tr><tr><td><code>Tipo ajuste</code></td><td>Motivo por el cual se le sumará el saldo al usuario.</td></tr><tr><td><code>Descripción</code></td><td>Descripción del motivo por el cual se le va a sumar el saldo al usuario.</td></tr><tr><td><code>Monto</code></td><td>Monto que se le sumará al usuario de su cuenta.</td></tr><tr><td><code>Confirmar monto</code></td><td>Confirma el monto que se le sumará al usuario de su cuenta</td></tr></tbody></table>

<table><thead><tr><th width="133">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Usuario Id</code></td><td>ID del usuario al que se le realizará el ajuste.</td></tr><tr><td><code>Tipo saldo</code></td><td>Tipo de saldo que se le restará al usuario. <em>(saldo de recargas o retiro).</em></td></tr><tr><td><code>Tipo ajuste</code></td><td>Motivo por el cual se le restará el saldo al usuario.</td></tr><tr><td><code>Descripción</code></td><td>Descripción del motivo por el cual se le va a restar el saldo al usuario.</td></tr><tr><td><code>Monto</code></td><td>Monto que se le descontará al usuario de su cuenta.</td></tr><tr><td><code>Confirmar monto</code></td><td>Confirma el monto que se le descontará al usuario de su cuenta</td></tr></tbody></table>

#### **🔎 3.3 Filtros principales**

<table><thead><tr><th width="98">Campo</th><th width="146.6666259765625">Tipo de Control</th><th width="484">Descripción</th></tr></thead><tbody><tr><td><code>ID</code></td><td>Campo de texto</td><td>Permite buscar un ajuste específico ingresando su identificador único.</td></tr><tr><td><code>ID Usuario</code></td><td>Campo de texto</td><td>Filtra los ajustes relacionados con un usuario específico mediante su ID.</td></tr><tr><td><code>Fecha de Creación</code></td><td>Calendario</td><td>Delimita los resultados según el rango de fechas en el que se realizaron los ajustes.</td></tr><tr><td><code>Tipo de Saldo</code></td><td>Lista desplegable</td><td>Filtra los resultados de acuerdo con el tipo de saldo ajustado.</td></tr><tr><td><code>País</code></td><td>Lista desplegable</td><td>Permite mostrar únicamente los ajustes realizados en un país específico.</td></tr></tbody></table>

**📊 Tabla de Resultados**

Una vez aplicada la búsqueda, los resultados se presentan en una tabla con las siguientes columnas:

<table><thead><tr><th width="203.3333740234375">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del ajuste.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador del usuario afectado.</td></tr><tr><td><strong><code>Nombre Usuario</code></strong></td><td>Nombre del usuario correspondiente al ajuste.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha en la que se registró el ajuste.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Valor ajustado en el saldo del usuario.</td></tr><tr><td><strong><code>Tipo de Ajuste</code></strong></td><td>Categoría del ajuste realizado.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Breve detalle que explica el motivo o contexto del ajuste.</td></tr><tr><td><strong><code>Tipo de Saldo</code></strong></td><td>Tipo de saldo sobre el cual se aplicó el ajuste (ej. saldo retiro, recarga).</td></tr><tr><td><strong><code>Usuario que creó</code></strong></td><td>Identificación del administrador o usuario que realizó el ajuste.</td></tr><tr><td><strong><code>Saldo Antes del Ajuste</code></strong></td><td>Monto del saldo del usuario previo a la modificación.</td></tr><tr><td><strong><code>Saldo Después del Ajuste</code></strong></td><td>Monto del saldo del usuario luego de aplicar el ajuste.</td></tr></tbody></table>

***

#### 4. Validaciones y Reglas de Negocio

* No es obligatorio completar todos los filtros para realizar una búsqueda.
* La información mostrada dependerá de los criterios seleccionados en los filtros.

***

#### 5. Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 24/09/2025 | Ronald Peláez | Documento inicial  |
