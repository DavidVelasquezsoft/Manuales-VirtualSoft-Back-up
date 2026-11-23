---
description: >-
  El módulo Regalos permite la administración de premios asociados a bonos o
  productos físicos.     Ofrece funcionalidades para configurar reglas de
  visibilidad y restricción según niveles de jugador.
---

# Crear Regalo

### 1. Acceso al módulo

**Ruta de Acceso:** BackOffice > Torneos y bonos > Crear regalo

***

### 2. Visualización

<figure><img src="https://1957026231-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FrLdGx9JdTz3uLoquKvJw%2Fuploads%2Fzc2cRVAI1ktnW2jqY802%2Fimage.png?alt=media" alt=""><figcaption><p>Figura #1: Captura de pantalla Crear regalo</p></figcaption></figure>

***

### 3. Acciones de Usuario

<table><thead><tr><th width="133">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="crear-regalo.md#id-4.-creacion-de-regalo"><strong>Crear regalo</strong></a></td><td>Guarda el regalo con la información diligenciada, siempre que se cumplan las validaciones definidas por el sistema.</td></tr></tbody></table>

### 4. Formulario para la creación de un regalo

<table><thead><tr><th width="135.111083984375">Campo</th><th width="123.33331298828125">Tipo de campo</th><th width="479.55560302734375">Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha inicial</code></strong></td><td>Fecha</td><td>Fecha desde la cual estará disponible el regalo</td></tr><tr><td><strong><code>Fecha final</code></strong></td><td>Fecha </td><td>Fecha hasta la cual estará disponible el regalo</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Texto</td><td>Nombre asignado al regalo</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Breve texto que describe el regalo</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Numérico <em>(entero)</em></td><td>Define la posición en la que se mostrará el regalo dentro del listado de reclamación disponible para el usuario.</td></tr><tr><td><strong><code>Tipo de regalo</code></strong></td><td>Selector desplegable</td><td><p>Selecciona el tipo de regalo que será asignado. Las opciones disponibles son:</p><ul><li><strong>Tienda:</strong> Se podrá canjear un artículo o premio disponible en la tienda de recompensas de la plataforma utilizando los puntos de lealtad acumulados.</li><li><strong>Beneficios:</strong> Se recibirá un beneficio de forma gratuita, sin consumir saldo ni puntos de lealtad. El beneficio será asignado a partir de una configuración previamente definida en el sistema, como bonos u otros incentivos establecidos por la operación.</li></ul></td></tr><tr><td><strong><code>Tipo de producto</code></strong></td><td>Botón</td><td>Selecciona la vertical en la que se redimirá el regalo o beneficio asignado al usuario, <em>(Sportsbook, Casino, Casino en Vivo o Virtuales)</em>.</td></tr><tr><td><strong><code>URL imagen principal</code></strong></td><td>Texto <em>(URL)</em></td><td>Dirección de la imagen representativa del regalo</td></tr><tr><td><strong><code>URL Imagen Ícono</code></strong></td><td>Texto <em>(URL)</em></td><td>Ingrese la URL de la imagen representativa que se mostrará como ícono del regalo o beneficio. Esta imagen será visible para los jugadores dentro de la plataforma.</td></tr><tr><td><strong><code>Asignación de bono</code></strong></td><td>Selector desplegable</td><td><p>Selecciona un bono previamente creado en el módulo de bonos. Solo estarán disponibles los <a href="crear-bono./">bonos</a> de tipo <strong>Bono de Depósito</strong>, <strong>Freebet</strong>, <strong>Freespin</strong>, <strong>Bono de Casino</strong> y <strong>Cashback</strong>. El bono seleccionado será el beneficio asignado al usuario al momento de la redención.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Para que un bono esté disponible en esta sección, al momento de su creación el campo <strong>Es para</strong> debe estar configurado con una de las siguientes opciones:</p><ul><li><strong>Fidelización:</strong> Permite que el bono esté disponible para ser utilizado como recompensa dentro de la <strong>Tienda de Lealtad</strong>.</li><li><strong>Beneficios:</strong> Permite que el bono esté disponible para ser asignado como un <strong>Beneficio</strong> dentro del módulo de regalos.</li></ul><p>Solo los bonos configurados con alguna de estas opciones podrán ser seleccionados en este campo.</p></div></td></tr><tr><td><strong><code>Descripción premio físico</code></strong></td><td>Texto</td><td>Descripción del producto físico en caso de no asignar un bono</td></tr><tr><td><strong><code>Tipo de premio</code></strong></td><td>Botón</td><td><p>Permite definir la forma en que el usuario recibirá el regalo. Las opciones disponibles son:</p><ul><li><strong>Online:</strong> El regalo se entrega de manera digital dentro de la plataforma, sin requerir una entrega física. Algunos ejemplos son bonos, giros gratis, saldo promocional, etc.</li><li><strong>Físico:</strong> El regalo requiere una entrega presencial o el retiro de un artículo, como camisetas, gorras, etc.</li></ul><p>Si se selecciona la opción <strong>Físico</strong>, se desplegará un campo donde será obligatorio indicar el tipo de punto de venta en el que se realizará la entrega del regalo, pudiendo elegir entre <strong>Propios</strong> o <strong>Terceros</strong>.</p></td></tr><tr><td><strong><code>Acceso por</code></strong> <a href="crear-regalo.md#id-4.-glosario"><strong><code>nivel</code></strong></a></td><td>Selector desplegable</td><td><ul><li><strong>Disponible para todos los niveles:</strong> Todos los usuarios podrán redimir este regalo sin importar el nivel de lealtad que tengan</li><li> <strong>Disponible desde nivel específico:</strong> Se habilitará el campo <strong>"<code>Nivel mínimo requerido</code>"</strong>, donde deberás indicar el nivel mínimo de lealtad que debe tener el usuario para poder redimir el regalo.</li></ul></td></tr><tr><td><strong><code>Cantidad de redenciones</code></strong></td><td>Numérico (<em>entero)</em></td><td>Establece el número máximo de redenciones permitidas para el regalo o beneficio configurado. Al alcanzar la cantidad definida, el regalo dejará de estar disponible para su redención.</td></tr></tbody></table>

***

<details>

<summary>🪙Moneda</summary>

<table><thead><tr><th width="112">Campo</th><th width="145">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Puntos</code></strong></td><td>Número</td><td><p>Indica la cantidad de puntos que necesita el usuario para poder redimir este regalo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo sólo estará disponible para su configuración cuando en el campo <strong>Tipo de Regalo</strong> se haya seleccionado la opción <strong>Tienda</strong>.</p></div></td></tr></tbody></table>

</details>

***

<details>

<summary>⚙️Opciones avanzadas</summary>

<table><thead><tr><th width="158">Campo</th><th width="195">Tipo de campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Regiones</code></strong></td><td>Lista de selección</td><td>Seleccióna de regiones donde estará disponible el regalo</td></tr><tr><td><strong><code>Departamentos</code></strong></td><td>Lista de selección</td><td>Establece los departamentos en los que estarán disponibles</td></tr><tr><td><strong><code>Ciudades</code></strong></td><td>Lista de selección</td><td>Seleccióna de ciudades donde estará visible el regalo</td></tr></tbody></table>

</details>

***

### 4. Validaciones y reglas de negocio

* Si se selecciona “**Disponible desde nivel específico**”, el campo “**Nivel mínimo requerido**” será obligatorio.
* El **nivel mínimo configurado no podrá ser editado** después de crear el regalo. Para modificarlo, se debe eliminar y crear uno nuevo.
* Si se configura restricción por nivel:
  * Todos los jugadores podrán ver el regalo.
  * Solo los jugadores que hayan alcanzado el nivel mínimo o superior podrán redimirlo.
  * Los jugadores que no cumplan con el nivel verán el regalo bloqueado.
* Si se selecciona “**Disponible para todos los niveles**”, cualquier jugador podrá redimir el regalo si cumple las demás condiciones.
* El campo `Acceso por` [`nivel`](crear-regalo.md#id-4.-glosario) siempre estará por defecto con la opción "**disponible para todos los niveles".**

***

### 5. Control de versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="109">Versión</th><th width="127">Fecha</th><th width="144">Autor</th><th>Cambios realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/07/2025</td><td>Ronald Peláez</td><td>Documento inicial </td></tr><tr><td>1.1</td><td>22/06/2026</td><td>Karol Navia</td><td>Agregar el tipo beneficio</td></tr></tbody></table>

</details>
