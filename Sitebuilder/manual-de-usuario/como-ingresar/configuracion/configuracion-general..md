---
description: >-
  Este módulo permite gestionar preferencias generales de la plataforma,
  incluyendo opciones de privacidad, seguridad y configuración de dominios
  asociados al partner.
---

# Configuración general.

### 1. Acceso al Módulo

**Ruta de acceso**: Sitebuilder > Partner > Configuración > Configuración general

***

### 2. Vista General.

<figure><img src="../../../.gitbook/assets/image (290).png" alt=""><figcaption><p>Figura #1: Captura de pantalla configuración general.</p></figcaption></figure>

***

### 3. Configuración Técnica

Esta sección está destinada para realizar configuraciones técnicas esenciales para el funcionamiento del sistema.

<table><thead><tr><th width="129">Campo</th><th width="89">Tipo de control</th><th width="191.4444580078125">Descripción</th><th>Observaciones</th></tr></thead><tbody><tr><td><strong><code>Nombre del partner</code></strong></td><td>Texto</td><td>Identificador único del partner.</td><td>Campo bloqueado, se asigna automáticamente por el sistema.</td></tr><tr><td><strong><code>URL de sitio</code></strong></td><td>Texto</td><td>Dirección principal del sitio web.</td><td>Corresponde al dominio público visible para los usuarios.</td></tr><tr><td><strong><code>URL de datos</code></strong></td><td>Texto</td><td>Ruta que conecta la base de datos.<br></td><td>Pega la URL de datos <strong>(API)</strong> que conecta tu base de datos.</td></tr><tr><td><strong><code>URL datos en tiempo real</code></strong></td><td>Texto</td><td>Ruta WebSocket para actualización en tiempo real.</td><td>Canal de eventos que actualiza en vivo el estado de juegos y apuestas.</td></tr><tr><td><strong><code>Base URL</code></strong></td><td>Texto</td><td>URL base del sitio.</td><td>Dirección base del sitio que el sistema utiliza para generar rutas internas y redireccionar automáticamente a las páginas correspondientes. Solo se debe ingresar una.</td></tr><tr><td><strong><code>Email no reply</code></strong></td><td>Texto</td><td>Correo para envío de notificaciones.</td><td>Dirección utilizada para mensajes automáticos (ej: validación, avisos).</td></tr></tbody></table>

{% hint style="warning" %}
**Notas adicionales**

* **Base URL:** La **Base URL** debe iniciar con `https://` y contener un dominio válido.\
  Esta dirección debe configurarse de acuerdo con el país y el partner correspondiente.\
  Ejemplo: `https://ganaplay.sv/` para El Salvador.\
  <mark style="background-color:yellow;">**Todas las redirecciones automáticas del sitio web se realizarán hacia la URL definida en este campo**</mark><mark style="background-color:yellow;">, especialmente luego de completar procesos como pagos en pasarelas o verificaciones de identidad.</mark>
* **Email no reply:** El correo _noreply_ debe tener un formato válido (por ejemplo: `noreply@dominio.com`).\
  Debe configurarse según el país y el partner correspondiente.\
  Ejemplo: `noreply@ganaplay.sv` para El Salvador.
{% endhint %}

> ⚠️ Estas configuraciones no deben modificarse sin intervención técnica autorizada.

***

### 4. Configuración de Visibilidad y Seguridad

#### 4.1 Visibilidad por País

Define en qué países estará disponible el sitio web del partner.

| Campo                  | Tipo de control                    | Descripción                                                |
| ---------------------- | ---------------------------------- | ---------------------------------------------------------- |
| **Países habilitados** | Casilla de verificación (Checkbox) | Selecciona países para habilitar la visibilidad del sitio. |

***

### 5. Gestión de Dominios (otras configuraciones)

Permite asociar y administrar los dominios vinculados al sitio del partner.

| Campo                           | Tipo de control              | Descripción                              | Observaciones                                                       |
| ------------------------------- | ---------------------------- | ---------------------------------------- | ------------------------------------------------------------------- |
| **Código del proyecto**         | Texto                        | Código único del partner.                | Es un número único que identifica el sitio dentro del sistema.      |
| **País**                        | Lista desplegable (Dropdown) | País donde se va a configurar el dominio | Establece el país en el que se agregara el dominio.                 |
| **Escribe el link de tu sitio** | Texto                        | Dominio a registrar.                     | Habilita el botón “Agregar”.                                        |
| **Agregar (+)**                 | Botón                        | Agrega el dominio a la lista.            | Se refleja en la lista inferior.                                    |
| **Dominios configurados**       | Listado                      | Muestra dominios activos.                | <p>Activación entre 5 a 10 minutos.<br>- Eliminar con ícono 🗑️</p> |

***

### 6. Validaciones y Reglas de Negocio

* Solo se pueden agregar dominios válidos.
* La activación de dominios puede tardar hasta 20 minutos, y no sera notificada.
* Verifica todos los cambios antes de pulsar el botón **Guardar**.
* Las configuraciones técnicas pueden ser creadas o modificadas **por país sin afectar los ya existentes**.

***

### 7. Control de Versiones

En esta sección se registran las versiones del documento, la fecha de actualización, el autor responsable y los cambios realizados.

<details>

<summary>🔽 Historial de versiones </summary>

<table><thead><tr><th width="104.70367431640625">Versión</th><th width="114.9630126953125">Fecha</th><th width="141.888916015625">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>01/07/2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>23/07/2025</td><td>Karol Navia</td><td>Reestructuración del manual por cambios visuales y nuevas funcionalidades</td></tr></tbody></table>

</details>
