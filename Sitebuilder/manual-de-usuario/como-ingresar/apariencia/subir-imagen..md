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
---

# Subir imagen.

<mark style="color:$info;">Carga imágenes a la plataforma y generar una URL pública que podrá utilizarse en diferentes configuraciones del sistema, como banners, promociones, eventos, sorteos y demás funcionalidades que requieran imágenes.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso:** Site Builder > Seleccionar Partner > Apariencia > Subir Imagen

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (212).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección subir imagen.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="186">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Cargar archivo</strong></td><td>Abre el explorador de archivos del equipo para seleccionar la imagen que será cargada a la plataforma.</td></tr><tr><td><strong>Copiar URL</strong></td><td>Copia al portapapeles la dirección URL generada para la imagen cargada.</td></tr></tbody></table>

***

### 4. Flujo para cargar una imagen

{% stepper %}
{% step %}
#### Paso 1:

Seleccione el botón **Cargar archivo**.
{% endstep %}

{% step %}
#### Paso 2:

El sistema abrirá el explorador de archivos del equipo para seleccionar la imagen que desea cargar.
{% endstep %}

{% step %}
#### Paso: 3&#x20;

Una vez seleccionada la imagen, el sistema realizará la carga y mostrará una ventana emergente con la URL generada.
{% endstep %}

{% step %}
#### Paso: 4

Seleccione la opción **Copiar URL** para copiar la dirección generada y utilizarla en los módulos que requieran una imagen.
{% endstep %}
{% endstepper %}

***

### 5. Validaciones y reglas del negocio

* El sistema genera una URL únicamente cuando la imagen se carga correctamente.
* La URL generada corresponde a la imagen seleccionada durante la carga.
* La dirección generada puede utilizarse en los módulos que soliciten una URL de imagen.
* Es necesario completar la carga de la imagen antes de poder copiar la URL.
* Si el proceso de carga no finaliza correctamente, el sistema no generará una dirección URL.

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="106">Versión</th><th width="136">Fecha</th><th width="123">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>03/08/2026</td><td>Karol Navia</td><td>Reestructuración adaptada a la plantilla</td></tr></tbody></table>

</details>
