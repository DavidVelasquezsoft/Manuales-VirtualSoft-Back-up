---
description: >-
  Permite inhabilitar temporalmente una o varias funcionalidades dentro de
  Usuarios Online para el partner seleccionado.
---

# Contingencias Totales

<mark style="color:$info;">El módulo Contingencias Totales permite bloquear de forma temporal una vertical o funcionalidad completa de la plataforma de usuarios online (deportivas, casino, retiros, depósitos, entre otras) para todos los usuarios del partner. Se utiliza ante incidentes, mantenimientos o riesgos operativos, cuando es necesario detener una operación de inmediato sin modificar la configuración de cada usuario.</mark>

***

## 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice (BO) > Seguridad > Contingencias Totales

***

## 2. Visualización

<figure><img src="../../.gitbook/assets/image (199).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección contingencias totales.</p></figcaption></figure>

***

## 3. Acciones de usuario

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="contingencias-totales.md#id-4.-contingencias-disponibles"><strong>Contingencias disponibles</strong></a></td><td>Reúne los tipos de <a href="https://virtualsoft.gitbook.io/untitled/glosario#contingencia">contingencia</a> que pueden aplicarse y la funcionalidad que bloquea cada uno.</td></tr><tr><td><a href="contingencias-totales.md#id-5.-activar-o-inactivar-una-contingencia"><strong>Activar / Inactivar contingencia</strong></a></td><td>Aplica o retira la restricción de una funcionalidad para todos los usuarios de la plataforma de usuarios online mediante el interruptor de cada contingencia.</td></tr></tbody></table>

***

## 4. Contingencias disponibles

Cada interruptor corresponde a un tipo de contingencia. Al activarlo, la funcionalidad asociada queda restringida para todos los usuarios de la plataforma de usuarios online.

<table><thead><tr><th width="190">Contingencia</th><th width="130">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Contingencia Total</code></strong></td><td>Interruptor</td><td>Inhabilita todas las funcionalidades disponibles para los usuarios online e impide cualquier tipo de interacción con la plataforma. Se reserva para incidentes que afectan la operación completa.</td></tr><tr><td><strong><code>Contingencia Deportivas</code></strong></td><td>Interruptor</td><td>Restringe el acceso a la sección de apuestas deportivas, de modo que los usuarios no pueden realizar nuevas apuestas en esta vertical.</td></tr><tr><td><strong><code>Contingencia Retiro</code></strong></td><td>Interruptor</td><td>Bloquea la funcionalidad de retiros: los usuarios no pueden solicitar ni procesar retiros de fondos mientras esté activa.</td></tr><tr><td><strong><code>Contingencia Depósito</code></strong></td><td>Interruptor</td><td>Desactiva la opción de realizar depósitos, por lo que los usuarios no pueden recargar saldo en sus cuentas.</td></tr><tr><td><strong><code>Contingencia Casino</code></strong></td><td>Interruptor</td><td>Inhabilita el acceso general a los juegos de casino y bloquea la participación de los usuarios en esta vertical.</td></tr><tr><td><strong><code>Contingencia Casino en Vivo</code></strong></td><td>Interruptor</td><td>Restringe únicamente el acceso a los juegos de casino en vivo, sin afectar los demás juegos de casino que estén habilitados.</td></tr><tr><td><strong><code>Contingencia Virtuales</code></strong></td><td>Interruptor</td><td>Bloquea el acceso a los juegos virtuales e impide la interacción con este tipo de contenido.</td></tr><tr><td><strong><code>Contingencia Poker</code></strong></td><td>Interruptor</td><td>Impide el acceso a la sección de póker y deshabilita las mesas y partidas para los usuarios.</td></tr></tbody></table>

***

## 5. Activar o inactivar una contingencia

1. El usuario identifica la contingencia que necesita modificar.
2. Cambia el estado del interruptor correspondiente:
   * **Activo** <em>(verde)</em>: aplica la contingencia y restringe la funcionalidad.
   * **Inactivo** <em>(rojo)</em>: retira la contingencia y la funcionalidad vuelve a estar disponible.
3. El cambio se aplica de forma inmediata para el partner seleccionado, sin necesidad de guardar ni confirmar.

***

## 6. Validaciones y reglas del negocio:

* Las contingencias aplican a **todos los usuarios** de la plataforma de usuarios online del partner, no a un usuario en particular.
* El cambio de estado se aplica en el momento en que se mueve el interruptor; el módulo no solicita confirmación.

{% hint style="danger" %}
**Importante:** Una contingencia activa permanece hasta que alguien la inactiva manualmente. Si no se retira al finalizar el incidente, los usuarios siguen sin acceso a la funcionalidad bloqueada.
{% endhint %}

***

## 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>07/01/2026</td><td>David Velasquez</td><td>Creación inicial del documento.</td></tr><tr><td>1.1</td><td>09/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
