---
description: >-
  Este módulo permite visualizar, consultar y gestionar los jackpots creados en
  la plataforma, así como acceder al detalle de cada uno y realizar acciones
  sobre ellos.
---

# Jackpot.

### **1. Acceso al módulo**

Ruta de acceso: BackOffice > Torneos y bonos > menú lateral > Jackpot

***

### **2. Visualización general**

<figure><img src="../../../.gitbook/assets/image (279).png" alt=""><figcaption><p>Figura #1: Captura de pantalla lista de Jackpot</p></figcaption></figure>

***

### **3. Acciones disponibles**

<table><thead><tr><th width="174">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="../crear-eventos./crear-jackpot.md"><strong>Crear Jackpot</strong></a></td><td>Crea un nuevo jackpot y redirige a la pantalla de configuración.</td></tr><tr><td><strong>Buscar</strong></td><td>Ejecuta la consulta con base en los filtros seleccionados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros aplicados.</td></tr><tr><td><strong>👁️ Detalle</strong></td><td>Muestra la información completa del jackpot en formato ticket.</td></tr><tr><td><a href="jackpot..md#detalle-de-participantes"><strong>🔍 Participantes</strong></a></td><td>Muestra los usuarios inscritos en el jackpot.</td></tr><tr><td><strong>⏻ Desactivar</strong></td><td>Permite inactivar el Jackpot seleccionado.</td></tr><tr><td><a href="jackpot..md#id-6.-edicion-de-jackpot"><strong>✏️ Editar</strong></a></td><td>Modifica la configuración del jackpot.</td></tr><tr><td><strong>⬇️ Exportar</strong></td><td>Descarga la tabla de los jackpots creados en formato Excel según los filtros aplicados. </td></tr><tr><td><strong>🔃 Recargar</strong></td><td>Actualiza el listado de los jackpots creados.</td></tr></tbody></table>

***

### **4. Filtros**&#x20;

<table><thead><tr><th width="133">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Sorteo</code></strong></td><td>Permite buscar información filtrando únicamente por el Identificador del jackpot.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Facilita la búsqueda por rango de fechas en las que el jackpot fue creado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Realiza búsquedas según el estado del jackpot, ya sea <strong>activo</strong> o <strong>inactivo</strong>.</td></tr><tr><td><strong><code>País</code></strong></td><td>Filtra los jackpots según el país para el cual fueron creados.</td></tr></tbody></table>

***

### **5.** Lista de Jackpot:&#x20;

En este apartado se visualizan los jackpots creados y se pueden gestionar diferentes acciones sobre cada uno de ellos.

<table><thead><tr><th width="209">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td>Desde la primera columna se pueden ejecutar acciones específicas:</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="99">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td>👁️</td><td>Muestra un <a href="https://virtualsoft.gitbook.io/untitled/glosario#ticket">ticket</a>  con toda la información del jackpot registrada al momento de su creación. </td></tr><tr><td>🔍</td><td>Permite acceder a una interfaz donde se visualizan los usuarios que participan en el jackpot, junto con su información detallada.<br><a href="jackpot..md#detalle-de-participantes" class="button primary">Detalle de participantes (🔍)</a></td></tr><tr><td><strong>⏻</strong></td><td>Abre una ventana de confirmación para inactivar el jackpot seleccionado.</td></tr><tr><td><a href="jackpot..md#id-6.-edicion-de-jackpot"><strong>✏️.</strong></a></td><td>Permite modificar la configuración del jackpot.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

<table data-header-hidden><thead><tr><th width="132">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del jackpot, utilizado para diferenciarlo dentro del sistema</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre asignado al jackpot al momento de su creación, el cual permite reconocerlo fácilmente.</td></tr><tr><td><strong><code>Descripcion</code></strong></td><td>Información adicional que describe las características o propósito del jackpot.</td></tr><tr><td><strong><code>Fecha inició</code></strong></td><td>Fecha en la que inicia la vigencia del jackpot y comienza a estar disponible para los usuarios.</td></tr><tr><td><strong><code>Fecha fin</code></strong></td><td>Fecha en la que finaliza el jackpot <em>(si aplica)</em>, indicando el momento en el que deja de estar disponible.</td></tr></tbody></table>

***

<details>

<summary><strong>Detalle de participantes (🔍)</strong></summary>

Permite visualizar la información de los usuarios inscritos en el jackpot, junto con datos generales de participación.

#### **Información general**

<table><thead><tr><th width="235">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ranking</code></strong></td><td>Muestra el identificador del jackpot consultado.</td></tr><tr><td><strong><code>Número de participantes</code></strong></td><td>Indica la cantidad total de usuarios inscritos en el jackpot.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** El usuario ganador del jackpot no se visualiza de manera inmediata en esta sección.
{% endhint %}

#### **Filtros disponibles**

Permiten refinar la búsqueda de usuarios inscritos en el jackpot.

<table><thead><tr><th width="143">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario Id</code></strong></td><td>Busca un usuario específico mediante su identificador.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Filtra los registros a partir del código de inscripción del usuario.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Permite buscar usuarios por su nombre.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Filtrar los usuarios según su estado <em>(participante o ganador).</em></td></tr></tbody></table>

***

#### **Resultados de consulta**

Muestra el listado de usuarios inscritos según los filtros aplicados.

<table><thead><tr><th width="128">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario</code></strong></td><td>Identificador único del usuario participante dentro del jackpot.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre completo del usuario.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Indica si el usuario se encuentra como participante o ganador dentro del jackpot.</td></tr></tbody></table>

</details>

***

### **6. Edición de Jackpot (✏️)**

Permite modificar la configuración del jackpot mediante un pop-up con los siguientes campos:

<table><thead><tr><th width="162">Campo</th><th width="118">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre asignado al jackpot.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Texto descriptivo del jackpot.</td></tr><tr><td><strong><code>Información</code></strong></td><td>Texto</td><td><p>Información adicional asociada al jackpot.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo no permite el uso de emojis, ya que pueden generar errores en el sistema.</p></div></td></tr><tr><td><strong><code>Imagen</code></strong></td><td>Texto</td><td>URL de la imagen principal que se mostrará en el jackpot.</td></tr><tr><td><strong><code>Imagen 2</code></strong></td><td>Texto</td><td>URL de la imagen de fondo ubicada detrás del contador del jackpot.</td></tr><tr><td><strong><code>GIF</code></strong></td><td>Texto</td><td>URL del archivo GIF que se visualiza sobre las imágenes configuradas.</td></tr><tr><td><strong><code>Video Desktop</code></strong></td><td>Texto</td><td>URL del video mostrado cuando el usuario gana desde un computador.</td></tr><tr><td><strong><code>Video Mobile</code></strong></td><td>Texto</td><td>URL del video mostrado cuando el usuario gana desde un dispositivo móvil.</td></tr><tr><td><strong><code>Aceptar</code></strong></td><td>Botón</td><td>Aplica los cambios realizados y guarda la edición.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Botón</td><td>Cierra la ventana sin guardar cambios.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Todos los campos son obligatorios para guardar los cambios.
{% endhint %}

***

### **7. Validaciones y reglas del negocio**

* Los filtros deben estar correctamente diligenciados para ejecutar la búsqueda.
* El botón **Buscar** ejecuta la consulta con base en los filtros aplicados.
* El botón **Limpiar** restablece los filtros a su estado inicial.
* Todos los campos de edición son obligatorios; no se permite guardar si existen campos vacíos.
* Los cambios realizados se aplican únicamente al hacer clic en **Aceptar**.
* Solo los usuarios con permisos de edición de jackpots pueden modificar la configuración.
* La información actualizada del jackpot se refleja en el detalle _(icono 👁️)_ después de guardar los cambios.
* Los cambios realizados se verán reflejados en la interfaz del usuario sin requerir acciones adicionales.
* Un jackpot puede ser desactivado en cualquier momento mediante la opción correspondiente.

***

### 8. Control de versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99">Versión</th><th width="152.3333740234375">Fecha</th><th width="166.666748046875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>30/04/2026</td><td>Karol Navia</td><td>Reestructuración del manual</td></tr></tbody></table>

</details>
