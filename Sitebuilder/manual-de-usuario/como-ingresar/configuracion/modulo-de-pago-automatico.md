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

# Módulo de pago automático

<mark style="color:$info;">Permite administrar las pasarelas</mark> <mark style="color:$info;"></mark>_<mark style="color:$info;">(Subproveedor)</mark>_ <mark style="color:$info;"></mark><mark style="color:$info;">de pago automático, estableciendo reglas y condiciones para la ejecución de retiros de forma automática.</mark>

{% hint style="warning" %}
**Nota:** El acceso a este módulo requiere permisos específicos de **visualización** y **edición**. En caso de no contar con los permisos necesarios, el módulo no será visible o no permitirá realizar modificaciones. Para solicitar acceso, comuníquese con el área de soporte.
{% endhint %}

### 1. Acceso al Módulo

**Ruta de acceso**: Site Builder > Partner > Configuración > Módulo de pago automático

***

### 2. **Configuraciones previas.**

Para modificar y acceder a la configuración de las reglas del Módulo de pago automático, es necesario contar con la siguiente configuración. Esta se realiza a través de un pop-up que se despliega al seguir la ruta de acceso indicada al módulo.

<table><thead><tr><th width="207.55560302734375">Parámetro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País para el cual se realizará la configuración.</td></tr></tbody></table>

***

### 3. Visualización General.

<figure><img src="../../../.gitbook/assets/image (394).png" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Módulo de pago automático.</p></figcaption></figure>

***

### **4.** Acciones disponibles en el Módulo

En esta sección se podrán realizar las configuraciones correspondientes a las pasarelas de retiro _(subproveedores)_ de la plataforma de usuarios online.

<table><thead><tr><th width="112.09088134765625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="modulo-de-pago-automatico.md#id-6.-como-editar-una-pasarela-subproveedor-de-retiro"><img src="../../../.gitbook/assets/Button (1) (1).png" alt="" data-size="original"></a></td><td>Despliega un pop-up que permite modificar la configuración de la pasarela <em>(Subproveedor)</em>. Esta opción está disponible únicamente para usuarios con permisos de edición y cuando la pasarela se encuentra activa en la plataforma de usuarios online.</td></tr><tr><td><a href="modulo-de-pago-automatico.md#id-6.-como-editar-una-pasarela-de-retiro"><img src="../../../.gitbook/assets/Button (6).png" alt=""></a></td><td>Despliega un pop up que Permite visualizar la configuración de la pasarela (<em>Subproveedor)</em> en modo de solo lectura, sin posibilidad de realizar cambios. La información se presenta en un pop-up con los mismos campos de la opción de edición, pero deshabilitados y con fines únicamente informativos.</td></tr><tr><td><img src="../../../.gitbook/assets/Activa-inactiva (1).png" alt=""><br><img src="../../../.gitbook/assets/Activa-inactiva (1) (3).png" alt=""></td><td><p>Permite habilitar o deshabilitar la pasarela <em>(Subproveedor)</em> para su uso en pagos automáticos. Esta acción requiere autenticación mediante token, el cual es el mismo utilizado en backoffice. En caso de no contar con acceso, deberá solicitarlo al área de soporte.</p><p>Al activar una pasarela <em>(Subproveedor)</em>, esta se ubica en la última posición de prioridad disponible. Al inactivarla, se deshabilita para la operación automática.</p><div data-gb-custom-block data-tag="hint" data-style="warning" class="hint hint-warning"><p><strong>Nota:</strong> El estado activo/inactivo en este módulo hace referencia únicamente a la disponibilidad de la pasarela <em>(Subproveedor)</em> para pagos automáticos, no al estado general de la pasarela <em>(Subproveedor)</em> en el sistema.</p></div></td></tr><tr><td>       <img src="../../../.gitbook/assets/Frame 1321316608 (1).png" alt=""></td><td>Permite reorganizar la prioridad de las pasarelas <em>(Subproveedor)</em> mediante arrastrar y soltar la tarjeta hacia arriba o hacia abajo. El orden definido corresponde a la prioridad utilizada por el sistema para procesar los pagos automáticos.</td></tr></tbody></table>

***

### 5. Información Inicial

La pantalla inicial muestra las pasarelas _(Subproveedor)_ disponibles en la plataforma en formato de tarjetas _(Cards)_, presentando información operativa y de estado para su consulta. Esta información es únicamente informativa y permite visualizar la configuración actual y la prioridad de cada pasarela.

{% hint style="warning" %}
**Nota:** Si un usuario solicita un retiro a través de una pasarela _(Subproveedor)_ específica y esta no se encuentra disponible, el sistema intentará procesarlo utilizando la siguiente pasarela _(Subproveedor)_ según el orden de prioridad configurado en este módulo. La prioridad se determina de forma secuencial, iniciando por la pasarela _(Subproveedor)_ ubicada en la primera posición y continuando con las siguientes. Este proceso se repetirá hasta que el pago sea procesado exitosamente. En caso de no ser posible completar el pago de forma automática, el retiro deberá gestionarse manualmente.
{% endhint %}

<table><thead><tr><th width="168.54547119140625">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Imagen</code></strong></td><td>Logo o imagen representativa de la pasarela <em>(Subproveedor)</em>.</td></tr><tr><td><strong><code>Nombre de la pasarela</code></strong></td><td>Muestra el nombre de la pasarela configurada para pagos. </td></tr><tr><td><strong><code>Estado</code></strong></td><td>Indica si la pasarela <em>(Subproveedor)</em> se encuentra activa o inactiva para su uso en pagos automáticos.</td></tr><tr><td><strong><code>Prioridad</code></strong></td><td>Muestra el orden de prioridad en el que el sistema evaluará las pasarelas para procesar los pagos automáticos. Se intentará realizar la transacción utilizando la primera pasarela de la lista. Si esta no se encuentra disponible o ha alcanzado el límite de retiros configurado, se evaluará la siguiente pasarela según el orden establecido, repitiendo este proceso hasta encontrar una opción disponible para procesar la transacción.</td></tr><tr><td><strong><code>Monto enviado</code></strong></td><td>Muestra el valor total de los retiros enviados al proveedor para su procesamiento.</td></tr><tr><td><strong><code>Retiros enviados</code></strong></td><td>Indica la cantidad de retiros enviados al proveedor.</td></tr><tr><td><strong><code>Tope diario</code></strong></td><td>Muestra el monto máximo configurado para procesar pagos automáticos durante el día.</td></tr><tr><td><strong><code>Monto restante</code></strong></td><td>Indica el valor disponible del tope diario. Se calcula como la diferencia entre el tope diario y el monto enviado.</td></tr><tr><td><strong><code>Barra de progreso</code></strong></td><td>Representa visualmente el consumo del tope diario, permitiendo identificar el monto utilizado frente al disponible.</td></tr></tbody></table>

***

### 6. ¿Como editar una pasarela _(Subproveedor)_ de retiro?

{% hint style="warning" %}
**Nota:** Los campos marcados con _(\*)_ son obligatorios para completar la configuración.
{% endhint %}

<table><thead><tr><th width="154.54541015625">Campo</th><th>Descripción</th><th width="103.4544677734375">Editable</th></tr></thead><tbody><tr><td><strong><code>Paga retiros aprobados automáticamente</code></strong></td><td>Permite habilitar o deshabilitar el procesamiento automático de retiros aprobados por el sistema. La ejecución del pago automático dependerá de las configuraciones definidas en el módulo de <a data-mention href="puntaje-de-riesgo..md">puntaje-de-riesgo..md</a>; en caso de que el retiro no cumpla dichas condiciones, deberá ser gestionado de forma manual.</td><td>✅</td></tr><tr><td><strong><code>Paga retiros aprobados manualmente</code></strong></td><td>Habilita o deshabilita el procesamiento de retiros aprobados manualmente por un operador en el Módulo <a data-mention href="https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/financiero/solicitudes-de-retiro">Solicitudes de Retiro</a> . Puede activarse de forma independiente o junto con la opción automática.</td><td>✅</td></tr><tr><td><strong><code>Monto mínimo</code></strong></td><td>Define el valor mínimo requerido para que un retiro pueda ser procesado por la pasarela <em>(Subproveedor)</em> . <em>(Debe ser mayor a cero y no puede superar el monto máximo configurado)</em>.</td><td>✅</td></tr><tr><td><strong><code>Monto máximo</code></strong></td><td>Valor máximo permitido para procesar un retiro. <em>(Debe ser mayor a cero y no puede ser inferior al monto mínimo configurado).</em></td><td>✅</td></tr><tr><td><strong><code>Tope diario</code></strong></td><td>Establece el monto máximo total que la pasarela <em>(Subproveedor)</em> puede procesar en pagos automáticos durante el día.</td><td>✅</td></tr><tr><td><strong><code>Monto utilizado</code></strong></td><td>Indica el valor acumulado de los retiros enviados a la pasarela <em>(Subproveedor)</em> durante el día. Este valor es calculado automáticamente por el sistema.</td><td>❌</td></tr><tr><td><strong><code>Monto restante</code></strong></td><td>Indica el valor disponible restante del tope diario. Se calcula automáticamente como la diferencia entre el tope diario y el monto utilizado.</td><td>❌</td></tr><tr><td><strong><code>Hora de inicio</code></strong></td><td>Define la hora desde la cual la pasarela <em>(Subproveedor)</em> estará habilitada para procesar pagos automáticos. Es un campo obligatorio.</td><td>✅</td></tr><tr><td><strong><code>Hora de finalización</code></strong></td><td>Define la hora límite hasta la cual la pasarela podrá procesar pagos automáticos. <em>(Es obligatorio y debe ser posterior a la hora de inicio)</em>.</td><td>✅</td></tr><tr><td><strong><code>Guardar configuración</code></strong></td><td>Permite guardar los cambios realizados en la configuración de la pasarela <em>(Subproveedor)</em> . El sistema valida la información ingresada y solicita un token de autenticación para confirmar la acción.</td><td>N/A</td></tr><tr><td><strong><code>Cancelar</code></strong></td><td>Cierra la ventana de configuración sin guardar los cambios realizados.</td><td>N/A</td></tr></tbody></table>

***

### 7. Validaciones y reglas del negocio:

* El campo **Monto mínimo** no puede ser mayor al **Monto máximo**.
* Los valores de monto deben ser mayores a cero.
* La **Hora de inicio** no puede ser posterior a la **Hora de finalización**.
* Todos los campos de configuración son obligatorios para guardar.
* Solo se procesan pagos automáticos con pasarelas activas, configuradas y con disponibilidad.
* El sistema utiliza la pasarela con mayor prioridad que cumpla las condiciones.
* Si una pasarela falla, el sistema intenta con la siguiente según prioridad.
* Si se alcanza el tope diario, la pasarela queda inhabilitada hasta el día siguiente.
* La activación, inactivación y guardado requieren token de autenticación.
* Para activar una pasarela, primero debe habilitar el producto desde la sección [Habilitación productos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos-2/habilitacion-productos "mention") y posteriormente realizar la activación desde la opción correspondiente de [Activación Productos.](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/herramientas/partner-ajustes/productos-2/activacion-productos. "mention")

***

### 8. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="107">Versión</th><th width="141">Fecha</th><th width="134">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>20/04/2026</td><td>Karol Navia</td><td>Creación del manual del Módulo de Pago Automático</td></tr></tbody></table>

</details>
