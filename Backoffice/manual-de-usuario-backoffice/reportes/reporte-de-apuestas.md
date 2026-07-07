---
description: >-
  El Reporte de Apuestas permite consultar, analizar y realizar un seguimiento
  detallado de las apuestas registradas en el sistema, incluyendo información
  sobre estados, premios y detalles financieros.
---

# Reporte de Apuestas

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Reporte de Apuestas

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (563).png" alt=""><figcaption><p>Figura#1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="127.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-apuestas.md#id-4.-filtros-principales"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="reporte-de-apuestas.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. **Filtros principales**

<table><thead><tr><th width="150">Campo</th><th width="160">Tipo de Control</th><th width="431.111083984375">Descripción</th></tr></thead><tbody><tr><td><p><strong><code>Fecha de</code></strong> </p><p><strong><code>Creación</code></strong></p></td><td>Calendario</td><td>Rango de fechas en que se crearon las apuestas.</td></tr><tr><td><p><strong><code>Fecha de</code></strong> </p><p><strong><code>Expiración</code></strong></p></td><td>Calendario</td><td>Filtra apuestas según fecha de expiración.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País donde se registraron las apuestas.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Estado de la apuesta <em>(abierta, cerrada, anulada).</em></td></tr><tr><td><strong><code>Usuario ID</code></strong></td><td>Numérico</td><td>Identificador único del usuario.</td></tr><tr><td><strong><code>Ticket ID</code></strong></td><td>Numérico</td><td>Identificador del ticket de la apuesta.</td></tr><tr><td><strong><code>ID Cliente</code></strong></td><td>Numérico</td><td>Identificador del cliente que realizó la apuesta.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Campo de texto</td><td>Dirección IP desde la que se realizó la apuesta.</td></tr><tr><td><strong><code>Tipo de Apuesta</code></strong></td><td>Lista desplegable</td><td>Clasifica las apuestas que traerá el reporte <em>(simples, combinadas, sistemáticas.)</em></td></tr><tr><td><strong><code>Ordenar por</code></strong></td><td>Lista desplegable</td><td>Ordena por fecha, valor, estado.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Lista desplegable</td><td>Ascendente o descendente.</td></tr><tr><td><p><strong><code>Tipo de</code></strong> </p><p><a href="https://virtualsoft.gitbook.io/untitled/glosario/#billetera"><strong><code>Billetera</code></strong></a></p></td><td>Lista desplegable</td><td>Selecciona entre billeteras disponibles <em>(Online o Quisk).</em></td></tr><tr><td><strong><code>Resumido</code></strong></td><td>Casilla de verificación</td><td>Si está activo, el filtro "Tipo de Apuesta" se reemplaza por "<strong>Tipo para Premios</strong>".</td></tr><tr><td><strong><code>Tipo de Usuario</code></strong></td><td>Lista desplegable</td><td>Selecciona entre Usuario Final o Punto de Venta o todos.</td></tr><tr><td><strong><code>Con Eliminadas?</code></strong></td><td>Casilla de verificación</td><td>Incluye apuestas eliminadas en la consulta.</td></tr></tbody></table>

#### **4.1. Filtros avanzados**

<table><thead><tr><th width="180">Campo</th><th width="160">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Premio Total Mínimo</code></strong></td><td>Numérico</td><td>Valor mínimo de premios totales a consultar.</td></tr><tr><td><strong><code>Premio Total Máximo</code></strong></td><td>Numérico</td><td>Valor máximo de premios totales a consultar.</td></tr></tbody></table>

### **5. Resultados de consulta**

<table><thead><tr><th width="260">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha Creación</code></strong></td><td>Fecha y hora de registro de la apuesta.</td></tr><tr><td><strong><code>Ticket ID</code></strong></td><td>Número único que identifica el ticket.</td></tr><tr><td><strong><code>Tipo de Apuesta</code></strong></td><td>Clasificación de la apuesta registrada.</td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Identificación del punto de venta asociado.</td></tr><tr><td><strong><code>Fecha de Pago</code></strong></td><td>Fecha del pago de la apuesta.</td></tr><tr><td><strong><code>Punto Venta Pagó</code></strong></td><td>Punto de venta que procesó el pago.</td></tr><tr><td><strong><code>Cajero</code></strong></td><td>Identificación del cajero que gestionó la transacción.</td></tr><tr><td><strong><code>Usuario ID</code></strong></td><td>Identificación única del usuario que realizó la apuesta.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Nombre del usuario asociado a la apuesta.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual de la apuesta.</td></tr><tr><td><strong><code>Fecha Cierre</code></strong></td><td>Fecha en que se cerró la apuesta.</td></tr><tr><td><strong><code>Beneficiario ID</code></strong></td><td>Identificación del beneficiario en caso de premio.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto total apostado.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Monto total de premios entregados.</td></tr><tr><td><strong><code>Impuesto Premios</code></strong></td><td>Impuestos aplicados a los premios.</td></tr><tr><td><strong><code>Impuesto Apuesta</code></strong></td><td>Impuestos asociados a la apuesta realizada.</td></tr><tr><td><strong><code>Premio Total</code></strong></td><td>Valor total del premio después de impuestos.</td></tr><tr><td><strong><code>Odds</code></strong></td><td>Cuota registrada en la apuesta.</td></tr><tr><td><strong><code>IP</code></strong></td><td>Dirección IP desde donde se realizó la apuesta.</td></tr><tr><td><strong><code>Billetera</code></strong></td><td>Billetera utilizada en la transacción (Online o Quisk).</td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* No es necesario completar todos los filtros para realizar una búsqueda.
* Si se selecciona **Resumido**, el filtro **Tipo de Apuesta** será reemplazado por **Tipo para Premios**.

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="107">Versión</th><th width="139">Fecha</th><th width="157">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/08/2025</td><td>Ronald Peláez</td><td>Documento inicial del manual</td></tr></tbody></table>

</details>
