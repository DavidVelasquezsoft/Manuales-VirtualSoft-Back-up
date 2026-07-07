---
description: >-
  Permite consultar y gestionar los resultados de validaciones realizadas por
  los proveedores Compliance y Cumplo360.
---

# Reporte de listas de observados

{% hint style="warning" %}
**Nota:** Este reporte solo puede visualizarse con permisos específicos.\
Si no cuentas con acceso, comunícate con el equipo de **Soporte**.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de acceso:**  BackOffice > Menú principal > Seguridad > Reporte de listas de observados.

***

### 2. Acciones de usuario

<table><thead><tr><th width="153">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtrar</strong></td><td>Utiliza los filtros para adquirir información detallada sobre el reporte.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/seguridad/reporte-de-listas-de-observados#id-4.-tipos-de-reporte"><strong>Cambió de vista</strong></a></td><td>Alterna entre la vista detallada y la resumida según el análisis requerido.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros a su valor base.</td></tr><tr><td><strong>Consultar</strong></td><td>Ejecuta la búsqueda del reporte con los filtros aplicados.</td></tr><tr><td><strong>Exportar</strong></td><td>Permite descargar la información <em>(filtrada o completa)</em> en formato Excel o PDF. Para ello, ubica el botón <strong>Exportar</strong> en la parte inferior derecha de la página y selecciona el formato deseado para iniciar la descarga.</td></tr></tbody></table>

***

### 3. ¿Que es una validación de [compliance](https://virtualsoft.gitbook.io/untitled/glosario#compliance) y [Cumplo360](https://virtualsoft.gitbook.io/plantillas/glosario#cumplo360)?

Es un control que se realiza para asegurar que un usuario cumple con las políticas internas, leyes, regulaciones y estándares éticos establecidos por la ley, validando que no se encuentre en listas negras o especiales, cuando un usuario se registra en la plataforma Usuarios Online, los proveedores Compilance y Cumplo360 validan que el usuario esté en listas de observados y generará el reporte indicando si hay coincidencia en las listas de observados o no.

{% hint style="info" %}
**Nota**: Los reportes generados por **Compilance** y **Cumplo360** se diferencian mediante el **ID de Validación**. Los reportes de Compilance utilizan identificadores numéricos, mientras que los de Cumplo360 utilizan identificadores alfanuméricos.
{% endhint %}

***

### 4. Tipos de reporte

Los filtros varían según el **`tipo de vista`** seleccionada. Se recomienda establecer primero este filtro antes de aplicar los demás, para asegurar que los campos y resultados se ajusten correctamente a la vista elegida.

{% tabs %}
{% tab title="Vista Detallada" %}
El reporte se visualizará con información más detallada de los usuarios que están en las listas de observados.

#### 4.1. Visualización&#x20;

<figure><img src="../../.gitbook/assets/image (604).png" alt=""><figcaption><p>Figura #1: Captura de pantalla reporte detallado.</p></figcaption></figure>

#### 4.2 Filtros

<table><thead><tr><th width="145">Filtro</th><th>Descripción funcional</th></tr></thead><tbody><tr><td><strong><code>Tipo de vista</code></strong></td><td>Permite alternar entre la vista detallada <em>(por usuario y lista)</em> y la vista resumida <em>(indicadores diarios).</em></td></tr><tr><td><strong><code>Fecha de validación</code></strong></td><td>Filtra los registros de validación según la fecha en la que se ejecutó la verificación en <a href="https://virtualsoft.gitbook.io/untitled/glosario#compliance">Compliance</a> o <a href="https://virtualsoft.gitbook.io/plantillas/glosario#cumplo360">Cumplo360</a>. En la vista resumida, solo se muestran resultados hasta el día anterior.</td></tr><tr><td><strong><code>Resultado</code></strong></td><td>Permite mostrar los casos con coincidencias, sin coincidencias o todos en las listas revisadas.</td></tr><tr><td><strong><code>Número de documento</code></strong></td><td>Permite realizar una búsqueda directa por número de documento del usuario.</td></tr><tr><td><strong><code>ID de usuario</code></strong></td><td>Permite buscar un caso puntual mediante el identificador único del usuario en la plataforma.</td></tr></tbody></table>

#### **4.3 Resultados de búsqueda Vista Detallada**

Muestra una fila por cada coincidencia encontrada por el sistema de [Compliance](https://virtualsoft.gitbook.io/untitled/glosario#compliance) y [Cumplo360](https://virtualsoft.gitbook.io/plantillas/glosario#cumplo360).\
Si un usuario presenta coincidencias en varias listas, se mostrará una fila por cada una, con el **score** correspondiente a cada lista.

<table><thead><tr><th width="145">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Validación</code></strong></td><td>Identificador único de la validación generada por el sistema.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario dentro de la plataforma.</td></tr><tr><td><strong><code>Fecha Validación</code></strong></td><td>Momento exacto en que se envió la solicitud de validación a <a href="https://virtualsoft.gitbook.io/untitled/glosario#compliance">Compliance</a> o <a href="https://virtualsoft.gitbook.io/plantillas/glosario#cumplo360">Cumplo360</a>.</td></tr><tr><td><strong><code>Resultado</code></strong></td><td>Estado final de la revisión: <em>(Coincidencia o Sin coincidencia)</em>.</td></tr><tr><td><strong><code>Lista</code></strong></td><td>Nombre de la lista en la cual se encontró coincidencia <em>(ejemplo: OFAC, etc.).</em></td></tr><tr><td><strong><code>Score</code></strong></td><td>Nivel de riesgo asignado por el proveedor de <a href="https://virtualsoft.gitbook.io/untitled/glosario#compliance">Compliance </a>o <a href="https://virtualsoft.gitbook.io/plantillas/glosario#cumplo360">Cumplo360 </a>a la coincidencia encontrada.</td></tr><tr><td><strong><code>Nombre de usuario</code></strong></td><td>Nombre asociado al usuario revisado. </td></tr><tr><td><strong><code>Inactivo por regla automática</code></strong></td><td><ul><li><strong>S</strong>: La cuenta del usuario ha sido inactivado de manera automática por estar en el reporte.</li><li><strong>N</strong>: La cuenta del usuario está activa, aunque esté en el reporte.</li></ul></td></tr></tbody></table>
{% endtab %}

{% tab title="Vista Resumida" %}
El reporte se visualizará con información más general y resumida de los usuarios que aparecen en la lista de observados.

### 4.1. Visualización&#x20;

<figure><img src="../../.gitbook/assets/image (605).png" alt=""><figcaption><p>Figura #2: Captura de pantalla reporte resumido.</p></figcaption></figure>

### 4.2. Filtros

{% hint style="warning" %}
**Nota**: En la vista resumida, solo se muestran resultados hasta el día anterior.
{% endhint %}

<table><thead><tr><th width="170">Filtro</th><th>Descripción funcional</th></tr></thead><tbody><tr><td><strong><code>Tipo de vista</code></strong></td><td>Permite alternar entre la vista detallada (por usuario y lista) y la vista resumida (indicadores diarios).</td></tr><tr><td><strong><code>Fecha de validación</code></strong></td><td>Filtra los registros de validación según la fecha en la que se ejecutó la verificación en <a href="https://virtualsoft.gitbook.io/untitled/glosario#compliance">Compliance</a> o <a href="https://virtualsoft.gitbook.io/plantillas/glosario#cumplo360">Cumplo360</a>.</td></tr></tbody></table>

#### 4.3 Resultados de búsqueda Vista Resumida

Agrupa la información por día, mostrando métricas globales de validaciones realizadas.

<table><thead><tr><th width="170">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Día correspondiente al grupo de validaciones.</td></tr><tr><td><strong><code>Total Validaciones</code></strong></td><td>Número total de usuarios validados en esa fecha.</td></tr><tr><td><strong><code>Coincidencias</code></strong></td><td>Total de validaciones que presentaron coincidencias en alguna lista.</td></tr><tr><td><strong><code>Sin Coincidencias</code></strong></td><td>Total de validaciones que no tuvieron coincidencias.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 5. Validaciones del negocio:

* Cuando no se encuentran coincidencias, los campos _Lista_ y _Score_  del reporte detallado permanecen vacíos.
* La vista detallada permite seguimiento individual por usuario y facilita la trazabilidad de acciones.
* Solo permite visualizar información hasta el día anterior.
* El reporte resumido es útil para monitoreo general del comportamiento diario del sistema de [Compliance](https://virtualsoft.gitbook.io/untitled/glosario#compliance) y [Cumplo360](https://virtualsoft.gitbook.io/plantillas/glosario#cumplo360).
* Los registros visualizados en el reporte podrán estar duplicados debido a que se muestran todos los reportes enviados por los proveedores.

***

### 6. Control de versiones

<details>

<summary>🔽Historial de versiones</summary>

| Versión | Fecha      | Autor         | Descripción                                       |
| ------- | ---------- | ------------- | ------------------------------------------------- |
| 1.0     | 21/10/2025 | Karol Navia   | Creación inicial del documento.                   |
| 1.1     | 26/06/2026 | Ronald Pelaez | Refinamiento y agregar nuevo proveedor Cumplo360. |
| 1.2     | 01/07/2026 | Ronald Peláez | Nueva columna de inactivación automática.         |

</details>
