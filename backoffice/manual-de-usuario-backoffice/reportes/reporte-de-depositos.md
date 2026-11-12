---
description: >-
  Permite visualizar todos los depósitos realizados y aplicar filtros generales
  o avanzados para consultas específicas.
---

# Reporte de depósitos

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > reporte de depósitos

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FXgZOgZzDmnvdSUs8XDER%2Fimage.png?alt=media&#x26;token=ee5d3219-49c3-4344-9d51-670c4575541c" alt=""><figcaption><p>figura#1: Captura de pantalla filtros sección reporte de depósitos.</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-depositos.md#id-4.-filtros-principales"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="reporte-de-depositos.md#id-5.-resultados-de-busqueda"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. Filtros principales

<table><thead><tr><th width="132.148193359375">Campo</th><th width="155">Tipo de Control</th><th width="455.5555419921875">Descripción</th></tr></thead><tbody><tr><td><code>ID</code></td><td>Numérico</td><td>Filtra por un identificador único del depósito.</td></tr><tr><td><code>Fecha</code></td><td>Calendario</td><td>Selecciona un rango de fechas.</td></tr><tr><td><code>ID Usuario</code></td><td>Numérico</td><td>Filtra depósitos de un usuario específico.</td></tr><tr><td><code>País</code></td><td>Lista desplegable</td><td>Selecciona un país para limitar resultados.</td></tr><tr><td><code>Estado</code></td><td>Lista desplegable</td><td>Filtra depósitos según estado: todos, activo, inactivo.</td></tr><tr><td><p><code>Resumen</code> </p><p><code>por Proveedor</code></p></td><td>Casilla de verificación</td><td>Agrupa resultados por proveedor de pasarela de pago.</td></tr><tr><td><code>Ordenar por</code></td><td>Lista desplegable</td><td>Ordena por ID Usuario, Valor, Fecha de creación.</td></tr><tr><td><code>Orden</code></td><td>Lista desplegable</td><td>Define orden ascendente o descendente.</td></tr></tbody></table>

#### 4.1. Filtros avanzados

<table><thead><tr><th width="164.18511962890625">Campo</th><th width="164.03704833984375">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo Pasarela de Pago</code></strong></td><td>Lista desplegable</td><td>Filtra por tipo de pasarela utilizada.</td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Lista desplegable</td><td>Selecciona un punto de venta asociado a la operación.</td></tr><tr><td><strong><code>Agente</code></strong></td><td>Lista desplegable</td><td>Filtra depósitos procesados por un agente específico.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Campo de texto</td><td>Filtra resultados según la dirección IP asociada.</td></tr><tr><td><strong><code>External ID</code></strong></td><td>Campo de texto</td><td>Busca por identificador externo asociado al depósito.</td></tr><tr><td><p><strong><code>Proveedor</code></strong> </p><p><strong><code>Pasarela de Pago</code></strong></p></td><td>Lista desplegable</td><td>Filtra por proveedor de pasarela de pago.</td></tr><tr><td><strong><code>Valor Mínimo</code></strong></td><td>Numérico</td><td>Limita resultados a depósitos con valor mínimo establecido.</td></tr><tr><td><strong><code>Valor Máximo</code></strong></td><td>Numérico</td><td>Limita resultados a depósitos con valor máximo establecido.</td></tr></tbody></table>

### 5. Resultados de busqueda

<table><thead><tr><th width="246.88885498046875">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del depósito.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario que realizó el depósito.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha en la que se registró el depósito.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Proveedor de la pasarela de pago utilizada.</td></tr><tr><td><strong><code>Nombre del Sistema de Pasarela de Pago</code></strong></td><td>Nombre del sistema que procesó el depósito.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de transacción realizada.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda en la que se realizó el depósito.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto del depósito.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Comisión aplicada a la transacción.</td></tr><tr><td><strong><code>Impuesto de Depósito</code></strong></td><td>Impuesto cobrado en la operación.</td></tr><tr><td><strong><code>Modificado</code></strong></td><td>Fecha y hora de la última modificación del registro.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del depósito <em>(Activo, Inactivo, etc.).</em></td></tr><tr><td><strong><code>Notas</code></strong></td><td>Observaciones o comentarios adicionales.</td></tr><tr><td><strong><code>External ID</code></strong></td><td>Identificador externo utilizado por la pasarela de pago para asociar y reconocer la transacción.</td></tr><tr><td><strong><code>IP</code></strong></td><td>Dirección IP desde la que se realizó la transacción.</td></tr><tr><td><strong><code>Recepción de Efectivo</code></strong></td><td>Indica si la operación incluyó la recepción de efectivo.</td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* No es necesario completar todos los filtros para poder realizar una búsqueda.

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="97">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/08/2025</td><td>Ronald Peláez</td><td>Documento inicial del manual</td></tr></tbody></table>

</details>
