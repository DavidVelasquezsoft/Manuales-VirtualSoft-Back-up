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

# Dashboard.

Esta será la visual principal que tendrás al momento de ingresar a esta opción:

Podrás realizar una búsqueda filtrando la información según tu necesidad. Los filtros disponibles son los siguientes:

* **Dato**: Permite seleccionar si deseas visualizar la información relacionada con los bonos o los torneos en la gráfica.
* **Fecha**: Permite establecer un rango de fechas para visualizar los datos dentro del período seleccionado.
* **Moneda**: Muestra la moneda correspondiente al país seleccionado previamente en la plataforma. No permite cambiar entre diferentes monedas, sino que se adapta automáticamente a la del país con el que estás trabajando.
* **Tipo de visualización**: Permite configurar la escala temporal en la que se mostrará la gráfica, ya sea por hora, día o mes.
* **Estado**: Filtra los bonos o torneos según el estado en el que se encuentren, mostrando solo la información relevante a la selección realizada.
* **Tipo de valor**: Permite elegir entre tres opciones para determinar qué datos se visualizarán en la gráfica:
  * **Valor bono**: Muestra el valor otorgado al usuario por cada bono redimido. En este caso, la gráfica reflejará únicamente los bonos entregados y su respectivo valor.
  * **Valor base**: Representa un valor auxiliar que puede utilizarse de diferentes maneras según el tipo de bono. Puede funcionar como un límite o como un parámetro adicional para determinar el valor final que recibe el usuario. Al seleccionar esta opción, la gráfica mostrará el valor base del bono, sin que este represente necesariamente el monto entregado al usuario.
  * **Cantidad de bonos**: Muestra el número total de bonos según el estado seleccionado en el filtro de estado.

Una vez configurados los filtros según tu necesidad, puedes hacer clic en el botón "**Aplicar**", ubicado en la parte superior derecha del apartado de filtros. Esto actualizará la gráfica con la información correspondiente a los parámetros seleccionados, a continuación, encontrarás un ejemplo de la gráfica que podrás ver.

<figure><img src="../../../.gitbook/assets/image (199).png" alt=""><figcaption><p>Figura #3: Captura de pantalla Grafico.</p></figcaption></figure>

En este caso, podrás visualizar una gráfica con distintos parámetros. En la parte inferior, se mostrará la línea de tiempo, mientras que en el eje lateral se representará el valor total de los bonos correspondientes a cada fecha.

En la parte inferior veremos los siguientes campos:&#x20;

* Bonos activos: La cantidad de bonos activos según el rango de fechas.
* Bonos redimidos: La cantidad de bonos redimidos según el rango de fechas y el monto de dichos bonos.
* Bonos expirados: La cantidad de bonos expirados según el rango de fechas, junto con el monto total de dichos bonos.
* Todos los bonos: La cantidad de bonos totales según el rango de fechas junto con el monto total de dichos bonos.

***

## Dashboard

El módulo Dashboard centraliza la visualización de los principales indicadores de los bonos y torneos creados, permitiendo consultar su comportamiento mediante gráficos e información resumida a partir de diferentes criterios de filtrado.

### 1. Acceso al Módulo

**Ruta de acceso**: Menú principal > Torneos y Bonos > Dashboard

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (197).png" alt=""><figcaption><p>Figura #1: Captura de pantalla inicio Dashboard.</p></figcaption></figure>

***

### 3. Acciones del Usuario

<table><thead><tr><th width="121">Sección</th><th width="172">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Selección múltiple</td><td>Permite consultar la información del Dashboard aplicando diferentes criterios de búsqueda.</td></tr><tr><td><strong>Gráfica</strong></td><td>Visualización</td><td>Presenta el comportamiento de los datos consultados de acuerdo con los filtros aplicados.</td></tr><tr><td><strong>Indicadores</strong></td><td>Visualización</td><td>Muestra un resumen de los principales indicadores asociados a los datos consultados.</td></tr><tr><td><strong>Aplicar</strong></td><td>Botón</td><td>Ejecuta la consulta utilizando los filtros seleccionados y actualiza la información de la gráfica.</td></tr></tbody></table>

***

### 4. Filtros Disponibles

Los filtros permiten personalizar la información que se visualizará en la gráfica.

<table><thead><tr><th width="168">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Dato</strong></td><td>Permite seleccionar si la información a consultar corresponde a <strong>Bonos</strong> o <strong>Torneos</strong>.</td></tr><tr><td><strong>Fecha</strong></td><td>Permite definir el rango de fechas sobre el cual se realizará la consulta de información.</td></tr><tr><td><strong>Moneda</strong></td><td>Muestra la moneda correspondiente al país seleccionado previamente en la plataforma. Este valor es informativo y no permite seleccionar otra moneda.</td></tr><tr><td><strong>Tipo de visualización</strong></td><td>Define la agrupación temporal de la información mostrada en la gráfica. Las opciones disponibles son <strong>Hora</strong>, <strong>Día</strong> o <strong>Mes</strong>.</td></tr><tr><td><strong>Estado</strong></td><td>Filtra la información según el estado de los bonos o torneos seleccionados.</td></tr><tr><td><strong>Tipo de valor</strong></td><td>Permite seleccionar el tipo de información que se representará en la gráfica.</td></tr></tbody></table>

#### Opciones del filtro **Tipo de valor**

| Opción                | Descripción                                                                                                     |
| --------------------- | --------------------------------------------------------------------------------------------------------------- |
| **Valor bono**        | Muestra el valor total entregado a los usuarios mediante los bonos redimidos.                                   |
| **Valor base**        | Presenta el valor base configurado para los bonos, independientemente del valor finalmente otorgado al usuario. |
| **Cantidad de bonos** | Muestra la cantidad total de bonos correspondientes al estado seleccionado.                                     |

Una vez configurados los filtros, haz clic en el botón **Aplicar** para actualizar la información de la gráfica con los criterios seleccionados.

***

### 5. Gráfica e Indicadores

Después de aplicar los filtros, el sistema actualizará la gráfica con la información correspondiente.

La gráfica presenta la evolución de la información durante el período consultado.

* El eje horizontal representa la línea de tiempo según el tipo de visualización seleccionado.
* El eje vertical representa el valor o la cantidad correspondiente a la información consultada.

#### Indicadores

En la parte inferior de la gráfica se visualizarán los siguientes indicadores:

| Indicador           | Descripción                                                                                                     |
| ------------------- | --------------------------------------------------------------------------------------------------------------- |
| **Bonos activos**   | Muestra la cantidad de bonos activos dentro del rango de fechas consultado.                                     |
| **Bonos redimidos** | Presenta la cantidad de bonos redimidos y el valor total asociado a dichos bonos durante el período consultado. |
| **Bonos expirados** | Muestra la cantidad de bonos expirados y el valor total correspondiente al período consultado.                  |
| **Todos los bonos** | Presenta la cantidad total de bonos registrados y el valor acumulado dentro del rango de fechas seleccionado.   |

***

### 6. Validaciones y Reglas de Negocio

* El Dashboard únicamente muestra información correspondiente al **partner** seleccionado previamente desde BackOffice.
* La información presentada en la gráfica se actualizará únicamente al hacer clic en el botón **Aplicar**.
* El filtro **Moneda** es informativo y corresponde automáticamente al país seleccionado en la plataforma.
* El filtro **Tipo de visualización** modifica únicamente la agrupación temporal de los datos mostrados en la gráfica.
* La información disponible en los indicadores inferiores corresponde a los filtros aplicados en la consulta.
* Si no existen registros para los criterios seleccionados, la gráfica y los indicadores se mostrarán sin información.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

| Versión | Fecha      | Autor | Cambios realizados                                 |
| ------- | ---------- | ----- | -------------------------------------------------- |
| 1.0     | DD/MM/AAAA | -     | Creación de la documentación del módulo Dashboard. |

</details>
