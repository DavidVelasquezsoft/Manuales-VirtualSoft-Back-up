---
description: >-
  En esta sección puedes configurar y personalizar el contenido que aparecerá en
  el módulo de Preguntas Frecuentes dentro de la plataforma de usuarios online.
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

# Preguntas frecuentes

<mark style="color:$info;">Administra las categorías y subcategorías de preguntas frecuentes que serán visualizadas en la plataforma. Desde esta sección se pueden crear nuevas categorías, organizar su contenido mediante subcategorías y configurar el texto que será presentado a los usuarios.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso:** SiteBuilder > Partner > Acuerdos > Preguntas frecuentes

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (230).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección preguntas frecuentes.</p></figcaption></figure>

***

### 3.  **Configuraciones previas.**

Antes de realizar las acciones disponibles, es necesario contar con las siguientes configuraciones:

<table><thead><tr><th width="225">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País para el cual se realizará la configuración</td></tr><tr><td><strong><code>Idioma</code></strong></td><td>Idioma en el que estará las configuraciones</td></tr></tbody></table>

***

### 4. Acciones disponibles

<table><thead><tr><th width="140" align="center">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><a href="preguntas-frecuentes.md#id-5.-agregar"><img src="../../../.gitbook/assets/image (483).png" alt="" data-size="line"></a></td><td>Crea una nueva categoría de preguntas frecuentes y habilita los campos para configurar su información.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (485).png" alt="" data-size="line"></td><td>Abre el contenido de la pregunta o sección para configurar el texto que será presentado en la plataforma.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (484).png" alt="" data-size="line"></td><td>Modifica la posición de las categorías, subcategorías o preguntas dentro de la estructura configurada.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (488).png" alt="" data-size="line"></td><td>Muestra los submenús asociados.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (486).png" alt="" data-size="line"></td><td>Crea una subcategoría o subtítulo asociado a una categoría principal.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (487).png" alt=""></td><td>Elimina la categoría, subcategoría o pregunta seleccionada.</td></tr><tr><td align="center"><strong>Buscar</strong></td><td>Localiza preguntas mediante el texto original o personalizado registrado en la configuración.</td></tr></tbody></table>

***

### 5. Agregar

Al seleccionar el botón <img src="../../../.gitbook/assets/image (489).png" alt="" data-size="line">, se presenta una tarjeta para configurar una nueva categoría de preguntas frecuentes.

<table><thead><tr><th width="150" align="center">Campo</th><th width="118">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><img src="../../../.gitbook/assets/image (497).png" alt="" data-size="line"></td><td>Botón</td><td><p>Modifica la posición de las categorías, subcategorías o preguntas para establecer el orden de visualización en la plataforma.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Importante:</strong> El orden establecido en la configuración determina la posición en la que las categorías, subcategorías y preguntas serán presentadas en la plataforma.</p></div></td></tr><tr><td align="center"><strong><code>Ruta de Preguntas</code></strong></td><td>Texto / URL</td><td>Registra la ruta URL interna asociada a la categoría de preguntas frecuentes.</td></tr><tr><td align="center"><strong><code>Título</code></strong></td><td>Texto</td><td>Define el nombre que identificará la categoría de preguntas frecuentes.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (496).png" alt="" data-size="line"></td><td>Botón</td><td>Crea una subcategoría asociada a la categoría principal.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
<table><thead><tr><th width="130" align="center">Campo</th><th width="100">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><strong><code>Ruta de Preguntas</code></strong></td><td>Texto / URL</td><td>Registra la ruta específica asociada a la subcategoría.</td></tr><tr><td align="center"><strong><code>Subtítulo Preguntas</code></strong></td><td>Texto</td><td>Define el nombre que identificará la subcategoría dentro de la categoría principal.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (500).png" alt="" data-size="line"></td><td>Botón</td><td>Abre el contenido de la subcategoría para configurar la información que será presentada en la plataforma.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (501).png" alt=""></td><td>Botón</td><td>Elimina el submenú creado.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="150" align="center">Acción</th><th width="119"></th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><img src="../../../.gitbook/assets/image (498).png" alt=""></td><td>Botón</td><td>Elimina la sección o pregunta seleccionada de la configuración.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (499).png" alt="" data-size="line"></td><td>Botón</td><td><p>Muestra los submenús asociados.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El botón <strong>Desplegar</strong> muestra los submenús asociados a cada política principal y permite consultar la estructura configurada.</p></div></td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio

* Cada categoría debe contar con una **Ruta de Preguntas** y un **Título**.
* Cada subcategoría debe contar con una **Ruta de Preguntas** y un **Subtítulo Preguntas**.
* La barra de **Buscar** consulta las preguntas mediante el texto original o personalizado.
* El contenido HTML registrado en el editor se utiliza para aplicar formatos personalizados al contenido.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="104">Versión</th><th width="125">Fecha</th><th width="117">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>01/08/2026</td><td>Karol Navia</td><td>Reestructuración adaptada a plantilla.</td></tr></tbody></table>

</details>
