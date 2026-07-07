---
description: >-
  El Histórico de Saldos de Agentes es un reporte diseñado para proporcionar una
  visión detallada de los movimientos financieros y la gestión de los saldos de
  los agentes.
---

# Histórico Saldos Agentes

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Histórico Saldos Agentes

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (41).png" alt=""><figcaption><p>Figura #1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### 3. Funcionalidades

**📋 3.1 Acciones disponibles**

<table><thead><tr><th width="145">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtrar registros</strong></td><td>Permite aplicar filtros de búsqueda por usuario, concesionario, país o tipo de reporte.</td></tr><tr><td><strong>Visualizar tabla de resultados</strong></td><td>Presenta la información del historial de saldos según los filtros aplicados.</td></tr><tr><td><strong>Exportar los resultados</strong></td><td>Exporta en formato Excel la tabla de resultados según los filtros seleccionados.</td></tr></tbody></table>

**🔎 3.2 Filtros principales**

<table><thead><tr><th width="123">Campo</th><th width="155">Tipo de Control</th><th width="484">Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo de texto</td><td>Identificador único del agente para el cual se desea consultar el historial de saldos.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Calendario</td><td>Rango de fechas para filtrar las transacciones realizadas durante un período específico.</td></tr><tr><td><strong><code>ID Concesionario</code></strong></td><td>Campo de texto</td><td>Identificador del concesionario principal asociado al agente.</td></tr><tr><td><strong><code>Subconcesionario</code></strong></td><td>Campo de texto</td><td>Identificador del subconcesionario si se desea una consulta más específica.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Región o país correspondiente al agente o concesionario.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Clasificación de la visualización del reporte. Las opciones disponibles son:<br>Totales: muestra información resumida.<br>Detallado: proporciona información más específica y extensa.</td></tr></tbody></table>

**📊 Tabla de Resultados**

Los resultados de la consulta se presentan en una tabla con las siguientes columnas:

<table><thead><tr><th width="211">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Fecha y hora en que se registraron las transacciones o movimientos.</td></tr><tr><td><strong><code>País</code></strong></td><td>País asociado al agente o la operación.</td></tr><tr><td><strong><code>Saldo Inicial</code></strong></td><td>Saldo disponible al inicio del período consultado.</td></tr><tr><td><strong><code>Cupo Recargas Inicial</code></strong></td><td>Cupo inicial asignado para realizar recargas.</td></tr><tr><td><strong><code>Cupo Juego Inicial</code></strong></td><td>Cupo inicial asignado para operaciones de juego.</td></tr><tr><td><strong><code>Depósitos</code></strong></td><td>Total de depósitos realizados por el agente.</td></tr><tr><td><strong><code>Ap. Deportivas</code></strong></td><td>Total apostado en eventos deportivos.</td></tr><tr><td><strong><code>Pr. Deportivas</code></strong></td><td>Total ganado como premios en apuestas deportivas.</td></tr><tr><td><strong><code>Transf. Apuesta E</code></strong></td><td>Total de transferencias de apuestas recibidas.</td></tr><tr><td><strong><code>Transf. Apuesta S</code></strong></td><td>Total de transferencias de apuestas enviadas.</td></tr><tr><td><strong><code>Transf. Recarga E</code></strong></td><td>Total de transferencias de recargas recibidas.</td></tr><tr><td><strong><code>Transf. Recarga S</code></strong></td><td>Total de transferencias de recargas enviadas.</td></tr><tr><td><strong><code>Retiros Pagados</code></strong></td><td>Total de retiros pagados al agente.</td></tr><tr><td><strong><code>Recargas Eliminadas</code></strong></td><td>Cantidad de recargas eliminadas durante el período.</td></tr><tr><td><strong><code>Saldo Final</code></strong></td><td>Saldo disponible al final del período consultado.</td></tr><tr><td><strong><code>Saldo Final Calc.</code></strong></td><td>Saldo final calculado con base en las transacciones registradas.</td></tr><tr><td><strong><code>Calc. Desfase</code></strong></td><td>Diferencia entre el saldo final registrado y el saldo calculado.</td></tr><tr><td><strong><code>Cupo</code></strong></td><td>Cupo disponible al final del período consultado.</td></tr><tr><td><strong><code>Cupo Calc.</code></strong></td><td>Cupo calculado basado en las operaciones registradas.</td></tr></tbody></table>

***

### **4. Validaciones y Reglas de Negocio**

* No es obligatorio completar todos los filtros para realizar una búsqueda.
* La información mostrada dependerá de los filtros seleccionados en la consulta.
* El tipo de visualización seleccionado (Totales o Detallado) define el nivel de detalle mostrado en los resultados.

***

### **5. Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 08/10/2025 | Ronald Peláez | Documento inicial  |
