# Reporte de limitaciones

Una **limitación** es un método de control para las apuestas. Estas limitaciones son generadas directamente por los usuarios desde la **plataforma de usuarios online**, con el fin de establecer restricciones personales sobre su actividad.\
En esta reportería se visualiza la información detallada de dichas limitaciones creadas, modificadas o finalizadas.

***

### 1. Acceso al Módulo

**Ruta de acceso:** BackOffice > Reportes > Reporte de limitaciones

***

### 2. Visualización

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FV5GsMvZIQnekrAze3EtL%2Fimage.png?alt=media&#x26;token=07feb575-aee8-41ec-b61c-e1f96116ef64" alt=""><figcaption><p><strong>Figura #1:</strong> Captura de pantalla del reporte de Limitaciones.</p></figcaption></figure>

***

### 3. 🧑‍💻 Acciones del Usuario

<table><thead><tr><th width="251">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtrar limitaciones</strong></td><td>Permite aplicar diferentes filtros para realizar una consulta sobre las limitaciones establecidas por los usuarios.</td></tr><tr><td><strong>Visualizar tabla de resultados</strong></td><td>Presenta la información detallada de las limitaciones generadas según los filtros aplicados.</td></tr><tr><td><strong>Exportar los resultados</strong></td><td>Permite exportar en formato Excel la tabla de resultados obtenida tras la búsqueda.</td></tr></tbody></table>

***

**🎛️ 3.1 Filtros Disponibles**

<table><thead><tr><th width="191">Campo</th><th width="159">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>ID Limitación</strong></td><td>Numérico</td><td>Identificador asignado a la limitación generada por el usuario.</td></tr><tr><td><strong>ID Usuario</strong></td><td>Numérico</td><td>Permite filtrar por el identificador único del usuario.</td></tr><tr><td><strong>Email</strong></td><td>Texto</td><td>Correo electrónico asociado a la cuenta del usuario.</td></tr><tr><td><strong>Tipo de limitación</strong></td><td>Lista desplegable</td><td>Tipo o categoría de la limitación <em>(por ejemplo: depósito, sesión, apuesta).</em></td></tr><tr><td><strong>Fecha y hora</strong></td><td>Calendario</td><td>Fecha y hora en la que se generó la limitación.</td></tr><tr><td><strong>Fecha en que finaliza</strong></td><td>Calendario</td><td>Fecha y hora en la que finaliza la limitación generada por el usuario.</td></tr><tr><td><strong>Fecha modificó</strong></td><td>Calendario</td><td>Fecha en la que se modificó la limitación.</td></tr><tr><td><strong>Estado</strong></td><td>Lista desplegable</td><td>Estado actual de la limitación <em>(Activo, Inactivo, Cancelado).</em></td></tr></tbody></table>

***

**📋 3.2 Columnas del Resultado**

La tabla de resultados muestra la información consolidada de las limitaciones registradas, incluyendo detalles sobre su creación, duración y estado actual.

<table><thead><tr><th width="188">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>ID</strong></td><td>Identificador único de la limitación registrada en el sistema.</td></tr><tr><td><strong>ID Usuario</strong></td><td>Código interno que identifica al usuario que generó la limitación.</td></tr><tr><td><strong>Email</strong></td><td>Correo electrónico del usuario asociado a la limitación.</td></tr><tr><td><strong>Tipo</strong></td><td>Tipo o categoría de la limitación <em>(Ejemplo: límite de depósito).</em></td></tr><tr><td><strong>Fecha y hora</strong></td><td>Fecha y hora exacta en la que el usuario creó la limitación.</td></tr><tr><td><strong>Fecha en que finaliza</strong></td><td>Fecha y hora en que la limitación dejará de estar activa.</td></tr><tr><td><strong>Valor</strong></td><td>Valor numérico o monto asociado al límite configurado <em>(Ejemplo: $50.000 diarios).</em></td></tr><tr><td><strong>Horas</strong></td><td>Número de horas definidas en caso de que la limitación sea de tipo temporal.</td></tr><tr><td><strong>Estado</strong></td><td>Indica si la limitación está <strong>Activa</strong>, <strong>Inactiva</strong> o <strong>Cancelada</strong>.</td></tr><tr><td><strong>Fecha modificación</strong></td><td>Fecha en la que el usuario o el sistema modificó el registro de la limitación.</td></tr><tr><td><strong>Observación</strong></td><td>Comentarios o notas relacionadas con la limitación, si aplica (por ejemplo: "limitación voluntaria de depósito").</td></tr></tbody></table>

***

#### 4. ✅ Validaciones y Reglas de Negocio

* Solo los usuarios autenticados pueden generar limitaciones desde la plataforma de usuarios online.
* Una vez creada una limitación, no puede eliminarse, únicamente modificarse o cancelarse según las políticas establecidas.
* El sistema registra automáticamente las fechas de creación, modificación y finalización.
* Las limitaciones activas afectan directamente el comportamiento de las apuestas o depósitos según el tipo configurado.
* La información mostrada en el reporte depende de los filtros aplicados y el rango de fechas seleccionado.

***

#### 5. 🕒 Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados       |
| ------- | ---------- | ------------- | ------------------------ |
| 1.0     | 22/10/2025 | Ronald Peláez | Documento inicial creado |
