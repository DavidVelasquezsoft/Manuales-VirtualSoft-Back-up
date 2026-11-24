# Recargar Agentes

<mark style="color:$info;">Acredita crédito al saldo de los agentes desde la caja del punto de venta. Consulta al agente por su identificador, su nombre o el punto de venta asociado y genera la factura de la recarga.</mark>

{% hint style="warning" %}
**Nota:** El menú **Caja** está disponible únicamente para los usuarios de tipo punto de venta.
{% endhint %}

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Caja > Recargar Agentes

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (198).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección recargar agentes.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="recargar-agentes.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los datos para identificar al agente al que se realizará la recarga de crédito.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="recargar-agentes.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos, muestra la información del agente y habilita el formulario de recarga.</td></tr><tr><td><a href="recargar-agentes.md#id-6.-recarga-del-agente"><strong>Recargar</strong></a></td><td>Acredita al agente consultado el valor ingresado en el formulario de recarga.</td></tr></tbody></table>

***

### 4. Filtros

{% hint style="warning" %}
**Nota:** No es obligatorio completar todos los filtros. Un solo filtro es suficiente para ejecutar la consulta.
{% endhint %}

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID usuario</code></strong></td><td>Campo numérico</td><td>Localiza al agente por el identificador único de su cuenta en la plataforma.</td></tr><tr><td><strong><code>Agente</code></strong></td><td>Campo de texto</td><td>Busca al agente por su nombre.</td></tr><tr><td><strong><code>Punto de venta</code></strong></td><td>Campo de texto</td><td>Identifica al agente a partir del nombre del punto de venta al que está asociado.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliegan los datos del agente encontrado junto con el formulario de recarga.

<table><thead><tr><th width="176">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nro. de cliente</code></strong></td><td>Muestra el identificador único de la cuenta del agente dentro de la plataforma.</td></tr><tr><td><strong><code>Nombre del cliente</code></strong></td><td>Presenta el nombre completo del agente, para confirmar que la recarga se hará a la cuenta correcta.</td></tr><tr><td><strong><code>País</code></strong></td><td>Indica el país en el que está registrado el agente.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Corresponde a la moneda de la cuenta del agente. El valor de la recarga se acredita en esta moneda.</td></tr></tbody></table>

***

### 6. Recarga del agente

Después de consultar al agente, el formulario de recarga permite ingresar el monto y ejecutar la operación.

<table><thead><tr><th width="118.5">Campo</th><th width="110.33331298828125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor a recargar</code></strong></td><td>Campo numérico</td><td>Define el monto que se acreditará al saldo del agente.</td></tr><tr><td><strong><code>Confirmar valor</code></strong></td><td>Campo numérico</td><td>Repite el monto ingresado en <strong><code>Valor a recargar</code></strong>. Existe para evitar recargas por un valor equivocado debido a un error de digitación.</td></tr><tr><td><strong><code>Recargar</code></strong></td><td>Botón</td><td>Ejecuta la recarga y despliega una ventana de confirmación. Después de confirmar, el sistema solicita el tipo de factura que se genera como comprobante. Los dos tipos disponibles se describen a continuación.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
**Tipos de factura**

<table><thead><tr><th width="100">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>POS</strong></td><td>Genera la factura en formato compacto, pensado para las impresoras de tickets de los puntos de venta.</td></tr><tr><td><strong>Carta</strong></td><td>Genera la factura en PDF tamaño carta, con una visualización más amplia y detallada del comprobante.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

### 7. Validaciones y reglas del negocio:

* La consulta requiere al menos uno de los filtros.
* El formulario de recarga se habilita solo después de consultar a un agente.
* Los campos **`Valor a recargar`** y **`Confirmar valor`** deben coincidir.
* La recarga se ejecuta solo después de aceptar la ventana de confirmación.
* El valor se acredita en la moneda de la cuenta del agente.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>09/01/2026</td><td>David Velasquez</td><td>Actualización de formato.</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
