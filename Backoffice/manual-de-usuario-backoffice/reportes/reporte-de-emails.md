---
description: >-
  Permite consultar y analizar datos relacionados con los correos electrónicos
  enviados desde el programa de referidos.
---

# Reporte de Emails

### Configuración general

#### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Reportes > Reporte de Emails

***

#### 2. Visualización:

<figure><img src="../../.gitbook/assets/image (549).png" alt=""><figcaption><p>Figura#1: Captura de pantalla reporte de emails</p></figcaption></figure>

**🧑‍💻 3. Acciones del Usuario**

Los campos disponibles para realizar la consulta son los siguientes:

<table><thead><tr><th width="131">Campo</th><th width="128">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id usuario referente</code></strong></td><td>Texto</td><td>Permite ingresar el ID del referente asignado en la plataforma de usuarios online.</td></tr><tr><td><strong><code>Fecha de envío</code></strong></td><td>Calendario</td><td>Permite filtrar la búsqueda según una fecha específica de envío.</td></tr><tr><td><strong><code>País</code></strong></td><td>Dropdown</td><td>Selecciona el país desde el cual se realizará la consulta.</td></tr><tr><td><strong><code>Limpiar</code></strong></td><td>Botón</td><td>Elimina la información ingresada en los campos de búsqueda.</td></tr><tr><td><strong><code>Consultar</code></strong></td><td>Botón</td><td>Ejecuta la búsqueda y muestra los resultados según los filtros establecidos.</td></tr></tbody></table>

***

#### 4. Resultados de la Consulta

Los resultados de la búsqueda se mostrarán en forma de tabla con las siguientes columnas:

<table><thead><tr><th width="150">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID referente</code></strong></td><td>Muestra el ID del referente consultado.</td></tr><tr><td><strong><code>ID invitación</code></strong></td><td>Contiene un número único del mensaje enviado en la plataforma de usuarios online. Sirve únicamente para identificar el mensaje.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Direcciones de correo a las que fueron enviadas las invitaciones.</td></tr><tr><td><strong><code>Usuario existente</code></strong></td><td><p>Indica si el usuario al que se le envió la invitación completó el registro.</p><ul><li>"<strong>Existe</strong>" = completó el registro. </li><li><strong>"No existe"</strong> = no completó el registro.</li></ul></td></tr><tr><td><strong><code>Asunto</code></strong></td><td>Muestra el asunto del correo enviado, brindando una breve descripción de su contenido.</td></tr><tr><td><strong><code>Mensaje</code></strong></td><td>Muestra el contenido del correo enviado. Para visualizarlo completo es necesario colocar el cursor sobre la casilla.</td></tr><tr><td><strong><code>Estado</code></strong></td><td><p>Indica la condición del correo: </p><ul><li><strong>"Enviado"</strong> = el correo se envió con éxito. </li><li>"<strong>No enviado"</strong> = el correo no se envió correctamente.</li></ul></td></tr><tr><td><strong><code>País</code></strong></td><td>Muestra el país seleccionado en la consulta.</td></tr><tr><td><strong><code>Fecha de envío</code></strong></td><td>Registra la fecha y hora en la que se realizó el envío de la invitación.</td></tr></tbody></table>

***

**✅ 5. Validaciones y Reglas de Negocio**

* Si no se ingresa ningún criterio de búsqueda (ID referente, fecha o país), se mostrará toda la información.
* La opción **Limpiar** restaura todos los filtros y deja la búsqueda en blanco.

***

**🕒 6. Control de Versiones**

| Versión | Fecha      | Autor       | Cambios Realizados |
| ------- | ---------- | ----------- | ------------------ |
| 1.0     | 21/08/2025 | Karol Navia | Documento inicial  |
