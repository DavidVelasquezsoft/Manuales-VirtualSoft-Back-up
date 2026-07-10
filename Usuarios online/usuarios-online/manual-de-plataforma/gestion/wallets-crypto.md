---
description: >-
  Este módulo permite gestionar tus wallets cripto asociadas a una criptomoneda
  y red específica.
---

# Wallets Crypto

### 1. Acceso al Módulo

**Ruta de Acceso**: Menú > Servicios > Gestión > Wallets Crypto.

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (163) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Wallets Crypto.</p></figcaption></figure>

#### 🧑‍💻 2. Acciones del Usuario

**2.1. Formulario para crear Wallets Crypto**

{% hint style="warning" %}
**Nota**: Solo se visualizarán crypto monedas y redes blockchain cuando estén activas y configuradas desde el partner, en caso de que se visualice una y se seleccione, se mostrará el siguiente mensaje "**No es posible realizar transacciones mediante esta red**".
{% endhint %}

| Campo                                                                                            | Tipo de control   | Descripción                                               | Observaciones                                                 |
| ------------------------------------------------------------------------------------------------ | ----------------- | --------------------------------------------------------- | ------------------------------------------------------------- |
| Crypto Monedas                                                                                   | Lista desplegable | Selecciona una cripto moneda creada.                      | Solo se listan criptomonedas activas para retiro.             |
| [Red Blockchain](https://virtualsoft.gitbook.io/untitled/glosario/#red-blockchain)               | Lista desplegable | Red asociada a la criptomoneda (ej: TRC20, ERC20, BEP20). | Debe coincidir con la red de destino.                         |
| [Dirección Wallet](https://app.gitbook.com/s/mbqa0WvDWam8G20QQoIZ/#d)                            | Campo de texto    | Dirección cripto a la que se enviarán los fondos.         | Verifica que sea válida y compatible con la red seleccionada. |
| Confirmar [Dirección Wallet](https://virtualsoft.gitbook.io/untitled/glosario/#direccion-wallet) | Campo de texto    | Reingresa la dirección para asegurar que sea correcta.    | Ambas direcciones deben coincidir para habilitar el registro. |

**2.2. Tabla de Wallets Registradas**

| Campo                                                                                  | Descripción                                                         |
| -------------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| [Criptomoneda](https://virtualsoft.gitbook.io/untitled/glosario/#criptomoneda)         | Muestra la criptomoneda asociada a la wallet registrada.            |
| Red Blockchain                                                                         | Indica la red seleccionada al momento del registro de la wallet.    |
| [Dirección Wallet](https://virtualsoft.gitbook.io/untitled/glosario/#direccion-wallet) | Dirección cripto registrada. Se visualiza en formato abreviado.     |
| Estado                                                                                 | Indica si la wallet está activa para retiros o ha sido desactivada. |

**2.3. Acciones del Usuario**

<table><thead><tr><th width="158.09088134765625">Ícono</th><th>Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><img src="../../../.gitbook/assets/image-Photoroom (4) (1).png" alt="" data-size="original"></td><td>Guardar</td><td>Permite registrar una nueva <a href="https://app.gitbook.com/s/mbqa0WvDWam8G20QQoIZ/#w">wallet cripto.</a></td></tr><tr><td><img src="../../../.gitbook/assets/image-Photoroom (5) (1).png" alt="" data-size="original"></td><td>Eliminar</td><td>Permite eliminar de forma permanente la <a href="https://app.gitbook.com/s/mbqa0WvDWam8G20QQoIZ/#w">wallet cripto</a> registrada, disponible únicamente si está activa.</td></tr></tbody></table>

***

### 3. ✅ Validaciones y Reglas de Negocio

| Validación                                 | Mensaje de error                                                                                        |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------------- |
| Dirección vacía o no coincidente           | “Las direcciones ingresadas no coinciden.”                                                              |
| Combinación duplicada en la misma cuenta   | “Ya has registrado esta dirección para esta cripto y red.”                                              |
| Dirección ya registrada por otro jugador   | “Esta dirección ya fue registrada por otro usuario.”                                                    |
| Límite superado por combinación cripto/red | “Solo puedes registrar hasta (Número definido anteriormente) direcciones para esta criptomoneda y red.” |

* Solo se pueden registrar wallets de criptomonedas configuradas previamente en BackOffice.
* Es obligatorio seleccionar correctamente la red blockchain asociada a la criptomoneda.
* No se permite registrar múltiples wallets con la misma dirección y red.
* El botón “Eliminar” solo está disponible para wallets con estado “Activa”.
* Una wallet solo puede eliminarse si no está asociada a retiros activos o pendientes.
* El número máximo de wallets por combinación cripto/red es configurable.

***

### 4. 👤 Permisos de Acceso

| Acción                 | Requisito                                     |
| ---------------------- | --------------------------------------------- |
| Ver sección de wallets | Jugador logueado y activo                     |
| Registrar nueva wallet | Permitido si no supera el límite configurado  |
| Eliminar wallet        | Solo si no tiene retiros activos o pendientes |

***

### 5. 📘 Glosario

| Término             | Definición                                                                |
| ------------------- | ------------------------------------------------------------------------- |
| **Estado Activo**   | La wallet está habilitada para ser usada en solicitudes de retiro.        |
| **Estado Inactivo** | La wallet ha sido deshabilitada y no puede ser seleccionada para retiros. |

***

### 6. 🕒 Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados                                    |
| ------- | ---------- | ------------- | ----------------------------------------------------- |
| 1.0     | 22/07/2025 | Ronald Pelaez | Documento inicial                                     |
| 1.0.1   | 06/08/2025 | Ronald Peláez | Ajuste en función de las condiciones de criptomoneda. |
