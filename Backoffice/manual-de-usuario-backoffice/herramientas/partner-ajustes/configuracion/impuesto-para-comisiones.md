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

# Impuesto para comisiones

Este módulo permite configurar y gestionar los impuestos aplicables a las comisiones, según el tipo de transacción y tipo de comisión, segmentados por marca y país. Su objetivo es asegurar el cálculo correcto de impuestos y comisiones en las operaciones y reportes, adaptándose a distintos contextos fiscales y regulatorios.

***

### 1. Acceso al Módulo

**Ruta de acceso:** BackOffice > Herramientas > Partner Ajustes > Configuración > Impuestos para Comisiones

***

### 2. Visualización General

<figure><img src="../../../../.gitbook/assets/image (628).png" alt=""><figcaption><p>Figura #1: Captura de pantalla impuestos para comisiones.</p></figcaption></figure>

***

### 3. Funcionalidades

<table><thead><tr><th width="253">Función</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Configuración de Impuestos</strong></td><td>Permite definir el porcentaje de impuesto aplicable a cada sección del partner, según el país seleccionado, asegurando una correcta parametrización de los valores fiscales asociados a las comisiones.</td></tr></tbody></table>

#### **🧾 3.1 Tipos de Comisión Disponibles**

El sistema permite configurar impuestos para los siguientes tipos de comisión:

<table><thead><tr><th width="212">Tipo de Comisión</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Sportbook NGR Afiliados</code></strong></td><td>Comisión calculada sobre el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#net-gaming-revenue-ngr">Net Gaming Revenue (NGR) </a>generado por los afiliados en apuestas deportivas, considerando apuestas, premios y bonos.</td></tr><tr><td><strong><code>Depósito Afiliados</code></strong></td><td>Comisión generada a partir de los depósitos realizados por afiliadores.</td></tr><tr><td><strong><code>Sportbook GGR Punto venta IP</code></strong></td><td>Comisión basada en el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr">Gross Gaming Revenue (GGR)</a> generado por apuestas deportivas realizadas desde un punto de venta.</td></tr><tr><td><strong><code>Sportbook GGR Punto venta</code></strong></td><td>Comisión calculada sobre el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr">Gross Gaming Revenue (GGR)</a> generado por las apuestas deportivas de un punto de venta.</td></tr><tr><td><strong><code>Depósito Punto venta</code></strong></td><td>Comisión asociada a los depósitos realizados en un punto de venta.</td></tr><tr><td><strong><code>Apuesta Sport Punto venta</code></strong></td><td>Comisión generada por las apuestas deportivas realizadas desde un punto de venta.</td></tr><tr><td><strong><code>Notas de retiro Punto venta</code></strong></td><td>Comisión aplicada sobre las solicitudes de retiro realizadas por un punto de venta.</td></tr><tr><td><strong><code>Sportbook GGR Afiliados</code></strong></td><td>Comisión calculada sobre el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ggr">Gross Gaming Revenue (GGR)</a> generado por los afiliados en apuestas deportivas.</td></tr><tr><td><strong><code>Casino NGR Afiliados</code></strong></td><td>Comisión calculada sobre el <a href="https://virtualsoft.gitbook.io/untitled/glosario/#net-gaming-revenue-ngr">Net Gaming Revenue (NGR)</a> generado por los afiliados en juegos de casino.</td></tr><tr><td><strong><code>Depósito Comisión por Transacción</code></strong></td><td>Comisión aplicada individualmente a cada transacción de depósito realizada en la plataforma.</td></tr></tbody></table>

***

### 4. Reglas de Cálculo

El valor del impuesto se calcula según el tipo de transacción asociado a la comisión:

<table><thead><tr><th width="193">Tipo</th><th>Fórmula</th></tr></thead><tbody><tr><td><strong><code>GGR</code></strong></td><td>(Apuestas − Premios) × (Impuesto %)</td></tr><tr><td><strong><code>NGR</code></strong></td><td>(Apuestas − Premios − Bonos) × (Impuesto %)</td></tr><tr><td><strong><code>Depósitos</code></strong></td><td>Depósitos × (Impuesto %)</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>Retiros × (Impuesto %)</td></tr></tbody></table>

***

#### **4.2 📊 Cálculo de la Comisión**

Una vez aplicado el impuesto, la comisión se calcula sobre el valor neto resultante:

<table><thead><tr><th width="231">Tipo</th><th>Fórmula</th></tr></thead><tbody><tr><td><strong><code>Depósitos</code></strong></td><td>(Depósitos − Valor Impuesto) × (% Comisión)</td></tr><tr><td><strong><code>Retiros</code></strong></td><td>(Retiros − Valor Impuesto) × (% Comisión)</td></tr><tr><td><strong><code>GGR</code></strong></td><td>(GGR − Valor Impuesto) × (% Comisión)</td></tr><tr><td><strong><code>NGR</code></strong></td><td>(NGR − Valor Impuesto) × (% Comisión)</td></tr></tbody></table>

***

### 5. ✅ Validaciones y Reglas de Negocio

* El impuesto se configura de forma independiente por **marca, país y tipo de comisión**.
* El porcentaje de impuesto debe ser un valor numérico entre **0 y 100**.
* Si no existe un impuesto configurado para un tipo de comisión, **no se aplica ningún impuesto**.
* Los cálculos de impuestos y comisiones se reflejan automáticamente en las operaciones y reportes correspondientes.
* Los cambios en la configuración de impuestos impactan únicamente las operaciones y reportes posteriores a su aplicación.

***

#### 6.🕒 Control de Versiones

<table><thead><tr><th width="109">Versión</th><th width="123">Fecha</th><th width="164">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2025-12-23</td><td>Ronald Peláez</td><td>Documento inicial.</td></tr></tbody></table>
