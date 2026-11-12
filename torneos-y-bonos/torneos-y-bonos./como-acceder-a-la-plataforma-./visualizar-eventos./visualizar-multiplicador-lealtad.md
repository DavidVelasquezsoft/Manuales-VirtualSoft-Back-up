---
description: >-
  Permite administrar multiplicadores de puntos de lealtad para diferentes tipos
  de apuestas en la plataforma temporalmente, según la configuración
  establecida.
---

# Visualizar multiplicador lealtad

### 1. Acceso al Módulo

**Ruta de acceso**: BackOffice > Torneos y Bonos > Menú lateral izquierdo > Multiplicador lealtad

***

### 2. 🖼️ Visualización

<figure><img src="../../../.gitbook/assets/image (274).png" alt=""><figcaption><p>Figura #1: Captura de pantalla visualización de multiplicadores lealtad</p></figcaption></figure>

***

### 3. 🧑‍💻 Acciones de usuario

<table><thead><tr><th width="156.22222900390625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="visualizar-multiplicador-lealtad.md#id-3.1.-filtros"><strong>Filtrar</strong></a></td><td>Permite aplicar criterios de búsqueda para visualizar únicamente los multiplicadores de premios que cumplen con las condiciones seleccionadas.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./visualizar-eventos./visualizar-multiplicador-lealtad#id-3.2.-tabla-de-multiplicadores"><strong>Visualizar y gestionar multiplicadores</strong></a></td><td>Permite visualizar una tabla con los multiplicadores válidos según los filtros aplicados y gestionarlos mediante acciones individuales por cada multiplicador.</td></tr><tr><td><strong>Crear Multiplicador</strong></td><td>Desde el botón <a href="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./multiplicador-lealtad#id-3.1.-filtros" class="button secondary">Crear Multiplicador</a> podrás acceder al formulario para crear un nuevo multiplicador.</td></tr></tbody></table>

#### 3.1. 🔎 Filtros

<table><thead><tr><th width="156.11102294921875">Filtro</th><th width="119.99993896484375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID campaña</code></strong>  </td><td>Numérico</td><td>Permite filtrar utilizando el identificador único del multiplicador.</td></tr><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Calendario</td><td>Define la fecha inicial para consultar los multiplicadores previamente creados.</td></tr><tr><td><strong><code>Fecha de fin</code></strong></td><td>Calendario</td><td>Define la fecha final para consultar los multiplicadores registrados dentro del período seleccionado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra por los multiplicadores según su estado actual, (<em>activo o inactivo</em>).</td></tr></tbody></table>

#### 3.2. 👁️‍🗨️ Tabla de multiplicadores

Permite visualizar el listado de multiplicadores creados según los filtros aplicados y gestionarlos mediante acciones específicas disponibles para cada multiplicador.

<table data-full-width="false"><thead><tr><th width="120.666748046875">Campos</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td>Permite gestionar el multiplicador mediante las siguientes acciones:<br><a href="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./visualizar-eventos./visualizar-multiplicador-lealtad#acciones-disponibles" class="button secondary">Acciones disponibles</a></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre del multiplicador</td></tr><tr><td><strong><code>Fecha inicio</code></strong></td><td>Muestra la fecha a partir de la cual el multiplicador está o estuvo activo.</td></tr><tr><td><strong><code>Fecha fin</code></strong></td><td>Indica la fecha de finalización del multiplicador en la plataforma.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Muestra el estado en el que se encuentra actualmente el multiplicador (<em>Activo / Inactivo</em>)</td></tr></tbody></table>

<details>

<summary><strong>Acciones disponibles.</strong></summary>

<table><thead><tr><th width="146.33334350585938">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>👁️ Ver Configuración</code></strong></td><td>Permite visualizar toda la configuración definida durante la creación del multiplicador.</td></tr><tr><td><strong><code>⏹ Inactivar Campaña</code></strong></td><td>Permite desactivar el multiplicador instantáneamente de todas las apuestas.</td></tr><tr><td><strong><code>🔎 Ver detalles</code></strong></td><td>Permite visualizar una tabla con información sobre las apuestas a las que fueron afectadas por el multiplicador.<br><a href="visualizar-multiplicador-lealtad.md#detalles-del-multiplicador" class="button secondary">Detalles del multiplicador</a></td></tr></tbody></table>

<a href="visualizar-multiplicador-lealtad.md#id-3.2.-tabla-de-multiplicadores" class="button secondary">Regresar</a>

</details>

<details>

<summary><strong>Detalles del multiplicador</strong></summary>

<table><thead><tr><th width="147">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Cliente</code></strong></td><td>Identificador único del usuario al cual se le aplico el multiplicador de puntos.</td></tr><tr><td><strong><code>Nombre Cliente</code></strong></td><td>Nombre del usuario al cual se le aplico el multiplicador de puntos.</td></tr><tr><td><strong><code>ID Apuesta</code></strong></td><td>Identificador único de la apuesta a la cual se le multiplicaron los puntos.</td></tr><tr><td><strong><code>Puntos Base</code></strong></td><td>Cantidad de puntos base obtenidos por el usuario antes de aplicar el multiplicador.</td></tr><tr><td><strong><code>Multiplicador</code></strong> </td><td>Indica el numero por el cual se multiplicaron los puntos base.</td></tr><tr><td><strong><code>Puntos finales</code></strong></td><td>Cantidad total de puntos obtenidos con el multiplicador ya aplicado.</td></tr></tbody></table>

</details>

***

### 4. Aplicación y funcionamiento

{% stepper %}
{% step %}
#### Creación del multiplicador

Una vez creado y guardado, el multiplicador se activa automáticamente y queda vigente durante el período promocional configurado.
{% endstep %}

{% step %}
#### Funcionamiento en apuestas.

Las apuestas realizadas dentro del período de vigencia generarán puntos de lealtad multiplicados según el valor definido y el tipo de apuesta correspondiente.\
Las apuestas efectuadas fuera de este período acumularán puntos de forma estándar, sin multiplicador.
{% endstep %}

{% step %}
#### Registro y reporte

Cada apuesta impactada por el multiplicador quedará registrada en:

* El [historial de puntos del usuario](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/historial-de-puntos).
* El detalle del multiplicador, para fines de control y seguimiento.
{% endstep %}

{% step %}
#### Finalización del multiplicador

Al finalizar el período de vigencia o al desactivarse manualmente, el multiplicador dejará de aplicarse.\
Las apuestas realizadas posteriormente **no recibirán puntos multiplicados**.
{% endstep %}
{% endstepper %}

***

### 5. ✅ Validaciones y reglas del negocio

* Únicamente los usuarios con permisos podrán hacer uso de este módulo.

***

### 6. 🕐 Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 21/01/2026 | Ronald Peláez | Documento inicial  |

***
