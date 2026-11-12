---
description: >-
  En esta sección se podrán consultar, mediante filtros, la información de uno o
  varios tipos de partners, además de añadir nuevos partners tipo.
---

# Partners Tipo

### 1. Acceso al Módulo <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de Acceso**: BackOffice > Productos > Partners tipo

### 2. Visualización.&#x20;

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FZ1iFcxLn47c9NXzgbhjG%2Fimage.png?alt=media&#x26;token=b9167280-1a11-4a7b-aaa9-a3f35dd98d19" alt=""><figcaption><p>Figura #1: Captura de pantalla sección partners tipo.</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="118">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong>​</td><td>Permiten realizar búsquedas específicas mediante la selección de uno o varios filtros</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los campos de filtros a su estado inicial, eliminando cualquier criterio seleccionado previamente y permitiendo realizar una nueva búsqueda desde cero.</td></tr><tr><td><strong>​Consultar</strong></td><td>Ejecuta la búsqueda de acuerdo con los filtros definidos por el usuario y muestra los resultados en la tabla correspondiente.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite descargar la información resultante de la consulta en un archivo en formato Excel, el cual se descarga desde la parte inferior derecha de la pantalla.</td></tr></tbody></table>

### 4. ¿Cómo buscar un Tipo de Producto Partner?

Para consultar la información, se dispone de filtros básicos y avanzados.

<table><thead><tr><th width="142">Campo</th><th width="150">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td> Numérico</td><td>Permite buscar un tipo de partner por su identificador único.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Filtra según el producto asignado al partner (Ej: Casino, Apuestas).</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra por el nombre del partner registrado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra por estado del tipo de partner.</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Checkbox</td><td>Filtra si el partner ha sido verificado o no.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra por país de integración.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Numérico</td><td>Establece un valor mínimo asociado al partner.</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Numérico</td><td>Establece un valor máximo asociado al partner.</td></tr><tr><td><strong><code>Tiempo Procesamiento</code></strong></td><td>Numérico</td><td>Filtra según el tiempo de procesamiento configurado.</td></tr></tbody></table>

Una vez aplicados los filtros, haz clic en **"Consultar"** para obtener los resultados.

***

### 5. Información mostrada en la tabla

Al consultar, se presentará una tabla con los siguientes campos:

<table><thead><tr><th width="147">Campo</th><th width="136">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>Texto</td><td>Identificador único del tipo de partner.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Texto</td><td>Nombre del partner registrado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Estado actual del partner.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Texto</td><td>Tipo de producto asignado (Casino, Slots, Deportes, etc.).</td></tr><tr><td><strong><code>Site ID</code></strong></td><td>Texto</td><td>Identificador del sitio asociado al partner.</td></tr><tr><td><strong><code>Clave</code></strong></td><td>Texto </td><td>Clave única para autenticación con el partner.</td></tr><tr><td><strong><code>URL API</code></strong></td><td>Texto (URL)</td><td>Dirección de la API usada para integración.</td></tr><tr><td><strong><code>Tipo de integración</code></strong></td><td>Texto</td><td>Método de integración con el partner.</td></tr><tr><td><strong><code>Contingencia</code></strong></td><td>Texto</td><td>Indica si el partner cuenta tipo de <a href="https://virtualsoft.gitbook.io/untitled/glosario#contingencia">contingencia.</a></td></tr></tbody></table>

***

### 6. ¿Cómo añadir un Tipo de Producto a un Partner?

Al hacer clic en **"Añadir Tipo Producto Partner"**, se abrirá un formulario emergente donde deberás completar los siguientes campos:

<table><thead><tr><th width="150">Campo</th><th width="149">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de producto (Casino, etc.).</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Selecciona el partner con el que se integrará el producto.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Toggle (On/Off)</td><td>Define si el producto estará activado o inactivado.</td></tr><tr><td><strong><code>URL API</code></strong></td><td>Caja de texto (URL)</td><td>Dirección de la API usada para la integración.</td></tr><tr><td><strong><code>Tipo de integración</code></strong></td><td>Lista desplegable</td><td>Método definido para la conexión.</td></tr><tr><td><strong><code>Contingencia</code></strong></td><td>Texto</td><td>Información sobre planes alternativos en caso de fallo.</td></tr></tbody></table>

Una vez completados los campos:

* Haz clic en **"Guardar"** para registrar la información.
* Haz clic en **"Cancelar"** si deseas salir sin guardar.

***

### 7.  Validaciones y Reglas de Negocio

* El **Id** del Tipo de Partner es único y se autogenera en el sistema.
* El campo **Mínimo** debe ser un número mayor que 0.
* El campo **Máximo** debe ser mayor al valor definido en **Mínimo**.
* La **URL API** debe ser una dirección válida con prefijo `http://` o `https://`.
* El **Site ID** debe ser único dentro del sistema.

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="110">Versión</th><th width="211">Fecha</th><th width="189">Autor</th><th>Descripción del cambio</th></tr></thead><tbody><tr><td>1.0</td><td>2025-08-28</td><td>Karol Navia</td><td>Creación del documento </td></tr></tbody></table>

</details>
