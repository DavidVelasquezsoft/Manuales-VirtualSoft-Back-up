---
description: >-
  Este reporte permite visualizar información detallada sobre los programas y
  modalidades de juego disponibles dentro de la plataforma de casino durante un
  periodo determinado.
---

# Reporte específico de la plataforma (3.7.8)

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes de regulación > Reporte específico de la plataforma (3.7.8)

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (205).png" alt=""><figcaption><p>figura#1: Captura de pantalla reporte específico de la plataforma.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-especifico-de-la-plataforma-3.7.8.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Define el criterio de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-especifico-de-la-plataforma-3.7.8.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según el filtro definido y muestra la información en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el periodo en el que se desea consultar la información.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con la información de los programas y modalidades de juego según el periodo seleccionado.

<table><thead><tr><th width="248.5">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Día en que se registró la información en la plataforma.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Denominación del programa o modalidad de juego.</td></tr><tr><td><strong><code>Versión</code></strong></td><td>Número de la versión actual del juego o programa registrado en la plataforma.</td></tr><tr><td><strong><code>Programa de juego / Modalidad de juego</code></strong></td><td>Clasificación del juego dentro del sistema <em>(ejemplo: Ruleta, Póker, Slots, Blackjack, etc.)</em>.</td></tr><tr><td><strong><code>Código de registro de MINCETUR</code></strong></td><td><p>Identificación oficial del juego ante el Ministerio de Comercio Exterior y Turismo (MINCETUR).</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este código corresponde al registro del juego ante la entidad reguladora, en cumplimiento de la normativa vigente.</p></div></td></tr><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Día en que el programa de juego se activó en la plataforma.</td></tr><tr><td><strong><code>Fecha de fin</code></strong></td><td>Día en que el programa de juego dejó de estar disponible, si aplica.</td></tr><tr><td><strong><code>Proveedor de servicios</code></strong></td><td>Empresa o desarrollador responsable de la implementación del juego en la plataforma.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* Es obligatorio seleccionar un periodo de fechas para ejecutar la consulta.
* El reporte muestra los programas y modalidades de juego disponibles en la plataforma de casino durante el periodo consultado.
* Cada juego o programa cuenta con su código de registro oficial ante MINCETUR, en cumplimiento de la normativa vigente.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
