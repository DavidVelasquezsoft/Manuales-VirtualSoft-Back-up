---
description: >-
  Desde este apartado de la herramienta podrás configurar y automatizar mensajes
  dinámicos en el apartado del cupón de apuestas de usuarios online que estés
  configurando.
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
---

# Cupón de apuestas.

<mark style="color:$info;">Administra los mensajes asociados al cupón de apuestas que serán visualizados por los usuarios en la plataforma. Desde este módulo se pueden crear, actualizar, visualizar, activar, desactivar y eliminar mensajes, de acuerdo con su período de vigencia.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso:** Site Builder > Seleccionar Partner > Mensajes > Cupón de apuestas

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (457).png" alt=""><figcaption><p>Figura #1: Captura de pantalla mensajes.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="cupon-de-apuestas..md#id-4.-agregar"><strong>Agregar</strong></a></td><td>Inicia la creación de un nuevo mensaje y despliega el calendario para configurar su período de vigencia.</td></tr><tr><td><strong>Visualizar (👁️)</strong></td><td>Presenta una vista previa de cómo será visualizado el mensaje en la plataforma.</td></tr><tr><td><strong>Activar (✅)</strong></td><td>Habilita el mensaje seleccionado para su visualización.</td></tr><tr><td><strong>Desactivar (⛔)</strong></td><td>Deshabilita el mensaje seleccionado para evitar su visualización en la plataforma.</td></tr><tr><td><strong>Eliminar (🗑️)</strong></td><td>Elimina el mensaje seleccionado.</td></tr><tr><td><strong>Guardar</strong></td><td>Almacena los cambios realizados para que sean aplicados en la plataforma de usuarios.</td></tr></tbody></table>

***

### 4. Agregar

Al seleccionar el botón [<img src="../../../.gitbook/assets/image (459).png" alt="" data-size="line">](cupon-de-apuestas..md#id-4.-agregar), se despliega un calendario para establecer el período durante el cual estará vigente el mensaje.

En el calendario se deben configurar los siguientes campos:

<table><thead><tr><th width="190">Campo</th><th width="130">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha y hora inicio</code></strong></td><td>Fecha y hora</td><td>Establece la fecha y hora a partir de la cual el mensaje podrá ser visualizado en la plataforma.</td></tr><tr><td><strong><code>Fecha y hora fin</code></strong></td><td>Fecha y hora</td><td>Establece la fecha y hora en la que finalizará la vigencia del mensaje.</td></tr></tbody></table>

Una vez establecido el período de vigencia, selecciona<img src="../../../.gitbook/assets/image (458).png" alt="" data-size="line">para aplicar el rango de fecha y hora al nuevo mensaje.

{% hint style="warning" %}
**Nota:** Si ya existe un mensaje configurado dentro del mismo rango de fechas, el sistema mostrará el mensaje: **"Ya existe un mensaje activo en este período. Ajuste las fechas o edite el mensaje existente."**
{% endhint %}

***

### 5. Configuraciones

Después de establecer el rango de fecha y hora, se genera una nueva card para completar la configuración del mensaje.

<table><thead><tr><th width="190">Campo</th><th width="130">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha inicio</code></strong></td><td>Fecha</td><td>Presenta la fecha configurada para el inicio de vigencia del mensaje.</td></tr><tr><td><strong><code>Hora inicio</code></strong></td><td>Hora</td><td>Presenta la hora a partir de la cual iniciará la vigencia del mensaje.</td></tr><tr><td><strong><code>Fecha fin</code></strong></td><td>Fecha</td><td>Presenta la fecha configurada para la finalización del mensaje.</td></tr><tr><td><strong><code>Hora fin</code></strong></td><td>Hora</td><td>Presenta la hora en la que finalizará la vigencia del mensaje.</td></tr><tr><td><strong><code>Título</code></strong></td><td>Texto</td><td>Registra el título que identificará el mensaje.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Registra el contenido del mensaje que será mostrado al usuario en el cupón de apuestas.</td></tr><tr><td><strong><code>Activar (✅)/Desactivar (⛔)</code></strong></td><td>Botón</td><td>Habilita o Deshabilita el mensaje.</td></tr><tr><td><strong><code>Visualizar (👁️)</code></strong></td><td>Botón</td><td>Presenta una vista previa de cómo se mostrará el mensaje al usuario.</td></tr><tr><td><strong><code>Eliminar (🗑️)</code></strong></td><td>Botón</td><td>Elimina el mensaje seleccionado.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:**

* Los mensajes pasan a la sección **Expirados** cuando finaliza el período de vigencia establecido en la configuración de fecha y hora.&#x20;
* Para que los cambios realizados se reflejen en la plataforma de usuarios, es necesario seleccionar el botón **Guardar** ubicado en la barra lateral.
{% endhint %}

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
