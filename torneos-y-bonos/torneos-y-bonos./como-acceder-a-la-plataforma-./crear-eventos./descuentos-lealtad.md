---
description: >-
  Permite configurar y administrar descuentos en los premios de la tienda de
  lealtad, modificando temporalmente el costo en puntos de los premios según una
  programación definida.
---

# Descuentos Lealtad

### 1. Acceso al Módulo

**Ruta de acceso**: Backoffice > Torneos y Bonos > Descuentos Lealtad

***

### 2. 🖼️ Visualización

<figure><img src="../../../.gitbook/assets/image (10).png" alt=""><figcaption><p>Figura#1: Captura de pantalla seccion decuentos de lealtad.</p></figcaption></figure>

***

### 3. 🧑‍💻 Acciones de usuario

<table><thead><tr><th width="156.22222900390625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="descuentos-lealtad.md#id-3.1.-filtros"><strong>Filtrar</strong></a></td><td>Permite aplicar criterios de búsqueda para visualizar únicamente los descuentos de premios que cumplen con las condiciones seleccionadas.</td></tr><tr><td><a href="descuentos-lealtad.md#id-3.3.-tabla-de-descuentos"><strong>Visualizar y gestionar descuentos</strong></a></td><td>Permite visualizar una tabla con los descuentos válidos según los filtros aplicados y gestionarlos mediante acciones individuales por cada descuento.</td></tr><tr><td><a href="descuentos-lealtad.md#id-3.2.-crear-nuevo-descuento"><strong>Crear nuevo descuento</strong></a></td><td>Permite crear un nuevo descuento definiendo sus condiciones, valores y vigencia, para su posterior aplicación y gestión dentro del sistema.</td></tr></tbody></table>

#### 3.1. 🔎 Filtros

<table><thead><tr><th width="174.333251953125">Filtro</th><th width="140.22216796875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID del descuento</code></strong></td><td>Numérico</td><td>Permite filtrar utilizando el identificador único del descuento.</td></tr><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Calendario</td><td>Define la fecha inicial para consultar los descuentos registrados dentro del período seleccionado.</td></tr><tr><td><strong><code>Fecha de fin</code></strong></td><td>Calendario</td><td>Define la fecha final para consultar los descuentos registrados dentro del período seleccionado.</td></tr><tr><td><strong><code>Estado del descuento</code></strong></td><td>Lista desplegable</td><td>Filtra por los descuentos según su estado actual, (<em>activo o inactivo</em>).</td></tr></tbody></table>

#### 3.2. ➕ Crear nuevo descuento

Para crear un descuento, ubique el botón en la parte superior derecha. Al hacer clic, se abrirá una ventana donde se deberá configurar la siguiente información.

<table data-full-width="false"><thead><tr><th width="179.66668701171875">Campo</th><th width="134.77783203125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Indica el país en el que aplicará el descuento.</td></tr><tr><td><strong><code>Fecha de inicial</code></strong></td><td>Selector de fecha</td><td>Define la fecha a partir de la cual el descuento estará vigente.</td></tr><tr><td><strong><code>Fecha de final</code></strong></td><td>Selector de fecha</td><td>Define la fecha hasta la cual el descuento estará vigente.</td></tr><tr><td><strong><code>Asignacion de premio</code></strong></td><td>Lista desplegable múltiple</td><td><p>Permite seleccionar uno o varios premios de la tienda de lealtad a los que se aplicará el descuento.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> </p><p>No es posible aplicar un descuento a un premio que ya tenga un descuento activo en el mismo período. En caso de intentar seleccionar un descuento ya aplicado, el sistema mostrará un mensaje de error.</p></div></td></tr><tr><td><strong><code>Porcentaje</code></strong> </td><td>Numérico</td><td><p>Define el porcentaje de descuento que se aplicará.<br>Solo se permiten valores enteros entre 1% y 100%; no se aceptan números decimales.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong><br>Si un premio de lealtad tiene un valor de <strong>100 puntos</strong> y se configura un descuento del <strong>23%</strong>, el sistema aplicará un descuento de <strong>23 puntos</strong>, por lo que el valor final del premio será de <strong>77 puntos</strong>. Este será el valor que el usuario visualizará, ya que el descuento se muestra aplicado.</p></div></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Define el nombre con el que se identificará el descuento en la plataforma.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Escribe una descripción del descuento, indicando su propósito o condiciones.</td></tr></tbody></table>

#### 3.3. 👁️‍🗨️ Lista de descuentos&#x20;

Permite visualizar el listado de descuentos creados según los filtros aplicados y gestionarlos mediante acciones específicas disponibles para cada descuento.

<table data-full-width="false"><thead><tr><th width="120.666748046875">Campos</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Accion</code></strong></td><td><p>Permite gestionar el descuento mediante las siguientes acciones:</p><p>-🔍 <strong>Ver premios impactados:</strong> Accede a una pestaña donde se listan los premios afectados por el descuento.<br>-👁️ <strong>Inactivar descuento:</strong> Permite desactivar el descuento cuando ya no se desea que esté vigente.<br>-🖋️ <strong>Detalle del descuento:</strong> Permite visualizar la información y configuración del descuento.</p></td></tr><tr><td><strong><code>Id descuento</code></strong></td><td>Identificador único asignado al descuento.</td></tr><tr><td><strong><code>Nombre del descuento</code></strong></td><td>Nombre asignado al descuento.</td></tr><tr><td><strong><code>Fecha inicio</code></strong></td><td>Muestra la fecha a partir de la cual el descuento está o estuvo activo.</td></tr><tr><td><strong><code>Fecha fin</code></strong></td><td>Indica la fecha de finalización del descuento en la tienda de lealtad.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Muestra el estado en el que se encuentra actualmente el descuento (<em>Activo / Inactivo</em>)</td></tr></tbody></table>

***

### 4. Aplicación y funcionamiento

{% stepper %}
{% step %}
#### Creación del descuento

Una vez creado y guardado el descuento, este se aplicará automáticamente en la tienda de lealtad durante el período de vigencia configurado.
{% endstep %}

{% step %}
#### Visualización del descuento activo

Mientras el descuento esté activo:

* El precio del premio en puntos se actualizará automáticamente en la tienda.
* El usuario verá el valor reducido sin necesidad de realizar ninguna acción adicional.
{% endstep %}

{% step %}
#### Canjeó de premio

Si un cliente canjea el premio durante el período del descuento:

* Se descontarán los puntos correspondientes al valor reducido.
{% endstep %}

{% step %}
#### Finalización del descuento

Cuando el período del descuento finaliza:

* El precio del premio vuelve automáticamente a su valor original en la tienda.
* No se requiere ninguna configuración adicional.
{% endstep %}
{% endstepper %}

***

### 5. ✅ Validaciones y reglas del negocio

* Los campos que contienen un <mark style="color:red;">\*</mark> son obligatorios para la creación de un nuevo descuento.
* Únicamente los usuarios con permisos podrán hacer uso de este módulo.

***

### 6. 🕐 Control de Versiones

| Versión | Fecha      | Autor           | Cambios Realizados     |
| ------- | ---------- | --------------- | ---------------------- |
| 1.0     | 02/01/2026 | David Velasquez | Documento inicial      |
| 1.1     | 15/01/2025 | Karol Navia     | Mejoras en informacion |
