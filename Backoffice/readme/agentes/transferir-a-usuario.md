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

# Transferir a Usuario

<mark style="color:$info;">Este módulo permite realizar transferencias de saldo a usuarios tipo agente dentro de la plataforma, garantizando el registro y validación de la información requerida antes de ejecutar la operación.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Agentes > Transferencias de saldo

***

### 2. Visualización general

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FU0T76WM6ENjRJHiSN6hN%2Fimage.png?alt=media&#x26;token=002cd428-e3af-4842-be15-41e11982ea5f" alt=""><figcaption><p>Figura#1: Captura de pantalla sección transferir a usuario.</p></figcaption></figure>

El módulo se compone de una sección de filtros para la identificación del agente y, posteriormente, un formulario donde se ejecuta la operación de transferencia.

***

### 3. Acciones de usuario

<table><thead><tr><th width="122">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Permiten localizar el agente al cual se le aplicará la transferencia de saldo.</td></tr><tr><td><strong>Continuar</strong></td><td>Habilita el formulario de transferencia una vez validada la información del agente.</td></tr><tr><td><strong>Transferir</strong></td><td>Ejecuta la operación y acredita el saldo indicado en la cuenta del agente.</td></tr></tbody></table>

***

### 4. Filtros

Los filtros permiten identificar de manera precisa al agente sobre el cual se realizará la operación.

<table><thead><tr><th width="181">Campo</th><th width="111">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del Usuario</code></strong></td><td>Texto</td><td>Permite ingresar el nombre del usuario tipo agente al que se desea realizar la transferencia.</td></tr><tr><td><strong><code>ID del Usuario</code></strong></td><td>Numérico</td><td>Identificador único del usuario tipo agente dentro de la plataforma.</td></tr></tbody></table>

Una vez ingresada la información correspondiente, el botón **"Continuar"** permite avanzar al formulario de transferencia.

***

### 5. Formulario de Transferencia

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FsDMZhPFDvzXBSvvUVlKC%2Fimage.png?alt=media&#x26;token=689b3d72-2563-47ba-b7b5-2699a1b3095e" alt=""><figcaption><p>Figura#2: Captura de pantalla transferencia a usuario.</p></figcaption></figure>

Al seleccionar el agente, el sistema muestra la información general del mismo y los campos necesarios para ejecutar la transferencia.

<table><thead><tr><th width="132">Campo</th><th width="162">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificación única del agente en la plataforma. Campo informativo no editable.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre del agente seleccionado. Campo informativo no editable.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Indicador</td><td>Muestra si el agente se encuentra activo o inactivo en el sistema.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Lista desplegable</td><td>Tipo de moneda en la que se realizará la transacción.</td></tr><tr><td><strong><code>Valor *</code></strong></td><td>Numérico</td><td>Monto que se desea transferir al saldo del agente.</td></tr><tr><td><strong><code>Confirmar Valor</code></strong></td><td>Numérico</td><td>Confirmación del monto ingresado para validar la operación.</td></tr><tr><td><strong><code>ID de Transacción Relacionada</code></strong></td><td>Texto</td><td>Referencia única de la transacción asociada.</td></tr><tr><td><strong><code>Banco</code></strong></td><td>Lista desplegable</td><td>Entidad bancaria desde la cual se efectuará la transferencia.</td></tr></tbody></table>

> **Nota:** Los campos marcados con (\*) son obligatorios y deben completarse antes de confirmar la operación.

El botón **"Transferir"** ejecuta la operación. Si la información ingresada es válida, el sistema acreditará el saldo al agente seleccionado.

### 6. Control de versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="104">Versión</th><th width="116">Fecha</th><th width="133">Autor</th><th>Descripción</th></tr></thead><tbody><tr><td>1.0</td><td>21/04/2026</td><td>Ronald Peláez</td><td>Documento inicial</td></tr></tbody></table>

</details>
