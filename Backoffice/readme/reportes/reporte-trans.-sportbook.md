# Reporte Trans. Sportbook

<mark style="color:$info;">Consulta las transacciones generadas por la actividad de apuestas deportivas en la plataforma. Cada registro corresponde a un movimiento de dinero asociado a un ticket de apuesta, lo que permite hacer seguimiento al detalle de la operación y conciliar los valores registrados.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Trans. Sportbook

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2F67j8TfvJGvu5TOHczkLe%2Fimage.png?alt=media&#x26;token=82888ee2-bf90-4f30-bce2-47fbb3bbdc6c" alt=""><figcaption><p>Figura #1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-trans.-sportbook.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar las transacciones registradas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-trans.-sportbook.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las transacciones en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="152">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo de texto</td><td>Consulta las transacciones asociadas a un usuario específico mediante su identificador único.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Calendario</td><td>Delimita los resultados según el rango de fechas en el que se registraron las transacciones.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Selecciona la clase de movimiento que se desea consultar.</td></tr><tr><td><strong><code>Transacción Id</code></strong></td><td>Campo de texto</td><td>Localiza una transacción puntual a partir de su identificador.</td></tr><tr><td><strong><code>Ticket Id</code></strong></td><td>Campo de texto</td><td>Reúne todas las transacciones generadas por un mismo ticket de apuesta.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las transacciones que cumplen con los filtros aplicados.

<table><thead><tr><th width="176">Campo</th><th width="112">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único del registro dentro del reporte.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador del usuario que generó la transacción.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha</td><td>Fecha en la que se registró la transacción.</td></tr><tr><td><strong><code>Transacción ID</code></strong></td><td>Numérico</td><td>Identificador único del movimiento de dinero dentro del sistema.</td></tr><tr><td><strong><code>Ticket ID</code></strong></td><td>Numérico</td><td>Identificador del ticket de apuesta que originó la transacción.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Texto</td><td>Clase de movimiento registrado <em>(por ejemplo: apuesta, premio o reverso)</em>.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Numérico</td><td>Monto correspondiente a la transacción.</td></tr></tbody></table>

{% hint style="info" %}
**Nota:** Un mismo **`Ticket ID`** puede aparecer en varias filas del reporte. Esto ocurre porque un ticket agrupa todos los movimientos generados por una misma apuesta _(el descuento del monto apostado, el pago del premio, un reverso, etc.)_, y cada uno de esos movimientos se registra como una transacción independiente con su propio **`Transacción ID`**.
{% endhint %}

***

### 6. Validaciones y reglas del negocio:

* No es obligatorio diligenciar todos los filtros para ejecutar la consulta.
* Los resultados mostrados corresponden únicamente a los criterios seleccionados en los filtros.
* Cada fila del reporte corresponde a un movimiento individual, no a un ticket completo. Para conocer el detalle total de una apuesta deben consultarse todas las transacciones asociadas a su **`Ticket ID`**.
* El reporte es informativo: las transacciones no pueden modificarse ni eliminarse desde este módulo.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>24/09/2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>13/10/2026</td><td>David Velasquez</td><td>Actualización del manual</td></tr></tbody></table>

</details>
