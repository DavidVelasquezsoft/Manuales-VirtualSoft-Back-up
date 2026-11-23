---
description: >-
  Aquí encontrarás información importante que se debe tener en cuenta al momento
  de la creación de un bono FreeSpin para Netgaming.
---

# Netgaming

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Torneos y Bonos > Bono FreeSpin

***

### 2. Visualización:

<figure><img src="../../.gitbook/assets/image (103).png" alt=""><figcaption><p>Figura#1: Captura de pantalla creación bono FreeSpin.</p></figcaption></figure>

### **3. Acciones del Usuario**

Estas son las configuraciones principales y necesarias para generar un bono FreeSpin con los juegos del proveedor Netgaming, en caso de necesitar información más detallada sobre cómo crear el bono FreeSpin, puedes acceder a la siguiente página:

{% content-ref url="/broken/spaces/rLdGx9JdTz3uLoquKvJw/pages/In6CZXpJjhI4lzZIWd1Q" %}
[Broken link](/broken/spaces/rLdGx9JdTz3uLoquKvJw/pages/In6CZXpJjhI4lzZIWd1Q)
{% endcontent-ref %}

<table><thead><tr><th width="123">Sección</th><th width="100.626220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td>Define la fecha de inicio y finalización en la que el bono estará activo.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Define el nombre que se asignará al bono.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Campo numérico</td><td><p>Define la prioridad del bono frente a otros activos. En caso de que existan varios bonos activos, el sistema dará preferencia al bono con el valor de prioridad más alto.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> si se configuran dos bonos con prioridad 10 y 1 respectivamente, el sistema aplicará primero el bono con prioridad <strong>10</strong>.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Breve explicación de las condiciones o características del bono.</td></tr><tr><td><strong><code>Cantidad de jugadores</code></strong></td><td>Numérico</td><td>Define el número total de usuarios que recibirán el bono.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td>Selecciona el proveedor del bono, en este caso "Netgaming".</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td>Lista los juegos disponibles del proveedor seleccionado. Se debe elegir el título específico por bono creado <a href="netgaming.md#id-4.-validaciones-y-reglas-de-negocio"><sub>(Más información)</sub></a>.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Al seleccionar la moneda, se activarán las siguientes configuraciones.<br><a href="netgaming.md#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr><tr><td><strong><code>Cliente puede recibir otros bonos adicionales</code></strong></td><td>Selector</td><td>Permite definir si el cliente podrá acumular más bonos, aparte del actual.</td></tr><tr><td><strong><code>Cliente puede repetir bono</code></strong></td><td>Selector</td><td>Define si el mismo bono se puede asignar más de una vez al mismo usuario.</td></tr><tr><td><strong><code>Crear Bono</code></strong></td><td>Botón</td><td>Guarda la configuración y activa el bono.</td></tr></tbody></table>

<details>

<summary>Configuración de moneda</summary>

<table><thead><tr><th width="114">Campo</th><th width="129">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Campo numérico</td><td><p>Indica el valor que tendrá el bono por cada ronda gratuita.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El valor ingresado debe corresponder a un monto disponible dentro de la configuración del juego, específicamente a uno de los valores definidos en el campo <strong>“<code>Apuesta en efectivo</code>” que se encuentra dentro del mismo juego</strong>.</p></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Establece la cantidad de giros gratis que tendrá este bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Permite cargar un archivo en formato CSV con los ID de los jugadores que recibirán el bono.</td></tr></tbody></table>

<a href="netgaming.md#id-3.-acciones-del-usuario" class="button secondary">Regresar</a>

</details>

***

La información de este bono estará disponible en la reportería de _Productos No Deportivos_.

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos" %}
[Reporte productos no deportivos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos)
{% endcontent-ref %}

***

### **4. Validaciones y Reglas de Negocio**

* El bono se crea de forma inmediata, pero la asignación a jugadores puede tardar entre **2 y 3 minutos**.
* El bono solo se puede configurar para un único juego. En caso de seleccionar varios juegos simultáneamente, el sistema asignará el bono únicamente a uno de ellos de forma aleatoria.
* Si se ingresa un valor erróneo en el campo **`Valor por ronda`** el bono se creará, pero no se le asignará al usuario.
* Una vez creado el bono, este quedará funcional para CRM.

***

### &#x20;**5. Control de Versiones**

| Versión | Fecha      | Autor           | Cambios Realizados                          |
| ------- | ---------- | --------------- | ------------------------------------------- |
| 1.0     | 26/01/2026 | David velasquez | Documento inicial                           |
| 1.1     | 02/02/2026 | Ronald Peláez   | Refinamiento de manual por entrega de la HU |
