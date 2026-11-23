# Reporte de Ajustes de Saldos

<mark style="color:$info;">Consulta los ajustes realizados sobre el saldo de los usuarios y registrar nuevos ajustes, ya sea sumando o restando saldo. Cada registro conserva el motivo, el administrador que lo ejecutó y el saldo del usuario antes y después de la operación, lo que permite auditar cualquier movimiento manual sobre las cuentas.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Ajustes de Saldos

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2F83fQZXQFOhDX7kaInoo8%2Fimage.png?alt=media&#x26;token=ebffd91a-3895-4d5e-b495-3240265c6f3c" alt=""><figcaption><p>Figura #1: Captura de pantalla de filtros de búsqueda.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-ajustes-de-saldos.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los ajustes registrados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-ajustes-de-saldos.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los ajustes en la tabla de resultados.</td></tr><tr><td><strong>Sumar saldo</strong></td><td>Despliega el formulario para acreditar saldo a un usuario.</td></tr><tr><td><strong>Restar saldo</strong></td><td>Despliega el formulario para descontar saldo a un usuario.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="152">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Campo de texto</td><td>Localiza un ajuste específico mediante su identificador único.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo de texto</td><td>Consulta los ajustes asociados a un usuario específico.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Calendario</td><td>Delimita los resultados según el rango de fechas en el que se registraron los ajustes.</td></tr><tr><td><strong><code>Tipo de Saldo</code></strong></td><td>Lista desplegable</td><td>Filtra los ajustes según el tipo de saldo afectado <em>(saldo de recargas o saldo de retiro)</em>.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente los ajustes realizados en el país seleccionado.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los ajustes que cumplen con los filtros aplicados.

<table><thead><tr><th width="196">Campo</th><th width="112">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único del ajuste.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador del usuario al que se le aplicó el ajuste.</td></tr><tr><td><strong><code>Nombre Usuario</code></strong></td><td>Texto</td><td>Nombre del usuario correspondiente al ajuste.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha</td><td>Fecha en la que se registró el ajuste.</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Numérico</td><td>Valor sumado o restado al saldo del usuario.</td></tr><tr><td><strong><code>Tipo de Ajuste</code></strong></td><td>Texto</td><td>Motivo seleccionado al momento de realizar el ajuste.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Detalle ingresado por el administrador para explicar el contexto del ajuste.</td></tr><tr><td><strong><code>Tipo de Saldo</code></strong></td><td>Texto</td><td>Saldo sobre el cual se aplicó el ajuste <em>(saldo de recargas o saldo de retiro)</em>.</td></tr><tr><td><strong><code>Usuario que creó</code></strong></td><td>Texto</td><td>Administrador que registró el ajuste.</td></tr><tr><td><strong><code>Saldo Antes del Ajuste</code></strong></td><td>Numérico</td><td>Saldo que tenía el usuario antes de aplicar la operación.</td></tr><tr><td><strong><code>Saldo Después del Ajuste</code></strong></td><td>Numérico</td><td>Saldo resultante del usuario una vez aplicada la operación.</td></tr></tbody></table>

{% hint style="info" %}
**Nota:** Los campos **`Saldo Antes del Ajuste`** y **`Saldo Después del Ajuste`** permiten verificar la operación: la diferencia entre ambos debe corresponder exactamente al valor registrado en el campo **`Monto`**.
{% endhint %}

***

### 6. Ajuste de saldo

Desde este módulo es posible modificar manualmente el saldo de un usuario mediante dos acciones:

<table><thead><tr><th width="152">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Sumar saldo</strong></td><td>Acredita un monto al saldo del usuario. Se utiliza, por ejemplo, para compensaciones, devoluciones o correcciones a favor del usuario.</td></tr><tr><td><strong>Restar saldo</strong></td><td>Descuenta un monto del saldo del usuario. Se utiliza, por ejemplo, para corregir acreditaciones erróneas o revertir movimientos no procedentes.</td></tr></tbody></table>

Ambas acciones despliegan una ventana emergente con el mismo formulario; la única diferencia es si el monto se suma o se resta al saldo del usuario.

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario Id</code></strong></td><td>Campo numérico</td><td>Identificador del usuario al que se le aplicará el ajuste.</td></tr><tr><td><strong><code>Tipo saldo</code></strong></td><td>Lista desplegable</td><td>Determina sobre cuál saldo del usuario se aplica la operación <em>(saldo de recargas o saldo de retiro)</em>.</td></tr><tr><td><strong><code>Tipo ajuste</code></strong></td><td>Lista desplegable</td><td>Clasifica el motivo del ajuste. Es el valor que se muestra en la columna <strong><code>Tipo de Ajuste</code></strong> de los resultados.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td><p>Detalle del motivo por el cual se realiza el ajuste.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo es el único registro del contexto de la operación, por lo que se recomienda describir el motivo de forma clara y específica para facilitar auditorías posteriores.</p></div></td></tr><tr><td><strong><code>Monto</code></strong></td><td>Campo numérico</td><td>Valor que se sumará o restará al saldo del usuario.</td></tr><tr><td><strong><code>Confirmar monto</code></strong></td><td>Campo numérico</td><td><p>Repite el valor ingresado en el campo <strong><code>Monto</code></strong> para validar que sea correcto.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo existe para evitar errores de digitación. Si los dos valores no coinciden, el ajuste no se guarda.</p></div></td></tr></tbody></table>

{% hint style="danger" %}
**Importante:** Un ajuste ya registrado **no puede editarse ni eliminarse** desde el módulo. Si se comete un error, debe realizarse la operación contraria para corregirlo, lo que deja ambos movimientos registrados en el reporte.
{% endhint %}

***

### 7. Validaciones y reglas del negocio:

* No es obligatorio diligenciar todos los filtros para ejecutar la consulta.
* Los resultados mostrados corresponden únicamente a los criterios seleccionados en los filtros.
* Todos los campos del formulario de ajuste son obligatorios para guardar la operación.
* Los campos **`Monto`** y **`Confirmar monto`** deben coincidir; si presentan valores diferentes, el ajuste no se guarda.
* El ajuste se aplica sobre el tipo de saldo seleccionado en el campo **`Tipo saldo`**, no sobre el saldo total del usuario.
* Cada ajuste queda registrado con el administrador que lo ejecutó y con el saldo del usuario antes y después de la operación, lo que permite su trazabilidad.
* Un ajuste registrado no puede editarse ni eliminarse; para corregirlo debe realizarse la operación contraria.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>24/09/2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>13/10/2026</td><td>David Velasquez</td><td>Actualización del manual</td></tr></tbody></table>

</details>
