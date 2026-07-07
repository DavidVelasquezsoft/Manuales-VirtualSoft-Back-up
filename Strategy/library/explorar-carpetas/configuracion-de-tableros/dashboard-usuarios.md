---
description: >-
  Este dashboard ha sido desarrollado para brindar una visión clara y completa
  del comportamiento de los usuarios en la plataforma.
---

# Dashboard Usuarios

#### Configuración general

### 1. Acceso al Módulo

**Ruta de acceso:** [Acceso directo](https://reporting.virtualsoft.tech/MicroStrategyLibrary/app/3394329B42569ED3E0CDD1AABE6F7740/56C2A5FE41C02C7312A22785B8201304/W1ECB82B720B04051AE74DFBEEC6E05EB--K46).

{% hint style="warning" %}
**Nota:**\
El tablero presenta información actualizada según el rango horario configurado (00:00:00 a 23:59:59), pudiendo visualizar datos diarios o mensuales, de acuerdo con los filtros aplicados.
{% endhint %}

***

### 2. Visualización

<figure><img src="../../../.gitbook/assets/image (37) (1).png" alt=""><figcaption><p>Figura #1: Vista general del Dashboard de Análisis de Usuarios.</p></figcaption></figure>

***

### 3. 🧑‍💻Acciones del Usuario

| Acción                            | Descripción                                                                                     |
| --------------------------------- | ----------------------------------------------------------------------------------------------- |
| **Aplicar filtros**               | Permite ejecutar la consulta según los parámetros seleccionados.                                |
| **Visualizar tendencias**         | Despliega gráficos que muestran la evolución diaria y mensual de usuarios activos por vertical. |
| **Consultar detalles de usuario** | Permite acceder a la información individual de cada usuario y sus últimas actividades.          |

***

### 4. 🧩Filtros Disponibles

| Filtro           | Descripción                                                                   |
| ---------------- | ----------------------------------------------------------------------------- |
| **`Partner`**    | El tablero solo mostrará información referente al partner seleccionado.       |
| **`País`**       | El tablero solo mostrará información referente al país seleccionado.          |
| **`Id Usuario`** | El tablero solo mostrará información referente al id del usuario a consultar. |
| **`Mes`**        | El tablero solo mostrará información referente al mes seleccionado.           |
| **`Día`**        | El tablero solo mostrará información referente al día seleccionado.           |

{% hint style="warning" %}
**Nota:** Puedes combinar varios filtros al mismo tiempo para realizar análisis más detallados.
{% endhint %}

***

### 5. Datos del tablero.

#### 5.1 Kpi´s diarios

<table><thead><tr><th width="228">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Activos en Deportivas</code></strong></td><td>Número diario de usuarios con actividad en apuestas deportivas en la plataforma.</td></tr><tr><td><strong><code>Activos en Casino</code></strong></td><td>Total de usuarios con actividad en casino, ya sea diaria o mensual.</td></tr><tr><td><strong><code>Activos depositante</code></strong></td><td>Cantidad total de usuarios que realizaron depósitos diarios en la plataforma.</td></tr><tr><td><strong><code>Activos General</code></strong></td><td>Total de usuarios con actividad diaria en cualquiera de las verticales: deportivas, casino o depósitos.</td></tr></tbody></table>

#### 5.2 Kpi´s mensual.

| Indicador                   | Descripción                                                                                       |
| --------------------------- | ------------------------------------------------------------------------------------------------- |
| **`Activos en Deportivas`** | Número de usuarios con actividad en apuestas deportivas por lo menos 1 vez al mes.                |
| **`Activos en Casino`**     | Total de usuarios con actividad en casino mensual.                                                |
| **`Activos depositante`**   | Cantidad total de usuarios que realizaron depósitos por lo menos una vez al mes en la plataforma. |
| **`Activos General`**       | Usuarios con actividad mensual en cualquiera de las verticales: deportivas, casino o depósitos.   |
| **`Primeros depositos`**    | Total de usuarios que realizaron un primer de usuarios en el mes                                  |
| `Registros`                 | Total de usuarios que se realizaron un registro en ese mes.                                       |

{% hint style="warning" %}
**Importante:**

* Un **usuario activo mensual** es aquel que haya realizado al menos un depósito durante el mes, sin importar cuántas veces lo haya hecho.
  * Ejemplo: si un usuario deposita 2 veces en el mes y otro también 2 veces, se cuentan como **2 usuarios activos únicos**.
* Para los datos diarios, si un usuario deposita varias veces en un mismo día, se contabiliza solo una vez.
  * Ejemplo: si un usuario deposita el 3 y el 27 de enero, se contará como activo en ambos días (una vez por día).
{% endhint %}

***

El dashboard presenta gráficos que ayudan a visualizar la información para un mejor análisis, estos gráficos se dividen entre mensuales y diarios.

{% tabs %}
{% tab title="Gráficos diarios" %}
<table><thead><tr><th width="165">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuarios Activos General - Mes</code></strong></td><td>Gráfico de barras que muestra la cantidad de usuarios que han tenido actividad mensual en la plataforma, ya sea en casino, deportivas o cualquier vertical.</td></tr><tr><td><strong><code>Usuarios activos casino - Mes</code></strong></td><td>Gráfico de barras que muestra la cantidad de usuarios que han tenido mensual en la plataforma desde la vertical de casino.</td></tr><tr><td><strong><code>Usuarios activos deportivas - Mes</code></strong></td><td>Gráfico de barras que muestra la cantidad de usuarios que han tenido actividad mensual en la plataforma desde la vertical de <strong>deportivas</strong>.</td></tr><tr><td><strong><code>Usuarios activos depositante - Mes</code></strong></td><td>Gráfico de barras que muestra la cantidad de usuarios que han realizado depósitos en su cuenta por lo menos una vez al mes.</td></tr></tbody></table>
{% endtab %}

{% tab title="Gráficos mensuales " %}
<table><thead><tr><th width="194">Gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuarios Activos General - Diarios</code></strong></td><td>Gráfico de barras que muestra la cantidad de usuarios que han tenido actividad diaria en la plataforma, ya sea en casino, deportivas o cualquier vertical.</td></tr><tr><td><strong><code>Usuarios activos casino - Diarios</code></strong></td><td>Gráfico de barras que muestra la cantidad de usuarios que han tenido actividad diaria en la plataforma desde la vertical de casino.</td></tr><tr><td><strong><code>Usuarios activos deportivas - Diarios</code></strong></td><td>Gráfico de barras que muestra la cantidad de usuarios que han tenido actividad diaria en la plataforma desde la vertical de <strong>deportivas</strong>.</td></tr><tr><td><strong><code>Usuarios activos depositante - Diarios</code></strong></td><td>Gráfico de barras que muestra la cantidad de usuarios que han realizado depósitos en su cuenta en un solo día.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

### **6. Últimos Movimientos del Usuario**

| Columna                              | Descripción                                                       |
| ------------------------------------ | ----------------------------------------------------------------- |
| **`Partner`**                        | Nombre del partner en el que el usuario tuvo su última actividad. |
| **`País`**                           | País del partner en el que el usuario tuvo su última actividad.   |
| **`Usuario ID`**                     | Identificador único del usuario.                                  |
| **`Fecha de Registro`**              | Fecha en la que el usuario se registró.                           |
| **`Fecha Último Depósito`**          | Última fecha en que el usuario realizó un depósito.               |
| **`Fecha Última Apuesta Deportiva`** | Fecha de la última apuesta en deportivas.                         |
| **`Fecha Última Apuesta Casino`**    | Fecha de la última apuesta en casino.                             |
| **`Días sin Depositar`**             | Número de días desde el último depósito.                          |
| **`Días sin Apostar en Deportivas`** | Días transcurridos desde la última apuesta deportiva.             |
| **`Días sin Apostar en Casino`**     | Días transcurridos desde la última apuesta en casino.             |

#### **7 .📅 Detalles de Activos por Día**

| Columna                           | Descripción                                                 |
| --------------------------------- | ----------------------------------------------------------- |
| **`Partner`**                     | Nombre del partner correspondiente.                         |
| **`País`**                        | País asociado.                                              |
| **`Mes`**                         | Número del mes analizado.                                   |
| **`Día`**                         | Día específico dentro del mes.                              |
| **`Registros`**                   | Total de registros disponibles.                             |
| **`Primer Depósito`**             | Usuarios que realizaron su primer depósito.                 |
| **`Activos Generales`**           | Usuarios con actividad en cualquiera de las verticales.     |
| **`Activos en Deportivas (mes)`** | Usuarios que realizaron apuestas deportivas durante el mes. |
| **`Activos en Depósito`**         | Usuarios que realizaron al menos un depósito.               |
| **`Activos en Casino`**           | Usuarios con actividad en casino.                           |

***

#### ✅ 8. Validaciones y Reglas de Negocio

* Las consultas solo se ejecutan si se selecciona al menos un **rango de fechas válido**.
*   Si no existen datos para los filtros aplicados, el sistema mostrará el mensaje:

    > “No se obtuvieron datos para esta visualización.”
* Los cálculos de usuarios activos se basan en la identificación única de cada usuario por día o mes.
* Los datos reflejan información actualizada dentro del rango **00:00:00 a 23:59:59** del día en curso o periodo seleccionado.

***

#### 🕒 9. Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 07/11/2025 | Ronald Peláez | Documento inicial  |
