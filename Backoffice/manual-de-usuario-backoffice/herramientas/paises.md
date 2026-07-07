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

# Países

Desde este módulo se pueden visualizar los países habilitados para la creación de partners en la herramienta Sitebuilder, así como modificar el estado de cada país según corresponda.

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Herramientas > Países

***

### 2.🖼️Visualización

<figure><img src="../../.gitbook/assets/image (633).png" alt=""><figcaption><p>Figura#1: Pantalla principal del módulo Países.</p></figcaption></figure>

***

### 3.🧑‍💻Acciones de usuario

<table><thead><tr><th width="137.33331298828125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/paises#id-3.1-filtros"><strong>Filtrar</strong></a></td><td>Permite filtrar información sobre los países disponibles para crear partners en Sitebuilder.</td></tr><tr><td><strong>Consultar</strong></td><td>Aplica los filtros seleccionados y muestra los países disponibles para crear partners.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/paises#detalle-del-pais"><strong>Editar estado</strong></a></td><td>Permite editar el estado del país.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel </strong><em><strong>(.XLS)</strong></em> y <strong>PDF.</strong></td></tr><tr><td><strong>Limpiar</strong> </td><td>Restablece todos los campos del formulario a su estado inicial.</td></tr></tbody></table>

#### 3.1 🔎 Filtros

<table><thead><tr><th width="153.66668701171875">Campo</th><th width="147.33331298828125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Filtra por el identificador único asignado al país.</td></tr><tr><td><strong><code>ISO</code></strong></td><td>Texto</td><td>Filtra por el código ISO del país <em>(por ejemplo, CO, MX, AR).</em></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Filtra por el nombre del país.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Texto</td><td>Filtra por el código o nombre de la moneda asociada al país.</td></tr><tr><td><strong><code>UTC</code></strong></td><td>Texto</td><td>Filtra por la zona horaria <em>(UTC)</em> configurada para el país.</td></tr><tr><td><strong><code>Lenguaje</code></strong></td><td>Texto</td><td>Filtra por el idioma configurado para el país.</td></tr><tr><td><strong><code>Prefijo celular</code></strong></td><td>Texto</td><td>Filtra por el prefijo telefónico internacional del país.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#codigo-path"><strong><code>Código PATH</code></strong></a></td><td>Texto</td><td>Filtra por el código PATH utilizado para la configuración del país en Sitebuilder.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Desplegable</td><td>Filtra los países según su estado <em>(Activo / Inactivo)</em>.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: Si no se aplica ningún filtro, el sistema mostrará todos los países registrados.
{% endhint %}

#### 3.2 🚀 Tabla de países

<table><thead><tr><th width="156">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>🖋️</code></strong></td><td>Despliega un pop-up con el detalle del país seleccionado, permitiendo visualizar y gestionar su estado.<br><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/paises#detalle-del-pais" class="button secondary">Detalles del país</a></td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del país dentro del sistema.</td></tr><tr><td><strong><code>ISO</code></strong></td><td>Código ISO del país utilizado para su identificación estándar.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre completo del país.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda configurada para las operaciones del país.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Indica si el país se encuentra <strong>Activo</strong> o <strong>Inactivo</strong> para la creación de partners en Sitebuilder.</td></tr><tr><td><strong><code>Lenguaje</code></strong></td><td>Idioma configurado por defecto para el país.</td></tr><tr><td><strong><code>UTC</code></strong></td><td>Zona horaria asociada al país.</td></tr><tr><td><strong><code>Prefijo celular</code></strong></td><td>Prefijo telefónico internacional utilizado para números móviles.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#codigo-path"><strong><code>Código PATH</code></strong></a></td><td>Código PATH utilizado para la configuración y ruteo del país en Sitebuilder.</td></tr></tbody></table>

<details>

<summary><strong>Detalle del país</strong></summary>

A continuación, se describen los campos visualizados en el pop-up de detalle del país.\
Todos los campos son informativos, **excepto el campo Estado**, que es el único editable.

<table><thead><tr><th width="160">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del país dentro del sistema.</td></tr><tr><td><strong><code>ISO</code></strong></td><td>Código ISO del país utilizado como estándar de identificación.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre completo del país.</td></tr><tr><td><strong><code>Lenguaje</code></strong></td><td>Idioma configurado por defecto para el país.</td></tr><tr><td><strong><code>UTC</code></strong></td><td>Zona horaria asociada al país.</td></tr><tr><td><strong><code>Prefijo celular</code></strong></td><td>Prefijo telefónico internacional utilizado para números móviles.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda configurada para las operaciones del país.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#codigo-path"><strong><code>Código PATH</code></strong></a></td><td>Código que identifica la ruta del país dentro del sistema y se utiliza para su configuración en Sitebuilder.</td></tr><tr><td><strong><code>Estado</code></strong></td><td><p>Define la disponibilidad del país para la creación de partners en <a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar#id-3.2.-crear-nuevo-partner">Sitebuilder</a>:</p><ul><li><strong>Activo:</strong> El país puede ser utilizado para crear partners en la herramienta Sitebuilder.</li><li><strong>Inactivo:</strong> El país no estará disponible al momento de crear un partner.</li></ul></td></tr></tbody></table>

* **Guardar:** Aplica y almacena el cambio realizado en el estado del país.
* **Cancelar:** Cierra el pop-up sin guardar ningún cambio.

</details>

***

### 4.✅ Validaciones y reglas de negocio

* Los filtros no son obligatorios para realizar la consulta.
* Este módulo estará disponible solo si se cuentan con los permisos necesarios.

***

### 5.🕒 Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 24/01/2025 | Ronald Peláez | Documento inicial  |
