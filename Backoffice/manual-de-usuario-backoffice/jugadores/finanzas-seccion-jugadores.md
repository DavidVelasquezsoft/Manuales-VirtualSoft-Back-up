---
description: >-
  Esta sección está dividida en dos apartados principales: Financiero y Cuentas
  Bancarias, donde se muestra información relevante sobre el estado financiero
  del usuario y sus cuentas asociadas.
---

# Finanzas sección Jugadores

***

### 1. Acceso al módulo

**Ruta de acceso**: BackOffice > Jugadores > Finanzas

***

### 2. Finanzas

Tendrás 2 opciones para gestionar las finanzas del jugador.

{% tabs %}
{% tab title="2.1. Financiero" %}
Permite visualizar un desglose detallado de la actividad financiera del usuario.

#### 2.1.1🖼️ Visualización&#x20;

<figure><img src="../../.gitbook/assets/image (27).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección financiero.</p></figcaption></figure>

#### 2.1.2📑 Descripción de campos

<table><thead><tr><th width="218.666748046875">Campo</th><th width="106.3333740234375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total  Depósitos</code></strong></td><td>Numérico</td><td>Monto total depositado por el usuario.</td></tr><tr><td><strong><code>Total Apuestas deportivas</code></strong></td><td>Numérico</td><td>Total de apuestas realizadas en deportes.</td></tr><tr><td><strong><code>Total Ganancias deportivas</code></strong></td><td>Numérico</td><td>Monto ganado en apuestas deportivas.</td></tr><tr><td><strong><code>Total Apuestas casino</code></strong></td><td>Numérico</td><td>Total de apuestas realizadas en juegos de casino.</td></tr><tr><td><strong><code>Ganancias totales casino</code></strong></td><td>Numérico</td><td>Monto ganado en apuestas de casino.</td></tr><tr><td><strong><code>Total Retiros</code></strong></td><td>Numérico</td><td>Valor total retirado por el usuario.</td></tr><tr><td><strong><code>Ajustes de entrada</code></strong></td><td>Numérico</td><td>Modificaciones en el saldo del usuario por ajustes entradas.</td></tr><tr><td><strong><code>Ajustes de salida</code></strong></td><td>Numérico</td><td>Modificaciones en el saldo del usuario por ajustes de salidas.</td></tr></tbody></table>

#### 2.1.3📄 Resumen

Además, se muestra un **resumen financiero**, donde se reflejan los montos de cada categoría, junto con indicadores visuales que diferencian valores positivos y negativos.

<table><thead><tr><th width="119.6666259765625">Categoría</th><th>Resumen</th></tr></thead><tbody><tr><td><strong><code>Depósitos</code></strong></td><td>Resumen del monto total depositado en la cuenta del usuario.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Resumen </td></tr><tr><td><strong><code>Premios</code></strong></td><td>Resumen de los premios adquiridos por el usuario.</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Resumen de los retiros solicitados por el usuario.</td></tr><tr><td><strong><code>Saldo de bonos</code></strong></td><td>Resumen de los bonos adquiridos por el usuario.</td></tr><tr><td><strong><code>Ajustes</code></strong></td><td>Resumen de los ajustes realizados en la cuenta del usuario.</td></tr><tr><td><strong><code>Indicadores de juego</code></strong></td><td>Muestra los indicadores de rendimiento económico del jugador</td></tr></tbody></table>
{% endtab %}

{% tab title="2.2. Cuentas Bancarias" %}
Permite consultar las cuentas bancarias vinculadas al usuario.

#### 2.2.1🖼️ Visualización

<figure><img src="../../.gitbook/assets/image (578).png" alt=""><figcaption><p>Figura#2: Captura de pantalla sección cuentas bancarias.</p></figcaption></figure>

#### 2.2.2🔍 Filtros

<table><thead><tr><th width="110.22216796875"> Campo</th><th width="166.77777099609375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Cuenta</code></strong></td><td>Numérico</td><td>Identificador único asignada a la cuenta bancaria.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el estado actual de la cuenta. (Todos, Activo o Inactivo)</td></tr></tbody></table>

#### 2.2.4🚀 Resultados de consulta

Aplica los filtros seleccionados y muestra las cuentas bancarias válidas.

<table><thead><tr><th width="143.111083984375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>🖋️</code></td><td>Despliega un pop-up con información de la tarjeta ya registrada y con la posibilidad de editar solo el estado de la tarjeta.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Código único identificador de la tarjeta.</td></tr><tr><td><strong><code>Banco</code></strong></td><td>Nombre de la entidad bancaria.</td></tr><tr><td><strong><code>Número de cuenta bancaria</code></strong></td><td>Clave única de la cuenta registrada.</td></tr><tr><td><strong><code>Código interbancario</code></strong></td><td>Código asignado para transacciones interbancarias.</td></tr><tr><td><strong><code>Tipo de cuenta</code></strong></td><td>Clasificación de la cuenta <em>(ejemplo: ahorro, corriente).</em></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Indica si la cuenta está: <em>(activa o inactiva).</em></td></tr><tr><td><strong><code>Fecha registro</code></strong></td><td>Fecha en la que se registró la tarjeta.</td></tr></tbody></table>

#### 2.2.3⚡Acciones Disponibles

<table><thead><tr><th width="127.88885498046875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Registrar tarjeta Stradacarte</strong></td><td>Despliega un pop-up que permite registrar una tarjeta para retiros y recargas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Limpia todos los filtros con información</td></tr><tr><td><strong>Consultar</strong></td><td>Realiza la consulta según los filtros completados.</td></tr></tbody></table>

#### 2.2.5✅Validaciones y reglas del negocio

* Las acciones para registrar, editar o eliminar tarjetas, solo estarán disponibles si el usuario cuenta con los permisos correspondientes.
* En caso de intentar registrar una tarjeta con un ID duplicado se visualizará el siguiente mensaje: _**"Este ID CARD ya está registrado para otro jugador. Verifica la información ingresada."**_
* Un jugador puede tener un máximo de 5 tarjetas activas.
* No es posible editar una tarjeta en caso de que tenga un retiro/recarga procesando, en caso de intentarlo se visualizará el siguiente mensaje: _**“Esta tarjeta tiene un retiro activo y no puede ser modificada ni eliminada.”**_
* Si se elimina una tarjeta o se inactiva, esta dejará de visualizarse en la plataforma de usuarios online.

#### 2.2.6📩Mensajes y confirmaciones&#x20;

* Registro exitoso:

_“Tarjeta registrada exitosamente.”_

* Eliminación confirmada:

_“Tarjeta eliminada. Ya no estará disponible para retiros ni recargas.”_

* Registro fallido por duplicado global:

_“Este ID CARD ya está registrado para otro jugador.”_

* Límite de tarjetas alcanzado:

_“Este jugador ya tiene el máximo de 5 tarjetas activas.”_
{% endtab %}
{% endtabs %}

***

### 3. Validaciones y reglas del negocio

* La clasificación del bono depende de la vertical donde se cumpla el rollover: **casino** _(slots, casino en vivo o virtuales)_ o **deportivo** _(sportsbook)._
* Si no existe valor correspondiente en un campo de la tabla resumen, debe aparecer 0.

### 4. Control de versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="107" align="right">Versión</th><th width="148">Fecha</th><th width="164">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td align="right">1.0</td><td>2025-09-08</td><td>David Velásquez</td><td>Actualización de formato</td></tr><tr><td align="right">1.1</td><td>2025-09-11</td><td>Ronald Peláez</td><td>Registro de tarjeta  Stradacard y refinamiento de manual.</td></tr><tr><td align="right">1.2</td><td>2025-11-05</td><td>Ronald Peláez</td><td>Agregar tabla de resumen financiero.</td></tr></tbody></table>

</details>
