---
description: >-
  Permite consultar la información de uno o varios proveedores utilizando
  filtros, así como también añadir nuevos proveedores.
---

# Proveedores

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Productos > Proveedores.

***

### 2. Visualización:

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FmHYYRqohBLTROYktY6BV%2Fimage.png?alt=media&#x26;token=3019108b-7954-4eef-98fb-5c53e5df8acb" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Proveedores.</p></figcaption></figure>

### **3. Acciones del Usuario**

<table><thead><tr><th width="156">Acción</th><th width="586.39990234375">Descripción</th></tr></thead><tbody><tr><td><a href="proveedores.md#id-4.-filtros-de-busqueda"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros aplicados, mostrando en la tabla los registros que cumplen con los criterios definidos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los campos de los filtros a su valor predeterminado, eliminando cualquier criterio aplicado para permitir una nueva búsqueda desde cero.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite descargar la información visualizada en pantalla en formato <em>(<strong>Excel</strong> o <strong>CSV)</strong></em>, utilizando el botón <em><strong>(Exportar)</strong></em> ubicado en la parte inferior de la página.</td></tr><tr><td><a href="proveedores.md#id-7.-editar-proveedor"><strong>Editar</strong></a></td><td>Habilita la modificación de un registro existente, permitiendo actualizar su información o ajustar configuraciones previamente guardadas.</td></tr><tr><td><a href="proveedores.md#id-6.-anadir-proveedor"><strong>Agregar</strong></a></td><td>permite registrar un nuevo proveedor en el sistema .</td></tr></tbody></table>

### 4. Filtros de Búsqueda

<table><thead><tr><th width="128">Filtro</th><th width="121">Tipo de Control</th><th width="472.5999755859375">Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor ID</code></strong></td><td>Texto</td><td>Permite buscar un proveedor específico ingresando su identificador único.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Filtra proveedores según el nombre registrado en el sistema.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Filtra  por la categoría a la que pertenecen <em>(ejemplo: Casino, CRM).</em></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite filtrar proveedores según su estado en la plataforma.</td></tr></tbody></table>

### 5. Resultados de la Consulta

<table><thead><tr><th width="154">Campo</th><th width="573">Descripción</th></tr></thead><tbody><tr><td><a href="proveedores.md#id-7.-editar-proveedor"><strong><code>🖋(Editar)</code></strong></a></td><td>Permite modificar la información de un proveedor. </td></tr><tr><td><strong><code>Proveedor ID</code></strong></td><td>Identificador único asignado al proveedor en el sistema.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre oficial del proveedor registrado.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Clasificación del proveedor según el servicio ofrecido.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del proveedor dentro de la plataforma.</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Indica si el proveedor ha sido validado y aprobado en el sistema.</td></tr><tr><td><strong><code>Abreviado</code></strong></td><td>Abreviatura o alias asignado al proveedor para referencias rápidas.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Url del Logotipo o imagen representativa del proveedor.</td></tr></tbody></table>

***

### **6. Añadir proveedor:**

Para **añadir un nuevo proveedor**, se debe seleccionar el botón **“Añadir proveedor”**, ubicado debajo de la sección de **Filtros Avanzados**. Se desplegará una ventana emergente _(pop-up)_ con los siguientes campos:

<table><thead><tr><th width="155">Campo</th><th width="125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Permite ingresar el nombre completo del proveedor. Este dato será visible en los listados y reportes asociados.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Define el tipo de proveedor disponible en el sistema <em>(ejemplo: Casino, CRM).</em>.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Indica si el proveedor se encuentra <strong>Activado</strong> o <strong>Inactivado</strong>. Solo los proveedores activos estarán disponibles para asignaciones o uso operativo.</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Lista desplegable</td><td><p>Permite definir si el proveedor está habilitado para aprobación manual en operaciones como depósitos o retiros. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Se recomienda mantener este campo en <strong>Inactivo</strong>, ya que establecerlo en <strong>Activo</strong> puede generar errores en el funcionamiento del sistema.</p></div></td></tr><tr><td><strong><code>Abreviado</code></strong></td><td>Texto</td><td>Permite registrar un nombre corto o identificador abreviado del proveedor para uso interno.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Carga de archivo</td><td>Permite subir una imagen representativa del proveedor.</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Botón</td><td>Almacena la información ingresada en el sistema.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Botón</td><td>Descarta los cambios y cierra el formulario. </td></tr></tbody></table>

***

### **7. Editar proveedor**

Para acceder a la edición, se debe seleccionar el **icono de lápiz 🖉**, ubicado en la **primera columna de la tabla de resultados** al consultar los proveedores.

<table><thead><tr><th width="126">Campo</th><th width="121">Tipo de control</th><th>Descripción</th><th width="113">Editable</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>Texto</td><td>Identificador único del proveedor generado automáticamente por el sistema. </td><td>❌ No</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre oficial del proveedor.</td><td>❌ No</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Define la categoría del proveedor. </td><td>❌ No</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite <strong>activar o inactivar</strong> el proveedor.</td><td>✅ Sí</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Lista desplegable</td><td>Cambiar el estado de verificación del proveedor entre <strong>“Activado”</strong> e <strong>“Inactivado”</strong>.</td><td>✅ Sí</td></tr><tr><td><strong><code>Abreviado</code></strong></td><td>Texto</td><td>Modifica para ajustar el nombre corto o alias del proveedor.</td><td>✅ Sí</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Campo de texto</td><td>Actualiza la URL o ruta de la imagen asociada <em>(por ejemplo, logotipo del proveedor).</em></td><td>✅ Sí</td></tr><tr><td><strong><code>Explicación</code></strong></td><td>Texto</td><td> Registrar observaciones o justifica los cambios realizados en la edición.</td><td>✅ Sí</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Botón</td><td>Aplica las modificaciones y actualiza el registro.</td><td>N/A</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Botón</td><td><strong>D</strong>escarta los cambios.</td><td>N/A</td></tr></tbody></table>

***

### **8. Control de Versiones**

<details>

<summary>🔽Historial de versiones </summary>

<table><thead><tr><th width="113.4000244140625">Versión</th><th width="138.79998779296875">Fecha</th><th width="128.2000732421875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/08/2025</td><td>Karol Navia</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>09/10/2025</td><td>Karol Navia</td><td>Incorporación de Añadir proveedor , editar.</td></tr><tr><td>1.2</td><td>29/10/2025</td><td>Karol Navia</td><td>Mejoramiento del campo tipo</td></tr></tbody></table>

</details>
