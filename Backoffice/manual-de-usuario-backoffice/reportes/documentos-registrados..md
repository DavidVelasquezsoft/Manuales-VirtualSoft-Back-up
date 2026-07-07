---
description: >-
  Configura los documentos legales por defecto de todos los usuarios que en la
  plataforma
---

# Documentos registrados.

#### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Documentos registrados

***

#### 2. Visualización

<figure><img src="../../.gitbook/assets/image (598).png" alt=""><figcaption><p>Captura de pantalla #1: Documentos registrados.</p></figcaption></figure>

***

### 3. **Acciones disponibles**

<table><thead><tr><th width="163">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtrar documentos</strong></td><td>Permite aplicar filtros para realizar búsqueda de los documentos legales establecidos.</td></tr><tr><td><strong>Visualizar tabla de resultados</strong></td><td>Presenta la información del historial de saldos según los filtros aplicados.</td></tr><tr><td><strong>Exportar los resultados</strong></td><td>Exporta en formato Excel la tabla de resultados según los filtros seleccionados.</td></tr><tr><td><strong>Añadir documentos</strong></td><td>Establece nuevos documentos legales para los usuarios en la plataforma.</td></tr></tbody></table>

#### 3.1 Añadir documento

Desde el botón `Añadir documento` despliega un pop-up con el formulario para establecer un nuevo documento legal para todos los usuarios de la plataforma.

<table><thead><tr><th width="124">Campo</th><th width="144">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre del documento legal.</td></tr><tr><td><strong><code>Ruta</code></strong></td><td>Texto</td><td>URL del documento legal.</td></tr><tr><td><strong><code>Versión</code></strong></td><td>Texto</td><td>Número de versión semántica del documento</td></tr><tr><td><strong><code>Encriptación</code></strong></td><td>Texto</td><td>Método de encriptación aplicado al documento.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Segmento al que pertenece el documento.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Estado del documento <em>(Activo: Aplicará para todos los usuarios, Inactivo: No aplicará para los usuarios</em>).</td></tr><tr><td><strong><code>Perfil</code></strong></td><td>Lista desplegable</td><td>Entorno en el que aplicará el documento legal <em>(punto de venta o plataforma de usuarios online).</em></td></tr><tr><td><strong><code>Tipo método</code></strong></td><td>Lista desplegable</td><td>Establece si el documento aplicará para servicios propios o para servicios con proveedores.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable </td><td>País para el que aplica el documento.</td></tr></tbody></table>

#### **3.2 🔎Filtros principales**

<table><thead><tr><th width="93">Filtro</th><th width="163">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Nombre</code></td><td>Texto</td><td>Nombre del documento.</td></tr><tr><td><code>Tipo</code></td><td>Lista desplegable</td><td>Segmento al que pertenece el documento.</td></tr><tr><td><code>Estado</code></td><td>Lista desplegable</td><td>Estado en el que se encuentra el documento.</td></tr><tr><td><code>Ruta</code></td><td>Texto</td><td>URL del archivo PDF asociado al documento.</td></tr></tbody></table>

#### **3.3📊 Tabla de Resultados**

Los resultados de la consulta se presentan en una tabla con las siguientes columnas:

<table><thead><tr><th width="122">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td>Acciones</td><td></td></tr><tr><td>ID</td><td>Id del documento.</td></tr><tr><td>Nombre</td><td>Nombre del documento legal.</td></tr><tr><td>Ruta</td><td>URL del documento legal.</td></tr><tr><td>Encriptación</td><td>Método de encriptación aplicado al documento.</td></tr><tr><td>Id externo</td><td>Identificador que se utilizará para este documento de manera externa <em>(proveedores, clientes, etc.…)</em></td></tr><tr><td>Tipo</td><td>Segmento al que pertenece el documento.</td></tr><tr><td>Perfil</td><td>Entorno en el que aplicará el documento legal <em>(punto de venta o plataforma de usuarios online).</em></td></tr><tr><td>Estado</td><td>Estado del documento <em>(Activo: Aplicará para todos los usuarios, Inactivo: No aplicará para los usuarios</em>).</td></tr><tr><td>País</td><td>País para el que aplica el documento.</td></tr></tbody></table>



***

**4. Validaciones y Reglas de Negocio**

* No es obligatorio completar todos los filtros para realizar una búsqueda.
* La información mostrada dependerá de los filtros seleccionados en la consulta.
* Los documentos que se agreguen deben ser legalmente establecidos para todos los usuarios.

***

**5. Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 09/10/2025 | Ronald Peláez | Documento inicial  |
