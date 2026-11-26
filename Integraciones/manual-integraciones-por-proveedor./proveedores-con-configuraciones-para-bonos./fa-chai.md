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

# FA Chai

<mark style="color:$info;">Aquí encontrarás información importante que se debe tener en cuenta al momento de la creación de un bono FreeSpin para el proveedor FA Chai.</mark>

### 1. Acceso al Módulo

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización

<figure><img src="https://2840730235-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FpVk1Kqoe0aInaa5Ofl6i%2Fuploads%2Fd8eTDDmwLdFjT3eQanUz%2Fimage.png?alt=media&#x26;token=6a75d10d-f5f3-448d-97e9-3be2b6bd6b5f" alt=""><figcaption><p>Figura #1: Captura de pantalla creación bono FreeSpin.</p></figcaption></figure>

### 3. Formulario para creación de bonos FA Chai

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **FA Chai** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% content-ref url="https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}
[FreeSpin](https://app.gitbook.com/s/rLdGx9JdTz3uLoquKvJw/readme/como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin)
{% endcontent-ref %}

<table><thead><tr><th width="123">Sección</th><th width="96.18182373046875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td><p>Define la fecha de inicio y finalización en la que el bono estará activo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El rango máximo desde Fecha Inicio a Fecha Fin es de 30 días.</p></div></td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Define el nombre que se asignará al bono.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Campo numérico</td><td><p>Define la prioridad del bono frente a otros activos. En caso de que existan varios bonos activos, el sistema dará preferencia al bono con el valor de prioridad más alto.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> si se configuran dos bonos con prioridad 10 y 1 respectivamente, el sistema aplicará primero el bono con prioridad <strong>10</strong>.</p></div></td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Breve explicación de las condiciones o características del bono.</td></tr><tr><td><strong><code>Cantidad de jugadores</code></strong></td><td>Numérico</td><td>Define el número total de usuarios que recibirán el bono.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td>Selecciona el proveedor del bono, en este caso "FA Chai".</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td>En este campo se debe seleccionar el título específico al cual se asociará el bono. Solo es posible crear un bono por cada juego.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Al seleccionar la moneda, se activarán las siguientes configuraciones.<br><a href="fa-chai.md#configuracion-de-moneda" class="button secondary">Configuraciones por moneda</a></td></tr><tr><td><strong><code>Cliente puede recibir otros bonos adicionales</code></strong></td><td>Selector</td><td>Permite definir si el cliente podrá acumular más bonos, aparte del actual.</td></tr><tr><td><strong><code>Cliente puede repetir bono</code></strong></td><td>Selector</td><td>Define si el mismo bono se puede asignar más de una vez al mismo usuario.</td></tr><tr><td><strong><code>Crear Bono</code></strong></td><td>Botón</td><td>Guarda la configuración y activa el bono.</td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

Al seleccionar la moneda será necesario configurar los siguientes campos

<table><thead><tr><th width="154">Campo</th><th width="157">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Numérico</td><td>Establece el valor que tendrá asignado a cada ronda jugada bajo este bono.</td></tr><tr><td><strong><code>Rondas gratuitas</code></strong> </td><td>Numérico</td><td>Determina la cantidad total de rondas gratuitas que se otorgarán al usuario como parte del bono.</td></tr><tr><td><strong><code>límite de ganancia</code></strong></td><td>Numérico</td><td>Establece el monto máximo acumulado que el usuario podrá obtener con este bono. Si las ganancias superan este valor, únicamente se acreditará el monto correspondiente al límite configurado.</td></tr><tr><td><strong><code>Límite mínimo de ganancia</code></strong></td><td>Numérico</td><td>Define el monto mínimo que debe alcanzarse en una ronda para que la ganancia sea válida y acreditada. Si el premio obtenido es inferior a este valor, no se realizará acreditación.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Archivo CSV</td><td>Permite cargar un archivo en formato CSV con los ID de los jugadores que recibirán el bono.</td></tr></tbody></table>

</details>

***

La información de este bono estará disponible en la reportería de _Productos No Deportivos_.

{% content-ref url="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/readme/reportes/reporte-productos-no-deportivos" %}
[Reporte productos no deportivos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/readme/reportes/reporte-productos-no-deportivos)
{% endcontent-ref %}

***

### 4. Validaciones y Reglas de Negocio

* El bono se crea de forma inmediata, pero la asignación a jugadores puede tardar entre **2 y 3 minutos**.
* El bono solo se puede configurar para un único juego. En caso de seleccionar varios juegos simultáneamente, el sistema asignará el bono únicamente a uno de ellos de forma aleatoria.
* Si se ingresa un valor erróneo en el campo **`Valor por ronda`** el bono se creará, pero no se le asignará al usuario.
* Las configuraciones de monto mínimo y monto máximo se validan con el valor final del bono.

***

### 5. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>17/02/2026</td><td>Ronald Peláez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>26/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
