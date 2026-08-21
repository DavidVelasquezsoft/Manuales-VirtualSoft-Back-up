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

**Ruta de Acceso:**  > Cupón de apuestas

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (457).png" alt=""><figcaption><p>Figura #1: Captura de pantalla mensajes.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="134.4444580078125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Agregar</strong></td><td>Abre el formulario para crear un nuevo mensaje asociado al cupón de apuestas.</td></tr><tr><td><strong>Editar</strong></td><td>Habilita la modificación de la información configurada en un mensaje existente.</td></tr><tr><td><strong>Actualizar</strong></td><td>Guarda las modificaciones realizadas sobre un mensaje existente.</td></tr><tr><td><strong>Visualizar</strong> </td><td>Presenta una vista previa de cómo se mostrará el mensaje en la plataforma.</td></tr><tr><td><strong>Activar</strong></td><td>Activa un mensaje para que pueda ser mostrado de acuerdo con su configuración de vigencia.</td></tr><tr><td><strong>Desactivar</strong> </td><td>Desactiva un mensaje para evitar su visualización en la plataforma.</td></tr><tr><td><strong>Eliminar</strong> </td><td>Elimina el mensaje seleccionado.</td></tr><tr><td><strong>Guardar</strong></td><td>Almacena los cambios realizados para que sean aplicados en la plataforma de usuarios.</td></tr></tbody></table>

***

### 4. Agregar

Al seleccionar **Agregar**, se presenta un calendario donde se debrea estanblecer

ESTE MODULO CUEBNTA CON 2 SECCIONES ACTIBPOS Y EXPIRADOS LLOS ACTIVOS SON : Y LOS EXPIRAFDOS

<table><thead><tr><th width="143.3333740234375">Campo</th><th width="120">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha y Hora Inicio</code></strong></td><td>Fecha y hora</td><td>Establece la fecha y hora a partir de la cual comenzará a mostrarse el mensaje.</td></tr><tr><td><strong><code>Fecha y HORA Fin</code></strong></td><td>Fecha y hora</td><td>Establece la fecha y hora hasta la cual estará vigente el mensaje.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Si ya existe un mensaje configurado dentro del mismo rango de fechas, el sistema mostrará el mensaje: **"Ya existe un mensaje activo en este período. Ajuste las fechas o edite el mensaje existente."**
{% endhint %}

Una vez completada la información, selecciona Aceptar&#x20;

***

#### 5. Configuraciones&#x20;

Los mensajes creados se presentan mediante cards, en las cuales se muestra la información configurada y las acciones disponibles para administrar cada registro.

Los mensajes activos corresponden a aquellos que se encuentran habilitados y dentro del período de vigencia configurado.

<table><thead><tr><th width="190">Campo / Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha Inicio</code></strong></td><td>Presenta la fecha y hora desde la cual se encuentra vigente el mensaje.</td></tr><tr><td><strong><code>Fecha Fin</code></strong></td><td>Presenta la fecha y hora hasta la cual se encuentra vigente el mensaje.</td></tr><tr><td><strong><code>Título</code></strong></td><td>título configurado para el mensaje.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Establece el contenido configurado para el mensaje.</td></tr><tr><td><strong>Visualizar (👁️)</strong></td><td>Presenta una vista previa del mensaje tal como será mostrado en la plataforma.</td></tr><tr><td><strong>Desactivar (⛔)</strong></td><td>Deshabilita el mensaje seleccionado.</td></tr><tr><td><strong>Eliminar (🗑️)</strong></td><td>Elimina el mensaje seleccionado.</td></tr><tr><td>Activar</td><td></td></tr></tbody></table>

***

#### 8. Validaciones y reglas del negocio

* La **Fecha Inicio** establece el momento a partir del cual el mensaje puede comenzar a mostrarse.
* La **Fecha Fin** establece el momento en que finaliza la vigencia del mensaje.
* No se pueden configurar dos mensajes activos dentro del mismo rango de fechas.
* Cuando existe un mensaje activo en el período seleccionado, el sistema muestra el mensaje: **"Ya existe un mensaje activo en este período. Ajuste las fechas o edite el mensaje existente."**
* Los mensajes cuyo período de vigencia finalizó se clasifican como **Expirados**.
* Los mensajes habilitados se clasifican como **Activos** cuando se encuentran dentro de su período de vigencia.
* La opción **Desactivar** cambia el estado del mensaje y evita su visualización en la plataforma.
* La opción **Activar** habilita nuevamente el mensaje.
* Las modificaciones realizadas sobre un mensaje se almacenan mediante el botón **Actualizar**.
* Para que las modificaciones sean reflejadas en la plataforma de usuarios, se debe seleccionar el botón **Guardar** de la barra lateral.

***

#### 9. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="108">Versión</th><th width="130">Fecha</th><th width="134.4444580078125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21/08/2026</td><td><strong>Karol Navia</strong></td><td>Reestructuración adaptada a plantilla.</td></tr></tbody></table>

</details>
