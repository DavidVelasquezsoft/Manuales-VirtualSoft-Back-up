---
description: >-
  Este tablero te permite visualizar y analizar datos clave relacionados con las
  apuestas en dos categorías principales: Deportivas y Casino.
---

# Datos por rangos apuestas casino y deportivas

{% hint style="danger" %}
**Nota**: Este manual ya no se encuentra en funcionamiento debido a que el tablero ya no se utiliza.
{% endhint %}

### ⚙️ Configuración inicial del tablero

Antes de ingresar al tablero, es necesario realizar las siguientes configuraciones:

<figure><img src="../../.gitbook/assets/image (81).png" alt=""><figcaption></figcaption></figure>

Ubica el modelo semántico y haz clic en el ícono <img src="../../.gitbook/assets/image (82).png" alt="" data-size="line">**"actualizar"** para hacer las respectivas configuraciones.\
Al hacer clic en el ícono, se abrirá una visual con las opciones de configuración.\
Luego es necesario **tomar el control** antes de realizar cualquier cambio:

* Haz clic en el botón **“Tomar el control”**.
* Aparecerá una ventana emergente solicitando confirmación.
* Confirma haciendo clic nuevamente en **“Tomar el control”**.

### **Configurar los parámetros:**<br>

<figure><img src="../../.gitbook/assets/image (83).png" alt="" width="340"><figcaption></figcaption></figure>

Una vez con el control, busca y haz clic en la opción **“Parámetros”**.\
Se desplegarán los siguientes campos que debes completar:

* **Fecha\_fin:** Fecha final del periodo a analizar (ejemplo: `2025-05-31`).
* **Mandante:** Nombre del partner u operador.
* **País**: País al cual se requiere hacer el análisis.
* **Fecha\_inicio:** Fecha inicial del periodo a analizar (ejemplo: `2025-05-15`).
* **Rangos**: Definición de rangos personalizados en el siguiente formato:\
  _&#x52;ango mínimo 1; Rango máximo 1000; Pasos 100._

Una vez completados todos los parámetros, haz clic en el botón **“Aplicar”** para guardar y actualizar la configuración.

## 📑Informe:

### Filtros disponibles

En el lado izquierdo del tablero encontrarás los filtros que puedes aplicar para personalizar la visualización de los datos. Los filtros disponibles son:

<figure><img src="../../.gitbook/assets/image (3).png" alt="" width="235"><figcaption><p>Figura#1: Captura de pantalla Filtros de búsqueda.</p></figcaption></figure>

* **Rango Deportivo:** Permite seleccionar un rango de valores para mostrar los resultados en deportivas.
* **Rango Casino:** te permite seleccionar un rango de valores para agrupar las apuestas según montos definidos.
* **Tipo de casino:** este filtro solo afecta la sección de casino, y te permite elegir entre “Todas”, “Casino”, “Live Casino” o “Virtual”.

## 📈 Visualización de los datos

Una vez aplicados los filtros, el lado derecho del tablero mostrará dos tablas de información diferenciados: uno para **apuestas deportivas** (parte superior) y otro para **apuestas de casino** (parte inferior).

### Apuestas Deportivas&#x20;

<figure><img src="../../.gitbook/assets/image (78).png" alt=""><figcaption><p>Figura#2: Captura de pantalla tablero deportivas.</p></figcaption></figure>

Esta sección muestra los datos agrupados por rangos de valor apostado, contiene la siguiente información:

* **Partner**: Nombre del partner asociado.
* **País**: País donde se realizaron las apuestas.
* **Rangos**: Intervalos del valor de las apuestas realizadas.
* **Cantidad Tickets**: Número total de tickets de apuestas generados en ese rango.
* **Valor Apuestas**: Monto total apostado por todos los usuarios dentro del rango especificado.
* **Valor Premios:** Valor total de los premios entregados en ese rango de apuestas.
* **Cantidad Usuarios:** Número de usuarios únicos que participaron dentro del rango.

### Apuestas de Casino

<figure><img src="../../.gitbook/assets/image (79).png" alt=""><figcaption><p>Figura#3: Captura de pantalla tablero casino.</p></figcaption></figure>

En la parte inferior del tablero encontrarás los datos relacionados con casino. La información mostrada será la siguiente:

* **Partner**: Nombre del partner filtrado.
* **País**: País donde se realizaron las apuestas.
* **Cantidad Tickets**: Número de tickets registrados para ese grupo de apuestas.
* **Valor Apostado**: Suma total del dinero apostado por los usuarios.
* **Valor Premios**: Total de premios otorgados por el sistema en esa categoría.
* **Cantidad Usuarios**: Número de usuarios únicos que participaron.
* **Tipo Casino**: Indica el tipo de experiencia de casino: Casino, Live Casino o Virtual.
