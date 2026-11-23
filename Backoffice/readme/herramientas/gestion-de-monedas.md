---
description: >-
  Desde este módulo se pueden visualizar las monedas habilitadas para la
  creación de partners en la herramienta Sitebuilder, así como modificar el
  estado de cada moneda según corresponda.
---

# Gestión de monedas

### **1. Acceso al Módulo**

**Ruta de Acceso**: BackOffice > Menú principal > Herramientas > Gestión de Monedas.

***

### **2.🖼️Visualización**

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FbIiWcsnYV0PiRcuoTQp5%2Fimage.png?alt=media&#x26;token=78f98d87-a936-481c-baa8-45c2d3f0d752" alt=""><figcaption><p>Figura #1: Captura de pantalla módulo gestión de monedas.</p></figcaption></figure>

***

### **3.🧑‍💻Acciones de usuario**

<table><thead><tr><th width="137.33331298828125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/gestion-de-monedas#id-3.1-filtros"><strong>Filtrar</strong></a></td><td>Permite aplicar criterios de búsqueda para localizar monedas disponibles en el sistema.</td></tr><tr><td><strong>Consultar</strong></td><td>Ejecuta la búsqueda con base en los filtros configurados y muestra las monedas que coinciden con los criterios seleccionados.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/gestion-de-monedas#editar-moneda"><strong>Editar estado</strong></a></td><td>Permite modificar el estado de disponibilidad de la moneda.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite descargar el resultado de la consulta en formatos <strong>Excel </strong><em><strong>(.XLS)</strong></em> y <strong>PDF</strong>, conservando los filtros aplicados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros y campos del formulario a su estado inicial.</td></tr></tbody></table>

#### **3.1 🔎 Filtros**

<table><thead><tr><th width="153.66668701171875">Campo</th><th width="147.33331298828125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Moneda</code></strong></td><td>Texto</td><td>Permite filtrar las monedas ingresando su <a href="https://virtualsoft.gitbook.io/untitled/glosario#codigo-iso">código ISO</a>.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Numérico</td><td>Permite filtrar la moneda mediante su código único identificador dentro del sistema.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Desplegable</td><td>Permite filtrar las monedas según su estado de disponibilidad <em>(Activo / Inactivo)</em>.</td></tr></tbody></table>

#### **3.2 🚀 Tabla de países**

<table><thead><tr><th width="156">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>🖋️</code></strong></td><td>Abre un pop-up con el detalle de la moneda seleccionada, desde donde se puede consultar su información y modificar su estado.<br><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/gestion-de-monedas#editar-moneda" class="button secondary">Editar moneda</a></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Muestra el <a href="https://virtualsoft.gitbook.io/untitled/glosario#codigo-iso">código ISO</a> que identifica la moneda.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Indica el identificador numérico único asignado a la moneda dentro del sistema.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Presenta el nombre o descripción completa de la moneda.</td></tr><tr><td><strong><code>Estatus</code></strong></td><td>Indica si la moneda se encuentra habilitada o deshabilitada para su uso en la creación de partners.</td></tr><tr><td><strong><code>Símbolo</code></strong></td><td>Visualiza el símbolo representativo de la moneda.</td></tr></tbody></table>

<details>

<summary><strong>Editar moneda</strong></summary>

A continuación, se describen los campos visualizados en el pop-up de detalles de la moneda.\
Todos los campos son informativos, **excepto el campo Estado**, que es el único editable.

<table><thead><tr><th width="160">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Moneda</code></strong></td><td>Muestra el código ISO que identifica la moneda seleccionada.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Presenta el nombre o descripción completa de la moneda.</td></tr><tr><td><strong><code>Símbolo</code></strong></td><td>Indica el símbolo representativo de la moneda.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Muestra el identificador numérico único asignado a la moneda dentro del sistema.</td></tr><tr><td><strong><code>Estado</code></strong></td><td><p>Define la disponibilidad de la moneda para la creación de partners en <a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar#id-3.2.-crear-nuevo-partner">Sitebuilder</a>:</p><ul><li><strong>Activo:</strong> Permite utilizar la moneda durante la creación de partners en la herramienta Sitebuilder.</li><li><strong>Inactivo:</strong> Impide que la moneda esté disponible al momento de crear un partner.</li></ul></td></tr></tbody></table>

* **Guardar:** Aplica y almacena el cambio realizado en el estado de la moneda.
* **Cancelar:** Cierra el pop-up sin guardar cambios.

</details>

***

### **4.✅ Validaciones y reglas de negocio**

* Los filtros no son obligatorios para realizar la consulta.
* Si se realiza la consulta sin aplicar ningún filtro, el sistema desplegará todas las monedas disponibles.

***

### **5.🕒 Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 03/02/2026 | Ronald Peláez | Documento inicial  |
