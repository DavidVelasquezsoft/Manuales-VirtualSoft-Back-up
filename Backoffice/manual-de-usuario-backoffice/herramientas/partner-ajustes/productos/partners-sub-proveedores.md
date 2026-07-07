---
description: Permite consultar y gestionar los subproveedores asociados a un partner.
---

# Partners Sub Proveedores

### 1. Acceso al Módulo

**Ruta de Acceso:** Backoffice > Herramientas > Partner ajustes > Partner > Productos >  partners Subproveedores

***

### 2. 🖼️ Visualización

<figure><img src="../../../../.gitbook/assets/image (370).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección partners sub proveedores.</p></figcaption></figure>

***

### 3. 🧑‍💻 Acciones disponibles

<table><thead><tr><th width="148">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtrar</strong></td><td>Permite definir criterios para ubicar subproveedores específicos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros ingresados.</td></tr><tr><td><strong>Consultar</strong></td><td>Muestra los registros que cumplen con los criterios seleccionados.</td></tr><tr><td><strong>Editar</strong></td><td>Permite modificar la configuración del subproveedor seleccionado.</td></tr></tbody></table>

***

#### 3.1. 🔎 Filtros

<table><thead><tr><th width="163.99993896484375">Campo</th><th width="153">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único del subproveedor.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Nombre del proveedor principal.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Texto</td><td>Nombre del subproveedor asociado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por estado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País o países donde opera el subproveedor.</td></tr><tr><td><strong><code>Bonus System</code></strong></td><td>Lista desplegable</td><td>Indica si está habilitado para gestionar bonos.</td></tr></tbody></table>

<details>

<summary>🔎 Filtros avanzados</summary>

<table><thead><tr><th width="160.99993896484375">Campo</th><th width="137">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Verificado</code></strong></td><td>Lista desplegable</td><td>Estado de validación del subproveedor en el sistema.</td></tr><tr><td><strong><code>Filtro País</code></strong></td><td>Lista desplegable</td><td>Filtra por el estado del filtro país que tiene el proveedor</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Numérico</td><td>Límite máximo permitido para operaciones.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Numérico</td><td>Límite mínimo permitido para operaciones.</td></tr><tr><td><strong><code>Tiempo de Procesamiento</code></strong></td><td>Numérico</td><td>Tiempo estimado de ejecución de transacciones por el subproveedor.</td></tr></tbody></table>

</details>

***

#### 3.2.  🚀 Consultar

El sistema presenta los subproveedores en una tabla informativa.

<table><thead><tr><th width="163">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td>✏️</td><td>Abre modal que permite editar toda la información de ese proveedor. <a href="partners-sub-proveedores.md#id-3.3.-editar-subproveedor">Ver campos</a></td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del subproveedor.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor principal.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner asociado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Indica si está activo o inactivo.</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Indica si fue validado en el sistema.</td></tr><tr><td><strong><code>Filtro País</code></strong></td><td>País o países donde opera.</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Límite máximo permitido.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Límite mínimo permitido.</td></tr><tr><td><strong><code>Bonus System</code></strong></td><td>N: No activo / S: Activo.</td></tr><tr><td><strong><code>Test Users</code></strong></td><td>Indica si tiene usuarios de prueba habilitados. </td></tr><tr><td><strong><code>Detalle</code></strong></td><td>Información adicional.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Logotipo o representación gráfica.</td></tr></tbody></table>

<details>

<summary>3.3. ✏️ Editar subproveedor</summary>

Al seleccionar el ícono de edición, el sistema muestra un pop-up con la configuración disponible.

<table><thead><tr><th width="176">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único (no editable).</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor asociado (no editable).</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Permite activar o inactivar el subproveedor.</td></tr><tr><td><strong><code>Verificado</code></strong></td><td>Permite modificar el estado de verificación.</td></tr><tr><td><strong><code>Filtro País</code></strong></td><td>Permite ajustar la disponibilidad por país.</td></tr><tr><td><strong><code>Máximo</code></strong></td><td>Define el valor máximo permitido.</td></tr><tr><td><strong><code>Mínimo</code></strong></td><td>Define el valor mínimo permitido.</td></tr><tr><td><strong><code>Detalle</code></strong></td><td>Permite ingresar información adicional.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Permite adjuntar o actualizar una imagen.</td></tr><tr><td><strong><code>Bonus System</code></strong></td><td>Habilita o deshabilita la visibilidad en torneos y bonos.</td></tr><tr><td><strong><code>Usuarios de Prueba</code></strong></td><td><p>Define si el subproveedor será exclusivo para usuarios de prueba.</p><ul><li>Si está marcada, indica que el subproveedor es de prueba.</li><li>Si no está marcada, el subproveedor será visible para todos los usuarios en la plataforma.</li></ul></td></tr><tr><td><strong><code>Explicación</code></strong></td><td>Permite registrar una justificación del cambio.</td></tr></tbody></table>

Para aplicar los cambios, selecciona **`Guardar`**.\
Para cerrar el formulario sin modificar la información, selecciona **`Cancelar`**.

</details>

***

### 4. ✅ Validaciones y reglas del negocio

* Si el subproveedor está marcado como **de prueba** y el usuario no tiene habilitado ese permiso, el sistema mostrará un mensaje indicando que los juegos no se encuentran disponibles.
* Después de realizar los cambios, si un proveedor ha sido marcado como  de "**prueba"** y el usuario no tiene habilitada la opción de **"usuario de prueba"**, al intentar acceder a los juegos de ese proveedor, verá un mensaje indicando que los juegos no están disponibles.

***

### 5. 🕓 Control de Versiones

| Versión | Fecha      | Autor           | Cambios Realizados |
| ------- | ---------- | --------------- | ------------------ |
| 1.0     | 2026/02/11 | David velasquez | Documento inicial  |
