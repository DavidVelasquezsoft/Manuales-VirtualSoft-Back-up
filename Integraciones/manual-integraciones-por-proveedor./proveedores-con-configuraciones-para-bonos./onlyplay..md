---
description: >-
  Aquí encontrarás información importante que se debe tener en cuenta al momento
  de la creación de un bono FreeSpin para ONLYPLAY.
---

# ONLYPLAY.

{% hint style="danger" %}
**Nota importante**: Antes de crear el bono es necesario que los juegos del proveedor estén cerrados, en caso de crear el bono con los juegos abiertos es necesario cerrar el juego y volverlo a abrir para visualizar el bono creado.
{% endhint %}

#### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Torneos y Bonos > Bono FreeSpin

***

#### 2. Visualización

<figure><img src="../../.gitbook/assets/image (119).png" alt=""><figcaption></figcaption></figure>

#### 3. Acciones del Usuario

Estas son las configuraciones principales y necesarias para generar un bono FreeSpin con los juegos del proveedor ONLYPLAY. En caso de necesitar información más detallada sobre cómo crear el bono FreeSpin, puedes acceder a la siguiente página.

<table><thead><tr><th width="149">Sección</th><th width="155">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td><p>Define la fecha de inicio y finalización en la que el bono estará activo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: El rango máximo desde Fecha Inicio a Fecha Fin es de 30 días.</p></div></td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td>Despliega únicamente los proveedores que tienen habilitada la integración con Bonus System. Para este caso se debe seleccionar el proveedor <strong>ONLYPLAY</strong>.</td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td><p>Permite seleccionar los juegos disponibles para el proveedor elegido. Al acceder a esta opción será necesario seleccionar nuevamente el proveedor <strong>ONLYPLAY</strong> para visualizar el catálogo de juegos disponibles.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota</strong>: Al configurar los campos <strong>Proveedor</strong> y <strong>Productos</strong>, se desplegará una tabla donde deberá indicarse el porcentaje del bono que será asumido por el proveedor.</p></div></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Al seleccionar la moneda correspondiente al país donde se utilizará el bono, se habilitarán las configuraciones específicas del proveedor.<br><a class="button secondary">Configuración Moneda</a></td></tr><tr><td><strong><code>Crear Bono</code></strong></td><td>Botón</td><td>Guarda la configuración y activa el bono.</td></tr></tbody></table>

<details>

<summary><strong>Configuración de moneda</strong></summary>

<table><thead><tr><th width="146">Campo</th><th width="141">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Numérico</td><td><p>valor que tendrá el bono por cada ronda, teniendo en cuenta las cuotas del juego multiplicada por cien.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong></p><ul><li>Si un juego tiene una cuota de <strong>0.25</strong>.</li><li>El valor por ronda debe configurarse como <strong>25</strong>.</li><li>Fórmula: <strong>Cuota × 100 = Valor por ronda</strong>.</li></ul></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Define la cantidad total de giros gratuitos que recibirá cada usuario beneficiado por el bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "<strong>Seleccionar archivo</strong>"</td><td>Permite cargar un archivo en formato CSV con los ID de los jugadores que recibirán el bono. El sistema procesará automáticamente la información y asignará el bono a los usuarios incluidos en el archivo.</td></tr></tbody></table>

</details>

***

#### 4. Validaciones y Reglas de Negocio

* El bono se crea de forma inmediata, pero la asignación a jugadores puede tardar entre **2 y 3 minutos**.
* El campo **Valor por ronda** debe configurarse utilizando la fórmula **Cuota × 100**.
* Si el valor configurado no corresponde a una cuota válida para el juego seleccionado, el bono podrá crearse, pero no será asignado correctamente al usuario.
* Al configurar los campos **Proveedor** y **Productos**, es obligatorio definir el porcentaje del bono que será asumido por el proveedor.
* Cada jugada gratuita otorgada a través del **Bonus System** debe registrarse de manera individual en la reportería; no está permitido consolidar múltiples jugadas en un solo registro.
* Los premios derivados de bonos deben reportarse asociados explícitamente al juego específico en el que fueron otorgados.
* La información reportada debe permitir identificar de forma clara y diferenciada:
  * Jugadas estándar.
  * Jugadas provenientes de bonos.
  * Premios estándar y premios generados por bonos.
* Para validar las cuotas disponibles de cada juego del proveedor ONLYPLAY, puedes consultarlas directamente desde la plataforma.

***

#### 5. Control de Versiones

<details>

<summary>🔽 Historial de versiones.</summary>

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 23/06/2026 | Ronald Peláez | Documento inicial  |

</details>
