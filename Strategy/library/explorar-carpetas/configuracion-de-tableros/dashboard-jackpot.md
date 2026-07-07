---
description: >-
  Permite visualizar, analizar y exportar información detallada sobre la
  acumulación de un jackpot, y darle un seguimiento continuo.
---

# Dashboard Jackpot

### **1. Acceso al Módulo**

**Ruta de Acceso:** Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales

***

### **2. Configuraciones Previas**

Antes de visualizar el reporte, es necesario definir las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/tableros#id-2.-configuracion-previa) obligatorias. Adicionalmente, se pueden establecer las siguientes configuraciones **opcionales**.

<table><thead><tr><th width="170.25">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#jackpot-padre"><strong><code>Jackpot padre</code></strong></a></td><td>Identificador único del jackpot principal, que permite consultar y relacionar todas las series generadas a partir de sus reinicios (<em>jackpots hijos</em>), es decir, las nuevas instancias creadas cuando el jackpot se reinicia.</td></tr><tr><td><strong><code>Id Jackpot</code></strong></td><td>identificador único del jackpot en especifico por el cual deseas realizar la consulta</td></tr></tbody></table>

***

### 3. Vistas disponibles

Este reporte permite consultar la información en dos vistas: resumida y detallada.\
Mediante el **botón de cambio de vista**, el usuario puede alternar entre ambos modos de consulta de los [jackpots](https://virtualsoft.gitbook.io/untitled/glosario/#jackpot) según su necesidad.

* **Vista detallada:** muestra información mas detallada por tickets
* **Vista resumida:** muestra información acumulada agrupada por el ID del jackpot principal.

A continuación, se describe el funcionamiento de cada vista.

#### 3.1. 🔍 Filtros Disponibles

<table><thead><tr><th width="159.83343505859375">Filtros</th><th width="119.33331298828125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Permite seleccionar un rango de fechas mediante un calendario para consultar información dentro de ese periodo.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>permite filtrar por un <a href="https://virtualsoft.gitbook.io/untitled/glosario/#partner">partner</a> en especifico.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el país en el cual fue creado el jackpot.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#jackpot-padre"><strong><code>Jackpot Padre</code></strong></a></td><td>Lista desplegable</td><td>Permite filtrar la información por el identificador único del jackpot principal y visualizar las series (<em>Jackpots hijos</em>) asociadas a el.</td></tr><tr><td><strong><code>ID Jackpot</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por múltiples identificadores únicos de jackpots.</td></tr><tr><td><strong><code>Nombre Jackpot</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por múltiples nombres de jackpots mostrados en el reporte.</td></tr><tr><td><strong><code>¿Hay ganador?</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los jackpots según la existencia de un ganador, mostrando aquellos que tienen ganador o los que aún no lo tienen.</td></tr><tr><td><strong><code>Verticales</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar una o varias verticales (<em>Deportivas, Casino Slot, Casino en Vivo, Virtuales, etc...</em>) para ver resultados específicos en ellas.</td></tr><tr><td><strong><code>Tipo de saldo</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por el tipo de saldo en el que esta configurado el jackpot (<em>Saldo recarga, saldo retiro, etc...</em>).</td></tr></tbody></table>

{% tabs fullWidth="false" %}
{% tab title="📈 Resumido" %}
#### 3.2. 🖼️ Visualización

<figure><img src="../../../.gitbook/assets/image (122).png" alt=""><figcaption></figcaption></figure>

#### 3.3. KP&#x49;**´s**

Los KPI se muestran en la parte superior del dashboard y presentan **indicadores generales** calculados sobre todos los jackpots consultados, ya sea uno o varios, **según los filtros aplicados**.

<table><thead><tr><th width="224.25">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Apuestas</code></strong></td><td>Indica el monto total acumulado de las apuestas válidas que participan en los jackpots mostrados en el reporte.</td></tr><tr><td><strong><code>Cantidad de apuestas</code></strong></td><td>Muestra el número total de apuestas válidas registradas en los jackpots.</td></tr><tr><td><strong><code>pozo Jackpot</code></strong></td><td>Presenta el valor total acumulado en el pozo del jackpot, calculado a partir del porcentaje de acumulación de las apuestas válidas.</td></tr><tr><td><strong><code>Premio Jackpot</code></strong></td><td>Indica el valor total entregado como premio a los ganadores del jackpot o de los jackpots consultados.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Muestra el valor total de los premios ganados por los usuarios en las apuestas que participaron en los jackpots.</td></tr><tr><td><strong><code>Participantes únicos</code></strong></td><td>Indica la cantidad de jugadores diferentes que realizaron apuestas válidas en los jackpots mostrados.</td></tr><tr><td><strong><code>Valor base</code></strong></td><td>Muestra el valor inicial con el que se configuró el jackpot.</td></tr><tr><td><strong><code>Cantidad verticales</code></strong></td><td>Indica el número de verticales activas en las que se realizaron apuestas que participaron en el jackpot.</td></tr></tbody></table>

#### 3.4. Grafico Tendencias de acumulación

<table><thead><tr><th width="132.8333740234375">Grafico</th><th width="143.75">Tipo de grafico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Comportamiento Apuestas Jackpot</code></strong></td><td>Grafico de barras + grafico de líneas</td><td><p>Permite visualizar el <strong>crecimiento del valor acumulado</strong> del jackpot dentro del <strong>rango de fechas seleccionado</strong>, mostrando su comportamiento a lo largo del <strong>tiempo</strong>.</p><p>Este gráfico combina <strong>barras y una línea</strong> para mostrar la evolución diaria:</p><ul><li><strong>La línea</strong>, formada por puntos unidos, representa el <strong>valor acumulado del jackpot alcanzado en cada día</strong>, el cual se muestra en la escala ubicada al <strong>lado derecho del gráfico</strong>.</li><li><strong>Las barras</strong> representan el <strong>monto total de las apuestas válidas realizadas cada día</strong>, el cual se muestra en la <strong>escala</strong> ubicada al <strong>lado izquierdo del grafico</strong>.</li><li><strong>El eje x</strong> muestra los días del período seleccionado.</li></ul><p>Cada barra y cada punto de la línea corresponden al mismo día, lo que permite comparar de forma sencilla el valor apostado diariamente con el crecimiento acumulado del jackpot.</p></td></tr></tbody></table>

#### 3.5. Resultados de consulta

Al realizar la consulta en tipo de visualización como "_**Resumido**_" permite visualizar **2 tipos** de tablas las cuales son:

{% tabs %}
{% tab title="Detalle Jackpot" %}
Permite visualizar información detallada de los jackpots consultados.

<table><thead><tr><th width="214">Campos</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Indica el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#partner">partner</a> en el que fue creado el jackpot.</td></tr><tr><td><strong><code>País</code></strong></td><td>Indica el país en el que ese jackpot esta activo.</td></tr><tr><td><strong><code>Id Jackpot</code></strong></td><td>Indica el identificador unico del jackpot.</td></tr><tr><td><strong><code>Jackpot padre</code></strong></td><td>Indica el identificador único del jackpot principal del que se derivo la serie (<em>Si aplica</em>).</td></tr><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Permite visualizar la fecha en la que inicio el jackpot.</td></tr><tr><td><strong><code>Nombre Jackpot</code></strong></td><td>Muestra el nombre del jackpot.</td></tr><tr><td><strong><code>Vertical</code></strong></td><td>Indica las <a href="https://virtualsoft.gitbook.io/untitled/glosario#vertical">verticales</a> aplicadas en la creación del jackpot (<em>Deportivas, Casino Slot, Virtuales o Varias</em>).</td></tr><tr><td><strong><code>Tipo Saldo jackpot</code></strong></td><td>Permite visualizar el tipo de saldo al que va dirigido el premio del jackpot.</td></tr><tr><td><strong><code>¿Hay ganador Jackpot?</code></strong></td><td>Indica si ya hay un ganador en el jackpot.</td></tr><tr><td><strong><code>Cantidad participantes</code></strong></td><td>Permite visualizar el total de jugadores que participaron o están participando en la campaña del jackpot.</td></tr><tr><td><strong><code>Cantidad apuesta</code></strong></td><td>Muestra el número total de apuestas válidas registradas en los jackpots.</td></tr><tr><td><strong><code>Valor Apostado</code></strong></td><td>Permite visualizar el monto total acumulado de las apuestas que participaron en el jackpot.</td></tr><tr><td><strong><code>Premio</code></strong></td><td>Permite visualizar el valor total ganado por las apuestas que aportaron al jackpot.</td></tr><tr><td><strong><code>Valor Acumulado</code></strong></td><td>Permite visualizar el valor total acumulado en el pozo del jackpot.</td></tr></tbody></table>
{% endtab %}

{% tab title="Jackpot ganador" %}
Permite visualizar información de los jackpots consultados que ya han finalizado y cuentan con un ganador.

<table><thead><tr><th width="214">Campos</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Jackpot</code></strong></td><td>Indica el identificador unico del jackpot.</td></tr><tr><td><strong><code>Jackpot padre</code></strong></td><td>Indica el identificador único del jackpot principal del que se derivo la serie (<em>Si aplica</em>).</td></tr><tr><td><strong><code>Nombre Jackpot</code></strong></td><td>Muestra el nombre del jackpot.</td></tr><tr><td><strong><code>Id usuario ganador</code></strong></td><td>Muestra el identificador unico del usuario que gano el jackpot</td></tr><tr><td><strong><code>Vertical ganador</code></strong></td><td>Indica la <a href="https://virtualsoft.gitbook.io/untitled/glosario#vertical">vertical</a> en la que se realizo la apuesta ganadora. (<em>Ej: Deportivas, Casino Slot, Virtuales</em>).</td></tr><tr><td><strong><code>Premio jackpot</code></strong></td><td>Permite visualizar el valor del premio del jackpot otorgado al usuario.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}



> ⚠️**Nota:** Este es el reporte **Resumido**, para ver la documentación relacionada al reporte **Detallado** clic aquí 🔽

<p align="center"><a href="dashboard-jackpot.md#detallado" class="button primary" data-icon="clipboard-list-check">Reporte detallado</a></p>
{% endtab %}

{% tab title="🗂️ Detallado" %}
#### 3.2. 🖼️ Visualización

<figure><img src="../../../.gitbook/assets/image (123).png" alt=""><figcaption></figcaption></figure>

#### 3.3. KP&#x49;**´s**

Los KPI se muestran en la parte superior del dashboard y presentan **indicadores generales** calculados sobre todos los jackpots consultados, ya sea uno o varios, **según los filtros aplicados**.

<table><thead><tr><th width="210.9166259765625">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Apuestas</code></strong></td><td>Indica el monto total acumulado de las apuestas válidas que participan en los jackpots mostrados en el reporte.</td></tr><tr><td><strong><code>Cantidad de apuestas</code></strong></td><td>Muestra el número total de apuestas válidas registradas en los jackpots.</td></tr><tr><td><strong><code>pozo Jackpot</code></strong></td><td>Presenta el valor total acumulado en el pozo del jackpot, calculado a partir del porcentaje de acumulación de las apuestas válidas.</td></tr><tr><td><strong><code>Premio Jackpot</code></strong></td><td>Indica el valor total entregado como premio a los ganadores del jackpot o de los jackpots consultados.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Muestra el valor total de los premios ganados por los usuarios en las apuestas que participaron en los jackpots.</td></tr><tr><td><strong><code>Participantes únicos</code></strong></td><td>Indica la cantidad de jugadores diferentes que realizaron apuestas válidas en los jackpots mostrados.</td></tr><tr><td><strong><code>Valor base</code></strong></td><td>Muestra el valor inicial con el que se configuró el jackpot.</td></tr><tr><td><strong><code>Cantidad verticales</code></strong></td><td>Indica el número de verticales activas en las que se realizaron apuestas que participaron en el jackpot.</td></tr></tbody></table>

#### 3.4. Gráficos

<table><thead><tr><th width="157.00006103515625">Nombre </th><th width="158.33331298828125">Tipo de grafica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Apuestas por vertical</code></strong></td><td>Grafico de barras comparativas</td><td>Gráfico de barras comparativo que muestra, por cada vertical del jackpot (Deportivas, Casino y Live Casino), el <strong>monto total de apuestas válidas acumuladas</strong> y <strong>el valor total de premios generados por esas apuestas</strong>. El eje X representa las verticales y el eje Y los valores acumulados.</td></tr><tr><td><strong><code>Top 10 usuarios que más apostaron</code></strong></td><td>Gráfico de barras horizontales de ranking</td><td>Gráfico que muestra el top 10 de usuarios con mayor valor apostado, indicando el ID de cada usuario y el monto total apostado.</td></tr></tbody></table>

#### 3.5. Resultados de consulta

Al seleccionar el tipo de visualización **"Detallado"**, el sistema muestra la tabla **Detallado por ticket**, la cual presenta la información desglosada por cada ticket de apuesta.

<table><thead><tr><th width="226.5">Campos</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Indica el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#partner">partner</a> en el que fue creado el jackpot.</td></tr><tr><td><strong><code>Pais</code></strong></td><td>Indica el país en el que ese jackpot esta activo.</td></tr><tr><td><strong><code>ID Jackpot Padre</code></strong></td><td>Muestra el identificador único del Jackpot Padre al que pertenece la serie o jackpot consultado.</td></tr><tr><td><strong><code>ID Jackpot</code></strong></td><td>Identificador único asignado al jackpot específico dentro de una serie derivada del Jackpot Padre.</td></tr><tr><td><strong><code>Fecha Ticket</code></strong></td><td>Permite visualizar la fecha correspondiente al registro del jackpot.</td></tr><tr><td><strong><code>Nombre Jackpot</code></strong></td><td>Muestra el nombre del jackpot.</td></tr><tr><td><strong><code>Vertical</code></strong></td><td>Indica las <a href="https://virtualsoft.gitbook.io/untitled/glosario#vertical">verticales</a> aplicadas en la creación del jackpot (<em>Deportivas, Casino Slot, Virtuales o Varias</em>).</td></tr><tr><td><strong><code>Ticket</code></strong></td><td>Muestra el identificador único de la apuesta.</td></tr><tr><td><strong><code>Ticket ganador</code></strong></td><td>Muestra el identificador unico de la apuesta ganadora.</td></tr><tr><td><strong><code>Id usuario</code></strong></td><td>Indica el identificador único del usuario que realizó la apuesta</td></tr><tr><td><strong><code>Valor apostado</code></strong></td><td>Muestra el monto apostado en la apuesta.</td></tr><tr><td><strong><code>Premio</code></strong></td><td>Permite visualizar el valor ganado con la apuesta realizada.</td></tr><tr><td><strong><code>Valor acumulado jackpot</code></strong></td><td>Indica el valor acumulado al jackpot a partir del porcentaje de acumulación aplicado a la apuesta.</td></tr></tbody></table>

> ⚠️**Nota:** Este es el reporte **detallado**, para ver la documentación relacionada al reporte **resumido** clic aquí 🔽

<p align="center"><a href="dashboard-jackpot.md#resumido" class="button primary" data-icon="clipboard-list-check">Reporte resumido</a></p>
{% endtab %}
{% endtabs %}

***

### 4.  Validaciones y Reglas de Negocio

* El dashboard está disponible únicamente para perfiles con permisos autorizados.
* El jackpot solo acumula sobre las apuestas que estén dentro del valor mínimo y máximo permitido; cualquier apuesta fuera de esos límites no suma a la acumulación.

***

### 5. Control de Versiones

| Versión | Fecha      | Autor           | Cambios Realizados |
| ------- | ---------- | --------------- | ------------------ |
| 1.0     | 20/12/2025 | David Velasquez | Documento inicial  |
