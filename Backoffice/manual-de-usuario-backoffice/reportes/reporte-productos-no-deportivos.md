---
description: >-
  Este reporte te permite consultar el resumen de actividad de todos los
  usuarios en juegos que no son deportivos, como loterías, casino.
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
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

# Reporte productos no deportivos

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Reporte productos no deportivos

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (636).png" alt=""><figcaption><p>Figura#1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="127.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-productos-no-deportivos.md#id-4.-filtros-principales"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="https://sites.gitbook.com/preview/site_U8bCN/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos#id-5.-tipo-de-reporte"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. **Filtros principales**

<table><thead><tr><th width="157">Campo</th><th width="155">Tipo de Control</th><th width="437.77783203125">Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Selecciona el rango de fechas en el que se realizaron las apuestas.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador único del usuario que realizó la apuesta.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Identificador único de la apuesta realizada.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra las transacciones por país.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Selecciona el proveedor del producto o juego.</td></tr><tr><td><strong><code>Sub Proveedor</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por subproveedor asociado.</td></tr><tr><td><strong><code>Producto</code></strong></td><td>Lista desplegable</td><td>Escoge el tipo de producto o juego consultado.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Identifica el tipo de transacción <em>(Normal, FreeSpin, FreeCash, etc.).</em></td></tr><tr><td><strong><code>Valor Mínimo</code></strong></td><td>Numérico</td><td>Establece el monto más bajo que debe tener una apuesta para ser incluida en el reporte.<br>Solo se mostrarán apuestas cuyo valor sea <strong>igual o superior</strong> al monto ingresado en este campo.</td></tr><tr><td><strong><code>Valor Máximo</code></strong></td><td>Numérico</td><td>Establece el monto más alto que puede tener una apuesta para ser incluida en el reporte. Solo se mostrarán apuestas cuyo valor sea <strong>igual o inferior</strong> al monto ingresado en este campo.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td><p>filtra las transacciones según su estado actual:</p><ul><li><strong>Abiertas:</strong> Apuestas que se encuentran en curso y aún no han sido resueltas.</li><li><strong>Cerradas:</strong> Apuestas que ya fueron finalizadas y cuentan con un resultado definido.</li></ul></td></tr><tr><td><strong><code>Vertical</code></strong></td><td>Lista desplegable</td><td><p>Filtra según el tipo de <a href="https://sites.gitbook.com/preview/site_E7EPL/glosario?fallback=true#vertical">vertical</a> que generó la transacción.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Si no se selecciona una vertical, la búsqueda se realizará con todas las verticales por defecto.</p></div></td></tr><tr><td><strong><code>Resumen por proveedor</code></strong></td><td>Casilla seleccionable</td><td><p>Establece de qué forma se visualizará el reporte.</p><ul><li><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos#resumen-por-proveedor"><strong>Casilla seleccionada</strong></a>: El reporte se visualizará en filas resumidas por proveedor.</li><li><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos#reporte-detallado#reporte-detallado"><strong>Casilla no seleccionada</strong></a>: El reporte se visualizará de manera detallada según las configuraciones avanzadas con los filtros.</li></ul></td></tr></tbody></table>

***

### **5. Tipo de reporte**

{% tabs %}
{% tab title="Resumen por proveedor " %}
Este reporte presenta la información agrupada por proveedor, ya sea según el proveedor seleccionado en los filtros o considerando todos los proveedores disponibles.

{% hint style="warning" %}
**Nota:** El reporte se muestra en formato agrupado por la columna **Proveedor**.
{% endhint %}

**Resultados de la consulta**

Cada proveedor contará con un ícono 📁 que permite expandir o contraer el detalle asociado.

* La fila principal _(donde se visualiza el ícono 📁)_ presenta los valores **totales agrupados** por proveedor.
* Al desplegar el grupo, se visualizarán filas adicionales con el **detalle individual de las apuestas** correspondientes a ese proveedor.

<table><thead><tr><th width="153">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Saldo gratis</code></strong></td><td>Monto total de saldo promocional utilizado en las apuestas asociadas al proveedor.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>En las filas agrupadas no aplica. En el detalle, indica la fecha y hora exacta en la que se registró la apuesta <em>(Formato: AAAA-MM-DD HH:MM:SS)</em>.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>En el detalle, identificador único del usuario que realizó la apuesta.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor del juego. En la fila agrupada, identifica el proveedor al que corresponden los totales mostrados.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>En el detalle, nombre del juego desde el cual se realizó la apuesta.</td></tr><tr><td><strong><code>Identificador</code></strong></td><td>Identificador de la apuesta realizada.</td></tr><tr><td><strong><code>Cantidad</code></strong></td><td>Total de apuestas registradas para el proveedor en la fila agrupada. En el detalle, corresponde al número de apuestas del registro individual.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Nombre del subproveedor relacionado con la apuesta, cuando aplique.</td></tr><tr><td><strong><code>Premios bonos</code></strong></td><td>Monto total de premios obtenidos a partir de apuestas realizadas con saldo promocional o bonos.</td></tr><tr><td><strong><code>Impuesto Apuesta</code></strong></td><td>Valor total de impuesto cobrado al momento de la apuesta.</td></tr><tr><td><strong><code>Apuestas bonos</code></strong></td><td>Monto total apostado utilizando saldo promocional o bonos.</td></tr><tr><td><strong><code>GGR</code></strong></td><td>Ingreso bruto generado, calculado como la diferencia entre el total apostado y los premios otorgados.</td></tr><tr><td><strong><code>%GGR</code></strong></td><td>Porcentaje que representa el GGR frente al total apostado.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>En la fila agrupada, valor total de las apuestas realizadas por el usuario con el proveedor, en el detalle, valor de la apuesta realizada.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>En la fila agrupada, total de premios obtenidos con el proveedor. En el detalle, valor obtenido como premio correspondiente a la apuesta realizada.</td></tr></tbody></table>
{% endtab %}

{% tab title="Reporte detallado" %}
{% hint style="warning" %}
**Nota:** Estos filtros solo estarán disponibles cuando **no** se encuentre seleccionada la casilla **`Resumen por proveedor`**.
{% endhint %}

#### **Filtros avanzados**

Los filtros avanzados permiten definir los criterios de organización y búsqueda que se aplicarán al reporte generado.

<table><thead><tr><th width="142">Campo</th><th width="170">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ordenar por</code></strong></td><td>Lista desplegable</td><td>Selecciona el criterio con el cual se organizarán los registros del reporte <em>(Fecha, Usuario, Apuestas, Premios).</em></td></tr><tr><td><strong><code>Orden</code></strong></td><td>Lista desplegable</td><td>Define la dirección en la que se visualizarán los resultados <em>(Ascendente o Descendente).</em></td></tr><tr><td><strong><code>Identificador</code></strong></td><td>Campo de texto</td><td>Filtra únicamente por el identificador único de la apuesta realizada.</td></tr><tr><td><strong><code>Transacción ID</code></strong></td><td>Campo de texto</td><td>Consulta una transacción puntual ingresando su identificador único.</td></tr></tbody></table>

#### Resultados consulta

{% hint style="warning" %}
**Nota**: Cada fila de la tabla corresponde a una apuesta individual y refleja de forma asociada el valor apostado y el premio resultante en las columnas **Apuestas** y **Premios**, respectivamente.
{% endhint %}

<table><thead><tr><th width="153">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Saldo gratis</code></strong></td><td>Monto de saldo promocional utilizado para realizar la apuesta <em>(bonos, créditos promocionales, entre otros).</em></td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha y hora exacta en la que se registró la apuesta <em>(Formato: AAAA-MM-DD HH:MM:SS).</em></td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador único del usuario que realizó la apuesta.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor del juego en el que se efectuó la apuesta.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego desde el cual se realizó la apuesta.</td></tr><tr><td><strong><code>Identificador</code></strong></td><td>Identificador del juego o evento asociado a la apuesta.</td></tr><tr><td><strong><code>Cantidad</code></strong></td><td>Número de apuestas registradas en el movimiento correspondiente.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Nombre del subproveedor relacionado con la apuesta, cuando aplique.</td></tr><tr><td><strong><code>Premios bonos</code></strong></td><td>Monto total de premios obtenidos a partir de apuestas realizadas con saldo promocional o de bonos.</td></tr><tr><td><strong><code>Impuesto Apuesta</code></strong></td><td>Valor descontado por concepto de impuesto aplicado a la apuesta.</td></tr><tr><td><strong><code>Apuestas bonos</code></strong></td><td>Monto total apostado utilizando saldo promocional o de bonos.</td></tr><tr><td><strong><code>GGR</code></strong></td><td>Ingreso bruto generado por la apuesta, correspondiente a la diferencia entre el valor apostado y los premios otorgados.</td></tr><tr><td><strong><code>%GGR</code></strong></td><td>Porcentaje que representa el GGR en relación con el total apostado.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Saldo que tenía el usuario al momento de realizar la apuesta.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Saldo con el que quedó el usuario después de procesarse la apuesta y aplicarse el resultado correspondiente.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 6. Validaciones y Reglas de Negocio

* No es obligatorio completar todos los filtros para ejecutar una búsqueda.
* **Todas las ganancias provenientes de giros gratis asignados por el Bonus System** se registran como **premios bonos**.
* **Los bonos, multiplicadores o giros otorgados por el proveedor** deben registrarse como **premios**, no como **premios bonos**.
* Este reporte se puede consultar de manera más detallada por el usuario desde el [reporte productos no deportivo (por usuario)](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/reporte-productos-no-deportivos-por-usuario)
* Algunas acciones de este reporte dependen de permisos específicos.

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="105">Versión</th><th width="149">Fecha</th><th width="169">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/08/2025</td><td>Ronald Peláez</td><td>Documento inicial del manual</td></tr><tr><td>1.1</td><td>09/09/2025</td><td>Karol Navia</td><td>Actualización de descripciones</td></tr><tr><td>1.2</td><td>29/01/2026</td><td>Ronald Peláez</td><td>Refinamiento de manual.</td></tr><tr><td>1.3</td><td>04/05/2026</td><td>Ronald Peláez</td><td>Ajuste en el tipo de reporte.</td></tr></tbody></table>

</details>
