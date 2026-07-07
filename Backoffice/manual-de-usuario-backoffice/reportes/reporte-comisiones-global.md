---
description: >-
  El Reporte Comisiones Global permite consultar información detallada sobre las
  comisiones generadas por puntos de venta.
---

# Reporte Comisiones Global

### 1. Acceso al Módulo

**Ruta de acceso:** BackOffice > Reportes > Reporte Comisiones global

### 2. visualización:

<figure><img src="../../.gitbook/assets/image (599).png" alt=""><figcaption><p>Figura#1: Captura de pantalla reporte comisiones globales.</p></figcaption></figure>

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-comisiones-global.md#id-4.-filtros-de-busqueda"><strong>Filtros</strong></a></td><td>Permite definir el rango de fechas y el país para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-comisiones-global.md#id-5.-resultado-de-la-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra la información consolidada en la tabla.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite descargar el reporte en formato Excel mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4.  Filtros de búsqueda

<table><thead><tr><th width="172">Campo</th><th width="159">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Permite seleccionar el rango de fechas a consultar.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Especifica el tipo de reporte que se desea visualizar. <em>(Mensual, Diario)</em></td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Lista desplegable</td><td>Filtra los datos de un punto de venta específico.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el país o región a consultar.</td></tr><tr><td><strong><code>Agrupado solo por afiliador</code></strong></td><td>Interruptor </td><td>Determina si los resultados deben agruparse por usuario afiliador.</td></tr><tr><td><strong><code>Ver solo por punto de venta</code></strong></td><td>Interruptor </td><td>Muestra únicamente los registros asociados a puntos de venta.</td></tr><tr><td><strong><code>Mi comisión</code></strong></td><td>Interruptor</td><td>Filtra para mostrar solo las comisiones correspondientes al usuario actual.</td></tr></tbody></table>

***

### 5. Resultado de la Consulta

Una vez aplicados los filtros y realizada la consulta, se mostrará una tabla con las siguientes columnas:

<table><thead><tr><th width="186">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>TypeName</code></strong></td><td>Hace referencia al tipo de la comisión que fue realizada</td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del registro del punto de venta.</td></tr><tr><td><strong><code>ID Afiliador</code></strong></td><td>Identificador del afiliador responsable.</td></tr><tr><td><strong><code>Nombre Afiliador</code></strong></td><td>Nombre del afiliador.</td></tr><tr><td><strong><code>Usuario REF</code></strong></td><td>Es el identificador del usuario el cual realizo la apuesta.</td></tr><tr><td><strong><code>Nombre Usuario REF</code></strong></td><td>Nombre completo del usuario de referencia.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha en la que se generó la transacción.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda utilizada en la operación.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Monto total apostado.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Total de premios pagados.</td></tr><tr><td><strong><code>Bonos</code></strong></td><td>Total de bonos otorgados.</td></tr><tr><td><strong><code>Valor Base</code></strong></td><td>Base sobre la que se calcula la comisión <em>(GGR o NGR según país)</em>.</td></tr><tr><td><strong><code>Comisión</code></strong></td><td>Valor total de la comisión generada.</td></tr><tr><td><strong><code>Costo Plataforma</code></strong></td><td>Costos asociados al uso de la plataforma.</td></tr><tr><td><strong><code>Valor Pagado</code></strong></td><td>Valor final pagado al afiliado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del registro.</td></tr><tr><td><strong><code>Modificado</code></strong></td><td>Indica si el registro ha sido editado.</td></tr></tbody></table>

***

### 6. Ajuste de Cálculo para Perú (Gangabet y Doradobet)

Para cumplir con la regulación peruana sobre apuestas deportivas, el sistema aplica una deducción del **12% en impuestos** al cálculo del Net Gaming Revenue (NGR).

#### ✍️ Detalle del cálculo:

| Paso                            | Fórmula                    | Ejemplo                        |
| ------------------------------- | -------------------------- | ------------------------------ |
| **NGR bruto**                   | Apuestas - Premios - Bonos | 1,000 - 800 - 50 = **150 PEN** |
| **Impuesto (12%) sobre NGR**    | NGR \* 0.12                | 150 \* 0.12 = **18 PEN**       |
| **NGR** Neto                    | NGR - Impuestos            | 150 - 18 = **132 PEN**         |
| **Comisión del Afiliado (25%)** | NGR Neto \* % Comisión     | 132 \* 0.25 = **33 PEN**       |

🔁 Este ajuste **solo aplica** a registros originados en **Gangabet Perú** y **Doradobet Perú**, únicamente dentro del **Backoffice**. No afecta a otros países ni otras vistas.

***

### 7. Validaciones y Reglas de Negocio

* El reporte **solo muestra transacciones que hayan generado comisión.**
* Si se activa el filtro “Ver solo por punto de venta”, el reporte mostrará exclusivamente información asociada al punto de venta seleccionado.
* Cuando el reporte es consultado desde el perfil de afiliado, el campo **"Valor Base"** se ajusta según la regulación fiscal de Perú si aplica.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="111.90911865234375">Versión</th><th width="151">Fecha</th><th width="135.54541015625">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>30/07/2025</td><td>Karol Navia</td><td>Documento inicial basado en estructura estándar.</td></tr><tr><td>1.1</td><td>14/10/2025</td><td>Ronald pelaez</td><td>Refinamiento manual</td></tr><tr><td>1.2</td><td>20/04/2026</td><td>Karol Navia</td><td>Refinamiento manual</td></tr></tbody></table>

</details>
