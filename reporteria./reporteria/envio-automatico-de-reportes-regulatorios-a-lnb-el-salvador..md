---
description: >-
  Este módulo permite la generación y envío automático de archivos regulatorios
  requeridos por la LNB (Lotería Nacional de Beneficencia), a través del agente
  oficial proporcionado por dicha entidad.
---

# Envío automático de reportes regulatorios a LNB El Salvador.

***

### 1. Acceso al módulo

**Ubicación del sistema fuente**: **/implementaciones/el salvador/**

**Aplicativo utilizado**: Agente LNB instalado en un servidor autorizado por la LNB.

***

### 2. Acciones del sistema

El proceso consiste en generar diariamente los archivos regulatorios requeridos por la LNB y enviarlos automáticamente mediante el Agente LNB. Para ello, se requiere una estructura de carpetas específica y un proceso validado.

<table><thead><tr><th width="197.44439697265625">Sección</th><th width="160.111083984375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Generación de archivos</strong></td><td>Automática</td><td>El sistema genera diariamente 2 archivos CSV: uno de saldos y otro de transacciones.</td></tr><tr><td><strong>Estructura de carpetas</strong></td><td>Crear en <code>C:/ARCHIVOS_LNB/</code></td><td>Se debe crear una estructura fija de directorios donde el Agente LNB buscará diariamente los archivos generados. Las subcarpetas necesarias son: <code>SALDOS/</code> para los archivos de saldos diarios, <code>TRANSACCIONES/</code> para las transacciones diarias, y <code>PROCESADOS/</code> para almacenar los archivos que ya fueron enviados exitosamente.</td></tr><tr><td><strong>Movimiento de archivos</strong></td><td>Automático</td><td>Al finalizar el envío exitoso, los archivos se mueven automáticamente a la carpeta <code>PROCESADOS/</code>.</td></tr><tr><td><strong>Reintentos</strong></td><td>Automático</td><td>Si falla el envío, el sistema reintenta automáticamente hasta 3 veces.</td></tr><tr><td><strong>Registro de errores</strong></td><td>Registro en logs</td><td>Se registran los errores en un log accesible para el equipo técnico.</td></tr></tbody></table>

***

#### 2.1. Estructura de directorios

Ruta raíz: `C:/ARCHIVOS_LNB/`

Subcarpetas necesarias:

* `/SALDOS/`
* `/TRANSACCIONES/`
* `/PROCESADOS/`

<figure><img src="https://1436566604-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F4oliKJn51O4j6grKI5lm%2Fuploads%2FTymBLVVQUq3UWq8HMqPi%2Fimage.png?alt=media&#x26;token=681361cb-2c21-4703-bb20-bf2b21769970" alt=""><figcaption><p>Figura #1: Estructura de carpetas esperada en el servidor.</p></figcaption></figure>

***

#### 2.2. Nombres de archivos esperados

| Partner         | Archivo de Saldos               | Archivo de Transacciones  |
| --------------- | ------------------------------- | ------------------------- |
| **`Doradobet`** | `SALDO-DOBE+YYYYMMDDHHMMSS.csv` | `DOBE+YYYYMMDDHHMMSS.csv` |
| **`Ganaplay`**  | `SALDO-GPLA+YYYYMMDDHHMMSS.csv` | `GPLA+YYYYMMDDHHMMSS.csv` |

{% hint style="warning" %}
**Nota:** La nomenclatura debe cumplirse estrictamente, incluyendo el uso del prefijo correspondiente.
{% endhint %}

***

#### 2.3. Contenido de los archivos

* **SALDOS (SALDO-GPLA / SALDO-DOBE)**\
  A continuación, se describe el contenido y los campos incluidos en los archivos mediante la siguiente tabla.

| Campo                                                                                 | Descripción                                                                                                                                                                               |
| ------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **`CodigoOperador`**                                                                  | Código del operador ([GPLA ](envio-automatico-de-reportes-regulatorios-a-lnb-el-salvador..md#glosario)o [DOBE](envio-automatico-de-reportes-regulatorios-a-lnb-el-salvador..md#glosario)) |
| **`FechaHoraSaldo`**                                                                  | Fecha y hora de captura de saldos                                                                                                                                                         |
| **`CodigoClienteText`**                                                               | Identificador único del cliente                                                                                                                                                           |
| [**`PEP`**](envio-automatico-de-reportes-regulatorios-a-lnb-el-salvador..md#glosario) | Si el cliente es persona políticamente expuesta                                                                                                                                           |
| **`Nacionalidad`**                                                                    | Nacionalidad del cliente                                                                                                                                                                  |
| **`FechaCreacion`**                                                                   | Fecha y hora de creación del usuario                                                                                                                                                      |
| **`SaldoUSDTotal`**                                                                   | Total en billetera (créditos + premios + bonos) sin impuestos                                                                                                                             |
| **`SaldoUSDCreditos`**                                                                | Monto de recargas realizadas por el jugador                                                                                                                                               |
| **`SaldoUSDPremios`**                                                                 | Premios cargados a la billetera                                                                                                                                                           |
| **`SaldoUSDPromocion`**                                                               | Bonos promocionales aplicados                                                                                                                                                             |
| `UltimoMovCliente`                                                                    | Fecha y hora del último movimiento registrado del cliente                                                                                                                                 |

* **TRANSACCIONES (GPLA / DOBE)**\
  A continuación, se describe el contenido y los campos incluidos en los archivos mediante la siguiente tabla.

| Campo                                                                                                | Descripción                                        |
| ---------------------------------------------------------------------------------------------------- | -------------------------------------------------- |
| **`FechaHoraTransaccion`**                                                                           | Fecha y hora de la transacción                     |
| **`IdTransaccion`**                                                                                  | ID único de transacción                            |
| **`CodigoOperador`**                                                                                 | Código del operador (GPLA o DOBE)                  |
| **`CodigoClienteText`**                                                                              | Código del cliente dentro del operador             |
| **`PEP`**                                                                                            | Persona políticamente expuesta                     |
| [**`TipoOperacion`**](envio-automatico-de-reportes-regulatorios-a-lnb-el-salvador..md#glosario)      | Tipo de transacción (ver glosario)                 |
| **`TipoProducto`**                                                                                   | Tipo de producto en el que se realiza la operación |
| **`IDProducto`**                                                                                     | ID del producto (juego, evento, etc.)              |
| **`MontoUSDCreditos`**                                                                               | Valor de transacción desde créditos                |
| **`MontoUSDPremios`**                                                                                | Valor de transacción desde premios                 |
| **`MontoUSDPromocion`**                                                                              | Valor de transacción desde bonos promocionales     |
| [**`MetodoPago`**](envio-automatico-de-reportes-regulatorios-a-lnb-el-salvador..md#glosario)         | Método de pago del depósito                        |
| [**`MetodoCanjePremios`**](envio-automatico-de-reportes-regulatorios-a-lnb-el-salvador..md#glosario) | Método utilizado para la entrega el premio         |

***

### 3. Validaciones y reglas de negocio

* Los archivos deben generarse diariamente en la ruta `/implementaciones/el salvador/`.
* Se deben cumplir las estructuras de nombres de archivo definidas para cada tipo de archivo y operador.
* Los archivos deben moverse automáticamente a `C:/ARCHIVOS_LNB/SALDOS/` y `C:/ARCHIVOS_LNB/TRANSACCIONES/`.
* El contenido de los archivos debe cumplir con el [diccionario de datos](envio-automatico-de-reportes-regulatorios-a-lnb-el-salvador..md#glosario) proporcionado por la LNB.
* El sistema debe validar que:
  * Los archivos existen y están en la carpeta correcta.
  * El nombre del archivo es único (no ha sido enviado antes).
  * El contenido cumple con el formato, estructura y catálogos definidos.
* En caso de error:
  * Los archivos inválidos se moverán a una carpeta de errores.
  * Los intentos de envío fallidos se reintentarán automáticamente hasta 3 veces.
  * Todos los eventos de error se registrarán en un log técnico para revisión.

***

#### Glosario

| Término              | Definición                                                               |
| -------------------- | ------------------------------------------------------------------------ |
| DOBE                 | Prefijo del operador Doradobet El Salvador                               |
| GPLA                 | Prefijo del operador Ganaplay El Salvador                                |
| PEP                  | Persona Políticamente Expuesta                                           |
| Tipo de operación    | DEPOSITO, RETIRO, REEMBOLSO, APUESTA, PREMIO, AJUSTE, TEST, APUESTABONO  |
| Método de pago       | TDC (Tarjeta crédito), TDD (Tarjeta débito), PPAGO (Pasarela de pago)    |
| MetodoCanjePremios   | Forma en que se entrega el premio (ej. billetera, cuenta bancaria, etc.) |
| Diccionario de Datos | Documento oficial entregado por la LNB con estructura y catálogos        |

***

### 4. Control de versiones

<details>

<summary>🔽Historial de versiones</summary>

| Versión | Fecha      | Autor         | Cambios realizados                            |
| ------- | ---------- | ------------- | --------------------------------------------- |
| 1.0     | 24/07/2025 | Ronald Peláez | Documento con formato inicial y ajuste por HU |
| 1.1     | 24/08/2026 | Ronald Peláez | Ajustes en formato                            |

</details>
