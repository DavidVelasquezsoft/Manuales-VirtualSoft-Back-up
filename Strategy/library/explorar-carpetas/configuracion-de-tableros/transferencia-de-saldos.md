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

# Transferencia de saldos

<mark style="color:$info;">Este tablero permite consultar y analizar los movimientos de depósito y salida generados por las transferencias de saldo entre usuarios, mediante filtros, indicadores, gráficos y tablas de detalle.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Transferencia de saldos

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (188).png" alt=""><figcaption><p>Figura #1: Captura de pantalla dashboard transferencia de saldo.</p></figcaption></figure>

***

### 3. Filtros

<table><thead><tr><th width="175">Campo</th><th width="542">Descripción</th></tr></thead><tbody><tr><td><strong><code>Desde</code></strong></td><td>Fecha inicial para realizar la consulta.</td></tr><tr><td><strong><code>Hasta</code></strong></td><td>Fecha final para realizar la consulta.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Filtra la información según la operación o partner seleccionado.</td></tr><tr><td><strong><code>País</code></strong></td><td>Filtra los registros asociados al país seleccionado.</td></tr><tr><td><strong><code>ID Transacción</code></strong></td><td>Identificador único de la transacción consultada.</td></tr><tr><td><strong><code>ID Irrigador</code></strong></td><td>Identificador del usuario que realiza la asignación o transferencia de saldo.</td></tr><tr><td><strong><code>Perfil Irrigador</code></strong></td><td>Perfil del usuario que realiza la asignación o transferencia <em>(Ejemplo: Concesionario, Punto de venta, Etc.).</em></td></tr><tr><td><strong><code>ID Receptor</code></strong></td><td>Identificador del usuario que recibe la transferencia de saldo.</td></tr><tr><td><strong><code>Perfil Receptor</code></strong></td><td>Perfil asociado al usuario que recibe la transferencia.</td></tr></tbody></table>

***

### 4. Contenido del dashboard

En la parte superior del tablero se encuentran las vistas **Todos**, **Depósitos** y **Salidas**, las cuales permiten filtrar la información según el tipo de movimiento que se desea consultar.

> * **Todos:** Consulta de forma consolidada los movimientos de depósito y salida.
> * **Depósitos:** Consulta únicamente los movimientos de depósito.
> * **Salidas:** Consulta únicamente los movimientos de salida.

{% hint style="warning" %}
**Nota:**&#x20;

* Independientemente de la vista seleccionada, el tablero conserva los mismos componentes _(indicadores, gráficos y tabla de detalle)_. La vista funciona como un filtro sobre la información mostrada, por lo que únicamente cambiarán los datos presentados según el tipo de movimiento seleccionado.
{% endhint %}

#### 4.1. Indicadores

Los indicadores muestran información resumida de acuerdo con los filtros seleccionados.

<table><thead><tr><th width="159.5999755859375">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad Transacciones</code></strong></td><td>Cantidad total de transacciones encontradas en la consulta realizada, de acuerdo con los filtros seleccionados.</td></tr><tr><td><strong><code>Máximo Depósito</code></strong></td><td>Valor más alto registrado en una transacción de tipo depósito según los filtros aplicados. <em>(Este valor permanecerá igual en todas las vistas del tablero)</em>.</td></tr><tr><td><strong><code>Máxima Salida</code></strong></td><td>Valor más alto registrado en una transacción de tipo salida dentro del período consultado. <em>(Este valor se mantendrá igual en todas las vistas del tablero).</em></td></tr></tbody></table>

***

#### 4.2. Gráficos

{% hint style="warning" %}
**Nota:** Los gráficos **Top 10 Depósitos** y **Top 10 Salidas** siempre mostrarán la misma información, independientemente de la vista seleccionada, ya que se generan con base en los datos globales obtenidos según los filtros aplicados.
{% endhint %}

<table><thead><tr><th width="166.79998779296875">Indicador</th><th width="109.99993896484375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Top 10 Depósitos</code></strong></td><td>Gráfico de Barras</td><td>Presenta los diez usuarios o cuentas con los montos de depósito más altos registrados durante el período consultado, de acuerdo con los filtros seleccionados.</td></tr><tr><td><strong><code>Top 10 Salidas</code></strong></td><td>Gráfico de Barras</td><td>Presenta los diez usuarios o cuentas con los montos de salida más altos registrados durante el período consultado, de acuerdo con los filtros seleccionados.</td></tr><tr><td><strong><code>Valor por dia y tipo de transacción</code></strong></td><td>Gráfico de Líneas</td><td>Muestra el valor total de los depósitos y salidas registrados por día durante el período consultado, permitiendo comparar el comportamiento de ambos tipos de transacción a lo largo del tiempo.</td></tr></tbody></table>

***

#### 4.3. Tabla de Detalle

Presenta el listado detallado de las transacciones obtenidas como resultado de la consulta realizada, de acuerdo con los filtros seleccionados.

<table><thead><tr><th width="230">Campo</th><th width="512.4000244140625">Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner asociado a la transacción.</td></tr><tr><td><strong><code>País</code></strong></td><td>País en el que se registró la transacción.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se realizó la transacción.</td></tr><tr><td><strong><code>Id Transacción</code></strong></td><td>Identificador único de la transacción.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador único del usuario asociado a la transacción.</td></tr><tr><td><strong><code>User Name</code></strong></td><td>Nombre de usuario asociado a la transacción.</td></tr><tr><td><strong><code>Perfil Receptor</code></strong></td><td>Perfil que recibe la transacción.</td></tr><tr><td><strong><code>Tipo Cupo</code></strong></td><td>Tipo de cupo asociado a la transacción.</td></tr><tr><td><strong><code>Tipo Transacción</code></strong></td><td>Tipo de movimiento realizado <em>(Depósito o Salida)</em>.</td></tr><tr><td><strong><code>Asignado Por</code></strong></td><td>Usuario responsable de la asignación de la transacción.</td></tr><tr><td><strong><code>Perfil Irrigador</code></strong></td><td>Perfil desde el cual se origina o distribuye la transacción.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto registrado para la transacción.</td></tr></tbody></table>

***

### 5. Validaciones y reglas del Negocio

* La información presentada en el tablero se mostrará de acuerdo con los filtros seleccionados por el usuario.
* La **fecha inicial** no puede ser mayor que la **fecha final**.
* Todos los filtros aplicados afectan de manera simultánea los **indicadores**, **gráficos** y la **tabla de detalle**.
* La información del tablero se actualiza automáticamente cada vez que se aplican o modifican los filtros de consulta.
* Cuando no existan registros que cumplan con los criterios de búsqueda seleccionados, los indicadores, gráficos y la tabla de detalle se mostrarán sin información.

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="108">Versión</th><th width="132">Fecha</th><th width="171">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>09/06/2026</td><td>Karol Juliana Navia</td><td>Creación inicial del manual</td></tr></tbody></table>

</details>
