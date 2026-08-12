---
description: >-
  Permite la creación, configuración y gestión de bonos de giros gratuitos
  (FreeSpin) asociados a los juegos del proveedor.
---

# Barbarabang

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Torneos y Bonos > Bono FreeSpin

***

### 2. Visualización:

<figure><img src="../../.gitbook/assets/image (103).png" alt=""><figcaption><p>Figura#1: Captura de pantalla creación bono FreeSpin.</p></figcaption></figure>

### **3. Formulario para creación de bonos Barbarabang.**

Estas son las configuraciones principales y necesarias para generar un bono FreeSpin con los juegos del proveedor Barbarabang, en caso de necesitar información más detallada sobre cómo crear el bono FreeSpin, puedes acceder a la siguiente página:

{% content-ref url="https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}
[FreeSpin](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin)
{% endcontent-ref %}

<table><thead><tr><th width="123">Sección</th><th width="96.18182373046875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón Agregar</td><td><p>Define la fecha de inicio y finalización en la que el bono estará activo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> La fecha de inicio debe ser igual o posterior a la fecha actual.</p></div></td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td>Selecciona el proveedor del bono, en este caso "<strong>Barbarabang</strong>".</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td><p>Juegos <em>(productos)</em> a los que aplicará el bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> </p><ul><li>Al seleccionar un juego, se habilitará una tabla que mostrará el porcentaje del bono asumido por el proveedor <strong>Barbarabang</strong>.</li><li>Solo se debe seleccionar un juego por bono creado, en caso de seleccionar más de 2 juegos el bono se creará, pero no se les asignará a los usuarios.</li></ul></div></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Al seleccionar la moneda, se activarán las siguientes configuraciones.<br><a href="https://virtualsoft.gitbook.io/manuales/integraciones./manual-integraciones-por-proveedor./proveedores-con-configuraciones-para-bonos./barbarabang#configuracion-de-moneda" class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

<details>

<summary><strong>🔽 Configuración de moneda.</strong></summary>

<table><thead><tr><th width="107">Campo</th><th width="125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Numérico</td><td><p>Define el monto de la apuesta asignado a cada giro gratuito.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El valor ingresado en este campo debe ser exactamente uno de los valores permitidos en apuestas dentro del juego, en caso de ingresar un valor distinto, el bono se creará, pero no se asignará.</p></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Cantidad de giros gratis que tendrá el bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Carga un archivo en formato CSV con los ID de los jugadores que recibirán el bono.</td></tr></tbody></table>

<a href="https://virtualsoft.gitbook.io/manuales/integraciones./manual-integraciones-por-proveedor./proveedores-con-configuraciones-para-bonos./barbarabang#id-3.-formulario-para-creacion-de-bonos-barbarabang" class="button secondary">Regresar</a>

</details>

Finaliza la configuración del bono guardando y aplicando las configuraciones realizadas desde el botón "**`Crear Bono`**".

***

* La información de este bono estará disponible en la reportería de _Productos No Deportivos_.

{% hint style="warning" %}
Nota: Si se realiza una compra de giros en la tienda del proveedor, las ganancias de estos giros se reportarán como "**Premios**" y no como "**Premios bonos**"
{% endhint %}

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos" %}
[Reporte productos no deportivos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-productos-no-deportivos)
{% endcontent-ref %}

* La información sobre los movimientos realizados por el usuario con este bono estará disponible en la reportería _Historial de movimientos._

{% hint style="warning" %}
**Nota:** El historial de movimientos mostrará un registro agrupado por bono redimido.
{% endhint %}

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/historial-de-movimientos" %}
[Historial de movimientos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/historial-de-movimientos)
{% endcontent-ref %}

***

### **4. Validaciones y Reglas de Negocio**

* El bono se crea de forma inmediata, pero la asignación a jugadores puede tardar entre **2 y 3 minutos**.
* El bono solo se puede configurar para un único juego. En caso de seleccionar varios juegos simultáneamente, el sistema asignará el bono únicamente a uno de ellos de forma aleatoria.

***

### &#x20;**5. Control de Versiones**

<details>

<summary><strong>🔽Historial de versiones</strong></summary>

| Versión | Fecha      | Autor         | Cambios Realizados   |
| ------- | ---------- | ------------- | -------------------- |
| 1.0     | 27/11/2025 | Ronald Pelaez | Documento inicial    |
| 1.1     | 05/08/2026 | Ronald Peláez | Ajustes en plantilla |

</details>
