---
description: >-
  Permite consultar y dar seguimiento a los usuarios que han solicitado
  autoexcluirse, mostrando información clave sobre fechas, estados y condiciones
  de la autoexclusion.
---

# Autoexclusiones de Usuario

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Autoexclusiones de Usuario

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FFuXkuPWAZr9MKjZvbyjh%2Fimage.png?alt=media&#x26;token=19f72fe4-a143-440e-8ee7-01da38e46c31" alt=""><figcaption><p>Figura #1: Captura de pantalla usuarios autoexcluidos.</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="127.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="autoexclusiones-de-usuario.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="autoexclusiones-de-usuario.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. **Filtros principales**

<table><thead><tr><th width="138">Campo</th><th width="163">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único de la autoexclusión.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador único asociado al usuario.</td></tr><tr><td><p><strong><code>Usuario</code></strong> </p><p><strong><code>(Correo</code></strong> </p><p><strong><code>Electrónico)</code></strong></p></td><td>Campo de texto</td><td>Dirección de correo electrónico del usuario.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Estado actual de la autoexclusión (activa, inactiva, etc.).</td></tr><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td>Clasificación de la <a href="https://virtualsoft.gitbook.io/untitled/glosario/#autoexclusion">autoexclusión</a> por categoría.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Producto o servicio al que aplica la autoexclusión.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País asociado al usuario.</td></tr></tbody></table>

***

#### **4.1 Filtros avanzados**

<table><thead><tr><th width="142">Campo</th><th width="164">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Selecciona un rango de fechas en el que se registró la autoexclusión.</td></tr><tr><td><strong><code>Usuario Creación</code></strong></td><td>Campo de texto</td><td>Usuario que registró la autoexclusión.</td></tr><tr><td><strong><code>Usuario Modificó</code></strong></td><td>Campo de texto</td><td>Usuario que realizó la última modificación en la autoexclusión.</td></tr><tr><td><strong><code>Fecha Modificó</code></strong></td><td>Calendário</td><td>Fecha en la que se realizó la última modificación.</td></tr></tbody></table>

***

### **5. Resultados de consulta**

<table><thead><tr><th width="206">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del registro de autoexclusión.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario asociado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual de la autoexclusión (activa, inactiva, etc.).</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de autoexclusión registrada.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Producto o servicio al que aplica la autoexclusión.</td></tr><tr><td><strong><code>Fecha de inicio de la autoexclusión</code></strong></td><td>Fecha en que comenzó la autoexclusión.</td></tr><tr><td><strong><code>Fecha final de la autoexclusión</code></strong></td><td>Fecha en que finaliza la autoexclusión (si aplica).</td></tr><tr><td><strong><code>Usuario Creación</code></strong></td><td>Nombre o identificador del usuario que registró la autoexclusión.</td></tr><tr><td><strong><code>Usuario Modificó</code></strong></td><td>Nombre o identificador del usuario que realizó la última modificación.</td></tr><tr><td><strong><code>Fecha de Modificación</code></strong></td><td>Fecha en la que se efectuó la última actualización del registro.</td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* No es necesario completar todos los filtros para poder realizar una búsqueda.
* Si no se aplican filtros, el sistema mostrará todas las auto exclusiones registradas.

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="107">Versión</th><th width="126">Fecha</th><th width="151">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>27/08/2025</td><td>Ronald Peláez</td><td>Documento inicial del manual</td></tr></tbody></table>

</details>
