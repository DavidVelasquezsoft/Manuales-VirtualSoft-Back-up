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

**Ruta de Acceso**: BackOffice (BO) > Reportes > Reporte de Ingresos Consolidados Doradobet

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (664).png" alt=""><figcaption></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-ingresos-consolidados-doradobet.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Permite definir el rango de fechas y el país para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-ingresos-consolidados-doradobet.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra la información consolidada en la tabla.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite descargar el reporte en formato Excel mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="98.99993896484375">Campo</th><th width="127.27276611328125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el rango de fechas a consultar. Es obligatorio.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el país asociado al partner de la sesión. Si no se selecciona un país, el sistema no mostrará información.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Muestra la información consolidada del reporte según el rango de fechas seleccionado. Los datos se agrupan por día y se presentan en una sola fila por fecha.

<table><thead><tr><th width="217.63641357421875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Indica el día al que corresponde la información consolidada.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Representa el valor total de los depósitos registrados en la operación.</td></tr><tr><td><strong><code>Rejuego</code></strong></td><td><p>Corresponde a la diferencia entre las apuestas totales y los depósitos registrados en el histórico de saldos. </p><p><strong>Formula:</strong><br><em>Rejuego = Apuestas Totales− Depósitos</em></p></td></tr><tr><td><strong><code>Apuestas + Rejuego</code></strong></td><td>Muestra la suma total de las apuestas realizadas <em>(deportivas y de casino)</em> más el valor de rejuego.</td></tr><tr><td><strong><code>Apuestas + Rejuego Deportivas</code></strong></td><td>Representa el total de apuestas deportivas registradas en el histórico de saldos, más el valor de rejuego correspondiente.</td></tr><tr><td><strong><code>Apuestas + Rejuego Casino</code></strong></td><td>Representa el total de apuestas de casino registradas en el histórico de saldos, más el valor de rejuego correspondiente.</td></tr><tr><td><strong><code>Premios Deportivas</code></strong></td><td>Indica el valor total de premios pagados en apuestas deportivas.</td></tr><tr><td><strong><code>Premios Casino</code></strong></td><td>Indica el valor total de premios pagados en casino.</td></tr><tr><td><strong><code>Retiros Pagados</code></strong></td><td>Muestra el valor total de los retiros procesados y pagados.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, no será visible en el sistema.
* Es obligatorio seleccionar un rango de fechas para consultar la información.
* Este reporte presenta la información a día vencido, por lo que solo incluye datos de fechas ya cerradas; no se muestra información del día actual.&#x20;
* El reporte es exportable a Excel.
* Este reporte muestra la información extraída del reporte [historico-de-saldos.md](historico-de-saldos.md "mention")&#x20;

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="111">Versión</th><th width="135.54541015625">Fecha</th><th width="131.727294921875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>20/04/2026</td><td>Karol Navia</td><td>Creación del manual del Reporte de Ingresos Consolidados Doradobet</td></tr></tbody></table>

</details>
