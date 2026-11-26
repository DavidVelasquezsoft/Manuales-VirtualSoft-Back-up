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

# Veliplay

<mark style="color:$info;">Permite la creación, configuración y gestión de bonos de giros gratuitos (FreeSpin) asociados a los juegos del proveedor.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (108).png" alt=""><figcaption><p>Figura #1: Captura de pantalla creación bono freeSpin.</p></figcaption></figure>

### 3. Formulario para creación de bonos Veliplay

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **Veliplay** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% content-ref url="https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}
[FreeSpin](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin)
{% endcontent-ref %}

<table><thead><tr><th width="112">Sección</th><th width="96.18182373046875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón Agregar</td><td>Define la fecha de inicio y finalización en la que el bono estará activo.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Define el nombre que se asignará al bono.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Campo numérico</td><td>Indica la prioridad del bono frente a otros activos.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Breve explicación de las condiciones o características del bono.</td></tr><tr><td><strong><code>Cantidad de jugadores</code></strong></td><td>Numérico</td><td>Define el número total de usuarios que recibirán el bono.</td></tr><tr><td><strong><code>Valor por giro</code></strong></td><td>Campo numérico</td><td>Indica el monto exacto de la apuesta por cada giro.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td>Selecciona el proveedor del bono, en este caso "<em><strong>Veliplay</strong></em>".</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td>Lista los juegos disponibles del proveedor seleccionado. Se debe elegir el título específico.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td><p>Al seleccionar la moneda, se activaran las siguientes configuraciones.</p><table><thead><tr><th width="107">Campo</th><th width="106">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Campo numérico</td><td><p>Define el monto de la apuesta para cada giro gratuito ingresando el número correspondiente al nivel de apuesta (ejemplo: <strong>1, 2 o 3</strong>).<br>Los valores permitidos son los siguientes:</p><ul><li><strong>BetLevel 1 → USD 0.10</strong></li><li><strong>BetLevel 2 → USD 0.20</strong></li><li><strong>BetLevel 3 → USD 1.00</strong></li><li><strong>BetLevel 4 → USD 2.00</strong></li><li><strong>BetLevel 5 → USD 5.00</strong></li></ul><div data-gb-custom-block data-tag="hint" data-style="danger" class="hint hint-danger"><p><strong>Nota:</strong> Solo se podrán seleccionar los valores de apuesta definidos en esta lista.<br>En caso de que el bono se configure con un nivel de apuesta diferente a los permitidos, este <strong>no será válido</strong> y no se podrá aplicar al jugador.</p></div></td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Permite cargar un archivo en formato <a href="https://virtualsoft.gitbook.io/untitled/glosario#csv">CSV</a> con los ID de los jugadores que recibirán el bono.</td></tr></tbody></table></td></tr><tr><td><strong><code>Cliente puede recibir otros bonos adicionales</code></strong></td><td>Selector</td><td>Permite definir si el cliente podrá acumular más bonos.</td></tr><tr><td><strong><code>Cliente puede repetir bono</code></strong></td><td>Selector</td><td>Define si el mismo bono se puede asignar más de una vez al mismo usuario.</td></tr><tr><td><strong><code>Crear Bono</code></strong></td><td>Botón</td><td>Guarda la configuración y activa el bono.</td></tr></tbody></table>

***

* La información de este bono estará disponible en la reportería de _Productos No Deportivos_.

{% hint style="warning" %}
**Nota:** Si se realiza una compra de giros en la tienda del proveedor, las ganancias de estos giros se reportarán como "**Premios**" y no como "**Premios bonos**"
{% endhint %}

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/readme/reportes/reporte-productos-no-deportivos" %}
[Reporte productos no deportivos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/readme/reportes/reporte-productos-no-deportivos)
{% endcontent-ref %}

* La información sobre los movimientos realizados por el usuario con este bono estará disponible en la reportería _Historial de movimientos._

{% hint style="warning" %}
**Nota:** El historial de movimientos mostrará un registro independiente por cada jugada gratuita realizada.
{% endhint %}

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/readme/jugadores/reportes-seccion-jugadores/historial-de-movimientos" %}
[Historial de movimientos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/readme/jugadores/reportes-seccion-jugadores/historial-de-movimientos)
{% endcontent-ref %}

***

### 4. Validaciones y Reglas de Negocio

* El bono se crea de forma inmediata, pero la asignación a jugadores puede tardar entre **2 y 3 minutos**.
* No se permite la creación de bonos con fechas de inicio anteriores a la fecha actual del sistema.
* La fecha de finalización siempre debe ser mayor a la fecha de inicio.

***

### 5. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>30/09/2025</td><td>Karol Navia</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>26/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
