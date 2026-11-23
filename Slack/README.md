---
description: >-
  Se detalla el funcionamiento del bot que identifica discrepancias entre
  BackOffice y el archivo de control, generando notificaciones automáticas a
  través de Slack.
---

# Bot de Alerta de Anomalías en Activación de Juegos y Subproveedores.

### 1. Acceso

La recepción de las alertas se realiza de forma automática a través de **Slack**.

{% hint style="warning" %}
**Nota:** En caso de no visualizar el canal o no recibir notificaciones, solicitar acceso al área de soporte.
{% endhint %}

***

### 2. Funcionamiento General

El bot envía el reporte de manera automática tres **veces al día**:

<table><thead><tr><th width="248">Momento ejecución</th><th>Hora</th></tr></thead><tbody><tr><td><strong><code>Mañana</code></strong></td><td>09:00 am</td></tr><tr><td><strong><code>Tarde</code></strong></td><td>02:00 pm</td></tr><tr><td><strong><code>Noche</code></strong></td><td>06:00 pm</td></tr></tbody></table>

El sistema compara el **archivo de control en Excel** con la información almacenada en el **BackOffice** de las plataformas:

* **Dorado Perú**
* **Gangabet Perú**

***

### 3. Tipos de Discrepancia

| Código Discrepancia               | Descripción                                                   |
| --------------------------------- | ------------------------------------------------------------- |
| **`Activación no registrada`**    | En BackOffice figura como activo, pero no en Excel            |
| **`Desactivación no autorizada`** | En Excel figura como activo, pero está inactivo en BackOffice |

***

#### 4. 📄 Formato de la Alerta Automática

El bot adjunta un archivo Excel con la siguiente estructura:

| Columna                                                   | Descripción                                                        |
| --------------------------------------------------------- | ------------------------------------------------------------------ |
| **`Fecha Detección`**                                     | Momento en que se encontró la discrepancia                         |
| **`Tipo`**                                                | Producto o Subproveedor                                            |
| **`Marca`**                                               | Dorado Perú o Gangabet Perú                                        |
| **`ID`**                                                  | Identificador del producto o subproveedor                          |
| **`Nombre`**                                              | Nombre del producto o subproveedor                                 |
| **`Usuario Administrativo`**                              | Usuario que realizó la acción en BackOffice _(si está disponible)_ |
| **`Estado en BO`**                                        | Activo / Inactivo según BackOffice                                 |
| **`Estado en Excel`**                                     | Estado esperado según archivo controlado por Cumplimiento          |
| [**`Tipo Discrepancia`**](./#id-3.-tipos-de-discrepancia) | Activación no registrada o Desactivación no autorizada             |

***

#### 5. 🕒 Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 27/11/2025 | Ronald Peláez | Documento inicial. |
