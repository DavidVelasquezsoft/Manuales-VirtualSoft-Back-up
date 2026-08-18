---
description: >-
  Permite personalizar la  organización de los tipos de métodos disponibles para
  realizar depósitos.
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

# Configurar depósitos

<mark style="color:$info;">Administra el orden de visualización de los métodos de depósito disponibles en la plataforma de usuarios. Desde esta sección se organizan los canales informativos y transaccionales según la prioridad definida.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso:** Menú lateral > Productos > Configurar depósitos

***

### 2. Visualización

La interfaz presenta los métodos de depósito organizados mediante dos tipos de cards:

* **Cards informativas:** Representan métodos de depósito que no realizan una transacción directamente desde la plataforma o que presentan información para completar el depósito por otro medio.
* **Cards transaccionales:** Representan métodos de depósito activos mediante los cuales el usuario puede iniciar una transacción desde la plataforma.

<figure><img src="../../../.gitbook/assets/image (287).png" alt=""><figcaption><p>Figura#1: Captura de pantalla Configurar depósito.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="119.81817626953125" align="center">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><strong>Arrastrar y soltar</strong></td><td>Reorganiza la posición de las cards dentro de la lista de métodos de depósito.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (447).png" alt="" data-size="line"></td><td>Modifica la posición de una card mediante el ícono de movimiento ubicado en su centro.</td></tr><tr><td align="center"><strong>Guardar</strong></td><td>Almacena el nuevo orden de visualización configurado para los métodos de depósito.</td></tr></tbody></table>

***

### 4. **Comportamiento**

La posición configurada para cada método de depósito determina el orden en que estos serán presentados al usuario en la plataforma.

El comportamiento al seleccionar un método depende de si corresponde a un **método transaccional** o **informativo**:

<table><thead><tr><th width="163.45452880859375">Tipo de método</th><th>Comportamiento</th></tr></thead><tbody><tr><td><strong>Transaccional</strong></td><td>Al seleccionar <strong>Depositar</strong>, inicia el flujo de depósito correspondiente y redirige al usuario hacia la página externa definida para completar la transacción.</td></tr><tr><td><strong>Informativo</strong></td><td>Al seleccionar <strong>Depositar</strong>, presenta un <strong>pop-up</strong> con la información e instrucciones necesarias para realizar el depósito mediante el canal indicado.</td></tr></tbody></table>

**Ejemplos de comportamiento**

* **PayU:** corresponde a un método **transaccional**. Al seleccionar **Depositar**, el usuario es redirigido a una página externa para continuar con el proceso de recarga.
* **Tiendas TAMBO:** corresponde a un método **informativo**. Al seleccionar **Depositar**, se presenta un **pop-up** con la información e instrucciones necesarias para completar el depósito de manera presencial.

{% hint style="warning" %}
**Nota:** El orden definido en el módulo **Configurar depósitos** determina únicamente la posición visual de los métodos en la plataforma. El comportamiento de cada método depende de su configuración.
{% endhint %}

***

### 5. Validaciones y reglas del negocio

* El nuevo orden de las cards se aplica únicamente después de seleccionar **Guardar**.
* El orden configurado modifica la posición visual de los métodos de depósito en la plataforma.
* La reorganización de las cards no modifica la lógica transaccional de los métodos de depósito.

***

### 6. Control de Versiones

<details>

<summary>🔽Historial de Versiones</summary>

<table><thead><tr><th width="103.45458984375">Versión</th><th width="121.8182373046875">Fecha</th><th width="117.6363525390625">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>23/07/2025</td><td><strong>Karol Navia</strong></td><td>Documento inicial de configuración de depósitos.</td></tr></tbody></table>

</details>
