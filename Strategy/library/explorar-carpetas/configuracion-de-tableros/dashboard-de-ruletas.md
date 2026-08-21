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

# Dashboard de Ruletas

<mark style="color:$info;">Consulta y analiza la información relacionada con las ruletas, su participación, estados, premios entregados, usuarios y principales indicadores de desempeño.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso:** \[Pendiente de confirmar]

***

### 2.

### 3. Filtros

Los filtros generales establecen los criterios utilizados para consultar y segmentar la información presentada en el dashboard.

<table><thead><tr><th width="168.5555419921875">Campo</th><th width="160.1112060546875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Selecciona el partner asociado a la información que será consultada.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país asociado a la información que será consultada.</td></tr><tr><td><strong><code>Desde</code></strong></td><td>Fecha</td><td>Establece la fecha inicial del período de consulta.</td></tr><tr><td><strong><code>Hasta</code></strong></td><td>Fecha</td><td>Establece la fecha final del período de consulta.</td></tr><tr><td><strong><code>Estado de ruleta</code></strong></td><td>Lista desplegable</td><td>Selecciona el estado de las ruletas que serán incluidas en la consulta.</td></tr><tr><td><strong><code>Estado del giro</code></strong></td><td>Lista desplegable</td><td>Selecciona el estado del giro que será incluido en la consulta.</td></tr><tr><td><strong><code>ID ruleta</code></strong></td><td>Campo de búsqueda</td><td>Consulta la información correspondiente a un ID de ruleta específico.</td></tr><tr><td><strong><code>Nombre Ruleta</code></strong></td><td>Lista desplegable</td><td>Selecciona el nombre de la ruleta que será consultada.</td></tr><tr><td><strong><code>Tipo Premio</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de premio asociado a las ruletas que serán consultadas.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo de búsqueda</td><td>Consulta la información asociada a un usuario específico.</td></tr></tbody></table>

***

### 4. Contenido del Dashboard

El dashboard se encuentra organizado en dos vistas principales:

* #### **Indicadores**

En la parte superior se presentan los principales indicadores del dashboard.

<table><thead><tr><th width="209.6666259765625">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ruletas activas</code></strong></td><td>Presenta la cantidad de ruletas que se encuentran activas.</td></tr><tr><td><strong><code>Usuarios que han usado la ruleta</code></strong></td><td>Presenta la cantidad de usuarios que han utilizado las ruletas.</td></tr><tr><td><strong><code>Usuarios pendientes</code></strong></td><td>Presenta la cantidad de usuarios que se encuentran pendientes dentro del proceso de la ruleta.</td></tr><tr><td><strong><code>Premios Entregados</code></strong></td><td>Presenta la cantidad de premios entregados.</td></tr><tr><td><strong><code>GGR asociado</code></strong></td><td>Presenta el GGR asociado a las ruletas consultadas.</td></tr><tr><td><strong><code>Dinero real / Monto apostado</code></strong></td><td>Presenta el valor de dinero real o monto apostado asociado a las ruletas.</td></tr><tr><td><strong><code>Tasa de redención</code></strong></td><td>Presenta el porcentaje de redención de los premios o beneficios asociados a las ruletas.</td></tr></tbody></table>

{% tabs %}
{% tab title="General" %}
La vista **General** presenta los indicadores, gráficos comparativos y el resumen de las ruletas de acuerdo con los filtros aplicados.

{% tabs %}
{% tab title="Gráficos comparativos" %}
Presenta los principales indicadores y comportamientos asociados a las ruletas durante el período seleccionado

#### Visualización:

<figure><img src="../../../.gitbook/assets/image (240).png" alt=""><figcaption><p>Figura #1: Captura de pantalla ejemplo de la vista Gráficos comparativos.</p></figcaption></figure>

#### Información del Dashboard

<table><thead><tr><th width="197.4444580078125">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Distribución por estado del giro</code></strong></td><td><p>El gráfico presenta la distribución de los participantes según el estado del giro.</p><ul><li><strong>Activa:</strong> Participantes asociados a giros en estado activo.</li><li><strong>Expirado:</strong> Participantes asociados a giros cuyo período ha finalizado.</li><li><strong>Pendiente:</strong> Participantes cuyos giros se encuentran pendientes.</li><li><strong>Pendiente de Rollover:</strong> Participantes cuyos giros se encuentran pendientes de cumplir el rollover asociado.</li><li><strong>Pendiente Login o Registro:</strong> Participantes pendientes de completar el inicio de sesión o registro.</li><li><strong>Redimido:</strong> Participantes que han redimido el beneficio asociado al giro.</li></ul></td></tr><tr><td><strong><code>Evolución de uso de ruletas por fecha</code></strong></td><td>Presenta la evolución de la cantidad de usuarios que utilizan las ruletas durante el período seleccionado.</td></tr><tr><td><strong><code>Indicadores de comparación:</code></strong></td><td><ul><li><code>Ranking por país</code>: Presenta el ranking de los países de acuerdo con el indicador seleccionado en la sección <strong>Comparación por</strong>.</li><li><strong><code>Ranking por partner:</code></strong>Presenta el ranking de los partners de acuerdo con el indicador seleccionado en la sección <strong>Comparación por</strong>.</li><li><p><strong>Comparación por:</strong></p><ul><li><strong>Participación:</strong> Compara los partners según la cantidad de participación registrada en las ruletas.</li><li><strong>Premios entregados:</strong> Compara los partners según la cantidad de premios entregados.</li><li><strong>Pendientes:</strong> Compara los partners según la cantidad de usuarios o participaciones pendientes.</li><li><strong>GGR:</strong> Compara los partners según el GGR asociado a las ruletas.</li></ul></li></ul></td></tr><tr><td>Premios entregados por tipo de premio</td><td>Presenta la cantidad de premios entregados, agrupados según el tipo de premio.</td></tr><tr><td>Ruletas con mayor participación</td><td>Presenta las ruletas con mayor cantidad de participantes durante el período seleccionado.</td></tr></tbody></table>
{% endtab %}

{% tab title="Resumen de ruletas" %}
Presenta el detalle consolidado de las ruletas incluidas en la consulta.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (241).png" alt=""><figcaption><p>Figura #2: Captura de pantalla ejemplo de la vista Resumen de ruletas.</p></figcaption></figure>

#### **Detalle del reporte**

<table><thead><tr><th width="197.4444580078125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID ruleta</code></strong></td><td>Identificador de la ruleta.</td></tr><tr><td><strong><code>Nombre ruleta</code></strong></td><td>Nombre asignado a la ruleta.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner al que pertenece la ruleta.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado a la ruleta.</td></tr><tr><td><strong><code>Estado ruleta</code></strong></td><td>Estado actual de la ruleta.</td></tr><tr><td><strong><code>Fecha inicio</code></strong></td><td>Fecha y hora de inicio de la ruleta.</td></tr><tr><td><strong><code>Fecha fin</code></strong></td><td>Fecha y hora de finalización de la ruleta.</td></tr><tr><td><strong><code>Tipo Premio</code></strong></td><td>Tipo de premio configurado para la ruleta.</td></tr><tr><td><strong><code>Participantes</code></strong></td><td>Cantidad de usuarios que participan en la ruleta.</td></tr><tr><td><strong><code>Usuarios pendientes</code></strong></td><td>Cantidad de usuarios que permanecen pendientes.</td></tr><tr><td><strong><code>Usuarios redimidos</code></strong></td><td>Cantidad de usuarios que han redimido el beneficio.</td></tr><tr><td><strong><code>Usuarios expirados</code></strong></td><td>Cantidad de usuarios cuyo beneficio ha expirado.</td></tr><tr><td><strong><code>Premios entregados</code></strong></td><td>Cantidad de premios entregados.</td></tr><tr><td><strong><code>GGR</code></strong></td><td>GGR asociado a la ruleta.</td></tr><tr><td><strong><code>Dinero real</code></strong></td><td>Valor de dinero real asociado a la ruleta.</td></tr><tr><td><strong><code>Tasa de redención</code></strong></td><td>Porcentaje de usuarios que han redimido el beneficio.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}

{% tab title="Detalle" %}
La vista **Detalle** presenta la información desagregada relacionada con los usuarios participantes y los premios entregados.

{% tabs %}
{% tab title="Detalle de usuarios" %}
Presenta la información individual de los usuarios asociados a las ruletas consultadas.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (242).png" alt=""><figcaption><p>Figura #3: Captura de pantalla ejemplo de la vista detalles de usuarios.</p></figcaption></figure>

#### **Detalle del reporte**

<table><thead><tr><th width="189.6666259765625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador del usuario asociado a la ruleta.</td></tr><tr><td><strong><code>ID Ruleta</code></strong></td><td>Identificador de la ruleta utilizada por el usuario.</td></tr><tr><td><strong><code>Nombre Ruleta</code></strong></td><td>Nombre de la ruleta asociada al usuario.</td></tr><tr><td><strong><code>Fecha activación</code></strong></td><td>Fecha y hora en la que se activó la participación del usuario.</td></tr><tr><td><strong><code>Fecha redención</code></strong></td><td>Fecha y hora en la que el usuario redimió el beneficio.</td></tr><tr><td><strong><code>Fecha expiración</code></strong></td><td>Fecha y hora en la que expiró el beneficio asociado al usuario.</td></tr><tr><td><strong><code>Estado del giro</code></strong></td><td>Estado actual del giro asociado al usuario.</td></tr><tr><td><strong><code>Tipo Premio</code></strong></td><td>Tipo de premio asociado al usuario.</td></tr><tr><td><strong><code>Descripción Premio</code></strong></td><td>Descripción del premio asociado al usuario.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado al usuario y la ruleta.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al registro.</td></tr><tr><td><strong><code>Premio entregado</code></strong></td><td>Valor correspondiente al premio entregado al usuario.</td></tr></tbody></table>
{% endtab %}

{% tab title="Detalle de premios entregados" %}
Presenta el detalle de los premios entregados como resultado de la participación en las ruletas.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (243).png" alt=""><figcaption><p>Figura #4: Captura de pantalla ejemplo de la vista Detalle de premios entregados.</p></figcaption></figure>

#### **Detalle del reporte**

<table><thead><tr><th width="196.3333740234375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Ruleta</code></strong></td><td>Identificador de la ruleta asociada al premio.</td></tr><tr><td><strong><code>Nombre Ruleta</code></strong></td><td>Nombre de la ruleta asociada al premio.</td></tr><tr><td><strong><code>Tipo Premio</code></strong></td><td>Tipo de premio entregado.</td></tr><tr><td><strong><code>Detalle premio</code></strong></td><td>Descripción o detalle del premio entregado.</td></tr><tr><td><strong><code>Fecha de entrega</code></strong></td><td>Fecha y hora en la que se realizó la entrega del premio.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner asociado al premio.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado a la entrega del premio.</td></tr><tr><td><strong><code>Premio entregado</code></strong></td><td>Valor correspondiente al premio entregado.</td></tr><tr><td><strong><code>Cantidad entregada</code></strong></td><td>Cantidad de premios entregados.</td></tr><tr><td><strong><code>Usuarios beneficiados</code></strong></td><td>Cantidad de usuarios beneficiados con el premio.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}
{% endtab %}
{% endtabs %}

***

### 5. Validaciones y reglas del negocio

* La información presentada en las vistas corresponde a los filtros seleccionados en el panel de consulta.
* El período de información se determina mediante los campos **Desde** y **Hasta**.
* Los indicadores y gráficos se actualizan de acuerdo con los criterios de consulta aplicados.
* La vista **General** presenta información consolidada de las ruletas.
* La vista **Detalle** presenta información desagregada de usuarios y premios entregados.
* Los rankings de partner y país utilizan el criterio seleccionado en la opción **Comparación por**.

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="102.111083984375">Versión</th><th width="135.1112060546875">Fecha</th><th width="121.7777099609375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21/08/2026</td><td>Karol Navia</td><td>Reestructuración adaptada a plantilla.</td></tr></tbody></table>

</details>
