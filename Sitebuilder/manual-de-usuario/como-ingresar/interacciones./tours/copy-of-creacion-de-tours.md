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

# Copy of Creación de tours

<mark style="color:$info;">Módulo para crear y configurar los tours que se visualizan en la plataforma Usuarios Online, definiendo los parámetros de funcionamiento y presentación.</mark>

***

#### 2. Formulario para creación de tours

El formulario se divide en pasos, cada uno correspondiente a un segmento de configuración del tour.

{% tabs %}
{% tab title="Paso 1" %}
**Nuevo tour**

Configuración de la información básica y los parámetros generales del tour.

**Visualización**

<figure><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2F1yFZVdwjtoz7ZiRJKXJS%2Fimage.png?alt=media&#x26;token=d7f64c32-8a30-409d-8eff-5f50fec78a36" alt=""><figcaption><p>Figura #1: Captura de pantalla creación de Tour - paso 1.</p></figcaption></figure>

**Datos generales**

Información general del tour.

<table><thead><tr><th width="129">Campo</th><th width="124">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del tour</code></strong></td><td>Texto</td><td>Nombre asignado al tour.</td></tr><tr><td><strong><code>Descripción interna</code></strong></td><td>Texto</td><td>Breve descripción del propósito o contenido del tour, de uso interno.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Lista desplegable</td><td>Orden de visualización del tour respecto a los demás tours creados y activos. Cuando existen varios tours en una misma sección, se muestra primero el de mayor prioridad.</td></tr><tr><td><strong><code>Rango de fechas</code></strong></td><td>Calendario</td><td>Fechas de inicio y finalización del periodo de actividad del tour en la plataforma.</td></tr></tbody></table>

<a class="button secondary">Siguiente</a>
{% endtab %}

{% tab title="Paso 2" %}
**Segmentación de audiencia**

Configuración de los criterios que determinan a qué usuarios se muestra el tour en la plataforma.

**Visualización**

<figure><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2Fg2AofizUrQ3psjQf2LM7%2Fimage.png?alt=media&#x26;token=2c2c98c9-e94c-4553-a100-e88cc6719a8a" alt=""><figcaption><p>Figura #1: Captura de pantalla creación de Tour - paso 2.</p></figcaption></figure>

**Público objetivo**

El tour se muestra únicamente a los usuarios que cumplan los criterios de la opción seleccionada. Cada opción dispone de configuraciones específicas para definir el público al que se dirige el tour.

<table><thead><tr><th width="191">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Jugadores recién registrados</code></strong></td><td>Usuarios que se registren en la plataforma Usuarios Online.</td></tr><tr><td><strong><code>Por nivel de lealtad</code></strong></td><td><p>Usuarios que pertenezcan al nivel de lealtad seleccionado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al seleccionar esta opción, se habilita una lista desplegable para elegir el nivel de lealtad al que se dirige el tour <em>(solo es posible seleccionar un nivel).</em></p></div></td></tr><tr><td><strong><code>Subir lista de CSV</code></strong></td><td><p>Usuarios incluidos en un archivo <a href="https://virtualsoft.gitbook.io/plantillas/glosario#csv">.csv</a>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al seleccionar esta opción, se habilita el botón <strong><code>Subir archivo CSV</code></strong>, desde el cual se carga el archivo que contiene los identificadores de los usuarios autorizados para visualizar el tour.</p></div></td></tr><tr><td><strong><code>Disparado desde CRM</code></strong></td><td><p>Usuarios asociados a las campañas configuradas desde el área de CRM.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al seleccionar esta opción, se habilita el campo <strong><code>Agregar ID asignado</code></strong>, en el que se ingresa el identificador de la campaña creada por el área de CRM.</p></div></td></tr><tr><td><strong><code>Todos los jugadores</code></strong></td><td>Todos los jugadores, la próxima vez que inicien sesión en la plataforma.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: En el proceso de edición, este paso solo puede editarse cuando el tour está en estado **Borrador**.
{% endhint %}
{% endtab %}

{% tab title="Paso 3" %}
**Recompensa y modal final**

Configuración de la recompensa que recibe el usuario al finalizar el tour y del modal final. Las configuraciones se organizan por segmentos.

**Visualización**

<figure><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FV6ZJ1EeKR6ILzqPLe4qU%2Fimage.png?alt=media&#x26;token=ae1bda1d-0f57-4f90-b135-85c539a5c89e" alt=""><figcaption><p>Figura #1: Captura de pantalla creación de Tour - paso 3.</p></figcaption></figure>

**Configuración de recompensa**

<table><thead><tr><th width="142">Configuración</th><th width="124">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>El tour entrega recompensa</code></strong></td><td>Interruptor</td><td><p>Establece si el tour entrega recompensa.</p><ul><li><strong>Habilitado</strong>: Se despliegan las configuraciones de bonos y del modal de recompensa.</li><li><strong>Deshabilitado</strong>: No se exige este paso para la creación del tour.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Para que un bono aparezca en la lista de bonos, en el campo "¿<strong>Es para</strong>?" del formulario de creación de bonos debe seleccionarse "<strong>tours</strong>".</p></div></td></tr></tbody></table>

**Tipo de modal final**

Define el tipo de modal que el usuario visualiza al finalizar el tour. Cada tipo tiene configuraciones diferentes.

{% hint style="warning" %}
**Nota**: Por defecto, en esta configuración siempre está seleccionada la opción "**Recompensa**".
{% endhint %}

{% tabs %}
{% tab title="Recompensa" %}
El pop-up de recompensa combina textos, una imagen opcional y un único botón.

<table><thead><tr><th width="136">Configuración</th><th width="121">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Título del modal</code></strong></td><td>Texto</td><td>Título principal del modal de recompensa.</td></tr><tr><td><strong><code>Mensaje principal</code></strong></td><td>Texto</td><td>Mensaje que se visualiza en el modal de recompensa.</td></tr><tr><td><strong><code>Texto secundario</code></strong></td><td>Texto</td><td>Texto adicional que se visualiza en otro párrafo del modal de recompensa.</td></tr><tr><td><strong><code>Texto del botón</code></strong></td><td>Texto</td><td>Texto del botón del modal.</td></tr><tr><td><strong><code>Activar imagen o ilustración</code></strong></td><td>Interruptor</td><td><p>Establece si el pop-up de recompensa incluye una imagen.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al activar esta opción, se habilita la configuración <strong><code>Imagen o ilustración</code></strong>, en la cual se ingresa la imagen del pop-up.</p></div></td></tr></tbody></table>
{% endtab %}

{% tab title="Display" %}
El pop-up display combina imagen y texto, y admite una cantidad limitada de botones.

<table><thead><tr><th width="139">Configuración</th><th width="121">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Agregar imagen</code></strong></td><td>Cargar archivo</td><td>Imagen principal del pop-up.</td></tr><tr><td><strong><code>Título</code></strong></td><td>Texto</td><td>Título del pop-up.</td></tr><tr><td><strong><code>Información</code></strong></td><td>Texto</td><td>Párrafo que se visualiza en el pop-up.</td></tr><tr><td><strong><code>Configuración de botones</code></strong></td><td>Formulario</td><td><p>Botones del pop-up <em>(máximo 3)</em>. Su orden se modifica arrastrándolos con <img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FDwrbM11QZ2GArSAcAwBG%2Ficon_drag_indicator.png?alt=media&#x26;token=78d6f82e-bcae-4beb-9f16-24e255e6f5de" alt=""> y los botones creados se eliminan con <img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FohzgxPPR0UPBBp6AO5de%2FVector%20(4).png?alt=media&#x26;token=2d5571d9-1248-49d2-9ec7-e6a09ef2862d" alt="" data-size="original">. Cada botón se configura con los siguientes campos:<br></p><ul><li><strong>Texto del botón</strong>: Texto del botón visible para el usuario.</li><li><strong>URL de redirección</strong>: URL a la que se redirige al usuario al hacer clic en el botón.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Los botones tienen una prioridad predeterminada según su ubicación: al crear 3 botones, el de la izquierda es acción primaria, el del centro secundaria y el de la derecha terciaria. La prioridad se mantiene por ubicación aunque se cambie el orden de los botones.</p></div></td></tr></tbody></table>
{% endtab %}

{% tab title="Texto" %}
El pop-up texto se conforma únicamente de textos y botones.

<table><thead><tr><th width="125">Configuración</th><th width="121">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Título</code></strong></td><td>Texto</td><td>Título del pop-up.</td></tr><tr><td><strong><code>Información</code></strong></td><td>Texto</td><td>Párrafo que se visualiza en el pop-up.</td></tr><tr><td><strong><code>Botón</code></strong></td><td>Formulario</td><td><p>Botones del pop-up <em>(máximo 3)</em>. Su orden se modifica arrastrándolos con <img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FDwrbM11QZ2GArSAcAwBG%2Ficon_drag_indicator.png?alt=media&#x26;token=78d6f82e-bcae-4beb-9f16-24e255e6f5de" alt=""> y los botones creados se eliminan con <img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FohzgxPPR0UPBBp6AO5de%2FVector%20(4).png?alt=media&#x26;token=2d5571d9-1248-49d2-9ec7-e6a09ef2862d" alt="" data-size="original">. Cada botón se configura con los siguientes campos:<br></p><ul><li><strong>Texto del botón</strong>: Texto del botón visible para el usuario.</li><li><strong>URL de redirección</strong>: URL a la que se redirige al usuario al hacer clic en el botón.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Los botones tienen una prioridad predeterminada según su ubicación: al crear 3 botones, el de la izquierda es acción primaria, el del centro secundaria y el de la derecha terciaria. La prioridad se mantiene por ubicación aunque se cambie el orden de los botones.</p></div></td></tr></tbody></table>
{% endtab %}

{% tab title="Visual" %}
El pop-up visual tiene un diseño enfocado en imágenes.

<table><thead><tr><th width="125">Configuración</th><th width="121">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Agregar imagen</code></strong></td><td>Cargar archivo</td><td>Imagen principal del pop-up.</td></tr><tr><td><strong><code>Título</code></strong></td><td>Texto</td><td>Título del pop-up.</td></tr><tr><td><strong><code>Botón</code></strong></td><td>Formulario</td><td><p>Botones del pop-up <em>(máximo 3)</em>. Su orden se modifica arrastrándolos con <img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FDwrbM11QZ2GArSAcAwBG%2Ficon_drag_indicator.png?alt=media&#x26;token=78d6f82e-bcae-4beb-9f16-24e255e6f5de" alt=""> y los botones creados se eliminan con <img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FohzgxPPR0UPBBp6AO5de%2FVector%20(4).png?alt=media&#x26;token=2d5571d9-1248-49d2-9ec7-e6a09ef2862d" alt="" data-size="original">. Cada botón se configura con los siguientes campos:<br></p><ul><li><strong>Texto del botón</strong>: Texto del botón visible para el usuario.</li><li><strong>URL de redirección</strong>: URL a la que se redirige al usuario al hacer clic en el botón.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Los botones tienen una prioridad predeterminada según su ubicación: al crear 3 botones, el de la izquierda es acción primaria, el del centro secundaria y el de la derecha terciaria. La prioridad se mantiene por ubicación aunque se cambie el orden de los botones.</p></div></td></tr></tbody></table>
{% endtab %}
{% endtabs %}

**Vista previa del modal final**

Previsualización del pop-up configurado, con opción de alternar entre la vista de escritorio y la de dispositivo móvil.
{% endtab %}

{% tab title="Paso 4" %}
**Calificación del tour**

Configuración para que los usuarios puntúen el tour al finalizarlo.

**Visualización**

<figure><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FRbVEFbbcgMG9m8HKr1UV%2Fimage.png?alt=media&#x26;token=48948ca0-2290-4ffc-8c9d-6b7ee8b08e95" alt=""><figcaption></figcaption></figure>

**Configuraciones de calificación**

<table><thead><tr><th width="145">Configuración</th><th width="133">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Activar calificación</code></strong></td><td>Interruptor</td><td><p>Establece si los usuarios pueden puntuar el tour al finalizarlo.</p><ul><li><strong>Habilitado</strong>: Se despliegan las configuraciones de la calificación.</li><li><strong>Deshabilitado</strong>: No se exige este paso para la creación del tour.</li></ul></td></tr><tr><td><strong><code>Tipo de calificación</code></strong></td><td>Selector</td><td><p>Método con el que el usuario califica el tour.</p><ul><li><strong>Estrellas</strong>: El usuario selecciona la cantidad de estrellas con la que califica el tour <em>(de 1 a 5 estrellas)</em>.</li><li><strong>Numérica 1-5</strong>: El usuario asigna una calificación numérica del 1 al 5, siendo 1 la calificación más baja y 5 la más alta.</li></ul></td></tr><tr><td><strong><code>Título de la pantalla de calificación</code></strong></td><td>Texto</td><td>Título de la pantalla de calificación.</td></tr><tr><td><strong><code>Texto descriptivo o mensaje de retroalimentación</code></strong></td><td>Texto</td><td>Texto descriptivo o mensaje de retroalimentación de la pantalla de calificación.</td></tr><tr><td><strong><code>Permitir comentario abierto</code></strong></td><td>Interruptor</td><td>Establece si el usuario puede dejar un comentario abierto al calificar el tour.</td></tr><tr><td><strong><code>Texto del botón</code></strong></td><td>Texto</td><td>Texto del botón de la pantalla de calificación.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: Si se activa la calificación, es obligatorio completar los campos para continuar al siguiente paso, pero para el usuario es opcional responder. Si el usuario cierra la pantalla sin responder, no se le vuelve a solicitar.
{% endhint %}

**Vista del jugador**

Previsualización del pop-up configurado, con opción de alternar entre la vista de escritorio y la de dispositivo móvil.
{% endtab %}

{% tab title="Paso 5" %}
Paso final de la configuración de tours. Desde aquí se agregan los pasos que el usuario sigue en la plataforma Usuarios Online y se previsualiza el resultado final.

**Visualización**

<figure><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2Fwj6nRxRZ351qC9FDjMwi%2Fimage.png?alt=media&#x26;token=26d5abd0-dcae-4973-b623-40e17cf5e830" alt=""><figcaption></figcaption></figure>

**¿Cómo crear un paso para el tour?**

Al ingresar a este paso se visualiza un prototipo de la plataforma Usuarios Online, en el que se seleccionan las partes de la plataforma que serán los pasos que sigue el usuario. Antes de crear un paso es posible navegar libremente entre las vistas, páginas y secciones del prototipo, y el tour puede iniciar en cualquier sección configurada, no únicamente en la página principal.

{% @guideflow/guideflow-embed requestedUrl="<https://app.guideflow.com/player/qkq9m27u1r>" %}

{% hint style="warning" %}
**Notas**:

* Antes de empezar a crear los pasos, se debe seleccionar si se crearán para dispositivo Móvil o Escritorio desde ![](https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FnGUHNPfQ2FH2ePunaCXw%2FFrame%201321316373.png?alt=media\&token=3f79ea00-7b8b-4b47-9aff-78d5641c42c5) _(por defecto, siempre está en Escritorio)._
* Para empezar a crear los pasos, primero se debe iniciar sesión en el prototipo con un usuario de la plataforma Usuarios Online.
* Cada paso se configura en una de las versiones (Móvil o Escritorio) y se crea automáticamente en la otra, asociado al mismo componente. Se muestra un mensaje que indica revisar la configuración de los pasos en ambas versiones antes de continuar.
{% endhint %}

**Acciones para crear un paso**

Para crear un paso se hace clic en el prototipo de Usuarios Online. Solo permiten crear pasos los módulos resaltados con fondo amarillo; el elemento seleccionado se identifica visualmente y se despliega un pop-up con 2 opciones.

<table><thead><tr><th width="158">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Crear viñeta</code></strong></td><td>Abre el formulario para configurar el contenido del paso en el lugar seleccionado.</td></tr><tr><td><strong><code>Navegar</code></strong></td><td>Abre la vista del módulo seleccionado sin crear un paso adicional en el tour. Ejemplo: al seleccionar Deportivas y elegir <strong><code>Navegar</code></strong>, se abre la sección de Deportivas.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: Cada paso se asocia a la vista donde se creó. Si el siguiente paso está configurado en otra vista, el sistema redirige al jugador a esa vista y el recorrido continúa automáticamente.
{% endhint %}

**Formulario para la creación de un paso**

<table><thead><tr><th width="133">Campo</th><th width="163">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Título</code></strong></td><td>Texto</td><td>Título del pop-up que el usuario visualiza durante el tour.</td></tr><tr><td><strong><code>Texto principal</code></strong></td><td>Texto</td><td>Texto principal del pop-up del paso.</td></tr><tr><td><strong><code>Agregar imagen de fondo</code></strong></td><td>Cargar archivo</td><td>Imagen de fondo del pop-up del paso.</td></tr><tr><td><strong><code>Agregar mascotas</code></strong></td><td>Interruptor</td><td><p>Establece si se agregan mascotas al lado del paso.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al habilitar este campo, se despliega un campo para agregar la imagen de la mascota, que puede seleccionarse desde una librería o cargarse manualmente.</p></div></td></tr><tr><td><strong><code>Abandonar tour</code></strong></td><td>Interruptor</td><td>Establece si el paso muestra el botón <strong><code>No volver a mostrar</code></strong>, con el que el usuario abandona el tour sin finalizarlo. Si está desactivado, el paso muestra únicamente los demás botones.</td></tr><tr><td><strong><code>¿Este es el último paso?</code></strong></td><td>Interruptor</td><td>Establece que el paso es el último del tour y, por lo tanto, el que muestra el botón de finalizar.</td></tr></tbody></table>

Para crear el paso se selecciona el botón **`Guardar paso`**.

**Botones del paso**

<table><thead><tr><th width="205">Botón</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Siguiente</code></strong></td><td>Avanza al siguiente paso del tour.</td></tr><tr><td><strong><code>Atrás</code></strong></td><td>Regresa al paso anterior.</td></tr><tr><td><strong><code>Omitir para más tarde</code></strong></td><td>Omite el recorrido. El tour se vuelve a mostrar en el próximo inicio de sesión.</td></tr><tr><td><strong><code>No volver a mostrar</code></strong></td><td>Abandona el tour y no se vuelve a mostrar al jugador. Se muestra únicamente cuando el interruptor <strong><code>Abandonar tour</code></strong> está activo.</td></tr></tbody></table>

**¿Cómo gestionar los pasos creados?**

Desde el botón **`Pasos`** se despliega el listado de los pasos creados hasta el momento, con opciones para gestionar cada uno. Cada paso se muestra como una entidad independiente y el listado permite identificar la secuencia completa del tour.

{% hint style="warning" %}
**Nota**: Al seleccionar un paso de la lista, en el modal del prototipo se visualiza el pop-up de ese paso.
{% endhint %}

<table><thead><tr><th width="149">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FcjrFlRELWQ54Dk4QqPo0%2Ficon_desktop_process.png?alt=media&#x26;token=9d07cac0-24d5-4273-960c-88fa0a623666" alt="">/<img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FdOeR8wn9VEBm597mcZWz%2Fimage.png?alt=media&#x26;token=2833ffe3-9b77-49f1-a8be-a342643763ea" alt=""></td><td>Indicador informativo del dispositivo para el que está creado el paso: móvil o escritorio.</td></tr><tr><td><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2Fve07obOcysxRXyFedHTo%2FVector%20(5).png?alt=media&#x26;token=8beaabb3-b5fd-43ed-bf46-390f75056ed2" alt=""></td><td>Despliega el pop-up del formulario para editar el paso.</td></tr><tr><td><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2F0nOfhGJmQ5FObWRBp2AT%2FVector%20(6).png?alt=media&#x26;token=3c49800b-1c05-4568-8d0c-caa578c81aaa" alt=""></td><td>Elimina el paso.</td></tr></tbody></table>

**Previsualizar**

El botón **`Previsualizar`** despliega un pop-up de la plataforma Usuarios Online en el que se visualiza el tour completo. Desde la previsualización se puede navegar entre pasos, ver las transiciones, las imágenes y las mascotas, y alternar entre las vistas Desktop y Mobile.

**Reglas y validaciones de los pasos**

* No se puede crear más de un paso en el mismo lugar. Al intentarlo, aparece un mensaje indicando el error.
* Se pueden configurar varios pasos dentro de una misma vista, siempre que correspondan a lugares diferentes.
* No se puede crear un nuevo paso después de haber configurado un paso como último.
* Los pasos se guardan de forma individual.
* El orden de los pasos no se puede modificar una vez creados. El tour se ejecuta en el orden configurado.
* En el formulario de edición no se pueden agregar nuevos pasos al tour; solo se pueden editar los pasos ya creados.
* Cada paso se configura en una de las versiones (Móvil o Escritorio) y se crea automáticamente en la otra.
* La posición y el contenido del paso pueden configurarse de forma independiente por dispositivo.
* Se muestran indicadores de estado por dispositivo y alertas cuando existe configuración pendiente.

**Comportamiento del tour para el jugador**

* El tour no es obligatorio para el jugador y puede cerrarse en cualquier momento.
* Un tour cuyo primer paso está configurado en una sección específica se asigna al usuario desde el inicio de sesión, pero solo se visualiza cuando el usuario accede a esa sección.
* Al completar el tour, no se vuelve a mostrar.
* Al seleccionar **`Omitir para más tarde`**, el tour se vuelve a mostrar en el próximo inicio de sesión.
* Al seleccionar **`No volver a mostrar`**, el tour no se vuelve a mostrar.
* Si el usuario cambia de dispositivo, el recorrido se reinicia desde el primer paso.
* Cuando existen varios tours en una misma sección, se muestra primero el de mayor prioridad.
{% endtab %}
{% endtabs %}
