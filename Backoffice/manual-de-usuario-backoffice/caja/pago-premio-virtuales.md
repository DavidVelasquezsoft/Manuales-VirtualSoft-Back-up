---
description: >-
  Al ingresar a esta sección, encontraras la siguiente visual, con unos filtros
  que serán explicados a continuación.
---

# Pago premio virtuales

### 1. Acceso al Módulo

Ruta de Acceso: Backoffice > Caja > Pago Premio virtuales

### 2. 🖼️ Visualización

<figure><img src="../../.gitbook/assets/image (391).png" alt=""><figcaption><p>Figura#1:Captura de pantalla Filtros.</p></figcaption></figure>

### 3. 🧑‍💻 Acciones disponibles

<table><thead><tr><th width="169.5555419921875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="pago-premio-virtuales.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten identificar el ticket de apuesta mediante sus datos de referencia.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros ingresados a su estado inicial.</td></tr><tr><td><a href="pago-premio-virtuales.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Valida la información del ticket y muestra su estado y detalles.</td></tr><tr><td><a href="pago-premio-virtuales.md#id-3.3.-pagar-premio"><strong>Pagar Premio</strong></a></td><td>Permite realizar el pago del premio cuando el ticket es ganador y no ha sido pagado.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

#### 3.1. 🔎 Filtros

<table><thead><tr><th width="179.66668701171875">Campo</th><th width="136.3333740234375">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>No.</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ticket"><strong><code>Ticket</code></strong></a></td><td>Texto / Numérico</td><td>Permite ingresar el número de ticket, el cual se encuentra en el recibo de la apuesta realizada.</td></tr><tr><td><strong><code>Clave</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ticket"><strong><code>Ticket</code></strong></a></td><td>Texto</td><td>Permite ingresar la clave del ticket, indicada en el recibo de la apuesta.</td></tr></tbody></table>

#### 3.2. 🚀 Consultar

Al realizar la consulta, el sistema muestra el **estado del** [**ticket**](https://virtualsoft.gitbook.io/untitled/glosario/#ticket) y la información asociada a la apuesta.

**Estados posibles del ticket**

* **Ticket Perdedor**: Indica que la apuesta realizada fue perdida.
* **Ticket Ganador**: Indica que la apuesta fue ganada y puede proceder al pago del premio (_En caso de que no se halla pagado_).
* **Ticket Pendiente**: Indica que la apuesta aún no ha finalizado.

<table><thead><tr><th width="189.111083984375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor a pagar</code></strong></td><td>Monto que el punto de venta debe entregar al usuario si la apuesta es ganadora.</td></tr><tr><td><strong><code>Valor apostado</code></strong></td><td>Monto de dinero invertido por el usuario en la apuesta.</td></tr><tr><td><strong><code>Impuesto</code></strong></td><td>Valor aplicado por concepto de impuestos relacionados con la apuesta.</td></tr><tr><td><strong><code>Premio proyectado</code></strong></td><td>Monto estimado que el usuario podría ganar en caso de resultar ganador.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual de la apuesta: ganada, perdida o pendiente.</td></tr><tr><td><strong><code>Ganador</code></strong></td><td>Indica si la apuesta resultó ganadora o no.</td></tr></tbody></table>

**Detalle del ticket**

<table><thead><tr><th width="149.111083984375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ticket ID</code></strong></td><td>Identificador único generado para el ticket.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor con el cual se realizó la apuesta.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego en el que se efectuó la apuesta.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador del usuario que realizó la apuesta.</td></tr></tbody></table>

#### 3.3. 💰 Pagar Premio

Esta acción se habilita únicamente cuando el ticket se encuentra en estado **Ganador** y **no ha sido pagado**.

Al seleccionar **`Pagar Premio`**, el sistema solicitará el formato de entrega de la factura:

* **POS**: Genera la factura en un formato compacto, ideal para impresoras de tickets.
* **Carta**: Genera la factura en formato PDF tamaño carta, con mayor nivel de detalle.

Una vez seleccionada la opción deseada, el sistema finaliza el proceso de pago del premio.

### 4. 🕓 Control de Versiones

<table><thead><tr><th width="141.88885498046875">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>23/01/2026</td><td>David Velásquez</td><td>Actualización de formato.</td></tr></tbody></table>
