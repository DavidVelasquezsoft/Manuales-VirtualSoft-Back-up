---
description: >-
  Permite crear nuevas conversiones, consultar las existentes y actualizar las
  tasas de cambio cuando sea necesario, asegurando que las operaciones se
  realicen con valores actualizados y consistentes.
---

# TRM Virtual Soft

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > TRM Virtual Soft.

{% hint style="danger" %}
**Nota importante:**

* Si no puedes ver la opción **"**[**TRM Virtual Soft**](https://virtualsoft.gitbook.io/untitled/glosario#trm)**"**, solicita el permiso correspondiente al equipo de soporte.&#x20;
* Si eliminas un TRM, **no podrás volver a crearlo con los mismos valores de moneda origen y moneda destino**. En caso de necesitarlo nuevamente, contacta al equipo de soporte para su reactivación.
{% endhint %}

***

### 2. Visualización:

<figure><img src="../.gitbook/assets/image (590).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección TRM.</p></figcaption></figure>

### **3. Acciones del Usuario**

#### **3.1. Crear** [**TRM**](https://virtualsoft.gitbook.io/untitled/glosario#trm)**:**

Al hacer clic en el botón **Crear TRM**, se abre un pop-up que contiene los siguientes campos:

<table><thead><tr><th width="158.09088134765625">Campo</th><th width="167">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Moneda de origen</code></strong></td><td>Lista desplegable</td><td>Selecciona la moneda desde la cual se realizará la conversión.</td></tr><tr><td><strong><code>Moneda de destino</code></strong></td><td>Lista desplegable</td><td>Selecciona la moneda a la cual se realizará la conversión.</td></tr><tr><td><strong><code>Tasa de cambio (TRM)</code></strong></td><td>Numérico</td><td>Ingresa la tasa de conversión entre las dos monedas.</td></tr><tr><td><strong><code>Agregar conversión</code></strong></td><td>Botón</td><td>Guarda el TRM configurado.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Botón</td><td>Cierra el pop-up sin guardar cambios.</td></tr></tbody></table>

#### **3.2  Crear** [**TRM criptomoneda**](https://virtualsoft.gitbook.io/untitled/glosario#trm)

Al hacer clic en el botón **TRM criptomoneda**, se abre un pop-up que contiene los siguientes campos:

<table><thead><tr><th width="158.09088134765625">Campo</th><th width="167">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Moneda de origen</code></strong></td><td>Lista desplegable</td><td>Selecciona la moneda desde la cual se realizará la conversión.</td></tr><tr><td><strong><code>Criptomoneda destino</code></strong></td><td>Lista desplegable</td><td>Selecciona la Criptomoneda a la cual se realizará la conversión.</td></tr><tr><td><strong><code>Tasa de cambio (TRM)</code></strong></td><td>Numérico</td><td>Ingresa la tasa de conversión entre las dos monedas.</td></tr><tr><td><strong><code>Agregar conversión</code></strong></td><td>Botón</td><td>Guarda el TRM configurado.</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Botón</td><td>Cierra el pop-up sin guardar cambios.</td></tr></tbody></table>

#### **3.3. Consultar** [**TRM**](https://virtualsoft.gitbook.io/untitled/glosario#trm)**:**

Al dar clic en **Consultar**, se despliega una tabla con los siguientes datos:

<table><thead><tr><th width="217">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Moneda de origen</code></strong></td><td>Muestra la moneda desde la cual se genera la conversión.</td></tr><tr><td><strong><code>Moneda de destino</code></strong></td><td>Muestra la moneda hacia la cual se realiza la conversión.</td></tr><tr><td><strong><code>Tasa de cambio (TRM)</code></strong></td><td>Valor configurado de la tasa de conversión.</td></tr><tr><td><strong><code>Acciones</code></strong></td><td><ul><li>Ícono ✏️: Permite editar únicamente la tasa de cambio registrada.</li><li>Ícono ❌: Inactiva el TRM seleccionado y lo elimina visualmente del sistema.</li></ul></td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Indica el tipo de conversión realizada, por ejemplo: de Fiat a Fiat o de Fiat a Cripto.</td></tr></tbody></table>

***

### **4. Validaciones y Reglas de Negocio**

* Si eliminas un TRM, **no podrás volver a crearlo con la misma combinación de moneda origen y moneda destino**. Para reactivarla, será necesario solicitar soporte al equipo encargado.

***

### **5. Control de Versiones**

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="101">Versión</th><th width="170">Fecha</th><th width="142">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21/08/2025</td><td>Karol Navia</td><td>Aplicación del formato</td></tr><tr><td>1.1</td><td>26/09/2025</td><td>Karol Navia</td><td>Agregar TRM criptomoneda</td></tr></tbody></table>

</details>
