---
description: >-
  Permite gestionar los banners de la plataforma, ya sea modificando los
  existentes o agregando nuevos, lo que permite mantenerlos actualizados y
  personalizados.
---

# Banners

### **1. Acceso al Módulo**

**Ruta:** Site Builder > Seleccionar Partner > Apariencia > Banners

{% hint style="warning" %}
**Nota:** Cualquier usuario que tenga los permisos  podrá acceder a este módulo.
{% endhint %}

***

### **2. Configuraciones previas.**

Antes de realizar las acciones disponibles con los banners, es necesario contar con las siguientes configuraciones:

{% hint style="warning" %}
**Notas**:&#x20;

* Las configuraciones de este módulo dependen de las previas _(ejemplo: los banners en estado logueado no muestran las mismas opciones que en estado no logueado)._
* Estas configuraciones van apareciendo a medida que se sigue la ruta para llegar a este módulo.
{% endhint %}

<table><thead><tr><th width="159.55560302734375">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País para el cual se realizará la configuración</td></tr><tr><td><strong><code>Idioma</code></strong></td><td>Selecciona el idioma en el que se encuentran configurados los banners en la plataforma.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#partner"><strong><code>Partner</code></strong></a></td><td>Nombre del partner a configurar</td></tr><tr><td><strong><code>Dispositivo</code></strong></td><td>Dispositivo al que aplicarán las configuraciones <em>(móvil o escritorio).</em></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado en el que estará el usuario en la plataforma para visualizar los banners a configurar <em>(logueado o no logueado).</em></td></tr></tbody></table>

***

### 3. Alcance del manual

Este manual cubre el uso de la funcionalidad **Banners**, incluyendo las acciones disponibles para su administración.

**Incluye:**

* Acciones disponibles en el módulo de banners.
* Edición, creación, programación y eliminación de banners.
* Establecer el orden de los banners.

***

### **4. Visualización**

<figure><img src="../../../.gitbook/assets/image (418).png" alt=""><figcaption><p>Figura #1: Captura de pantalla módulo de banners.</p></figcaption></figure>

***

### **5. Acciones del usuario**

{% hint style="warning" %}
**Nota**: Los cambios guardados y aplicados pueden tardar aproximadamente 20 minutos en reflejarse.
{% endhint %}

<table><thead><tr><th width="137.88909912109375" align="center">Icono</th><th width="123.77777099609375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><a href="banners.md#id-6.-filtros"><strong>Filtrar</strong></a></td><td>Filtrar los banners existentes</td><td>Permite filtrar los banners según criterios definidos para localizar los banners deseados. </td></tr><tr><td align="center"><a href="banners.md#id-7.-como-crear-un-banner"><img src="../../../.gitbook/assets/Button programar (1).png" alt="" data-size="line"></a></td><td>Crea un nuevo banner</td><td>Despliega un formulario para crear un nuevo banner.</td></tr><tr><td align="center"><a href="banners.md#id-8.-editar-y-configurar-programacion-del-banner"><strong>Editar</strong></a></td><td>Editar banner existente</td><td>Permite editar banners existentes modificando sus campos y programaciones.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/Button (2) (3).png" alt="" data-size="line"></td><td>Guardar cambios</td><td>Aplica las modificaciones en la plataforma de usuarios online.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/ojo (1).png" alt="" data-size="line"></td><td>Previsualizar</td><td>Permite previsualizar en tiempo real la plataforma de usuarios online directamente desde SiteBuilder, sin necesidad de guardar los cambios. Al seleccionar <strong>Previsualizar</strong>, deberá indicar el país y el idioma para visualizar la plataforma con la configuración actual del partner.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}


&#x20;
{% endcolumn %}

{% column width="66.66666666666667%" %}
<details>

<summary>🔽 Funcionamiento de la previsualización</summary>

* La vista refleja **todas las configuraciones realizadas en el SiteBuilder**, incluso aquellas que **aún no han sido guardadas**.
* Los cambios se muestran de forma **temporal y no persistente**, permitiendo validar ajustes sin afectar la plataforma productiva.
* Permite alternar entre **vista escritorio y móvil**, así como cambiar la **resolución de pantalla**, mediante estos botones <img src="https://virtualsoft.gitbook.io/manuales/~gitbook/image?url=https%3A%2F%2F2760919989-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FOjl0Z2z0C78jMb0KvTb8%252Fuploads%252ForWaS2rhhMpGOCoWEtLa%252Fimage.png%3Falt%3Dmedia%26token%3Dc5175e08-d4e5-43c2-a391-3fbfa7f8bf33&#x26;width=398&#x26;dpr=3&#x26;quality=100&#x26;sign=2c67ecca&#x26;sv=2" alt="" data-size="line">.
* Permite **regresar en cualquier momento** a la sección anterior mediante el botón <img src="https://virtualsoft.gitbook.io/manuales/~gitbook/image?url=https%3A%2F%2F2760919989-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FOjl0Z2z0C78jMb0KvTb8%252Fuploads%252FOp1FWbcxQPsPigDxABGq%252Fimage.png%3Falt%3Dmedia%26token%3Dbb67935a-7f4e-447e-9a57-d5e607ec0838&#x26;width=40&#x26;dpr=3&#x26;quality=100&#x26;sign=420702c5&#x26;sv=2" alt="" data-size="line">, para continuar con la configuración sin perder el contexto de trabajo.

</details>

{% hint style="warning" %}
**Nota:** La previsualización está disponible únicamente para los partners disponibles en el sistema.
{% endhint %}
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="146.77764892578125"></th><th width="114.88873291015625"></th><th></th></tr></thead><tbody><tr><td><img src="../../../.gitbook/assets/Button (7).png" alt="" data-size="original"></td><td>Agregar programación al banner</td><td>Configura una o múltiples programaciones de activación del banner en la plataforma de usuarios online. <a href="banners.md#id-8.-editar-y-configurar-programacion-del-banner">Ver funcionamiento y validaciones</a></td></tr></tbody></table>

***

### **6. Filtros**

<table><thead><tr><th width="197.70367431640625">Filtro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Sección del banner (<code>Home</code>)</strong></td><td>Filtra los banners según la categoría a la que pertenezcan dentro de la sección de usuarios online. (<em>Home, Casino, Virtuales, inicio de sesión, etc...</em>)</td></tr><tr><td><strong>Estado del banner (<code>Activos</code>)</strong></td><td><p>Permite filtrar los banners según su estado actual:</p><ul><li><strong>Activo:</strong> El banner se encuentra habilitado y podrá visualizarse en la plataforma cuando tenga una programación vigente.</li><li><strong>Expirado:</strong> El banner fue deshabilitado manualmente o todas las programaciones del banner han finalizado, por lo que ya no se visualiza en la plataforma.</li></ul></td></tr></tbody></table>

Los banners se despliegan de manera permanente debajo de los filtros y se actualizan automáticamente en tiempo real según los filtros seleccionados.

{% hint style="warning" %}
**Nota:** La visualización de los banners depende de las configuraciones previas del módulo, como Partner, país, idioma y estado de autenticación del usuario.
{% endhint %}

***

### **7. ¿Cómo crear un banner?**&#x20;

{% stepper %}
{% step %}
#### Agregar banner

Utiliza el botón **`Agregar`** que se visualiza en la sección principal de banners.
{% endstep %}

{% step %}
#### Establecer categoría del banner.

<figure><img src="../../../.gitbook/assets/image (300).png" alt="" width="563"><figcaption><p>Figura #3: Captura de pantalla ubicación del banner.</p></figcaption></figure>

Los banners pueden configurarse en diferentes secciones de la plataforma, incluyendo:

<table><thead><tr><th width="127.4444580078125">Ubicación</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Home</code></strong></td><td>Banner visible en la página principal de la plataforma.</td></tr><tr><td><strong><code>Izquierdo</code></strong></td><td>Banner ubicado en la parte lateral izquierda de la interfaz.</td></tr><tr><td><strong><code>Derecho</code></strong></td><td>Banner ubicado en la parte lateral derecha de la interfaz.</td></tr><tr><td><strong><code>Central</code></strong></td><td>Banner que se muestra en el centro de la pantalla, destacando contenido principal.</td></tr><tr><td><strong><code>Casino</code></strong></td><td>Banner exclusivo para la sección de juegos de casino.</td></tr><tr><td><strong><code>Virtuales</code></strong></td><td>Banner destinado a la sección de juegos virtuales.</td></tr><tr><td><strong><code>Live casino</code></strong></td><td>Banner exclusivo para la sección de juegos de casino en vivo.</td></tr><tr><td><strong><code>Banners Bingos</code></strong></td><td>Banner visible en la sección de juegos de bingo.</td></tr><tr><td><strong><code>Inicio de sesión</code></strong></td><td><p>Banner que se muestra en el pop-up de inicio de sesión cuando el usuario aún no ha ingresado a su cuenta.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Esta sección se muestra únicamente cuando en las configuraciones previas se define el estado como <strong>no logueado</strong>.</p></div></td></tr><tr><td><strong><code>Promociones</code></strong></td><td>Banner que se muestra en la página de inicio, dentro de la sección de Promociones de la plataforma.</td></tr><tr><td><strong><code>Lealtad</code></strong></td><td>Este banner será de tipo tradicional y se configurará como el banner principal de visualización, el cual se mostrará en la sección de lealtad de la plataforma.</td></tr></tbody></table>
{% endstep %}

{% step %}
#### Seleccionar el tipo de banner

<figure><img src="../../../.gitbook/assets/image (301).png" alt="" width="563"><figcaption><p>Figura #3: Captura de pantalla tipo de banner.</p></figcaption></figure>

Existen tres tipos de banners disponibles:

<table><thead><tr><th width="177.0740966796875">Tipo de banner</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Tradicional</strong></td><td>Requiere una sola imagen, que se visualizará en la plataforma de usuarios online.</td></tr><tr><td><strong>Compuesto x2</strong></td><td>Requiere dos imágenes, que se mostrarán en la plataforma de usuarios online.</td></tr><tr><td><strong>Compuesto x3</strong></td><td>Requiere tres imágenes, que serán visibles en la plataforma de usuarios online.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: El tamaño permitido de las imágenes puede variar según el tipo de banner que se desee agregar. En caso de que la imagen no cumpla con las características requeridas, se mostrará un mensaje de error.
{% endhint %}
{% endstep %}

{% step %}
#### Agregar banner&#x20;

<table><thead><tr><th width="86.7777099609375">ícono</th><th width="120.92584228515625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><code>➕</code></td><td>Botón</td><td><p>Despliega un formulario para cargar las imágenes y configurar los campos correspondientes al tipo de banner seleccionado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La imagen debe ser del <strong>tipo</strong> y <strong>tamaño</strong> recomendado según el tipo de banner, de lo contrario  se mostrará un mensaje de error.</p></div></td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Dentro de un mismo flujo de creación es posible agregar varios banners:

* Una vez iniciado el flujo de creación, el botón ➕ permite añadir banners adicionales del mismo tipo.
* Si se selecciona otro tipo de banner, se desplegarán formularios específicos para la carga y configuración de ese nuevo tipo.
* Al finalizar el proceso, todos los banners configurados en el flujo serán creados y quedarán listos para su gestión posterior.
{% endhint %}

Para finalizar la creación utiliza el botón **`Aceptar`** para crear el banner y continuar con su configuración.

{% hint style="warning" %}
**Nota:** Al crear el banner, el sistema generará automáticamente una programación inicial activa con la fecha y hora actuales. Posteriormente, deberás revisar y configurar las programaciones del banner según tus necesidades. [#id-7.-editar-y-configurar-programacion-del-banner](banners.md#id-7.-editar-y-configurar-programacion-del-banner "mention")
{% endhint %}
{% endstep %}
{% endstepper %}

***

### 8. Editar y configurar programación del banner

Al crear un banner, el sistema genera automáticamente una programación inicial activa con la fecha del día actual. Desde esta sección podrás administrar las programaciones del banner, incluyendo la creación, edición y eliminación de programaciones, así como configurar otros parámetros asociados a su visualización.

En el banner podrás configurar los siguientes campos:

{% hint style="danger" %}
**Nota importante:** Ninguno de los cambios realizados se reflejará en la plataforma de usuarios online hasta que guardes la información utilizando el botón <img src="../../../.gitbook/assets/Button (2) (3).png" alt="" data-size="line"> ubicado en la parte inferior del módulo.
{% endhint %}

<table><thead><tr><th width="122.33331298828125" align="center">Icono</th><th width="141.81488037109375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><img src="../../../.gitbook/assets/Adobe Express - file (1).png" alt="" data-size="line"></td><td><strong><code>Establecer orden de los banners</code></strong></td><td>Arrastra los banners con este botón para definir el orden en que se mostrarán en la plataforma de usuarios online.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/Frame 1321316372.png" alt=""></td><td><strong><code>Eliminar banner</code></strong></td><td>Elimina de forma definitiva el banner seleccionado y lo retira automáticamente de la plataforma de usuarios online si se encuentra activo.</td></tr><tr><td align="center"> <i class="fa-circle-check" style="color:green;">:circle-check:</i> <em>/</em> <i class="fa-circle-minus" style="color:red;">:circle-minus:</i> </td><td><strong><code>Activar / Desactivar</code></strong></td><td><p>Define si el banner se encuentra habilitado para ser visualizado según sus programaciones configuradas o estará expirado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Para que un banner se visualice en la plataforma debe estar <strong>activo</strong> y contar con una <strong>programación vigente (</strong><em><strong>Activa</strong></em><strong>)</strong>. Si el banner se encuentra expirado, <strong>no se mostrará en la plataforma</strong> aunque tenga programaciones configuradas.</p></div></td></tr><tr><td align="center"><img src="../../../.gitbook/assets/input-right side.png" alt="" data-size="original"></td><td><strong><code>Enlace redirección</code></strong></td><td>indica la URL a la que será dirigido el usuario al hacer clic en el banner.</td></tr><tr><td align="center"></td><td><strong><code>Estado de programación</code></strong></td><td>Permite visualizar la programación más relevante del banner, indicando si se encuentra actualmente activo en la plataforma, pendiente de publicación o si corresponde a la última programación ejecutada, junto con sus fechas y horas de inicio y finalización.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="138.14813232421875">Estado</th><th>Descripción</th></tr></thead><tbody><tr><td><mark style="color:$success;background-color:$success;"><strong>Programación Activa</strong></mark></td><td>Indica que la programación se encuentra vigente y que el banner se está visualizando actualmente en la plataforma de usuarios online. Al finalizar, el sistema activará automáticamente la siguiente programación disponible o, si no existen más programaciones configuradas, el banner pasará al estado <strong>Expirado</strong>.</td></tr><tr><td><mark style="color:purple;background-color:violet;"><strong>Programación Próxima</strong></mark></td><td>Indica que existe una programación futura pendiente de iniciar. El banner se publicará automáticamente cuando llegue la fecha y hora configuradas. Si existe una programación activa anterior, el banner dejará de mostrarse temporalmente entre ambas programaciones.</td></tr><tr><td><mark style="background-color:$info;"><strong>Última programación</strong></mark></td><td>Corresponde a la programación más reciente finalizada cuando no existen programaciones futuras pendientes. Al finalizar esta programación, el banner cambiará automáticamente al estado <strong>Expirado</strong> y dejará de visualizarse en la plataforma.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Las programaciones únicamente se ejecutan cuando el banner se encuentra en estado **Activo**. Un banner solo se visualizará en la plataforma cuando tenga una **programación vigente** y se encuentre **Activo**. Si el banner está **Expirado**, las programaciones configuradas no se aplicarán.
{% endhint %}
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="122.33331298828125" align="center">Icono</th><th width="138.85186767578125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><img src="../../../.gitbook/assets/Frame 1321316347.png" alt=""></td><td><strong><code>Editar programaciones</code></strong></td><td><p>Abre una ventana que permite administrar las programaciones configuradas para el banner. Desde esta sección podrás consultar, agregar, editar o eliminar las programaciones configuradas.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El banner debe contar con al menos una programación configurada. Si no tiene programaciones vigentes o registradas, pasará automáticamente al estado <strong>Expirado</strong>.</p></div></td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<details>

<summary>🔽 Flujo de edición de programación</summary>

Al acceder a esta opción, se mostrará un listado con todas las programaciones asociadas al banner, cada una con la siguiente información:

<table><thead><tr><th width="114.9630126953125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado</code></strong></td><td>Indica si la programación se encuentra <strong>activa</strong> actualmente o corresponde a una <strong>próxima</strong> publicación del banner.</td></tr><tr><td><strong><code>Fecha inicio / fin</code></strong></td><td>Muestra el período de tiempo configurado para la programación, indicando su fecha y hora de inicio y finalización.</td></tr><tr><td><img src="../../../.gitbook/assets/Frame 1321316372.png" alt="" data-size="line"><strong><code>(Eliminar)</code></strong></td><td>Permite eliminar la programación del banner.</td></tr><tr><td><img src="../../../.gitbook/assets/Frame 1321316371.png" alt="" data-size="line"><strong><code>(Editar)</code></strong></td><td><p>Permite modificar la fecha y hora de inicio y de finalización de la programación del banner.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> No se pueden configurar fechas y horarios idénticos a los de otra programación del mismo banner.</p></div></td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Los cambios realizados en cada programación deben confirmarse mediante el botón <img src="../../../.gitbook/assets/Button programar.png" alt="" data-size="line">. Para aplicar definitivamente todas las modificaciones realizadas en el listado de programaciones, utiliza el botón <img src="../../../.gitbook/assets/Button (2) (3).png" alt="" data-size="line">.
{% endhint %}

</details>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="122.33331298828125" align="center">Icono</th><th width="138.85186767578125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><img src="../../../.gitbook/assets/Button (7).png" alt=""></td><td><strong><code>Agregar programación</code></strong></td><td><p>Permite agregar una o múltiples programaciones sin limite a un banner, definiendo las fechas y horarios en los que estará disponible para su visualización en la plataforma.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Las fechas y horarios de una programación no pueden coincidir exactamente con los de otra programación del mismo banner.</p></div></td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="134.11102294921875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha inicio</code></strong></td><td>Día a partir del cual el banner será visible en la plataforma.</td></tr><tr><td><strong><code>Fecha fin</code></strong></td><td>Dia en el que el banner dejará de visualizarse en la plataforma.</td></tr><tr><td><strong><code>Hora inicio</code></strong></td><td>Hora desde la que el banner se mostrará en la plataforma.</td></tr><tr><td><strong><code>Hora fin</code></strong></td><td>Hora en la que el banner dejará de visualizarse en la plataforma.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Para registrar la programación, utiliza el botón <img src="../../../.gitbook/assets/Button programar (1).png" alt="" data-size="line">. Posteriormente, selecciona <img src="../../../.gitbook/assets/Button (2) (3).png" alt="" data-size="line"> para aplicar los cambios al banner.
{% endhint %}
{% endcolumn %}
{% endcolumns %}

***

### 9. Validaciones y reglas de visualización

* Las configuraciones realizadas se visualizarán en la plataforma Usuarios online según el partner que se estará configurando y la sección en la que se agregaron o editaron los banners.
* Si existe más de un banner activo en la misma sección, se muestran en formato carrusel automático.
* Si el banner se agrega correctamente se visualizará un mensaje indicando: _**"**_**El banner se ha creado correctamente**_**"**_
* Si existe solo un banner activo en la plataforma, se muestra de forma estática.
* Los banners se visualizan en el orden definido en el módulo.
* El carrusel rota automáticamente según el intervalo de tiempo configurado en el sistema, sin recargar la página.
* Un mismo banner puede tener una o múltiples programaciones configuradas.
* Las programaciones solo se ejecutarán cuando el banner se encuentre en estado **Activo** y tenga una programación vigente (_Activa_).
* Un mismo banner no puede tener programaciones idénticas.
* Para aplicar cualquier cambio y que se visualice  en la plataforma de usuarios online debe darle al botón **guardar** del modulo.

***

### **10. Control de versiones**

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="98.7037353515625">Versión</th><th width="124.40740966796875">Fecha</th><th width="134.896240234375">Autor</th><th>Cambios realizados</th></tr></thead><tbody><tr><td>1.0</td><td>19-09-2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>28-10-2025</td><td>David Ortiz</td><td>Incorporación de banner promocional y ajustes en campos.</td></tr><tr><td>1.2</td><td>06/05/2026</td><td>David Ortiz</td><td>Incorporación de nuevas notas y validaciones</td></tr><tr><td>1.3</td><td>05/06/2026</td><td>David Ortiz</td><td>Refinamiento del manual, e incorporación de programación de banners</td></tr><tr><td>1.4</td><td>19/06/2026</td><td>Karol Navia</td><td>Añadir el tipo de banner lealtad.</td></tr></tbody></table>

</details>
