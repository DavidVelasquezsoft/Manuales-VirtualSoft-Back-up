# Reporte declaración de impuestos

<mark style="color:$info;">Administra los porcentajes con los que se distribuyen los valores de Apuestas y Premios entre Deportivas y Casino para la operación. Permitiendo consultar y actualizar directamente por período mensual, y el resultado alimenta a los reportes de regulación.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes de regulación > Reporte declaración de impuestos

{% hint style="warning" %}
**Nota:** El acceso a esta sección se controla con dos permisos independientes: uno habilita la **visualización** del módulo y otro la **creación y edición** de configuraciones. Un usuario con el permiso de consulta visualiza los registros pero no puede modificarlos.
{% endhint %}

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (729).png" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte declaración de impuestos</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-declaracion-de-impuestos.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar las configuraciones registradas.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporte-declaracion-de-impuestos.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra las configuraciones en la tabla de resultados.</td></tr><tr><td><a href="reporte-declaracion-de-impuestos.md#id-6.-configuracion-de-porcentajes"><strong>Crear</strong></a></td><td>Despliega el formulario para registrar la configuración de porcentajes de un período.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Las acciones **Crear** y **Editar** se habilitan únicamente para los usuarios que cuenten con el permiso de edición.
{% endhint %}

***

### 4. Filtros

<table><thead><tr><th width="152">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Consulta el mes en específico que se va revisar la configuración de porcentajes.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta se despliega la configuración registrada para el período. El sistema registra un **total de dinero apostado** y un **total de dinero pagado en premios**; estos porcentajes definen qué parte de cada total corresponde a **deportivas** y qué parte a **casino**. Por eso funcionan en dos pares, y cada par suma siempre el **100%**.

<table><thead><tr><th width="200.75">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Editar</code></strong> <i class="fa-pencil">:pencil:</i></td><td>Despliega el <a href="reporte-declaracion-de-impuestos.md#id-6.-configuracion-de-porcentajes">formulario de configuración</a> con los porcentajes registrados para el período, permitiendo modificarlos.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único de la configuración de porcentajes registrada.</td></tr><tr><td><strong><code>Apuestas Deportivas</code></strong></td><td><p>Porcentaje del dinero total apostado que se registra como apuestas de <strong>deportivas</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Con un <strong>60%</strong> configurado, de cada 100 apostados en el período se registran <strong>60</strong> como apuestas de deportivas y los <strong>40</strong> restantes como apuestas de casino.</p></div></td></tr><tr><td><strong><code>Apuestas Casino</code></strong></td><td>Porcentaje del dinero total apostado que se registra como apuestas de <strong>casino</strong>.</td></tr><tr><td><strong><code>Premios Deportivas</code></strong></td><td>Porcentaje del dinero total pagado en premios que se registra como premios de <strong>deportivas</strong>.</td></tr><tr><td><strong><code>Premios Casino</code></strong></td><td>Porcentaje del dinero total pagado en premios que se registra como premios de <strong>casino</strong>.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Cada período mensual admite **una sola configuración vigente**, por lo que la consulta devuelve un único registro por mes. Las configuraciones anteriores no se eliminan: se conservan en el historial de&#x20;

modificaciones para mantener la trazabilidad.
{% endhint %}

***

### 6. Configuración de porcentajes

Mediante el botón **Crear**, o la acción **Editar** de un registro existente, se despliega una ventana emergente con el formulario de porcentajes del período.

Los valores monetarios sobre los que se aplica la distribución provienen del [**Historial de Saldo**](../reportes/historico-de-saldos.md): el total de **Apuestas** y el total de **Retiros Pagados**. Los porcentajes configurados determinan qué proporción de cada uno corresponde a deportivas y cuál a casino.

<table><thead><tr><th width="212">Campo</th><th width="140">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Período mensual al que aplica la configuración.</td></tr><tr><td><strong><code>Apuestas Deportivas (%)</code></strong></td><td>Campo numérico</td><td><p>Porcentaje del total apostado que se asigna a la vertical de deportivas.</p><p><strong>Fórmula:</strong><br><em>Apuestas Deportivas = Apuestas × % Apuestas Deportivas</em></p></td></tr><tr><td><strong><code>Apuestas Casino (%)</code></strong></td><td>Campo numérico</td><td><p>Porcentaje del total apostado que se asigna a la vertical de casino.</p><p><strong>Fórmula:</strong><br><em>Apuestas Casino = Apuestas × % Apuestas Casino</em></p></td></tr><tr><td><strong><code>Premios Deportivas (%)</code></strong></td><td>Campo numérico</td><td><p>Porcentaje del total pagado en premios que se asigna a la vertical de deportivas.</p><p><strong>Fórmula:</strong><br><em>Premios Deportivas = Retiros Pagados × % Premios Deportivas</em></p></td></tr><tr><td><strong><code>Premios Casino (%)</code></strong></td><td>Campo numérico</td><td><p>Porcentaje del total pagado en premios que se asigna a la vertical de casino.</p><p><strong>Fórmula:</strong><br><em>Premios Casino = Retiros Pagados × % Premios Casino</em></p></td></tr></tbody></table>

{% hint style="danger" %}
**Importante:** Los porcentajes deben sumar exactamente **100%** en cada par, considerando los dos decimales configurados:

* **`Apuestas Deportivas (%)`** + **`Apuestas Casino (%)`** = 100,00%
* **`Premios Deportivas (%)`** + **`Premios Casino (%)`** = 100,00%

Si alguna de las dos sumas no corresponde al 100%, la plataforma no permite guardar la configuración.
{% endhint %}

{% hint style="warning" %}
**Nota:** Al guardar la configuración, los valores recalculados se reflejan en el siguiente orden dentro de la reportería regulatoria:

[**Reporte de Ingresos Consolidados Doradobet**](../reportes/reporte-de-ingresos-consolidados-doradobet.md) → **Reportes de regulación del BackOffice** _(_[_Reporte de los ingresos consolidados del titular (Deportivas) 8.7.3_](reporte-de-los-ingresos-consolidados-del-titular-deportivas-8.7.3.md) _y_ [_Reporte de los ingresos consolidados del titular 3.7.3_](reporte-de-los-ingresos-consolidados-del-titular-3.7.3.md)_)_ → **Reporte diario enviado a MINCETUR**.

La actualización conserva los tiempos de procesamiento ya configurados para esos reportes, por lo que los nuevos valores no se reflejan de forma inmediata.
{% endhint %}

***

### 7. Validaciones y reglas del negocio:

* El acceso a la sección requiere el permiso de visualización; la creación y la edición de configuraciones requieren un permiso independiente.
* Los porcentajes se configuran por **período mensual** _(mes y año)_ y solo puede existir una configuración vigente por período.
* La suma de **`Apuestas Deportivas (%)`** y **`Apuestas Casino (%)`** debe ser exactamente **100%**.
* La suma de **`Premios Deportivas (%)`** y **`Premios Casino (%)`** debe ser exactamente **100%**.
* Los porcentajes admiten hasta **dos decimales**, y la validación del 100% se realiza considerando esos dos decimales.
* Si alguna de las dos sumas no corresponde al 100%, la configuración no se guarda.
* La configuración de un período no modifica los porcentajes ni los resultados de otros períodos.
* Los valores base de la distribución provienen del **Historial de Saldo**: las apuestas se distribuyen sobre el total de **Apuestas** y los premios sobre el total de **Retiros Pagados**.
* La configuración afecta únicamente la reportería regulatoria del alcance definido: el Reporte de Ingresos Consolidados Doradobet, los reportes de regulación del BackOffice y el reporte diario enviado a MINCETUR. No modifica ningún otro reporte de la plataforma.
* Cada cambio queda registrado con el período modificado, el campo afectado, el porcentaje anterior, el porcentaje nuevo, el usuario que realizó la modificación y la fecha y hora.
* Las configuraciones anteriores no se reemplazan ni se eliminan: se conservan para mantener la trazabilidad completa de los cambios.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>20/10/2026</td><td>David Velasquez</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-34571">Documento inicial</a></td></tr></tbody></table>

</details>
