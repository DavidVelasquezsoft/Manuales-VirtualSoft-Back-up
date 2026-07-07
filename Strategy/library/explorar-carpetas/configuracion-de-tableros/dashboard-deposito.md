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

### 2. 🖼️Visualización

<figure><img src="../../../.gitbook/assets/image (32) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Dashboard depósitos.</p></figcaption></figure>

***

### 3. Acciones del usuario

<table><thead><tr><th width="245">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Consultar Depósitos</code></strong></td><td>Ver el historial de retiros creados, aprobados y pagados dentro de un rango de fechas.</td></tr><tr><td><strong><code>Filtrar información</code></strong></td><td>Aplicar filtros para obtener información más detallada en el dashboard.</td></tr><tr><td><strong><code>Exportar datos</code></strong></td><td>Descargar la información en formatos <em>(Excel, CSV, PDF).</em></td></tr></tbody></table>

#### 3.1. Filtros disponibles

<table><thead><tr><th width="155">Campo</th><th width="137">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Desplegable</td><td>Muestra datos del partner seleccionado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Desplegable</td><td>Muestra datos del país seleccionado.</td></tr><tr><td><strong><code>Año</code></strong></td><td>Desplegable</td><td>Filtra datos según el año seleccionado.</td></tr><tr><td><strong><code>Mes</code></strong></td><td>Desplegable</td><td>Muestra datos del mes seleccionado.</td></tr><tr><td><strong><code>Día mes</code></strong></td><td>Desplegable</td><td>Filtra por día específico dentro del mes.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Buscador</td><td>Filtra el dashboard por el usuario que realzó el depósito.</td></tr><tr><td><strong><code>Id Depósito</code></strong></td><td>Buscador</td><td>Filtra del dashboard por el depósito realizado.</td></tr><tr><td><strong><code>Estado Depósito</code></strong></td><td>Desplegable</td><td>Filtra por el estado del depósito.</td></tr><tr><td><strong><code>Medio depósito</code></strong></td><td>Desplegable</td><td>Visualiza información en el dashboard según medio por el cual se realizó el depósito.</td></tr></tbody></table>

***

#### 3.2. Indicadores KPI’s

<table><thead><tr><th width="209">Nombre del campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor depósito</code></strong></td><td>Visualiza el total de todos los depósitos realizados.</td></tr><tr><td><strong><code>Cant. Depósitos</code></strong></td><td>Número total de depósitos registrados.</td></tr><tr><td><strong><code>Promedio Valor</code></strong></td><td>Promedio del valor de depósitos realizados.</td></tr><tr><td><strong><code>Cant. usuarios</code></strong></td><td>Número de usuarios que realizaron depósitos.</td></tr></tbody></table>

#### 3.3. Gráficas

<table><thead><tr><th width="220">Gráfica</th><th width="143">Tipo de gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Depósitos diarios</code></strong></td><td>Líneal</td><td>Evolución diaria del valor de los depósitos <em>(Eje Y: monto, Eje X: día).</em></td></tr><tr><td><strong><code>Valor depósitos mensual</code></strong></td><td>Barras</td><td>Valor total de los depósitos según el mes correspondiente.</td></tr><tr><td><strong><code>Top % valor pasarela</code></strong></td><td>Torta</td><td>Participación porcentual de pasarelas por monto.</td></tr><tr><td><strong><code>Top % valor punto de venta</code></strong></td><td>Torta</td><td>Participación porcentual de puntos de venta por monto.</td></tr><tr><td><strong><code>Medio de depósitos</code></strong></td><td>Barras</td><td>Comparativo mensual pasarela vs punto de venta.</td></tr><tr><td><strong><code>Top usuario</code></strong></td><td>Barras</td><td>Ranking de usuarios con mayor monto depositado <em>(Descendente).</em></td></tr></tbody></table>

***

#### 3.5 Tablas

**3.5.1 Resumen por usuario**

<table><thead><tr><th width="236">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador del usuario que realizó el depósito.</td></tr><tr><td><strong><code>Valor Depósito</code></strong></td><td>Suma total de depósitos realizados por el usuario.</td></tr><tr><td><strong><code>Cantidad Depósitos</code></strong></td><td>Número total de depósitos realizados por el usuario.</td></tr><tr><td><strong><code>Promedio Depósito</code></strong></td><td>Promedio de los depósitos realizados por el usuario.</td></tr></tbody></table>

***

**3.5.2 Detalle de depósitos**

<table><thead><tr><th width="240">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador del usuario que realizó el depósito.</td></tr><tr><td><strong><code>Id Depósito</code></strong></td><td>Identificador único del depósito registrado.</td></tr><tr><td><strong><code>Id Externo</code></strong></td><td>Referencia externa de la transacción.</td></tr><tr><td><strong><code>Fecha Time</code></strong></td><td>Fecha del depósito <em>(formato: dd/mm/aaaa).</em></td></tr><tr><td><strong><code>Medio del depósito</code></strong></td><td>Canal utilizado para realizar el depósito.</td></tr><tr><td><strong><code>Nombre medio del depósito</code></strong></td><td>Nombre del canal usado para el depósito.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor del canal de pago.</td></tr><tr><td><strong><code>Estado Depósito</code></strong></td><td>Estado actual del depósito <em>(Ej. Aprobado, rechazado).</em></td></tr><tr><td><strong><code>Valor Depósito</code></strong></td><td>Monto del depósito realizado.</td></tr></tbody></table>

***

### 🕒 4. Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados  |
| ------- | ---------- | ------------- | ------------------- |
| 1.0     | 02/07/2025 | Ronald Pelaez | Documento inicial   |
| 1.1     | 25/11/2025 | Ronald peláez | Refinamiento manual |
