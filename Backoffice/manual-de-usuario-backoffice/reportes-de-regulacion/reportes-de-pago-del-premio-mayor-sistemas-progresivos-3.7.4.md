# Reportes de Pago del Premio Mayor (Sistemas Progresivos) (3.7.4)

<mark style="color:$info;">Este reporte permite visualizar los pagos realizados a los jugadores que han obtenido el premio mayor en casino, ofreciendo un desglose detallado de la información asociada a cada premio otorgado dentro del periodo de consulta.</mark>

{% hint style="warning" %}
**Nota:** El acceso al módulo requiere permisos específicos; en caso de no contar con ellos, el reporte no será visible.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Reportes de regulación > Reportes de Pago del Premio Mayor (Sistemas Progresivos) (3.7.4)

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (297).png" alt=""><figcaption><p>figura#1: Captura de pantalla reportes de Pago del Premio Mayor (Sistemas Progresivos).</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="118.54541015625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reportes-de-pago-del-premio-mayor-sistemas-progresivos-3.7.4.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar la información del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="reportes-de-pago-del-premio-mayor-sistemas-progresivos-3.7.4.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los pagos de premios mayores en la tabla de resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="198.00006103515625">Campo</th><th width="122">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar un día o un rango de fechas en las que se registraron premios.</td></tr><tr><td><strong><code>ID del jugador</code></strong></td><td>Numérico</td><td>Indica el código único asignado al usuario dentro de la plataforma.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de identificación del jugador <em>(DNI, cédula de extranjería, pasaporte)</em>.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Campo de texto</td><td>Corresponde al número de identificación del jugador, utilizado para verificar su identidad.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Campo de texto</td><td>Filtra por el nombre completo del usuario registrado en la plataforma.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con la información correspondiente a los premios mayores pagados según los filtros aplicados.

<table><thead><tr><th width="248.5">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Día en el que se registró el pago del premio.</td></tr><tr><td><strong><code>Identificación única</code></strong></td><td>Código único asignado a la transacción del premio.</td></tr><tr><td><strong><code>Identificación del jugador ganador</code></strong></td><td>Código único que identifica al usuario que recibió el premio.</td></tr><tr><td><strong><code>Nombre del jugador</code></strong></td><td>Nombre completo del usuario que obtuvo el premio.</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Tipo de identificación del jugador <em>(DNI, cédula de extranjería, pasaporte)</em>.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Número de identificación personal del jugador.</td></tr><tr><td><strong><code>Nombre del juego</code></strong></td><td>Título del juego en el que se otorgó el premio mayor.</td></tr><tr><td><strong><code>Monto total ganado</code></strong></td><td>Cantidad exacta de dinero recibida por el jugador.</td></tr><tr><td><strong><code>Modalidad de sistema progresivo</code></strong></td><td><p>Indica el tipo de sistema progresivo en el que se generó el premio.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Un sistema progresivo es un premio que crece de forma acumulada: una parte de cada apuesta se suma al pozo hasta que un jugador lo gana.</p></div></td></tr><tr><td><strong><code>Fecha y hora</code></strong></td><td>Momento exacto en el que se efectuó el pago del premio.</td></tr><tr><td><strong><code>Monto inicial del sistema progresivo</code></strong></td><td>Valor inicial del premio progresivo antes de acumularse.</td></tr><tr><td><strong><code>Fecha de inicio del sistema progresivo</code></strong></td><td>Día en que comenzó a generarse la acumulación del premio progresivo.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio:

* El acceso al módulo requiere permisos específicos; de lo contrario, el reporte no será visible en el sistema.
* Es obligatorio seleccionar un periodo de fechas para ejecutar la consulta.
* La información mostrada corresponde únicamente a los pagos de premios mayores de los sistemas progresivos de casino.
* Cada registro corresponde a un premio mayor efectivamente pagado dentro del periodo consultado.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/06/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
