---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# Usuarios Afiliados al regalo

<mark style="color:$info;">Consolida la información de los usuarios que han redimido los premios asociados a un regalo específico. Desde esta vista es posible consultar indicadores clave</mark> <mark style="color:$info;"></mark>_<mark style="color:$info;">(KPIs),</mark>_ <mark style="color:$info;"></mark><mark style="color:$info;">realizar búsquedas mediante filtros y visualizar el detalle de los registros correspondientes a cada redención.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso:** BackOffice > Torneos y bonos > Menú lateral > Regalos > 🔍

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (298).png" alt=""><figcaption><p>Figura #1: Captura de pantalla información de regalos.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="121">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="usuarios-afiliados-al-regalo.md#id-5.-filtros"><strong>Filtros</strong></a></td><td>Realiza búsquedas específicas utilizando diferentes criterios de consulta.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados y muestra nuevamente todos los registros disponibles.</td></tr><tr><td><strong>Buscar</strong></td><td>Ejecuta la consulta utilizando los criterios de búsqueda seleccionados.</td></tr></tbody></table>

***

### 4. KPIs

En la parte superior de la pantalla se presentan indicadores que muestran información consolidada del regalo seleccionado.

{% hint style="warning" %}
**Nota:** Los KPIs se actualizan automáticamente de acuerdo con los filtros aplicados en la consulta.
{% endhint %}

<table><thead><tr><th width="283">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total regalos</code></strong></td><td>Cantidad total de regalos asociados al registro seleccionado.</td></tr><tr><td><strong><code>Cantidad de regalos redimidos</code></strong></td><td>Total de regalos redimidos por los usuarios.</td></tr><tr><td><strong><code>Cantidad de bonos entregados mediante regalos</code></strong></td><td>Total de bonos entregados mediante el regalo seleccionado.</td></tr></tbody></table>

***

### 5. Filtros

Los filtros permiten consultar la información de los usuarios afiliados al regalo utilizando diferentes criterios de búsqueda.

<table><thead><tr><th width="163">Campo</th><th width="143">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único del premio.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador del usuario que redimió el regalo.</td></tr><tr><td><strong><code>ID Casino</code></strong></td><td>Numérico</td><td>Identificador del casino mediante el cual se obtuvo el premio.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Estado actual del premio <em>(Comprado o Entregado).</em></td></tr><tr><td><strong><code>Fecha Inicial</code></strong></td><td>Selector de fecha</td><td>Fecha de inicio de la vigencia del regalo</td></tr><tr><td><strong><code>Fecha Final</code></strong></td><td>Selector de fecha</td><td>Fecha de finalización de la vigencia del regalo</td></tr><tr><td><strong><code>Fecha Modificó Inicial</code></strong></td><td>Selector de fecha</td><td>Fecha inicial correspondiente a la última modificación del registro.</td></tr><tr><td><strong><code>Fecha Modificó Final</code></strong></td><td>Selector de fecha</td><td>Fecha final correspondiente a la última modificación del registro.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Tipo de premio <em>(Físico u Online).</em></td></tr></tbody></table>

***

### 6. Tabla de información

Listado de usuarios afiliados al regalo seleccionado. Inicialmente se muestran todos los registros disponibles; al aplicar filtros, únicamente se visualizarán aquellos que cumplan con los criterios de búsqueda establecidos.

<table><thead><tr><th width="247">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del premio.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha de creación del registro.</td></tr><tr><td><strong><code>Fecha modificó</code></strong></td><td>Fecha de la última modificación realizada sobre el registro.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador del usuario que redimió el premio.</td></tr><tr><td><strong><code>ID Casino</code></strong></td><td>Identificador de casino mediante el cual se obtuvo el premio.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado del premio <em>(Entregado, Comprado).</em></td></tr><tr><td><strong><code>Descripción premio</code></strong></td><td>Descripción del premio entregado.</td></tr><tr><td><strong><code>Tipo premio</code></strong></td><td>Tipo de premio asociado al registro.</td></tr><tr><td><strong><code>Observación</code></strong></td><td>Información adicional registrada sobre el premio.</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio

* Los KPIs se actualizan automáticamente según los filtros aplicados en la consulta.
* Los filtros **Fecha Inicial** y **Fecha Final** permiten consultar los registros dentro del rango de fechas seleccionado.
* El filtro **Tipo** permite consultar registros correspondientes a premios **Físicos** u **Online**.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="110">Versión</th><th width="134">Fecha</th><th width="123">Autor</th><th>Cambios realizados</th></tr></thead><tbody><tr><td><strong>1.0</strong></td><td>09/07/2026</td><td>Karol Navia</td><td>Reestructuración del manual</td></tr></tbody></table>

</details>
