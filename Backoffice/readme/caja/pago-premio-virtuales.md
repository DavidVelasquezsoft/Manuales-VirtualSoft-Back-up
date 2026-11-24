# Pago premio virtuales

<mark style="color:$info;">Consulta los tickets de las apuestas de juegos virtuales realizadas en el punto de venta y paga el premio de los tickets ganadores.</mark>

{% hint style="warning" %}
**Nota:** El menú **Caja** está disponible únicamente para los usuarios de tipo punto de venta.
{% endhint %}

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Caja > Pago premio virtuales

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (362).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección pago premio virtuales.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="pago-premio-virtuales.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los datos del ticket que se va a consultar.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="pago-premio-virtuales.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra el estado del ticket, la información del pago y el detalle de la apuesta.</td></tr><tr><td><a href="pago-premio-virtuales.md#id-6.-pagar-premio"><strong>Pagar Premio</strong></a></td><td>Paga el premio de un ticket ganador y genera la factura del pago.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

Los datos del [ticket](https://virtualsoft.gitbook.io/untitled/glosario/#ticket) se encuentran en el comprobante de la apuesta. En el módulo [GoldenRace](../goldenrace.md), este comprobante se genera con el botón **Imprimir**.

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>No. Ticket</code></strong></td><td>Campo numérico</td><td><p>Identifica el ticket por el número impreso en el comprobante de la apuesta.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El campo se completa automáticamente al escanear el <strong>primer código de barras</strong> del comprobante.</p></div></td></tr><tr><td><strong><code>Clave Ticket</code></strong></td><td>Campo de texto</td><td><p>Corresponde a la clave impresa en el comprobante, que se valida junto con el número del ticket.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El campo se completa automáticamente al escanear el <strong>segundo código de barras</strong> del comprobante.</p></div></td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, el sistema muestra el estado del ticket y, en la parte inferior de la pantalla, la información del pago y el detalle de la apuesta.

<table><thead><tr><th width="176">Estado del ticket</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Ticket Ganador</strong></td><td>La apuesta resultó ganadora. Si el premio aún no se ha pagado, se habilita el botón <strong>Pagar Premio</strong>.</td></tr><tr><td><strong>Ticket Perdedor</strong></td><td>La apuesta resultó perdedora y no genera premio.</td></tr><tr><td><strong>Ticket Pendiente</strong></td><td>El evento virtual de la apuesta aún no ha finalizado.</td></tr></tbody></table>

#### 5.1. Información del pago

<table><thead><tr><th width="176">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor a pagar</code></strong></td><td>Indica el monto que el punto de venta entrega al usuario cuando la apuesta es ganadora.</td></tr><tr><td><strong><code>Valor apostado</code></strong></td><td>Muestra el monto que el usuario invirtió en la apuesta.</td></tr><tr><td><strong><code>Impuesto</code></strong></td><td>Corresponde al valor de impuestos aplicado a la apuesta.</td></tr><tr><td><strong><code>Premio proyectado</code></strong></td><td>Presenta el monto estimado que el usuario puede ganar si la apuesta resulta ganadora.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Señala la situación de la apuesta <em>(Ganada, Perdida o Pendiente)</em>.</td></tr><tr><td><strong><code>Ganador</code></strong></td><td>Confirma si la apuesta resultó ganadora o no.</td></tr></tbody></table>

#### 5.2. Detalle del ticket

<table><thead><tr><th width="176">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ticket ID</code></strong></td><td>Muestra el identificador único generado para el ticket.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Indica el proveedor de juegos virtuales con el que se realizó la apuesta.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Presenta el nombre del juego virtual en el que se realizó la apuesta.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Corresponde al identificador del usuario que realizó la apuesta.</td></tr></tbody></table>

***

### 6. Pagar Premio

El botón **Pagar Premio** se muestra solo cuando el ticket está en estado **Ganador** y el premio aún no se ha pagado.

<table><thead><tr><th width="106.83331298828125">Campo</th><th width="132.8333740234375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Pagar Premio</code></strong></td><td>Botón</td><td>Inicia el pago del premio. Antes de finalizar, el sistema solicita el tipo de factura que se entrega al usuario como comprobante. Los dos tipos disponibles se describen a continuación.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
**Tipos de factura**

<table><thead><tr><th width="100">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>POS</strong></td><td>Genera la factura en formato compacto, pensado para las impresoras de tickets de los puntos de venta.</td></tr><tr><td><strong>Carta</strong></td><td>Genera la factura en PDF tamaño carta, con una visualización más amplia y detallada del comprobante.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

Al seleccionar el tipo de factura, el sistema finaliza el pago del premio.

***

### 7. Validaciones y reglas del negocio:

* El pago se habilita únicamente para tickets en estado **Ganador** que aún no se han pagado.
* Los tickets en estado **Perdedor** o **Pendiente** no habilitan el pago.
* Un ticket ya pagado no se puede pagar de nuevo.
* Los campos **`No. Ticket`** y **`Clave Ticket`** se completan automáticamente al escanear los códigos de barras del comprobante.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>23/01/2026</td><td>David Velasquez</td><td>Actualización de formato.</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
