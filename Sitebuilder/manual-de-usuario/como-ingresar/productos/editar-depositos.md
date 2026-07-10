---
description: >-
  Esta sección permite agregar y modificar los métodos de depósito en la
  plataforma de usuarios online
---

# Editar depósitos

{% hint style="danger" %}
**Nota importante**: Esta configuración solo aplica para la visual antigua de depósitos en usuarios online.
{% endhint %}

### **1. Acceso al Módulo**

**Ruta:** Site Builder > Partner > Productos > Editar depósitos

***

### **2. Visualización**

<figure><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2FywsloFJVhnuB3QuvvPGB%2Fimage.png?alt=media&#x26;token=60f2124b-4639-4212-9844-60941e75cd74" alt="Captura de pantalla Editar depósitos"><figcaption><p>Figura #1: Captura de pantalla del módulo Editar depósitos.</p></figcaption></figure>

***

#### **2.1. Alcance**

<details>

<summary>Ver resumen del alcance</summary>

Este manual describe las acciones permitidas dentro del módulo **Editar depósitos**: agregar nuevas pasarelas de pago (métodos de depósito), modificar la configuración de depósitos existentes, reordenar la visualización y previsualizar cómo verá el usuario final el medio de depósito.

**Incluye:**

* Instrucciones para configurar parámetros generales (Partner y País).
* Descripción de las acciones disponibles (agregar, editar, mover, previsualizar y guardar).
* Recomendaciones y pasos para validar los cambios en la plataforma de usuarios online.

**No incluye:**

* Flujos de procesamiento de pagos ni conciliaciones bancarias.

</details>

***

### **3. Configuraciones generales**

Antes de ingresar a este módulo, es necesario contar con las siguientes configuraciones:

| Parámetro                                                            | Descripción                                     | Configuración sugerida                                       |
| -------------------------------------------------------------------- | ----------------------------------------------- | ------------------------------------------------------------ |
| [Partner](https://virtualsoft.gitbook.io/untitled/glosario/#partner) | Nombre del partner a configurar                 | Seleccionar el partner correspondiente al alcance del cambio |
| País                                                                 | País para el cual se realizará la configuración | Seleccionar el país objetivo                                 |

<details>

<summary>¿Por qué configurar esto primero?</summary>

Para que los cambios se apliquen correctamente debes indicar el **Partner** y el **País** antes de editar. Estas dos variables determinan qué depósitos estarán disponibles y cómo se mostrarán en la plataforma de usuarios online.

</details>

***

### **4. Acciones del usuario**

<table><thead><tr><th width="143.4444580078125">Icono</th><th width="199.77777099609375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><div><figure><img src="../../../.gitbook/assets/image-Photoroom.png" alt="" width="49"><figcaption></figcaption></figure></div></td><td>Agregar depósito</td><td>Despliega un formulario que permite crear una nueva pasarela de pago para que los usuarios puedan realizar depósitos.</td></tr><tr><td><div><figure><img src="../../../.gitbook/assets/image-Photoroom (1).png" alt=""><figcaption></figcaption></figure></div></td><td>Configurar depósito ya creado</td><td>Edita los parámetros de un depósito existente, teniendo en cuenta que todos los parametros son editables.</td></tr><tr><td><div><figure><img src="../../../.gitbook/assets/image-Photoroom (2).png" alt=""><figcaption></figcaption></figure></div></td><td>Mover depósito ya creado</td><td>Cambia el orden de visualización de los depósitos. El orden definido aquí será el mismo que se mostrará en la plataforma de usuarios online.</td></tr><tr><td><div><figure><img src="../../../.gitbook/assets/image-Photoroom (3).png" alt="" width="40"><figcaption></figcaption></figure></div></td><td>Eliminar método de pago</td><td>Elimina el método de pago creado, es necesario confirmar esta acción desde un pop-up.</td></tr><tr><td><strong>Botón "Previsualizar"</strong></td><td>Previsualizar</td><td>Muestra un pop-up con la vista que verá el usuario al seleccionar este medio de depósito.</td></tr><tr><td><strong>Botón "Guardar"</strong></td><td>Guardar cambios</td><td>Aplica las modificaciones en la plataforma de usuarios online. </td></tr></tbody></table>

{% hint style="warning" %}
Nota Los cambios pueden tardar aproximadamente 20 minutos en reflejarse.
{% endhint %}

***

### **5. Formularios para crear o editar depósitos**

{% tabs %}
{% tab title="Pasarela de pago" %}
Este formulario configura la pasarela de pago que verá el usuario en el menú de métodos de depósito.

| Campo                     | Descripción                                                          |
| ------------------------- | -------------------------------------------------------------------- |
| `Subir imagen*`           | Imagen que visualizará el usuario en el menú de métodos de depósito. |
| `Monto mínimo`            | Monto mínimo permitido para depósitos con esta pasarela.             |
| `Monto máximo`            | Monto máximo permitido para depósitos con esta pasarela.             |
| `Nombre*`                 | Nombre identificativo de la pasarela de pago.                        |
| `Tiempo de procesamiento` | Tiempo estimado para que el banco procese la transacción.            |
| `Monto por defecto*`      | Monto preseleccionado por defecto al elegir esta pasarela.           |

**Reglas y recomendaciones:**

* Los campos marcados con (\*) son obligatorios; si no se completan, no será posible guardar el depósito.
* Usa **Cancelar** para cerrar el formulario sin aplicar cambios.
* Usa **Guardar** para almacenar los cambios en el formulario (esto no publica los cambios en usuarios online).
* La imagen debe tener un tamaño máximo de 224x224 píxeles, formato PNG y un peso máximo de 200 KB.
{% endtab %}

{% tab title="Pop-up" %}
Este formulario define el contenido que se muestra en el pop-up al seleccionar un método de depósito.

| Campo                | Descripción                                                                                                                                            |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `Subir imagen*`      | Imagen que verá el usuario al abrir el pop-up del método de depósito.                                                                                  |
| `Texto informativo*` | Utiliza un editor de texto con barra de herramientas que permite personalizar el texto dirigido al usuario luego de seleccionar el método de deposito. |

**Reglas y recomendaciones:**

* Los campos marcados con (\*) son obligatorios; si no se completan, no será posible guardar el depósito.
* Usa **Cancelar** para cerrar el formulario sin aplicar cambios.
* Usa **Guardar** para almacenar los cambios en el formulario (esto no publica los cambios en usuarios online).
* La imagen debe tener un tamaño máximo de 224x224 píxeles, formato PNG y un peso máximo de 200 KB.
{% endtab %}
{% endtabs %}

***

### **6. Gestión de permisos, usuarios y roles**

Para acceder a este módulo es necesario contar con un permiso específico asignado.\
Si el módulo **Editar depósitos** no está visible en el menú, solicita al equipo de soporte que te asigne el permiso correspondiente.

***

### **7. Recomendaciones sobre la configuración**

Siempre que realices cambios:

* Haz clic en **Guardar** en la parte inferior del módulo.
* Ten en cuenta que los cambios pueden tardar unos 20 minutos en propagarse a la plataforma de usuarios online.
* Verifica que el **Partner** y el **País** seleccionados sean los correctos antes de guardar.

***

### **8. Validación de configuraciones**

<details>

<summary>Cómo validar los cambios</summary>

Los cambios se verifican directamente en la **plataforma de usuarios online**, en la sección **Depósitos.**.

**Checklist de validación**:

1. Seleccionar el **País** correcto en el módulo "Editar depósitos".
2. Usar **Previsualizar** para comprobar:
   * Texto
   * Logos e imágenes cargadas.
3. Si la previsualización es correcta, hacer clic en **Guardar (El botón de la seccion principal)**.
4. Esperar aproximadamente 20  para que se apliquen los cambios.
5. Revisar en la plataforma de usuarios online (Usuarios online → Depósitos) que el depósito aparezca con la nueva configuración.

**Consejos**:

* Si modificas el orden, confirma que la lista en la plataforma coincida con el orden definido.
* Si notas diferencias, revisa nuevamente que **Partner** y **País** sean correctos y repite la previsualización.

</details>

***

### **9. Recursos relacionados**

{% content-ref url="https://app.gitbook.com/s/yyrHDz69FZMnpZ9NBm8u/usuarios-online/manual-de-plataforma/depositos" %}
[Depósitos](https://app.gitbook.com/s/yyrHDz69FZMnpZ9NBm8u/usuarios-online/manual-de-plataforma/depositos)
{% endcontent-ref %}

***

### **10. Control de versiones**

| Versión | Fecha      | Autor         | Cambios realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 2025-08-08 | Ronald Peláez | Documento inicial  |
