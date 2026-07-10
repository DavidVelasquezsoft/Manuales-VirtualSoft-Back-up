---
description: >-
  Permite la creación, configuración y gestión de bonos de giros gratuitos
  (FreeSpin) asociados a los juegos del proveedor.
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
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
---

# AMUSNET.

{% hint style="warning" %}
**Notas**:&#x20;

* El número máximo de campañas creadas para este proveedor no puede exceder las **1000 en un mes calendario**.\
  Por ejemplo: si crea 1000 campañas el 20 de junio _(independientemente de la Fecha de Inicio de la campaña)_, su cuota se agotará y no podrá crear más hasta finales de junio.
* En este manual se detallan únicamente los campos cuya configuración presenta condiciones, variaciones o restricciones específicas para la creación de bonos FreeSpin con el proveedor AMUSNET.\
  Para más detalles sobre el proceso completo de creación del bono FreeSpin, consulta la siguiente página.\
  [Manual de usuario FreeSpin](https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin.)
{% endhint %}

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Torneos y Bonos > Crear bono > Seleccionar país > Bono FreeSpin

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (113).png" alt=""><figcaption><p>Figura #1: Captura de pantalla bono FreeSpin.</p></figcaption></figure>

***

### 3. Formulario para creación de bonos Amusnet.

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **Amusnet** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

<table><thead><tr><th width="112">Campo</th><th width="97">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón Agregar</td><td><p>Define la fecha de inicio y finalización en la que el bono estará activo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: </p><ul><li>La campaña debe iniciar en máximo 2 meses y durar hasta 3 meses. En AMUSNET, el bono se activa 5 horas después de la creación. Se recomienda añadir algunos minutos extra a la hora inicial para evitar errores.</li><li>Si se crea un bono tipo <em><strong>Countdown Free Spin</strong></em>, el rango definido entre la fecha de inicio y la fecha de fin corresponderá al tiempo durante el cual el usuario podrá utilizar los giros gratuitos, con un máximo de una <em>(1)</em> hora.</li></ul></div></td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td>Despliega un listado de proveedores con el Bonus System activo. Se debe seleccionar <em><strong>AMUSNET</strong></em>.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td><p>Despliega una lista de juegos del proveedor seleccionado. En este caso, nuevamente se debe elegir <em><strong>AMUSNET</strong></em> para visualizar los juegos disponibles.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al configurar los campos <em>Proveedores</em> y <em>Productos</em> se desplegará una tabla en la cual se debe especificar el porcentaje del bono asumido por el proveedor.</p></div></td></tr></tbody></table>

En el caso de AMUSNET, la configuración varía según el tipo de bono que se cree. Este campo se ajusta en la configuración de la moneda y, dependiendo del bono, puede afectar parámetros definidos previamente.

#### 3.1 Configuración por tipo de bono.

{% hint style="warning" %}
**Nota**: Estas configuraciones se despliegan luego de seleccionar el botón correspondiente a la moneda correspondiente al país al cual se está configurando el bono, pero los campos cambian según la opción seleccionada en el campo "**`Tipo de Bonos`**".
{% endhint %}

{% tabs %}
{% tab title="Free Spin" %}
El bono free spin se utiliza para que los usuarios tengan giros gratis en apuestas de slot o apuestas gratis en casino.

<table><thead><tr><th width="118">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Valor que tendrá el bono en cada ronda.</td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Cantidad de rondas que dará el bono de manera gratuita.</td></tr><tr><td><strong><code>Tipo de bonos</code></strong></td><td>Indica el tipo de bono que se entregará con esta configuración.</td></tr><tr><td><strong><code>Estrategia de valor de apuesta</code></strong></td><td><p>Define cómo se ajusta el valor de la apuesta configurada al valor permitido en el juego.<br><br>- <strong>Minimum</strong>:  El sistema usará el valor de apuesta más bajo permitido por el juego.<br><br>-<strong>Exact</strong>: sistema intentará aplicar exactamente el valor de apuesta configurado. Si el juego lo permite, se usará ese monto sin ajustes. <br></p><p>-<strong>Closest</strong>: El sistema seleccionará el valor de apuesta más cercano posible al configurado, sin importar si es superior o inferior.<br></p><p>-<strong>Closest Lower</strong>: El sistema elegirá el valor de apuesta más cercano, pero siempre menor o igual al configurado.<br></p><p>-<strong>Closest Higher</strong>: El sistema elegirá el valor de apuesta más cercano, pero siempre mayor o igual al configurado.</p></td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Carga un archivo CSV con los id´s de los jugadores que obtendrán el bono.</td></tr></tbody></table>
{% endtab %}

{% tab title="Free Buy Bonus" %}
El bono Free buy bonus se utiliza para que los usuarios puedan comprar bonos dentro de los juegos.

<table><thead><tr><th width="118">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Valor que tendrá el bono en cada ronda.</td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Cantidad de rondas que dará el bono de manera gratuita.</td></tr><tr><td><strong><code>Tipo de bonos</code></strong></td><td>Indica el tipo de bono que se entregará con esta configuración.</td></tr><tr><td><strong><code>Estrategia de valor de apuesta</code></strong></td><td><p>Define cómo se ajusta el valor de la apuesta configurada al valor permitido en el juego.<br><br>- <strong>Minimum</strong>:  El sistema usará el valor de apuesta más bajo permitido por el juego.<br><br>-<strong>Exact</strong>: sistema intentará aplicar exactamente el valor de apuesta configurado. Si el juego lo permite, se usará ese monto sin ajustes. <br></p><p>-<strong>Closest</strong>: El sistema seleccionará el valor de apuesta más cercano posible al configurado, sin importar si es superior o inferior.<br></p><p>-<strong>Closest Lower</strong>: El sistema elegirá el valor de apuesta más cercano, pero siempre menor o igual al configurado.<br></p><p>-<strong>Closest Higher</strong>: El sistema elegirá el valor de apuesta más cercano, pero siempre mayor o igual al configurado.</p></td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Carga un archivo CSV con los id´s de los jugadores que obtendrán el bono.</td></tr></tbody></table>
{% endtab %}

{% tab title="Golden Chip" %}
El bono Golden chip se utiliza solo para apuestas de ruleta en casino en vivo, les brinda a los usuarios apuestas en dichos juegos.



<table><thead><tr><th width="118">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Valor que tendrá el bono en cada ronda.</td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Cantidad de rondas que dará el bono de manera gratuita.</td></tr><tr><td><strong><code>Tipo de bonos</code></strong></td><td>Indica el tipo de bono que se entregará con esta configuración.</td></tr><tr><td><strong><code>Estrategia de valor de apuesta</code></strong></td><td><p>Define cómo se ajusta el valor de la apuesta configurada al valor permitido en el juego.<br><br>- <strong>Minimum</strong>:  El sistema usará el valor de apuesta más bajo permitido por el juego.<br><br>-<strong>Exact</strong>: sistema intentará aplicar exactamente el valor de apuesta configurado. Si el juego lo permite, se usará ese monto sin ajustes. <br></p><p>-<strong>Closest</strong>: El sistema seleccionará el valor de apuesta más cercano posible al configurado, sin importar si es superior o inferior.<br></p><p>-<strong>Closest Lower</strong>: El sistema elegirá el valor de apuesta más cercano, pero siempre menor o igual al configurado.<br></p><p>-<strong>Closest Higher</strong>: El sistema elegirá el valor de apuesta más cercano, pero siempre mayor o igual al configurado.</p></td></tr><tr><td><strong><code>Permisos de tipo de apuesta</code></strong></td><td><p>Establece qué tipos de apuestas están habilitados para el bono, de acuerdo con las opciones que el juego seleccionado <em>(producto)</em> soporte.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Desde esta configuración se podrán seleccionar múltiples estrategias al mismo tiempo <em>(solo para este tipo de bono)</em>.</p></div></td></tr><tr><td><strong><code>Límite de cobertura</code></strong></td><td>Define el valor máximo que puede cubrir el bono en las rondas.</td></tr><tr><td><strong><code>Máximo de fichas por ronda</code></strong></td><td>Límite de fichas <em>(tokens/credits)</em> que se pueden usar en una sola ronda gratuita.</td></tr><tr><td><strong><code>Máximo de fichas por tipo de apuesta</code></strong></td><td>Límite de fichas que se pueden apostar en un mismo tipo de apuesta dentro de la ronda.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Carga un archivo CSV con los id´s de los jugadores que obtendrán el bono.</td></tr></tbody></table>
{% endtab %}

{% tab title="COUNTDOWN FREE SPIN" %}
Este tipo de freespin otorga rondas gratuitas con un contador regresivo activo durante el período configurado.

{% hint style="danger" %}
**Nota importante**:

El rango de tiempo se define entre la **`fecha inicio`** y la **`fecha fin`** del bono, con un máximo de una _(1)_ hora de duración para las rondas gratuitas. Si el bono se configura con un rango superior a una hora, el sistema limitará automáticamente el conteo regresivo a un máximo de una _(1)_ hora, estos campos seguirán cumpliendo su función general, pero también definirán el rango de tiempo del bono.
{% endhint %}

<table><thead><tr><th width="118">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Valor que tendrá el bono en cada ronda.</td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td><p></p><div data-gb-custom-block data-tag="hint" data-style="danger" class="hint hint-danger"><p><strong>Nota importante</strong>: Este campo se encuentra como obligatorio en el formulario, pero no aplica con este tipo de bono, se puede ingresar cualquier valor, pero los giros siempre dependerán del tiempo configurado.</p></div></td></tr><tr><td><strong><code>Tipo de bonos</code></strong></td><td>Indica el tipo de bono que se entregará con esta configuración.</td></tr><tr><td><strong><code>Estrategia de valor de apuesta</code></strong></td><td><p>Define cómo se ajusta el valor de la apuesta configurada al valor permitido en el juego.<br><br>- <strong>Minimum</strong>:  El sistema usará el valor de apuesta más bajo permitido por el juego.<br><br>-<strong>Exact</strong>: sistema intentará aplicar exactamente el valor de apuesta configurado. Si el juego lo permite, se usará ese monto sin ajustes. <br></p><p>-<strong>Closest</strong>: El sistema seleccionará el valor de apuesta más cercano posible al configurado, sin importar si es superior o inferior.<br></p><p>-<strong>Closest Lower</strong>: El sistema elegirá el valor de apuesta más cercano, pero siempre menor o igual al configurado.<br></p><p>-<strong>Closest Higher</strong>: El sistema elegirá el valor de apuesta más cercano, pero siempre mayor o igual al configurado.</p></td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Carga un archivo CSV con los id´s de los jugadores que obtendrán el bono.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

* La información de este bono estará disponible en la reportería de _Productos No Deportivos_.

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos" %}
[Reporte productos no deportivos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos)
{% endcontent-ref %}

* La información sobre los movimientos realizados por el usuario con este bono estará disponible en la reportería _Historial de movimientos._

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/historial-de-movimientos" %}
[Historial de movimientos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/historial-de-movimientos)
{% endcontent-ref %}

***

### **4. Validaciones y Reglas de Negocio** <a href="#id-4.-validaciones-y-reglas-de-negocio" id="id-4.-validaciones-y-reglas-de-negocio"></a>

* El bono se crea de forma inmediata, pero la asignación a jugadores puede tardar entre **2 y 3 minutos**.
* El bono solo puede configurarse para un único juego. Si se seleccionan varios, el sistema asignará uno de ellos de forma aleatoria al momento de la creación.
* Este bono una vez creado quedará disponible para **CRM optimove**.

### 5. Control de versiones.

<details>

<summary>🕛 Historial de versiones</summary>

| Versión | Fecha      | Autor         | Cambios Realizados                                        |
| ------- | ---------- | ------------- | --------------------------------------------------------- |
| 1.0     | 26/09/2025 | Karol Navia   | Documento inicial                                         |
| 1.1     | 15/04/2025 | Ronald Peláez | Se agrega el nuevo tipo de bono y se actualiza el manual. |

</details>
