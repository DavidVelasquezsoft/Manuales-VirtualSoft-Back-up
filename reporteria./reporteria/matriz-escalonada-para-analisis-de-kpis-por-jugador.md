---
description: >-
  Este reporte nos permite obtener los datos del comportamiento mensual de los
  usuarios de sus  depósitos y su GGR.
hidden: true
---

# Matriz Escalonada para Análisis de KPIs por Jugador

{% hint style="danger" %}
**Nota**: Esta reportería ya no está en funcionamiento.
{% endhint %}

***

## 1. Acceso al Reporte.

**Ruta de Acceso**: El reporte es enviado por correo electrónico durante los primeros días de cada mes, a los usuarios configurados.

* **Paso 1:**  Descargar el archivo ZIP adjunto.
* **Paso 2:** Descomprimir archivo.
* **Paso 3:** Abrir el archivo Excel de interés.

***

## &#x20;2. Visualización.

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption><p>Figura 1: Captura de pantalla Correo.</p></figcaption></figure>

***

## 3. Estructura y deFuncionalidades.

La carpeta contiene varios archivos, cada uno asociado a un partner y un país. Aunque los datos varían, todos comparten el mismo formato. A continuación, se listan los partners disponibles:

* Doradobet.
* Ecuabet.
* Paniplay.
* Camanbet.
* Ganaplay.

#### 3.1 Formato:&#x20;

| FDT (Primeros ingresos) | periodo 1 | periodo 1                                                              |
| ----------------------- | --------- | ---------------------------------------------------------------------- |
| **periodo 1**           | GGR       | Cantidad generada en GGR de casino + deportivas                        |
| **periodo 1**           | Usuarios  | cantidad de usuarios que realizaron un primer depósito en ese periodo. |

#### 3.2 Interpretación de la Matriz

La tabla esta organizada de la siguiente manera:

eliminar=

* **Filas (vertical / eje Y):** Representan el mes en que los usuarios realizaron su primer depósito.
* **Columnas (horizontal / eje X):** Corresponden a los meses en los que se evalúa su comportamiento.
* **Cada celda** contiene dos datos:
  * **GGR:** Ingresos generados.
  * **Usuarios:** Cantidad activa ese mes.

**Lectura detallada:**

* **Diagonal principal:** Las celdas donde **coinciden el FTD y el Período** muestran el momento en que los usuarios hicieron su primer depósito y el GGR generado en ese mes.
* **Celdas hacia la derecha:** Indican los siguientes meses, reflejando retención y evolución de ingresos de esa cohorte.&#x20;
* **Filas posteriores:** representan cohortes de usuarios FTD en otros meses, con su propia evolución temporal.

