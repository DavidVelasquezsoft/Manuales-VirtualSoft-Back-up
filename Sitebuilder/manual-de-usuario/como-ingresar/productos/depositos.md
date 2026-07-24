---
icon: sack-dollar
---

# Depósitos

<mark style="color:$info;">El módulo de Depósito permite administrar la configuración de la experiencia de depósitos de la plataforma de usuarios online para el partner seleccionado. Desde aquí es posible activar la nueva visual de depósitos, personalizar su apariencia y comportamiento, configurar los estados de las transacciones y gestionar las franquicias de pago, definiendo cuáles se muestran al jugador, en qué orden y con qué pasarelas operan.</mark>

### 1. Acceso al Módulo:

**Ruta de Acceso**: Site Builder > seleccionar partner > Productos > Depósito

***

### 2. Configuraciones previas

Para acceder a este módulo, es necesario haber completado previamente las siguientes configuraciones previas.

<table><thead><tr><th width="207.55560302734375">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País para el cual se realizará la configuración</td></tr></tbody></table>

***

### 3.  Activar o desactivar la nueva visual de depósitos

{% hint style="warning" %}
**Nota:**&#x4C;a nueva visual de depósitos estará **desactivada por defecto**.
{% endhint %}

En la parte superior de la sección se encuentra un **toggle** con dos opciones:

<figure><img src="../../../.gitbook/assets/image (71).png" alt=""><figcaption><p>Figura#1: Captura de pantalla Interruptor</p></figcaption></figure>

<table><thead><tr><th width="156">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Desactivar (predeterminado)</code></strong></td><td><ul><li>No será posible cambiar otras opciones de configuración visual mientras esta esté desactivada.</li><li>Al estar desactivada, los usuarios no podrán cambiar el estado de la visual entre la versión nueva y la antigua.</li></ul></td></tr><tr><td><strong><code>Activar</code></strong></td><td><ul><li>Se habilitan todas las configuraciones visuales disponibles para depósitos.</li><li>Los usuarios podrán elegir entre la visual nueva o mantener la visual anterior.</li></ul></td></tr></tbody></table>

***

### 4. Configuración del módulo

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
Esta pestaña permite administrar las franquicias de depósito que verá el jugador en la plataforma de usuarios online, definiendo cuáles se muestran, en qué orden aparecen y con qué pasarelas de pago operan.

{% hint style="warning" %}
**Nota:** El módulo contempla permisos independientes para **Consulta**, **Creación**, **Edición** y **Eliminación**. Los usuarios que no cuenten con el permiso correspondiente no visualizarán las acciones restringidas.
{% endhint %}

#### **Visualización**

<figure><img src="../../../.gitbook/assets/image (433).png" alt=""><figcaption><p>Figura #4: Captura de pantalla Gestión de franquicias en Depósitos</p></figcaption></figure>

#### **Indicadores (**_**KPIs**_**)**

En la parte superior de la pestaña se muestran indicadores que resumen el estado de las franquicias del país seleccionado.

<table><thead><tr><th width="146.66668701171875">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Franquicias creadas</code></strong></td><td>Cantidad total de franquicias asociadas al partner y país seleccionados, sumando activas e inactivas.</td></tr><tr><td><strong><code>Franquicias activas</code></strong></td><td>Cantidad de franquicias habilitadas, es decir, aquellas disponibles para que el jugador realice depósitos.</td></tr><tr><td><strong><code>Franquicias inactivas</code></strong></td><td>Cantidad de franquicias deshabilitadas, las cuales conservan su configuración pero no se muestran al jugador.</td></tr></tbody></table>

#### **Acciones disponibles**

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Buscar franquicia</strong></td><td>Permite localizar rápidamente una franquicia dentro del listado de tarjetas del país seleccionado, facilitando su gestión cuando existe un número elevado de franquicias configuradas.</td></tr><tr><td><a href="depositos.md#asociar-franquicia"><strong>Asociar franquicia</strong></a></td><td>Permite vincular al partner y país seleccionados una franquicia ya existente en el sistema, definiendo las pasarelas de pago con las que operará y su configuración.</td></tr><tr><td><a href="depositos.md#vista-principal-de-franquicias"><strong>Gestionar franquicias</strong></a></td><td>Permite visualizar, editar, activar, desactivar, eliminar y reordenar las franquicias ya asociadas.</td></tr><tr><td><a href="depositos.md#historial-de-movimientos"><strong>Historial de movimientos</strong></a></td><td>Permite consultar el registro de auditoría con los cambios realizados sobre las franquicias y sus pasarelas.</td></tr></tbody></table>

{% hint style="info" %}
La configuración definida aquí determina el orden en el que las franquicias y sus pasarelas se presentan al jugador al momento de depositar. La prioridad, los rangos de montos, el estado de cada pasarela y las reglas programadas establecen cuál se muestra primero y cuál se utiliza según el monto que el jugador desee depositar.
{% endhint %}

***

#### **Vista principal de franquicias**

Las franquicias asociadas al país seleccionado se muestran en formato de tarjetas, ordenadas según su prioridad. Cada tarjeta presenta las siguientes acciones e información:

<table><thead><tr><th width="214.16668701171875">Acción / Campo</th><th>Descripción</th></tr></thead><tbody><tr><td> <img src="../../../.gitbook/assets/Frame 1321316371.png" alt=""> <strong><code>Editar</code></strong></td><td>Permite modificar el nombre, la imagen, el estado, las pasarelas asociadas, las prioridades, los rangos de montos, los tiempos configurados y las reglas programadas de la franquicia.</td></tr><tr><td><img src="../../../.gitbook/assets/suiche.png" alt="">  <strong><code>Activar / Desactivar</code></strong></td><td>Habilita o deshabilita la franquicia. Al desactivarla, conserva toda su configuración pero deja de mostrarse en la plataforma de usuarios online.</td></tr><tr><td> <img src="../../../.gitbook/assets/image (425).png" alt="" data-size="line"> <strong><code>Eliminar</code></strong></td><td>Elimina la franquicia del sistema junto con su configuración.</td></tr><tr><td><img src="../../../.gitbook/assets/icon_drag_indicator.png" alt=""> <strong><code>Reordenar</code></strong></td><td>Cambia la posición de prioridad de la franquicia mediante arrastrar y soltar; al modificar el orden, el sistema recalcula automáticamente las posiciones.</td></tr><tr><td><strong><code>Nombre de la franquicia</code></strong></td><td>Nombre con el que se identifica la franquicia.</td></tr><tr><td><strong><code>Logo o imagen</code></strong></td><td>Imagen representativa de la franquicia, la cual se muestra al jugador en la plataforma.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual de la franquicia <em>(Activa o Inactiva)</em>.</td></tr><tr><td><img src="../../../.gitbook/assets/icon_credit_card.png" alt="" data-size="line"> <strong><code>Pasarelas</code></strong></td><td>Número de productos de pasarela vinculados a la franquicia.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Posición de la franquicia dentro del orden de visualización <em>(Prioridad #1, #2, #3, etc.)</em>. La prioridad #1 corresponde a la franquicia que el jugador ve en primer lugar en la vista de depósitos.</td></tr><tr><td><img src="../../../.gitbook/assets/icon_flag.png" alt="" data-size="line"><strong><code>Reglas programadas activas</code></strong></td><td>Indicador visual destacado que advierte cuando la franquicia tiene reglas programadas vigentes que modifican temporalmente su prioridad o la de sus pasarelas.</td></tr><tr><td><strong><code>Estado pasarelas</code></strong></td><td>Indicador visual informativo que muestra cuántas de las pasarelas asociadas a la franquicia se encuentran activas y cuántas inactivas, permitiendo identificar de un vistazo si alguna dejó de operar.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Al editar una franquicia, antes de guardar se muestra un resumen de los cambios realizados y el guardado requiere token de autenticación.
{% endhint %}

***

#### **Asociar franquicia**

El botón <img src="../../../.gitbook/assets/Button (4) (1).png" alt="" data-size="line"> permite vincular al partner y país seleccionados una franquicia ya existente en el sistema, y configurar las pasarelas de pago con las que operará. El proceso se realiza en dos pasos.

**Paso 1: Información general**

Al seleccionar el botón <img src="../../../.gitbook/assets/Button (4) (1).png" alt="" data-size="line"> se abre un modal con los siguientes campos:

<table><thead><tr><th width="150.27783203125">Campo</th><th width="111.77777099609375">Obligatorio</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Franquicia</code></strong></td><td>Sí</td><td>Permite seleccionar una franquicia existente en el sistema, creada previamente desde el módulo <a href="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/productos/franquicias">Franquicias BackOffice</a>.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Sí</td><td>Nombre con el que se identificará la franquicia.</td></tr><tr><td><strong><code>Imagen / logo</code></strong></td><td>No</td><td>Imagen representativa de la franquicia, la cual se muestra al jugador en la plataforma.</td></tr></tbody></table>

Una vez diligenciados los campos, se debe seleccionar el botón **Continuar** para avanzar al paso 2.

{% hint style="warning" %}
**Nota:** La imagen y el nombre de la franquicia puede modificarse posteriormente desde la acción <img src="../../../.gitbook/assets/Frame 1321316371.png" alt="" data-size="line"> **Editar** de la tarjeta de la franquicia.
{% endhint %}

**Paso 2: Configuración de pasarelas de pago**

En el segundo modal se define el comportamiento operativo de la franquicia y se seleccionan las pasarelas que participarán en ella:

<table><thead><tr><th width="200">Campo</th><th width="111.77777099609375">Obligatorio</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tiempo de exclusión temporal</code></strong></td><td>Sí</td><td>Define, en minutos, el tiempo que el usuario deberá esperar para volver a realizar un depósito con la misma pasarela después de un rechazo. Durante ese lapso, la plataforma le ofrece la siguiente pasarela disponible según el orden de prioridad.</td></tr><tr><td><strong><code>Productos (pasarelas de pago)</code></strong></td><td>Sí</td><td>Lista desplegable que permite seleccionar, sin límite de cantidad, las pasarelas de pago que quedarán asociados a la franquicia.</td></tr></tbody></table>

{% hint style="warning" %}
**Notas:**

* Solo aparecen disponibles los productos que se encuentren **activos** en la operación sobre la cual se está trabajando configurados desde la sección [productos del BackOffice](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/productos/productos)
* Debe asociarse **como mínimo una pasarela de paago** para poder guardar la franquicia.
{% endhint %}

**Configuración de cada pasarela seleccionada**

Cada pasarela de pago seleccionada se agrega como una **tarjeta** dentro del modal, en la que se configuran los siguientes campos y acciones:

<table><thead><tr><th width="213.111083984375">Campo / Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><img src="../../../.gitbook/assets/icon_drag_indicator.png" alt=""> <strong><code>Mover</code></strong></td><td>Permite reordenar la tarjeta mediante arrastrar y soltar para definir la prioridad del producto. La primera posición corresponde a la pasarela de mayor prioridad, y la interfaz identifica visualmente la primera, segunda, tercera y siguientes prioridades.</td></tr><tr><td><img src="../../../.gitbook/assets/image (425).png" alt="" data-size="line"> <strong><code>Eliminar</code></strong></td><td>Quita el producto de la franquicia.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre del producto de pasarela asociado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Permite activar o desactivar el producto dentro de la franquicia. Al desactivarlo, conserva toda su configuración pero deja de mostrarse al jugador como opción de pago.</td></tr><tr><td><strong><code>Monto mínimo</code></strong></td><td>Monto mínimo que permitirá la pasarela de pago para depósitos.</td></tr><tr><td><strong><code>Monto máximo</code></strong></td><td>Monto máximo que permitirá la pasarela de pago para depósitos.</td></tr><tr><td><strong><code>Porcentaje de costo</code></strong></td><td>Campo informativo que indica el porcentaje que cobra la pasarela; sirve de apoyo para decidir el orden de prioridad.</td></tr><tr><td><strong><code>Cantidad de reglas</code></strong></td><td>Campo informativo que indica el número de reglas creadas que tiene la pasarela de pago actualmente.</td></tr><tr><td><strong><code>Cantidad máxima de solicitudes en estado Enviado</code></strong></td><td><p>Número máximo de solicitudes de depósito en estado <em>Enviado</em> que un mismo usuario puede tener con esa pasarela. Al alcanzarlo, la plataforma omite esa pasarela y continúa con la siguiente disponible según la prioridad.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si el valor es <strong>0</strong> o el campo se deja vacío, esta validación no se aplica.</p></div></td></tr><tr><td><strong><code>Tiempo de espera en estado Enviado</code></strong></td><td><p>Tiempo, en minutos, que una solicitud puede permanecer en estado <em>Enviado</em> antes de mostrar al jugador un mensaje invitándolo a comunicarse con el servicio de atención al cliente.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si el campo se deja vacío, el mensaje no se muestra al jugador, sin importar cuánto tiempo permanezca la solicitud en ese estado.</p></div></td></tr><tr><td><img src="../../../.gitbook/assets/Button agregar.png" alt="" data-size="line"></td><td>Abre el modal de reglas programadas, donde se definen las prioridades temporales del producto.</td></tr></tbody></table>

{% hint style="info" %}
Los montos mínimo y máximo determinan qué pasarela procesará la transacción según el valor que el jugador desee depositar. La interfaz representa visualmente los rangos configurados, por ejemplo:

* Pasarela 1: 10 - 20
* Pasarela 2: 21 - 30
* Pasarela 3: 31 - 40
{% endhint %}

{% hint style="warning" %}
**Nota:** El sistema permite que varias pasarelas compartan el mismo rango de montos. Cuando esto ocurre, se muestra la advertencia: _"Existen pasarelas con rangos compartidos. El orden de prioridad configurado será utilizado para determinar cuál se utilizará primero."_
{% endhint %}

**Reglas programadas**

Desde el botón <img src="../../../.gitbook/assets/Button agregar.png" alt="" data-size="line"> de cada tarjeta se abre un modal que permite crear, editar y eliminar las reglas que modifican temporalmente la prioridad del producto dentro de la franquicia. Cada regla se configura con los siguientes campos:

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha inicial</code></strong></td><td>Fecha desde la cual aplica la regla.</td></tr><tr><td><strong><code>Fecha final</code></strong></td><td>Fecha hasta la cual aplica la regla.</td></tr><tr><td><strong><code>Hora inicial</code></strong></td><td>Hora desde la cual aplica la regla.</td></tr><tr><td><strong><code>Hora final</code></strong></td><td>Hora hasta la cual aplica la regla.</td></tr><tr><td><strong><code>Días de aplicación</code></strong></td><td>Días de la semana en los que la regla estará vigente.</td></tr></tbody></table>

Desde el mismo modal es posible agregar varias reglas, así como editar o eliminar las existentes. La interfaz identifica las reglas **activas**, las **próximas** y las **finalizadas**.

{% hint style="info" %}
**Ejemplo:** _"La Pasarela 3 será prioridad #1 todos los lunes entre las 08:00 y las 09:00"_. Durante ese rango, la plataforma dará preferencia a esa pasarela por encima del orden configurado de forma permanente.
{% endhint %}

{% hint style="warning" %}
**Nota:** No se permite configurar dos reglas que compartan el mismo rango de fecha y hora dentro de una misma franquicia, aun cuando correspondan a productos diferentes, ya que generaría un conflicto en la definición de la prioridad.
{% endhint %}

**Guardar la asociación**

Una vez configurados todos los productos, se selecciona el botón **Guardar**. El sistema solicita el **token de autenticación** y, al validarlo correctamente, la franquicia queda asociada y comienza a mostrarse como una tarjeta en la vista principal y en caso de que se encuentre activa empezará a visualizarse en la plataforma de usuarios online.

{% hint style="warning" %}
**Nota:** Si la información no cumple con las validaciones establecidas, el sistema muestra un mensaje indicando el error a corregir antes de permitir el guardado.
{% endhint %}

***

#### **Historial de movimientos**

Al seleccionar el botón <img src="../../../.gitbook/assets/Button historial de movimiento.png" alt="" data-size="line">se muestra un módulo que permite consultar el registro de los cambios realizados sobre las franquicias y sus pasarelas, identificando qué acción se ejecutó, en qué momento y qué usuario la realizó.

{% hint style="info" %}
**Nota:** Para regresar a la vista principal de franquicias, selecciona el botón <img src="../../../.gitbook/assets/Button (4) (2).png" alt="" data-size="line">.
{% endhint %}

**Filtros**

<table><thead><tr><th width="112">Campo</th><th width="120.44451904296875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Selecciona el periodo del cual se desean consultar los movimientos registrados.</td></tr><tr><td><strong><code>Acción</code></strong></td><td>Lista desplegable</td><td>Filtra los registros según el tipo de acción realizada <em>(Creado, Cargado, Editado, Prioridad cambiada o Monto cambiado)</em>.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Campo de texto</td><td>Permite buscar los movimientos realizados por un usuario específico a partir de su nombre.</td></tr></tbody></table>

**Información de cada movimiento**

Cada acción registrada muestra la siguiente información:

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Partner sobre el cual se realizó la acción.</td></tr><tr><td><strong><code>País</code></strong></td><td>País al que corresponde la franquicia.</td></tr><tr><td><strong><code>Franquicia</code></strong></td><td>Franquicia sobre la cual se ejecutó la acción.</td></tr><tr><td><strong><code>Usuario responsable</code></strong></td><td>Usuario que realizó la acción.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se registró la acción.</td></tr><tr><td><strong><code>Hora</code></strong></td><td>Hora en la que se registró la acción.</td></tr><tr><td><strong><code>Acción ejecutada</code></strong></td><td>Tipo de acción realizada sobre la franquicia o sus pasarelas.</td></tr><tr><td><strong><code>Valor anterior</code></strong></td><td>Valor que tenía la configuración antes del cambio.</td></tr><tr><td><strong><code>Valor nuevo</code></strong></td><td>Valor resultante después del cambio.</td></tr><tr><td><strong><code>Motivo del cambio</code></strong></td><td>Justificación registrada al momento de ejecutar la acción.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

{% hint style="warning" %}
**⚠️ Nota:** Para guardar los cambios, debe hacer clic en el botón **Guardar** ubicado en la parte inferior de la página.
{% endhint %}

***

### 5. Validaciones y Reglas de Negocio

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
* La configuración definida en esta sección determina las franquicias y pasarelas que se muestran al jugador en la plataforma de usuarios online, así como el orden en el que se presentan.
* El módulo contempla permisos independientes para **Consulta**, **Creación**, **Edición** y **Eliminación**. Los usuarios sin permiso no visualizan las acciones restringidas.

***

### **6. Control de Versiones**

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="95.5">Versión</th><th width="126.83331298828125">Fecha</th><th width="142">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>07/08/2025</td><td>Karol Navia</td><td>Adaptación y actualización del manual al formato estándar.</td></tr><tr><td>1.1</td><td>04/09/2025</td><td>Karol Navia</td><td>Añadir Interruptor superior</td></tr><tr><td>1.2</td><td>06/07/2026</td><td>David Velasquez</td><td>Actualización del manual e incorporación de la pestaña gestión de franquicias</td></tr></tbody></table>

</details>
