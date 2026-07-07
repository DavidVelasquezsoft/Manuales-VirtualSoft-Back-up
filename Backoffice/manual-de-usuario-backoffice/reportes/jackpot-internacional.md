---
description: >-
  Presenta información en tiempo real de los jackpots internacionales, con datos
  generales por jackpot internacional y desgloses de aportes por partner y país,
  además de los detalles de ganadores.
---

# Jackpot internacional

{% hint style="warning" %}
**Nota:** Este reporte esta disponible únicamente para operadores con permisos habilitados.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: Backoffice > Reportes > Jackpot internacional

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (625).png" alt=""><figcaption><p>Figura #1: captura de pantalla reporte Jackpot internacional</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="jackpot-internacional.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información de manera resumida o detallada para obtener resultados mas precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="jackpot-internacional.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos ya sea en vista resumida o detallada.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

#### 3.1. Filtros

<table><thead><tr><th width="152.8333740234375">Campo</th><th width="123.16668701171875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID padre</code></strong></td><td>Numérico</td><td>Identificador único del jackpot principal, que permite consultar todas las series (<em>jackpots hijos</em>) generadas a partir de sus reinicios.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Indica el nombre asignado al jackpot.</td></tr><tr><td><strong><code>Rango de fechas</code></strong></td><td>Fecha Inicio /Fin</td><td>Filtra por el rango de fechas correspondiente al inicio del jackpot.</td></tr><tr><td><strong><code>Vista</code></strong></td><td>Selector</td><td>Permite elegir la vista en la cual se visualizará el reporte (<em>Detallada o Resumida).</em></td></tr></tbody></table>

<details>

<summary>3.1.1. 🔎 Filtros Vista detallada</summary>

Al seleccionar la vista **Detallada**, se habilitan los siguientes filtros adicionales para una consulta mas detallada.

<table><thead><tr><th width="132.8333740234375">Campo</th><th width="123.16668701171875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Jackpot</code></strong></td><td>Numérico</td><td>Indica el Identificador único del jackpot.</td></tr><tr><td><strong><code>Fecha de caída</code></strong></td><td>Fecha Inicio / Fin</td><td>Especifica la fecha o el periodo de tiempo en el que ocurrió la caída del jackpot.</td></tr><tr><td><strong><code>ID Jugador</code></strong></td><td>Numérico</td><td>Filtra por el identificador único del usuario ganador del jackpot.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Filtra por el partner en el que se creo el jackpot.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por el estado del jackpot: (<em>Ganados, Inactivos o Activos.</em>)</td></tr></tbody></table>

</details>

#### 3.2.  Consultar

Aplica los filtros seleccionados y presenta los resultados de los [jackpots internacionales](https://virtualsoft.gitbook.io/untitled/glosario/#jackpot-internacional) validos.

{% tabs %}
{% tab title="📜 Reporte detallado" %}
Cada registro en este reporte pertenece a **una operación** (_partner y país_) del jackpot internacional.

<table><thead><tr><th width="186.5">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#jackpot-padre"><strong><code>Padre Jackpot</code></strong></a></td><td>Muestra el identificador único del Jackpot Principal al que pertenece la serie (<em>Si aplica</em>).</td></tr><tr><td><strong><code>ID Jackpot</code></strong></td><td>Identificador único del jackpot internacional dentro del sistema.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre asignado al jackpot internacional.</td></tr><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Fecha en la que comenzó la acumulación o campaña del jackpot internacional.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner en el que se creo el jackpot.</td></tr><tr><td><strong><code>País</code></strong></td><td>Muestra el país al que pertenece el jackpot.</td></tr><tr><td><strong><code>Valor acumulado local</code></strong> </td><td>Muestra el monto acumulado del jackpot generado localmente, expresado en la moneda oficial del país.</td></tr><tr><td><strong><code>Valor acumulado base</code></strong></td><td>Monto total acumulado que aporto la operación al pozo del jackpot internacional, expresado en la moneda base definida.</td></tr><tr><td><strong><code>Cantidad de participantes</code></strong> </td><td>Número total de jugadores que han generado al menos una apuesta valida en el jackpot dentro de la operación (<em>Partner y país</em>).</td></tr><tr><td><strong><code>Fecha de caída</code></strong></td><td>Fecha en la que el jackpot internacional finalizó y se asignó un ganador.</td></tr><tr><td><strong><code>ID Jugador (ganador)</code></strong></td><td>Identificador único del jugador que ganó el jackpot internacional.</td></tr><tr><td><strong><code>ID Apuesta</code></strong> </td><td>Identificador único de la apuesta específica con la que ganó el usuario.</td></tr><tr><td><strong><code>Moneda base</code></strong></td><td>Moneda estándar utilizada para unificar los valores del jackpot internacional (<em>Ej: USD o EUR</em>).</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Muestra el estado actual del jackpot (<em>Activo, Inactivo o Ganado</em>).</td></tr></tbody></table>
{% endtab %}

{% tab title="📄 Reporte resumido" %}
Cada registro en este reporte pertenece a **un jackpot internacional**.

<table><thead><tr><th width="208.83331298828125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#jackpot-padre"><strong><code>Padre Jackpot</code></strong></a></td><td>Identificador único del jackpot principal que centraliza el pozo acumulado y del cual se derivan los jackpots asociados por operación (<em>plataforma y país</em>).</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre asignado al jackpot padre dentro del sistema.</td></tr><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Fecha en la que comenzó la acumulación o campaña del jackpot internacional.</td></tr><tr><td><strong><code>Valor acumulado base</code></strong></td><td>Monto total acumulado en el jackpot internacional definido en la moneda base.</td></tr><tr><td><strong><code>Cantidad de participantes</code></strong></td><td>Número total de jugadores únicos que participan o han participado en el jackpot durante su periodo de vigencia.</td></tr><tr><td><strong><code>Moneda base</code></strong></td><td>Moneda base estándar utilizada para unificar los valores del jackpot internacional (<em>Ej: USD o EUR</em>).</td></tr><tr><td><strong><code>Cantidad de caídas</code></strong></td><td>Número total de veces que el jackpot ha caído (<em>Finalizado y entregado</em>) durante su ciclo de operación.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 4. Validaciones y Reglas de Negocio

* El reporte solo muestra información de los partners habilitados en tu perfil.
* Si algunas columnas se muestran vacias es debido a este reporte no presenta esa información

***

### 5. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="107.88885498046875">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/12/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
