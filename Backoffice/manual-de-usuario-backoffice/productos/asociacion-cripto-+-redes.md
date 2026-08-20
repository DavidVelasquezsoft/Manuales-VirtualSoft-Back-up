---
description: >-
  Permite gestionar la asociación entre una criptomoneda y una red blockchain,
  definiendo la combinación bajo la cual una criptomoneda puede operar dentro de
  la plataforma.
---

# Asociación Cripto + Redes

### 1. Acceso al Módulo <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de Acceso**: BackOffice > Productos > Asociación cripto + redes

***

### 2. Visualización general <a href="#id-4.-visualizacion" id="id-4.-visualizacion"></a>

<figure><img src="../../.gitbook/assets/image (535).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Asociación Cripto + Redes.</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="118">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong>​</td><td>Permiten realizar búsquedas específicas mediante la selección de uno o varios filtros</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los campos de filtros a su estado inicial, eliminando cualquier criterio seleccionado previamente y permitiendo realizar una nueva búsqueda desde cero.</td></tr><tr><td><strong>​Consultar</strong></td><td>Ejecuta la búsqueda de acuerdo con los filtros definidos por el usuario y muestra los resultados en la tabla correspondiente.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite descargar la información resultante de la consulta en un archivo en formato Excel, el cual se descarga desde la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros  <a href="#id-2.-filtros" id="id-2.-filtros"></a>

Busca una asociación específica rápidamente mediante filtros opcionales.

<table><thead><tr><th width="161.22222900390625">Campo</th><th width="120.77783203125">Tipo de Control</th><th width="464.5926513671875">Descripción</th></tr></thead><tbody><tr><td><strong><code>Criptomoneda</code></strong></td><td>Texto + Lista desplegable</td><td>Busca nombre de <a href="https://virtualsoft.gitbook.io/untitled/glosario#criptomoneda">criptomoneda</a>, debe estar <strong>Activa</strong>.</td></tr><tr><td><strong><code>Red Blockchain</code></strong></td><td>Texto + Lista desplegable</td><td>Busca nombre de <a href="https://virtualsoft.gitbook.io/untitled/glosario#red-blockchain">Red Blockchain</a>, debe estar <strong>Activa</strong>.</td></tr><tr><td><strong><code>Estado (Avanzado)</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los registros según su estado: (activa, inactiva o todos).</td></tr></tbody></table>

***

### 5. Consultar

Aquí puedes consultar las asociaciones existentes, crear nuevas, modificar su estado o visualizar los detalles de cada una.&#x20;

<table><thead><tr><th width="140.5556640625">Campo</th><th width="115.44439697265625">Tipo</th><th>Descripcion</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td>Columna de acciones</td><td>Permite realizar acciones directas sobre un registro:</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único de la asociación</td></tr><tr><td><strong><code>Cripto</code></strong></td><td>Texto</td><td>Indica el nombre de la criptomoneda.</td></tr><tr><td><strong><code>Red</code></strong></td><td>Texto</td><td>Indica la <a href="https://virtualsoft.gitbook.io/untitled/glosario#red-blockchain">red blockchain</a> de la asociación.</td></tr><tr><td><strong><code>Código de Red</code></strong></td><td>Texto</td><td>Muestra el código que identifica la <a href="https://virtualsoft.gitbook.io/untitled/glosario#red-blockchain">red blockchain</a> utilizada por la criptomoneda.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Muestra el estado de la asociación: Activa o Inactiva.</td></tr></tbody></table>

***

### 6. Asociar cripto + Red

Abre una ventana emergente que permite asociar una criptomoneda con Red Blockchain, completando los siguientes campos obligatorios.

{% hint style="danger" %}
**Nota importante:** Para poder asociar una criptomoneda con una red blockchain, **ambas deben encontrarse en estado activo**. Al realizar esta asociación ([Cripto + Red](https://virtualsoft.gitbook.io/untitled/glosario#criptomoneda--red-blockchain)), el sistema generará automáticamente un banco con el nombre conformado por los **primeros 3 caracteres de la criptomoneda y de la red, separados por un guion** (ejemplo: **Bit-Eth**), cuyo estado dependerá de la asociación.

Este banco **no quedará disponible** para el registro de cuentas bancarias en la plataforma de usuarios online. Para que el jugador pueda utilizarlo y realizar retiros en criptomonedas, es necesario completar la configuración descrita en Flujo completo: [**habilitar retiros en criptomonedas.**](asociacion-cripto-+-redes.md#id-7.-flujo-habilitar-retiros-en-criptomonedas)
{% endhint %}

<table><thead><tr><th width="162.6666259765625">Campo</th><th width="123">Tipo</th><th width="462.111083984375">Descripcion</th></tr></thead><tbody><tr><td><strong><code>Criptomonedas</code></strong></td><td>Lista desplegable</td><td>Selecciona la <a href="https://virtualsoft.gitbook.io/untitled/glosario#criptomoneda">criptomoneda</a> a vincular</td></tr><tr><td><strong><code>Red Blockchain</code></strong></td><td>Lista desplegable</td><td>Selecciona la <a href="https://virtualsoft.gitbook.io/untitled/glosario#red-blockchain">Red Blockchain</a> a asociar.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Selector</td><td>Indica si la asociación estará Activa o Inactiva desde su creación.</td></tr></tbody></table>

***

### 7. Flujo habilitar retiros en criptomonedas

El banco generado por la asociación Cripto + Red es un registro interno que representa esa combinación dentro del sistema; el jugador nunca lo selecciona directamente.&#x20;

Para que la criptomoneda y la red queden disponibles como opción de retiro en la plataforma de usuarios online, es necesario crear un producto, habilitarlo para el partner y el país, y asociarlo a ese banco.

A continuación se describe la configuración completa, en el orden en que debe realizarse.

{% stepper %}
{% step %}
#### [**Crear la criptomoneda**](criptomonedas.md)

Registrar la criptomoneda que se habilitará para retiros y dejarla en estado activo.
{% endstep %}

{% step %}
#### [**Crear la red blockchain**](redes-blockchain.md)

Registrar la red blockchain sobre la cual operará la criptomoneda y dejarla en estado activo
{% endstep %}

{% step %}
#### [**Asociar la criptomoneda con la red blockchain**](asociacion-cripto-+-redes.md#id-6.-asociar-cripto--red)

Realizar la asociación entre ambas. Al completarla, el sistema genera automáticamente un **banco vinculado**, el cual puede consultarse en el [módulo de Bancos](bancos.md).

{% hint style="warning" %}
**Nota:** El banco generado es un registro **interno** que representa la combinación de criptomoneda y red blockchain. No se utiliza para el registro de cuentas bancarias ni es visible para el jugador: su función es permitir que esa combinación quede disponible como opción de retiro una vez completada la configuración.
{% endhint %}
{% endstep %}

{% step %}
#### [**Crear el producto**](productos.md)

Crear un producto que represente el medio de retiro que verá el jugador en la plataforma. El producto es el elemento con el que el usuario interactúa en la plataforma de usuarios online, por lo que sin él el banco no se muestra.

Al crearlo, debe asociarse un **proveedor que permita realizar retiros en criptomonedas** _(por ejemplo: EukaPay)_ y dejarse habilitado para los canales correspondientes.
{% endstep %}

{% step %}
#### [**Habilitar el producto para el partner y el país**](../herramientas/partner-ajustes/productos-2/habilitacion-productos.md)

En **Herramientas > Partner ajustes > Productos 2 > Habilitación de productos**, habilitar el producto creado para el partner y el país correspondientes.
{% endstep %}

{% step %}
#### [**Activar el producto**](../herramientas/partner-ajustes/productos-2/activacion-productos..md)

En **Herramientas > Partner ajustes > Productos 2 > Activación de productos**, activar el producto habilitado en el paso anterior.&#x20;

{% hint style="danger" %}
**Nota importante:** El producto debe estar habilitado y activo para el partner y el país. De lo contrario, no aparecerá disponible en el módulo **Productos a bancos** y no será posible continuar con la configuración.
{% endhint %}
{% endstep %}

{% step %}
#### [**Asociar el producto al banco**](../herramientas/partner-ajustes/productos/productos-a-bancos.md)

En **Herramientas > Partner ajustes > Productos > Productos a bancos**, vincular el producto con el banco generado por la asociación Cripto + Red, indicando el país correspondiente y dejando la asociación en estado activo. Con esta asociación, el medio de retiro en criptomonedas **queda visible** en la plataforma de usuarios online.
{% endstep %}

{% step %}
#### [**El jugador registra su billetera**](https://app.gitbook.com/s/yyrHDz69FZMnpZ9NBm8u/usuarios-online/manual-de-plataforma/gestion/wallets-crypto)

Desde la sección **Wallet cripto** de la plataforma de usuarios online, el jugador registra su billetera seleccionando primero la **criptomoneda** y luego la **red blockchain**, e ingresando la dirección de wallet correspondiente.

{% hint style="warning" %}
**Notas:**&#x20;

* Las billeteras de criptomonedas se registran en una sección independiente a la de cuentas bancarias, ya que requieren información distinta _(criptomoneda, red y dirección de wallet)_.
* Al seleccionar una criptomoneda, el sistema muestra únicamente las redes blockchain asociadas a ella y habilitadas para retiro. El jugador no selecciona el banco: este opera de forma interna, representando la combinación de criptomoneda y red configurada.
{% endhint %}
{% endstep %}

{% step %}
#### **El jugador realiza el retiro**

En la sección **Retirar**, el jugador selecciona la opción **Criptomonedas**, elige una de las billeteras registradas e ingresa el monto a retirar. Consultar el manual de Retirar.
{% endstep %}
{% endstepper %}

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="100">Versión</th><th width="125.7999267578125">Fecha</th><th width="135.5999755859375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2025/08/04</td><td>David velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>2025/08/08</td><td>Ronald Peláez</td><td>Actualización de condición por activaciones</td></tr><tr><td>1.2</td><td>2025/08/19</td><td>David velasquez</td><td>Actualización de nota sobre nueva funcionalidad.</td></tr><tr><td>1.3</td><td>2025/12/16</td><td>Ronald Peláez</td><td>Refinamiento de manual</td></tr><tr><td>1.4</td><td>2026/08/20</td><td>David velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-21110#icft=VSFT-21110">Flujo habilitar retiros en criptomonedas</a></td></tr></tbody></table>

</details>
