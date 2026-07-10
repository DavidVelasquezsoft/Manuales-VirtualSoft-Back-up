# Puntaje de riesgo.

Configura las reglas que determinan la aprobación automática de retiros según el nivel de riesgo de cada usuario. Las condiciones definidas en las reglas activas se verifican automáticamente y, si todas se cumplen, el retiro se aprueba; de lo contrario, la solicitud se envía a revisión manual para su validación.

### 1. Acceso al módulo

Ruta: SiteBuilder > Partner > Configuración > Puntaje de riesgo.

{% hint style="warning" %}
**Nota:** Para poder ingresar a este apartado existen dos permisos diferenciados:

* **Permiso de visualización:** permite únicamente consultar las configuraciones actuales.
* **Permiso de gestión:** permite crear, editar o eliminar reglas (requiere validación 2FA).<br>
{% endhint %}

***

### 2. Configuraciones previas

Antes de continuar, deben completarse las configuraciones previas indicadas en la siguiente tabla para garantizar que lo definido en este módulo se aplique correctamente.

<table><thead><tr><th width="158.4444580078125">Configuración</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Idioma</strong></td><td>Idioma por defecto de la plataforma.</td></tr><tr><td><strong>Partner</strong></td><td>Nombre del partner a configurar.</td></tr><tr><td><strong>País</strong></td><td>País para el que aplicarán las configuraciones.</td></tr></tbody></table>

#### ¿Por qué configurar esto primero?

Porque todas las reglas definidas en este módulo se aplican de forma específica a la combinación **Partner + País**. Esto garantiza que cada operación tenga sus propios parámetros de control de riesgo.

***

### 3. Visualización&#x20;

<figure><img src="../../../.gitbook/assets/image (69).png" alt=""><figcaption><p>Figura #1: Captura de pantalla módulo aprobación automática de retiros.</p></figcaption></figure>

***

### 4. Acciones por el usuario

<table><thead><tr><th width="226.22222900390625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Visualizar reglas</strong></td><td>Permite consultar las reglas configuradas para aprobación automática de retiros, según los permisos asignados.</td></tr><tr><td><strong>Establecer reglas para aprobación automática de retiros</strong></td><td>Selecciona el nivel de riesgo del usuario (vacío, bajo, medio, alto) y configura las condiciones bajo las cuales un retiro podrá ser aprobado automáticamente.</td></tr><tr><td><strong>Activar / Desactivar reglas</strong></td><td>Permite habilitar o deshabilitar reglas activas en la plataforma para la aprobación de retiros automáticos.</td></tr></tbody></table>

#### 4.1 Acciones de gestión

Las siguientes acciones solo están disponibles para usuarios con **permiso de gestión** y requieren validación mediante doble [autenticación (2FA)](https://virtualsoft.gitbook.io/untitled/glosario/#autenticacion-2fa) para ser aplicadas:

<table><thead><tr><th width="226">Acción de gestión</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Crear reglas</strong></td><td>Permite definir nuevas reglas de aprobación automática para cada nivel de riesgo. Requiere validación con doble autenticación (2FA).</td></tr><tr><td><strong>Editar reglas</strong></td><td>Modifica reglas ya configuradas. El cambio debe ser confirmado mediante 2FA para aplicarse.</td></tr><tr><td><strong>Eliminar reglas</strong></td><td>Elimina reglas existentes de la plataforma. Solo se completa si el usuario valida con 2FA.</td></tr><tr><td><strong>Activar / Desactivar reglas desde la gestión</strong></td><td>Permite habilitar o deshabilitar reglas a nivel de gestión, con validación de 2FA.</td></tr><tr><td><strong>Confirmar cambios</strong></td><td>Todo cambio realizado debe ser validado mediante 2FA. Si la validación falla o no se completa, los cambios no serán guardados.</td></tr></tbody></table>

{% hint style="warning" %}
**Notas:**&#x20;

* Si la validación 2FA falla o no se completa, los cambios no serán guardados.
* El token de 2FA debe ser el mismo que se utiliza para ingresar a BackOffice.<br>
{% endhint %}

***

### 5. Niveles de Score disponibles.

<table><thead><tr><th width="155">Nivel de riesgo</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#score"><strong>Score</strong></a> <strong>vacío</strong></td><td>Usuarios sin score asignado o partners que no utilizan el módulo de score, las reglas aquí se aplican como generales.</td></tr><tr><td><strong>Score bajo</strong></td><td>Usuarios con bajo nivel de riesgo.</td></tr><tr><td><strong>Score medio</strong></td><td>Usuarios con nivel de riesgo intermedio.</td></tr><tr><td><strong>Score alto</strong></td><td>Usuarios con alto nivel de riesgo.</td></tr></tbody></table>

***

### 6. Proceso para agregar reglas de aprobación automática

{% stepper %}
{% step %}
#### Paso 1 – Selección de Score de Riesgo

Selecciona el nivel de riesgo (Vacío, Bajo, Medio, Alto) para el cual deseas configurar reglas.
{% endstep %}

{% step %}
#### **Paso 2 – Definir si se aplican reglas**

Utiliza la switch **“Activar reglas” (On/Off)**:

* **Off:** Todos los retiros de ese score se aprueban automáticamente sin validación.
* **On:** Habilita la creación de reglas personalizadas.
{% endstep %}

{% step %}
#### **Paso 3 – Crear reglas**

Completa el formulario para establecer condiciones.

<figure><img src="https://2760919989-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOjl0Z2z0C78jMb0KvTb8%2Fuploads%2Fjji3gubZk5maAubl2q2o%2Fimage.png?alt=media&#x26;token=252bb620-2530-48b1-bac8-bde3c2bd58ac" alt=""><figcaption><p>Figura #2: Formulario de configuración de reglas.</p></figcaption></figure>

<table><thead><tr><th width="156">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Monto mínimo de retiro</code></strong></td><td>Valor mínimo para que aplique la regla. <em>(Ejemplo: si se establece en 200, un retiro de 199 no aplicará.)</em></td></tr><tr><td><strong><code>Monto máximo de retiro</code></strong></td><td>Valor máximo permitido por regla. No puede ser menor que el mínimo.</td></tr><tr><td><strong><code>Porcentaje mínimo de rentabilidad</code></strong></td><td>Valor decimal que define la rentabilidad mínima requerida para aprobar un retiro, calculada como <em><strong>(GGR Deportivas + GGR Casino) / Depósitos</strong>.</em></td></tr><tr><td><strong><code>Cantidad mínima de reinversiones de saldo ganado</code></strong></td><td>Valor decimal que indica la actividad mínima de juego requerida para aprobar un retiro, calculada como <em><strong>(Apuestas Deportivas + Apuestas Casino) / Depósitos</strong>.</em></td></tr><tr><td><strong><code>Similitud máxima entre depósito y retiro</code></strong></td><td>Valor decimal (0.00 a 1.00). El retiro solo se aprueba si la similitud calculada es menor o igual a el valor obtenido por esta <strong>Fórmula:</strong> <code>Retiros pagados / Depósitos</code>.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**: Todos los campos son obligatorios para guardar las reglas creadas.
{% endhint %}
{% endstep %}
{% endstepper %}

***

### 7. Flujo de reglas cuando están activas.

{% stepper %}
{% step %}
El sistema identifica la **marca y país** del usuario.
{% endstep %}

{% step %}
Determina el **Score de Riesgo actual** (Bajo, Medio, Alto, Vacío).
{% endstep %}

{% step %}
Busca las reglas configuradas para ese Score.
{% endstep %}

{% step %}
Evalúa

* **Si** “**Activar reglas**” = Off→ el retiro se aprueba automáticamente.
* **Si** “**Activar reglas**” = On→ el sistema valida si el retiro cumple alguna de las reglas activas.
* **Si cumple** → retiro aprobado automáticamente.
* **Si no cumple** → retiro enviado a revisión manual.
{% endstep %}
{% endstepper %}

***

### 8. Validaciones en la creación de reglas

* No se permiten rangos de monto duplicados dentro del mismo Score.
* Cuando se guardan las reglas configuradas se visualizará el siguiente mensaje:\
  `"Configuración de reglas de aprobación automática actualizada correctamente."`
* Cuando se realiza una configuración inválida aparecerá el siguiente mensaje:\
  `"Error en la configuración de la regla. Verifique los valores ingresados."`
* En caso de que un retiro no aplique para aprobación automática, se debe realizar el proceso desde el BackOffice en la sección de solicitudes de [retiro](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/financiero/solicitudes-de-retiro).
* Todas las acciones de gestión requieren validación de **doble autenticación (2FA)**.
* Si el 2FA falla → los cambios no se guardan.
* Toda acción queda registrada en un **log de auditoría** con:
  * Usuario que realizó la acción.
  * Fecha y hora.
  * Parámetros modificados.
  * Confirmación de 2FA exitoso.

***

### 9. Control de Versiones

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="114">Versión</th><th width="147">Fecha</th><th width="152">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>01/10/2025</td><td>Ronald Peláez</td><td>Documento inicial</td></tr></tbody></table>

</details>
