# Cuentas bancarias

<mark style="color:$info;">Registra y consulta las cuentas bancarias de los puntos de venta, y permite desactivar las que ya no se utilizan.</mark>

{% hint style="warning" %}
**Nota:** El menú **Caja** está disponible únicamente para los usuarios de tipo punto de venta.
{% endhint %}

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Caja > Cuentas Bancarias

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (308) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección cuentas bancarias.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="cuentas-bancarias.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar las cuentas bancarias registradas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="cuentas-bancarias.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las cuentas bancarias en la tabla de resultados.</td></tr><tr><td><a href="cuentas-bancarias.md#id-6.-agregar-cuenta"><strong>Agregar</strong></a></td><td>Abre el formulario para registrar una nueva cuenta bancaria.</td></tr><tr><td><strong>Desactivar</strong> <i class="fa-xmark">:xmark:</i></td><td>Desactiva una cuenta bancaria desde la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID usuario</code></strong></td><td>Campo numérico</td><td>Localiza las cuentas bancarias asociadas al usuario indicado.</td></tr><tr><td><strong><code>Número de cuenta</code></strong></td><td>Campo numérico</td><td>Busca una cuenta bancaria por su número.</td></tr><tr><td><strong><code>Banco</code></strong></td><td>Lista desplegable</td><td>Acota los resultados a las cuentas de la entidad bancaria seleccionada.</td></tr><tr><td><strong><code>Tipo de cuenta</code></strong></td><td>Lista desplegable</td><td>Restringe la búsqueda al tipo de cuenta seleccionado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Muestra las cuentas según su estado <em>(Activa o Inactiva)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las cuentas bancarias que cumplen con los filtros aplicados.

<table><thead><tr><th width="176">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><i class="fa-xmark">:xmark:</i></td><td>Desactiva la cuenta bancaria del registro.</td></tr><tr><td><strong><code>Id</code></strong></td><td>Muestra el identificador único de la cuenta bancaria en la plataforma.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Presenta el nombre del usuario asociado a la cuenta bancaria.</td></tr><tr><td><strong><code>Número de cuenta</code></strong></td><td>Indica el número de la cuenta bancaria registrada.</td></tr><tr><td><strong><code>Tipo de cuenta</code></strong></td><td>Corresponde al tipo de cuenta seleccionado al registrarla.</td></tr><tr><td><strong><code>Banco</code></strong></td><td>Identifica la entidad bancaria a la que pertenece la cuenta.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Señala si la cuenta está habilitada para su uso <em>(Activa o Inactiva)</em>.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Muestra la moneda en la que opera la cuenta bancaria.</td></tr></tbody></table>

***

### 6. Agregar cuenta

Al presionar **Agregar**, se despliega una ventana emergente con el formulario para registrar la cuenta bancaria.

<table><thead><tr><th width="176">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Número de cuenta</code></strong></td><td>Campo numérico</td><td>Define el número de la cuenta bancaria que se va a registrar.</td></tr><tr><td><strong><code>Tipo de cuenta</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de cuenta bancaria.</td></tr><tr><td><strong><code>Banco</code></strong></td><td>Lista desplegable</td><td>Indica la entidad bancaria a la que pertenece la cuenta.</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Botón</td><td>Registra la cuenta bancaria, que queda disponible en la tabla de resultados.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Botón</td><td>Cierra el formulario sin registrar la cuenta.</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* La cuenta bancaria se registra solo al presionar **Guardar**. **Cancelar** cierra el formulario sin guardar cambios.
* Una cuenta desactivada se muestra con estado **Inactiva**.
* Las cuentas bancarias registradas se pueden seleccionar como destino en el formulario **Retirar** del módulo **Caja > Retiros**.
* **Exportar** descarga únicamente los resultados mostrados tras aplicar los filtros.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>09/01/2026</td><td>David Velasquez</td><td>Actualización de formato.</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
