---
description: Permite realizar recargas de saldos para los agentes.
---

# Recargar Agentes

### 1. Acceso al Módulo

Ruta de Acceso: Backoffice > Caja > Recarga de Crédito

***

### 2. 🖼️ Visualización

<figure><img src="../../.gitbook/assets/image (203).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Recargar crédito agente.</p></figcaption></figure>

***

### 3. 🧑‍💻 Acciones disponibles

<table><thead><tr><th width="131">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="recargar-agentes.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten identificar al agente al que se le realizará la recarga de crédito.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros ingresados a su estado inicial.</td></tr><tr><td><a href="recargar-agentes.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Valida los filtros ingresados y muestra la información del agente junto con el formulario de recarga individual.</td></tr></tbody></table>

#### 3.1. 🔎 Filtros

> **Nota:** No es obligatorio completar todos los filtros. Con un solo filtro es posible realizar la consulta.

<table><thead><tr><th width="139">Campo</th><th width="125">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID usuario</code></strong></td><td>Numérico</td><td>Permite ingresar el identificador único del usuario a recargar.</td></tr><tr><td><strong><code>Agente</code></strong></td><td>Numérico</td><td>Permite ingresar nombre del agente</td></tr><tr><td><strong><code>Punto de venta</code></strong></td><td>Texto</td><td>Permite ingresar el nombre del punto de venta.</td></tr></tbody></table>

#### 3.2. 🚀 Consultar

Al realizar la consulta, el sistema muestra la información general del agente y habilita el formulario para la **recarga individual**.

<table><thead><tr><th width="149">Campo</th><th width="125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nro. de cliente</code></strong></td><td>Visualización</td><td>Muestra el identificador único de la cuenta del usuario dentro de la plataforma.</td></tr><tr><td><strong><code>Nombre del cliente</code></strong></td><td>Visualización</td><td>Muestra el nombre completo del usuario asociado a la cuenta.</td></tr><tr><td><strong><code>País</code></strong></td><td>Visualización</td><td>Indica el país en el que se encuentra registrado el usuario.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Visualización</td><td>Muestra la moneda configurada para la cuenta del usuario en la plataforma.</td></tr><tr><td><strong><code>Valor a recargar</code></strong></td><td>Numérico</td><td>Permite ingresar el monto que se desea acreditar al saldo del usuario.</td></tr><tr><td><strong><code>Confirmar valor</code></strong></td><td>Numérico</td><td>Permite confirmar el monto ingresado previamente para evitar errores en la recarga.</td></tr><tr><td><strong><code>Recargar</code></strong></td><td>Botón</td><td><p>Ejecuta la recarga y despliega un pop-up de confirmación para validar la operación. Tras confirmar, permite seleccionar el tipo de factura antes de completar el proceso.</p><table><thead><tr><th width="88">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>POS</code></strong></td><td>Genera la factura en un formato de impresión compacto, optimizado para impresoras de tickets utilizadas en puntos de venta.</td></tr><tr><td><strong><code>Carta</code></strong></td><td>Genera la factura en formato PDF tamaño carta, ofreciendo una visualización más amplia y detallada del comprobante.</td></tr></tbody></table></td></tr></tbody></table>

***

### 4. 🕓 Control de Versiones

<table><thead><tr><th width="141.88885498046875">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>09/01/2026</td><td>David Velásquez</td><td>Actualización de formato.</td></tr></tbody></table>
