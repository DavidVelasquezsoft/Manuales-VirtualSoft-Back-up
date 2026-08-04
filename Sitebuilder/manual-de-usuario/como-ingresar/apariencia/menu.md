# Menú

En este apartado podrás gestionar las categorías del menú que se mostrarán en la plataforma, aquí podrás agregar gif e imágenes con los formatos permitidos (PNG) con un peso máximo de 200 KB.

<figure><img src="../../../.gitbook/assets/image (214).png" alt=""><figcaption><p>Figura #1: Captura de pantalla menú.</p></figcaption></figure>

Desde la vista principal, puedes ver la opción para agregar una nueva categoría al menú de la plataforma. Primero, debes elegir si deseas agregarla a las categorías del menú o si prefieres añadir un gif (los gifs se colocan en la parte inicial del menú). Para agregar cualquiera de estas opciones, simplemente elige entre la opción "**Categorías de menú**" y "**Gif**", luego selecciona el botón de "**Agregar (**<img src="../../../.gitbook/assets/image (113).png" alt="" data-size="line">**)**".

### Categorías de menú:&#x20;

Para agregar una nueva categoría al menú se desplegará en tipo cards el siguiente formulario:

<figure><img src="../../../.gitbook/assets/image (216).png" alt=""><figcaption><p>Figura #2: Captura de pantalla agregar categorías de menú.</p></figcaption></figure>

Desde este formulario debes configurar la categoría que se agregará al menú, completando los siguientes campos:

* **Cargar imagen (**<img src="../../../.gitbook/assets/image (219).png" alt="" data-size="line">**)**: Debes agregar la imagen que tendrá como ícono la nueva categoría que agregarás a la plataforma.
* **Título**: Debes ingresar el título que tendrá la categoría.
* **URL de redirección**: Debes ingresar la URL a la que se redirigirá el usuario al momento se seleccionar esta opción.
* **Botón mover y eliminar**: Con estos botones podrás eliminar la categoría agregada o alternar entre las posiciones del menú con las otras categorías creadas.

{% hint style="warning" %}
**Nota**: El orden en el que se encuentran las categorías en esta sección, ese mismo orden tendrá en la plataforma.
{% endhint %}

### Gif:&#x20;

Para agregar un nuevo Gif al menú se desplegará en tipo cards el siguiente formulario:

<figure><img src="../../../.gitbook/assets/image (221).png" alt="" width="375"><figcaption><p>Figura #2: Captura de pantalla agregar Gif al menú.</p></figcaption></figure>

En este formulario podrás configurar el Gif que se visualizará en la plataforma junto con una vista previa de cómo se verá el Gif.

* **Fondo degradado**: Podrás escoger el color del fondo que tendrán los Gif, tienes la opción de escoger dos colores, los cuales se combinarán y se reflejarán inicialmente en la vista previa.&#x20;
* **Subir imagen izquierda**: Debes ingresar una imagen que acompañará el Gif, al agregarla también aparecerá en la vista previa.
* **Subir gif**: Debes ingresar el gif, este también se verá reflejado en la vista previa.
* **URL de redireccionamiento**: Debes agregar la URL a la que será redirigido el usuario al dar clic en esta Gif.

Finalmente podrás completar los cambios seleccionando el botón "**Guardar**"\
\
\
\
Menú

El módulo **Menú** permite administrar las categorías y los elementos gráficos que serán visualizados en el menú principal de la plataforma. Desde esta sección es posible crear nuevas categorías, configurar GIF promocionales y definir el orden en el que serán presentados a los usuarios.

***

### 1. Acceso al Módulo

**Ruta de Acceso:** Backoffice > Configuración > Menú

***

### 3. Acciones disponibles

<table><thead><tr><th width="169">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Agregar (+)</strong></td><td>Crea un nuevo registro según el tipo de elemento seleccionado.</td></tr><tr><td><strong>Guardar</strong></td><td>Almacena las modificaciones realizadas.</td></tr><tr><td><strong>Mover</strong></td><td>Cambia la posición del elemento dentro del menú.</td></tr><tr><td><strong>Eliminar</strong></td><td>Elimina el elemento seleccionado.</td></tr></tbody></table>

***

#### 4. Configuración del módulo <a href="#id-4.-configuracion-del-modulo" id="id-4.-configuracion-del-modulo"></a>

este modulo cuenta con 2 vistas las cuales son:



{% tabs %}
{% tab title="Categorías de Menú" %}
Al ingresar al módulo se presentan las opciones disponibles para administrar el contenido del menú. Desde esta pantalla es posible seleccionar el tipo de elemento que se desea crear (**Categoría de menú** o **Gif**) y agregar nuevos registros.

Las categorías permiten crear accesos personalizados que serán visualizados dentro del menú principal de la plataforma.

### Visualización



### Configuración

| Campo                    | Tipo         | Descripción                                                             |
| ------------------------ | ------------ | ----------------------------------------------------------------------- |
| **`Imagen`**             | Imagen (PNG) | Registra la imagen que identificará la categoría dentro del menú.       |
| **`Título`**             | Texto        | Define el nombre que será mostrado para la categoría.                   |
| **`URL de redirección`** | URL          | Registra la dirección web que será abierta al seleccionar la categoría. |
| **Mover**                |              | Modifica la posición de la categoría dentro del menú.                   |
| **Eliminar**             |              | Elimina la categoría seleccionada.                                      |

{% hint style="warning" %}
**Importante:**\
El orden en que se organizan las categorías en esta sección corresponde al mismo orden en que serán visualizadas por los usuarios en la plataforma.
{% endhint %}
{% endtab %}

{% tab title="GIF" %}
Los GIF permiten incorporar elementos gráficos animados al inicio del menú principal para destacar promociones, campañas o accesos específicos.

Durante la configuración se presenta una vista previa que facilita validar la apariencia del GIF antes de guardar los cambios.

### Visualización

### Configuración

| Campo                    | Tipo              | Descripción                                                       |
| ------------------------ | ----------------- | ----------------------------------------------------------------- |
| **`Fondo degradado`**    | Selector de color | Define los colores que conformarán el fondo degradado del GIF.    |
| **`Imagen izquierda`**   | Imagen            | Registra la imagen que acompañará el GIF dentro del menú.         |
| **`GIF`**                | Imagen animada    | Registra el archivo GIF que será visualizado en la plataforma.    |
| **`URL de redirección`** | URL               | Registra la dirección web que será abierta al seleccionar el GIF. |
{% endtab %}
{% endtabs %}



***

### 4. Validaciones y reglas del negocio

* Las imágenes utilizadas para las categorías deben estar en formato **PNG**.
* El tamaño máximo permitido para las imágenes es de **200 KB**.
* Los GIF siempre se visualizan al inicio del menú principal.
* El orden configurado para las categorías corresponde al mismo orden en que serán presentadas en la plataforma.
* La vista previa del GIF tiene únicamente fines informativos y no aplica cambios sobre la plataforma.
* Las modificaciones realizadas se almacenan únicamente al hacer clic en **Guardar**.

***

### 5. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

| Versión | Fecha      | Autor           | Cambios Realizados                     |
| ------- | ---------- | --------------- | -------------------------------------- |
| 1.0     | dd/mm/aaaa | **Karol Navia** | Reestructuración adaptado a plantilla. |

</details>
