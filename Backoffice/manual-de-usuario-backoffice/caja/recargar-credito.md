# Recargar Crédito

<mark style="color:$info;">Permite acreditar crédito al saldo de los usuarios de la plataforma, de forma individual a partir de la búsqueda del usuario o de forma masiva mediante la carga de un archivo CSV. Se utiliza cuando es necesario cargar saldo a una o varias cuentas desde la caja del BackOffice.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Caja > Recarga de Crédito

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (356).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección recargar crédito.</p></figcaption></figure>

***

### 3. Acciones de usuario

<table><thead><tr><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="recargar-credito.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los datos para identificar al usuario al que se realizará la recarga de crédito.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="recargar-credito.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos, muestra la información del usuario y habilita el formulario de recarga individual.</td></tr><tr><td><a href="recargar-credito.md#id-6.-recarga-individual"><strong>Recargar</strong></a></td><td>Acredita al usuario consultado el valor ingresado en el formulario de recarga individual.</td></tr><tr><td><a href="recargar-credito.md#id-7.-recarga-masiva"><strong>Cargar CSV</strong></a></td><td>Realiza recargas de crédito a varios usuarios a la vez mediante la carga de un archivo CSV.</td></tr></tbody></table>

***

### 4. Filtros

{% hint style="info" %}
**Nota:** No es obligatorio completar todos los filtros. Un solo filtro es suficiente para ejecutar la consulta.
{% endhint %}

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Número del cliente</code></strong></td><td>Campo numérico</td><td>Localiza al usuario por el identificador único de su cuenta en la plataforma.</td></tr><tr><td><strong><code>Cédula del cliente</code></strong></td><td>Campo numérico</td><td>Busca al usuario por el número de documento de identidad registrado en su cuenta.</td></tr><tr><td><strong><code>Email del cliente</code></strong></td><td>Campo de texto</td><td>Identifica al usuario por el correo electrónico asociado a su cuenta.</td></tr><tr><td><strong><code>Número de teléfono</code></strong></td><td>Campo numérico</td><td>Ubica al usuario por el número de teléfono registrado en su cuenta.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliegan los datos del usuario encontrado junto con el formulario de recarga individual.

<table><thead><tr><th width="176">Campo</th><th width="120">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nro. de cliente</code></strong></td><td>Numérico</td><td>Muestra el identificador único de la cuenta del usuario dentro de la plataforma.</td></tr><tr><td><strong><code>Nombre del cliente</code></strong></td><td>Texto</td><td>Presenta el nombre completo del usuario, para confirmar que la recarga se hará a la cuenta correcta.</td></tr><tr><td><strong><code>País</code></strong></td><td>Texto</td><td>Indica el país en el que está registrado el usuario.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Texto</td><td>Corresponde a la moneda de la cuenta del usuario. El valor de la recarga se acredita en esta moneda.</td></tr></tbody></table>

***

### 6. Recarga individual

Después de consultar al usuario, el formulario de recarga permite ingresar el monto y ejecutar la operación.

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor a recargar</code></strong></td><td>Campo numérico</td><td>Define el monto que se acreditará al saldo del usuario.</td></tr><tr><td><strong><code>Confirmar valor</code></strong></td><td>Campo numérico</td><td><p>Repite el monto ingresado en <strong><code>Valor a recargar</code></strong>. Existe para evitar recargas por un valor equivocado debido a un error de digitación.</p></td></tr><tr><td><strong><code>Recargar</code></strong></td><td>Botón</td><td><p>Ejecuta la recarga y despliega una ventana de confirmación. Después de confirmar, el sistema solicita el tipo de factura que se genera como comprobante. Los dos tipos disponibles se describen a continuación.</p></td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
**Tipos de factura**

<table><thead><tr><th width="132">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>POS</strong></td><td>Genera la factura en formato compacto, pensado para las impresoras de tickets de los puntos de venta.</td></tr><tr><td><strong>Carta</strong></td><td>Genera la factura en PDF tamaño carta, con una visualización más amplia y detallada del comprobante.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

### 7. Recarga masiva

El botón **Cargar CSV** permite recargar crédito a varios usuarios en una sola operación mediante un archivo <a href="https://virtualsoft.gitbook.io/untitled/glosario/#csv">CSV</a>.

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cargar archivo CSV</code></strong></td><td>Archivo CSV</td><td><p>Recibe el archivo con los usuarios y los montos que se van a recargar.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El archivo lleva en la primera columna el ID del usuario y en la segunda el monto a recargar.</p></div></td></tr></tbody></table>

Para completar la recarga masiva:

1. El usuario selecciona el archivo y presiona **Guardar**.
2. El sistema muestra el nombre del archivo cargado y el listado de usuarios con los valores a recargar.
3. El usuario revisa el listado y presiona nuevamente **Guardar** para ejecutar la recarga.

***

### 8. Validaciones y reglas del negocio:

* La consulta requiere al menos uno de los filtros.
* La recarga individual se habilita solo después de consultar a un usuario.
* Los campos **`Valor a recargar`** y **`Confirmar valor`** deben coincidir.
* En la recarga masiva, la recarga se ejecuta solo al presionar **Guardar** por segunda vez, después de revisar el listado.

***

### 9. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>09/01/2026</td><td>David Velasquez</td><td>Actualización de formato.</td></tr><tr><td>1.1</td><td>09/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
