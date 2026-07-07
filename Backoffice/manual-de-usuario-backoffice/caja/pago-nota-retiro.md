---
description: >-
  Permite pagar las notas de retiro que generen los usuarios desde la
  plataforma.
---

# Pago Nota Retiro

### 1. Acceso al Módulo

Ruta de Acceso: Backoffice > Caja > Nota de Retiro

***

### 2. 🖼️ Visualización

<figure><img src="../../.gitbook/assets/image (275).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Pago Nota Retiro</p></figcaption></figure>

***

### 3. 🧑‍💻 Acciones disponibles

<table><thead><tr><th width="159">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="pago-nota-retiro.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten ingresar los datos requeridos para ubicar una nota de retiro específica.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los campos ingresados a su estado inicial.</td></tr><tr><td><a href="pago-nota-retiro.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Valida la información ingresada y muestra los datos de la nota de retiro.</td></tr><tr><td><a href="pago-nota-retiro.md#id-3.3.-pagar-nota-retiro"><strong>Pagar Nota Retiro</strong></a></td><td>Botón que ejecuta el pago de la nota de retiro y actualiza su estado a pagada.</td></tr></tbody></table>

#### 3.1. 🔎 Filtros

<table><thead><tr><th width="122">Campo</th><th width="116">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Nota de Retiro</code></strong></td><td>Numérico</td><td>Permite ingresar el identificador de la nota de retiro, el cual es entregado al usuario en el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ticket">ticket</a> generado.</td></tr><tr><td><strong><code>Clave</code></strong></td><td>Numérico</td><td>Permite ingresar la clave indicada en el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ticket">ticket</a> al momento de generar la nota de retiro.</td></tr></tbody></table>

#### 3.2. 🚀 Consultar

Al realizar la consulta, se mostrará la información correspondiente a la nota de retiro validada.

<table><thead><tr><th width="157">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nota de Retiro</code></strong></td><td>Identificador de la nota de retiro generada.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador del usuario que generó la nota de retiro.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre del usuario que generó la nota de retiro.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto total a pagar correspondiente a la nota de retiro.</td></tr></tbody></table>

#### 3.3. 💰 Pagar Nota Retiro

Permite ejecutar el pago de la nota de retiro consultada.\
Al seleccionar esta opción, el sistema actualiza el estado de la nota de retiro a **pagada** y realiza la entrega del monto correspondiente al usuario.

***

### 4. ✅Validaciones y reglas del negocio.

* Para poder efectuar el pago de una nota de retiro, esta debe haber sido aprobada previamente.

### 5. 🕓 Control de Versiones

<table><thead><tr><th width="141.88885498046875">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>09/01/2026</td><td>David Velásquez</td><td>Actualización de formato.</td></tr><tr><td>1.2</td><td>22/01/2026</td><td>Ronald Peláez</td><td>Agregar reglas y validaciones.</td></tr></tbody></table>
