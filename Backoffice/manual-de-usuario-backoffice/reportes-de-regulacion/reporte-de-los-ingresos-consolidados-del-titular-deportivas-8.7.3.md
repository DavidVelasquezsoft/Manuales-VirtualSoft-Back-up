# Reporte de los ingresos consolidados del titular (Deportivas) (8.7.3)

<mark style="color:$info;">El Reporte de Ingresos Consolidados del Titular permite visualizar un resumen de los ingresos generados en la plataforma de apuestas deportivas, con un desglose detallado de los montos recaudados y pagados dentro de un periodo específico.</mark>

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Reporte de los Ingresos Consolidados del Titular (Deportivas)

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (373).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección Reporte de los ingresos consolidados del titular.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-los-ingresos-consolidados-del-titular-deportivas-8.7.3.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Define el criterio de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-los-ingresos-consolidados-del-titular-deportivas-8.7.3.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según el filtro definido y muestra la información consolidada en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formato Excel mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Ingresa el periodo de consulta seleccionando una fecha de inicio y una fecha de fin.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con la información consolidada según el periodo seleccionado.

<table><thead><tr><th width="192.12957763671875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td><p>Indica el día en que se consolidan las operaciones.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La consolidación abarca desde las 00:00:00 hasta las 23:59:59 horas del mismo día. Se genera un registro por cada día dentro del periodo seleccionado.</p></div></td></tr><tr><td><strong><code>Total de Apuestas</code></strong></td><td>Monto total apostado, incluyendo las apuestas realizadas con bonificaciones.</td></tr><tr><td><strong><code>Total de Premios</code></strong></td><td>Suma de los premios pagados a los jugadores, considerando premios obtenidos por bonificaciones y/o premios progresivos, según corresponda.</td></tr><tr><td><strong><code>Total de Bonificaciones</code></strong></td><td><p>Monto total otorgado a los jugadores en forma de bonificaciones.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Una bonificación es el saldo promocional que la plataforma otorga al jugador; no corresponde a dinero propio del jugador.</p></div></td></tr><tr><td><strong><code>Total de Premios del Sistema Progresivo</code></strong></td><td><p>Suma de los premios entregados a través del sistema progresivo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Un sistema progresivo es un premio que crece de forma acumulada: una parte de cada apuesta se suma al pozo hasta que un jugador lo gana.</p></div></td></tr><tr><td><strong><code>Total de Devoluciones</code></strong></td><td>Monto total de las devoluciones realizadas a los jugadores.</td></tr><tr><td><strong><code>Total de Comisiones por Servicio</code></strong></td><td>Ingresos generados a partir de las comisiones cobradas por los servicios prestados en la plataforma.</td></tr><tr><td><strong><code>Derechos de Inscripción</code></strong></td><td><p>Monto total recaudado por concepto de derechos de inscripción en eventos o competiciones.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Los derechos de inscripción son las cuotas que paga el jugador para participar en un evento o competición.</p></div></td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* Es obligatorio seleccionar un periodo de fechas para ejecutar la consulta.
* La información se presenta consolidada por día: se genera un registro por cada día del periodo seleccionado, abarcando desde las 00:00:00 hasta las 23:59:59 horas.
* El reporte muestra la información correspondiente a la plataforma de apuestas deportivas.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>19/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
