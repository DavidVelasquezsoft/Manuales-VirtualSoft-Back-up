---
description: >-
  Permite crear, configurar y asignar las imágenes de las tarjetas que se
  visualizarán en el módulo de Deportivas dentro de la plataforma Usuarios
  Online.
---

# Cards deportivas

### 1. Acceso al Módulo

**Ruta de Acceso**: Site Builder > Partner > Productos > Cards deportivas

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (370).png" alt=""><figcaption><p>Figura #1: Captura de pantalla módulo cards deportivas.</p></figcaption></figure>

***

### 3. Configuraciones previas

Para acceder a este módulo, es necesario haber completado previamente las siguientes configuraciones.

{% hint style="warning" %}
**Nota**: Estas configuraciones se desplegarán de forma progresiva a medida que se siga la ruta de navegación correspondiente para ingresar al módulo.
{% endhint %}

<table><thead><tr><th width="207.55560302734375">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País para el cual se realizará la configuración</td></tr></tbody></table>

***

### 4. Acciones del Usuario

<table><thead><tr><th width="170.85174560546875" align="center">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><strong>Filtrar</strong></td><td><p><strong>Filtra por segmento deportivo</strong> <em>(Deportes, Ligas o Partidos)</em> para definir el alcance de la configuración de las tarjetas en el módulo <strong>Tarjetas Deportivas</strong> de Usuarios Online.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Todos los cambios realizados aplicarán únicamente para el módulo seleccionado.</p></div></td></tr><tr><td align="center"><img src="../../../.gitbook/assets/Vector.png" alt="" data-size="original"></td><td>Permite previsualizar, mediante una simulación de la plataforma Usuarios Online, cómo se aplicarán las configuraciones definidas en este módulo, con la opción de alternar la visualización entre modo escritorio y móvil.</td></tr><tr><td align="center"><a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/productos/cards-deportivas#id-5.-configuracion-de-tarjetas-deportivas"><strong>Configurar tarjetas deportivas</strong></a></td><td>Configura tarjetas que estarán disponibles en el módulo de deportivas.</td></tr><tr><td align="center"><strong>Guardar cambios</strong></td><td>Aplica los cambios realizados en la plataforma Usuarios Online.</td></tr></tbody></table>

***

### 5. Configuración de tarjetas deportivas

<table><thead><tr><th width="143">Configuración</th><th width="112" align="center">Botón</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Creación individual de tarjetas</code></strong></td><td align="center"><img src="../../../.gitbook/assets/Increment Button (1).png" alt="" data-size="original"></td><td>Permite agregar una única tarjeta de forma manual desplegando un <strong>pop-up</strong> con un formulario para ingresar la información requerida.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="101">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Ingresa el ID que se asociará a la tarjeta. Se recomienda utilizar el ID de un deporte existente para garantizar una correcta vinculación.</td></tr><tr><td><strong><code>Name</code></strong></td><td>Ingresa el nombre de la tarjeta.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Ingresa la imagen que tendrá la tarjeta.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="143"></th><th width="109"></th><th></th></tr></thead><tbody><tr><td><strong><code>Creación masiva de tarjetas</code></strong></td><td><img src="../../../.gitbook/assets/ChatGPT Image 20 mar 2026, 04_16_52 p.m. (1).png" alt="" data-size="line"></td><td><p>Permite agregar múltiples tarjetas desde un mismo archivo <a href="https://virtualsoft.gitbook.io/untitled/glosario#csv">.CSV</a> que contenga el ID, la URL de la imagen que tendrá la tarjeta y el nombre que tendrá la tarjeta.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Notas</strong>: </p><ul><li>Desde el botón <strong>“<code>Descargar plantilla CSV</code>”</strong> podrás obtener un archivo con la estructura requerida, el cual contiene los campos y el orden necesarios para completar la información y realizar la creación masiva de tarjetas.</li><li><p>Luego de cargar el archivo .CSV, se mostrará un mensaje emergente con el resumen del procesamiento, indicando la cantidad de tarjetas válidas <em>(que serán creadas)</em> y tarjetas inválidas <em>(que no serán creadas)</em>.</p><p>Además, se podrá visualizar el detalle de cada registro, incluyendo el ID de la tarjeta, la URL de la imagen y el estado en el que quedará configurada.</p></li></ul></div></td></tr><tr><td><strong><code>Editar tarjeta creada</code></strong></td><td>Tarjeta</td><td><p>Desde cada tarjeta previamente creada se pueden realizar las siguientes acciones:</p><ul><li><p><strong>Eliminar la tarjeta (🗑️):</strong> Permite eliminar la tarjeta del módulo, dejando de visualizarse en la plataforma Usuarios Online.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al seleccionar esta opción, se desplegará un mensaje de confirmación que permitirá cancelar o confirmar la acción. Una vez confirmada la eliminación, la tarjeta no podrá ser recuperada.</p></div></li><li><p><strong>Ordenar tarjetas (⠿):</strong> Permite cambiar la posición de la tarjeta mediante arrastre.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Este orden solo aplica para la plataforma SiteBuilder.</p></div></li><li><p><strong>Modificar la imagen:</strong> Permite actualizar la imagen de la tarjeta, ya sea ingresando una nueva URL o cargando un archivo desde el dispositivo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Cargar la imagen desde el dispositivo solo estará disponible desde el computador.</p></div></li></ul></td></tr></tbody></table>

***

### 6. Reglas y validaciones

* Si durante la creación individual de una tarjeta se ingresa el ID de una **tarjeta existente**, se realizará la edición de dicha tarjeta en lugar de crear una nueva.
* Es posible crear tarjetas con el mismo nombre y la misma imagen, sin restricciones de duplicidad.
* Solo se permiten imágenes en formato **PNG**, con un tamaño máximo de **200 KB** y dimensiones de **400 x 140 px**.
* Al editar una tarjeta, existen dos opciones para definir la imagen, cargarla desde el dispositivo o ingresar la URL. En caso de utilizar ambas, tendrá prioridad la imagen cargada desde el dispositivo.
* El orden definido para las tarjetas en este módulo se reflejará de la misma manera en **Usuarios Online**.
* Solo los usuarios con permisos habilitados podrán visualizar y realizar configuraciones desde este módulo.
* Al intentar realizar una carga masiva de tarjetas mediante un archivo .CSV, si este no cumple con la estructura definida en la plantilla, se mostrará un mensaje de error.

***

### 7. Flujos relacionados con este módulo

* El **carrusel** que contiene estas tarjetas puede ser modificado desde el módulo [mesa de trabajo](https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/mesa-de-trabajo#sportbook).
* Las tarjetas configuradas en este módulo se visualizarán en la plataforma [Usuarios Online.](https://virtualsoft.gitbook.io/manuales/usuarios/usuarios-online/manual-de-plataforma/apuestas-deportivas)
* Al momento de crear una tarjeta se recomienda crearla con el ID de un deporte existente, esto para asociar la tarjeta a el deporte correspondiente.

***

### 8.Control de versiones

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 20/03/2026 | Ronald Peláez | Documento inicial. |
