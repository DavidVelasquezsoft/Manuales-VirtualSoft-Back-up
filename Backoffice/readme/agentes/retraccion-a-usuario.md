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

# Retracción a Usuario

<mark style="color:$info;">Este módulo permite gestionar la reversión de saldo previamente transferido a agentes dentro de la plataforma.</mark>

<mark style="color:$info;">En este manual se describe la estructura del módulo, sus componentes, los campos disponibles y las acciones que puede ejecutar el usuario para realizar correctamente una retracción.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú pricipal > Agentes > Retracción a Usuario

***

### 2. Visualización general

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FvnblrWd8mcdn4oKGHmiM%2Fimage.png?alt=media&#x26;token=4c5a8858-0511-4d81-a2d2-e7c301e3c2c0" alt=""><figcaption><p>Figura#1: Captura de pantalla sección retracción de usuario.</p></figcaption></figure>

El módulo se compone de una sección de filtros para la identificación del agente y, posteriormente, un formulario donde se ejecuta la operación de retracción.

***

### 3. Acciones de usuario

<table><thead><tr><th width="122">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Permiten localizar el agente al cual se le aplicará la retracción de saldo.</td></tr><tr><td><strong>Continuar</strong></td><td>Habilita el formulario de retracción una vez validada la información del agente.</td></tr><tr><td><strong>Retraer</strong></td><td>Ejecuta la operación y descuenta el saldo indicado de la cuenta del agente.</td></tr></tbody></table>

***

### 4. Filtros

Los filtros permiten identificar de manera precisa al agente sobre el cual se realizará la operación.

<table><thead><tr><th width="181">Campo</th><th width="111">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del Agente</code></strong></td><td>Texto</td><td>Permite ingresar el nombre del agente al que se desea realizar la retracción.</td></tr><tr><td><strong><code>ID del Usuario</code></strong></td><td>Numérico</td><td>Identificador único del usuario tipo agente dentro de la plataforma.</td></tr></tbody></table>

Una vez ingresada la información correspondiente, el botón **"Continuar"** permite avanzar al formulario de retracción.

***

### 5. Formulario de Retracción

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FlV0QwwKC2MQZdyrkBFZj%2Fimage.png?alt=media&#x26;token=1634079f-ac28-4da0-9a04-fa9647223de9" alt=""><figcaption><p>Figura#2: Captura de pantalla retracción de saldo.</p></figcaption></figure>

Al seleccionar el agente, el sistema muestra la información general del mismo y los campos necesarios para ejecutar la retracción.

#### 5.1 Información del agente

<table><thead><tr><th width="132">Campo</th><th width="162">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificación única del agente en la plataforma. Campo informativo no editable.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre del agente seleccionado. Campo informativo no editable.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Indicador</td><td>Muestra si el agente se encuentra activo o inactivo en el sistema.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Lista desplegable</td><td>Tipo de moneda en la que se realizará la transacción.</td></tr></tbody></table>

#### **5.2. Formulario para retracción de saldo**

<table><thead><tr><th width="152">Campo</th><th width="149">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor</code></strong></td><td>Numérico</td><td>Monto que se desea retraer del saldo del agente.</td></tr><tr><td><strong><code>Confirmar Valor</code></strong></td><td>Numérico</td><td>Confirmación del monto ingresado para validar la operación.</td></tr><tr><td><strong><code>Retraer</code></strong></td><td>Botón</td><td>Confirma los valores ingresados y despliega un mensaje emergente (pop-up) para confirmar la acción o cancelarla antes de ejecutarla.</td></tr></tbody></table>

Una vez realizada la retracción de saldo, dicho valor será descontado de la cuenta del agente.

***

### 6. Control de versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="104">Versión</th><th width="116">Fecha</th><th width="133">Autor</th><th>Descripción</th></tr></thead><tbody><tr><td>1.0</td><td>16/04/2026</td><td>Ronald Peláez</td><td>Documento inicial</td></tr></tbody></table>

</details>
