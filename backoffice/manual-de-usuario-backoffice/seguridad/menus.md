---
description: >-
  Administra los menús y las secciones que se muestran en el BackOffice. Permite
  consultar los menús existentes, crear nuevos y editar su URL, nombre, menú
  padre y orden de visualización.
---

# Menus

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Seguridad > Menus

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2Ff6hAOxx0iOcg7QTRuXgk%2Fimage.png?alt=media&#x26;token=abdc298c-8228-46eb-be96-73cf94a47dab" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Menus.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="160">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="menus.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los menús registrados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="menus.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los menús en la tabla de resultados.</td></tr><tr><td><a href="menus.md#id-6.-crear-menu"><strong>Crear Menú</strong></a></td><td>Abre una ventana emergente para registrar un nuevo menú o una nueva sección dentro del BackOffice.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="140">Campo</th><th width="140">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>URL API</code></strong></td><td>Campo de texto</td><td>Localiza los menús según la URL de la API que utilizan.</td></tr><tr><td><strong><code>Menú Padre</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente las secciones asociadas al menú principal seleccionado.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Consulta los menús a partir del nombre con el que se visualizan en el BackOffice.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Campo numérico</td><td>Acota la consulta a los menús que ocupan la posición indicada.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los menús que cumplen con los filtros aplicados.

<table><thead><tr><th width="125">Campo</th><th width="110">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>URL API</code></strong></td><td>Texto</td><td>Muestra la URL de la API que el menú consulta para cargar la información de la sección.</td></tr><tr><td><i class="fa-pencil">:pencil:</i></td><td>Acción</td><td>Abre la ventana de edición del menú con los mismos campos de la sección Crear Menú.</td></tr><tr><td><strong><code>Menú Padre</code></strong></td><td>Texto</td><td><p>Indica el menú principal al que pertenece cada sección.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Nota:</strong> Los resultados se agrupan por menú padre. Cada grupo se despliega para mostrar las secciones que contiene.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Muestra el nombre del menú que se visualiza en el BackOffice.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Numérico</td><td>Indica la posición del menú respecto a los demás.</td></tr></tbody></table>

***

### 6. Crear Menú

Al hacer clic en **Crear Menú**, se abre una ventana emergente con los siguientes campos. La misma ventana se utiliza para editar un menú desde el ícono <i class="fa-pencil">:pencil:</i> de los resultados.

<table><thead><tr><th width="190">Campo</th><th width="140">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>URL API</code></strong> <em>(obligatorio)</em></td><td>Campo de texto</td><td>Define la URL de la API que el menú consulta para cargar la información de la sección.</td></tr><tr><td><strong><code>Descripción</code></strong> <em>(obligatorio)</em></td><td>Campo de texto</td><td>Indica el nombre del menú que se muestra a los usuarios del BackOffice.</td></tr><tr><td><strong><code>Menú padre</code></strong></td><td>Lista desplegable</td><td><p>Asocia el nuevo menú a un menú existente:</p><ul><li><strong>Sin selección:</strong> el menú se crea como menú principal.</li><li><strong>Con selección:</strong> el menú se crea como sección dentro del menú seleccionado.</li></ul></td></tr><tr><td><strong><code>Orden</code></strong></td><td>Campo numérico</td><td><p>Establece la posición del menú respecto a los demás.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> los menús se muestran de menor a mayor valor, por lo que un menú con orden 1 aparece antes que uno con orden 2.</p></div></td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Al crear un menú, el sistema genera automáticamente un permiso asociado. El menú solo es visible para los usuarios que tienen ese permiso asignado desde [**Perfiles Options**](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/seguridad/perfiles-options).
{% endhint %}

***

### 7. Validaciones y reglas del negocio:

* Los campos **URL API** y **Descripción** son obligatorios para crear un menú.
* Si no se selecciona un **Menú padre**, el menú se crea como menú principal. Si se selecciona, se crea como sección dentro de ese menú.
* Cada menú creado genera un permiso que debe asignarse desde **Perfiles Options** para que el menú sea visible.
* Los menús se muestran de menor a mayor según el valor de **Orden**.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>30/12/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>03/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
