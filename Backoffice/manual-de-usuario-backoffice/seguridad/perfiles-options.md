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

<mark style="color:$info;">Este módulo permite crear y gestionar permisos para todos los tipos de usuarios que hay en la plataforma de BackOffice, Site Builder y Torneos y bonos, otorgándoles acceso a diferentes módulos o funcionalidades según sea necesario.</mark>

***

### 1. Acceso al Módulo <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de Acceso**: Backoffice > Seguridad > Perfiles Options

***

### 2. Visualización general <a href="#id-4.-visualizacion" id="id-4.-visualizacion"></a>

<figure><img src="../../.gitbook/assets/image (673).png" alt=""><figcaption><p>Figura #1: Captura de pantalla módulo perfiles options.</p></figcaption></figure>

***

### 3. Acciones de usuario

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="perfiles-options.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Elige el tipo de usuario a gestionar.</td></tr><tr><td><a href="perfiles-options.md#id-3.3.-asignar-permisos"><strong>Gestionar permisos</strong></a></td><td>Visualiza, asigna y quita permisos a un usuario.</td></tr><tr><td><a href="perfiles-options.md#id-3.2.-crear-permiso"><strong>Crear Permiso</strong></a></td><td>Abre pop-up que permite crear un nuevo permiso que puede ser asignado a múltiples tipos de usuario.</td></tr></tbody></table>

#### 3.1. Crear permiso

<table><thead><tr><th width="150.66668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>URL API</code></strong> <em>(obligatorio)</em></td><td>Define la URL de la API a la que se accederá para obtener la información asociada al nuevo permiso.</td></tr><tr><td><strong><code>Descripción</code></strong> <em>(obligatorio)</em></td><td>Especifica el nombre del menú que verán los usuarios.</td></tr><tr><td><strong><code>Menú padre</code></strong></td><td>Establece el menú padre al que se asociará el nuevo permiso.<br>Si no se selecciona un menú padre, el permiso se creará como permiso principal; en caso contrario, quedará definido como un permiso dentro del menú seleccionado.</td></tr><tr><td><strong><code>Sub Menú</code></strong></td><td>En caso de haber seleccionado un menú padre si aplica permite seleccionar un submenú en el que quedara el nuevo permiso</td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="158.166748046875">Campo</th><th width="121.8333740234375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de usuario</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el tipo de usuario al que se le gestionarán los permisos.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Texto</td><td><p><strong>En caso de que aplique</strong> se deberá ingresar el nombre de usuario en específico al cual se le gestionarán los permisos.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Este filtro solo estará disponible si el tipo de usuario lo requiere.</p></div></td></tr></tbody></table>

#### 4.1. ¿Cómo Gestionar permisos?

Al momento de seleccionar un tipo de usuario en los filtros se desplegarán automáticamente todos los permisos _(según el tipo de usuario)_.

{% stepper %}
{% step %}
#### Buscar permisos

Una vez desplegada la lista de permisos, el sistema ofrece dos formas de localizarlos:

* **Búsqueda por nombre:** Utilice el campo **`Buscar permiso`** para encontrar un permiso específico ingresando su nombre.
* **Navegación manual:** Explore la estructura de menús y submenús. Los permisos que contienen otros permisos se identifican con un ícono de flecha, el cual permite desplegar y visualizar sus opciones internas.

{% hint style="warning" %}
**Nota**: Los permisos visualizados dependen del rol seleccionado en el campo **Tipo de usuario**. Desde este archivo es posible consultar la descripción detallada de cada permiso y de los roles disponibles en el sistema.
{% endhint %}
{% endstep %}

{% step %}
#### gestionar permisos

Para habilitar o deshabilitar un permiso para un tipo de usuario:

* Ubique el permiso deseado en la lista.
* Haga clic en el **check-box** correspondiente.
  * [x] **Marcado:** el permiso queda habilitado para el tipo de usuario.
  * [ ] **Desmarcado:** el permiso queda deshabilitado para el tipo de usuario.

Los cambios se aplican según la configuración definida para el perfil seleccionado.
{% endstep %}

{% step %}
#### Aplicación automática de cambios

Al habilitar o deshabilitar un permiso, el sistema aplica el cambio de forma inmediata.\
El permiso queda automáticamente **activo o inactivo** para el tipo de usuario o perfil configurado, sin necesidad de realizar acciones adicionales.
{% endstep %}
{% endstepper %}

***

### 4. Control de versiones

<details>

<summary>🔽 <strong>Historial de versiones</strong></summary>

| Versión | Fecha      | Autor           | Descripción                     |
| ------- | ---------- | --------------- | ------------------------------- |
| 1.0     | 02/01/2026 | David velasquez | Creación inicial del documento. |

</details>
