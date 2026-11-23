# Puntos lealtad

<mark style="color:$info;">Consulta los puntos lealtad acumulados por los usuarios y asignar los puntos correspondientes a una apuesta realizada. Desde este módulo se revisa el saldo de puntos de cada cuenta, cuántos están próximos a expirar, cuántos se expiraron y cuántos ha redimido el usuario.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Puntos lealtad

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2Fns8N8BGSlnJxNpa8Tekg%2Fimage.png?alt=media&#x26;token=5711d60a-5ddb-4d88-84d7-fd89a06e996e" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Puntos lealtad.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Definen los criterios de búsqueda para consultar los puntos lealtad de los usuarios.</td></tr><tr><td><strong>Consultar</strong></td><td>Ejecuta la búsqueda según los filtros definidos y muestra la información en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formato Excel <em>(.XLS)</em> mediante el botón <strong>Exportar</strong>.</td></tr><tr><td><strong>Ajustar puntos</strong></td><td>Despliega el formulario para asignar al usuario los puntos lealtad correspondientes a una apuesta.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="126.22222900390625">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id usuario</code></strong></td><td>Campo de texto</td><td>Consulta los puntos lealtad de un usuario específico mediante su identificador.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente los usuarios cuya cuenta pertenece al país seleccionado.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selector</td><td><p>Determina la vista con la que se presentan los resultados.</p><ul><li><strong>Detallado:</strong> muestra el saldo de puntos de cada usuario.</li><li><strong>Totales:</strong> muestra la información consolidada por moneda, sin desagregar por usuario.</li></ul></td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla cuyo contenido depende de la vista seleccionada en el filtro **`Tipo`**:

{% tabs %}
{% tab title="Detallado" %}
Presenta el saldo de puntos lealtad de cada usuario que cumple con los filtros aplicados.

<table><thead><tr><th width="186">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del usuario</code></strong></td><td>Texto</td><td>Nombre del usuario al que corresponden los puntos.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Texto</td><td>Moneda con la que opera la cuenta del usuario.</td></tr><tr><td><strong><code>Puntos</code></strong></td><td>Numérico</td><td>Cantidad de puntos lealtad disponibles actualmente en la cuenta del usuario.</td></tr><tr><td><strong><code>Puntos a expirar</code></strong></td><td>Numérico</td><td>Cantidad de puntos que se encuentran próximos a vencer y que el usuario aún puede redimir.</td></tr><tr><td><strong><code>Puntos expirados</code></strong></td><td>Numérico</td><td>Cantidad de puntos que el usuario no utilizó dentro del plazo establecido y que ya no están disponibles.</td></tr><tr><td><strong><code>Puntos redimidos</code></strong></td><td>Numérico</td><td>Cantidad total de puntos que el usuario ha canjeado hasta el momento de la consulta.</td></tr></tbody></table>
{% endtab %}

{% tab title="Totales" %}
Presenta la información consolidada por moneda, agrupando los puntos de todos los usuarios que cumplen con los filtros aplicados.

<table><thead><tr><th width="186">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Moneda</code></strong></td><td>Texto</td><td>Moneda sobre la que se consolida la información.</td></tr><tr><td><strong><code>Puntos</code></strong></td><td>Numérico</td><td>Total de puntos lealtad disponibles en las cuentas consultadas.</td></tr><tr><td><strong><code>Puntos a expirar</code></strong></td><td>Numérico</td><td>Total de puntos próximos a vencer en las cuentas consultadas.</td></tr><tr><td><strong><code>Puntos expirados</code></strong></td><td>Numérico</td><td>Total de puntos que vencieron sin ser utilizados.</td></tr><tr><td><strong><code>Puntos redimidos</code></strong></td><td>Numérico</td><td>Total de puntos canjeados hasta el momento de la consulta.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

{% hint style="warning" %}
**Nota:** Los **`Puntos expirados`** no se suman a los **`Puntos`** disponibles, ya que corresponden a puntos que vencieron sin ser utilizados y no pueden recuperarse.
{% endhint %}

***

### 6. Ajuste de puntos

Mediante el botón **Ajustar puntos** se despliega una ventana emergente con el formulario para asignar al usuario los puntos lealtad generados por una apuesta.

<table><thead><tr><th width="152">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario id</code></strong></td><td>Campo de texto</td><td>Identificador del usuario al que se le asignarán los puntos.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Producto en el que se realizó la apuesta que genera los puntos <em>(Deportivas o Casino)</em>.</td></tr><tr><td><strong><code>Id apuesta</code></strong></td><td>Campo de texto</td><td>Identificador de la apuesta por la cual se asignarán los puntos al usuario.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** El formulario no incluye un campo para digitar la cantidad de puntos. Al enviar la información, el sistema valida los datos, identifica la apuesta indicada y **calcula y acredita automáticamente** los puntos que le corresponden según las reglas configuradas para ese producto.
{% endhint %}

***

### 7. Validaciones y reglas del negocio:

* No es obligatorio diligenciar todos los filtros para ejecutar la consulta.
* Los resultados mostrados corresponden únicamente a los criterios seleccionados en los filtros.
* Todos los campos del formulario de ajuste son obligatorios para procesar la asignación.
* La cantidad de puntos no se ingresa manualmente: el sistema la calcula a partir de la apuesta indicada en el campo **`Id apuesta`** y del producto seleccionado en el campo **`Tipo`**.
* El campo **`Id apuesta`** debe corresponder a una apuesta existente del usuario indicado. Si los datos no coinciden, el sistema no procesa el ajuste.
* Los puntos expirados no pueden recuperarse ni reasignarse desde este módulo.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>14/10/2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>13/10/2026</td><td>David Velasquez</td><td>Actualización del manual</td></tr></tbody></table>

</details>
