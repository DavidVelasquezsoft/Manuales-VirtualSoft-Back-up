---
description: Este reporte muestra información relacionada con las operaciones de cupones.
---

# Reporte de Cupones

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Reporte de Cupones

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2Fy322ueG7KL295YiaVqgt%2Fimage.png?alt=media&#x26;token=a47e6a1f-f69f-4c0c-bcb0-4e919c9b4adc" alt=""><figcaption><p>figura#1: captura de pantalla sección reporte de cupones.</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-cupones.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="reporte-de-cupones.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="128.48147583007812">Campo</th><th width="148.22222900390625">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Fecha</code></td><td>Calendario</td><td>Filtra los resultados según un rango de fechas.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Filtra las transacciones relacionadas con un usuario específico.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra por un país específico.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Filtra resultados por estado.</td></tr><tr><td><p><strong><code>Resumen por</code></strong> </p><p><strong><code>Proveedor</code></strong></p></td><td>Casilla de verificación</td><td>Agrupa los datos por proveedor de los cupones.</td></tr><tr><td><strong><code>Ordenar por</code></strong></td><td>Lista desplegable</td><td>Ordena por Fecha, Valor o ID Usuario.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Lista desplegable</td><td>Define si es ascendente o descendente.</td></tr></tbody></table>

### 5.  Resultados de consulta

Los resultados se presentan en una tabla con las siguientes columnas:

<table><thead><tr><th width="302">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha en que se generó la operación del cupón.</td></tr><tr><td><strong><code>Nombre del Sistema de Pasarela de Pago</code></strong></td><td>Sistema utilizado para procesar la transacción.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda usada en la operación.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto del cupón.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Comisión aplicada a la operación del cupón.</td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* No es necesario completar todos los filtros para realizar una búsqueda.
* Cuando `Resumen por Proveedor` está desmarcado, se puede utilizar los filtros `Ordenar por` y `Orden`.

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="109">Versión</th><th width="133">Fecha</th><th width="146">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2025-08-26</td><td>Ronald Peláez</td><td>Documento inicial del manual</td></tr></tbody></table>

</details>
