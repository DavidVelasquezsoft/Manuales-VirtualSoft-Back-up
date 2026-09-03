---
description: >-
  Permite consultar, crear y administrar los usuarios administrativos del
  BackOffice, gestionando sus datos, permisos, partners asociados y
  configuraciones de seguridad.
---

# Administración de Usuarios

***

### 1. Acceso al Módulo

**Ruta de Acceso**: Backoffice > Seguridad > Usuarios administrativos

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (69).png" alt=""><figcaption><p>Figura#1: Captura de pantalla módulo administración de usuarios.</p></figcaption></figure>

***

### 3. Acciones disponibles en el módulo

<table><thead><tr><th width="180">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="administracion-de-usuarios.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los usuarios registrados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="administracion-de-usuarios.md#id-5.-registro-de-usuarios-registrados-en-backoffice"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los usuarios en la tabla de resultados.</td></tr><tr><td><a href="administracion-de-usuarios.md#id-6.-anadir-usuario"><strong>Agregar usuarios</strong></a></td><td>Permite registrar un nuevo usuario administrativo en el BackOffice.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="151.22222900390625">Campo</th><th width="145.888916015625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario</code></strong></td><td>Texto</td><td>Correo electrónico o Nombre del usuario.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador único del usuario.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Filtra usuarios según su fecha de creación.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra usuarios de un partner especifico.</td></tr></tbody></table>

<details>

<summary><strong>Filtros Avanzados</strong></summary>

<table><thead><tr><th width="185.888916015625">Campo</th><th width="170.2222900390625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Primer nombre</code></strong></td><td>Texto</td><td>Busca por primer nombre de usuario.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Texto</td><td>Busca por correo electrónico.</td></tr><tr><td><strong><code>Ciudad</code></strong></td><td>Texto</td><td>Filtra resultados según la ciudad.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Texto</td><td>Usuarios asociados a una moneda específica.</td></tr><tr><td><strong><code>Categoría cliente</code></strong></td><td>Dropdown</td><td>Permite buscar usuarios según su categoría.</td></tr></tbody></table>

</details>

***

### 5. Registro de usuarios registrados en BackOffice

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los usuarios que cumplen con los filtros aplicados.

<table><thead><tr><th width="169.333251953125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>🔎</code></td><td>Permite visualizar el detalle del usuario y acceder a sus configuraciones. Su contenido se detalla en <a data-mention href="administracion-de-usuarios.md#id-6.-detalles-del-usuario">#id-6.-detalles-del-usuario</a>.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Nombre completo del usuario.</td></tr><tr><td><strong><code>Primer nombre</code></strong></td><td>Primer nombre del usuario.</td></tr><tr><td><strong><code>Teléfono</code></strong></td><td>Número de contacto registrado.</td></tr><tr><td><strong><code>Fecha del último logueo</code></strong></td><td>Fecha y hora en la que el usuario inició sesión por última vez.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Dirección de correo electrónico registrada.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del usuario.</td></tr></tbody></table>

### 6. Detalles del usuario

Al seleccionar el ícono de lupa _(🔎)_ ubicado en la primera columna de la tabla de resultados, se accede al detalle del usuario, organizado en las siguientes pestañas:

{% tabs %}
{% tab title="Información del Usuario" %}
Presenta la información registrada del usuario dentro del sistema.

<table><thead><tr><th width="282.33331298828125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único asignado al usuario dentro del sistema.</td></tr><tr><td><strong><code>Primer Nombre</code></strong></td><td>Nombre principal del usuario registrado.</td></tr><tr><td><strong><code>Segundo Nombre</code></strong></td><td>Segundo nombre del usuario, si aplica.</td></tr><tr><td><strong><code>Apellidos</code></strong></td><td>Apellido o apellidos registrados del usuario.</td></tr><tr><td><strong><code>Número de Documento</code></strong></td><td>Numero de identificación del usuario, como DNI, cédula o pasaporte.</td></tr><tr><td><strong><code>Género</code></strong></td><td>Género del usuario (Masculino, Femenino, Otro).</td></tr><tr><td><strong><code>Cumpleaños</code></strong></td><td>Día, mes y año en que nació el usuario.</td></tr><tr><td><strong><code>Login para Acceso</code></strong></td><td>Nombre de usuario o credenciales utilizadas para ingresar al sistema.</td></tr><tr><td><strong><code>Email Registrado</code></strong></td><td>Dirección de correo electrónico asociada a la cuenta del usuario.</td></tr><tr><td><strong><code>Estado de Cuenta</code></strong></td><td>Indica si el usuario está activo, inactivo o bloqueado en la plataforma.</td></tr><tr><td><strong><code>Fecha de Registro</code></strong></td><td>Fecha en la que el usuario creó su cuenta en la plataforma.</td></tr><tr><td><strong><code>Fecha del Último Login</code></strong></td><td>Última vez que el usuario accedió a su cuenta.</td></tr><tr><td><strong><code>Fecha del Último Cambio de Contraseña</code></strong></td><td>Última vez que el usuario modificó su contraseña de acceso.</td></tr><tr><td><strong><code>Fecha Cuenta Activo/Desactivo</code></strong></td><td>Fecha en la que la cuenta fue activada o desactivada dentro del sistema.</td></tr><tr><td><strong><code>Perfil de Usuario</code></strong></td><td>Rol o tipo de perfil asignado al usuario dentro de la plataforma (Ejemplo: Administrador, Cliente, Agente).</td></tr><tr><td><strong><code>Balance</code></strong></td><td>Saldo disponible en la cuenta del usuario en la moneda asignada.</td></tr><tr><td><strong><code>País de Residencia</code></strong></td><td>País en el que el usuario está registrado y opera dentro de la plataforma.</td></tr><tr><td><strong><code>Provincia/Región de Residencia</code></strong></td><td>División territorial dentro del país donde reside el usuario.</td></tr><tr><td><strong><code>Ciudad de Residencia</code></strong></td><td>Ciudad específica donde el usuario se encuentra registrado.</td></tr><tr><td><strong><code>Dirección</code></strong></td><td>Dirección exacta del usuario según los datos ingresados.</td></tr><tr><td><strong><code>Código ZIP</code></strong></td><td>Código postal asociado a la dirección del usuario.</td></tr><tr><td><strong><code>Teléfono</code></strong></td><td>Número de contacto del usuario registrado en la plataforma.</td></tr><tr><td><strong><code>Celular</code></strong></td><td>Número de teléfono móvil asociado a la cuenta del usuario.</td></tr><tr><td><strong><code>¿Está Bloqueado?</code></strong></td><td>Indica si la cuenta del usuario está restringida por alguna razón.</td></tr><tr><td><strong><code>Concesionario</code></strong></td><td>Identifica si el usuario está asociado a algún concesionario dentro de la plataforma.</td></tr><tr><td><strong><code>Partners Seleccionados</code></strong></td><td>Lista de los partners a los que está vinculado el usuario.</td></tr><tr><td><strong><code>Partners No Seleccionados</code></strong></td><td>Partners disponibles que aún no han sido asignados al usuario.</td></tr><tr><td><strong><code>Lista partners seleccionados/ no seleccionados</code></strong></td><td>Permite editar los partners en los que esta creado el usuario.</td></tr></tbody></table>
{% endtab %}

{% tab title="Reportes" %}
Presenta el registro de [logs](https://virtualsoft.gitbook.io/untitled/glosario#logs) del usuario, permitiendo consultar las acciones que ha realizado en el sistema.

#### Visualización

<figure><img src="../../.gitbook/assets/image (592).png" alt=""><figcaption></figcaption></figure>

#### Filtros

<table><thead><tr><th width="115.11102294921875">Campo</th><th width="119.66668701171875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>fecha</code></strong></td><td>Fecha Inicio / Fin</td><td>Permite filtrar las acciones según la fecha en que fueron registrados en el sistema.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Permite buscar una acción especifica utilizando su identificador único de <a href="https://virtualsoft.gitbook.io/untitled/glosario#logs">log</a>.</td></tr><tr><td><strong><code>tipo</code></strong></td><td>Lista desplegable</td><td>Filtra según el tipo de actividad realizada por el usuario.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Numérico</td><td>Permite buscar acciones hechas por el usuario desde una dirección IP en especifico.</td></tr></tbody></table>

#### Resultados de Consulta

Aplica los filtros seleccionados y muestra los [logs](https://virtualsoft.gitbook.io/untitled/glosario#logs) válidos del usuario.

{% hint style="info" %}
Los resultados pueden exportarse en formatos Excel (.XLS) y PDF mediante el botón **Exportar**, ubicado en la parte inferior derecha del reporte.
{% endhint %}

<table><thead><tr><th width="165.9998779296875">Campo</th><th width="117.99993896484375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único de el reporte.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Calendario y hora</td><td>Fecha exacta de la acción.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Texto</td><td>Indica el tipo de acción registrada.</td></tr><tr><td><strong><code>Elemento</code></strong></td><td>Texto</td><td>Nombre del evento o acción ejecutada.</td></tr><tr><td><strong><code>Valor antes</code></strong></td><td>Numérico</td><td>Identificador del dispositivo que ejecutó la acción.</td></tr><tr><td><strong><code>Valor despues</code></strong></td><td>Numérico</td><td>Token o IP de después de la acción.</td></tr><tr><td><strong><code>Usuario Modificó</code></strong></td><td>Numérico</td><td>identificador único del usuario que hizo la acción.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Numérico</td><td>Indica el identificador único del dispositivo que ejecutó la acción.</td></tr><tr><td><strong><code>Sistema operativo</code></strong></td><td>Texto</td><td>Nombre sistema operativo del dispositivo usado en la acción.</td></tr></tbody></table>
{% endtab %}

{% tab title="Configuración" %}
Reúne las opciones de gestión y personalización de la cuenta del usuario.

**Cambio de contraseña**

Permite actualizar la contraseña del usuario mediante los siguientes campos:

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nueva Contraseña</code></strong></td><td>Nueva clave de acceso del usuario.</td></tr><tr><td><strong><code>Confirmar Contraseña</code></strong></td><td>Confirmación de la nueva clave de acceso.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Para aplicar el cambio es necesario seleccionar el botón **Guardar**.
{% endhint %}

**Generar Token**

Genera un token de autenticación requerido para los procesos de seguridad del usuario.

**QR Google**

Genera un código QR para configurar la autenticación de dos factores mediante Google Authenticator.

**Seguridad y Cambios**

Reúne las configuraciones relacionadas con la seguridad del usuario y su operación en la plataforma.

<table><thead><tr><th width="230">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Desbloquear Usuario por Clave</code></strong></td><td>Habilita el acceso del usuario a la plataforma.</td></tr><tr><td><strong><code>Generar contraseña</code></strong></td><td>Envía una contraseña al correo electrónico registrado del usuario.</td></tr><tr><td><strong><code>Estado de Usuario</code></strong></td><td>Indica si la cuenta se encuentra activa o inactiva.</td></tr><tr><td><strong><code>Usuario es Global</code></strong></td><td>Habilita la cuenta para operar en todos los países.</td></tr><tr><td><strong><code>Usuario es de País</code></strong></td><td>Limita la operación del usuario únicamente al país seleccionado.</td></tr><tr><td><strong><code>Estado de Contingencia</code></strong></td><td>Indica si el usuario se encuentra restringido por un evento inesperado en el sistema.</td></tr><tr><td><strong><code>Contingencia Deportivas</code></strong></td><td>Restringe las operaciones del usuario en la vertical de apuestas deportivas.</td></tr><tr><td><strong><code>Contingencia Casino</code></strong></td><td>Restringe las operaciones del usuario en la vertical de casino.</td></tr><tr><td><strong><code>Contingencia Casino en Vivo</code></strong></td><td>Restringe las operaciones del usuario en la vertical de casino en vivo.</td></tr><tr><td><strong><code>Estado de Contingencia Virtuales</code></strong></td><td>Restringe el acceso del usuario a los juegos virtuales.</td></tr><tr><td><strong><code>Estado de Contingencia Poker</code></strong></td><td>Restringe las operaciones del usuario en la vertical de póker.</td></tr><tr><td><strong><code>Restricción IP</code></strong></td><td>Limita el acceso del usuario a las direcciones IP definidas en el campo.</td></tr><tr><td><strong><code>Token Google</code></strong></td><td>Habilita el token de Google para asegurar el inicio de sesión.</td></tr><tr><td><strong><code>Token Local</code></strong></td><td>Habilita el token local para el usuario.</td></tr><tr><td><strong><code>Cancelar cuenta</code></strong></td><td><p>Cancela la cuenta del usuario.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al ejecutar esta acción es obligatorio registrar una observación que indique el motivo de la cancelación.</p></div></td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 7. Añadir usuario

Registra un nuevo usuario en el sistema vinculándolo a un país y a uno o varios partners.

<figure><img src="../../.gitbook/assets/image (524).png" alt=""><figcaption></figcaption></figure>

<details>

<summary><strong>Datos principales</strong></summary>

<table><thead><tr><th width="138.2222900390625">Campo</th><th width="122.77783203125">Tipo control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Login para Acceso</code></strong></td><td>Correo</td><td>Correo electronico del usuario.</td></tr><tr><td><strong><code>Nombre del usuario</code></strong></td><td>Texto</td><td>Nombre que se mostrará públicamente en la plataforma.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona pais del usuario.</td></tr><tr><td><strong><code>Clave</code></strong></td><td>Numerico</td><td>Código que se envía por correo al completar el registro. Sirve para generar un token para el inicio de sesión.</td></tr><tr><td><strong><code>Idioma preferido</code></strong></td><td>Lista desplegable</td><td>Selecciona idioma para la interfaz del usuario.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Lista desplegable</td><td>Moneda del pais seleccionado.</td></tr><tr><td><strong><code>Tipo de usuario</code></strong></td><td>Lista desplegable</td><td>Según el tipo seleccionado, se asignan diferentes niveles de permisos y accesos.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el estado actual del usuario</td></tr><tr><td><strong><code>Partners</code></strong></td><td>Lista doble</td><td>Permite seleccionar uno o varios partners en los que estara creado el usuario.</td></tr><tr><td><strong><code>Usuario de País</code></strong></td><td>Lista desplegable</td><td>Indica si el registro se limita únicamente al país seleccionado.</td></tr><tr><td><strong><code>Consesionario</code></strong></td><td>Dropdown</td><td>No requiere ingreso manual, el sistema lo gestiona automáticamente.</td></tr></tbody></table>

</details>

<details>

<summary><strong>Datos configuración</strong></summary>

Establece los permisos y acciones disponibles para el usuario, Todos son campos **obligatorios**.

<table><thead><tr><th width="138.77783203125">Campo</th><th width="119.22222900390625">Tipo control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado especial</code></strong></td><td>Toggle switch</td><td>Debe estar "<strong>Activado</strong>" para garantizar el correcto funcionamiento del usuario en la plataforma.</td></tr><tr><td><strong><code>Bloqueado para ventas</code></strong></td><td>Toggle switch</td><td>Restringe las ventas al usuario. Se sugiere seleccionar "<strong>Sí</strong>".</td></tr><tr><td><strong><code>Permite recargas</code></strong></td><td>Toggle switch</td><td>Permite o bloquea la posibilidad de realizar recargas. Por defecto, debe estar en "<strong>No</strong>".</td></tr><tr><td><strong><code>Pinagent</code></strong></td><td>Toggle switch</td><td>Define si aplica para código de referencia que asocia al nuevo usuario con el agente o punto de venta. Se sugiere seleccionar "<strong>No</strong>".</td></tr><tr><td><strong><code>Imprime recibo caja</code></strong></td><td>Toggle switch</td><td>Activa o desactiva el permiso de hacer la impresión del recibo de caja. La opción recomendada es "<strong>No</strong>".</td></tr><tr><td><strong><code>Permite activar reg</code></strong></td><td>Toggle switch</td><td>Indica si el usuario tiene permiso para activar <strong>regalos</strong> en la plataforma. La opción recomendada es "<strong>No</strong>".</td></tr></tbody></table>

</details>

<details>

<summary><strong>Activación de acceso a la plataforma</strong></summary>

Para habilitar el acceso al usuario:

* **Buscar** el usuario en la sección Usuarios administrativos.
* **Seleccionar** el ícono 🔎 del usuario correspondiente.
* &#x20;**Ingresar** a la sección Configuración > Seguridad cambios.
* Hacer clic en "**Desbloquear usuario**" para habilitarlo.
* **Activar** el "**Token Google**".
* Hacer clic en "**Generar contraseña**" para enviar la contraseña al correo del usuario.

📍**Ruta:** BackOffice > Seguridad > Usuarios administrativos > 🔎 usuario > Configuración > Seguridad cambios.

{% @guideflow/guideflow-embed requestedUrl="https://app.guideflow.com/player/ok8e7veixk" %}

</details>

***

### 8. Control de Versiones

<details>

<summary><strong>🔽Historial de versiones</strong></summary>

<table><thead><tr><th width="161.8148193359375">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2025-07-15</td><td>David velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
