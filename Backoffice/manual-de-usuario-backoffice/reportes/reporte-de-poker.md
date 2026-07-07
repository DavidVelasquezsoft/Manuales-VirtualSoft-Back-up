---
description: >-
  Este reporte permite consultar el detalle de las sesiones de juego de poker
  realizadas por los usuarios en la plataforma.
---

# Reporte de Póker

### **1. Acceso al Módulo**

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Reporte de Póker

***

### **2. Visualización**

<figure><img src="../../.gitbook/assets/image (658).png" alt=""><figcaption><p>Figura #1: Captura de pantalla filtros de búsqueda del reporte de Póker.</p></figcaption></figure>

***

### **3. Funcionalidades**

| Acción                  | Descripción                                                                                 |
| ----------------------- | ------------------------------------------------------------------------------------------- |
| **Aplicar filtros**     | Permite segmentar la información por fecha, proveedor, país, tipo de comisión, entre otros. |
| **Consultar reporte**   | Genera el reporte según los filtros seleccionados.                                          |
| **Limpiar filtros**     | Restablece todos los valores de búsqueda a su estado inicial.                               |
| **Exportar resultados** | Descarga la información mostrada en formato Excel.                                          |

#### &#x20;**3.1. 🔎 Filtros principales**

<table><thead><tr><th width="170">Campo</th><th width="165">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Selecciona el rango de fechas para visualizar la información del reporte de poker.</td></tr><tr><td><strong><code>Tipo Transacción</code></strong></td><td>Texto</td><td>Filtra por el ID del tipo de transacción asociado al reporte.</td></tr><tr><td><strong><code>ID Usuario Plataforma</code></strong></td><td>Campo de texto</td><td>Identificador del usuario dentro de la plataforma.</td></tr><tr><td><strong><code>País</code></strong></td><td>Buscador / Lista desplegable</td><td>Selecciona el país de origen del usuario.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Buscador / Lista desplegable</td><td>Filtra por el nombre del juego relacionado al producto.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Buscador / Lista desplegable</td><td>Filtra los resultados por proveedor principal del juego.</td></tr><tr><td><strong><code>Tipo de Reporte</code></strong></td><td>Lista desplegable</td><td>Define el nivel de detalle del reporte: <a href="reporte-de-poker.md#id-4.1-detallado-por-sesion-del-usuario">Detallado por sesión</a>, <a href="reporte-de-poker.md#id-4.2-resumido-por-jugador">Resumido por jugador</a> o <a href="reporte-de-poker.md#id-4.3-resumido-por-proveedor">Resumido por proveedor</a>.</td></tr></tbody></table>

***

### **4. 📊 Tabla de Resultados**

Los resultados se presentan en una tabla cuya estructura varía según el tipo de reporte seleccionado.

{% tabs %}
{% tab title="4.1 Detallado por sesión del usuario" %}
Cada fila del reporte representa una sesión individual iniciada por un usuario en el juego seleccionado según los filtros aplicados.

<table><thead><tr><th width="261">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID de Usuario</code></strong></td><td>Identificador único del usuario.</td></tr><tr><td><strong><code>ID de Casino Usuario</code></strong></td><td>Identificador del usuario específico del casino.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Proveedor del juego.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Subproveedor asociado, si aplica.</td></tr><tr><td><strong><code>ID de Sesión</code></strong></td><td>Código identificador de la sesión de juego.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego de póker jugado.</td></tr><tr><td><strong><code>Valor Apostado</code></strong></td><td>Monto total apostado durante la sesión.</td></tr><tr><td><strong><code>Premio</code></strong></td><td>Monto total ganado por el usuario.</td></tr><tr><td><strong><code>GGR (Gross Gaming Revenue)</code></strong></td><td>Ingreso bruto generado por la sesión.</td></tr><tr><td><strong><code>Rake</code></strong></td><td>Comisión aplicada por la casa sobre las apuestas.</td></tr><tr><td><strong><code>Inscripción a Torneo</code></strong></td><td>Monto pagado para participar en un torneo.</td></tr><tr><td><strong><code>% GGR</code></strong></td><td>Porcentaje del GGR respecto al valor apostado (<code>GGR / Valor Apostado * 100</code>).</td></tr></tbody></table>
{% endtab %}

{% tab title="4.2 Resumido por jugador" %}
Cada fila consolida la información de todas las sesiones realizadas por un mismo jugador, agrupadas por fecha y proveedor, según los filtros aplicados.

<table><thead><tr><th width="258">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID de Usuario</code></strong></td><td>Identificador único del jugador.</td></tr><tr><td><strong><code>ID de Casino Usuario</code></strong></td><td>Identificador del jugador dentro del agregador.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor del juego.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Subproveedor asociado <em>(si no aplica, se repite el nombre del proveedor).</em></td></tr><tr><td><strong><code>Valor Apostado Total</code></strong></td><td>Total de apuestas realizadas por el jugador.</td></tr><tr><td><strong><code>Premio Total</code></strong></td><td>Total de premios obtenidos.</td></tr><tr><td><strong><code>GGR</code></strong></td><td>Ingreso bruto generado (<code>Valor Apostado Total - Premio Total</code>).</td></tr><tr><td><strong><code>Rake</code></strong></td><td>Total de comisiones aplicadas al jugador.</td></tr><tr><td><strong><code>Inscripción a Torneos Total</code></strong></td><td>Total pagado en inscripciones a torneos.</td></tr><tr><td><strong><code>% GGR</code></strong></td><td>Porcentaje del GGR respecto al total apostado (<code>GGR / Valor Apostado Total * 100</code>).</td></tr></tbody></table>
{% endtab %}

{% tab title="4.3 Resumido por proveedor" %}
El reporte **Resumido por proveedor** organiza la información de forma jerárquica y expandible: inicia con un resumen por día y permite ver el detalle por proveedor, producto y tipo de transacción.

En el nivel más detallado, las transacciones se muestran mediante **códigos de tipo de transacción**, los cuales representan conceptos como **Buy-In, Rebuy, Add-on y sus fees asociados**.

<table><thead><tr><th width="180">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha consolidada del reporte. Cada fila principal corresponde a un día específico desde el cual se puede desplegar el detalle por proveedor.</td></tr><tr><td><strong><code>Entradas</code></strong></td><td>Suma de todos los valores correspondientes a transacciones de tipo <strong>crédito</strong>, representando el dinero que <strong>ingresa a la cuenta del jugador</strong> <em>(ej: premios pagados).</em></td></tr><tr><td><strong><code>Salidas</code></strong></td><td>Suma de todos los valores correspondientes a transacciones de tipo <strong>débito</strong>, representando el dinero que <strong>sale de la cuenta del jugador</strong> <em>(ej: apuestas, buy-in, rebuy, add-on).</em></td></tr><tr><td><strong><code>Rake</code></strong></td><td>Valor de comisión enviado por el proveedor, correspondiente a la ganancia directa de la casa por la operación de poker. Se visualiza de forma independiente para facilitar su identificación.</td></tr><tr><td><strong><code>Total (GGR)</code></strong></td><td>Ingreso neto de la operación calculado como <code>Entradas - Salidas</code>, reflejando la ganancia o pérdida desde la perspectiva de la casa.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### **5. Validaciones y Reglas de Negocio**

* No es obligatorio completar todos los filtros para realizar una búsqueda.
* La información mostrada dependerá de los filtros y del tipo de reporte seleccionado.
* Los datos consolidados pueden variar según las políticas de cálculo de GGR y Rake de cada proveedor.

***

### **6. Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados                       |
| ------- | ---------- | ------------- | ---------------------------------------- |
| 1.0     | 22/10/2025 | Ronald Peláez | Documento inicial                        |
| 1.1     | 25/03/2026 | Ronald Peláez | Ajuste en reporte resumido por proveedor |
