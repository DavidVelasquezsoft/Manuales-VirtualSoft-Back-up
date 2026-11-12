---
description: >-
  Visualiza la información agrupada sobre las apuestas realizadas en la vertical
  deportiva.
---

# Reporte de Apuestas Deportivas

***

### **1. Acceso al Módulo**

**Ruta de acceso**: Area de trabajo > Equipo respuesta > Apuestas Deportivas + Estados + Refund

***

### 2. Composición del tabero.

En este reporte se encuentran disponibles dos vistas principales, que permiten analizar las apuestas desde diferentes enfoques operativos:

1. [**Apuestas Refund**](https://virtualsoft.gitbook.io/manuales/power-bi./power-bi/acceso-a-los-tableros./reporte-de-apuestas-deportivas#apuestas-refund)**:** Muestra todas aquellas apuestas que han sido **canceladas o anuladas**, generando un proceso de **reembolso (refund)**.
2. [**Apuestas Transacción**](https://virtualsoft.gitbook.io/manuales/power-bi./power-bi/acceso-a-los-tableros./reporte-de-apuestas-deportivas#apuestas-transaccion)**:** Presenta las apuestas con movimientos **transaccionales negativos**, correspondientes a ajustes, devoluciones o diferencias registradas entre el valor reportado y el saldo reflejado.

{% tabs %}
{% tab title="Apuestas Refund" %}
### **3. Visualización**

<figure><img src="../../.gitbook/assets/image (86).png" alt=""><figcaption><p>Figura#1: Captura de pantalla apuestas refund.</p></figcaption></figure>

### **4. Acciones del Usuario**

| Sección                | Tipo       | Descripción                                                                         |
| ---------------------- | ---------- | ----------------------------------------------------------------------------------- |
| `Selector de Fechas`   | Calendario | Permite definir el rango de fechas para visualizar apuestas con estados refund.     |
| `Segmento de Apuestas` | Botón      | Permite alternar entre las pestañas **Apuestas Refund** y **Apuestas Transacción**. |
| `Borrar Filtros`       | Botón      | Limpia todos los filtros aplicados en el tablero.                                   |

#### **4.1. Indicadores**

* **Usuarios**: Número total de usuarios impactados por apuestas refundadas.
* **Total refund**: Suma total del valor refund en el rango de fechas seleccionado.

#### **4.2. Filtros disponibles**

| Campo                 | Tipo de control    | Descripción                                                                         |
| --------------------- | ------------------ | ----------------------------------------------------------------------------------- |
| `Partner`             | Lista Desplegable. | Filtra por el (partner) asociado a la apuesta.                                      |
| `País`                | Lista Desplegable. | Permite filtrar por un país en específico.                                          |
| `ID Usuario`          | Lista Desplegable. | Selecciona un ID específico de usuario.                                             |
| `Estado apuesta`      | Lista Desplegable. | Filtra según el estado actual de la apuesta. Ej. abierta, anulada, ganada, perdida. |
| `Tipo transacción`    | Lista Desplegable. | Selecciona el tipo de transacción asociada.                                         |
| `Nombre evento`       | Lista Desplegable. | Filtra por el evento deportivo correspondiente.                                     |
| `Cantidad de estados` | Lista Desplegable. | Filtra por número de estados registrados en la apuesta.                             |
| `Validar diferencia`  | Lista Desplegable. | Filtra apuestas con diferencias por revisar o ya validadas.                         |

#### **4.3. Columnas del Resultado**

<table><thead><tr><th width="250">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Partner</code></td><td>Muestra el nombre del partner asociado a la apuesta.</td></tr><tr><td><code>País</code></td><td>País donde se originó la apuesta.</td></tr><tr><td><code>ID_Usuario</code></td><td>Identificador único del usuario que realizó la apuesta.</td></tr><tr><td><code>Ticket ID</code></td><td>Identificador del ticket de la apuesta.</td></tr><tr><td><code>Transacción del ticket</code></td><td>Número de la transacción asociada al ticket.</td></tr><tr><td><code>Estado apuesta</code></td><td>Estado actual de la apuesta.</td></tr><tr><td><code>Tipo transacciones</code></td><td>Tipo de transacción realizada, en este caso siempre se mostrará Refund.</td></tr><tr><td><code>Fecha Crea</code></td><td>Fecha en la que se creó la apuesta.</td></tr><tr><td><code>Fecha Cierre</code></td><td>Fecha en la que se cerró la apuesta.</td></tr><tr><td><code>Fecha_Pago</code></td><td>Fecha en la que se realizó el reembolso.</td></tr><tr><td><code>Nombre evento</code></td><td>Nombre del evento deportivo.</td></tr><tr><td><code>Apuesta</code></td><td>Valor de la apuesta realizada.</td></tr><tr><td><code>Premio</code></td><td>Valor del premio asociado.</td></tr><tr><td><code>Diferencia apuestas</code></td><td><p>Diferencia detectada en el valor de la apuesta.</p><p><strong>Fórmula:</strong></p><ol><li>En el <strong>Backoffice</strong>, se debe filtrar el reporte de apuestas por tipo de apuesta: <strong>"creadas"</strong> y en el histórico de saldos por detallado.</li><li>Se debe restar el valor total de la <strong>columna </strong><em><strong>valor</strong></em> del reporte de apuestas, con el valor total correspondiente en la <strong>columna </strong><em><strong>Ap. Deportivas</strong></em> del reporte de historial de saldos.</li></ol></td></tr><tr><td><code>Diferencia premios</code></td><td><p>Diferencia detectada en el valor del premio.</p><p><strong>Fórmula:</strong></p><ol><li>En el <strong>Backoffice</strong>, se debe filtrar el reporte de apuestas por tipo de apuesta: <strong>"cerradas"</strong> y en el histórico de saldos por <strong>detallado</strong>.</li><li>Se debe restar el valor total de la <strong>columna </strong><em><strong>premios</strong></em> del reporte de apuestas, con el valor correspondiente en la <strong>columna </strong><em><strong>Pr. Deportivas</strong></em> del reporte de historial de saldos.</li></ol></td></tr><tr><td><code>Validar diferencia</code></td><td>Indica si se debe revisar el reporte si existe alguna diferencia.</td></tr></tbody></table>

#### 5. Validaciones y Reglas de Negocio

* Las apuestas refund se generan exclusivamente cuando un evento es cancelado o anulado.
* Las diferencias de apuestas y premios deben ser revisadas y validadas por el equipo correspondiente.
{% endtab %}

{% tab title="Apuestas transacción " %}
### 3. Visualización

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption><p><strong>Figura #1:</strong> Captura de pantalla de la vista Apuestas Transacción.</p></figcaption></figure>

### 4. Acciones del Usuario

| Sección                    | Tipo       | Descripción                                                                  |
| -------------------------- | ---------- | ---------------------------------------------------------------------------- |
| **`Selector de Fechas`**   | Calendario | Permite definir el rango de fechas para visualizar apuestas transaccionales. |
| **`Segmento de Apuestas`** | Botón      | Alterna entre las pestañas **Apuestas Refund** y **Apuestas Transacción**.   |
| **`Borrar Filtros`**       | Botón      | Limpia todos los filtros aplicados en el tablero.                            |

#### 4.1. Indicadores

* **Usuarios:** Número total de usuarios con apuestas transaccionales en el rango seleccionado.

#### 4.2. Filtros Disponibles

| Campo                    | Tipo de Control    | Descripción                                              |
| ------------------------ | ------------------ | -------------------------------------------------------- |
| **`Partner`**            | Lista Desplegable. | Filtra por el partner asociado a la apuesta.             |
| **`País`**               | Lista Desplegable. | Permite filtrar por país.                                |
| **`ID Usuario`**         | Lista Desplegable. | Selecciona un ID específico de usuario.                  |
| **`Evento`**             | Lista Desplegable. | Filtra por el nombre del evento deportivo.               |
| **`Tipo`**               | Lista Desplegable. | Tipo de transacción o apuesta.                           |
| **`Cantidad estados`**   | Lista Desplegable. | Filtra por el número de estados registrados.             |
| **`Validar diferencia`** | Lista Desplegable. | Filtra apuestas con diferencias por revisar o validadas. |
| **`Usuarios únicos`**    | Lista Desplegable. | Muestra apuestas agrupadas por usuario.                  |

#### 4.3. Columnas del Resultado

<table><thead><tr><th width="190">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner asociado.</td></tr><tr><td><strong><code>País</code></strong></td><td>País donde se originó la apuesta.</td></tr><tr><td><strong><code>Ticket ID</code></strong></td><td>Identificador único de la apuesta.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario.</td></tr><tr><td><strong><code>Fecha Crea</code></strong></td><td>Fecha en la que se creó la apuesta.</td></tr><tr><td><strong><code>Fecha Cierre</code></strong></td><td>Fecha en la que se cerró la apuesta.</td></tr><tr><td><strong><code>Fecha Pago</code></strong></td><td>Fecha en la que se ejecutó la transacción.</td></tr><tr><td><strong><code>Tipo transacciones</code></strong></td><td>Tipo de transacción registrada (ej. Win, Bet, Loss, etc).</td></tr><tr><td><strong><code>Estado apuesta</code></strong></td><td>Estado actual de la apuesta (ganada, perdido, anulada).</td></tr><tr><td><strong><code>Valor Apostado</code></strong></td><td>Valor total apostado.</td></tr><tr><td><strong><code>Premios Deportivos</code></strong></td><td>Valor total de premios entregados.</td></tr><tr><td><strong><code>Fecha transacción</code></strong></td><td>Fecha efectiva de la transacción.</td></tr><tr><td><strong><code>Diferencia apuestas</code></strong></td><td><p>Diferencia detectada en el valor apostado.</p><p><strong>Fórmula:</strong></p><ol><li>En el <strong>BackOffice</strong>, se debe filtrar el reporte de apuestas por tipo de apuesta: <strong>"creadas"</strong> y en el histórico de saldos por detallado.</li><li>Se debe restar el valor total de la <strong>columna </strong><em><strong>valor</strong></em> del reporte de apuestas, con el valor total correspondiente en la <strong>columna </strong><em><strong>Ap. Deportivas</strong></em> del reporte de historial de saldos.</li></ol></td></tr><tr><td><strong><code>Diferencia premios</code></strong></td><td><p>Diferencia detectada en el valor del premio.</p><p><strong>Fórmula:</strong></p><ol><li>En el <strong>BackOffice</strong>, se debe filtrar el reporte de apuestas por tipo de apuesta: <strong>"cerradas"</strong> y en el histórico de saldos por <strong>detallado</strong>.</li><li>Se debe restar el valor total de la <strong>columna </strong><em><strong>premios</strong></em> del reporte de apuestas, con el valor correspondiente en la <strong>columna </strong><em><strong>Pr. Deportivas</strong></em> del reporte de historial de saldos.</li></ol></td></tr><tr><td><strong><code>Validar diferencia</code></strong></td><td>Indica si la diferencia ha sido revisada o no.</td></tr></tbody></table>

### &#x20;5. Validaciones y Reglas de Negocio

* Las diferencias que se visualizan deben ser revisadas y validadas por el equipo correspondiente.
* Las transacciones negativas reflejan movimientos contables generados por devoluciones, errores o ajustes en el sistema.
* Una diferencia distinta de cero en cualquiera de las columnas indica que se debe realizar un análisis detallado por parte del equipo.
{% endtab %}
{% endtabs %}

### 6. Control de Versiones:

<details>

<summary>🔽Historial de versiones</summary>

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 28/07/2025 | Karol Navia.  | Documento inicial  |
| 1.1     | 19/08/2026 | Ronald Peláez | Ajustes en formato |

</details>
