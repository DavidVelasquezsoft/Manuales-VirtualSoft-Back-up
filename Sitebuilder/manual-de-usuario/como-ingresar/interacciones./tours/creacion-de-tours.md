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
En este paso se configura la información básica y los parámetros generales del tour.

#### Visualización

<figure><img src="../../../../.gitbook/assets/image (519).png" alt=""><figcaption><p>Figura #1: Captura de pantalla paso 1.</p></figcaption></figure>

#### Datos generales

Esta es la información general sobre el tour.

<table><thead><tr><th width="129">Campo</th><th width="124">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del tour</code></strong></td><td>Texto</td><td>Nombre asignado al tour.</td></tr><tr><td><strong><code>Descripción interna</code></strong></td><td>Texto</td><td>Breve descripción del propósito o contenido del tour, destinada a uso interno.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Lista desplegable</td><td>Define el orden de visualización del tour frente a los demás tours creados y activos.</td></tr><tr><td><strong><code>Rango de fechas</code></strong></td><td>Calendario</td><td>Establece las fechas de inicio y finalización del periodo de actividad del tour en la plataforma.</td></tr></tbody></table>

&#x20;                                                                                                                                        <a class="button secondary">Siguiente</a>     &#x20;
{% endtab %}

{% tab title="Paso 2" %}
En este paso se configuran los criterios que determinan a qué usuarios se les mostrará el tour en la plataforma.

Visualización

<figure><img src="../../../../.gitbook/assets/image (520).png" alt=""><figcaption></figcaption></figure>

#### Público objetivo

El tour se mostrará únicamente a los usuarios que cumplan con los criterios del público objetivo seleccionado. Cada opción cuenta con configuraciones específicas que permiten definir las condiciones de visualización. Actualmente, las opciones disponibles son las siguientes:

<table><thead><tr><th width="191">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Jugadores recién registrados</code></strong></td><td>El tour solo lo visualizarán los usuarios que realicen un nuevo registro en la plataforma Usuarios Online.</td></tr><tr><td><strong><code>Por nivel de lealtad</code></strong></td><td><p>El tour se mostrará únicamente a los usuarios que pertenezcan al nivel de lealtad seleccionado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al seleccionar esta opción, se habilitará una lista desplegable para elegir el nivel de lealtad al que estará dirigido el tour <em>(solo es posible seleccionar un nivel).</em></p></div></td></tr><tr><td><strong><code>Subir lista de CSV</code></strong></td><td><p>El tour se mostrará únicamente a los usuarios que se ingresen por medio de un archivo <a href="https://virtualsoft.gitbook.io/plantillas/glosario#csv">.csv</a>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al seleccionar esta opción se desplegará el botón "<strong><code>subir archivo csv</code></strong>" en el que se debe cargar el archivo con los id´s de los usuarios que tendrán acceso al tour.</p></div></td></tr><tr><td><strong><code>Disparado desde CRM</code></strong></td><td><p>El tour se mostrará únicamente a los usuarios configurados desde las campañas creadas por CRM.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al seleccionar esta opción se desplegará el campo "<strong><code>Agregar ID asignado</code></strong>" en el cuál se debe ingresar el id de la campaña creada por el área de CRM.</p></div></td></tr><tr><td><strong><code>Todos los jugadores</code></strong></td><td>El tour se les mostrará a todos los jugadores la próxima vez que inicien sesión.</td></tr></tbody></table>
{% endtab %}

{% tab title="Paso 3" %}

{% endtab %}

{% tab title="Paso 4" %}

{% endtab %}

{% tab title="Paso 5" %}

{% endtab %}
{% endtabs %}
