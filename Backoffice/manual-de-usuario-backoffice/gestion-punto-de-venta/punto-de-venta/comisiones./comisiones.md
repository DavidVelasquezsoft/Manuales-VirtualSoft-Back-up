---
description: >-
  En esta sección se encuentran las siguientes configuraciones relacionadas con
  las comisiones.
---

# Comisiones

### 1. Acceso al módulo

**Ruta de acceso**: Backoffice > Gestión punto de venta > punto de venta > buscar un punto de venta > 📁> 📁  > 🔎 > Comisiones > comisiones

{% @guideflow/guideflow-embed requestedUrl="https://app.guideflow.com/player/zkjxv87hep" %}

***

***

### 2. Configuraciones&#x20;

<details>

<summary>🔽Sportbook NGR Afiliados</summary>

Permite definir la distribución de comisiones sobre el NGR para los diferentes niveles (punto de venta, concesionarios y subconcesionarios)

{% hint style="warning" %}
**Nota:** En el cálculo de las comisiones, se debe tener en cuenta que los impuestos o comisiones adicionales también serán descontados del NGR.\
**Fórmula:** NGR = Apuestas – Bonos – Premios
{% endhint %}

#### 1. Acceso al módulo <a href="#id-1.-acceso-al-modulo-10" id="id-1.-acceso-al-modulo-10"></a>

**Ruta de acceso**: Backoffice > Gestión punto de venta > 🔎 > Comisiones > comisiones > Sportbook NGR Afiliados

***

#### 2. Visualización general <a href="#id-2.-visualizacion-general-2" id="id-2.-visualizacion-general-2"></a>

<figure><img src="../../../../.gitbook/assets/image (667).png" alt=""><figcaption><p>Figura 1: Captura de pantalla de la sección Sportbook NGR Afiliados</p></figcaption></figure>

***

#### 3. Acciones disponibles

<table><thead><tr><th width="122.0909423828125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Guardar</code></strong></td><td>Permite guardar la configuración de comisiones ingresada. El sistema valida la información antes de realizar el guardado.</td></tr></tbody></table>

#### 4. Configuraciones de Sportbook NGR Afiliados <a href="#id-3.-configuracion-de-niveles" id="id-3.-configuracion-de-niveles"></a>

<table><thead><tr><th width="184.3636474609375">Campo</th><th width="139.0909423828125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Comisión Usuario</code></strong></td><td>Numérico</td><td>Define el porcentaje de comisión asignado al punto de venta. Este valor corresponde a la ganancia del punto de venta sobre el NGR y sirve como referencia principal para la distribución de las demás comisiones.</td></tr><tr><td><strong><code>Por Concesionario</code></strong></td><td>Numérico</td><td>Define el valor de comisión correspondiente al concesionario. Es obligatorio.</td></tr><tr><td><strong><code>Por Subconcesionario</code></strong></td><td>Numérico</td><td>Define la comisión asignada al subconcesionario.</td></tr><tr><td><strong><code>Por Subconcesionario 1</code></strong></td><td>Numérico</td><td>Define la comisión asignada al subconcesionario 1 .</td></tr><tr><td><strong><code>Por Subconcesionario 2</code></strong></td><td>Numérico</td><td>Define la comisión asignada al subconcesionario  2.</td></tr><tr><td><strong><code>Total</code></strong></td><td>numérico (solo lectura)</td><td>Muestra la suma total de las comisiones ingresadas. Este valor se calcula automáticamente y no es editable.</td></tr></tbody></table>

### 5. Validaciones y reglas del negocio:

* Todos los campos de comisión son obligatorios.
* Los valores deben ser numéricos y mayores o iguales a cero.
* El campo **Total** se calcula automáticamente y no puede ser modificado.

</details>

<details>

<summary>🔽Sportbook GGR Punto venta IP</summary>



#### 1. Acceso al módulo <a href="#id-1.-acceso-al-modulo-10" id="id-1.-acceso-al-modulo-10"></a>

**Ruta de acceso**: Backoffice > Gestión punto de venta > 🔎 > Comisiones > comisiones > Sportbook GGR Punto venta IP

***

#### 2. Visualización general <a href="#id-2.-visualizacion-general-2" id="id-2.-visualizacion-general-2"></a>



Figura 1: Captura de pantalla de la sección Sportbook GGR Punto venta IP

***

#### 3. Configuraciones de Sportbook NGR Afiliados <a href="#id-3.-configuracion-de-niveles" id="id-3.-configuracion-de-niveles"></a>



</details>

<details>

<summary>🔽Sportbook GGR Punto venta</summary>



</details>

<details>

<summary>🔽Depósito Punto venta</summary>

<mark style="color:$info;">En esta sección se configuran los porcentajes de comisión aplicados a los depósitos realizados en el punto de venta.</mark>

#### 1. Acceso al módulo <a href="#id-1.-acceso-al-modulo-10" id="id-1.-acceso-al-modulo-10"></a>

**Ruta de acceso**: Backoffice > Gestión punto de venta > punto de venta >buscar un punto de venta > 📁> 📁 > 🔎 > Comisiones > comisiones

***

#### 2. Visualización general <a href="#id-2.-visualizacion-general-2" id="id-2.-visualizacion-general-2"></a>

<figure><img src="../../../../.gitbook/assets/image (668).png" alt=""><figcaption><p>Figura 1: Captura de pantalla de la sección Depósito Punto venta</p></figcaption></figure>

***

#### 3. Acciones disponibles

<table><thead><tr><th width="122.0909423828125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Guardar</code></strong></td><td>Guarda la configuración de comisiones ingresada. El sistema valida la información antes de realizar el guardado.</td></tr></tbody></table>

***

#### 4. Configuraciones de **Depósito Punto venta** <a href="#id-3.-configuracion-de-niveles" id="id-3.-configuracion-de-niveles"></a>

<table><thead><tr><th width="164">Campo</th><th width="124">Tipo</th><th width="392">Descripción</th></tr></thead><tbody><tr><td><strong><code>Comisión Usuario</code></strong></td><td>Numérico</td><td>Define el porcentaje de comisión que recibe el punto de venta sobre los depósitos realizados.</td></tr><tr><td><strong><code>Por Concesionario</code></strong></td><td>Numérico</td><td>Define el porcentaje de comisión asignado al concesionario dentro de la distribución de los depósitos.</td></tr><tr><td><strong><code>Por Subconcesionario</code></strong></td><td>Numérico</td><td>Define el porcentaje de comisión correspondiente al subconcesionario dentro de la estructura.</td></tr><tr><td><strong><code>Por Subconcesionario 1</code></strong></td><td>Numérico</td><td>Define el porcentaje de comisión para el primer nivel adicional de subconcesionario.</td></tr><tr><td><strong><code>Por Subconcesionario 2</code></strong></td><td>Numérico</td><td>Define el porcentaje de comisión para el segundo nivel adicional de subconcesionario.</td></tr><tr><td><strong><code>Total</code></strong></td><td>Numérico <em>(solo lectura</em>)</td><td>Muestra la suma total de los porcentajes ingresados. Este valor se calcula automáticamente y no puede ser modificado.</td></tr></tbody></table>

***

#### **5. Manuales relacionados**&#x20;

* [Reporte Comisiones Global | Manuales](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/reportes/reporte-comisiones-global)
* [Reporte de comisiones | Manuales](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/gestion-punto-de-venta/punto-de-venta/comisiones./reporte-de-comisiones)
* [Configuración | Manuales](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/gestion-punto-de-venta/punto-de-venta/configuracion#id-2.5.-configuracion-ntc-personalizada)

#### **6. Validaciones y reglas del negocio**

* Todos los campos de comisión son **obligatorios**.
* Los valores ingresados deben ser **numéricos** y **mayores o iguales a cero**.
* El campo **Total** se calcula automáticamente y **no es editable**.
* No se permite guardar la configuración si existen campos vacíos o con valores inválidos.
* Los cambios solo se aplican cuando el usuario hace clic en el botón **Guardar**.

</details>

<details>

<summary>🔽Apuesta Sport Punto venta</summary>



</details>

<details>

<summary>🔽Notas de retiro Punto venta</summary>



</details>

<details>

<summary>🔽Sportbook GGR Afiliados</summary>



</details>

<details>

<summary>🔽Casino NGR Afiliados</summary>



</details>

<details>

<summary>🔽Deposito Comision por Transaccion</summary>



</details>

<details>

<summary>🔽Sportbook NGR Afiliados con impuesto del 12%</summary>



</details>

<details>

<summary>🔽Deposito Afiliados</summary>



</details>

### 3. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="101.88885498046875">Versión</th><th width="151.272705078125">Fecha</th><th width="168.727294921875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21/04/2026</td><td>Karol Navia</td><td>Documento inicial</td></tr></tbody></table>

</details>
