# Consultar depositos

<mark style="color:$info;">Permite visualizar el histórico de los depósitos realizados por el usuario en su cuenta, con la opción de buscar la información mediante filtros de fechas.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: Menú principal → Consultas → Consultar depósitos

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (164).png" alt=""><figcaption><p><strong>Figura #1</strong>: Captura de pantalla – Consulta de depósitos</p></figcaption></figure>

***

### 3. Acciones del Usuario

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="consultar-depositos.md#id-4.-filtros-de-busqueda"><strong>Filtros</strong></a></td><td>Definen el rango de fechas en el que se consultan los depósitos realizados.</td></tr><tr><td><a href="consultar-depositos.md#id-5.-resultados-mostrados"><strong>Buscar</strong></a></td><td>Ejecuta la consulta y muestra los depósitos realizados dentro del rango de fechas seleccionado.</td></tr></tbody></table>

***

### 4. Filtros de búsqueda

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th><th>Validaciones</th></tr></thead><tbody><tr><td><strong><code>Fecha Inicio</code></strong></td><td>Calendario</td><td>Fecha desde la cual se desea consultar los depósitos realizados.</td><td>Campo obligatorio.</td></tr><tr><td><strong><code>Fecha Fin</code></strong></td><td>Calendario</td><td>Fecha hasta la cual se desea consultar.</td><td>Campo obligatorio. No debe ser anterior a la fecha inicial.</td></tr></tbody></table>

***

### 5. Resultados mostrados

<table><thead><tr><th width="200">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Número de Depósito</code></strong></td><td>Identificador único del depósito realizado.</td></tr><tr><td><strong><code>Fecha Depósito</code></strong></td><td>Fecha en la que se realizó el depósito.</td></tr><tr><td><strong><code>Medio</code></strong></td><td>Método utilizado para realizar el depósito (Ej. PSE, tarjeta, etc.).</td></tr><tr><td><strong><code>Código de Transacción</code></strong></td><td>Código generado por el sistema o entidad financiera.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto depositado por el usuario.</td></tr><tr><td><strong><code>Bono</code></strong></td><td>Valor adicional otorgado como bono (si aplica).</td></tr><tr><td><strong><code>Total</code></strong></td><td>Suma del valor depositado más el bono recibido.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Tipo de moneda en la que se hizo el depósito (Ej. COP, USD).</td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* Deben seleccionarse ambas fechas para ejecutar la consulta.
* El sistema solo mostrará los depósitos realizados dentro del rango de fechas seleccionado.
* El campo de bono puede estar vacío si no se recibió beneficio adicional en el depósito.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/07/2025</td><td>Karol Navia</td><td>Versión inicial – Consulta de depósitos</td></tr><tr><td>1.1</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
