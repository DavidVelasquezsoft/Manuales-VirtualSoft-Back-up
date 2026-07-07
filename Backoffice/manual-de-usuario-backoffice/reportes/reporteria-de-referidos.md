# Reportería de Referidos

### Configuración general

#### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Reportes > Reporte de Referidos

***

#### 2. Visualización:

<figure><img src="../../.gitbook/assets/image (62).png" alt=""><figcaption><p>Figura#1: Captura de pantalla reporte de referidos.</p></figcaption></figure>

**🧑‍💻 3. Acciones del Usuario**

<table><thead><tr><th width="158.09088134765625">Sección</th><th width="151">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id Referente</code></strong></td><td>Campo de texto</td><td>Permite consultar la información de un referente específico mediante su identificador único.</td></tr><tr><td><strong><code>Id Referido</code></strong></td><td>Campo de texto</td><td> consulta la información de un referido específico mediante su identificador único.</td></tr><tr><td><strong><code>Fecha de Registro</code></strong></td><td>Campo de fecha</td><td>Filtra la búsqueda por fecha de registro del referente o referido.</td></tr><tr><td><strong><code>Fecha de Primer Depósito</code></strong></td><td>Campo de fecha</td><td>Filtra la búsqueda por la fecha en que se efectuó el primer depósito.</td></tr><tr><td><strong><code>País</code></strong></td><td>Dropdown</td><td>Selecciona el país sobre el cual se desea realizar la consulta.</td></tr><tr><td><strong><code>Estado de Referido</code></strong></td><td>Dropdown</td><td>Permite seleccionar si el referido está Activo o Inactivo.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Dropdown</td><td><p>Define el tipo de consulta:</p><ul><li>Totales: información de referentes.</li><li>Detallado: el Id del referente es obligatorio.</li></ul></td></tr><tr><td><strong><code>Consultar</code></strong></td><td>Botón</td><td>Ejecuta la búsqueda de acuerdo con los filtros ingresados.</td></tr><tr><td><strong><code>Limpiar</code></strong></td><td>Botón</td><td>Elimina los valores ingresados en los campos y restablece la vista inicial.</td></tr></tbody></table>



4. **Tabla de resultados**

{% tabs %}
{% tab title="Tipo totales" %}
## Tipo Totales - Información de Referentes

Después de realizar la consulta, se presentará la siguiente tabla que contiene información sobre los referentes.

<table><thead><tr><th width="197">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Referente</code></strong></td><td>Identificadores de los referentes. Si se especifica una consulta, los resultados se mostrarán de acuerdo con la misma.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre del referente correspondientes a la consulta realizada.</td></tr><tr><td><strong><code>Referidos Totales</code></strong></td><td>Cantidad de referidos que han completado exitosamente el registro en la página de usuarios online utilizando el link enviado por el referente (por correo o compartido directamente).</td></tr><tr><td><strong><code>Referidos Exitosos</code></strong></td><td>Número de referidos que han acreditado al menos un premio para el referente.</td></tr><tr><td><strong><code>Bonos por Depósito</code></strong></td><td>Total de bonos que el referente puede reclamar o ya ha reclamado, como resultado del cumplimiento de la condición <strong>“Mínimo primer depósito”</strong> por parte de sus referidos.</td></tr><tr><td><strong><code>Bonos por Apuesta</code></strong></td><td>Total de bonos que el referente puede reclamar o ya ha reclamado, como resultado del cumplimiento de la condición <strong>“Mínimo valor en apuestas”</strong> por parte de sus referidos.</td></tr></tbody></table>
{% endtab %}

{% tab title="Tipo detallado" %}
## Información de Referido

Después de hacer clic en **"Consultar"**,  una tabla con la siguiente información sobre los referidos del referente consultado.

<table><thead><tr><th width="182">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Referido</code></strong></td><td>Muestra los identificadores de los referidos registrados en la página. </td></tr><tr><td><strong><code>Fecha de Registro</code></strong></td><td>Fecha y hora en que el referido realizó el registro en la página de usuarios online.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Nombre del referido tal como se registró en la plataforma.</td></tr><tr><td><strong><code>Apellido</code></strong></td><td>Apellido del referido tal como se registró en la página.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Indica el estado del referido: <strong>Activo</strong> (con acceso a la plataforma) o <strong>Desactivado</strong> (sin acceso).</td></tr><tr><td><strong><code>Último Login</code></strong></td><td>Fecha en la que el referido realizó su último inicio de sesión en la página.</td></tr><tr><td><strong><code>Referente</code></strong></td><td>ID del referente que envió la invitación al usuario.</td></tr><tr><td><strong><code>Primer Depósito</code></strong></td><td>Fecha y hora en que el referido efectuó su primer depósito en la plataforma.</td></tr><tr><td><strong><code>Valor Primer Depósito</code></strong></td><td>Monto del primer depósito realizado por el referido.</td></tr><tr><td><strong><code>Valor Apuestas Deportivas</code></strong></td><td>Total de las apuestas realizadas en la vertical de <strong>Deportes</strong> por el referido.</td></tr><tr><td><strong><code>Última Apuesta Deportiva</code></strong></td><td>Fecha de la última apuesta realizada en la sección de <strong>Deportes</strong>.</td></tr><tr><td><strong><code>Valor Apuesta Casino</code></strong></td><td>Total de las apuestas realizadas en la sección de <strong>Casino</strong>.</td></tr><tr><td><strong><code>Última Apuesta Casino</code></strong></td><td>Fecha de la última apuesta realizada en la sección de <strong>Casino</strong>.</td></tr><tr><td><strong><code>Premio Primer Depósito</code></strong></td><td>Indica si el referido generó un premio para el referente al realizar el primer depósito. Puede mostrarse <strong>“Generó premio”</strong> o <strong>“No ha generado premio”</strong>.</td></tr><tr><td><strong><code>Premio Apuestas</code></strong></td><td>Especifica si el referido generó un premio para el referente al realizar apuestas. Puede mostrarse <strong>“Generó premio”</strong> o <strong>“No ha generado premio”</strong>.</td></tr><tr><td><strong><code>Total Referidos</code></strong></td><td>Número total de referidos que tiene el usuario (un referido que también actúa como referente con sus propios invitados).</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

**✅ 5. Validaciones y Reglas de Negocio**

* Si se ejecuta la consulta sin llenar campos y seleccionando únicamente el tipo "Totales", el sistema mostrará todos los registros existentes.
* El campo **Id Referente** es obligatorio para consultar información de tipo "Detallado".
* Los premios asociados dependen del cumplimiento de condiciones de depósito y apuestas por parte del referido.

***

**🕒 6. Control de Versiones**

| Versión | Fecha      | Autor       | Cambios Realizados |
| ------- | ---------- | ----------- | ------------------ |
| 1.0     | 21/08/2025 | Karol Navia | Documento inicial  |
