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

# Visualizar multiplicador lealtad

<mark style="color:$info;">Permite consultar y administrar los multiplicadores de puntos de lealtad creados en la plataforma. Se utiliza para revisar su configuración, inactivarlos y conocer las apuestas en las que se aplicaron.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Torneos y Bonos > Menú lateral izquierdo > Multiplicador lealtad

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (274) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla visualización de multiplicadores lealtad.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="156.22222900390625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="visualizar-multiplicador-lealtad.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para visualizar únicamente los multiplicadores que cumplen con las condiciones seleccionadas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="visualizar-multiplicador-lealtad.md#id-5.-resultados-de-consulta"><strong>Buscar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra en la tabla de resultados los multiplicadores válidos, que pueden gestionarse mediante acciones individuales por cada multiplicador.</td></tr><tr><td><a href="../crear-eventos./multiplicador-lealtad.md"><strong>Crear Multiplicador</strong></a></td><td>Desde el botón <strong>Crear Multiplicador</strong> se accede al formulario para crear un nuevo multiplicador.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="156.11102294921875">Campo</th><th width="140">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id de la campaña</code></strong></td><td>Campo numérico</td><td>Localiza un multiplicador específico a partir de su identificador único.</td></tr><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Calendario</td><td>Define la fecha inicial del período en el que se consultan los multiplicadores.</td></tr><tr><td><strong><code>Fecha de fin</code></strong></td><td>Calendario</td><td>Delimita la fecha final del período en el que se consultan los multiplicadores.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Restringe la consulta según el estado actual del multiplicador <em>(Activo o Inactivo)</em>.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega la tabla **Lista de Multiplicadores** con los multiplicadores que cumplen con los filtros aplicados. Desde esta tabla, cada multiplicador puede gestionarse mediante las acciones específicas disponibles.

<table><thead><tr><th width="150">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acción</code></strong></td><td>Reúne las acciones disponibles para gestionar cada multiplicador. Las acciones se describen a continuación.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
**Acciones por multiplicador**

<table><thead><tr><th width="160">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>👁️ Ver Configuración</code></strong></td><td>Permite visualizar toda la configuración definida durante la creación del multiplicador.</td></tr><tr><td><strong><code>⏹ Inactivar Campaña</code></strong></td><td>Permite desactivar el multiplicador instantáneamente de todas las apuestas.</td></tr><tr><td><strong><code>🔎 Ver detalles</code></strong></td><td>Permite visualizar una tabla con información sobre las apuestas que fueron afectadas por el multiplicador.<br> <a href="visualizar-multiplicador-lealtad.md#detalles-del-multiplicador" class="button secondary">Detalles del multiplicador</a></td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="150">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Nombre asignado al multiplicador.</td></tr><tr><td><strong><code>Fecha inicio</code></strong></td><td>Fecha a partir de la cual el multiplicador está o estuvo vigente.</td></tr><tr><td><strong><code>Fecha fin</code></strong></td><td>Fecha en la que finaliza la vigencia del multiplicador.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del multiplicador <em>(Activo o Inactivo)</em>.</td></tr></tbody></table>

<details>

<summary>🔽 Detalles del multiplicador</summary>

Al utilizar la acción **Ver detalles**, se muestra una tabla con las apuestas en las que se aplicó el multiplicador:

<table><thead><tr><th width="147">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Cliente</code></strong></td><td>Identificador único del usuario al que se le aplicó el multiplicador.</td></tr><tr><td><strong><code>Nombre Cliente</code></strong></td><td>Nombre del usuario al que se le aplicó el multiplicador.</td></tr><tr><td><strong><code>ID Apuesta</code></strong></td><td>Identificador único de la apuesta cuyos puntos se multiplicaron.</td></tr><tr><td><strong><code>Puntos Base</code></strong></td><td>Puntos que obtuvo el usuario por la apuesta antes de aplicar el multiplicador.</td></tr><tr><td><strong><code>Multiplicador</code></strong></td><td>Valor por el que se multiplicaron los puntos base.</td></tr><tr><td><strong><code>Puntos finales</code></strong></td><td><p>Total de puntos obtenidos con el multiplicador ya aplicado.</p><p><strong>Fórmula:</strong><br><em>Puntos finales = Puntos Base × Multiplicador</em></p></td></tr></tbody></table>

</details>

***

### 6. Aplicación y funcionamiento

{% stepper %}
{% step %}
#### Creación del multiplicador

Una vez creado y guardado, el multiplicador se activa automáticamente y queda vigente durante el período promocional configurado.
{% endstep %}

{% step %}
#### Funcionamiento en apuestas

Las apuestas realizadas dentro del período de vigencia generan puntos de lealtad multiplicados según el valor definido para su tipo de apuesta. Las apuestas realizadas fuera de este período acumulan puntos de forma estándar, sin multiplicador.
{% endstep %}

{% step %}
#### Registro y reporte

Cada apuesta impactada por el multiplicador queda registrada en:

* El [historial de puntos del usuario](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/readme/jugadores/reportes-seccion-jugadores/historial-de-puntos).
* El detalle del multiplicador, para fines de control y seguimiento.
{% endstep %}

{% step %}
#### Finalización del multiplicador

Al terminar el período de vigencia o al inactivarse manualmente, el multiplicador deja de aplicarse. Las apuestas realizadas después **no reciben puntos multiplicados**.
{% endstep %}
{% endstepper %}

***

### 7. Validaciones y reglas del negocio:

* Al inactivar un multiplicador, deja de aplicarse de inmediato a las nuevas apuestas.
* Únicamente los usuarios con permisos pueden hacer uso de este módulo.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21/01/2026</td><td>Ronald Peláez</td><td>Documento inicial.</td></tr><tr><td>1.1</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
