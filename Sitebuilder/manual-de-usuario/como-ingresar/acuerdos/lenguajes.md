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

Este módulo permite gestionar los textos personalizados que se muestran en la plataforma, reemplazando mensajes originales por contenidos adaptados según el país y el idioma configurados. Además, facilita la administración de estas personalizaciones mediante opciones para crear, editar, buscar y eliminar registros.

### **1. Acceso al módulo**

**Ruta de acceso:** SiteBuilder > Partner > Configuración > Lenguajes

***

### **2. Visualización**

<figure><img src="../../../.gitbook/assets/image (430).png" alt=""><figcaption><p>Figura #1: Captura de pantalla módulo lenguajes.</p></figcaption></figure>

***

### **3. Configuraciones previas**

Antes de realizar las acciones disponibles, es necesario contar con las siguientes configuraciones:

<table><thead><tr><th width="147">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País para el cual se realizará la configuración de los textos personalizados.</td></tr><tr><td><strong><code>Idioma</code></strong></td><td>Idioma sobre el cual se aplicarán las personalizaciones de los textos.</td></tr></tbody></table>

***

### **4. Acciones del usuario**

Desde esta vista podrás realizar las siguientes acciones:

| Campo                           | Descripción                                                                                                                    |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **Agregar nuevo texto**         | Permite crear una nueva personalización mediante el botón **"Agregar"** ubicado en la parte superior derecha.                  |
| **Buscar texto**                | Permite localizar un texto personalizado mediante la barra de búsqueda, utilizando el texto original o el texto personalizado. |
| **Gestionar textos existentes** | Permite visualizar, modificar o eliminar los textos personalizados registrados.                                                |

***

### **5. Gestionar textos personalizados**

Para cada texto personalizado se permiten realizar las siguientes acciones:

<table><thead><tr><th width="196">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Texto original</code></strong></td><td>Corresponde al código o texto existente en la plataforma que será reemplazado por una personalización. Ejemplo: <code>ERROR09</code>.</td></tr><tr><td><strong><code>Texto personalizado</code></strong></td><td>Define el mensaje que se visualizará en reemplazo del texto original.</td></tr></tbody></table>

{% columns %}
{% column width="25%" %}

{% endcolumn %}

{% column width="75%" %}
<table><thead><tr><th width="191">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Editor de contenido</code></strong></td><td>Disponible mediante el ícono de engranaje. Abre un pop-up para visualizar el contenido en mayor detalle y realizar ajustes adicionales, como la aplicación de estilos al texto.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table><thead><tr><th width="195">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Eliminar</code></strong></td><td>Permite eliminar una personalización mediante el ícono de papelera ubicado al final de la fila correspondiente.</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Guarda todas las personalizaciones realizadas en los textos configurados.</td></tr></tbody></table>

***

#### **6. Validaciones y Reglas de Negocio**

* El **Texto original** debe corresponder exactamente al código o mensaje existente en la plataforma para que la personalización sea aplicada correctamente.
* Las modificaciones realizadas sobre el **Texto personalizado** reemplazarán el contenido original durante la visualización en la plataforma.
* Para aplicar cualquier cambio realizado, es obligatorio guardar la configuración.

***

#### **7. Control de Versiones**

<details>

<summary>🔽 Historial de versiones</summary>

| Versión | Fecha      | Autor         | Descripción del cambio |
| ------- | ---------- | ------------- | ---------------------- |
| 1.0     | 03/07/2026 | Ronald Peláez | Creación inicial.      |

</details>
