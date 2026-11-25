# Historial de saldo.

<mark style="color:$info;">Permite consultar los movimientos realizados en la cuenta del usuario, ya sean entradas o salidas de fondos, aplicando filtros que facilitan la búsqueda de transacciones específicas.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: Menú principal → Gestión → Historial de saldo

***

### 2. Visualización

<figure><img src="https://3756725920-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FI1JHf1oqcL4UapE69pFw%2Fuploads%2FA60XFjH023LjQYpjzZan%2Fimage.png?alt=media&#x26;token=31d67067-453d-4189-931b-f5c7c65a8e41" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Historial de movimientos.</p></figcaption></figure>

***

### 3. Acciones del Usuario

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="historial-de-saldo..md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen el rango de fechas, el tipo de movimiento y el movimiento por los que se consultan las transacciones de la cuenta.</td></tr><tr><td><a href="historial-de-saldo..md#id-5.-tabla-de-resultados"><strong>Tabla de resultados</strong></a></td><td>Muestra los movimientos que cumplen con los filtros aplicados.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de inicio</code></strong></td><td>Selector de fecha</td><td>Permite seleccionar la fecha a partir de la cual se desean visualizar los movimientos. Debe ser menor o igual a la fecha final.</td></tr><tr><td><strong><code>Fecha de fin</code></strong></td><td>Selector de fecha</td><td>Define el límite hasta el cual se mostrarán los resultados. La diferencia entre las fechas no puede superar los tres meses.</td></tr><tr><td><strong><code>Tipo de movimiento</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por categoría del movimiento: Entrada o Salida.</td></tr><tr><td><strong><code>Movimiento</code></strong></td><td>Lista desplegable</td><td><p>Permite seleccionar el tipo de transacción:</p><ul><li>Depósito</li><li>Retiro</li><li>Apuesta deportiva</li><li>Apuesta de casino</li><li>Bono redimido</li><li>Ajuste de saldo</li></ul></td></tr></tbody></table>

***

### 5. Tabla de resultados

Una vez realizada la consulta, se mostrará una tabla con los movimientos que cumplen con los filtros aplicados.

<figure><img src="https://3756725920-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FI1JHf1oqcL4UapE69pFw%2Fuploads%2F6RtWaFf3EUv23Qv1xIIY%2Fimage.png?alt=media&#x26;token=276b2597-a6ec-4990-9cb8-ab7d5c6dde10" alt=""><figcaption><p>Figura #2: Captura de pantalla tabla de resultados.</p></figcaption></figure>

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha y hora</code></strong></td><td>Indica el momento exacto en que se registró el movimiento.</td></tr><tr><td><strong><code>Tipo de movimiento</code></strong></td><td>Especifica si es una entrada o salida de saldo.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Detalla el tipo de operación (ej. depósito, retiro, apuesta, ajuste, etc.).</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Valor asociado a la transacción realizada.</td></tr><tr><td><strong><code>Saldo recargas</code></strong></td><td>Saldo disponible derivado de las recargas efectuadas.</td></tr><tr><td><strong><code>Saldo retiros</code></strong></td><td>Saldo disponible correspondiente a los retiros procesados.</td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* La fecha de inicio debe ser menor o igual a la fecha final.
* La diferencia entre la fecha de inicio y la fecha de fin no puede superar los tres meses.
* En caso de que no existan movimientos para el rango de fechas o criterios seleccionados, se muestra el siguiente mensaje:

<figure><img src="https://3756725920-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FI1JHf1oqcL4UapE69pFw%2Fuploads%2FNlEDBkiLN4teLlaZGhXo%2Fimage.png?alt=media&#x26;token=ebb4ef5f-4718-4851-a026-375b780a7b10" alt=""><figcaption><p>Figura #3: Captura de pantalla texto informativo.</p></figcaption></figure>

***

### 7. Control de versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>23/07/2025</td><td>Ronald Pelaez</td><td>Documento funcional inicial</td></tr><tr><td>1.1</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
