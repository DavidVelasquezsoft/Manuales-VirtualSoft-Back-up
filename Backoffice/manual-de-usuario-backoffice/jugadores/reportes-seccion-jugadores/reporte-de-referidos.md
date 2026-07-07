# Reporte de referidos

### 1. Acceso al módulo

**Ruta de acceso**: Backoffice > Jugadores > Reportes > Reporte de referidos

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="119.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtro</strong></td><td>Permite filtrar la información para obtener resultados más precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="reporte-de-referidos.md#id-3.1.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. Filtros

Tendrás los siguientes filtros que te ayudarán a realizar una búsqueda más detallada:

<table><thead><tr><th width="125.11102294921875">Campo</th><th width="119.66668701171875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID referido</code></strong></td><td>Numérico</td><td>Identificador único del referido.</td></tr><tr><td><strong><code>Fecha de registro</code></strong></td><td>Calendario</td><td>Fecha en la que se registro el usuario referido.</td></tr><tr><td><strong><code>Fecha del primer deposito</code></strong></td><td>Fecha y hora</td><td>Fecha del primer deposito del usuario referido.</td></tr><tr><td><strong><code>Estado de referido</code></strong></td><td>Lista desplegable</td><td>Estado del usuario referido.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Opción única</td><td>Elige el tipo de reporte que quieres consultar.<br><strong>Totales:</strong> Reporte mas resumido con información de referentes.<br><strong>Detallado:</strong> Reporte mas detallado con información de los referidos.</td></tr></tbody></table>

***

### 5. Resultados de Consulta

Aplica los filtros seleccionados y muestra los reportes detallados de los usuarios referidos por el usuario seleccionado.

{% tabs %}
{% tab title="Tipo totales" %}
## Tipo Totales - Información de Referentes

Después de realizar la consulta, se presentará la siguiente tabla que contiene información sobre los referentes.

<table><thead><tr><th width="197">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Referente</code></strong></td><td>Identificadores de los referentes. Si se especifica una consulta, los resultados se mostrarán de acuerdo con la misma.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre del referente correspondientes a la consulta realizada.</td></tr><tr><td><strong><code>Referidos Totales</code></strong></td><td>Cantidad de referidos que han completado exitosamente el registro en la página de usuarios online utilizando el link enviado por el referente (por correo o compartido directamente).</td></tr><tr><td><strong><code>Referidos Exitosos</code></strong></td><td>Número de referidos que han acreditado al menos un premio para el referente.</td></tr><tr><td><strong><code>Bonos por Depósito</code></strong></td><td>Total de bonos que el referente puede reclamar o ya ha reclamado, como resultado del cumplimiento de la condición <strong>“Mínimo primer depósito”</strong> por parte de sus referidos.</td></tr><tr><td><strong><code>Bonos por Apuesta</code></strong></td><td>Total de bonos que el referente puede reclamar o ya ha reclamado, como resultado del cumplimiento de la condición <strong>“Mínimo valor en apuestas”</strong> por parte de sus referidos.</td></tr></tbody></table>
{% endtab %}

{% tab title="Tipo detallado" %}
## Información de Referido

Después de hacer clic en **"Consultar"**,  una tabla con la siguiente información sobre los referidos del referente consultado.

<table><thead><tr><th width="182">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Referido</code></strong></td><td>Muestra los identificadores de los referidos registrados en la página. </td></tr><tr><td><strong><code>Fecha de Registro</code></strong></td><td>Fecha y hora en que el referido realizó el registro en la página de usuarios online.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre del referido tal como se registró en la plataforma.</td></tr><tr><td><strong><code>Apellido</code></strong></td><td>Apellido del referido tal como se registró en la página.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Indica el estado del referido: <strong>Activo</strong> (con acceso a la plataforma) o <strong>Desactivado</strong> (sin acceso).</td></tr><tr><td><strong><code>Último Login</code></strong></td><td>Fecha en la que el referido realizó su último inicio de sesión en la página.</td></tr><tr><td><strong><code>Referente</code></strong></td><td>ID del referente que envió la invitación al usuario.</td></tr><tr><td><strong><code>Primer Depósito</code></strong></td><td>Fecha y hora en que el referido efectuó su primer depósito en la plataforma.</td></tr><tr><td><strong><code>Valor Primer Depósito</code></strong></td><td>Monto del primer depósito realizado por el referido.</td></tr><tr><td><strong><code>Valor Apuestas Deportivas</code></strong></td><td>Total de las apuestas realizadas en la vertical de <strong>Deportes</strong> por el referido.</td></tr><tr><td><strong><code>Última Apuesta Deportiva</code></strong></td><td>Fecha de la última apuesta realizada en la sección de <strong>Deportes</strong>.</td></tr><tr><td><strong><code>Valor Apuesta Casino</code></strong></td><td>Total de las apuestas realizadas en la sección de <strong>Casino</strong>.</td></tr><tr><td><strong><code>Última Apuesta Casino</code></strong></td><td>Fecha de la última apuesta realizada en la sección de <strong>Casino</strong>.</td></tr><tr><td><strong><code>Premio Primer Depósito</code></strong></td><td>Indica si el referido generó un premio para el referente al realizar el primer depósito. Puede mostrarse <strong>“Generó premio”</strong> o <strong>“No ha generado premio”</strong>.</td></tr><tr><td><strong><code>Premio Apuestas</code></strong></td><td>Especifica si el referido generó un premio para el referente al realizar apuestas. Puede mostrarse <strong>“Generó premio”</strong> o <strong>“No ha generado premio”</strong>.</td></tr><tr><td><strong><code>Total Referidos</code></strong></td><td>Número total de referidos que tiene el usuario (un referido que también actúa como referente con sus propios invitados).</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 6. Control de versiones

<details>

<summary>🔽Historial de version</summary>

<table><thead><tr><th width="100.22216796875" align="right">Versión</th><th width="129">Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td align="right">1.0</td><td>2025-09-22</td><td>David velasquez</td><td>Documento inicial.</td></tr></tbody></table>

</details>
