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

# Menú

Administra las categorías y los elementos gráficos que serán visualizados en el menú principal de la plataforma. Desde esta sección es posible crear categorías personalizadas y configurar GIF promocionales que serán presentados a los usuarios.

***

### 1. Acceso al Módulo

**Ruta de Acceso:** Backoffice > Configuración > Menú

***

### 2. **Configuraciones previas.**

Antes de realizar las acciones disponibles en la sección pop ups, es necesario contar con las siguientes configuraciones:

<table><thead><tr><th width="130">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Pais</code></strong></td><td>Indica el país para el cual se realizará la configuración</td></tr><tr><td><strong><code>Dispositivo</code></strong></td><td>Selecciona el dispositivo que se utilizará para realizar las configuraciones.</td></tr><tr><td><strong><code>modo de Logueo</code></strong></td><td>Selecciona el Modo de logueo que </td></tr></tbody></table>

***

#### 3. Acciones disponibles

<table><thead><tr><th width="157">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="menu.md#id-4.-agregar"><strong>Agregar (+)</strong></a></td><td>Crea un nuevo registro según el tipo de configuración seleccionado.</td></tr><tr><td><strong>Guardar</strong></td><td>Almacena la configuración realizada.</td></tr><tr><td><strong>Mover</strong></td><td>Modifica la posición de un elemento dentro del menú.</td></tr><tr><td><strong>Eliminar</strong></td><td>Elimina el registro seleccionado.</td></tr></tbody></table>

***

#### 4. Agregar

{% tabs %}
{% tab title="Categorías de Menú" %}
Crear nuevas accesos que serán visualizados dentro del menú principal de la plataforma.

**Visualización**

<figure><img src="../../../.gitbook/assets/image (444).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Categorias de menú.</p></figcaption></figure>

**Configuración**

<table><thead><tr><th width="131" align="center">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><img src="../../../.gitbook/assets/image (440).png" alt="" data-size="line"></td><td>Agrega una nueva categoría</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (443).png" alt="" data-size="line"></td><td>Sube la imagen que identificará la categoría dentro del menú.</td></tr><tr><td align="center"><strong><code>Título</code></strong></td><td>Registra el nombre que será mostrado para la categoría.</td></tr><tr><td align="center"><strong><code>URL de redirección</code></strong></td><td>Registra la dirección web a la que será dirigido el usuario al presionar la categoría.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (438).png" alt="" data-size="line"></td><td><p>Modifica la posición de la categoría dentro del menú.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Importante:</strong><br>El orden en que se organizan las categorías en esta sección corresponde al mismo orden en que serán visualizadas dentro de la plataforma.</p></div></td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (439).png" alt="" data-size="line"></td><td>Elimina la categoría seleccionada.</td></tr></tbody></table>
{% endtab %}

{% tab title="GIF" %}
Incorpora elementos gráficos animados al inicio del menú principal para destacar promociones, campañas o accesos específicos.

**Visualización**

<figure><img src="../../../.gitbook/assets/image (445).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Gif.</p></figcaption></figure>

**Configuración**

<table><thead><tr><th width="194">Campo</th><th width="124">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td></td><td></td><td></td></tr><tr><td>Vista Previa</td><td>Imagen</td><td></td></tr><tr><td><strong><code>Fondo degradado</code></strong></td><td>Selector de color</td><td>Define los colores que conformarán el fondo del GIF.</td></tr><tr><td><strong><code>Imagen izquierda</code></strong></td><td>Imagen</td><td>Registra la imagen que acompañará el GIF al lado derecho.</td></tr><tr><td><strong><code>GIF</code></strong></td><td>Imagen animada</td><td>Registra el archivo GIF que será visualizado en la plataforma.</td></tr><tr><td><strong><code>URL de redirección</code></strong></td><td>URL</td><td>Registra la dirección web que será redirigido al presionar el GIF.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

#### 5. Validaciones y reglas del negocio

* Las imágenes utilizadas para las categorías deben estar en formato **PNG**.
* El tamaño máximo permitido para las imágenes es de **200 KB**.
* Los GIF siempre se visualizarán al inicio del menú principal.
* El orden configurado para las categorías corresponde al mismo orden en que serán presentadas en la plataforma.
* Las modificaciones realizadas se almacenan únicamente al hacer clic en **Guardar**.

***

#### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="108.3333740234375">Versión</th><th width="141">Fecha</th><th width="118">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>05/08/2026</td><td><strong>Karol Navia</strong></td><td>Reestructuración adaptado a plantilla.</td></tr></tbody></table>

</details>
