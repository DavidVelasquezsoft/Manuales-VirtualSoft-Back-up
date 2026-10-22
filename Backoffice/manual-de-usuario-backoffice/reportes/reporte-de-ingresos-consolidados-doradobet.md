---
description: >-
  Permite visualizar la información consolidada de ingresos de la operación por
  rango de fechas y país, basada en el histórico de saldos, con el fin de apoyar
  la declaración de impuestos.
---

# Reporte de Ingresos Consolidados Doradobet

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.&#x20;
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Reportes > Reporte de Ingresos Consolidados Doradobet

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (706).png" alt=""><figcaption><p>Figura #1: Captura de Pantalla del reporte</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-ingresos-consolidados-doradobet.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Permite definir el rango de fechas y el país para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-ingresos-consolidados-doradobet.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra la información consolidada en la tabla.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite descargar el reporte en formato Excel mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="98.99993896484375">Campo</th><th width="127.27276611328125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el rango de fechas a consultar. <em>(Es obligatorio)</em>.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el país asociado al partner de la sesión. <em>(Si no se selecciona un país, el sistema no mostrará información).</em></td></tr></tbody></table>

***

### 5. Resultados de consulta

Muestra la información consolidada del reporte según el rango de fechas seleccionado. Los datos se agrupan por día y se presentan en una sola fila por fecha.

{% hint style="warning" %}
**Nota:** La distribución de los valores entre las verticales de **deportivas** y **casino** no es fija: se calcula aplicando los porcentajes configurados por período mensual en el módulo [**Reporte declaración de impuestos**](../reportes-de-regulacion/reporte-declaracion-de-impuestos.md).
{% endhint %}

<table><thead><tr><th width="196.63641357421875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Día al que corresponde la información consolidada.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Valor total de los depósitos registrados en la operación.</td></tr><tr><td><strong><code>Apuestas deportivas</code></strong></td><td><p>Porción del total apostado que corresponde a la vertical de apuestas deportivas, según el porcentaje configurado para el período.</p><p><strong>Fórmula:</strong><br><em>Apuestas Deportivas = Apuestas × % Apuestas Deportivas</em></p></td></tr><tr><td><strong><code>Apuestas casino</code></strong></td><td><p>Porción del total apostado que corresponde a la vertical de casino, según el porcentaje configurado para el período.</p><p><strong>Fórmula:</strong><br><em>Apuestas Casino = Apuestas × % Apuestas Casino</em></p></td></tr><tr><td><strong><code>Cantidad Apuestas</code></strong></td><td>Cantidad total de depósitos realizados, sumando las verticales de deportivas y casino.</td></tr><tr><td><strong><code>Cantidad Apuestas Deportivas</code></strong></td><td>Cantidad de de depósitos realizadas en la vertical de apuestas deportivas.</td></tr><tr><td><strong><code>Cantidad Apuestas Casino</code></strong></td><td>Cantidad de depósitos realizadas en la vertical de casino.</td></tr><tr><td><strong><code>Rejuego</code></strong></td><td><p>Diferencia entre las apuestas totales y los depósitos registrados en el histórico de saldos. </p><p><strong>Fórmula: </strong><em><strong>(</strong>Rejuego = Apuestas Totales− Depósitos<strong>)</strong></em></p></td></tr><tr><td><strong><code>Apuestas + Rejuego</code></strong></td><td>Suma total de las apuestas realizadas <em>(deportivas y de casino)</em> más el valor de rejuego.</td></tr><tr><td><strong><code>Apuestas + Rejuego Deportivas</code></strong></td><td>Total de apuestas deportivas registradas en el histórico de saldos, más el valor de rejuego correspondiente.</td></tr><tr><td><strong><code>Apuestas + Rejuego Casino</code></strong></td><td>Total de apuestas de casino registradas en el histórico de saldos, más el valor de rejuego correspondiente.</td></tr><tr><td><strong><code>Premios Deportivas</code></strong></td><td>Valor total de premios pagados en apuestas deportivas.</td></tr><tr><td><strong><code>Premios Casino</code></strong></td><td>Valor total de premios pagados en casino.</td></tr><tr><td><strong><code>Retiros Pagados</code></strong></td><td>Valor total de los retiros procesados y pagados.</td></tr><tr><td><strong><code>Premios Pagados Deportivas</code></strong></td><td><p>Porción de los retiros pagados que corresponde a la vertical de apuestas deportivas, según el porcentaje configurado para el período.</p><p><strong>Fórmula:</strong><br><em>Premios Pagados Deportivas = Retiros Pagados × % Premios Deportivas</em></p></td></tr><tr><td><strong><code>Premios Pagados Casino</code></strong></td><td><p>Porción de los retiros pagados que corresponde a la vertical de casino, según el porcentaje configurado para el período.</p><p><strong>Fórmula:</strong><br><em>Premios Pagados Casino = Retiros Pagados × % Premios Casino</em></p></td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, no será visible en el sistema.
* Es obligatorio seleccionar un rango de fechas para consultar la información.
* Este reporte presenta la información a día vencido, por lo que solo incluye datos de fechas ya cerradas; no se muestra información del día actual.&#x20;
* Este reporte muestra la información extraída del reporte [historico-de-saldos.md](historico-de-saldos.md "mention")&#x20;
* La distribución de los valores entre deportivas y casino se calcula con los porcentajes configurados por período mensual en el módulo **Reporte declaración de impuestos**. Modificar esos porcentajes cambia los valores que muestra este reporte para el período correspondiente.
* La parametrización aplica a partir de **octubre de 2026**. Los períodos anteriores conservan los porcentajes preestablecidos en el sistema, por lo que al comparar meses anteriores y posteriores a esa fecha la distribución responde a dos lógicas distintas.
* Los valores de este reporte alimentan los reportes de regulación del BackOffice **(8.7.3** y **3.7.3)** y el reporte diario que se envía a MINCETUR.
* Los cambios en los porcentajes se reflejan según los tiempos de procesamiento ya configurados para este reporte, no de forma inmediata.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="111">Versión</th><th width="135.54541015625">Fecha</th><th width="131.727294921875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>20/04/2026</td><td>Karol Navia</td><td>Creación del manual del Reporte de Ingresos Consolidados Doradobet</td></tr><tr><td>1.1</td><td>23/06/2026</td><td>Karol Navia</td><td>Se agregan las columnas: <strong><code>Apuestas Deportivas, Apuestas Casino, Cantidad Apuestas, Cantidad Apuestas Deportivas, Cantidad Apuestas Casino, Premios Pagados Deportivas y Premios Pagados Casino.</code></strong></td></tr><tr><td>1.2</td><td>22/10/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-34571">Los valores por vertical pasan a calcularse con los porcentajes configurables del módulo Reporte declaración de impuestos.</a></td></tr></tbody></table>

</details>
