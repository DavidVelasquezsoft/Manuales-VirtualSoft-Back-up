---
description: >-
  El Reporte de Movimientos de Saldo permite consultar y analizar los cambios
  realizados en los saldos de los usuarios de la plataforma.
---

# Reporte de Movimientos Saldo

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Reporte de movimientos Saldo

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (47).png" alt=""><figcaption><p>Figura #1: Captura de pantalla de los filtros de búsqueda.</p></figcaption></figure>

***

### 3. Funcionalidades

**📋 3.1 Acciones disponibles**

<table><thead><tr><th width="253">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td>Filtrar movimientos</td><td>Permite aplicar filtros de búsqueda para localizar movimientos específicos.</td></tr><tr><td>Seleccionar categoría</td><td>Opción para clasificar movimientos según el tipo o naturaleza.</td></tr><tr><td>Visualizar tabla de resultados</td><td>Presenta la información detallada de los movimientos según los filtros aplicados.</td></tr><tr><td>Exportar los resultados</td><td>Exporta en formato Excel la tabla de los resultados según los filtros seleccionados.</td></tr></tbody></table>

**🔎 3.2 Filtros principales**

| Campo               | Tipo de Control   | Descripción                                                                                                                                        |
| ------------------- | ----------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| `ID Usuario`        | Campo de texto    | Permite buscar movimientos asociados a un usuario en particular mediante su identificador único.                                                   |
| `ID Externo`        | Campo de texto    | Filtra movimientos relacionados con un identificador externo (ejemplo: número de referencia o ticket).                                             |
| `Fecha de Creación` | Calendario        | Limita los resultados a movimientos dentro de un rango de fechas determinado.                                                                      |
| `Movimiento`        | Lista desplegable | Clasifica los movimientos. Opciones: **Todos**, **Entrada**, **Salida**, **Cancelación**.                                                          |
| `Tipo`              | Lista desplegable | Filtra movimientos por categoría específica. Opciones: **Todos**, **Recargas**, **Ajuste de Saldo**, **Apuestas Deportivas**, **Apuestas Casino**. |
| `País`              | Lista desplegable | Filtra los movimientos según el país asociado al usuario o la operación.                                                                           |

**📊 3.3 Resultados de la consulta**

La tabla de resultados muestra la siguiente información:

| Columna               | Descripción                                                    |
| --------------------- | -------------------------------------------------------------- |
| **ID**                | Identificador único del movimiento.                            |
| **ID Usuario**        | Identificador del usuario que realizó o recibió el movimiento. |
| **Movimiento**        | Tipo de movimiento ejecutado (Entrada, Salida, Cancelación).   |
| **Tipo**              | Categoría del movimiento (Recarga, Apuesta, Ajuste, etc.).     |
| **ID Externo**        | Referencia externa asociada al movimiento.                     |
| **Fecha de Creación** | Fecha y hora en la que se registró el movimiento.              |
| **Valor**             | Monto total del movimiento.                                    |
| **Saldo Recargas**    | Saldo acumulado de recargas tras el movimiento.                |
| **Saldo Retiros**     | Saldo acumulado de retiros tras el movimiento.                 |

{% hint style="info" %}
**Sobre el consumo de saldo:** el usuario siempre consume primero su **saldo recarga**; una vez agotado o cuando este no alcanza a cubrir el movimiento, se comienza a consumir el **saldo retiro**. Esto explica cómo se reflejan ambos saldos tras cada movimiento.
{% endhint %}

***

### 4. Validaciones y Reglas de Negocio

* No es necesario completar todos los filtros para realizar una búsqueda.
* Los resultados dependerán de los filtros aplicados y las categorías seleccionadas.
* La información en la tabla refleja el saldo actualizado después de cada movimiento.

***

### 5. Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 24/09/2025 | Ronald Peláez | Documento inicial  |
