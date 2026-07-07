---
description: >-
  Permite gestionar la asociación entre una criptomoneda y una red blockchain,
  definiendo la combinación bajo la cual una criptomoneda puede operar dentro de
  la plataforma.
---

# Asociación Cripto + Redes

### 1. Acceso al Módulo <a href="#id-1.-acceso-al-modulo" id="id-1.-acceso-al-modulo"></a>

**Ruta de Acceso**: BackOffice > Productos > Asociación cripto + redes

***

### 2. Visualización general <a href="#id-4.-visualizacion" id="id-4.-visualizacion"></a>

<figure><img src="../../.gitbook/assets/image (535).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Asociación Cripto + Redes.</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="118">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong>​</td><td>Permiten realizar búsquedas específicas mediante la selección de uno o varios filtros</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los campos de filtros a su estado inicial, eliminando cualquier criterio seleccionado previamente y permitiendo realizar una nueva búsqueda desde cero.</td></tr><tr><td><strong>​Consultar</strong></td><td>Ejecuta la búsqueda de acuerdo con los filtros definidos por el usuario y muestra los resultados en la tabla correspondiente.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite descargar la información resultante de la consulta en un archivo en formato Excel, el cual se descarga desde la parte inferior derecha de la pantalla.</td></tr></tbody></table>

***

### 4. Filtros  <a href="#id-2.-filtros" id="id-2.-filtros"></a>

Busca una asociación específica rápidamente mediante filtros opcionales.

<table><thead><tr><th width="161.22222900390625">Campo</th><th width="120.77783203125">Tipo de Control</th><th width="464.5926513671875">Descripción</th></tr></thead><tbody><tr><td><strong><code>Criptomoneda</code></strong></td><td>Texto + Lista desplegable</td><td>Busca nombre de <a href="https://virtualsoft.gitbook.io/untitled/glosario#criptomoneda">criptomoneda</a>, debe estar <strong>Activa</strong>.</td></tr><tr><td><strong><code>Red Blockchain</code></strong></td><td>Texto + Lista desplegable</td><td>Busca nombre de <a href="https://virtualsoft.gitbook.io/untitled/glosario#red-blockchain">Red Blockchain</a>, debe estar <strong>Activa</strong>.</td></tr><tr><td><strong><code>Estado (Avanzado)</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los registros según su estado: (activa, inactiva o todos).</td></tr></tbody></table>

***

### 5. Consultar

Aquí puedes consultar las asociaciones existentes, crear nuevas, modificar su estado o visualizar los detalles de cada una.&#x20;

<table><thead><tr><th width="140.5556640625">Campo</th><th width="115.44439697265625">Tipo</th><th>Descripcion</th></tr></thead><tbody><tr><td><strong><code>Acciones</code></strong></td><td>Columna de acciones</td><td>Permite realizar acciones directas sobre un registro:</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único de la asociación</td></tr><tr><td><strong><code>Cripto</code></strong></td><td>Texto</td><td>Indica el nombre de la criptomoneda.</td></tr><tr><td><strong><code>Red</code></strong></td><td>Texto</td><td>Indica la red blockchain de la asociación.</td></tr><tr><td><strong><code>Código de Red</code></strong></td><td>Texto</td><td>Muestra el código que identifica la red blockchain utilizada por la criptomoneda.</td></tr><tr><td><code>Estado</code></td><td>Texto</td><td>Muestra el estado de la asociación: Activa o Inactiva.</td></tr></tbody></table>

***

### 6. Asociar cripto + Red

Abre una ventana emergente que permite asociar una criptomoneda con Red Blockchain, completando los siguientes campos obligatorios.

{% hint style="danger" %}
**Nota importante:** Para poder asociar una criptomoneda con una red blockchain, **ambas deben encontrarse en estado activo**. Al realizar esta asociación ([Cripto + Red](https://virtualsoft.gitbook.io/untitled/glosario#criptomoneda--red-blockchain)), el sistema generará automáticamente un banco vinculado, cuyo estado dependerá directamente del de la asociación.

&#x20;(Este banco **NO** estará presente para registro de cuentas bancarias en la plataforma).
{% endhint %}

<table><thead><tr><th width="162.6666259765625">Campo</th><th width="123">Tipo</th><th width="462.111083984375">Descripcion</th></tr></thead><tbody><tr><td><strong><code>Criptomonedas</code></strong></td><td>Lista desplegable</td><td>Selecciona la <a href="https://virtualsoft.gitbook.io/untitled/glosario#criptomoneda">criptomoneda</a> a vincular</td></tr><tr><td><strong><code>Red Blockchain</code></strong></td><td>Lista desplegable</td><td>Selecciona la <a href="https://virtualsoft.gitbook.io/untitled/glosario#red-blockchain">Red Blockchain</a> a asociar.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Selector</td><td>Indica si la asociación estará Activa o Inactiva desde su creación.</td></tr></tbody></table>

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="100">Versión</th><th width="125.7999267578125">Fecha</th><th width="135.5999755859375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2025/08/04</td><td>David velasquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>2025/08/08</td><td>Ronald Peláez</td><td>Actualización de condición por activaciones</td></tr><tr><td>1.2</td><td>2025/08/19</td><td>David velasquez</td><td>Actualización de nota sobre nueva funcionalidad.</td></tr><tr><td>1.3</td><td>2025/12/16</td><td>Ronald Peláez</td><td>Refinamiento de manual</td></tr></tbody></table>

</details>
