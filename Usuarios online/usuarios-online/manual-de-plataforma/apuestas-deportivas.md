---
description: >-
  Desde este módulo se pueden realizar todas las apuestas deportivas para la
  plataforma de usuarios online.
---

# Apuestas Deportivas

### Configuración general

{% hint style="warning" %}
**Nota**: Este módulo se puede manejar con 2 proveedores según el partner configurado, dichos proveedores se configuran desde el BackOffice, [más información](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion/proveedores-internos#id-3.1-configuraciones-disponibles).
{% endhint %}

### 1. Acceso al Módulo:

**Ruta de Acceso:** Menú principal > Sección **“Deportivas”**

***

### 2. Visualización.

<figure><img src="../../.gitbook/assets/image (189).png" alt=""><figcaption><p>Figura #1 Captura de pantalla ejemplo apuestas deportivas.</p></figcaption></figure>

### **3. 🧑‍💻 Acciones del Usuario**

<table><thead><tr><th width="177">Sección</th><th width="168">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Selección</code></strong></td><td>Clic en categoría</td><td>El usuario elige el deporte de interés <em>(fútbol, tenis, baloncesto, etc.)</em></td></tr><tr><td><strong><code>Elección de evento</code></strong></td><td>Clic en evento</td><td>Se despliegan los partidos o encuentros disponibles dentro del deporte elegido.</td></tr><tr><td><strong><code>Tipo de apuesta</code></strong></td><td>Clic en cuota</td><td>El usuario selecciona el mercado <em>(ganador, goles, hándicap, etc.).</em></td></tr><tr><td><strong><code>Configuración del boleto</code></strong></td><td>Escribir monto</td><td>Se define cuánto desea apostar por selección <em>(una sola apuesta)</em> o combinada <em>(Múltiples apuestas en una).</em></td></tr><tr><td><strong><code>Confirmación de la apuesta</code></strong></td><td>Clic en botón “<em>Apostar</em>”</td><td>Confirma la apuesta a realizar según las configuraciones previas.</td></tr></tbody></table>

#### **3.1. Accesos directos desde el sportsbook:**

Estas serán las acciones que se pueden realizar con cada apuesta en la sección de deportivas

<table><thead><tr><th>Campo</th><th width="162">Tipo de control</th><th width="176">Descripción</th><th>Observaciones</th></tr></thead><tbody><tr><td><strong><code>Búsqueda de eventos</code></strong></td><td>Campo de texto</td><td>Permite buscar un equipo, torneo o país específico.</td><td>Filtra eventos según las necesidades ingresadas.</td></tr><tr><td><strong><code>Tipos de apuesta</code></strong></td><td>Listado dinámico</td><td>Incluye: resultado final, total de goles, doble oportunidad, hándicap, etc.</td><td>Varían según el evento o disciplina.</td></tr><tr><td><strong><code>Cuotas</code></strong></td><td>Botones interactivos</td><td>Valores que representan la ganancia esperada.</td><td>Se actualizan automáticamente si hay cambios antes de apostar.</td></tr><tr><td><strong><code>Boletos combinados</code></strong></td><td>Opciones seleccionables</td><td>Permite hacer apuestas múltiples o sistemas.</td><td>Aumenta el riesgo y el potencial de ganancia.</td></tr><tr><td><strong><code>Monto de apuesta</code></strong></td><td>Campo numérico</td><td>Indica cuánto se arriesga por cada selección.</td><td>Afecta el cálculo automático de ganancia potencial.</td></tr><tr><td><strong><code>Botón “Apostar”</code></strong></td><td>Botón</td><td>Finaliza y confirma el boleto de apuesta.</td><td>La apuesta queda registrada y no puede modificarse.</td></tr></tbody></table>

***

### **4. ✅ Validaciones y Reglas de Negocio**

* Solo se puede apostar con saldo disponible en la cuenta _(tanto el saldo retiro como el saldo depósito)._
* Cuando se cambia de proveedor para este módulo, las apuestas guardadas y la información que se tenía, quedará guardada hasta volver a activar ese mismo proveedor.
* Una vez confirmada una apuesta, no puede ser cancelada.
* Las cuotas están sujetas a cambios hasta el momento de confirmación.
* El sistema no permite apuestas duplicadas idénticas en eventos restringidos.
* Las ganancias se calculan automáticamente al cierre del evento según el mercado apostado.
* Algunas promociones aplican solo a apuestas simples o determinadas ligas/deportes.
* Las apuestas en vivo pueden tener un leve retraso y validación adicional del sistema.

{% hint style="warning" %}
**Nota:** Cuando existan torneos o sorteos activos, estos se mostrarán en los [banners](https://virtualsoft.gitbook.io/untitled/glosario/#banners) con la cantidad de usuarios participantes _(torneos)_ o inscritos _(sorteos)._ La información aparecerá en la parte inferior junto al cronómetro correspondiente y se actualizará automáticamente cada 120 segundos.
{% endhint %}

***

### **5. 🕒 Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados              |
| ------- | ---------- | ------------- | ------------------------------- |
| 1.0     | 30/10/2025 | Ronald Peláez | formato inicial                 |
| 1.1     | 04/11/2025 | Karol Navia   | Ajuste por cambio de proveedor. |
