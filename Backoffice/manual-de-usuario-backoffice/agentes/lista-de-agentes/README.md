---
description: >-
  Gestiona y consulta la información de los agentes registrados en el sistema. A
  través de diversos filtros
---

# Lista de agentes

### 1. Acceso al Módulo

**Ruta de acceso**: Agentes> Lista de agentes.

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (63).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección agentes.</p></figcaption></figure>

***

### 3. Acciones del Usuario

<table><thead><tr><th width="104.00006103515625">Acción</th><th width="643.9999389648438">Descripción</th></tr></thead><tbody><tr><td><a href="./#id-3.-filtros-de-busqueda"><strong>Filtrar</strong></a></td><td>Permite definir los criterios de búsqueda del reporte.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros a su estado inicial.</td></tr><tr><td><a href="./#id-4.-resultado-de-la-busqueda"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda según los filtros seleccionados.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. Filtros de búsqueda

<table><thead><tr><th width="195">Campo</th><th width="159">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><code>ID Usuario</code></td><td>Numérico</td><td>Identificador único del agente en el sistema.</td></tr><tr><td><code>Nombre</code></td><td>Texto</td><td>Nombre completo del agente.</td></tr><tr><td><code>Número de cédula</code></td><td>Texto</td><td>Documento de identidad del agente.</td></tr><tr><td><code>Login</code></td><td>Texto</td><td>Usuario con el que el agente accede al sistema.</td></tr><tr><td><code>País</code></td><td>Lista desplegable</td><td>Selección del país donde opera el agente.</td></tr><tr><td><code>Estado de Registro</code></td><td>Lista desplegable</td><td>Estado del registro del agente en la plataforma.</td></tr><tr><td><code>Estado</code></td><td>Lista desplegable</td><td>Estado actual del agente (activo, inactivo, etc.).</td></tr><tr><td><code>Tipo</code></td><td>Lista desplegable</td><td>Clasificación del agente dentro del sistema.</td></tr><tr><td><code>Dirección IP</code></td><td>Lista desplegable</td><td>IP desde la que el agente ha iniciado sesión.</td></tr></tbody></table>

***

### 5. Resultado de la búsqueda

Una vez ejecutada la búsqueda, se despliega una tabla con la siguiente información:

<table><thead><tr><th width="233">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Nombre</code></td><td>Nombre completo del agente.</td></tr><tr><td><code>ID Usuario</code></td><td>Identificación única en el sistema.</td></tr><tr><td><code>Usuario</code></td><td>Login utilizado por el agente para acceder al sistema.</td></tr><tr><td><code>Número de cédula</code></td><td>Documento de identidad.</td></tr><tr><td><code>Email</code></td><td>Dirección de correo electrónico registrada.</td></tr><tr><td><code>Estado</code></td><td>Estado actual del agente (activo, inactivo, etc.).</td></tr><tr><td><code>Estado de Validación</code></td><td>Nivel de verificación del agente.</td></tr><tr><td><code>Región</code></td><td>Ubicación geográfica del agente.</td></tr><tr><td><code>Departamento</code></td><td>Departamento del país donde opera.</td></tr><tr><td><code>Ciudad</code></td><td>Ciudad de residencia o trabajo.</td></tr><tr><td><code>Moneda</code></td><td>Moneda utilizada por el agente.</td></tr><tr><td><code>Teléfono</code></td><td>Número de contacto.</td></tr><tr><td><code>Dirección</code></td><td>Dirección física registrada.</td></tr><tr><td><code>Dirección IP</code></td><td>IP del último inicio de sesión.</td></tr><tr><td><code>Fecha de creación</code></td><td>Fecha en la que fue registrado el agente.</td></tr><tr><td><code>Fecha de último login</code></td><td>Último acceso al sistema.</td></tr><tr><td><code>Modificado</code></td><td>Indica si el registro fue actualizado recientemente.</td></tr><tr><td><a href="reporte-de-comisiones-detallado.md" class="button primary">🔍(Ver Detalle)</a></td><td>Redirige a una nueva página con la información completa del agente, incluyendo historial, configuración, y datos adicionales.</td></tr></tbody></table>

### 6. Añadir Agente

Para registrar un nuevo agente, haz clic en el botón **"Añadir Agente"**, lo cual abre un formulario con dos secciones:

<figure><img src="../../../.gitbook/assets/image (64).png" alt=""><figcaption><p>FIgura#2: Captura de pantalla sección añadir agentes.</p></figcaption></figure>

<table><thead><tr><th width="199">Campo</th><th width="160">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Login para acceso</code></td><td>Texto</td><td>Nombre de usuario que utilizará el agente para iniciar sesión.</td></tr><tr><td><code>Clave</code></td><td>Contraseña</td><td>Contraseña para el acceso.</td></tr><tr><td><code>Estado</code></td><td>Lista desplegable</td><td>Estado del agente (activo / inactivo).</td></tr><tr><td><code>Nombre del usuario</code></td><td>Texto</td><td>Nombre completo del agente.</td></tr><tr><td><code>Idioma preferido</code></td><td>Lista desplegable</td><td>Idioma de visualización de la plataforma.</td></tr><tr><td><code>Tipo</code></td><td>Lista desplegable</td><td>Categoría del agente dentro del sistema.</td></tr><tr><td><code>País</code></td><td>Lista desplegable</td><td>País de operación.</td></tr><tr><td><code>Moneda</code></td><td>Lista desplegable</td><td>Moneda que usará el agente.</td></tr><tr><td><code>Partner</code></td><td>Lista desplegable</td><td>Asociación a la que pertenece (ej. Doradobet).</td></tr></tbody></table>

***

#### **6.1. Datos del Agente**

<table><thead><tr><th width="192">Campo</th><th width="165">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Nombre del contacto</code></td><td>Texto</td><td>Persona responsable o contacto principal.</td></tr><tr><td><code>Número de cédula</code></td><td>Texto</td><td>Documento de identidad.</td></tr><tr><td><code>Correo electrónico</code></td><td>Email</td><td>Dirección de correo registrada.</td></tr><tr><td><code>Descripción</code></td><td>Texto</td><td>Comentario adicional o detalles del agente.</td></tr><tr><td><code>Concesionario</code></td><td>Lista desplegable</td><td>Entidad principal a la que pertenece el agente.</td></tr><tr><td><code>Subconcesionario</code></td><td>Lista desplegable</td><td>Subentidad dentro del concesionario (si aplica).</td></tr><tr><td><code>Provincia/Región</code></td><td>Lista desplegable</td><td>Región dentro del país.</td></tr><tr><td><code>Ciudad</code></td><td>Texto</td><td>Ciudad de residencia o trabajo.</td></tr><tr><td><code>Dirección</code></td><td>Texto</td><td>Dirección física registrada.</td></tr><tr><td><code>Barrio</code></td><td>Texto</td><td>Área específica dentro de la ciudad.</td></tr><tr><td><code>Teléfono</code></td><td>Numérico</td><td>Número de contacto.</td></tr><tr><td><code>IP</code></td><td>Texto</td><td>Dirección IP desde la que accede.</td></tr></tbody></table>

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de Versiones</summary>

<table><thead><tr><th width="110">Versión</th><th width="158">Fecha</th><th width="180">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2025-08-01</td><td>Karol Navia</td><td>Implementación de formato</td></tr></tbody></table>

</details>
