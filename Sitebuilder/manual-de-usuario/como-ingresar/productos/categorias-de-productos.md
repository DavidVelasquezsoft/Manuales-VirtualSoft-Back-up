---
description: >-
  Permite gestionar las categorías de juegos de un partner-país mediante
  funcionalidades de creación, consulta, edición, organización y configuración
  de su visualización, estado y programación.
---

# Categorías de productos

### 1. Acceso al Módulo

**Ruta de Acceso**: Site Builder > Partner > Productos > Categorías de productos

***

### 2. Configuraciones previas

Para acceder a este módulo, es necesario haber completado previamente las siguientes configuraciones.

<table><thead><tr><th width="207.55560302734375">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País para el cual se realizará la configuración</td></tr></tbody></table>

***

### 3. Visualización

<figure><img src="../../../.gitbook/assets/image (413).png" alt=""><figcaption><p>Figura #1: Vista general módulo de Categorías de juegos.</p></figcaption></figure>

***

### 4. Acciones del Usuario

<table><thead><tr><th width="169.2962646484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="categorias-de-productos.md#id-5.-filtros"><strong>Filtrar</strong></a></td><td>Filtra las categorías según criterios definidos para localizar las categorías deseadas.</td></tr><tr><td><a href="categorias-de-productos.md#id-7.-agregar-categoria"><strong>Agregar categoría</strong></a></td><td>Permite crear una nueva categoría.</td></tr><tr><td><a href="categorias-de-productos.md#id-6.-gestion-de-categorias"><strong>Gestionar categoría</strong></a></td><td>Modifica, elimina, programa y cambia el estado de una categoría existente.</td></tr><tr><td><a href="categorias-de-productos.md#id-8.-reordenar-categorias"><strong>Reordenar</strong></a></td><td>Cambia la posición de las categorías mediante arrastrar y soltar (<em>Drag &#x26; Drop</em>).</td></tr><tr><td><strong>Guardar orden</strong></td><td>Aplica y guarda definitivamente el nuevo orden configurado.</td></tr></tbody></table>

***

### 5. Filtros

Filtra las categorías mediante los siguientes parámetros:

<table><thead><tr><th width="131.22222900390625">Campo</th><th width="138.3704833984375">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre de categoría</code></strong></td><td>Texto</td><td>Busca categorías por nombre completo o parcial.</td></tr><tr><td><strong><code>Tipo de categoría</code></strong></td><td>Lista desplegable</td><td>Filtra por el tipo de categoría ya sea Casino, Casino en Vivo, Virtuales, Minigames, Bingos o Todos.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Consulta categorías Activas, Inactivas o Todas.</td></tr></tbody></table>

> Para aplicar correctamente los filtros presiona el botón <img src="../../../.gitbook/assets/Button (1) (3).png" alt="" data-size="line">.

***

### 6. Gestión de categorías

Las categorías se presentan en elementos individuales de visualización, donde cada categoría contiene las siguientes propiedades y acciones:

<table><thead><tr><th width="224.66668701171875">Propiedad</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Imagen</code></strong></td><td>Indica la imagen o icono de la categoría.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Muestra el nombre de la categoría</td></tr><tr><td><strong><code>Estado de programación</code></strong></td><td>Muestra el estado de programación en el que se encuentra la categoría, los cuales pueden ser:</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="120.666748046875">Estado</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Programada</code></strong></td><td>La categoría tiene configuradas fechas de inicio y fin válidas, cuando entre a ese rango de fechas se activara automáticamente la categoría.</td></tr><tr><td><strong><code>Indefinida</code></strong></td><td>La categoría no tiene fechas de inicio ni fin configuradas y toma el estado que se le asigne de manera manual.</td></tr><tr><td><strong><code>Vencida</code></strong></td><td><p>La fecha fin configurada ya fue superada. La categoría se inactiva automáticamente y deja de visualizarse en la plataforma</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Posteriormente para activarla nuevamente deberá configurar una nueva programación.</p></div></td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table><thead><tr><th width="77.66668701171875">Icono</th><th width="143.8333740234375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><img src="../../../.gitbook/assets/suiche.png" alt="" data-size="line"></td><td><strong><code>Activar / Inactivar</code></strong></td><td><p>Indica el estado de visibilidad de la categoría en la plataforma. Una categoría <strong>Activa</strong> se muestra a los usuarios, mientras que una categoría <strong>Inactiva</strong> permanece oculta.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este estado solo puede gestionarse cuando la categoría se encuentra en estado <strong>Indefinido</strong> o <strong>Programado</strong>. Una vez la programación finaliza y la categoría pasa a estado <strong>Vencido</strong>, quedará inactiva automáticamente. Para volver a activarla, deberá configurarse una nueva programación.</p></div></td></tr><tr><td><img src="../../../.gitbook/assets/Borrar.png" alt=""></td><td><strong><code>Eliminar</code></strong></td><td><p>Permite <strong>eliminar permanentemente</strong> la categoría. Para confirmar la acción, deberá ingresar el <strong>token de autenticación</strong> configurado en el backOffice. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Una vez eliminada, la categoría dejará de estar disponible y ya no se mostrará en la plataforma para los usuarios.</p></div></td></tr><tr><td><img src="../../../.gitbook/assets/icon_drag_indicator.png" alt=""></td><td><strong><code>Mover orden</code></strong></td><td>Permite modificar el orden de visualización de las categorías dentro de cada tipo de categoría. <a href="categorias-de-productos.md#id-8.-reordenar-categorias"><em>Ver Validaciones y funcionamiento</em></a></td></tr><tr><td><img src="../../../.gitbook/assets/Propiedades.png" alt=""></td><td><strong><code>Editar</code></strong></td><td>Permite modificar la configuración de una categoría existente, actualizando los siguientes datos:</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="138.16668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado inicial</code></strong></td><td>Define el estado inicial de la categoría al momento de su creación, permitiendo establecer si estará activa o inactiva en la plataforma.</td></tr><tr><td><strong><code>Nombre de categoría</code></strong></td><td>Nombre que identificará la categoría.</td></tr><tr><td><strong><code>Tipo de categoría</code></strong></td><td>Indica el tipo de categoría a la que pertenece (<em>Casino, Casino en Vivo, Virtuales, Minigames o Bingos</em>)</td></tr><tr><td><strong><code>Fecha inicio</code> (</strong><em><strong>Opcional</strong></em><strong>)</strong></td><td>Fecha desde la cual la categoría estará disponible.</td></tr><tr><td><strong><code>Fecha fin</code> (</strong><em><strong>Opcional</strong></em><strong>)</strong></td><td>Fecha hasta la cual la categoría estará disponible.</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Permite cargar desde el equipo la imagen que representará la categoría. La imagen debe cumplir con los formatos y dimensiones indicados en el campo. Al cargar una imagen, la URL correspondiente se completará automáticamente.</td></tr><tr><td><strong><code>URL de imagen</code></strong></td><td><p>Permite ingresar la URL de la imagen que representará la categoría. Al ingresar una URL válida, la imagen se asociará automáticamente.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Puede configurar la imagen mediante una <strong>URL</strong> o mediante la <strong>carga de un archivo</strong>. No es necesario completar ambas opciones.</p></div></td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

### 7. Agregar categoría

Crea una nueva categoría presionando el botón <img src="../../../.gitbook/assets/Button (3) (1).png" alt="" data-size="line"> mediante un formulario con los siguientes campos:

<table><thead><tr><th width="136.5">Campo</th><th width="419.61138916015625">Descripción</th><th width="116.2408447265625" align="center">¿Obligatorio?</th></tr></thead><tbody><tr><td><strong><code>Estado inicial</code></strong></td><td>Define el estado inicial de la categoría al momento de su creación, permitiendo establecer si estará activa o inactiva.</td><td align="center">No</td></tr><tr><td><strong><code>Nombre de categoría</code></strong></td><td>Nombre que identificará la categoría.</td><td align="center">Si</td></tr><tr><td><strong><code>Tipo de categoría</code></strong></td><td>Indica el tipo de categoría a la que pertenecerá (<em>Casino, Casino en Vivo, Virtuales, Minigames o Bingos</em>)</td><td align="center">Si</td></tr><tr><td><strong><code>Fecha inicio</code> (</strong><em><strong>Opcional</strong></em><strong>)</strong></td><td>Fecha desde la cual la categoría estará disponible.</td><td align="center">No</td></tr><tr><td><strong><code>Fecha fin</code> (</strong><em><strong>Opcional</strong></em><strong>)</strong></td><td>Fecha hasta la cual la categoría estará disponible.</td><td align="center">No</td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Permite cargar desde el equipo la imagen que representará la categoría. La imagen debe cumplir con los formatos y dimensiones indicados en el campo. Al cargar una imagen, la URL correspondiente se completará automáticamente.</td><td align="center">Si</td></tr><tr><td><strong><code>URL de imagen</code></strong></td><td><p>Permite ingresar la URL de la imagen que representará la categoría. Al ingresar una URL válida, la imagen se asociará automáticamente.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Puede configurar la imagen mediante una <strong>URL</strong> o mediante la <strong>carga de un archivo</strong>. No es necesario completar ambas opciones.</p></div></td><td align="center">Si</td></tr></tbody></table>

Para crear la categoría correctamente debe presionar el botón <img src="../../../.gitbook/assets/Button (2) (3).png" alt="" data-size="line"> y confirmar la acción con el **Token de autenticación** configurado desde el backOffic&#x65;**.**

***

### 8. Reordenar categorías

Reorganizar el orden de visualización de las categorías dentro de su mismo tipo utilizando el ícono de movimiento (![](../../../.gitbook/assets/icon_drag_indicator.png)) disponible en cada categoría.

#### 8.1. Funcionamiento

1. Seleccione el ícono de movimiento (![](../../../.gitbook/assets/icon_drag_indicator.png)) de la categoría que desea reubicar.
2. Arrastre la categoría hasta la posición deseada.
3. Presione el botón <img src="../../../.gitbook/assets/Button (2) (3).png" alt="" data-size="line"> para establecerel nuevo orden.

***

### 9. Reglas y validaciones del negocio

* Solo se permiten administrar las categorías asociadas a (_Casino, Casino en Vivo, Virtuales, Minigames y Bingos_)
* Los productos de las categorías se gestionan desde [Productos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/productos/productos) en el BackOffice
* Los cambios de posición no se guardan automáticamente.
* Mientras no se presione el botón de guardar, las modificaciones solo se visualizarán temporalmente en la pantalla.
* El nuevo orden se reflejará en la plataforma de usuarios online una vez se complete el proceso de actualización del sistema.

***

### 10. Control de versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.14813232421875">Versión</th><th width="116.48150634765625">Fecha</th><th width="163.14813232421875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>04/06/2026</td><td>David Velásquez</td><td>Documento inicial.</td></tr></tbody></table>

</details>
