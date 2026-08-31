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

# Responsable.

<mark style="color:$info;">Administra las políticas de juego responsable que serán visualizadas en la plataforma. Desde esta sección se pueden consultar las políticas existentes, crear nuevas políticas y organizar su estructura mediante submenús.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso:** SiteBuilder > Partner > Acuerdos > Responsable

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (228).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Juego responsable.</p></figcaption></figure>

***

### 3. **Configuraciones previas.**

Antes de realizar las acciones disponibles, es necesario contar con las siguientes configuraciones:

<table><thead><tr><th width="220">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País para el cual se realizará la configuración</td></tr><tr><td><strong><code>Idioma</code></strong></td><td>Idioma en el que estará las configuraciones</td></tr></tbody></table>

***

### 4. Acciones disponibles

<table><thead><tr><th width="131.63641357421875" align="center">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><a href="responsable..md#id-4.-agregar"><img src="../../../.gitbook/assets/image (450).png" alt="" data-size="line"></a></td><td>Crea una nueva política de juego responsable y configura la información que será presentada en la plataforma.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (471).png" alt="" data-size="line"></td><td>Modifica la posición de las políticas de juego responsable para establecer el orden en que serán visualizadas en la plataforma.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (453).png" alt="" data-size="line"></td><td>Crea un submenú asociado a una política principal para organizar su contenido.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (472).png" alt="" data-size="line"></td><td>Muestra los submenús asociados a una política principal.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (473).png" alt=""></td><td>Elimina una política de juego responsable o un submenú configurado.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (474).png" alt="" data-size="line"></td><td>Almacena las configuraciones realizadas en el módulo.</td></tr></tbody></table>

***

### 5. Agregar

Al seleccionar el botón <img src="../../../.gitbook/assets/image (475).png" alt="" data-size="line">, se presenta el formulario para configurar una nueva política de juego responsable.

<table><thead><tr><th width="141.3636474609375" align="center">Campo</th><th width="115.1817626953125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><img src="../../../.gitbook/assets/image (476).png" alt="" data-size="line"></td><td>Control de orden</td><td>Modifica la posición de la política dentro del listado configurado.</td></tr><tr><td align="center"><strong><code>Ruta de juego responsable</code></strong></td><td>Texto / URL</td><td>Registra la ruta donde estará disponible la política de juego responsable.</td></tr><tr><td align="center"><strong><code>Título</code></strong></td><td>Texto</td><td>Define el título que será mostrado para la política de juego responsable.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (477).png" alt="" data-size="line"></td><td>Botón</td><td>Crea un submenú asociado a la política principal y habilita los campos necesarios para configurar su contenido.</td></tr></tbody></table>

{% columns %}
{% column width="33.33333333333333%" %}

{% endcolumn %}

{% column width="66.66666666666667%" %}
#### Configuración del submenú

<table><thead><tr><th width="123.6363525390625" align="center" valign="middle">Campo</th><th width="86.727294921875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td align="center" valign="middle"><strong><code>Ruta de juego responsable</code></strong></td><td>URL</td><td>Registra la ruta donde estará disponible el contenido del submenú.</td></tr><tr><td align="center" valign="middle"><strong><code>Título</code></strong></td><td>Texto</td><td>Define el título que identificará el submenú dentro de la política principal.</td></tr><tr><td align="center" valign="middle"><img src="../../../.gitbook/assets/image (478).png" alt="" data-size="line"></td><td>Editor de texto</td><td>Configura el contenido que será presentado dentro del submenú de juego responsable.</td></tr><tr><td align="center" valign="middle"><img src="../../../.gitbook/assets/image (479).png" alt=""></td><td>Botón</td><td>Elimina el submenú creado.</td></tr></tbody></table>
{% endcolumn %}
{% endcolumns %}

***

<table data-header-hidden><thead><tr><th width="141.3636474609375" align="center">Campo</th><th width="115.1817626953125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td align="center"><img src="../../../.gitbook/assets/image (481).png" alt=""></td><td>Botón</td><td>Elimina la política de juego responsable seleccionada.</td></tr><tr><td align="center"><img src="../../../.gitbook/assets/image (482).png" alt="" data-size="line"></td><td>Botón</td><td><p>Muestra los submenús asociados a la política principal.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El botón <strong>Desplegar</strong> muestra los submenús asociados a cada política principal y permite consultar la estructura configurada.</p></div></td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio

* Cada política de juego responsable debe contar con una **ruta** y un **título** para completar su configuración.
* Los submenús se asocian a una política principal mediante el botón **Agregar submenú**.
* Cada submenú debe contar con una **ruta**, un **título** y el **contenido** correspondiente.
* El orden configurado para las políticas determina su posición de visualización en la plataforma.
* La eliminación de una política o submenú debe realizarse mediante el botón **Eliminar** correspondiente.
* Las modificaciones realizadas deben guardarse mediante el botón **Guardar** para almacenar la configuración.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="104.3636474609375">Versión</th><th width="124.54541015625">Fecha</th><th width="116.54541015625">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>31/08/2026</td><td>Karol Navia</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33475">Reestructuración adaptada a plantilla.</a></td></tr></tbody></table>

</details>
