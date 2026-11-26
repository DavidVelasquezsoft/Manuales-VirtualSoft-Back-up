---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
---

# Elbet

<mark style="color:$info;">El proveedor Elbet cuenta con un BackOffice propio, desde el cual se gestiona su Bonus System. Por lo tanto, la creación y administración de bonos debe realizarse directamente en la plataforma del proveedor.</mark>

La integración permite posteriormente la **trazabilidad**, **reportería por jugador** y el uso de estos beneficios dentro de campañas CRM internas.

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice Elbet → Configuration → Promo Management

***

### 2. Visualización

En esta sección se permite consultar jugadores activos, validar su actividad y asignar beneficios promocionales como giros gratuitos o tickets de apuesta.

<figure><img src="https://2840730235-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FpVk1Kqoe0aInaa5Ofl6i%2Fuploads%2FbEIqHGatdQswVcF7YTuy%2Fimage.png?alt=media&#x26;token=5e6ab14b-2300-4c48-960a-b6380546bcaf" alt=""><figcaption><p>Figura #1: Filtros de búsqueda Promo Management.</p></figcaption></figure>

***

### 3. Acciones del Usuario

<table><thead><tr><th width="250">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="elbet.md#id-4.-busqueda-de-jugadores-para-asignacion-de-bonos"><strong>Búsqueda de jugadores</strong></a></td><td>Permite ubicar los jugadores dentro del módulo <strong>Promo Management</strong> para asignarles un bono.</td></tr><tr><td><a href="elbet.md#id-5.-creacion-del-bonus-system-asignacion-de-free-tickets"><strong>Creación del Bonus System</strong></a></td><td>Permite asignar <strong>Free Tickets</strong> al jugador identificado y configurar los parámetros del bono.</td></tr><tr><td><a href="elbet.md#id-6.-uso-del-bono-en-el-juego"><strong>Uso del bono en el juego</strong></a></td><td>Describe cómo el jugador visualiza y utiliza las apuestas asignadas dentro de un juego del proveedor.</td></tr></tbody></table>

***

### 4. Búsqueda de jugadores para asignación de bonos

Para asignar un bono es necesario ubicar primero los jugadores dentro del módulo **Promo Management**.

**Pasos para buscar jugadores**

1. Ingresar al BackOffice del proveedor.
2. Acceder al módulo **Promo Management**.
3. Completar los filtros según la campaña o necesidad operativa.
4. Ejecutar la búsqueda para visualizar los jugadores disponibles.

<table><thead><tr><th width="180">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Company</code></strong></td><td>Lista desplegable</td><td>Seleccionar <strong>VirtualSoft STAGE (CIWS) - 10187</strong>.</td></tr><tr><td><strong><code>Game</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el juego al cual se aplicará el bono.</td></tr><tr><td><strong><code>Order By</code></strong></td><td>Lista desplegable</td><td>Se recomienda seleccionar <strong>Sessions</strong> para identificar usuarios con sesión activa.</td></tr><tr><td><strong><code>From Date</code></strong></td><td>Selector de fecha</td><td>Define la fecha inicial del rango de búsqueda.</td></tr><tr><td><strong><code>To Date</code></strong></td><td>Selector de fecha</td><td>Define la fecha final del rango de búsqueda.</td></tr><tr><td><strong><code>Min Ticket</code></strong></td><td>Campo numérico</td><td>Filtra jugadores según el número mínimo de apuestas realizadas.</td></tr><tr><td><strong><code>Top</code></strong></td><td>Campo numérico</td><td>Define la cantidad máxima de jugadores a mostrar en la búsqueda.</td></tr><tr><td><strong><code>Player ID</code></strong></td><td>Campo de texto</td><td>Permite buscar un jugador específico mediante su identificador.</td></tr><tr><td><strong><code>Games</code></strong></td><td>Lista desplegable</td><td>Permite filtrar resultados por juegos específicos del proveedor.</td></tr></tbody></table>

***

### 5. Creación del Bonus System (Asignación de Free Tickets)

Una vez identificado el jugador, se podrá asignar el beneficio promocional.

**Pasos para crear el bono**

1. Ubicar el jugador en la lista de resultados.
2. Ingresar a la columna **Settings**.
3. Seleccionar la opción **Edit User**.
4. Agregar los **Free Tickets**.
5. Configurar los parámetros del bono.
6. Guardar la configuración.

<table><thead><tr><th width="180">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Bet Count</code></strong></td><td>Numérico</td><td>Define la cantidad total de apuestas que tendrá el bono.</td></tr><tr><td><strong><code>Bet Amount</code></strong></td><td>Numérico</td><td>Define el valor individual de cada apuesta incluida en el bono.</td></tr><tr><td><strong><code>Min Cashout Multiplier</code></strong></td><td>Numérico</td><td>Define el multiplicador mínimo requerido para generar ganancias. El jugador solo obtendrá premio si supera este valor dentro del juego.</td></tr></tbody></table>

***

### 6. Uso del bono en el juego

Una vez asignado el bono:

**Pasos para utilizarlo**

1. El jugador debe ingresar a un juego del proveedor Elbet.
2. En la parte superior del juego, junto al saldo, aparecerá un botón indicando la cantidad de apuestas disponibles.
3. El botón mostrará el formato:

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>06/02/2026</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>26/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
