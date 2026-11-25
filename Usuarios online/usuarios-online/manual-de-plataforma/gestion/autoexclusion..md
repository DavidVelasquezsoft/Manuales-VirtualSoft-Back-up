# Autoexclusión.

<mark style="color:$info;">Permite al usuario restringir de forma voluntaria y temporal su acceso a una vertical de juego durante un período definido, como medida de juego responsable.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: Menú principal → Autoexclusión

***

### 2. Visualización

En la parte superior de la sección se muestra una descripción informativa sobre en qué consiste la autoexclusión.

<figure><img src="../../../.gitbook/assets/image (23) (2).png" alt=""><figcaption><p>Figura #1: Captura de pantalla descripción de la autoexclusión.</p></figcaption></figure>

Debajo del texto, el usuario podrá configurar los parámetros de su autoexclusión mediante un formulario:

<figure><img src="../../../.gitbook/assets/image (24) (2).png" alt=""><figcaption><p>Figura #2: Captura de pantalla formulario de autoexclusión.</p></figcaption></figure>

***

### 3. Acciones del Usuario

<table><thead><tr><th width="200">Sección</th><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="autoexclusion..md#id-4.-campos-del-formulario-de-autoexclusion"><strong>Formulario de configuración</strong></a></td><td>Ingreso de datos</td><td>Define el tipo, el período y el motivo de autoexclusión.</td></tr><tr><td><strong>Botón "Guardar"</strong></td><td>Confirmación</td><td>Guarda la solicitud de autoexclusión si todos los campos fueron completados.</td></tr><tr><td><a href="autoexclusion..md#id-5.-tabla-de-autoexclusiones-registradas"><strong>Tabla de registros</strong></a></td><td>Consulta y anulación</td><td>Permite visualizar el historial de autoexclusiones y anular si aplica.</td></tr></tbody></table>

***

### 4. Campos del formulario de Autoexclusión

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th><th>Observaciones</th></tr></thead><tbody><tr><td><strong><code>Tipo</code></strong></td><td>Menú desplegable</td><td>Permite seleccionar la vertical a excluir.</td><td>Opciones: Sportsbook, Virtual Sport, Casino, Live Casino.</td></tr><tr><td><strong><code>Fecha Límite de Autoexclusión</code></strong></td><td>Menú desplegable</td><td>Define el período durante el cual la autoexclusión estará activa.</td><td>Opciones: 1 día, 1 semana, 1 mes, 3 meses, 6 meses, 1 año.</td></tr><tr><td><strong><code>Motivo de Autoexclusión</code></strong></td><td>Campo de texto</td><td>Permite ingresar el motivo por el cual se desea activar la autoexclusión.</td><td>Campo obligatorio.</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Botón</td><td>Guarda la configuración ingresada.</td><td></td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Selecciona cuidadosamente el período de autoexclusión, ya que, una vez activado, no podrá ser revertido hasta que hayan transcurrido al menos 24 horas.
{% endhint %}

***

### 5. Tabla de autoexclusiones registradas

Una vez guardada la autoexclusión, se listará en la tabla inferior con la siguiente información:

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del registro de autoexclusión.</td></tr><tr><td><strong><code>Anular</code></strong></td><td>Botón disponible para cancelar la autoexclusión, habilitado luego de transcurridas 24 horas desde su activación.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Vertical o línea de producto seleccionada para la autoexclusión.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha en la que se generó la autoexclusión.</td></tr><tr><td><strong><code>Fecha de Finalización</code></strong></td><td>Fecha en la que la autoexclusión expira automáticamente.</td></tr><tr><td><strong><code>Estado</code></strong></td><td><p>Estado actual de la autoexclusión. Estados posibles:</p><ul><li><strong>Activo</strong>: La autoexclusión está en vigor. No se puede acceder a la vertical seleccionada.</li><li><strong>Inactivo</strong>: La autoexclusión ha finalizado. El usuario puede volver a acceder a la vertical.</li><li><strong>Cancelado</strong>: La autoexclusión fue anulada antes de la fecha de finalización.</li></ul></td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* El campo **`Motivo de Autoexclusión`** es obligatorio para guardar la solicitud.
* Una vez activada, la autoexclusión no puede revertirse hasta que hayan transcurrido al menos 24 horas; a partir de ese momento se habilita el botón **Anular**.
* Mientras la autoexclusión está activa, el usuario no puede acceder a la vertical seleccionada.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>23/07/2025</td><td>Ronald Peláez</td><td>Documento inicial del módulo.</td></tr><tr><td>1.1</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
