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

# Reporte de Depósitos

Reporte de depósitos realizados por el punto de venta.

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Gestión punto de venta > 🔍 Ingresar a punto de venta > Reportes > Reporte de Depósitos.

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (698).png" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte de Depósitos.</p></figcaption></figure>

***

### 3.  Acciones de usuario

<table><thead><tr><th width="170.4444580078125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Permite buscar el historial de los depósitos realizados por el punto de venta con la ayuda de filtros.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros por defecto.</td></tr><tr><td><strong>Consultar</strong></td><td>Aplica los filtros configurados y obtén los resultados.</td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="135.25">Campo</th><th width="117.25">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Rango de fechas en la cual se realizaron los depósitos.</td></tr><tr><td><strong><code>Transacción ID</code></strong></td><td>Numérico</td><td>Identificador único del depósito realizado.</td></tr></tbody></table>

### 5. Resultado de Consulta

El reporte de depósitos se visualizará en una tabla que contiene las siguientes columnas:

<table><thead><tr><th width="140.25">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del depósito realizado.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td></td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td></td></tr><tr><td><strong><code>Nombre del sistema de pasarela de pago</code></strong></td><td></td></tr><tr><td><strong><code>Tipo</code></strong></td><td></td></tr><tr><td><strong><code>Moneda</code></strong></td><td></td></tr><tr><td><strong><code>Valor</code></strong></td><td></td></tr><tr><td><strong><code>Modificado</code></strong></td><td></td></tr><tr><td><strong><code>Estado</code></strong></td><td></td></tr><tr><td><strong><code>External ID</code></strong></td><td></td></tr></tbody></table>

#### **5.2. Tabla de detalles**

<table><thead><tr><th width="139">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ticket Det ID</code></strong></td><td>Identificador único del detalle de la apuesta, que permite distinguir cada selección individual dentro de un ticket de apuesta.</td></tr><tr><td><strong><code>Ticket ID</code></strong></td><td>Identificador único generado por el sistema para el ticket de apuesta.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Describe el evento o la apuesta deportiva realizada por el usuario.</td></tr><tr><td><strong><code>Market</code></strong></td><td>Mercado de la apuesta seleccionada (por ejemplo: 1X2, Over, Under).</td></tr><tr><td><strong><code>Option</code></strong></td><td>Opción específica elegida dentro del mercado seleccionado.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#odds"><strong><code>Odds</code></strong></a></td><td>Multiplicador aplicado al valor apostado para calcular la ganancia potencial; a mayor odds, mayor será el premio en caso de ganar.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador único del usuario que realizó la apuesta.</td></tr></tbody></table>

***

### 6. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="119.14813232421875">Versión</th><th width="130.77777099609375">Fecha</th><th width="164.5555419921875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2026-01-09</td><td>David Velasquez</td><td>Actualización de formato.</td></tr></tbody></table>

</details>
