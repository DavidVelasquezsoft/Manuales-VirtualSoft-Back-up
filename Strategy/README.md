---
description: >-
  El presente manual describe el cambio de la plataforma MicroStrategy hacia
  Library y Workstation, así como el nuevo esquema para la creación de tableros
  en Workstation y su visualización en Library.
---

# Transición de plataformas Strategy

### 1. Introducción

La plataforma **MicroStrategy** será reemplazada debido a que **ya no contará con mantenimiento ni actualizaciones**.\
Como alternativa, se implementan **Library** y **Workstation**, plataformas más actuales, seguras y con soporte continuo.

A partir de este cambio:

* **Library** será utilizada por los usuarios para la **visualización de tableros y reportes**.
* **Workstation** será la plataforma para la **creación, gestión y administración de reportes y tableros**.

**Library** funciona como una **herramienta de uso personal**, permitiendo a cada usuario visualizar únicamente los reportes y tableros que **tenga agregados**.\
**Workstation**, por su parte, centraliza la creación y administración de la información y es instalada y configurada **por el administrador**.

***

### 2. Nuevo flujo de uso de plataformas

Los principales cambios en el uso de las plataformas se describen a continuación, con el objetivo de explicar el nuevo flujo de acceso, creación y visualización de reportes.

A partir de esta transacción, los usuarios accederán a diferentes plataformas según el tipo de actividad que realicen.

#### 2.1. Visualización de tableros e informes (_MicroStrategy → Library_)

**Con el cambio de plataforma**, MicroStrategy deja de ser la herramienta para la **visualización de reportes**.\
La consulta de reportes que anteriormente se realizaba en MicroStrategy ahora se efectúa a través de **Library**, que será la nueva plataforma de visualización.

Para ingresar a **Library**, el usuario debe acceder a través de el siguiente enlace:\
\
**Enlace:** [**Reportes Library**](https://reporting.virtualsoft.tech/MicroStrategyLibrary/app)

<details>

<summary>🔽 ¿Cómo acceder a Library?</summary>

Al acceder al enlace, se mostrará la pantalla de **inicio de sesión**, donde el usuario deberá autenticarse con sus credenciales (_Usuario y contraseña_) y presionar el botón **"Iniciar sesión con credenciales**" para ingresar a la plataforma.

<figure><img src=".gitbook/assets/image (23) (1).png" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla login Library</p></figcaption></figure>

Una vez completado el inicio de sesión, el usuario podrá visualizar los reportes disponibles en su **Library personal**.

<figure><img src=".gitbook/assets/image (24) (1).png" alt="" width="563"><figcaption><p>Figura #2: Captura de pantalla inicio Library</p></figcaption></figure>

{% hint style="warning" %}
**Nota:** Los reportes se asignan según el rol del usuario desde el **Workstation** y también pueden agregarse manualmente **mediante el enlace** de un tablero compartido.
{% endhint %}

</details>

#### 2.2. Gestión y administración de reportes (_MicroStrategy → Workstation_)

**Workstation** será la plataforma utilizada para la **creación, gestión y modificación de reportes y tableros**.

Esta aplicación debe ser **instalada y configurada previamente por el administrador**, mediante el administrador de configuración.

El acceso a Workstation está disponible para los siguientes tipos de usuarios:

*   **Usuarios creadores de tableros**

    Son responsables de la creación, modificación y administración de dashboards.\
    Estos usuarios definen el contenido de los tableros y controlan la asignación y visibilidad de la información para los distintos usuarios.
*   **Usuarios administrativos o miembros de equipo**

    Pueden acceder a Workstation como un **repositorio de información del equipo** al que pertenecen (_por ejemplo, Riesgo_).

    Desde la carpeta de su equipo, estos usuarios pueden:

    * Crear y almacenar informes (consultas y tablas de datos).
    * Organizar y gestionar información interna del equipo.
    * Consultar los contenidos creados dentro de su carpeta.
    * Visualizar paneles virtuales asociados a dicha información.

    Estos usuarios no tienen permisos **para crear ni administrar dashboards**, ni para definir la visibilidad global de los tableros.

El uso detallado de las funcionalidades de Workstation **no se documenta en este manual**, ya que cuenta con una guía específica.

Para conocer el proceso de acceso y uso de Workstation, consulte el siguiente manual:

{% content-ref url="workstation.md" %}
[workstation.md](workstation.md)
{% endcontent-ref %}

#### **2.3 Uso compartido y visualización de reportes en Library**

**Library es una herramienta de uso personal**, asociada a cada usuario.\
Cada usuario puede visualizar únicamente los reportes y tableros que se encuentren agregados a su Library personal.

Cuando un usuario comparte un enlace de un reporte o tablero desde Library, el proceso para acceder y utilizar el contenido es el siguiente:

{% stepper %}
{% step %}
#### 🖱️Acceder al enlace compartido

Haga clic en el enlace del reporte o tablero compartido.

Al acceder al enlace, deberá **iniciar sesión en Library** utilizando sus credenciales de acceso (_usuario y contraseña_), tal como se muestra en la siguiente guía:\
🔗 [#como-acceder-a-library](./#como-acceder-a-library "mention")
{% endstep %}

{% step %}
#### ⚙️Configurar parámetros previos del tablero

Una vez iniciada la sesión, se mostrará la pantalla de configuraciones previas, donde el usuario deberá definir los filtros y parámetros necesarios para la visualización de la información (_si aplica_).\
Al finalizar, se debe hacer clic en el botón **Aplicar**.

{% hint style="warning" %}
**Nota:** Las configuraciones definidas quedarán guardadas **por defecto en su Library personal** y se utilizarán cada vez que acceda al tablero.
{% endhint %}

<figure><img src=".gitbook/assets/image (17) (1).png" alt="" width="563"><figcaption><p>Figura #3: Captura de pantalla ejemplo de configuraciones previas</p></figcaption></figure>
{% endstep %}

{% step %}
#### ➕ Agregar el tablero a la Library personal

Después de aplicar las configuraciones, se mostrará el tablero con la información correspondiente.

En la parte superior derecha se habilitará la opción **"Agregar a Library"**, la cual permite añadir el tablero a la Library personal del usuario.

<figure><img src=".gitbook/assets/image (20) (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### ✅ Visualizar el tablero en Library

Una vez agregado, el reporte o tablero quedará disponible en su **Library personal**.

Desde allí, podrá acceder al contenido en cualquier momento para su visualización y uso.
{% endstep %}

{% step %}
#### 🔎 Modificación de filtros

Si desea modificar los filtros o las configuraciones previas del tablero:

1. Ubique la barra superior de herramientas dentro del tablero.
2. Seleccione el **ícono de filtros**.
3. Ajuste los filtros o parámetros según sea necesario.
4. Aplique los cambios para actualizar la visualización de la información.

<figure><img src=".gitbook/assets/image (21) (1).png" alt=""><figcaption></figcaption></figure>

Para más información sobre **Library**, consulte el siguiente manual:

{% content-ref url="https://github.com/DavidVelasquezsoft/BackUp-Manuales-de-usuario/tree/main/Strategy/library/README.md" %}
[https://github.com/DavidVelasquezsoft/BackUp-Manuales-de-usuario/tree/main/Strategy/library/README.md](https://github.com/DavidVelasquezsoft/BackUp-Manuales-de-usuario/tree/main/Strategy/library/README.md)
{% endcontent-ref %}
{% endstep %}
{% endstepper %}

***

### 3. Control de Versiones

<table><thead><tr><th width="99.66665649414062">Versión</th><th width="150.6666259765625">Fecha</th><th width="180">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>06/02/2026</td><td>David Velasquez</td><td>Documento inicial</td></tr></tbody></table>
