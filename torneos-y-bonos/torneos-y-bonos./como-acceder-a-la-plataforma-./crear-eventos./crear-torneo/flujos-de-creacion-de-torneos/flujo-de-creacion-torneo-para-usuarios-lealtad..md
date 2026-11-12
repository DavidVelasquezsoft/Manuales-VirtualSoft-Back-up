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

# Flujo de Creación – Torneo para usuarios lealtad.

<mark style="color:$info;">En este manual se describe el flujo de creación del torneo dirigido a usuarios de lealtad, detallando únicamente los campos y configuraciones específicos de este tipo de torneo.</mark>\ <mark style="color:$info;">Para la configuración general de torneo, consultar el manual</mark> [<mark style="color:$info;">Crear torneo</mark>](https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-torneo)<mark style="color:$info;">.</mark>

***

### 1. Resumen del Tipo de Torneo

Este tipo de torneo está diseñado para campañas de fidelización y restringe la participación exclusivamente a usuarios que pertenecen a niveles de lealtad previamente configurados.

Se utiliza cuando se requiere segmentar el acceso al torneo según criterios definidos dentro del programa de lealtad, permitiendo ejecutar dinámicas diferenciadas y otorgar beneficios exclusivos por nivel.

Para el usuario final, implica acceso condicionado según su estatus dentro del programa, incentivando la permanencia y el mantenimiento de su nivel.

***

### 2. Campos de Configuración

Los siguientes campos son obligatorios para la creación de un torneo dirigido a usuarios de lealtad. Aunque el formulario incluye opciones adicionales de personalización, los campos descritos a continuación son los mínimos requeridos para su correcto funcionamiento.

<table><thead><tr><th width="147.6666259765625">Campo</th><th>Descripción</th><th width="306">Recomendación a para diligenciarlo</th></tr></thead><tbody><tr><td><strong><code>Fechas</code></strong></td><td>Establece la vigencia del torneo desde las configuraciones <strong><code>Fecha inicial</code></strong> y <strong><code>Fecha final</code></strong>.</td><td>A preferencia de la duración de la campaña.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre diferencial del torneo</td><td>Nombre alusivo a la campaña de usuarios lealtad.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Define la prioridad de evaluación del torneo frente a otros torneos activos en simultáneo. A mayor número, mayor prioridad.</td><td>Varía según la cantidad de campañas activas y la prioridad que se le desea dar al torneo que se está creando</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Detalles adicionales del torneo que se visualizará en la plataforma usuarios online.</td><td>Información adicional sobre los puntos lealtad y el torneo creado.</td></tr><tr><td><strong><code>Es para?</code></strong></td><td>Define la campaña a la cual estará asociado el torneo.</td><td>En la lista desplegable se debe seleccionar "<strong>niveles de lealtad</strong>" para que el formulario se adapte a los campos de torneo lealtad.</td></tr><tr><td><strong><code>Usuario debe suscribirse?</code></strong></td><td>Indica si el usuario debe inscribirse manualmente al sorteo para comenzar a acumular Stikers.</td><td><p></p><ul><li><strong>Si:</strong> los usuarios que cumplan el nivel requerido deberán realizar la suscripción manualmente para participar.</li><li><strong>No:</strong> cualquier usuario que cumpla el nivel configurado y realice una acción válida para sumar puntos quedará registrado automáticamente como participante.</li></ul></td></tr><tr><td><strong><code>Niveles disponibles</code></strong></td><td>Define los niveles de lealtad que tendrán acceso al torneo. Solo los usuarios pertenecientes a los niveles seleccionados podrán participar.</td><td><p></p><p>Seleccionar uno o varios niveles según la segmentación definida. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: </p><ul><li>Si no se selecciona ningún nivel, no se permitirá crear el torneo.</li><li>Si no existen niveles configurados para el Partner y País seleccionados, se visualizará un pop-up indicando que no hay niveles de lealtad disponibles para esa configuración.</li></ul></div></td></tr><tr><td><strong><code>Tipo producto</code></strong></td><td>Define las verticales (Sportsbook, Casino, Casino en vivo, Virtuales) desde las cuales el usuario podrá generar acumulación de Stikers.</td><td>Seleccionar las verticales aplicables según la campaña, teniendo en cuenta que cada vertical tiene ciertas configuraciones, se recomienda validar <a href="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-torneo#tipo-de-producto">manual general</a>.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Define el comportamiento de acumulación de Stikers y la asignación de premios.</td><td>Las configuraciones disponibles son generales, pero contienen campos obligatorios, se recomienda validar el <a href="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-torneo#id-3.1-moneda">manual general</a>.</td></tr></tbody></table>

***

### 3. Configuraciones Requeridas en Otras Plataformas

#### 🔹 SiteBuilder

* Es necesario que existan niveles de lealtad configurados para los usuarios desde [SiteBuilder](https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/promocionales/niveles-de-lealtad.), para el correcto funcionamiento del sorteo.
* Si no existen niveles configurados para el Partner y País seleccionados, Se visualizará un pop-up indicando que no hay niveles de lealtad disponibles para esa configuración.

***

### 4. Usuarios Online

* La participación del torneo se puede realizar y visualizar desde la plataforma Usuarios Online en el módulo de [**Torneos**](https://virtualsoft.gitbook.io/manuales/usuarios/usuarios-online/manual-de-plataforma/torneos)

**¿Cómo participar en un sorteo?**

{% stepper %}
{% step %}
**Validar en la plataforma que el Torneo esté activo.**
{% endstep %}

{% step %}
**Validar que se cumpla con el nivel lealtad para poder participar en el Torneo.**
{% endstep %}

{% step %}
**Inscribirse manualmente en el torneo o validar la participación automática** _(depende como esté configurado)._
{% endstep %}

{% step %}
**Realizar apuestas que cumplan con los criterios para obtener puntos.**
{% endstep %}

{% step %}
**A medida que vas obteniendo puntos va subiendo en el ranking del torneo.**
{% endstep %}

{% step %}
**Al final del torneo se rifan los premios según el ranking.**
{% endstep %}
{% endstepper %}

***

### 5. Reglas y Validaciones

<details>

<summary><strong>5.1. Configuración por niveles de lealtad</strong></summary>

* Cuando la opción **“Niveles de Lealtad”** no esté seleccionada, el torneo conservará el comportamiento actual sin aplicar cambios en su funcionamiento.
* Al seleccionar la opción **“Niveles de Lealtad”**, solo se visualizarán los niveles previamente configurados para el Partner y el País seleccionados.
* El torneo podrá configurarse para uno o varios niveles de lealtad.

</details>

<details>

<summary><strong>5.2. Participación según niveles configurados</strong></summary>

* Solo los usuarios que pertenezcan a alguno de los niveles configurados podrán acumular puntos dentro del torneo.
* Los usuarios que no cumplan con el nivel requerido podrán visualizar el torneo, pero al intentar suscribirse o al abrir el detalle del torneo se mostrará un pop-up informativo indicando que solo los usuarios con los niveles configurados pueden participar.

</details>

<details>

<summary><strong>5.3. Cambios de nivel durante la vigencia del torneo</strong></summary>

* Si un usuario se suscribe cumpliendo el nivel requerido y posteriormente pierde dicho nivel, la inscripción debe mantenerse activa.
  * Los puntos acumulados previamente deben conservarse.
  * Mientras el usuario permanezca por debajo del nivel requerido, las nuevas jugadas no deben generar acumulación de puntos.
* Si el usuario recupera nuevamente el nivel requerido antes de finalizar el torneo, la acumulación de puntos debe reactivarse automáticamente.
  * La reactivación no debe aplicar efecto retroactivo sobre las jugadas realizadas durante el periodo en que el usuario no cumplía la condición.
* Si el usuario asciende a un nivel superior válido para el torneo, podrá continuar participando sin necesidad de realizar una nueva suscripción.
* Si el usuario finaliza el torneo sin recuperar el nivel requerido, conservará su inscripción y los puntos acumulados hasta el último momento en que cumplió la condición de nivel.

</details>

<details>

<summary><strong>5.4. Compatibilidad con torneos privados</strong></summary>

* Si el torneo es privado y utiliza carga de usuarios mediante CSV, el sistema debe validar adicionalmente que el usuario cumpla con alguno de los niveles configurados antes de acumular puntos.
* La inclusión de un usuario en el archivo CSV no omite ni reemplaza la validación de niveles de lealtad configurada para el torneo. El usuario deberá cumplir igualmente con las condiciones de nivel establecidas para poder participar correctamente.

</details>

<details>

<summary><strong>5.5. Proceso de premiación</strong></summary>

* Los niveles de lealtad no afectan el proceso de premiación del torneo.
* La asignación de premios depende exclusivamente del ranking final del torneo.

</details>

***

### 6. Control de Versiones

<details>

<summary>🕛Historial de versiones</summary>

<table><thead><tr><th width="108">Versión</th><th width="133">Fecha</th><th>Autor</th><th width="271">Descripción del Cambio</th></tr></thead><tbody><tr><td>1.0</td><td>20/05/2026</td><td>Ronald Peláez</td><td>Documento inicial</td></tr></tbody></table>

</details>

***
