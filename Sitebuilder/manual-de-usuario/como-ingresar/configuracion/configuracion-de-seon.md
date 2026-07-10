---
description: >-
  Permite configurar reglas SEON asociadas a eventos de la plataforma, que se
  evalúan según el nivel de riesgo del usuario y se ejecutan automáticamente
  aplicando restricciones.
---

# Configuración de SEON

### 1. Acceso al Módulo

**Ruta de acceso**: Site Builder > Partner > Configuración > Configuración [SEON](https://virtualsoft.gitbook.io/untitled/glosario/#seon)

***

### 2. **Configuraciones previas.**

Para modificar y acceder a la configuración de las reglas de [SEON](https://virtualsoft.gitbook.io/untitled/glosario/#seon) es necesario contar con la siguiente configuración:

<table><thead><tr><th width="207.55560302734375">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País para el cual se realizará la configuración.</td></tr></tbody></table>

***

### 3. Visualización General.

<figure><img src="../../../.gitbook/assets/image (20).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección configuración SEON</p></figcaption></figure>

***

### 4. Funcionamiento de las reglas SEON

Las reglas [SEON](https://virtualsoft.gitbook.io/untitled/glosario/#seon) permiten evaluar el riesgo de un usuario en tiempo real y aplicar restricciones automáticas según el score recibido.

**Flujo de funcionamiento:**

{% stepper %}
{% step %}
#### Creación de regla SEON

El operador selecciona un **evento SEON** (_por ejemplo, registro, login, depósito o retiro_) y configura una regla definiendo un **rango de score**, contingencias y límites.
{% endstep %}

{% step %}
#### Ejecución del evento

1. Un usuario realiza ese evento, el sistema envía la información a **SEON**.
2. SEON evalúa el comportamiento del usuario y retorna un **score de riesgo** en tiempo real.
{% endstep %}

{% step %}
#### Validación y ejecución de reglas

El sistema compara el score recibido con los rangos configurados para ese evento.

* ✅ Si el score **entra dentro de un rango válido**:
  * La regla se **dispara automáticamente** en el menor tiempo posible.
  * Se aplican las **contingencias y límites configurados**.
  * Las **restricciones quedan activas de forma indefinida** sobre el usuario.
* ❌ Si el score **no coincide con ningún rango configurado**:
  * No se ejecuta ninguna regla.
{% endstep %}

{% step %}
#### Consideraciones generales

Cada evento puede tener múltiples reglas, siempre que los rangos de score **no se repitan ni se superpongan**. Para un mismo evento, **solo una regla puede aplicarse por score**.

Las restricciones aplicadas solo pueden ser retiradas **manualmente por un operador autorizado**, garantizando control, trazabilidad y consistencia en la operación.
{% endstep %}
{% endstepper %}

***

### 5. Gestión por eventos

Permite **gestionar y configurar de forma independiente** cada evento de la plataforma, permitiendo **habilitar o deshabilitar** su ejecución de reglas, rangos de score y contingencias específicas.

Al **desactivar un evento**, se inactivan automáticamente **todas las reglas** asociadas, deteniendo la aplicación de controles de prevención de fraude y gestión de riesgo para dicho evento.\
Los eventos disponibles son:

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><img src="../../../.gitbook/assets/Icon Container.png" alt="" data-size="line"> <strong>Registro</strong></td><td>Controla y configura las reglas <a href="https://virtualsoft.gitbook.io/untitled/glosario/#seon">SEON</a> y contingencias que se <strong>activan automáticamente</strong> según el nivel riesgo calculado durante el registro de nuevos usuarios.</td></tr><tr><td><img src="../../../.gitbook/assets/Icon Container (1).png" alt="" data-size="line"> <strong>Login</strong></td><td>Gestiona las reglas <a href="https://virtualsoft.gitbook.io/untitled/glosario/#seon">SEON</a> y contingencias que se <strong>activan automáticamente</strong> según el nivel riesgo calculado durante el inicio de sesión de los usuarios.</td></tr><tr><td><img src="../../../.gitbook/assets/Icon Container (2).png" alt="" data-size="line"> <strong>Depósito</strong></td><td>Controla y configura las reglas <a href="https://virtualsoft.gitbook.io/untitled/glosario/#seon">SEON</a> y contingencias que se <strong>activan automáticamente</strong> según el nivel de riesgo calculado cuando los usuarios realizan depósitos en sus cuentas.</td></tr><tr><td><img src="../../../.gitbook/assets/Icon Container (3).png" alt="" data-size="line"> <strong>Retiro</strong></td><td>Controla y configura las reglas <a href="https://virtualsoft.gitbook.io/untitled/glosario/#seon">SEON</a> y contingencias que se <strong>activan automáticamente</strong> según el nivel de riesgo calculado cuando los usuarios solicitan el retiro de su saldo.</td></tr></tbody></table>

***

### 6. Configuración de reglas

Dentro de cada evento de la plataforma, el usuario puede realizar distintas **acciones de gestión** para administrar sus reglas [SEON](https://virtualsoft.gitbook.io/untitled/glosario/#seon).

#### 6.1. Visualización

<figure><img src="../../../.gitbook/assets/image (21).png" alt=""><figcaption><p>Figura #2: Captura de pantalla ejemplo de reglas en un evento</p></figcaption></figure>

#### 6.2.  Acciones de usuario

Permite **visualizar, crear, editar y gestionar** las reglas SEON asociadas al evento, definiendo su comportamiento según el score de riesgo recibido.\
Las acciones son:

<table><thead><tr><th width="131.99993896484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtrar reglas</strong></td><td>En la parte superior se encuentran <strong>opciones de filtrado por estado</strong>, que permiten visualizar las reglas <strong>activas</strong>, <strong>inactivas</strong> o <strong>todas</strong>.</td></tr><tr><td><strong>Eliminar regla</strong></td><td>Al hacer clic en el botón <img src="../../../.gitbook/assets/icon-button.png" alt="" data-size="line"> permite eliminar una regla con previa validación mediante <strong>token de autenticación</strong>. Al finalizar, se muestra un mensaje de confirmación.</td></tr><tr><td><strong>Cambiar estado de la regla</strong></td><td>Al hacer clic en el botón del estado de la regla se solicitará el <strong>token de autenticación</strong> para cambiar su estado (<em>Activo / Inactivo</em>).</td></tr><tr><td><strong>Información de reglas</strong></td><td>Permite visualizar por cada <strong>regla</strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#seon"><strong>SEON</strong></a> la información configurada.</td></tr></tbody></table>

{% columns %}
{% column width="16.666666666666664%" %}

{% endcolumn %}

{% column width="83.33333333333334%" %}
<details>

<summary>🔽 Detalle de información por regla</summary>

Cada regla cuenta con la siguiente información:

<table><thead><tr><th width="161">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado</code></strong></td><td>En la parte superior de la regla indica si esta se encuentra <strong>activa o inactiva</strong>.</td></tr><tr><td><strong><code>Score minimo</code></strong></td><td>Muestra el puntaje mínimo de riesgo a partir del cual la regla comienza a aplicarse.</td></tr><tr><td><strong><code>Score maximo</code></strong></td><td>Muestra el puntaje máximo de riesgo hasta el cual la regla se aplica, cerrando el rango de score configurado.</td></tr><tr><td><strong><code>Contingencias</code></strong></td><td>Indica si la regla tiene o no contingencias configuradas.</td></tr></tbody></table>

</details>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="133"></th><th></th></tr></thead><tbody><tr><td><strong>Agregar regla</strong></td><td>Al hacer clic en el botón <img src="../../../.gitbook/assets/Button (4).png" alt="" data-size="line">, se muestra un formulario que permite crear una nueva regla completando los siguientes campos:</td></tr></tbody></table>

{% columns %}
{% column width="16.666666666666664%" %}

{% endcolumn %}

{% column width="83.33333333333334%" %}
<details>

<summary>🔽 Formulario de creación</summary>

<table><thead><tr><th width="147">Campo</th><th width="110">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Score minimo</code></strong></td><td>Numérico</td><td>Indica el <strong>puntaje mínimo de riesgo</strong> a partir del cual la regla se ejecuta al evaluarse el score del usuario <strong>en tiempo real</strong>.</td></tr><tr><td><strong><code>Score maximo</code></strong></td><td>Numérico</td><td>Indica el <strong>puntaje máximo de riesgo</strong> hasta el cual la regla se ejecuta al evaluarse el score del usuario <strong>en tiempo real</strong>.</td></tr><tr><td><strong><code>Inactivar registro automaticamente</code></strong></td><td>Interruptor</td><td><p>Indica si al ejecutarse la regla, el registro del usuario se <strong>inactiva automáticamente</strong>, impidiendo el ingreso al usuario.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo solo aplica únicamente para el evento de registro.</p></div></td></tr><tr><td><strong><code>Contingencias</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar múltiples contingencias y límites que se aplicarán automáticamente al usuario cuando la regla se ejecute. <a href="configuracion-de-seon.md#contingencias-disponibles">Contingencias disponibles</a></td></tr><tr><td><strong><code>Comentario</code></strong></td><td>Texto</td><td>Indica el comentario que se guardará en el perfil del usuario cuando la regla se aplique.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Los **rangos de score** configurados por cada regla **no pueden repetirse ni superponerse**. Cada regla debe tener un **rango de score distinto**, sin coincidir ni cruzarse con los rangos de otras reglas del **mismo evento**.
{% endhint %}

* Al finalizar, se solicitará el ingreso del **token de autenticación** para validar la creación de la regla.

</details>

<details>

<summary>🔽 Contingencias disponibles</summary>

Cada regla permite activar múltiples contingencias, las cuales se ejecutarán automáticamente cuando la regla sea aplicada.

<table><thead><tr><th width="193.6666259765625">Contingencia</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Abusador de Bonos</code></strong></td><td>Marca al usuario con uso indebido de promociones. Al estar activo, bloquea beneficios asociados a bonos, jackpots, torneos, sorteos y ruletas.</td></tr><tr><td><strong><code>Contingencia Depósitos</code></strong></td><td>Bloquea la realización de depósitos del usuario en los canales definidos por la plataforma.</td></tr><tr><td><strong><code>Contingencia Depositos Retail</code></strong></td><td>Impide que el usuario realice depósitos en puntos físicos, redes aliadas, corresponsales o agentes autorizados. No afecta pasarelas electrónicas.</td></tr><tr><td><strong><code>Contingencia Retiros Retail</code></strong></td><td>Impide que el usuario retire dinero en puntos físicos o redes aliadas. Si intenta hacerlo, el sistema mostrará un mensaje de restricción.</td></tr><tr><td><strong><code>Contingencia Retiros</code></strong></td><td>Bloquea cualquier solicitud de retiro de fondos desde la cuenta del usuario.</td></tr><tr><td><strong><code>Contingencia Apuestas deportivas</code></strong></td><td>Restringe la posibilidad de realizar apuestas sobre eventos deportivos.</td></tr><tr><td><strong><code>Contingencia Apuestas casino</code></strong></td><td>Bloquea el acceso del usuario a los juegos de casino.</td></tr><tr><td><strong><code>Contingencia Apuestas casino en vivo</code></strong></td><td>Impide la participación en mesas o juegos con crupier en vivo.</td></tr><tr><td><strong><code>Contingencia Póker</code></strong></td><td>Restringe el acceso a las mesas y funcionalidades de póker.</td></tr></tbody></table>

</details>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="137.00006103515625"></th><th></th></tr></thead><tbody><tr><td><strong>Editar regla</strong></td><td><p>Al hacer clic en el botón <img src="../../../.gitbook/assets/icon-button (2).png" alt="" data-size="line"> dentro de una regla, se abrirá el formulario de edición, permitiendo <strong>modificar todos</strong> sus campos.</p><p><br><a href="configuracion-de-seon.md#formulario-de-creacion" class="button secondary">Ver campos del formulario</a></p><ul><li>Al finalizar de hacer un cambio, se solicitará el ingreso del <strong>token de autenticación</strong> para validar la actualización de la regla.</li></ul></td></tr><tr><td><strong>Visualización de regla</strong></td><td>Al hacer clic en el botón <img src="../../../.gitbook/assets/icon-button (1).png" alt="" data-size="line"> dentro de una regla, se abrirá un modal con la información de la regla permitiendo únicamente su visualización.<br><a href="configuracion-de-seon.md#formulario-de-creacion" class="button secondary">Ver información de campos</a></td></tr></tbody></table>

***

### 7.  Validaciones y Reglas de Negocio

* Estas configuraciones solo aplican para el partner y el país previamente seleccionado.
* Solo usuarios con permisos podrán crear, editar y visualizar este modulo.
* ⚠️ Las restricciones aplicadas a un usuario permanecen **de forma indefinida**, hasta que un operador las retire manualmente desde la sección [Seguridad y cambios](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/configuracion-seccion-jugadores#id-2.2.-seguridad-y-cambios) del backoffice.

***

### 8. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="106">Versión</th><th width="147">Fecha</th><th width="156">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/01/2026</td><td>David Ortiz</td><td>Documento inicial</td></tr></tbody></table>

</details>
