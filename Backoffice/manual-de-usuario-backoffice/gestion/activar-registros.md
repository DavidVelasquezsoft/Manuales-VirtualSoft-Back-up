---
description: Permite activar usuarios en la plataforma que se registraron previamente.
---

# Activar Registros

### 1. Acceso al Módulo

**Ruta de Acceso**: Backoffice > Gestión > Activar Registros

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (383).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección activar registro.</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="activar-registros.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar por un usuario de manera obligatoria.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="activar-registros.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

### 4. Filtros

Para activar a un usuario, se debe ingresar al menos uno de los siguientes filtros:

<table><thead><tr><th width="159">Campos</th><th width="124">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cédula del cliente</code></strong></td><td>Numérico</td><td>Permite ingresar el número de documento del usuario a activar.</td></tr><tr><td> <strong><code>Email del cliente</code></strong></td><td>Correo electrónico</td><td>Permite ingresar el email del usuario a activar.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: Si el usuario ya se encuentra activado, se mostrará un **pop-up** indicando que el usuario ya está registrado o no se encuentra en la base de datos.
{% endhint %}

### 5. Resultado de Consulta

Al ingresar alguno de estos datos y realizar la consulta, se desplegará la información del usuario para su activación, incluyendo:

<table><thead><tr><th width="184">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Número de cliente</code></strong></td><td>Identificador único asignado al cliente dentro de la plataforma.</td></tr><tr><td><strong><code>Nombre del cliente</code></strong></td><td>Nombre completo del cliente asociado al registro.</td></tr><tr><td><strong><code>País</code></strong></td><td>País al que pertenece el cliente según su registro u operación.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda asociada al cliente para sus transacciones y operaciones.</td></tr></tbody></table>

En la parte inferior se encuentra el botón **“Activar”**, que finaliza el proceso de activación del usuario. Al seleccionarlo, el sistema mostrará un mensaje de confirmación para validar la acción.

***

### 6. Control de Versiones

<details>

<summary>🔽Historial de versiones </summary>

<table><thead><tr><th width="104.88885498046875">Versión</th><th width="142">Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>07/01/2026</td><td>David Velasquez</td><td>Actualización de formato</td></tr></tbody></table>

</details>
