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

# Flujo de Creación – Sorteo para usuarios lealtad.

<mark style="color:$info;">En este manual se describe el flujo de creación del sorteo dirigido a usuarios de lealtad, detallando únicamente los campos y configuraciones específicos de este tipo.</mark>\ <mark style="color:$info;">Para la configuración general de sorteos, consultar el</mark> [<mark style="color:$info;">manual Crear sorteo</mark>](https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-sorteo)<mark style="color:$info;">.</mark>

***

### 1. Resumen del Tipo de Sorteo

Este tipo de sorteo está diseñado para campañas de fidelización y restringe la participación exclusivamente a usuarios que pertenecen a niveles de lealtad previamente configurados.

Se utiliza cuando se requiere segmentar el acceso al sorteo según criterios definidos dentro del programa de lealtad, permitiendo ejecutar dinámicas diferenciadas y otorgar beneficios exclusivos por nivel.

Para el usuario final, implica acceso condicionado según su estatus dentro del programa, incentivando la permanencia y el mantenimiento de su nivel.

***

#### 2. Campos de Configuración

Los siguientes campos son obligatorios para la creación de un sorteo dirigido a usuarios de lealtad. Aunque el formulario incluye opciones adicionales de personalización, los campos descritos a continuación son los mínimos requeridos para su correcto funcionamiento.

<table><thead><tr><th width="128">Campo</th><th width="296">Descripción</th><th width="326">Recomendación para diligenciamiento</th></tr></thead><tbody><tr><td><strong><code>Fechas</code></strong></td><td>Define el periodo de vigencia del sorteo a través de la configuración de <strong><code>Fecha inicial</code></strong> y <strong><code>Fecha fina</code>l</strong>.</td><td>Configurar según la duración planificada de la campaña, asegurando coherencia con los objetivos de activación y cierre del sorteo.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Identificador del sorteo visible en la plataforma.</td><td>Utilizar un nombre representativo de la campaña de usuarios de lealtad que permita su fácil identificación operativa.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Determina la prioridad del sorteo frente a otros sorteos activos de forma simultánea. A mayor valor, mayor prioridad de ejecución.</td><td>Definir según la criticidad de la campaña y su prioridad dentro del ecosistema de sorteos activos.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Información complementaria del sorteo que será visible para los usuarios en la plataforma de Usuarios Online.</td><td>Incluir detalles claros sobre la dinámica del sorteo, especialmente enfocados en beneficios o condiciones del programa de lealtad.</td></tr><tr><td><strong><code>Es para?</code></strong></td><td>Define el tipo de segmentación o campaña a la que estará asociado el sorteo.</td><td>Seleccionar obligatoriamente <strong>“Niveles de lealtad”</strong> para habilitar la lógica de segmentación por niveles.</td></tr><tr><td><strong><code>Niveles disponibles</code></strong></td><td>Define los niveles de lealtad que tendrán acceso al sorteo. Solo los usuarios pertenecientes a los niveles seleccionados podrán participar.</td><td><p>Seleccionar uno o varios niveles según la segmentación definida. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Si no se selecciona ningún nivel, no se permitirá crear el sorteo.</p></div></td></tr><tr><td><strong><code>Usuario debe suscribirse?</code></strong></td><td>Indica si el usuario debe inscribirse manualmente al sorteo para comenzar a acumular Stikers.</td><td><p></p><ul><li>Si se selecciona la opción "<strong>Si</strong>" el usuario empezará a sumar Stikers en el sorteo luego de dar clic en "<strong>participar ahora</strong>" <em>(si cumple con el nivel lealtad).</em></li><li>Si se selecciona "<strong>No</strong>" el usuario entrará a participar en el sorteo automáticamente si cumple con las condiciones configuradas y los niveles lealtad.</li></ul></td></tr><tr><td><strong><code>Es con stikers?</code></strong></td><td>Determina si la participación del sorteo se basa en acumulación de <strong>Stikers</strong> o en otra mecánica equivalente.</td><td>Seleccionar obligatoriamente "<strong>Si</strong>" ya que actualmente no hay funcionamiento de sorteos sin Stikers.</td></tr><tr><td><strong><code>Tipo producto</code></strong></td><td>Define las <a href="https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#vertical">verticales </a><em>(Sportsbook, Casino, Casino en vivo, Virtuales)</em> desde las cuales el usuario podrá generar acumulación de Stikers.</td><td>Seleccionar las verticales aplicables según la campaña, teniendo en cuenta que cada vertical tiene ciertas configuraciones, se recomienda validar <a href="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-sorteo/con-stickers.">manual general</a>.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Define el comportamiento de acumulación de Stikers y la asignación de premios.</td><td>Las configuraciones disponibles son generales, pero contienen campos obligatorios, se recomienda validar el <a href="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-sorteo#id-4.1.-configuracion-por-moneda">manual general</a>.</td></tr></tbody></table>

***

### 3. Configuraciones Requeridas en Otras Plataformas

#### 🔹 SiteBuilder

* Es necesario que existan niveles de lealtad configurados para los usuarios desde [SiteBuilder](https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/promocionales/niveles-de-lealtad.), para el correcto funcionamiento del sorteo.
* Si no existen niveles configurados para el Partner y País seleccionados, Se visualizará un pop-up indicando que no hay niveles de lealtad disponibles para esa configuración.

***

### 4. Usuarios Online

* La participación del sorteo se puede realizar y visualizar desde la plataforma Usuarios Online en el módulo de [**sorteos**](https://virtualsoft.gitbook.io/manuales/usuarios/usuarios-online/manual-de-plataforma/sorteos)

**¿Cómo participar en un sorteo?**

{% stepper %}
{% step %}
**Validar en la plataforma que el sorteo esté activo.**
{% endstep %}

{% step %}
**Validar que se cumpla con el nivel lealtad para poder participar en el sorteo**
{% endstep %}

{% step %}
**Inscribirse manualmente en el sorteo**
{% endstep %}

{% step %}
**Realizar apuestas que cumplan con los criterios para obtener Stikers**
{% endstep %}

{% step %}
**Si se obtiene la cantidad de Stikers necesarios para un premio, se participa en la posibilidad de obtener dicho premio.**
{% endstep %}
{% endstepper %}

***

### 5. Reglas y Validaciones

<details>

<summary><strong>5.1 Participación según nivel de lealtad</strong></summary>

* Solo los usuarios que cumplan con al menos uno de los niveles configurados podrán acumular puntos en el sorteo.
* Los usuarios que no cumplan el nivel podrán visualizar el sorteo, pero al intentar participar verán un pop-up informativo indicando que no cumplen la condición.
* La activación o inactivación del usuario por nivel es funcional _(afecta acumulación)_, no visual.

</details>

<details>

<summary><strong>5.2 Cambios de nivel durante el sorteo</strong></summary>

* Si un usuario pierde el nivel requerido después de haberse inscrito, su inscripción se mantiene, pero la acumulación de puntos queda en pausa.
* Sus jugadas no sumarán hasta que recupere el nivel requerido.
* Al recuperarlo, la participación se reactiva sin efecto retroactivo.
* Si el usuario asciende a un nivel superior válido para el sorteo, podrá continuar participando sin necesidad de nueva inscripción.

</details>

<details>

<summary><strong>5.3 Ascenso a niveles con otros sorteos activos</strong></summary>

Si un usuario asciende a un nivel superior que tenga sorteos activos configurados para ese nivel:

* Podrá participar tanto en el sorteo de su nivel anterior como en el del nuevo nivel.
* Si los sorteos pertenecen a diferentes verticales, podrá optar a ganar en ambos.
* Si pertenecen a la misma vertical, figurará en ambos sorteos; sin embargo, los stickers acumulados aplicarán únicamente al sorteo correspondiente a su último nivel alcanzado.

</details>

<details>

<summary><strong>5.4 Proceso de premiación</strong></summary>

* Los niveles de lealtad no afectan el proceso de premiación.
* La asignación de premios depende exclusivamente del ranking final.

</details>

***

### 6. Control de Versiones

<details>

<summary>🕛Historial de versiones</summary>

<table><thead><tr><th width="108">Versión</th><th width="133">Fecha</th><th>Autor</th><th width="271">Descripción del Cambio</th></tr></thead><tbody><tr><td>1.0</td><td>15/05/2026</td><td>Ronald Peláez</td><td>Documento inicial</td></tr></tbody></table>

</details>

***
