---
description: >-
  Permite visualizar todos los movimientos realizados por un usuario dentro de
  la plataforma.
---

# Historial de movimientos

### 1. Acceso al módulo

**Ruta de acceso**: Backoffice > Jugadores > Reportes > Historial de movimientos

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (637).png" alt=""><figcaption><p>Figura#1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="historial-de-movimientos.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados más precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="historial-de-movimientos.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="115.11102294921875">Campo</th><th width="119.66668701171875">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>fecha creacion</code></strong></td><td>Calendario</td><td>Permite filtrar los movimientos según la fecha en que fueron registrados en el sistema.</td></tr><tr><td><strong><code>ID externo</code></strong></td><td>Numérico</td><td>Permite buscar un movimiento específico utilizando su identificador externo único.</td></tr><tr><td><strong><code>Movimiento</code></strong></td><td>Lista desplegable</td><td> Filtra según el tipo de flujo de saldo:<br><a href="historial-de-movimientos.md#tipos-de-movimientos-filtros" class="button secondary">Ver tipos de movimientos</a></td></tr><tr><td><strong><code>tipo</code></strong></td><td>Lista desplegable</td><td>Filtra según el tipo de evento que generó el movimiento de los puntos.<br><a href="historial-de-movimientos.md#tipos-de-eventos" class="button secondary">Ver tipos de eventos</a></td></tr></tbody></table>

<details>

<summary>🔽 Tipos de movimientos (<em>Filtros</em>)</summary>

<table><thead><tr><th width="125">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Todos</strong></td><td>Filtra y muestra todos los tipos de movimientos registrados en la cuenta del usuario.</td></tr><tr><td><strong>Entrada</strong></td><td>Muestra los movimientos en los que se ingresó saldo a la cuenta del usuario.</td></tr><tr><td><strong>Salida</strong></td><td>Muestra los movimientos en los que se descontó saldo de la cuenta del usuario.</td></tr><tr><td><strong>Cancelación</strong></td><td>Muestra los movimientos que fueron anulados y no generaron efecto en el saldo final del usuario.</td></tr></tbody></table>

<p align="center"><a href="historial-de-movimientos.md#id-3.1.-filtros" class="button secondary">Volver a filtros</a></p>

</details>

<details>

<summary>🔽 Tipos de eventos</summary>

<table><thead><tr><th width="136">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Todos</strong></td><td>Filtra y muestra todos los tipos de eventos registrados en la cuenta del usuario.</td></tr><tr><td><strong>Recargas</strong></td><td>Muestra los depósitos realizados por el usuario a través de tarjetas, transferencias u otros medios de pago habilitados.</td></tr><tr><td><strong>Ajuste de Saldo</strong></td><td>Muestra los cambios manuales aplicados al saldo del usuario por el sistema o el equipo de soporte, utilizados para corregir o ajustar montos.</td></tr><tr><td><strong>Apuestas Deportivas</strong></td><td>Registra los movimientos generados por la participación del usuario en apuestas sobre eventos deportivos.</td></tr><tr><td><strong>Apuestas Casino</strong></td><td>Incluye los movimientos generados por apuestas en juegos de casino, como tragamonedas, ruleta, blackjack, entre otros.</td></tr><tr><td><strong>Nota de Retiro Creada</strong></td><td>Filtra los movimientos correspondientes a retiros solicitados por el usuario que se encuentran pendientes de aprobación o en proceso de validación.</td></tr><tr><td><strong>Nota de Retiro Pagada</strong></td><td>Refleja que una solicitud de retiro fue aprobada y los fondos fueron entregados al usuario.</td></tr><tr><td><strong>Bono Redimido</strong></td><td>Muestra los movimientos generados cuando el usuario aplica o utiliza un bono promocional.</td></tr><tr><td><strong>Aumento de Cupo</strong></td><td>Refleja un incremento en el límite de crédito o en el saldo disponible del usuario.</td></tr><tr><td><strong>Gamificación</strong></td><td>Filtra las transacciones asociadas a <a href="https://virtualsoft.gitbook.io/untitled/glosario/#polla-deportiva">Penkas</a>, incluyendo ingresos por compra de participaciones y egresos por premios pagados.</td></tr></tbody></table>

<p align="center"><a href="historial-de-movimientos.md#id-3.1.-filtros" class="button secondary">Volver a filtros</a></p>

</details>

### 5. Resultado de Consulta

Aplica los filtros seleccionados y muestra los registros detallados del historial de movimientos del usuario.

{% hint style="info" %}
**Sobre el consumo de saldo:** el usuario siempre consume primero su **saldo recarga**; una vez agotado o cuando este no alcanza a cubrir el movimiento, se comienza a consumir el **saldo retiro**. Esto explica cómo se reflejan ambos saldos tras cada movimiento.
{% endhint %}

<table><thead><tr><th width="140.66668701171875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Identificador interno del movimiento en el sistema.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario asociado al movimiento.</td></tr><tr><td><strong><code>Movimiento</code></strong></td><td>Indica si el movimiento corresponde a una <strong>entrada</strong> o una <strong>salida</strong> de saldo.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Categoría que clasifica el tipo de movimiento. Las opciones disponibles son:<br><a href="historial-de-movimientos.md#tipos-de-movimientos" class="button secondary">Ver tipos de movimientos</a></td></tr><tr><td><strong><code>ID Externo</code></strong></td><td>Identificador externo único asociado al movimiento.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha y hora en que el movimiento fue registrado.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Valor económico asociado al movimiento realizado.</td></tr><tr><td><strong><code>Saldo Recargas</code></strong></td><td>Saldo disponible del usuario correspondiente a recargas y depósitos realizados sobre la cuenta del usuario.</td></tr><tr><td><strong><code>Saldo Retiros</code></strong></td><td>Saldo disponible del usuario para efectuar retiros.</td></tr></tbody></table>

<details>

<summary>🔽 Tipos de movimientos</summary>

<table><thead><tr><th width="181">Opción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Recargas</code></strong></td><td>Registra los depósitos realizados por el usuario a través de tarjetas, transferencias u otros medios de pago habilitados.</td></tr><tr><td><strong><code>Ajuste de Saldo</code></strong></td><td>Muestra los cambios manuales aplicados al saldo del usuario por el sistema o el equipo de soporte para corregir o ajustar montos.</td></tr><tr><td><strong><code>Apuestas Deportivas</code></strong></td><td>Registra los movimientos generados por la participación del usuario en apuestas sobre eventos deportivos.</td></tr><tr><td><strong><code>Apuestas Casino</code></strong></td><td>Incluye los movimientos generados por apuestas en juegos de casino, como tragamonedas, ruleta, blackjack, entre otros.</td></tr><tr><td><strong><code>Nota de Retiro Creada</code></strong></td><td>Indica que el usuario ha solicitado un retiro y que este se encuentra pendiente de aprobación o en proceso de validación.</td></tr><tr><td><strong><code>Nota de Retiro Pagada</code></strong></td><td>Confirma que una solicitud de retiro fue aprobada y que los fondos fueron entregados al usuario.</td></tr><tr><td><strong><code>Bono Redimido</code></strong></td><td>Movimiento generado cuando el usuario aplica o utiliza un bono promocional, como bonos de bienvenida o recarga.</td></tr><tr><td><strong><code>Aumento de Cupo</code></strong></td><td>Refleja un incremento en el límite de crédito o en el saldo disponible del usuario.</td></tr><tr><td><strong><code>Reducción de apuesta</code></strong></td><td><p>Devolución parcial o total del dinero apostado; el sistema reintegra el monto al mismo tipo de saldo utilizado. <strong>¿Cómo funciona?</strong></p><ul><li>Si la apuesta se hizo solo con saldo de recargas, la devolución se hará a recargas.</li><li>Si se usó únicamente saldo de retiros, la devolución irá a retiros.</li><li>Si se usaron ambos tipos de saldo, el monto se devuelve en proporción al aporte de cada uno.</li></ul><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Un usuario apostó $100:</p><ul><li>$80 eran de recargas <strong>/</strong> $20 eran de retiros</li></ul><p>Si la apuesta se reduce en $20, el sistema devuelve:</p><ul><li>$16 a recargas <strong>/</strong> $4 a retiros</li></ul></div></td></tr><tr><td><strong><code>Gamificación</code></strong></td><td>Transacciones relacionadas con <a href="https://virtualsoft.gitbook.io/untitled/glosario/#polla-deportiva"><strong>Penkas</strong></a>, incluyendo ingresos por compra de participaciones y egresos por premios pagados.</td></tr></tbody></table>

<p align="center"><a href="historial-de-movimientos.md#id-3.2.-consultar" class="button secondary">Volver a resultados</a></p>

</details>

***

### 6. Reglas y validaciones.

* Este reporte trae información del [reporte de productos no deportivas](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/reporte-productos-no-deportivos-por-usuario) por las apuestas realizadas del usuario.
* Cada movimiento realizado por el usuario se registra en el reporte de forma individual y consecutiva. Es decir, si un usuario realiza 5 apuestas en un juego, en el reporte deberán visualizarse las 5 transacciones por separado.
* En caso de visualizar reportes agrupados por ganancias se recomienda validar el proveedor con el cual se realizó la apuesta.
* En este reporte se pueden visualizar saldos positivos los cuales podrán ser generados por diferentes eventos.
* En caso de cancelación de una [polla deportiva](https://virtualsoft.gitbook.io/untitled/glosario#polla-deportiva), los movimientos del jugador se reflejan como una salida (_pago de la inscripción_) y una entrada (_devolución del valor apostado_).

### 7. Control de versiones

<details>

<summary>🔽 Historial de movimiento</summary>

<table><thead><tr><th width="102.22216796875" align="right">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td align="right">1.0</td><td>2025-09-18</td><td>David velasquez</td><td>Actualización de formato</td></tr><tr><td align="right">1.1</td><td>2026-01-02</td><td>David velasquez</td><td>Incorporación de nuevo tipo de movimiento</td></tr><tr><td align="right">1.2</td><td>2026-01-29</td><td>Ronald Peláez</td><td>Incorporación de reglas y validaciones.</td></tr><tr><td align="right">1.3</td><td>2026-04-01</td><td>David velasquez</td><td>Incorporación de validación por cancelación de penka</td></tr></tbody></table>

</details>
