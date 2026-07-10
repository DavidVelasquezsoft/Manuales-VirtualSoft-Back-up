---
description: >-
  Ajusta la paleta de colores correspondiente al partner previamente
  seleccionado
---

# Colores

### **1. Acceso al Módulo**

**Ruta:** Site Builder > Seleccionar Partner > Apariencia > Colores

### **2. Configuraciones previas.**

Antes de realizar las acciones disponibles en la sección colores, es necesario contar con las siguientes configuraciones:

<table><thead><tr><th width="159.55560302734375">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Dispositivo</code></strong></td><td>Dispositivo al que aplicarán las configuraciones <em>(móvil o escritorio).</em></td></tr></tbody></table>

***

### 3. Alcance del manual

Este manual cubre el uso de la sección **Colores**, incluyendo las acciones disponibles para su administración.

**Incluye:**

* Acciones disponibles en el módulo de **Colores**.
* Edición de paleta de **Colores**.

***

### **4. Visualización**

<figure><img src="../../../.gitbook/assets/image (59).png" alt=""><figcaption><p>Figura #1: Captura de pantalla módulo de colores.</p></figcaption></figure>

***

### **5. Acciones del usuario**

<table><thead><tr><th width="179.333251953125">Acción</th><th width="113.7037353515625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td>Establecer paleta de colores</td><td>Selector</td><td>Establece la configuración de la paleta de colores que tendrá la plataforma usuarios online.</td></tr><tr><td>Recomendaciones <i class="fa-lightbulb">:lightbulb:</i></td><td>Botón</td><td>Muestra recomendaciones y sugerencias relacionadas con el uso de los colores.<br>Cuando se realiza una modificación en la paleta de colores, los cambios se reflejan también en los tips correspondientes.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: Los cambios pueden tardar aproximadamente 20 minutos en reflejarse en la plataforma.
{% endhint %}

#### **5.1 Cómo editar la paleta de colores.**

Este apartado se divide en dos secciones: en la parte izquierda se encuentran las opciones disponibles para editar la paleta de colores, y en la parte derecha se muestra un ejemplo en tiempo real de los cambios aplicados en la plataforma de usuarios online.

{% stepper %}
{% step %}
**Seleccionar el modo a configurar**

Utiliza este switch <img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2Fifu6sFYmmtItM0KtHk3t%2Fimage.png?alt=media&#x26;token=2beb4cc6-d397-4b71-94bf-f4a9a5c304bf" alt="" data-size="line"> para definir si se configurarán los colores del **modo oscuro** o el **modo claro** de la plataforma.
{% endstep %}

{% step %}
**Editar colores según segmento**

Los colores se agrupan en **categorías funcionales**, que representan su propósito dentro del diseño de la plataforma usuarios online.

<table><thead><tr><th width="125">Segmento</th><th>Función / Aplicación</th></tr></thead><tbody><tr><td><strong><code>Base</code></strong></td><td>Define la base cromática de la plataforma. Se usa como referencia general para fondos, encabezados o elementos estructurales que mantienen coherencia visual en toda la interfaz.</td></tr><tr><td><strong><code>Primario</code></strong></td><td>Representa el color principal de marca. Se aplica en botones primarios, enlaces destacados y elementos que requieren mayor énfasis.</td></tr><tr><td><strong><code>Secundario</code></strong></td><td>Complementa al color primario y se usa en acciones o componentes de menor jerarquía visual, como botones secundarios o paneles informativos.</td></tr><tr><td><strong><code>Acento</code></strong></td><td>Se emplea para resaltar elementos específicos <em>(íconos, indicadores, etiquetas o badges)</em>. Ayuda a dirigir la atención del usuario hacia puntos clave.</td></tr><tr><td><strong><code>Neutrales</code></strong></td><td>Incluye grises, blancos y negros. Se usan para fondos, textos, bordes o divisores, aportando balance y legibilidad al diseño.</td></tr><tr><td><strong><code>Semánticos</code></strong></td><td>Asocian un color a un estado o mensaje: <em>verde (éxito), rojo (error), amarillo (advertencia), azul (informativo)</em>. Se aplican en alertas, validaciones y notificaciones.</td></tr><tr><td><strong><code>Formularios</code></strong></td><td>Colores aplicados en campos de entrada, bordes, fondos y placeholders. Mantienen la consistencia visual en formularios y elementos interactivos.</td></tr></tbody></table>
{% endstep %}

{% step %}
#### Modificar color

Luego de definir el **segmento** que se va a configurar, será posible **modificar los colores** asociados.\
Cada segmento dispone de **campos de color específicos**, según su función dentro del sistema (por ejemplo: _Primary_, _Focus_, _Content_, entre otros).

Al seleccionar alguno de estos campos, se despliega un **pop-up con el selector de color**, que permite ajustar los siguientes parámetros:

* **Tono y saturación:** controlan la apariencia general del color.
* **Transparencia:** ajusta la opacidad para lograr efectos visuales más suaves o destacar elementos.
* **Formato:** permite definir el color en distintos formatos (_HEX_, _RGB_ o _HSL_), según las necesidades del diseño.

Una vez configurado el color deseado, el cambio se confirma mediante el botón **“Guardar” en el pop-up**, aplicándose la actualización del color en el segmento seleccionado.
{% endstep %}

{% step %}
#### **Visualizar resultados**

En la parte derecha de esta sección se visualizará un ejemplo de cómo quedan todos los cambios realizados en la plataforma usuarios online.
{% endstep %}

{% step %}
#### Guardar cambios

Utiliza el botón "Guardar" ubicado en la sección principal para aplicar los cambios en el partner configurado.
{% endstep %}
{% endstepper %}

***

### **6. Validación, reglas y comportamiento del sistema**

* Las configuraciones realizadas se visualizarán en la plataforma **Usuarios Online** según el _partner_ que se esté configurando.
* La paleta de colores establecida aplica únicamente para el dispositivo seleccionado en las configuraciones previas _(por ejemplo: si se configura la paleta de colores para escritorio, no aplicará para móvil)_.
* La previsualización y la sección de recomendaciones deben actualizarse de manera inmediata con cada cambio realizado.

**Reglas y validaciones**

<table><thead><tr><th width="192">Regla</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Validación de formato</strong></td><td>El sistema valida en tiempo real los valores ingresados en formato <strong>HEX</strong>, <strong>RGB</strong> o <strong>HSL</strong>. Si el formato no es válido, se muestra el mensaje <em>“Ingrese un color válido”</em>.</td></tr><tr><td><strong>Retención de configuración</strong></td><td>Los colores aplicados y guardados permanecen visibles en sesiones futuras, conservando la configuración establecida.</td></tr></tbody></table>

***

**Errores y validaciones**

<table><thead><tr><th width="220">Escenario</th><th>Comportamiento esperado</th></tr></thead><tbody><tr><td><strong>Ingreso de formato no válido</strong></td><td>Se muestra un mensaje de error: <em>“Ingrese un color válido”</em>. El campo queda resaltado hasta que se ingrese un valor correcto.</td></tr><tr><td><strong>Cierre o cambio de partner sin guardar</strong></td><td>Los cambios no se conservan ni se aplican en <strong>Sitios Online</strong>. Es necesario guardar antes de salir de la sección.</td></tr><tr><td><strong>Salida del módulo sin guardar</strong></td><td>Los colores permanecen visibles localmente, pero no se reflejan en la plataforma hasta que se confirme la acción mediante el botón <strong>Guardar</strong>.</td></tr><tr><td><strong>Guardar sin cambios previos</strong></td><td>El sistema no genera modificaciones en la paleta, pero mantiene la coherencia con otras configuraciones globales del <strong>SiteBuilder</strong>.</td></tr><tr><td><strong>Error interno o de red</strong></td><td>Los cambios no guardados se pierden. Una vez restablecida la conexión, la configuración más reciente guardada seguirá vigente.</td></tr><tr><td><strong>Manejo de errores o desconexiones</strong></td><td>En caso de error interno, pérdida de conexión o cambio de <em>partner</em> sin guardar, los cambios no guardados se descartan. Para asegurar la persistencia, es necesario guardar antes de salir de la sección.</td></tr></tbody></table>

***

### **7. Control de versiones**

| Versión | Fecha      | Autor         | Cambios realizados                            |
| ------- | ---------- | ------------- | --------------------------------------------- |
| 1.0     | 15-10-2025 | Ronald Peláez | Documento inicial                             |
| 1.1     | 05-11-2025 | David Ortiz   | Ajustes en formato y actualizacion de imagen. |
