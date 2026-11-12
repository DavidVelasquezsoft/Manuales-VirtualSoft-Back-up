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

# Sorteo punto de venta.

El módulo **Sorteo Punto de Venta** permite crear sorteos dirigidos a los usuarios que realizan apuestas desde puntos de venta autorizados.&#x20;

***

### 1. Acceso al Módulo

**Ruta de Acceso:** BackOffice > Torneos y Bonos > Eventos > Crear Evento > **Sorteo Punto Venta**

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (304).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Creación de Sorteos.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Crear Sorteo</strong></td><td>Utiliza el formulario para crear un sorteo para los puntos de venta.</td></tr></tbody></table>

***

### 4. Formulario para creación de sorteos punto de venta.

<table><thead><tr><th width="151">Campo</th><th width="129">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha inicial</code></strong></td><td>Fecha</td><td>Establece la fecha desde la cual el sorteo estará disponible para participar.</td></tr><tr><td><strong><code>Fecha final</code></strong></td><td>Fecha</td><td>Establece la fecha hasta la cual el sorteo permanecerá activo.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Registra el nombre con el que será identificado el sorteo.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Numérico</td><td>Define la posición en la que se visualizará el sorteo frente a los demás eventos disponibles.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Registra una descripción general del sorteo.</td></tr><tr><td><strong><code>Tipo de Producto</code></strong></td><td>Lista desplegable</td><td>Selecciona la vertical sobre la cual se configurará el sorteo. Para este tipo de evento únicamente se encuentra disponible <strong>Sportsbook</strong>.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="128">Campo</th><th width="118">Tipo de control</th><th></th></tr></thead><tbody><tr><td><strong><code>Tipo de Ranking</code></strong></td><td>Lista desplegable</td><td>Define el criterio utilizado para calcular el ranking del sorteo.</td></tr><tr><td><strong><code>Todas las condiciones son obligatorias</code></strong></td><td>Interruptor</td><td>Indica que todas las condiciones configuradas deben cumplirse para participar en el sorteo.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

* #### **`Segmento Sportsbook`**

El segmento seleccionado determina los eventos deportivos que serán considerados para el sorteo.

{% tabs %}
{% tab title="Deportes" %}
<table><thead><tr><th width="147">Campo</th><th width="112">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Añadir Manual</code></strong></td><td>Botón</td><td>Agrega deportes manualmente mediante su identificador.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Registra el identificador del deporte.</td></tr><tr><td><strong><code>Deportes seleccionados</code></strong></td><td>Texto</td><td>Muestra el nombre del deporte agregado.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL</td><td>Registra la dirección de la imagen asociada al deporte.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Botón</td><td>Elimina el deporte agregado.</td></tr><tr><td><strong><code>Deportes</code></strong></td><td>Texto</td><td>Agrega varios deportes mediante IDs separados por comas (,).</td></tr></tbody></table>
{% endtab %}

{% tab title="Mercados" %}
<table><thead><tr><th width="155">Campo</th><th width="112">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Añadir Manual</code></strong></td><td>Botón</td><td>Agrega mercados manualmente mediante su identificador.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Registra el identificador del mercado.</td></tr><tr><td><strong><code>Mercados seleccionados</code></strong></td><td>Texto</td><td>Muestra el nombre del mercado agregado.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL</td><td>Registra la dirección de la imagen asociada al mercado.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Botón</td><td>Elimina el mercado agregado.</td></tr><tr><td><strong><code>Mercados</code></strong></td><td>Texto</td><td>Agrega varios mercados mediante IDs separados por comas (,).</td></tr></tbody></table>


{% endtab %}

{% tab title="Ligas" %}
<table><thead><tr><th width="135">Campo</th><th width="110">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Añadir Manual</code></strong></td><td>Botón</td><td>Agrega ligas manualmente mediante su identificador.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Registra el identificador de la liga.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Muestra el nombre de la liga agregada.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL</td><td>Registra la dirección de la imagen asociada a la liga.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Botón</td><td>Elimina la liga agregada.</td></tr><tr><td><strong><code>Ligas</code></strong></td><td>Texto</td><td>Agrega varias ligas mediante IDs separados por comas (,).</td></tr></tbody></table>


{% endtab %}

{% tab title="Partidos" %}
<table><thead><tr><th width="149">Campo</th><th width="166">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Deporte</code></strong></td><td>Lista desplegable</td><td>Define el deporte sobre el cual se realizará la búsqueda de partidos.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Define el país correspondiente al evento deportivo.</td></tr><tr><td><strong><code>Campeonato</code></strong></td><td>Lista desplegable</td><td>Define el campeonato del cual se seleccionarán los partidos.</td></tr><tr><td><strong><code>Añadir Manual</code></strong></td><td>Botón</td><td>Agrega partidos manualmente mediante su identificador.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Registra el identificador del partido.</td></tr><tr><td><strong><code>Partidos seleccionados</code></strong></td><td>Texto</td><td>Muestra el nombre del partido agregado.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>URL</td><td>Registra la dirección de la imagen asociada al partido.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Botón</td><td>Elimina el partido agregado.</td></tr><tr><td><strong><code>Partidos</code></strong></td><td>Texto</td><td>Agrega varios partidos mediante IDs separados por comas (,).</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

<table><thead><tr><th width="186">Campo</th><th width="164">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de apuesta</code></strong></td><td>Selección múltiple</td><td>Define los tipos de apuesta que serán tenidos en cuenta para participar en el sorteo.</td></tr><tr><td><strong><code>Tipo de evento</code></strong></td><td>Lista desplegable</td><td>Define el tipo de evento deportivo considerado para el sorteo.</td></tr><tr><td><strong><code>Mínima cantidad en selecciones</code></strong></td><td>Numérico</td><td>Establece la cantidad mínima de selecciones requeridas en apuestas múltiples o System.</td></tr><tr><td><strong><code>Mínima cuota en selecciones</code></strong></td><td>Numérico</td><td>Establece la cuota mínima permitida para cada selección.</td></tr><tr><td><strong><code>Mínima cuota total</code></strong></td><td>Numérico</td><td>Establece la cuota mínima total de la apuesta.</td></tr><tr><td><strong><code>Repetir partidos</code></strong></td><td>Interruptor</td><td>Define si un mismo partido puede repetirse dentro del sorteo.</td></tr><tr><td><strong><code>Repetir mercados</code></strong></td><td>Interruptor</td><td>Define si un mismo mercado puede repetirse dentro del sorteo.</td></tr><tr><td>Configuración moneda</td><td>Botón</td><td>Moneda </td></tr><tr><td>Opciones avanzadas</td><td>Botón</td><td>Al hacer clic en "<strong>Opciones avanzadas</strong>", se desplegarán los siguientes campos:</td></tr></tbody></table>

<details>

<summary><strong>Configuración de Moneda</strong></summary>

<table><thead><tr><th width="157">Campo</th><th width="117">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Mínimo valor de la apuesta</code></strong></td><td>Numérico</td><td>Establece el valor mínimo que debe tener una apuesta para participar en el sorteo.</td></tr><tr><td><strong><code>Tipo Premio</code></strong></td><td>Lista desplegable</td><td>Define el tipo de premio que entregará el sorteo. Para este evento únicamente se encuentra disponible el tipo <strong>Físico</strong>.</td></tr><tr><td><strong><code>Posición</code></strong></td><td>Numérico</td><td>Define la posición que ocupará el premio dentro de la tabla de premiación.</td></tr><tr><td><strong><code>Descripción Premio</code></strong></td><td>Texto</td><td>Registra la descripción del premio.</td></tr><tr><td><strong><code>URL Imagen Premio</code></strong></td><td>URL</td><td>Registra la dirección de la imagen asociada al premio.</td></tr><tr><td><strong><code>Hora</code></strong></td><td>Hora</td><td>Establece la hora en la que se realizará el sorteo para la posición configurada.</td></tr><tr><td><strong><code>Agregar</code></strong></td><td>Botón</td><td>Incorpora el premio a la configuración del sorteo.</td></tr></tbody></table>

</details>

<details>

<summary><strong>Opciones Avanzadas</strong></summary>

<table><thead><tr><th width="153">Campo</th><th width="151">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>URL Imagen Principal</code></strong></td><td>URL</td><td>Registra la imagen principal que se visualizará en el sorteo.</td></tr><tr><td><strong><code>URL de Fondo</code></strong></td><td>URL</td><td>Registra la imagen de fondo del sorteo.</td></tr><tr><td><strong><code>Regiones Usuario</code></strong></td><td>Selección múltiple</td><td>Define las regiones donde el sorteo estará disponible.</td></tr><tr><td><strong><code>Departamentos Usuario</code></strong></td><td>Selección múltiple</td><td>Define los departamentos donde el sorteo estará disponible.</td></tr><tr><td><strong><code>Ciudades Usuario</code></strong></td><td>Selección múltiple</td><td>Define las ciudades donde el sorteo estará disponible.</td></tr></tbody></table>

</details>

***

### 7. Validaciones y reglas del negocio

* La creación del sorteo se encuentra disponible únicamente para la vertical **Sportsbook**.
* Los campos identificados con **(\*)** son obligatorios para registrar el sorteo.
* El tipo de premio disponible para los sorteos de punto de venta corresponde únicamente a **Premio Físico**.
* La fecha final debe ser igual o posterior a la fecha inicial.
* Las condiciones configuradas en Sportsbook determinan qué apuestas serán consideradas para el sorteo.
* Al habilitar la opción **Todas las condiciones son obligatorias**, el participante deberá cumplir cada una de las condiciones configuradas para ingresar al sorteo.
* Los deportes, mercados, ligas y partidos pueden agregarse manualmente o mediante una lista de identificadores separados por comas.
* La configuración geográfica restringe la disponibilidad del sorteo a las regiones, departamentos y ciudades seleccionadas.

> **Nota:** Los cambios se almacenan únicamente al hacer clic en **Crear Sorteo**.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="111">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>31/08/2026</td><td>Ronald Peláez</td><td>Documento inicial</td></tr></tbody></table>

</details>
