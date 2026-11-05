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
  anchors:
    visible: true
---

# Perfiles Options

<mark style="color:$info;">Administra los permisos de acceso a los módulos y funcionalidades del BackOffice y del SiteBuilder. Los permisos se autorizan o se bloquean de forma global, por operación o para un usuario específico, según una jerarquía que define qué configuración prevalece.</mark>

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

<table><thead><tr><th width="124.83331298828125">Campo</th><th width="122.5">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>URL API</code></strong> <em>(obligatorio)</em></td><td>Texto</td><td><p>URL de la API o módulo que se va a bloquear con el permiso a crear.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> En este campo no se permiten caracteres especiales <em>(#, -, !)</em>, se debe ingresar la URL directa.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong> <em>(obligatorio)</em></td><td>Texto</td><td>Especifica el nombre del menú que verán los usuarios.</td></tr><tr><td><strong><code>Menú padre</code></strong></td><td>Lista desplegable</td><td>Define el menú al que se asociará el nuevo permiso. Si no se selecciona un menú padre, el permiso se creará como un menú de primer nivel dentro de la estructura de permisos. Si se selecciona un menú padre, el permiso se agregará como una opción o submenú dentro del menú elegido.</td></tr><tr><td><strong><code>Sub Menú</code></strong></td><td>Lista desplegable</td><td>En caso de haber seleccionado un menú padre si aplica permite seleccionar un submenú en el que quedara el nuevo permiso</td></tr></tbody></table>

***

### 5. Gestión de permisos

Los permisos se gestionan en tres niveles:

* **Global:** aplica a todos los usuarios de un mismo tipo de usuario.
* **Operación:** aplica a un tipo de usuario dentro de un Partner y un país específicos.
* **Usuario:** aplica a un usuario específico.

#### 5.1. Jerarquía de aplicación

La jerarquía de aplicación es **Bloqueos > Global > Operación > Usuario**:

* Un bloqueo prevalece sobre cualquier autorización, sin importar el nivel en que se configure.
* Una autorización otorgada en **Global** no se puede retirar desde **Operación** ni desde **Usuario**. Una autorización otorgada en **Operación** no se puede retirar desde **Usuario**.
* Para impedir el acceso a un permiso autorizado en un nivel superior, se aplica un bloqueo en el nivel inferior.

{% hint style="warning" %}
**Nota:** Un usuario tiene acceso a un permiso cuando está autorizado en al menos un nivel y no está bloqueado en ninguno.
{% endhint %}

**Ejemplos de aplicación**

<table><thead><tr><th width="140">Global</th><th width="140">Operación</th><th width="140">Usuario</th><th>Resultado</th></tr></thead><tbody><tr><td>Autorizado</td><td>—</td><td>—</td><td>Con acceso</td></tr><tr><td>—</td><td>—</td><td>Autorizado</td><td>Con acceso</td></tr><tr><td>Autorizado</td><td>—</td><td>Bloqueado</td><td>Sin acceso</td></tr><tr><td>—</td><td>Bloqueado</td><td>Autorizado</td><td>Sin acceso</td></tr></tbody></table>

#### 5.2. Niveles de gestión

{% tabs %}
{% tab title="Global" %}
Autoriza o bloquea permisos para todos los usuarios de un mismo tipo de usuario.

{% hint style="warning" %}
**Nota:** Las autorizaciones de este nivel no se pueden retirar desde Operación ni desde Usuario. Desde esos niveles solo pueden bloquearse.
{% endhint %}

**Filtros**

<table><thead><tr><th width="160">Campo</th><th width="140">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de usuario</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de usuario al que se aplican los permisos.</td></tr><tr><td><strong><code>Tipo de acción</code></strong></td><td>Lista desplegable</td><td>Define si los permisos marcados se registran como <strong>Autorizaciones</strong> o como <strong>Bloqueos</strong>.</td></tr></tbody></table>
{% endtab %}

{% tab title="Operación" %}
Autoriza o bloquea permisos para un tipo de usuario dentro de un Partner y un país específicos.

{% hint style="warning" %}
**Nota:** Las autorizaciones otorgadas en Global no se pueden retirar desde este nivel. Las autorizaciones de este nivel no se pueden retirar desde Usuario.
{% endhint %}

**Filtros**

<table><thead><tr><th width="160">Campo</th><th width="140">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Selecciona la operación sobre la que se aplican los permisos.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Delimita el país de la operación seleccionada.</td></tr><tr><td><strong><code>Tipo de usuario</code></strong></td><td>Lista desplegable</td><td>Indica el tipo de usuario al que se aplican los permisos dentro de la operación.</td></tr><tr><td><strong><code>Tipo de acción</code></strong></td><td>Lista desplegable</td><td>Define si los permisos marcados se registran como <strong>Autorizaciones</strong> o como <strong>Bloqueos</strong>.</td></tr></tbody></table>
{% endtab %}

{% tab title="Usuario" %}
Autoriza o bloquea permisos para un usuario específico.

{% hint style="warning" %}
**Nota:** Las autorizaciones otorgadas en Global u Operación no se pueden retirar desde este nivel, pero sí pueden bloquearse para que el usuario no tenga acceso.
{% endhint %}

**Filtros**

<table><thead><tr><th width="160">Campo</th><th width="140">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario</code></strong></td><td>Lista desplegable</td><td>Localiza al usuario por su nombre o correo electrónico.</td></tr><tr><td><strong><code>Tipo de acción</code></strong></td><td>Lista desplegable</td><td>Define si los permisos marcados se registran como <strong>Autorizaciones</strong> o como <strong>Bloqueos</strong>.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

#### 5.3. ¿Cómo gestionar permisos?

El flujo es el mismo en los tres niveles; solo cambian los filtros disponibles.

{% stepper %}
{% step %}
**Configurar filtros**

Seleccionar los filtros del nivel correspondiente y el **Tipo de acción**.
{% endstep %}

{% step %}
**Buscar el permiso**

Ubicar el permiso con el campo **Buscar permiso** o navegar por el árbol de menús hasta encontrarlo.
{% endstep %}

{% step %}
**Marcar o desmarcar el permiso**

* **Autorizaciones:** marcar un permiso lo habilita; desmarcarlo retira la autorización de ese nivel.
* **Bloqueos:** marcar un permiso lo bloquea; desmarcarlo retira el bloqueo.

{% hint style="warning" %}
**Nota:** Una autorización otorgada en un nivel superior no se retira desde este paso. Para restringir el acceso, se aplica un bloqueo.
{% endhint %}
{% endstep %}

{% step %}
**Aplicación de cambios**

Los cambios se aplican de forma inmediata, sin necesidad de guardar.
{% endstep %}
{% endstepper %}

***

### 6. Reglas y validaciones

* La gestión de permisos respeta la siguiente jerarquía de aplicación: **Bloqueos > Global > Operación&#x20;**_**(Partner)**_**&#x20;> Usuario**.
* Un permiso bloqueado en cualquier nivel no puede habilitarse desde ningún otro nivel mientras el bloqueo exista.
* Los cambios en los permisos se aplican de forma inmediata, sin necesidad de guardar.
* La lista de permisos es la misma para todos los niveles y tipos de usuario.
* El árbol de permisos de este módulo refleja siempre los permisos vigentes. Para ubicar uno se usa el campo **Buscar permiso**.
* Los tipos de usuario disponibles se consultan en el módulo [**Perfiles**](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/seguridad/perfiles).
* Listado de Roles disponibles en BackOffice.

{% file src="../../.gitbook/assets/Roles BO.pdf" %}

* Listado de permisos disponibles en BackOffice.

{% file src="../../.gitbook/assets/Permosis BackOffice.pdf" %}

### 7. Control de versiones

<details>

<summary>🔽 <strong>Historial de versiones</strong></summary>

<table><thead><tr><th width="98">Versión</th><th width="135">Fecha</th><th width="151">Autor</th><th>Descripción</th></tr></thead><tbody><tr><td>1.0</td><td>02/01/2026</td><td>David Velásquez</td><td>Creación inicial del documento.</td></tr><tr><td>1.1</td><td>24/07/2026</td><td>Ronald Peláez</td><td>Actualización de módulo.</td></tr></tbody></table>

</details>
