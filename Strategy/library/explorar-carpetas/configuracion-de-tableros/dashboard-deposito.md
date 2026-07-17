---
description: >-
  Este módulo permite analizar y monitorear el comportamiento de los depósitos
  realizados por los usuarios, a través de un dashboard interactivo en
  MicroStrategy.
---

# Dashboard Depósito

## Dashboard Depósito

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft / Informes compartidos / Datas TI / Deposito

***

### 2. Visualización

Este dashboard cuenta con dos vistas: **Moneda Local** y **Moneda USD**. Ambas presentan la misma estructura, componentes y funcionalidades; la única diferencia es la moneda en la que se visualiza la información. En la vista **Moneda Local**, los valores se muestran en la moneda local configurada para el operador, mientras que en la vista **Moneda USD**, los mismos datos se presentan en dólares estadounidenses (USD).

<figure><img src="../../../.gitbook/assets/image (32).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Dashboard depósitos.</p></figcaption></figure>

***

### 3. Acciones del usuario

<table><thead><tr><th width="245">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Consultar Depósitos</code></strong></td><td>Ver el historial de retiros creados, aprobados y pagados dentro de un rango de fechas.</td></tr><tr><td><strong><code>Filtrar información</code></strong></td><td>Aplicar filtros para obtener información más detallada en el dashboard.</td></tr><tr><td><strong><code>Exportar datos</code></strong></td><td>Descargar la información en formatos <em>(Excel, CSV, PDF).</em></td></tr></tbody></table>

### 3. Filtros disponibles

<table><thead><tr><th width="155">Campo</th><th width="137">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Desplegable</td><td>Muestra datos del partner seleccionado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Desplegable</td><td>Muestra datos del país seleccionado.</td></tr><tr><td><strong><code>Año</code></strong></td><td>Desplegable</td><td>Filtra datos según el año seleccionado.</td></tr><tr><td><strong><code>Mes</code></strong></td><td>Desplegable</td><td>Muestra datos del mes seleccionado.</td></tr><tr><td><strong><code>Día mes</code></strong></td><td>Desplegable</td><td>Filtra por día específico dentro del mes.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Buscador</td><td>Filtra el dashboard por el usuario que realzó el depósito.</td></tr><tr><td><strong><code>Id Depósito</code></strong></td><td>Buscador</td><td>Filtra del dashboard por el depósito realizado.</td></tr><tr><td><strong><code>Estado Depósito</code></strong></td><td>Desplegable</td><td>Filtra por el estado del depósito.</td></tr><tr><td><strong><code>Medio depósito</code></strong></td><td>Desplegable</td><td>Visualiza información en el dashboard según medio por el cual se realizó el depósito.</td></tr><tr><td>Proveedor</td><td></td><td></td></tr><tr><td>Valor deposito</td><td></td><td></td></tr></tbody></table>

***

### 4. Indicadores KPI’s

<table><thead><tr><th width="209">Nombre del campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor depósito</code></strong></td><td>Visualiza el total de todos los depósitos realizados.</td></tr><tr><td><strong><code>Cant. Depósitos</code></strong></td><td>Número total de depósitos registrados.</td></tr><tr><td><strong><code>Promedio Valor</code></strong></td><td>Promedio del valor de depósitos realizados.</td></tr><tr><td><strong><code>Cant. usuarios</code></strong></td><td>Número de usuarios que realizaron depósitos.</td></tr></tbody></table>

### 5. Gráficas

<table><thead><tr><th width="220">Gráfica</th><th width="143">Tipo de gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Depósitos diarios</code></strong></td><td>Lineal </td><td>Evolución diaria del valor de los depósitos <em>(Eje Y: monto, Eje X: día).</em></td></tr><tr><td><strong><code>Valor depósitos mensual</code></strong></td><td>Barras</td><td>Valor total de los depósitos según el mes correspondiente.</td></tr><tr><td><strong><code>Top % valor pasarela</code></strong></td><td>Torta</td><td>Participación porcentual de pasarelas por monto.</td></tr><tr><td><strong><code>Top % valor punto de venta</code></strong></td><td>Torta</td><td>Participación porcentual de puntos de venta por monto.</td></tr><tr><td><strong><code>Medio de depósitos</code></strong></td><td>Barras</td><td>Comparativo mensual pasarela vs punto de venta.</td></tr><tr><td><strong><code>Top usuario</code></strong></td><td>Barras</td><td>Ranking de usuarios con mayor monto depositado <em>(Descendente).</em></td></tr></tbody></table>

***

### 6. Tablas

* &#x20;**Resumen por usuario**

<table><thead><tr><th width="236">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador del usuario que realizó el depósito.</td></tr><tr><td><strong><code>Valor Depósito</code></strong></td><td>Suma total de depósitos realizados por el usuario.</td></tr><tr><td><strong><code>Cantidad Depósitos</code></strong></td><td>Número total de depósitos realizados por el usuario.</td></tr><tr><td><strong><code>Promedio Depósito</code></strong></td><td>Promedio de los depósitos realizados por el usuario.</td></tr></tbody></table>

***

* &#x20;**Detalle de depósitos**

<table><thead><tr><th width="240">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador del usuario que realizó el depósito.</td></tr><tr><td><strong><code>Id Depósito</code></strong></td><td>Identificador único del depósito registrado.</td></tr><tr><td><strong><code>Id Externo</code></strong></td><td>Referencia externa de la transacción.</td></tr><tr><td><strong><code>Fecha Time</code></strong></td><td>Fecha del depósito <em>(formato: dd/mm/aaaa).</em></td></tr><tr><td><strong><code>Medio del depósito</code></strong></td><td>Canal utilizado para realizar el depósito.</td></tr><tr><td><strong><code>Nombre medio del depósito</code></strong></td><td>Nombre del canal usado para el depósito.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor del canal de pago.</td></tr><tr><td><strong><code>Estado Depósito</code></strong></td><td>Estado actual del depósito <em>(Ej. Aprobado, rechazado).</em></td></tr><tr><td><strong><code>Valor Depósito</code></strong></td><td>Monto del depósito realizado.</td></tr></tbody></table>

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="99">Versión</th><th width="142">Fecha</th><th width="148">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>02/07/2025</td><td>Ronald Pelaez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>25/11/2025</td><td>Ronald peláez</td><td>Refinamiento manual</td></tr><tr><td>2.0</td><td>17/07/2026</td><td>Karol Navia</td><td>Reestructuración del manual</td></tr></tbody></table>

</details>
