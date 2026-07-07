---
description: >-
  Este reporte permite consultar el histórico de las contingencias aplicadas a
  los usuarios, facilitando el análisis y seguimiento de los cambios realizados.
---

# Usuarios con Contingencia

### **1. Acceso al Módulo** <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de Acceso:** Virtualsoft > Objetos públicos > Informes > Datas TI > Paneles Visuales

{% hint style="warning" %}
**Nota:** La ruta de acceso aplica para usuarios con permisos si no tiene permisos pedirlos a soporte
{% endhint %}

***

### 2. Acciones disponibles

<table><thead><tr><th width="204.333251953125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="usuarios-con-contingencia.md#id-3.-filtros-disponibles"><strong>Aplicar filtros</strong></a></td><td>Permite filtrar la información según los criterios disponibles y utilizar el dashboard de forma dinámica para enfocar el análisis.</td></tr><tr><td><strong>Cambiar de pestaña</strong></td><td>Permite alternar entre las diferentes pestañas del dashboard para visualizar distintas versiones del contenido según la opción seleccionada.</td></tr><tr><td><a href="usuarios-con-contingencia.md#id-4.-contenido-del-dashboard"><strong>Visualizar contenido del tablero</strong></a></td><td>Permite consultar y analizar la información relacionada con las contingencias mediante gráficos, tablas e indicadores disponibles en el dashboard.</td></tr><tr><td><strong>Exportar</strong></td><td>En cada <a href="https://sites.gitbook.com/preview/site_E7EPL/glosario/~/changes/141#card">card</a>, al seleccionar el menú de los ⋮ <em>(3 puntos)</em>, se visualizará la opción de exportación <em>(PDF o Excel)</em>.</td></tr></tbody></table>

***

### **3. Filtros disponibles**

El reporte cuenta con los siguientes filtros, los cuales pueden utilizarse de forma combinada:

<table><thead><tr><th width="240">Filtro</th><th width="152.333251953125">Tipo</th><th width="355.8887939453125">Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de aplicación</code></strong></td><td>Selector de rango de fechas</td><td>Permite filtrar las contingencias según el rango de fechas en que fueron aplicadas, en formato YYYY-MM-DD-HH.</td></tr><tr><td><strong><code>Fecha de modificación</code></strong></td><td>Selector de rango de fechas</td><td>Permite filtrar las contingencias según el rango de fechas de su última modificación, en formato YYYY-MM-DD-HH.</td></tr><tr><td><strong><code>Estado de la contingencia</code></strong></td><td>Lista desplegable</td><td>Muestra las contingencias de acuerdo con su estado <em>(Activa o Inactiva).</em></td></tr><tr><td><strong><code>Tipo de contingencia</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar uno o varios tipos de contingencia para consultar información específica.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Texto</td><td>Facilita la búsqueda de un usuario específico mediante su identificador.</td></tr></tbody></table>

***

### 4. Contenido del dashboard

Este dashboard cuenta con 2 vistas principales, disponibles a través de las siguientes pestañas:

{% tabs %}
{% tab title="Detalle" %}
Desde esta vista se muestra una tabla con el detalle de las contingencias registradas, de acuerdo con los filtros aplicados.

#### 4.1 Visualización

<figure><img src="../../../.gitbook/assets/image (157) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección detalle.</p></figcaption></figure>

#### 4.2. Tabla de registros

<table><thead><tr><th width="213">Campo</th><th width="476.5">Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner al que pertenece el usuario relacionado con la contingencia.</td></tr><tr><td><strong><code>País</code></strong></td><td>País de residencia registrado para el usuario.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario al que se le aplicó la contingencia.</td></tr><tr><td><strong><code>Tipo de contingencia</code></strong></td><td>Nombre o categoría de la contingencia aplicada al usuario.</td></tr><tr><td><strong><code>ID</code></strong> <a href="https://sites.gitbook.com/preview/site_E7EPL/glosario#operador"><strong><code>operador</code></strong></a></td><td>Identificador del <a href="https://sites.gitbook.com/preview/site_E7EPL/glosario#operador">operador </a>que realizó la aplicación o modificación de la contingencia.</td></tr><tr><td><strong><code>Correo operador</code></strong></td><td>Correo electrónico del usuario de BackOffice que ejecutó la acción sobre la contingencia.</td></tr><tr><td><strong><code>Motivo Contingencia</code></strong></td><td>Observación o comentario registrado por el <a href="https://sites.gitbook.com/preview/site_E7EPL/glosario#operador">operador </a>al momento de aplicar la contingencia. En caso de no registrar información, el campo permanecerá vacío.</td></tr><tr><td><strong><code>Fecha de aplicación</code></strong></td><td>Fecha y hora en la que se aplicó o activó la contingencia.</td></tr><tr><td><strong><code>Fecha de última modificación</code></strong></td><td>Fecha y hora correspondiente a la modificación más reciente realizada sobre la contingencia.</td></tr><tr><td><strong><code>Estado Contingencia</code></strong></td><td>Estado actual de la contingencia, el cual puede ser <em>(Activa o Inactiva).</em></td></tr></tbody></table>
{% endtab %}

{% tab title="General" %}
La vista general se compone de diferentes componentes, como KPIs y gráficas, que permiten visualizar y analizar la información de manera clara y organizada. A continuación, se muestra la información disponible:

#### 4.1 Visualización

<figure><img src="../../../.gitbook/assets/image (159) (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección General.</p></figcaption></figure>

#### 4.2. KPIs

<table><thead><tr><th width="147.33331298828125">Nombre</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Contingencias por estado</code></strong></td><td>Muestra la cantidad total de contingencias agrupadas por estado <em>(activas o inactivas)</em>.</td></tr><tr><td><strong><code>Contingencias totales</code></strong></td><td>Presenta el total general de contingencias registradas en la plataforma.</td></tr></tbody></table>

#### 4.3. Gráficas

<table><thead><tr><th width="151.7777099609375">Nombre</th><th>Tipo</th><th width="401.6666259765625">Descripción</th></tr></thead><tbody><tr><td><strong><code>% Contingencias</code></strong></td><td>Gráfico de porcentaje</td><td><p>Permite visualizar el porcentaje total de contingencias registradas, calculado a partir de la cantidad de contingencias por estado respecto al total registrado.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p>Ejemplo: si existen 721 contingencias por estado y 870 contingencias totales, el porcentaje corresponde a <code>82,87%</code>.</p></div></td></tr><tr><td><strong><code>Contingencias por partner</code></strong></td><td>Gráfico de barras</td><td>Muestra la cantidad de contingencias asociadas a cada partner registrado.</td></tr><tr><td><strong><code>Distribución de contingencias por país</code></strong></td><td>Gráfico de barras</td><td>Presenta la cantidad de contingencias agrupadas y organizadas según el país en el que fueron registradas.</td></tr><tr><td><strong><code>Contingencias por tipo</code></strong></td><td>Gráfico de barras</td><td>Presenta la cantidad de contingencias agrupadas y organizadas según el tipo de contingencia aplicada.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### **5. Validaciones y reglas del negocio**

* El reporte muestra únicamente el **histórico de contingencias aplicadas**.
* Cada contingencia aplicada se registra como un evento independiente dentro del reporte.

{% hint style="info" %}
**Ejemplo:** Si a un usuario se le aplican 3 contingencias diferentes, el sistema generará 3 registros separados.
{% endhint %}

* Los filtros pueden combinarse para refinar la consulta.
* El campo **Comentario** no se modifica posteriormente.
* Todas las fechas visualizadas y utilizadas en los filtros del reporte se muestran en el formato YYYY-MM-DD-HH.

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="117">Versión</th><th width="123">Fecha</th><th width="165">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>07/05/2026</td><td>Karol Navia</td><td>Documento inicial</td></tr></tbody></table>

</details>
