# Sorteo punto de venta.

Para crear una ruleta, selecciona la opción "**Sorteo Punto Venta**" en la lista de tipos de eventos.

Al ingresar a esta sección, verás la siguiente visual:

<figure><img src="../../../.gitbook/assets/image (59).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Creación de Sorteos.</p></figcaption></figure>

* **Fecha inicial**: Especifica la fecha en la que la ruleta estará disponible para participar.
* **Fecha final**: Indica la fecha hasta la cual la ruleta permanecerá activa.
* **Nombre**: Asigna un nombre único a la ruleta.
* **Descripción**: Proporciona una breve descripción de la ruleta.
* **Orden**: Define la posición de la ruleta en relación con otras disponibles.
* **Tipo de producto**: Para los sorteos de punto de venta, solo es posible crearlos bajo la [vertical](https://app.gitbook.com/o/QcwavWzh0dfIwPyknoIT/s/mbqa0WvDWam8G20QQoIZ/#vertical) Sportsbook. Esta configuración desplegará las siguientes opciones:

<figure><img src="../../../.gitbook/assets/image (60).png" alt=""><figcaption><p>Figura #2: Captura de pantalla configuraciones tipo de producto.</p></figcaption></figure>

* Tipo de Ranking: Indica si el tipo de ranking va a ser por monto de dinero o por líneas de apuestas.
* Todas las condiciones son obligatorias: Indica así las configuraciones realizadas previamente son obligatorias para ingresa al sorteo.

También es necesario configurar qué segmento de Sportsbook estará disponible para activar la ruleta. Según el segmento seleccionado, cambiarán las configuraciones. A continuación, encontrarás las configuraciones de cada segmento:

* **Deporte**: Permite definir los deportes en los que aplicará la ruleta. Puedes agregarlos de las siguientes formas:
  * **Botón "añadir Manual"**: Podrás añadir deportes de manera manual dando clic en este botón y completando los siguientes campos:
    * **ID**: Ingresa el ID del deporte.
    * **Deportes seleccionados**: Especifica el nombre del deporte.
    * **Imagen**: Agrega la URL de la imagen representativa.
    * **Acción**: Usa el botón "**Eliminar**" para quitar un deporte agregado.
  * **Deportes**: También puedes ingresar varios ID separados por comas (,) para agregarlos rápidamente.&#x20;
* **Mercados**: Define los mercados en los que aplicará la ruleta, con las siguientes opciones:
  * **Botón "añadir Manual"**: Podrás añadir mercados de manera manual dando clic en este botón y completando los siguientes campos:
    * **ID**: Ingresa el ID del mercado.
    * **Mercados seleccionados**: Especifica el nombre del mercado.
    * **Imagen**: Agrega la URL de la imagen representativa.
    * **Acción**: Usa el botón "**Eliminar**" para quitar un mercado agregado.
  * **Mercados**: También puedes ingresar varios ID separados por comas (,) para agregarlos rápidamente.
* **Ligas**: Permite seleccionar las ligas en las que aplicará la ruleta con las siguientes opciones:
  * **Botón "añadir Manual"**: Podrás añadir ligas de manera manual dando clic en este botón y completando los siguientes campos:
    * **ID**: Ingresa el ID de la liga.
    * **Nombre**: Especifica el nombre de la liga.
    * **Imagen**: Agrega la URL de la imagen representativa.
    * **Acción**: Usa el botón "**Eliminar**" para quitar una liga agregada.
  * **Ligas**: También puedes ingresar varios ID separados por comas (,) para agregar ligas rápidamente.
* **Partidos**: Permite seleccionar los partidos en los que aplicará la ruleta, realizando las siguientes configuraciones:
  * **Deporte**: Debes indicar en qué deporte estará disponible la ruleta.
  * **País**: Debes indicar en qué país estará disponible la ruleta.
  * **Campeonato**: Debes indicar en qué campeonato estará disponible la ruleta.
  * **Añadir manual**: Podrás añadir ciertos partidos de manera manual dando clic en este botón. Esto desplegará los siguientes campos:
    * **ID**: Debes ingresar el ID del partido que estará disponible para la ruleta.
    * **Partidos seleccionados**: Debes indicar el nombre del partido que estará disponible para la ruleta.
    * **Imagen**: Debes agregar la URL de la imagen que tendrá la ruleta.
    * **Acción**: Encontrarás el botón "Eliminar", para borrar los partidos ingresados manualmente.
  * **Partidos**: También podrás agregar los partidos agregando los IDs separados por comas (,).
* **Tipo de apuesta**: Debes seleccionar el tipo de apuesta que contará para la ruleta. Puedes seleccionar múltiples opciones, las cuales son las siguientes:
  * **Single**: Es el tipo de apuesta más simple, donde se elige un pronóstico, se define el monto a apostar y se realiza la apuesta.
  * **Múltiple**: Consiste en combinar múltiples selecciones en una única apuesta.
  * **System**: Funciona combinando los pronósticos seleccionados, permitiendo obtener cuotas atractivas con menor riesgo que las apuestas múltiples, ya que no se pierde todo en caso de un solo fallo.
* **Tipo de evento**: Debes seleccionar el tipo de evento que contará para la ruleta. En este caso, solo puedes seleccionar una opción, las cuales son las siguientes:
  * **Both**: Es la combinación de ambos mercados.
  * **Pre-match**: Hace referencia a eventos que no son en vivos y que pueden pronosticar antes de que inicien.
  * **Live**: Hace referencia a eventos que ya están en juego y pueden apostarse únicamente cuando estén jugando.
* **Mínima cantidad en selecciones**: Debes indicar la cantidad mínima de selecciones que el jugador puede tener en las apuestas múltiples (system).
* **Mínima cuota en selecciones**: Debes indicar las cuotas mínimas para cada selección.
* **Mínima cuota total**: Debes indicar las cuotas mínimas en total.
* Repetir partidos: Establece si es posible que se reportan partidos en el sorteo.
* Repetir mercados: Establece si es posible que se reportan mercados en el sorteo.

### Configuración moneda:

En este apartado verás la moneda correspondiente al país seleccionado antes de ingresar a torneos y bonos, al seleccionarla se desplegarán las siguientes configuraciones:

<figure><img src="../../../.gitbook/assets/image (61).png" alt=""><figcaption><p>Figura #3: Captura de pantalla configuración moneda.</p></figcaption></figure>

Las opciones disponibles son las siguientes:

* Mínimo valor de la apuesta: Indica el valor mínimo por apuesta para ingresar al sorteo.
* Tipo Premio: Solo podrás establecer el tipo de premio como Físico, indicando que de esta manera se entregará el premio, teniendo en cuenta que es necesario realizar las siguientes configuraciones:
  * Posición: Indica la posición del premip en la tabla de premiaciones.
  * Descripción Premio: Indica una breve descripción del premio.
  * URL Imagen premio: Ingresa la URL de la imagen que tendrá el premio.
  * Hora: Indica una hora fija en la que se sorteará esta posición.
  * Botón agregar: este botón funciona para agregar los datos ingresados en los anteriores campos como un premio del sorteo.

### Opciones avanzadas:

Al hacer clic en "**Opciones avanzadas**", se desplegarán los siguientes campos:

<figure><img src="../../../.gitbook/assets/image (62).png" alt=""><figcaption><p>Figura #4: Captura de pantalla opciones avanzadas.</p></figcaption></figure>

* **URL Imagen Principal:** Especifica la URL de la imagen principal que tendrá el sorteo.
* **URL de fondo**: Especifica la URL de la imagen de fondo que tendrá el sorteo.
* **Regiones Usuario**: Indica las regiones donde el sorteo estará disponible.
* **Departamentos Usuario**: Indica los departamentos donde el sorteo estará disponible.
* **Ciudades Usuario**: Indica las ciudades donde el sorteo estará disponible.

Una vez configurada la ruleta, haz clic en el botón **"Crear Sorteo"** para guardar los ajustes y crear el sorteo.

{% hint style="warning" %}
**Nota**: Los campos que finalizan el nombre con un \* son obligatorios para la creación del sorteo punto de venta.
{% endhint %}

\
\
\
\
\
\
\
Sorteo Punto de Venta

El módulo **Sorteo Punto de Venta** permite crear sorteos dirigidos a los usuarios que realizan apuestas desde puntos de venta autorizados. Durante la configuración del sorteo es posible establecer su vigencia, condiciones de participación, criterios aplicables para Sportsbook, configuración de premios, restricciones geográficas y demás parámetros necesarios para su funcionamiento.

***

### 1. Acceso al Módulo

**Ruta de Acceso:** Backoffice > Torneos y Bonos > Eventos > Crear Evento > **Sorteo Punto Venta**

***

### 2. Visualización

La pantalla se encuentra dividida en las siguientes secciones:

* Configuración general.
* Configuración Sportsbook.
* Configuración de moneda.
* Opciones avanzadas.

***

### 3. Acciones disponibles

| Acción           | Descripción                                                                                          |
| ---------------- | ---------------------------------------------------------------------------------------------------- |
| **Crear Sorteo** | Registra el sorteo con la configuración establecida y lo deja disponible según las fechas definidas. |

***

### 4. Configuración General

| Campo                  | Tipo              | Descripción                                                                                                                                |
| ---------------------- | ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| **`Fecha inicial`**    | Fecha             | Establece la fecha desde la cual el sorteo estará disponible para participar.                                                              |
| **`Fecha final`**      | Fecha             | Establece la fecha hasta la cual el sorteo permanecerá activo.                                                                             |
| **`Nombre`**           | Texto             | Registra el nombre con el que será identificado el sorteo.                                                                                 |
| **`Descripción`**      | Texto             | Registra una descripción general del sorteo.                                                                                               |
| **`Orden`**            | Numérico          | Define la posición en la que se visualizará el sorteo frente a los demás eventos disponibles.                                              |
| **`Tipo de Producto`** | Lista desplegable | Selecciona la vertical sobre la cual se configurará el sorteo. Para este tipo de evento únicamente se encuentra disponible **Sportsbook**. |

***

### Configuración Sportsbook

Al seleccionar la vertical **Sportsbook** se habilitan las configuraciones específicas del sorteo.

#### Configuración general

| Campo                                        | Tipo              | Descripción                                                                                 |
| -------------------------------------------- | ----------------- | ------------------------------------------------------------------------------------------- |
| **`Tipo de Ranking`**                        | Lista desplegable | Define el criterio utilizado para calcular el ranking del sorteo.                           |
| **`Todas las condiciones son obligatorias`** | Interruptor       | Indica que todas las condiciones configuradas deben cumplirse para participar en el sorteo. |

#### Segmento Sportsbook

El segmento seleccionado determina los eventos deportivos que serán considerados para el sorteo.

**Deportes**

| Campo                        | Tipo     | Descripción                                                  |
| ---------------------------- | -------- | ------------------------------------------------------------ |
| **`Añadir Manual`**          | Botón    | Agrega deportes manualmente mediante su identificador.       |
| **`ID`**                     | Numérico | Registra el identificador del deporte.                       |
| **`Deportes seleccionados`** | Texto    | Muestra el nombre del deporte agregado.                      |
| **`Imagen`**                 | URL      | Registra la dirección de la imagen asociada al deporte.      |
| **`Acción`**                 | Botón    | Elimina el deporte agregado.                                 |
| **`Deportes`**               | Texto    | Agrega varios deportes mediante IDs separados por comas (,). |

**Mercados**

| Campo                        | Tipo     | Descripción                                                  |
| ---------------------------- | -------- | ------------------------------------------------------------ |
| **`Añadir Manual`**          | Botón    | Agrega mercados manualmente mediante su identificador.       |
| **`ID`**                     | Numérico | Registra el identificador del mercado.                       |
| **`Mercados seleccionados`** | Texto    | Muestra el nombre del mercado agregado.                      |
| **`Imagen`**                 | URL      | Registra la dirección de la imagen asociada al mercado.      |
| **`Acción`**                 | Botón    | Elimina el mercado agregado.                                 |
| **`Mercados`**               | Texto    | Agrega varios mercados mediante IDs separados por comas (,). |

**Ligas**

| Campo               | Tipo     | Descripción                                               |
| ------------------- | -------- | --------------------------------------------------------- |
| **`Añadir Manual`** | Botón    | Agrega ligas manualmente mediante su identificador.       |
| **`ID`**            | Numérico | Registra el identificador de la liga.                     |
| **`Nombre`**        | Texto    | Muestra el nombre de la liga agregada.                    |
| **`Imagen`**        | URL      | Registra la dirección de la imagen asociada a la liga.    |
| **`Acción`**        | Botón    | Elimina la liga agregada.                                 |
| **`Ligas`**         | Texto    | Agrega varias ligas mediante IDs separados por comas (,). |

**Partidos**

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

#### Condiciones de participación

| Campo                                | Tipo               | Descripción                                                                            |
| ------------------------------------ | ------------------ | -------------------------------------------------------------------------------------- |
| **`Tipo de apuesta`**                | Selección múltiple | Define los tipos de apuesta que serán tenidos en cuenta para participar en el sorteo.  |
| **`Tipo de evento`**                 | Lista desplegable  | Define el tipo de evento deportivo considerado para el sorteo.                         |
| **`Mínima cantidad en selecciones`** | Numérico           | Establece la cantidad mínima de selecciones requeridas en apuestas múltiples o System. |
| **`Mínima cuota en selecciones`**    | Decimal            | Establece la cuota mínima permitida para cada selección.                               |
| **`Mínima cuota total`**             | Decimal            | Establece la cuota mínima total de la apuesta.                                         |
| **`Repetir partidos`**               | Interruptor        | Define si un mismo partido puede repetirse dentro del sorteo.                          |
| **`Repetir mercados`**               | Interruptor        | Define si un mismo mercado puede repetirse dentro del sorteo.                          |

***

### 5. Configuración de Moneda

| Campo                            | Tipo              | Descripción                                                                                                               |
| -------------------------------- | ----------------- | ------------------------------------------------------------------------------------------------------------------------- |
| **`Mínimo valor de la apuesta`** | Valor monetario   | Establece el valor mínimo que debe tener una apuesta para participar en el sorteo.                                        |
| **`Tipo Premio`**                | Lista desplegable | Define el tipo de premio que entregará el sorteo. Para este evento únicamente se encuentra disponible el tipo **Físico**. |
| **`Posición`**                   | Numérico          | Define la posición que ocupará el premio dentro de la tabla de premiación.                                                |
| **`Descripción Premio`**         | Texto             | Registra la descripción del premio.                                                                                       |
| **`URL Imagen Premio`**          | URL               | Registra la dirección de la imagen asociada al premio.                                                                    |
| **`Hora`**                       | Hora              | Establece la hora en la que se realizará el sorteo para la posición configurada.                                          |
| **`Agregar`**                    | Botón             | Incorpora el premio a la configuración del sorteo.                                                                        |

***

### 6. Opciones Avanzadas

| Campo                       | Tipo               | Descripción                                                   |
| --------------------------- | ------------------ | ------------------------------------------------------------- |
| **`URL Imagen Principal`**  | URL                | Registra la imagen principal que se visualizará en el sorteo. |
| **`URL de Fondo`**          | URL                | Registra la imagen de fondo del sorteo.                       |
| **`Regiones Usuario`**      | Selección múltiple | Define las regiones donde el sorteo estará disponible.        |
| **`Departamentos Usuario`** | Selección múltiple | Define los departamentos donde el sorteo estará disponible.   |
| **`Ciudades Usuario`**      | Selección múltiple | Define las ciudades donde el sorteo estará disponible.        |

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

<table><thead><tr><th width="111">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td></td><td></td><td></td></tr></tbody></table>

</details>
