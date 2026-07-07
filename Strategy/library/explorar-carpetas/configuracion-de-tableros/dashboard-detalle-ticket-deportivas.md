---
description: >-
  Permite analizar en profundidad la información de tickets generados en la
  plataforma, incluyendo apuestas cerradas, valores apostados, cuotas, ganancias
  potenciales y reales.
---

# Dashboard detalle ticket deportivas

### Configuración General

### **1. Acceso al Módulo**

**Ruta de Acceso:** [Acceso directo.](https://reporting.virtualsoft.tech/MicroStrategyLibrary/app/3394329B42569ED3E0CDD1AABE6F7740/668D0D8342AB20C7CEB7F380F95DD2F3/W6E684F240A58418DBAF3C3DA0DB0A31A--K46)

***

### **2. Configuraciones Previas**

Antes de visualizar el reporte, es necesario establecer las [configuraciones previas.](https://virtualsoft.gitbook.io/manuales/microstrategy/tableros#id-2.-configuracion-previa)

***

### 3. Visualización:

<figure><img src="../../../.gitbook/assets/image (46).png" alt=""><figcaption><p><strong>Figura#1: Captura de pantalla Dashboard</strong></p></figcaption></figure>

### 4. 🔍 Filtros Disponibles

<table><thead><tr><th width="140">Filtro</th><th width="179">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Estado de la Apuesta</code></strong></td><td>Lista desplegable</td><td>Filtra por el estado actual de la apuesta <em>(ej. cashOut, Ganada, perdida).</em></td></tr><tr><td><strong><code>Cuota</code></strong></td><td>Buscador</td><td>Permite filtrar según la cuota definida en el ticket.</td></tr><tr><td><strong><code>Día</code></strong></td><td>Lista desplegable</td><td>Selecciona un día específico dentro del rango de fechas.</td></tr><tr><td><strong><code>Mercado</code></strong></td><td>Lista desplegable</td><td>Filtra por el mercado apostado <em>(ej. 1X2, Over/Under).</em></td></tr><tr><td><strong><code>Evento</code></strong></td><td>Lista desplegable</td><td>Filtra por el nombre del evento deportivo.</td></tr><tr><td><strong><code>Liga</code></strong></td><td>Lista desplegable</td><td>Filtra por la liga o competencia <em>(ej. Premier League).</em></td></tr><tr><td><strong><code>Deporte</code></strong></td><td>Lista desplegable</td><td>Filtra por la categoría deportiva <em>(ej. Fútbol, Tenis).</em></td></tr><tr><td><strong><code>Tipo de Evento</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar Prematch, Live, Mixta o Hípicas.</td></tr></tbody></table>

{% hint style="warning" %}
Nota: Los filtros _`Estado de la apuesta`_ y _`Cuota`_ son los principales; los demás filtros dependen de la información que se obtiene a partir de estos.
{% endhint %}

***

#### 4.1. Resultados de la Consulta

**Tabla Apuestas detalladas.**

<table><thead><tr><th width="170">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Partner</code></strong></td><td>Nombre del operador donde se generó el ticket.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al usuario que realizó la apuesta.</td></tr><tr><td><strong><code>ID Ticket</code></strong></td><td>Identificador único del ticket.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Código único del usuario que realizó la apuesta.</td></tr><tr><td><strong><code>Nombre del Evento</code></strong></td><td>Evento deportivo relacionado con la apuesta.</td></tr><tr><td><strong><code>Deporte</code></strong></td><td>Nombre de la categoría deportiva <em>(ej. Fútbol, Tenis)</em>.</td></tr><tr><td><strong><code>Liga</code></strong></td><td>Nombre de la competencia (<em>ej. Premier League</em>).</td></tr><tr><td><strong><code>Mercado</code></strong></td><td>Nombre del tipo de mercado apostado <em>(ej. 1X2, Over/Under).</em></td></tr><tr><td><strong><code>Modo de Apuesta</code></strong></td><td>Muestra si la apuesta es sencilla o combinada.</td></tr><tr><td><strong><code>Valor Apostado del Ticket</code></strong></td><td>Monto total invertido en el ticket.</td></tr><tr><td><strong><code>Valor Apostado por Evento</code></strong></td><td>Monto proporcional invertido en cada selección.<br><strong>Fórmula:</strong> <code>Valor total apostado ÷ Número de selecciones</code></td></tr><tr><td><strong><code>Cuota Neta</code></strong></td><td>Producto de todas las cuotas seleccionadas en el ticket.<br><strong>Fórmula:</strong> <code>Cuota 1 × Cuota 2 × … × Cuota n</code></td></tr><tr><td><strong><code>Equivalencia de Cuota</code></strong></td><td>Proporción de una cuota individual respecto al total de cuotas.<br><strong>Fórmula:</strong> <code>Cuota individual ÷ Suma total de cuotas</code></td></tr><tr><td><strong><code>Ganancia Potencial</code></strong></td><td>Monto que el usuario podría obtener si todas las selecciones son acertadas.<br><strong>Fórmula:</strong> <code>Valor apostado × Cuota neta</code></td></tr><tr><td><strong><code>Equivalencia de Ganancia</code></strong></td><td>Proporción de la ganancia potencial atribuida a cada selección.<br><strong>Fórmula:</strong> <code>Ganancia total esperada × Equivalencia de cuota</code></td></tr><tr><td><strong><code>Ganancia Real</code></strong></td><td>Monto efectivamente ganado tras el cierre de los eventos.</td></tr><tr><td><strong><code>Equivalencia de Ganancia Real</code></strong></td><td>Distribución proporcional de la ganancia real en función de cada selección acertada.</td></tr></tbody></table>

***

### 5.  Validaciones y Reglas de Negocio

* El dashboard está disponible únicamente para perfiles con permisos autorizados.

***

### 6. Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados  |
| ------- | ---------- | ------------- | ------------------- |
| 1.0     | 16/09/2025 | Karol Navia   | Documento inicial   |
| 1.1     | 24/11/2025 | Ronald Pelaez | Refinamiento manual |
