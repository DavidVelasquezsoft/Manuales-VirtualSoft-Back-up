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

# Multiplicador Lealtad

<mark style="color:$info;">Permite crear multiplicadores temporales de puntos de lealtad para cada tipo de apuesta de la plataforma. Se utiliza para que, durante un período promocional, las apuestas generen más puntos de lealtad de lo habitual, para todos los jugadores o solo para los usuarios cargados en un archivo.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Torneos y Bonos > Crear Multiplicador Lealtad

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (273) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla creación multiplicador lealtad.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="156.22222900390625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="multiplicador-lealtad.md#id-4.-formulario-de-creacion"><strong>Crear Multiplicador</strong></a></td><td>Envía el formulario con la información diligenciada y crea el multiplicador, siempre que se cumplan las validaciones del sistema.</td></tr></tbody></table>

***

### 4. Formulario de creación

<table><thead><tr><th width="159.00003051757812">Campo</th><th width="134.77783203125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha Inicial</code></strong></td><td>Calendario</td><td>Define la fecha a partir de la cual el multiplicador estará vigente.</td></tr><tr><td><strong><code>Fecha Final</code></strong></td><td>Calendario</td><td><p>Define la fecha hasta la cual el multiplicador estará vigente.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Debe ser posterior a la <strong><code>Fecha Inicial</code></strong>; de lo contrario, el sistema muestra mensaje de error.</p></div></td></tr><tr><td><strong><code>Nombre del Multiplicador</code></strong></td><td>Campo de texto</td><td>Nombre con el que se identificará el multiplicador en la plataforma.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Campo numérico</td><td><p>Define qué multiplicador se aplica cuando hay varios vigentes en el mismo período. Un número mayor indica mayor prioridad.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si hay dos multiplicadores configurados con las siguientes prioridades en el mismo período de tiempo:</p><ul><li><strong>Multiplicador A:</strong> 1</li><li><strong>Multiplicador B:</strong> 2</li></ul><p>El sistema da preferencia al <strong>Multiplicador B</strong>, ya que tiene la prioridad más alta.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Detalle o condiciones del multiplicador, para su correcta identificación dentro del programa de lealtad.</td></tr><tr><td><strong><code>Tabla de multiplicadores</code></strong></td><td>Campo numérico</td><td><p>Define el valor por el que se multiplicarán los puntos de lealtad en cada tipo de apuesta: <em>Casino, Casino en Vivo, Virtuales, Deportivas Simple y Combinada 2 a Combinada 10</em>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Notas:</strong></p><ul><li>Solo se permiten valores numéricos enteros.</li><li>Debe asignarse un multiplicador a por lo menos un tipo de apuesta.</li></ul></div></td></tr><tr><td><strong><code>Carga de usuarios por CSV</code></strong></td><td>Archivo CSV</td><td><p>Carga un archivo <a href="https://virtualsoft.gitbook.io/untitled/glosario#csv">CSV</a> con los ID de los usuarios a los que se aplicará el multiplicador.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si no se carga ningún archivo, el multiplicador se aplica a todos los jugadores de la plataforma.</p></div></td></tr></tbody></table>

Una vez completado el formulario, se utiliza el botón **Crear Multiplicador** para crear el multiplicador. El multiplicador creado se consulta desde el siguiente módulo:

{% content-ref url="../visualizar-eventos./visualizar-multiplicador-lealtad.md" %}
[visualizar-multiplicador-lealtad.md](../visualizar-eventos./visualizar-multiplicador-lealtad.md)
{% endcontent-ref %}

***

### 5. Validaciones y reglas del negocio:

* Los campos marcados con <mark style="color:red;">\*</mark> son obligatorios para crear un multiplicador.
* La **Fecha Final** debe ser posterior a la **Fecha Inicial**.
* Si existen dos multiplicadores con el mismo período y la misma prioridad, se aplica el que se creó primero.
* Únicamente los usuarios con permisos pueden hacer uso de este módulo.

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>05/01/2026</td><td>David Velasquez</td><td>Documento inicial.</td></tr><tr><td>1.1</td><td>21/01/2026</td><td>Ronald Peláez</td><td>Refinamiento de manual.</td></tr><tr><td>1.2</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
