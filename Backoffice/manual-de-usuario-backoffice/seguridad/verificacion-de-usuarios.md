---
description: >-
  Permite consultar y analizar información relacionada con el proceso de
  validación de los usuarios registrados en el sistema.
---

# Verificación de usuarios

### 1. Acceso al Módulo:

**Ruta de Acceso:** Backoffice > Seguridad > Verificación de Usuario

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (622).png" alt=""><figcaption><p>Figura#1: Captura de pantalla verificación de usuario</p></figcaption></figure>

### 🧑‍💻3. Acciones de usuario

<table><thead><tr><th width="153">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="verificacion-de-usuarios.md#id-3.1.-resultados-de-la-busqueda"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos ya sea en la vista detallada o total.</td></tr><tr><td><a href="verificacion-de-usuarios.md#id-4.-filtros"><strong>Filtrar</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos.</td></tr><tr><td><a href="verificacion-de-usuarios.md#id-3.2.-agregar-verificacion"><strong>Agregar</strong></a></td><td>Permite agregar la verificación a un usuario existente.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite descargar la información <em>(filtrada o completa)</em> en formato Excel o PDF. Para ello, ubica el botón <strong>Exportar</strong> en la parte inferior derecha de la página y selecciona el formato deseado para iniciar la descarga.</td></tr></tbody></table>

#### **🔎 3.1. Filtros:**

<table><thead><tr><th width="125">Filtro</th><th width="123">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Selector de fecha</td><td>Define el rango de fechas en el que se desea visualizar los resultados.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Filtra los resultados utilizando el identificador único del usuario. Este identificador se asigna automáticamente cuando el usuario crea su cuenta en la plataforma de usuarios online.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el estado del proceso de verificación.<br><em>(Ejemplo: Todos / Pendiente / Aprobada , etc)</em></td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra los resultados según el país del usuario.</td></tr><tr><td><strong><code>Origen</code></strong></td><td>Lista desplegable</td><td>Permite filtrar según el origen del registro, ya sea (<em>Manual o por proveedor</em>).</td></tr><tr><td><strong><code>Tipo reporte</code></strong></td><td>Lista desplegable</td><td>Permite clasificar los registros dependiendo si fueron creados mediante <strong>verificación de datos</strong> o a través de una <strong>actualización de información</strong>.</td></tr><tr><td><strong><code>Tipo decisión</code></strong></td><td>Lista desplegable</td><td>Permite identificar si la decisión asociada al registro fue tomada automáticamente por el sistema o de forma manual por un operador.</td></tr><tr><td><strong><code>Motivo de rechazo</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por el motivo del rechazo de la verificación en caso de que halla sido rechazada.</td></tr><tr><td><strong><code>Tipo</code></strong> </td><td>Selector</td><td>Permite seleccionar el formato de salida del reporte.<em>(Detallado / Totalizado.)</em></td></tr><tr><td><strong><code>Proveedor de verificación</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por el proveedor de verificación en especifico en el que se hizo el registro.</td></tr></tbody></table>

#### ➕ 3.2. Agregar verificación

Permite verificar a un usuario previamente registrado en la plataforma mediante el ingreso de la siguiente información:

<table data-full-width="false"><thead><tr><th width="139.83331298828125">Campo</th><th width="479.416748046875">Descripción</th><th align="center">¿Obligatorio?</th></tr></thead><tbody><tr><td><strong><code>ID usuario</code></strong></td><td><p>Ingresa el identificador único del usuario a verificar.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Debes hacer clic en el botón "<strong>Consultar"</strong> para que el sistema verifique si el usuario existe y muestre automáticamente la información asociada.</p></div></td><td align="center">✅</td></tr><tr><td><strong><code>Fecha de nacimiento</code></strong></td><td>Ingresa la fecha de nacimiento del usuario.</td><td align="center">✅</td></tr><tr><td><strong><code>Segundo nombre</code></strong></td><td>Ingresa el segundo del usuario.</td><td align="center">✅</td></tr><tr><td><strong><code>Segundo apellido</code></strong></td><td>Permite ingresar el segundo apellido del usuario</td><td align="center">✅</td></tr><tr><td><strong><code>DNI anterior</code></strong></td><td>Permite adjuntar la imagen de el documento anterior del usuario.</td><td align="center">✅</td></tr><tr><td><strong><code>DNI posterior</code></strong></td><td>Permite adjuntar la imagen de el documento posterior del usuario.</td><td align="center">✅</td></tr></tbody></table>

#### **📋 3.3. Resultados de la búsqueda**

{% tabs %}
{% tab title="Visualización Detallada" %}
Cuando se selecciona la opción **Detallado**, el sistema muestra una tabla con información completa de cada proceso de verificación.

<table><thead><tr><th width="145">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>🔍</code></strong></td><td>Al seleccionar este ícono, se abrirá una ventana emergente desde la cual podrás aprobar manualmente la solicitud de verificación y consultar información del usuario. <br><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/seguridad/verificacion-de-usuarios#informacion-detallada-por-usuario" class="button secondary">Información de ventana emergente</a></td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al usuario.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del proceso de verificación.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha en que se realizó la verificación.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario verificado.</td></tr><tr><td><strong><code>Usuario Aprueba</code></strong></td><td>Nombre del usuario que realizó la aprobación de la verificación <em>(cuando esta se hizo de forma manual).</em></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del proceso <em>(No ejecutado, aprobada, rechazada, etc.)</em>.</td></tr><tr><td><strong><code>Usuario Genera</code></strong></td><td>Nombre del usuario que inició el proceso de verificación.</td></tr><tr><td><strong><code>Nota</code></strong></td><td>Observaciones o comentarios asociados al proceso.</td></tr></tbody></table>
{% endtab %}

{% tab title="Visualización Totalizada" %}
Cuando se selecciona la opción **Totalizado**, el sistema muestra un resumen estadístico con los totales de cada estado del proceso de verificación.

<table><thead><tr><th width="200">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Iniciadas</code></strong></td><td>Cantidad total de verificaciones iniciadas.</td></tr><tr><td><strong><code>Pendientes</code></strong></td><td>Cantidad total de verificaciones pendientes.</td></tr><tr><td><strong><code>Aprobadas</code></strong></td><td>Cantidad total de verificaciones aprobadas.</td></tr><tr><td><strong><code>Rechazadas</code></strong></td><td>Cantidad total de verificaciones rechazadas.</td></tr><tr><td><strong><code>No Ejecutadas</code></strong></td><td>Cantidad total de verificaciones no ejecutadas.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

<details>

<summary>Información detallada por usuario</summary>

Desde la ventana emergente desplegada al seleccionar los detalles del usuario se podrán visualizar los siguientes campos:&#x20;

<table><thead><tr><th width="245">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único de la cuenta verificada del usuario.</td></tr><tr><td><strong><code>Primer nombre</code></strong></td><td>Primer nombre del usuario.</td></tr><tr><td><strong><code>Segundo nombre</code></strong></td><td>Segundo nombre del usuario <em>(Si aplica).</em></td></tr><tr><td><strong><code>Apellido</code></strong></td><td>Primer apellido del usuario.</td></tr><tr><td><strong><code>Segundo apellido</code></strong></td><td>Segundo apellido del usuario.</td></tr><tr><td><strong><code>Género</code></strong></td><td>Genero de nacimiento del usuario.</td></tr><tr><td><strong><code>Fecha de nacimiento</code></strong> </td><td>Fecha en la que nació el usuario.</td></tr><tr><td><strong><code>Celular</code></strong></td><td>Número de celular registrado por el usuario.</td></tr><tr><td><strong><code>País residencia</code></strong></td><td>País de residencia del usuario</td></tr><tr><td><strong><code>Provincia / Región residencia</code></strong></td><td>Provincia o región en la que el usuario reside.</td></tr><tr><td><strong><code>Ciudad Residencia</code></strong></td><td>Ciudad en la cual el usuario reside.</td></tr><tr><td><strong><code>Dirección</code></strong></td><td>Dirección de vivienda del usuario</td></tr><tr><td><strong><code>Tipo de documento</code></strong></td><td>Tipo de documento de identidad con el que el usuario realizó el registro</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Número de documento de identidad del usuario.</td></tr><tr><td><strong><code>Email</code></strong></td><td>Correo electrónico del usuario.</td></tr></tbody></table>

Campos enviados luego de que el usuario realiza el proceso de verificación por medio del proveedor _(JUMIO)_

<table><thead><tr><th width="235">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nuevo primer nombre</code></strong></td><td>Nombre actualizado luego de realizar el proceso de verificación</td></tr><tr><td><strong><code>Nuevo segundo nombre</code></strong></td><td>Segundo nombre actualizado luego de realizar el proceso de verificación</td></tr><tr><td><strong><code>Nuevo primer apellido</code></strong></td><td>Primer apellido del usuario actualizado.</td></tr><tr><td><strong><code>Nuevo segundo apellido</code></strong></td><td>Segundo apellido del usuario actualizado.</td></tr><tr><td><strong><code>Nueva fecha de nacimiento</code></strong></td><td>Fecha de nacimiento del usuario actualizada.</td></tr><tr><td><strong><code>DNI Anterior</code></strong></td><td>Foto del documento de identidad por la parte frontal del documento de identidad.</td></tr><tr><td><strong><code>DNI Posterior</code></strong></td><td>Foto del documento de identidad de la parte trasera del documento de identidad.</td></tr><tr><td><strong><code>Imagen verificación</code></strong></td><td>Imagen del usuario tomada al momento de realizar la verificación con el proveedor.</td></tr></tbody></table>

Desde esta ventana emergente será posible aceptar de manera manual la verificación de la cuenta del usuario o rechazarla.

</details>

***

### **✅ 4. Validaciones y Reglas de Negocio**

* Los filtros pueden combinarse entre sí para refinar la búsqueda.
* Si no se define ningún filtro, el sistema mostrará todos los registros disponibles del rango de fechas seleccionado.
* El tipo de visualización _(Detallado o Totalizado)_ determina el formato de salida del reporte.
* La visualización de imágenes faciales y de documentos estará controlada por un **permiso.**

***

### **🕒 5. Control de Versiones**

<table><thead><tr><th width="109">Versión</th><th width="148">Fecha</th><th width="178">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>12/11/2025</td><td>Karol Navia</td><td>Documento inicial.</td></tr><tr><td>1.1</td><td>10/12/2025</td><td>David velasquez</td><td>Actualización y reestructuración del manual.</td></tr><tr><td>1.2</td><td>06/01/2026</td><td>David velasquez</td><td>Incorporación del campo <strong><code>Imagen facial</code></strong></td></tr><tr><td>1.3</td><td>15/01/2026</td><td>Ronald Peláez</td><td>Ajuste en formato y campo <strong><code>Imagen verificación</code></strong></td></tr></tbody></table>
