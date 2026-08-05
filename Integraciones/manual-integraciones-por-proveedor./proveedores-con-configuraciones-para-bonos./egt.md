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

# EGT

<mark style="color:$info;">Aquí encontrarás información importante que se debe tener en cuenta al momento de la creación de un bono FreeSpin para el proveedor EGT.</mark>

### 1. Acceso al Módulo:

**Ruta de Acceso**: Torneos y bonos > Crear bono > Seleccionar País > FreeSpin

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (90).png" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla de la sección FreeSpin.</p></figcaption></figure>

### **3. Formulario para creación de bonos** EGT

Estas configuraciones corresponden a los campos que pueden presentar comportamientos específicos o variaciones propias del proveedor **EGT** dentro del proceso de creación de bonos FreeSpin.

Para consultar el detalle completo de los demás campos y la configuración general del bono, se recomienda acceder a la documentación principal indicada a continuación.

{% embed url="https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-bono./freespin" %}

<table><thead><tr><th width="105">Sección</th><th width="124">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Rango de fechas</code></strong></td><td>Selector de fecha</td><td>Define la fecha de inicio y finalización durante las cuales el bono permanecerá activo.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Botón</td><td><p>Selecciona el proveedor del bono, en este caso <strong>EGT</strong>.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al configurar los campos <strong>Proveedor</strong> y <strong>Productos</strong>, se desplegará una tabla donde se deberá especificar el porcentaje del bono que será asumido por el proveedor.</p></div></td></tr><tr><td><strong><code>Productos</code></strong></td><td>Botón</td><td>Permite seleccionar el juego para el cual aplicará el bono. Al seleccionar esta opción se mostrarán dos listas; es necesario volver a seleccionar el proveedor <strong>EGT</strong> para visualizar los juegos disponibles.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Botón</td><td>Selecciona la moneda correspondiente al país para el cual se creará el bono. Al hacerlo se habilitarán las configuraciones adicionales disponibles.<br><a class="button secondary">Configuraciones disponibles</a></td></tr></tbody></table>

<details>

<summary>🔽 Configuración de moneda</summary>

<table><thead><tr><th width="112">Campo</th><th width="146">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor por ronda</code></strong></td><td>Numérico</td><td><p>Monto asignado a cada giro del juego, al configurar esta opción, es crucial verificar previamente el monto de apuesta permitido en los juegos seleccionados, ya que este debe coincidir exactamente con el valor ingresado en este campo.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si se configura un valor por ronda de <strong>10</strong>, pero el juego únicamente permite una apuesta máxima de <strong>5</strong>, el bono no funcionará debido a que los valores no coinciden.</p></div></td></tr><tr><td><strong><code>Rondas gratuitas</code></strong></td><td>Numérico</td><td>Define la cantidad de rondas gratuitas que recibirá el usuario con este bono.</td></tr><tr><td><strong><code>Jugadores</code></strong></td><td>Botón "Seleccionar archivo"</td><td>Permite cargar un archivo en formato <strong>CSV</strong> con los ID de los jugadores que recibirán el bono. El sistema procesará automáticamente el archivo y asignará el bono a los usuarios incluidos.</td></tr></tbody></table>

<a class="button secondary">Regresar</a>

</details>

Finaliza la configuración del bono guardando y aplicando los cambios realizados desde el botón **`Crear Bono`**.

***

### **4. Validaciones y Reglas de Negocio**

* El proveedor seleccionado debe ser **EGT** para visualizar los juegos compatibles con este tipo de bono.
* La asignación de jugadores se realiza mediante la carga de un archivo **CSV** que contenga los ID de los usuarios que recibirán el bono.

***

### **5. Control de Versiones**

<details>

<summary>🔽 Historial de versiones.</summary>

<table><thead><tr><th width="104">Versión</th><th width="136">Fecha</th><th width="131">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>05/08/2026</td><td>Ronald Peláez</td><td>Documento inicial.</td></tr></tbody></table>

</details>
