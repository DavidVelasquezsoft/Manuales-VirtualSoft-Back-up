---
description: >-
  Esta sección permite consultar y reordenar los juegos disponibles según los
  filtros aplicados, definiendo la posición en la que se mostrarán dentro de la
  plataforma de usuarios online.
---

# Ordenar Juegos

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, no será visible en el sistema.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Herramientas > Partner Ajustes > Productos > Ordenar Juegos

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (377).png" alt=""><figcaption><p>Figura#1: Capturta de pantalla filtros de busqueda.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="ordenar-juegos.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para listar los juegos que se desean ordenar.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="ordenar-juegos.md#id-5.-ordenamiento-de-juegos"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra la lista de juegos disponibles para reordenar.</td></tr></tbody></table>

***

### 4. Filtros

Antes de proceder con la reordenación, se deben seleccionar los siguientes filtros:

<table><thead><tr><th width="140.666748046875">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona el proveedor que ofrece los juegos.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona el subproveedor asociado al proveedor principal.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td><p>Indica el país en el que se aplicará la configuración.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Es un filtro <strong>obligatorio</strong> para ejecutar la consulta.</p></div></td></tr><tr><td><strong><code>Categorías</code></strong></td><td>Lista desplegable</td><td><p>Selecciona la categoría de juegos que se desea ordenar.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Es un filtro <strong>obligatorio</strong> para ejecutar la consulta.</p></div></td></tr><tr><td><strong><code>Dispositivo</code></strong></td><td>Lista desplegable</td><td><p>Especifica el tipo de dispositivo en el que se visualizarán los cambios <em>(por ejemplo: escritorio, móvil)</em>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La reordenación de juegos será visible únicamente cuando los usuarios accedan desde el dispositivo seleccionado.</p></div></td></tr></tbody></table>

***

### 5. Ordenamiento de Juegos

Una vez aplicados los filtros y presionado el botón **Consultar**, en la parte inferior aparece la lista de juegos correspondientes a la configuración establecida. Para modificar el orden, sigue estos pasos:

1. **Selecciona** el juego que deseas mover.
2. **Arrástralo** hasta la posición deseada.
3. **Suelta** el juego en la nueva ubicación.

Al soltar el juego en la nueva posición, se abre una ventana emergente que solicita registrar el motivo del cambio:

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Observación</code></strong></td><td>Campo de texto</td><td>Permite ingresar la explicación o el motivo por el cual se realizó el cambio de orden del juego.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Para que el cambio de orden quede registrado, es necesario completar el campo **Observación** y confirmar la acción en la ventana emergente.
{% endhint %}

***

### 6. Validaciones y reglas del negocio

* El acceso al módulo requiere permisos específicos; de lo contrario, no será visible en el sistema.
* Los filtros **País** y **Categorías** son obligatorios para ejecutar la consulta.
* La reordenación de los juegos se refleja únicamente en el dispositivo seleccionado en los filtros.
* Cada cambio de orden requiere registrar una **observación** que justifique la modificación.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>01/07/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
