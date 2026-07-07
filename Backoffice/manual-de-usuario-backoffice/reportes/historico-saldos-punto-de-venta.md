---
description: >-
  Permite analizar y consultar las operaciones de los saldos asociados a los
  puntos de venta.
---

# Histórico saldos punto de venta

***

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Reportes > Historico saldos punto de venta

***

### 2. 🖼️Visualización

<figure><img src="../../.gitbook/assets/image (70).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección Historial de saldo punto de venta</p></figcaption></figure>

***

### 3. 🧑‍💻 Acciones sobre la Consulta

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="historico-saldos-punto-de-venta.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados más precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="historico-saldos-punto-de-venta.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

#### 3.1. 🔎 Filtros&#x20;

<table><thead><tr><th width="119.55548095703125">Campo</th><th width="138.74078369140625">Tipo de Control</th><th width="312.77764892578125">Descripción</th><th>Validaciones</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador único del usuario.</td><td>Solo números</td></tr><tr><td><strong><code>Fecha de creacion</code></strong></td><td>Calendario</td><td>Define el período de tiempo para realizar la consulta.</td><td>Formato: YYYY-MM-DD - YYYY-MM-DD</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra por país.</td><td>Solo se puede seleccionar uno</td></tr><tr><td><strong><code>Punto de venta propio?</code></strong></td><td>Interruptor</td><td>Determina si aplica punto de venta propio o no.</td><td>Valor binario: Sí / No</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selector</td><td><p>Elige cómo se mostrará el reporte.</p><ul><li><strong>Totales</strong>: Información resumida.</li><li><strong>Detallado</strong>: Información más específica y extensa.</li></ul></td><td>Campo opcional</td></tr><tr><td><strong><code>Ordenar por</code></strong></td><td>Lista desplegable</td><td>Elige el criterio por el cual se priorizará la información en el reporte.</td><td><ul><li>Calc. Desfase</li><li>GGR. Deportivas</li><li>GGR. Casino</li><li>Fecha de Creación</li></ul></td></tr><tr><td><strong><code>Orden</code></strong></td><td>Lista desplegable</td><td>Indica si deseas ordenar en forma ascendente o descendente según el criterio elegido.</td><td>Segun la fecha.</td></tr></tbody></table>

#### 3.2. 🚀 Consultar

Al realizar la consulta, se mostrará una tabla con la siguiente información:

<table><thead><tr><th width="303.0369873046875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner asociado al movimiento.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>fecha en la que se creó el registro.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al usuario.</td></tr><tr><td><strong><code>Saldo Inicial</code></strong></td><td>Saldo al inicio del período.</td></tr><tr><td><strong><code>Cupo recargas inicial</code></strong></td><td>Valor inicial asignado para realizar recargas.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador de usuario.</td></tr><tr><td><strong><code>Nombre Usuario</code></strong></td><td>Nombre del usuario vinculado al movimiento.</td></tr><tr><td><strong><code>Cupo juego inicial</code></strong></td><td>Valor inicial asignado para operaciones de juego.</td></tr><tr><td><strong><code>Depósitos</code></strong></td><td>Muestra las recargas realizadas a usuarios online</td></tr><tr><td><strong><code>Apuestas Virtuales</code></strong></td><td>Corresponde al monto total de apuestas virtuales vendidas en el punto de venta.</td></tr><tr><td><strong><code>Premios Virtuales</code></strong></td><td>Refleja el monto total pagado en premios de apuestas virtuales en el punto de venta.</td></tr><tr><td><strong><code>Saldo Bruto Apuestas Virtuales</code></strong></td><td>Muestra el <strong>total apostado en juegos virtuales (GoldenRace)</strong> por el punto de venta.</td></tr><tr><td><strong><code>Saldo Bruto Premios Virtuales</code></strong></td><td>Refleja el total pagado en premios de juegos virtuales (GoldenRace) independientemente de si estas apuestas aún no se han pagado.</td></tr><tr><td><strong><code>Ap. Deportivas</code></strong></td><td>Registro de lo apostado en eventos deportivos.</td></tr><tr><td><strong><code>Pr. Deportivas</code></strong></td><td>Total ganado como premios en apuestas deportivas.</td></tr><tr><td><strong><code>Transf Apuesta E</code></strong></td><td>Total de transferencias de apuestas recibidas.</td></tr><tr><td><strong><code>Transf Apuesta S</code></strong></td><td>Total de transferencias de apuestas enviadas.</td></tr><tr><td><strong><code>Transf Recarga E</code></strong></td><td>Total de transferencias de recargas recibidas.</td></tr><tr><td><strong><code>Transf Recarga S</code></strong></td><td>Total de transferencias de recargas enviadas.</td></tr><tr><td><strong><code>Retiros Pagados</code></strong></td><td>Total de retiros pagados al agente.</td></tr><tr><td><strong><code>Recargas Eliminadas</code></strong></td><td>Cantidad de recargas eliminadas durante el período.</td></tr><tr><td><strong><code>Saldo Final</code></strong></td><td>Restante disponible al final del período consultado.</td></tr><tr><td><strong><code>Saldo Final Calc.</code></strong></td><td>Saldo final calculado con base en las transacciones registradas.</td></tr><tr><td><strong><code>Calc. Desfase</code></strong></td><td>Diferencia entre el saldo final registrado y el saldo calculado.</td></tr><tr><td><strong><code>Impuesto Deposito</code></strong></td><td>Valor descontado por concepto de impuesto al realizar un depósito.</td></tr><tr><td><strong><code>Impuesto Apuesta</code></strong></td><td>Valor descontado por impuesto sobre el monto apostado.</td></tr><tr><td><strong><code>Impuesto Apuesta Casino</code></strong></td><td>Muestra el valor descontado por impuesto sobre apuestas de casino.</td></tr><tr><td><strong><code>Cupo</code></strong></td><td>Cupo disponible al final del período consultado.</td></tr><tr><td><strong><code>Cupo Calc.</code></strong></td><td>Cupo calculado basado en las operaciones registradas.</td></tr><tr><td><strong><code>Total Depósitos a agentes</code></strong></td><td>Monto total depositado a un <a href="https://virtualsoft.gitbook.io/untitled/glosario/#agente">agente</a> o punto de venta.</td></tr><tr><td><strong><code>Total Depósitos Usuarios Online</code></strong></td><td>Monto total depositado por un punto de venta a un usuario en la plataforma Usuarios Online.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** El campo **`Calc. Desfase`** el sistema resalta el registro en color <mark style="color:red;">**rojo**</mark> para alertar sobre una posible inconsistencia en los saldos finales que debe ser revisada.
{% endhint %}

***

### 5. ✅ Validaciones&#x20;

* Solo los usuarios con permisos asignados podrán acceder al módulo y ejecutar consultas.
* El filtro **Fecha de creación** debe ingresarse en el formato válido `YYYY-MM-DD`.
* Cuando no exista información de apuestas o premios virtuales para una fecha o punto de venta, la consulta mostrará el valor **“0.00”**

***

### 6. 🕒 Control de Versiones

<table><thead><tr><th width="107.81478881835938">Versión</th><th width="127">Fecha</th><th width="153">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>07-07-2025</td><td>David Velásquez</td><td>Documento inicial</td></tr><tr><td>1.1</td><td>03-09-2025</td><td>Karol Navia</td><td>Agregar nuevas columnas </td></tr><tr><td>1.2</td><td>01-12-2025</td><td>Ronald Peláez</td><td>Nuevas columnas Depósitos por agente y usuarios online.</td></tr><tr><td>1.3</td><td>19-01-2026</td><td>David velasquez</td><td>Refinamiento del manual y de algunas columnas.</td></tr><tr><td>1.4</td><td>26-01-2026</td><td>Ronald Pelaez</td><td>Ajuste en el campo <strong><code>Depósitos</code></strong> y <strong><code>Total Depósitos a agentes</code></strong></td></tr></tbody></table>
