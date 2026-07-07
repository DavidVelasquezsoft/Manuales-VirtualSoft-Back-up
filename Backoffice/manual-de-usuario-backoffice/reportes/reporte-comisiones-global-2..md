---
description: >-
  Este reporte permite consultar la información relacionada con las comisiones
  globales generadas por afiliados, concesionarios y puntos de venta.
---

# Reporte Comisiones Global 2.

***

## **1. Acceso al módulo**

**Ruta de navegación**: Backoffice > Reportes > Reporte de Comisiones -

***

## 🖼️ 2. Visualización

<figure><img src="../../.gitbook/assets/image (552).png" alt=""><figcaption><p>Figura#1: Captura de pantalla seccion reporte comisiones global 2.</p></figcaption></figure>

***

## **🔍 3. Filtros de búsqueda**

<table><thead><tr><th width="95.72222900390625">Campo</th><th width="125.462890625">Tipo de Control</th><th width="393.7222900390625">Descripción</th><th>Validaciones</th></tr></thead><tbody><tr><td><code>Fecha</code></td><td>Calendario</td><td>Permite definir el rango de fechas para la consulta.</td><td>Formato: YYYY-MM-DD</td></tr><tr><td><code>Tipo Usuario</code></td><td>Lista desplegable</td><td>Filtra y muestra únicamente las comisiones correspondientes al tipo de usuario seleccionado: (Concesionario, Subconcesionario, Subconcesionario 2, Afiliado y Punto de Venta.).  <a href="https://virtualsoft.gitbook.io/untitled/glosario#tipos-de-usuario-comision">Ver definiciones</a></td><td>Campo opcional</td></tr><tr><td><code>Punto de Venta</code></td><td>Lista desplegable</td><td>Permite seleccionar un punto de venta específico.</td><td>Opcional</td></tr><tr><td><code>Tipo</code></td><td>Botón de opción</td><td>Define el formato del reporte: <strong>Totales</strong> (resumen) o <strong>Detallado</strong> (desglose).</td><td>Obligatorio</td></tr><tr><td><code>Mi Comisión</code></td><td>Botón de opción</td><td>Indica si se deben mostrar únicamente las comisiones asociadas al usuario actual.</td><td>Valor binario: Sí / No</td></tr><tr><td><code>País</code></td><td>Lista desplegable</td><td>Filtra la información por país o región.</td><td>Opcional</td></tr><tr><td><code>Nombre Afiliado</code></td><td>Campo de texto</td><td>Permite buscar un afiliado específico por nombre.</td><td>Opcional</td></tr></tbody></table>

***

## 🧑‍💻 **4. Acciones disponibles**

### **4.1. ⚙️ Click to configure**

Abre ventana emergente para configurar y agregar campos a los filtros y a los resultados de busqueda para visualizar datos más específicos y detallados:

<table><thead><tr><th width="222">Sección</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Fields</code> (<strong>Campos</strong>)</td><td>Lista de campos disponibles para aplicar a las demás secciones.</td></tr><tr><td><code>Filters</code> (<strong>Filtros</strong>)</td><td>Filtros que se mostrarán para hacer una búsqueda mas específica</td></tr><tr><td><code>Rows</code> (<strong>Filas</strong>)</td><td>Filas adicionales por cada registro en la tabla.</td></tr><tr><td><code>Columns</code> (<strong>Columnas</strong>)</td><td>Columnas adicionales por cada registro en la tabla.</td></tr><tr><td><code>Values</code> (<strong>Valores</strong>)</td><td>Valores que se muestran en la tabla durante la consultar.</td></tr></tbody></table>

#### 4.1.1. Acciones de configuración

Permite realizar diferentes acciones entre los campos y secciones:

<table><thead><tr><th width="183.2222900390625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td>Arrastrar</td><td>Permite sujetar cada campo y ubicarlo en la sección deseada.</td></tr><tr><td>✖️ (<strong>Eliminar</strong>)</td><td>Retira el campo de la sección correspondiente.</td></tr><tr><td>Cancel (<strong>Cancelar</strong>)</td><td>No aplica los cambios hechos.</td></tr><tr><td>Apply (<strong>Aplicar</strong>)</td><td>Aplica los cambios hechos en todas las secciones.</td></tr></tbody></table>

### 🔁 4.2. Limpiar

Restablece todos los filtros a su estado inicial.

### 🚀 4.3. Consultar

Aplica los filtros seleccionados y muestra los registros válidos con estos campos predeterminados.

{% hint style="warning" %}
**Nota:** El reporte **siempre genera resultados**, incluso si no se han generado comisiones durante el periodo consultado.
{% endhint %}

{% tabs %}
{% tab title="(SC#) Apuesta Sport Punto de Venta con impuesto 12%" %}
<table><thead><tr><th width="232.55560302734375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Monto</code></td><td>Valor total generado por las operaciones de apuestas deportivas.</td></tr><tr><td><code>Comisión</code></td><td>Monto correspondiente a la comisión generada.</td></tr><tr><td><code>Apuestas</code></td><td>Cantidad total de apuestas realizadas.</td></tr><tr><td><code>Premios</code></td><td>Total de premios entregados.</td></tr><tr><td><code>Bonos</code></td><td>Monto total de bonos otorgados.</td></tr></tbody></table>
{% endtab %}

{% tab title=" Total" %}
<table><thead><tr><th width="203.2222900390625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Monto</code></td><td>Suma total de los montos generados.</td></tr><tr><td><code>Comisión</code></td><td>Total acumulado de las comisiones.</td></tr><tr><td><code>Apuestas</code></td><td>Número total de apuestas realizadas.</td></tr><tr><td><code>Premios</code></td><td>Total de premios entregados.</td></tr><tr><td><code>Bonos</code></td><td>Suma total de bonos otorgados.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

* En la parte inferior se muestra una **fila** con el total de cada columna, calculando la suma de los valores de todos los registros.

***

### 5. ✅ Reglas de Negocio

* Esta lógica aplica exclusivamente a afiliados registrados en **Gangabet Perú** o **Doradobet Perú**, conforme a la normativa local vigente.

**Cálculo de NGR:**

> ℹ️ **Fórmulas aplicadas**
>
> 1. `Apuestas - Premios - Bonos = NGR`
> 2. `NGR * 12% = Impuestos`
> 3. `NGR - Impuestos = NGR Neto`
> 4. `NGR Neto * % Comisión = Comisión del afiliado`

{% hint style="info" %}
**Ejemplo de cálculo**

* **Apuestas**: 1,000 PEN
* **Premios**: 800 PEN
* **Bonos**: 50 PEN
* **NGR**: 1,000 - 800 - 50 = 150 PEN
* **Impuesto (12%)**: 150 × 12% = 18 PEN
* **NGR Neto**: 150 - 18 = 132 PEN
* **Comisión (25%)**: 132 × 25% = 33 PEN

En este ejemplo, el afiliado recibiría **33 PEN** como comisión neta del mes.
{% endhint %}

***

## 🕒 6. Control de Versiones

<table><thead><tr><th width="120.77777099609375">Versión </th><th width="137.2222900390625">Fecha</th><th width="163">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>​30-07-2025</td><td>Karol Navia</td><td>Documento inicial, actualización del formato</td></tr><tr><td>1.1</td><td>2025-08-25</td><td>David velasquez</td><td>Mejora de formato e incorporación de seccion "Click to configure".</td></tr></tbody></table>
