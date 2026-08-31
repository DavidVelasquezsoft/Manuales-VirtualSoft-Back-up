# Orden y gestión de juegos

<mark style="color:$info;">Esta sección permite organizar y administrar los juegos que se muestran en el lobby de la plataforma de usuarios online, definiendo qué juegos pertenecen a cada categoría y en qué orden se presentan al jugador. La disposición de los juegos en pantalla refleja visualmente cómo el usuario los verá en el lobby.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Site Builder > Partner > Productos > Orden y gestión de juegos

{% hint style="warning" %}
**Nota:** El acceso a este módulo requiere permisos específicos; en caso de no contar con ellos, no será visible en el sistema.
{% endhint %}

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (490).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Módulo Orden y gestión de juegos</p></figcaption></figure>

{% hint style="warning" %}
**Nota:** Cada juego se muestra como una tarjeta con la siguiente información:
{% endhint %}

<table><thead><tr><th width="189.99993896484375">Elemento</th><th>Descripción</th></tr></thead><tbody><tr><td> <strong>Control de arrastre</strong></td><td>Ubicado en la esquina superior derecha de la tarjeta, permite mover el juego a otra posición.</td></tr><tr><td><strong>Casilla de selección</strong></td><td>Ubicada en la esquina superior izquierda de la tarjeta, permite seleccionar el juego para aplicar acciones sobre él.</td></tr><tr><td><strong>Imagen</strong></td><td>Miniatura del juego, tal como se muestra en el lobby.</td></tr><tr><td><strong>Nombre</strong></td><td>Nombre del juego.</td></tr><tr><td><strong>ID</strong></td><td>Identificador único del juego.</td></tr><tr><td><strong>Vertical</strong></td><td><a href="https://virtualsoft.gitbook.io/plantillas/glosario#vertical">Vertical</a> a la que pertenece el juego <em>(Casino, Casino en vivo o Virtuales)</em>.</td></tr></tbody></table>

***

### 3. Configuraciones previas

Antes de realizar cualquier acción en el módulo, es necesario contar con la siguiente configuración:

<table><thead><tr><th width="207.55560302734375">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País y partner para el cual se realizará la configuración. Hasta que no se seleccione, no se habilita la vista ni las acciones del módulo.</td></tr></tbody></table>

***

### 4. Acciones del Usuario

<table><thead><tr><th width="176.99993896484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="orden-y-gestion-de-juegos.md#id-5.-filtros"><strong>Filtrar</strong></a></td><td>Permite filtrar los juegos por categoría o por <a href="https://virtualsoft.gitbook.io/plantillas/glosario#vertical">vertical</a>: <em>(Casino, casino en vivo, virtuales)</em> y aplicar filtros avanzados (<img src="../../../.gitbook/assets/image (491).png" alt="" data-size="line">) para búsquedas más específicas.</td></tr><tr><td><a href="orden-y-gestion-de-juegos.md#id-6.-gestionar-juegos"><strong>Gestionar juegos</strong></a></td><td>Permite aplicar acciones sobre uno o varios juegos seleccionados, según la vista en la que se encuentre.</td></tr><tr><td><strong>Organizar juegos</strong></td><td>Permite cambiar el orden de visualización de los juegos <strong>mediante arrastrar y soltar</strong>, utilizando el control  <img src="../../../.gitbook/assets/Vector (1).png" alt="">  ubicado en cada tarjeta. Los juegos pueden moverse tanto entre filas como entre columnas.</td></tr><tr><td><a href="orden-y-gestion-de-juegos.md#id-7.-organizacion-masiva-por-csv"><strong>Organización masiva por CSV</strong></a></td><td>Permite agregar o reorganizar juegos de forma masiva dentro de una categoría mediante un archivo CSV, utilizando el botón <img src="../../../.gitbook/assets/Button (3).png" alt="" data-size="line">.</td></tr><tr><td><strong>Descargar plantilla</strong></td><td>Permite descargar el archivo CSV modelo con la estructura requerida para la organización masiva de juegos mediante el botón<img src="../../../.gitbook/assets/image (493).png" alt="" data-size="line">.</td></tr><tr><td><strong>Guardar cambios</strong></td><td>Aplica los cambios realizados en la organización o categorización de los juegos.</td></tr></tbody></table>

### &#x20;5. Filtros

<table><thead><tr><th width="125.29620361328125">Filtro</th><th width="126">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categoría</code></strong></td><td>Lista desplegable</td><td><p>Permite seleccionar la <a href="https://virtualsoft.gitbook.io/plantillas/glosario#vertical">vertical</a> de las categorías o una categoría específica para visualizar y gestionar los juegos correspondientes.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Solo se muestran las categorías activas creadas desde la sección <a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos-2/partners-categorias">Categorías partner</a>.</p></div></td></tr><tr><td><strong><code>Filtros avanzados</code></strong></td><td>Botón</td><td>Despliega criterios adicionales para obtener resultados más detallados:</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="128.51849365234375">Campo</th><th width="121.14813232421875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre de juego</code></strong></td><td>Campo de texto</td><td>Filtra los juegos por su nombre.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Filtra los juegos por proveedor.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Lista desplegable</td><td>Filtra los juegos por subproveedor.</td></tr><tr><td><strong><code>Limpiar</code></strong></td><td>Botón</td><td>Restablece los filtros aplicados a su estado inicial.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

### 6. Gestionar juegos

Las acciones disponibles dependen de la **vista seleccionada en el filtro de categoría**:

<table><thead><tr><th width="220">Vista</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Vista general</strong> <em>(Todas las categorías)</em></td><td>Muestra todos los juegos de la <a href="https://virtualsoft.gitbook.io/plantillas/glosario#vertical">vertical</a> <em>(Casino, Casino en vivo o Virtuales)</em>, tengan o no categorías asignadas. Permite agregarlos a una o varias categorías.</td></tr><tr><td><strong>Vista de categoría</strong></td><td>Muestra los juegos de una categoría específica. Permite agregar juegos, cambiar su orden o quitarlos de la categoría.</td></tr></tbody></table>

Para aplicar una acción, se seleccionan uno o varios juegos mediante la casilla ubicada en la esquina superior izquierda de cada tarjeta. Los juegos seleccionados quedan destacados y en la parte inferior de la pantalla se despliega una barra con las acciones disponibles, que varían según la vista en la que se esté trabajando.

{% tabs %}
{% tab title="Vista general (Todas las categorías)" %}
Al seleccionar uno o varios juegos en esta vista, la barra de acciones habilita las siguientes opciones:

#### **Cambiar orden**

Abre un modal que permite reorganizar la posición de los juegos seleccionados mediante el botón <img src="../../../.gitbook/assets/Button (8).png" alt="" data-size="line">.

<table><thead><tr><th width="117.629638671875">Campo</th><th width="102.74078369140625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Posición</code></strong></td><td>Numérico</td><td>Define la posición desde la cual se ubicarán los juegos seleccionados, de forma consecutiva. Admite valores entre <strong>1 y 999</strong>.</td></tr><tr><td><strong><code>Comentario</code></strong></td><td>Campo de texto</td><td>Registra el motivo del reordenamiento. Este comentario queda asociado al cambio para fines de control y auditoría.</td></tr></tbody></table>

{% hint style="info" %}
**Ejemplo:** Si se seleccionan los juegos de las posiciones 10 a 15 y se indica la posición **1**, esos juegos pasan a ocupar las primeras posiciones y los que estaban antes se desplazan a continuación.
{% endhint %}

#### **Agregar a la categoría**&#x20;

Abre un modal que permite asignar los juegos seleccionados a una o varias categorías mediante el botón <img src="../../../.gitbook/assets/Button (9).png" alt="" data-size="line">, el cual cuenta con los siguientes componentes:

{% hint style="warning" %}
**Nota:** Las categorías seleccionada debe coincidir con la [vertical](https://virtualsoft.gitbook.io/plantillas/glosario#vertical) del juego. No es posible asignar juegos a categorías de una vertical distinta (_ej. agregar un juego de Casino en una categoría de Live Casino_).
{% endhint %}

<table><thead><tr><th width="125.77777099609375">Componente</th><th width="102.66668701171875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Lista de selección</td><td>Muestra las categorías disponibles a las que pueden agregarse los juegos seleccionados. Permite elegir una o varias.</td></tr><tr><td><strong><code>Seleccionar todas</code></strong></td><td>Selección</td><td>Selecciona todas las categorías disponibles de forma rápida.</td></tr><tr><td><strong><code>Agregar juegos</code></strong></td><td>Botón</td><td>Confirma la acción y vincula los juegos seleccionados a las categorías elegidas.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Botón</td><td>Cierra el modal sin aplicar cambios.</td></tr></tbody></table>
{% endtab %}

{% tab title="Vista de categoría" %}
Al trabajar sobre una categoría específica, además de las acciones sobre los juegos seleccionados, la vista habilita opciones propias para administrar el contenido de la categoría:

#### **Agregar juegos**

Abre un modal que permite buscar y agregar uno o varios juegos a la categoría mediante el botón <img src="../../../.gitbook/assets/Button (11).png" alt="" data-size="line">.

{% hint style="warning" %}
**Nota:** Los juegos seleccionada deben coincidir con la [vertical](https://virtualsoft.gitbook.io/plantillas/glosario#vertical) de la categoria. No es posible asignar juegos a categorías de una vertical distinta (_ej. agregar un juego de Casino en una categoría de Live Casino_).
{% endhint %}

<table><thead><tr><th width="122.0740966796875">Componente</th><th width="107.629638671875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Buscador de juegos</code></strong></td><td>Campo de texto</td><td><p>Permite buscar juegos por <strong>nombre</strong> o <strong>ID</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Se deben ingresar al menos los primeros tres caracteres para que se muestren resultados.</p></div></td></tr><tr><td><strong><code>Juegos</code></strong></td><td>Lista de selección</td><td>Muestra los juegos disponibles según la búsqueda realizada. Permite seleccionar uno o varios.</td></tr><tr><td><strong><code>Seleccionar todos los disponibles</code></strong></td><td>Selección</td><td>Selecciona automáticamente todos los juegos que coinciden con la búsqueda actual.</td></tr><tr><td><strong><code>Contador de selección</code></strong></td><td>Indicador</td><td>Muestra la cantidad de juegos seleccionados que serán agregados a la categoría.</td></tr><tr><td><strong><code>Agregar juegos</code></strong></td><td>Botón</td><td>Confirma la acción y agrega los juegos seleccionados a la categoría.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Botón</td><td>Cierra el modal sin realizar cambios.</td></tr></tbody></table>

#### **Cambiar orden**

Abre un modal que permite reorganizar la posición de los juegos seleccionados dentro de la categoría.

<table><thead><tr><th width="117.629638671875">Campo</th><th width="102.74078369140625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Posición</code></strong></td><td>Numérico</td><td>Define la posición desde la cual se ubicarán los juegos seleccionados, de forma consecutiva. Admite valores entre <strong>1 y 999</strong>.</td></tr><tr><td><strong><code>Comentario</code></strong></td><td>Campo de texto</td><td>Registra el motivo del reordenamiento. Este comentario queda asociado al cambio para fines de control y auditoría.</td></tr></tbody></table>

#### **Vaciar categoría**

Permite quitar todos los juegos de la categoría seleccionada mediante el botón <img src="../../../.gitbook/assets/Button (5).png" alt="" data-size="line">, sin eliminarlos del sistema.

{% hint style="warning" %}
**Nota:** El sistema solicita confirmación antes de ejecutar la acción.
{% endhint %}

#### **Eliminar de la categoría**

Permite quitar uno o varios juegos de la categoría seleccionada mediante el botón . Los juegos **no se eliminan del sistema** y permanecen disponibles en la vista general.

{% hint style="warning" %}
**Nota:** El sistema solicita confirmación antes de ejecutar la acción, advirtiendo que los elementos seleccionados se eliminarán de la categoría y que la acción no puede deshacerse.
{% endhint %}
{% endtab %}
{% endtabs %}

***

### 7. Organización masiva por CSV

Permite agregar o reorganizar juegos dentro de una categoría de forma masiva mediante la carga de un archivo **CSV** con las siguientes columnas:

{% hint style="warning" %}
**Nota:** El archivo modelo con la estructura requerida puede obtenerse mediante la opción <img src="../../../.gitbook/assets/image (493).png" alt="" data-size="line">.
{% endhint %}

<table><thead><tr><th width="201.88873291015625">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID del juego</code></strong></td><td>Identificador único del juego que se desea agregar o reorganizar.</td></tr><tr><td><strong><code>ID Categoría</code></strong></td><td>Identificador de la categoría sobre la cual se aplicará el cambio.</td></tr><tr><td><strong><code>Nueva posición</code></strong></td><td>Número que define la posición en la que se ubicará el juego dentro de la categoría.</td></tr></tbody></table>

#### **7.1. Reglas de procesamiento**

Al cargar el archivo, el sistema procesa cada registro aplicando las siguientes reglas:

* Si el juego **ya existe en la categoría**, actualiza su posición según la indicada en el archivo.
* Si el juego **no pertenece a la categoría**, lo agrega automáticamente en la posición indicada.
* Si el **ID del juego no existe o el juego se encuentra inactivo**, registra el error y continúa procesando los demás registros.

#### **7.2. Resumen de la carga**

Al finalizar el procesamiento, el sistema muestra un resumen con el resultado de cada registro del archivo:

<table><thead><tr><th width="189.88873291015625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID del juego</code></strong></td><td>Identificador único del juego procesado.</td></tr><tr><td><strong><code>Nombre del juego</code></strong></td><td>Nombre del juego procesado.</td></tr><tr><td><strong><code>Nombre de la categoría</code></strong></td><td>Categoría sobre la cual se aplicó el cambio.</td></tr><tr><td><strong><code>Posición anterior</code></strong></td><td>Posición que ocupaba el juego antes de la carga.</td></tr><tr><td><strong><code>Nueva posición</code></strong></td><td>Posición asignada al juego tras la carga.</td></tr><tr><td><strong><code>Estado de la carga</code></strong></td><td><p>Resultado del procesamiento del registro:</p><ul><li><strong>Agregado:</strong> el juego se cargó correctamente en la categoría.</li><li><strong>Reordenado:</strong> el juego ya existia en la cateoria y se reordeno su orden. </li><li><strong>Error:</strong> el juego no pudo cargarse en la categoría.</li></ul></td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Si el archivo no cumple con la estructura esperada, el sistema muestra un mensaje indicando que debe verificarse el formato antes de intentarlo nuevamente.
{% endhint %}

***

### 8. Guardar cambios

Los cambios realizados en el módulo, como **reordenar, agregar, eliminar, vaciar o cargar mediante CSV**, no se aplican en la plataforma hasta seleccionar el botón <img src="../../../.gitbook/assets/image (456).png" alt="" data-size="line">, ubicado en la parte inferior. Una vez guardados, el sistema confirma la operación y los cambios quedan aplicados.

{% hint style="warning" %}
**Nota:** Si se intenta salir del módulo con cambios sin guardar, el sistema muestra una advertencia para confirmar si desea salir sin aplicarlos.
{% endhint %}

***

### 9. Validaciones y Reglas de Negocio

* El acceso al módulo requiere permisos específicos; de lo contrario, no será visible en el sistema.
* En el filtro de categoría solo se muestran las categorías activas creadas previamente desde el módulo [Partners Categorias](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos-2/partners-categorias) del backoffice.
* Los cambios realizados son visuales hasta seleccionar el botón **Guardar cambios**; una vez guardados, se reflejan en la plataforma de usuarios online.
* Al cambiar el orden de los juegos es obligatorio registrar un comentario que justifique el reordenamiento.
* Al reordenar un bloque de juegos, estos se ubican de forma consecutiva desde la posición indicada y los juegos existentes se desplazan a las siguientes posiciones.
* Los juegos eliminados de una categoría o quitados mediante **Vaciar categoría** no se eliminan del sistema y permanecen disponibles en la vista general.
* La vista general de ala vertical _(Todas las categorías)_ incluye los juegos con y sin categorías asignadas.
* Las acciones de eliminar juegos y vaciar categoría requieren confirmación previa y no pueden deshacerse.
* Cuando la categoría seleccionada no tiene juegos asignados, el sistema muestra un mensaje informativo indicando que aún no cuenta con juegos y que deben agregarse para que se visualicen en el lobby.

***

### 10. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="100.99993896484375">Versión</th><th width="127">Fecha</th><th width="169">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>08/07/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>2.0</td><td>12/03/2026</td><td>David Velasquez</td><td>Reestructuración y actualización de módulo.</td></tr><tr><td>2.1</td><td>13/08/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-27402">Organización de las acciones por vista e incorporación de la carga masiva por CSV.</a></td></tr></tbody></table>

</details>
