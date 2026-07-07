---
description: >-
  Permite consultar toda la información relacionada con los giros realizados en
  ruletas promocionales.
---

# Reporte de ruleta

### Configuración General

{% hint style="warning" %}
⚠️ **Nota:** Solo los usuarios con permisos asignados podrán acceder al módulo y generar consultas, si no cuenta con este permiso comuníquese con el equipo de soporte.
{% endhint %}

### **1.  Acceso al Módulo**

**Ruta de acceso:** BackOffice > Reportes > Reporte Ruleta

***

### **2. Visualización**

<figure><img src="../../.gitbook/assets/image (567).png" alt=""><figcaption><p>Figura#1: Captura de pantalla reporte de ruleta</p></figcaption></figure>

***

### 🧑‍💻 3. Acciones del Usuario <a href="#id-3.-acciones-del-usuario" id="id-3.-acciones-del-usuario"></a>

#### 3.1.🔍 ¿Cómo buscar los registros de ruleta?

Se puede consultar información aplicando los siguientes filtros:

{% hint style="warning" %}
⚠️ **Nota:**

* &#x20;Si no existen datos que cumplan los criterios del filtro, el sistema no mostrará resultados en la tabla.
* Para consultar todos los registros disponibles, es necesario presionar el botón **Limpiar** y ejecutar la búsqueda nuevamente.
* El uso de filtros es opcional; no es obligatorio aplicar criterios de búsqueda.
{% endhint %}

<table><thead><tr><th width="152">Campo</th><th width="183">Tipo de Filtro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de Activación</code></strong></td><td>Fecha (desde/hasta)</td><td>Selecciona el período en el que se activó el giro al usuario.</td></tr><tr><td><strong><code>Fecha de Redención</code></strong></td><td>Fecha (desde/hasta)</td><td>Selecciona el período en el que el giro fue redimido.</td></tr><tr><td><strong><code>Fecha de Expiración</code></strong></td><td>Fecha (desde/hasta)</td><td>Selecciona la fecha final de la ruleta.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Texto</td><td>Busca por identificador único del jugador.</td></tr><tr><td><strong><code>Estado del Giro</code></strong></td><td>Lista desplegable</td><td><p>Filtra por el estado: </p><ul><li><strong>Pendiente:</strong> Giro aún no disponible, falta cumplir condición.</li><li><strong>Pendiente Rollback:</strong> Giro realizado pero sujeto a validación.</li><li><strong>Activa:</strong> Giro habilitado y disponible para el jugador.</li><li><strong>Redimido:</strong> Giro utilizado, con premio entregado o no.</li><li><strong>Expirado:</strong> Giro no utilizado y ya vencido.</li></ul></td></tr><tr><td><strong><code>ID Ruleta</code></strong></td><td>Numérico</td><td>Filtra por identificador interno de la ruleta.</td></tr><tr><td><strong><code>Nombre Ruleta</code></strong></td><td>Texto</td><td>Búsqueda por el nombre configurado de la ruleta.</td></tr><tr><td><strong><code>Tipo de Premio</code></strong></td><td>Lista desplegable</td><td>Selecciona el tipo de premio como: Freebet, Freespin, Bono, Dinero, Premio físico, Giro Extra.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Busca por el nombre del operador (ej. Doradobet, Betplay, etc.).</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Selecciona el país asignado al usuario.</td></tr></tbody></table>

***

#### 3.2. 🔄 Limpiar <a href="#id-4.2.-limpiar" id="id-4.2.-limpiar"></a>

Restablece los filtros por defecto.

#### 3.3. 🚀 Consultar

&#x20;Al realizar la búsqueda se muestran los siguientes datos en la tabla de resultados:

<table><thead><tr><th width="222">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del jugador.</td></tr><tr><td><strong><code>Nombre Usuario</code></strong></td><td>Nombre o alias del jugador.</td></tr><tr><td><strong><code>ID Ruleta</code></strong></td><td>Identificador interno de la ruleta.</td></tr><tr><td><strong><code>Nombre Ruleta</code></strong></td><td>Nombre visible de la ruleta promocional.</td></tr><tr><td><strong><code>Fecha Activación</code></strong></td><td>Fecha y hora en que se asignó el giro al jugador.</td></tr><tr><td><strong><code>Fecha Redención</code></strong></td><td>Fecha y hora en que el jugador usó su giro (si aplica).</td></tr><tr><td><strong><code>Estado del Giro</code></strong></td><td>Estado actual: Pendiente, Pendiente Rollback, Activa, Redimido o Expirado.</td></tr><tr><td><strong><code>Premio Entregado</code></strong></td><td>Nombre del premio que se le dio al usuario.</td></tr><tr><td><strong><code>Tipo de Premio</code></strong></td><td>Tipo de beneficio otorgado, (saldo freeBet, saldo premio, premio físico, etc)</td></tr><tr><td><strong><code>Detalle Premio</code></strong></td><td>ID del bono, monto, saldo entregado o descripción del premio físico.</td></tr><tr><td><strong><code>Fecha Expiración</code></strong></td><td>Fecha y hora en que expira la ruleta.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Nombre del operador asignada al jugador.</td></tr><tr><td><strong><code>País</code></strong></td><td>País de residencia registrado por el usuario.</td></tr></tbody></table>

***

### 4. ¿Cómo exportar los resultados?

Para exportar los resultados de la búsqueda, acceda al **selector de exportación** ubicado en la parte inferior derecha, debajo de la tabla de resultados, y elija uno de los formatos disponibles.

<table><thead><tr><th width="188">Sección</th><th width="121">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Exportar XLSX</code></strong></td><td>Selector</td><td>Descarga el reporte en formato <strong>Excel</strong>.</td></tr><tr><td><strong><code>Exportar PDF</code></strong></td><td>Selector</td><td>Descarga el reporte en formato <strong>PDF</strong>.</td></tr></tbody></table>

***

### 5. Validaciones y Reglas de Negocio

* Solo los usuarios con permisos habilitados podrán acceder al módulo.
* Los filtros permiten limitar la búsqueda de giros según fechas, usuario, ruleta, estado, premio, partner y país.

***

### 6. Control de Versiones

| Versión | Fecha      | Autor       | Cambios Realizados |
| ------- | ---------- | ----------- | ------------------ |
| 1.0     | 25/08/2025 | Karol Navia | Documento inicial  |
