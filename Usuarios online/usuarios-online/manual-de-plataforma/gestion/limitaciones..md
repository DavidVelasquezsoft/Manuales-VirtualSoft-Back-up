# Limitaciones.

<mark style="color:$info;">Permite al usuario establecer restricciones voluntarias para fomentar el juego responsable, limitando los montos relacionados con depósitos o apuestas por tipo de actividad y durante un periodo de tiempo determinado.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: Menú principal → Limitaciones

***

### 2. Visualización

<figure><img src="https://3756725920-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FI1JHf1oqcL4UapE69pFw%2Fuploads%2FMtctdkHrj4sHpT2kHDYn%2Fimage.png?alt=media&#x26;token=382a8d5b-93d7-4650-9d99-3135f9f8b84c" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Limitaciones.</p></figcaption></figure>

***

### 3. Acciones del Usuario

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="limitaciones..md#id-4.-formulario-de-limitaciones"><strong>Formulario de limitaciones</strong></a></td><td>Permite configurar una limitación definiendo el tipo de actividad, el periodo de tiempo, el monto y el motivo.</td></tr><tr><td><strong>Guardar</strong></td><td>Guarda y aplica la limitación configurada.</td></tr><tr><td><a href="limitaciones..md#id-5.-tabla-de-visualizacion-de-registros"><strong>Tabla de registros</strong></a></td><td>Muestra las limitaciones configuradas y permite anularlas cuando aplica.</td></tr></tbody></table>

***

### 4. Formulario de limitaciones

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tipo</code></strong></td><td>Lista de opciones</td><td>Permite seleccionar la actividad a la que se le aplicará la limitación (Depósito, Apuestas Deportivas, Casino, Casino en Vivo).</td></tr><tr><td><strong><code>Periodo de Tiempo</code></strong></td><td>Lista de opciones</td><td>Define el intervalo en el que estará activa la limitación (día, semana o mes).</td></tr><tr><td><strong><code>Monto</code></strong></td><td>Campo numérico</td><td>Valor máximo permitido para gastar o depositar durante el periodo indicado.</td></tr><tr><td><strong><code>Motivo de Limitación</code></strong></td><td>Campo de texto</td><td>Campo libre para detallar la razón de la restricción.</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Botón</td><td>Guarda y aplica la limitación configurada.</td></tr></tbody></table>

***

### 5. Tabla de visualización de registros

En la parte inferior se muestra una tabla con todas las limitaciones configuradas:

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único de la limitación.</td></tr><tr><td><strong><code>Anular</code></strong></td><td>Botón para cancelar la limitación. Solo disponible después de 24 horas desde su creación.</td></tr><tr><td><strong><code>Periodo de Tiempo</code></strong></td><td>Duración de la limitación activa (día, semana o mes).</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Actividad sobre la que se aplica la limitación.</td></tr><tr><td><strong><code>Estado</code></strong></td><td><p>Estado actual de la limitación:</p><ul><li><strong>Activo</strong>: la limitación está en vigor.</li><li><strong>Inactivo</strong>: expiró o fue desactivada.</li><li><strong>Cancelado</strong>: fue anulada manualmente antes de su vencimiento.</li></ul></td></tr><tr><td><strong><code>Fecha generación</code></strong></td><td>Fecha en la que se creó la limitación.</td></tr><tr><td><strong><code>Fecha de Fin</code></strong></td><td>Fecha en que la limitación deja de estar vigente.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto límite configurado.</td></tr></tbody></table>

***

### 6. Validaciones y reglas de negocio

* La opción de anular una limitación solo estará habilitada 24 horas después de haber sido creada.
* El sistema validará que no existan varias limitaciones activas para el mismo tipo y periodo.

***

### 7. Control de versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>23/07/2025</td><td>Ronald Pelaez</td><td>Documento funcional inicial</td></tr><tr><td>1.1</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
