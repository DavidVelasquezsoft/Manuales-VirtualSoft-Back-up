---
description: >-
  Permite consultar, mediante filtros, la información de uno o varios partners
  proveedores, además de añadir nuevos partners proveedores.
---

# Partners Proveedores

### 1. Acceso al Módulo

**Ruta de Acceso:** Backoffice > Herramientas > Partner ajustes > Partner > Productos >Parners proveedores

***

### 2. 🖼️ Visualización

<figure><img src="../../../../.gitbook/assets/image (369).png" alt=""><figcaption><p>Figura#1: Captura de pantralla filtros de bisqueda.</p></figcaption></figure>

***

### 3. 🧑‍💻 Acciones disponibles

<table><thead><tr><th width="166.00006103515625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="partners-proveedores.md#id-3.1.-filtros"><strong>Filtrar</strong></a></td><td>Permite definir criterios para ubicar proveedores asociados a un partner.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros a su estado inicial.</td></tr><tr><td><a href="partners-proveedores.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Muestra los registros que cumplen con los filtros seleccionados.</td></tr><tr><td><strong>Añadir Proveedor</strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#partner"><strong>Partner</strong></a></td><td>Permite asociar un nuevo proveedor a el partner.</td></tr></tbody></table>

#### 3.1. 🔎 Filtros

<table><thead><tr><th width="138.77783203125">Campo</th><th width="139.66668701171875">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único del proveedor dentro del partner.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el proveedor.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por el estado actual del proveedor. (<em>Activo/Inactivo</em>)</td></tr></tbody></table>

#### 3.2. 🚀 Consultar

Al ejecutar la búsqueda, el sistema muestra una tabla con los proveedores asociados.

<table><thead><tr><th width="164.2222900390625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td>✏️</td><td>Permite editar la información del proveedor registrada al momento de su creación, requiriendo una justificación del cambio realizado. <a href="partners-proveedores.md#id-3.3.-anadir-proveedor-partner">Campos permitidos</a></td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del proveedor.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor asociado al partner.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner registrado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Indica si el proveedor está activo o inactivo.</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Indica si el proveedor fue validado en el sistema.</td></tr><tr><td><strong><code>Filtro País</code></strong></td><td>País o países en los que el proveedor está disponible.</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Límite máximo permitido para operar con el proveedor.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Límite mínimo permitido para operar con el proveedor.</td></tr><tr><td><strong><code>Detalle</code></strong></td><td>Información adicional del proveedor.</td></tr></tbody></table>

#### 3.3. ➕ Añadir Proveedor [Partner](https://virtualsoft.gitbook.io/untitled/glosario/#partner)

Al seleccionar el botón **`Añadir Proveedor Partner`**, el sistema abre un pop-up para registrar la asociación, indicando los siguientes campos.

<table><thead><tr><th width="162.4444580078125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores</code></strong></td><td>Selecciona el proveedor que se asociará al partner.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Define si la asociación estará activa o inactiva.</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Indica si el proveedor quedará registrado como validado.</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Define el monto máximo permitido para operar con el proveedor.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Define el monto mínimo permitido para operar con el proveedor.</td></tr><tr><td><strong><code>Detalles</code></strong></td><td>Permite ingresar información adicional sobre el proveedor.</td></tr></tbody></table>

Una vez completados los campos requeridos, se debe confirmar la acción para registrar la asociación del proveedor con el _partner_.

***

### 🕒 4. Control de Versiones

| Versión | Fecha      | Autor           | Cambios Realizados |
| ------- | ---------- | --------------- | ------------------ |
| 1.0     | 2026/02/11 | David velasquez | Documento inicial  |
