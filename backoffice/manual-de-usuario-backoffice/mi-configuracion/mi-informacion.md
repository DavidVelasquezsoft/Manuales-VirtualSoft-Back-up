---
description: >-
  Se organizan los datos en tres áreas principales: Datos Principales, Datos del
  Agente y Datos de Configuración, cada una con información específica sobre tu
  cuenta y su funcionamiento.
---

# Mi Información

### 1. Acceso al Módulo:

**Ruta de Acceso**: BackOffice > Mi configuración > Mi Información.

***

### 2. Visualización:

<figure><img src="https://1262136405-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FUadX6RX6l8fMhEZxOqcT%2Fuploads%2FoCxzs32A5i9v9VpCYgcB%2Fimage.png?alt=media&#x26;token=4b1750e3-3c8c-43e4-bfba-2ee7918b17ad" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Mi Información.</p></figcaption></figure>

### **3. Acciones del Usuario**

Dentro de esta sección encontrarás tus datos organizados en tres áreas principales.

{% hint style="warning" %}
**Nota**: Los siguientes campos no son editables; su función es únicamente informativa.
{% endhint %}

***

{% tabs %}
{% tab title="3.1 . Datos Principales" %}
<table><thead><tr><th width="160">Campo</th><th width="105">Tipo de Control</th><th width="452">Descripción</th></tr></thead><tbody><tr><td><strong><code>Número de usuario</code></strong></td><td>Texto</td><td>Identificación única dentro del sistema.</td></tr><tr><td><strong><code>Login para acceso</code></strong></td><td>Texto</td><td>Nombre o correo utilizado para iniciar sesión en la plataforma.</td></tr><tr><td><strong><code>Saldo de comisión</code></strong></td><td>Numérico</td><td>Monto acumulado por comisiones generadas.</td></tr><tr><td><strong><code>Última dirección IP</code></strong></td><td>Texto</td><td>Última dirección IP desde la que accediste a la plataforma.</td></tr><tr><td><strong><code>Último usuario modificado</code></strong></td><td>Texto</td><td>Última persona que realizó cambios en tu perfil.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Texto</td><td>Clasificación de la cuenta dentro del sistema.</td></tr><tr><td><strong><code>Estado</code></strong></td><td>Texto</td><td>Indica si la cuenta está activa o inactiva.</td></tr><tr><td><strong><code>Idioma preferido</code></strong></td><td>Texto</td><td>Idioma en el que se muestra la interfaz.</td></tr><tr><td><strong><code>Nombre del usuario</code></strong></td><td>Texto</td><td>Nombre registrado en la cuenta.</td></tr><tr><td><strong><code>País</code></strong></td><td>Texto</td><td>País asociado a la cuenta.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Texto</td><td>Tipo de moneda con la que operas dentro del sistema.</td></tr><tr><td><strong><code>Fecha de creación</code></strong></td><td>Fecha</td><td>Fecha en la que la cuenta fue creada.</td></tr><tr><td><strong><code>Fecha última entrada</code></strong></td><td>Fecha</td><td>Última vez que iniciaste sesión.</td></tr><tr><td><strong><code>Última fecha modificada</code></strong></td><td>Fecha</td><td>Fecha en la que se realizó la última modificación en la cuenta.</td></tr></tbody></table>
{% endtab %}

{% tab title="3.2. Datos del Agente" %}
<table><thead><tr><th width="160">Campo</th><th width="106">Tipo de Control</th><th width="428">Descripción</th></tr></thead><tbody><tr><td><strong><code>Nombre del contacto</code></strong></td><td>Texto</td><td>Nombre del agente o persona de contacto.</td></tr><tr><td><strong><code>Correo electrónico</code></strong></td><td>Texto</td><td>Dirección de correo electrónico del agente registrada.</td></tr><tr><td><strong><code>Descripción</code></strong></td><td>Texto</td><td>Información adicional sobre el agente.</td></tr><tr><td><strong><code>Teléfono</code></strong></td><td>Texto</td><td>Número de contacto del agente.</td></tr><tr><td><strong><code>Concesionario</code></strong></td><td>Texto</td><td>Nombre del concesionario al que pertenece el usuario, en caso de aplicar.</td></tr><tr><td><strong><code>Subconcesionario</code></strong></td><td>Texto</td><td>Nombre del subconcesionario al que pertenece el usuario, en caso de aplicar.</td></tr><tr><td><strong><code>Provincia/Región</code></strong></td><td>Texto</td><td>Ubicación geográfica del agente.</td></tr><tr><td><strong><code>Ciudad</code></strong></td><td>Texto</td><td>Ciudad de residencia del agente.</td></tr><tr><td><strong><code>Dirección</code></strong></td><td>Texto</td><td>Dirección física del agente.</td></tr><tr><td><strong><code>Barrio</code></strong></td><td>Texto</td><td>Zona específica dentro de la ciudad.</td></tr><tr><td><strong><code>IP</code></strong></td><td>Texto</td><td>Dirección IP asociada al agente.</td></tr></tbody></table>
{% endtab %}

{% tab title="3.3. Datos de Configuración" %}
<table><thead><tr><th width="161">Campo</th><th width="106">Tipo de Control</th><th width="428">Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado especial</code></strong></td><td>Texto</td><td>Indica si la cuenta tiene privilegios especiales dentro del sistema. </td></tr><tr><td><strong><code>Pinagent</code></strong></td><td>Texto</td><td>Muestra si el usuario tiene asignado un pin de agente o no.</td></tr><tr><td><strong><code>Bloqueado para ventas</code></strong></td><td>Texto</td><td>Define si el usuario tiene restricción para realizar ventas.</td></tr><tr><td><strong><code>Imprime recibo de caja</code></strong></td><td>Texto</td><td>Indica si la cuenta tiene permisos para generar recibos de caja.</td></tr><tr><td><strong><code>Permite recargas</code></strong></td><td>Texto</td><td>Especifica si la cuenta puede realizar recargas de saldo.</td></tr><tr><td><strong><code>Permite activar registro</code></strong></td><td>Texto</td><td>Define si el usuario tiene la opción de activar nuevos registros.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### **4. Validaciones y Reglas de Negocio**

* Los datos marcados como **No editables** son de solo lectura.
* Los campos automáticos se actualizan sin intervención del usuario.
* Las configuraciones aplicadas afectan directamente el acceso y uso de la cuenta.

***

### **5. Control de Versiones**

<details>

<summary>🔽Historial de versiones</summary>

<table><thead><tr><th width="127">Versión</th><th>Fecha</th><th>Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/08/2025</td><td>Karol Navia</td><td>Documento inicial</td></tr></tbody></table>

</details>
