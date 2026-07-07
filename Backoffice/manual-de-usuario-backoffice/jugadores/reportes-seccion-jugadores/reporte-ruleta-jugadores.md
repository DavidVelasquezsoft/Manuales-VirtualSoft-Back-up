---
description: >-
  Permite consultar los giros realizados en ruletas Por un usuario, mostrando
  información detallada sobre su estado, premios otorgados y demás datos
  relacionados.
---

# Reporte Ruleta- Jugadores

{% hint style="warning" %}
**Nota:** Este reporte solo muestra la información de giros correspondientes al **usuario previamente seleccionado en el módulo de Jugadores**.\
Si desea consultar todos los usuarios debe utilizar el reporte general de ruletas.
{% endhint %}

### **1. Acceso al Módulo**

**Ruta de acceso:** BackOffice > jugadores > Perfil del Jugador > reportes > Reporte Ruleta&#x20;

***

### **2. Visualización**

<figure><img src="../../../.gitbook/assets/image (58).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección reporte ruleta.</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="119.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtro</strong></td><td>Permite filtrar la información para obtener resultados más precisos</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="reporte-ruleta-jugadores.md#id-3.1.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

***

### 4. Filtros **¿Cómo buscar los registros de ruleta del usuario?**

Se puede consultar información aplicando los siguientes filtros:

{% hint style="warning" %}
⚠️ **Nota:**

* Si no existen datos que cumplan los criterios del filtro, el sistema no mostrará resultados en la tabla.
* Para consultar todos los registros del usuario, es necesario presionar el botón **Limpiar** y ejecutar la búsqueda nuevamente.
* El uso de filtros es opcional; no es obligatorio aplicar criterios de búsqueda.
{% endhint %}

<table><thead><tr><th width="153">Campo</th><th width="183">Tipo de Filtro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de Activación</code></strong></td><td>Fecha (desde/hasta)</td><td>Selecciona el período en el que se activó el giro al usuario.</td></tr><tr><td><strong><code>Fecha de Redención</code></strong></td><td>Fecha (desde/hasta)</td><td>Selecciona el período en el que el giro fue redimido.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Fecha (desde/hasta)</td><td>Selecciona la fecha final de la ruleta.</td></tr><tr><td><strong><code>ID Ruleta</code></strong></td><td>Numérico</td><td>Filtra por identificador interno de la ruleta.</td></tr><tr><td><strong><code>Nombre Ruleta</code></strong></td><td>Texto</td><td>Búsqueda por el nombre configurado de la ruleta.</td></tr><tr><td><strong><code>Estado del Giro</code></strong></td><td>Lista desplegable</td><td>Filtra por estado: Pendiente, Pendiente Rollback, Activa, Redimido o Expirado.</td></tr><tr><td><strong><code>Tipo de Premio</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de premio: Freebet, Freespin, Bono, Dinero, Premio físico, Giro Extra.</td></tr></tbody></table>

### 5. Resultados de Consulta <a href="#id-4.2.-limpiar" id="id-4.2.-limpiar"></a>

&#x20;Al realizar la búsqueda se muestran los siguientes datos en la tabla de resultados:

<table><thead><tr><th width="222">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del jugador.</td></tr><tr><td><strong><code>Nombre Usuario</code></strong></td><td>Nombre o alias del jugador.</td></tr><tr><td><strong><code>ID Ruleta</code></strong></td><td>Identificador interno de la ruleta.</td></tr><tr><td><strong><code>Nombre Ruleta</code></strong></td><td>Nombre visible de la ruleta promocional.</td></tr><tr><td><strong><code>Fecha Activación</code></strong></td><td>Fecha y hora en que se asignó el giro al jugador.</td></tr><tr><td><strong><code>Fecha Redención</code></strong></td><td>Fecha y hora en que el jugador usó su giro (si aplica).</td></tr><tr><td><strong><code>Estado del Giro</code></strong></td><td>Estado actual: Pendiente, Pendiente Rollback, Activa, Redimido o Expirado.</td></tr><tr><td><strong><code>Premio Entregado</code></strong></td><td>Nombre del premio que se le otorgó.</td></tr><tr><td><strong><code>Tipo de Premio</code></strong></td><td>Tipo de beneficio otorgado (saldo freeBet, saldo premio, premio físico, etc).</td></tr><tr><td><strong><code>Detalle Premio</code></strong></td><td>ID del bono, monto, saldo entregado o descripción del premio físico.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Nombre del operador asignado al jugador.</td></tr><tr><td><strong><code>País</code></strong></td><td>País de residencia registrado.</td></tr></tbody></table>

***

### 6. Validaciones y Reglas de Negocio

* El reporte está limitado al **usuario seleccionado en el módulo de Jugadores**.
* Solo los usuarios con permisos habilitados podrán acceder al módulo.
* Los filtros permiten limitar la búsqueda de giros según fechas, ruleta, estado y tipo de premio.

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="115">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>02/09/2025</td><td>Karol Navia</td><td>Documento inicial</td></tr></tbody></table>

</details>
