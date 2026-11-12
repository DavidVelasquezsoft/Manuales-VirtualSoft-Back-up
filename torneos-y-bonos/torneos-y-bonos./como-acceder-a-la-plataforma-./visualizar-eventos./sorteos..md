---
description: >-
  En esta sección podrás visualizar información general sobre todos los sorteos
  creados.
---

# Sorteos.

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Torneos y bonos > Ver sorteos

***

### 2. Visualización general

<figure><img src="../../../.gitbook/assets/image (7).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección visualizar sorteos.</p></figcaption></figure>

En la parte superior derecha se encuentra el botón **"Crear sorteo"**, el cual dirige a la sección destinada para la creación de sorteos.\
Para más información, consulte el siguiente apartado:

{% content-ref url="../crear-eventos./crear-sorteo/" %}
[crear-sorteo](../crear-eventos./crear-sorteo/)
{% endcontent-ref %}

***

### 3. Acciones del usuario

<table><thead><tr><th width="195.5555419921875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="sorteos..md#id-3.1.-filtros"><strong>Filtrar</strong></a></td><td>Utiliza los filtros disponibles para buscar sorteos ya creados.</td></tr><tr><td><strong>Visualizar sorteos activos</strong></td><td>Permite visualizar en un KPI la cantidad de sorteos activos del partner país previamente seleccionado.</td></tr><tr><td><a href="sorteos..md#id-3.2.-lista-de-sorteos"><strong>Lista de sorteos</strong></a></td><td>Aquí se muestran los sorteos creados en una tabla que permite visualizarlos y administrarlos fácilmente.</td></tr><tr><td><strong>Gestionar sorteos creados</strong></td><td>Para cada sorteo, se encuentran disponibles distintas acciones que permiten su gestión.</td></tr><tr><td><strong>Crear sorteo</strong></td><td>Botón que redirecciona al formulario de creación de un sorteo.</td></tr></tbody></table>

#### 3.1. Filtros

Los filtros permiten obtener información más detallada de los sorteos, adaptándose a las necesidades de búsqueda.

<table><thead><tr><th width="120.666748046875">Campo</th><th width="144.7777099609375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Sorteo</code></strong></td><td>Numérico</td><td>Permite buscar información filtrando únicamente por el ID del sorteo.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Busca por rango de fechas en las que el sorteo fue creado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra sorteos según su estado (<strong>activo</strong> o <strong>inactivo</strong>).</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra los sorteos según el país para el cual fueron creados.</td></tr></tbody></table>

Una vez completados los filtros, utiliza el botón **"Buscar"**.\
Para limpiar los criterios aplicados, utilizar el botón **"Limpiar"**.

#### 3.2. Lista de sorteos

En esta sección se muestran todos los sorteos creados. La información se despliega en una tabla interactiva que permite consultar y gestionar detalles de cada sorteo.

<table><thead><tr><th width="188.333251953125">Columna</th><th width="559.666748046875">Descripción</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td>Por cada sorteo se permiten realizar las siguientes acciones:</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="133.1112060546875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Editar (</strong><i class="fa-pencil">:pencil:</i><strong>)</strong></td><td>Abre el formulario del sorteo con toda su configuración visible, permitiendo modificar únicamente los campos <strong>“Nombre”</strong> y <strong>“Descripción”</strong>.</td></tr><tr><td><a href="sorteos..md#ver-detalle-de-torneo-lupa"><strong>Lupa (🔍)</strong></a></td><td>Muestra información general del sorteo, incluyendo participantes y progreso. <a href="sorteos..md#ver-detalle-de-sorteo-lupa" class="button secondary">Ver detalles</a></td></tr><tr><td> <strong>Inactivar sorteo (⏻)</strong></td><td>Abre un pop-up para confirmar la inactivación del sorteo.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="206.8887939453125">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Sorteo</code></strong></td><td>Identificador único asignado al sorteo.</td></tr><tr><td><strong><code>Nombre Sorteo</code></strong></td><td>Nombre definido para el sorteo.</td></tr><tr><td><strong><code>Descripción Sorteo</code></strong></td><td>Breve descripción con detalles del sorteo, que esta la visualizaran los usuarios en la plataforma en usuarios online.</td></tr><tr><td><strong><code>Fecha de Inicio</code></strong></td><td>Fecha en la que comenzó el sorteo.</td></tr><tr><td><strong><code>Fecha de Fin</code></strong></td><td>Fecha en la que finalizó el sorteo.</td></tr></tbody></table>

<details>

<summary>🔽 Ver detalle de sorteo (<em>🔎 Lupa</em>)</summary>

Permite visualizar la información completa de un sorteo, organizada en las siguientes secciones:

#### 📊 Kpis generales

Permiten visualizar un resumen general del estado y desempeño del sorteo, a través de los siguientes indicadores:

<table><thead><tr><th width="192.00006103515625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Participantes</code></strong></td><td>Número total de usuarios que participan en el sorteo.</td></tr><tr><td><strong><code>Progreso del sorteo</code></strong></td><td>Porcentaje  de avance del sorteo según su duración o condiciones configuradas.</td></tr></tbody></table>

#### 🔎 Filtros

<table><thead><tr><th width="132.99993896484375">Campo</th><th width="119.00006103515625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario Id</code></strong></td><td>Numérico</td><td>Permite filtrar la información asociada a un usuario específico mediante su identificador único.</td></tr><tr><td><strong><code>Código cupón</code></strong></td><td>Numérico</td><td>Filtra por el código de cupón del usuario dentro del sorteo.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Permite filtrar los resultados por el nombre del usuario.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por el estado de los jugadores (<em>ganador / participante</em>)</td></tr></tbody></table>

#### 🏅 Ranking Usuarios&#x20;

Permite visualizar todos los jugadores participantes y consultar los detalles de su participación en el sorteo, a través de los siguientes campos:

<table><thead><tr><th width="175.00006103515625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario</code></strong></td><td>Identificador único del usuario en la plataforma.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre del usuario participante en el sorteo.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado del jugador en el sorteo (<em>ganador / participante</em>)</td></tr><tr><td><strong><code>Codigo cupon</code></strong></td><td>Código del cupón del usuario con el que participo en el sorteo.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Monto total de premios obtenidos por el usuario.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Permite visualizar el detalle de la participación del usuario, mostrando el valor apostado y la información de todas las apuestas válidas realizadas.</td></tr></tbody></table>

</details>

***

### 4. Validaciones y reglas del negocio:

* Los sorteos activos también se muestran en los **banners de la plataforma** con el número de inscritos y un cronómetro con el tiempo restante.
* La información de participantes y progreso se actualiza automáticamente cada **120 segundos**.

***

### 5. Control de Versiones

<details>

<summary> 🕒Historial de versiones.</summary>

<table><thead><tr><th width="107.88897705078125">Versión</th><th width="132.111083984375">Fecha</th><th width="170.333251953125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2025-08-25</td><td>Ronald Pelaez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>2025-09-09</td><td>Ronald Peláez</td><td>Nuevas columnas de cantidad de usuarios en el sorteo.</td></tr><tr><td>2.0</td><td>2026-02-13</td><td>David Velasquez</td><td>Refinamiento del manual e incorporación de nuevo campo</td></tr></tbody></table>

</details>
