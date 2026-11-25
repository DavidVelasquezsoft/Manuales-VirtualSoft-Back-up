# Informe de apuestas de casino

<mark style="color:$info;">Permite visualizar el histórico de las apuestas realizadas por el usuario desde la sección de juegos de casino, con filtros por fechas para obtener el detalle de sus tickets de juego.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: Menú principal → Consultas → Informe de otras apuestas

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (163).png" alt=""><figcaption><p><strong>Figura #1</strong>: Captura de pantalla – Informe de otras apuestas</p></figcaption></figure>

***

### 3. Acciones del Usuario

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="informe-de-apuestas-de-casino.md#id-4.-filtros-de-busqueda"><strong>Filtros</strong></a></td><td>Definen el rango de fechas en el que se consulta el historial de apuestas de casino.</td></tr><tr><td><strong>Buscar</strong></td><td>Carga automáticamente la información correspondiente a las fechas seleccionadas. El resultado se muestra en la tabla ubicada en la parte inferior de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros de búsqueda

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th><th>Validaciones</th></tr></thead><tbody><tr><td><strong><code>Fecha Inicio</code></strong></td><td>Calendario</td><td>Fecha desde la cual se desea consultar el historial de apuestas de casino.</td><td>Campo obligatorio.</td></tr><tr><td><strong><code>Fecha Fin</code></strong></td><td>Calendario</td><td>Fecha hasta la cual se desea consultar el historial.</td><td>Campo obligatorio. No debe ser anterior a la fecha inicial.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Las validaciones pueden variar dependiendo del **partner**.
{% endhint %}

***

### 5. Validaciones y Reglas de Negocio

* Se deben ingresar ambas fechas para ejecutar la consulta.
* El sistema no cargará datos si no existen registros en el rango de fechas seleccionado.
* Las validaciones pueden estar sujetas a reglas específicas definidas por cada **partner**.

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/07/2025</td><td>Karol Navia</td><td>Documento inicial para informe de otras apuestas (casino)</td></tr><tr><td>1.1</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
