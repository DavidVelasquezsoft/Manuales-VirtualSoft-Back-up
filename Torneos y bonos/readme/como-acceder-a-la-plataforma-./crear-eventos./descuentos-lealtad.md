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

# Descuentos Lealtad

<mark style="color:$info;">Permite configurar y administrar descuentos sobre los premios de la tienda de lealtad, reduciendo temporalmente su costo en puntos durante un período definido. Se utiliza para impulsar el canje de premios en campañas o fechas especiales sin modificar el valor original de cada premio.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Torneos y Bonos > Descuentos Lealtad

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (10) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Descuentos Lealtad.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="156.22222900390625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="descuentos-lealtad.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para visualizar únicamente los descuentos de premios que cumplen con las condiciones seleccionadas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="descuentos-lealtad.md#id-5.-resultados-de-consulta"><strong>Buscar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra en la tabla de resultados los descuentos válidos, que pueden gestionarse mediante acciones individuales por cada descuento.</td></tr><tr><td><a href="descuentos-lealtad.md#id-6.-crear-descuento"><strong>Crear Descuento</strong></a></td><td>Permite crear un nuevo descuento definiendo sus condiciones, valores y vigencia, para su posterior aplicación y gestión dentro del sistema.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="174.333251953125">Campo</th><th width="140.22216796875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Descuento</code></strong></td><td>Campo numérico</td><td>Localiza un descuento específico a partir de su identificador único.</td></tr><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Calendario</td><td>Define la fecha inicial del período en el que se consultan los descuentos.</td></tr><tr><td><strong><code>Fecha de fin</code></strong></td><td>Calendario</td><td>Delimita la fecha final del período en el que se consultan los descuentos.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Restringe la consulta según el estado actual del descuento <em>(Activo o Inactivo)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega la tabla **Lista de Descuentos** con los descuentos que cumplen con los filtros aplicados. Desde esta tabla, cada descuento puede gestionarse mediante las acciones específicas disponibles.

<table><thead><tr><th width="180">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acción</code></strong></td><td><p>Reúne las acciones disponibles para gestionar cada descuento:</p><ul><li>🔍 <strong>Ver premios impactados:</strong> Accede a una pestaña donde se listan los premios afectados por el descuento.</li><li>👁️ <strong>Inactivar descuento:</strong> Permite desactivar el descuento cuando ya no se desea que esté vigente.</li><li>🖋️ <strong>Detalle del descuento:</strong> Permite visualizar la información y configuración del descuento.</li></ul></td></tr><tr><td><strong><code>ID Descuento</code></strong></td><td>Identificador único asignado al descuento.</td></tr><tr><td><strong><code>Nombre Descuento</code></strong></td><td>Nombre con el que se identifica el descuento.</td></tr><tr><td><strong><code>Fecha Inicio</code></strong></td><td>Fecha a partir de la cual el descuento está o estuvo vigente.</td></tr><tr><td><strong><code>Fecha Fin</code></strong></td><td>Fecha en la que finaliza la vigencia del descuento en la tienda de lealtad.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del descuento <em>(Activo o Inactivo)</em>.</td></tr></tbody></table>

***

### 6. Crear descuento

Al utilizar el botón **Crear Descuento**, ubicado en la parte superior derecha, se abre un formulario con los siguientes campos:

<table><thead><tr><th width="179.66668701171875">Campo</th><th width="134.77783203125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Indica el país en el que aplicará el descuento.</td></tr><tr><td><strong><code>Fecha inicial</code></strong></td><td>Calendario</td><td>Define la fecha a partir de la cual el descuento estará vigente.</td></tr><tr><td><strong><code>Fecha final</code></strong></td><td>Calendario</td><td>Define la fecha hasta la cual el descuento estará vigente.</td></tr><tr><td><strong><code>Asignación de premio</code></strong></td><td>Lista desplegable</td><td><p>Selecciona uno o varios premios de la tienda de lealtad a los que se aplicará el descuento.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> No es posible aplicar un descuento a un premio que ya tenga un descuento activo en el mismo período. Si se intenta seleccionar un premio con un descuento ya aplicado, el sistema muestra mensaje de error.</p></div></td></tr><tr><td><strong><code>Porcentaje</code></strong></td><td>Campo numérico</td><td><p>Define el porcentaje de descuento que se aplicará sobre el costo en puntos del premio. Solo se permiten valores enteros entre 1% y 100%; no se aceptan números decimales.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si un premio de lealtad tiene un valor de <strong>100 puntos</strong> y se configura un descuento del <strong>23%</strong>, el sistema aplica un descuento de <strong>23 puntos</strong>, por lo que el valor final del premio es de <strong>77 puntos</strong>. Este es el valor que el usuario visualiza, ya que el descuento se muestra aplicado.</p></div></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Nombre con el que se identificará el descuento en la plataforma.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Texto que describe el propósito o las condiciones del descuento.</td></tr></tbody></table>

***

### 7. Aplicación y funcionamiento

{% stepper %}
{% step %}
#### Creación del descuento

Una vez creado y guardado, el descuento se aplica automáticamente en la tienda de lealtad durante el período de vigencia configurado.
{% endstep %}

{% step %}
#### Visualización del descuento activo

Mientras el descuento está activo:

* El costo en puntos del premio se actualiza automáticamente en la tienda.
* El usuario ve el valor reducido sin realizar ninguna acción adicional.
{% endstep %}

{% step %}
#### Canje del premio

Si el usuario canjea el premio durante el período del descuento, se descuentan los puntos correspondientes al valor reducido.
{% endstep %}

{% step %}
#### Finalización del descuento

Cuando termina el período del descuento:

* El costo del premio vuelve automáticamente a su valor original en la tienda.
* No se requiere ninguna configuración adicional.
{% endstep %}
{% endstepper %}

***

### 8. Validaciones y reglas del negocio:

* Los campos marcados con <mark style="color:red;">\*</mark> son obligatorios para crear un descuento.
* Un premio no puede tener más de un descuento activo en el mismo período.
* El porcentaje de descuento solo admite números enteros entre 1% y 100%; no se aceptan decimales.
* Únicamente los usuarios con permisos pueden hacer uso de este módulo.

***

### 9. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>02/01/2026</td><td>David Velasquez</td><td>Documento inicial.</td></tr><tr><td>1.1</td><td>15/01/2026</td><td>Karol Navia</td><td>Mejoras en información.</td></tr><tr><td>1.2</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
