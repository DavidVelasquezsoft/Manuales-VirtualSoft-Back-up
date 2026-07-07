# Reporte de retiros

### 1. Acceso al Módulo

**Ruta de Acceso:** Gestión punto de venta > punto de venta > Comisiones > Reporte de Retiros

***

### 2. Visualización del Módulo

<figure><img src="../../../../.gitbook/assets/image (675).png" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte de retiros.</p></figcaption></figure>

### 3. Acciones del Usuario

<table><thead><tr><th width="104.00006103515625">Acción</th><th width="643.9999389648438">Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-retiros.md#id-4.-filtros"><strong>Filtrar</strong></a></td><td>Permite definir los criterios de búsqueda del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros a su estado inicial.</td></tr><tr><td><a href="reporte-de-retiros.md#id-5.-resultados-del-reporte"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros seleccionados.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="160">Sección</th><th width="145">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Seleccionar rango</td><td>Permite filtrar los retiros por un rango de fechas específico.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Seleccionar</td><td>Filtra los retiros según su estado (ej. aprobado, pendiente, rechazado).</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Ingresar texto</td><td>Permite buscar retiros asociados a una dirección IP específica.</td></tr><tr><td><strong><code>Formas de Pago</code></strong></td><td>Seleccionar</td><td>Filtra los resultados por el método de pago utilizado.</td></tr></tbody></table>

***

### 5. Resultados del Reporte

Una vez ejecutada la consulta, el sistema muestra una tabla con el detalle de los retiros registrados.

<table><thead><tr><th width="227">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>Identificador único del retiro.</td></tr><tr><td><strong><code>ID Cliente</code></strong></td><td>Código único del cliente asociado al retiro.</td></tr><tr><td><strong><code>Nombre Cliente</code></strong></td><td>Nombre del cliente que realizó el retiro.</td></tr><tr><td><strong><code>DNI</code></strong></td><td>Documento de identificación del cliente.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto del retiro solicitado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del retiro.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se registró el retiro.</td></tr><tr><td><strong><code>Departamento</code></strong></td><td>Departamento asociado a la ubicación del cliente.</td></tr><tr><td><strong><code>Ciudad</code></strong></td><td>Ciudad del cliente.</td></tr><tr><td><strong><code>Forma de pago</code></strong></td><td>Método de pago utilizado para el retiro.</td></tr><tr><td><strong><code>Cuenta Bancaria</code></strong></td><td>Número de cuenta registrada para el retiro.</td></tr><tr><td><strong><code>Código Interbancario</code></strong></td><td>Código utilizado para transferencias interbancarias.</td></tr><tr><td><strong><code>IP</code></strong></td><td>Dirección IP desde la cual se realizó la solicitud.</td></tr></tbody></table>

***

### &#x20;6. Validaciones y Reglas de Negocio

* El **rango de fechas** es obligatorio para realizar la consulta.
* Los filtros pueden combinarse para obtener resultados más específicos.
* Si no existen registros para los filtros aplicados, la tabla se mostrará vacía.
* El botón **Limpiar** no ejecuta una nueva búsqueda automáticamente.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de Versiones</summary>

<table><thead><tr><th width="103">Versión</th><th width="144">Fecha</th><th width="143">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>25/02/2025</td><td>Karol Navia</td><td>Documento inicial</td></tr></tbody></table>

</details>
