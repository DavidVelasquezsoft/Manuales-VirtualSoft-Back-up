---
description: >-
  Permite crear, gestionar y consultar diferentes tipos de restricciones a
  usuarios.
---

# Restricción de usuarios

***

### 1. Acceso al Módulo <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de Acceso**: Backoffice > Gestión > Restricción de usuarios

***

### 2.  Visualización general <a href="#id-4.-visualizacion" id="id-4.-visualizacion"></a>

<figure><img src="../../.gitbook/assets/image (323).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección restricción de usuarios</p></figcaption></figure>

***

### 3.  Acciones de usuario

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="restriccion-de-usuarios.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="restriccion-de-usuarios.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra las restricciones validas.</td></tr><tr><td><a href="restriccion-de-usuarios.md#id-3.4.-carga-masiva-de-restricciones"><strong>Cargar CSV</strong></a></td><td>Permite cargar un archivo tipo <a href="https://virtualsoft.gitbook.io/untitled/glosario/#csv">CSV</a> para aplicar restricciones a varios usuarios simultáneamente</td></tr><tr><td><a href="restriccion-de-usuarios.md#id-3.3.-creacion-de-una-restriccion"><strong>Crear restricción</strong></a></td><td>Permite crear una nueva restricción para un usuario.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="139.66668701171875">Campo</th><th width="140.44451904296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único de la restricción, asignado automáticamente por el sistema.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Correo electrónico</td><td>Dirección de correo electrónico asociada al usuario al que se le aplica la restricción.</td></tr><tr><td><strong><code>Documento</code></strong></td><td>Numérico</td><td>Número de identificación del usuario restringido, según el documento registrado.</td></tr><tr><td><strong><code>Tipo de Documento</code></strong></td><td>Lista desplegable</td><td>Tipo de documento de identificación del usuario. (<em>ejemplo: DNI, pasaporte o cédula de extrangeria.</em>)</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre completo del usuario al que se le ha aplicado la restricción.</td></tr><tr><td><strong><code>Teléfono</code></strong></td><td>Numérico</td><td>Número de teléfono registrado del usuario restringido.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#partner">Partner</a> u operación a la que pertenece el usuario restringido.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País asociado al usuario sobre el cual se aplica la restricción.</td></tr><tr><td><strong><code>Tipo de Restricción</code></strong></td><td>Lista desplegable</td><td>Clasificación de la restricción aplicada al usuario, como acceso limitado o bloqueo de transacciones.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Indica si la restricción se encuentra actualmente activa o eliminada.</td></tr></tbody></table>

### 5. Resultados de consulta

Permite visualizar las restricciones validas segun los filtros, con los siguientes campos:

<table><thead><tr><th width="146.77783203125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td>Permite gestionar la restricción mediante las siguientes acciones.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único asignado por el sistema para identificar la restricción.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Categoría o tipo de restricción aplicada al usuario.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Dirección de correo electrónico del usuario restringido.</td></tr><tr><td><strong><code>Documento</code></strong></td><td>Número de identificación del usuario restringido según el documento registrado.</td></tr><tr><td><strong><code>Tipo de Documento</code></strong></td><td>Tipo de documento de identificación del usuario.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre completo del usuario al que se le aplicó la restricción.</td></tr><tr><td><strong><code>Teléfono</code></strong></td><td>Número telefónico asociado al usuario restringido.</td></tr><tr><td><strong><code>Partner</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#partner">Partner</a> en el que se restringió el usuario.</td></tr><tr><td><strong><code>País</code></strong></td><td>País de residencia asociado al usuario restringido.</td></tr><tr><td><strong><code>Usuario de Creación</code></strong></td><td>Usuario del sistema que registró la restricción.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha en la que la restricción fue creada en el sistema.</td></tr><tr><td><strong><code>Estado del Usuario</code></strong></td><td>Indica si el usuario se encuentra activo o inactivo en la plataforma.</td></tr><tr><td><strong><code>Fecha de Modificación</code></strong></td><td>Fecha de la última actualización realizada sobre la restricción.</td></tr><tr><td><strong><code>Nota</code></strong></td><td>Observaciones o comentarios adicionales relacionados con la restricción aplicada.</td></tr></tbody></table>

### **6.  Creación de una Restricción**

Abre modal que permite crear una nueva restricción a un usuario con los siguientes campos obligatorios:

<table><thead><tr><th width="131.5">Campo</th><th width="190">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Email</code></strong></td><td>Correo electrónico</td><td>Indica la dirección de correo electrónico del usuario al que se le aplicará la restricción.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar la clasificación de la restricción que se aplicará al usuario.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Muestra o registra el nombre completo del usuario a restringir.</td></tr><tr><td><strong><code>Teléfono</code></strong></td><td>Numérico</td><td>Especifica el número de contacto asociado al usuario.</td></tr><tr><td><strong><code>Tipo de Documento</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el tipo de identificación del usuario, por ejemplo, cédula o pasaporte.</td></tr><tr><td><strong><code>Documento</code></strong></td><td>Numérico</td><td>Indica el número de identificación del usuario según el tipo de documento seleccionado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el país al que pertenece el usuario restringido.</td></tr></tbody></table>

Una vez completados los campos requeridos, presiona “**Guardar**” para crear la restricción. Para descartar los cambios, selecciona “**Cancelar**”.

### **7. Carga Masiva de Restricciones "CSV"**

Abre modal que permite aplicar restricciones a varios usuarios simultáneamente, mediante estos campos.

<table><thead><tr><th width="139">Campos</th><th width="135">Tipo</th><th>Descripciones</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Selecciona el partner al que pertenecen los usuarios.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Indica el país en el que se encuentran los usuarios.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar la clasificación de la restricción que se aplicará al usuario.</td></tr><tr><td><strong><code>Cargar</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#csv"><strong><code>archivo CSV</code></strong></a></td><td>Botón</td><td>Permite cargar un archivo CSV con los usuarios a los que se aplicará la restricción. Si no cuentas con el formato correcto, descarga la plantilla desde <strong>“Descargar archivo de ejemplo”</strong>.</td></tr><tr><td><strong><code>Descargar archivo ejemplo</code></strong></td><td>Botón</td><td>Permite descargar un archivo CSV de referencia con el formato y el orden de campos requeridos para la correcta creación de restricciones.</td></tr></tbody></table>

Una vez completados todos los campos, debes presionar **"Guardar"** para confirmar la restricción. Si no deseas continuar con el proceso, puedes hacer clic en **"Cancelar"**.

***

### 8. Control de versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="104">Versión</th><th width="127">Fecha</th><th width="168">Autor</th><th>Descripción</th></tr></thead><tbody><tr><td>1.0</td><td>07/01/2026</td><td>David Velásquez</td><td>Creación inicial del documento.</td></tr></tbody></table>

</details>
