# Consulta de apuestas deportivas

<mark style="color:$info;">Permite consultar el historial de tickets de las apuestas deportivas realizadas por el usuario en la plataforma.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: Menú principal → Consultas → Consulta de apuestas deportivas

***

### 2. Visualización

📌 **Figura #1**: Captura de pantalla – Consulta de tickets de apuestas deportivas

***

### 3. Acciones del Usuario

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="consulta-de-apuestas-deportivas.md#id-4.-filtros-de-busqueda"><strong>Filtros</strong></a></td><td>Definen el rango de fechas y el estado de los tickets que se desean consultar.</td></tr><tr><td><a href="consulta-de-apuestas-deportivas.md#id-5.-resultados"><strong>Resultado</strong></a></td><td>Muestra los tickets según los filtros aplicados.</td></tr></tbody></table>

***

### 4. Filtros de búsqueda

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th><th>Validaciones</th></tr></thead><tbody><tr><td><strong><code>Fecha inicial</code></strong></td><td>Calendario</td><td>Fecha desde la cual se desea consultar las apuestas.</td><td>Campo obligatorio.</td></tr><tr><td><strong><code>Fecha final</code></strong></td><td>Calendario</td><td>Fecha hasta la cual se desea consultar las apuestas.</td><td>Campo obligatorio. No debe ser anterior a la fecha inicial.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Selector</td><td>Permite alternar entre apuestas "Abiertas" o "Resueltas".</td><td>Selección opcional.</td></tr></tbody></table>

***

### 5. Resultados

<table><thead><tr><th width="200">Campo</th><th>Descripción</th><th>Validaciones</th></tr></thead><tbody><tr><td><strong><code>Resultado</code></strong></td><td>Área donde se muestran los tickets según los filtros aplicados.</td><td>Se muestra mensaje si no hay apuestas en el rango o estado seleccionado.</td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* El sistema no mostrará resultados si no existen apuestas en el rango de fechas seleccionado.
* El uso de los campos de fecha es obligatorio para ejecutar la consulta.
* Las etiquetas "Abierto" y "Resuelto" corresponden al estado actual del ticket.
* Las validaciones pueden cambiar dependiendo del **partner**.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/07/2025</td><td>Karol Navia</td><td>Documento inicial de la sección de consulta</td></tr><tr><td>1.1</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
