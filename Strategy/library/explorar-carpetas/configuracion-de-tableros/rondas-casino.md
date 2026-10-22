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

# Rondas casino

Este tablero presenta información general consolidada de todas las [campañas](https://virtualsoft.gitbook.io/plantillas/glosario#campana) de los diferentes partners, centralizando la información en un solo lugar.

### 1. Acceso al Módulo

**Ruta de acceso**: Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales > Rondas Casino.

***

### 2. Configuraciones previas

Antes de ingresar a este tablero, es necesario completar los filtros que se visualizarán durante las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/library/explorar-carpetas/configuracion-de-tableros#id-1.-configuraciones-previas).

<table><thead><tr><th width="145">Filtro</th><th width="136">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Ronda</code></strong></td><td>Alfanuméricos</td><td>Filtra únicamente por una ronda en específico según su identificador único.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Numérico</td><td>Filtra por los movimientos realizados por el usuario con su identificador único.</td></tr><tr><td><strong><code>Id Casino</code></strong></td><td>Numérico</td><td>Filtra por el identificador único del proveedor de casino con el que se realizó el movimiento.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: Los filtros que no se requieran deben configurarse con el valor **0**. De esta manera, se cumple con el requisito de obligatoriedad del tablero y se consulta la información únicamente con los filtros necesarios.
{% endhint %}

***

### 3. Acciones disponibles

<table><thead><tr><th width="175.92572021484375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Aplicar filtros</strong></td><td>Utiliza los filtros visualizados en las configuraciones previas para realizar la consulta directa antes de ingresar al tablero.</td></tr><tr><td><strong>Visualizar contenido del tablero</strong></td><td>Visualiza información detallada sobre las rondas de casino en la tabla que contiene el dashboard.</td></tr><tr><td><strong>Exportar contenido</strong></td><td>El tablero permite exportar su contenido. Para más información, consulte la guía de exportación <a data-mention href="./#id-3.-exportar-contenido">#id-3.-exportar-contenido</a>.</td></tr></tbody></table>

***

### 4. Visualización

<figure><img src="../../../.gitbook/assets/image (263).png" alt=""><figcaption></figcaption></figure>

### 4. Contenido del dashboard

Este dashboard se compone de una tabla que centraliza la información de las rondas de casino filtradas anteriormente.

<table><thead><tr><th width="169">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha y hora en la que se registró la ronda.</td></tr><tr><td><strong><code>ID Aggregator</code></strong></td><td>Identificador asociado al agregador o proveedor.</td></tr><tr><td><strong><code>ID B.O.</code></strong></td><td>Identificador de la operación o registro en BackOffice.</td></tr><tr><td><strong><code>Identificador de la ronda</code></strong></td><td>ID único correspondiente a la ronda consultada.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Tipo de movimiento registrado <em>(ejemplo: Debit, Credit u otros).</em></td></tr><tr><td><strong><code>Monto</code></strong></td><td>Valor monetario asociado al movimiento.</td></tr><tr><td><strong><code>Respuesta</code></strong></td><td><p>Resultado de la transacción, mostrando <strong>OK</strong> o el código de error correspondiente.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p>Nota: Con el fin de facilitar la lectura de la información, el tablero no mostrará el <strong>JSON</strong> completo.</p></div></td></tr><tr><td><strong><code>Transjuegolog_id</code></strong></td><td>Identificador del registro transaccional.</td></tr></tbody></table>

***

### 5. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="94.7037353515625">Versión</th><th width="133.25927734375">Fecha</th><th width="161.77777099609375">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>22/10/2026</td><td>Ronald Pelaéz</td><td><a href="https://virtualsoftlatam.atlassian.net/browse/VSFT-32701">Documento inicial</a></td></tr></tbody></table>

</details>
