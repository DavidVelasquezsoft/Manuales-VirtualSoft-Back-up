---
description: >-
  Permite realizar la configuración de la cuenta del punto de venta en cada una
  de las secciones disponibles.
---

# Configuración

### 1. Acceso al módulo

**Ruta de acceso**: Backoffice > Gestión punto de venta > punto de venta > buscar un punto de venta > 📁> 📁 > 🔎 > Configuración&#x20;

{% @guideflow/guideflow-embed requestedUrl="https://app.guideflow.com/player/vkmxd75s3p" %}

***

### 2. Secciones de configuración

La configuración de un punto de venta se organiza en diferentes secciones, cada una destinada a administrar aspectos específicos de su operación y seguridad.

{% hint style="warning" %}
**Nota:** \
Debido a la cantidad de secciones, **la última pestaña de este manual no se muestra de forma inmediata** en la barra de tabs.\
Para visualizarla, es necesario utilizar el botón de navegación adicional del manual.

La sección correspondiente se encuentra disponible en el siguiente enlace: [2.5. Configuración NTC personalizada](configuracion.md#id-2.5.-configuracion-ntc-personalizada)
{% endhint %}

{% tabs %}
{% tab title="2.1. Cambiar contraseña" %}
Permite actualizar la contraseña del usuario diligenciando los siguientes campos:

#### 2.1.1 Visualización

<figure><img src="../../../.gitbook/assets/image (434).png" alt=""><figcaption><p>Figura#1: Captura de pantalla de la sección cambiar contraseña.</p></figcaption></figure>

#### 2.1.2 Descripción de campos&#x20;

<table><thead><tr><th width="199.33343505859375">Campo</th><th width="129">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nueva Contraseña</code></strong></td><td>Contraseña</td><td>Ingrese la nueva clave de acceso.</td></tr><tr><td><strong><code>Confirmar Contraseña</code></strong></td><td>Contraseña</td><td>Vuelva a ingresar la contraseña para validarla.</td></tr><tr><td><strong><code>Limpiar</code></strong></td><td>Botón</td><td>Elimina los datos ingresados en los campos anteriores.</td></tr></tbody></table>

Para guardar los cambios haga clic en el botón **"Guardar"**.
{% endtab %}

{% tab title="2.2. Generar Token" %}
Permite visualizar, editar y crear tokens de seguridad para el punto de venta.

#### 2.2.1 Visualización

<figure><img src="../../../.gitbook/assets/image (641).png" alt=""><figcaption><p>Figura #2: Captura de pantalla sección generar Token</p></figcaption></figure>

#### 2.2.2 **Acciones disponibles**

<table><thead><tr><th width="171.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="configuracion.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="configuracion.md#crear-token-personalizado"><strong>Crear Token personalizado</strong></a></td><td>Permite crear un nuevo token personalizado para el punto de venta.</td></tr><tr><td><a href="configuracion.md#generar-token"><strong>Generar Token</strong> </a></td><td>Permite generar un token para un punto de venta.</td></tr><tr><td><a href="configuracion.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr></tbody></table>

#### 2.2.3 Filtros

<table><thead><tr><th width="115">Campo</th><th width="128.00006103515625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Permite seleccionar un rango de fechas para visualizar los tokens vigentes.</td></tr></tbody></table>

#### 2.2.4 Consultar

<table><thead><tr><th width="166">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>✏️</code></td><td>Permite editar un token previamente creado con los siguientes campos editables:</td></tr></tbody></table>

<details>

<summary>🔽 Campos de edición</summary>

<table><thead><tr><th width="158">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha y hora en la que se generó el token.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador único del usuario o punto de venta asociado al token.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Indica el tipo de Token.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado en el que se encuentra el Token actualmente.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Código único del Token.</td></tr></tbody></table>

</details>

***

<table data-header-hidden><thead><tr><th width="165.99993896484375"></th><th></th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha y hora en la que se registró el token.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador único del usuario o punto de venta asociado al token.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>indica el tipo de Token.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del Token (<em>por ejemplo: activo o inactivo</em>).</td></tr><tr><td><strong><code>Código</code></strong></td><td>Código único que identifica el token.</td></tr></tbody></table>

#### **2.2.5** Crear Token personalizado

Permite crear un nuevo token personalizado para el punto de venta, indicando los siguientes campos

<table><thead><tr><th width="149.00006103515625">Campo</th><th width="121">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Indica el tipo de token a crear</td></tr><tr><td><strong><code>Token</code></strong></td><td>Texto</td><td>Ingresa el token nuevo</td></tr></tbody></table>

#### **2.2.6** Generar Token

Al hacer clic en el botón **"Generar Token"** automaticamente se generará un nuevo token para este punto de venta.
{% endtab %}

{% tab title="2.3. Seguridad Cambios" %}
Sección con diversas configuraciones relacionadas con la seguridad del punto de venta y la plataforma.

#### 2.3.1 Visualización

<figure><img src="../../../.gitbook/assets/image (639).png" alt=""><figcaption><p>Figura #3: captura de pantalla sección seguridad Cambios</p></figcaption></figure>

#### 2.3.2 Descripción de campos&#x20;

{% hint style="warning" %}
**Nota:** Al modificar una opción, el sistema aplica el cambio de manera inmediata.
{% endhint %}

<table><thead><tr><th width="192.22222900390625">Campo</th><th width="498.83319091796875">Descripción</th></tr></thead><tbody><tr><td><strong><code>Desbloquear Usuario por Clave</code></strong></td><td>Habilita usuario en plataforma.</td></tr><tr><td><strong><code>Generar contraseña</code></strong></td><td>Envia la contraseña al correo del usuario.</td></tr><tr><td><strong><code>Estado de Usuario</code></strong></td><td>Indica si la cuenta está activa o inactiva.</td></tr><tr><td><strong><code>Estado de recarga</code></strong></td><td>Indica si el estado de recargas vaa aestar activo o no.</td></tr><tr><td><strong><code>Estado de Contingencia</code></strong></td><td>Indica si el usuario esta restringido por un eventos inesperado en el sistema.</td></tr><tr><td><strong><code>Contingencia Deportivas</code></strong></td><td>Restringe las operaciones en la vertical de apuestas deportivas.</td></tr><tr><td><strong><code>Contingencia Casino</code></strong></td><td>Restringe las operaciones en la vertical de casino.</td></tr><tr><td><strong><code>Contingencia Casino en Vivo</code></strong></td><td>Restringe las operaciones en la vertical de casino en vivo.</td></tr><tr><td><strong><code>Estado de Contingencia Virtuales</code></strong></td><td>Restringe al usuario el acceso a juegos virtuales ante situaciones excepcionales.</td></tr><tr><td><strong><code>Estado de Contingencia Poker</code></strong></td><td>Aplica limitaciones en la vertical de poker ante condiciones excepcionales.</td></tr><tr><td><strong><code>Contingencia Retiros</code></strong></td><td>Indica si el punto de venta tiene contingencia de retiros.</td></tr><tr><td><strong><code>Actualizar IP</code></strong></td><td>Permite <strong>actualizar la dirección IP del</strong> punto de venta, para eso debes ingresar en el campo <strong><code>IP</code></strong> la dirección y presionar el botón <strong><code>actualizar</code></strong>.</td></tr><tr><td><strong><code>Restricción IP</code></strong></td><td>Limita el acceso del usuario a direcciones IP específicas definidas en el campo.</td></tr><tr><td><strong><code>Token IP</code></strong></td><td>Permite habilitar el token local al usuario.</td></tr><tr><td><strong><code>Token Google</code></strong></td><td>Habilita el token de Google para asegurar el inicio de sesión.</td></tr><tr><td><strong><code>Cancelar cuenta</code></strong></td><td>Permite cancelar cancelar la cuenta del punto de venta, al darle al botón debes indicar una observación de porque se cancelara la cuenta.</td></tr></tbody></table>
{% endtab %}

{% tab title="2.4. QR Google" %}
Esta sección permite generar un **código QR** para habilitar la autenticación de dos factores mediante la aplicación **Google Authenticator**, reforzando la seguridad de acceso del usuario.

#### 2.4.1 Visualización

<figure><img src="../../../.gitbook/assets/image (643).png" alt=""><figcaption><p>Figura #4: Captura de pantalla seccion QR Google</p></figcaption></figure>

#### 2.4.2 Configuración

En esta sección, el usuario puede asociar su cuenta a una aplicación de autenticación de dos factores mediante una de las siguientes opciones:

* **Escanear el código QR** utilizando la aplicación Google Authenticator u otra aplicación compatible, para agregar la cuenta automáticamente.
* **Copiar el código de configuración** asociado al QR mediante el botón **Copiar**, y registrarlo manualmente en la aplicación de autenticación.

Ambos métodos permiten completar la configuración de la autenticación de dos factores de forma segura y efectiva.
{% endtab %}

{% tab title="2.5. Configuración NTC personalizada" %}
Permite definir una condición de tiempo de exclusión NTC de forma personalizada para cada punto de venta. En caso de no estar configurada, el sistema tomará por defecto la configuración general establecida en [#ajustes-generales](../../herramientas/partner-ajustes/configuracion-1.md#ajustes-generales "mention")

#### 2.5.1 Visualización

<figure><img src="../../../.gitbook/assets/image (644).png" alt=""><figcaption><p>Figura #5: Captura de pantalla sección Configuración NTC personalizada</p></figcaption></figure>

#### ¿Qué es NTC?

**NTC (No Tiene Comisión)** es una configuración que permite que un punto de venta **no aplique comisión en los depósitos** realizados por un usuario **dentro de un tiempo definido después de haber realizado un retiro** en el mismo punto de venta.

Durante este período, los depósitos que cumplan la condición **se procesan sin comisión**.

#### Tiempo de exclusión NTC

Define el tiempo, en minutos, que debe transcurrir desde un **retiro** para que los **depósitos posteriores del mismo usuario y punto de venta** sean considerados **sin comisión**.

Esta configuración es **personalizada por punto de venta** y, cuando existe, **tiene prioridad** sobre la configuración general del partner.\
Si el campo se deja vacío, el sistema aplicará automáticamente la **configuración global del partner**.

Para confirmar y aplicar el valor configurado, el usuario debe **presionar el botón Guardar y confirmar la acción**.

{% hint style="warning" %}
**Nota:**&#x20;

* Esta opción solo se muestra si el partner tiene NTC activo.
* Solo usuarios con el permiso correspondiente pueden modificar este valor.
* La configuración aplica únicamente al punto de venta seleccionado.
{% endhint %}
{% endtab %}
{% endtabs %}

***

### 3. Control de versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="98.25250244140625">Versión</th><th width="128.6363525390625">Fecha</th><th width="186.272705078125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>29/01/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>20/04/2026</td><td>Karol Navia</td><td>Mejoramiento de Manual</td></tr></tbody></table>

</details>
