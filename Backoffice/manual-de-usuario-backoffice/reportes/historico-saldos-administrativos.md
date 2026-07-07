---
description: >-
  Este reporte permite consultar el historial de saldos administrativos
  aplicando diversos filtros.
---

# Histórico Saldos Administrativos

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Histórico Saldos Administrativos

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (42).png" alt=""><figcaption><p>Figura #1: Captura de pantalla de los filtros de búsqueda.</p></figcaption></figure>

***

### 3. Funcionalidades

**📋 3.1 Acciones disponibles**

<table><thead><tr><th width="163">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td>Filtrar registros</td><td>Permite aplicar filtros de búsqueda por usuario, país, fecha o tipo de reporte.</td></tr><tr><td>Visualizar tabla de resultados</td><td>Muestra la información del historial de saldos administrativos según los filtros aplicados.</td></tr><tr><td>Exportar los resultados</td><td>Exporta en formato Excel la tabla con los resultados filtrados.</td></tr></tbody></table>

**🔎 3.2 Filtros principales**

<table><thead><tr><th width="123">Campo</th><th width="155">Tipo de Control</th><th width="484">Descripción</th></tr></thead><tbody><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo de texto</td><td>Identificador único del usuario administrativo para el cual se desea consultar el historial.</td></tr><tr><td><strong><code>Fecha de Creación</code></strong></td><td>Calendario</td><td>Rango de fechas para filtrar los registros según su fecha de creación.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Región o país asociado al usuario administrativo.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Define el formato del reporte a consultar. Las opciones disponibles son:<br>Totales: muestra información resumida.<br>Detallado: proporciona información más específica y extensa.</td></tr></tbody></table>

#### **📊 Tabla de Resultados**

Dependiendo del tipo de reporte seleccionado, los resultados se presentan de la siguiente manera:

**Tipo Detallado**

La consulta mostrará una tabla con las siguientes columnas:

| Columna                     | Descripción                                                         |
| --------------------------- | ------------------------------------------------------------------- |
| **`Fecha de Creación`**     | Fecha y hora en que se registraron las transacciones o movimientos. |
| **`País`**                  | País asociado al usuario.                                           |
| **`ID Usuario`**            | Identificador único del usuario.                                    |
| **`Nombre Usuario`**        | Nombre del usuario administrativo.                                  |
| **`Saldo Inicial`**         | Saldo disponible al inicio del período consultado.                  |
| **`Cupo Recargas Inicial`** | Cupo inicial asignado para realizar recargas.                       |
| **`Cupo Juego Inicial`**    | Cupo inicial asignado para operaciones de juego.                    |
| **`Transf. Apuesta E`**     | Total de transferencias de apuestas recibidas.                      |
| **`Transf. Apuesta S`**     | Total de transferencias de apuestas enviadas.                       |

***

**Tipo Totales**

La consulta mostrará un resumen con los siguientes campos:

| Campo                       | Descripción                                        |
| --------------------------- | -------------------------------------------------- |
| **`Fecha de Creación`**     | Fecha en que se registraron las operaciones.       |
| **`País`**                  | País asociado al usuario.                          |
| **`Saldo Inicial`**         | Saldo disponible al inicio del período consultado. |
| **`Cupo Recargas Inicial`** | Cupo inicial asignado para realizar recargas.      |
| **`Cupo Juego Inicial`**    | Cupo inicial asignado para operaciones de juego.   |
| **`Transf. Apuesta E`**     | Total de transferencias de apuestas recibidas.     |
| **`Transf. Apuesta S`**     | Total de transferencias de apuestas enviadas.      |

***

### 4. Validaciones y Reglas de Negocio

* No es obligatorio completar todos los filtros para realizar una búsqueda.
* La información mostrada dependerá de los filtros y del tipo de reporte seleccionado.
* En el tipo “Detallado”, la tabla mostrará todos los movimientos asociados al usuario.
* En el tipo “Totales”, los valores reflejan un resumen consolidado del período consultado.

***

### 5. Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 08/10/2025 | Ronald Peláez | Documento inicial  |
