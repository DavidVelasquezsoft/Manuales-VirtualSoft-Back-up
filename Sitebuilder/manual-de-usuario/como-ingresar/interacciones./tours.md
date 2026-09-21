---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
---

# Tours

<mark style="color:$info;">Los tours son un conjunto de pasos que se crean para ayudar en el conocimiento de la plataforma Usuarios Online, desde este módulo se podrá realizar la creación y gestión de dichos tours.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso:** Site Builder > Seleccionar Partner > interacciones > Tours.

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (513).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Tours.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Gestionar tours</strong></td><td>Visualiza y gestiona los tours creados para la plataforma Usuarios Online.</td></tr><tr><td><strong>Crear tours</strong></td><td>Crea tours para secciones específicas de la plataforma Usuarios Online.</td></tr></tbody></table>

***

### 4. Módulo inicial

Inicialmente el módulo se complementará de KPIs, listas e indicadores relacionados a los tours previamente creados para la plataforma.

#### 4.1. KPIs

Los KPIs se conforman de las cantidades totales de tours.

<table><thead><tr><th width="145">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total</code></strong></td><td>Tours creados para la plataforma Usuarios Oline.</td></tr><tr><td><strong><code>Activos</code></strong></td><td>Tours activos actualmente para la plataforma Usuarios Online.</td></tr><tr><td><strong><code>Borradores</code></strong></td><td>Tours que iniciaron la creación, pero no se guardaron.</td></tr><tr><td><strong><code>Inactivo</code></strong></td><td>Tours que fueron creados, pero ya se encuentran inactivos para la plataforma Usuarios Online.</td></tr></tbody></table>

#### 4.2. Lista de tours

Es esta tabla se visualizarán cada uno de los tours previamente creados.

{% hint style="info" %}
Nota: La tabla corresponde a los filtros ![](<../../../.gitbook/assets/Frame 1321316418.png>) que ayudan a obtener una información más precisa, o se puede filtrar directamente por el nombre de un tour desde <img src="../../../.gitbook/assets/Text Input.png" alt="" data-size="line">.
{% endhint %}

<table><thead><tr><th width="174">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><img src="../../../.gitbook/assets/icon_drag_indicator (2).png" alt=""></td><td>Esta acción permite mover los tours </td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del tour.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre asignado al tour.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Prioridad que tiene el tour respecto a los demás tours creados.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado en el que se encuentra en tour.</td></tr><tr><td><strong><code>Recompensa</code></strong></td><td>Recompensa que obtienen los usuarios de la plataforma Usuarios Online al momento de finalizar el tour.</td></tr><tr><td><strong><code>ID bono</code></strong></td><td>Identificador del bono que obtienen los usuarios al finalizar el tour.</td></tr><tr><td><strong><code>Audiencia</code></strong></td><td>Audiencia que tendrá disponible y visible el tour.</td></tr><tr><td><strong><code>Inicio</code></strong></td><td>Fecha en la que el tour inició su vigencia.</td></tr><tr><td><strong><code>Fin</code></strong></td><td>Fecha en la que el tour finalizó su vigencia.</td></tr><tr><td><strong><code>Acciones</code></strong></td><td>Acciones disponibles para gestonar el tour.</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="76">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><img src="../../../.gitbook/assets/Vector (1) (2).png" alt=""></td><td>Edita las condiciones del tour.</td></tr><tr><td><img src="../../../.gitbook/assets/Vector (10).png" alt=""></td><td>Previsualiza el funcionamiento del tour.</td></tr><tr><td><img src="../../../.gitbook/assets/Vector (2) (2).png" alt="" data-size="original"></td><td>Copia el tour</td></tr><tr><td><img src="../../../.gitbook/assets/settings_power.png" alt=""></td><td>Inactiva/activa el tour seleccionado.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

















***

### 4. Agregar

Al seleccionar el botón <img src="../../../.gitbook/assets/Button (13).png" alt="" data-size="line">, se despliega un calendario para establecer el período durante el cual estará vigente el mensaje.

En el calendario se deben configurar los siguientes campos:

***

### 6. Validaciones y reglas del negocio

* La fecha y hora de inicio deben ser anteriores a la fecha y hora de finalización.
* No se pueden configurar mensajes activos con períodos de vigencia que se superpongan.
* Cuando existe un mensaje activo dentro del período seleccionado, el sistema muestra el mensaje: **"Ya existe un mensaje activo en este período. Ajuste las fechas o edite el mensaje existente."**
* Para aplicar los cambios en la plataforma de usuarios es necesario seleccionar **Guardar**.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="108">Versión</th><th width="130">Fecha</th><th width="140">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21/08/2026</td><td><strong>Karol Navia</strong></td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-32852">Reestructuración adaptada a plantilla.</a></td></tr></tbody></table>

</details>
