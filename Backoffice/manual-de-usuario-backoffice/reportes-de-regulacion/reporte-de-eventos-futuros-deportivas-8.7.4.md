---
description: >-
  Este reporte permite visualizar las apuestas realizadas sobre eventos
  deportivos futuros dentro de la plataforma.
---

# Reporte de eventos futuros (Deportivas) (8.7.4)

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes de regulación > Reporte de eventos futuros (Deportivas) (8.7.4)

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (277).png" alt=""><figcaption><p>Figura#1: Captura de pantalla de la sección reporte de eventos futuros.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-eventos-futuros-deportivas-8.7.4.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-eventos-futuros-deportivas-8.7.4.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las apuestas sobre eventos futuros en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el periodo de consulta indicando una fecha de inicio y una fecha de fin.</td></tr><tr><td><strong><code>ID del Jugador</code></strong></td><td>Numérico</td><td>Indica el código único asignado a cada jugador.</td></tr><tr><td><strong><code>Tipo de Documento</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de documento de identidad del jugador.</td></tr><tr><td><strong><code>Número de Documento</code></strong></td><td>Campo de texto</td><td>Corresponde al número de identificación del jugador.</td></tr><tr><td><strong><code>Nombre del Jugador</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre completo del jugador.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con la información de las apuestas sobre eventos futuros según los filtros aplicados.

<table><thead><tr><th width="211.4630126953125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td><p>Fecha en la que se registró del evento futuro.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Se genera uno o varios registros siempre que existan apuestas sobre eventos futuros dentro del periodo solicitado.</p></div></td></tr><tr><td><strong><code>Identificador único de la transacción</code></strong></td><td>Código único asignado a cada apuesta.</td></tr><tr><td><strong><code>Identificador único del jugador</code></strong></td><td>Código único del jugador que realizó la apuesta.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Nombre completo del jugador que realizó la apuesta.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Tipo de documento de identidad del jugador <em>(DNI, pasaporte, cédula, etc.)</em>.</td></tr><tr><td><strong><code>Numero de documento</code></strong></td><td>Número de identificación del jugador.</td></tr><tr><td><strong><code>Fecha de ticket</code></strong></td><td>Fecha y hora en la que se generó la apuesta.</td></tr><tr><td><strong><code>Apuesta abierta</code></strong></td><td>Monto total apostado, incluyendo cualquier bonificación, comisión o derecho de inscripción, correspondiente a apuestas en estado abierto y aún no resueltas.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* Es obligatorio seleccionar un periodo de fechas para ejecutar la consulta.
* El reporte muestra únicamente las apuestas realizadas sobre eventos deportivos futuros aún no resueltos.
* Se genera uno o varios registros siempre que existan apuestas sobre eventos futuros dentro del periodo solicitado.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
