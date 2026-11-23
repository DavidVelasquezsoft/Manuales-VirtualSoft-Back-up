---
hidden: true
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

# Copy of Tours

Tours

<mark style="color:$info;">Los tours son secuencias de pasos diseñadas para facilitar el conocimiento y aprendizaje de la plataforma Usuarios Online. Desde este módulo se gestiona la creación y administración de tours y tutoriales que guían el uso de las funcionalidades de la plataforma.</mark>

1. Acceso al Módulo

Ruta de Acceso: SiteBuilder > Seleccionar Partner > Seleccionar País > interacciones > Tours.

{% hint style="warning" %}
Nota: Solo los usuarios con el permiso "Tours" pueden acceder a este módulo. Existen dos tipos de permiso:

Visualizar: Permite acceder al módulo y previsualizar los tours. No permite crear ni editar tours. Crear: Permite, además, crear y editar tours.
{% endhint %}

2. Acciones disponibles

<table><thead><tr><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/interacciones./tours#id-1-lista-de-tours"><strong>Gestionar tours</strong></a></td><td>Visualiza y gestiona los tours creados para la plataforma Usuarios Online.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/interacciones./tours/creacion-de-tours"><strong>Crear tours</strong></a></td><td>Crea tours para secciones específicas de la plataforma Usuarios Online.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/interacciones./tours#id-3-tutoriales"><strong>Gestionar tutoriales</strong></a></td><td>Visualiza y gestiona los tutoriales creados para la plataforma Usuarios Online.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/interacciones./tours#crear-tutorial"><strong>Crear tutoriales</strong></a></td><td>Crea y administra los videos que utilizarán los jugadores para aprender a utilizar la plataforma Usuarios Online.</td></tr></tbody></table>

3\. Gestión de módulos

Esta sección se compone de tres módulos que complementan los tours disponibles en la plataforma Usuarios Online. Cada módulo corresponde a una etapa del proceso de configuración y funcionamiento de los tours.

{% tabs %}
{% tab title="① Lista de tours" %}
El módulo presenta los indicadores y la lista de los tours previamente creados. Para acceder se requiere el permiso "Tours"; crear y editar tours requiere el permiso de tipo Crear.

Visualización

<figure><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2F15s1kJx30Z00ETmRPb5N%2Fimage.png?alt=media&#x26;token=b5372229-b463-4b5f-ac7f-fc6bb7a5f269" alt=""><figcaption><p>Figura #1: Captura de pantalla Tours.</p></figcaption></figure>

KPIs

Los indicadores KPI se componen de las cantidades totales de tours registrados en la plataforma.

<table><thead><tr><th width="145">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total</code></strong></td><td>Tours creados para la plataforma Usuarios Online.</td></tr><tr><td><strong><code>Activos</code></strong></td><td>Tours en estado Activo, que se visualizan en la plataforma Usuarios Online según su configuración de fechas.</td></tr><tr><td><strong><code>Borradores</code></strong></td><td>Tours guardados en estado Borrador, que no se visualizan para los jugadores.</td></tr><tr><td><strong><code>Inactivo</code></strong></td><td>Tours en estado Inactivo, por haber alcanzado su fecha de finalización o por haberse inactivado manualmente. No se visualizan para los jugadores.</td></tr></tbody></table>

Filtros

Los filtros permiten consultar de forma más precisa los tours creados.

<table><thead><tr><th width="174">Filtro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID del tour</code></strong></td><td>Filtra por el identificador del tour.</td></tr><tr><td><strong><code>Nombre del tour</code></strong></td><td>Filtra por el nombre del tour.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Filtra por el estado del tour: Todos, Borradores, Activo, Inactivo o Con recompensa.</td></tr></tbody></table>

{% hint style="warning" %}
Nota: Desde Mostrar imagen se aplican los filtros para obtener información más precisa. También se puede filtrar directamente por el nombre de un tour desde <img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FnNn5oIQ16ZMkZ7OONHeo%2FText%20Input.png?alt=media&#x26;token=f366aa16-a8eb-4164-a105-13fe9c11ef8c" alt="" data-size="line">.
{% endhint %}

Lista de tours

En esta tabla se visualizan los tours previamente creados.

<table><thead><tr><th width="174">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del tour.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre asignado al tour.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td><p>Prioridad que tiene el tour respecto a los demás tours creados.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Desde <img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FDwrbM11QZ2GArSAcAwBG%2Ficon_drag_indicator.png?alt=media&#x26;token=78d6f82e-bcae-4beb-9f16-24e255e6f5de" alt=""> también se puede modificar la prioridad del tour: al arrastrar el tour seleccionado, se establece la prioridad correspondiente a la nueva ubicación.</p></div></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del tour: Borrador, Activo o Inactivo.</td></tr><tr><td><strong><code>Recompensa</code></strong></td><td>Indica si el tour tiene recompensa configurada para los usuarios de la plataforma Usuarios Online que lo finalizan.</td></tr><tr><td><strong><code>ID bono</code></strong></td><td>Identificador del bono que obtienen los usuarios al finalizar el tour.</td></tr><tr><td><strong><code>Audiencia</code></strong></td><td>Audiencia configurada para el tour.</td></tr><tr><td><strong><code>Inicio</code></strong></td><td>Fecha de inicio de la vigencia del tour, cuando está configurada.</td></tr><tr><td><strong><code>Fin</code></strong></td><td>Fecha de finalización de la vigencia del tour, cuando está configurada.</td></tr><tr><td><strong><code>Acciones</code></strong></td><td>Acciones disponibles para gestionar el tour.<br><a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/interacciones./tours#lista-de-acciones" class="button secondary">Lista de acciones</a></td></tr></tbody></table>

<details>

<summary><strong>Lista de acciones</strong></summary>

<table><thead><tr><th width="74">Acción</th><th width="557">Descripción</th></tr></thead><tbody><tr><td><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FGMLZbtP3CDdw8cTNOC6U%2FVector%20(1).png?alt=media&#x26;token=b8c585ae-e13d-439f-9889-c1d6c55e6b5d" alt=""></td><td>Redirige hacia el formulario de creación de tours para editar el tour seleccionado.</td></tr><tr><td><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FJTTtVc4SjQ9WNTPMkMsu%2FVector.png?alt=media&#x26;token=3771f683-78ae-4e09-b7b8-86387c32ec63" alt=""></td><td>Previsualiza el funcionamiento del tour.</td></tr><tr><td><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FkONcf8WsUaA79dbLbr7v%2FVector%20(2).png?alt=media&#x26;token=ecad5704-59d6-44d9-aea0-678a3654e2ea" alt="" data-size="original"></td><td><p>Despliega el pop-up para confirmar si se desea duplicar el tour seleccionado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al duplicar un tour, este se crea con las mismas configuraciones que el seleccionado, pero en estado "<strong>Borrador</strong>".</p></div></td></tr><tr><td><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FR3dz48h1UT4hfUmK5YNy%2Fsettings_power.png?alt=media&#x26;token=5356a95a-3b32-436f-863e-b04d8ed2c46f" alt=""></td><td><p>Despliega un pop-up para confirmar si se desea activar o desactivar un tour.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Esta acción está bloqueada para los tours en estado "<strong>Borrador</strong>". Un tour inactivo solo puede reactivarse si no tiene fecha de finalización o si esta es posterior a la fecha actual; de lo contrario, primero se debe editar la fecha.</p></div></td></tr></tbody></table>

</details>

{% hint style="warning" %}
Nota: Al final de esta tabla se puede modificar la cantidad de registros visualizados.
{% endhint %}

Crear tour

Al seleccionar el botón <img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FdttyLX2MUH91yN2DZRo6%2FButton.png?alt=media&#x26;token=80552a00-6f21-463c-b773-520a56c66df2" alt="" data-size="line"> se redirige al formulario para la creación de tours.

Reglas y validaciones Las acciones disponibles en los tours registrados dependen de los permisos del usuario. En la columna Prioridad se puede ingresar directamente el número que definirá el orden del tour. No se permiten prioridades duplicadas; al asignar una prioridad que ya está ocupada, se ajusta el orden de los tours afectados para mantener una secuencia única y consecutiva. Al modificar la prioridad se muestra una confirmación de éxito.

{% hint style="info" %}
Ejemplo: Si existen 5 tours y el tour con prioridad 3 pasa a tener prioridad 5, el tour que ocupaba la prioridad 5 pasa a la prioridad 4, y los demás tours se reorganizan según corresponda. La prioridad se organiza de menor a mayor.
{% endhint %}

Un tour pasa automáticamente a estado Inactivo al alcanzar su fecha de finalización. Los tours sin fecha de inicio ni de finalización permanecen activos indefinidamente. No se permite cambiar el estado de un tour de Activo a Borrador ni de Inactivo a Borrador. La vista que se muestra en la previsualización depende del usuario de la plataforma Usuarios Online con el que se haya iniciado sesión: las configuraciones, permisos y condiciones de ese usuario determinan lo que se visualiza. Los cambios realizados desde este módulo se aplican de manera inmediata, sin necesidad de otra confirmación.
{% endtab %}

{% tab title="② Indicadores" %}
{% hint style="warning" %}
Nota: Este módulo aún se encuentra en desarrollo, por lo que todavía no cuenta con acceso habilitado ni documentación relacionada.
{% endhint %}
{% endtab %}

{% tab title="③ Tutoriales" %}
{% hint style="danger" %}
Importante: Actualmente, la biblioteca de tutoriales no está disponible en Usuarios Online. Por lo tanto, aunque los tutoriales se pueden crear, no es posible visualizarlos en la plataforma.
{% endhint %}

Los tutoriales son videos que ayudan a conocer los procesos que se pueden realizar en la plataforma Usuarios Online. Desde este módulo se crean y gestionan dichos tutoriales. En la sección "Tutoriales" de la plataforma, los jugadores autenticados visualizan los videos configurados desde este módulo y los tours activos disponibles. Crear, editar, activar o desactivar, reordenar y modificar las fechas de los tutoriales requiere permisos autorizados; sin ellos, solo se puede visualizar la información configurada.

Visualización

<figure><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FGDaPPR83uz0S4YjeBrW0%2Fimage.png?alt=media&#x26;token=45bc4627-a7f0-4274-883c-4070b8d52bf0" alt=""><figcaption><p>Figura #1: Captura de pantalla Tutoriales.</p></figcaption></figure>

Filtros

Los filtros permiten consultar y gestionar de forma más precisa los tutoriales creados para la plataforma Usuarios Online.

<table><thead><tr><th width="145">Filtro</th><th width="132">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td><p>Filtra por los estados en los que se encuentran los tutoriales.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Aunque en el filtro estén disponibles todos los estados, el filtro funciona de la siguiente manera:</p><ul><li><strong>Activo</strong>: Filtra solo por los tutoriales en estado activo.</li><li><strong>Inactivo</strong>: Filtra por los tutoriales vencidos e inactivos al mismo tiempo.</li><li><strong>Programados</strong>: Filtra solo por los tutoriales en estado Programado.</li></ul></div></td></tr><tr><td><strong><code>Calificación</code></strong></td><td>Lista desplegable</td><td>Filtra los tutoriales según la calificación que han obtenido desde la plataforma Usuarios Online.</td></tr><tr><td><strong><code>Vigencia</code></strong></td><td>Calendario</td><td>Filtra según la fecha de vigencia que tenga configurada el tutorial.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Buscador</td><td>Filtra por el nombre del tutorial.</td></tr></tbody></table>

{% hint style="warning" %}
Nota: Desde las acciones <img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2Fdp6vkUyWmIvF6W0AkBzc%2FFrame%201321316631.png?alt=media&#x26;token=840fe86f-635c-402f-b895-173718200157" alt="" data-size="line"> se pueden aplicar filtros o restablecer los filtros previamente aplicados.
{% endhint %}

Lista de tutoriales

En esta tabla se visualizan los tutoriales previamente creados.

<table><thead><tr><th width="174">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FDwrbM11QZ2GArSAcAwBG%2Ficon_drag_indicator.png?alt=media&#x26;token=78d6f82e-bcae-4beb-9f16-24e255e6f5de" alt=""></td><td>Arrastra los tutoriales para modificar su orden de visualización. El orden establecido en esta tabla es el mismo que se muestra en Usuarios Online, y la nueva posición se guarda automáticamente.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del tutorial.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre asignado al tutorial.</td></tr><tr><td><strong><code>Descripción corta</code></strong></td><td>Breve contexto de lo que enseña el tutorial.</td></tr><tr><td><strong><code>Calific.</code></strong></td><td>Calificación obtenida por el tutorial en Usuarios Online.</td></tr><tr><td><strong><code>Vigencia</code></strong></td><td>Rango de fechas en las que estará activo el tutorial.</td></tr><tr><td><strong><code>Estado</code></strong></td><td><p>Estado en el que se encuentra el tutorial.</p><ul><li><strong>Activo</strong>: Tutoriales que están disponibles para que el jugador los visualice.</li><li><strong>Inactivo</strong>: Tutoriales que fueron inactivados manualmente.</li><li><strong>Programado</strong>: Tutoriales que tienen fecha de inicio posterior a la actual.</li><li><strong>Vencido</strong>: Tutoriales cuya fecha final es inferior a la actual.</li></ul></td></tr><tr><td><strong><code>Acciones</code></strong></td><td>Acciones disponibles para gestionar el tutorial.<br><a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/interacciones./tours#lista-de-acciones-1" class="button secondary">Lista de acciones</a></td></tr></tbody></table>

<details>

<summary><strong>Lista de acciones</strong></summary>

<table><thead><tr><th width="74">Acción</th><th width="557">Descripción</th></tr></thead><tbody><tr><td><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FJTTtVc4SjQ9WNTPMkMsu%2FVector.png?alt=media&#x26;token=3771f683-78ae-4e09-b7b8-86387c32ec63" alt="" data-size="original"></td><td>Redirige al módulo de previsualización, en el que se visualiza un ejemplo de cómo queda el tutorial en Usuarios Online.</td></tr><tr><td><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FGMLZbtP3CDdw8cTNOC6U%2FVector%20(1).png?alt=media&#x26;token=b8c585ae-e13d-439f-9889-c1d6c55e6b5d" alt=""></td><td>Redirige hacia el <a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/interacciones./tours#crear-tutorial">formulario de creación de tutoriales</a> para editar el tutorial seleccionado.</td></tr><tr><td><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FR3dz48h1UT4hfUmK5YNy%2Fsettings_power.png?alt=media&#x26;token=5356a95a-3b32-436f-863e-b04d8ed2c46f" alt=""></td><td>Despliega un pop-up para confirmar si se desea activar o desactivar el tutorial.</td></tr><tr><td><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2Ftdm3sWChsh70I1wQFoMp%2FVector%20(3).png?alt=media&#x26;token=9b735a58-8e66-4d8d-bce1-29da7b12b56d" alt="" data-size="original"></td><td>Despliega el pop-up para confirmar si se desea eliminar el tutorial seleccionado.</td></tr></tbody></table>

</details>

{% hint style="warning" %}
Nota: Al final de esta tabla se puede modificar la cantidad de registros visualizados.
{% endhint %}

Crear tutorial

Al seleccionar el botón <img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FBDMNkDeUxT4xo9oZIDmL%2FButton%20(1).png?alt=media&#x26;token=b87f25dd-e375-4d79-ae15-0117dff1a22b" alt="" data-size="line"> se redirige al formulario para la creación de tutoriales.

Formulario para creación de tutorial

Desde esta pestaña se gestionan los tutoriales de la plataforma Usuarios Online mediante la carga de videos previamente grabados y la configuración de los parámetros necesarios para su organización y distribución en la biblioteca de tutoriales.

<table><thead><tr><th width="135">Campo</th><th width="121">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del tutorial</code></strong></td><td>Texto</td><td>Nombre que tendrá el tutorial en la biblioteca de Usuarios Online. Campo obligatorio.</td></tr><tr><td><strong><code>Descripción interna</code></strong></td><td>Texto</td><td>Breve contexto del contenido del tutorial. Campo obligatorio.</td></tr><tr><td><strong><code>Contenido del video</code></strong></td><td>Selector</td><td><p>Establece si el video se sube por medio de una URL externa o cargando el archivo directamente desde el dispositivo. Campo obligatorio.</p><ul><li><p><strong>URL externa:</strong> Se despliega el campo para ingresar la URL del video que tendrá el tutorial.<br></p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Cuando se ingresa la URL, es necesario seleccionar el botón <img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FZy8hnxsV7DhCzVNt6Nlu%2FButton%20(3).png?alt=media&#x26;token=adf81f95-f0b1-4218-9f92-b5b8dbd82cb2" alt="" data-size="line"> para validar la URL ingresada y obtener la vista previa del video.</p></div></li><li><p><strong>Subir video:</strong> Se despliega un pop-up con el gestor de archivos del dispositivo para seleccionar el video que tendrá el tutorial.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: El video ingresado debe tener un peso máximo de 100 MB.</p></div></li></ul></td></tr><tr><td><strong><code>Estado del tutorial</code></strong></td><td>Botón</td><td>Establece si el tutorial se crea inicialmente activo o inactivo.</td></tr><tr><td><strong><code>Miniatura</code></strong></td><td>Archivo</td><td><p>Imagen que se visualiza como miniatura del video.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: La imagen debe tener un <strong>tamaño recomendado de 50 x 50 px</strong>, <strong>peso máximo de 200kb</strong>, y <strong>solo permite formatos JPG y PNG.</strong></p></div></td></tr><tr><td><strong><code>Vigencia</code></strong></td><td>Calendario</td><td><p>Rango de tiempo en el que el tutorial está activo y visible en la biblioteca de tutoriales. La fecha inicial y la fecha final son obligatorias.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Cuando se crea un tutorial con fecha de inicio posterior a la actual, se crea en estado <strong>Programado</strong> y se muestra en la vigencia establecida.</p></div></td></tr></tbody></table>

Para crear correctamente un tutorial es necesario dar clic en el botón Guardar, o en el botón Cancelar para cancelar el proceso.

Visualizar tutoriales.

El botón <img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FoBGLJrl1n2xfrqKeaMcL%2FButton%20(2).png?alt=media&#x26;token=85d5b08f-22a2-4dce-a81b-81ef2da7ebbf" alt="" data-size="line"> redirige a la pestaña Vista previa, donde se encuentra una biblioteca con los videos tutoriales activos en la plataforma, lo que permite visualizar cómo se presentan en Usuarios Online.

{% hint style="warning" %}
Nota: En el previsualizador solo se ven los tutoriales activos y en el orden establecido en la lista. La vista depende del usuario de la plataforma Usuarios Online con el que se haya iniciado sesión.
{% endhint %}

Reglas y validaciones Solo los usuarios con permisos autorizados pueden crear y editar tutoriales, activarlos o desactivarlos, modificar sus fechas de disponibilidad y reordenarlos. Los usuarios sin permisos solo pueden visualizar la información configurada. Al intentar una acción de edición sin permisos, se muestra el mensaje "No tienes permisos para modificar la configuración de Tutoriales." Los campos obligatorios se validan antes de guardar. Si falta información requerida, se muestra un mensaje que indica el campo que debe completarse, por ejemplo: "El nombre del video es obligatorio.", "Debes seleccionar una fecha inicial." o "Debes cargar un video válido." En cualquier momento se pueden editar el nombre, la descripción, el video cargado, las fechas de disponibilidad y el estado del tutorial. Si ocurre un error al guardar los cambios, se muestra el mensaje "Ocurrió un error al actualizar el video tutorial. Intenta nuevamente." Un tutorial que alcanza su fecha final deja de estar disponible para el jugador y puede reactivarse modificando sus fechas. Al reordenar los tutoriales, el orden se actualiza en Usuarios Online sin necesidad de recrearlos.
{% endtab %}
{% endtabs %}

4\. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="108">Versión</th><th width="130">Fecha</th><th width="140">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>14/10/2026</td><td>Ronald Peláez</td><td>Documento inicial <em>(incluye</em> <a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-32313?xpis=eyJicmlkZ2UiOiJzbWFydExpbmtzIiwiaWQiOiIxNzkyMDA2MDU5NjgxIiwic291cmNlIjoiamlyYS1KU1cifQ%3D%3D#icft=VSFT-32313"><em>tours</em></a><em>,</em> <a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-32312?xpis=eyJicmlkZ2UiOiJzbWFydExpbmtzIiwiaWQiOiIxNzkyMDA2MDczODc3Iiwic291cmNlIjoiamlyYS1KU1cifQ%3D%3D#icft=VSFT-32312"><em>pasos</em> </a><em>y</em> <a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33143#icft=VSFT-33143"><em>tutoriales</em></a><em>).</em></td></tr></tbody></table>

</details>
