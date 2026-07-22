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

<figure><img src="../../../../.gitbook/assets/image (698).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Pago premio.</p></figcaption></figure>

***

### 3.  Acciones de usuario

<table><thead><tr><th width="170.4444580078125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-de-depositos.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permite buscar por un ticket en específico.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros por defecto.</td></tr><tr><td><a href="reporte-de-depositos.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Busca el ticket en el sistema y muestra toda la información acerca de ese ticket y el pago del premio.</td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="135.25">Campo</th><th width="117.25">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#ticket"><strong><code>Ticket</code></strong></a></td><td>Numérico</td><td>Ingresa el <strong>ID de la apuesta</strong>, el cual se encuentra en el recibo generado al realizar una apuesta desde la sección <strong>Apuestas Deportivas</strong>.</td></tr><tr><td><strong><code>Clave</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario/#ticket"><strong><code>Ticket</code></strong></a></td><td>Numérico</td><td>Ingresa el valor <strong>IB</strong> asociado a la apuesta, disponible en el recibo de la apuesta realizada en la sección <strong>Apuestas Deportivas</strong>.</td></tr></tbody></table>

### 5. Resultado de Consulta

Permite consultar un ticket para verificar la información del pago y su estado. Si el ticket se encuentra en estado ganador y no ha sido pagado, habilita el pago del premio y la entrega de la factura. Adicionalmente, muestra una tabla con el detalle completo del ticket consultado.

#### **5.1. Información del pago y su estado**

<table><thead><tr><th width="140.25">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Valor a pagar</code></strong></td><td>Indica el monto que el punto de venta debe entregar al usuario cuando la apuesta resulta ganadora.</td></tr><tr><td><strong><code>Valor apostado</code></strong></td><td>Representa la cantidad de dinero que el usuario invirtió al realizar la apuesta.</td></tr><tr><td><strong><code>Impuesto</code></strong></td><td>Muestra el valor aplicado al usuario correspondiente a impuestos asociados a la apuesta.</td></tr><tr><td><strong><code>Premio proyectado</code></strong></td><td>Indica el monto estimado que el usuario podría ganar si la apuesta resulta exitosa.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Refleja el estado actual de la apuesta con los siguientes estados:</td></tr><tr><td><strong><code>Ganador</code></strong></td><td>Indica si la apuesta fue ganadora o no, según el resultado final del evento.</td></tr><tr><td><strong><code>Pagar premio</code></strong></td><td><p>Permite procesar el pago del ticket ganador y despliega las opciones disponibles para generar y entregar la factura al usuario. Selecciona la opción correspondiente para completar el proceso.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Esta opción solo se muestra cuando el ticket tiene estado ganador y el premio aún no ha sido pagado.</p></div></td></tr></tbody></table>

#### **5.2. Tabla de detalles**

<table><thead><tr><th width="139">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Ticket Det ID</code></strong></td><td>Identificador único del detalle de la apuesta, que permite distinguir cada selección individual dentro de un ticket de apuesta.</td></tr><tr><td><strong><code>Ticket ID</code></strong></td><td>Identificador único generado por el sistema para el ticket de apuesta.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Describe el evento o la apuesta deportiva realizada por el usuario.</td></tr><tr><td><strong><code>Market</code></strong></td><td>Mercado de la apuesta seleccionada (por ejemplo: 1X2, Over, Under).</td></tr><tr><td><strong><code>Option</code></strong></td><td>Opción específica elegida dentro del mercado seleccionado.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#odds"><strong><code>Odds</code></strong></a></td><td>Multiplicador aplicado al valor apostado para calcular la ganancia potencial; a mayor odds, mayor será el premio en caso de ganar.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Identificador único del usuario que realizó la apuesta.</td></tr></tbody></table>

***

### 6. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="119.14813232421875">Versión</th><th width="130.77777099609375">Fecha</th><th width="164.5555419921875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>2026-01-09</td><td>David Velasquez</td><td>Actualización de formato.</td></tr></tbody></table>

</details>
