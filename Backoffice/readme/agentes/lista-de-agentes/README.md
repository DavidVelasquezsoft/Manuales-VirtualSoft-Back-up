# Lista de agentes

<mark style="color:$info;">Consulta los agentes registrados, crea nuevos agentes y accede al detalle de cada uno, incluido su reporte de comisiones. Un agente es una persona o empresa autorizada para ofrecer y vender los productos de la plataforma.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Agentes > Lista de agentes

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (64).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección lista de agentes.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="200">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="./#id-4.-filtros"><strong>Filtros</strong></a></td><td>Definen los criterios de búsqueda para consultar los agentes registrados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados, dejando los campos en su estado inicial.</td></tr><tr><td><a href="./#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros definidos y muestra los agentes en la tabla de resultados.</td></tr><tr><td><a href="./#id-6.-anadir-agente"><strong>Añadir Agente</strong></a></td><td>Abre el formulario para registrar un nuevo agente.</td></tr><tr><td><a href="reporte-de-comisiones-detallado.md"><strong>Ver detalle</strong></a> <i class="fa-magnifying-glass">:magnifying-glass:</i></td><td>Abre la información completa de un agente, incluido el reporte de comisiones detallado.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel <em>(.XLS)</em> y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Localiza al agente por su identificador único en el sistema.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Busca al agente por su nombre.</td></tr><tr><td><strong><code>Número cédula</code></strong></td><td>Campo de texto</td><td>Identifica al agente por su documento de identidad.</td></tr><tr><td><strong><code>Login</code></strong></td><td>Campo de texto</td><td>Consulta al agente por el usuario con el que inicia sesión.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Acota los resultados al país donde opera el agente.</td></tr><tr><td><strong><code>Estado de Registro</code></strong></td><td>Lista desplegable</td><td>Separa a los agentes según el estado de su registro en la plataforma.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Muestra a los agentes según su estado actual.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Restringe la búsqueda a la clasificación de agente seleccionada.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Campo de texto</td><td>Delimita la consulta por la dirección IP desde la que el agente inició sesión.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al ejecutar la consulta, en la parte inferior de la pantalla se despliega una tabla con los agentes que cumplen con los filtros aplicados.

<table><thead><tr><th width="200">Campo</th><th width="120">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Presenta el nombre completo del agente.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Muestra el identificador único del agente.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Texto</td><td>Indica el login con el que el agente accede al sistema.</td></tr><tr><td><strong><code>Número cédula</code></strong></td><td>Texto</td><td>Contiene el documento de identidad del agente.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Texto</td><td>Corresponde al correo electrónico registrado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Señala el estado actual del agente.</td></tr><tr><td><strong><code>Estado Validación</code></strong></td><td>Texto</td><td>Indica el nivel de verificación del agente.</td></tr><tr><td><strong><code>Región</code></strong></td><td>Texto</td><td>Muestra la región donde opera el agente.</td></tr><tr><td><strong><code>Departamento</code></strong></td><td>Texto</td><td>Presenta el departamento del país donde opera el agente.</td></tr><tr><td><strong><code>Ciudad</code></strong></td><td>Texto</td><td>Indica la ciudad registrada.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Texto</td><td>Corresponde a la moneda con la que opera el agente.</td></tr><tr><td><strong><code>Teléfono</code></strong></td><td>Texto</td><td>Contiene el número de contacto.</td></tr><tr><td><strong><code>Dirección</code></strong></td><td>Texto</td><td>Muestra la dirección física registrada.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Texto</td><td>Presenta la dirección IP del último inicio de sesión.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha</td><td>Registra el momento en que se creó el agente.</td></tr><tr><td><strong><code>Fecha de último login</code></strong></td><td>Fecha</td><td>Registra el último acceso del agente al sistema.</td></tr><tr><td><strong><code>Modificado</code></strong></td><td>Texto</td><td>Indica si el registro fue actualizado.</td></tr><tr><td><i class="fa-magnifying-glass">:magnifying-glass:</i></td><td>Acción</td><td>Abre la información completa del agente, con su historial, configuración y reporte de comisiones detallado.</td></tr></tbody></table>

***

### 6. Añadir Agente

Al presionar **Añadir Agente**, se abre el formulario de registro, organizado en dos secciones: **Datos Principales** y **Datos Agente**.

<figure><img src="../../../.gitbook/assets/image (65).png" alt=""><figcaption><p>Figura #2: Captura de pantalla formulario añadir agente.</p></figcaption></figure>

{% hint style="warning" %}
**Nota:** Los campos marcados con asterisco _(*)_ en el formulario son obligatorios.
{% endhint %}

#### 6.1. Datos Principales

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Login para acceso</code></strong></td><td>Campo de texto</td><td>Define el usuario con el que el agente inicia sesión.</td></tr><tr><td><strong><code>Clave</code></strong></td><td>Campo de texto</td><td>Establece la contraseña de acceso del agente.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Indica si el agente queda activo o inactivo. Por defecto: <strong>Activo</strong>.</td></tr><tr><td><strong><code>Nombre del usuario</code></strong></td><td>Campo de texto</td><td>Registra el nombre completo del agente.</td></tr><tr><td><strong><code>Idioma preferido</code></strong></td><td>Lista desplegable</td><td>Selecciona el idioma en que el agente ve la plataforma. Por defecto: <strong>español</strong>.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Asigna la clasificación del agente dentro del sistema. Por defecto: <strong>Agente</strong>.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Indica el país donde opera el agente.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Lista desplegable</td><td>Determina la moneda con la que opera el agente.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Asocia el agente a un partner <em>(Ejemplo: Doradobet)</em>.</td></tr></tbody></table>

#### 6.2. Datos Agente

<table><thead><tr><th width="200">Campo</th><th width="150">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del contacto</code></strong></td><td>Campo de texto</td><td>Registra la persona de contacto principal del agente.</td></tr><tr><td><strong><code>Número cédula</code></strong></td><td>Campo de texto</td><td>Define el documento de identidad del agente.</td></tr><tr><td><strong><code>Correo electrónico</code></strong></td><td>Campo de texto</td><td>Establece el correo electrónico del agente.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Contiene comentarios o detalles adicionales del agente.</td></tr><tr><td><strong><code>Concesionario</code></strong></td><td>Lista desplegable</td><td>Asocia el agente al concesionario al que pertenece.</td></tr><tr><td><strong><code>Subconcesionario</code></strong></td><td>Lista desplegable</td><td>Vincula el agente a un subconcesionario del concesionario, cuando aplica.</td></tr><tr><td><strong><code>Provincia/Región</code></strong></td><td>Lista desplegable</td><td>Selecciona la región del país donde opera el agente.</td></tr><tr><td><strong><code>Ciudad</code></strong></td><td>Campo de texto</td><td>Especifica la ciudad del agente.</td></tr><tr><td><strong><code>Dirección</code></strong></td><td>Campo de texto</td><td>Señala la dirección física del agente.</td></tr><tr><td><strong><code>Barrio</code></strong></td><td>Campo de texto</td><td>Ubica el barrio dentro de la ciudad.</td></tr><tr><td><strong><code>Teléfono</code></strong></td><td>Campo numérico</td><td>Contiene el número de contacto del agente.</td></tr><tr><td><strong><code>IP</code></strong></td><td>Campo de texto</td><td>Corresponde a la dirección IP desde la que accede el agente.</td></tr><tr><td><strong><code>Limpiar</code></strong></td><td>Botón</td><td>Restablece los campos del formulario.</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Botón</td><td>Registra el nuevo agente.</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* El agente se registra solo al presionar **Guardar** con todos los campos obligatorios completos.
* Los campos marcados con asterisco _(*)_ en el formulario son obligatorios.
* El detalle de cada agente, incluido el [Reporte de comisiones detallado](reporte-de-comisiones-detallado.md), se abre desde el ícono <i class="fa-magnifying-glass">:magnifying-glass:</i> de la tabla de resultados.

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>01/08/2025</td><td>Karol Navia</td><td>Implementación de formato</td></tr><tr><td>1.1</td><td>24/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
