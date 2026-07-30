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
---

# RUBYPLAY.

<mark style="color:$info;">Aquí encontrarás información importante que se debe tener en cuenta al momento de la creación de un bono FreeSpin para el proveedor RUBYPLAY.</mark>

### 1. Acceso al Módulo:

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (90).png" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla de la sección FreeSpin.</p></figcaption></figure>

### **3. Formulario para creación de bonos RUBYPLAY**

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **RUBYPLAY** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

<table><thead><tr><th width="140.5">Sección</th><th width="108.126220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha + botón</td><td>Define la fecha de inicio y finalización durante la cual el bono estará activo.</td></tr><tr><td><strong><code>Proveedores</code></strong></td><td>Botón</td><td><p>Despliega el listado de proveedores que tienen activo el <strong>Bonus System</strong>. Para este bono se debe seleccionar el proveedor <strong>RUBYPLAY</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al configurar el proveedor y seleccionar los productos correspondientes, se desplegará una tabla en la que se debe especificar el porcentaje del bono que asumirá el proveedor <strong>RUBYPLAY</strong>.</p></div></td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td><p>Despliega las listas disponibles para seleccionar el juego al que aplicará el bono. Para visualizar los juegos disponibles, es necesario seleccionar nuevamente el proveedor <strong>RUBYPLAY</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Dentro del catálogo de juegos de <strong>RUBYPLAY</strong>, algunos juegos son compatibles con FreeSpin y otros no. La disponibilidad debe validarse previamente con el listado de juegos correspondiente.</p></div></td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/integraciones./manual-integraciones-por-proveedor./proveedores-con-configuraciones-para-bonos./rubyplay.#configuracion-de-moneda"><strong><code>Moneda</code></strong></a></td><td>Botón</td><td>Al seleccionar la moneda correspondiente al país con el que se genera el bono, se activarán las configuraciones necesarias para establecer el valor de las rondas gratuitas y los jugadores beneficiarios.</td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

<table><thead><tr><th width="114">Campo</th><th width="129">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Campo numérico</td><td><p>Define el monto asignado a cada ronda gratuita del bono.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El valor configurado debe coincidir exactamente con el monto de apuesta permitido por los juegos seleccionados. Si los valores no coinciden, el bono no funcionará correctamente.</p></div><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si se configura un <strong>Valor por ronda</strong> de <strong>10</strong>, pero el juego seleccionado tiene una apuesta máxima permitida de <strong>5</strong>, el bono no funcionará debido a que los valores configurados no coinciden.</p></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Campo numérico</td><td>Establece la cantidad de rondas gratuitas que podrá jugar el usuario con el bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Permite cargar un archivo en formato CSV con los ID de los jugadores que recibirán el bono. El sistema utilizará los ID incluidos en el archivo para activar el bono a los jugadores especificados.</td></tr></tbody></table>

<a href="https://virtualsoft.gitbook.io/manuales/integraciones./manual-integraciones-por-proveedor./proveedores-con-configuraciones-para-bonos./rubyplay.#id-3.-formulario-para-creacion-de-bonos-rubyplay" class="button secondary">Regresar</a>

</details>

Finaliza la configuración del bono guardando y aplicando las configuraciones realizadas desde el botón "**`Crear Bono`**".

***

{% hint style="warning" %}
**Nota:** Dentro del catálogo de juegos ofrecido por **RUBYPLAY**, algunos juegos cuentan con funcionalidad FreeSpin y otros no son compatibles con esta modalidad. Se debe validar previamente la compatibilidad del juego antes de realizar la configuración del bono.
{% endhint %}

* Consulta el listado de juegos compatibles y no compatibles con FreeSpin en el siguiente recurso:

[Game list - FR.xlsx](https://virtualsoftserv-my.sharepoint.com/:x:/g/personal/sebastian_rico_virtualsoft_tech/EUsOjXKTvvRFkaSS7u41MJYBCnkq4H1sP7lgC1ozM1SKFw?e=pvSBWw)

***

### **4. Validaciones y Reglas de Negocio**

* El proveedor seleccionado para este bono debe ser **RUBYPLAY**.
* El juego seleccionado debe ser compatible con la funcionalidad **FreeSpin** de RUBYPLAY.
* El **Valor por ronda** debe coincidir exactamente con el monto de apuesta permitido por el juego seleccionado. Si los valores no coinciden, el bono no funcionará correctamente.
* El archivo utilizado en la configuración de **Jugadores** debe estar en formato **CSV** y contener los ID de los jugadores que recibirán el bono.
* Al configurar los campos **Proveedores** y **Productos**, se debe especificar el porcentaje del bono que será asumido por el proveedor **RUBYPLAY**.
* La moneda seleccionada debe corresponder al país para el cual se está generando el bono.

***

### **5. Control de Versiones**

<details>

<summary>🕛Historial de versiones.</summary>

<table><thead><tr><th width="105.8148193359375">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>30/07/2026</td><td>Ronald Peláez</td><td>Documento inicial</td></tr></tbody></table>

</details>



