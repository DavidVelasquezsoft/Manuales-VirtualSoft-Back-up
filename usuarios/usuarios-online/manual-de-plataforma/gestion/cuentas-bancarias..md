---
description: Permite añadir y gestionar las cuentas bancarias registradas por los usuarios.
---

# Cuentas Bancarias.

### 1. Acceso al Módulo:

**Ruta de Acceso**: Menú principal > Gestión > Cuentas Bancarias

***

### 2. Visualización:

<figure><img src="../../../.gitbook/assets/image (26) (2).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Cuentas bancarias.</p></figcaption></figure>

### **3. Acciones del Usuario**

<table><thead><tr><th width="215.4000244140625">Sección</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Agregar cuenta bancaria</strong></td><td>Permite registrar una nueva cuenta llenando los campos requeridos.</td></tr><tr><td><strong>Estado</strong></td><td>Permite filtrar las cuentas bancarias mostradas según su estado (por ejemplo: activa o inactiva).</td></tr><tr><td><strong>Tabla de cuentas bancarias</strong></td><td>Permite visualizar la información registrada de cada cuenta.</td></tr></tbody></table>

#### **3.1. Campos del formulario de cuenta bancaria:**

Los campos de este formulario pueden modificarse desde el Site Builder, desde el apartado [**Formularios.**](https://virtualsoft.gitbook.io/manuales/sitebuilder/manual-de-usuario/como-ingresar/apariencia/formularios)

<table><thead><tr><th width="136">Campo</th><th width="146">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre de usuario</code></strong></td><td>Campo de texto (no editable)</td><td>Muestra el nombre del usuario.</td></tr><tr><td><strong><code>Banco</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el banco asociado a la cuenta bancaria.</td></tr><tr><td><strong><code>Confirmar banco</code></strong></td><td>Lista desplegable</td><td>Se debe volver a seleccionar el banco para confirmar que la información es correcta.</td></tr><tr><td><strong><code>Tipo de cuenta</code></strong></td><td>Lista desplegable</td><td>Define el tipo de cuenta bancaria <em>(Ejemplo: Ahorros)</em>.</td></tr><tr><td><strong><code>Tipo de cliente</code></strong></td><td>Campo de texto (no editable)</td><td>Indica el tipo de cliente registrado <em>(Ejemplo: personal)</em>.</td></tr><tr><td><strong><code>Número de cuenta</code></strong></td><td>Numérico</td><td>Permite ingresar el número de cuenta bancaria.</td></tr><tr><td><strong><code>Confirmar número de cuenta</code></strong></td><td>Numérico</td><td>Se debe volver a ingresar el número de cuenta para validarlo y evitar errores.</td></tr></tbody></table>

{% hint style="warning" %}
**Nota**:

Dependiendo de la configuración establecida en la opción “[Validar cuentas bancarias únicas por usuario](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion/ajustes-generales)”, si esta se encuentra activada, el sistema restringirá el registro de cuentas bancarias repetidas para los usuarios. En este caso, se realizarán las validaciones necesarias al registrar una cuenta bancaria.

*   Si la cuenta ya pertenece a otro usuario, aparecerá el mensaje:

    > “**Esta cuenta bancaria ya está asociada a otro usuario. Por favor, ingresa una cuenta diferente**.”
*   Si la cuenta no existe en otro perfil, el sistema permitirá el registro y mostrará:

    > “**Cuenta bancaria guardada satisfactoriamente**.”
{% endhint %}

#### **3.2. Columnas de la tabla de cuentas bancarias:**

En esta tabla se pueden consultar y gestionar las cuentas bancarias registradas.

<table><thead><tr><th width="179.5999755859375">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Banco</code></strong></td><td>Nombre del banco asociado a la cuenta.</td></tr><tr><td><strong><code>Cuenta</code></strong></td><td>Número de cuenta registrado.</td></tr><tr><td><strong><code>Código interbancario</code></strong></td><td>Código proporcionado por el banco para transferencias.</td></tr><tr><td><strong><code>Tipo de cuenta</code></strong></td><td>Tipo de cuenta seleccionada</td></tr><tr><td><strong><code>Tipo de cliente</code></strong></td><td>Tipo de cliente registrado <em>(Ejemplo: persona)</em>.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Estado actual de la cuenta (activa o inactiva).</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda asociada a la cuenta bancaria.</td></tr><tr><td><strong><code>Anular</code></strong></td><td>Opción para elimina la cuenta.</td></tr></tbody></table>

***

### **4. Validaciones y Reglas de Negocio**

* El campo "**Tipo de cliente**" no puede ser editado por el usuario.
* Todos los campos marcados como "**Confirmar**" deben coincidir con el valor original ingresado.
* El botón "**Aceptar**" sólo se habilita si los campos requeridos están correctamente diligenciados.
* Este módulo puede presentar diferentes comportamientos según las configuraciones realizadas desde el módulo [partner ajustes en BackOffice](https://virtualsoft.gitbook.io/manuales/manual-de-usuario-backoffice/herramientas/partner-ajustes/configuracion-1).

***

### **5. Control de Versiones**

<details>

<summary>🕛Historial de versiones</summary>

| Versión | Fecha      | Autor         | Cambios Realizados                 |
| ------- | ---------- | ------------- | ---------------------------------- |
| 1.0     | 22/07/2025 | Ronald Pelaez | Documento inicial                  |
| 1.1     | 10/11/2025 | Karol Navia   | Reestructuración de todo el manual |

</details>
