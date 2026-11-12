# Reportería de Referidos

<mark style="color:$info;">Consulta la información del programa de referidos: cuántos usuarios ha invitado cada referente, cuáles de esos referidos cumplieron las condiciones que generan un premio y cuál ha sido su actividad en la plataforma. La consulta se presenta en dos vistas según el nivel de detalle que se requiera: una consolidada por referente y otra con el detalle de cada referido.</mark>

{% hint style="warning" %}
**Nota:** El **referente** es el usuario que envía la invitación, y el **referido** es la persona que se registra en la plataforma a través de ella. El referente obtiene premios cuando sus referidos cumplen las condiciones configuradas en el programa.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes > Reporte de Referidos

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FLrPwFfRxHmmUeUfYUaTA%2Fimage.png?alt=media&#x26;token=a3aaa3d8-f0c0-45fa-812c-99f3446bb457" alt=""><figcaption><p>Figura #1: Captura de pantalla Reporte de Referidos.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="164">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporteria-de-referidos.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información del programa de referidos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reporteria-de-referidos.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los registros en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="212">Campo</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Referente</code></strong></td><td>Campo de texto</td><td>Consulta la información de un referente específico mediante su identificador.</td></tr><tr><td><strong><code>Id Referido</code></strong></td><td>Campo de texto</td><td>Localiza a un referido puntual mediante su identificador.</td></tr><tr><td><strong><code>Fecha de Registro</code></strong></td><td>Calendario</td><td>Delimita los resultados según la fecha en la que el referido se registró en la plataforma.</td></tr><tr><td><strong><code>Fecha de Primer Depósito</code></strong></td><td>Calendario</td><td>Delimita los resultados según la fecha en la que el referido realizó su primer depósito.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Muestra únicamente los registros del país seleccionado.</td></tr><tr><td><strong><code>Estado de Referido</code></strong></td><td>Lista desplegable</td><td>Acota la consulta según si el referido conserva o no el acceso a la plataforma <em>(Activo o Inactivo)</em>.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td><p>Determina la vista con la que se presentan los resultados.</p><ul><li><strong>Totales:</strong> muestra el consolidado de cada referente y sus cifras de referidos y premios.</li><li><strong>Detallado:</strong> muestra el listado de referidos de un referente, con su actividad en la plataforma.</li></ul><div data-gb-custom-block data-tag="hint" data-style="danger" class="hint hint-danger"><p><strong>Importante:</strong> Para la vista <strong>Detallado</strong>, el campo <strong><code>Id Referente</code></strong> es <strong>obligatorio</strong>, ya que el reporte muestra los referidos de un referente en particular.</p></div></td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla cuyo contenido depende de la vista seleccionada en el filtro **`Tipo`**:

{% tabs %}
{% tab title="Totales" %}
Presenta una fila por cada referente, con el consolidado de sus referidos y de los premios generados.

<table><thead><tr><th width="212">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Referente</code></strong></td><td>Numérico</td><td>Identificador del usuario que envió las invitaciones.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre del referente.</td></tr><tr><td><strong><code>Referidos Totales</code></strong></td><td>Numérico</td><td>Cantidad de usuarios que completaron su registro en la plataforma utilizando el enlace enviado por el referente, ya sea por correo o compartido directamente.</td></tr><tr><td><strong><code>Referidos Exitosos</code></strong></td><td>Numérico</td><td>Cantidad de esos referidos que cumplieron alguna de las condiciones del programa y, por lo tanto, generaron al menos un premio para el referente.</td></tr><tr><td><strong><code>Bonos por Depósito</code></strong></td><td>Numérico</td><td>Total de bonos que el referente puede reclamar o ya reclamó porque sus referidos cumplieron la condición <strong>Mínimo primer depósito</strong>.</td></tr><tr><td><strong><code>Bonos por Apuesta</code></strong></td><td>Numérico</td><td>Total de bonos que el referente puede reclamar o ya reclamó porque sus referidos cumplieron la condición <strong>Mínimo valor en apuestas</strong>.</td></tr></tbody></table>

{% hint style="info" %}
**Nota:** La diferencia entre **`Referidos Totales`** y **`Referidos Exitosos`** indica cuántos usuarios se registraron pero aún no han cumplido ninguna condición del programa, por lo que todavía no generan premio para el referente.
{% endhint %}
{% endtab %}

{% tab title="Detallado" %}
Presenta una fila por cada referido del referente consultado, con su información de registro y su actividad en la plataforma.

<table><thead><tr><th width="244">Campo</th><th width="104">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Referido</code></strong></td><td>Numérico</td><td>Identificador del usuario referido.</td></tr><tr><td><strong><code>Fecha de Registro</code></strong></td><td>Fecha</td><td>Fecha y hora en la que el referido completó su registro en la plataforma.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre del referido tal como quedó registrado.</td></tr><tr><td><strong><code>Apellido</code></strong></td><td>Texto</td><td>Apellido del referido tal como quedó registrado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Indica si el referido conserva el acceso a la plataforma <em>(Activo)</em> o si lo perdió <em>(Desactivado)</em>.</td></tr><tr><td><strong><code>Último Login</code></strong></td><td>Fecha</td><td>Fecha del último inicio de sesión del referido.</td></tr><tr><td><strong><code>Referente</code></strong></td><td>Numérico</td><td>Identificador del referente que envió la invitación a este usuario.</td></tr><tr><td><strong><code>Primer Depósito</code></strong></td><td>Fecha</td><td>Fecha y hora en la que el referido realizó su primer depósito.</td></tr><tr><td><strong><code>Valor Primer Depósito</code></strong></td><td>Numérico</td><td>Monto del primer depósito realizado por el referido.</td></tr><tr><td><strong><code>Valor Apuestas Deportivas</code></strong></td><td>Numérico</td><td>Total apostado por el referido en la vertical de deportes.</td></tr><tr><td><strong><code>Última Apuesta Deportiva</code></strong></td><td>Fecha</td><td>Fecha de la última apuesta deportiva realizada por el referido.</td></tr><tr><td><strong><code>Valor Apuesta Casino</code></strong></td><td>Numérico</td><td>Total apostado por el referido en la vertical de casino.</td></tr><tr><td><strong><code>Última Apuesta Casino</code></strong></td><td>Fecha</td><td>Fecha de la última apuesta de casino realizada por el referido.</td></tr><tr><td><strong><code>Premio Primer Depósito</code></strong></td><td>Texto</td><td>Indica si el primer depósito de este referido generó un premio para el referente <em>(Generó premio o No ha generado premio)</em>.</td></tr><tr><td><strong><code>Premio Apuestas</code></strong></td><td>Texto</td><td>Indica si las apuestas de este referido generaron un premio para el referente <em>(Generó premio o No ha generado premio)</em>.</td></tr><tr><td><strong><code>Total Referidos</code></strong></td><td>Numérico</td><td>Cantidad de usuarios que este referido ha invitado a su vez. Un valor mayor a cero indica que el referido también actúa como referente dentro del programa.</td></tr></tbody></table>

{% hint style="info" %}
**Nota:** Los campos **`Valor Primer Depósito`**, **`Valor Apuestas Deportivas`** y **`Valor Apuesta Casino`** permiten verificar por qué un referido generó premio o no: son los valores que se comparan contra las condiciones configuradas en el programa.
{% endhint %}
{% endtab %}
{% endtabs %}

***

### 6. Validaciones y reglas del negocio:

* En la vista **Totales** no es obligatorio diligenciar ningún filtro: si no se define ninguno, la consulta devuelve todos los referentes registrados.
* En la vista **Detallado** el campo **`Id Referente`** es obligatorio, ya que el reporte muestra los referidos asociados a un referente en particular.
* Los resultados mostrados corresponden únicamente a los criterios seleccionados en los filtros.
* Un referido genera premio para su referente únicamente cuando cumple alguna de las condiciones configuradas en el programa: **Mínimo primer depósito** o **Mínimo valor en apuestas**.
* Un mismo referido puede generar los dos premios, uno solo o ninguno, según las condiciones que cumpla.
* Un usuario referido puede convertirse a su vez en referente e invitar a otros usuarios, lo que se refleja en el campo **`Total Referidos`**.
* El reporte es informativo: desde este módulo no es posible otorgar, reclamar ni anular los premios del programa.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21/08/2025</td><td>Karol Navia</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>19/10/2026</td><td>David Velasquez</td><td>Actualización de formato.</td></tr></tbody></table>

</details>
