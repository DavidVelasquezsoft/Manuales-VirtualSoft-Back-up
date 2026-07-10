---
description: >-
  Referidos permite que los usuarios compartan su enlace único de invitación,
  gestionen sus referidos y consulten las recompensas generadas.
---

# Referidos

### 1. Acceso al módulo

**Ruta:** Menú lateral > Referidos

### 2. Acciones del usuario

Al ingresar, se muestran dos secciones principales:

* [**Agregar referidos**](referidos.md#id-2.1-agregar-referidos)
* [**Estado de referidos**](referidos.md#id-2.2.-estado-de-referidos)

{% tabs %}
{% tab title="2.1 Agregar referidos" %}
#### 2.1.2 Visualización:

<figure><img src="../../.gitbook/assets/image (13) (1).png" alt=""><figcaption><p><strong>Figura</strong>#1: Captura de pantalla referir a un amigo.</p></figcaption></figure>

#### 2.1.3. Configuraciones

En esta sección, el usuario puede enviar invitaciones y obtener su enlace único.

<table><thead><tr><th width="131.40008544921875">Campo</th><th width="99.066650390625">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Texto informativo</code></strong></td><td>Texto</td><td>Explica el funcionamiento del programa de referidos y los beneficios.</td></tr><tr><td><strong><code>Correo</code></strong><img src="../../.gitbook/assets/image (9) (1).png" alt="" data-size="line"></td><td>Botón</td><td>Permite enviar invitaciones ingresando uno o varios usuarios por medio de sus correos electrónicos.</td></tr><tr><td><strong><code>Copiar enlacel</code></strong> <img src="../../.gitbook/assets/image (12) (1).png" alt="" data-size="line"></td><td>Botón</td><td>Muestra el enlace único del usuario y permite copiarlo para compartirlo por cualquier canal para realizar registros por referidos.</td></tr></tbody></table>

<table><thead><tr><th width="106.199951171875">Campo</th><th width="100">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Agregar dirección de correo</code></strong></td><td>Botón <em>(+)</em></td><td>Agrega nuevos campos para ingresar correos adicionales, permite solo 4.</td></tr></tbody></table>
{% endtab %}

{% tab title="2.2. Estado de Referidos" %}
#### 2.2.1 Visualizacion:

<figure><img src="../../.gitbook/assets/image (14) (1).png" alt=""><figcaption><p>Figura#1: Captura de pantalla referir a un amigo.</p></figcaption></figure>

#### 2.2.2 Informacion:

Aquí el usuario visualiza su actividad relacionada con referidos.

<table><thead><tr><th width="189.79998779296875">Campo</th><th width="144">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Recompensas por referencias</code></strong></td><td>Lista Desplegable</td><td>Muestra los bonos o recompensas obtenidos por los referidos activos.</td></tr><tr><td><strong><code>Referidos expirados</code></strong></td><td>Lista Desplegable</td><td>Lista de referidos cuyo periodo para cumplir requisitos ha vencido.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

### 3. Validaciones y reglas de negocio

* Se permite enviar un máximo de **4 correos** por invitación.
* El usuario solo recibirá recompensa si el referido **cumple los requisitos configurados** (depósitos, apuestas, etc.).
* Los referidos pueden **expirar** si no cumplen condiciones en el tiempo establecido.
* Cada usuario posee un **enlace único** de referencia.
* El ID de los referidos se visualizará enmascarado, de modo que los dos últimos dígitos serán reemplazados por asteriscos (\*).

***

### 4. Control de versiones

| Versión | Fecha      | Autor       | Cambios realizados |
| ------- | ---------- | ----------- | ------------------ |
| 1.0     | 01/12/2025 | Karol Navia | Manual inicial.    |
