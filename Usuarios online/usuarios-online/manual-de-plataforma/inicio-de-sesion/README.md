---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# Inicio de Sesión

<mark style="color:$info;">El módulo de Inicio de Sesión permite a los usuarios registrados acceder a la plataforma de forma segura, ingresando sus credenciales previamente asociadas</mark> _<mark style="color:$info;">(correo electrónico y contraseña).</mark>_

### 1. Acceso al Módulo:

**Ruta de Acceso**: Botón **"Iniciar sesión"** ubicado en la parte superior derecha.

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (20) (1).png" alt="" width="427"><figcaption><p>Figura #1: Captura de pantalla inicio de sesión.</p></figcaption></figure>

### **3. Acciones del Usuario**

<table><thead><tr><th width="188.33331298828125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="restaurar-contrasena.md"><strong>Restaurar contraseña</strong></a></td><td>Redirige al flujo de recuperación de cuenta.</td></tr><tr><td><a href="../registro.md"><strong>Crear una cuenta</strong></a></td><td>Redirige al formulario de registro para nuevos usuarios.</td></tr><tr><td><a href="https://sites.gitbook.com/preview/site_U8bCN/usuarios/usuarios-online/manual-de-plataforma/inicio-de-sesion#id-4.-formulario-de-inicio-de-sesion"><strong>Iniciar sesión</strong></a></td><td><p>Valida los datos ingresados en el formulario y permite acceder a la cuenta.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si la autenticación en dos pasos (2FA) está activa, será obligatorio ingresar el código de verificación. El dispositivo podrá marcarse como seguro durante este proceso para que no se solicite nuevamente el token en futuros inicios de sesión desde el mismo dispositivo.</p></div></td></tr><tr><td><strong>Registro simplificado multi país</strong></td><td><p>Permite que un usuario ya registrado en un país de un mismo partner <strong>cree una cuenta local en otro país de forma rápida y simplificada</strong>, reutilizando sus datos básicos previamente registrados.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El modal se muestra automáticamente cuando el usuario intenta <strong>iniciar sesión en un país distinto al de su registro original</strong>, dentro del mismo partner.</p></div></td></tr></tbody></table>

<details>

<summary>🔽 Detalle de registro simplificado</summary>

Cuando un jugador registrado en un país de la marca intenta **iniciar sesión en otro país del mismo partner**, el sistema mostrará un **modal de invitación al registro simplificado** con el siguiente mensaje:

> _“Hemos detectado que ya tienes una cuenta en \[país de origen]. Para jugar en \[país actual], necesitas una cuenta local. ¿Deseas crearla utilizando tus datos ya registrados?”_

✅ Si el usuario **acepta**:

* Se abre un formulario con datos básicos **precargados y bloqueados**.
  *   **Campos precargados y bloqueados:**

      * Nombre completo
      * Fecha de nacimiento
      * Correo electrónico

      **Campos obligatorios a completar en el país actual:**

      * Número de celular local
      * Tipo y número de documento válido
      * Dirección completa
      * Contraseña
      * Nacionalidad
      * Provincia
      * Ciudad
      * Código promocional
      * Regalo de registro
      * Autorización publicitaria
      * Declaración Persona PEP (solo aplica para Perú)
* Los datos ingresados se validan según las **reglas locales**, incluyendo formato de celular y documento, y controles de **duplicidad por correo electrónico y documento** dentro de la operación, antes de finalizar el registro.
* Al confirmar, se crea la nueva cuenta y el usuario puede acceder inmediatamente.

❌ Si el usuario **rechaza**:

* El sistema permitirá continuar el **inicio de sesión con la cuenta del país de origen**, sin iniciar el proceso de registro multipaís.

> La **configuración de esta funcionalidad** se gestiona desde el **Back Office** en el siguiente modulo: [Configuración - Ajustes generales](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#ajustes-generales)

{% hint style="warning" %}
**Nota:** Solo aplica en partners que tengan la opcion disponible y activa.
{% endhint %}

</details>

**3.1. Otras acciones:**

<table><thead><tr><th width="126.22222900390625">Acción</th><th width="145.22216796875">Tipo de control</th><th width="250.44451904296875">Descripción</th><th>Observaciones</th></tr></thead><tbody><tr><td><strong>Bloqueo por intentos</strong></td><td>Mensaje/Alerta</td><td>Si hay varios intentos fallidos, el sistema puede bloquear temporalmente el acceso a la plataforma.</td><td>Se recomienda restablecer la contraseña en ese caso.</td></tr></tbody></table>

***

### 4. Formulario de inicio de sesión.

<table><thead><tr><th width="120">Campo</th><th width="152">Tipo de control</th><th>Descrioción</th></tr></thead><tbody><tr><td><strong><code>Correo electrónico</code></strong></td><td>Texto</td><td><p>Correo electrónico previamente registrado en la plataforma.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: El correo debe tener un formato válido.</p></div></td></tr><tr><td><strong><code>Contraseña</code></strong></td><td>Texto <em>(Oculto)</em></td><td><p>Contraseña asociada al correo electrónico.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>:</p><ul><li>La contraseña debe tener al menos 4 caracteres.</li><li>El ícono 👁️ permitirá visualizar los caracteres ingresados sin afectar la seguridad de la contraseña.</li></ul></div></td></tr><tr><td><strong><code>Iniciar sesión</code></strong></td><td>Botón</td><td>Envía los datos ingresados e inicia sesión en tu cuenta.</td></tr></tbody></table>

#### **4.1. Elige un bono de primer deposito**

Al iniciar sesión por primera vez, se mostrará un **pop-up** con los bonos disponibles para redimir _(es decir, seleccionar y aplicar al primer depósito)_, Desde allí podrás elegir el bono que desees.

**4.1.1. Términos y condiciones del bono**

* El bono se activará automáticamente al realizar tu **primer depósito**, siempre que cumplas con las **condiciones requeridas** _(por ejemplo, monto mínimo)._
* Si no cumples las condiciones del bono seleccionado, **no se activará**.
* Este apartado solo se muestra cuando hay bonos de primer depósito activos en la plataforma.
* Para que este pop-up se visualice debe haber bonos de primer depósito creados desde la sección [Torneos y bonos](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./bono-deposito.)

#### 4.2. Formulario para personas expuestas políticamente.

Los usuarios configurados como [personas expuestas políticamente](https://virtualsoft.gitbook.io/plantillas/glosario#pep) desde [BackOffice](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/jugadores/informacion-seccion-jugadores#id-3.-informacion-detallada) deberán completar el siguiente formulario de información complementaria antes de continuar utilizando la plataforma, con el fin de cumplir los requerimientos legales y regulatorios aplicables a este tipo de usuarios.

{% hint style="warning" %}
**Nota**:

* Todo el formulario es de diligenciamiento obligatorio, si no se completa la información, no se podrá cerrar o realizar alguna acción en la plataforma.
* Si existen otros pop ups configurados para el mismo módulo, estos se mostrarán únicamente después de completar el formulario.
* Algunos campos se mostrarán de forma dinámica según las respuestas proporcionadas por el usuario.
* El pop up se visualizará una única vez en el siguiente inicio de sesión del usuario después de ser configurado como [Persona PEP](https://virtualsoft.gitbook.io/plantillas/glosario#pep).
{% endhint %}

<table><thead><tr><th width="181">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>¿Usted es una Persona Expuesta Políticamente?</code></strong></td><td>Lista desplegable</td><td>Indica si ocupa o ha ocupado un cargo considerado políticamente expuesto, con el fin de habilitar los campos de información correspondientes.</td></tr></tbody></table>

{% columns %}
{% column width="41.66666666666667%" %}

{% endcolumn %}

{% column width="58.33333333333333%" %}
<table><thead><tr><th width="121">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cargo</code></strong></td><td>Cargo público o función desempeñada por la Persona Expuesta Políticamente.</td></tr><tr><td><strong><code>Nombre de la institución</code></strong></td><td>Entidad u organismo en el que desempeña o desempeñó el cargo indicado.</td></tr><tr><td><strong><code>Nombres y apellidos de familiares</code></strong></td><td>Nombres completos de los familiares relacionados con la condición de Persona Expuesta Políticamente.</td></tr><tr><td><strong><code>Tipo de parentesco</code></strong></td><td>Relación familiar existente con la persona registrada.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="181"></th><th width="150"></th><th></th></tr></thead><tbody><tr><td><strong><code>¿Usted es beneficiario final de alguna persona jurídica?</code></strong></td><td>Lista desplegable</td><td>Indica si posee o controla, directa o indirectamente, una participación relevante en una persona jurídica.</td></tr></tbody></table>

{% columns %}
{% column width="41.66666666666667%" %}

{% endcolumn %}

{% column width="58.33333333333333%" %}
<table><thead><tr><th width="148">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Razón social</code></strong></td><td>Nombre legal o denominación registrada de la persona jurídica.</td></tr><tr><td><strong><code>Registro Único de Contribuyentes</code></strong></td><td>Número de identificación tributaria de la persona jurídica.</td></tr><tr><td><strong><code>Nombre de socios, accionistas o asociados</code></strong></td><td>Nombres completos de los socios, accionistas o asociados de la entidad registrada.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

### &#x35;**. Doble factor de autenticación&#x20;**_**(2FA)**_

Funcionalidad de autenticación en dos factores _(**2FA**)_ que **refuerza** la seguridad del acceso a la plataforma mediante la solicitud de un código de verificación adicional en cada **inicio de sesión**. Al habilitarse, en el siguiente acceso se mostrará un pop-up solicitando su activación; este se presenta una única vez. Si no se activa en ese momento, podrá configurarse posteriormente desde la sección “[**Cambiar contraseña**](../gestion/cambiar-contrasena..md)”.

Una vez activado el 2FA, en cada inicio de sesión se mostrará un pop-up para ingresar el código de verificación; si el dispositivo se marca como seguro durante este proceso, el pop-up no volverá a mostrarse en futuros accesos realizados desde ese mismo dispositivo.

#### 6.1 Visualización

<figure><img src="../../../.gitbook/assets/image (195) (1).png" alt=""><figcaption><p>Figura #2: Captura de pantalla pop-up doble autenticación</p></figcaption></figure>

<table><thead><tr><th width="126.88885498046875">Campo</th><th width="114.44451904296875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>token</code></strong></td><td>Numérico</td><td>Ingresar el código de autenticación de doble factor (<strong>2FA</strong>) previamente configurado en <em>Google Authenticator</em> o <em>Microsoft Authenticator</em>.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Botón</td><td>Cancela el inicio de sesión y cierra el pop-up.</td></tr><tr><td><strong><code>Recordar este dispositivo como seguro</code></strong></td><td>Selector</td><td><ul><li>Si está seleccionado, no se volverá a solicitar el token de autenticación en este navegador durante futuros inicios de sesión por los días que esté configurado en <a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#seguridad">BackOffice</a>.</li><li>Si no está seleccionado, el token se requerirá en cada intento de inicio de sesión <em>(Esta validación solo se puede desactivar desde el</em> <a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/jugadores/configuracion-seccion-jugadores#id-2.2.-seguridad-y-cambios"><em>BackOffice</em></a><em>).</em></li></ul></td></tr><tr><td><strong><code>Continuar</code></strong></td><td>Botón</td><td>Confirma el token de seguridad y accede a la sesión si la validación es correcta; en caso contrario, mostrará mensaje de error.</td></tr></tbody></table>

***

### **6. Validaciones y Reglas de Negocio**

* El correo y la contraseña deben coincidir con una cuenta activa en la plataforma.
* Si el usuario no ha verificado su correo electrónico, se mostrará una alerta para completar el proceso.
* Tras varios intentos fallidos, el sistema puede solicitar verificación adicional _(captcha o bloqueo temporal)._
* El sistema puede cerrar sesiones automáticamente después de un periodo de inactividad.
* Para poder realizar apuestas en la plataforma, es necesario que la cuenta del usuario esté previamente verificada.
* Si el usuario tiene 2FA activo y accede desde un dispositivo o navegador no marcado como seguro, se solicitará obligatoriamente el token de verificación.
* Es posible tener varios dispositivos y navegadores marcados como seguros, cada dispositivo registrado aplica al mismo periodo que se ha establecido desde [BackOffice](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#seguridad).

***

### **7. Control de Versiones**

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th>Versión</th><th>Fecha</th><th width="151.1666259765625">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>25/07/2025</td><td>Karol Navia</td><td>Sección de inicio de sesión incorporada</td></tr><tr><td>1.1</td><td>11/08/2025</td><td>David velasquez</td><td>creación de la sección del bono de primer deposito.</td></tr><tr><td>1.2</td><td>26/09/2025</td><td>David velasquez</td><td>Incorporación de 2FA.</td></tr><tr><td>1.3</td><td>26/01/2026</td><td>David velasquez</td><td>Incorporación de el registro simplificado</td></tr><tr><td>1.4</td><td>11/03/2026</td><td>David velasquez</td><td>Cambio de descripción en 2FA</td></tr><tr><td>1.5</td><td>08/05/2026</td><td>Ronald Peláez</td><td>Ajuste en formato y 2FA.</td></tr><tr><td>1.6</td><td>03/06/2026</td><td>Ronald Peláez</td><td>Pop up régimen reforzado.</td></tr></tbody></table>

</details>
