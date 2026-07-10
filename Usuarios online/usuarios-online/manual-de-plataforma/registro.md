---
description: >-
  Permite a los nuevos usuarios crear una cuenta en la plataforma completando un
  formulario con sus datos personales, de contacto y de acceso.
---

# Registro

### 1. Acceso al Módulo:

**Ruta de Acceso**: Botón **"Regístrate"** (_parte superior derecha de la pantalla principal_).

***

### **2. Acciones disponibles**

<table><thead><tr><th width="187.18182373046875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="registro.md#id-2.1.-formulario-de-registro"><strong><code>Completar registro de cuenta</code></strong></a></td><td>El usuario debe llenar todos los campos personales, de contacto y acceso.</td></tr><tr><td><strong><code>Confirmación</code></strong></td><td>El sistema envía un código único de verificación al correo y teléfono ingresado.</td></tr><tr><td><strong><code>Aceptación legal</code></strong></td><td>El usuario acepta los términos y condiciones, política de privacidad y de juego responsable.</td></tr><tr><td><strong><code>Finalizar registro</code></strong></td><td>Envía la solicitud para crear la cuenta mediante el botón "<strong><code>Registrarse</code></strong>".</td></tr></tbody></table>

#### **2.1.** formulario de registro

{% hint style="warning" %}
**Nota:**\
Cuando el usuario selecciona **Turquía** como nacionalidad, el sistema ejecuta automáticamente un proceso de validación de identidad.

* Si la validación es **exitosa**, el registro continúa con normalidad.
* Si la validación es **fallida**, el sistema bloquea el registro y muestra un mensaje de error
{% endhint %}

<table><thead><tr><th width="185.28125">Campo</th><th width="121.94256591796875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País de Residencia</code></strong></td><td>Lista desplegable</td><td>Selecciona el país de residencia.</td></tr><tr><td><strong><code>Nacionalidad</code></strong></td><td>Lista desplegable</td><td>Selecciona el país de nacionalidad.</td></tr><tr><td><strong><code>Tipo de Documento</code></strong></td><td>Lista desplegable</td><td>Define el tipo de identificación: (<em>DNI, Pasaporte, etc...</em>).</td></tr><tr><td><strong><code>Número de Identificación</code></strong></td><td>Texto</td><td>Ingresa el número de documento del usuario a registrar.</td></tr><tr><td><strong><code>Primer Nombre</code></strong></td><td>Texto</td><td>Nombre(s) tal como aparece en el documento.</td></tr><tr><td><strong><code>Primer Apellido</code></strong></td><td>Texto</td><td>Apellido(s) del usuario.</td></tr><tr><td><strong><code>Fecha de Nacimiento</code></strong></td><td>Selector de fecha</td><td>Indica la fecha de nacimiento.</td></tr><tr><td><strong><code>Sexo</code></strong></td><td>Selector</td><td>Selecciona "Masculino" o "Femenino".</td></tr><tr><td><strong><code>Teléfono Celular</code></strong></td><td>Texto numérico</td><td>Ingresar número celular local.<br><br>Si en la configuración del partner y país está activa la verificación de celular, se habilitará el proceso de validación mediante <strong>código SMS</strong>.</td></tr></tbody></table>

{% columns %}
{% column width="41.66666666666667%" %}

{% endcolumn %}

{% column width="58.33333333333333%" %}
<table><thead><tr><th width="136">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Generar código SMS</strong></td><td>Envía un código numérico de 6 dígitos al número de celular ingresado.</td></tr><tr><td><strong>Código</strong></td><td>Permite ingresar el código recibido por SMS para validar el número.</td></tr></tbody></table>

{% hint style="warning" %}
**Notas:**

* El código debe ingresarse antes de que finalice la cuenta regresiva mostrada en pantalla.
* Una vez validado correctamente, el número de celular quedará verificado y no podrá editarse.
* Si el código expira, deberá generarse uno nuevo.
{% endhint %}
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="165.8182373046875">Campo</th><th width="137.7203369140625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Provincia de Residencia</code></strong></td><td>Lista desplegable</td><td>Selecciona tu provincia o estado.</td></tr><tr><td><strong><code>Ciudad de Residencia</code></strong></td><td>Lista desplegable</td><td>Elige la ciudad correspondiente a la provincia.</td></tr><tr><td><strong><code>Dirección de domicilio</code></strong></td><td>Texto libre</td><td>Escribe tu dirección completa.</td></tr><tr><td><strong><code>Correo electrónico</code></strong></td><td>Email</td><td><p>Ingresa un correo electrónico válido y funcional.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El sistema no permite registrar correos electrónicos que contengan el símbolo <strong>“+”</strong>, ya que pueden generar conflictos de autenticación. Utiliza siempre un correo electrónico válido, único y sin este símbolo.</p></div><p>Si en la configuración del partner y país está activa la verificación de correo electrónico, se habilitará el proceso de validación mediante código enviado por email.</p></td></tr></tbody></table>

{% columns %}
{% column width="41.66666666666667%" %}

{% endcolumn %}

{% column width="58.33333333333333%" %}
<table><thead><tr><th width="142">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Generar código email</strong></td><td>Envía un código numérico de 6 dígitos al correo electrónico ingresado.</td></tr><tr><td><strong>Código</strong></td><td>Permite ingresar el código recibido en el correo para validar la dirección.</td></tr></tbody></table>

{% hint style="warning" %}
**Notas:**

* El código debe ingresarse antes de que finalice la cuenta regresiva mostrada en pantalla.
* Una vez validado correctamente, el correo electrónico quedará verificado y no podrá editarse.
* Si el código expira, deberá generarse uno nuevo.
{% endhint %}
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="176.818115234375">Campo</th><th width="135.42413330078125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Contraseña</code></strong></td><td>Texto (<em>oculto</em>)</td><td>Permite crear una contraseña segura que debe contener mínimo 8 caracteres, incluyendo letras mayúsculas, minúsculas y números.</td></tr><tr><td><strong><code>Confirmar contraseña</code></strong></td><td>Texto (<em>oculto</em>)</td><td>Repite la contraseña.</td></tr><tr><td><strong><code>Código promocional</code></strong></td><td>Texto (<em>opcional</em>)</td><td>Ingresa el código promocional correspondiente a tu afiliador.</td></tr><tr><td><strong><code>Aceptación de Términos</code></strong></td><td>Casilla de verificación</td><td>Confirmación de mayoría de edad y aceptación de políticas legales.</td></tr><tr><td><strong><code>reCAPTCHA (no visible)</code></strong></td><td>Validación automática</td><td>Se activa para evitar registros automatizados.</td></tr></tbody></table>

***

### **3. Validaciones y Reglas de Negocio**

* Todos los campos marcados con asterisco (\*) son obligatorios.
* El correo electrónico y teléfono deben ser únicos por cuenta.
* El usuario debe ser mayor de 18 años, validado por fecha de nacimiento.
* Las contraseñas deben coincidir y cumplir con criterios de seguridad.
* La aceptación de los Términos y Condiciones y políticas es obligatoria.
* El formulario verifica errores en tiempo real y resalta campos vacíos o inválidos.
* Al momento de ingresar la identificación del usuario, el sistema validará automáticamente si este mismo está ingresado en la lista de clientes ludópatas de MINCETUR _(En caso de que la validación esté activa en la plataforma desde el_ [_BackOffice_](https://sites.gitbook.com/preview/site_U8bCN/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#general)_)_.
  * La validación se realiza en tiempo real.
  * En caso de que el usuario esté en la lista, no se permitirá el registro en la plataforma.
* La verificación de correo electrónico y/o número de celular será **obligatoria** según la configuración definida por **Partner y país**. Actualmente, esta configuración se gestiona a través de **SiteBuilder** mediante solicitudes al equipo de TI, ya que no se dispone de una vista para su administración directa.
* El registro no podrá completarse hasta que todas las verificaciones activas hayan sido realizadas correctamente.

***

### **4. Control de Versiones**

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="107.33331298828125">Versión</th><th width="136.3333740234375">Fecha</th><th width="162.29632568359375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>17/07/2025</td><td>Karol Navia</td><td>Registro detallado campo por campo (versión base)</td></tr><tr><td>1.1</td><td>30/09/2025</td><td>Karol Navia</td><td>Agregación de nota</td></tr><tr><td>1.2</td><td>18/12/2025</td><td>Ronald Peláez</td><td>Actualización reglas y validaciones por clientes ludópatas.</td></tr><tr><td>1.3</td><td>18/02/2026</td><td>David Velasquez</td><td>Incorporación de validación verificación de correo y celular.</td></tr><tr><td>1.4</td><td>16/03/2026</td><td>David Velasquez</td><td>Incoporación de nota de validación "+" en correo electronico</td></tr><tr><td>1.5</td><td>01/04/2026</td><td>David Velasquez</td><td>Ajuste validaciones en campos</td></tr></tbody></table>

</details>
