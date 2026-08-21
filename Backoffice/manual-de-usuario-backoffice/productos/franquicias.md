---
description: >-
  Esta sección permite consultar, crear y gestionar las franquicias registradas
  en el sistema, las cuales agrupan las pasarelas de pago con las que operan los
  métodos de depósito de la plataforma.
---

# Franquicias

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Productos > Franquicias

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (501).png" alt=""><figcaption><p>Figura#1: Captura de pantalla seccion franquicia.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="165.83331298828125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="franquicias.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información de las franquicias.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="franquicias.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las franquicias en la tabla de resultados.</td></tr><tr><td><a href="franquicias.md#id-6.-anadir-franquicia"><strong>Añadir franquicia</strong></a></td><td>Permite registrar una nueva franquicia mediante una ventana emergente.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="146.851806640625">Campo</th><th width="105.888916015625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Franquicia Id</code></strong></td><td>Numérico</td><td>Indica el identificador único de la franquicia.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre completo o parcial de la franquicia.</td></tr><tr><td><strong><code>Abreviado</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre abreviado asignado a la franquicia.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra las franquicias según su estado <em>(Activado, Inactivo o Todos)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las franquicias que cumplen con los filtros aplicados.

<table><thead><tr><th width="138.40740966796875">Campo</th><th width="125.70367431640625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Editar</code></strong> <em>(✏️)</em></td><td>Columna de acciones</td><td>Permite modificar la información de la franquicia seleccionada. Su funcionamiento se detalla en Editar franquicia.</td></tr><tr><td><strong><code>Franquicia Id</code></strong></td><td>Numérico</td><td>Identificador único asignado a la franquicia.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre completo de la franquicia.</td></tr><tr><td><strong><code>Abreviado</code></strong></td><td>Texto</td><td>Identificador corto utilizado como referencia interna.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Estado actual de la franquicia <em>(Activada o Inactiva)</em>.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Texto</td><td>URL de la imagen asociada a la franquicia.</td></tr></tbody></table>

***

### 6. Añadir franquicia

Permite registrar una nueva franquicia en el sistema. Al seleccionar el botón **Añadir franquicia**, se abre una ventana emergente con los siguientes campos:

<table><thead><tr><th width="122.5740966796875">Campo</th><th width="125.70367431640625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Nombre completo con el que se identifica la franquicia.</td></tr><tr><td><strong><code>Abreviado</code></strong></td><td>Campo de texto</td><td>Identificador corto utilizado como referencia interna.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Campo de texto</td><td>URL de la imagen asociada a la franquicia, la cual se muestra al jugador en la plataforma.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Define si la franquicia queda <em>Activada</em> o <em>Inactiva</em> desde su creación.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Todos los campos son obligatorios. Para completar el registro, es necesario seleccionar el botón **Guardar**.
{% endhint %}

***

### 7. Editar franquicia

Al seleccionar el ícono de lápiz _(✏️)_ ubicado en la primera columna de la tabla de resultados, se abre una ventana que permite modificar la información de la franquicia. Son editables todos los campos, con excepción del identificador único.

<table><thead><tr><th width="138.40740966796875">Campo</th><th width="125.70367431640625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Franquicia Id</code></strong></td><td>No editable</td><td>Identificador único de la franquicia. Se muestra solo como referencia.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Nombre completo de la franquicia.</td></tr><tr><td><strong><code>Abreviado</code></strong></td><td>Campo de texto</td><td>Identificador corto utilizado como referencia interna.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Campo de texto</td><td>URL de la imagen asociada a la franquicia.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Define si la franquicia queda <em>Activada</em> o <em>Inactiva</em>.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Para que las modificaciones queden registradas, es necesario seleccionar el botón **Guardar**.
{% endhint %}

***

### 8. Validaciones y reglas del negocio:

* Todos los campos son obligatorios para crear una franquicia.
* El campo **`Franquicia Id`** no puede modificarse, ya que corresponde al identificador único de la franquicia.
* Los cambios realizados al crear o editar una franquicia requieren seleccionar el botón **Guardar** para aplicarse.
* Las franquicias registradas en este módulo son las que pueden asociarse posteriormente a un partner y país desde SiteBuilder, en la sección de Gestión de franquicias.

***

### 9. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="104">Versión</th><th width="141">Fecha</th><th width="172">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/08/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>21/08/2026</td><td>David Velasquez</td><td>Actualización de formato y de las acciones disponibles.</td></tr></tbody></table>

</details>
