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
  anchors:
    visible: true
---

# Crear Regalo

<mark style="color:$info;">Permite crear los regalos que los jugadores pueden canjear con puntos de lealtad o recibir como beneficio, ya sea un bono o un premio físico. Se utiliza para definir qué se entrega, en qué vertical, en qué regiones y a partir de qué nivel de lealtad puede redimirse cada regalo.</mark>

***

### 1. Acceso al Módulo

**Ruta de Acceso:** BackOffice > Torneos y bonos > Crear regalo

***

### 2. Visualización

<figure><img src="https://1957026231-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FrLdGx9JdTz3uLoquKvJw%2Fuploads%2Fzc2cRVAI1ktnW2jqY802%2Fimage.png?alt=media" alt=""><figcaption><p>Figura #1: Captura de pantalla Crear regalo.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="133">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="crear-regalo.md#id-4.-formulario-de-creacion-de-regalo"><strong>Crear regalo</strong></a></td><td>Guarda el regalo con la información diligenciada, siempre que se cumplan las validaciones definidas por el sistema.</td></tr></tbody></table>

***

### 4. Formulario de creación de regalo

<table><thead><tr><th width="135.111083984375">Campo</th><th width="123.33331298828125">Tipo de control</th><th width="479.55560302734375">Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha inicial</code></strong></td><td>Calendario</td><td>Fecha desde la cual estará disponible el regalo.</td></tr><tr><td><strong><code>Fecha final</code></strong></td><td>Calendario</td><td>Fecha hasta la cual estará disponible el regalo.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Nombre asignado al regalo.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Campo de texto</td><td>Breve texto que describe el regalo.</td></tr><tr><td><strong><code>Orden</code></strong></td><td>Campo numérico</td><td>Define la posición en la que se mostrará el regalo dentro del listado de reclamación disponible para el usuario. Solo admite números enteros.</td></tr><tr><td><strong><code>Tipo de regalo</code></strong></td><td>Lista desplegable</td><td><p>Selecciona el tipo de regalo que será asignado. Las opciones disponibles son:</p><ul><li><strong>Tienda:</strong> El usuario canjea un artículo o premio de la tienda de recompensas de la plataforma con sus puntos de lealtad acumulados.</li><li><strong>Beneficios:</strong> El usuario recibe un beneficio gratuito, sin consumir saldo ni puntos de lealtad. El beneficio se asigna a partir de una configuración previamente definida en el sistema, como bonos u otros incentivos establecidos por la operación.</li></ul></td></tr><tr><td><strong><code>Tipo de producto</code></strong></td><td>Botón</td><td>Selecciona la vertical en la que se redimirá el regalo o beneficio asignado al usuario <em>(Sportsbook, Casino, Casino en Vivo o Virtuales)</em>.</td></tr><tr><td><strong><code>URL imagen principal</code></strong></td><td>Campo de texto</td><td>Dirección de la imagen representativa del regalo.</td></tr><tr><td><strong><code>URL Imagen Ícono</code></strong></td><td>Campo de texto</td><td>Dirección de la imagen que se mostrará como ícono del regalo o beneficio. Esta imagen es visible para los jugadores dentro de la plataforma.</td></tr><tr><td><strong><code>Asignación de bono</code></strong></td><td>Lista desplegable</td><td><p>Selecciona un bono previamente creado en el módulo de bonos. Solo están disponibles los <a href="crear-bono./">bonos</a> de tipo <strong>Bono de Depósito</strong>, <strong>Freebet</strong>, <strong>Freespin</strong>, <strong>Bono de Casino</strong> y <strong>Cashback</strong>. El bono seleccionado es el beneficio que recibe el usuario al momento de la redención.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Para que un bono aparezca en esta lista, al crearlo el campo <strong><code>Es para</code></strong> debe estar configurado con una de las siguientes opciones:</p><ul><li><strong>Fidelización:</strong> El bono queda disponible como recompensa dentro de la <strong>Tienda de Lealtad</strong>.</li><li><strong>Beneficios:</strong> El bono queda disponible para asignarse como un <strong>Beneficio</strong> dentro del módulo de regalos.</li></ul><p>Solo los bonos configurados con alguna de estas opciones pueden seleccionarse en este campo.</p></div></td></tr><tr><td><strong><code>Descripción premio físico</code></strong></td><td>Campo de texto</td><td>Descripción del producto físico, cuando el regalo no asigna un bono.</td></tr><tr><td><strong><code>Tipo de premio</code></strong></td><td>Botón</td><td><p>Define la forma en que el usuario recibirá el regalo. Las opciones disponibles son:</p><ul><li><strong>Online:</strong> El regalo se entrega de manera digital dentro de la plataforma, sin entrega física. Por ejemplo: bonos, giros gratis o saldo promocional.</li><li><strong>Físico:</strong> El regalo requiere una entrega presencial o el retiro de un artículo, como camisetas o gorras.</li></ul><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Al seleccionar <strong>Físico</strong>, se habilita un campo obligatorio para indicar el tipo de punto de venta donde se entregará el regalo <em>(Propios o Terceros)</em>.</p></div></td></tr><tr><td><strong><code>Acceso por nivel</code></strong></td><td>Lista desplegable</td><td><ul><li><strong>Disponible para todos los niveles:</strong> Todos los usuarios pueden redimir el regalo, sin importar su nivel de lealtad. Es la opción seleccionada por defecto.</li><li><strong>Disponible desde nivel específico:</strong> Habilita el campo <strong><code>Nivel mínimo requerido</code></strong>, donde se indica el nivel mínimo de lealtad que debe tener el usuario para redimir el regalo.</li></ul></td></tr><tr><td><strong><code>Cantidad de redenciones</code></strong></td><td>Campo numérico</td><td>Número máximo de redenciones permitidas para el regalo o beneficio. Al alcanzar esta cantidad, el regalo deja de estar disponible para su redención.</td></tr></tbody></table>

#### 4.1. Moneda

<table><thead><tr><th width="135.111083984375">Campo</th><th width="123.33331298828125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Puntos</code></strong></td><td>Campo numérico</td><td><p>Cantidad de puntos de lealtad que necesita el usuario para redimir el regalo.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> Este campo solo se habilita cuando en <strong><code>Tipo de regalo</code></strong> se selecciona la opción <strong>Tienda</strong>.</p></div></td></tr></tbody></table>

#### 4.2. Opciones avanzadas

<table><thead><tr><th width="135.111083984375">Campo</th><th width="123.33331298828125">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Regiones</code></strong></td><td>Lista desplegable</td><td>Selecciona las regiones donde estará disponible el regalo.</td></tr><tr><td><strong><code>Departamentos</code></strong></td><td>Lista desplegable</td><td>Delimita los departamentos en los que estará disponible el regalo.</td></tr><tr><td><strong><code>Ciudades</code></strong></td><td>Lista desplegable</td><td>Restringe las ciudades donde estará visible el regalo.</td></tr></tbody></table>

***

### 5. Validaciones y reglas del negocio:

* El campo **`Acceso por nivel`** tiene seleccionada por defecto la opción **Disponible para todos los niveles**; con ella, cualquier jugador puede redimir el regalo si cumple las demás condiciones.
* Si se selecciona **Disponible desde nivel específico**, el campo **`Nivel mínimo requerido`** es obligatorio.
* El **nivel mínimo configurado no se puede editar** después de crear el regalo. Para modificarlo, se debe eliminar el regalo y crear uno nuevo.
* Si se configura restricción por nivel:
  * Todos los jugadores pueden ver el regalo.
  * Solo los jugadores que alcanzaron el nivel mínimo o uno superior pueden redimirlo.
  * Los jugadores que no cumplen con el nivel ven el regalo bloqueado.

***

### 6. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="99.888916015625">Versión</th><th width="128.87872314453125">Fecha</th><th width="153.94952392578125">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>28/07/2025</td><td>Ronald Peláez</td><td>Documento inicial.</td></tr><tr><td>1.1</td><td>22/06/2026</td><td>Karol Navia</td><td>Agregar el tipo beneficio.</td></tr><tr><td>1.2</td><td>25/11/2026</td><td>David Velasquez</td><td>Actualización de la estructura del manual.</td></tr></tbody></table>

</details>
