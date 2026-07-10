---
description: >-
  Este módulo permite personalizar la sección inferior (footer) del sitio web de
  usuarios online, configurando elementos visuales como menú, redes sociales,
  patrocinadores, licencia, enlaces y más.
---

# Footer

## 1. Acceso al Módulo

**Ruta de Acceso**: Site Builder > Partner > Apariencia > Footer

***

## 🖼️ 2. Visualización

<figure><img src="../../../.gitbook/assets/image (99).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección footer.</p></figcaption></figure>

***

## 🛠️ &#x33;**.** Configuarión elementos footer.

<table><thead><tr><th width="163.388916015625">Opción</th><th width="103.2037353515625">Tipo de Control</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Descarga la app</code></td><td>Checkbox</td><td>Activa/Desactiva tarjeta en el footer con enlace para descarga de la app.</td></tr><tr><td><code>Menú en el footer</code></td><td>Checkbox</td><td>Activa/Desactiva menú de navegación inferior.</td></tr><tr><td><code>Pasarelas de pago</code></td><td>Checkbox</td><td>Activa/Desactiva la visibilidad de íconos de medios de pago.</td></tr><tr><td><code>Patrocinadores</code></td><td>Checkbox</td><td>Muestra/Oculta los logos de los patrocinadores.</td></tr><tr><td><code>Redes sociales</code></td><td>Checkbox</td><td>Activa/Desactiva íconos con enlaces a redes sociales oficiales.</td></tr><tr><td><code>Virtualsoft</code></td><td>Checkbox</td><td>Habilita/Desabilita la marca/logo de la plataforma.</td></tr><tr><td><code>Mostrar +18</code></td><td>Checkbox</td><td>Muestra/Oculta ícono de restricción de edad.</td></tr><tr><td><code>Licencia de Curazao</code></td><td>Checkbox</td><td>Activa/desactiva la visibilidad de la información sobre la licencia de Curazao en el pie de página.</td></tr></tbody></table>

***

## **📖 4. Libro de reclamaciones**

Configura un botón/enlace con imagen personalizada que dirige al libro de reclamaciones.

<table><thead><tr><th width="70.4814453125">icono</th><th width="205.40740966796875">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><div><figure><img src="../../../.gitbook/assets/image (96).png" alt=""><figcaption></figcaption></figure></div></td><td>Activar/Desactivar</td><td><p><strong>Activar:</strong> Permite configurar el libro de reclamaciones en el pie de pagina.</p><p>📌 <em>Nota: Solo se permite agregar una única dirección como destino.</em></p><p></p><p><strong>Desactivar:</strong> Inhabilita el libro de reclamaciones en la sección Footer.</p></td></tr></tbody></table>

<table><thead><tr><th width="110">Campo</th><th width="81.92584228515625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Agregar imagen</code></td><td>Imagen</td><td>Imagen que funciona como enlace.</td></tr><tr><td><code>Insertar dirección</code></td><td>Texto</td><td><p>Direccion interna (<code>/Ruta/sub_ruta</code>)  o</p><p>URL externa (<code>https://ejemplo.com</code>).</p></td></tr></tbody></table>

***

## 🧷 5. Enlace de Descarga **de APK**

Agrega el enlace directo al APK. Se mostrará en el footer para su descarga.

<table><thead><tr><th width="94.18511962890625">Campo</th><th width="108.888916015625">Tipo</th><th>Descripcion</th></tr></thead><tbody><tr><td><code>URL</code></td><td>URL </td><td>Direccion (<code>https://</code>) directa para la descarga.</td></tr></tbody></table>

***

## ⚙️6. Configuración de contenido

### 🔽 6.1. **Menú**

Permite configurar títulos y subtítulos con enlaces a secciones internas o externas.

<table><thead><tr><th width="59.66668701171875">Icono</th><th width="94.5556640625">Acción</th><th width="580.9998779296875" valign="middle">Descripcion</th></tr></thead><tbody><tr><td><div><figure><img src="../../../.gitbook/assets/image (261).png" alt=""><figcaption></figcaption></figure></div></td><td>Agregar elemento</td><td valign="middle"><p>Crea un título principal de menú.</p><ul><li>En el campo <code>Tipo de URL</code> solo se permite seleccionar una única opción.</li></ul></td></tr></tbody></table>

<table><thead><tr><th width="111.185302734375" valign="middle">Campo</th><th>Descripcion</th></tr></thead><tbody><tr><td valign="middle"><code>Titulo</code></td><td>Nombre que identifica el menu.</td></tr><tr><td valign="middle"><code>Eliminar</code></td><td>Borra el menú.</td></tr><tr><td valign="middle"><code>Agregar subtitulo</code></td><td>Añade subcategorias.</td></tr></tbody></table>

<table><thead><tr><th width="105.72216796875">Campo</th><th width="83.35186767578125">Tipo</th><th>Descripcion</th></tr></thead><tbody><tr><td><code>Menú ID</code></td><td>Texto</td><td>Define identificador unico del menu.</td></tr><tr><td><code>Título</code></td><td>Texto</td><td>Nombre visible.</td></tr><tr><td><code>URL de redirección</code></td><td>Texto</td><td>Direccion interna o externa.</td></tr><tr><td><code>Tipo de URL</code></td><td>Radio Button</td><td><ul><li><strong>Absoluta</strong>: URL completa de la web (<code>https://ejemplo.com</code>).</li><li><strong>relativa</strong>: ruta del sitio (<code>/Ruta/sub_ruta</code>).</li></ul></td></tr><tr><td><code>Eliminar</code></td><td>Button</td><td>Borra ítems del menú.</td></tr></tbody></table>

***

### 💳 6.2. Pasarelas de pago

Administra qué pasarelas se muestran en el footer.

<table><thead><tr><th width="109.74066162109375">Campo</th><th width="118.00006103515625">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Orden</code></td><td>Numerico</td><td>Posición en la lista.</td></tr><tr><td><code>Icono</code></td><td>Imagen</td><td>Imagen de la pasarela.</td></tr><tr><td><code>Título</code></td><td>Texto</td><td> Nombre visible.</td></tr><tr><td><code>Activar</code></td><td>Checkbox </td><td> habilitar/deshabilitar pasarela.</td></tr><tr><td><code>Eliminar</code></td><td>Button</td><td> Botón para remover pasarela.</td></tr></tbody></table>

***

### 🏢6.&#x33;**. Proveedores**

Gestion de los campos a los proveedores

<table><thead><tr><th width="58.99993896484375" align="center" valign="middle">icono</th><th width="95.3333740234375" valign="middle">Acción</th><th>descripción</th></tr></thead><tbody><tr><td align="center" valign="middle"><div><figure><img src="../../../.gitbook/assets/image (269).png" alt="" width="72"><figcaption></figcaption></figure></div></td><td valign="middle">Agregar</td><td>Para agregar un nuevo proveedor</td></tr></tbody></table>

<table><thead><tr><th width="134.88897705078125">Campo</th><th width="158.09259033203125">Tipo</th><th>descripción</th></tr></thead><tbody><tr><td><code>Orden</code></td><td>Numerico</td><td>Posición.</td></tr><tr><td><code>Icono</code></td><td>Imagen</td><td>Imagen representativa.</td></tr><tr><td><code>Título</code></td><td>Texto</td><td>Nombre del proveedor.</td></tr><tr><td><code>Alto/Ancho</code></td><td>Numerico</td><td>Dimensiones de la imagen.</td></tr><tr><td><code>Redirección</code></td><td>URL</td><td>Enlace destino.</td></tr><tr><td><code>Activar</code></td><td>Checkbox</td><td>Mostrar/Ocultar proveedor.</td></tr><tr><td><code>Eliminar</code></td><td>Button</td><td>Borra el proveedor.</td></tr><tr><td></td><td></td><td></td></tr></tbody></table>

***

## 🕒 7. Control de Versiones

<table><thead><tr><th>Versión</th><th>Fecha</th><th data-type="users" data-multiple>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>03/07/2025</td><td><a href="https://app.gitbook.com/u/QNLawjQjAmOHwajEjd48cer1Xpq2">david.velasquez</a></td><td>Documento inicial</td></tr></tbody></table>



