---
description: >-
  Este módulo permite administrar las criptomonedas disponibles en la
  plataforma, definiendo sus atributos básicos, tipo, estado e identificación.
---

# Criptomonedas

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Productos > Criptomonedas

***

### 2. Visualización:

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FJloPXmobEPGeDSL53m1x%2Fimage.png?alt=media&#x26;token=00051f21-e8cf-4ca0-9ae7-7456c981a782" alt=""><figcaption><p>Figura #1: Vista inicial de criptomonedas registradas.</p></figcaption></figure>

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="118">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong>​</td><td>Permiten realizar búsquedas específicas mediante la selección de uno o varios filtros</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los campos de filtros a su estado inicial, eliminando cualquier criterio seleccionado previamente y permitiendo realizar una nueva búsqueda desde cero.</td></tr><tr><td><strong>​Consultar</strong></td><td>Ejecuta la búsqueda de acuerdo con los filtros definidos por el usuario y muestra los resultados en la tabla correspondiente.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite descargar la información resultante de la consulta en un archivo en formato Excel, el cual se descarga desde la parte inferior derecha de la pantalla.</td></tr></tbody></table>

### 4. Filtros  <a href="#id-2.-filtros" id="id-2.-filtros"></a>

<table><thead><tr><th width="154.890869140625">Sección</th><th width="146.39996337890625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Criptomoneda</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por nombre de criptomoneda.</td></tr><tr><td><strong><code>Tipo de criptomoneda</code></strong></td><td>Lista desplegable</td><td>Permite filtrar según el tipo:<br>• Estable (ej: USDT).<br>• Inestable (ej: BTC).</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra por el estado de la moneda:<br>• Activa<br>• Inactiva</td></tr><tr><td><strong><code>Nueva Criptomoneda</code></strong></td><td>Botón</td><td>Abre el formulario para crear una nueva criptomoneda.</td></tr><tr><td><strong><code>Limpiar</code></strong></td><td>Botón</td><td>Restablece los filtros aplicados.</td></tr><tr><td><strong><code>Consultar</code></strong></td><td>Botón</td><td>Ejecuta la búsqueda con los filtros definidos.</td></tr></tbody></table>

***

### 5. Tabla de resultados

En la sección principal se listan todas las criptomonedas creadas con sus respectivos atributos:

<table><thead><tr><th width="158.09088134765625">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Criptomoneda</code></strong></td><td>Identificador único asignado a la criptomoneda.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre de la criptomoneda registrada.</td></tr><tr><td><strong><code>Código ISO</code></strong></td><td>Código de 3 letras asociado.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Indica si la criptomoneda es estable o inestable.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Muestra si la criptomoneda está activa o inactiva.</td></tr></tbody></table>

***

### 6. Como editar una criptomoneda

La opción de **editar criptomoneda** se encuentra en la columna **Acciones** de la tabla principal. Para acceder, se debe dar clic en el ícono de **lápiz** ✏️.

Al hacerlo, se abrirá el formulario de **Edición de Criptomoneda**, donde se muestran los siguientes campos:

<table><thead><tr><th width="142.4000244140625">Campo</th><th width="371">Descripción</th><th width="125">Tipo de control</th><th width="105.5999755859375">Editable</th></tr></thead><tbody><tr><td><strong><code>Id Criptomoneda</code></strong></td><td>Identificador único asignado automáticamente a la criptomoneda.</td><td>Texto</td><td>No</td></tr><tr><td><strong><code>Nombre de Criptomoneda</code></strong></td><td>Nombre de la criptomoneda registrada en el sistema.</td><td>Texto</td><td>No</td></tr><tr><td><strong><code>Código ISO</code></strong></td><td>Código ISO correspondiente a la criptomoneda.</td><td>Texto</td><td>No</td></tr><tr><td><strong><code>Tipo de Criptomoneda</code></strong></td><td>Clasificación de la criptomoneda según su naturaleza.</td><td>Desplegable</td><td>Sí</td></tr><tr><td><strong><code>Subir Ícono</code></strong></td><td>Permite cargar o actualizar el ícono representativo de la criptomoneda.</td><td>Botón</td><td>Sí</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Define si la criptomoneda se encuentra <strong>Activa</strong> o <strong>Inactiva</strong>.</td><td>Desplegable</td><td>Sí</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Cierra el formulario sin guardar los cambios realizados.</td><td>Botón</td><td>N/A</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Almacena los cambios realizados en los campos editables.</td><td>Botón</td><td>N/A</td></tr></tbody></table>

### 6. Creación de una Nueva Criptomoneda

Para añadir una criptomoneda, haga clic en el botón **“Nueva criptomoneda”**. Esta acción desplegará una ventana emergente (pop-up) con los campos necesarios para el registro.

<table><thead><tr><th width="158.09088134765625">Campo</th><th width="136">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre de Criptomoneda</code></strong></td><td>Texto</td><td>Define el nombre de la criptomoneda.</td></tr><tr><td><strong><code>Código ISO</code></strong></td><td>Texto</td><td>Introduce el código ISO de 3 letras que identifica la moneda.</td></tr><tr><td><strong><code>Tipo de Criptomoneda</code></strong></td><td>Lista desplegable</td><td>Define si la criptomoneda será:<br>• Estable: valor ligado a otra moneda (ej: USD).<br>• Inestable: valor fluctuante (ej: BTC).</td></tr><tr><td><strong><code>Subir Icono</code></strong></td><td>Botón</td><td>Permite cargar la imagen representativa de la criptomoneda.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Indica si la criptomoneda estará activa o inactiva.</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Botón</td><td>Registra la criptomoneda en el sistema.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Botón</td><td>Cierra el formulario sin guardar cambios.</td></tr></tbody></table>

***

### **7.  Validaciones y Reglas de Negocio**

* Solo los usuarios con permisos habilitados podrán realizar la creación o edición de criptomonedas.
* El código ISO debe cumplir el estándar de **3 letras en mayúscula**.
* El nombre de la criptomoneda no puede repetirse en registros existentes.
* Al crear o editar una criptomoneda no es necesario subir un icono de esta, en caso de no subirla, la criptomoneda se creará sin errores.

***

### **8. Control de Versiones**

<details>

<summary>🔽Historial de versiones</summary>

| Versión | Fecha      | Autor         | Cambios Realizados     |
| ------- | ---------- | ------------- | ---------------------- |
| 1.0     | 27/08/2025 | Karol Navia   | Documento inicial      |
| 1.1     | 16/12/2025 | Ronald Peláez | Refinamiento de manual |

</details>
