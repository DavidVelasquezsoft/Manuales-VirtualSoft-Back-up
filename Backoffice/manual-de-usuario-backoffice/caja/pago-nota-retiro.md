---
description: >-
  Permite pagar en el punto de venta las notas de retiro que los usuarios
  generan desde la plataforma de usuarios online. El módulo valida la nota con
  su identificador y su clave antes de registrar el pago.
---

# Pago Nota Retiro

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Caja > Nota de Retiro

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (275).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección pago nota retiro.</p></figcaption></figure>

***

### 3. Acciones de usuario

<table><thead><tr><th width="159">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="pago-nota-retiro.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los datos del ticket necesarios para ubicar una nota de retiro específica.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="pago-nota-retiro.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Valida el identificador y la clave ingresados y muestra los datos de la nota de retiro en la tabla de resultados.</td></tr><tr><td><a href="pago-nota-retiro.md#id-6.-pagar-nota-de-retiro"><strong>Pagar Nota Retiro</strong></a></td><td>Ejecuta el pago de la nota de retiro consultada y actualiza su estado a <strong>pagada</strong>.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Nota de Retiro</code></strong> <em>(obligatorio)</em></td><td>Campo numérico</td><td>Indica el identificador de la nota de retiro, que el usuario recibe en el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ticket">ticket</a> generado al solicitar el retiro.</td></tr><tr><td><strong><code>Clave</code></strong> <em>(obligatorio)</em></td><td>Campo de texto</td><td><p>Recibe la clave impresa en el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ticket">ticket</a> de la nota de retiro. Funciona como código de seguridad: confirma que quien presenta la nota es su titular.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si la clave no corresponde al <strong><code>Id Nota de Retiro</code></strong> ingresado, el sistema muestra mensaje de error y no presenta los datos de la nota.</p></div></td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliegan los datos de la nota de retiro validada.

<table><thead><tr><th width="176">Campo</th><th width="120">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nota de Retiro</code></strong></td><td>Numérico</td><td>Muestra el identificador de la nota de retiro consultada.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Numérico</td><td>Corresponde al identificador del usuario que generó la nota de retiro.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Presenta el nombre del usuario titular de la nota, para que el cajero lo compare con el documento de quien se presenta a cobrar.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Numérico</td><td>Indica el monto total que debe pagarse al usuario por la nota de retiro.</td></tr></tbody></table>

***

### 6. Pagar nota de retiro

Después de consultar la nota, el botón **Pagar Nota Retiro** ejecuta el pago. El sistema actualiza el estado de la nota de retiro a **pagada** y registra la entrega del monto al usuario.

{% hint style="warning" %}
**Nota:** Antes de pagar, el cajero verifica que el **`Nombre`** y el **`Valor`** coincidan con el ticket presentado.
{% endhint %}

***

### 7. Validaciones y reglas del negocio:

* Los campos **`Id Nota de Retiro`** y **`Clave`** son obligatorios para ejecutar la consulta.
* Solo pueden pagarse notas de retiro **aprobadas** previamente.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>09/01/2026</td><td>David Velasquez</td><td>Actualización de formato.</td></tr><tr><td>1.2</td><td>22/01/2026</td><td>Ronald Peláez</td><td>Agregar reglas y validaciones.</td></tr><tr><td>1.3</td><td>09/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
