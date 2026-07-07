---
description: >-
  Permite visualizar información de los primeros depósitos y usuarios
  registrados en tiempo real.
---

# Dashboard Registros y primeros depósitos

### 1. Acceso al Módulo

**Ruta de acceso**: [Acceso directo](https://reporting.virtualsoft.tech/MicroStrategyLibrary/app/3394329B42569ED3E0CDD1AABE6F7740/CA2BB694406AAD789C556AA5545FE233/K53--K46).

***

### **2. Configuraciones Previas**

Antes de visualizar el reporte, es necesario establecer las [configuraciones previas](https://virtualsoft.gitbook.io/manuales/microstrategy/tableros#id-2.-configuracion-previa).

***

### 🖼️ 2. Visualización

<figure><img src="../../../.gitbook/assets/image (38).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Dashboard registros y primeros depósitos.</p></figcaption></figure>

***

### 3. 🧑‍💻Acciones del usuario

<table><thead><tr><th width="245">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Filtrar información</code></strong></td><td>Aplicar filtros disponibles para obtener información en el dashboard.</td></tr><tr><td><strong><code>Exportar datos</code></strong></td><td>Descargar la información en formatos <em>(Excel, CSV, PDF).</em></td></tr></tbody></table>

#### 3.1. Filtros disponibles

<table><thead><tr><th width="161.22222900390625">Campo</th><th width="135.44439697265625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el partner asociado al depósito.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Especifica el país desde donde se realizó el depósito o registro.</td></tr><tr><td><strong><code>ID de Usuario</code></strong></td><td>Campo numérico</td><td>Filtra por el identificador único del usuario que realizó el depósito o registro.</td></tr><tr><td><strong><code>Estado (depósito)</code></strong></td><td>Lista desplegable</td><td>Permite especificar el estado actual del depósito (<em>ej. pendiente, aprobado, rechazado</em>).</td></tr><tr><td><strong><code>Nombre Link</code></strong></td><td>Campo de texto</td><td><p>Permite especificar el nombre descriptivo del enlace asociado al depósito o registro.</p><div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo</strong><em><strong>:</strong></em> En una publicación de Facebook sobre un evento deportivo, se incluye un enlace que dirige al sitio de <strong>Doradobet</strong> para registrarse y realizar apuestas relacionadas. (<em>El nombre asignado a ese enlace corresponde al <strong><code>nombre del link</code></strong>.</em>)</p></div></td></tr><tr><td><strong><code>ID Afiliador</code></strong></td><td>Campo numérico</td><td>Filtra por el identificador del <a href="https://virtualsoft.gitbook.io/untitled/glosario/#afiliador">afiliado</a><a href="https://virtualsoft.gitbook.io/untitled/glosario/#afiliador">r</a> responsable del usuario o del link.</td></tr><tr><td><strong><code>Nombre Afiliador</code></strong></td><td>Campo de texto</td><td>Permite especificar el nombre del <a href="https://virtualsoft.gitbook.io/untitled/glosario/#afiliador">afiliador</a> vinculado al usuario.</td></tr><tr><td><strong><code>Código Promocional</code></strong></td><td>Campo de texto</td><td>Filtra por el código utilizado para aplicar promociones o bonos en el depósito.</td></tr><tr><td><strong><code>Tipo Documento</code></strong></td><td>Lista desplegable</td><td>Filtra por el tipo de documento de identidad del usuario (<em>DNI, extranjería, pasaporte</em>).</td></tr><tr><td><strong><code>Fecha Registro</code></strong></td><td>Selector de fecha</td><td>Filtra por la fecha en la que se realizó el registro de un usuario en la plataforma. <em>(No puede ser anterior a la fecha del depósito.)</em></td></tr><tr><td><strong><code>Fecha primer Depósito</code></strong></td><td>Selector de fecha</td><td>Filtra por la fecha en la que se realizó el depósito.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: Los filtros **`Fecha Registro`** y **`Fecha primer Depósito`** Dependen del resto de filtros indicados en la tabla.
{% endhint %}

***

#### 3.2 Indicadores KPI’s

<table><thead><tr><th width="266.77777099609375">Nombre del campo</th><th width="483.88885498046875">Descripción</th></tr></thead><tbody><tr><td><strong><code>Cant. Registros</code></strong> </td><td>Cantidad total de usuarios únicos registrados en la plataforma.</td></tr><tr><td><strong><code>Cant. Primeros Depósitos</code></strong></td><td>Total de usuarios que han realizado su primer depósito hasta la última actualización.</td></tr><tr><td><strong><code>Valor Primer Depósito</code></strong>  </td><td>Suma total del monto de todos los primeros depósitos realizados por los usuarios.</td></tr><tr><td><strong><code>Promedio Registro</code></strong></td><td>Promedio calculado de registros de usuarios en el rango de fechas especificado en el filtro <strong><code>Fecha registro</code></strong></td></tr></tbody></table>

***

#### 3.3. Gráficas

<table><thead><tr><th width="188.444580078125">Gráfica</th><th width="161.5555419921875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Tendencia de registros en el tiempo</code></strong></td><td>Grafica de Líneas</td><td>Muestra la evolución a lo largo del tiempo del número de registros en el tango de fechas especificado.</td></tr><tr><td><strong><code>Tendencia de primeros depósitos por dia</code></strong>   </td><td>Grafica de Líneas</td><td>Muestra la evolución de los depósitos a lo largo del tiempo, uniendo los valores registrados por día para reflejar su tendencia.</td></tr><tr><td><strong><code>Registros VS ftd</code></strong>  </td><td>Grafica de Líneas </td><td>Compara la cantidad de registros con la de primeros depósitos <em>(FTD)</em> a lo largo del tiempo, mostrando mediante dos líneas la evolución.</td></tr><tr><td><strong><code>Top medio depósito</code></strong> </td><td>Grafica de Barras horizontal</td><td>Presenta la cantidad y el valor de los primeros depósitos agrupados por pasarela.</td></tr><tr><td><strong><code>Pasarela VS punto de venta</code></strong>    </td><td>Grafica de Torta</td><td>Muestra la proporción de depósitos realizados a través de puntos de venta en comparación con los efectuados mediante pasarelas de pago.</td></tr></tbody></table>

***

#### 3.4 Tablas

{% tabs %}
{% tab title="3.4.1 Detalle primeros depósitos" %}
<table><thead><tr><th width="252.22216796875">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner asociado al depósito.</td></tr><tr><td><strong><code>País</code></strong></td><td>País desde el cual se realizó el depósito.</td></tr><tr><td><strong><code>ID externo</code></strong></td><td>Identificador externo de la transacción.</td></tr><tr><td><strong><code>Trans Producto ID</code></strong></td><td>Identificador único de el producto (<em>Pasarela de pago</em>) del cual se realizo el primer depósito.</td></tr><tr><td><strong><code>ID usuario</code></strong></td><td>Identificador único del usuario que realizó el depósito.</td></tr><tr><td><strong><code>ID Casino</code></strong></td><td>Identificador único que corresponde al casino o marca de apuestas vinculada al registro o primer depósito del usuario en la plataforma.</td></tr><tr><td><strong><code>Nombre Usuario</code></strong></td><td>Nombre del usuario que efectuó el depósito.</td></tr><tr><td><strong><code>Fecha Primer Deposito</code></strong></td><td>Fecha en la que se registró el primer depósito.</td></tr><tr><td><strong><code>ID Recarga</code></strong></td><td>Código de referencia de la recarga efectuada.</td></tr><tr><td><strong><code>Valor Primer Deposito</code></strong></td><td>Monto total del primer depósito realizado.</td></tr><tr><td><strong><code>Medio depósito</code></strong>        </td><td>Indica cual fue el medio por el cual se realizó el depósito.</td></tr><tr><td><strong><code>Nombre medio depósito</code></strong> </td><td>Nombre del medio por el cual se realizo el depósito</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual del depósito (<em>procesado, pendiente, rechazado, etc.</em>).</td></tr></tbody></table>
{% endtab %}

{% tab title="3.4.2 Detalle de usuarios registrados" %}
<table><thead><tr><th width="185.55560302734375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner asociado al registro.</td></tr><tr><td><strong><code>País</code></strong></td><td>País del usuario registrado.</td></tr><tr><td><strong><code>Id Usuario</code></strong></td><td>Identificador único del usuario.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre completo del usuario.</td></tr><tr><td><strong><code>Login</code></strong></td><td>Nombre de usuario o alias usado para acceder a la cuenta.</td></tr><tr><td><strong><code>Tipo Documento</code></strong></td><td>Tipo de documento del usuario (<em>DNI, pasaporte, etc...</em>).</td></tr><tr><td><strong><code>Documento</code></strong></td><td>Número de documento de identidad.</td></tr><tr><td><strong><code>IP registro</code></strong></td><td>Dirección IP utilizada al momento del registro.</td></tr><tr><td><strong><code>Celular</code></strong></td><td>Número de teléfono móvil del usuario.</td></tr><tr><td><strong><code>Id link</code></strong></td><td>Identificador del enlace de registro.</td></tr><tr><td><strong><code>Nombre Link</code></strong></td><td>Nombre o descripción del enlace de registro.</td></tr><tr><td><strong><code>Id Afiliador</code></strong></td><td>Identificador del afiliador asociado.</td></tr><tr><td><strong><code>Nombre Afiliador</code></strong></td><td>Nombre del afiliador que refirió al usuario.</td></tr><tr><td><strong><code>Código</code></strong></td><td>Código promocional o de referencia.</td></tr><tr><td><strong><code>Nombre del código</code></strong></td><td>Nombre asociado al código promocional.</td></tr><tr><td><strong><code>Fecha Registro</code></strong></td><td>Fecha en la que se completó el registro del usuario.</td></tr></tbody></table>
{% endtab %}

{% tab title="3.4.3. Resumen" %}
<table><thead><tr><th width="218.4444580078125">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner asociado.</td></tr><tr><td><strong><code>País</code></strong></td><td>País correspondiente al registro.</td></tr><tr><td><strong><code>ID_Link</code></strong></td><td>Identificador del link de registro.</td></tr><tr><td><strong><code>Nombre_Link</code></strong></td><td>Nombre o descripción del link de registro.</td></tr><tr><td><strong><code>ID_Afiliador</code></strong></td><td>Identificador del afiliador.</td></tr><tr><td><strong><code>Nombre_Afiliador</code></strong></td><td>Nombre del afiliador vinculado.</td></tr><tr><td><strong><code>Medio del deposito</code></strong></td><td>Canal o método mediante el cual se realizó el depósito.</td></tr><tr><td><strong><code>Cantidad de registros</code></strong></td><td>Número total de usuarios registrados.</td></tr><tr><td><strong><code>Cantidad de primeros depósitos</code></strong></td><td>Número de usuarios que realizaron su primer depósito.</td></tr><tr><td><strong><code>Valor total del primer depósito</code></strong></td><td>Suma total de los valores de los primeros depósitos.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 🕒 4. Control de Versiones

| Versión | Fecha      | Autor           | Cambios Realizados       |
| ------- | ---------- | --------------- | ------------------------ |
| 1.0     | 20/10/2025 | David velasquez | Documento inicial        |
| 1.1     | 22/11/2025 | Ronald Pelaez   | Refinamiento del manual. |
