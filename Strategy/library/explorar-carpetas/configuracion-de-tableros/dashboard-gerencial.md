---
description: >-
  Este panel fue creado para ayudarte a entender mejor cómo se está comportando
  tu operación en las verticales de deportes, casino, depósitos y retiros.
---

# Dashboard gerencial

### 1. Acceso al Módulo

**Ruta de acceso**: [Acceso directo](https://reporting.virtualsoft.tech/MicroStrategyLibrary/app/3394329B42569ED3E0CDD1AABE6F7740/A0D3E7A04E96AFEB23144EBA5DB1C7E0/W1CBBA35787CE4A56994A98AED880F24A--K46?continue).

***

### 2. Configuraciones previas

Antes de visualizar el reporte, es necesario confirmar las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/tableros#id-2.-configuracion-previa).

***

### 3. 🖼️ Visualización general

<figure><img src="../../../.gitbook/assets/image (116).png" alt=""><figcaption><p>Figura #1 Captura de pantalla Dashboard gerencial.</p></figcaption></figure>

***

### 4. KPI’s Principales

Los KPI’s principales se encuentran en la parte superior del dashboard. Estos representan el comportamiento general del negocio y son los indicadores base para el análisis.

#### 4.1 KPI’s principales

<table><thead><tr><th width="217">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Registros</code></strong></td><td>Total de usuarios registrados en el periodo seleccionado.</td></tr><tr><td><strong><code>CantFtds (FTDs)</code></strong></td><td>Cantidad de usuarios que realizaron su primer depósito.</td></tr><tr><td><strong><code>Valor FTD</code></strong></td><td>Monto total depositado por los FTDs.</td></tr><tr><td><strong><code>Tasa de Conversión</code></strong></td><td>Porcentaje de leads que se convierten en FTDs. Fórmula: <em>(CantFtds / Registros) * 100.</em></td></tr></tbody></table>

#### 4.2. KPI’s Deportivas

Los KPI’s deportivos representan la actividad de apuestas deportivas dentro de la plataforma.

<table><thead><tr><th width="183">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>CantCreated</code></strong></td><td>Total de apuestas deportivas creadas.</td></tr><tr><td><strong><code>APCreated</code></strong></td><td>Monto total apostado en apuestas creadas.</td></tr><tr><td><strong><code>WinCreated</code></strong></td><td>Monto total pagado en premios de apuestas creadas.</td></tr><tr><td><strong><code>CantClosed</code></strong></td><td>Total de apuestas cerradas.</td></tr><tr><td><strong><code>APClosed</code></strong></td><td>Monto total apostado en apuestas cerradas.</td></tr><tr><td><strong><code>WinClosed</code></strong></td><td>Total pagado en apuestas cerradas.</td></tr><tr><td><strong><code>BonusSP</code></strong></td><td>Total de bonos aplicados en la vertical deportiva.</td></tr><tr><td><strong><code>GGR Deportiva</code></strong></td><td>Ganancia bruta: <em>(APClosed − WinClosed − BonusSP).</em></td></tr></tbody></table>

***

#### 4.3. KPI’s Casino

Los KPI’s del casino representan la actividad de juegos virtuales y juegos de slot.

<table><thead><tr><th width="174">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>CantSpin</code></strong></td><td>Total de jugadas/spins realizadas.</td></tr><tr><td><strong><code>APCasino</code></strong></td><td>Monto total apostado en casino.</td></tr><tr><td><strong><code>PrCasino</code></strong></td><td>Total pagado en premios del casino.</td></tr><tr><td><strong><code>PrBonus</code></strong></td><td>Total entregado en premios provenientes de bonos.</td></tr><tr><td><strong><code>BonosCasino</code></strong></td><td>Total de bonos aplicados en casino.</td></tr><tr><td><strong><code>GGR Casino</code></strong></td><td>Ganancia bruta del casino: <em>(APCasino − PrCasino − PrBonus − BonosCasino)</em>.</td></tr></tbody></table>

***

### 5. Tablas

El dashboard contiene tablas que ayudan a obtener información más detallada tanto de casino como de deportivas.

#### 5.1. Tablas solo de vertical deportivas.

<table><thead><tr><th width="149">Tabla</th><th>Descripción </th></tr></thead><tbody><tr><td><strong><code>GGR deportiva</code></strong></td><td>Permite analizar el comportamiento de las ganancias butas <em>(GGR)</em> en la semana</td></tr><tr><td><strong><code>AP Closed</code></strong></td><td>Permite analizar el comportamiento de las apuestas deportivas cerradas en la semana</td></tr></tbody></table>

#### 5.2. Tablas solo de vertical Casino

<table><thead><tr><th width="149">Tabla</th><th>Descripción </th></tr></thead><tbody><tr><td><strong><code>GGR Casino</code></strong></td><td>Permite analizar el comportamiento de las ganancias butas <em>(GGR)</em> en la semana</td></tr><tr><td><strong><code>AP Casino</code></strong></td><td>Permite analizar el comportamiento de las apuestas deportivas cerradas en la semana</td></tr></tbody></table>

#### 5.3. Tablas generales.

Estas tablas contienen información general, sobre el comportamiento financiero con el partner.

<table><thead><tr><th width="125">Tabla</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Depósitos</code></strong></td><td>Permite analizar el comportamiento de los depósitos realizados en la semana.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Permite analizar el comportamiento de los retiros realizados en la semana.</td></tr><tr><td>Detalle GGR por verticales</td><td>Permite visualizar información sobre las ganancias brutas obtenidas de manera más detallada de las verticales Casino y deportivas.</td></tr><tr><td><strong><code>Detalle apuestas por verticales</code></strong></td><td>Permite visualizar información de manera detallada sobre las apuestas realizadas en las verticales Casino y Deportivas.</td></tr><tr><td>Detalle depósito y retiros</td><td>Permite visualizar información de manera detallada sobre los depósitos y retiros realizados en la plataforma.</td></tr></tbody></table>

***

### 6. Gráficas de Barras

<table><thead><tr><th width="305">Nombre de la gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>GGR Deportiva vs GGR Casino (Mensual)</code></strong></td><td>Comparación directa de la ganancia bruta por vertical.</td></tr><tr><td><strong><code>AP Closed vs AP Casino (Mensual)</code></strong></td><td>Compara el volumen apostado entre deportivas y casino.</td></tr><tr><td><strong><code>Depósitos vs Retiros</code></strong></td><td>Contrasta los montos depositados y retirados.</td></tr></tbody></table>

***

### 7. Gráficas Lineales

<table><thead><tr><th width="266">Nombre de la gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Apuesta: Deportiva (Cerrada) vs casino x día</code></strong></td><td>Compara diariamente el total apostado en apuestas deportivas cerradas frente al total apostado en casino, mostrando cómo varía la actividad entre ambas verticales.</td></tr><tr><td><strong><code>GGR: Deportiva vs Casino x día</code></strong></td><td>Muestra la evolución diaria del GGR <em>(ganancia bruta del juego)</em> de deportivas y casino, permitiendo identificar cuál vertical genera mayor margen en cada día.</td></tr><tr><td><strong><code>Registro vs FTD x día</code></strong></td><td>Presenta la tendencia diaria entre la cantidad de usuarios registrados y aquellos que realizan su primer depósito <em>(FTD),</em> mostrando la conversión de registros a clientes depositantes.</td></tr><tr><td><strong><code>Depósitos vs Retiros x día</code></strong></td><td>Grafica la relación diaria entre los depósitos ingresados a la plataforma y los retiros realizados, facilitando el análisis del flujo de dinero y el comportamiento financiero de los usuarios.</td></tr></tbody></table>

***

### 8. Control de versiones

| Versión | Fecha      | Autor         | Cambios           |
| ------- | ---------- | ------------- | ----------------- |
| **1.0** | 25/11/2025 | Ronald Peláez | Documento inicial |
