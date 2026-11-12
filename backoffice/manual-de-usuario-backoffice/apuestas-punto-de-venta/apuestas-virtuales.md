---
description: >-
  Permite realizar apuestas en un punto de venta para un usuario en eventos
  deportivos simulados como fútbol, carreras de caballos, galgos, entre otros.
---

# Apuestas virtuales

{% hint style="danger" %}
**Nota importante:**  Este modulo solo aplica para **Puntos de venta**.
{% endhint %}

### 1. Acceso al Módulo:

**Ruta de Acceso:** BackOffice > Apuestas Virtuales

***

### 2. Prerrequisitos

Para realizar apuestas desde un punto de venta, primero se debe iniciar sesión con el número de documento (DNI) del usuario que realizará la apuesta.&#x20;

{% hint style="warning" %}
**Nota:** El usuario debe estar previamente registrado en la plataforma. Sin embargo, si el modo de **apuestas anónimas** está habilitado, no será necesario contar con un usuario creado. En este caso, los datos requeridos como documento o número de teléfono dependerán de la configuración establecida por el _partner_ o país en la sección [**Ajustes generales**](/broken/pages/y9CSJzuItyKui5k9v8xg)**.**
{% endhint %}

Al ingresar los datos, se mostrará un **pop-up de confirmación** con la información del usuario para verificar su identidad; una vez confirmados los datos, se debe presionar el botón **“Continuar”** para proceder con la apuesta.

***

### **3. Acciones del Usuario**

<table><thead><tr><th width="202.257568359375">Sección</th><th width="158.6666259765625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Deportes Virtuales</code></strong></td><td>Visualizar</td><td>Permite acceder a la lista completa de juegos simulados.</td></tr><tr><td><strong><code>Filtros de deportes</code></strong></td><td>Seleccionar</td><td>Permite elegir entre distintas categorías como fútbol, caballos, Etc.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Filtrar</td><td>Permite seleccionar el proveedor de juegos, por ejemplo “<em>GoldenRace</em>”.</td></tr><tr><td><strong><code>Botón “Cargar más”</code></strong></td><td>Clic</td><td>Visualiza más juegos disponibles en la sección de virtuales.</td></tr></tbody></table>

#### **3.1. Otras configuraciones:**

<table><thead><tr><th width="158.09088134765625">Campo</th><th width="146">Tipo de control</th><th>Descripción</th><th>Observaciones</th></tr></thead><tbody><tr><td><strong><code>Categorías</code></strong></td><td>Botones</td><td>Permite navegar entre distintos tipos de deportes virtuales.</td><td>El contenido puede variar según el proveedor y configuración del partner.</td></tr><tr><td><strong><code>Eventos simulados</code></strong></td><td>Animaciones</td><td>Muestra una animación corta del evento con resultados generados automáticamente.</td><td>Duración aproximada por evento: 2–3 minutos.</td></tr></tbody></table>

***

### **4. Validaciones y Reglas de Negocio**

* Los eventos y resultados se generan de forma aleatoria mediante sistemas.
* Los juegos disponibles pueden variar según país o configuración del operador.
* No se requiere espera de eventos reales; las partidas inician cada pocos minutos.

***

### **5. Control de Versiones**

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="123">Versión</th><th width="148">Fecha</th><th width="169">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>04/11/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
