---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# Relación Usuario Aggregato

<mark style="color:$info;">Permite consultar la relación entre el ID de usuario utilizado en la plataforma y el</mark> [<mark style="color:$info;">ID Aggregator</mark> ](https://virtualsoft.gitbook.io/plantillas/glosario#id-aggregator)<mark style="color:$info;">asociado internamente, facilitando la trazabilidad e identificación de usuarios en procesos y transacciones internas.</mark>

***

### 1. Acceso al Módulo

**Ruta de acceso:** BackOffice > Menú principal > Reportes > usuario - Agregator

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (672).png" alt=""><figcaption><p>Figura #1: Vista general del Reporte Comisiones Global.</p></figcaption></figure>

***

### 3. Acciones en el módulo

<table><thead><tr><th width="163">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Consultar relación de usuarios.</code></strong></td><td>Aplica filtros para consultar la relación entre el ID del usuario en la plataforma del partner y el <a href="https://virtualsoft.gitbook.io/plantillas/glosario#id-aggregator">ID Aggregator</a> asociado internamente.</td></tr><tr><td><strong><code>Añadir relación</code></strong></td><td>Actualmente, el botón <strong>“<code>Añadir relación</code>”</strong> se encuentra visible en la plataforma; sin embargo, su funcionalidad no está habilitada, por lo que no ejecuta ninguna acción dentro del sistema.</td></tr></tbody></table>

***

### **4. Filtros de búsqueda**

Los filtros se utilizan para buscar información de forma más precisa según lo que se necesite, ayudando a encontrar más rápido los registros específicos.

<table><thead><tr><th width="120">Filtro</th><th width="161">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td>Usuario Partner</td><td>Numérico</td><td>ID del usuario visible desde la plataforma Usuarios Online.</td></tr><tr><td>Usuario Aggregato</td><td>Numérico</td><td>ID aggregator asociado al usuario en el sistema.</td></tr><tr><td>Fecha de creación</td><td>Calendario</td><td>Fecha en la que fueron registrados los usuarios en el sistema.</td></tr></tbody></table>

***

### **5. Tabla Relación Usuario Aggregato**

<table><thead><tr><th width="142">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td>Acción</td><td>En esta columna estará el ícono 🖋️, el cual despliega el pop up para editar una relación, pero actualmente esta lógica no tiene funcionamiento activo.</td></tr><tr><td>Usuario Partner</td><td>Id único del usuario que utiliza para diferenciarse en la plataforma.</td></tr><tr><td>User Agreggator</td><td>Id único del usuario que se utiliza para transacciones internas.</td></tr><tr><td>Fecha creación</td><td>Fecha en la que se creó el usuario.</td></tr></tbody></table>

***

### 6. Control de Versiones

<details>

<summary>🕛 Historial de versiones </summary>

<table><thead><tr><th width="106">Versión</th><th width="129">Fecha</th><th width="149">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>21-05-2026</td><td>Ronald Peláez</td><td>Documentación inicial.</td></tr></tbody></table>



</details>
