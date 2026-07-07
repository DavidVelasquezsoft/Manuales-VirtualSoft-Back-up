---
description: >-
  En esta sección se podrán consultar, mediante filtros, la información de una o
  varias etiquetas.
---

# Etiquetas

### 1. Acceso al Módulo <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de Acceso**: Backoffice > Productos > Etiquetas.

***

### 2. Visualización <a href="#id-2.-visualizacion" id="id-2.-visualizacion"></a>

<figure><img src="../../.gitbook/assets/image (562).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección etiquetas.</p></figcaption></figure>

***

### 3.  Acciones disponibles

<table><thead><tr><th width="120.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Permiten filtrar la información para obtener resultados mas precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><strong>Consultar</strong></td><td>Aplica los filtros seleccionados y muestra los proveedores y subproveedores válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. ¿Cómo buscar una etiqueta?

**📌 Filtros disponibles**

En esta sección se puede consultar información de etiquetas aplicando los siguientes filtros:

<table><thead><tr><th width="124">Campo</th><th width="184">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Campo de texto</td><td>Identificador único de la etiqueta.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Nombre asignado a la etiqueta.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Define si la etiqueta está Activa o Inactiva.</td></tr></tbody></table>

### 5.  Resultados de la consulta

Al realizar la búsqueda se muestran los siguientes datos en la tabla de resultados:

<table><thead><tr><th width="319">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único de la etiqueta.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre de la etiqueta.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Descripción detallada de la etiqueta.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual de la etiqueta (Activo/Inactivo).</td></tr><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha en la que se creó la etiqueta.</td></tr></tbody></table>

***

### 6. Editar Etiqueta

En la primer coluna se encuentra un icono de lápiz que permite  la modificación de una etiqueta existente.

{% hint style="warning" %}
**Nota:**\
El campo **ID** no puede ser editado, ya que corresponde al identificador único.
{% endhint %}

<table><thead><tr><th width="129">Campo</th><th>Tipo de Control</th><th width="303">Descripción</th><th>Validaciones</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Campo de texto (solo lectura)</td><td>Identificador único de la etiqueta.</td><td>No se puede modificar.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Nombre asignado a la etiqueta.</td><td>Obligatorio.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Detalle descriptivo de la etiqueta.</td><td>Opcional.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Define si la etiqueta está <strong>Activa</strong> o <strong>Inactiva</strong>.</td><td>Solo admite valores: <strong>Activo</strong> / <strong>Inactivo</strong>.</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Botón</td><td>Actualiza los datos de la etiqueta con los cambios realizados.</td><td>N/A</td></tr><tr><td><strong>Cancelar</strong></td><td>Botón</td><td>Cierra el formulario sin guardar cambios.</td><td>N/A</td></tr></tbody></table>

### 7.  Añadir Etiqueta

Para registrar una nueva etiqueta, ubica y haz clic en el botón **"Añadir Etiqueta"**.\
A continuación, completa los campos requeridos en el formulario, estos son obligatorios para la creación:

<table><thead><tr><th width="152">Campo</th><th width="185">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Nombre o detalle de la etiqueta.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Detalle o información adicional de la etiqueta.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Define si la etiqueta está Activa o Inactiva.</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Botón</td><td>Almacena la etiqueta creada.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Botón</td><td>Cierra la ventana sin guardar cambios.</td></tr></tbody></table>

***

### 8.  Validaciones y Reglas de Negocio

* El campo **Estado** es obligatorio (Activo/Inactivo).
* No se permiten etiquetas duplicadas con el mismo nombre.

***

### 9. Control de Versiones

<details>

<summary>🔽Historial de Versiones</summary>

<table><thead><tr><th width="98">Versión</th><th width="143">Fecha</th><th width="164">Autor</th><th>Descripción del cambio</th></tr></thead><tbody><tr><td>1.0</td><td>28/08/2025</td><td>Karol Navia</td><td>Creación del documento.</td></tr></tbody></table>

</details>
