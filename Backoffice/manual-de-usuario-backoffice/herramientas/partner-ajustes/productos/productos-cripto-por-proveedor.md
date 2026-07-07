---
description: >-
  Permite asociar un producto con una criptomoneda específica y la red
  blockchain en la que opera, vinculándola con un proveedor determinado.
---

# Productos Cripto por Proveedor

***

## 1. Acceso al Módulo <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de Acceso**: Backoffice > Herramientas > Partner ajustes > Partner > Productos > Productos cripto por proveedor

***

## 🖼️ 2. Visualización <a href="#id-4.-visualizacion" id="id-4.-visualizacion"></a>

<figure><img src="../../../../.gitbook/assets/image (523).png" alt=""><figcaption><p>Figura#1: Captura de pantalla seccion Productos Cripto por Proveedor</p></figcaption></figure>

***

## 🔎3. Filtros  <a href="#id-2.-filtros" id="id-2.-filtros"></a>

<table><thead><tr><th width="161.22222900390625">Campo</th><th width="120.77783203125">Tipo de Control</th><th width="267.5556640625">Descripción</th><th>Validación</th></tr></thead><tbody><tr><td><code>Proveedor</code></td><td>Dropdown</td><td>Selecciona el proveedor.</td><td>N/A</td></tr><tr><td><code>Criptomoneda</code></td><td>Dropdown</td><td>Selecciona nombre de criptomoneda</td><td>N/A</td></tr><tr><td><code>Red Blockchain</code></td><td>Dropdown</td><td>Selecciona Red Blockchain</td><td>N/A</td></tr><tr><td><code>País</code></td><td>Dropdown</td><td>Filtra por pais</td><td>Campo obligatorio.</td></tr><tr><td><code>Estado</code></td><td>Dropdown</td><td>Permite filtrar los registros por estado: activa, inactiva o todos.</td><td>La opción Por defecto es "<strong>Todos</strong>".</td></tr></tbody></table>

***

## 🧑‍💻 4. Acciones del Usuario

### 4.1. 🤝 Asociar producto - Criptomoneda

Abre una ventana emergente que permite vincular un producto con una criptomoneda, su red blockchain y un proveedor asociado.

<table><thead><tr><th width="162.6666259765625">Campo</th><th width="123">Tipo</th><th width="462.111083984375">Descripcion</th></tr></thead><tbody><tr><td><code>Pais</code></td><td>Dropdown</td><td>Elige el país de la asociación.</td></tr><tr><td><code>Proveedor</code></td><td>Dropdown</td><td>Elige el Proveedor.</td></tr><tr><td><code>Producto</code></td><td>Dropdown</td><td>Permite seleccionar productos disponibles.</td></tr><tr><td><code>Criptomoneda + Red blockchain</code></td><td>Dropdown</td><td>Selecciona Criptomoneda + Red blockchain.</td></tr><tr><td><code>Estado</code></td><td>Toggle switch</td><td>Indica si la asociación está activa o inactiva.</td></tr></tbody></table>

* Todos los campos son obligatorios para crear la asociacion.
* Para crear la asociacion debe haber creada una Criptomoneda + Red blockchain.

### 4.2 🔄 Limpiar

Restablece los filtros por defecto.

### 4.3. Consultar

Aplica los filtros seleccionados y muestra los registros válidos.

<table><thead><tr><th width="140.5556640625">Campo</th><th width="115.44439697265625">Tipo</th><th>Descripcion</th></tr></thead><tbody><tr><td><code>Acciones</code></td><td>Columna de acciones</td><td>Permite realizar acciones directas sobre un registro:</td></tr><tr><td><code>ID</code></td><td>Numerico</td><td>Identificador unico de la asociación</td></tr><tr><td><code>Proveedor</code></td><td>Texto</td><td>Nombre del proveedor asociado.</td></tr><tr><td><code>Producto Técnico</code></td><td>Texto</td><td>Nombre del producto asociado.</td></tr><tr><td><code>Cripto</code></td><td>Texto</td><td>Indica el nombre de la criptomoneda.</td></tr><tr><td><code>Red</code></td><td>Texto</td><td>Indica la red blockchain de la asociacion.</td></tr><tr><td><code>Código de Red</code></td><td>Texto</td><td>Muestra el código que identifica la red blockchain utilizada por la criptomoneda.</td></tr><tr><td><code>Estado</code></td><td>Texto</td><td>Muestra el estado de la asociación: Activa o Inactiva.</td></tr><tr><td><code>Partner/País</code></td><td>Texto</td><td>Muestra el país y el partner asociados al registro.</td></tr></tbody></table>

<table><thead><tr><th width="84.5555419921875">Campo</th><th>Descripcion</th></tr></thead><tbody><tr><td>🔍</td><td> Permite visualizar los detalles de la asociación.</td></tr><tr><td>✏️</td><td>Permite visualizar y modificar únicamente el estado del registro. Activa/Inactiva</td></tr></tbody></table>

***

## 🕒 5. Control de Versiones

| Versión | Fecha      | Autor           | Cambios Realizados |
| ------- | ---------- | --------------- | ------------------ |
| 1.0     | 2025/07/08 | David velasquez | Documento inicial  |

