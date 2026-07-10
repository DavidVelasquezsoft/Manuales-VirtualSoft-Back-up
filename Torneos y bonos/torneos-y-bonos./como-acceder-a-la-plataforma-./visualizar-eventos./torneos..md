---
description: >-
  Permite visualizar y gestionar los torneos generados en la plataforma,
  organizados en apartados que facilitan el acceso y comprensión de la
  información.
---

# Torneos.

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Torneos y bonos > Ver torneos

***

### 2. 🖼️ Visualización general

<figure><img src="../../../.gitbook/assets/image (5).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Visualizar torneos.</p></figcaption></figure>

En la parte superior derecha se encuentra el botón **"Crear Torneo"**, el cual dirige a la sección destinada para la creación de torneos.\
Para más información, consulte el siguiente apartado:

{% content-ref url="../crear-eventos./crear-torneo/" %}
[crear-torneo](../crear-eventos./crear-torneo/)
{% endcontent-ref %}

***

### 3. 🧑‍💻 Acciones del usuario

<table><thead><tr><th width="250">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="torneos..md#id-3.1.-filtros"><strong>Filtrar</strong></a></td><td>Utiliza los filtros disponibles para buscar torneos ya creados.</td></tr><tr><td><strong>Crear Torneo</strong></td><td>Botón que redirecciona al formulario de creación de un torneo.</td></tr><tr><td><a href="torneos..md#id-3.2.-lista-de-torneos"><strong>Visualizar torneos activos</strong></a></td><td>Permite visualizar el número de torneos activos en el momento de ingresar a la sección.</td></tr><tr><td><strong>Gestionar torneos creados</strong></td><td>Utiliza las acciones disponibles para gestionar cada torneo creado.</td></tr></tbody></table>

#### 3.1. 🔎 Filtros

Los filtros permiten obtener información más detallada de los torneos, adaptándose a las necesidades de búsqueda.

<table><thead><tr><th width="185.22235107421875">Campo</th><th width="155.5556640625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Torneo</code></strong></td><td>Numérico</td><td>Permite buscar información filtrando únicamente por el ID del torneo.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Busca por rango de fechas en las que el torneo fue creado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra torneos según su estado (<strong>activo</strong> o <strong>inactivo</strong>).</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra los torneos según el país para el cual fueron creados.</td></tr></tbody></table>

Una vez completados los filtros, utiliza el botón **"Buscar"**.\
Para limpiar los criterios aplicados, utilizar el botón **"Limpiar"**.

#### 3.2. 📋 Lista de torneos

En esta sección se muestran todos los torneos creados. La información se despliega en una tabla interactiva que permite consultar y gestionar detalles de cada torneo.

<table><thead><tr><th width="188.333251953125">Columna</th><th width="559.666748046875">Descripción</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td>Por cada torneo  se permiten realizar las siguientes acciones:</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="126.1112060546875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Editar (</strong><i class="fa-pencil">:pencil:</i><strong>)</strong></td><td>Abre el formulario del torneo con toda su configuración visible, permitiendo modificar únicamente los campos <strong>“Nombre”</strong> y <strong>“Descripción”</strong>. <a href="torneos..md#id-4.-validaciones-y-reglas-del-negocio">(Ver validaciones)</a></td></tr><tr><td><a href="torneos..md#ver-detalle-de-torneo-lupa"><strong>Lupa (🔍)</strong></a></td><td>Muestra información general del torneo, incluyendo participantes y progreso. <a href="torneos..md#ver-detalle-de-torneo-lupa" class="button secondary">Ver detalles</a></td></tr><tr><td> <strong>Inactivar sorteo (⏻)</strong></td><td>Abre un pop-up para confirmar la inactivación del torneo.</td></tr><tr><td><strong>Agregar usuarios a torneo (</strong><i class="fa-user-plus">:user-plus:</i><strong>)</strong></td><td>Abre pop-up que permite agregar un archivo <a href="https://virtualsoft.gitbook.io/untitled/glosario/#csv">CSV</a> con IDs de jugadores que se van a agregar al torneo.</td></tr><tr><td><strong>Premios del torneo (</strong><i class="fa-medal">:medal:</i><strong>)</strong></td><td>Muestra los ganadores del torneo y permite pagar premios directamente.</td></tr><tr><td><strong>Visualizar TyC (</strong><i class="fa-eye">:eye:</i><strong>)</strong></td><td>Permite visualizar información relevante del torneo ademas de sus términos y condiciones.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="190.66668701171875">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Orden</code></strong></td><td>Indica el orden de creación del torneo, determinando su prioridad.</td></tr><tr><td><strong><code>ID Torneo</code></strong></td><td>Identificador único asignado al torneo.</td></tr><tr><td><strong><code>Nombre Torneo</code></strong></td><td>Nombre definido para el torneo.</td></tr><tr><td><strong><code>Descripción Torneo</code></strong></td><td>Breve descripción con detalles del torneo.</td></tr><tr><td><strong><code>Fecha de Inicio</code></strong></td><td>Fecha en la que comenzó el torneo.</td></tr><tr><td><strong><code>Fecha de Fin</code></strong></td><td>Fecha en la que finalizó el torneo.</td></tr><tr><td><strong><code>Tipo de Producto</code></strong></td><td>Tipo de producto al cual está asociado el torneo.</td></tr></tbody></table>

<details>

<summary>🔽 Ver detalle de torneo (<em>🔎 Lupa</em>)</summary>

Permite visualizar la información completa de un torneo, organizada en las siguientes secciones:

#### 📊 Kpis generales

Permiten visualizar un resumen general del estado y desempeño del torneo, a través de los siguientes indicadores:

<table><thead><tr><th width="192.00006103515625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Participantes</code></strong></td><td>Número total de usuarios que participan en el torneo.</td></tr><tr><td><strong><code>Total Puntos</code></strong></td><td>Cantidad acumulada de puntos generados por los participantes durante el torneo.</td></tr><tr><td><strong><code>Dinero Real</code></strong></td><td>Monto total de dinero real apostado por los participantes en el torneo.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Valor total de los premios otorgados a los usuarios en el torneo.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr"><strong><code>GGR</code></strong></a></td><td>Ingreso bruto total generado por el torneo, calculado como la diferencia entre lo apostado y lo pagado en premios.</td></tr><tr><td><strong><code>Progreso del torneo</code></strong></td><td>Porcentaje  de avance del torneo según su duración o condiciones configuradas.</td></tr></tbody></table>

#### 🔎 Filtros

<table><thead><tr><th width="132.99993896484375">Campo</th><th width="109.00006103515625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Posición</code></strong></td><td>Numérico</td><td>Permite filtrar los resultados según la posición del usuario en el ranking del torneo.</td></tr><tr><td><strong><code>Usuario Id</code></strong></td><td>Numérico</td><td>Permite filtrar la información asociada a un usuario específico mediante su identificador único.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Permite filtrar los resultados por el nombre del usuario.</td></tr></tbody></table>

#### 🏅 Ranking Usuarios&#x20;

Permite visualizar todos los jugadores participantes y consultar los detalles de su participación en el torneo, a través de los siguientes campos:

<table><thead><tr><th width="175.00006103515625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Posición</code></strong></td><td>Posición que ocupa el usuario dentro del ranking del torneo.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador único del usuario en la plataforma.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre del usuario participante en el torneo.</td></tr><tr><td><strong><code>Puntos</code></strong></td><td>Total de puntos acumulados por el usuario durante el torneo.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Cantidad total de apuestas realizadas por el usuario.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Monto total de premios obtenidos por el usuario.</td></tr><tr><td><strong><code>Usuario Suscrito</code></strong></td><td><p>Indica si el usuario se encuentra suscrito al torneo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si esta validación se encuentra activa en el torneo, el usuario <strong>deberá suscribirse para poder participar</strong>, independientemente de si el torneo es <strong>público</strong> o <strong>privado</strong>.</p></div></td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr"><strong><code>GGR</code></strong></a></td><td>Ingreso bruto generado por el usuario dentro del torneo.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Permite visualizar el detalle de la participación del usuario, mostrando el valor apostado y la información de todas las apuestas válidas realizadas.</td></tr></tbody></table>

</details>

***

### 4. ✅Validaciones y reglas del negocio:

* Si el torneo se configura sin inscripción de usuario, la tabla mostrará ‘0’ en `inscritos` y reflejará únicamente la cantidad de usuarios que estén participando en el torneo
* Dependiendo de la configuración del torneo, si el campo **`Usuario debe suscribirse`** se encuentra activo, los usuarios deberán suscribirse para comenzar a participar y acumular puntos, tanto en torneos públicos como privados.
* Al momento de **editar** un torneo, tenga en cuenta las siguientes validaciones:
  * El campo **Nombre** es obligatorio y no puede quedar vacío.
  * Solo se permiten letras, números, espacios y los siguientes caracteres: **`- _ ( ) /`**
  * El botón **Editar** estará disponible únicamente para usuarios con rol administrador o con permisos específicos de edición en sorteos y torneos.
  * Al guardar los cambios correctamente, el sistema mostrará el mensaje:\
    &#xNAN;**“Los cambios se guardaron correctamente.”**

***

### 5. 🕒 Control de Versiones

| Versión | Fecha      | Autor           | Cambios Realizados                                    |
| ------- | ---------- | --------------- | ----------------------------------------------------- |
| 1.0     | 2025-08-25 | Ronald Peláez   | Documento inicial                                     |
| 1.1     | 2025-09-09 | Ronald Peláez   | Nuevas columnas de cantidad de usuarios en el torneo. |
| 1.2     | 2026-02-20 | David velasquez | Incorporación de los detalles del torneo              |
