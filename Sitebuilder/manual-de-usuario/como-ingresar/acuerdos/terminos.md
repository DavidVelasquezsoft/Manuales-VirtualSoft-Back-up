---
description: >-
  Permite crear, editar, ordenar y eliminar los términos y condiciones de la
  plataforma de usuarios online, además de gestionar submenús asociados para
  organizar su contenido.
---

# Términos

### **1. Acceso al módulo**

**Ruta de acceso:** SiteBuilder > Partner > Acuerdos > Términos&#x20;

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (396).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección términos y condiciones.</p></figcaption></figure>

***

### **3. Configuraciones previas.**

Antes de realizar las acciones disponibles, es necesario contar con las siguientes configuraciones:

<table><thead><tr><th width="220">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País para el cual se realizará la configuración</td></tr><tr><td><strong><code>Idioma</code></strong></td><td>Idioma en el que estará las configuraciones</td></tr></tbody></table>

***

### **4. Acciones del usuario**

Desde esta vista podrás realizar las siguientes acciones:

<table><thead><tr><th width="220">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="terminos.md#id-5.-gestionar-terminos-y-condiciones"><strong>Gestionar términos existentes.</strong></a></td><td>Permite, visualizar, modificar y reordenar los términos y condiciones registrados y además sus subsecciones (<em>0</em>).</td></tr><tr><td><strong>Agregar nuevo término</strong></td><td>Permite crear un nuevo término utilizando el botón <strong>“Agregar”</strong> ubicado en la parte superior derecha; el registro se añadirá al <strong>final</strong> de la lista de términos existente.</td></tr><tr><td>B<strong>uscar</strong></td><td>En la parte superior se encuentra un campo de texto que permite buscar un termino en especifico.</td></tr></tbody></table>

### 5. Gestionar términos y condiciones.

Para cada termino se permiten hacer las siguientes acciones:

<table><thead><tr><th width="177.77777099609375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ordenar</code></strong></td><td>Ordena los términos y condiciones mediante funcionalidad de arrastrar y soltar, ubicándolos en la posición deseada dentro de la lista de términos.</td></tr><tr><td><strong><code>Ingresar identificadores</code></strong></td><td>Define la información básica del término:</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="136.29638671875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ruta de TyC</code></strong></td><td>Especifica la URL o ruta donde se visualizarán los términos y condiciones.</td></tr><tr><td><strong><code>Título</code></strong></td><td>Define el nombre o encabezado principal que tendrá el término.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="177.77783203125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Desplegar termino</code></strong></td><td>Permite expandir el término para visualizar sus submenús asociados.</td></tr><tr><td><strong><code>Agregar </code></strong><em><strong><code>(Submenú)</code></strong></em></td><td>Agregar un submenú al término principal para organizar secciones adicionales; cada submenú debe configurarse con los siguientes campos:</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="136.29638671875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ordenar</code></strong></td><td><p>Permite reorganizar los submenús mediante arrastrar y soltar dentro del mismo término.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> No es posible mover submenús entre diferentes términos.</p></div></td></tr><tr><td><strong><code>Ruta de TyC</code></strong></td><td>Especifica la URL o ruta donde se visualizarán los términos y condiciones.</td></tr><tr><td><strong><code>Subtítulo TyC</code></strong></td><td>Define el nombre o encabezado principal que tendrá el submenú dentro del término.</td></tr><tr><td><strong><code>Texto</code></strong></td><td>Abre un modal para ingresar el contenido que se mostrará en el submenú.</td></tr><tr><td><strong><code>Eliminar</code></strong></td><td>Permite eliminar el submenú junto con toda su información.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="177.77783203125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Botón Eliminar</code></strong></td><td>Eliminar completamente un término, incluyendo todos sus submenús asociados.</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Guarda completamente todos los términos y condiciones, incluyendo el orden y todos sus submenús asociados.</td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* El orden establecido determinará la visualización final de los términos en la plataforma.
* Para aplicar cualquier cambio realizado (_orden, contenido u otros_), es obligatorio hacer clic en el botón **Guardar**.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="113.4073486328125">Versión</th><th width="143.59259033203125">Fecha</th><th width="179.8148193359375">Autor</th><th>Descripción del cambio</th></tr></thead><tbody><tr><td>1.0</td><td>20/10/2025</td><td>Karol Navia</td><td>Creación inicial </td></tr><tr><td>1.1</td><td>06/05/2026</td><td>David Velasquez</td><td>Actualización de manual e incorporación de nuevos campos.</td></tr></tbody></table>

</details>
