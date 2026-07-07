---
description: >-
  Permite la administración de menús y secciones del Backoffice. Además, se
  ofrece la funcionalidad de crear nuevos menús de forma sencilla y ordenada.
---

# Menus

***

### 1. Acceso al Módulo <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de Acceso**: Backoffice > Seguridad > Menus

***

### 2. 🖼️ Visualización general <a href="#id-4.-visualizacion" id="id-4.-visualizacion"></a>

<figure><img src="../../.gitbook/assets/image (289).png" alt=""><figcaption><p>Figura#1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### 3. 🧑‍💻 Acciones de usuario

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="menus.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="menus.md#id-3.2.-crear-menu"><strong>Crear Menú</strong></a></td><td>Abre modal que permite ingresar la información para crear un nuevo menú o sección dentro del Backoffice.</td></tr><tr><td><a href="menus.md#id-3.1.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los menus validos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

#### 3.1. 🔎 Filtros

Para visualizar los menús de la plataforma, se dispone de los siguientes filtros:

<table><thead><tr><th width="128.1666259765625">Filtro</th><th width="129.8333740234375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>URL API</code></strong></td><td>Texto</td><td>Filtra los registros según la URL de la API que identifica el menú dentro del sistema.</td></tr><tr><td><strong><code>Menú Padre</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por el menú principal mostrando únicamente las subsecciones asociadas.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Permite buscar menús según el texto descriptivo que detalla su funcionalidad o propósito.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Numérico</td><td>Filtra los menús según su posición o jerarquía dentro de la estructura de la plataforma.</td></tr></tbody></table>

#### 3.2. ➕ Crear menú

Abre un pop-up que permite la creación de un nuevo menú o sección en el backoffice:&#x20;

<table><thead><tr><th width="150.66668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>URL API</code></strong> <em>(obligatorio)</em></td><td>Define la URL de la API a la que se accederá para obtener la información asociada a la nueva sección o menú del sistema.</td></tr><tr><td><strong><code>Descripción</code></strong> <em>(obligatorio)</em></td><td>Especifica el nombre del menú que verán los usuarios.</td></tr><tr><td><strong><code>Menú padre</code></strong></td><td>Establece el menú padre al que se asociará el nuevo menú.<br>Si no se selecciona un menú padre, el menú se creará como menú principal; en caso contrario, quedará definido como una sección dentro del menú seleccionado.</td></tr><tr><td><strong><code>Orden</code></strong></td><td><p>Indica la posición que ocupará el menú en relación con los demás menús del sistema.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El valor de <em>orden</em> define la prioridad de visualización del menú. A menor valor asignado, mayor prioridad tendrá el menú de mostrarse.</p></div></td></tr></tbody></table>

#### 3.1. 🚀 Consultar

Al realizar una consulta aplica los filtros seleccionados y muestra los registros validos con los siguientes campos:

<table><thead><tr><th width="209.8333740234375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>URL API</code></strong></td><td>Indica la URL de la API a la que se accede para obtener la información asociada a la sección o menú dentro del sistema.</td></tr><tr><td><code>✏️</code></td><td>Permite la edición del menú, incluyendo la modificación de todos los parámetros configurados en su creación.</td></tr><tr><td><strong><code>Menú Padre</code></strong></td><td>Muestra el menú principal (<em>menú padre</em>) al que pertenece cada menú.<br>Los menús padres se presentan de forma desplegable, permitiendo visualizar los menús hijos asociados.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Especifica el propósito o funcionalidad del menú dentro de la plataforma.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Define la posición que ocupará el menú dentro de la jerarquía del sistema.</td></tr></tbody></table>

***

### 4. Validaciones y reglas del negocio

* Al crear un nuevo menú o sección, este se genera automáticamente como un permiso. Dicho permiso debe asignarse al tipo de usuario correspondiente desde la sección [_**Perfiles Options**_](perfiles-options.md) para que el menú o la sección sea visible.

***

### 5. Control de versiones

| Versión | Fecha      | Autor           | Descripción                     |
| ------- | ---------- | --------------- | ------------------------------- |
| 1.0     | 30/12/2025 | David velasquez | Creación inicial del documento. |
