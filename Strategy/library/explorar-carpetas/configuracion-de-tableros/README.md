---
icon: sun
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

# Configuración de tableros

### 1. Configuraciones previas

Antes de visualizar la información del tablero, es necesario configurar los **parámetros iniciales** desde una **ventana emergente**. Estos parámetros funcionan como **filtros globales** que determinan el alcance de los datos que se mostrarán en todo el tablero.\
Los **filtros internos** del panel dependerán de la configuración establecida en esta etapa.

{% hint style="warning" %}
**Nota:** Estos parámetros deben definirse al momento de ingresar al tablero, antes de ejecutar cualquier consulta.
{% endhint %}

{% stepper %}
{% step %}
#### Desplegar ventana emergente

En la parte superior de la Library se encuentra la barra de herramientas. Desde allí, seleccione el ícono de **filtrar.**

<figure><img src="../../../.gitbook/assets/upscalemedia-transformed (5).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Completar parámetros

Los parámetros permiten agilizar la búsqueda de información. Se dividen en tres segmentos, cada uno obligatorio y conformado por filtros específicos que determinan los datos a mostrar en el tablero.

<table><thead><tr><th width="153">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha Calendario</code></strong></td><td>Configura los parámetros de fecha que definirán la información disponible para los filtros del tablero.</td></tr><tr><td><strong><code>Partner</code></strong></td><td><p>Configura los parámetros del <strong>partner</strong> que determinarán qué opciones estarán disponibles en los filtros del tablero.</p><p>La sección se divide en dos listas:</p><ul><li><strong>Disponibles:</strong> muestra todos los partners por los que se puede filtrar.</li><li><strong>Seleccionadas:</strong> indica los que estarán habilitados en los filtros del tablero.</li></ul></td></tr><tr><td><strong><code>País</code></strong></td><td><p>Configura los parámetros del país que determinarán qué opciones estarán disponibles en los filtros del tablero.</p><p>La sección se divide en dos listas:</p><ul><li><strong>Disponibles:</strong> muestra todos los partners por los que se puede filtrar.</li><li><strong>Seleccionadas:</strong> indica los que estarán habilitados en los filtros del tablero.</li></ul></td></tr></tbody></table>
{% endstep %}

{% step %}
#### Aplicar filtros

Una vez definidos los parámetros, haga clic en el botón **Aplicar** para ejecutar la consulta de datos según los criterios seleccionados y actualizar el contenido del dashboard.
{% endstep %}
{% endstepper %}

***

### 2. Cambio de pestaña

Los dashboards en Library pueden estar compuestos por múltiples pestañas, las cuales permiten visualizar diferentes versiones de la misma información. Estas pestañas suelen representar variaciones del tablero, como visualización en moneda local, USD o datos consolidados.

Cada pestaña presenta particularidades en los datos y métricas mostradas, por lo que el contenido del dashboard se actualiza según la opción seleccionada.

{% hint style="warning" %}
**Nota:** Todas las pestañas consultan la información con base en el mismo periodo definido en las configuraciones previas, por lo que los datos se mantienen consistentes entre vistas.
{% endhint %}

{% stepper %}
{% step %}
#### Abrir tabla de contenido

En la parte superior de la Library se encuentra la barra de herramientas. Desde allí, seleccione el ícono de **Tabla de contenido.**

<figure><img src="../../../.gitbook/assets/image (141).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Visualizar pestañas disponibles

Se desplegará una ventana emergente que presenta todas las pestañas disponibles del dashboard para su selección.
{% endstep %}

{% step %}
#### **Seleccionar la pestaña deseada**

Elija la pestaña que desea consultar (_por ejemplo: Moneda Local, USD o Consolidados_); posteriormente, el contenido del dashboard se actualizará automáticamente según la opción seleccionada.
{% endstep %}

{% step %}
#### **Cambiar de pestaña cuando sea necesario**

Repita el proceso para navegar entre las diferentes pestañas y consultar otras vistas del dashboard según su necesidad.
{% endstep %}
{% endstepper %}

***

### 3. Exportar contenido

Los dashboards en Library permiten exportar la información mediante dos modalidades principales. A continuación, se presentan las guías para cada una de ellas:

#### **3.1. Por componente**

Permite exportar datos de elementos individuales como gráficas, tablas u otros componentes del dashboard. La siguiente guía interactiva muestra cómo realizar este proceso desde cada elemento.

{% @guideflow/guideflow-embed requestedUrl="https://app.guideflow.com/player/gky4womtdk" %}

#### **3.2. Dashboard completo**

Permite exportar toda la información del tablero desde la opción **Compartir** en la barra de herramientas, configurando previamente el formato y parámetros de descarga según la necesidad.

{% stepper %}
{% step %}
#### Acceder a las opciones de exportación

En la parte superior de la Library se encuentra la barra de herramientas. Desde allí, seleccione el ícono de **Compartir** para visualizar las opciones disponibles de exportación.

<figure><img src="../../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Seleccionar el método de exportación

Elija el método de exportación deseado según su necesidad:

<table><thead><tr><th width="199.29632568359375">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Compartir Dashboard</code></strong></td><td>Permite generar un acceso compartido al dashboard.</td></tr><tr><td><strong><code>Exportar a Excel</code></strong></td><td>Permite descargar la información del dashboard en formato Excel.</td></tr><tr><td><strong><code>Exportar a CSV</code></strong></td><td>Permite exportar los datos en formato <a href="https://virtualsoft.gitbook.io/untitled/glosario#csv"><strong>CSV</strong></a>.</td></tr><tr><td><strong><code>Exportar a PDF</code></strong></td><td>Permite generar un archivo PDF del dashboard.</td></tr><tr><td><strong><code>Descargar Dashboard</code></strong></td><td>Permite descargar el dashboard completo según la configuración disponible.</td></tr></tbody></table>
{% endstep %}

{% step %}
#### Configurar la información a exportar

Según el método seleccionado, defina los parámetros de exportación requeridos antes de continuar.
{% endstep %}

{% step %}
#### Descargar el dashboard

Haga clic en el botón **Exportar** para generar y descargar la información del dashboard.
{% endstep %}
{% endstepper %}

***

### 4. Tableros disponibles

{% hint style="info" %}
El nombre del tablero también es un acceso directo para acceder al manual del mismo.
{% endhint %}

<table><thead><tr><th width="242">Tablero</th><th>Resumen</th></tr></thead><tbody><tr><td><a href="dashboard-facturacion-casino.md">Dashboard Facturación Casino</a></td><td>Permite visualizar y analizar la información relacionada con la facturación generada por la vertical de casino, con el fin de facilitar el seguimiento, control y toma de decisiones.</td></tr><tr><td><a href="dashboard-facturacion-deportivas.md">Dashboard Facturación Deportivas</a></td><td>Permite visualizar y analizar la información relacionada con la facturación generada por la vertical de deportivas, con el fin de facilitar el seguimiento, control y toma de decisiones.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/~/revisions/rtwfoTgBNjl4cNkdGfWj/tableros/dashboard-usuarios">Dashboard Usuarios</a></td><td>Este dashboard centraliza y analiza la información del comportamiento de los usuarios, permitiendo identificar tendencias, actividad y resultados en las distintas verticales de la plataforma.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/tableros/dashboard-bonos">Dashboard Bonos</a></td><td><p>Este dashboard contiene información sobre todos los bonos creados para la plataforma Usuarios online.</p><h4 id="id-1.-acceso-al-modulo"><br></h4></td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/tableros/dashboard-casino">Dashboard Casino</a></td><td><p>Permite analizar el comportamiento de la vertical de Apuestas Casino a nivel general, por proveedor y por juego, con KPIs clave como giros, apuestas, premios, GGR y más.</p><h4 id="configuracion-general"><br></h4></td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/tableros/dashboard-de-eventos-deportivos-or-reporte">Dashboard de eventos deportivos | Reporte</a></td><td>El Dashboard de Eventos Deportivos permite visualizar y analizar datos de apuestas mediante filtros, tablas y gráficas para apoyar la toma de decisiones.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/tableros/dashboard-deportiva">Dashboard deportiva</a></td><td>Este dashboard fue diseñado para brindar una visión estratégica del comportamiento de las apuestas deportivas.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/tableros/copy-of-dashboard-retiros">Dashboard Retiros</a></td><td>Permite visualizar, analizar y exportar información detallada sobre las solicitudes de retiro generadas en la plataforma.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/tableros/dashboard-detalle-ticket-deportivas">Dashboard detalle ticket deportivas</a></td><td><p>Permite analizar en profundidad la información de tickets generados en la plataforma, incluyendo apuestas cerradas, valores apostados, cuotas, ganancias potenciales y reales.</p><h4 id="configuracion-general"><br></h4></td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/tableros/dashboard-gerencial">Dashboard gerencial</a></td><td><p>Este panel fue creado para ayudarte a entender mejor cómo se está comportando tu operación en las verticales de deportes, casino, depósitos y retiros.</p><h4 id="id-1.-acceso-al-modulo"><br></h4></td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/tableros/casino-real-time">Casino real time</a></td><td>Presenta la información consolidada de las operaciones de casino correspondientes al día en curso y al día anterior. Permite analizar en tiempo real los resultados de las apuestas.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/tableros/dashboard-deposito">Dashboard Depósito</a></td><td>Este módulo permite analizar y monitorear el comportamiento de los depósitos realizados por los usuarios, a través de un dashboard interactivo en MicroStrategy.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/microstrategy/tableros/dashboard-registros-y-primeros-depositos">Dashboard Registros y primeros depósitos</a></td><td>Permite visualizar información de los primeros depósitos y usuarios registrados en tiempo real.</td></tr><tr><td><a href="dashboard-jackpot.md">Dashboard Jackpot</a></td><td>Permite visualizar, analizar y exportar información detallada sobre la acumulación y demás datos del jackpot, facilitando su seguimiento continuo.</td></tr><tr><td><a href="desfases-jugadores.md">Dasboard desfases jugadores</a></td><td>Permite visualizar y analizar información de los desfaces de saldo de los jugadores de manera detallada y resumida.</td></tr><tr><td><a href="desfases-puntos-de-venta.md">Dashboard desfases puntos de venta</a></td><td>Permite visualizar y analizar información de los desfaces de saldo de los puntos de venta de manera detallada y resumida.</td></tr></tbody></table>

### 5. Control de versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="98">Versión</th><th width="133">Fecha</th><th width="148">Autor</th><th>Cambios</th></tr></thead><tbody><tr><td>1.0</td><td>25/03/2026</td><td>David Velasquez</td><td>Mejora del manual</td></tr></tbody></table>

</details>
