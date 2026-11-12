---
description: >-
  Este módulo permite crear y configurar ruletas promocionales que pueden ser
  asignadas a usuarios según condiciones específicas de participación.
---

# Crear Ruleta.

### 1. Acceso al Módulo

**Ruta de acceso**: Backoffice > Torneos y Bonos > Crear Ruleta

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (37).png" alt=""><figcaption><p>Figura #1: Captura de pantalla Creación de ruletas.</p></figcaption></figure>

***

### 3. Acciones del Usuario

#### 3.1 Configuración General

A continuación, se describen los campos principales para personalizar la ruleta:

| Campo                                 | Tipo de control | Descripción                                                                  |
| ------------------------------------- | --------------- | ---------------------------------------------------------------------------- |
| **Fecha inicial\***                   | Fecha           | Fecha desde la cual estará activa la ruleta.                                 |
| **Fecha final\***                     | Fecha           | Fecha hasta la cual estará disponible.                                       |
| **Nombre\***                          | Texto           | Nombre identificador de la ruleta.                                           |
| **Orden**                             | Número          | Prioridad de aparición frente a otras ruletas.                               |
| **Descripción**                       | Texto           | Breve detalle de la ruleta.                                                  |
| Usuario puede participar varias veces | Selector Si/NO  | Establece si el usuario puede participar múltiples veces en la misma ruleta. |

***

#### 3.2 Expiración de Ruleta

| Campo                      | Tipo de control         | Descripción                                                                 |
| -------------------------- | ----------------------- | --------------------------------------------------------------------------- |
| Fecha de expiración o días | Selector (Fecha / Días) | Selecciona si la expiración es por fecha fija o por cantidad de días.       |
| Fecha Expiración           | Fecha                   | Se habilita si se selecciona "Fecha". Indica hasta cuándo está disponible.  |
| Días                       | Número                  | Se habilita si se selecciona "Días". Indica cuántos días estará disponible. |

***

#### 3.3 Asignación Automática

| Campo                      | Tipo de control | Descripción                                                                          |
| -------------------------- | --------------- | ------------------------------------------------------------------------------------ |
| ¿Es para registro?         | Sí / No         | **Sí**: Se asigna automáticamente al registrarse. **No**: No se asigna por registro. |
| ¿Es para inicio de sesión? | Sí / No         | **Sí**: Se asigna en el primer inicio del día. **No**: No se asigna automáticamente. |

{% hint style="warning" %}
**Nota**: Solo una opción puede estar activa, al seleccionar una, se desaparecerá la otra.
{% endhint %}

***

#### 3.4 Activación Condicional

| Campo             | Tipo de control   | Descripción                                              |
| ----------------- | ----------------- | -------------------------------------------------------- |
| Pasarelas de pago | Selector múltiple | Define mediante qué pasarelas puede activarse la ruleta. |
| Tipo de producto  | Selector múltiple | Establece con qué productos se activará la ruleta.       |

{% hint style="warning" %}
**Nota**: Al configurar una, se desaparecerá la otra configuración.
{% endhint %}

***

### 4. Configuración de Moneda

| Campo                            | Tipo de control | Descripción                                      |
| -------------------------------- | --------------- | ------------------------------------------------ |
| Valor mínimo de activación       | Número          | Monto mínimo necesario para activar la ruleta.   |
| Máxima cantidad de giros diarios | Número          | Número máximo de giros permitidos por día.       |
| Jugadores                        | Archivo (CSV)   | Carga un archivo con los ID de usuarios válidos. |

{% hint style="warning" %}
**Nota**: Los IDs cargados pueden visualizarse mediante el ícono 👁️.
{% endhint %}

***

### 5. Tipo de Premio

| Tipo de premio     | Campos principales y Descripción resumida                                                        |
| ------------------ | ------------------------------------------------------------------------------------------------ |
| Premio Físico      | Descripción, URL imagen ruleta y premio, Porcentaje. Se muestra imagen y descripción al ganar.   |
| Premio en Dinero   | URL imagen ruleta y premio, Tipo de saldo, Monto, Porcentaje.                                    |
| Premio en Bono     | URL imagen ruleta y premio, Tipo de saldo, Valor bono, Porcentaje.                               |
| Intenta nuevamente | URL imagen ruleta y premio, Porcentaje. Permite giro adicional si el usuario cae en esta opción. |

{% hint style="info" %}
**Restricción**: La suma de los porcentajes de todos los premios no debe superar el 100%. De lo contrario, no podrás agregar nuevos premios.
{% endhint %}

***

### 6. Tabla de Premios

<table><thead><tr><th width="206">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td>Tipo de premio</td><td>Tipo del premio agregado (físico, bono, dinero, intenta nuevamente).</td></tr><tr><td>Descripción</td><td>Texto corto que describe el premio.</td></tr><tr><td>Tipo Saldo</td><td>Tipo de saldo entregado (cuando aplique).</td></tr><tr><td>Bono valor</td><td>Monto en bono o dinero del premio (cuando aplique).</td></tr><tr><td>URL imagen ruleta</td><td>Imagen que se muestra al girar la ruleta.</td></tr><tr><td>URL imagen premio</td><td>Imagen mostrada cuando el premio es ganado.</td></tr><tr><td>Porcentaje</td><td>Probabilidad de obtener el premio.</td></tr><tr><td>Acción</td><td>Permite eliminar el premio de la ruleta.</td></tr></tbody></table>

***

### 7. Configuraciones Avanzadas

| Campo            | Tipo de control   | Descripción                                   |
| ---------------- | ----------------- | --------------------------------------------- |
| URL de fondo     | Texto             | Imagen de fondo personalizada para la ruleta. |
| Regiones Usuario | Selector múltiple | Regiones donde aplica la ruleta.              |
| Departamentos    | Selector múltiple | Departamentos habilitados.                    |
| Ciudades         | Selector múltiple | Ciudades habilitadas.                         |

***

### 8. Casos Especiales

* Si la ruleta se configura como **"Es para inicio de sesión"**, esta se asignará únicamente al **primer login del día**, siempre y cuando el usuario **no tenga una ruleta asignada por registro**.
* Al elegir **"Intenta nuevamente"**, si el usuario cae sobre esta opción, obtendrá un nuevo giro **automáticamente**. Este giro extra **no es acumulable**: si el usuario sale de la ruleta, el beneficio se pierde.
* En las configuraciones por **Tipo de producto**, si se selecciona un producto como Sportsbook, se podrá condicionar la ruleta por Deporte, Mercado, Ligas, Partidos, Tipo de evento, etc.
* En caso de configurar con **Casino**, **Casino en Vivo** o **Virtuales**, se pueden elegir Categorías, Proveedores o Productos específicos.
* La activación de ruletas de tipo deportivo o casino solo ocurre si la apuesta fue hecha con **saldo real**. Si se usa bono, la ruleta **no se activa**.
* Cuando se usa la opción por **Días de expiración**, el conteo inicia desde el momento en que se le asigna la ruleta al usuario, no desde la fecha de creación.

***

### 9. Validaciones y Reglas de Negocio

* Solo una condición automática puede estar activa: registro o inicio de sesión.
* No se puede configurar simultáneamente por pasarela y tipo de producto.
* La suma de los porcentajes de premios no puede superar el 100%.
* Las ruletas solo se activan con saldo real.
* Todos los campos con asterisco (\*) son obligatorios para guardar la ruleta.
* Es posible agregar varios premios de "**Intenta nuevamente**" en la ruleta.

***

### 10. Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 04/07/2025 | Ronald Pelaez | Documento inicial. |
