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

# Punto de Venta

<mark style="color:$info;">Consulta los puntos de venta registrados mediante filtros de búsqueda y una tabla de resultados. Desde este espacio también se encuentran disponibles las funcionalidades de creación, configuración y gestión operativa de los puntos de venta.</mark>

{% hint style="danger" %}
**Nota importante**: Para acceder a un punto de venta específico es necesario realizar la búsqueda exacta.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Gestión Punto de Venta > Punto de Venta

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (681).png" alt=""><figcaption><p>Figura #1: Captura de pantalla módulo puntos de venta.</p></figcaption></figure>

***

### 3. Acciones de usuario

<table><thead><tr><th width="232">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Consultar</strong></td><td>Aplica los filtros seleccionados y muestra los puntos de venta encontrados.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece los filtros de búsqueda.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/gestion-punto-de-venta/punto-de-venta#anadir-punto-de-venta"><strong>Añadir Punto de Venta</strong></a></td><td>Registra un nuevo punto de venta.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/gestion-punto-de-venta/punto-de-venta#activar-contingencia-masiva"><strong>Activar Contingencia</strong></a></td><td>Activa contingencias a los puntos de venta de forma masiva mediante un archivo CSV.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/gestion-punto-de-venta/punto-de-venta#desactivar-contingencia-masiva"><strong>Desactivar Contingencia</strong></a></td><td>Desactiva contingencias a los puntos de venta de forma masiva mediante un archivo CSV.</td></tr></tbody></table>

<details>

<summary><strong>Activar Contingencia Masiva</strong></summary>

Despliega un pop-up para cargar un archivo .CSV con los ID de los puntos de venta a los que se les activará una contingencia.

<table><thead><tr><th width="139">Campo</th><th width="163">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cargar archivo CSV</code></strong></td><td>Carga de archivo</td><td>Contiene el listado de puntos de venta a los que se les activará la contingencia.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Selecciona la contingencia que será activada.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Registra el motivo de la activación realizada.</td></tr></tbody></table>

</details>

<details>

<summary><strong>Desactivar Contingencia Masiva</strong></summary>

Despliega un pop-up para cargar un archivo .CSV con los ID de los puntos de venta a los que se les desactivará una contingencia.

<table><thead><tr><th width="139">Campo</th><th width="163">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cargar archivo CSV</code></strong></td><td>Carga de archivo</td><td>Contiene el listado de puntos de venta a los que se les desactivar la contingencia.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Selecciona la contingencia que será desactivada.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Registra el motivo de la desactivación realizada.</td></tr></tbody></table>

</details>

<details>

<summary><strong>Añadir Punto</strong></summary>

Crea un nuevo punto de venta dentro de la plataforma. Al hacer clic en este botón se abrirá una ventana de configuración en la que se deberán registrar los datos de acceso, información de contacto, ubicación y parámetros operativos necesarios para habilitar su funcionamiento.

La configuración se encuentra organizada en las siguientes secciones:

#### Datos principales

Registra los datos básicos de identificación y acceso del punto de venta, así como la información general relacionada con su operación, ubicación y configuración inicial.

<table><thead><tr><th width="154">Campo</th><th width="161">Tipo de control</th><th width="374">Descripción</th></tr></thead><tbody><tr><td><strong><code>Login para acceso</code></strong></td><td>Texto</td><td>Usuario utilizado para ingresar a la plataforma.</td></tr><tr><td><strong><code>Clave</code></strong></td><td>Texto</td><td>Contraseña asociada al usuario de acceso.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Estado del punto de venta.</td></tr><tr><td><strong><code>Idioma preferido</code></strong></td><td>Lista desplegable</td><td>Idioma utilizado en la interfaz de la plataforma.</td></tr><tr><td><strong><code>Nombre del usuario</code></strong></td><td>Texto</td><td>Nombre del responsable del punto de venta.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País asociado al punto de venta.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Lista desplegable</td><td>Moneda utilizada para las transacciones.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Partner asociado al punto de venta.</td></tr><tr><td><strong><code>Tipo de establecimiento</code></strong></td><td>Lista desplegable</td><td>Categoría del establecimiento comercial.</td></tr></tbody></table>

#### Datos de Configuración

Contiene los parámetros operativos y de seguridad que determinan el comportamiento del punto de venta dentro de la plataforma, incluyendo permisos de venta, recargas, validación de IP, impresión de recibos y mensajes personalizados para comprobantes.



<table><thead><tr><th width="120">Campo</th><th width="118">Tipo de control</th><th width="427">Descripción</th></tr></thead><tbody><tr><td><strong><code>Bloqueado para ventas</code></strong></td><td>Interruptor</td><td>Controla la disponibilidad de ventas en el punto de venta.</td></tr><tr><td><strong><code>Imprime recibo de caja</code></strong></td><td>Interruptor</td><td>Controla la impresión de recibos de caja.</td></tr><tr><td><strong><code>Permite recargas</code></strong></td><td>Interruptor</td><td>Controla la disponibilidad de recargas.</td></tr><tr><td><strong><code>Permite activar registros</code></strong></td><td>Interruptor</td><td>Controla la activación de registros de usuarios.</td></tr><tr><td><strong><code>Programa de identificación de IP activo</code></strong></td><td>Interruptor</td><td>Controla la validación de IP durante el acceso.</td></tr><tr><td><strong><code>Latitud</code></strong></td><td>Campo numérico</td><td>Coordenada geográfica de ubicación.</td></tr><tr><td><strong><code>Longitud</code></strong></td><td>Campo numérico</td><td>Coordenada geográfica de ubicación.</td></tr><tr><td><strong><code>IP</code></strong></td><td>Campo de texto</td><td>Dirección IP asociada al punto de venta.</td></tr><tr><td><strong><code>Parte superior recibo pago premio</code></strong></td><td>Área de texto</td><td>Texto mostrado en la parte superior del recibo de pago de premio.</td></tr><tr><td><strong><code>Parte inferior recibo pago premio</code></strong></td><td>Área de texto</td><td>Texto mostrado en la parte inferior del recibo de pago de premio.</td></tr><tr><td><strong><code>Parte superior recibo pago retiro</code></strong></td><td>Área de texto</td><td>Texto mostrado en la parte superior del recibo de pago de retiro.</td></tr><tr><td><strong><code>Parte inferior recibo pago retiro</code></strong></td><td>Área de texto</td><td>Texto mostrado en la parte inferior del recibo de pago de retiro.</td></tr></tbody></table>

#### Datos Punto de Venta

Permite registrar la información de contacto, ubicación física y estructura comercial asociada al punto de venta, facilitando su identificación y gestión dentro de la operación.

<table><thead><tr><th width="127">Campo</th><th width="127">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del contacto</code></strong></td><td>Texto</td><td>Nombre de la persona responsable del punto de venta.</td></tr><tr><td><strong><code>Número de cédula</code></strong></td><td>Texto</td><td>Documento de identidad del contacto.</td></tr><tr><td><strong><code>Correo electrónico</code></strong></td><td>Texto</td><td>Correo electrónico de contacto.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Información adicional del punto de venta.</td></tr><tr><td><strong><code>Teléfono</code></strong></td><td>Texto</td><td>Número de contacto principal.</td></tr><tr><td><strong><code>Concesionario</code></strong></td><td>Lista desplegable</td><td>Concesionario asociado al punto de venta.</td></tr><tr><td><strong><code>Subconcesionario</code></strong></td><td>Lista desplegable</td><td>Subconcesionario asociado al punto de venta.</td></tr><tr><td><strong><code>Subconcesionario 2</code></strong></td><td>Lista desplegable</td><td>Segundo subconcesionario asociado al punto de venta.</td></tr><tr><td><strong><code>Provincia</code></strong></td><td>Lista desplegable</td><td>Provincia asociada al punto de venta.</td></tr><tr><td><strong><code>Región</code></strong></td><td>Lista desplegable</td><td>Región asociada al punto de venta.</td></tr><tr><td><strong><code>Ciudad</code></strong></td><td>Lista desplegable</td><td>Ciudad asociada al punto de venta.</td></tr><tr><td><strong><code>Zona</code></strong></td><td>Lista desplegable</td><td>Zona asociada al punto de venta.</td></tr><tr><td><strong><code>Dirección</code></strong></td><td>Texto</td><td>Dirección física registrada.</td></tr><tr><td><strong><code>Barrio</code></strong></td><td>Texto</td><td>Barrio asociado al punto de venta.</td></tr><tr><td><strong><code>Teléfono móvil</code></strong></td><td>Texto</td><td>Número de contacto móvil.</td></tr></tbody></table>

#### Configuración punto de Venta

Agrupa las reglas operativas y límites transaccionales aplicables al punto de venta, incluyendo montos máximos permitidos, impuestos, clasificación operativa y características específicas de funcionamiento.

<table><thead><tr><th width="157">Campo</th><th width="145">Tipo</th><th width="365">Descripción</th></tr></thead><tbody><tr><td><strong><code>Límite diario de recargas</code></strong></td><td>Numérico</td><td>Monto máximo permitido para recargas diarias.</td></tr><tr><td><strong><code>Máximo monto por retiro</code></strong></td><td>Numérico</td><td>Monto máximo permitido por retiro.</td></tr><tr><td><strong><code>Máximo monto de pago de premio</code></strong></td><td>Numérico</td><td>Monto máximo permitido para pagos de premios.</td></tr><tr><td><strong><code>Impuesto al pago de premio (GGR)</code></strong></td><td>Numérico</td><td>Porcentaje aplicado al pago de premios.</td></tr><tr><td><strong><code>¿Es propio?</code></strong></td><td>Selector</td><td>Indica si el punto de venta pertenece a la operación.</td></tr><tr><td><strong><code>Tipo de punto</code></strong></td><td>Selector</td><td>Clasificación operativa del punto de venta <em>(física, Virtual).</em></td></tr><tr><td><strong><code>¿Entrega premio físico?</code></strong></td><td>Selector</td><td>Indica si el punto de venta puede entregar premios físicos.</td></tr></tbody></table>

</details>

### **4. Filtros**

Los filtros disponibles permiten consultar los puntos de venta según criterios específicos.

{% hint style="warning" %}
**Nota:** Si no se aplica ningún filtro, el sistema mostrará todos los puntos de venta registrados.
{% endhint %}

<table><thead><tr><th width="202">Filtro</th><th width="146">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Identificador único del punto de venta.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre del punto de venta.</td></tr><tr><td><strong><code>Número de cédula</code></strong></td><td>Texto</td><td>Documento de identidad del propietario del punto de venta</td></tr><tr><td><strong><code>Login</code></strong></td><td>Texto</td><td>Nombre de usuario con el que accede al sistema.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País donde se encuentra registrado el punto de venta.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Lista desplegable</td><td>Estado actual del punto de venta.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha</td><td>Fecha de registro del punto de venta.</td></tr></tbody></table>

#### **4.1. Filtros avanzados**

<details>

<summary><strong>Detalles</strong></summary>

Los filtros disponibles permiten consultar los puntos de venta según criterios específicos.

<table><thead><tr><th width="165">Filtro</th><th width="146">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del contacto</code></strong></td><td>Texto</td><td>Nombre de la persona de contacto asociada al punto de venta.</td></tr><tr><td><strong><code>Correo electrónico</code></strong></td><td>Texto</td><td>Correo electrónico registrado para contacto.</td></tr><tr><td><strong><code>Teléfono</code></strong></td><td>Numérico</td><td>Número de contacto asociado al punto de venta.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Texto</td><td>Dirección IP registrada para el punto de venta.</td></tr><tr><td><strong><code>Provincia/Región</code></strong></td><td>Texto</td><td>Provincia o región asociada al punto de venta.</td></tr><tr><td><strong><code>Ciudad</code></strong></td><td>Texto</td><td>Ciudad asociada al punto de venta.</td></tr><tr><td><strong><code>Barrio</code></strong></td><td>Texto</td><td>Barrio registrado para el punto de venta.</td></tr><tr><td><strong><code>Zona</code></strong></td><td>Lista desplegable</td><td>Zona asociada al punto de venta.</td></tr><tr><td><strong><code>Dirección</code></strong></td><td>Texto</td><td>Dirección física registrada.</td></tr><tr><td><strong><code>Programa de identificación de IP Activo</code></strong></td><td>Lista desplegable</td><td>Estado de la validación de IP para el acceso al sistema.</td></tr><tr><td><strong><code>Ordenar por</code></strong></td><td>Lista desplegable</td><td>Campo utilizado para organizar los resultados.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Lista desplegable</td><td>Determina el criterio con el que se organizarán los resultados de la tabla <em>(Fecha de creación, ID, Login, Nombre).</em></td></tr><tr><td><strong><code>ID Concesionario</code></strong></td><td>Texto</td><td>Identificador del concesionario asociado al punto de venta.</td></tr><tr><td><strong><code>Subconcesionario</code></strong></td><td>Texto</td><td>Subconcesionario asociado al punto de venta.</td></tr></tbody></table>

</details>

### **5. Tabla puntos de venta**

{% hint style="warning" %}
**Nota:** Cuando la consulta arroje un punto de venta específico, los resultados se mostrarán en una estructura jerárquica organizada de la siguiente manera:

📁 **Partner**\
&#x20;   ↳ 📁 **País**\
&#x20;       ↳ 🔍 **Punto de Venta**

Selecciona cada ícono **📁** para desplegar el siguiente nivel de la estructura hasta visualizar el punto de venta consultado.

Al llegar al último nivel, la opción **🔍** permitirá ingresar al detalle del punto de venta y acceder a sus módulos de información, configuración y demás funcionalidades de gestión.

Las consultas generales mostrarán directamente los registros en la tabla de resultados y no dispondrán de acceso al detalle del punto de venta.
{% endhint %}

<table><thead><tr><th width="194">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha de registro del punto de venta.</td></tr><tr><td><strong><code>🔍</code></strong></td><td>Accede al detalle del punto de venta y a los módulos disponibles para su gestión <em>(Disponible únicamente en consultas específicas)</em>.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario propietario.</td></tr><tr><td><strong><code>Número de cédula</code></strong></td><td>Documento de identidad de la persona encargada del punto de venta</td></tr><tr><td><strong><code>Login</code></strong></td><td>Usuario de acceso al sistema.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre del propietario del punto de venta.</td></tr><tr><td><strong><code>Saldo</code></strong></td><td>Saldo disponible para la operación.</td></tr><tr><td><strong><code>Región</code></strong></td><td>Región asociada al punto de venta.</td></tr><tr><td><strong><code>Departamento</code></strong></td><td>Departamento asociado al punto de venta.</td></tr><tr><td><strong><code>Ciudad</code></strong></td><td>Ciudad asociada al punto de venta.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda configurada para la operación.</td></tr><tr><td><strong><code>Teléfono</code></strong></td><td>Número de contacto registrado.</td></tr><tr><td><strong><code>Dirección</code></strong></td><td>Dirección física registrada.</td></tr><tr><td><strong><code>Dirección IP</code></strong></td><td>Dirección IP asociada al punto de venta.</td></tr><tr><td><strong><code>Fecha de último login</code></strong></td><td>Última fecha de acceso al sistema.</td></tr><tr><td><strong><code>Modificado</code></strong></td><td>Indica si el registro presenta modificaciones recientes.</td></tr></tbody></table>

***

### 5. Validaciones y reglas de negocio

* Los filtros de consulta son opcionales.
* La activación y desactivación masiva requieren la carga de un archivo CSV válido.
* El campo **Descripción** es obligatorio para las operaciones de activación y desactivación de contingencias.
* Los campos obligatorios deben completarse antes de registrar un nuevo punto de venta.

***

### 6. Control de Versiones

<details>

<summary>🔽 <strong>Historial de versiones</strong></summary>

| Versión | Fecha      | Autor         | Cambios Realizados         |
| ------- | ---------- | ------------- | -------------------------- |
| 1.0     | 10/07/2026 | Ronald Peláez | Documento inicial.         |
| 1.1     | 22/07/2020 | Ronald Peláez | Ajustes por nuevo formato. |

</details>
