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

# Partners Categorías

<mark style="color:$info;">Esta sección permite consultar y gestionar las categorías asociadas a un partner y país, las cuales agrupan los juegos que se muestran en el lobby de la plataforma de usuarios online.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Herramientas > Partner Ajustes > Seleccionar partner > Productos 2 > Partners Categorías

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (713).png" alt=""><figcaption><p>Figura #1: </p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="137">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="partners-categorias.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar las categorías registradas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="partners-categorias.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las categorías en la tabla de resultados.</td></tr><tr><td><a href="partners-categorias.md#id-6.-agregar-categoria"><strong>Agregar</strong></a></td><td>Permite registrar una nueva categoría para el partner y país seleccionados mediante una ventana emergente.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="130">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre con el que se identifica la categoría.</td></tr><tr><td><strong><code>Slug</code></strong></td><td>Campo de texto</td><td>Filtra por el identificador de la categoría utilizado internamente por el sistema.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td><p>Selecciona el país sobre el cual se consultarán las categorías.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo es <strong>obligatorio</strong> para ejecutar la consulta.</p></div></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra las categorías según su estado <em>(Activa o Inactiva)</em>.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Filtra las categorías según la vertical a la que pertenecen <em>(Casino, Virtuales, Mini Games o Bingo)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las categorías que cumplen con los filtros aplicados.

<table><thead><tr><th width="140">Campo</th><th width="108">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Editar</code></strong> <em>(✏️)</em></td><td>Acción</td><td>Permite modificar la información de la categoría seleccionada.</td></tr><tr><td><strong><code>Slug</code></strong></td><td>Texto</td><td>Identificador de la categoría utilizado internamente por el sistema.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Nombre con el que se identifica la categoría.</td></tr><tr><td><strong><code>Icono</code></strong></td><td>Acción</td><td>Al seleccionar el ícono de lupa <em>(🔎)</em>, se abre una ventana emergente que muestra el ícono en formato SVG asociado a la categoría.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Numérico</td><td>Posición en la que se muestra la categoría dentro del lobby de la plataforma de usuarios online.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Estado actual de la categoría <em>(Activa o Inactiva)</em>.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Texto</td><td>Vertical a la que pertenece la categoría <em>(Casino, Virtuales, Mini Games o Bingo)</em>.</td></tr></tbody></table>

***

### 6. Agregar categoría

Permite registrar una nueva categoría para el partner y país seleccionados. Al seleccionar el botón **Agregar**, se abre una ventana emergente con los siguientes campos:

<table><thead><tr><th width="130">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Slug</code></strong></td><td>Campo de texto</td><td>Identificador de la categoría utilizado internamente por el sistema.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Nombre con el que se identifica la categoría.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País para el cual se habilitará la categoría.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Vertical a la que pertenece la categoría <em>(Casino, Virtuales, Mini Games o Bingo)</em>.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Numérico</td><td>Posición en la que se mostrará la categoría dentro del lobby de la plataforma de usuarios online.</td></tr><tr><td><strong><code>SVG Icono</code></strong></td><td>Campo de texto</td><td>Código SVG del ícono que representa la categoría en la plataforma.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Define si la categoría queda <em>Activa</em> o <em>Inactiva</em> desde su creación.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Todos los campos son obligatorios. Para completar el registro, es necesario seleccionar el botón **Guardar**.
{% endhint %}

***

### 7. Validaciones y reglas del negocio:

* El campo **`País`** es obligatorio para ejecutar la consulta.
* Todos los campos del formulario **Agregar categoría** son obligatorios.
* Las categorías registradas en este módulo son las que quedan disponibles para asignar juegos desde la sección [Orden y gestión de juegos](https://app.gitbook.com/s/Ojl0Z2z0C78jMb0KvTb8/manual-de-usuario/como-ingresar/productos/orden-y-gestion-de-juegos) para asignarle los juegos.
* Únicamente las categorías en estado **Activa** se muestran en la sección correspondiente de la plataforma de usuarios online.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="102">Versión</th><th width="127">Fecha</th><th width="169">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>31/08/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
