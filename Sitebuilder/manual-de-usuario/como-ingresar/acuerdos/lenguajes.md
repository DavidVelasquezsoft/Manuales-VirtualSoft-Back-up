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

# Lenguajes

<mark style="color:$info;">Este módulo permite gestionar los textos personalizados que se muestran en la plataforma, reemplazando mensajes originales por contenidos adaptados según el país y el idioma configurados. Además, facilita la administración de estas personalizaciones mediante opciones para crear, editar, buscar y eliminar registros</mark>.

### **1. Acceso al módulo**

**Ruta de acceso:** SiteBuilder > Partner > Configuración > Lenguajes

***

### **2. Visualización**

<figure><img src="../../../.gitbook/assets/image (502).png" alt=""><figcaption><p>Figura #1: Captura de pantalla módulo lenguajes.</p></figcaption></figure>

***

### **3. Configuraciones previas**

Antes de realizar las acciones disponibles, es necesario contar con las siguientes configuraciones:

<table><thead><tr><th width="147">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País para el cual se realizará la configuración de los textos personalizados.</td></tr><tr><td><strong><code>Idioma</code></strong></td><td>Idioma sobre el cual se aplicarán las personalizaciones de los textos.</td></tr></tbody></table>

***

### **4. Acciones del usuario**

Desde esta vista podrás realizar las siguientes acciones:

<table><thead><tr><th width="188">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Agregar nuevo texto</strong></td><td>Permite crear una nueva personalización mediante el botón <strong>"</strong><img src="../../../.gitbook/assets/image (504).png" alt="" data-size="line"><strong>"</strong> ubicado en la parte superior derecha.</td></tr><tr><td><strong>Buscar texto</strong></td><td>Permite localizar un texto personalizado mediante la barra de búsqueda, utilizando el texto original o el texto personalizado.</td></tr><tr><td><strong>Gestionar textos existentes</strong></td><td>Permite visualizar, modificar o eliminar los textos personalizados registrados.</td></tr></tbody></table>

***

### **5. Gestionar textos personalizados**

Para cada texto personalizado se permiten realizar las siguientes acciones:

<table><thead><tr><th width="150">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Texto original</code></strong></td><td>Corresponde al código o texto existente en la plataforma que será reemplazado por una personalización. Ejemplo: <code>ERROR09</code>.</td></tr><tr><td><strong><code>Texto personalizado</code></strong></td><td>Define el mensaje que se visualizará en reemplazo del texto original.</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Editor de contenido</code></strong></td><td>Disponible mediante el ícono (<img src="../../../.gitbook/assets/image (505).png" alt="" data-size="line">). Abre un pop-up para visualizar el contenido en mayor detalle y realizar ajustes adicionales, como la aplicación de estilos al texto.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table><thead><tr><th width="129">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><img src="../../../.gitbook/assets/image (507).png" alt=""></td><td>Elimina una personalización mediante el ícono de papelera ubicado al final de la fila correspondiente.</td></tr><tr><td><img src="../../../.gitbook/assets/image (509).png" alt=""></td><td>Guarda todas las personalizaciones realizadas en los textos configurados.</td></tr></tbody></table>

***

### **6. Validaciones y Reglas de Negocio**

* El **Texto original** debe corresponder exactamente al código o mensaje existente en la plataforma para que la personalización sea aplicada correctamente.
* Las modificaciones realizadas sobre el **Texto personalizado** reemplazarán el contenido original durante la visualización en la plataforma.
* Para aplicar cualquier cambio realizado, es obligatorio guardar la configuración.

***

### **7. Control de Versiones**

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="103">Versión</th><th width="137">Fecha</th><th width="149">Autor</th><th>Descripción del cambio</th></tr></thead><tbody><tr><td>1.0</td><td>03/07/2026</td><td>Ronald Peláez</td><td>Creación inicial.</td></tr><tr><td>1.1</td><td>01/08/2026</td><td>Karol Navia </td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33465">Arreglos en la estructura</a></td></tr></tbody></table>

</details>
