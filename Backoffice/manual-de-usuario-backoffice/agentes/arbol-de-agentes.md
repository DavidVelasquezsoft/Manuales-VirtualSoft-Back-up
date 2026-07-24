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

# Árbol de Agentes

<mark style="color:$info;">Consultar y visualizar la estructura jerárquica de los agentes registrados en la plataforma. A través de este reporte es posible identificar la relación entre agentes, concesionarios y subconcesionarios, así como consultar información general sobre su operación, saldo y nivel dentro de la estructura organizacional.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso:** Agentes > Árbol de Agentes

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (235).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección árbol de agentes.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="121">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="arbol-de-agentes.md#id-4.-filtros"><strong>Filtros</strong></a></td><td>Establece los criterios para consultar la información de los agentes registrados en la plataforma.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros de búsqueda a su estado inicial.</td></tr><tr><td><a href="arbol-de-agentes.md#id-5.-resultados-de-consulta"><strong>Consultar</strong></a></td><td>Ejecuta la búsqueda utilizando los filtros seleccionados y presenta los registros encontrados.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="165">Campo</th><th width="126">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Permite consultar un agente mediante su identificador único dentro del sistema.</td></tr><tr><td><strong><code>Usuario (Correo Electrónico)</code></strong></td><td>Campo de texto</td><td>Localizar un agente utilizando el correo electrónico registrado en la plataforma.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Busca un agente por su nombre registrado.</td></tr><tr><td><strong><code>Punto de Venta</code></strong></td><td>Lista desplegable</td><td>Filtra los agentes asociados a un punto de venta específico.</td></tr><tr><td><strong><code>ID Concesionario</code></strong></td><td>Campo numérico</td><td>Consulta un concesionario por su identificador.</td></tr><tr><td><strong><code>Subconcesionario</code></strong></td><td>Campo de texto</td><td>Filtra la información según el subconcesionario asociado al agente.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Consultar los agentes registrados en un país específico.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al hacer clic en **Consultar**, el sistema mostrará los agentes que cumplan con los criterios de búsqueda seleccionados.

{% hint style="warning" %}
**Nota:** La información presentada corresponde a la estructura organizacional vigente al momento de realizar la consulta y dependerá de los filtros seleccionados.
{% endhint %}

<table><thead><tr><th width="167">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Partner o aliado comercial al que pertenece el agente dentro de la estructura de la plataforma.</td></tr><tr><td><strong><code>País</code></strong></td><td>País donde se encuentra registrado el agente.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único asignado al agente dentro del sistema.</td></tr><tr><td><strong><code>UserName</code></strong></td><td>Nombre de usuario utilizado por el agente para acceder a la plataforma.</td></tr><tr><td><strong><code>Transf.</code></strong></td><td></td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda en la que opera el agente dentro de la plataforma.</td></tr><tr><td><strong><code>Saldo</code></strong></td><td>Valor disponible en la cuenta del agente para realizar las operaciones permitidas por el sistema.</td></tr><tr><td><strong><code>Consolidado Nivel</code></strong></td><td>Nivel jerárquico que ocupa el agente dentro de la estructura organizacional de la red comercial.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio

* Para realizar una consulta es necesario ingresar al menos un criterio de búsqueda o seleccionar los filtros correspondientes, según los permisos configurados para el usuario.
* Los filtros pueden utilizarse de manera individual o combinada para obtener resultados más específicos.
* Si no existen registros que cumplan con los criterios de búsqueda, la tabla de resultados permanecerá vacía.
* La información visualizada dependerá de los permisos asignados al usuario autenticado.
* El campo **Saldo** corresponde al saldo disponible del agente al momento de ejecutar la consulta.
* El campo **Consolidado Nivel** refleja la posición jerárquica actual del agente dentro de la estructura de la red.
* La información de **Partner**, **Concesionario** y **Subconcesionario** corresponde a la estructura organizacional configurada en la plataforma.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="117">Versión</th><th width="132">Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>24/07/2026</td><td></td><td></td></tr></tbody></table>

</details>
