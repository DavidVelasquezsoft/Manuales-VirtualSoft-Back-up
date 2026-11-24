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

# Países

<mark style="color:$info;">Consulta los países registrados en la plataforma y activa o inactiva su disponibilidad para crear partners en Sitebuilder.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Herramientas > Países

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (587).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección países.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="paises.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los países registrados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="paises.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los países en la tabla de resultados.</td></tr><tr><td><a href="paises.md#id-6.-detalle-del-pais"><strong>Editar estado</strong></a> <i class="fa-pencil">:pencil:</i></td><td>Abre el detalle del país para activarlo o inactivarlo.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

{% hint style="warning" %}
**Nota:** No es obligatorio completar los filtros. Si no se aplica ninguno, el sistema muestra todos los países registrados.
{% endhint %}

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Campo numérico</td><td>Localiza el país por su identificador único.</td></tr><tr><td><strong><code>Iso</code></strong></td><td>Campo de texto</td><td>Busca el país por su código ISO <em>(Ejemplo: CO, MX o AR)</em>.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Consulta el país por su nombre.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Campo de texto</td><td>Acota los resultados por el código o el nombre de la moneda del país.</td></tr><tr><td><strong><code>UTC</code></strong></td><td>Campo de texto</td><td>Restringe la búsqueda por la zona horaria configurada para el país.</td></tr><tr><td><strong><code>Lenguaje</code></strong></td><td>Campo de texto</td><td>Delimita los resultados por el idioma configurado para el país.</td></tr><tr><td><strong><code>Prefijo celular</code></strong></td><td>Campo de texto</td><td>Filtra por el prefijo telefónico internacional del país.</td></tr><tr><td><strong><code>Código PATH</code></strong></td><td>Campo de texto</td><td>Identifica el país por el código que define la ruta de acceso a su sitio y configuraciones en Sitebuilder.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Muestra los países según su estado <em>(Activo o Inactivo)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los países que cumplen con los filtros aplicados.

<table><thead><tr><th width="200">Campo</th><th width="120">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><i class="fa-pencil">:pencil:</i></td><td>Acción</td><td>Abre el detalle del país para consultar su información y modificar su estado.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Muestra el identificador único del país.</td></tr><tr><td><strong><code>Iso</code></strong></td><td>Texto</td><td>Presenta el código ISO que identifica al país.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Indica el nombre completo del país.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Texto</td><td>Corresponde a la moneda configurada para el país.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Señala si el país está <strong>Activo</strong> o <strong>Inactivo</strong> para crear partners en Sitebuilder.</td></tr><tr><td><strong><code>Lenguaje</code></strong></td><td>Texto</td><td>Indica el idioma configurado por defecto para el país.</td></tr><tr><td><strong><code>UTC</code></strong></td><td>Texto</td><td>Muestra la zona horaria del país.</td></tr><tr><td><strong><code>Prefijo celular</code></strong></td><td>Texto</td><td>Presenta el prefijo telefónico internacional del país.</td></tr><tr><td><strong><code>Código PATH</code></strong></td><td>Texto</td><td>Contiene el código que define la ruta de acceso al sitio del país en Sitebuilder.</td></tr></tbody></table>

***

### 6. Detalle del país

El ícono <i class="fa-pencil">:pencil:</i> de la tabla de resultados abre una ventana emergente con el detalle del país. Todos los campos son informativos, excepto **`Estado`**, que es el único editable.

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Muestra el identificador único del país.</td></tr><tr><td><strong><code>ISO</code></strong></td><td>Presenta el código ISO del país.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Indica el nombre completo del país.</td></tr><tr><td><strong><code>Lenguaje</code></strong></td><td>Corresponde al idioma configurado por defecto.</td></tr><tr><td><strong><code>UTC</code></strong></td><td>Muestra la zona horaria del país.</td></tr><tr><td><strong><code>Prefijo celular</code></strong></td><td>Presenta el prefijo telefónico internacional.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Señala la moneda configurada para el país.</td></tr><tr><td><strong><code>Código PATH</code></strong></td><td>Contiene el código que define la ruta de acceso al sitio del país en Sitebuilder.</td></tr><tr><td><strong><code>Estado</code></strong></td><td><p>Define si el país está disponible para crear partners en Sitebuilder.</p><ul><li><strong>Activo:</strong> el país se puede usar al crear un partner.</li><li><strong>Inactivo:</strong> el país no está disponible al crear un partner.</li></ul></td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Aplica el cambio de estado del país.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Cierra la ventana sin guardar cambios.</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* Los filtros no son obligatorios para ejecutar la consulta.
* El campo **`Estado`** es el único editable en el detalle del país.
* Solo los países activos están disponibles al crear partners en [Sitebuilder](https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar#id-3.2.-crear-nuevo-partner).
* El módulo está disponible solo para los usuarios con los permisos necesarios.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>24/01/2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
