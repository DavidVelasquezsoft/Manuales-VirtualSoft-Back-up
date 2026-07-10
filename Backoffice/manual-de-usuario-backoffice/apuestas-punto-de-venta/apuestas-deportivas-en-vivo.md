---
description: >-
  Permite realizar apuestas en un punto de venta para un usuario en eventos
  deportivos en vivo.
---

# Apuestas deportivas en vivo

{% hint style="danger" %}
**Nota importante:**  Este modulo solo aplica para **Puntos de venta**.
{% endhint %}

### 1. Acceso al Módulo:

**Ruta de Acceso:** BackOffice > Apuestas deportivas en vivo

***

### 2. Prerrequisitos

Para realizar apuestas desde un punto de venta, primero se debe iniciar sesión con el número de documento (DNI) del usuario que realizará la apuesta.&#x20;

{% hint style="warning" %}
**Nota:** El usuario debe estar previamente registrado en la plataforma. Sin embargo, si el modo de **apuestas anónimas** está habilitado, no será necesario contar con un usuario creado. En este caso, los datos requeridos como documento o número de teléfono dependerán de la configuración establecida por el _partner_ o país en la sección [**Ajustes generales**](../herramientas/partner-ajustes/configuracion-1.md#general)**.**
{% endhint %}

Al ingresar los datos, se mostrará un **pop-up de confirmación** con la información del usuario para verificar su identidad; una vez confirmados los datos, se debe presionar el botón **“Continuar”** para proceder con la apuesta.

***

### **3. Acciones del Usuario**

<table><thead><tr><th width="176.05560302734375">Sección</th><th width="200.333251953125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Selección</code></strong></td><td>Clic en categoría</td><td>El usuario elige el deporte de interés: fútbol, tenis, baloncesto, etc.</td></tr><tr><td><strong><code>Elección de evento</code></strong></td><td>Clic en evento</td><td>Se despliegan los partidos o encuentros disponibles dentro del deporte elegido.</td></tr><tr><td><strong><code>Tipo de apuesta</code></strong></td><td>Clic en cuota</td><td>El usuario selecciona el mercado (ganador, goles, hándicap, etc.).</td></tr><tr><td><strong><code>Configuración del boleto</code></strong></td><td>Escribir monto</td><td>Se define cuánto desea apostar por selección o combinada.</td></tr><tr><td><strong><code>Confirmación de la apuesta</code></strong></td><td>Clic en botón “Apostar”</td><td>Confirma el boleto con las selecciones y el importe deseado.</td></tr></tbody></table>

#### **3.1. Otras configuraciones:**

<table><thead><tr><th width="155.1666259765625">Campo</th><th>Tipo de control</th><th>Descripción</th><th>Observaciones</th></tr></thead><tbody><tr><td><strong><code>Búsqueda de eventos</code></strong></td><td>Campo de texto</td><td>Permite buscar un equipo, torneo o país específico.</td><td>Filtra eventos según el término ingresado.</td></tr><tr><td><strong><code>Tipos de apuesta</code></strong></td><td>Listado dinámico</td><td>Incluye: resultado final, total de goles, doble oportunidad, hándicap, etc.</td><td>Varían según el evento o disciplina.</td></tr><tr><td><strong><code>Cuotas</code></strong></td><td>Botones interactivos</td><td>Valores que representan la ganancia esperada.</td><td>Se actualizan automáticamente si hay cambios antes de apostar.</td></tr><tr><td><strong><code>Boletos combinados</code></strong></td><td>Opciones seleccionables (<em>Checkbox</em>)</td><td>Permite hacer apuestas múltiples o sistemas.</td><td>Aumenta el riesgo y el potencial de ganancia.</td></tr><tr><td><strong><code>Monto de apuesta</code></strong></td><td>Campo numérico</td><td>Indica cuánto se arriesga por cada selección.</td><td>Afecta el cálculo automático de ganancia potencial.</td></tr><tr><td><strong><code>Botón “Apostar”</code></strong></td><td>Botón</td><td>Finaliza y confirma el boleto de apuesta.</td><td>La apuesta queda registrada y no puede modificarse.</td></tr></tbody></table>

***

### **4. Validaciones y Reglas de Negocio**

* Una vez confirmada una apuesta, no puede ser cancelada.
* Las cuotas están sujetas a cambios hasta el momento de confirmación.
* El sistema no permite apuestas duplicadas idénticas en eventos restringidos.
* Las ganancias se calculan automáticamente al cierre del evento según el mercado apostado.
* Algunas promociones aplican solo a apuestas simples o determinadas ligas/deportes.
* Las apuestas en vivo pueden tener un leve retraso y validación adicional del sistema.

{% hint style="warning" %}
**Nota:** Cuando existan torneos o sorteos activos, estos se mostrarán en los banners con la cantidad de usuarios participantes (_torneos_) o inscritos (_sorteos_). La información aparecerá en la parte inferior junto al cronómetro correspondiente y se actualizará automáticamente cada 120 segundos.
{% endhint %}

***

### **5. Control de Versiones**

<details>

<summary>🔽Historial de Versiones</summary>

<table><thead><tr><th width="112">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>04/11/2025</td><td>David Ortiz</td><td>Documento inicial</td></tr></tbody></table>

</details>
