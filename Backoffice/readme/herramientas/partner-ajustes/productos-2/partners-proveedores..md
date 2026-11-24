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
  anchors:
    visible: true
---

# Partners Proveedores.

<mark style="color:$info;">Asocia o retira los proveedores de un partner mediante dos listas: Proveedores no agregados y Proveedores Agregados.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Herramientas > Partner Ajustes > Productos 2 > Partners Proveedores

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (605).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección partners proveedores.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="partners-proveedores..md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen el proveedor y el partner sobre los que se realiza la gestión.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="partners-proveedores..md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los proveedores en las listas.</td></tr><tr><td><a href="partners-proveedores..md#id-6.-gestion-de-proveedores"><strong>Agregar / Retirar</strong></a></td><td>Asocia proveedores al partner o los retira mediante los botones ubicados entre las listas.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona un proveedor creado previamente.</td></tr><tr><td><strong><code>Partner Referencia</code></strong></td><td>Lista desplegable</td><td><p>Define el partner sobre el que se realiza la gestión.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La lista <strong>Proveedores Agregados</strong> muestra solo los proveedores vinculados a este partner, y todas las acciones se aplican sobre él.</p></div></td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td><p>Habilita el botón <strong>Consultar</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo es obligatorio, pero no cambia los resultados ni las acciones sobre los proveedores.</p></div></td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, los proveedores se organizan en dos listas según estén asociados o no al partner seleccionado.

<table><thead><tr><th width="200">Campo</th><th width="120">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores no agregados</code></strong></td><td>Lista</td><td>Muestra los proveedores disponibles que aún no están asociados al partner.</td></tr><tr><td><strong><code>Proveedores Agregados</code></strong></td><td>Lista</td><td>Reúne los proveedores ya asociados al partner.</td></tr></tbody></table>

***

### 6. Gestión de proveedores

Para asociar o retirar proveedores, se seleccionan uno o varios en la lista correspondiente y se usan los botones ubicados entre las dos listas.

<table><thead><tr><th width="120">Botón</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>&#x3E;</code></strong></td><td>Asocia al partner los proveedores seleccionados en <strong>Proveedores no agregados</strong>.</td></tr><tr><td><strong><code>&#x3C;</code></strong></td><td>Retira del partner los proveedores seleccionados en <strong>Proveedores Agregados</strong>.</td></tr><tr><td><strong><code>&#x3E;&#x3E;</code></strong></td><td>Asocia al partner todos los proveedores de la lista <strong>Proveedores no agregados</strong>.</td></tr><tr><td><strong><code>&#x3C;&#x3C;</code></strong></td><td>Retira del partner todos los proveedores de la lista <strong>Proveedores Agregados</strong>.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Al asociar o retirar un proveedor, el sistema muestra una ventana emergente que solicita una **Observación**. Si el campo queda vacío, la acción no se ejecuta.
{% endhint %}

***

### 7. Validaciones y reglas del negocio:

* El campo **`País`** es obligatorio para habilitar el botón **Consultar**.
* La **Observación** es obligatoria para confirmar la asociación o el retiro de proveedores.
* Los cambios se aplican al presionar **Guardar** en la ventana emergente de la observación.
* Solo aparecen los proveedores creados previamente en el módulo [Partners Proveedores](../productos/partners-proveedores.md).

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>18/03/2026</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
