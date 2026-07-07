---
description: >-
  El Informe Gerencial permite analizar información clave relacionada con las
  apuestas, usuarios y métricas financieras.
---

# Informe Gerencial

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Informe Gerencial

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FdO5f5njwCEo84H3xRqV6%2Fimage.png?alt=media&#x26;token=33e6276e-5764-417b-901a-4b407396f60b" alt=""><figcaption><p>Figura#1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="127.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="informe-gerencial.md#id-4.-filtros-principales"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="informe-gerencial.md#id-5.resultados-de-consulta"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. **Filtros principales**

<table><thead><tr><th width="121">Campo</th><th width="166">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Selecciona el rango de fechas para el análisis.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra los datos por país de operación.</td></tr><tr><td><strong><code>Tipo de Apuesta</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar apuestas <strong>creadas (registradas)</strong> o <strong>cerradas (resueltas)</strong>.</td></tr><tr><td><strong><code>Tipo de Usuario</code></strong></td><td>Lista desplegable</td><td>Define si en el reporte se visualizarán <strong>Todos los usuarios</strong> o únicamente <strong>Puntos de Venta</strong>.</td></tr></tbody></table>

### **5. Resultados de consulta**

<table><thead><tr><th width="260">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se generó el reporte.</td></tr><tr><td><strong><code>Apuesta</code></strong></td><td>Suma total de las apuestas realizadas.</td></tr><tr><td><strong><code>Apuestas Live</code></strong></td><td>Monto apostado en eventos en vivo.</td></tr><tr><td><strong><code>Apuestas</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#prematch"><strong><code>PREMATCH</code></strong></a></td><td>Monto apostado antes del inicio de los eventos.</td></tr><tr><td><strong><code>Apuestas Mixtas</code></strong></td><td>Total de apuestas combinadas entre eventos en vivo y prematch.</td></tr><tr><td><strong><code>Apuesta Promedio</code></strong></td><td>Valor promedio de las apuestas realizadas por los usuarios.</td></tr><tr><td><strong><code>Apuestas</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#hipicas"><strong><code>HÍPICAS</code></strong></a></td><td>Monto total apostado en carreras de caballos. <em>(Nota: Hípicas se categoriza como PreLive, por lo que esta columna mostrará un valor de cero.)</em></td></tr><tr><td><strong><code>Apuestas VIRTUALES</code></strong></td><td>Total apostado en juegos y eventos virtuales.</td></tr><tr><td><strong><code>Impuesto Apuesta</code></strong></td><td>Total de impuestos aplicados sobre las apuestas.</td></tr><tr><td><strong><code>Retenciones Premios Deportivas</code></strong></td><td>Monto retenido sobre premios de apuestas deportivas.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Total de premios entregados a los usuarios.</td></tr><tr><td><strong><code>Premios Live</code></strong></td><td>Total de premios pagados en apuestas en vivo.</td></tr><tr><td><strong><code>Premios PREMATCH</code></strong></td><td>Total de premios pagados en apuestas prematch.</td></tr><tr><td><strong><code>Premios Mixtos</code></strong></td><td>Total de premios otorgados en apuestas mixtas.</td></tr><tr><td><strong><code>Premios HÍPICAS</code></strong></td><td>Premios pagados en apuestas hípicas.</td></tr><tr><td><strong><code>Premios VIRTUALES</code></strong></td><td>Total de premios otorgados en apuestas virtuales.</td></tr><tr><td><strong>Bonos</strong></td><td>Monto total de bonos utilizados o asignados a los usuarios.</td></tr><tr><td><strong><code>Bonos Proveedor</code></strong></td><td>Valor total de bonos ofrecidos por proveedores.</td></tr><tr><td><strong><code>GGR (Gross Gaming Revenue)</code></strong></td><td>Ganancia bruta obtenida de las apuestas calculada con la siguiente formula: <code>Apuestas - Premios - Bonos</code>.</td></tr><tr><td><strong><code>GGR Live</code></strong></td><td>Ganancia bruta generada en eventos en vivo.</td></tr><tr><td><strong><code>GGR PREMATCH</code></strong></td><td>Ganancia bruta generada en eventos deportivos previos.</td></tr><tr><td><strong><code>GGR Mixtos</code></strong></td><td>Resultado de apuestas combinadas.</td></tr><tr><td><strong><code>GGR HÍPICAS</code></strong></td><td>Ganancia bruta de apuestas hípicas (valor esperado 0).</td></tr><tr><td><strong><code>GGR VIRTUALES</code></strong></td><td>Ganancia bruta de juegos y eventos virtuales.</td></tr><tr><td><strong><code>GGR %</code></strong></td><td>Porcentaje de ganancia bruta calculado como <code>(GGR / Total de Apuestas) × 100</code>.</td></tr><tr><td><strong><code>Usuarios Registrados</code></strong></td><td>Total de usuarios registrados en el período.</td></tr><tr><td><strong><code>Primeros Depósitos</code></strong></td><td>Cantidad de usuarios que realizaron su primer depósito.</td></tr><tr><td><strong><code>Suma Total Premio Jackpot</code></strong></td><td>Monto acumulado de premios entregados por jackpots.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda en la que se registraron las operaciones <em>(USD, PEN, CLP, etc.).</em></td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* No es obligatorio configurar todos los filtros para generar el informe.
* Algunos campos del resultado pueden presentar valores en cero según la categoría seleccionada (ejemplo: **Apuestas HÍPICAS**).
* En la columna de **fecha** se generarán subcarpetas que dividen la información por país, dentro de esa subcarpeta se visualizarán las fechas correspondientes.

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="102">Versión</th><th width="127">Fecha</th><th width="151">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/08/2025</td><td>Ronald Peláez</td><td>Documento inicial del manual</td></tr></tbody></table>

</details>
