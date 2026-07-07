# TRM

<mark style="color:$info;">Esta sección permite consultar la</mark> [<mark style="color:$info;">TRM</mark>](https://virtualsoft.gitbook.io/plantillas/glosario#trm) <mark style="color:$info;">(Tasa Representativa del Mercado) configurada por país, es decir, las tasas de cambio de las distintas monedas frente a la moneda base de cada país. Estos valores se utilizan para la conversión de montos dentro de la plataforma de usuarios online.</mark>

{% hint style="warning" %}
**Nota:** La consulta se realiza según la configuración general del país definida en el BackOffice; dicha configuración determina el país sobre el cual se filtra la información.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Herramientas > Partner ajustes > TRM

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (690).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección TRM partner ajustes</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="trm.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Define el criterio de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="trm.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según el filtro definido y muestra la información de la TRM en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="132.0740966796875">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td><p>Selecciona el país sobre el cual se consultará la <a href="https://virtualsoft.gitbook.io/plantillas/glosario#trm">TRM</a>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El país disponible para la consulta depende de la configuración general definida en el BackOffice.</p></div></td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con la [TRM](https://virtualsoft.gitbook.io/plantillas/glosario#trm) correspondiente al país seleccionado. Se muestra un registro con el valor de cada moneda frente a la moneda base del país.

<table><thead><tr><th width="126.2779541015625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td>Al seleccionar la acción <strong>Editar (</strong><i class="fa-pencil">:pencil:</i><strong>)</strong> sobre un registro, se habilita un formulario que permite modificar las tasas de cambio de las monedas</td></tr></tbody></table>

{% columns %}
{% column width="16.666666666666664%" %}

{% endcolumn %}

{% column width="83.33333333333334%" %}
<table><thead><tr><th width="115.77783203125">Campo</th><th width="102">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>No editable</td><td>Identificador único del registro de <a href="https://virtualsoft.gitbook.io/plantillas/glosario#trm">TRM</a>. Se muestra solo como referencia.</td></tr><tr><td><strong><code>País</code></strong></td><td>No editable</td><td>País al que corresponde el registro. Se muestra solo como referencia.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>No editable</td><td>Moneda base del país, identificada por su código <em>(ejemplo: PEN, USD, COP)</em>. Se muestra solo como referencia.</td></tr><tr><td><strong><code>Monedas (USD, NIO, PEN, CLP, GTQ, JMD, MXN, BRL, CRC, GYD, VES, etc.)</code></strong></td><td>Numérico Editable</td><td>Permiten ingresar o actualizar la tasa de cambio de cada moneda frente a la moneda base del país.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Para que los cambios queden registrados en el Partner País, es necesario seleccionar el botón **Guardar**. El botón **Cancelar** descarta las modificaciones y cierra el formulario sin aplicar cambios.
{% endhint %}
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="121.83343505859375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id</code></strong></td><td>Identificador único del registro de TRM.</td></tr><tr><td><strong><code>País</code></strong></td><td>País al que corresponde la TRM consultada.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda base del país, identificada por su código <em>(ejemplo: PEN, USD, COP)</em>.</td></tr><tr><td><strong><code>Monedas (USD, NIO, MXN, PEN, BRL, CLP, CRC, GTQ, GYD, JMD, VES, etc.)</code></strong></td><td>Cada columna corresponde a una moneda y muestra su tasa de cambio frente a la moneda base del país consultado.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, no será visible en el sistema.
* La consulta se realiza según la configuración general del país definida en el BackOffice.
* Al consultar un país siempre se muestra un registro con la TRM de cada moneda disponible.
* Los campos Id, País y Moneda no son editables; únicamente se pueden modificar las tasas de cambio de las monedas.
* Para aplicar las modificaciones realizadas en la edición es obligatorio seleccionar el botón **Guardar**.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
