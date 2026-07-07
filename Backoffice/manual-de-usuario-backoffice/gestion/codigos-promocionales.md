---
description: >-
  Permite consultar y generar códigos promocionales destinados a nuevos usuarios
  durante su registro en la plataforma, ya sean códigos de bono o de referidos.
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
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

# Códigos Promocionales

### 1. Acceso al Módulo

**Ruta de Acceso**: Backoffice > Gestión > Códigos promocionales

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (22).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección de códigos promocionales</p></figcaption></figure>

***

### &#x33;**. Acciones disponibles**

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="codigos-promocionales.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información para obtener resultados más precisos.</td></tr><tr><td><a href="codigos-promocionales.md#id-3.2.-anadir-codigo"><strong>Añadir código</strong></a></td><td>Permite añadir un nuevo código promocional para un registro de un usuario nuevo en la plataforma.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="codigos-promocionales.md#id-3.1.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

### 4. Filtros

<table><thead><tr><th width="119.99993896484375">Campos</th><th width="120.66668701171875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID</code></strong></td><td>Numérico</td><td>Permite filtrar por el identificador único asignado a cada código promocional.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Filtra por el número de identificación del usuario asociado al código promocional.</td></tr><tr><td><strong><code>Código</code></strong></td><td>General</td><td>Indica el código promocional en específico.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Calendario</td><td>Permite filtrar por el rango de fecha en la que fue generado el código promocional.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#punto-de-venta"><strong><code>Punto de Venta</code></strong></a></td><td>Lista desplegable</td><td>Permite filtrar por el punto de venta en específico.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Permite filtrar por el estado del código promocional (<em>Activo/Inactivo</em>).</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#partner"><strong><code>Partner</code></strong></a></td><td>Lista desplegable</td><td>Permite filtrar por el partner en específico.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra por el país donde el código promocional es válido o puede ser utilizado.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Indica el nombre asignado al código promocional para su identificación.</td></tr></tbody></table>

### 5. Resultados de Consulta

Muestra los resultados correspondientes según los filtros aplicados.

<table><thead><tr><th width="173.33331298828125">Campos</th><th>Descripción</th></tr></thead><tbody><tr><td>✖️</td><td>Abre pop-up que permite eliminar el código promocional y quedará en estado inactivo.</td></tr><tr><td><strong><code>ID</code></strong></td><td>Identificador único asignado al código promocional en la plataforma.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Valor específico del código promocional registrado.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre descriptivo asociado al código promocional.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha en la que el código fue registrado en el sistema.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Muestra si el código se encuentra activo o inactivo.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Usuario que generó o utilizó el código.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner en el que se creo el código promocional.</td></tr><tr><td><strong><code>País</code></strong></td><td>País donde el código aplica o está asociado.</td></tr><tr><td><strong><code>Función</code></strong></td><td>Uso o finalidad que cumple el código dentro del sistema.</td></tr></tbody></table>

***

### 6. Añadir código

Permite agregar un nuevo código promocional desde el botón “**Añadir código**”, el cual abrirá un pop-up con los campos necesarios para su creación.

<table><thead><tr><th width="165">Campos</th><th width="131.00006103515625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Código</code></strong></td><td>Texto</td><td>Indica el código único con el cual se otorgará la promoción al ingresarlo en el <a href="https://app.gitbook.com/s/yyrHDz69FZMnpZ9NBm8u/usuarios-online/manual-de-plataforma/registro">formulario de registro</a>.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Especifica el nombre descriptivo que identifica el código dentro del sistema.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Numérico </td><td>Define la identificación del usuario asociado al código.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Selecciona el <a href="https://virtualsoft.gitbook.io/untitled/glosario#partner">partner</a> en el cual estará activo al código promocional.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Indica el país en el que el código estará disponible .</td></tr><tr><td><strong><code>Función</code></strong></td><td>Lista desplegable</td><td>Especifica el propósito o uso que tendrá el código dentro de la plataforma.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Define si el código se encuentra activo o inactivo.</td></tr></tbody></table>

***

### 7. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="105.88885498046875">Versión</th><th width="131">Fecha</th><th width="180">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>16/12/2025</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
