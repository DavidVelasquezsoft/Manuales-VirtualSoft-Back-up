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

# Dashboard Retiros

<mark style="color:$info;">El Dashboard de Retiros presenta información analítica relacionada con las transacciones de retiro realizadas por los usuarios. La información se organiza mediante indicadores, gráficos y tablas que facilitan el análisis del comportamiento de los retiros.</mark>

### 1. Acceso al módulo

**Ruta:** Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Dashboard Retiros

***

### 2. Visualización:

Este dashboard cuenta con dos vistas: **Moneda Local** y **Moneda USD**. Ambas presentan la misma estructura, componentes y funcionalidades; la única diferencia es la moneda en la que se visualiza la información. En la vista **Moneda Local**, los valores se muestran en la moneda local configurada para el operador, mientras que en la vista **Moneda USD**, los mismos datos se presentan en dólares estadounidenses (USD).

<figure><img src="../../../.gitbook/assets/image (218).png" alt=""><figcaption><p>Figura #1: Captura de pantalla dashboard retiro.</p></figcaption></figure>

### 3. Acciones del usuario

<table><thead><tr><th width="245">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Consultar retiros</code></strong></td><td>Ver el historial de retiros creados, aprobados y pagados dentro de un rango de fechas.</td></tr><tr><td><strong><code>Filtrar información</code></strong></td><td>Aplicar filtros como mandante, país, estado, medio de pago, nivel de riesgo y tipo de aprobación.</td></tr><tr><td><strong><code>Ver detalles</code></strong></td><td>Acceder a tablas con detalle de retiros individuales y resumen por usuario.</td></tr><tr><td><strong><code>Exportar datos</code></strong></td><td>Descargar la información en formatos <em>(Excel, CSV, PDF).</em></td></tr></tbody></table>

### 4. Filtros disponibles

<table><thead><tr><th width="195">Filtro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Partner sobre el cual se desea consultar los retiros <em>(ej. Doradobet).</em></td></tr><tr><td><strong><code>País</code></strong></td><td>País desde donde se realizó el retiro.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del retiro <em>(Pagado, Pendiente, Rechazado, etc.)</em>.</td></tr><tr><td><strong><code>Medio de Pago</code></strong></td><td>Método utilizado para realizar el retiro <em>(Punto de Venta, físicamente.).</em></td></tr><tr><td><strong><code>Nivel de Riesgo</code></strong></td><td>Clasificación de riesgo de la transacción <em>(Bajo, Medio, Alto)</em>.</td></tr><tr><td><strong><code>Tipo de Aprobación</code></strong></td><td>Modo en que se aprobó el retiro <em>(Automático o Manual).</em></td></tr><tr><td><strong><code>Id usuario</code></strong></td><td>Identificador del usuario, asignado automáticamente por el sistema.</td></tr><tr><td><strong><code>Id Retiro</code></strong></td><td>Identificador del retiro, asignado automáticamente por el sistema.</td></tr><tr><td><strong><code>Canal</code></strong></td><td>Filtrar por el nombre del canal utilizado en la realización del retiro.</td></tr><tr><td><strong><code>Fecha Pago</code></strong></td><td>Rango de fechas en que se efectuó el pago al usuario.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto del retiro que se realizó.</td></tr></tbody></table>

***

### 5. KPIs

<table><thead><tr><th width="202">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad Retiros</code></strong></td><td>Número total de solicitudes de retiro generadas en el período filtrado.</td></tr><tr><td><strong><code>Valor Retiros</code></strong></td><td>Suma total de los retiros creados.</td></tr><tr><td><strong><code>Promedio Retiro</code></strong></td><td>Valor promedio por cada retiro.</td></tr><tr><td><strong><code>Cantidad de Usuarios</code></strong></td><td>Número de usuarios únicos que realizaron retiros.</td></tr><tr><td><strong><code>Valor Punto de Venta</code></strong></td><td>Monto total retirado a través de puntos de venta físicos.</td></tr><tr><td><strong><code>Valor Sistema</code></strong></td><td>Monto total retirado a través del sistema en general <em>(incluye todos los medios)</em>.</td></tr></tbody></table>

***

### **6. Clasificación de gráficos:**

Los gráficos se visualizan de manera general, y también agrupados en gráficos por los retiros

* **Gráficos de barras generales.**

<table><thead><tr><th width="222">Gráfico</th><th width="121">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor retiros por medio</code></strong></td><td>Gráfica de barras</td><td>Muestra, mediante barras, el valor total retirado agrupado por cada medio de pago utilizado.</td></tr><tr><td><strong><code>Valor retiros diarios</code></strong></td><td>Gráfica de barras</td><td>Presenta el valor total de retiros realizado por día del mes, permitiendo identificar picos diarios.</td></tr><tr><td><strong><code>Top 100 usuarios con mayor valor retiros</code></strong></td><td>Gráfica de barras</td><td>Visualiza en barras a los 100 usuarios que registran el mayor valor acumulado en retiros.</td></tr><tr><td><strong><code>Retiros por mes</code></strong></td><td>Gráfica de barras</td><td>Muestra la cantidad total o el valor de retiros agrupados por mes, facilitando una vista comparativa mensual.</td></tr><tr><td><strong><code>Tipo de aprobación por fecha de aprobación</code></strong></td><td>Gráfica de líneas</td><td>Visualiza la distribución de los tipos de aprobación según las fechas procesadas.</td></tr><tr><td><strong><code>Valor promedio retiros por día de la semana</code></strong></td><td>Gráfica de barras</td><td>Representa el valor promedio retirado para cada día de la semana, ayudando a identificar patrones recurrentes.</td></tr><tr><td><strong><code>Cantidad promedio retiros por día de la semana</code></strong></td><td>Gráfica de barras</td><td>Muestra el número promedio de retiros realizados en cada día de la semana.</td></tr></tbody></table>

* **Top 10 retiros por medio.**

<table><thead><tr><th width="193">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Bancos</code></strong></td><td>Muestra el Top 10 de los bancos por los cuales se han realizado la mayor cantidad de retiros.</td></tr><tr><td><strong><code>PDV´S</code></strong></td><td>Presenta el Top 10 de puntos de venta con mayor volumen de retiros procesados.</td></tr><tr><td><strong><code>Pasarelas</code></strong></td><td>Visualiza el Top 10 de pasarelas de pago utilizadas para realizar retiros.</td></tr><tr><td><strong><code>N° Retiros por tipo aprobación</code></strong></td><td>Indica la cantidad de retiros procesados según cada tipo de aprobación.</td></tr><tr><td><strong><code>N° Retiros por tipo aprobación</code></strong></td><td>Muestra la distribución del número de retiros según el tipo de aprobación utilizado <em>(Automático y Manual)</em>.</td></tr></tbody></table>

***

### 7.  Tablas

* **Tabla resumen x tipo aprobación**

<table><thead><tr><th width="180">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del operador o casa de apuestas al que pertenece el retiro.</td></tr><tr><td><strong><code>País</code></strong></td><td>País desde el cual se realizó o procesó el retiro.</td></tr><tr><td><strong><code>Tipo Aprobación</code></strong></td><td>Tipo de aprobación asignado al retiro <em>(ej. automática, manual).</em></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del retiro según su proceso de aprobación.</td></tr><tr><td><strong><code>Nro Retiro</code></strong></td><td>Número total de retiros asociados a ese tipo de aprobación.</td></tr></tbody></table>

* **Tabla Detalle de Retiros**

<table><thead><tr><th width="201">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del operador.</td></tr><tr><td><strong><code>País</code></strong></td><td>País de origen de la transacción.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha del registro de la transacción.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario que realizó el retiro.</td></tr><tr><td><strong><code>ID Retiro</code></strong></td><td>Identificador único de la solicitud de retiro.</td></tr><tr><td><strong><code>Ip</code></strong></td><td>Identificador único del dispositivo desde el cual se realizó el retiro.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del retiro <em>(Pagado, Pendiente, etc.).</em></td></tr><tr><td><strong><code>Fecha aprobación</code></strong></td><td>Fecha en la que se aprobó el retiro.</td></tr><tr><td><strong><code>Fecha Creación</code></strong> </td><td>Fecha en que se creó la solicitud de retiro.</td></tr><tr><td><strong><code>Fecha Pago</code></strong></td><td>Fecha en que se efectuó el pago.</td></tr><tr><td><strong><code>Medio de Pago</code></strong></td><td>Medio por el cual se pagó el retiro <em>(Ej: Físicamente).</em></td></tr><tr><td><strong><code>Canal</code></strong></td><td>Canal a través del cual se realizó el retiro.</td></tr><tr><td><strong><code>Nivel de Riesgo</code></strong></td><td>Clasificación de riesgo de la transacción.</td></tr><tr><td><strong><code>Operador de Cambio</code></strong></td><td>Usuario o sistema que realizó un cambio en el retiro.</td></tr><tr><td><strong><code>Operador de Pago</code></strong></td><td>Usuario que procesó el pago.</td></tr><tr><td><strong><code>Operador de Rechazo</code></strong></td><td>Nombre o correo del usuario que rechazó el retiro.</td></tr><tr><td><strong><code>Tipo Aprobación</code></strong> </td><td>Tipo de aprobación original <em>(Manual o Automático).</em></td></tr><tr><td><strong><code>Valor</code></strong> </td><td>Monto del retiro que se realizó.</td></tr></tbody></table>

***

### 8. Validaciones y Reglas de Negocio

* Cada [card ](https://virtualsoft.gitbook.io/untitled/glosario/#card)es exportable en diferentes formatos.
* Las fechas deben seleccionarse dentro de un rango válido para obtener resultados.
* Las gráficas muestran siempre la información activa: si aplicas filtros, muestran lo filtrado; si seleccionas un dato en una tabla, se actualizan según esa selección.

***

### 9. Control de Versiones

<details>

<summary>🔽Historial de versiones </summary>

<table><thead><tr><th width="99">Versión</th><th width="116">Fecha</th><th width="133">Autor</th><th>Descripción</th></tr></thead><tbody><tr><td>1.0</td><td>13/08/2025</td><td>Karol Navia</td><td>Creación del documento inicial.</td></tr><tr><td>1.1</td><td>10/10/2025</td><td>Karol Navia</td><td>Actualización de nuevos campos</td></tr><tr><td>1.2</td><td>24/11/2025</td><td>Ronald Pelaez</td><td>Refinamiento de manual</td></tr><tr><td>2.0</td><td>17/07/2026</td><td>Karol Navia</td><td>Reestructuración del manual</td></tr></tbody></table>

</details>
