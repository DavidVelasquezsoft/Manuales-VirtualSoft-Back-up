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

# Perfiles Options

<mark style="color:$info;">Administra los permisos de acceso a los diferentes módulos y funcionalidades de la plataforma BackOffice. Los permisos pueden gestionarse de forma global, por operación</mark> <mark style="color:$info;"></mark>_<mark style="color:$info;">(Partner)</mark>_ <mark style="color:$info;"></mark><mark style="color:$info;">o para un usuario específico, siguiendo una jerarquía de aplicación que define la prioridad entre bloqueos y autorizaciones en cada nivel de configuración.</mark>

***

### 1. Acceso al Módulo <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de acceso:** BackOffice > Seguridad > Perfiles-Options.

***

### 2. Visualización <a href="#id-2.-visualizacion" id="id-2.-visualizacion"></a>

<figure><img src="../../.gitbook/assets/image (702).png" alt=""><figcaption><p>Figura #1: Captura de pantalla módulo perfiles-options.</p></figcaption></figure>

***

### 3. Acciones de usuario

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/seguridad/perfiles-options#id-4.-crear-permiso"><strong>Crear Permiso</strong></a></td><td>Crea un nuevo permiso para ser utilizado en la plataforma.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/seguridad/perfiles-options#id-5.-gestion-de-permisos"><strong>Gestionar permisos</strong></a></td><td>Administra los permisos de acceso de los usuarios mediante configuraciones <strong>Global</strong>, <strong>Operación </strong><em><strong>(Partner)</strong></em> o <strong>Usuario</strong>, así como aplicar bloqueos y autorizaciones según la jerarquía establecida.</td></tr></tbody></table>

***

### **4. Crear permiso**

Crea un permiso para gestionar el acceso a diferentes módulos existentes.

<table><thead><tr><th width="150.66668701171875">Campo</th><th width="140">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>URL API</code></strong> <em>(obligatorio)</em></td><td>Texto</td><td><p>URL de la API o módulo que se va a bloquear con el permiso a crear.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> En este campo no se permiten caracteres especiales <em>(#, -, !)</em>, se debe ingresar la URL directa.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong> <em>(obligatorio)</em></td><td>Texto</td><td>Especifica el nombre del menú que verán los usuarios.</td></tr><tr><td><strong><code>Menú padre</code></strong></td><td>Lista desplegable</td><td>Define el menú al que se asociará el nuevo permiso. Si no se selecciona un menú padre, el permiso se creará como un menú de primer nivel dentro de la estructura de permisos. Si se selecciona un menú padre, el permiso se agregará como una opción o submenú dentro del menú elegido.</td></tr><tr><td><strong><code>Sub Menú</code></strong></td><td>Lista desplegable</td><td>En caso de haber seleccionado un menú padre si aplica permite seleccionar un submenú en el que quedara el nuevo permiso</td></tr></tbody></table>

***

### 5. Gestión de permisos

Los permisos pueden administrarse desde tres niveles diferentes:

* [**Global**](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/seguridad/perfiles-options#id-5.-gestion-de-permisos#global#global)
* [**Operación&#x20;**_**(Partner)**_](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/seguridad/perfiles-options#id-5.-gestion-de-permisos#global#operacion)
* [**Usuario**](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/seguridad/perfiles-options#id-5.-gestion-de-permisos#global#usuario)

La aplicación de permisos sigue una **jerarquía**, la cual determina qué configuración tiene prioridad sobre otra.

La jerarquía es la siguiente:

* **Bloqueos > Global > Operación > Usuario**.

Esto significa que:

* Un **bloqueo** siempre tendrá prioridad sobre cualquier autorización.
* Un permiso otorgado de forma **Global** no podrá ser eliminado desde **Operación** ni desde **Usuario**.
* Un permiso otorgado desde **Operación** no podrá ser eliminado desde **Usuario**.
* Los permisos configurados para un **Usuario** únicamente aplican para ese usuario y respetan las configuraciones definidas en los niveles superiores.

{% tabs %}
{% tab title="Usuario" %}
La gestión por **Usuario** permite asignar o bloquear permisos para un usuario específico.

{% hint style="warning" %}
**Nota**: Los permisos otorgados desde la configuración **Global** o por **Operación** no podrán quitarse desde este nivel, sin embargo, podrán bloquearse para que un usuario en específico no tenga el acceso.
{% endhint %}

#### Filtros

<table><thead><tr><th width="141">Campo</th><th width="166">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario</code></strong></td><td>Lista desplegable</td><td>Permite buscar el usuario por nombre o correo electrónico.</td></tr><tr><td><strong><code>Tipo de acción</code></strong></td><td>Lista desplegable</td><td>Define si los permisos seleccionados serán <strong>Autorizaciones</strong> o <strong>Bloqueos</strong>.</td></tr></tbody></table>
{% endtab %}

{% tab title="Global" %}
La gestión **Global** permite asignar o bloquear permisos para **todos los usuarios pertenecientes a un mismo tipo de usuario**.

{% hint style="warning" %}
**Nota**: Los permisos asignados desde este nivel no se podrán quitar desde otros niveles.
{% endhint %}

#### Filtros&#x20;

<table><thead><tr><th width="157">Campo</th><th width="123">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de usuario</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el tipo de usuario al que se le gestionarán los permisos.</td></tr><tr><td><strong><code>Tipo de acción</code></strong></td><td>Lista desplegable</td><td>Define si los permisos seleccionados serán <strong>Autorizaciones</strong> o <strong>Bloqueos</strong>.</td></tr></tbody></table>
{% endtab %}

{% tab title="Operación" %}
La gestión por **Operación** permite asignar o bloquear permisos para un **tipo de usuario** dentro de un **Partner** y **País** específicos configurados en BackOffice.

{% hint style="warning" %}
**Notas**: Los permisos otorgados desde la configuración Global no podrán eliminarse desde este nivel.
{% endhint %}

#### Filtros

<table><thead><tr><th width="147">Campo</th><th width="175">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar la operación <em>(Partner)</em> sobre la cual se gestionarán los permisos.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el país correspondiente a la operación.</td></tr><tr><td><strong><code>Tipo de usuario</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el tipo de usuario al que se le gestionarán los permisos.</td></tr><tr><td><strong><code>Tipo de acción</code></strong></td><td>Lista desplegable</td><td>Define si los permisos seleccionados serán <strong>Autorizaciones</strong> o <strong>Bloqueos</strong>.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

#### 5.1. ¿Cómo gestionar permisos?

El flujo de gestión de permisos es el mismo para las modalidades **Global**, **Operación** y **Usuario**. La única diferencia corresponde a los filtros disponibles en cada modalidad, se recomienda seguir los siguientes pasos.

{% stepper %}
{% step %}
**Configurar filtros**

Seleccionar los filtros correspondientes según la gestión necesaria.
{% endstep %}

{% step %}
**Buscar permisos**

Ubicar el permiso mediante el campo **Buscar permiso** o navegar por la estructura de menús hasta encontrar el permiso requerido.
{% endstep %}

{% step %}
**Gestionar permisos**

Marcar o desmarcar los permisos según el **Tipo de acción** seleccionado.

* **Autorizaciones:** habilita el permiso seleccionado.
* **Bloqueos:** bloquea el permiso seleccionado.

{% hint style="warning" %}
**Importante:** La aplicación de permisos respeta la jerarquía del sistema. Un permiso autorizado desde un nivel superior no puede retirarse desde un nivel inferior y un permiso bloqueado siempre tendrá prioridad sobre cualquier autorización.
{% endhint %}
{% endstep %}

{% step %}
**Aplicación de cambios**

La modificación de los permisos se aplica de forma inmediata, sin necesidad de realizar acciones adicionales.
{% endstep %}
{% endstepper %}

### 6. Reglas y validaciones

* La gestión de permisos respeta la siguiente jerarquía de aplicación: **Bloqueos > Global > Operación&#x20;**_**(Partner)**_**&#x20;> Usuario**.
* Un permiso **bloqueado** no podrá ser habilitado desde un nivel inferior de la jerarquía.
* Los cambios realizados en los permisos se aplican de forma inmediata, sin necesidad de guardar la configuración.
* La lista de permisos es la misma para todos, sin importar el nivel o el tipo de usuario.
* Listado de Roles disponibles en BackOffice.

{% file src="../../.gitbook/assets/Roles BO.pdf" %}

* Listado de permisos disponibles en BackOffice.

{% file src="../../.gitbook/assets/Permosis BackOffice.pdf" %}

### 7. Control de versiones

<details>

<summary>🔽 <strong>Historial de versiones</strong></summary>

<table><thead><tr><th width="98">Versión</th><th width="135">Fecha</th><th width="151">Autor</th><th>Descripción</th></tr></thead><tbody><tr><td>1.0</td><td>02/01/2026</td><td>David Velásquez</td><td>Creación inicial del documento.</td></tr><tr><td>1.1</td><td>24/07/2026</td><td>Ronald Peláez</td><td>Actualización de módulo.</td></tr></tbody></table>

</details>
