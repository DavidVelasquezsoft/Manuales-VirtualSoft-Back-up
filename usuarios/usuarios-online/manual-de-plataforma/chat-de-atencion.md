---
description: >-
  Ofrece soporte en tiempo real a los usuarios mediante un canal directo con el
  equipo de asistencia.
---

# Chat de atención

### Configuración general

#### 1. Acceso al Módulo:

**Ruta de Acceso**: Chat de Atención

***

#### 2. Visualización:

**🧑‍💻 2. Acciones del Usuario**

| Elemento          | Acción   | Descripción                                                                |
| ----------------- | -------- | -------------------------------------------------------------------------- |
| Campo “Nombre”    | Ingresar | Nombre completo del usuario que requiere asistencia.                       |
| Campo “E-mail”    | Ingresar | Correo electrónico del usuario para contacto posterior o confirmación.     |
| Campo “Teléfono”  | Ingresar | Número de teléfono de contacto (opcional o requerido según configuración). |
| Campo “Contenido” | Redactar | Mensaje o consulta que desea enviar al soporte.                            |
| Botón “Enviar”    | Click    | Envía el mensaje al equipo de atención al cliente.                         |

***

#### 2.1. Otras configuraciones

| Elemento                        | Tipo             | Descripción                                                                                | Observaciones                                  |
| ------------------------------- | ---------------- | ------------------------------------------------------------------------------------------ | ---------------------------------------------- |
| Formulario “Déjenos un mensaje” | Modal / Popup    | Se muestra cuando el chat en vivo no está disponible o si hay tiempo de espera prolongado. | Incluye campos obligatorios marcados con "\*". |
| Indicador de disponibilidad     | Icono / Etiqueta | Muestra si hay agentes disponibles para chatear en vivo.                                   | Puede variar según la carga de usuarios.       |
| Respuestas automáticas          | Texto sugerido   | El sistema puede ofrecer respuestas rápidas según la consulta ingresada.                   | Configuración opcional por parte del partner.  |

***

#### ✅ 3. Validaciones y Reglas de Negocio

* Los campos obligatorios están marcados con “\*”:
  * Nombre
  * E-mail
  * Contenido
* El campo Teléfono puede ser obligatorio u opcional según el partner.
* No se permite el envío de mensajes con campos vacíos o formatos inválidos.
* El sistema puede mostrar mensajes de error en tiempo real si los campos no están completos o contienen errores.

> 🔒 **Nota**: Las validaciones aplicadas pueden variar según el partner. Cada operador define los campos obligatorios, validaciones de formato y comportamiento de los formularios.

***

#### 🕒 4. Control de Versiones

| Versión | Fecha      | Autor       | Cambios Realizados                               |
| ------- | ---------- | ----------- | ------------------------------------------------ |
| 1.0     | 22/07/2025 | Karol Navia | Creación inicial del módulo de atención vía chat |
