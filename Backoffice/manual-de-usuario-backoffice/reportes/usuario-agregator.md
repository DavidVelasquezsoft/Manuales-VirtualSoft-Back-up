---
description: >-
  La funcionalidad de Relación Usuario Agregator permite consultar y gestionar
  la relación entre el ID de un usuario y su ID de casino asociado. Esta
  relación es utilizada para registrar correctamente
---

# Usuario - Agregator

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Usuario - Agregator

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (568).png" alt=""><figcaption><p>Figura#1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="127.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="usuario-agregator.md#id-4.-filtros-principales"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="usuario-agregator.md#id-3.3-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. **Filtros principales**

<table><thead><tr><th width="121.111083984375">Campo</th><th width="124.4444580078125">Tipo de Control</th><th width="498.8890380859375">Descripción</th></tr></thead><tbody><tr><td><p><strong><code>Usuario</code></strong> </p><p><strong><code>Partner</code></strong></p></td><td>Numérico</td><td>Identificador único del usuario asociado <em>(partner).</em></td></tr><tr><td><p><strong><code>Usuario</code></strong> </p><p><strong><code>Agregator</code></strong></p></td><td>Numérico</td><td>Identificador del usuario dentro del sistema Agregator.</td></tr><tr><td><p><strong><code>Fecha de</code></strong> </p><p><strong><code>Creación</code></strong></p></td><td>Calendario</td><td>Rango de fechas en que se registró la relación.</td></tr></tbody></table>

### **5. Resultados de consulta**

<table><thead><tr><th width="209">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario Partner</code></strong></td><td>ID del usuario asociado al partner.</td></tr><tr><td><strong><code>Usuario Agregator</code></strong></td><td>ID del usuario dentro del sistema Agregator.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha en la que se creó la relación entre el Usuario Partner y el Usuario Agregator.</td></tr></tbody></table>

### **6. Añadir Relación**

Para agregar un usuario a un partner, se debe utilizar el botón **"Añadir Relación"**, que permite establecer un nuevo vínculo entre el **Usuario Partner** y el **Usuario Agregator**.

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FHz4ihEoDosPXd3EHiOSb%2Fimage.png?alt=media&#x26;token=86c368b8-3027-4fb4-bd3b-c5a91c898181" alt="" width="231"><figcaption><p>Figura#2: Captura de pantalla añadir relación.</p></figcaption></figure>

**Campos del formulario:**

<table><thead><tr><th width="232">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario Partner</code></strong></td><td>Selección del usuario que se vinculará con el partner.</td></tr><tr><td><strong><code>Usuario Agregator</code></strong></td><td>Usuario que formará parte de la relación.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha en la que se establece la relación.</td></tr></tbody></table>

Una vez diligenciados los campos, se debe confirmar la acción para guardar la nueva relación en el sistema.

***

### 7. Validaciones y Reglas de Negocio

* No es necesario completar todos los filtros para realizar una búsqueda.
* La combinación **Usuario Partner + Usuario Agregator** debe ser única.
* La **Fecha de Creación** no puede ser mayor a la fecha actual.

***

### 8. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="112">Versión</th><th width="135">Fecha</th><th width="150">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/08/2025</td><td>Ronald Peláez</td><td>Documento inicial del manual</td></tr></tbody></table>

</details>
