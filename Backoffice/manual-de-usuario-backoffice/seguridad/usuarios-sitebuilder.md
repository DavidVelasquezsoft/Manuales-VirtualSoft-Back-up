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

# Usuarios Sitebuilder

<mark style="color:$info;">Administra y crea usuarios para la plataforma</mark> [<mark style="color:$info;">SiteBuilder</mark>](https://virtualsoft.gitbook.io/manuales/sitebuilder)<mark style="color:$info;">.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Seguridad > Usuarios Sitebuilder

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (1) (1).png" alt=""><figcaption><p>Figura#1: Captura de pantalla módulo Usuarios Sitebuilder.</p></figcaption></figure>

***

### 3. Acciones de usuario

<table><thead><tr><th width="138">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros por defecto.</td></tr><tr><td><strong>Consultar</strong></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Agregar usuarios</strong></td><td>Crea usuarios en la plataforma <a href="https://virtualsoft.gitbook.io/manuales/sitebuilder">Site Builder</a>.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="140.6666259765625">Campo</th><th width="120.5">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Filtra los usuarios creados de Sitebuilder por el ID único del usuario.</td></tr><tr><td><strong><code>Nombre de Usuario</code></strong></td><td>Texto</td><td>Nombre de usuario de Sitebuilder.</td></tr><tr><td><strong><code>Login</code></strong></td><td>Texto</td><td>Permite buscar por el nombre de inicio de sesión del usuario.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha Inicio/Fin</td><td>Filtra los resultados dentro de un rango de fechas de creación.</td></tr><tr><td><strong><code>país</code></strong></td><td>Lista desplegable</td><td>Limita los resultados a usuarios asociados a un país específico.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra por el estado actual del usuario <em>(Todos, Activo, Inactivo).</em></td></tr></tbody></table>

***

### 5. Tabla de usuarios

<table><thead><tr><th width="153.99993896484375">Campo</th><th width="112">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td>🔍</td><td>Columna de acciones</td><td>Permite consultar la información del usuario, actualizar la contraseña mediante los campos “<strong><code>Nueva contraseña</code></strong>” y “<strong><code>Confirmar contraseña</code></strong>”, y modificar su <strong><code>estado</code></strong>.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador único del usuario.</td></tr><tr><td><strong><code>Nombre del Usuario</code></strong></td><td>Texto</td><td>Nombre completo registrado en el sistema.</td></tr><tr><td><strong><code>Login</code></strong></td><td>Texto</td><td>Nombre de inicio de sesión asociado al usuario.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha y hora</td><td>Fecha en que el usuario fue registrado en la plataforma.</td></tr><tr><td><strong><code>País</code></strong></td><td>Texto</td><td>País al que pertenece el usuario.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Estado actual del usuario en el sistema <em>(Ejemplo: Activo, Inactivo).</em></td></tr></tbody></table>

### 6. Agregar usuario

Despliega un pop up para crear nuevos usuarios en la plataforma de Site Builder basados en los usuarios de BackOffice.

{% hint style="warning" %}
**Nota:** Para poder crear un usuario en Site Builder, es necesario que exista un correo previamente creado en el BackOffice para el mismo usuario.
{% endhint %}

<table><thead><tr><th width="114.83331298828125">Campo </th><th width="126">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario Backoffice</code></strong></td><td>Texto</td><td><p>Busca y selecciona el nombre del usuario ya previamente creado en el BackOffice.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Para filtrar es necesario que se escriba el nombre del usuario tal cual como se creó para BackOffice.</p></div></td></tr><tr><td><strong><code>Contraseña</code></strong></td><td>Texto</td><td>Contraseña de acceso que tendrá el usuario en Site Builder.</td></tr></tbody></table>

* Para crear el usuario correctamente, debes dar clic al botón "**Guardar**".

***

### 7. Reglas y validaciones

* Los permisos de los usuarios creados para Site Builder dependen del tipo de usuario que tenga en el BackOffice.
* Una vez creado el usuario se podrá ingresar inmediatamente en Site Builder.
* Para poder crear un usuario de SiteBuilder, debe haber estado creado previamente en [BackOffice](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/seguridad/administracion-de-usuarios#id-1.-acceso-al-modulo).

### 8. Control de Versiones

<details>

<summary>🔽 <strong>Historial de versiones</strong></summary>

<table><thead><tr><th width="161.8148193359375">Versión</th><th width="123">Fecha</th><th width="174">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2025-09-01</td><td>David</td><td><p>Actualización de </p><p>formato.</p></td></tr><tr><td>1.1</td><td>2026-06-02</td><td>Ronald Peláez</td><td>Refinamiento de manual.</td></tr></tbody></table>

</details>
