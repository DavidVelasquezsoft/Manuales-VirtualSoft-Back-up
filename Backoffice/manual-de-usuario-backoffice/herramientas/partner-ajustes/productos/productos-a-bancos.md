---
description: >-
  Esta sección permite consultar y gestionar la asociación de productos con
  bancos específicos mediante diferentes filtros y acciones.
---

# Productos a Bancos

***

## 1. Acceso al Módulo&#x20;

**Ruta de Acceso:** Backoffice > Herramientas > Partner ajustes > Partner > Productos > Productos a Bancos

***

## 🖼️ 2. Visualización general

<figure><img src="../../../../.gitbook/assets/image (541).png" alt=""><figcaption><p>Figura #1: Captura de pantalla productos a bancos.</p></figcaption></figure>

***

## 🔍 3. filtros

<table><thead><tr><th width="114.00006103515625">Campo</th><th width="138.1666259765625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Productos</code></td><td>Dropdown</td><td>Selecciona el producto que deseas buscar.</td></tr><tr><td><code>Banco</code></td><td>Dropdown</td><td>Permite seleccionar un banco específico.</td></tr><tr><td><code>País</code></td><td>Dropdown</td><td><p>Indique el país en el que se encuentra el banco.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> este campo es obligatorio para consultar.</p></div></td></tr><tr><td><p><code>Estado</code></p><p><code>(Avanzado)</code></p></td><td>Dropdown</td><td>Seleccione el estado de la asociación a consultar.</td></tr></tbody></table>

***

## 🧑‍💻 4. Acciones de usuario

### ➕ 4.1. **Añadir Producto** a **Banco**

Abre una ventana emergente que permite vincular un producto a un banco en específico.&#x20;

<table><thead><tr><th width="162.6666259765625">Campo</th><th width="123">Tipo</th><th width="462.111083984375">Descripcion</th></tr></thead><tbody><tr><td><code>País</code></td><td>Dropdown</td><td>Elige el país en el que se encuentra el banco.</td></tr><tr><td><code>Productos</code></td><td>Dropdown</td><td>Elige el Producto que deseas asociar al banco.</td></tr><tr><td><code>Banco</code></td><td>Dropdown</td><td>Elige el banco al cual deseas asociar el producto seleccionado.</td></tr><tr><td><code>Estado</code></td><td>Toggle switch</td><td>Indica si la asociación está activa o inactiva.</td></tr></tbody></table>

{% hint style="warning" %}
Nota:&#x20;

* Para la creacion todos los campos son obligatorios.
* La relación entre **Producto** y [**Cripto+Red**](https://virtualsoft.gitbook.io/untitled/glosario#criptomoneda--red-blockchain) deja de ser directa, Estableciéndose a través del Banco\
  **Producto** ↔ **Banco** ↔ **Cripto+Red.**
{% endhint %}

### 4.2 🔄 Limpiar

Restablece los filtros por defecto.

### 4.3. 🚀 Consultar

Aplica los filtros seleccionados y muestra los registros válidos.

<table><thead><tr><th width="113.88897705078125">Campo</th><th width="115.44439697265625">Tipo</th><th>Descripcion</th></tr></thead><tbody><tr><td><code>Acciones</code></td><td>Columna de acciones</td><td>Permite realizar acciones directas sobre un registro:</td></tr><tr><td><code>ID</code></td><td>Numerico</td><td>Identificador unico de la asociación</td></tr><tr><td><code>Productos</code></td><td>Texto</td><td>Nombre del producto asociado con su código de identificación entre paréntesis.</td></tr><tr><td><code>Banco</code></td><td>Texto</td><td>Nombre del banco asociado con su código entre paréntesis.</td></tr><tr><td><code>Estado</code></td><td>Texto</td><td>Muestra el estado de la asociación: Activa o Inactiva.</td></tr><tr><td><code>Partner</code></td><td>Texto</td><td>Nombre de la plataforma con la que está asociado el banco.</td></tr></tbody></table>

<table><thead><tr><th width="87.0555419921875">Campo</th><th>Descripcion</th></tr></thead><tbody><tr><td>✏️</td><td>Permite visualizar y modificar únicamente el estado del registro. Activa/Inactiva</td></tr></tbody></table>

***

## 🕒 5. Control de Versiones

| Versión | Fecha      | Autor           | Cambios Realizados |
| ------- | ---------- | --------------- | ------------------ |
| 1.0     | 2025/08/11 | David velasquez | Documento inicial  |
