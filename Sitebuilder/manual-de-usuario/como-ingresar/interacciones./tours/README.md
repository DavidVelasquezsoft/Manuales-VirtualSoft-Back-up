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
  anchors:
    visible: true
---

# Tours

<mark style="color:$info;">Los tours son secuencias de pasos diseñadas para facilitar el conocimiento y aprendizaje de la plataforma Usuarios Online. Desde este módulo se gestiona la creación y administración de tours y tutoriales que guían el uso de las funcionalidades de la plataforma.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso:** Site Builder > Seleccionar Partner > interacciones > Tours.

***

### 2. Acciones disponibles

<table><thead><tr><th width="150">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Gestionar tours</strong></td><td>Visualiza y gestiona los tours creados para la plataforma Usuarios Online.</td></tr><tr><td><strong>Crear tours</strong></td><td>Crea tours para secciones específicas de la plataforma Usuarios Online.</td></tr><tr><td><strong>Crear tutoriales</strong></td><td>Crea y administra los videos que utilizarán los jugadores para aprender a utilizar la plataforma Usuarios Online.</td></tr></tbody></table>

***

### 3. Gestión de módulos

Esta sección se compone de tres módulos que complementan los tours disponibles en la plataforma Usuarios Online. Cada módulo corresponde a una etapa del proceso de configuración y funcionamiento de los tours.

{% tabs %}
{% tab title="① Lista de tours" %}
El módulo presenta indicadores, listas y métricas relacionadas con los tours previamente creados.

#### Visualización

<figure><img src="../../../../.gitbook/assets/image (515).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Tours.</p></figcaption></figure>

#### KPIs

Los indicadores KPI se componen de las cantidades totales de tours registrados en la plataforma.

<table><thead><tr><th width="145">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Total</code></strong></td><td>Tours creados para la plataforma Usuarios Oline.</td></tr><tr><td><strong><code>Activos</code></strong></td><td>Tours activos actualmente en la plataforma Usuarios Online.</td></tr><tr><td><strong><code>Borradores</code></strong></td><td>Tours que iniciaron la creación, pero no se guardaron.</td></tr><tr><td><strong><code>Inactivo</code></strong></td><td>Tours que fueron creados, pero ya se encuentran inactivos para la plataforma Usuarios Online.</td></tr></tbody></table>

#### Lista de tours

Es esta tabla se visualizarán cada uno de los tours previamente creados.

{% hint style="warning" %}
**Nota**: La tabla corresponde a los filtros ![](<../../../../.gitbook/assets/Frame 1321316418.png>) que ayudan a obtener una información más precisa, o se puede filtrar directamente por el nombre de un tour desde <img src="../../../../.gitbook/assets/Text Input.png" alt="" data-size="line">.
{% endhint %}

<table><thead><tr><th width="174">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del tour.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre asignado al tour.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td><p>Prioridad que tiene el tour respecto a los demás tours creados.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Desde <img src="../../../../.gitbook/assets/icon_drag_indicator (2).png" alt=""> también se podrá modificar la prioridad del tour, al momento de arrastrar el tour seleccionado se establecerá una nueva prioridad correspondiente a la ubicación establecida.</p></div></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado en el que se encuentra en tour.</td></tr><tr><td><strong><code>Recompensa</code></strong></td><td>Recompensa que obtienen los usuarios de la plataforma Usuarios Online al momento de finalizar el tour.</td></tr><tr><td><strong><code>ID bono</code></strong></td><td>Identificador del bono que obtienen los usuarios al finalizar el tour.</td></tr><tr><td><strong><code>Audiencia</code></strong></td><td>Audiencia que tendrá disponible y visible el tour.</td></tr><tr><td><strong><code>Inicio</code></strong></td><td>Fecha en la que el tour inició su vigencia.</td></tr><tr><td><strong><code>Fin</code></strong></td><td>Fecha en la que el tour finalizó su vigencia.</td></tr><tr><td><strong><code>Acciones</code></strong></td><td>Acciones disponibles para gestionar el tour.<br><a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/interacciones./tours#lista-de-acciones" class="button secondary">Lista de acciones</a></td></tr></tbody></table>

<details>

<summary><strong>Lista de acciones</strong></summary>

<table><thead><tr><th width="74">Acción</th><th width="557">Descripción</th></tr></thead><tbody><tr><td><img src="../../../../.gitbook/assets/Vector (1) (2).png" alt=""></td><td>Redirige hacia el formulario de creación de tours para editar el tour seleccionado.</td></tr><tr><td><img src="../../../../.gitbook/assets/Vector (10).png" alt=""></td><td>Previsualiza el funcionamiento del tour.</td></tr><tr><td><img src="../../../../.gitbook/assets/Vector (2) (2).png" alt="" data-size="original"></td><td><p>Despliega el pop-up para confirmar si se desea duplicar el tour seleccionado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al momento de duplicar un tour, este se duplicará con las mismas configuraciones que el seleccionado, pero en estado "<strong>Borrador</strong>".</p></div></td></tr><tr><td><img src="../../../../.gitbook/assets/settings_power.png" alt=""></td><td><p>Despliega un pop-up para confirmar si se desea activar o desactivar un tour.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Esta acción estará bloqueada para los tours que estén en estado "<strong>Borrador</strong>".</p></div></td></tr></tbody></table>

</details>

{% hint style="warning" %}
**Nota**: Al final de esta tabla se puede modificar la cantidad de registros visualizados&#x20;
{% endhint %}

***

#### Crear tour

Al seleccionar el botón <img src="../../../../.gitbook/assets/Button (13).png" alt="" data-size="line"> se redirigirá al formulario para la creación de tours.

{% content-ref url="creacion-de-tours.md" %}
[creacion-de-tours.md](creacion-de-tours.md)
{% endcontent-ref %}

***

#### Reglas y validaciones

* Las acciones disponibles en los torus registrados dependen de permisos específicos.
* En la columna Prioridad se puede ingresar directamente el número que definirá el orden del tour. No se permiten prioridades duplicadas; al asignar una prioridad que ya está ocupada, se ajustará el orden de los tours afectados para mantener una secuencia única y consecutiva.

{% hint style="info" %}
**Ejemplo**: Si existen 5 tours y el tour con prioridad 3 pasa a tener prioridad 5, el tour que ocupaba la prioridad 5 pasará a la prioridad 4, y los demás tours se reorganizarán según corresponda. La prioridad se organiza de menor a mayor.
{% endhint %}

* Los cambios realizados desde este módulo aplicaran de manera inmediata sin necesidad de realizar alguna otra confirmación.
{% endtab %}

{% tab title="② Indicadores" %}
{% hint style="warning" %}
Nota: Este módulo aún se encuentra en desarrollo, por lo que todavía no cuenta con acceso habilitado ni documentación relacionada.
{% endhint %}
{% endtab %}

{% tab title="③ Tutoriales" %}
Los tours&#x20;

#### Visualización

<figure><img src="../../../../.gitbook/assets/image (517).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Tours.</p></figcaption></figure>

#### Filtros

Los filtros permiten consultar y gestionar de forma más precisa los tutoriales creados para la plataforma Usuarios Online.

<table><thead><tr><th width="145">Filtro</th><th width="132">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td></td></tr><tr><td><strong><code>Clasificación</code></strong></td><td>Lista desplegable</td><td></td></tr><tr><td><strong><code>Vigencia</code></strong></td><td>Calendario</td><td></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Buscador</td><td></td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: Desde las acciones <img src="../../../../.gitbook/assets/Frame 1321316631.png" alt="" data-size="line"> se pueden aplicar filtros o restablecer los filtros previamente aplicados.
{% endhint %}

#### Lista de tutoriales

Es esta tabla se visualizarán cada uno de los tutoriales previamente creados.

<table><thead><tr><th width="174">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><img src="../../../../.gitbook/assets/icon_drag_indicator (2).png" alt=""> </td><td></td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único del tour.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre asignado al tour.</td></tr><tr><td><strong><code>Descripción corta</code></strong></td><td></td></tr><tr><td><strong><code>Clasific</code></strong></td><td></td></tr><tr><td><strong><code>Vigencia</code></strong></td><td></td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado en el que se encuentra en tour.<br>Activo: El tutorial está activo y funcional en la plataforma Usuarios Online<br>Inactivo: El tutorial fue inactivado y no está visible en usuarios online<br>Está programado: Tiene fecha de inicio futura a la actual<br>Vencido: La fecha final es interior a la actual</td></tr><tr><td><strong><code>Acciones</code></strong></td><td>Acciones disponibles para gestionar el tour.<br><a href="https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/interacciones./tours#lista-de-acciones" class="button secondary">Lista de acciones</a></td></tr></tbody></table>

<details>

<summary><strong>Lista de acciones</strong></summary>

<table><thead><tr><th width="74">Acción</th><th width="557">Descripción</th></tr></thead><tbody><tr><td>   <img src="../../../../.gitbook/assets/Vector (10).png" alt="" data-size="original"></td><td>Previsualiza el funcionamiento del tour.</td></tr><tr><td>   <img src="../../../../.gitbook/assets/Vector (1) (2).png" alt=""></td><td>Redirige hacia el formulario de creación de tours para editar el tour seleccionado.</td></tr><tr><td>   <img src="../../../../.gitbook/assets/settings_power.png" alt=""></td><td><p>Despliega un pop-up para confirmar si se desea activar o desactivar un tour.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Esta acción estará bloqueada para los tours que estén en estado "<strong>Borrador</strong>".</p></div></td></tr><tr><td>   <img src="../../../../.gitbook/assets/Vector (3) (1).png" alt="" data-size="original"></td><td><p>Despliega el pop-up para confirmar si se desea duplicar el tour seleccionado.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al momento de duplicar un tour, este se duplicará con las mismas configuraciones que el seleccionado, pero en estado "<strong>Borrador</strong>".</p></div></td></tr></tbody></table>

</details>

{% hint style="warning" %}
**Nota**: Al final de esta tabla se puede modificar la cantidad de registros visualizados&#x20;
{% endhint %}

***

#### Crear tour

Al seleccionar el botón <img src="../../../../.gitbook/assets/Button (13).png" alt="" data-size="line"> se redirigirá al formulario para la creación de tours.

{% content-ref url="creacion-de-tours.md" %}
[creacion-de-tours.md](creacion-de-tours.md)
{% endcontent-ref %}

***

#### Reglas y validaciones

*
{% endtab %}
{% endtabs %}



***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="108">Versión</th><th width="130">Fecha</th><th width="140">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>14/10/2026</td><td>Ronald Peláez</td><td>Documento inicial (incluye <a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-32313?xpis=eyJicmlkZ2UiOiJzbWFydExpbmtzIiwiaWQiOiIxNzkyMDA2MDU5NjgxIiwic291cmNlIjoiamlyYS1KU1cifQ%3D%3D#icft=VSFT-32313">tours</a>, <a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-32312?xpis=eyJicmlkZ2UiOiJzbWFydExpbmtzIiwiaWQiOiIxNzkyMDA2MDczODc3Iiwic291cmNlIjoiamlyYS1KU1cifQ%3D%3D#icft=VSFT-32312">pasos </a>y <a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-33143#icft=VSFT-33143">tutoriales</a>).</td></tr></tbody></table>

</details>
