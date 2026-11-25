# Registro método de retiro

<mark style="color:$info;">Permite registrar métodos de retiro en Paniplay, ofreciendo dos opciones principales: cuenta bancaria y número de celular.</mark>

{% hint style="warning" %}
**Nota:** Estas configuraciones aplican específicamente para la plataforma **Paniplay**
{% endhint %}

***

### 1. Acceso al Módulo

**Ruta de Acceso**: Usuarios online > Gestión > Registro de método de retiro

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (171).png" alt=""><figcaption><p>Figura #1: Captura de pantalla registro método de retiro.</p></figcaption></figure>

***

### 3. Acciones del Usuario

Al ingresar a **Registro de método de retiro**, el sistema muestra dos botones principales para que el jugador seleccione cómo registrar su método:

<table><thead><tr><th width="200">Acción</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="registro-metodo-de-retiro.md#id-4.-cuenta-bancaria"><strong>Cuenta bancaria</strong></a></td><td>Botón</td><td>Permite registrar una cuenta bancaria ingresando los datos requeridos.</td></tr><tr><td><a href="registro-metodo-de-retiro.md#id-5.-numero-de-celular"><strong>Número de celular</strong></a></td><td>Botón</td><td>Permite registrar un número de celular como método de retiro.</td></tr></tbody></table>

***

### 4. Cuenta bancaria

<figure><img src="../../../.gitbook/assets/image (172).png" alt=""><figcaption><p>Figura #2: Captura de pantalla registro de cuenta bancaria como método de retiro.</p></figcaption></figure>

Al seleccionar **Cuenta bancaria**, se despliega un formulario con los siguientes campos de configuración:

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th><th>Observaciones</th></tr></thead><tbody><tr><td><strong><code>Nombre de usuario</code></strong></td><td>Texto</td><td>Nombre del titular de la cuenta bancaria.</td><td>Debe coincidir con la cuenta registrada en el banco.</td></tr><tr><td><strong><code>Banco</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el banco asociado a la cuenta.</td><td>Campo obligatorio.</td></tr><tr><td><strong><code>Confirmar banco</code></strong></td><td>Lista desplegable</td><td>Debe volver a seleccionar el banco elegido.</td><td>Validación obligatoria.</td></tr><tr><td><strong><code>Tipo de cuenta</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de cuenta: Ahorros o Corriente.</td><td>Campo obligatorio.</td></tr><tr><td><strong><code>Tipo de cliente</code></strong></td><td>Texto</td><td>Identifica si es cuenta Personal o Empresarial.</td><td>No es un campo editable</td></tr><tr><td><strong><code>Número de cuenta</code></strong></td><td>Numérico</td><td>Ingresa el número de cuenta bancaria.</td><td>Debe ser válido y único.</td></tr><tr><td><strong><code>Confirmar número de cuenta</code></strong></td><td>Numérico</td><td>Vuelva a ingresar el número de cuenta.</td><td>Debe coincidir con el primer campo.</td></tr><tr><td><strong><code>Aceptar</code></strong></td><td>Botón</td><td>Guarda la cuenta bancaria como método de retiro.</td><td>Se habilita cuando todos los campos son válidos.</td></tr></tbody></table>

***

### 5. Número de celular

<figure><img src="../../../.gitbook/assets/image (173).png" alt=""><figcaption><p>Figura #3: Captura de pantalla registro de número de celular como método de retiro.</p></figcaption></figure>

Al seleccionar **Número de celular**, se despliega un nuevo formulario con los siguientes campos:

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th><th>Observaciones</th></tr></thead><tbody><tr><td><strong><code>Número de celular</code></strong></td><td>Texto</td><td>Ingrese el número de celular que se asociará al retiro.</td><td>Campo obligatorio. Debe ser único por proveedor.</td></tr><tr><td><strong><code>Confirmar número de celular</code></strong></td><td>Texto</td><td>Confirma el número de celular ingresado previamente.</td><td>Debe coincidir con el primer campo.</td></tr><tr><td><strong><code>Proveedor de servicio</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el proveedor disponible.</td><td>Actualmente solo disponible: TigoMoney.</td></tr><tr><td><strong><code>Aceptar</code></strong></td><td>Botón</td><td>Guarda el número de celular como método de retiro.</td><td>Se Guarda cuando todos los campos son válidos.</td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* Los campos obligatorios deben estar completos para guardar.
* Validaciones en **Número de celular**:
  * Los dos números ingresados deben coincidir.
  * No se permite registrar un número repetido en el mismo proveedor.
  * Si el número ya fue utilizado por otro usuario, se muestra un mensaje de error genérico.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>10/09/2025</td><td>Karol Navia</td><td>Documentacion inicial</td></tr><tr><td>1.1</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
