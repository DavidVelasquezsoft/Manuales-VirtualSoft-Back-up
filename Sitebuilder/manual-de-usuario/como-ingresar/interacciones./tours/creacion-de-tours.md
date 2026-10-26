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

# Creación de tours

<mark style="color:$info;">Desde este módulo se crean y configuran los tours que se visualizarán en la plataforma Usuarios Online, definiendo los parámetros necesarios para su funcionamiento y presentación.</mark>

***

### 2. Formulario para creación de tours

El formulario se divide en pasos, cada paso hace parte de un segmento de configuraciones para la creación del tour.

{% tabs %}
{% tab title="Paso 1" %}
#### Nuevo tour

En este paso se configura la información básica y los parámetros generales del tour.

#### Visualización

<figure><img src="../../../../.gitbook/assets/image (522).png" alt=""><figcaption><p>Figura #1: Captura de pantalla creación de Tour - paso 1.</p></figcaption></figure>

**Datos generales**

Esta es la información general sobre el tour.

<table><thead><tr><th width="129">Campo</th><th width="124">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del tour</code></strong></td><td>Texto</td><td>Nombre asignado al tour.</td></tr><tr><td><strong><code>Descripción interna</code></strong></td><td>Texto</td><td>Breve descripción del propósito o contenido del tour, destinada a uso interno.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Lista desplegable</td><td>Define el orden de visualización del tour frente a los demás tours creados y activos.</td></tr><tr><td><strong><code>Rango de fechas</code></strong></td><td>Calendario</td><td>Establece las fechas de inicio y finalización del periodo de actividad del tour en la plataforma.</td></tr></tbody></table>

&#x20;                                                                                                                                  <a class="button secondary">Siguiente</a>     &#x20;
{% endtab %}

{% tab title="Paso 2" %}
#### Segmentación de audiencia

En este paso se configuran los criterios que determinan a qué usuarios se les mostrará el tour en la plataforma.

#### Visualización

<figure><img src="../../../../.gitbook/assets/image (523).png" alt=""><figcaption><p>Figura #1: Captura de pantalla creación de Tour - paso 2.</p></figcaption></figure>

#### Público objetivo

El tour se mostrará únicamente a los usuarios que cumplan con los criterios de la opción seleccionada. Cada opción dispone de configuraciones específicas para establecer el público al que estará dirigido el tour.

<table><thead><tr><th width="191">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Jugadores recién registrados</code></strong></td><td>El tour se mostrará a los usuarios que se registren en la plataforma Usuarios Online.</td></tr><tr><td><strong><code>Por nivel de lealtad</code></strong></td><td><p>El tour se mostrará únicamente a los usuarios que pertenezcan al nivel de lealtad seleccionado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al seleccionar esta opción, se habilitará una lista desplegable para elegir el nivel de lealtad al que estará dirigido el tour <em>(solo es posible seleccionar un nivel).</em></p></div></td></tr><tr><td><strong><code>Subir lista de CSV</code></strong></td><td><p>El tour se mostrará únicamente a los usuarios incluidos en un archivo <a href="https://virtualsoft.gitbook.io/plantillas/glosario#csv">.csv</a>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al seleccionar esta opción, se habilitará el botón <strong><code>Subir archivo CSV</code></strong>, desde el cual se podrá cargar el archivo que contiene los identificadores de los usuarios autorizados para visualizar el tour.</p></div></td></tr><tr><td><strong><code>Disparado desde CRM</code></strong></td><td><p>El tour se mostrará a los usuarios asociados a las campañas configuradas desde el área de CRM.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al seleccionar esta opción, se habilitará el campo <strong><code>Agregar ID asignado</code></strong>, en el que se debe ingresar el identificador de la campaña creada por el área de CRM.</p></div></td></tr><tr><td><strong><code>Todos los jugadores</code></strong></td><td>El tour se mostrará a todos los jugadores la próxima vez que inicien sesión en la plataforma.</td></tr></tbody></table>
{% endtab %}

{% tab title="Paso 3" %}
#### Recompensa y modal final

En este paso se configura la recompensa que tendrá el usuario al finalizar el tour, estas configuraciones están separadas por segmentos

#### Visualización

<figure><img src="../../../../.gitbook/assets/image (524).png" alt=""><figcaption><p>Figura #1: Captura de pantalla creación de Tour - paso 2.</p></figcaption></figure>

**Configuración de recompensa**

<table><thead><tr><th width="142">Configuració</th><th width="124">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>El tour entrega recompensa</code></strong></td><td>Interruptor</td><td><p>Establece si el tour entregará o no recompensa.</p><ul><li><strong>Habilitado</strong>: Se desplegarán las configuraciones de bonos y el modal de recompensa.</li><li><strong>Deshabilitado</strong>: No se exigirá este paso para la creación del tour.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Para que un bono aparezca en lista de bonos, en el campo "¿<strong>Es para</strong>?" en el formulario de creación de bonos, debe seleccionar "<strong>tours</strong>".</p></div></td></tr></tbody></table>

**Tipo de modal final**

Establece qué tipo de modal se va a configurar para que el usuario vea al finalizar el tour, cada modal tendrá configuraciones diferentes.&#x20;

{% hint style="warning" %}
**Nota**: Por defecto en esta configuración siempre estará seleccionada la opción "**Recompensa**"
{% endhint %}

{% tabs %}
{% tab title="Recompensa" %}
El pop recompensa se complementa de diferentes tipos de textos, imágenes y botones y un solo botón.

<table><thead><tr><th width="136">Configuración</th><th width="121">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Título del modal</code></strong></td><td>Texto</td><td>Título principal que el usuario verá en el modal de recompensa</td></tr><tr><td><strong><code>Mensaje principal</code></strong></td><td>Texto</td><td>Mensaje secundario que el usuario verá en el modal de recompensa</td></tr><tr><td><strong><code>Texto secundario</code></strong></td><td>Texto</td><td>Texto adicional que el usuario visualizará en otro párrafo en el modal de recompensa</td></tr><tr><td><strong><code>Texto del botón</code></strong></td><td>Texto</td><td>Texto que tendrá el botón que visualizará el usuario en el modal</td></tr><tr><td><strong><code>Activar imagen o ilustración</code></strong></td><td>Interruptor</td><td><p>Establece si el pop-up de recompensa tendrá una imagen.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Cuándo se activa esta opción, se habilitará la configuración <strong><code>Imagen o ilustración</code></strong>, en la cuál se debe ingresar la imagen que tendrá el pop-up</p></div></td></tr></tbody></table>
{% endtab %}

{% tab title="Display" %}
El pop-up display tiene un diseño combinado entre imagen y texto, con la posibilidad de agregar una cantidad de botones determinada.

<table><thead><tr><th width="139">Configuración</th><th width="121">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Agregar imagen</code></strong></td><td>Cargar archivo</td><td>Agrega la imagen principal que tendrá el pop-up</td></tr><tr><td><strong><code>Título</code></strong></td><td>Texto</td><td>Agrega el título que tendrá el pop-up.</td></tr><tr><td><strong><code>Información</code></strong></td><td>Texto</td><td>Párrafo que se visualizará en el pop-up de recompensa.</td></tr><tr><td><strong><code>Configuración de botones</code></strong></td><td>Formulario</td><td><p>Este pop-up es posible crearlo con varios botones <em>(máximo 3)</em>, desde aquí se pueden configurar su orden arrastrándolo con  <img src="../../../../.gitbook/assets/icon_drag_indicator (2).png" alt=""> o eliminar los botones creados con  <img src="../../../../.gitbook/assets/Vector (4) (1).png" alt="" data-size="original">, los botones se configuran utillizando lo siguientes campos:<br> </p><ul><li><strong>Texto del botón</strong>: Texto que tendrá el botón que verá el usuario.</li><li><strong>URL de redirección</strong>: URL donde será redirigido el usuario al dar Click al botón.  </li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Los botones tienen una prioridad predeterminada, en caso de crear 3 botones, el de la izquierda será acción primaria, el del centro secundaria y el derecho terciario, aunque se cambie el orden de los botones, siempre tendrá la misma prioridad según la ubicación.</p></div></td></tr></tbody></table>
{% endtab %}

{% tab title="Texto" %}
El pop-up texto solo se conforma de textos y botones.

<table><thead><tr><th width="125">Configuración</th><th width="121">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Título</code></strong></td><td>Texto</td><td>Agrega el título que tendrá el pop-up.</td></tr><tr><td><strong><code>Información</code></strong></td><td>Texto</td><td>Párrafo que se visualizará en el pop-up de recompensa.</td></tr><tr><td><strong><code>Botón</code></strong></td><td>Formulario</td><td><p>Este pop-up es posible crearlo con varios botones <em>(máximo 3)</em>, desde aquí se pueden configurar su orden arrastrándolo con  <img src="../../../../.gitbook/assets/icon_drag_indicator (2).png" alt=""> o eliminar los botones creados con  <img src="../../../../.gitbook/assets/Vector (4) (1).png" alt="" data-size="original">, los botones se configuran utillizando lo siguientes campos:<br> </p><ul><li><strong>Texto del botón</strong>: Texto que tendrá el botón que verá el usuario.</li><li><strong>URL de redirección</strong>: URL donde será redirigido el usuario al dar Click al botón.  </li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Los botones tienen una prioridad predeterminada, en caso de crear 3 botones, el de la izquierda será acción primaria, el del centro secundaria y el derecho terciario, aunque se cambie el orden de los botones, siempre tendrá la misma prioridad según la ubicación.</p></div></td></tr></tbody></table>
{% endtab %}

{% tab title="Visual" %}
El pop visual tiene un diseño más enfocado en imágenes.

<table><thead><tr><th width="125">Configuración</th><th width="121">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Agregar imagen</code></strong></td><td>Archivo</td><td>Imagen principal que tendrá el pop-up</td></tr><tr><td><strong><code>Título</code></strong></td><td>Texto</td><td>Agrega el título que tendrá el pop-up.</td></tr><tr><td><strong><code>Botón</code></strong></td><td>Formulario</td><td><p>Este pop-up es posible crearlo con varios botones <em>(máximo 3)</em>, desde aquí se pueden configurar su orden arrastrándolo con  <img src="../../../../.gitbook/assets/icon_drag_indicator (2).png" alt=""> o eliminar los botones creados con  <img src="../../../../.gitbook/assets/Vector (4) (1).png" alt="" data-size="original">, los botones se configuran utillizando lo siguientes campos:<br> </p><ul><li><strong>Texto del botón</strong>: Texto que tendrá el botón que verá el usuario.</li><li><strong>URL de redirección</strong>: URL donde será redirigido el usuario al dar Click al botón.  </li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Los botones tienen una prioridad predeterminada, en caso de crear 3 botones, el de la izquierda será acción primaria, el del centro secundaria y el derecho terciario, aunque se cambie el orden de los botones, siempre tendrá la misma prioridad según la ubicación.</p></div></td></tr></tbody></table>
{% endtab %}
{% endtabs %}

Vista previa del modal final

Ofrece la opción de visualizar cómo se verá el pop-up configurado, con la opción de cambiar la vista, ya sea desde escritorio o desde dispositivo móvil.
{% endtab %}

{% tab title="Paso 4" %}


Visualización

<figure><img src="../../../../.gitbook/assets/image (525).png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Paso 5" %}


Visualización

<figure><img src="../../../../.gitbook/assets/image (526).png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

