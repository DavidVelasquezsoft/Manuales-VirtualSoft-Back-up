---
description: >-
  Presenta la información consolidada de las operaciones de casino
  correspondientes al día en curso y al día anterior. Permite analizar en tiempo
  real los resultados de las apuestas.
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# Casino real time

### Configuración general

### 1. Acceso al Módulo

**Ruta de acceso**: [Acceso directo](https://reporting.virtualsoft.tech/MicroStrategyLibrary/app/3394329B42569ED3E0CDD1AABE6F7740/0534AE664214A86B81280CA76E4EC4D4/W1CBBA35787CE4A56994A98AED880F24A--K46).

{% hint style="warning" %}
**Nota:**\
El tablero presenta datos actualizados en tiempo real correspondientes al rango horario de 00:00:00 a 23:59:59, ya sea del día en curso o del día anterior, según la hora de corte establecida.
{% endhint %}

***

### **2. Configuraciones Previas**

Antes de visualizar el reporte, es necesario establecer las [configuraciones previas.](https://virtualsoft.gitbook.io/manuales/microstrategy/tableros#id-2.-configuracion-previa)

***

### 3. Visualización

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2Flu9BpmBVDUutKfN58803%2Fimage.png?alt=media&#x26;token=9b3de4a6-614e-47e3-a0da-1efa0dda83f4" alt="Dashboard Casino Real Time"><figcaption><p>Figura #1: Vista general del reporte Casino Real Time.</p></figcaption></figure>

***

### 🧑‍💻 4. Acciones del Usuario

<table><thead><tr><th width="275">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Aplicar filtros</strong></td><td>Permite ejecutar la consulta según los parámetros seleccionados <em>(fecha, partner, juego, etc.).</em></td></tr><tr><td><strong>Visualizar ranking</strong></td><td>Despliega los resultados en los paneles <strong>(</strong><em><strong>Top GGR Positivo</strong></em><strong>, </strong><em><strong>Negativo</strong></em><strong> o </strong><em><strong>Top 10 por valor de apuesta)</strong></em>.</td></tr><tr><td><strong>Consultar detalle de usuario</strong></td><td>Permite analizar el comportamiento y resultados de un jugador específico.</td></tr></tbody></table>

***

### 🧩 5. Filtros disponibles

<table><thead><tr><th width="185">Filtro</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Permite seleccionar uno o varios <em>Partners</em> para realizar la consulta.</td></tr><tr><td><strong><code>País</code></strong></td><td>Determina el país desde el cual se desea visualizar la información.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Filtra los resultados por un juego específico.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Permite seleccionar el <em>proveedor</em> del cual se desea consultar la información. Es posible elegir uno o varios proveedores según sea necesario.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Filtra los juegos pertenecientes a un subproveedor determinado.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Ingresa el <em>ID del usuario</em> que se desea consultar.</td></tr><tr><td><strong><code>Rango de fechas (Desde/Hasta)</code></strong></td><td>Define el periodo sobre el cual se ejecutará la consulta.</td></tr></tbody></table>

***

{% hint style="warning" %}
**Nota:**\
Todos los datos mostrados se rigen según los filtros aplicados en el tablero.
{% endhint %}

### 6. KPIs principales mostrados en el panel lateral

<table><thead><tr><th width="185">Indicador</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Nro Spin</code></strong></td><td>Total de giros realizados según los filtros aplicados.</td></tr><tr><td><strong><code>Apuesta</code></strong></td><td>Valor total apostado en juegos de casino.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Valor total de premios otorgados a los jugadores.</td></tr><tr><td><strong><code>Premio Bono</code></strong></td><td>Valor total de premios generados mediante bonificaciones.</td></tr><tr><td><strong><code>Bono</code></strong></td><td>Valor total de bonos utilizados durante las sesiones de juego.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a></td><td><p>Representa el ingreso total generado por la actividad de juego antes de aplicar deducciones o impuestos. Se calcula mediante la siguiente fórmula:</p><p><em><strong>(GGR = Apuestas – Premios – Premios Bono)</strong></em></p></td></tr></tbody></table>

> **Interpretación del GGR:**
>
> * **GGR Positivo:** Los jugadores perdieron más dinero del que ganaron _(ganancia para el operador)._
> * **GGR Negativo:** Los jugadores ganaron más dinero del que apostaron _(pérdida para el operador)._

***

### 7. Información del Dashboard

<table><thead><tr><th width="152">Bloque</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Top GGR Positivo</code></strong></td><td>Esta gráfica muestra los juegos con mayor generación de ingresos (GGR positivo).</td></tr><tr><td><strong><code>Top GGR Negativo</code></strong></td><td>Esta gráfica presenta los juegos con menor rentabilidad <em>(GGR negativo)</em>.</td></tr><tr><td><strong><code>Detallado usuario</code></strong></td><td>Muestra información detallada de cada jugador.</td></tr><tr><td>Columna</td><td>Descripción</td></tr><tr><td><strong><code>IdUsuario</code></strong></td><td>Identificador único asignado a cada jugador dentro del sistema.</td></tr><tr><td><strong><code>NroSpin</code></strong></td><td>Número total de giros realizados por el usuario durante el período seleccionado.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Monto total apostado por el usuario en todas las sesiones de juego.</td></tr><tr><td><strong><code>Apuestas Promedio</code></strong></td><td>Promedio del valor apostado por giro. Se calcula como: <strong>Apuestas / NroSpin</strong>.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Total de premios obtenidos por el usuario a partir de las apuestas realizadas.</td></tr><tr><td><strong><code>Premios Bono</code></strong></td><td>Total de premios generados a partir de bonos o promociones otorgadas.</td></tr><tr><td><strong><code>Apuestas Saldo Gratis</code></strong></td><td>Valor total apostado utilizando saldo gratuito o créditos promocionales.</td></tr><tr><td><strong><code>GGR Bruto</code></strong></td><td>Resultado bruto del juego antes de deducciones. Se calcula como: <strong>Apuestas – Premios – Premios Bono</strong>.</td></tr><tr><td><strong><code>Top 10 por valor de apuesta</code></strong></td><td>Muestra los 10 juegos con el valor promedio de apuesta más alto, determinado a partir del total de giros realizados y los montos apostados por los usuarios.</td></tr><tr><td>Columna</td><td>Descripción</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego al que pertenecen las estadísticas mostradas.</td></tr><tr><td><strong><code>Activos</code></strong></td><td>Número total de usuarios que participaron activamente en el juego durante el período seleccionado.</td></tr><tr><td><strong><code>NroSpin</code></strong></td><td>Cantidad total de giros realizados en el juego.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Suma total del valor apostado por todos los usuarios en ese juego.</td></tr><tr><td><strong><code>Apuesta</code></strong> <strong><code>Promedio</code></strong></td><td>Valor promedio apostado por giro. Se obtiene mediante la fórmula: <strong>Apuestas / NroSpin</strong>.</td></tr><tr><td><strong><code>GGR</code></strong> <strong><code>Bruto</code></strong></td><td>Ganancia bruta del juego antes de deducciones. Se calcula como: <strong>Apuestas – Premios – Premios Bono</strong>.</td></tr><tr><td><strong><code>Consolidado</code></strong></td><td>Resume las métricas globales del período seleccionado.</td></tr><tr><td>Columna</td><td>Descripción</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner o socio comercial asociado a la operación.</td></tr><tr><td><strong><code>País</code></strong></td><td>País correspondiente a la cuenta o al partner seleccionado.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor principal que ofrece los juegos.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Nombre del subproveedor vinculado al proveedor principal.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego al que pertenecen las métricas mostradas.</td></tr><tr><td><strong><code>Activos</code></strong></td><td>Total de usuarios activos durante el período analizado.</td></tr><tr><td><strong><code>NroSpin</code></strong></td><td>Número total de giros o rondas realizadas en los juegos.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Valor total apostado por los usuarios dentro del rango seleccionado.</td></tr><tr><td><strong><code>Apuestas Promedio</code></strong></td><td>Valor promedio apostado por giro. Se calcula mediante la fórmula: <strong>Apuestas / NroSpin</strong>.</td></tr><tr><td><strong><code>Saldo Gratis</code></strong></td><td>Total apostado utilizando saldo gratuito o promocional.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Valor total de los premios entregados a los usuarios.</td></tr><tr><td><strong><code>Premios Bono</code></strong></td><td>Total de premios obtenidos a partir de bonos o promociones.</td></tr><tr><td><strong><code>GGR Bruto</code></strong></td><td>Ganancia bruta generada antes de deducciones. Se calcula como: <strong>Apuestas – Premios – Premios Bono</strong>.</td></tr><tr><td><strong><code>% GGR</code></strong></td><td>Porcentaje que representa el <strong>GGR Bruto</strong> respecto al total apostado. Se obtiene mediante la fórmula: <em><strong>(GGR Bruto / Apuestas) × 100</strong>.</em></td></tr></tbody></table>

<table><thead><tr><th width="157">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del partner o socio comercial asociado a la operación.</td></tr><tr><td><strong><code>País</code></strong></td><td>País correspondiente a la cuenta o al partner seleccionado.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Nombre del proveedor principal que ofrece los juegos.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Nombre del subproveedor vinculado al proveedor principal.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego al que pertenecen las métricas mostradas.</td></tr><tr><td><strong><code>Activos</code></strong></td><td>Total de usuarios activos durante el período analizado.</td></tr><tr><td><strong><code>NroSpin</code></strong></td><td>Número total de giros o rondas realizadas en los juegos.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Valor total apostado por los usuarios dentro del rango seleccionado.</td></tr><tr><td><strong><code>Apuestas Promedio</code></strong></td><td>Valor promedio apostado por giro. Se calcula mediante la fórmula: <strong>Apuestas / NroSpin</strong>.</td></tr><tr><td><strong><code>Saldo Gratis</code></strong></td><td>Total apostado utilizando saldo gratuito o promocional.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Valor total de los premios entregados a los usuarios.</td></tr><tr><td><strong><code>Premios Bono</code></strong></td><td>Total de premios obtenidos a partir de bonos o promociones.</td></tr><tr><td><strong><code>GGR Bruto</code></strong></td><td>Ganancia bruta generada antes de deducciones. Se calcula como: <strong>Apuestas – Premios – Premios Bono</strong>.</td></tr><tr><td><strong><code>% GGR</code></strong></td><td>Porcentaje que representa el <strong>GGR Bruto</strong> respecto al total apostado. Se obtiene mediante la fórmula: <em><strong>(GGR Bruto / Apuestas) × 100</strong>.</em></td></tr></tbody></table>

<table><thead><tr><th width="157">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Juego</code></strong></td><td>Nombre del juego al que pertenecen las estadísticas mostradas.</td></tr><tr><td><strong><code>Activos</code></strong></td><td>Número total de usuarios que participaron activamente en el juego durante el período seleccionado.</td></tr><tr><td><strong><code>NroSpin</code></strong></td><td>Cantidad total de giros realizados en el juego.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Suma total del valor apostado por todos los usuarios en ese juego.</td></tr><tr><td><strong><code>Apuesta</code></strong> <strong><code>Promedio</code></strong></td><td>Valor promedio apostado por giro. Se obtiene mediante la fórmula: <strong>Apuestas / NroSpin</strong>.</td></tr><tr><td><strong><code>GGR</code></strong> <strong><code>Bruto</code></strong></td><td>Ganancia bruta del juego antes de deducciones. Se calcula como: <strong>Apuestas – Premios – Premios Bono</strong>.</td></tr></tbody></table>

<table><thead><tr><th width="139">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>IdUsuario</code></strong></td><td>Identificador único asignado a cada jugador dentro del sistema.</td></tr><tr><td><strong><code>NroSpin</code></strong></td><td>Número total de giros realizados por el usuario durante el período seleccionado.</td></tr><tr><td><strong><code>Apuestas</code></strong></td><td>Monto total apostado por el usuario en todas las sesiones de juego.</td></tr><tr><td><strong><code>Apuestas Promedio</code></strong></td><td>Promedio del valor apostado por giro. Se calcula como: <strong>Apuestas / NroSpin</strong>.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Total de premios obtenidos por el usuario a partir de las apuestas realizadas.</td></tr><tr><td><strong><code>Premios Bono</code></strong></td><td>Total de premios generados a partir de bonos o promociones otorgadas.</td></tr><tr><td><strong><code>Apuestas Saldo Gratis</code></strong></td><td>Valor total apostado utilizando saldo gratuito o créditos promocionales.</td></tr><tr><td><strong><code>GGR Bruto</code></strong></td><td>Resultado bruto del juego antes de deducciones. Se calcula como: <strong>Apuestas – Premios – Premios Bono</strong>.</td></tr></tbody></table>

***

### ✅ 8. Validaciones y Reglas de Negocio

* Las consultas solo se ejecutan si el usuario selecciona al menos un **rango de fechas válido**.
*   Si no existen datos para los filtros aplicados, el sistema mostrará el mensaje:

    > “No se obtuvieron datos para esta visualización.”
* Los cálculos de GGR y %GGR se realizan con base en la fórmula establecida:\
  **GGR =&#x20;**_**(Apuestas – Premios – Premios Bono)**_
* El tablero muestra los datos actualizados **en tiempo real, hora vencida**, dentro del rango **00:00:00 a 23:59:59** del día en curso o del día anterior.
* Las gráficas muestran siempre la información activa: si aplicas filtros, muestran lo filtrado; si seleccionas un dato en una tabla, se actualizan según esa selección.

***

### 🕒 9. Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados  |
| ------- | ---------- | ------------- | ------------------- |
| 1.0     | 15/10/2025 | Karol Navia   | Documento inicial.  |
| 1.1     | 25/11/2025 | Ronald Pelaez | Refinamiento manual |
