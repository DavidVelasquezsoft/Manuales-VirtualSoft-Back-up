---
description: >-
  Este reporte permite consultar el listado de usuarios afiliados registrados en
  la plataforma, mostrando información sobre su estado, su actividad y el
  afiliador y punto de venta asociados.
---

# Usuarios afiliados

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Reporte de Afiliados

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (151).png" alt=""><figcaption><p>Figura#1: Captura de pantalla reporte usuarios Afiliados</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="usuarios-afiliados.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="usuarios-afiliados.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los usuarios afiliados en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el periodo de consulta para visualizar los usuarios afiliados creados dentro del rango indicado.</td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Lista desplegable</td><td>Filtra la información por un punto de venta específico asociado a los usuarios afiliados.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con el listado de usuarios afiliados que cumplen con los criterios seleccionados.

<table><thead><tr><th width="218.5">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha en la que el usuario afiliado fue registrado en el sistema.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único asignado al usuario afiliado.</td></tr><tr><td><strong><code>Nombre Usuario</code></strong></td><td>Nombre del usuario afiliado registrado en la plataforma.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del usuario afiliado <em>(activo o inactivo)</em>.</td></tr><tr><td><strong><code>Fecha del Último Logueo</code></strong></td><td>Fecha en la que el usuario afiliado accedió por última vez a la plataforma.</td></tr><tr><td><strong><code>Nombre Afiliador</code></strong></td><td>Nombre del afiliador asociado al usuario.</td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Nombre del punto de venta asociado al usuario afiliado.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* El reporte muestra los usuarios afiliados creados dentro del periodo seleccionado.
* Cada registro detalla el estado del usuario afiliado, su última actividad y el afiliador y punto de venta asociados.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>30/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
