---
description: >-
  El reporte de saldos permite visualizar información detallada sobre los saldos
  de los usuarios en la plataforma.
---

# Reporte de Saldos

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Reporte de Saldos

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption><p>Figura#1: Captura de pantalla filtros sección reporte de saldos.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="134">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-saldos.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Permite definir los criterios de búsqueda para consultar la información del reporte, incluyendo los filtros de fecha.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros seleccionados, dejando los valores en estado inicial.</td></tr><tr><td><a href="reporte-de-saldos.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda de información según los filtros definidos.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite descargar la información del reporte en formato excel desde la parte inferior derecha.</td></tr></tbody></table>

***

### **4.  Filtros**

<table><thead><tr><th width="137.7037353515625">Campo</th><th width="123.8887939453125">Tipo de Control</th><th width="423.6666259765625">Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Permite buscar información asociada a un usuario específico.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Selecciona el rango de fechas <em>(desde – hasta)</em> para realizar la búsqueda de los registros que deseas consultar.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país para delimitar los resultados de acuerdo con la ubicación del usuario.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selector de opción</td><td>Define el nivel de detalle a visualizar (<em>Detallado o Totales)</em>. Según la opción seleccionada, el sistema mostrará la información correspondiente.</td></tr><tr><td><p><strong><code>Solo Saldos</code></strong> </p><p><strong><code>Negativos</code></strong></p></td><td>Selector de opción</td><td>Permite definir si se desea visualizar únicamente los registros con saldos negativos. Estos saldos pueden generarse por diferentes factores dentro de la operación, como ajustes, movimientos pendientes, etc</td></tr></tbody></table>

***

### **5. Resultados** de consulta

El sistema permite visualizar los resultados en dos tipos de vista, según el nivel de detalle seleccionado en el filtro **Tipo**:

{% tabs %}
{% tab title="Detallado" %}
Presenta la información desglosada por usuario, mostrando los siguientes datos:

<table><thead><tr><th width="185.88885498046875">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>🔍(Lupa)</code></strong></td><td>Al dar clic, se desplegará una vista con el resumen financiero del usuario.<br><a href="reporte-de-saldos.md#detalle-del-resumen-financiero-del-usuario" class="button secondary">Ver detalles De lupa</a></td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario.</td></tr><tr><td><strong><code>Nombre Usuario</code></strong></td><td>Nombre asociado al usuario.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Tipo de moneda utilizada.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha de la transacción o registro del usuario en la plataforma.</td></tr><tr><td><strong><code>Saldo Recargas</code></strong></td><td>Monto total asociado a las recargas realizadas por el usuario.</td></tr><tr><td><strong><code>Saldo Retiros</code></strong></td><td>Monto total de los retiros realizados por el usuario.</td></tr></tbody></table>

<details>

<summary>🔍 Detalle del resumen financiero del usuario</summary>

Se presentan los valores consolidados del usuario según el rango de fechas seleccionado.

<table><thead><tr><th width="243">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total Depósitos</code></strong></td><td>Valor total de los depósitos realizados durante el rango de fechas seleccionado.</td></tr><tr><td><strong><code>Total Apuestas Deportivas</code></strong></td><td>Suma total de las apuestas realizadas en la vertical de deportivas.</td></tr><tr><td><strong><code>Total Ganancias Deportivas</code></strong></td><td>Valor total de las ganancias obtenidas en apuestas deportivas durante el rango de fechas.</td></tr><tr><td><strong><code>Total Apuestas Casino</code></strong></td><td>Suma total de las apuestas realizadas en juegos de casino.</td></tr><tr><td><strong><code>Ganancias Totales Casino</code></strong></td><td>Valor total de las ganancias generadas en casino </td></tr><tr><td><strong><code>Total Retiros</code></strong></td><td>Valor total de los retiros realizados por el usuario</td></tr><tr><td><strong><code>Total Ajustes Entrada</code></strong></td><td>Suma de los ajustes que incrementan el saldo del usuario.</td></tr><tr><td><strong><code>Total Ajustes Salida</code></strong></td><td>Suma de los ajustes todos los movimientos realizados.</td></tr></tbody></table>

<a href="reporte-de-saldos.md#resultado-detallado" class="button secondary">Regresar</a>

</details>
{% endtab %}

{% tab title="Totales" %}
Muestra la información agrupada de forma general, Mostrando los saldos sin entrar en el detalle por usuario.

<table><thead><tr><th width="167">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Moneda</code></strong></td><td>Tipo de moneda utilizada por el usuario.</td></tr><tr><td><strong><code>Saldo recargas</code></strong></td><td>Valor total correspondiente a las recargas realizadas por el usuario.</td></tr><tr><td><strong><code>Saldo retiros</code></strong></td><td>Valor total correspondiente a los retiros realizados.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 6. Validaciones y Reglas de Negocio

* No es necesario completar todos los filtros para poder realizar una búsqueda.
* El filtro **Fecha** estará predeterminado con el día actual, incluso al limpiar los filtros.

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="102">Versión</th><th width="123">Fecha</th><th width="143">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>17/08/2025</td><td>Ronald Peláez</td><td>Documento inicial del manual</td></tr><tr><td>1.1</td><td>31/03/2025</td><td>Karol Navia</td><td>Mejoramiento de Formato y agregar el filtro fecha</td></tr></tbody></table>

</details>
