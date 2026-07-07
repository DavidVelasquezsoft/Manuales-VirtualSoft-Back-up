# Reporte de Historial de Puntos Calificables

Permite consultar las [**entradas y salidas**](reporte-de-historial-de-puntos-calificables.md#id-6.-validaciones-y-reglas-del-negocio) de los [**puntos calificables** ](https://virtualsoft.gitbook.io/untitled/glosario/#puntos-calificables)del jugador.\
Estos puntos se generan automáticamente con las apuestas y se usan para determinar el **nivel de lealtad**, sin posibilidad de uso directo por parte del jugador.

### 1. Acceso al módulo

**Ruta de acceso**: BackOffice > Jugadores > Reportes > Historial de Puntos&#x20;

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (26).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Historial de puntos calificables.</p></figcaption></figure>

***

### 3. Acciones de Usuario

<table><thead><tr><th width="228">Acción </th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Consultar</strong></td><td>Aplica los filtros seleccionados y muestra los registros del historial de puntos calificables del jugador.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros a sus valores por defecto.</td></tr><tr><td><strong>Exportar información</strong></td><td>Exporta la información consultada ya sea en PFD o en formato Excel.</td></tr></tbody></table>

***

### 4.Filtros

<table><thead><tr><th width="156">Campo</th><th width="161">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong> </td><td>Calendario</td><td>Permite elegir las fechas para ver los datos del reporte</td></tr><tr><td><strong><code>ID Externo</code></strong></td><td>Campo numérico</td><td>Identificador con el que los proveedores externos identifican el movimiento de los puntos <em>(solo aplica para entradas).</em></td></tr><tr><td><strong><code>Movimiento</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el tipo de movimiento a visualizar en el reporte <em>(Todos,</em> <a href="reporte-de-historial-de-puntos-calificables.md#id-6.-validaciones-y-reglas-del-negocio"><em>Entrada o Salida</em></a><em>)</em>.</td></tr><tr><td><strong><code>Tipo de transacción</code></strong></td><td>Lista desplegable</td><td>Clasificación del movimiento <em>(Apuesta Deportiva, Casino o Expiración de puntos).</em></td></tr></tbody></table>

***

### 5. Columnas del Reporte

<table><thead><tr><th width="190">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador interno de la transacción registrada en el sistema.</td></tr><tr><td><strong><code>Movimiento</code></strong></td><td>Indica si se trata de una <a href="reporte-de-historial-de-puntos-calificables.md#id-6.-validaciones-y-reglas-del-negocio"><em>Entrada</em> o <em>Salida</em></a> de puntos.</td></tr><tr><td><strong><code>ID Externo</code></strong></td><td>ID de la apuesta asociada <em>(solo en movimientos de entrada).</em></td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de transacción <em>(Apuesta Deportiva, Casino o Expiración de puntos calificables).</em></td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha y hora en la que le realizaron ya sea un movimiento de entrada o de salida a los puntos calificables del usuario.</td></tr><tr><td><strong><code>Puntos</code></strong></td><td>Cantidad de puntos que le agregan o le quitan al usuario.</td></tr><tr><td><strong><code>Puntos Final</code></strong></td><td>Cantidad final de puntos calificables asignados al jugador luego de realizar un movimiento ya sea de <a href="reporte-de-historial-de-puntos-calificables.md#id-6.-validaciones-y-reglas-del-negocio">entrada o de salida</a>.</td></tr><tr><td><strong><code>Periodo de acumulación</code></strong></td><td>Intervalo de fechas de los puntos expirados <em>(solo visible en movimientos de salida por expiración). Ejemplo: 01/09/2025 – 30/09/2025.</em></td></tr></tbody></table>

***

### &#x20;6. Validaciones y reglas del negocio

* La expiración se registra automáticamente cuando el jugador cumple el tiempo de permanencia configurado desde el [Site Builder](https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/promocionales/niveles-de-lealtad.).
* Los puntos expirados se reflejan como movimientos de salida automáticos.
* Los saldos se recalculan correctamente tras cada entrada o salida para mantener la consistencia del total de puntos calificables.
* El historial es de solo lectura y no permite modificaciones manuales.
* Los puntos calificables se dan en paralelo según la configuración del partner [<sub>(Más información.)</sub>](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion/tipos-de-movimientos-nota-por-cada-monto-en-xxx-va-a-obtener-z-puntos-base), pero los puntos calificables se utilizan para asignar los niveles de lealtad en Site Builder, y los puntos canjeables se utilizan para realizar compras en la tienda lealtad de usuarios online.
* &#x20;Los **movimientos de salida** son aquellos que le quitan puntos calificables, ya sea por vencimiento de puntos o ajustes realizados.
* Los **movimientos de entrada** son aquellos que le asignan puntos calificables al usuario y se obtienen automáticamente por las apuestas, según la configuración realizada en el [partner](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion/tipos-de-movimientos-nota-por-cada-monto-en-xxx-va-a-obtener-z-puntos-base).

***

### &#x20;7. Control de versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="100" align="right">Versión</th><th width="127">Fecha</th><th width="141">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td align="right">1.0</td><td>11/11/2025</td><td>Ronald Peláez</td><td>Creación del documento inicial.</td></tr></tbody></table>

</details>
