---
description: >-
  Este reporte permite consultar las transferencias de saldo recibidas aplicando
  uno o más filtros. Es importante destacar que ninguno de los filtros es
  obligatorio.
---

# Reporte de transferencias de saldo Recibidas

#### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Transferencias de Saldo Recibidas

***

#### 2. Visualización

<figure><img src="../../.gitbook/assets/image (600).png" alt=""><figcaption><p>Figura #1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

#### 3. Funcionalidades

<table><thead><tr><th width="163">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td>Filtrar transferencias</td><td>Permite aplicar filtros de búsqueda por usuario, fecha, concesionario, país o tipo de reporte.</td></tr><tr><td>Visualizar tabla de resultados</td><td>Presenta la información de las transferencias según los filtros aplicados.</td></tr><tr><td>Exportar los resultados</td><td>Permite exportar en formato Excel los resultados de las transferencias recibidas según los filtros seleccionados.</td></tr></tbody></table>

**🔎 3.1 Filtros principales**

<table><thead><tr><th width="107">Campo</th><th width="122">Tipo de Control</th><th width="484">Descripción</th></tr></thead><tbody><tr><td><code>ID Usuario</code></td><td>Texto</td><td>Identificador único del usuario que recibió la transferencia.</td></tr><tr><td><code>Nombre del Usuario</code></td><td>Texto</td><td>Permite buscar por el nombre del usuario receptor de la transferencia.</td></tr><tr><td><code>Fecha</code></td><td>Calendario</td><td>Filtra las transferencias realizadas dentro de un rango de fechas específico.</td></tr><tr><td><code>ID Concesionario</code></td><td>Texto</td><td>Identificador del concesionario asociado a la transferencia.</td></tr><tr><td><code>Subconcesionario</code></td><td>Texto</td><td>Permite filtrar por el subconcesionario relacionado con la transferencia.</td></tr><tr><td><code>País</code></td><td>Lista desplegable</td><td>Selecciona el país donde se efectuó la transferencia.</td></tr><tr><td><code>Tipo de Usuario</code></td><td>Lista desplegable</td><td>Clasifica al usuario según su perfil o rol dentro del sistema.</td></tr><tr><td><code>Tipo</code></td><td>Lista desplegable</td><td><p>Define de qué forma se visualizará el reporte.</p><ul><li><strong>Detallado</strong>: Reporte con información <a href="reporte-de-transferencias-de-saldo-recibidas.md#detallado">detallada</a>.</li><li><strong>Totales</strong>: Reporte con información <a href="reporte-de-transferencias-de-saldo-recibidas.md#totales">total</a>.</li></ul></td></tr><tr><td><code>Asignado Por</code></td><td>Texto</td><td>Permite buscar las transferencias realizadas por el usuario que asignó el saldo.</td></tr><tr><td><code>Id transacción</code></td><td>Texto</td><td>Id asociado a la transacción que se va a consultar.</td></tr></tbody></table>

**📊 Tabla de Resultados**\
Los resultados de la consulta se presentan en una tabla con las siguientes columnas:

{% tabs %}
{% tab title="Detallado" %}
El resultado de la consulta cuando sea tipo detallado tendrá una tabla con las siguientes columnas:

<table><thead><tr><th width="201">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Número único que identifica cada transferencia de saldo.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha y hora en que se realizó la transferencia.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario receptor de la transferencia.</td></tr><tr><td><strong><code>Nombre del Usuario</code></strong></td><td>Nombre del usuario que recibió el saldo.</td></tr><tr><td><strong><code>Tipo Cupo</code></strong></td><td>Clasificación del cupo transferido <em>(por ejemplo: recarga, juego, etc.).</em></td></tr><tr><td><strong><code>Tipo Transacción</code></strong></td><td>Tipo de transacción realizada <em>(por ejemplo: entrada, salida, etc.).</em></td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto total transferido en la transacción.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Tipo de moneda utilizada en la transferencia.</td></tr><tr><td><strong><code>Información de banco</code></strong></td><td>Información del banco con el que se generó la transacción.</td></tr><tr><td><strong><code>Id transacción</code></strong></td><td>Id de la transacción realizada.</td></tr></tbody></table>
{% endtab %}

{% tab title="Totales" %}

{% endtab %}
{% endtabs %}

<table><thead><tr><th width="155">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Asignado por</code></strong> </td><td></td></tr><tr><td><strong><code>Fecha</code></strong></td><td></td></tr><tr><td><strong><code>Tipo cupo</code></strong></td><td></td></tr><tr><td><strong><code>Tipo transacción</code></strong></td><td></td></tr><tr><td><strong><code>Valor</code></strong></td><td></td></tr><tr><td><strong><code>Moneda</code></strong></td><td></td></tr></tbody></table>

***

**4. Validaciones y Reglas de Negocio**

* No es obligatorio completar todos los filtros para realizar una búsqueda.
* La información mostrada dependerá de los filtros seleccionados en la consulta.
* Solo los usuarios con permisos adecuados pueden acceder o exportar los datos.

***

**5. Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 08/10/2025 | Ronald Peláez | Documento inicial  |
