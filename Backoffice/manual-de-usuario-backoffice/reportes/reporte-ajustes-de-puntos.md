---
description: >-
  Permite visualizar y realizar ajustes de puntos de lealtad de forma individual
  o masiva con movimientos de ingreso y egreso de puntos.
---

# Reporte ajustes de puntos

{% hint style="warning" %}
**Nota:** Este reporte esta disponible únicamente para operadores con permisos habilitados.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de Acceso**: Backoffice > Reportes > Reporte ajustes de puntos

***

### 2. 🖼️ Visualización

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption><p>Figura #1: captura de pantalla reporte ajustes puntos</p></figcaption></figure>

***

### &#x33;**.** 🧑‍💻 **Acciones disponibles**

<table><thead><tr><th width="192.66668701171875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="reporte-ajustes-de-puntos.md#id-3.1.-filtros"><strong>Filtros</strong></a></td><td>Permiten filtrar la información de manera resumida o detallada para obtener resultados mas precisos.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros a su estado inicial.</td></tr><tr><td><a href="reporte-ajustes-de-puntos.md#id-3.2.-consultar"><strong>Consultar</strong></a></td><td>Aplica los filtros seleccionados y muestra los registros válidos ya sea en vista resumida o detallada.</td></tr><tr><td><a href="reporte-ajustes-de-puntos.md#id-3.3.-ajustar-puntos"><strong>Ajustar Puntos</strong></a></td><td>Permite realizar un ajuste de <a href="https://virtualsoft.gitbook.io/untitled/glosario/#puntos-calificables">puntos</a> a un usuario en especifico ya sea <strong>Entrada</strong> para sumar puntos o <strong>Salida</strong> para restarlos.</td></tr><tr><td><strong>Exportar</strong></td><td>El botón <strong>Exportar</strong> en la parte inferior derecha del reporte permite descargar los resultados obtenidos con los filtros aplicados en los formatos <strong>Excel (.XLS)</strong> y <strong>PDF.</strong></td></tr></tbody></table>

#### 3.1. 🔎 Filtros

<table><thead><tr><th width="169.00006103515625">Filtro</th><th width="129.88885498046875">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha ajuste</code></strong></td><td>Calendario</td><td>Selecciona una fecha específica o un rango de fechas para consultar los ajustes de saldo realizados.</td></tr><tr><td><strong><code>ID ajuste</code></strong></td><td>Numérico</td><td>Filtra por los registros mediante el identificador único del ajuste de saldo.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Numérico</td><td>Busca los ajustes asociados a un usuario específico mediante su identificador único.</td></tr><tr><td><strong><code>Tipo Movimiento</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los ajustes según el tipo de movimiento de saldo, ya sea <strong>entrada</strong> o <strong>salida</strong>.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los ajustes de saldo según el país asociado al usuario o a la operación registrada.</td></tr></tbody></table>

#### 3.2. 🚀 Consultar

Aplica los filtros seleccionados y presenta los resultados de los registros validos.

<table><thead><tr><th width="231.77777099609375">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Ajuste</code></strong></td><td>Identificador único del ajuste de saldo registrado en el sistema.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único del usuario al que se le aplicó el ajuste de saldo.</td></tr><tr><td><strong><code>Nombre Usuario</code></strong></td><td>Nombre del usuario asociado al ajuste de saldo.</td></tr><tr><td><strong><code>Tipo de movimiento</code></strong></td><td>Indica el tipo de ajuste realizado sobre el saldo del usuario, ya sea <strong>entrada</strong> o <strong>salida</strong>.</td></tr><tr><td><strong><code>Valor</code></strong></td><td>Monto del ajuste de saldo aplicado al usuario.</td></tr><tr><td><strong><code>Fecha creación</code></strong></td><td>Fecha y hora en la que se registró el ajuste de saldo.</td></tr><tr><td><strong><code>Fecha Expiración</code></strong></td><td><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo se encuentra <strong>obsoleto</strong> y no tiene efecto en el sistema. Actualmente, los <strong>ajustes de puntos canjeables no tienen expiración</strong>, por lo que la fecha mostrada no es válida y no debe considerarse para la operación.</p></div></td></tr><tr><td><strong><code>Id operador</code></strong></td><td>Identificador único del operador o usuario administrativo que realizó el ajuste de saldo.</td></tr></tbody></table>

#### 3.3. 🎰 **Ajustar puntos**

Al hacer clic en el botón **`Ajustar puntos`** permite realizar entradas o salidas de [puntos de lealtad](https://virtualsoft.gitbook.io/untitled/glosario/#puntos-calificables) por medio de 2 modos de carga ya sea individualmente o masivamente.

👤 **Modo de carga individualmente**

Al seleccionar el método de carga individualmente se mostrarán los siguientes campos obligatorios.

<table><thead><tr><th width="187.333251953125">Campo</th><th width="136.00006103515625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID del Usuario</code></strong></td><td>Numérico</td><td>Indica el identificador único del usuario al que se le añadirán o quitarán puntos.</td></tr><tr><td><strong><code>Tipo de Movimiento</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el tipo de operación que se realizará sobre los puntos del usuario: <strong>Entrada</strong> para sumar puntos o <strong>Salida</strong> para restarlos.</td></tr><tr><td><strong><code>Cantidad de Puntos</code></strong></td><td>Numérico</td><td>Permite definir la cantidad de puntos a modificar. Solo acepta valores numéricos mayores a 0 y es de carácter obligatorio.</td></tr></tbody></table>

**👥** **Modo carga masivamente**

Al seleccionar el método de **carga masiva**, se permite realizar **múltiples movimientos individuales** a varios jugadores de forma simultánea mediante la **`Cargar archivo`** [**`CSV`**](https://virtualsoft.gitbook.io/untitled/glosario/#csv), el cual deberá tener las siguientes **columnas**:

<table><thead><tr><th width="177.55548095703125">Columna</th><th width="128.88897705078125">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>ID usuario</strong></td><td>Numérico</td><td>Indica el identificador único del usuario al cual se le hará el movimiento.</td></tr><tr><td><strong>Movimiento</strong></td><td>Texto</td><td><p>Indica que tipo de movimiento se le va a aplicar al usuario con los siguientes valores:<br></p><ul><li><strong>E</strong> : (<em>Entrada</em>) Para sumar puntos.</li><li><strong>S</strong> : (<em>Salida</em>) Para quitar puntos.</li></ul></td></tr><tr><td><strong>Cantidad de puntos</strong></td><td>Numérico</td><td>Indica la cantidad de puntos con los que se realizará el movimiento.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** para realizar un ajuste de puntos de forma correcta deberá indicar el **token de autenticación** de su cuenta para confirmar su identidad.
{% endhint %}

***

### 4. ✅ Validaciones y reglas del negocio

* En cualquier operación ya sea de salida o entrada el sistema validara cada campo que cumpla con las validaciones del sistema, de lo contrario se mostrará mensaje de error o ignorara la operación.
* cuando la operación se realizo exitosamente el sistema mostrará mensaje **"La operación se realizó exitosamente."**
* Para realizar ajustes de saldo, el usuario debe contar con el **permiso correspondiente**.

***

### 5. 🕓 Control de Versiones

<table><thead><tr><th width="141.88885498046875">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>30/01/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>
