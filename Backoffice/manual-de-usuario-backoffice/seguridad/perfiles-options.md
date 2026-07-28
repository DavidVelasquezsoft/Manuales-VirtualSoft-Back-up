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

<mark style="color:$info;">Este módulo permite administrar los permisos de acceso a los diferentes módulos y funcionalidades de la plataforma BackOffice. Los permisos pueden gestionarse de forma global, por operación (Partner) o para un usuario específico, siguiendo una jerarquía de aplicación que define la prioridad entre bloqueos y autorizaciones en cada nivel de configuración.</mark>

***

### 1. Acceso al Módulo <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de acceso:** BackOffice > Seguridad > Perfiles Options.

***

### 2. Visualización <a href="#id-2.-visualizacion" id="id-2.-visualizacion"></a>

***

### 3. Acciones de usuario

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Crear Permiso</strong></td><td>Crea un nuevo permiso para ser utilizado en la plataforma.</td></tr><tr><td><strong><code>Gestionar permisos</code></strong></td><td>Administra los permisos de acceso de los usuarios mediante configuraciones <strong>Global</strong>, <strong>Operación </strong><em><strong>(Partner)</strong></em> o <strong>Usuario</strong>, así como aplicar bloqueos y autorizaciones según la jerarquía establecida.</td></tr></tbody></table>

#### **3.1. Crear permiso**

<table><thead><tr><th width="150.66668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>URL API</code></strong> <em>(obligatorio)</em></td><td><p>URL de la API o módulo que se va a bloquear con el permiso a crear.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> En este campo no se permiten carácteres especiales <em>(#,-,!)</em>, se debe ingresar la URL directa.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong> <em>(obligatorio)</em></td><td>Especifica el nombre del menú que verán los usuarios.</td></tr><tr><td><strong><code>Menú padre</code></strong></td><td>Establece el menú padre al que se asociará el nuevo permiso.<br>Si no se selecciona un menú padre, el permiso se creará como permiso principal; en caso contrario, quedará definido como un permiso dentro del menú seleccionado.</td></tr><tr><td><strong><code>Sub Menú</code></strong></td><td>En caso de haber seleccionado un menú padre si aplica permite seleccionar un submenú en el que quedara el nuevo permiso</td></tr></tbody></table>

***

### 4. Gestión de permisos

Los permisos pueden administrarse desde tres niveles diferentes:

* **Global**
* **Operación (Partner)**
* **Usuario**

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
**Nota**: Los permisos otorgados desde la configuración **Global** o por **Operación** no podrán eliminarse desde este nivel, sin embargo, podrán bloquearse.
{% endhint %}

#### Filtros

<table><thead><tr><th width="141">Campo</th><th width="166">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario</code></strong></td><td>Lista desplegable</td><td>Permite buscar el usuario por nombre o correo electrónico.</td></tr><tr><td><strong><code>Tipo de acción</code></strong></td><td>Lista desplegable</td><td>Define si los permisos seleccionados serán <strong>Autorizaciones</strong> o <strong>Bloqueos</strong>.</td></tr></tbody></table>
{% endtab %}

{% tab title="Global" %}
La gestión **Global** permite asignar o bloquear permisos para **todos los usuarios pertenecientes a un mismo tipo de usuario**.

#### Filtros&#x20;

<table><thead><tr><th width="157">Campo</th><th width="123">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de usuario</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el tipo de usuario al que se le gestionarán los permisos.</td></tr><tr><td><strong><code>Tipo de acción</code></strong></td><td>Lista desplegable</td><td>Define si los permisos seleccionados serán <strong>Autorizaciones</strong> o <strong>Bloqueos</strong>.</td></tr></tbody></table>
{% endtab %}

{% tab title="Operación" %}
La gestión por **Operación** permite asignar o bloquear permisos para un **tipo de usuario** dentro de un **Partner** y **País** específicos configurados en BackOffice.

{% hint style="warning" %}
**Nota**: Los permisos otorgados desde la configuración Global no podrán eliminarse desde este nivel
{% endhint %}

#### Filtros

<table><thead><tr><th width="195">Campo</th><th>Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Partner</strong></td><td>Lista desplegable</td><td>Permite seleccionar la operación (Partner) sobre la cual se gestionarán los permisos.</td></tr><tr><td><strong>País</strong></td><td>Lista desplegable</td><td>Permite seleccionar el país correspondiente a la operación.</td></tr><tr><td><strong>Tipo de usuario</strong></td><td>Lista desplegable</td><td>Permite seleccionar el tipo de usuario al que se le gestionarán los permisos.</td></tr><tr><td><strong>Tipo de acción</strong></td><td>Lista desplegable</td><td>Define si los permisos seleccionados serán <strong>Autorizaciones</strong> o <strong>Bloqueos</strong>.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 5. ¿Cómo gestionar permisos?

El flujo de gestión de permisos es el mismo para las modalidades **Global**, **Operación** y **Usuario**. La única diferencia corresponde a los filtros disponibles en cada modalidad.

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
