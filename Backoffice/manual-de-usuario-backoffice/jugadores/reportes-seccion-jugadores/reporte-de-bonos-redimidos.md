# Reporte de bonos redimidos

### 1. Acceso al módulo

**Ruta de acceso**: Backoffice > Jugadores > Reportes > Reporte de bonos

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (582).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Reportes de bonos redimidos</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="119.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtro</strong></td><td>Permite filtrar la información para obtener resultados más precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="reporte-de-bonos-redimidos.md#id-3.1.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="123.44451904296875">Campo</th><th width="193.111083984375">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Rango de fechas para filtrar por bonos otorgados o utilizados.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Estado actual del bono <em>(activo, expirado, pendiente, etc.).</em></td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Clasificación del bono <em>(depósito, no depósito, etc.).</em></td></tr><tr><td><p><strong><code>Partner</code></strong> </p><p><strong><code>Bono ID</code></strong></p></td><td>Numérico</td><td>Identificador único del bono vinculado al partner.</td></tr></tbody></table>

***

### 5. Resultados de Consulta

Aplica los filtros seleccionados y muestra los reportes detallados del historial de bonos redimidos del usuario

<table><thead><tr><th width="209.99993896484375">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td>🔎</td><td>Despliega barra lateral de detalles avanzados sobre ese bono.</td></tr><tr><td><strong><code>Id</code></strong></td><td>Identificador único del bono en el sistema.</td></tr><tr><td><strong><code>ID Cliente</code></strong></td><td>Identificador único del cliente asociado.</td></tr><tr><td><strong><code>ID referidoa</code></strong> </td><td>Identificador único del referido en caso de que aplique.</td></tr><tr><td><strong><code>Id Bono</code></strong></td><td>Identificador interno del bono dentro de la plataforma.</td></tr><tr><td><strong><code>Nombre de Bono</code></strong></td><td>Nombre asignado, indicando tipo o campaña relacionada.</td></tr><tr><td><strong><code>Fecha Inicio</code></strong></td><td>Fecha de activación o disponibilidad del bono.</td></tr><tr><td><strong><code>Fecha Aceptación</code></strong></td><td>Fecha en la que el cliente reclamó o aceptó el bono.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Clasificación del bono <em>(bienvenida, recarga, fidelización, etc.).</em></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual <em>(activo, utilizado, expirado o pendiente)</em>.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto original otorgado en el bono.</td></tr><tr><td><strong><code>Fecha modificación</code></strong></td><td>Fecha de la última modificación registrada en el bono.</td></tr><tr><td><strong><code>Monto Convertido</code></strong></td><td>Valor convertido a saldo efectivo o utilizable.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#rollover"><strong><code>Rollover</code></strong></a> <strong><code>Requerido</code></strong></td><td>Monto mínimo que debe apostarse para liberar o convertir el bono.</td></tr><tr><td><strong><code>Apostado</code></strong></td><td>Cantidad ya apostada con el bono.</td></tr><tr><td><strong><code>Restante</code></strong></td><td>Monto pendiente para cumplir el requisito de <a href="https://virtualsoft.gitbook.io/untitled/glosario#rollover">rollover</a>.</td></tr><tr><td><strong><code>Fecha Expiración</code></strong></td><td>Fecha límite de vigencia del bono.</td></tr></tbody></table>

***

### 6. Añadir bono a saldo

Despliega un formulario emergente para añadir saldo en forma de bono a un usuario.

{% hint style="warning" %}
**Nota:** Para añadirlo requiere que el bono esté previamente creado.
{% endhint %}

<table><thead><tr><th width="146.49993896484375">Campo </th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario ID</code></strong></td><td>Identificador del usuario.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de bono asignado.</td></tr><tr><td><strong><code>Tipo Saldo</code></strong></td><td><p>Tipo de saldo aplicado al </p><p>usuario <em>(Ej: Saldo recargas)</em>.</p></td></tr><tr><td><strong><code>Referencia</code></strong></td><td>ID del bono previamente creado.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto del bono asignado.</td></tr></tbody></table>

***

### 7. Control de versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="116.22216796875" align="right">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td align="right">1.0</td><td>2025-09-22</td><td>David velasquez</td><td>Documento inicial.</td></tr></tbody></table>

</details>
