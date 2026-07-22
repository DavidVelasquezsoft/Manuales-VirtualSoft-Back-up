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

# Reporte de Retiros

Reporte de los retiros realizados por medio del punto de venta.

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Gestión punto de venta > 🔍 Ingresar a punto de venta > Reportes > Reporte de Retiros.

***

### 2. Visualización

<figure><img src="../../../../.gitbook/assets/image (1).png" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte de Retiros.</p></figcaption></figure>

***

### 3.  Acciones de usuario

<table><thead><tr><th width="170.4444580078125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Permite buscar el historial de los retiros realizados por el punto de venta con la ayuda de filtros.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros por defecto.</td></tr><tr><td><strong>Consultar</strong></td><td>Aplica los filtros configurados y obtén los resultados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite exportar los resultados obtenidos según los filtros aplicados en formatos Excel (.XLS) y PDF mediante el botón <strong>Exportar</strong>, ubicado en la parte inferior derecha de la pantalla.</td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="135.25">Campo</th><th width="117.25">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Rango de fechas en la cual se realizaron los depósitos.</td></tr><tr><td><strong><code>Transacción ID</code></strong></td><td>Numérico</td><td>Identificador único del depósito realizado.</td></tr></tbody></table>

### 5. Resultado de Consulta

El reporte de depósitos se visualizará en una tabla que contiene las siguientes columnas:

<table><thead><tr><th width="140.25">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador único del depósito realizado.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador único del usuario que realizó el depósito.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha en la que se generó el depósito.</td></tr><tr><td><strong><code>Nombre del sistema de pasarela de pago</code></strong></td><td>Nombre de la pasarela de pago por la cual se efectuó el depósito.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Tipo de depósito realizado.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda en la cual se realizó el depósito.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto total por el cual se realizó el depósito.</td></tr><tr><td><strong><code>Modificado</code></strong></td><td>Usuario que aprobó el depósito realizado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado en el que se encuentra el depósito.</td></tr><tr><td><strong><code>External ID</code></strong></td><td>Identificador único del depósito utilizado de manera externa.</td></tr></tbody></table>

***

### 6. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="119.14813232421875">Versión</th><th width="130.77777099609375">Fecha</th><th width="164.5555419921875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2026-07-22</td><td>Ronald Peláez</td><td>Documento inicial</td></tr></tbody></table>

</details>
