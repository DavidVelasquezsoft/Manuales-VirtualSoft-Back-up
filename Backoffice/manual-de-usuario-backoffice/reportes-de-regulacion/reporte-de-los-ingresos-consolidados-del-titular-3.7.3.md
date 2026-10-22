---
description: >-
  Este reporte proporciona un resumen consolidado de los ingresos generados en
  la categoría de casino, permitiendo un análisis financiero de la operación
  dentro de un periodo determinado.
---

# Reporte de los ingresos consolidados del titular (3.7.3)

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Reportes de regulación > Reporte de los ingresos consolidados del titular (3.7.3)

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (705).png" alt=""><figcaption><p>Figura#1: Captura de pantalla reporte de los ingresos consolidados del titular.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-los-ingresos-consolidados-del-titular-3.7.3.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Define el criterio de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-los-ingresos-consolidados-del-titular-3.7.3.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según el filtro definido y muestra la información consolidada en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="98.00006103515625">Campo</th><th width="81">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el periodo de consulta indicando una fecha de inicio y una fecha de fin, para visualizar los ingresos correspondientes.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con la información consolidada según el periodo seleccionado.

{% hint style="warning" %}
**Nota:** Los valores de este reporte provienen del [**Reporte de Ingresos Consolidados Doradobet**](../reportes/reporte-de-ingresos-consolidados-doradobet.md), donde el total apostado y los premios pagados se distribuyen entre deportivas y casino según los porcentajes configurados por período mensual en el módulo [**Reporte declaración de impuestos**.](reporte-declaracion-de-impuestos.md)
{% endhint %}

<table><thead><tr><th width="169.0555419921875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Día o periodo correspondiente al reporte.</td></tr><tr><td><strong><code>Total de apuestas</code></strong></td><td><p>Suma total del monto apostado por los jugadores en la vertical de casino.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Corresponde a la porción del total apostado que se asigna a casino según el porcentaje configurado para el período en el módulo <a href="reporte-declaracion-de-impuestos.md"><strong>Reporte declaración de impuestos</strong>.</a></p></div></td></tr><tr><td><strong><code>Total de premios</code></strong></td><td><p>Total de dinero pagado a los jugadores como premios por sus apuestas ganadoras.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Corresponde a la porción del total apostado que se asigna a casino según el porcentaje configurado para el período en el módulo <a href="reporte-declaracion-de-impuestos.md"><strong>Reporte declaración de impuestos</strong>.</a></p></div></td></tr><tr><td><strong><code>Total de bonificaciones</code></strong></td><td><p>Monto total otorgado en bonificaciones o promociones dentro del casino.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Una bonificación es el saldo promocional que la plataforma otorga al jugador; no corresponde a dinero propio del jugador.</p></div></td></tr><tr><td><strong><code>Total de premios del sistema progresivo</code></strong></td><td><p>Cantidad total de premios entregados a través de juegos con jackpot progresivo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Un sistema progresivo es un premio que crece de forma acumulada: una parte de cada apuesta se suma al pozo hasta que un jugador lo gana.</p></div></td></tr><tr><td><strong><code>Total de devoluciones</code></strong></td><td>Suma de los reembolsos o devoluciones de apuestas realizadas a los jugadores.</td></tr><tr><td><strong><code>Total de comisiones por servicio</code></strong></td><td>Total de comisiones aplicadas por la plataforma en concepto de servicio o uso.</td></tr><tr><td><strong><code>Derechos de inscripción</code></strong></td><td><p>Monto total recaudado por concepto de inscripciones a torneos u otros eventos dentro del casino.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Los derechos de inscripción son las cuotas que paga el jugador para participar en un torneo o evento.</p></div></td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* Es obligatorio seleccionar un periodo de fechas para ejecutar la consulta.
* El reporte presenta la información consolidada de los ingresos generados en la categoría de casino.
* La información se presenta agrupada por día dentro del periodo seleccionado.
* Los valores de **`Total de apuestas`** y **`Total de premios`** resultan de la distribución entre verticales configurada por período mensual en el módulo **Reporte declaración de impuestos**, y llegan a este reporte a través del Reporte de Ingresos Consolidados Doradobet.
* La parametrización aplica a partir de **octubre de 2026**. Los períodos anteriores conservan los porcentajes preestablecidos en el sistema.
* Modificar los porcentajes de un período no altera la información de otros períodos.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>22/10/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-34571">Se documenta el origen de los valores y su dependencia de los porcentajes configurables por período.</a></td></tr></tbody></table>

</details>
