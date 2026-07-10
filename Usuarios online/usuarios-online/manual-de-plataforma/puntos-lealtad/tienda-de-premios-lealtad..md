---
description: >-
  Permite a los usuarios visualizar y explorar los premios disponibles según su
  categoría, mostrando la información esencial de cada premio.
---

# Tienda de premios lealtad.

### 1. Acceso al Módulo

**Ruta de acceso**: Plataforma Usuarios Online > Puntos lealtad > Tienda de premios lealtad

***

### 2. visualización:

<figure><img src="../../../.gitbook/assets/image (190).png" alt="" width="563"><figcaption><p>Figura#1: Captura de pantalla de ejemplo tienda de premios</p></figcaption></figure>

### 3. Acciones del Usuario

Seleccionar categoria en la que se desean canjear los puntos.

<table><thead><tr><th width="206">Categoría</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Casino</code></strong></td><td>Muestra premios relacionados con juegos de casino.</td></tr><tr><td><strong><code>Casino en vivo</code></strong></td><td>Muestra premios aplicables a juegos de casino en vivo.</td></tr><tr><td><strong><code>Apuestas deportivas</code></strong></td><td>Muestra premios asociados a apuestas deportivas.</td></tr><tr><td><strong><code>Premios físicos</code></strong></td><td>Muestra premios tangibles que requieren entrega física al usuario.</td></tr></tbody></table>

#### **3.1 Secciones del módulo**

El módulo permite visualizar los premios disponibles según la categoría seleccionada.

<table><thead><tr><th width="192">Sección</th><th width="120">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Premios disponibles</code></strong></td><td>Visualizar</td><td>Permite consultar los premios activos, organizados por categoría.</td></tr></tbody></table>

#### **3.2 Exploración de premios**

Al seleccionar una categoría de premios, se muestra una vista compuesta por varias tarjetas, donde cada una representa un premio disponible.\
La información presentada en cada tarjeta se detalla en la siguiente tabla:

<table><thead><tr><th width="230">Elemento</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del premio</code></strong></td><td>Título o nombre asignado al premio.</td></tr><tr><td><strong><code>Puntos requeridos</code></strong></td><td>Cantidad de puntos lealtad necesarios para redimirlo.</td></tr><tr><td><strong><code>Imagen del premio</code></strong></td><td>Imagen ilustrativa o promocional asociada.</td></tr><tr><td><strong><code>Estado del premio</code></strong></td><td>Indica si el premio está disponible para redimir <em>(desbloqueado)</em> o no <em>(bloqueado)</em>.</td></tr></tbody></table>

***

### 4. Flujo de Canje de Premios

Este flujo describe los pasos que sigue el jugador al canjear un premio y los mensajes que verá según la vertical del premio.

{% stepper %}
{% step %}
#### Acceso a premios disponibles

Ingresa a la sección **Tienda de premios lealtad** y visualiza los premios disponibles según la categoría seleccionada.
{% endstep %}

{% step %}
#### Selección de premio

Se hace clic en **Canjear** sobre un premio que se encuentre en estado **Desbloqueado**.
{% endstep %}

{% step %}
#### Confirmación del canje

El sistema muestra un pop-up con el mensaje:

> **“Estás a punto de canjear un premio. ¿Deseas continuar?”**
{% endstep %}

{% step %}
#### Procesamiento del canje

Se hace clic en **Continuar**.\
El sistema procesa el canje y valida la **vertical del premio** _(Deportes, Casino o Casino en vivo)._
{% endstep %}

{% step %}
#### Mensaje final según la vertical

El sistema muestra un pop-up final cuyo contenido varía según la vertical del premio canjeado

**Vertical Deportes**

> ¡Canje exitoso! 🎉 Tu premio ya está disponible.\
> Dirígete a la sección apuestas deportivas y realiza tu pronóstico favorito.

**Vertical Casino / Casino en vivo**

> ¡Canje exitoso! 🎉 Tu premio ya está disponible.\
> Dirígete al juego seleccionado y encontrarás tus giros cargados.

Al hacer clic en Continuar, el mensaje se cierra y se completa el flujo de canje
{% endstep %}
{% endstepper %}

### 5. Validaciones y Reglas de Negocio

* Las categorías de premios se configuran desde la herramienta [Sitebuilder](https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/promocionales/premios).
* Los premios que aparecerán se configuran desde la herramienta [Torneos y Bonos](https://virtualsoft.gitbook.io/manuales/torneos-y-bonos/torneos-y-bonos./como-acceder-a-la-plataforma-./crear-eventos./crear-regalo).

***

### 6. Control de Versiones

<table><thead><tr><th width="103">Versión</th><th width="114">Fecha</th><th width="134">Autor</th><th>Descripción del cambio</th></tr></thead><tbody><tr><td>1.0</td><td>28/11/2025</td><td>Ronald Peláez</td><td>Creación del documento</td></tr><tr><td>1.1</td><td>19/01/2026</td><td>Karol Navia</td><td>Se mejoró la estructura general del documento y se agregó la documentación del flujo de canje de premios</td></tr></tbody></table>
