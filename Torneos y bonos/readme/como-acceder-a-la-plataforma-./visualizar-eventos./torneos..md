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

# Torneos.

<mark style="color:$info;">Permite consultar y gestionar los torneos creados en la plataforma. Desde este módulo se editan, inactivan y revisan los torneos, se agregan participantes y se consultan el ranking y los premios de cada uno.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Torneos y bonos > Ver torneos

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (5) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Visualizar torneos.</p></figcaption></figure>

En la parte superior se muestra el indicador **Torneos activos**, con el número de torneos activos al momento de ingresar a la sección.

En la parte superior derecha se encuentra el botón **Crear Torneo**, que dirige al formulario de creación de torneos. Para más información, consulte el siguiente apartado:

{% content-ref url="../crear-eventos./crear-torneo/" %}
[crear-torneo](../crear-eventos./crear-torneo/)
{% endcontent-ref %}

***

### 3. Acciones disponibles

<table><thead><tr><th width="250">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="torneos..md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los torneos ya creados, adaptándose a las necesidades de búsqueda.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="torneos..md#id-5.-resultados-de-consulta"><strong>Buscar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra en la tabla de resultados los torneos, que pueden gestionarse mediante las acciones disponibles por cada torneo.</td></tr><tr><td><a href="../crear-eventos./crear-torneo/"><strong>Crear Torneo</strong></a></td><td>Dirige al formulario de creación de un torneo.</td></tr><tr><td><a href="torneos..md#id-5.-resultados-de-consulta"><strong>Gestionar torneos</strong></a></td><td>Permite editar, revisar, inactivar y administrar cada torneo mediante las acciones disponibles en la tabla de resultados.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="185.22235107421875">Campo</th><th width="155.5556640625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Torneo</code></strong></td><td>Campo numérico</td><td>Localiza un torneo específico a partir de su identificador único.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Delimita el rango de fechas en el que se crearon los torneos.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Restringe la consulta según el estado del torneo <em>(Activo o Inactivo)</em>.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Muestra los torneos creados para el país seleccionado.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega la tabla **Lista de Torneos** con los torneos que cumplen con los filtros aplicados.

<table><thead><tr><th width="188.333251953125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acción</code></strong></td><td>Reúne las acciones disponibles para gestionar cada torneo. Las acciones se describen a continuación.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
**Acciones por torneo**

<table><thead><tr><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Editar</strong> (<i class="fa-pencil">:pencil:</i>)</td><td>Abre el formulario del torneo con toda su configuración visible y permite modificar únicamente los campos <strong><code>Nombre</code></strong> y <strong><code>Descripción</code></strong>. <a href="torneos..md#id-6.-validaciones-y-reglas-del-negocio">Ver validaciones</a></td></tr><tr><td><strong>Visualizar TyC</strong> (<i class="fa-eye">:eye:</i>)</td><td>Permite visualizar información relevante del torneo, además de sus términos y condiciones.</td></tr><tr><td><a href="torneos..md#ver-detalle-de-torneo-lupa"><strong>Lupa (🔍)</strong></a></td><td>Muestra información general del torneo, incluyendo participantes y progreso. <a href="torneos..md#ver-detalle-de-torneo-lupa" class="button secondary">Ver detalles</a></td></tr><tr><td><strong>Inactivar torneo (⏻)</strong></td><td>Abre un pop-up para confirmar la inactivación del torneo.</td></tr><tr><td><strong>Agregar usuarios a torneo</strong> (<i class="fa-user-plus">:user-plus:</i>)</td><td>Abre un pop-up que permite agregar un archivo <a href="https://virtualsoft.gitbook.io/untitled/glosario/#csv">CSV</a> con los ID de los jugadores que se agregarán al torneo.</td></tr><tr><td><strong>Premios del torneo</strong> (<i class="fa-medal">:medal:</i>)</td><td>Muestra los ganadores del torneo y permite pagar los premios directamente.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="188.333251953125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Orden</code></strong></td><td>Posición en la que se ordena el torneo, que determina su prioridad.</td></tr><tr><td><strong><code>ID Torneo</code></strong></td><td>Identificador único asignado al torneo.</td></tr><tr><td><strong><code>Nombre Torneo</code></strong></td><td>Nombre definido para el torneo.</td></tr><tr><td><strong><code>Descripción Torneo</code></strong></td><td>Breve descripción con los detalles del torneo.</td></tr><tr><td><strong><code>Fecha Inicio</code></strong></td><td>Fecha en la que inicia el torneo.</td></tr><tr><td><strong><code>Fecha Fin</code></strong></td><td>Fecha en la que finaliza el torneo.</td></tr><tr><td><strong><code>Tipo Producto</code></strong></td><td>Tipo de producto al que está asociado el torneo.</td></tr></tbody></table>

<details>

<summary>🔽 Ver detalle de torneo (<em>Lupa</em>)</summary>

Muestra la información completa del torneo, organizada en las siguientes secciones:

#### Kpis generales

Resumen del estado y el desempeño del torneo, a través de los siguientes indicadores:

<table><thead><tr><th width="192.00006103515625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Participantes</code></strong></td><td>Número total de usuarios que participan en el torneo.</td></tr><tr><td><strong><code>Total Puntos</code></strong></td><td>Cantidad acumulada de puntos generados por los participantes durante el torneo.</td></tr><tr><td><strong><code>Dinero Real</code></strong></td><td>Monto total de dinero real apostado por los participantes en el torneo.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Valor total de los premios otorgados a los usuarios en el torneo.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr"><strong><code>GGR</code></strong></a></td><td><p>Ingreso bruto generado por el torneo: lo que queda para la casa después de pagar los premios.</p><p><strong>Fórmula:</strong><br><em>GGR = Total apostado − Total pagado en premios</em></p></td></tr><tr><td><strong><code>Progreso del torneo</code></strong></td><td>Porcentaje de avance del torneo según su duración o las condiciones configuradas.</td></tr></tbody></table>

#### Filtros del detalle

<table><thead><tr><th width="132.99993896484375">Campo</th><th width="140">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Posición</code></strong></td><td>Campo numérico</td><td>Localiza a los usuarios según su posición en el ranking del torneo.</td></tr><tr><td><strong><code>Usuario Id</code></strong></td><td>Campo numérico</td><td>Muestra la información de un usuario específico a partir de su identificador único.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Acota los resultados por el nombre del usuario.</td></tr></tbody></table>

#### Ranking Usuarios

Muestra todos los jugadores participantes y el detalle de su participación en el torneo:

<table><thead><tr><th width="175.00006103515625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Posición</code></strong></td><td>Posición que ocupa el usuario dentro del ranking del torneo.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador único del usuario en la plataforma.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre del usuario participante en el torneo.</td></tr><tr><td><strong><code>Puntos</code></strong></td><td>Total de puntos acumulados por el usuario durante el torneo.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Cantidad total de apuestas realizadas por el usuario.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Monto total de premios obtenidos por el usuario.</td></tr><tr><td><strong><code>Usuario Suscrito</code></strong></td><td><p>Indica si el usuario está suscrito al torneo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si esta validación se encuentra activa en el torneo, el usuario <strong>deberá suscribirse para poder participar</strong>, independientemente de si el torneo es <strong>público</strong> o <strong>privado</strong>.</p></div></td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr"><strong><code>GGR</code></strong></a></td><td>Ingreso bruto generado por el usuario dentro del torneo.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Muestra el detalle de la participación del usuario, con el valor apostado y la información de todas sus apuestas válidas.</td></tr></tbody></table>

</details>

***

### 6. Validaciones y reglas del negocio:

* Si el torneo se configura sin inscripción de usuario, la tabla muestra **0** en `inscritos` y refleja únicamente la cantidad de usuarios que están participando en el torneo.
* Si el campo **`Usuario debe suscribirse`** está activo en la configuración del torneo, los usuarios deben suscribirse para empezar a participar y acumular puntos, tanto en torneos públicos como privados.
* Al **editar** un torneo se aplican las siguientes validaciones:
  * El campo **Nombre** es obligatorio y no puede quedar vacío.
  * Solo se permiten letras, números, espacios y los caracteres **`- _ ( ) /`**.
  * El botón **Editar** solo está disponible para usuarios con rol administrador o con permisos de edición en sorteos y torneos.
  * Al guardar los cambios correctamente, el sistema muestra un mensaje de confirmación.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>25/08/2025</td><td>Ronald Peláez</td><td>Documento inicial.</td></tr><tr><td>1.1</td><td>09/09/2025</td><td>Ronald Peláez</td><td>Nuevas columnas de cantidad de usuarios en el torneo.</td></tr><tr><td>1.2</td><td>20/02/2026</td><td>David Velasquez</td><td>Incorporación de los detalles del torneo.</td></tr><tr><td>1.3</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
