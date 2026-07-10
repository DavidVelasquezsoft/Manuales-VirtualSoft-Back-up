---
description: >-
  Permite activar, desactivar y configurar los productos disponibles para un
  partner en la plataforma.
---

# Activar productos

### 1. Acceso al Módulo

**Ruta de acceso:** Site Builder > Seleccionar Partner > Productos > Activar productos

***

### 2. Acciones del Usuario

<table><thead><tr><th width="227.07403564453125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="activar-productos.md#id-3.2.-filtros"><strong>Filtrar juegos</strong></a></td><td>Permite filtrar la información según criterios definidos para localizar los productos deseados.</td></tr><tr><td><a href="activar-productos.md#id-3.3.-editar-etiqueta"><strong>Seleccionar juegos</strong></a></td><td>Selecciona uno o varios juegos; también puede usarse la opción <strong>Seleccionar todos</strong> con el fin de editar las etiquetas del juego.</td></tr><tr><td><strong>Visualizar según estado</strong></td><td>Muestra los juegos activos, inactivos o todos los disponibles.</td></tr><tr><td><a href="activar-productos.md#id-3.4.-como-editar-juegos"><strong>Editar juegos</strong></a></td><td>Accede a la configuración del juego seleccionado para actualizar sus datos o parámetros.</td></tr><tr><td><a href="activar-productos.md#id-3.5.-cambiar-estado-de-forma-masiva"><strong>Cambiar estado de forma masiva</strong></a></td><td>Permite subir un archivo <a href="https://virtualsoft.gitbook.io/untitled/glosario#csv">CSV</a> para activar o desactivar múltiples productos de manera masiva.</td></tr><tr><td><a href="activar-productos.md#id-4.1.-visualizacion"><strong>Visualizar historial de carga</strong></a></td><td>Permite visualizar todas las cargas masivas realizadas anteriormente.</td></tr></tbody></table>

### 3. Secciones del modulo

Esta sección se divide por 2 pestañas diferentes, las cuales son:

{% tabs %}
{% tab title="3.1. Juegos" %}
Permite gestionar, agregar y configurar los productos disponibles.

#### 3.1.1. Visualización

<figure><img src="../../../.gitbook/assets/image (397).png" alt=""><figcaption><p><strong>Figura 1:</strong> Vista general del módulo <em>Activar productos</em>, donde se muestran los juegos disponibles para el partner seleccionado.</p></figcaption></figure>

#### 3.1.2. Filtros

Despliega un pop-up con los filtros disponibles para mostrar los juegos, utilizando el botón **`Buscar`** para aplicar los filtros y visualizar los resultados según los criterios ingresados.

<table><thead><tr><th width="158">Campo</th><th width="170">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del juego</code></strong></td><td>Campo de texto</td><td>Permite ingresar el nombre del juego a visualizar.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Lista desplegable</td><td>Escribe o selecciona el ID del juego.</td></tr><tr><td><strong><code>Partner ID</code></strong></td><td>Lista desplegable</td><td>Escribe o selecciona el identificador del partner.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona el proveedor principal del juego.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona el subproveedor del juego.</td></tr></tbody></table>

#### 3.1.3. Editar etiqueta

Al seleccionar un juego, se habilita la opción **Editar etiqueta**, la cual despliega un pop-up con el formulario para modificar la imagen o el texto de la etiqueta.

Una **etiqueta** es un distintivo visual que se muestra sobre la miniatura del juego (por ejemplo, _Top_, _Nuevo_ o _Destacado_), y su función es **resaltar o clasificar** ciertos juegos dentro de la plataforma, facilitando su identificación por parte de los usuarios.

<table><thead><tr><th width="131">Campo</th><th width="166">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Subir imagen</code></strong></td><td>Carga de imagen</td><td>Permite cargar la imagen que funcionará como distintivo o etiqueta del juego.</td></tr><tr><td><strong><code>Editar texto</code></strong></td><td>Campo de texto</td><td>Permite ingresar el texto que se mostrará en la etiqueta en caso de que la imagen no se visualice correctamente.</td></tr><tr><td><strong><code>Borrar etiqueta</code></strong></td><td>Botón</td><td>Borra la etiqueta que tiene el juego y se visualizará solo la miniatura de este.</td></tr><tr><td><strong><code>Aplicar</code></strong></td><td>Botón</td><td>Aplica los cambios realizados en la etiqueta</td></tr></tbody></table>

#### 3.1.4. ¿Cómo editar juegos?

Cada tarjeta representa un juego disponible en la plataforma. Desde esta vista, el usuario puede visualizar información del juego y realizar configuraciones específicas.

<table><thead><tr><th width="140.92596435546875">Campo</th><th width="205">Descripción</th><th>Funcionalidad</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único asignado al juego.</td><td>Solo lectura.</td></tr><tr><td><strong><code>Partner ID</code></strong></td><td>Identificador del partner al que pertenece el juego.</td><td>Solo lectura.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Indica si el juego está activo o inactivo en la plataforma.</td><td>Configurable desde el ícono de estado. Al cambiarlo <em>(</em>🟢 <em>activo /</em> 🔘 <em>inactivo)</em>, se muestra un pop-up para ingresar el motivo del cambio antes de confirmar.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Código <a href="https://virtualsoft.gitbook.io/untitled/glosario/#mincetur">MINCETUR</a> del producto.</td><td>Editable. Al hacer clic en el campo o en el icono de edición flotante, se despliega un pop-up para <strong><code>editar el código MINCETUR</code></strong> asociado al juego.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor principal del juego.</td><td>Solo lectura.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Nombre del estudio o subproveedor del juego.</td><td>Solo lectura.</td></tr></tbody></table>

#### 3.1.5. **Cambiar estado de forma masiva**

Permite activar o inactivar múltiples productos de forma masiva mediante un archivo [.CSV](https://virtualsoft.gitbook.io/untitled/glosario#csv) dando clic al botón <img src="../../../.gitbook/assets/Button.png" alt="" data-size="line">, siguiendo los siguientes pasos:

{% stepper %}
{% step %}
#### Ingresar archivo [CSV](https://virtualsoft.gitbook.io/untitled/glosario#csv)

{% hint style="warning" %}
**Nota:** El botón <img src="../../../.gitbook/assets/Button (1).png" alt="" data-size="line">  permite descargar la plantilla del archivo .CSV que se debe cargar para cambiar los estados de forma masiva correctamente.
{% endhint %}

El archivo obligatoriamente debe tener únicamente las siguientes 2 columnas:

<table><thead><tr><th width="117.44439697265625">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>ID</strong></td><td>Ingresa  el identificador único del producto al cual se le desea cambiar el estado.</td></tr><tr><td><strong>ACCIÓN</strong></td><td><p>Indica la acción que se realizará sobre el producto:<br></p><ul><li><strong>inactivar:</strong> cambiará el estado del producto a inactivo</li><li><strong>activar:</strong> Cambiara el estado del producto a activo</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La acción debe escribirse correctamente como <strong>“activar”</strong> o <strong>“inactivar”</strong>; El sistema reconoce el valor de la acción independientemente del uso de mayúsculas o minúsculas.</p></div></td></tr></tbody></table>

Una vez cargado el archivo CSV, el sistema valida automáticamente su contenido; si no cumple con el formato requerido, será rechazado y se mostrará un mensaje indicando el motivo del error.
{% endstep %}

{% step %}
#### Visualizar información procesada

Una vez el sistema halla validado el archivo correctamente, mostrara un resumen con los siguientes valores:

<table><thead><tr><th width="183.00006103515625">Valor</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total de filas procesadas</code></strong></td><td>Muestra el total de registros identificados y procesados por el sistema dentro del archivo .CSV, incluyendo válidos y con error.</td></tr><tr><td><strong><code>Total de filas válidadas</code></strong></td><td>Muestra el total de registros procesados correctamente, donde el identificador del producto y la acción ingresada son válidos.</td></tr><tr><td><strong><code>Total de filas erróneas</code></strong></td><td>Muestra el total de registros que presentaron errores durante la validación o procesamiento del archivo .CSV.</td></tr><tr><td><strong><code>Fila</code></strong></td><td>Columna que indica el numero de fila del producto en el archivo que fallo al realizarse la acción.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Columna que indica por cada fila el mensaje de error en especifico por el cual fallo la acción.</td></tr></tbody></table>

Una vez validada la información, si existe al menos un registro válido, se habilitará el botón <img src="../../../.gitbook/assets/Button (2).png" alt="" data-size="line"> para continuar.

{% hint style="warning" %}
**Nota:** Si el archivo se encuentra vacío, el sistema mostrará un mensaje de error y no permitirá continuar.
{% endhint %}
{% endstep %}

{% step %}
#### Confirmación con token de seguridad

Al cargar los juegos posteriormente el sistema solicitará el **token de autenticación** utilizado para ingresar al Backoffice (_aplicación Authenticator_) con el fin de validar la acción de carga masiva.

Ingresa el token y confirma nuevamente con **“Aceptar”** para finalizar y subir los cambios correctamente.
{% endstep %}

{% step %}
#### Visualizar historial de carga (_Opcional_)

En la parte superior derecha se encuentra la sección de historial de cargas, la cual cuenta con toda la información de cada fila por cada carga masiva que se realizó [#id-4.-historial-de-cargas](activar-productos.md#id-4.-historial-de-cargas "mention")
{% endstep %}
{% endstepper %}
{% endtab %}

{% tab title="3.2. Historial de cargas" %}
Permite visualizar el historial de cargas masivas realizadas y descargar sus resultados.

#### **3.2.1. Visualización**

<figure><img src="../../../.gitbook/assets/image (398).png" alt=""><figcaption><p><strong>Figura #2:</strong> Captura de pantalla historial de cargas en la sección activar juegos</p></figcaption></figure>

#### **3.2.2. Filtros**

<table><thead><tr><th width="104.48150634765625">Filtro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Permite filtrar los registros según la fecha de carga del archivo.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Permite filtrar por el estado del procesamiento del archivo (<em>Completado o Con errores</em>).</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Permite filtrar los registros según el usuario que realizó la carga.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** El botón <img src="../../../.gitbook/assets/Button (1).png" alt="" data-size="line">  en esta sección permite descargar la plantilla del archivo .CSV que se debe cargar para cambiar los estados de forma masiva correctamente desde la pestaña [#id-3.-juegos](activar-productos.md#id-3.-juegos "mention") dando clic al botón <img src="../../../.gitbook/assets/Button.png" alt="" data-size="line">.
{% endhint %}

#### **3.2.3. Resultados**

<table><thead><tr><th width="180.85198974609375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del archivo</code></strong></td><td>Muestra el nombre del archivo CSV cargado.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Indica el usuario que realizó la carga del archivo.</td></tr><tr><td><strong><code>Fecha y hora</code></strong></td><td>Muestra la fecha y hora en que se cargó el archivo.</td></tr><tr><td><strong><code>Estado</code></strong></td><td><p>Indica el resultado del procesamiento de la carga masiva: </p><p></p><ul><li><strong>Cargado:</strong> si todas las filas son válidas.</li><li><strong>Error:</strong> si alguna fila no fue valida y no se proceso.</li></ul></td></tr><tr><td><strong><code>Filas completadas</code></strong></td><td>Muestra el total de filas procesadas correctamente y en las que la acción se ejecutó exitosamente en el archivo CSV.</td></tr><tr><td><strong><code>Acciones</code></strong></td><td>Permite descargar el resultado de la carga masiva para visualizar el detalle de las filas procesadas y los posibles errores por cada registro.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 4. Validaciones y Reglas de Negocio

* Los cambios de estado realizados sobre los productos, ya sea de forma individual o masiva, se **guardan automáticamente** y se reflejarán en la plataforma de usuarios online después de algunos minutos.
* El campo **Código MINCETUR** solo acepta valores alfanuméricos válidos según la normativa vigente.

***

### 5. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="99.14813232421875">Versión</th><th width="116.48150634765625">Fecha</th><th width="163.14813232421875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>16/10/2025</td><td>Ronald Peláez</td><td>Documento inicial.</td></tr><tr><td>1.1</td><td>08/05/2026</td><td>David Velásquez</td><td>Refinamiento del manual, e incorporación de nuevas secciones.</td></tr></tbody></table>

</details>
