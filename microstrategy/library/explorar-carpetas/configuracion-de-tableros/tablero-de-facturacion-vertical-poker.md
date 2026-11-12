---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
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

# Tablero de Facturación – Vertical Poker

Este tablero permite visualizar y analizar la facturación de la [vertical](https://virtualsoft.gitbook.io/untitled/glosario#vertical) **Póker** de forma independiente a Casino, su objetivo es ofrecer una lectura clara del desempeño de Póker según su modelo de negocio, evitando distorsiones en los totales de otras verticales.

### **1. Acceso al Módulo**

**Ruta de Acceso**:

***

### **2.🖼️ Visualización**

<figure><img src="https://580350895-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FqV6PKDTPGEG39u2whMHJ%2Fuploads%2FO5j68QfMNwGVLOYIeoGg%2Fimage.png?alt=media&#x26;token=db3750be-a7d8-4b9b-8d61-1d1856e3527f" alt=""><figcaption><p>Figura #1: Captura de pantalla dashboartd reporte Póker.</p></figcaption></figure>

***

### **3.🧑‍💻 Acciones de usuario**

<table><thead><tr><th width="180">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Visualizar KPIs</strong></td><td>Permite consultar los indicadores clave de facturación de la <a href="https://virtualsoft.gitbook.io/untitled/glosario#vertical">vertical</a> Póker de forma independiente a Casino.</td></tr><tr><td><strong>Aplicar filtros</strong></td><td>Permite segmentar la información del tablero por partner, país, fecha, proveedor y día de la semana.</td></tr><tr><td><strong>Analizar tendencias</strong></td><td>Facilita la identificación de variaciones en apuestas, <a href="https://virtualsoft.gitbook.io/untitled/glosario#rake">rake</a>, <a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">GGR</a> y actividad de usuarios por período.</td></tr></tbody></table>

### **4.🔎Filtros del Dashboard**

<table><thead><tr><th width="181.66665649414062">Filtro</th><th width="141">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Selector</td><td>Filtra la información para un partner específico.</td></tr><tr><td><strong><code>País</code></strong></td><td>Selector</td><td>Restringe los resultados al país seleccionado.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Permite consultar datos por fecha o rango de fechas.</td></tr><tr><td><strong><code>Nombre proveedor</code></strong></td><td>Selector</td><td>Filtra la información por proveedor de la <a href="https://virtualsoft.gitbook.io/untitled/glosario#vertical">vertical</a> Póker.</td></tr><tr><td><strong><code>Día semana</code></strong></td><td>Selector</td><td>Permite analizar la información según el día de la semana.</td></tr></tbody></table>

### **5.🧑‍💻Contenido del Dashboard**

#### **5.1 📌 KPIs –** [**Vertical**](https://virtualsoft.gitbook.io/untitled/glosario#vertical) **Póker**

Los KPIs se calculan considerando únicamente los proveedores clasificados bajo la [vertical](https://virtualsoft.gitbook.io/untitled/glosario#vertical) Póker y respetan el modelo de negocio basado en [rake](https://virtualsoft.gitbook.io/untitled/glosario#rake).

<table><thead><tr><th width="243.33331298828125">KPI</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Cantidad de transacciones</code></strong></td><td>Total de movimientos registrados en la <a href="https://virtualsoft.gitbook.io/untitled/glosario#vertical">vertical</a> Póker durante el período seleccionado.</td></tr><tr><td><strong><code>Total de Apuestas</code></strong></td><td>Suma total apostada por los usuarios en juegos de Póker.</td></tr><tr><td><strong><code>Total de Premios pagados</code></strong></td><td>Valor total pagado a los usuarios como resultado de apuestas ganadoras.</td></tr><tr><td><strong><code>GGR</code></strong></td><td>Ingreso bruto de juego calculado como apuestas menos premios pagados.</td></tr><tr><td><strong><code>Total de</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario#rake"><strong><code>Rake</code></strong></a> <strong><code>generado</code></strong></td><td>Total de comisiones cobradas por la operación de Póker.</td></tr><tr><td><strong><code>Usuarios activos</code></strong></td><td>Cantidad de usuarios únicos con actividad en Póker durante el período consultado.</td></tr></tbody></table>

#### **5.2 📋 Tabla Facturación Póker**

La información presentada corresponde únicamente a la vertical Póker y se encuentra completamente desacoplada de la vertical Casino.

<table><thead><tr><th width="239.3333740234375">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Fecha a la que corresponden los registros de facturación.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Partner al que pertenecen los movimientos registrados.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado a la operación reportada.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Proveedor de la plataforma de Póker que genera la información.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Proveedor secundario o integración específica dentro del proveedor principal.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Nombre o tipo de juego de Póker asociado al registro.</td></tr><tr><td><strong><code>Usuarios activos</code></strong></td><td>Número de usuarios con actividad registrada en ese proveedor o juego.</td></tr><tr><td><strong><code>Cantidad de transacciones</code></strong></td><td>Total de transacciones procesadas en el período.</td></tr><tr><td><strong><code>Total de Apuestas</code></strong></td><td>Valor acumulado de apuestas realizadas.</td></tr><tr><td><strong><code>Total de Premios pagados</code></strong></td><td>Valor acumulado de premios liquidados por la <a href="https://virtualsoft.gitbook.io/untitled/glosario#vertical">vertical</a> póker.</td></tr><tr><td><a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr"><strong><code>GGR</code></strong></a></td><td>Resultado bruto obtenido por operación <em>(apuestas menos premios).</em></td></tr><tr><td><strong><code>Total de</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario#rake"><strong><code>Rake</code></strong></a> <strong><code>generado</code></strong></td><td>Total de comisiones generadas por mesas y torneos.</td></tr></tbody></table>

#### **5.3 📋 Gráficos**

<table><thead><tr><th width="186">Gráficos</th><th width="105">Tipo de gráfico</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Días de la semana con más actividad de usuarios</code></strong></td><td>Barras</td><td>Compara la cantidad de usuarios activos por cada día de la semana.</td></tr><tr><td><strong><code>GGR por mes en POKER</code></strong></td><td>Barras</td><td>Muestra la variación mensual del <a href="https://virtualsoft.gitbook.io/untitled/glosario#ggr">GGR</a> generado por la vertical Póker.</td></tr><tr><td><strong><code>Apuesta y</code></strong> <a href="https://virtualsoft.gitbook.io/untitled/glosario#rake"><strong><code>RAKE</code></strong></a> <strong><code>por periodo</code></strong></td><td>Lineal</td><td>Permite comparar la evolución de apuestas y <a href="https://virtualsoft.gitbook.io/untitled/glosario#rake">rake</a> a lo largo del tiempo.</td></tr></tbody></table>

***

### **6.✅ Validaciones y reglas de negocio**

* La vertical Póker se calcula de forma independiente a Casino.
* Solo se incluyen proveedores clasificados como Póker.
* Los totales no se mezclan entre verticales.

***

### **7.🕒Control de Versiones**

<table><thead><tr><th width="101.66668701171875">Versión</th><th width="197">Fecha</th><th width="154.66668701171875">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>26/01/2026</td><td>Ronald Peláez</td><td>Documento inicial</td></tr></tbody></table>
