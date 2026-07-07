---
icon: folder
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

# Explorar carpetas

<mark style="color:$info;">El módulo</mark> <mark style="color:$info;"></mark><mark style="color:$info;">**Explorar carpetas**</mark> <mark style="color:$info;"></mark><mark style="color:$info;">permite navegar por la estructura de carpetas disponibles dentro de la plataforma, facilitando el acceso a los informes y tableros (dashboards) según los permisos asignados.</mark>

<mark style="color:$info;">Este apartado reemplaza la funcionalidad anteriormente conocida como</mark> <mark style="color:$info;"></mark><mark style="color:$info;">**“Informes compartidos”**</mark> <mark style="color:$info;"></mark><mark style="color:$info;">en MicroStrategy.</mark>

### 1. Acceso al Módulo

**Ruta de acceso:** Library > Explorar carpetas

***

### 2. Visualización

{% @guideflow/guideflow-embed requestedUrl="https://app.guideflow.com/player/np18mzdtek" %}

***

### 3. Acciones disponibles

{% hint style="warning" %}
**Nota**: El usuario solo podrá visualizar las carpetas e informes para los cuales tenga acceso.
{% endhint %}

<table><thead><tr><th width="195">Acción</th><th>¿Para qué sirve?</th></tr></thead><tbody><tr><td><strong><code>Navegar carpetas</code></strong></td><td>Moverte entre las diferentes carpetas según el área o tema.</td></tr><tr><td><strong><code>Buscar</code></strong></td><td>Encontrar un informe o tablero escribiendo su nombre o alguna palabra clave.</td></tr><tr><td><strong><code>Ordenar</code></strong></td><td>Ver la información organizada por nombre, fecha o responsable.</td></tr><tr><td><strong><code>Seleccionar</code></strong></td><td>Marcar uno o varios informes dentro del listado.</td></tr><tr><td><strong><code>Abrir tablero</code></strong></td><td>Entrar al dashboard para ver la información.</td></tr></tbody></table>

***

### 4. Explorar carpetas

Cuando entras a una carpeta, verás todos los informes o tableros que contiene. Cada uno viene con información que te ayuda a identificarlo rápidamente:

Puedes moverte entre carpetas sin problema y entrar a los tableros directamente desde esta vista cada tablero contiene esta información.

<table><thead><tr><th width="211">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre</code></strong></td><td>Contiene el nombre de como se llama el informe o tablero.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Indica el tipo de tablero <em>(informe o dashboard).</em></td></tr><tr><td><strong><code>Certificado</code></strong></td><td>Indica que el dashboard ha sido validado por la organización y puede considerarse una fuente confiable. Cuando un tablero está certificado, se muestra el ícono <img src="../../.gitbook/assets/image (156).png" alt="" data-size="line"> ; de lo contrario, el campo estará vacío.</td></tr><tr><td><strong><code>Propietario</code></strong></td><td>Muestra el nombre del usuario que creó el informe o tablero.</td></tr><tr><td><strong><code>Fecha de actualización</code></strong></td><td>Indica la fecha de la última modificación del tablero.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Muestra información adicional sobre el contenido.</td></tr><tr><td><strong><code>Acciones</code></strong></td><td>En este apartado se encuentran disponibles las siguientes acciones:</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="89">Ícono</th><th>Descripción</th></tr></thead><tbody><tr><td>ℹ️</td><td>Muestra detalles generales del tablero, como descripción o datos relevantes.</td></tr><tr><td>📤</td><td>Permite compartir el tablero mediante un enlace o agregarlo manualmente.</td></tr><tr><td>📄 PDF</td><td>Permite descargar o exportar el tablero en formato PDF.</td></tr><tr><td>⭐</td><td>Permite marcar el tablero como favorito para acceder rápidamente desde el inicio.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}



***

### 5. Validaciones y reglas del negocio

* El usuario únicamente visualizará las carpetas e informes a los que tenga permisos asignados.
* La información corresponde a la última actualización del contenido.
* El acceso a los tableros depende de la disponibilidad y configuración del informe.

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="100">Versión</th><th width="126">Fecha</th><th width="128">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>04/05/2026</td><td>Karol Navia</td><td>Creación de la sección de exploración de carpetas.</td></tr></tbody></table>

</details>
