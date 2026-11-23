---
description: >-
  Permite consultar y analizar datos relacionados con los correos electrónicos
  enviados desde el programa de referidos.
---

# Reporte de Emails

<mark style="color:$info;">Consulta las invitaciones enviadas por correo electrónico desde el programa de referidos.</mark> <mark style="color:$info;"></mark><kbd><mark style="color:$info;">Cada registro muestra quién envió la invitación, a qué dirección se envió,<mark style="color:$info;"></kbd> <mark style="color:$info;"></mark><mark style="color:$info;">si el correo salió correctamente y si la persona invitada ya se encuentra registrada en la plataforma, lo que permite hacer seguimiento a la efectividad del programa.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Reporte de Emails

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2F3AQK0DzPgldIq7gJxw6H%2Fimage.png?alt=media&#x26;token=8a01787e-ae45-41ab-896a-aae6a01b37e6" alt=""><figcaption><p>Figura #1: Captura de pantalla Reporte de Emails.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-emails.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar las invitaciones enviadas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-emails.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las invitaciones en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="212">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id usuario referente</code></strong></td><td>Campo de texto</td><td>Consulta las invitaciones enviadas por un referente específico, mediante el ID que tiene asignado en la plataforma de usuarios online.</td></tr><tr><td><strong><code>Fecha de envío</code></strong></td><td>Calendario</td><td>Delimita los resultados según la fecha en la que se enviaron las invitaciones.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente las invitaciones enviadas desde el país seleccionado.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las invitaciones que cumplen con los filtros aplicados.

{% hint style="warning" %}
**Nota:** Los campos **`Estado`** y **`Usuario existente`** describen momentos distintos del proceso y deben leerse juntos. El primero indica si el correo salió de la plataforma; el segundo, si la persona invitada llegó a registrarse. Una invitación puede aparecer como **Enviado** y aun así tener **No existe**, lo que significa que el correo se entregó pero el invitado no completó el registro.
{% endhint %}

<table><thead><tr><th width="196">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID referente</code></strong></td><td>Numérico</td><td>Identificador del usuario que envió la invitación.</td></tr><tr><td><strong><code>ID invitación</code></strong></td><td>Numérico</td><td>Identificador único del mensaje enviado. Se utiliza únicamente para distinguir cada invitación dentro del reporte.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Texto</td><td>Dirección de correo a la que se envió la invitación.</td></tr><tr><td><strong><code>Usuario existente</code></strong></td><td>Texto</td><td><p>Indica si la persona invitada completó su registro en la plataforma.</p><ul><li><strong>Existe:</strong> completó el registro.</li><li><strong>No existe:</strong> no completó el registro.</li></ul></td></tr><tr><td><strong><code>Asunto</code></strong></td><td>Texto</td><td>Asunto con el que se envió el correo.</td></tr><tr><td><strong><code>Mensaje</code></strong></td><td>Texto</td><td><p>Contenido del correo enviado.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Nota:</strong> La columna muestra el texto de forma abreviada. Para visualizar el mensaje completo debe ubicarse el cursor sobre la casilla.</p></div></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td><p>Resultado del envío del correo.</p><ul><li><strong>Enviado:</strong> el correo salió correctamente hacia la dirección indicada.</li><li><strong>No enviado:</strong> el correo no pudo enviarse.</li></ul></td></tr><tr><td><strong><code>País</code></strong></td><td>Texto</td><td>País desde el que se envió la invitación.</td></tr><tr><td><strong><code>Fecha de envío</code></strong></td><td>Fecha</td><td>Fecha y hora en la que se envió la invitación.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* No es obligatorio diligenciar ningún filtro: si no se define ninguno, la consulta devuelve toda la información disponible.
* Los resultados mostrados corresponden únicamente a los criterios seleccionados en los filtros.
* El estado **No enviado** indica una falla en el envío del correo, no un rechazo por parte del invitado.
* El reporte es informativo: desde este módulo no es posible reenviar una invitación ni modificar su contenido.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21/08/2025</td><td>Karol Navia</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>19/10/2026</td><td>David Velasquez</td><td>Actualización de formato</td></tr></tbody></table>

</details>
