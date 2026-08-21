---
description: >-
  Esta sección permite consultar, crear y gestionar las etiquetas disponibles en
  el sistema, utilizadas para clasificar y organizar los elementos asociados
  dentro de la plataforma.
---

# Etiquetas

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Productos > Etiquetas

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (562).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección etiquetas.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="180">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="etiquetas.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información de las etiquetas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="etiquetas.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las etiquetas en la tabla de resultados.</td></tr><tr><td><a href="etiquetas.md#id-7.-anadir-etiqueta"><strong>Añadir Etiqueta</strong></a></td><td>Permite registrar una nueva etiqueta mediante una ventana emergente.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="124">Campo</th><th width="184">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Indica el identificador único de la etiqueta.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre asignado a la etiqueta.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra las etiquetas según su estado <em>(Activa o Inactiva)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con las etiquetas que cumplen con los filtros aplicados.

<table><thead><tr><th width="155.66668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Editar</code></strong> <em>(✏️)</em></td><td>Permite modificar la información de la etiqueta seleccionada. Su funcionamiento se detalla en Editar etiqueta.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único de la etiqueta.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre asignado a la etiqueta.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Detalle descriptivo de la etiqueta.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual de la etiqueta <em>(Activa o Inactiva)</em>.</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha en la que se registró la etiqueta.</td></tr></tbody></table>

***

### 6. Editar etiqueta

Al seleccionar el ícono de lápiz _(✏️)_ ubicado en la primera columna de la tabla de resultados, se abre una ventana que permite modificar la información de la etiqueta.

<table><thead><tr><th width="129">Campo</th><th width="150">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>No editable</td><td>Identificador único de la etiqueta. Se muestra solo como referencia.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Nombre asignado a la etiqueta. Es un campo obligatorio.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Detalle descriptivo de la etiqueta. Es un campo opcional.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Define si la etiqueta queda <em>Activa</em> o <em>Inactiva</em>.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Para que las modificaciones queden registradas, es necesario seleccionar el botón **Guardar**. El botón **Cancelar** cierra el formulario sin aplicar los cambios.
{% endhint %}

***

### 7. Añadir etiqueta

Permite registrar una nueva etiqueta en el sistema. Al seleccionar el botón **Añadir Etiqueta**, se abre una ventana emergente con los siguientes campos:

<table><thead><tr><th width="152">Campo</th><th width="150">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Nombre con el que se identifica la etiqueta.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Detalle o información adicional de la etiqueta.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Define si la etiqueta queda <em>Activa</em> o <em>Inactiva</em> desde su creación.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Para completar el registro, es necesario seleccionar el botón **Guardar**. El botón **Cancelar** cierra la ventana sin guardar la etiqueta.
{% endhint %}

***

### 8. Validaciones y reglas del negocio:

* Los campos **`Nombre`** y **`Estado`** son obligatorios para crear o editar una etiqueta.
* El campo **`Descripción`** es opcional.
* El campo **`ID`** no puede modificarse, ya que corresponde al identificador único de la etiqueta.
* No se permiten etiquetas duplicadas con el mismo nombre.
* Los cambios realizados al crear o editar una etiqueta requieren seleccionar el botón **Guardar** para aplicarse.

***

### 9. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="98">Versión</th><th width="143">Fecha</th><th width="164">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/08/2025</td><td>Karol Navia</td><td>Creación del documento.</td></tr><tr><td>1.1</td><td>21/08/2026</td><td>David Velasquez</td><td>Actualización de formato.</td></tr></tbody></table>

</details>
