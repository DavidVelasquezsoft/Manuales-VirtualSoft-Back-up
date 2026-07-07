---
description: >-
  Permite consultar los reportes de las apuestas realizadas en loterías por los
  usuarios.
---

# Reporte de apuestas

### 1. Acceso al Módulo:

**Ruta de Acceso**: Jugadores > 🔍 >  Reportes > Reporte de apuestas

***

### 2. Visualización:

<figure><img src="../../../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="119.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtro</strong></td><td>Permite filtrar la información para obtener resultados más precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="reporte-de-apuestas.md#id-3.1.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="130.64642333984375">Campo</th><th width="119.0001220703125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Selector de rango</td><td>Selecciona el rango de fechas de las apuestas que deseas consultar.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite filtrar las apuestas según su estado.</td></tr><tr><td><strong><code>¿Eliminadas?</code></strong></td><td>Selección única</td><td><p>Permite filtrar las apuestas según hayan sido eliminadas o no del sistema.</p><ul><li><strong>Sí</strong>: Muestra únicamente las apuestas que fueron eliminadas.</li><li><strong>No</strong>: Muestra únicamente las apuestas activas y no eliminadas.</li></ul></td></tr></tbody></table>

### 5. Consultar

Aplica los filtros seleccionados y muestra los reportes detallados del historial de depósitos del usuario.

<table><thead><tr><th width="147.55560302734375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td>🔎</td><td>Despliega barra lateral de detalles avanzados sobre ese depósito.</td></tr><tr><td><strong><code>Ticket Id</code></strong></td><td>Identificador único de la apuesta.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador único del usuario</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha exacta en la que se hizo la apuesta.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto de dinero que se aposto.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Total que se gano en la apuesta</td></tr><tr><td><strong><code>Impuesto premios</code></strong></td><td>Valor de impuesto que se le resta a los premios</td></tr><tr><td><strong><code>Impuesto apuesta</code></strong></td><td>Valor de impuesto que tuvo la apuesta.</td></tr><tr><td><strong><code>Premio total</code></strong></td><td>Total neto del premio asignado al usuario, después de aplicar la deducción del impuesto correspondiente.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#odds"><strong><code>Odds</code></strong></a></td><td>Indica el multiplicador que se aplicará al valor apostado para calcular la ganancia potencial. (<em><strong>Ejemplo:</strong> si el odds es <strong>2.00</strong>, el usuario duplicará el monto de su apuesta en caso de ganar</em>.)</td></tr><tr><td><strong><code>IP</code></strong></td><td>IP registrada en la creación de la apuesta.</td></tr><tr><td><strong><code>Billatera</code></strong></td><td>Nombre del tipo de <a href="https://virtualsoft.gitbook.io/untitled/glosario#billetera">billetera</a> que utilizo el usuario al realizar la apuesta.</td></tr></tbody></table>

***

### **6. Validaciones y Reglas de Negocio**

* El tipo de vista **Detallado** mostrará cada apuesta individual, mientras que **Totales** consolida los datos.
* El reporte se actualiza en tiempo real, mostrando la información más reciente de forma inmediata.

***

### **7. Control de Versiones**

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="111">Versión</th><th width="134">Fecha</th><th width="176">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>02/10/2025</td><td>David velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
