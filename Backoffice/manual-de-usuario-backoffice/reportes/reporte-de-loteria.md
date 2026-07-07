# Reporte de Lotería

### Descripción general

El **Reporte de Lotería** permite consultar todos los movimientos realizados en los juegos de lotería, ofreciendo control y trazabilidad sobre las transacciones ejecutadas por los usuarios.\
Mediante los filtros disponibles, podrás visualizar la información de forma detallada o resumida según tus necesidades de análisis.

***

#### 1. Acceso al Módulo

**Ruta de acceso:** BackOffice > Reportes > Reporte de Lotería

***

#### 2. Acciones de usuario

<table><thead><tr><th width="153">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Exportar</strong></td><td>Permite descargar la información <em>(filtrada o completa)</em> en formato Excel o PDF. Para ello, ubica el botón <strong>Exportar</strong> en la parte inferior derecha de la página y selecciona el formato deseado para iniciar la descarga.</td></tr><tr><td><strong>Actualizar</strong></td><td>Refresca los datos mostrados en pantalla. La información se actualiza de acuerdo con los movimientos registrados en el sistema.</td></tr><tr><td><strong>Cambio de vista</strong></td><td>Permite alternar entre la vista detallada y la vista resumida por proveedor, según el análisis que se desee realizar.</td></tr></tbody></table>

***

#### 3. Filtros del reporte

Para realizar una búsqueda, puedes aplicar los siguientes filtros disponibles en la parte superior de la pantalla:

> 💡 **Recomendación:**\
> Selecciona primero el tipo de visualización (Check de **Resumen por proveedor**) antes de aplicar los demás filtros. Esto garantiza que los resultados se ajusten correctamente a la vista elegida.

<table><thead><tr><th width="160">Filtro</th><th>Descripción funcional</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Permite seleccionar el día específico a consultar. Este campo es obligatorio para visualizar resultados.</td></tr><tr><td><strong><code>ID de Usuario</code></strong></td><td>Campo opcional que permite filtrar los movimientos asociados a un usuario específico.</td></tr><tr><td><strong><code>Resumen por proveedor</code></strong></td><td>selecciona si el resultado de la consulta será <a href="reporte-de-loteria.md#vista-resumida-por-proveedor"><em>resumido por proveedor</em></a> o <a href="reporte-de-loteria.md#vista-detallada-por-usuario"><em>detallado por usuario</em></a>.</td></tr></tbody></table>

***

{% tabs %}
{% tab title="Vista Resumida por Proveedor" %}
#### 3.1. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FvHp4KVPIMwRtxjVrtVjj%2Fimage.png?alt=media&#x26;token=3074b2a5-1bfd-404f-a39e-953a95b3ac2d" alt=""><figcaption><p>Figura#2: Captura de pantalla vista resumida del reporte de Lotería.</p></figcaption></figure>

En esta vista, la información se agrupa por proveedor, mostrando un resumen global de los resultados obtenidos.

#### 3.2. Resultados de búsqueda Vista Resumida

<table><thead><tr><th width="160">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor principal del juego de lotería.</td></tr><tr><td><strong><code>Sub Proveedor</code></strong></td><td>Nombre del sub proveedor asociado, si aplica.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego de lotería correspondiente.</td></tr><tr><td><strong><code>Cantidad</code></strong></td><td>Total de veces que se jugó el juego.</td></tr><tr><td><strong><code>Ventas</code></strong></td><td>Valor total apostado por los usuarios.</td></tr><tr><td><strong><code>Rollback</code></strong></td><td>Monto correspondiente a ajustes o reversos aplicados.</td></tr><tr><td><strong><code>GGR</code></strong></td><td>Ganancia bruta generada por el proveedor. Para más información consulta el término <a href="https://app.gitbook.com/o/QcwavWzh0dfIwPyknoIT/s/mbqa0WvDWam8G20QQoIZ/#ggr">GGR</a> en el glosario.</td></tr><tr><td><strong><code>% GGR</code></strong></td><td>Porcentaje de ganancia bruta respecto al total de ventas.</td></tr></tbody></table>

#### 3.3. Validaciones del negocio

* Muestra la información agrupada por proveedor y sub proveedor.
* Permite analizar el rendimiento global por cada proveedor de juegos.
* Es útil para obtener indicadores generales y comparar el desempeño entre proveedores.
{% endtab %}

{% tab title="Vista Detallada por Usuario" %}
### 3.1. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FXQWUHR3mLInhm01OXNpO%2Fimage.png?alt=media&#x26;token=dc8034fa-4bd9-4dc7-b6b6-204ed7a7f7bc" alt=""><figcaption><p>Figura#3: Captura de pantalla vista detallada del reporte de Lotería.</p></figcaption></figure>

Esta vista muestra los movimientos de forma individual por usuario, permitiendo un seguimiento más específico de las jugadas y resultados.

### 3.2. Filtros disponibles para consultas por usuario.

<table><thead><tr><th width="146">Filtro</th><th>Descripción funcional</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Permite seleccionar el rango de fechas a consultar. </td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario sobre el cual se desea consultar las transacciones.</td></tr><tr><td><strong><code>Ordenar por</code></strong></td><td>Define el criterio de orden del reporte <em>(Fecha o Valor).</em></td></tr><tr><td><strong><code>Orden</code></strong></td><td>Determina el sentido del ordenamiento de los resultados <em>(Ascendente y Descendente)</em>.</td></tr><tr><td><strong><code>Identificador</code></strong></td><td>Campo para filtrar los registros según el identificador interno de la transacción o apuesta.</td></tr><tr><td><strong><code>Transacción ID</code></strong></td><td>Permite realizar búsquedas específicas por el número de transacción.</td></tr></tbody></table>

#### 3.3. Resultados de búsqueda Vista Detallada

<table><thead><tr><th width="160">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del usuario que realizó la apuesta.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Día en que se registró la transacción.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Nombre o identificador del usuario que participó en el juego.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego jugado por el usuario.</td></tr><tr><td><strong><code>Identificador</code></strong></td><td>Código único asociado a la transacción o juego específico.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Proveedor principal del juego.</td></tr><tr><td><strong><code>Sub Proveedor</code></strong></td><td>Nombre del sub proveedor, si aplica.</td></tr><tr><td><strong><code>Cantidad</code></strong></td><td>Número total de jugadas realizadas por el usuario.</td></tr><tr><td><strong><code>Ventas</code></strong></td><td>Monto total apostado por el usuario.</td></tr><tr><td><strong><code>Rollback</code></strong></td><td>Valor correspondiente a los ajustes o reversos aplicados.</td></tr><tr><td><strong><code>GGR</code></strong></td><td>Ganancia bruta generada por el usuario en ese juego. Ver <a href="https://app.gitbook.com/o/QcwavWzh0dfIwPyknoIT/s/mbqa0WvDWam8G20QQoIZ/#ggr">GGR</a> en el glosario.</td></tr><tr><td><strong><code>% GGR</code></strong></td><td>Porcentaje del GGR con respecto a las ventas totales del usuario.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Total de premios obtenidos por el usuario en el juego.</td></tr></tbody></table>

#### 3.3. Validaciones del negocio

* Permite revisar los movimientos individuales por usuario.
* Muestra la trazabilidad completa de cada jugada registrada.
* Es útil para auditorías o revisiones específicas por cuenta.
{% endtab %}
{% endtabs %}

***

#### 4. Control de versiones

| Versión | Fecha      | Autor         | Descripción                     |
| ------- | ---------- | ------------- | ------------------------------- |
| 1.0     | 22/10/2025 | Ronald Peláez | Creación inicial del documento. |
