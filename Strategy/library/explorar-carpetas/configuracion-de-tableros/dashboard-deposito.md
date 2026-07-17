---
description: >-
  Este módulo permite analizar y monitorear el comportamiento de los depósitos
  realizados por los usuarios, a través de un dashboard interactivo en
  MicroStrategy.
---

# Dashboard Depósito

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Dashboard depósitos.

***

### **2. Configuraciones Previas**

Antes de visualizar el reporte, es necesario definir las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/tableros#id-2.-configuracion-previa) obligatorias.

### 3. Visualización

El Dashboard Depósito consolida la información relacionada con las transacciones de depósito realizadas por los usuarios, facilitando el análisis mediante indicadores, gráficos y tablas de detalle.

El dashboard dispone de dos vistas:

* **Moneda Local:** presenta la información en la moneda configurada para el operador.
* **Moneda USD:** muestra la misma información expresada en dólares estadounidenses (USD).

Ambas vistas contienen los mismos filtros, indicadores, gráficos y tablas; únicamente cambia la moneda utilizada para visualizar los valores.

<figure><img src="../../../.gitbook/assets/image (219).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Dashboard depósitos.</p></figcaption></figure>

***

### 3. Acciones del usuario

<table><thead><tr><th width="198">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Consultar Depósitos</code></strong></td><td>Visualiza la información consolidada de los depósitos registrados durante el período seleccionado.</td></tr><tr><td><a href="dashboard-deposito.md#id-3.-acciones-del-usuario"><strong><code>Filtrar información</code></strong></a></td><td>Aplica filtros para consultar información específica dentro del dashboard.</td></tr><tr><td><strong><code>Exportar datos</code></strong></td><td>Descarga los datos del dashboard en formatos <strong>Excel, CSV o PDF</strong>.</td></tr></tbody></table>

### 3. Filtros disponibles

<table><thead><tr><th width="160">Campo</th><th width="137">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Desplegable</td><td>Presenta la información correspondiente al partner seleccionado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Desplegable</td><td>Muestra los registros asociados al país seleccionado.</td></tr><tr><td><strong><code>Año</code></strong></td><td>Desplegable</td><td>Actualiza la información según el año seleccionado.</td></tr><tr><td><strong><code>Mes</code></strong></td><td>Desplegable</td><td>Consulta los registros correspondientes al mes seleccionado.</td></tr><tr><td><strong><code>Día mes</code></strong></td><td>Desplegable</td><td>Filtra por día específico dentro del mes.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Buscador</td><td>Localiza los depósitos realizados por un usuario específico.</td></tr><tr><td><strong><code>Id Depósito</code></strong></td><td>Buscador</td><td>Consulta un depósito mediante su identificador único.</td></tr><tr><td><strong><code>Estado Depósito</code></strong></td><td>Desplegable</td><td>Organiza la información de acuerdo con el estado del depósito.</td></tr><tr><td><strong><code>Medio depósito</code></strong></td><td>Desplegable</td><td>Presenta los depósitos según el canal utilizado para la transacción.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Muestra la información correspondiente al proveedor seleccionado.</td></tr><tr><td><strong><code>Valor depósito</code></strong></td><td>Numérico</td><td>Limita los resultados a un rango específico de valores.</td></tr></tbody></table>

***

### 4. Indicadores KPI’s

<table><thead><tr><th width="160">Nombre del campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor depósito</code></strong></td><td>Valor total de los depósitos registrados durante el período consultado.</td></tr><tr><td><strong><code>Cant. Depósitos</code></strong></td><td>Cantidad total de depósitos registrados.</td></tr><tr><td><strong><code>Promedio Valor</code></strong></td><td>Promedio del valor de depósitos realizados.</td></tr><tr><td><strong><code>Cant. usuarios</code></strong></td><td>Número de usuarios que realizaron al menos un depósito durante el período consultado.</td></tr></tbody></table>

### 5. Gráficas

<table><thead><tr><th width="220">Gráfica</th><th width="151">Tipo de gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Depósitos diarios</code></strong></td><td>Lineal </td><td>Evolución diaria del valor de los depósitos <em>(Eje Y: monto, Eje X: día).</em></td></tr><tr><td><strong><code>Valor depósitos mensual</code></strong></td><td>Barras</td><td>Valor total de los depósitos según el mes correspondiente.</td></tr><tr><td><strong><code>Top % valor pasarela</code></strong></td><td>Torta</td><td>Distribución porcentual del valor depositado por pasarela de pago.</td></tr><tr><td><strong><code>Top % valor punto de venta</code></strong></td><td>Torta</td><td>Distribución porcentual del valor depositado por punto de venta.</td></tr><tr><td><strong><code>Medio de depósitos</code></strong></td><td>Barras</td><td>Compara el valor de los depósitos realizados por pasarela y punto de venta.</td></tr><tr><td><strong><code>Top usuario</code></strong></td><td>Barras</td><td>Presenta el ranking de usuarios con mayor valor depositado durante el período consultado.</td></tr><tr><td><strong><code>Valor promedio depósito por día de la semana</code></strong></td><td>Barras</td><td>Presenta el valor promedio de los depósitos realizados para cada día de la semana.</td></tr><tr><td><strong><code>Cantidad promedio depósito por día de la semana</code></strong></td><td>Barras</td><td>Muestra la cantidad promedio de depósitos realizados para cada día de la semana.</td></tr></tbody></table>

***

### 6. Tablas

* &#x20;**Resumen por usuario**

<table><thead><tr><th width="236">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador del usuario que realizó el depósito.</td></tr><tr><td><strong><code>Valor Depósito</code></strong></td><td>Valor acumulado de los depósitos realizados por el usuario.</td></tr><tr><td><strong><code>Cantidad Depósitos</code></strong></td><td>Número total de depósitos realizados por el usuario.</td></tr><tr><td><strong><code>Promedio Depósito</code></strong></td><td>Valor promedio de los depósitos realizados por el usuario.</td></tr></tbody></table>

***

* &#x20;**Detalle de depósitos**

<table><thead><tr><th width="217">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador del usuario que realizó el depósito.</td></tr><tr><td><strong><code>Id</code></strong></td><td>Identificador único del depósito registrado.</td></tr><tr><td><strong><code>Id final</code></strong></td><td>Identificador generado para la transacción de depósito.</td></tr><tr><td><strong><code>Ip</code></strong></td><td>Dirección IP desde la cual el usuario realizó el depósito.</td></tr><tr><td><strong><code>Id Externo</code></strong></td><td>Identificador asignado por el proveedor.</td></tr><tr><td><strong><code>Fecha Creacion Time</code></strong></td><td>Fecha y hora en que se registró el depósito.</td></tr><tr><td><strong><code>Fecha modificacion Time</code></strong></td><td>Fecha y hora de la última actualización realizada sobre el depósito.</td></tr><tr><td><strong><code>Medio del depósito</code></strong></td><td>Canal mediante el cual se realizó el depósito.</td></tr><tr><td><strong><code>Id Medio Depósito</code></strong></td><td>Identificador del medio de depósito utilizado para la transacción.</td></tr><tr><td><strong><code>Nombre medio del depósito</code></strong></td><td>Nombre del medio utilizado para realizar la transacción.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor del canal de pago.</td></tr><tr><td><strong><code>Estado Depósito</code></strong></td><td>Estado actual del depósito <em>(Ej. Aprobado, rechazado).</em></td></tr><tr><td><strong><code>Valor Depósito</code></strong></td><td>Monto del depósito realizado.</td></tr></tbody></table>

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="99">Versión</th><th width="142">Fecha</th><th width="148">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>02/07/2025</td><td>Ronald Pelaez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>25/11/2025</td><td>Ronald peláez</td><td>Refinamiento manual</td></tr><tr><td>2.0</td><td>17/07/2026</td><td>Karol Navia</td><td>Reestructuración del manual</td></tr></tbody></table>

</details>
