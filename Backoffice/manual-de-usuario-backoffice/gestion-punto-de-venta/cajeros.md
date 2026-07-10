---
description: >-
  Esta sección permite visualizar y gestionar la información de los cajeros
  registrados en el sistema a través de distintos filtros de búsqueda.
---

# Cajeros

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, no será visible en el sistema.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Gestión Punto de Venta > Cajeros

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (353).png" alt=""><figcaption><p>Figura#1: Captura de pantalla seccion cajeros.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="cajeros.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información de los cajeros.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="cajeros.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los cajeros en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="149.77783203125">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Indica el identificador único del cajero.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre del cajero.</td></tr><tr><td><strong><code>Login</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre de usuario con el que el cajero accede al sistema.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país donde está registrado el cajero.</td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Lista desplegable</td><td>Selecciona el punto de venta asociado al cajero.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los cajeros que cumplen con los filtros aplicados.

<table><thead><tr><th width="178.6666259765625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td>🔎</td><td><p>Permite acceder al detalle del punto de venta para consultar y administrar su información mediante las siguientes secciones:</p><ul><li><a href="punto-de-venta/informacion.md">Información</a></li><li><a href="punto-de-venta/reportes/">Reportes</a></li><li><a href="punto-de-venta/configuracion.md">Configuración</a></li></ul></td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del cajero.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Nombre único del usuario en el sistema.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre del cajero.</td></tr><tr><td><strong><code>Login</code></strong></td><td>Nombre de usuario con el que el cajero accede al sistema.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Tipo de moneda con la que opera el cajero.</td></tr><tr><td><strong><code>ID Punto de Venta</code></strong></td><td>Identificador del punto de venta al que está asignado el cajero.</td></tr><tr><td><strong><code>Nombre Punto de Venta</code></strong></td><td>Nombre del punto de venta asociado al cajero.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, no será visible en el sistema.
* No es obligatorio completar todos los filtros para realizar una búsqueda.
* Los resultados mostrados dependen de los filtros aplicados en la consulta.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>10/07/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
