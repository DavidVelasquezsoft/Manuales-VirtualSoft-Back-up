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

# Jugadores

<mark style="color:$info;">Este módulo funciona como un reporte para la gestión de los usuarios registrados en la plataforma. Cuenta con filtros que facilitan la búsqueda y consulta de información, además de permitir la generación de reportes y la realización de diferentes configuraciones relacionadas con la administración de usuarios.</mark>

***

### 1. Acceso al módulo

**Ruta de acceso**: BackOffice > Menú principal > Jugadores

***

### 2. Visualización general

<figure><img src="../../.gitbook/assets/image (678).png" alt=""><figcaption><p>Figura #1: Filtros disponibles en la sección Jugadores.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="150.66668701171875">Acciones</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Carga masiva</code></strong></td><td><p>Abre un pop up desde el cual es posible actualizar de forma masiva la configuración de <strong><code>Persona PEP</code></strong> y <strong><code>Régimen reforzado</code></strong> para múltiples usuarios mediante la carga de un archivo .CSV.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> </p><ul><li>Desde el mismo pop up se puede descargar la plantilla <a href="https://virtualsoft.gitbook.io/plantillas/glosario?fallback=true#csv">CSV</a>, realizar las modificaciones necesarias y volver a cargar el archivo para aplicar los cambios.</li><li>Si alguna de las alguna de las columnas del archivo .CSV está vacía, no se modificará ese campo, solo se modificarán las columnas válidas.</li><li>Luego de finalizar la carga masiva se visualizará un pop up confirmando los cambios realizados.</li></ul></div></td></tr><tr><td><strong><code>Saldo Masivo</code></strong></td><td>Permite gestionar o actualizar saldos de forma masiva.</td></tr><tr><td><strong><code>Usuarios masivo</code></strong></td><td>Carga un archivo .CSV con la información de los usuarios que se desean agregar masivamente al partner.</td></tr><tr><td><strong><code>Categorización</code></strong></td><td><p>Despliega un pop up en el que estará la opción para cargar un archivo .CSV que contenga los ID de los jugadores a los que se les asignará un nivel de categorización, para realizar este proceso es necesario completar el campo <strong><code>tipo</code></strong> <em>(nivel de categorización)</em> desde la lista desplegable.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La categorización solo se puede modificar y obtener de manera manual a criterio del <a href="https://virtualsoft.gitbook.io/untitled/glosario/#partner">partner</a>, ya sea de manera masiva desde este módulo o por usuario en el módulo de <a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/jugadores/informacion-seccion-jugadores#id-3.-informacion-detallada">información</a>.</p><ul><li>La categorización de manera masiva solo se puede realizar por un nivel.</li></ul></div></td></tr><tr><td><strong><code>Desactivar contingencia</code></strong></td><td><p>Desactiva las contingencias aplicadas a usuarios de manera masiva mediante un pop-up siguientes campos:</p><ul><li><strong>Cargar archivo .CSV</strong>: permite adjuntar un archivo en formato <code>.csv</code> con los ID de los usuarios a quienes se les desactivará la contingencia.</li><li><strong>Tipo</strong>: campo de selección donde se elige la contingencia que se desea activar <em>(Ejemplo: contingencia casino, virtuales, etc.…)</em>.</li><li><strong>Descripción</strong>: campo obligatorio en el que se debe especificar el motivo o justificación de la desactivación.</li></ul><p>La ventana incluye las opciones <strong>Cancelar</strong>, para descartar la operación, y <strong>Guardar</strong>, para confirmar los cambios y retirar la contingencia seleccionada de los usuarios indicados en el archivo cargado.</p></td></tr><tr><td><strong><code>Activar contingencia</code></strong></td><td><p>Activas contingencias a usuarios de manera masiva mediante un pop-up siguientes campos:</p><ul><li><strong><code>Cargar archivo .CSV</code></strong>: permite adjuntar un archivo en formato <strong>.csv</strong> con los ID de los usuarios a quienes se les aplicará la contingencia.</li><li><strong><code>Tipo</code></strong>: campo de selección donde se elige la contingencia que se desea activar <em>(Ejemplo: contingencia casino, virtuales, etc.…)</em>.</li><li><strong><code>Descripción</code></strong>: campo obligatorio en el que se debe especificar el motivo o justificación de la activación.</li></ul><p>La ventana incluye las opciones <strong>Cancelar</strong>, para descartar la operación, y <strong>Guardar</strong>, para confirmar los cambios y aplicar la contingencia seleccionada a los usuarios indicados en el archivo cargado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Estas contingencias se pueden activar de forma individual desde el módulo <a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/jugadores/configuracion-seccion-jugadores#id-2.2.-seguridad-y-cambios">seguridad</a> y <a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/jugadores/configuracion-seccion-jugadores#id-2.3.-contingencia">contingencia</a>, en los manuales enlazados en cada módulo se detalla el funcionamiento y alcance de cada contingencia disponible.</p></div></td></tr><tr><td><strong><code>Limpiar</code></strong></td><td>Restablece los filtros por defecto.</td></tr></tbody></table>

### 4. Filtros de búsqueda

Permite aplicar múltiples condiciones para encontrar jugadores específicos.

{% hint style="warning" %}
**Nota:** Los filtros son compatibles con la paginación y las búsquedas combinadas. Además, no afectan la funcionalidad de exportación ni el comportamiento de las búsquedas.
{% endhint %}

<table><thead><tr><th width="175.83331298828125">Campo</th><th width="129.8333740234375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Texto</td><td>Permite buscar un jugador específico por su identificador único.</td></tr><tr><td><strong><code>Usuario (Correo Electrónico)</code></strong></td><td>Texto</td><td>Busca jugadores por su dirección de correo.</td></tr><tr><td><strong><code>Estado de Registro</code></strong></td><td>Lista desplegable</td><td>Filtra por estado: Activo, Inactivo, Rechazado o Bloqueado.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el partner asociado. Ejemplo: Doradobet.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra por el estado de la cuenta del usuario <em>(Activo, Inactivo, bloqueado).</em></td></tr><tr><td><strong><code>Medio de Registro</code></strong></td><td>Lista desplegable</td><td>Filtra según cómo se registró el jugador: Normal o Código Promocional.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Rango de fechas</td><td>Permite buscar jugadores registrados dentro de un periodo.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra según país asociado al jugador.</td></tr><tr><td><strong><code>Filtrar por Nivel de Riesgo</code></strong></td><td>Lista desplegable</td><td><p>Permite segmentar la información de los usuarios según su nivel de riesgo dentro de la plataforma: </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El nivel de riesgo se configura desde el módulo </p><p><a data-mention href="https://app.gitbook.com/s/Ojl0Z2z0C78jMb0KvTb8/manual-de-usuario/como-ingresar/configuracion/configuracion-de-seon">Configuración de SEON</a> de <strong>Site Builder</strong>.</p></div></td></tr></tbody></table>

{% columns %}
{% column width="41.66666666666667%" %}







{% endcolumn %}

{% column width="58.33333333333333%" %}
<table><thead><tr><th width="121">Nivel de riesgo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Bajo</code></strong></td><td>Usuarios que presentan un comportamiento normal dentro de la plataforma. No se identifican patrones sospechosos ni actividades que representen riesgo para la operación.</td></tr><tr><td><strong><code>Medio</code></strong></td><td>Usuarios que presentan ciertas alertas o comportamientos irregulares. Requieren seguimiento, ya que podrían evolucionar a un nivel de riesgo mayor.</td></tr><tr><td><strong><code>Alto</code></strong></td><td>Usuarios con comportamientos sospechosos o que representan un riesgo significativo. Pueden estar relacionados con posibles fraudes, abuso de bonos u otras actividades indebidas.</td></tr><tr><td><strong><code>No clasificado</code></strong></td><td>Hace referencia a usuarios que no cuentan con score de riesgo.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="188.83331298828125">Campo</th><th width="129.8333740234375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#nivel-lealtad"><strong><code>Nivel de lealtad</code></strong></a></td><td>Lista desplegable</td><td>Filtra según el nivel de lealtad que tenga el usuario.</td></tr></tbody></table>

***

#### &#x20;4.1. Detalles

<details>

<summary>Filtros adicionales en sección desplegable</summary>

**Esta sección se despliega al hacer clic en el ícono de lupa 🔍 junto a cada jugador.**

<table><thead><tr><th width="196.33349609375">Campo</th><th width="126.8333740234375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre registrado del jugador.</td></tr><tr><td><strong><code>Apellido</code></strong></td><td>Texto</td><td>Apellido registrado del jugador.</td></tr><tr><td><strong><code>Documento</code></strong></td><td>Texto</td><td>DNI o número de identificación.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Numérico</td><td>IP utilizada al registrarse o acceder.</td></tr><tr><td><strong><code>Teléfono</code></strong></td><td>Numérico</td><td>Filtra por el número de teléfono registrado por el usuario.</td></tr><tr><td><strong><code>ID Código Promocional</code></strong></td><td>Numérico</td><td>Código de campaña usado en el registro.</td></tr><tr><td><strong><code>¿Verificó DNI anterior?</code></strong></td><td>Lista desplegable</td><td>Indica si verificó su documento previamente.</td></tr><tr><td><strong><code>¿Verificó DNI posterior?</code></strong></td><td>Lista desplegable</td><td>Verificación posterior al registro.</td></tr><tr><td><strong><code>Estado de Contingencia</code></strong></td><td>Lista desplegable</td><td>Estado general de contingencia del usuario.</td></tr><tr><td><strong><code>Contingencia Deportivas</code></strong></td><td>Lista desplegable</td><td>Indica si el usuario tiene restricciones en deportivas.</td></tr><tr><td><strong><code>Contingencia Casino</code></strong></td><td>Lista desplegable</td><td>Indica restricciones aplicadas en casino.</td></tr><tr><td><strong><code>Contingencia Casino en Vivo</code></strong></td><td>Lista desplegable</td><td>Restricciones en modalidad en vivo.</td></tr><tr><td><strong><code>Estado de Contingencia Virtuales</code></strong></td><td>Lista desplegable</td><td>Aplica para vertical de juegos virtuales.</td></tr><tr><td><strong><code>Estado de Contingencia Poker</code></strong></td><td>Lista desplegable</td><td>Aplica para vertical de poker.</td></tr><tr><td><strong><code>Estado de Contingencia Retiros</code></strong></td><td>Lista desplegable</td><td>Aplicado para casos donde el retiro esté limitado.</td></tr><tr><td><strong><code>Condición</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario#pep"><strong><code>PEP</code></strong></a></td><td>Lista desplegable</td><td>Indica si el usuario es una Persona Expuesta Políticamente (<em>Sí/No/Todos</em>).</td></tr><tr><td><strong><code>Régimen reforzado</code></strong></td><td>Lista desplegable</td><td>Muestra los usuarios de acuerdo con el estado <a href="https://virtualsoft.gitbook.io/plantillas/glosario#regimen-reforzado">de esta configuración</a> <em>(Sí, No o Todos)</em>.</td></tr><tr><td><strong><code>Fecha de aceptación PEP</code></strong></td><td>Fecha Inicio/Fin</td><td>Especifica la fecha de validación de la condición <a href="https://virtualsoft.gitbook.io/untitled/glosario#pep">PEP</a> del usuario.</td></tr></tbody></table>

</details>

***

### 5. Tabla de usuarios.

Al realizar la búsqueda, se mostrará una tabla con la siguiente información:

<table><thead><tr><th width="129.5001220703125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td>Tendrás la opción de activar (<mark style="color:green;">Botón A</mark>) o rechazar el registro (<mark style="color:red;">Botón N</mark>) del usuario.</td></tr><tr><td>🔍</td><td>Permite configurar el jugador específicamente. <a href="./#id-6.-navegacion-adicional">Ver detalles.</a></td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del jugador.</td></tr><tr><td><strong><code>Nivel de lealtad</code></strong></td><td>Visualiza el nivel de lealtad que tiene el usuario al momento de realizar la búsqueda.</td></tr><tr><td><strong><code>Nivel de riesgo</code></strong></td><td>Muestra el nivel de riesgo asignado al usuario mediante un código de color: <em><mark style="color:green;">verde=riesgo</mark></em> <em><mark style="color:green;">bajo</mark>, <mark style="color:yellow;">amarillo=medio</mark> ,</em> <em><mark style="color:red;">rojo=alto</mark> ,</em> <em><mark style="color:$info;">Gris=No clasificado</mark>.</em></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre del jugador.</td></tr><tr><td><strong><code>Apellido</code></strong></td><td>Apellido registrado.</td></tr><tr><td><strong><code>Documento (DNI)</code></strong></td><td>Tipo de documento del jugador.</td></tr><tr><td><strong><code>(DNI)</code></strong></td><td>Identificación del jugador.</td></tr><tr><td><strong><code>IP</code></strong></td><td>Dirección IP desde la cual se conecta el usuario.</td></tr><tr><td><strong><code>Teléfono</code></strong></td><td>Teléfono de contacto.</td></tr><tr><td><strong><code>Estado de Registro</code></strong></td><td>Indica el estado del registro del usuario (<em>Activo, inactivo, rechazado o bloqueado</em>).</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha en que fue creado el jugador.</td></tr><tr><td><strong><code>Fecha último Login</code></strong></td><td>Fecha del último ingreso.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#pep"><strong><code>PEP</code></strong></a></td><td>Indica si el usuario es Persona Expuesta Políticamente</td></tr><tr><td><strong><code>Fecha de Aceptación</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario#pep"><strong><code>PEP</code></strong></a></td><td>Fecha en la que se aceptó el usuario como persona expuesta políticamente</td></tr><tr><td><strong><code>Código Promocional</code></strong></td><td>Código utilizado durante el registro <em>(si aplica).</em></td></tr><tr><td><strong><code>ID Código Promocional</code></strong></td><td>Identificador del código.</td></tr><tr><td><strong><code>Sitio</code></strong></td><td>Plataforma o dominio asociado.</td></tr><tr><td><strong><code>Celular verificado</code></strong></td><td>Visualiza si el teléfono de contacto del usuario fue verificado.</td></tr><tr><td><strong><code>Régimen reforzado</code></strong></td><td>Visualiza si el usuario pertenece o no al <a href="https://virtualsoft.gitbook.io/plantillas/glosario#regimen-reforzado">régimen reforzado</a>.</td></tr></tbody></table>

***

### 6. Navegación adicional

Al hacer clic en la lupa 🔍 del listado de jugadores, se muestra la información dividida en las siguientes secciones:&#x20;

| <a href="informacion-seccion-jugadores.md" class="button secondary">Información</a> | <a href="finanzas-seccion-jugadores.md" class="button secondary">Finanzas</a> | <a href="reportes-seccion-jugadores/" class="button secondary">Reportes</a> | <a href="configuracion-seccion-jugadores.md" class="button secondary">Configuración</a> |
| :---------------------------------------------------------------------------------: | :---------------------------------------------------------------------------: | :-------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------: |

***

### 7. Reglas y validaciones

* La visualización de determinadas acciones e información está sujeta a los permisos del usuario de BackOffice. Si algún elemento no aparece disponible, verifique los permisos asignados.

### 8. Control de versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="107.66668701171875" align="right">Versión</th><th width="119.66668701171875">Fecha</th><th width="151.5">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td align="right">1.0</td><td>24/07/2025</td><td>Ronald Pelaez</td><td>Versión inicial </td></tr><tr><td align="right">1.1</td><td>09/092025</td><td>David velasquez</td><td>Mejora de estructuración e incorporación de nuevas columnas.</td></tr><tr><td align="right">1.2</td><td>12/03/2026</td><td>Ronald Peláez</td><td>Ajuste en el campo <em><code>"</code></em><strong><code>Categorización</code></strong><em><code>"</code></em></td></tr><tr><td align="right">1.3</td><td>06/04/2026</td><td>Karol Navia</td><td>Agregar campo <code>"No clasificado"</code>  en el nivel de riesgo</td></tr><tr><td align="right">1.4</td><td>27/04/2026</td><td>Ronald Peláez </td><td>Ajuste en acciones de contingencias masivas</td></tr><tr><td align="right">1.5</td><td>02/06/2026</td><td>Ronald Peláez</td><td>Agregar filtro <strong><code>Régimen reforzado</code></strong> como filtros detallados y carga masiva.</td></tr></tbody></table>

</details>
