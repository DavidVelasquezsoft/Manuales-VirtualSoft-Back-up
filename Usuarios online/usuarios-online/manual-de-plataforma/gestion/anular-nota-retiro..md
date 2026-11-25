# Anular nota retiro.

<mark style="color:$info;">Permite consultar las notas de retiro generadas por el usuario y anularlas para que el valor retenido retorne a su saldo y quede nuevamente disponible para apostar.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: Menú principal → Gestión → Anular nota retiro.

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (27) (2).png" alt=""><figcaption><p>Figura #1: Captura de pantalla anular nota de retiro.</p></figcaption></figure>

***

### 3. Acciones del Usuario

<table><thead><tr><th width="200">Acción</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="anular-nota-retiro..md#id-4.-tabla-notas-de-retiro"><strong>Filtro de tabla</strong></a></td><td>Selección múltiple</td><td>Filtra la tabla de las notas de retiro según el estado.</td></tr><tr><td><a href="anular-nota-retiro..md#id-4.-tabla-notas-de-retiro"><strong>Anular</strong></a></td><td>Botón</td><td>Elimina la nota de retiro y retorna el saldo al usuario para que le permita seguir apostando.</td></tr></tbody></table>

***

### 4. Tabla notas de retiro

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>No. Nota de retiro</code></strong></td><td>Visualiza el Número asociado a la nota de retiro.</td></tr><tr><td><strong><code>Botón anular</code></strong></td><td>Elimina la nota de retiro y retorna el saldo al usuario para que le permita seguir apostando.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Visualiza el medio por el cual se generó la nota de retiro.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Visualiza el estado en el que se encuentra la nota de retiro.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha en la que se generó la nota de retiro.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto por el cual se generó la nota de retiro.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Tipo de divisa por el cual se generó la nota de retiro.</td></tr></tbody></table>

***

### 5. Validaciones y Reglas de Negocio

* Al generarse una nota de retiro, el valor correspondiente será descontado del saldo del usuario. En caso de que la nota sea anulada, dicho monto se reintegrará automáticamente al saldo, quedando nuevamente disponible para realizar apuestas.

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>17/07/2025</td><td>Ronald Peláez</td><td>Documento inicial.</td></tr><tr><td>1.1</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
