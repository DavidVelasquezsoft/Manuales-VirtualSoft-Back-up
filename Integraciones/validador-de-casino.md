# Validador de casino

<mark style="color:$info;">Ejecuta las pruebas de integración de los proveedores de juegos de casino del modelo APIGATEWAY y muestra el resultado de cada caso de prueba. Permite ajustar las variables de cada proveedor antes de ejecutar y verificar, después de cada cambio o despliegue, que las integraciones con la plataforma de Usuarios Online responden como se espera.</mark>

### 1. Información general

#### 1.1. ¿Qué es el validador de casino?

En las integraciones del modelo APIGATEWAY, el proveedor de juegos se comunica con la plataforma mediante una API: consulta el saldo del jugador, registra las apuestas, paga los premios y revierte transacciones. El validador reproduce esas llamadas con casos de prueba predefinidos y verifica que la plataforma responda como se espera.

Cada prueba sigue este flujo:

1. Inicia sesión en la plataforma con un usuario de pruebas.
2. Abre el juego del proveedor y obtiene el token de la sesión de juego.
3. Envía, como si fuera el proveedor, los requests de saldo, débito, crédito y rollback a la API de integraciones de casino.
4. Compara cada respuesta con el resultado esperado y muestra qué casos pasaron y cuáles fallaron.

#### 1.2. Objetivo

* Verificar de forma automática que los endpoints de casino de cada proveedor funcionan correctamente.
* Detectar errores después de cambios en el código o despliegues, antes de que lleguen a producción.
* Reducir las pruebas manuales y los errores humanos al validar una integración.

#### 1.3. Alcance

* Incluye los proveedores de casino del modelo APIGATEWAY configurados en la colección de pruebas.
* Valida el inicio de sesión y la apertura del juego, la autenticación, la consulta de saldo, los débitos, los créditos y los rollbacks, tanto en casos exitosos como en casos de error.
* Se ejecuta contra los ambientes definidos en las URL de las variables de cada proveedor.
* No modifica la colección de pruebas ni guarda los resultados en el servidor.
* No valida la interfaz gráfica de los juegos, solo la comunicación por API.

#### 1.4. Conceptos clave

<table><thead><tr><th width="154.16668701171875">Término</th><th>Significado</th></tr></thead><tbody><tr><td><strong>Colección</strong></td><td>Conjunto de pruebas del validador. Se organiza en una carpeta por proveedor.</td></tr><tr><td><strong>Caso de prueba</strong></td><td>Escenario que se valida <em>(Ejemplo: Debito - Exitoso)</em>. Contiene uno o varios requests.</td></tr><tr><td><strong>Request</strong></td><td>Llamada que el validador envía a un endpoint.</td></tr><tr><td><strong>Assertion</strong></td><td>Validación automática que compara la respuesta de un request con el resultado esperado.</td></tr><tr><td><strong>Wallet</strong></td><td>Saldo del jugador en la plataforma, que el proveedor consulta y modifica mediante la API.</td></tr><tr><td><strong>Débito</strong></td><td>Descuento del valor de la apuesta en el saldo del jugador.</td></tr><tr><td><strong>Crédito</strong></td><td>Acreditación del premio en el saldo del jugador.</td></tr><tr><td><strong>Rollback</strong></td><td>Reversión de una transacción ya registrada.</td></tr><tr><td><strong>Ronda</strong></td><td>Jugada del usuario en el juego. Agrupa el débito y el crédito correspondientes.</td></tr><tr><td><strong>Token</strong></td><td>Identificador de la sesión de juego que se envía en cada transacción.</td></tr><tr><td><strong>Mandante</strong></td><td>Partner en el que opera el proveedor. Se identifica con el <code>mandante_id</code>.</td></tr></tbody></table>

***

### 2. Acceso al Módulo

**Ruta de Acceso**: Pendiente

El ingreso requiere el usuario y la contraseña asignados por el equipo de Integraciones.

***

### 3. Visualización

<figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption><p>Figura #1: Captura de pantalla vista general del validador.</p></figcaption></figure>

***

### 4. Acciones disponibles

<table><thead><tr><th width="210">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="validador-de-casino.md#id-5.-seleccion-de-pruebas"><strong>Seleccionar pruebas</strong></a></td><td>Marca los proveedores que se van a probar.</td></tr><tr><td><a href="validador-de-casino.md#id-6.-variables"><strong>Ajustar variables</strong></a></td><td>Modifica, solo para la ejecución, los valores de cada proveedor seleccionado.</td></tr><tr><td><a href="validador-de-casino.md#id-7.-ejecucion-de-pruebas"><strong>Ejecutar pruebas</strong></a></td><td>Inicia las pruebas de los proveedores seleccionados, uno tras otro.</td></tr><tr><td><strong>Cancelar ejecución</strong></td><td>Detiene la ejecución en curso y conserva los resultados de los proveedores terminados. Se muestra solo mientras hay una ejecución activa.</td></tr><tr><td><a href="validador-de-casino.md#id-8.-resultado-de-ejecucion"><strong>Revisar resultados</strong></a></td><td>Muestra el resumen de la ejecución, los casos de prueba y el detalle de cada request.</td></tr><tr><td><strong>Copiar resumen</strong></td><td>Copia un resumen en texto de la ejecución, con la lista de fallas.</td></tr><tr><td><strong>Descargar reporte</strong></td><td>Descarga el reporte HTML de la ejecución. Con varios proveedores, descarga un archivo <em>(.zip)</em> con un reporte por proveedor.</td></tr><tr><td><a href="validador-de-casino.md#id-9.-ajustes"><strong>Ajustes</strong></a></td><td>Consulta las variables globales de plataforma.</td></tr><tr><td><strong>Salir</strong></td><td>Cierra la sesión.</td></tr></tbody></table>

***

### 5. Selección de pruebas

Los proveedores disponibles se listan en el panel lateral, en orden alfabético. Cada proveedor corresponde a una carpeta de la colección _(APIWATEWAY.Proveedor)_&#x79; para seleccionar los proveedores se permite interactuar con los siguientes elementos:

<table><thead><tr><th width="190">Elemento</th><th width="112.5">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Buscar proveedor...</code></strong></td><td>Campo de texto</td><td>Filtra la lista de proveedores por nombre.</td></tr><tr><td><strong><code>Lista de proveedores</code></strong></td><td>Casilla de verificación</td><td>Selecciona los proveedores que se van a ejecutar. Cada proveedor marcado se agrega como tarjeta en la pestaña <strong>Variables</strong>.</td></tr><tr><td><strong><code>Seleccionar todo</code></strong></td><td>Botón</td><td><p>Marca todos los proveedores visibles en la lista. </p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Con un texto en el buscador, el botón solo afecta a los proveedores de la lista filtrada.</p></div></td></tr></tbody></table>

***

### 6. Variables

Al seleccionar un proveedor, la pestaña **Variables** muestra su tarjeta con todas sus variables cargadas con los valores por defecto de la colección. Con esos valores, la prueba se ejecuta tal como está configurada en la colección.

{% hint style="warning" %}
**Notas:**&#x20;

* Todos los valores se pueden modificar antes de ejecutar, según lo que se necesite probar. Los cambios aplican solo a esa ejecución y no modifican la colección por defecto.
* Para aplicar el mismo usuario, partner, moneda y montos a varios proveedores, se usa la opción **Usar usuario y montos en las demás** de la tarjeta.
{% endhint %}

<figure><img src=".gitbook/assets/image (3).png" alt=""><figcaption><p>Figura #2: Captura de pantalla tarjeta de variables de un proveedor.</p></figcaption></figure>

#### 6.1. Campos de las variables

Las variables se agrupan en cuatro bloques. Los campos de cada tarjeta dependen de la configuración del proveedor en la colección.

{% tabs %}
{% tab title="Usuario" %}
<table><thead><tr><th width="135.83331298828125">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>username</code></strong></td><td>Campo de texto</td><td>Define el usuario de pruebas con el que el validador inicia sesión en la plataforma.</td></tr><tr><td><strong><code>password</code></strong></td><td>Campo de texto</td><td><p>Define la contraseña del usuario de pruebas. Es un campo sensible, por lo que el valor no se muestra.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si el campo queda vacío, se usa la contraseña de la colección. Si se escribe un valor, el campo indica <strong>Se usará el valor escrito</strong>.</p></div></td></tr><tr><td><strong><code>mandante_id</code></strong></td><td>Campo numérico</td><td>Indica el ID del partner en el que opera el proveedor <em>(Ejemplo: 0 para Doradobet u 8 para Ecuabet)</em>.</td></tr><tr><td><strong><code>currency</code></strong></td><td>Campo de texto</td><td>Define la moneda del usuario de pruebas <em>(Ejemplo: PEN o USD)</em>.</td></tr></tbody></table>
{% endtab %}

{% tab title="Montos" %}
<table><thead><tr><th width="170">Campo</th><th width="129.16668701171875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>debit_amount</code></strong></td><td>Campo numérico</td><td>Establece el valor que se descuenta en los casos de débito <em>(apuesta)</em>.</td></tr><tr><td><strong><code>credit_amount</code></strong></td><td>Campo numérico</td><td>Establece el valor que se acredita en los casos de crédito <em>(premio)</em>.</td></tr></tbody></table>
{% endtab %}

{% tab title="URLs" %}
<table><thead><tr><th width="179.1666259765625">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>url_session</code></strong></td><td>Campo de texto</td><td><p>Define la URL de la plataforma de Usuarios Online donde se inicia sesión con el usuario de pruebas.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Puede tener un valor global definido en <strong>Ajustes</strong>. En ese caso, el campo muestra la etiqueta <strong>global</strong>.</p></div></td></tr><tr><td><strong><code>url_wallet</code></strong></td><td>Campo de texto</td><td>Define la URL base de la API de integraciones de casino, a la que se envían las transacciones.</td></tr><tr><td><strong><code>url_balance</code></strong></td><td>Campo de texto</td><td>Define el endpoint de consulta de saldo.</td></tr><tr><td><strong><code>url_authenticate</code></strong></td><td>Campo de texto</td><td>Define el endpoint de autenticación. Solo aplica a algunos proveedores.</td></tr><tr><td><strong><code>url_debito</code></strong></td><td>Campo de texto</td><td>Define el endpoint de débito.</td></tr><tr><td><strong><code>url_credito</code></strong></td><td>Campo de texto</td><td>Define el endpoint de crédito.</td></tr><tr><td><strong><code>url_rollback</code></strong></td><td>Campo de texto</td><td>Define el endpoint de rollback.</td></tr><tr><td><strong><code>url_auth</code></strong>, <strong><code>url_credit_and_debit</code></strong>, <strong><code>url_debito2</code></strong>, <strong><code>url_credito2</code></strong></td><td>Campo de texto</td><td>Definen endpoints adicionales que usan algunos proveedores según su integración.</td></tr></tbody></table>
{% endtab %}

{% tab title="Proveedor / juego" %}
<table><thead><tr><th width="190">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>secret_key</code></strong></td><td>Campo de texto</td><td>Define la clave secreta de la integración con el proveedor. Es un campo sensible.</td></tr><tr><td><strong><code>game_id</code></strong></td><td>Campo numérico</td><td>Indica el ID del juego en la plataforma que se abre en las pruebas.</td></tr><tr><td><strong><code>abbreviated</code></strong></td><td>Campo de texto</td><td>Indica la abreviatura del proveedor en la plataforma <em>(Ejemplo: AIRDICE)</em>.</td></tr><tr><td><strong><code>external_id</code></strong></td><td>Campo de texto</td><td>Indica el identificador del juego en el sistema del proveedor <em>(Ejemplo: BookOfBloodLines)</em>.</td></tr><tr><td><strong><code>login_game</code></strong>, <strong><code>password_game</code></strong></td><td>Campo de texto</td><td>Definen el usuario y la contraseña que exige el proveedor para abrir el juego. Solo aplican a algunos proveedores.</td></tr><tr><td><strong><code>auth_token</code></strong>, <strong><code>country_code</code></strong>, <strong><code>operator_id</code></strong>, <strong><code>partner_id</code></strong>, <strong><code>userNamePartner</code></strong>, <strong><code>passwordPartner</code></strong></td><td>Campo de texto</td><td>Definen datos propios de la integración de algunos proveedores. </td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 7. Ejecución de pruebas

{% stepper %}
{% step %}
**Seleccionar los proveedores**

Marcar en el panel lateral los proveedores que se van a probar.
{% endstep %}

{% step %}
**Revisar las variables**

Verificar en la pestaña **Variables** los valores de cada proveedor y ajustar los necesarios.

{% hint style="warning" %}
**Notas:**

* La plataforma y los ambientes de prueba del proveedor deben estar disponibles. Si no lo están, el inicio de sesión falla y se omiten los demás casos del proveedor.
* El usuario de pruebas debe existir en el partner indicado en `mandante_id`, tener la moneda indicada en `currency` y contar con saldo suficiente para los débitos.
* Cada ejecución registra transacciones sobre el usuario de pruebas en el ambiente de pruebas y modifica su saldo.
* Los resultados se pierden al recargar o cerrar la página. Para conservarlos se descarga el reporte.
* Los valores modificados en la pestaña **Variables** se recuerdan en el navegador, por lo que se revisan antes de cada ejecución.
{% endhint %}
{% endstep %}

{% step %}
**Ejecutar las pruebas**

Hacer clic en **Ejecutar pruebas**. Antes de iniciar, el validador verifica que haya al menos un proveedor seleccionado y que los valores sean válidos. Si encuentra un error, muestra un mensaje y vuelve a la pestaña **Variables**.
{% endstep %}

{% step %}
**Seguir el progreso**

El panel lateral muestra el avance y la pestaña **Resultado de ejecución** se abre automáticamente. Los proveedores se ejecutan uno tras otro y sus resultados aparecen al terminar cada uno.
{% endstep %}

{% step %}
**Revisar el resultado**

Al finalizar, el panel lateral muestra el estado de la ejecución y la pestaña [**Resultado de ejecución**](validador-de-casino.md#id-8.-resultado-de-ejecucion) muestra el detalle.
{% endstep %}
{% endstepper %}

#### 7.1. Estados de la ejecución

<table><thead><tr><th width="210">Estado</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ejecución exitosa</code></strong></td><td>Indica que todas las assertions pasaron.</td></tr><tr><td><strong><code>Terminó con fallas</code></strong></td><td>Indica que la ejecución terminó y al menos una assertion falló.</td></tr><tr><td><strong><code>Error en la ejecución</code></strong></td><td><p>Indica que al menos un proveedor no se pudo ejecutar o no terminó. El resultado muestra el proveedor y el motivo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si un proveedor se interrumpe por el límite de tiempo del servidor, puede ejecutarse de nuevo por separado.</p></div></td></tr><tr><td><strong><code>Ejecución cancelada</code></strong></td><td>Indica que la ejecución se canceló. Se muestran los resultados parciales.</td></tr></tbody></table>

***

### 8. Resultado de ejecución

La pestaña **Resultado de ejecución** muestra el resultado de la última ejecución. Los resultados solo se ven en la pestaña del navegador donde se ejecutaron y se pierden al recargar o cerrar la página.

<figure><img src=".gitbook/assets/image (4).png" alt=""><figcaption><p>Figura #4: Captura de pantalla resumen del resultado de ejecución.</p></figcaption></figure>

#### 8.1. Resumen e indicadores de la ejecución

<table><thead><tr><th width="193.33331298828125">Elemento</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedores ✓ / ✗</code></strong></td><td>Lista los proveedores ejecutados: <strong>✓</strong> sin casos fallidos y <strong>✗</strong> con al menos un caso fallido. Los proveedores con fallas aparecen primero.</td></tr><tr><td><strong><code>Fecha, Duración y Ejecutó</code></strong></td><td>Indican cuándo inició la ejecución, cuánto duró y qué usuario la realizó.</td></tr><tr><td><strong><code>url_session</code></strong></td><td>Muestra la URL de la plataforma usada en la ejecución.</td></tr><tr><td><strong><code>Copiar resumen</code></strong></td><td>Copia un resumen en texto con los proveedores, los requests, las assertions y la lista de fallas.</td></tr><tr><td><strong><code>Descargar reporte HTML</code></strong></td><td>Descarga el reporte de la ejecución. Con varios proveedores, el botón cambia a <strong>Descargar reportes</strong> y descarga un archivo <em>(.zip)</em> con un reporte HTML por proveedor. Se habilita al terminar la ejecución.</td></tr><tr><td><strong><code>Avisos</code></strong></td><td>Informan las ejecuciones en curso, las cancelaciones, los proveedores que no terminaron y los errores internos.</td></tr><tr><td><strong><code>Requests</code></strong></td><td><p>Muestra los requests ejecutados frente al total de requests de los proveedores.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El conteo incluye los requests omitidos por un inicio de sesión fallido. Los requests que realmente se ejecutaron se identifican en el detalle de cada caso.</p></div></td></tr><tr><td><strong><code>Assertions</code></strong></td><td><p>Muestra el porcentaje de assertions aprobadas y la cantidad de aprobadas <strong>✓</strong> y fallidas <strong>✗</strong>.</p><p><strong>Fórmula:</strong><br><em>Assertions (%) = Aprobadas ÷ (Aprobadas + Fallidas) × 100</em></p></td></tr><tr><td><strong><code>Tiempo medio</code></strong></td><td><p>Muestra el tiempo promedio de respuesta por request, en milisegundos.</p><p><strong>Fórmula:</strong><br><em>Tiempo medio = Suma de los tiempos de respuesta ÷ Cantidad de requests ejecutados</em></p></td></tr></tbody></table>

#### 8.2. Resumen por proveedor

Se muestra cuando la ejecución incluye dos o más proveedores. Al hacer clic en una tarjeta, la lista de casos se filtra por ese proveedor; un segundo clic quita el filtro.

<table><thead><tr><th width="132.5">Elemento</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado</code></strong></td><td>Indica la cantidad de casos fallidos del proveedor <em>(Ejemplo: 1 caso falla)</em> o <strong>Todo OK</strong> si no hay fallas.</td></tr><tr><td><strong><code>Barra</code></strong></td><td>Muestra la proporción de assertions aprobadas y fallidas.</td></tr><tr><td><strong><code>casos ok</code></strong></td><td>Indica los casos sin fallas frente al total de casos del proveedor.</td></tr><tr><td><strong><code>assertions</code></strong></td><td>Indica las assertions aprobadas y, si las hay, las fallidas <strong>✗</strong>.</td></tr><tr><td><strong><code>requests</code></strong></td><td>Indica la cantidad de requests del proveedor y la suma de sus tiempos de respuesta.</td></tr></tbody></table>

#### 8.3. Filtros de casos

<table><thead><tr><th width="230">Filtro</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Todos los proveedores</code></strong></td><td>Lista desplegable</td><td>Muestra los casos de un proveedor o de todos. Se muestra solo con dos o más proveedores.</td></tr><tr><td><strong><code>Todos / Con fallas / Exitosos</code></strong></td><td>Selector</td><td>Filtra los casos según su estado. Cada opción indica la cantidad de casos.</td></tr><tr><td><strong><code>Categoría</code></strong></td><td>Selector</td><td>Restringe los casos a una categoría <em>(Ejemplo: Preparación, Balance, Debito, Credito o Rollback)</em>. Las categorías corresponden a las carpetas de la colección y varían según el proveedor.</td></tr><tr><td><strong><code>Buscar caso o request...</code></strong></td><td>Campo de texto</td><td>Localiza casos por el nombre del caso, del request o del proveedor.</td></tr></tbody></table>

#### 8.4. Casos de prueba

Los casos se muestran agrupados por cada proveedor y al hacer clic en un caso, se despliegan sus requests.

**Datos del caso**

<table><thead><tr><th width="117.5">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado</code></strong></td><td>Indica si el caso pasó <strong>✓</strong> o tiene al menos un request fallido <strong>✗</strong>.</td></tr><tr><td><strong><code>Categoría</code></strong></td><td>Muestra la carpeta a la que pertenece el caso. Los casos de la raíz de la carpeta se identifican como <strong>Caso de prueba</strong>.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Identifica el caso de prueba.</td></tr><tr><td><strong><code>Saldo</code></strong></td><td>Muestra el saldo inicial y el saldo final del caso, su diferencia <strong>Δ</strong> y si coincide con el esperado <em>(✓ esperado o ✗ no coincide)</em>. Se muestra solo en los casos que consultan el saldo.</td></tr><tr><td><strong><code>tests</code></strong></td><td>Indica las validaciones aprobadas frente al total del caso.</td></tr></tbody></table>

**Datos del request**

<table><thead><tr><th width="144.16668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>#</code></strong></td><td>Indica el orden de ejecución del request dentro del caso.</td></tr><tr><td><strong><code>Método</code></strong></td><td>Muestra el método HTTP del request <em>(GET o POST)</em>.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Identifica el request.</td></tr><tr><td><strong><code>Tipo de datos</code></strong></td><td>Indica el formato de los datos enviados <em>(Ejemplo: JSON, XML o Query params)</em>.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Muestra el código HTTP de la respuesta.</td></tr><tr><td><strong><code>Tiempo</code></strong></td><td>Muestra el tiempo de respuesta, en milisegundos.</td></tr><tr><td><strong><code>Resultado</code></strong></td><td>Indica las validaciones aprobadas <strong>✓</strong> o fallidas <strong>✗</strong>, <strong>sin respuesta</strong> u <strong>omitida</strong>.</td></tr></tbody></table>

#### 8.5. Casos de prueba de la colección

Los casos de cada proveedor provienen de su carpeta en la colección. La tabla describe los casos estándar; algunos proveedores tienen casos adicionales o no incluyen todos. Los términos se explican en [**Conceptos clave**](validador-de-casino.md#id-1.4.-conceptos-clave).

<table><thead><tr><th width="134.16668701171875">Categoría</th><th width="210">Caso</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Preparación</strong></td><td><strong><code>Abrir juego exitosamente</code></strong></td><td>Inicia sesión con el usuario de pruebas, abre el juego y obtiene el token que usan los demás casos. Si falla, se omite el resto de la carpeta.</td></tr><tr><td><strong>Pruebas por defecto</strong></td><td><strong><code>Pruebas por defecto</code></strong></td><td>Ejecuta las validaciones generales definidas en la carpeta del proveedor.</td></tr><tr><td><strong>Autenticación</strong></td><td><strong><code>Autenticación - Exitoso</code></strong></td><td>Valida la autenticación del usuario con datos correctos.</td></tr><tr><td><strong>Autenticación</strong></td><td><strong><code>Autenticación - Fallidos</code></strong></td><td>Valida el rechazo de la autenticación con datos incorrectos.</td></tr><tr><td><strong>Balance</strong></td><td><strong><code>Balance - Exitoso</code></strong></td><td>Valida la consulta de saldo con todos los parámetros.</td></tr><tr><td><strong>Balance</strong></td><td><strong><code>Balance - Fallido</code></strong></td><td>Valida el rechazo de la consulta de saldo con datos inválidos.</td></tr><tr><td><strong>Debito</strong></td><td><strong><code>Debito - Exitoso</code></strong></td><td>Valida el registro del débito y el descuento en el saldo.</td></tr><tr><td><strong>Debito</strong></td><td><strong><code>Debito + Debito - Cuando transacción ya existe</code></strong></td><td>Envía dos veces el mismo débito y valida que no se procese dos veces.</td></tr><tr><td><strong>Debito</strong></td><td><strong><code>Debito + Debito - usando el mismo código de ronda</code></strong></td><td>Valida dos débitos con el mismo código de ronda.</td></tr><tr><td><strong>Debito</strong></td><td><strong><code>Debito - Exitoso con token vacío</code></strong></td><td>Valida el débito cuando el token llega vacío.</td></tr><tr><td><strong>Debito</strong></td><td><strong><code>Debito - Erroneo con id usuario vacío</code></strong></td><td>Valida el rechazo del débito sin ID de usuario.</td></tr><tr><td><strong>Debito</strong></td><td><strong><code>Debito - Fallidos</code></strong></td><td>Valida el rechazo de débitos con datos inválidos.</td></tr><tr><td><strong>Credito</strong></td><td><strong><code>Debito + Credito - Exitoso</code></strong></td><td>Valida un débito seguido del crédito del premio.</td></tr><tr><td><strong>Credito</strong></td><td><strong><code>Credito - Fallidos - Token vencido y usuario vacío</code></strong></td><td>Valida el rechazo del crédito con token vencido o sin usuario.</td></tr><tr><td><strong>Credito</strong></td><td><strong><code>Credito Fallido - usuario vacío</code></strong></td><td>Valida el rechazo del crédito sin usuario.</td></tr><tr><td><strong>Credito</strong></td><td><strong><code>Debito + Credito - Ronda no existe</code></strong></td><td>Valida el rechazo de un crédito asociado a una ronda inexistente.</td></tr><tr><td><strong>Credito</strong></td><td><strong><code>Debito + Credito + Credito - Transacción ya procesada</code></strong></td><td>Valida que un crédito repetido no se pague dos veces.</td></tr><tr><td><strong>Credito</strong></td><td><strong><code>Debito + Credito + Debito + Credito - Transacción ya procesada</code></strong></td><td>Valida dos ciclos de débito y crédito, y el rechazo de las transacciones repetidas.</td></tr><tr><td><strong>Credito</strong></td><td><strong><code>Debito + Credito(ronda cerrada) + Credito(error ronda)</code></strong></td><td>Valida el rechazo de un crédito sobre una ronda ya cerrada.</td></tr><tr><td><strong>Rollback</strong></td><td><strong><code>Debito + Rollback - rollback solo al debito</code></strong></td><td>Valida la reversión de un débito.</td></tr><tr><td><strong>Rollback</strong></td><td><strong><code>Debito + Credito + Rollback - rollback solo al credito</code></strong></td><td>Valida la reversión de un crédito.</td></tr><tr><td><strong>Rollback</strong></td><td><strong><code>Debito + Rollback + Credito - credito debe ser erroneo</code></strong></td><td>Valida que no se acredite una ronda cuyo débito fue revertido.</td></tr><tr><td><strong>Rollback</strong></td><td><strong><code>Debito + Rollback + Rollback - ultimo rollback ya ejecutado</code></strong></td><td>Valida que un rollback repetido no se procese dos veces.</td></tr></tbody></table>

#### 8.6. Detalle del request

Al hacer clic en un request, se abre un panel lateral con su detalle.

<figure><img src=".gitbook/assets/image (156).png" alt=""><figcaption><p>Figura #5: Captura de pantalla detalle de un request.</p></figcaption></figure>

<table><thead><tr><th width="174.1666259765625">Sección</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Encabezado</code></strong></td><td>Muestra la ruta <em>(proveedor › caso)</em>, el nombre del request, su estado, el código HTTP, el tiempo de respuesta y las etiquetas <strong>Todas las validaciones pasaron</strong>, <strong>validación fallida</strong>, <strong>Error de script</strong>, <strong>Sin respuesta</strong> u <strong>Omitida</strong>.</td></tr><tr><td><strong><code>Copiar como cURL</code></strong></td><td>Copia el request como comando cURL para reproducirlo fuera del validador.</td></tr><tr><td><strong><code>URL</code></strong></td><td>Muestra el método y la URL del request. El enlace <strong>Copiar</strong> copia la URL.</td></tr><tr><td><strong><code>Datos enviados</code></strong></td><td>Muestra los parámetros de la URL y el body enviado, con su formato <em>(Ejemplo: JSON, XML o form-data)</em>. Los datos sensibles se muestran enmascarados.</td></tr><tr><td><strong><code>Respuesta del endpoint</code></strong></td><td><p>Muestra la respuesta del endpoint con formato.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si la respuesta es muy grande, se muestra recortada. El reporte HTML la contiene completa.</p></div></td></tr><tr><td><strong><code>Respuesta esperada</code></strong></td><td>Lista las condiciones del Post-response <em>(validaciones definidas en la colección)</em> con su resultado: <strong>✓</strong> aprobada, <strong>✗</strong> fallida con el motivo, <strong>–</strong> omitida y <strong>!</strong> error de script.</td></tr></tbody></table>

***

### 9. Ajustes

Muestra las variables globales de plataforma, que reemplazan su valor en el request «Iniciar sesion en plataforma apuestas» de todas las carpetas al ejecutar. Se accede desde el botón **Ajustes** del panel lateral; el botón **Volver** regresa a la pantalla principal.

{% hint style="danger" %}
**IMAGEN PENDIENTE: Figura #7**

**Captura:** página **Ajustes** con la tabla de variables globales.

**Pie de figura:** Figura #7: Captura de pantalla sección Ajustes.
{% endhint %}

<table><thead><tr><th width="230">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Variable</code></strong></td><td>Identifica la variable global <em>(Ejemplo: url_session)</em>.</td></tr><tr><td><strong><code>Valor vigente</code></strong></td><td>Muestra el valor que se aplica a todas las carpetas. Si no está definido, indica <strong>Sin definir: se usa el valor de la colección</strong>.</td></tr><tr><td><strong><code>Variable de entorno</code></strong></td><td>Indica la variable de entorno del servidor que define el valor <em>(Ejemplo: URL_SESSION)</em>.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Los valores de **Ajustes** son de solo lectura en el sitio, porque se definen como variables de entorno del servidor. Para cambiar un valor en una sola ejecución, se modifica en la pestaña **Variables**.
{% endhint %}

***

### 10. Validaciones y reglas del negocio:

* La ejecución requiere al menos un proveedor seleccionado.
* Los campos numéricos solo admiten números; con un valor inválido, la ejecución no inicia.
* Los proveedores se ejecutan uno tras otro, en orden alfabético.
* Al seleccionar un proveedor, sus variables se cargan con los valores de la colección.
* Los valores modificados aplican solo a la ejecución y no cambian la colección.
* Un valor modificado en la pestaña **Variables** tiene prioridad sobre el valor de **Ajustes**, solo para ese proveedor y esa ejecución.
* Si falla el inicio de sesión en la plataforma, se omite el resto de la carpeta del proveedor.
* Los resultados no se guardan en el servidor; se conservan solo descargando el reporte.
* Los valores no sensibles modificados se guardan en el navegador; los sensibles y los globales no.
* Los datos sensibles se enmascaran en los resultados y en los reportes.

***

### 11. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>23/11/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33116#icft=VSFT-33116">Documento inicial. Reemplaza la propuesta de validador de casino con Postman.</a></td></tr></tbody></table>

</details>
