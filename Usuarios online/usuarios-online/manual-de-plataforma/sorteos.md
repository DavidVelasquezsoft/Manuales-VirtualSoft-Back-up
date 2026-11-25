# Sorteos

<mark style="color:$info;">Permite a los usuarios participar en dinámicas para ganar premios como bonos, giros gratis o dinero en efectivo. Cada sorteo tiene condiciones específicas.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: Plataforma usuarios online > Menú principal > Sorteos

***

### 2. Acciones del Usuario

<table><thead><tr><th width="200">Elemento</th><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtro por tipo de sorteo</strong></td><td>Seleccionar</td><td>Permite elegir entre todos los sorteos registrados o el estado del sorteo.</td></tr><tr><td><a href="sorteos.md#id-3.-otras-configuraciones"><strong>Participa Ahora</strong></a></td><td>Click</td><td>Inscribe al usuario en el sorteo correspondiente si cumple los requisitos.</td></tr><tr><td><strong>Camino y Stickers</strong></td><td>Click</td><td>Permite el acceso a información del proceso de acumulación o elementos coleccionables del sorteo.</td></tr></tbody></table>

***

### 3. Otras configuraciones

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th><th>Observaciones</th></tr></thead><tbody><tr><td><strong><code>Contador de tiempo</code></strong></td><td>Visual dinámica</td><td>Muestra el tiempo restante para que finalice el sorteo.</td><td>Se actualiza en tiempo real.</td></tr><tr><td><strong><code>Requisitos para participar</code></strong></td><td>Texto informativo</td><td>Informa al usuario si debe apostar o depositar una cantidad mínima.</td><td>Puede variar según el tipo de sorteo.</td></tr><tr><td><strong><code>Premios del sorteo</code></strong></td><td>Visual en tarjetas</td><td>Presenta una descripción gráfica del premio (bonos, dinero, giros gratis).</td><td>Puede incluir imágenes o íconos.</td></tr><tr><td><strong><code>Usuarios inscritos</code></strong></td><td>Visual dinámica</td><td>Visualiza la cantidad de usuarios inscritos en el sorteo.</td><td>Se actualiza la información cada 120 segundos.</td></tr></tbody></table>

***

### 4. Validaciones y Reglas de Negocio

* Solo se puede participar en un sorteo si se cumplen los requisitos de acumulación.
* Cada sorteo tiene una fecha y hora límite.
* Los usuarios no pueden registrarse en sorteos inactivos o finalizados.
* El botón **Participa ahora** solo estará habilitado si el usuario cumple condiciones de elegibilidad.

***

### 5. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21/07/2025</td><td>Karol Navia</td><td>Creación inicial del módulo Sorteos</td></tr><tr><td>1.1</td><td>09/09/2025</td><td>Ronald Peláez</td><td>Nuevo contador de usuarios inscritos.</td></tr><tr><td>1.2</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
