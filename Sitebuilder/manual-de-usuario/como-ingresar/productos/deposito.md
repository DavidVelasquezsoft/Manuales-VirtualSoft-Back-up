---
icon: sack-dollar
---

# Depósito

<mark style="color:$info;">El módulo de Depósito permite administrar la configuración de la experiencia de depósitos de la plataforma de usuarios online para el partner seleccionado. Desde aquí es posible activar la nueva visual de depósitos, personalizar su apariencia y comportamiento, configurar los estados de las transacciones y gestionar las franquicias que definen el funcionamiento del Orquestador de Franquicias, el cual determina qué franquicia y qué pasarela se utilizan durante el procesamiento de cada depósito.</mark>

### 1. Acceso al Módulo:

**Ruta de Acceso**: Site Builder > seleccionar partner > Productos > Depósito

***

### 2.  Activar o desactivar la nueva visual de depósitos

{% hint style="warning" %}
**Nota:**&#x4C;a nueva visual de depósitos estará **desactivada por defecto**.
{% endhint %}

En la parte superior de la sección se encuentra un **toggle** con dos opciones:

<figure><img src="../../../.gitbook/assets/image (71).png" alt=""><figcaption><p>Figura#1: Captura de pantalla Interruptor</p></figcaption></figure>

<table><thead><tr><th width="156">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Desactivar (predeterminado)</code></strong></td><td><ul><li>No será posible cambiar otras opciones de configuración visual mientras esta esté desactivada.</li><li>Al estar desactivada, los usuarios no podrán cambiar el estado de la visual entre la versión nueva y la antigua.</li></ul></td></tr><tr><td><strong><code>Activar</code></strong></td><td><ul><li>Se habilitan todas las configuraciones visuales disponibles para depósitos.</li><li>Los usuarios podrán elegir entre la visual nueva o mantener la visual anterior.</li></ul></td></tr></tbody></table>

***

### 3. Configuración del módulo

El módulo se organiza en pestañas, cada una enfocada en un aspecto distinto de la configuración de depósitos. A continuación se describe cada una.

{% tabs %}
{% tab title="Configuración Visual" %}
Esta pestaña permite definir la apariencia y el comportamiento de la vista de depósitos que verá el usuario en la plataforma, incluyendo la vista por defecto, los métodos de depósito habilitados y los accesos rápidos.

#### Visualización

<figure><img src="../../../.gitbook/assets/image (82).png" alt=""><figcaption><p>Figura#1: Captura de pantalla configuración visual.</p></figcaption></figure>

#### **Acciones del Usuario**

<table><thead><tr><th width="207">Sección</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Vista predeterminada</code></strong></td><td>Botón de selección (Toggle switch)</td><td>Permite definir si se mostrará la vista moderna o clásica por defecto.</td></tr><tr><td><strong><code>Métodos de depósito</code></strong></td><td>Botón de selección (Toggle switch)</td><td><p>Configura qué tipo de métodos de depósito estará visible para los usuarios en la plataforma.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Solo puede seleccionarse una opción.</p></div></td></tr><tr><td><strong><code>Permite al jugador cambiar entre vista clásica y moderna</code></strong></td><td>Toggle switch</td><td>Habilita la opción que permite al usuario seleccionar entre la vista clásica y la vista moderna.</td></tr><tr><td><strong><code>Escribe el monto por defecto</code></strong></td><td>Campo de texto</td><td>Define el valor sugerido que se mostrará por defecto en el campo de depósito.</td></tr><tr><td><strong><code>Accesos rápidos de depósito</code></strong></td><td>Checkbox</td><td>Permite habilitar y personalizar accesos rápidos con montos predeterminados <em>(S/5, S/10, S/20)</em>, los cuales estarán visibles para el usuario al momento de realizar un depósito.</td></tr><tr><td><strong><code>Depósito con tarjeta de crédito</code></strong></td><td>Checkbox</td><td>Activa o desactiva el uso de tarjeta de crédito como método de depósito.</td></tr><tr><td><strong><code>Pasarela FRI</code></strong></td><td>Checkbox</td><td>Activa o desactiva el uso de pasarela FRI como método de depósito.</td></tr><tr><td><strong><code>Gestión de carrusel de juegos</code></strong></td><td>Radio button + imágenes</td><td>Permite seleccionar una categoría de juegos para visualizar en el carrusel.</td></tr><tr><td><strong><code>Vista previa (👁️)</code></strong></td><td>Botón</td><td>Visualiza una vista previa de la configuración aplicada.</td></tr></tbody></table>
{% endtab %}

{% tab title="Estados" %}
Esta pestaña permite configurar la representación visual y el texto de cada estado por el que puede pasar una transacción de depósito, personalizando lo que verá el usuario según el resultado de su operación.

### Visualización

<figure><img src="../../../.gitbook/assets/image (80).png" alt=""><figcaption><p>Figura#2: Captura de pantalla configuración estados.</p></figcaption></figure>

### **Acciones del Usuario**

<table><thead><tr><th width="202.63336181640625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Agregar imagen</code></strong></td><td><p>Permite subir una imagen representativa para cada estado del depósito.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La imagen que se cargue para cada estado no debe superar los <strong>200 KB</strong> de tamaño.</p></div></td></tr><tr><td><strong><code>Estados configurados por defecto</code></strong></td><td> Muestra el texto que se mostrará al usuario según el estado de la transacción. </td></tr></tbody></table>
{% endtab %}

{% tab title="Gestión de franquicias" %}
Esta pestaña permite configurar la representación visual y el texto de cada estado por el que puede pasar una transacción de depósito, personalizando lo que verá el usuario según el resultado de su operación.

{% hint style="warning" %}
**Nota:** Antes de visualizar información, el operador debe seleccionar el país sobre el cual desea administrar las franquicias. Hasta que no se seleccione un país, no se habilitan las acciones de configuración.
{% endhint %}

#### **Visualización**



#### **Indicadores (KPIs)**

En la parte superior de la pestaña se muestran indicadores que resumen el estado de las franquicias del país seleccionado.

<table><thead><tr><th width="146.66668701171875">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Franquicias creadas</code></strong></td><td>Cantidad total de franquicias registradas para el partner y país seleccionados, sumando activas e inactivas.</td></tr><tr><td><strong><code>Franquicias activas</code></strong></td><td>Cantidad de franquicias que se encuentran activas y participan en el Orquestador.</td></tr><tr><td><strong><code>Franquicias inactivas</code></strong></td><td>Cantidad de franquicias que se encuentran inactivas y no participan en el Orquestador.</td></tr></tbody></table>

#### **Acciones disponibles**

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Buscar franquicia</strong></td><td>Permite localizar rápidamente una franquicia dentro del listado de tarjetas del país seleccionado, facilitando su gestión cuando existe un número elevado de franquicias configuradas.</td></tr><tr><td><strong>Crear franquicia</strong></td><td>Permite registrar una nueva franquicia y configurar sus productos, prioridades, rangos y reglas.</td></tr><tr><td><strong>Gestionar franquicias</strong></td><td>Permite visualizar, editar, activar, desactivar, eliminar y reordenar las franquicias existentes.</td></tr><tr><td><strong>Historial de movimientos</strong></td><td>Permite consultar el registro de auditoría con los cambios realizados sobre las franquicias y sus productos.</td></tr></tbody></table>

***

#### **Vista principal de franquicias**

Las franquicias configuradas para el país seleccionado se muestran en formato de tarjetas. Cada tarjeta presenta la siguiente información:

<table><thead><tr><th width="214.16668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre de la franquicia</code></strong></td><td>Nombre con el que se identifica la franquicia.</td></tr><tr><td><strong><code>Logo o imagen</code></strong></td><td>Imagen representativa de la franquicia.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual de la franquicia <em>(Activa o Inactiva)</em>.</td></tr><tr><td><strong><code>Cantidad de pasarelas asociadas</code></strong></td><td>Número de productos de pasarela vinculados a la franquicia.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Posición de la franquicia dentro del orden de prioridad. La prioridad #1 corresponde a la franquicia que se visualiza en la primera posición de la plataforma en la vista de depósitos <em>(Prioridad #1, #2, #3, etc.)</em>.</td></tr><tr><td><strong><code>Reglas programadas activas</code></strong></td><td>Indicador visual destacado que se muestra cuando la franquicia tiene reglas programadas activas.</td></tr><tr><td><strong><code>Pasarelas inactivas</code></strong></td><td>Indicador visual informativo que se muestra cuando la franquicia tiene pasarelas inactivas, con la cantidad correspondiente.</td></tr><tr><td><strong><code>Fecha de última modificación</code></strong></td><td>Fecha del último cambio realizado sobre la franquicia.</td></tr></tbody></table>

***

#### &#x20;**Crear franquicia**

Mediante el botón **+ Crear Franquicia** se registra una nueva franquicia. La configuración se divide en información general, configuración de productos (_pasarelas de pago_) y reglas programadas.

**Información general**

<table><thead><tr><th width="159.16668701171875">Campo</th><th width="110">Obligatorio</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Sí</td><td>Nombre con el que se identifica la franquicia.</td></tr><tr><td><strong><code>Imagen o logo</code></strong></td><td>Sí</td><td>Imagen representativa de la franquicia.</td></tr><tr><td><strong><code>Monto mínimo</code></strong></td><td>Sí</td><td>Monto mínimo que podrá procesar la franquicia.</td></tr><tr><td><strong><code>Monto máximo</code></strong></td><td>Sí</td><td>Monto máximo que podrá procesar la franquicia.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Sí</td><td>Estado inicial de la franquicia <em>(Activa o Inactiva)</em>.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Al asociar los productos de pasarela, solo aparecerán disponibles aquellos cuyo rango mínimo y máximo (configurado en BackOffice, en productos) sea compatible con el rango definido para la franquicia. Esta validación evita crear franquicias cuyo rango supere el aceptado por la pasarela.
{% endhint %}

**Selección y configuración de productos (pasarelas de pago)**

Durante la creación se seleccionan los productos de pasarela que participarán en la franquicia. Solo se pueden asociar los productos que estén activos dentro de la operación en la que se trabaja, y debe asociarse **como mínimo uno** para poder crear la franquicia.

{% hint style="warning" %}
**Nota:** Lo que aparece como seleccionable son los productos de las pasarelas.
{% endhint %}

Por cada producto asociado se configura y visualiza lo siguiente:

<table><thead><tr><th width="220">Campo / Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Nombre del producto de pasarela.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del producto <em>(Activo o Inactivo)</em>. Puede activarse o desactivarse dentro de la franquicia.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Posición del producto dentro del orden de prioridad de la franquicia. Se ajusta mediante arrastrar y soltar.</td></tr><tr><td><strong><code>Monto mínimo</code></strong></td><td>Monto mínimo que procesará el producto.</td></tr><tr><td><strong><code>Monto máximo</code></strong></td><td>Monto máximo que procesará el producto.</td></tr><tr><td><strong><code>Porcentaje de costo</code></strong></td><td>Campo informativo que indica el porcentaje que cobra la pasarela; sirve de apoyo para tomar decisiones sobre las prioridades.</td></tr><tr><td><strong><code>Tiempo de exclusión temporal</code></strong></td><td>Tiempo durante el cual el producto queda temporalmente excluido tras un rechazo.</td></tr><tr><td><strong><code>Reglas programadas</code></strong></td><td>Reglas que modifican temporalmente la prioridad del producto dentro de la franquicia.</td></tr><tr><td><strong>Activar / Desactivar</strong></td><td>Permite habilitar o inhabilitar el producto dentro de la franquicia sin eliminar su configuración.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Al desactivar un producto, este no se elimina y conserva toda su configuración, pero no participa en la lógica de priorización del Orquestador.
{% endhint %}

Adicionalmente, durante la creación se puede configurar:

<table><thead><tr><th width="155.00006103515625">Campo</th><th width="110">Obligatorio</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad máxima de solicitudes enviadas</code></strong></td><td>No</td><td>Cantidad máxima de solicitudes de depósito que pueden permanecer en estado "Enviada" para la franquicia antes de que el Orquestador habilite el proceso con la siguiente pasarela disponible según la prioridad configurada.</td></tr></tbody></table>

**Priorización de productos**

Los productos se reorganizan mediante **arrastrar y soltar**. La primera posición corresponde al producto de mayor prioridad, y el Orquestador respeta ese orden al seleccionar la pasarela. La interfaz identifica visualmente la primera, segunda, tercera y siguientes prioridades.

**Rangos de montos**

Cada producto permite configurar un **monto mínimo** y un **monto máximo**, que el Orquestador utiliza para seleccionar la pasarela según el monto que el usuario desea depositar. La interfaz representa visualmente los rangos configurados.

<table><thead><tr><th width="200">Ejemplo de producto</th><th>Rango configurado</th></tr></thead><tbody><tr><td>Pasarela 1</td><td>10 - 20</td></tr><tr><td>Pasarela 2</td><td>21 - 30</td></tr><tr><td>Pasarela 3</td><td>31 - 40</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** El sistema permite que varios productos compartan el mismo rango de montos. Cuando esto ocurre, se muestra la advertencia: _"Existen pasarelas con rangos compartidos. El orden de prioridad configurado será utilizado para determinar cuál se utilizará primero."_
{% endhint %}

**Reglas programadas**

El operador puede crear reglas programadas para definir la prioridad de las franquicias o de sus productos dentro de un rango de tiempo determinado. Cada regla permite configurar:

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha inicial</code></strong></td><td>Fecha desde la cual aplica la regla.</td></tr><tr><td><strong><code>Fecha final</code></strong></td><td>Fecha hasta la cual aplica la regla.</td></tr><tr><td><strong><code>Hora inicial</code></strong></td><td>Hora desde la cual aplica la regla.</td></tr><tr><td><strong><code>Hora final</code></strong></td><td>Hora hasta la cual aplica la regla.</td></tr><tr><td><strong><code>Días de aplicación</code></strong></td><td>Días en los que la regla estará vigente.</td></tr></tbody></table>

Una regla puede modificar temporalmente la prioridad de una franquicia _(por ejemplo: "La Franquicia A será prioridad #1 durante una semana")_ o de un producto _(por ejemplo: "La Pasarela 3 será prioridad #1 todos los lunes entre las 08:00 y las 09:00")_. La interfaz muestra claramente las reglas activas, las próximas y las finalizadas.

{% hint style="warning" %}
**Nota:** No se permite configurar dos reglas que compartan el mismo rango de fecha y hora dentro de una misma franquicia, aun cuando estén definidas para productos diferentes, ya que generaría un conflicto en la definición de la prioridad.
{% endhint %}

{% hint style="info" %}
La configuración principal de una franquicia es la administración de los productos de pasarela que participarán en el Orquestador. No es posible crear una franquicia sin al menos un producto asociado.
{% endhint %}

***

**Gestionar franquicias**

Cada tarjeta de franquicia permite ejecutar las siguientes acciones:

<table><thead><tr><th width="180">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Visualizar</strong></td><td>Consulta la configuración completa de la franquicia y sus productos.</td></tr><tr><td><strong>Editar</strong></td><td>Modifica el nombre, la imagen, el estado, los productos asociados, las prioridades, los rangos, el tiempo de exclusión, la cantidad máxima de solicitudes enviadas y las reglas programadas.</td></tr><tr><td><strong>Activar</strong></td><td>Habilita la franquicia dentro del Orquestador.</td></tr><tr><td><strong>Desactivar</strong></td><td>Inhabilita la franquicia sin eliminar su configuración.</td></tr><tr><td><strong>Eliminar</strong></td><td>Elimina la franquicia.</td></tr><tr><td><strong>Reordenar</strong></td><td>Cambia la posición de prioridad de la franquicia mediante arrastrar y soltar; al modificar el orden, el sistema recalcula automáticamente las posiciones.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Al editar una franquicia, antes de guardar se muestra un resumen de los cambios y el guardado requiere token de autenticación.
{% endhint %}

***

#### **Historial de movimientos**

Permite consultar el registro de auditoría con los cambios realizados sobre las franquicias y sus productos. El sistema registra acciones como la creación, edición, eliminación, activación e inactivación de franquicias, la asociación y activación/inactivación de productos, y los cambios de prioridad, rangos, reglas programadas, tiempos de exclusión y cantidad máxima de solicitudes.

Cada registro almacena la siguiente información:

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Partner sobre el cual se realizó la acción.</td></tr><tr><td><strong><code>País</code></strong></td><td>País al que corresponde la franquicia.</td></tr><tr><td><strong><code>Franquicia</code></strong></td><td>Franquicia sobre la cual se ejecutó la acción.</td></tr><tr><td><strong><code>Usuario responsable</code></strong></td><td>Usuario que realizó la acción.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se registró la acción.</td></tr><tr><td><strong><code>Hora</code></strong></td><td>Hora en la que se registró la acción.</td></tr><tr><td><strong><code>Acción ejecutada</code></strong></td><td>Tipo de acción realizada.</td></tr><tr><td><strong><code>Valor anterior</code></strong></td><td>Valor previo al cambio.</td></tr><tr><td><strong><code>Valor nuevo</code></strong></td><td>Valor resultante tras el cambio.</td></tr><tr><td><strong><code>Motivo del cambio</code></strong></td><td>Justificación registrada para la acción.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

{% hint style="warning" %}
**⚠️ Nota:** Para guardar los cambios, debe hacer clic en el botón **Guardar** ubicado en la parte inferior de la página.
{% endhint %}

***

### 4. Validaciones y Reglas de Negocio

* Solo puede estar habilitado un método de depósito a la vez (Pasarela o Franquicias).
* El usuario podrá cambiar entre vista clásica y moderna solo si está habilitado el toggle correspondiente.
* El carrusel mostrará únicamente la categoría seleccionada.
* La sección Gestión de Franquicias solo está disponible cuando hay un partner seleccionado, y requiere seleccionar un país antes de habilitar las acciones de configuración.
* No es posible crear una franquicia sin asociar al menos una pasarela.
* El nombre de la franquicia es obligatorio y no puede duplicarse para un mismo partner y país.
* El monto mínimo no puede ser mayor al monto máximo.
* Al asociar pasarelas, solo se muestran las compatibles con el rango de la franquicia y activas en la operación.
* El tiempo de exclusión debe ser mayor a cero.
* La fecha final no puede ser menor a la fecha inicial, y la hora final no puede ser menor a la inicial cuando corresponde al mismo día.
* No se permiten dos reglas programadas con el mismo rango de fecha y hora dentro de una misma franquicia.
* El guardado de cambios en una franquicia requiere token de autenticación.
* SiteBuilder es la fuente oficial de configuración utilizada por el Orquestador de Franquicias para la toma de decisiones durante el procesamiento de depósitos.
* El módulo contempla permisos independientes para **Consulta**, **Creación**, **Edición** y **Eliminación**. Los usuarios sin permiso no visualizan las acciones restringidas.

***

### **6. Control de Versiones**

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="95.5">Versión</th><th width="126.83331298828125">Fecha</th><th width="142">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>07/08/2025</td><td>Karol Navia</td><td>Adaptación y actualización del manual al formato estándar.</td></tr><tr><td>1.1</td><td>04/09/2025</td><td>Karol Navia</td><td>Añadir Interruptor superior</td></tr><tr><td>1.2</td><td>06/07/2026</td><td>David Velasquez</td><td>Actualización del manual e incorporación de la pestaña gestión de franquicias</td></tr></tbody></table>

</details>
