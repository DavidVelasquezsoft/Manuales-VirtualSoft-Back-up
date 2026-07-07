---
description: >-
  Permite configurar los porcentajes de comisión que se asignan a usuarios,
  concesionarios y sub‑concesionarios, aplicando el impuesto del 12% de
  impuestos sobre apuestas deportivas según la regula
---

# Sportbook NGR afiliados con impuesto del 12%

### 1. Acceso al Módulo

**Ruta de acceso**: Gestión punto de venta > Puntos de venta > 🔍 > Comisiones > Sportbook NGR Afiliados con impuesto del 12%

***

### 2. Visualización:

<figure><img src="../../../.gitbook/assets/image (529).png" alt=""><figcaption><p>figura#1: Captura de pantalla sección Sportbook NGR afiliados con impuesto del 12%.</p></figcaption></figure>

### 3. Funcionalidades

<table><thead><tr><th width="206">Campo</th><th width="117">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Comisión Usuario</code></strong></td><td>Numérico</td><td>Porcentaje de la comisión que se le dará al usuario afiliado. </td></tr><tr><td><strong><code>Por Concesionario</code></strong></td><td>Numérico</td><td>Porcentaje de la comisión que se asigna al concesionario .</td></tr><tr><td><strong><code>Por Subconcesionario 1</code></strong></td><td>Numérico</td><td>Porcentaje de comisión destinada al primer subconcesionario.</td></tr><tr><td><strong><code>Por Subconcesionario 2</code></strong></td><td>Numérico</td><td>porcentaje de comisión destinada al segundo subconcesionario.</td></tr><tr><td><strong><code>Total</code></strong></td><td>Calculado</td><td>Suma de todas los campos establecidos anteriormente.</td></tr><tr><td><strong><code>Guardar</code></strong></td><td>Botón</td><td>Guarda la información en el sistema.</td></tr></tbody></table>

***

### 4. Validaciones y Reglas de Negocio

* Todos los montos (`Comisión Usuario`, `Por Concesionario`, `Por Subconcesionario 1`, `Por Subconcesionario 2`) deben ser numéricos y mayor o igual a 0.
* El campo `Total` es la suma automática de los subcomponentes. Si la suma no coincide con el NGR neto disponible, se muestra una advertencia que impide el guardado.
* Este ajuste se aplica **solo** para operaciones de Perú (ej. Gangabet Perú y Doradobet Perú) y sobre el NGR ya neteado con el 12% de impuesto descontado.
* La base para el reparto es el **NGR Neto**:
  *   Cálculo previo:

      ```
      NGR bruto = Apuestas - Premios - Bonos  
      Impuesto (12%) = NGR bruto * 0.12  
      NGR Neto = NGR bruto - Impuesto
      ```

***

### 5. Control de Versiones

<details>

<summary>🔽Historial de Versiones</summary>

<table><thead><tr><th width="107">Versión</th><th width="144">Fecha</th><th width="137">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>31/07/2025</td><td>Karol Navia</td><td>Documento inicial.</td></tr></tbody></table>

</details>
