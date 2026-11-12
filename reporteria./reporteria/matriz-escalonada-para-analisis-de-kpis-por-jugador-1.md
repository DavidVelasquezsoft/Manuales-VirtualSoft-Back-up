---
hidden: true
---

# Matriz Escalonada para Análisis de KPIs por Jugador

{% hint style="danger" %}
**Nota**: Esta reportería ya no está en funcionamiento.
{% endhint %}

### 1. Descripción General

La matriz escalonada permite analizar la evolución del **valor del jugador** a lo largo del tiempo, desde su primer depósito (FTD). Esta herramienta consolida datos históricos de KPIs clave por operación, segmentados por cohortes mensuales, facilitando el seguimiento de métricas como:

* **Usuarios adquiridos**
* **GGR total (Casino + Deportivas)**
* **Tasa de retención**
* **CPA (Costo por Adquisición)**
* **Utilidad neta**
* **ROI**

Este enfoque de análisis facilita una lectura clara del desempeño por cohorte y permite identificar tendencias de valor, rentabilidad y comportamiento del usuario en el tiempo.

***

### 2. Acceso al Reporte

#### Disponibilidad

El reporte se distribuye automáticamente vía correo electrónico a los usuarios autorizados durante los primeros días de cada mes.

#### Requisitos de acceso

El acceso está restringido a perfiles autorizados, en caso de ser necesario, se debe solicitar el acceso con el equipo de TI.

#### Pasos para acceder:

1. Descargar la carpeta comprimida recibida.
2. Descomprimir el archivo `.zip`.
3. Abrir el archivo excel correspondiente al partner y país deseado.

***

### 3. Visualización del Reporte

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption><p>Figura 1: Captura de pantalla Correo.</p></figcaption></figure>

Cada archivo representa los KPIs de una operación específica (partner) segmentada por país. Aunque los datos varían por operación, todos los archivos comparten el **mismo** **formato**.

La carpeta contiene los reportes para las siguientes operaciones:

* Doradobet
* Ecuabet
* Paniplay
* Camanbet
* Ganaplay

***

### 4. Estructura y Funcionalidades del Reporte

#### 4.1 Formato del Archivo

* **Tipo de archivo:** `.xlsx` o `.csv`
* **Estructura:** Matriz escalonada por cohortes mensuales
* **Dimensiones:**
  * **Filas (eje Y):** Cohortes de usuarios según el mes de su primer depósito (FTD)
  * **Columnas (eje X):** Meses posteriores al FTD (evolución temporal)

***

#### 4.2 Interpretación de la Matriz

La matriz muestra cómo se comportan los usuarios mes a mes desde su incorporación. Cada celda presenta indicadores clave de esa cohorte en un mes específico.

**Lectura detallada**

| Concepto                      | Descripción                                                                                                                                                       |
| ----------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **`Diagonal principal`**      | Muestra el GGR y usuarios activos en el mes en que realizaron su primer depósito (FTD).                                                                           |
| **`Celdas hacia la derecha`** | Reflejan la actividad de esa misma cohorte en los meses siguientes: número de usuarios que permanecen activos, ingresos generados, y métricas asociadas como ROI. |
| **`Filas posteriores`**       | Representan cohortes de adquisición de meses posteriores. La comparación entre filas permite observar tendencias de adquisición y retención entre cohortes.       |

***

### 5. Parámetros del Script que Genera el Reporte

El procesamiento de datos para esta matriz se realiza mediante un script en Python que:

* Estructura los datos por cohortes mensuales.
* Calcula indicadores clave como GGR, CPA, utilidad, ROI y tasa de retención.
* Genera la matriz escalonada para cada operación propia.
* Permite personalización por:
  * Rango de fechas
  * País u operación específica

***

### 6. Glosario

<table><thead><tr><th width="301.33331298828125">Término</th><th>Definición</th></tr></thead><tbody><tr><td><strong><code>FTD (First Time Deposit)</code></strong></td><td>Primer depósito realizado por un usuario.</td></tr><tr><td><strong><code>GGR (Gross Gaming Revenue)</code></strong></td><td>Ingreso bruto del juego: Apuestas realizadas menos premios pagados. Incluye Casino y Deportivas.</td></tr><tr><td><strong><code>Cohorte</code></strong></td><td>Grupo de usuarios que comparten una característica temporal, como la fecha de su primer depósito.</td></tr><tr><td><strong><code>Retención</code></strong></td><td>Porcentaje de usuarios que permanecen activos en períodos posteriores a su adquisición.</td></tr><tr><td><strong><code>CPA (Costo por Adquisición)</code></strong></td><td>Costo promedio incurrido para adquirir un usuario.</td></tr><tr><td><strong><code>Utilidad</code></strong></td><td>Ganancia neta después de restar costos de adquisición y operación.</td></tr><tr><td><strong><code>ROI (Return on Investment)</code></strong></td><td>Indicador que mide la rentabilidad de una cohorte en función del costo de adquisición.</td></tr><tr><td><strong><code>valor del jugador</code></strong></td><td>Valor generado por un jugador a lo largo de su ciclo de vida, calculado a partir de métricas como GGR, retención, y ROI.</td></tr><tr><td><strong><code>ROI (Return on Investment)</code></strong></td><td>Mide la rentabilidad de una cohorte en relación con su costo de adquisición.</td></tr></tbody></table>
