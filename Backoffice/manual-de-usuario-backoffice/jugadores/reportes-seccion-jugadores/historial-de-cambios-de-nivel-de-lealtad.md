---
description: >-
  Permite visualizar los cambios de nivel de lealtad (ascensos, descensos,
  mantenimientos y asignación inicial) aplicados al usuario previamente
  seleccionado de manera trazable.
---

# Historial de Cambios de Nivel de Lealtad

{% hint style="warning" %}
**Nota:** Este reporte esta disponible únicamente para operadores con permisos habilitados.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: Backoffice > Jugadores > Reportes > Historial de Cambios de Nivel de Lealtad

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (24).png" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte Historial de Cambios de Nivel de Lealtad</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="170.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtro</strong></td><td>Permite filtrar la información para obtener resultados más precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="historial-de-cambios-de-nivel-de-lealtad.md#id-3.1.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="170.11102294921875">Campo</th><th width="157.33331298828125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de rango de cambio</code></strong></td><td>Fecha Inicio / Fin</td><td>Filtra según la fecha en la que se realizó el depósito.</td></tr></tbody></table>

***

### 5. Resultados de Consulta

Aplica los filtros seleccionados y muestra los registros válidos de cambios de niveles de lealtad.

<table><thead><tr><th width="203.33331298828125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del jugador.</td></tr><tr><td><strong><code>Nivel anterior</code></strong></td><td>Nivel de lealtad en el que se encontraba el usuario antes del cambio.</td></tr><tr><td><strong><code>Nivel actual</code></strong></td><td>Nivel de lealtad en el que quedó el usuario después de actualizar su nivel según la cantidad actual de <a href="https://virtualsoft.gitbook.io/untitled/glosario/#puntos-calificables">puntos calificables</a> acumulados.</td></tr><tr><td><strong><code>Fecha de cambio</code></strong></td><td>Fecha y hora en la que se ejecutó el recálculo.</td></tr><tr><td><strong><code>Puntos al cambio</code></strong></td><td>Cantidad de <a href="https://virtualsoft.gitbook.io/untitled/glosario/#puntos-calificables">puntos calificables</a> que tenía el usuario en el momento de actualizar su nivel de lealtad.</td></tr><tr><td><strong><code>Motivo del cambio</code></strong></td><td>Indica la causa del cambio de nivel de lealtad:</td></tr><tr><td><strong><code>Periodo evaluado</code></strong></td><td>Rango de fechas correspondiente al período de acumulación de puntos calificables.</td></tr><tr><td><strong><code>ID Evento</code></strong></td><td>Identificador único del registro de cambio, utilizado para trazabilidad.</td></tr></tbody></table>

***

### 6. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="105.88885498046875">Versión</th><th width="147">Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2025-11-11</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
