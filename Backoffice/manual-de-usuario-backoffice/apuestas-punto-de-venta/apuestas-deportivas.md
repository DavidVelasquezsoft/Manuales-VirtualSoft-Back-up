---
description: >-
  Permite realizar apuestas en un punto de venta para un usuario en eventos
  deportivos.
---

# Apuestas deportivas

{% hint style="danger" %}
**Nota importante:**  Este modulo solo aplica para **Puntos de venta**.
{% endhint %}

### Configuración general

### 1. Acceso al Módulo:

**Ruta de Acceso:** BackOffice > Apuestas deportivas

***

### 2. Prerrequisitos

Para realizar apuestas desde un punto de venta, primero se debe iniciar sesión con el número de documento (DNI) del usuario que realizará la apuesta.&#x20;

{% hint style="warning" %}
**Nota:** El usuario debe estar previamente registrado en la plataforma. Sin embargo, si el modo de **apuestas anónimas** está habilitado, no será necesario contar con un usuario creado. En este caso, se podrá requerir el documento o número de teléfono dependiendo de la configuración establecida por el _partner_ o país en la sección [**Ajustes generales**](/broken/pages/y9CSJzuItyKui5k9v8xg)**.**
{% endhint %}

Al ingresar los datos, se mostrará un **pop-up de confirmación** con la información del usuario para verificar su identidad; una vez confirmados los datos, se debe presionar el botón **“Continuar”** para proceder con la apuesta.

***

### **3. Acciones del Usuario**

<table><thead><tr><th width="228.55560302734375">Sección</th><th width="200.333251953125">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Selección</code></strong></td><td>Clic en categoría</td><td>El usuario elige el deporte de interés: fútbol, tenis, baloncesto, etc.</td></tr><tr><td><strong><code>Elección de evento</code></strong></td><td>Clic en evento</td><td>Se despliegan los partidos o encuentros disponibles dentro del deporte elegido.</td></tr><tr><td><strong><code>Tipo de apuesta</code></strong></td><td>Clic en cuota</td><td>El usuario selecciona el mercado (ganador, goles, hándicap, etc.).</td></tr><tr><td><strong><code>Configuración del boleto</code></strong></td><td>Escribir monto</td><td>Se define cuánto desea apostar por selección o combinada.</td></tr><tr><td><strong><code>Confirmación de la apuesta</code></strong></td><td>Clic en botón “Apostar”</td><td>Confirma el boleto con las selecciones y el importe deseado.</td></tr></tbody></table>

#### **3.1. Otras configuraciones:**

| Campo                     | Tipo de control                    | Descripción                                                                 | Observaciones                                                  |
| ------------------------- | ---------------------------------- | --------------------------------------------------------------------------- | -------------------------------------------------------------- |
| **`Búsqueda de eventos`** | Campo de texto                     | Permite buscar un equipo, torneo o país específico.                         | Filtra eventos según el término ingresado.                     |
| **`Tipos de apuesta`**    | Listado dinámico                   | Incluye: resultado final, total de goles, doble oportunidad, hándicap, etc. | Varían según el evento o disciplina.                           |
| **`Cuotas`**              | Botones interactivos               | Valores que representan la ganancia esperada.                               | Se actualizan automáticamente si hay cambios antes de apostar. |
| **`Boletos combinados`**  | Opciones seleccionables (Checkbox) | Permite hacer apuestas múltiples o sistemas.                                | Aumenta el riesgo y el potencial de ganancia.                  |
| **`Monto de apuesta`**    | Campo numérico                     | Indica cuánto se arriesga por cada selección.                               | Afecta el cálculo automático de ganancia potencial.            |
| **`Botón “Apostar”`**     | Botón                              | Finaliza y confirma el boleto de apuesta.                                   | La apuesta queda registrada y no puede modificarse.            |

***

### **4. Validaciones y Reglas de Negocio**

* Una vez confirmada una apuesta, no puede ser cancelada.
* Las cuotas están sujetas a cambios hasta el momento de confirmación.
* El sistema no permite apuestas duplicadas idénticas en eventos restringidos.
* Las ganancias se calculan automáticamente al cierre del evento según el mercado apostado.
* Algunas promociones aplican solo a apuestas simples o determinadas ligas/deportes.

{% hint style="warning" %}
**Nota:** Cuando existan torneos o sorteos activos, estos se mostrarán en los banners con la cantidad de usuarios participantes (torneos) o inscritos (sorteos). La información aparecerá en la parte inferior junto al cronómetro correspondiente y se actualizará automáticamente cada 120 segundos.
{% endhint %}

***

### **5. Control de Versiones**

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="129">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>04/11/2025</td><td>David Ortiz</td><td>Documento inicial</td></tr></tbody></table>

</details>
