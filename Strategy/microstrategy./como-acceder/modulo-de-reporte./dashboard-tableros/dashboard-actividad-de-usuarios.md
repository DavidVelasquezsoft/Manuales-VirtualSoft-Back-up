---
description: >-
  Permite monitorear la interacción de los usuarios con la plataforma,
  incluyendo conexiones, reportes consultados, filtros aplicados y exportaciones
  realizadas.
---

# Dashboard Actividad de Usuarios

### Configuración general

{% hint style="warning" %}
**Nota:**

El acceso está restringido a perfiles **administrador** o con permisos específicos.
{% endhint %}

### 1. Acceso al Módulo:

**Ruta de Acceso**:\
Login MicroStrategy > Platform Analytics > Informes compartidos > a. Dashboards > Conexiones y movimientos de usuarios.

***

**🧑‍💻 2. Acciones del Usuario**

<table><thead><tr><th width="105.800048828125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td>Buscar</td><td>Permite localizar información específica dentro del reporte aplicando filtros.</td></tr><tr><td>Exportar</td><td>Opción disponible en cualquier card o tabla del dashboard. Para usarla, se deben ubicar los tres puntos verticales y seleccionar la opción "<em><strong>Exportar</strong></em>" Los formatos disponibles son: <em>(Excel, PDF y Datos).</em></td></tr></tbody></table>

El reporte está conformado por **dos hojas principales** que se navegan mediante los íconos ubicados en la parte superior:

{% tabs %}
{% tab title="👤 Conexiones de Usuario" %}
#### 3. Visualización:

<figure><img src="../../../../.gitbook/assets/image (41).png" alt=""><figcaption><p>Figura#1: Captura de pantalla vista conexiones de usuarios.</p></figcaption></figure>

**3.1. Filtros**

<table><thead><tr><th width="170.8182373046875">Sección</th><th width="222">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Selector de fechas</code></td><td>Selección de rango de fechas</td><td>Permite definir el período de análisis.</td></tr><tr><td><code>Usuario</code></td><td>Lista desplegable</td><td>Filtra la información por usuario específico o todos.</td></tr></tbody></table>

**3.2.** **Indicadores**&#x20;

<table><thead><tr><th width="158.09088134765625">Sección</th><th width="154.0909423828125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Usuarios Únicos</code></td><td>Visualización de card</td><td>Muestra el total de usuarios únicos que han ingresado en el rango de fechas seleccionado.</td></tr><tr><td><code>Cuentas Activas Diarias</code></td><td>Gráfico de líneas</td><td>Presenta la cantidad de cuentas activas por día dentro del período seleccionado, permitiendo identificar picos y tendencias de uso.</td></tr></tbody></table>

**3.3.** 📋 **Tabla cuentas más activas**

<table><thead><tr><th width="250.272705078125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Nombre de usuario</code></td><td>Muestra el nombre del usuario que inició la sesión.</td></tr><tr><td><code>Fecha</code></td><td>Fecha en la que se registra el log en la base de datos.</td></tr><tr><td><code>ID Sesión</code></td><td>Identificador único asignado a la sesión iniciada.</td></tr><tr><td><code>Session Source</code></td><td>Indica el origen de la conexión (Web, etc.).</td></tr><tr><td><code>Fecha Inicio</code></td><td>Fecha y hora en que el usuario inició sesión.</td></tr><tr><td><code>Fecha Fin</code></td><td>Fecha y hora en que el usuario cerró sesión.</td></tr><tr><td><code>Tiempo en sesión (m)</code></td><td>Duración total de la sesión en minutos.</td></tr><tr><td><code>Tiempo en sesión (hh:mm)</code></td><td>Duración de la sesión expresada en horas y minutos.</td></tr></tbody></table>

**3.4.**&#xD83D;�  **Tabla top usuario x conexión**&#x20;

<table><thead><tr><th width="250.36358642578125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Nombre de usuario</code></td><td>Identifica al usuario registrado en la plataforma.</td></tr><tr><td><code>Cantidad de sesiones</code></td><td>Muestra el número total de sesiones iniciadas por el usuario en el período seleccionado.</td></tr></tbody></table>
{% endtab %}

{% tab title="📄 Acciones Detalladas." %}
#### 3. Visualización:

<figure><img src="../../../../.gitbook/assets/image (42).png" alt=""><figcaption><p>Figura#2: Captura de pantalla acciones detalladas.</p></figcaption></figure>

**3.1. Filtros**

<table><thead><tr><th width="172.6363525390625">Sección</th><th width="134.36370849609375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Selector de fechas</code></td><td>Selector</td><td>Permite definir el período de análisis mediante un rango de fechas <em>(Desde – Hasta).</em></td></tr><tr><td><code>Usuario</code></td><td>Lista desplegable</td><td>Filtra la información por un usuario específico o todos.</td></tr><tr><td><code>Objeto</code></td><td>Lista desplegable</td><td>Filtra la información por el reporte consultado.</td></tr><tr><td><code>Tipo de acción</code></td><td>Lista desplegable</td><td>Filtra según el tipo de acción realizada en el sistema. (<em>ej: Export to pdf).</em></td></tr></tbody></table>

***

**3.2. Indicadores**

<table><thead><tr><th width="147.727294921875">Sección</th><th width="124.45452880859375">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Top objeto más consultado</code></td><td>Gráfico de barras</td><td>Muestra los reportes más consultados por los usuarios en el período seleccionado.</td></tr><tr><td><code>Cuentas Activas Diarias</code></td><td>Gráfico de líneas</td><td>Presenta la evolución de las cuentas activas por día dentro del período seleccionado, permitiendo identificar picos y tendencias de uso.</td></tr></tbody></table>

***

**3.3. Tabla – Detalle de acciones**

<table><thead><tr><th width="187.6363525390625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Nombre Usuario</code></td><td>Identifica el usuario que realizó la acción.</td></tr><tr><td><code>Fecha</code></td><td>Fecha en la que se ejecutó la acción.</td></tr><tr><td><code>Nombre Objeto</code></td><td>Nombre del reporte sobre el cual se realizó la acción.</td></tr><tr><td><code>Categoría Objeto</code></td><td>Clasifica el tipo de objeto <em>(ej. Reports, Managed Objects).</em></td></tr><tr><td><code>Tipo de Acción</code></td><td>Acción realizada por el usuario <em>(ej. Execute, Execute with Cache Hit).</em></td></tr><tr><td><code>Categoría Acción</code></td><td>Clasificación técnica de la acción <em>(ej. Cache Hit, Cache Creation, Execution).</em></td></tr><tr><td><code>Ejecuciones</code></td><td>Número de veces que la acción fue ejecutada.</td></tr></tbody></table>

***

**3.4. Tabla – Acciones ejecutadas**

<table><thead><tr><th width="190.3636474609375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Nombre Usuario</code></td><td>Identifica el usuario que ejecutó la acción.</td></tr><tr><td><code>Fecha</code></td><td>Fecha de ejecución de la acción.</td></tr><tr><td><code>Objeto</code></td><td>Nombre del reporte sobre el que se realizó la acción.</td></tr><tr><td><code>Ejecuciones</code></td><td>Número de veces que el usuario ejecutó dicha acción.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### ✅ 4. Validaciones y Reglas de Negocio

* La visualización de estos datos está restringida únicamente al perfil de administrador o a aquellos perfiles que cuenten con los permisos habilitados.
* El dashboard se compone de visualizaciones gráficas (líneas, barras, tablas dinámicas) para facilitar el análisis.

***

### 🕒 5. Control de Versiones

| Versión | Fecha      | Autor       | Cambios Realizados |
| ------- | ---------- | ----------- | ------------------ |
| 1.0     | 25/09/2025 | Karol Navia | Documento inicial  |
