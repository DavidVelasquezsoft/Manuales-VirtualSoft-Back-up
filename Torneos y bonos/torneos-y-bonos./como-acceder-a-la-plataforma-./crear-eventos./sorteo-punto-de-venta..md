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

<table><thead><tr><th width="151">Campo</th><th width="155">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha inicial</code></strong></td><td>Fecha</td><td>Establece la fecha desde la cual el sorteo estará disponible para participar.</td></tr><tr><td><strong><code>Fecha final</code></strong></td><td>Fecha</td><td>Establece la fecha hasta la cual el sorteo permanecerá activo.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Registra el nombre con el que será identificado el sorteo.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Numérico</td><td>Define la posición en la que se visualizará el sorteo frente a los demás eventos disponibles.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Registra una descripción general del sorteo.</td></tr><tr><td><strong><code>Tipo de Producto</code></strong></td><td>Lista desplegable</td><td>Selecciona la vertical sobre la cual se configurará el sorteo. Para este tipo de evento únicamente se encuentra disponible <strong>Sportsbook</strong>.</td></tr></tbody></table>

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
| Campo                        | Tipo     | Descripción                                                  |
| ---------------------------- | -------- | ------------------------------------------------------------ |
| **`Añadir Manual`**          | Botón    | Agrega deportes manualmente mediante su identificador.       |
| **`ID`**                     | Numérico | Registra el identificador del deporte.                       |
| **`Deportes seleccionados`** | Texto    | Muestra el nombre del deporte agregado.                      |
| **`Imagen`**                 | URL      | Registra la dirección de la imagen asociada al deporte.      |
| **`Acción`**                 | Botón    | Elimina el deporte agregado.                                 |
| **`Deportes`**               | Texto    | Agrega varios deportes mediante IDs separados por comas (,). |
{% endtab %}

{% tab title="Mercados" %}
| Campo                        | Tipo     | Descripción                                                  |
| ---------------------------- | -------- | ------------------------------------------------------------ |
| **`Añadir Manual`**          | Botón    | Agrega mercados manualmente mediante su identificador.       |
| **`ID`**                     | Numérico | Registra el identificador del mercado.                       |
| **`Mercados seleccionados`** | Texto    | Muestra el nombre del mercado agregado.                      |
| **`Imagen`**                 | URL      | Registra la dirección de la imagen asociada al mercado.      |
| **`Acción`**                 | Botón    | Elimina el mercado agregado.                                 |
| **`Mercados`**               | Texto    | Agrega varios mercados mediante IDs separados por comas (,). |


{% endtab %}

{% tab title="Ligas" %}
| Campo               | Tipo     | Descripción                                               |
| ------------------- | -------- | --------------------------------------------------------- |
| **`Añadir Manual`** | Botón    | Agrega ligas manualmente mediante su identificador.       |
| **`ID`**            | Numérico | Registra el identificador de la liga.                     |
| **`Nombre`**        | Texto    | Muestra el nombre de la liga agregada.                    |
| **`Imagen`**        | URL      | Registra la dirección de la imagen asociada a la liga.    |
| **`Acción`**        | Botón    | Elimina la liga agregada.                                 |
| **`Ligas`**         | Texto    | Agrega varias ligas mediante IDs separados por comas (,). |


{% endtab %}

{% tab title="Partidos" %}
| Campo                        | Tipo              | Descripción                                                           |
| ---------------------------- | ----------------- | --------------------------------------------------------------------- |
| **`Deporte`**                | Lista desplegable | Define el deporte sobre el cual se realizará la búsqueda de partidos. |
| **`País`**                   | Lista desplegable | Define el país correspondiente al evento deportivo.                   |
| **`Campeonato`**             | Lista desplegable | Define el campeonato del cual se seleccionarán los partidos.          |
| **`Añadir Manual`**          | Botón             | Agrega partidos manualmente mediante su identificador.                |
| **`ID`**                     | Numérico          | Registra el identificador del partido.                                |
| **`Partidos seleccionados`** | Texto             | Muestra el nombre del partido agregado.                               |
| **`Imagen`**                 | URL               | Registra la dirección de la imagen asociada al partido.               |
| **`Acción`**                 | Botón             | Elimina el partido agregado.                                          |
| **`Partidos`**               | Texto             | Agrega varios partidos mediante IDs separados por comas (,).          |
{% endtab %}
{% endtabs %}

<table><thead><tr><th width="186">Campo</th><th width="170">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo de apuesta</code></strong></td><td>Selección múltiple</td><td>Define los tipos de apuesta que serán tenidos en cuenta para participar en el sorteo.</td></tr><tr><td><strong><code>Tipo de evento</code></strong></td><td>Lista desplegable</td><td>Define el tipo de evento deportivo considerado para el sorteo.</td></tr><tr><td><strong><code>Mínima cantidad en selecciones</code></strong></td><td>Numérico</td><td>Establece la cantidad mínima de selecciones requeridas en apuestas múltiples o System.</td></tr><tr><td><strong><code>Mínima cuota en selecciones</code></strong></td><td>Decimal</td><td>Establece la cuota mínima permitida para cada selección.</td></tr><tr><td><strong><code>Mínima cuota total</code></strong></td><td>Decimal</td><td>Establece la cuota mínima total de la apuesta.</td></tr><tr><td><strong><code>Repetir partidos</code></strong></td><td>Interruptor</td><td>Define si un mismo partido puede repetirse dentro del sorteo.</td></tr><tr><td><strong><code>Repetir mercados</code></strong></td><td>Interruptor</td><td>Define si un mismo mercado puede repetirse dentro del sorteo.</td></tr><tr><td>Configuración moneda</td><td>Botón</td><td>Moneda </td></tr><tr><td>Opciones avanzadas</td><td>Botón</td><td>Al hacer clic en "<strong>Opciones avanzadas</strong>", se desplegarán los siguientes campos:</td></tr></tbody></table>

<details>

<summary><strong>Configuración de Moneda</strong></summary>

| Campo                            | Tipo              | Descripción                                                                                                               |
| -------------------------------- | ----------------- | ------------------------------------------------------------------------------------------------------------------------- |
| **`Mínimo valor de la apuesta`** | Valor monetario   | Establece el valor mínimo que debe tener una apuesta para participar en el sorteo.                                        |
| **`Tipo Premio`**                | Lista desplegable | Define el tipo de premio que entregará el sorteo. Para este evento únicamente se encuentra disponible el tipo **Físico**. |
| **`Posición`**                   | Numérico          | Define la posición que ocupará el premio dentro de la tabla de premiación.                                                |
| **`Descripción Premio`**         | Texto             | Registra la descripción del premio.                                                                                       |
| **`URL Imagen Premio`**          | URL               | Registra la dirección de la imagen asociada al premio.                                                                    |
| **`Hora`**                       | Hora              | Establece la hora en la que se realizará el sorteo para la posición configurada.                                          |
| **`Agregar`**                    | Botón             | Incorpora el premio a la configuración del sorteo.                                                                        |



</details>

<details>

<summary><strong>Opciones Avanzadas</strong></summary>

| Campo                       | Tipo               | Descripción                                                   |
| --------------------------- | ------------------ | ------------------------------------------------------------- |
| **`URL Imagen Principal`**  | URL                | Registra la imagen principal que se visualizará en el sorteo. |
| **`URL de Fondo`**          | URL                | Registra la imagen de fondo del sorteo.                       |
| **`Regiones Usuario`**      | Selección múltiple | Define las regiones donde el sorteo estará disponible.        |
| **`Departamentos Usuario`** | Selección múltiple | Define los departamentos donde el sorteo estará disponible.   |
| **`Ciudades Usuario`**      | Selección múltiple | Define las ciudades donde el sorteo estará disponible.        |

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
