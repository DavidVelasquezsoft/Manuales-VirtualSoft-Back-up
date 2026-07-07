---
description: >-
  Permite consultar en tiempo real que proveedores y subproveedores están
  activos en la operación (Partner y país) consultada
---

# Proveedores activos

{% hint style="warning" %}
**Nota:** Este reporte está disponible únicamente para operadores con permisos habilitados.
{% endhint %}

### 1. Acceso al módulo

**Ruta de acceso**: Backoffice > productos > Proveedores Activos&#x20;

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (630).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección proveedores activos</p></figcaption></figure>

***

### 3.  Acciones disponibles

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="proveedores-activos.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados mas precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="proveedores-activos.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los proveedores y subproveedores válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="135">Filtro</th><th width="119.6666259765625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Texto</td><td>Busca por el proveedor principal para buscar su estado y el de sus subproveedores.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Texto</td><td>Permite buscar por un subproveedor en especifico.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar un partner para visualizar el estado de todos los proveedores y subproveedores en dicho partner.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra la información según el país seleccionado.</td></tr></tbody></table>

### 5. Tabla de Resultados

Permite visualizar todos los proveedores y sub-proveedores validos segun los filtros aplicados.

<table><thead><tr><th width="146">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Proveedor</code></strong></td><td>Muestra el nombre del proveedor principal.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Muestra el subproveedor vinculado al proveedor principal dentro de la plataforma.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Indica el partner al que pertenece el proveedor o subproveedor.</td></tr><tr><td><strong><code>País</code></strong></td><td>Muestra el país operativo en el que el proveedor y/o subproveedor se encuentra configurado.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Indica el <strong>estado actual</strong> del proveedor y subproveedor dentro de la plataforma, representado visualmente por colores: <mark style="color:green;">Activo en verde</mark> e <mark style="color:$danger;">Inactivo en rojo.</mark></td></tr></tbody></table>

***

### 6.  Validaciones y reglas de negocio

* La información se actualiza en tiempo real, reflejando de forma inmediata los cambios en los estados.
* La información mostrada estará limitada según la configuración del perfil en el BackOffice. Solo podrá acceder y visualizar las operaciones (_Partners y países_) que tenga habilitadas en su perfil.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="102">Versión</th><th width="123">Fecha</th><th width="164">Autor</th><th>Descripción del cambio</th></tr></thead><tbody><tr><td>1.0</td><td>2026-01-19</td><td>David velasquez</td><td>Creación de la documentación.</td></tr></tbody></table>

</details>
