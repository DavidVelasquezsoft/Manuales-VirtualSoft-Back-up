---
description: >-
  Permite crear multiplicadores de puntos de lealtad para diferentes tipos de
  apuestas en la plataforma temporalmente.
---

# Multiplicador Lealtad

### 1. Acceso al Módulo

**Ruta de acceso**: BackOffice > Torneos y Bonos > Crear Multiplicador Lealtad

***

### 2. 🖼️ Visualización

<figure><img src="../../../.gitbook/assets/image (273).png" alt=""><figcaption><p>Figura #1: Captura de pantalla creación multiplicador lealtad.</p></figcaption></figure>

***

### 3. 🧑‍💻 Acciones de usuario

<table><thead><tr><th width="156.22222900390625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="multiplicador-lealtad.md#id-3.2.-crear-nuevo-multiplicador"><strong>Crear nuevo multiplicador</strong></a></td><td>Permite crear un nuevo multiplicador definiendo sus condiciones, valores y vigencia, para su posterior aplicación y gestión dentro del sistema.</td></tr></tbody></table>

#### 3.1. ➕ Crear nuevo multiplicador

<table data-full-width="false"><thead><tr><th width="159.00003051757812">Campo</th><th width="134.77783203125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha inicial</code></strong> </td><td>Selector de fecha</td><td>Define la fecha a partir de la cual el descuento estará vigente.</td></tr><tr><td><strong><code>Fecha final</code></strong></td><td>Selector de fecha</td><td>Define la fecha hasta la cual el descuento estará vigente.</td></tr><tr><td><strong><code>Nombre del multiplicador</code></strong> </td><td>Texto</td><td>Define el nombre con el que se identificará el multiplicador en la plataforma.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Numérico</td><td><p>Define el orden de asignación de prioridad a los usuarios, un número mayor indica mayor prioridad. </p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si hay dos multiplicadores configurados con las siguientes prioridades en el mismo periodo de tiempo:</p><ul><li><strong>Multiplicador A:</strong> 1</li><li><strong>Multiplicador B:</strong> 2</li></ul><p>El sistema dará preferencia al <strong>Multiplicador B</strong>, ya que tiene la prioridad más alta.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Especifica el detalle o condiciones del multiplicador para su correcta identificación y aplicación en el programa de lealtad.</td></tr><tr><td><p></p><p><strong><code>Tabla de multiplicadores</code></strong></p></td><td>Numérico</td><td><p>Define el valor del multiplicador que se aplicará a las apuestas realizadas para cada tipo de apuesta.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Notas:</strong></p><ul><li>Solo se permiten valores numéricos enteros.</li><li>Debe asignarse un multiplicador a por lo menos un tipo de apuesta.</li></ul></div></td></tr><tr><td><strong><code>Carga de usuarios por CSV</code></strong></td><td>Archivo CSV</td><td><p>Permite cargar un archivo CSV con los IDs de los usuarios a los que se aplicará el multiplicador.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si no se carga ningún archivo, el multiplicador se aplicará a todos los jugadores de la plataforma.</p></div></td></tr></tbody></table>

Utiliza el botón "**`Crear Multiplicador`**" para enviar el formulario y crear el multiplicador.

El multiplicador creado se visualizará desde el siguiente módulo:

{% content-ref url="../visualizar-eventos./visualizar-multiplicador-lealtad.md" %}
[visualizar-multiplicador-lealtad.md](../visualizar-eventos./visualizar-multiplicador-lealtad.md)
{% endcontent-ref %}

***

### 4. ✅ Validaciones y reglas del negocio

* Los campos que contienen un <mark style="color:red;">\*</mark> son obligatorios para la creación de un nuevo descuento.
* Únicamente los usuarios con permisos podrán hacer uso de este módulo.
* En caso de que existan dos multiplicadores configurados con el mismo periodo de tiempo y prioridad, aplica el multiplicador que se haya creado primero.

***

### 5. 🕐 Control de Versiones

| Versión | Fecha      | Autor           | Cambios Realizados     |
| ------- | ---------- | --------------- | ---------------------- |
| 1.0     | 05/01/2026 | David Velasquez | Documento inicial      |
| 1.1     | 21/01/2026 | Ronald Peláez   | Refinamiento de manual |
