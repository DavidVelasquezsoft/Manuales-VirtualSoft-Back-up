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

# Dashboard - Retail

<mark style="color:$info;">Ofrece una vista analítica del desempeño de la red de puntos de venta físicos de cada partner por país. Presenta métricas principales de registros, FTDs, depósitos y retiros, junto con información sobre concesionarios y puntos de venta, para facilitar el seguimiento de la operación Retail y su comparación frente al total de la operación.</mark>

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Dashboard - Retail.

***

### 2. Configuraciones previas

Antes de ingresar a este tablero, es necesario completar los filtros que se visualizarán durante las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-1.-configuraciones-previas).

***

### 3. Acciones disponibles

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Aplicar filtros</strong></td><td>Aplica los valores seleccionados en las configuraciones previas para consultar la información correspondiente en el tablero.</td></tr><tr><td><strong>Visualizar contenido del tablero</strong></td><td>Visualiza el contenido del tablero, organizado en métricas principales y pestañas de análisis.</td></tr><tr><td><strong>Exportar contenido</strong></td><td>Permite exportar el contenido del tablero. Para más información, consulte la guía de exportación /pages/O0GZK23EHet6KSEIywLs#id-3.-exportar-contenido.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="142">Filtro</th><th width="123">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Partner al cual está asociado el punto de venta.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País en el cual se encuentra el punto de venta.</td></tr><tr><td><strong><code>Año</code></strong></td><td>Lista desplegable</td><td>Año en el cual se realizaron las operaciones consultadas en el tablero.</td></tr><tr><td><strong><code>Mes</code></strong></td><td>Lista desplegable</td><td>Mes en el cual se realizaron las operaciones consultadas en el tablero.</td></tr><tr><td><strong><code>Día</code></strong></td><td>Lista desplegable</td><td>Día en el cual se realizaron las operaciones consultadas en el tablero.</td></tr><tr><td><strong><code>Ciudad PV</code></strong></td><td>Lista desplegable</td><td>Ciudad en la cual se encuentra el punto de venta.</td></tr><tr><td><strong><code>Concesionario</code></strong></td><td>Lista desplegable</td><td>Concesionario asociado a los puntos de venta consultados.</td></tr><tr><td><strong><code>Sub-concesionario 1</code></strong></td><td>Lista desplegable</td><td>Identificador del sub-concesionario 1 asociado a los puntos de venta.</td></tr><tr><td><strong><code>Sub-concesionario 2</code></strong></td><td>Lista desplegable</td><td>Identificador del sub-concesionario 2 asociado a los puntos de venta.</td></tr><tr><td><strong><code>PDV</code></strong></td><td>Lista desplegable</td><td>Nombre del punto de venta.</td></tr></tbody></table>

***

### 5. KPIs

El dashboard presenta un resumen de las principales métricas de la operación Retail y de la cobertura comercial según los filtros aplicados.

#### **5.1. Indicadores de cobertura comercial**

Los indicadores de cobertura muestran la cantidad de concesionarios y puntos de venta incluidos en la selección realizada.

<table><thead><tr><th width="215">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code># Concesionario</code></strong></td><td>Cantidad de concesionarios incluidos según los filtros aplicados.</td></tr><tr><td><strong><code># Puntos de venta</code></strong></td><td>Cantidad de puntos de venta incluidos según los filtros aplicados.</td></tr></tbody></table>

Estos indicadores se actualizan al modificar cualquiera de los filtros del dashboard.

#### **5.2. Indicadores de actividad**

Los indicadores de actividad presentan las principales métricas de la operación Retail. Para cada indicador se muestran tres niveles de información:

* **Retail:** resultado correspondiente al canal Retail según los filtros aplicados.
* **% Total:** porcentaje que representa el resultado de Retail frente al resultado total de la operación.
* **Total:** resultado consolidado de la operación, incluyendo Retail y los demás canales correspondientes.

El porcentaje se calcula tomando el resultado de **Retail** sobre el **Total** de cada indicador. Cuando el valor **Total** es cero, el porcentaje se muestra como **0 %**.

{% hint style="info" %}
**Ejemplo:** En el indicador **`Registros`**, si Retail presenta **90 registros** y el resultado total es de **99 registros**, la participación de Retail corresponde al **90,91 %**.
{% endhint %}

<table><thead><tr><th width="215">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Registros</code></strong></td><td>Cantidad de usuarios registrados según los filtros aplicados.</td></tr><tr><td><strong><code>Cantidad FTDs</code></strong></td><td>Cantidad de usuarios que realizaron su primer depósito (FTD) según los filtros aplicados.</td></tr><tr><td><strong><code>Valor FTD prom</code></strong></td><td>Valor promedio de los primeros depósitos realizados (FTD).</td></tr><tr><td><strong><code>Cantidad depósitos</code></strong></td><td>Cantidad total de operaciones de depósito realizadas.</td></tr><tr><td><strong><code>Valor depósito prom</code></strong></td><td>Valor promedio de las operaciones de depósito realizadas.</td></tr><tr><td><strong><code>Cantidad retiros</code></strong></td><td>Cantidad total de operaciones de retiro realizadas.</td></tr><tr><td><strong><code>Valor retiro prom</code></strong></td><td>Valor promedio de las operaciones de retiro realizadas.</td></tr></tbody></table>

Los valores de esta sección se actualizan de forma conjunta al modificar uno o varios filtros, manteniendo la correspondencia entre la información de Retail, su porcentaje de participación y el total de la operación.

***

### 6. Contenido del dashboard

El dashboard se compone de tres pestañas que permiten analizar la información de la red de puntos de venta desde diferentes perspectivas:

* **Ciudad y concesionario:** análisis de registros y FTDs por ciudad y concesionario, además de la evolución de las principales operaciones a través del tiempo.
* **Top PV y detalle:** identificación de los puntos de venta con mayor participación en depósitos, retiros, registros y FTDs, junto con el detalle de sus principales indicadores.
* **Distribución por ciudad:** análisis de la relación entre cantidades y valores de las principales operaciones según la ciudad.

{% tabs %}
{% tab title="Ciudad y concesionario" %}
Presenta información sobre el comportamiento de los registros y FTDs según la ciudad y el concesionario, así como la evolución de las principales operaciones a través del tiempo.

#### **Visualización**

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FNRmWzABt0aFrODjiAhYa%2Fimage.png?alt=media&#x26;token=87ddd451-0716-4bab-8dce-ccbd70cfdcfe" alt=""><figcaption><p>Figura #1: Captura de pantalla pestaña Ciudad y concesionario.</p></figcaption></figure>

<table><thead><tr><th width="192">Gráfico</th><th width="122">Tipo de gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad de registros y FTDs a través del tiempo</code></strong></td><td>Lineal</td><td>Muestra la evolución de la cantidad de registros y FTDs durante el periodo seleccionado.</td></tr><tr><td><strong><code>Cantidad registros por ciudad - top 10</code></strong></td><td>Torta</td><td>Muestra la distribución de los registros entre las diez ciudades con mayor cantidad de registros.</td></tr><tr><td><strong><code>Cantidad FTDs por ciudad - top 10</code></strong></td><td>Torta</td><td>Muestra la distribución de los FTDs entre las diez ciudades con mayor cantidad de FTDs.</td></tr><tr><td><strong><code>Cantidad registros por concesionario - top 10</code></strong></td><td>Torta</td><td>Muestra la distribución de los registros entre los diez concesionarios con mayor cantidad de registros.</td></tr><tr><td><strong><code>Cantidad FTDs por concesionario - top 10</code></strong></td><td>Torta</td><td>Muestra la distribución de los FTDs entre los diez concesionarios con mayor cantidad de FTDs.</td></tr></tbody></table>

**Tabla mapa de calor por cantidades**

Presenta las cantidades de las principales operaciones distribuidas por día.

<table><thead><tr><th width="168">Fila</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Registros</code></strong></td><td>Cantidad de registros correspondientes a cada día.</td></tr><tr><td><strong><code>FTDs</code></strong></td><td>Cantidad de usuarios que realizaron su primer depósito correspondiente a cada día.</td></tr><tr><td><strong><code>Depósitos</code></strong></td><td>Cantidad de operaciones de depósito correspondientes a cada día.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Cantidad de operaciones de retiro correspondientes a cada día.</td></tr></tbody></table>
{% endtab %}

{% tab title="Top PV y detalle" %}
Presenta los puntos de venta con mayor participación en las principales métricas de la operación y proporciona el detalle de sus indicadores.

### **Visualización**

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FR2fabknxlZZaB26a4xtj%2Fimage.png?alt=media&#x26;token=bfa2047c-ceae-4d92-b194-4f16d018a123" alt=""><figcaption><p>Figura #2: Captura de pantalla pestaña Top PV y detalle.</p></figcaption></figure>

<table><thead><tr><th width="171">Gráfico</th><th width="135">Tipo de gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Top 10 PV - valor depósitos</code></strong></td><td>Barras</td><td>Muestra los diez puntos de venta con mayor valor de depósitos.</td></tr><tr><td><strong><code>Top 10 PV - valor retiros</code></strong></td><td>Barras</td><td>Muestra los diez puntos de venta con mayor valor de retiros.</td></tr><tr><td><strong><code>Top 10 PV - cantidad registros</code></strong></td><td>Barras</td><td>Muestra los diez puntos de venta con mayor cantidad de registros.</td></tr><tr><td><strong><code>Top 10 PV - valor FTDs</code></strong></td><td>Barras</td><td>Muestra los diez puntos de venta con mayor valor de FTDs.</td></tr></tbody></table>

**Tabla detalle**

Presenta información detallada de los puntos de venta y sus principales indicadores de depósitos, retiros, registros y FTDs.

<table><thead><tr><th width="210">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID PDV</code></strong></td><td>Identificador único del punto de venta.</td></tr><tr><td><strong><code>Nombre PDV</code></strong></td><td>Nombre del punto de venta.</td></tr><tr><td><strong><code>Id concesionario</code></strong></td><td>Identificador del concesionario asociado al punto de venta.</td></tr><tr><td><strong><code>Nombre concesionario</code></strong></td><td>Nombre del concesionario asociado al punto de venta.</td></tr><tr><td><strong><code>Ciudad PDV</code></strong></td><td>Ciudad en la cual se encuentra el punto de venta.</td></tr><tr><td><strong><code>Cantidad depósitos</code></strong></td><td>Cantidad de operaciones de depósito realizadas en el punto de venta.</td></tr><tr><td><strong><code>Valor total depósitos</code></strong></td><td>Valor acumulado de los depósitos realizados en el punto de venta.</td></tr><tr><td><strong><code>Depósitos promedio</code></strong></td><td>Valor promedio de los depósitos realizados en el punto de venta.</td></tr><tr><td><strong><code>Cantidad retiros</code></strong></td><td>Cantidad de operaciones de retiro realizadas en el punto de venta.</td></tr><tr><td><strong><code>Valor total retiros</code></strong></td><td>Valor acumulado de los retiros realizados en el punto de venta.</td></tr><tr><td><strong><code>Retiro promedio</code></strong></td><td>Valor promedio de los retiros realizados en el punto de venta.</td></tr><tr><td><strong><code>Registros</code></strong></td><td>Cantidad de usuarios registrados asociados al punto de venta.</td></tr><tr><td><strong><code>FTD</code></strong></td><td>Cantidad de usuarios que realizaron su primer depósito asociados al punto de venta.</td></tr><tr><td><strong><code>Valor FTD promedio</code></strong></td><td>Valor promedio de los primeros depósitos realizados asociados al punto de venta.</td></tr></tbody></table>
{% endtab %}

{% tab title="Distribución por ciudad" %}
Presenta la relación entre las cantidades y los valores de las principales operaciones según la ciudad del punto de venta.

#### **Visualización**

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FWVdFeNVQWiLmR2VmNrGp%2Fimage.png?alt=media&#x26;token=ef9a647b-431d-4cbc-b91d-989d865ac68f" alt=""><figcaption><p>Figura #3: Captura de pantalla pestaña Distribución por ciudad.</p></figcaption></figure>

<table><thead><tr><th width="219">Gráfico</th><th width="126">Tipo de gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Relación entre cantidad y valor de depósitos por ciudad</code></strong></td><td>Lineal</td><td>Compara la cantidad de operaciones y el valor de los depósitos según la ciudad.</td></tr><tr><td><strong><code>Relación entre cantidad y valor de retiros por ciudad</code></strong></td><td>Lineal</td><td>Compara la cantidad de operaciones y el valor de los retiros según la ciudad.</td></tr><tr><td><strong><code>Relación entre cantidad de registros y valor FTD por ciudad</code></strong></td><td>Lineal</td><td>Compara la cantidad de registros y el valor de los FTDs según la ciudad.</td></tr><tr><td><strong><code>Relación entre cantidad y valor FTDs por ciudad</code></strong></td><td>Lineal</td><td>Presenta la relación entre las cantidades y los valores de FTDs según la ciudad.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 7. Consideraciones de la información

* Los indicadores y visualizaciones se actualizan de acuerdo con los filtros seleccionados en el dashboard.
* Todos los valores mostrados corresponden a la misma selección de filtros.
* Las métricas principales presentan la información de Retail, su participación porcentual frente al total y el resultado consolidado de la operación.
* Cuando una métrica no presenta resultados para la selección realizada, el valor se muestra como **0**.
* Las cantidades se presentan como números enteros, los valores monetarios utilizan el formato de moneda definido para el dashboard y los porcentajes incluyen el símbolo **%**.
* La información presentada en las métricas principales mantiene correspondencia con la información utilizada en los gráficos, rankings y tablas de detalle del dashboard.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="94.7037353515625">Versión</th><th width="133.25927734375">Fecha</th><th width="161.77777099609375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>05/10/2026</td><td>Ronald Peláez</td><td>Documento inicial.</td></tr></tbody></table>

</details>
