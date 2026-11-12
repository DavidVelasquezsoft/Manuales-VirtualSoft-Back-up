---
description: >-
  En esta sección podrás consultar el historial de tickets de tus apuestas
  deportivas realizadas en la plataforma.
---

# Consulta de apuestas deportivas

### Configuración general

#### 1. Acceso al Módulo:

**Ruta de Acceso**: Menú principal → Consultas → Consulta de apuestas deportivas

***

#### 2. Visualización:

📌 **Figura #1**: Captura de pantalla – Consulta de tickets de apuestas deportivas

***

#### 2.1. Acciones del Usuario:

| Campo           | Tipo de Control | Descripción                                                     | Validaciones                                                             |
| --------------- | --------------- | --------------------------------------------------------------- | ------------------------------------------------------------------------ |
| `Fecha inicial` | Calendario      | Fecha desde la cual se desea consultar las apuestas.            | Campo obligatorio. Formato: DD/MM/AAAA.                                  |
| `Fecha final`   | Calendario      | Fecha hasta la cual se desea consultar las apuestas.            | Campo obligatorio. No debe ser anterior a la fecha inicial.              |
| `Estado`        | Selector        | Permite alternar entre apuestas "Abiertas" o "Resueltas".       | Selección opcional.                                                      |
| `Resultado`     | Visualización   | Área donde se muestran los tickets según los filtros aplicados. | Se muestra mensaje si no hay apuestas en el rango o estado seleccionado. |

***

### Validaciones y Reglas de Negocio

* El sistema no mostrará resultados si no existen apuestas en el rango de fechas seleccionado.
* El uso de los campos de fecha es obligatorio para ejecutar la consulta.
* Las etiquetas "Abierto" y "Resuelto" corresponden al estado actual del ticket.
* Las validaciones pueden cambiar dependiendo del **partner**.

***

### Control de Versiones

| Versión | Fecha      | Autor       | Cambios Realizados                          |
| ------- | ---------- | ----------- | ------------------------------------------- |
| 1.0     | 22/07/2025 | Karol Navia | Documento inicial de la sección de consulta |
