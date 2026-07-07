---
description: >-
  Este reporte permite consultar todas las transacciones realizadas por cada
  jugador en apuestas deportivas de manera total.
---

# Reporte transacciones realizadas por cada jugador (Deportivas) (8.7.7) Primer nivel

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes de regulación > Reporte transacciones realizadas por cada jugador (Deportivas) (8.7.7)

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (319).png" alt=""><figcaption><p>Figura#1: Captura de pantalla reporte transacciones realizadas por cada jugador.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-transacciones-realizadas-por-cada-jugador-deportivas-8.7.7-primer-nivel.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-transacciones-realizadas-por-cada-jugador-deportivas-8.7.7-primer-nivel.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las transacciones en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el periodo de consulta indicando una fecha de inicio y una fecha de fin.</td></tr><tr><td><strong><code>ID del jugador</code></strong></td><td>Numérico</td><td>Indica el código único asignado a cada jugador dentro de la plataforma.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de documento de identidad del jugador <em>(DNI, pasaporte, etc.)</em>.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Campo de texto</td><td>Corresponde al número del documento de identidad del jugador, utilizado para verificar su identidad dentro del sistema.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre completo del usuario registrado en la plataforma.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con la información de las transacciones según los filtros aplicados.

<table><thead><tr><th width="191.46295166015625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en la que se registró la transacción.</td></tr><tr><td><strong><code>Identificador único de la transacción</code></strong></td><td>Código único asignado a cada transacción.</td></tr><tr><td><strong><code>Identificador único del jugador</code></strong></td><td>Código único asignado a cada jugador.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Nombre completo del usuario.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Tipo de documento de identidad del jugador <em>(DNI, pasaporte, etc.)</em>.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Número del documento de identificación del jugador.</td></tr><tr><td><strong><code>Estado de la apuesta</code></strong></td><td>Indica el estado actual de la apuesta. Puede ser:</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="121.40740966796875">Estado</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Abierta</strong></td><td>La apuesta aún no ha sido resuelta y permanece a la espera del resultado del evento.</td></tr><tr><td><strong>Ganadora</strong></td><td>La apuesta acertó el resultado y genera un premio para el jugador.</td></tr><tr><td><strong>Perdida</strong></td><td>La apuesta no acertó el resultado, por lo que no genera premio.</td></tr><tr><td><strong>Anulada</strong></td><td>La apuesta fue invalidada y el monto apostado se reintegra al jugador.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="196.648193359375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Apuesta</code></strong></td><td>Monto total apostado, incluyendo bonificaciones si aplica.</td></tr><tr><td><strong><code>Premio</code></strong></td><td>Monto total de los premios pagados, considerando posibles bonificaciones o premios adicionales.</td></tr><tr><td><strong><code>Cuota</code></strong></td><td><p>Valor que determina el pago potencial de la apuesta.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La cuota actúa como un multiplicador del monto apostado: a mayor cuota, mayor es el premio potencial.</p></div></td></tr><tr><td><strong><code>Cantidad de selecciones</code></strong></td><td>Número total de eventos combinados en la apuesta.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Indica si la apuesta fue realizada antes del evento <em>(prematch)</em> o en vivo <em>(live)</em>.</td></tr><tr><td><strong><code>Fecha de ticket</code></strong></td><td>Fecha y hora en que se generó la apuesta.</td></tr><tr><td><strong><code>Fecha de cálculo</code></strong></td><td>Fecha y hora en que la apuesta alcanzó su estado final <em>(ganada, perdida, cashout, etc.)</em>.</td></tr><tr><td><strong><code>Lugar de transacción</code></strong></td><td>Juego donde se realizó la transacción.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* Es obligatorio seleccionar un periodo de fechas para ejecutar la consulta.
* El reporte consolida la totalidad de las transacciones realizadas por cada jugador en apuestas deportivas.
* Cada registro detalla la apuesta, su estado, los montos asociados y el lugar de la transacción.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
