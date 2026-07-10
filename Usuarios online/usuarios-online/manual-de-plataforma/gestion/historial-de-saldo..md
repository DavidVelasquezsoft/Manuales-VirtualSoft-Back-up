# Historial de saldo.

La sección de **Historial de saldo** permite consultar los movimientos realizados en la cuenta del usuario, ya sea entradas o salidas de fondos, aplicando filtros que facilitan la búsqueda de transacciones específicas.

***

### 1. Visualización

<figure><img src="https://3756725920-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FI1JHf1oqcL4UapE69pFw%2Fuploads%2FA60XFjH023LjQYpjzZan%2Fimage.png?alt=media&#x26;token=31d67067-453d-4189-931b-f5c7c65a8e41" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Historial de movimientos.</p></figcaption></figure>

#### 🧑‍💻 Acciones del Usuario

| Campo              | Tipo de Control   | Descripción                                                                                                                                                        |
| ------------------ | ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Fecha de inicio    | Selector de fecha | Permite seleccionar la fecha a partir de la cual se desean visualizar los movimientos. Debe ser menor o igual a la fecha final.                                    |
| Fecha de fin       | Selector de fecha | Define el límite hasta el cual se mostrarán los resultados. La diferencia entre las fechas no puede superar los tres meses.                                        |
| Tipo de movimiento | Dropdown          | Permite filtrar por categoría del movimiento: Entrada o Salida.                                                                                                    |
| Movimiento         | Dropdown          | <p>Permite seleccionar el tipo de transacción:<br>- Depósito<br>- Retiro<br>- Apuesta deportiva<br>- Apuesta de casino<br>- Bono redimido<br>- Ajuste de saldo</p> |

***

### 2. Tabla de resultados

Una vez realizada la consulta, se mostrará una tabla con los movimientos que cumplen con los filtros aplicados.

<figure><img src="https://3756725920-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FI1JHf1oqcL4UapE69pFw%2Fuploads%2F6RtWaFf3EUv23Qv1xIIY%2Fimage.png?alt=media&#x26;token=276b2597-a6ec-4990-9cb8-ab7d5c6dde10" alt=""><figcaption><p>Figura #2: Captura de pantalla tabla de resultados.</p></figcaption></figure>

#### 📄 Columnas de la tabla

| Columna            | Descripción                                                                 |
| ------------------ | --------------------------------------------------------------------------- |
| Fecha y hora       | Indica el momento exacto en que se registró el movimiento.                  |
| Tipo de movimiento | Especifica si es una entrada o salida de saldo.                             |
| Descripción        | Detalla el tipo de operación (ej. depósito, retiro, apuesta, ajuste, etc.). |
| Monto              | Valor asociado a la transacción realizada.                                  |
| Saldo recargas     | Saldo disponible derivado de las recargas efectuadas.                       |
| Saldo retiros      | Saldo disponible correspondiente a los retiros procesados.                  |

***

### 3. Mensajes del sistema

En caso de que no existan movimientos para el rango de fechas o criterios seleccionados, se mostrará el siguiente mensaje:

<figure><img src="https://3756725920-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FI1JHf1oqcL4UapE69pFw%2Fuploads%2FNlEDBkiLN4teLlaZGhXo%2Fimage.png?alt=media&#x26;token=ebb4ef5f-4718-4851-a026-375b780a7b10" alt=""><figcaption><p>Figura #3: Captura de pantalla texto informativo.</p></figcaption></figure>

***

### 4. Control de versiones

| Versión | Fecha      | Autor         | Cambios Realizados          |
| ------- | ---------- | ------------- | --------------------------- |
| 1.0     | 23/07/2025 | Ronald Pelaez | Documento funcional inicial |
