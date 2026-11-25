# Chat de atención

<mark style="color:$info;">Ofrece soporte en tiempo real a los usuarios mediante un canal directo con el equipo de asistencia.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: Chat de Atención

***

### 2. Acciones del Usuario

<table><thead><tr><th width="200">Acción</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="chat-de-atencion.md#id-3.-formulario-de-contacto"><strong>Formulario de contacto</strong></a></td><td>Ingresar / Redactar</td><td>Permite ingresar los datos de contacto del usuario y el mensaje o consulta que desea enviar al soporte.</td></tr><tr><td><strong>Enviar</strong></td><td>Botón</td><td>Envía el mensaje al equipo de atención al cliente.</td></tr></tbody></table>

***

### 3. Formulario de contacto

<table><thead><tr><th width="200">Campo</th><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Ingresar</td><td>Nombre completo del usuario que requiere asistencia.</td></tr><tr><td><strong><code>E-mail</code></strong></td><td>Ingresar</td><td>Correo electrónico del usuario para contacto posterior o confirmación.</td></tr><tr><td><strong><code>Teléfono</code></strong></td><td>Ingresar</td><td>Número de teléfono de contacto (opcional o requerido según configuración).</td></tr><tr><td><strong><code>Contenido</code></strong></td><td>Redactar</td><td>Mensaje o consulta que desea enviar al soporte.</td></tr></tbody></table>

***

### 4. Otras configuraciones

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th><th>Observaciones</th></tr></thead><tbody><tr><td><strong><code>Formulario “Déjenos un mensaje”</code></strong></td><td>Modal / Popup</td><td>Se muestra cuando el chat en vivo no está disponible o si hay tiempo de espera prolongado.</td><td>Incluye campos obligatorios marcados con "*".</td></tr><tr><td><strong><code>Indicador de disponibilidad</code></strong></td><td>Icono / Etiqueta</td><td>Muestra si hay agentes disponibles para chatear en vivo.</td><td>Puede variar según la carga de usuarios.</td></tr><tr><td><strong><code>Respuestas automáticas</code></strong></td><td>Texto sugerido</td><td>El sistema puede ofrecer respuestas rápidas según la consulta ingresada.</td><td>Configuración opcional por parte del partner.</td></tr></tbody></table>

***

### 5. Validaciones y Reglas de Negocio

* Los campos obligatorios están marcados con “\*”:
  * **`Nombre`**
  * **`E-mail`**
  * **`Contenido`**
* El campo **`Teléfono`** puede ser obligatorio u opcional según el partner.
* No se permite el envío de mensajes con campos vacíos o formatos inválidos.
* El sistema puede mostrar mensajes de error en tiempo real si los campos no están completos o contienen errores.

{% hint style="warning" %}
**Nota:** Las validaciones aplicadas pueden variar según el partner. Cada operador define los campos obligatorios, validaciones de formato y comportamiento de los formularios.
{% endhint %}

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/07/2025</td><td>Karol Navia</td><td>Creación inicial del módulo de atención vía chat</td></tr><tr><td>1.1</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
