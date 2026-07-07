---
description: >-
  Este reporte permite consultar todas las transacciones realizadas por cada
  jugador en apuestas de casino, incluyendo depósitos, ajustes de saldo y
  créditos de bonificación.
---

# Reporte de las transacciones realizadas por cada jugador (3.7.6)

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes de regulación > Reporte de las transacciones realizadas por cada jugador (3.7.6)

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (320).png" alt=""><figcaption><p>Figura#1: Captura de pantalla reporte de las transacciones realizadas por cada jugador.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-las-transacciones-realizadas-por-cada-jugador-3.7.6.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-de-las-transacciones-realizadas-por-cada-jugador-3.7.6.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las transacciones en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el periodo de consulta indicando una fecha de inicio y una fecha de fin.</td></tr><tr><td><strong><code>ID del jugador</code></strong></td><td>Numérico</td><td>Indica el código único asignado a cada jugador dentro de la plataforma para su identificación.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de documento de identidad del jugador <em>(DNI, pasaporte, cédula de identidad, etc.)</em>.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Campo de texto</td><td>Corresponde al número del documento de identidad del jugador, utilizado para verificar su identidad dentro del sistema.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre completo del usuario registrado en la plataforma.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con la información de las transacciones según los filtros aplicados.

<table><thead><tr><th width="192.20361328125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se registró la transacción.</td></tr><tr><td><strong><code>Identificador único del jugador</code></strong></td><td>Código único que identifica al jugador dentro del sistema.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Nombre completo del usuario.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Tipo de documento de identidad utilizado por el jugador.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Número del documento de identidad del jugador.</td></tr><tr><td><strong><code>Fecha de depósito</code></strong></td><td>Fecha y hora en que se realizó el depósito.</td></tr><tr><td><strong><code>Depósito</code></strong></td><td>Monto total depositado por el jugador.</td></tr><tr><td><strong><code>Medios de pago</code></strong></td><td>Método utilizado para realizar el depósito <em>(tarjeta de crédito, transferencia, etc.)</em>.</td></tr><tr><td><strong><code>Estado de depósito</code></strong></td><td>Indica el estado actual de la transacción de depósito. Puede ser:</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="121.40740966796875">Estado</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Pendiente</strong></td><td>El depósito fue registrado y está a la espera de confirmación.</td></tr><tr><td><strong>En proceso</strong></td><td>El depósito está siendo gestionado antes de su confirmación final.</td></tr><tr><td><strong>Aprobado</strong></td><td>El depósito fue confirmado y el saldo acreditado al jugador.</td></tr><tr><td><strong>Rechazado</strong></td><td>El depósito no fue aceptado, por lo que no se acreditó saldo al jugador.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="192.94439697265625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Créditos de bonificación</code></strong></td><td>Monto de bonificación otorgado al jugador.</td></tr><tr><td><strong><code>Ajuste de saldo</code></strong></td><td>Modificaciones en el saldo del jugador debido a ajustes realizados en la cuenta.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* Es obligatorio seleccionar un periodo de fechas para ejecutar la consulta.
* El reporte consolida las transacciones de casino realizadas por cada jugador, incluyendo depósitos, ajustes de saldo y créditos de bonificación.
* Cada registro detalla la transacción, el medio de pago utilizado y su estado.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
