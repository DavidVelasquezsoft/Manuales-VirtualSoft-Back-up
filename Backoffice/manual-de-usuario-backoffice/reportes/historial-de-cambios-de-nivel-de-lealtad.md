---
description: >-
  Permite visualizar de forma general y trazable los cambios de nivel de lealtad
  (ascensos, descensos o mantenimientos) realizados por los jugadores.
---

# Historial de Cambios de Nivel de Lealtad

{% hint style="warning" %}
**Nota:** Este reporte esta disponible únicamente para operadores con permisos habilitados.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: Backoffice > Reportes > Historial de Cambios de Nivel de Lealtad

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (23).png" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte Historial de Cambios de Nivel de Lealtad</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="historial-de-cambios-de-nivel-de-lealtad.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="historial-de-cambios-de-nivel-de-lealtad.md#id-3.1.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID usuario</code></strong></td><td>Numérico</td><td>Indica el identificador único del usuario a consultar.</td></tr><tr><td><strong><code>Periodo evaluado</code></strong></td><td>Calendario</td><td>Define el periodo de tiempo a evaluar los cambios de nivel de lealtad</td></tr></tbody></table>

### 5.  Resultados de Consulta

Aplica los filtros seleccionados y muestra los registros válidos de cambios de niveles de lealtad.

<table><thead><tr><th width="203.33331298828125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del jugador.</td></tr><tr><td><strong><code>Nivel anterior</code></strong></td><td>Nivel de lealtad en el que se encontraba el usuario antes del cambio.</td></tr><tr><td><strong><code>Nivel actual</code></strong></td><td>Nivel de lealtad en el que quedó el usuario después de actualizar su nivel según la cantidad actual de <a href="https://virtualsoft.gitbook.io/untitled/glosario/#puntos-calificables">puntos calificables</a> acumulados.</td></tr><tr><td><strong><code>Fecha de cambio</code></strong></td><td>Fecha y hora en la que se ejecutó el recálculo.</td></tr><tr><td><strong><code>Puntos al cambio</code></strong></td><td>Cantidad de <a href="https://virtualsoft.gitbook.io/untitled/glosario/#puntos-calificables">puntos calificables</a> que tenía el usuario en el momento de actualizar su nivel de lealtad.</td></tr><tr><td><strong><code>Motivo del cambio</code></strong></td><td>Indica la causa del cambio de nivel de lealtad:</td></tr><tr><td><strong><code>Periodo evaluado</code></strong></td><td>Rango de fechas correspondiente al período de acumulación de puntos calificables.</td></tr><tr><td><strong><code>ID Evento</code></strong></td><td>Identificador único del registro de cambio, utilizado para trazabilidad.</td></tr></tbody></table>

***

### &#x20;6. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="141.88885498046875">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>11/11/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
