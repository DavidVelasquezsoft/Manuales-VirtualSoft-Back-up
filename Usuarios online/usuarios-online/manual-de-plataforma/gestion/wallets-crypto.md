# Wallets Crypto

<mark style="color:$info;">Registra y gestiona las billeteras de criptomonedas a las que el usuario puede recibir sus retiros. Las wallets se registran de forma independiente a las cuentas bancarias, ya que requieren información distinta. Una vez registrada la wallet, el usuario puede utilizarla para solicitar retiros mediante la opción Criptomonedas.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Menú > Servicios > Gestión > Wallets Crypto

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (163) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Wallets Crypto.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="126.42425537109375">Ícono</th><th>Descripción</th></tr></thead><tbody><tr><td><img src="../../../.gitbook/assets/image (213).png" alt="" data-size="original"></td><td>Registra una nueva <a href="https://virtualsoft.gitbook.io/plantillas/glosario#wallet-cripto">wallet</a> cripto con la información diligenciada en el formulario.</td></tr><tr><td><img src="../../../.gitbook/assets/image (214).png" alt="" data-size="original"></td><td>Elimina de forma permanente la <a href="https://virtualsoft.gitbook.io/plantillas/glosario#wallet-cripto">wallet</a> cripto registrada. Disponible únicamente para wallets en estado <em>Activa</em>.</td></tr></tbody></table>

***

### 4. Registro de [wallets](https://virtualsoft.gitbook.io/plantillas/glosario#wallet-cripto)

Permite registrar una nueva billetera mediante el siguiente formulario:

{% hint style="warning" %}
**Notas:**&#x20;

* Únicamente se visualizan las criptomonedas y redes blockchain que se encuentren activas y configuradas para el partner y el país. Si se selecciona una combinación no habilitada, el sistema muestra el mensaje: _"No es posible realizar transacciones mediante esta red"_.
* Las criptomonedas y redes blockchain disponibles para el usuario se definen desde el BackOffice: se registran en los módulos de Criptomonedas y Redes blockchain, se vinculan mediante la Asociación Cripto + Red y se habilitan para la plataforma siguiendo el [flujo completo para habilitar retiros en criptomonedas](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/productos/asociacion-cripto-+-redes#id-7.-flujo-habilitar-retiros-en-criptomonedas).
{% endhint %}

<table><thead><tr><th width="163.3333740234375">Campo</th><th width="140">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Criptomonedas</code></strong></td><td>Lista desplegable</td><td>Define la <a href="https://virtualsoft.gitbook.io/untitled/glosario/#criptomoneda">criptomoneda</a> con la que se recibirá el retiro. Se listan únicamente las criptomonedas activas y habilitadas para retiro.</td></tr><tr><td><strong><code>Red Blockchain</code></strong></td><td>Lista desplegable</td><td><p>Define la <a href="https://virtualsoft.gitbook.io/untitled/glosario/#red-blockchain">red blockchain</a> sobre la cual opera la criptomoneda <em>(por ejemplo: TRC20, ERC20, BEP20)</em>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Se muestran únicamente las redes asociadas a la criptomoneda seleccionada previamente. La red debe coincidir con la red de destino de la billetera.</p></div></td></tr><tr><td><strong><code>Dirección Wallet</code></strong></td><td>Campo de texto</td><td>Corresponde a la <a href="https://virtualsoft.gitbook.io/untitled/glosario/#direccion-wallet">dirección wallet</a> a la que se enviarán los fondos. Debe ser válida y compatible con la red seleccionada.</td></tr><tr><td><strong><code>Confirmar Dirección Wallet</code></strong></td><td>Campo de texto</td><td>Requiere reingresar la dirección para verificar que sea correcta. Ambas direcciones deben coincidir para habilitar el registro.</td></tr></tbody></table>

***

### 5. Wallets registradas

Las billeteras registradas se muestran en una tabla con la siguiente información:

<table><thead><tr><th width="180">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Criptomoneda</code></strong></td><td>Criptomoneda asociada a la wallet registrada.</td></tr><tr><td><strong><code>Red Blockchain</code></strong></td><td>Red blockchain seleccionada al momento del registro de la wallet.</td></tr><tr><td><strong><code>Dirección Wallet</code></strong></td><td>Dirección cripto registrada, visualizada en formato abreviado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td><p>Estado actual de la wallet:</p><ul><li><strong>Activa:</strong> habilitada para ser utilizada en solicitudes de retiro.</li><li><strong>Inactiva:</strong> deshabilitada; no puede seleccionarse para retiros.</li></ul></td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Las wallets registradas y activas quedan disponibles para seleccionarse al realizar un retiro mediante la opción **Criptomonedas**. Consultar el manual de Retirar.
{% endhint %}

***

### 6. Uso de la wallet para retirar

Una vez registrada y activa, la wallet queda disponible como destino de retiro. Para utilizarla, el usuario ingresa a la [sección **Retirar**](retirar.md), selecciona la opción **Criptomonedas**, elige una de sus wallets registradas e indica el monto a retirar en moneda local.

{% hint style="warning" %}
**Nota:** El retiro se procesa hacia la criptomoneda, red y dirección registradas en la wallet seleccionada, por lo que es responsabilidad del usuario verificar que la dirección sea correcta y compatible con la red antes de registrarla.
{% endhint %}

***

### 7. Validaciones y reglas del negocio:

* Durante el registro de una wallet, el sistema puede mostrar los siguientes mensajes:

<table><thead><tr><th width="280">Validación</th><th>Mensaje</th></tr></thead><tbody><tr><td>Dirección vacía o no coincidente</td><td><em>"Las direcciones ingresadas no coinciden."</em></td></tr><tr><td>Combinación duplicada en la misma cuenta</td><td><em>"Ya has registrado esta dirección para esta cripto y red."</em></td></tr><tr><td>Dirección ya registrada por otro jugador</td><td><em>"Esta dirección ya fue registrada por otro usuario."</em></td></tr><tr><td>Límite superado por combinación cripto/red</td><td><em>"Solo puedes registrar hasta (número configurado) direcciones para esta criptomoneda y red."</em></td></tr><tr><td>Red no habilitada para transacciones</td><td><em>"No es posible realizar transacciones mediante esta red."</em></td></tr></tbody></table>

* Solo pueden registrarse wallets de criptomonedas configuradas y habilitadas previamente desde el BackOffice.
* Es obligatorio seleccionar la red blockchain asociada a la criptomoneda.
* Ambas direcciones ingresadas deben coincidir para completar el registro.
* No se permite registrar múltiples wallets con la misma dirección y red.
* El número máximo de wallets por combinación de criptomoneda y red es configurable.
* La acción **Eliminar** está disponible únicamente para wallets en estado _Activa_.
* Una wallet solo puede eliminarse si no está asociada a retiros activos o pendientes.
* La sección está disponible para usuarios con sesión iniciada y cuenta activa.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="102">Versión</th><th width="127">Fecha</th><th width="169">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/07/2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>06/08/2025</td><td>Ronald Peláez</td><td>Ajuste en función de las condiciones de criptomoneda.</td></tr><tr><td>1.2</td><td>13/08/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-21110#icft=VSFT-21110">Actualización del manual e incorporación de notas.</a></td></tr></tbody></table>

</details>
