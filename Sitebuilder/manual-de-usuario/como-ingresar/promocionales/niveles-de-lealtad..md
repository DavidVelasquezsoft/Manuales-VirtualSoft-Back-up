---
description: >-
  Los niveles lealtad incentivan a los usuarios a realizar más apuestas,
  dándoles premios según su nivel de lealtad. Esta sección permite la creación y
  configuración dichos niveles.
---

# Niveles de lealtad.

### **1. Acceso al Módulo**

**Ruta:** Site Builder > Seleccionar Partner > Promocionales > Niveles de lealtad

***

### **2. Configuraciones previas**

Antes de ingresar a este módulo, asegúrate de contar con las siguientes configuraciones:

<table><thead><tr><th width="147">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Partner</strong></td><td>Selecciona el partner a configurar.</td></tr><tr><td><strong>País</strong></td><td>País para el cual se realizará la configuración.</td></tr></tbody></table>

{% hint style="warning" %}
**Notas:**&#x20;

* La edición es sensible a **Partner** y **País**. Estas variables determinan los niveles disponibles y cómo se visualizarán en la plataforma de usuarios online.
* Estas configuraciones van apareciendo a medida que se sigue la ruta para llegar a este módulo.
{% endhint %}

***

### **3. Alcance del manual**

Este manual describe el uso de la funcionalidad **Niveles de Lealtad**, incluyendo la configuración de los niveles, las condiciones para el ascenso de los jugadores y las reglas asociadas a los puntos calificables y depósitos requeridos.

**Incluye:**

* Configuración de los niveles de lealtad.
* Administración de los puntos calificables y depósitos requeridos por nivel.
* Configuración de la vigencia de los puntos y depósitos.
* Definición de las reglas de ascenso entre niveles.
* Configuración de la información asociada a cada nivel.

***

### **4. Contenido del Módulo**&#x20;

Esta sección dispone de dos vistas de configuración para la administración de los niveles de lealtad, las cuales permiten gestionar de manera independiente la información y visualización de cada nivel. Estas vistas son:

{% hint style="warning" %}
**Nota**: Los cambios pueden tardar aproximadamente 30 minutos en reflejarse.
{% endhint %}

{% tabs %}
{% tab title="Niveles de lealtad" %}
#### **Visualización del módulo**

<figure><img src="../../../.gitbook/assets/image (431).png" alt=""><figcaption><p>Figura #1: Visualización del módulo Niveles de lealtad.</p></figcaption></figure>

***

#### **Acciones disponibles**

<table><thead><tr><th width="130.39996337890625" align="center">Icono</th><th width="108">Tipo de control</th><th width="120.4000244140625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/promocionales/niveles-de-lealtad.#formularios-de-creacion-o-edicion"><img src="../../../.gitbook/assets/image (62).png" alt="" data-size="line"></a> </td><td>Botón</td><td>Crear nivel</td><td>Abre el formulario para añadir un nuevo nivel consecutivo.</td></tr><tr><td align="center">🗑️</td><td>Botón</td><td>Eliminar nivel</td><td>Elimina el último nivel configurado. Solo se pueden eliminar en orden descendente.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (8).png" alt="" data-size="original"></td><td>Botón</td><td>Guardar</td><td>Aplica las modificaciones y las refleja en la plataforma online.</td></tr><tr><td align="center">👁️</td><td>Botón</td><td>Previsualizar</td><td>Permite visualizar cómo se mostrará un nivel en la plataforma de usuarios online. Para ello, primero se debe seleccionar una card.</td></tr><tr><td align="center"><a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/promocionales/niveles-de-lealtad.#formularios-de-creacion-o-edicion"><img src="../../../.gitbook/assets/image (6).png" alt="" data-size="original"></a></td><td>Botón</td><td>Editar</td><td>Abre un <strong>pop-up</strong> en el que se puede editar la descripción del nivel.</td></tr></tbody></table>

***

#### **Formularios de creación o edición**

{% hint style="warning" %}
**Nota**:&#x20;

* Todos los campos marcados con \* son obligatorios.
* Si en el primer nivel los campos **`Puntos requeridos`** y **`Depósitos requeridos`** no están configurados _(están vacíos)_, en los niveles siguientes no será posible establecer valores para estos campos.
{% endhint %}

<table><thead><tr><th width="136.11114501953125">Campo</th><th width="558.25">Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del nivel</code></strong></td><td>Título o etiqueta con la que el jugador identificará el nivel en la plataforma <em>(ejemplo: Bronce, Plata, Diamante).</em></td></tr><tr><td><strong><code>Puntos requeridos</code></strong></td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#umbral">Umbral</a> mínimo de puntos necesarios para acceder al nivel.</td></tr><tr><td><strong><code>Depósitos requeridos</code></strong> </td><td>Número de depósitos requeridos que debe realizar el usuario para avanzar al siguiente nivel.</td></tr><tr><td><strong><code>Tiempo de permanencia del nivel</code></strong></td><td><p>Indica la cantidad de meses que el jugador debe permanecer en su nivel actual antes de que el sistema vuelva a evaluar su desempeño.<br>Durante este período, el jugador puede seguir acumulando puntos calificables:</p><ul><li>Si alcanza los puntos requeridos para el siguiente nivel, el sistema lo asciende automáticamente.</li><li>Si no logra mantener los puntos mínimos del nivel actual, descenderá al nivel correspondiente a los puntos que tenga.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong></p><ul><li>Si no se establece un valor en este campo, el sistema tomará por defecto <strong>1</strong>  que equivale a <em>(1 mes)</em>.</li><li>Este campo solo permite valores numéricos entre <strong>1 y 12, e</strong>n caso de ingresar un valor fuera de este rango (<em>por ejemplo, 13</em>), el sistema lo ajustará automáticamente al valor máximo permitido <em>(<strong>12</strong></em>).</li><li>Adicionalmente, el valor configurado en este campo debe ser <strong>mayor</strong> al definido en el campo de <a href="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#puntos-equivalentes-por-nivel"><strong>frecuencia de expiración de puntos calificables</strong> </a>de partner ajustes.</li></ul></div></td></tr><tr><td><strong><code>Imagen del nivel</code></strong></td><td>URL de la imagen o insignia que representará el nivel en la plataforma.</td></tr><tr><td><strong><code>Editar recompensa</code></strong></td><td><p>Al hacer clic en este botón, se despliega un pop-up donde se muestra la información configurada en la card seleccionada. Luego, el pop-up se voltea para presentar un cuadro de texto en el que se debe ingresar la descripción del nivel de lealtad.</p><p>Para finalizar, es necesario guardar la información haciendo clic en el botón <strong>Guardar</strong> dentro del mismo pop-up.</p></td></tr></tbody></table>

***

#### **Lógica funcional del sistema**

El sistema de **Niveles de lealtad** opera con dos tipos de puntos:

<table><thead><tr><th width="176.39996337890625">Tipo de puntos</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#puntos-calificables"><strong>Puntos calificables</strong></a></td><td>Se obtienen de forma automática cada vez que el jugador realiza una apuesta válida. Sirven para definir su nivel dentro del programa de lealtad y se reinician al concluir el tiempo de permanencia.</td></tr><tr><td><strong>Puntos canjeables</strong></td><td>Se acumulan automáticamente cada vez que el jugador realiza una apuesta válida. Estos puntos pueden utilizarse para obtener recompensas en la tienda de premios, como bonos, giros gratis u otros beneficios disponibles. A diferencia de los puntos calificables, los puntos canjeables no afectan el nivel del jugador dentro del programa de lealtad, pero sí permiten disfrutar de beneficios exclusivos al intercambiarlos.</td></tr></tbody></table>

***

#### **Reglas de funcionamiento:**

1.  Cada apuesta válida genera **puntos calificables** y **puntos canjeables**, de acuerdo con la siguiente fórmula: _**(Valor de la apuesta × Puntos base ÷ Valor determinado por tipo de apuesta)**_

    Los valores utilizados en el cálculo dependen de los parámetros definidos en:\
    [Tipos de movimientos _(Nota: Por cada monto en XXX va a obtener Z puntos base)_](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1#tipos-de-movimientos-nota-por-cada-monto-en-xxx-va-a-obtener-z-puntos-base).
2. Una vez que el jugador alcanza la cantidad de puntos calificables requeridos, el sistema lo asciende automáticamente **de forma inmediata** al siguiente nivel correspondiente dentro del programa de lealtad.
3. Al llegar al fin del **tiempo de permanencia configurado**, el sistema evalúa si el jugador mantiene, asciende o desciende según los puntos calificables obtenidos.
4. Si al finalizar el periodo configurado el jugador no alcanza el [umbral ](https://virtualsoft.gitbook.io/untitled/glosario/#umbral)del nivel actual, descenderá automáticamente al nivel que le corresponda según sus puntos acumulados.&#x20;
5. Cuando un usuario sube o baja de nivel, o se ajusta su tiempo de permanencia, el sistema reinicia el conteo del nuevo período asociado a su nivel actual.
6. Los **puntos calificables no se acumulan entre períodos**: cada ciclo inicia desde cero.

{% hint style="info" %}
**Ejemplo:**\
Un jugador comienza en el **nivel 1**, donde necesita **1.000 puntos calificables** para avanzar.\
Para alcanzar el **nivel 2**, debe reunir **3.000 puntos calificables**. Cuando cumple este requisito, **asciende automáticamente** y obtiene un **tiempo de permanencia de 1 mes** en dicho nivel.

Durante ese período, el sistema sigue registrando su actividad:

* Si al finalizar el mes el jugador acumula nuevamente **3.000 puntos calificables**, **permanece en el nivel 2**.
* Si solo obtiene **1.000 puntos calificables**, **desciende al nivel 1**.
* Si continúa acumulando puntos y alcanza, por ejemplo, **5.000 puntos calificables**, **asciende automáticamente al nivel 3**.

De esta forma, el sistema evalúa constantemente el desempeño del jugador para **mantenerlo, subirlo o bajarlo de nivel** según los puntos obtenidos.
{% endhint %}
{% endtab %}

{% tab title="Términos y condiciones" %}
#### **Visualización del módulo**

<figure><img src="../../../.gitbook/assets/image (419).png" alt=""><figcaption><p>Figura #2: Captura de pantalla terminos y condiciones.</p></figcaption></figure>

***

#### **Acciones disponibles**

Desde esta vista podrás realizar las siguientes acciones:

<table><thead><tr><th width="183">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="niveles-de-lealtad..md#gestionar-y-agregar-terminos-y-condiciones"><strong>Gestionar términos existentes.</strong></a></td><td>Visualiza, modifica y reordena los términos y condiciones registrados, además de sus respectivas subsecciones.</td></tr><tr><td><a href="niveles-de-lealtad..md#gestionar-y-agregar-terminos-y-condiciones"><strong>Agregar nuevo término</strong></a></td><td>Permite crear un nuevo término utilizando el botón <strong>“Agregar”</strong> ubicado en la parte superior derecha; el registro se añadirá al <strong>final</strong> de la lista de términos existente.</td></tr><tr><td>B<strong>uscar</strong></td><td>En la parte superior se encuentra un campo de texto que permite buscar un término en especifico.</td></tr><tr><td><img src="../../../.gitbook/assets/image (429).png" alt="" data-size="line"></td><td>Aplica las modificaciones y las refleja en la plataforma de usuarios online.</td></tr></tbody></table>

***

#### Gestionar y agregar términos y condiciones.

Para cada término se encuentran disponibles las siguientes acciones:

<table><thead><tr><th width="103.75" align="center">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><img src="../../../.gitbook/assets/image (422).png" alt="" data-size="line"></td><td>Permite reorganizar los términos y condiciones mediante la funcionalidad de arrastrar y soltar, ubicándolos en la posición deseada dentro de la lista.</td></tr><tr><td align="center"><strong><code>Título</code></strong></td><td>Define el nombre principal que identificará el término.</td></tr><tr><td align="center"><a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/promocionales/niveles-de-lealtad.#agregar-submenu"><img src="../../../.gitbook/assets/image (424).png" alt="" data-size="line"></a></td><td>Permite crear uno o varios submenús asociados al término principal para organizar la información en diferentes secciones.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (425).png" alt="" data-size="line"></td><td>Elimina el término seleccionado junto con todos los submenús y contenidos asociados.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (426).png" alt="" data-size="line"></td><td>Expande el término para visualizar y gestionar los submenús configurados.</td></tr></tbody></table>

***

#### Agregar submenú

Para crear un submenú, utiliza el botón **Agregar** ubicado en el término correspondiente. Al seleccionarlo, el sistema habilitará la configuración de una nueva sección dentro del término.

Los submenús disponen de las siguientes opciones:

<table><thead><tr><th width="99.5" align="center">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><strong><code>Título</code></strong></td><td>Define el nombre o encabezado que identificará la sección dentro del término.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (428).png" alt="" data-size="line"></td><td>Permite abrir el editor de texto enriquecido para ingresar y dar formato al contenido que se mostrará en el submenú.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (427).png" alt="" data-size="line"></td><td>Elimina el submenú seleccionado junto con el contenido configurado.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### **5. Validaciones y reglas adicionales**

* Máximo **10 niveles** disponibles (1–10).
* No se pueden crear niveles con puntos inferiores al nivel anterior.
* Solo se puede eliminar el último nivel creado.
* El **tiempo de permanencia** debe ser un valor entero entre **1 y 12 meses**.
* Los niveles correctamente configurados serán visibles en la plataforma de usuarios online.
* Los campos **Depósito requerido** y **Puntos requeridos** no serán obligatorios cuando su valor sea **0** o se encuentren vacíos.
* Si se configura una condición por **Depósito requerido** o **Puntos requeridos**, el campo correspondiente deberá diligenciarse.
* Los valores configurados en cada nivel deberán ser mayores a los del nivel anterior.
* El período de vigencia de los depósitos deberá coincidir con el período configurado para los puntos calificables.
* El progreso por depósitos se actualizará automáticamente de acuerdo con los depósitos válidos del período vigente.
* Los depósitos anulados descontarán el progreso generado cuando corresponda al período activo.

***

### **6. Control de versiones**

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="99">Versión</th><th width="123">Fecha</th><th width="132">Autor</th><th>Cambios realizados</th></tr></thead><tbody><tr><td>1.0</td><td>15-08-2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>17-09-2025</td><td>Ronald Peláez</td><td>Ajustes visuales y campos.</td></tr><tr><td>1.2</td><td>01-11-2025</td><td>Karol Navia</td><td>Nuevo campo “Tiempo de permanencia”.</td></tr><tr><td>1.3</td><td>10-11-2025</td><td>Karol Navia</td><td>Inclusión de la lógica de “Puntos calificables” y reglas de ascenso automático.</td></tr><tr><td>1.4</td><td>13-04-2025</td><td>Karol Navia</td><td>Mejoramiento del proceso de puntos calificables</td></tr><tr><td>1.5</td><td>25-06-2026</td><td>Karol Navia</td><td>Agregar la sección de términos y condiciones.</td></tr><tr><td>1.6</td><td>09-06-2026</td><td>Karol Navia</td><td>Agregar campo <strong><code>Depósitos requeridos</code></strong> </td></tr></tbody></table>

</details>
