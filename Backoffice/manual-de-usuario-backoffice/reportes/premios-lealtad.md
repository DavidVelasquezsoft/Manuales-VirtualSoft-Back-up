---
description: >-
  El Reporte permite consultar y auditar los premios redimidos por los usuarios
  según su nivel de lealtad, validando condiciones como nivel requerido, tipo de
  premio y estado de entrega.
---

# Premios lealtad

### Configuración General

### 1. Acceso al Módulo

**Ruta de acceso:**\
BackOffice > Reportes > Premios Lealtad

**URL:**[🔗 Acceso directo al reporte](https://admin.virtualsoft.tech/#/top/prizesLoyalty)

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (33).png" alt=""><figcaption><p><strong>Figura #1: Captura de pantalla</strong> reporte de Premios Lealtad.</p></figcaption></figure>

***

### 3.🧑‍💻 Acciones del Usuario

| Sección                                                       | Tipo               | Descripción                                                                                        |
| ------------------------------------------------------------- | ------------------ | -------------------------------------------------------------------------------------------------- |
| [**Filtros**](premios-lealtad.md#id-3.1.-filtros-disponibles) | Campos de búsqueda | Permiten aplicar condiciones sobre los datos que se desean consultar.                              |
| **Consultar**                                                 | Botón              | Ejecuta la consulta con los filtros aplicados.                                                     |
| **Limpiar**                                                   | Botón              | Restaura todos los filtros a sus valores por defecto.                                              |
| 📤 Exportar                                                   | Botón              | El botón Exportar permite descargar los resultados obtenidos en los formatos Excel _(.XLS)_ y PDF. |

***

#### 🎛️ 3.1. Filtros Disponibles

<table><thead><tr><th width="186">Campo</th><th width="160">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>ID</strong></td><td>Numérico</td><td>Filtra por el ID del registro.</td></tr><tr><td><strong>ID Usuario</strong></td><td>Numérico</td><td>Filtra por el identificador del usuario.</td></tr><tr><td><strong>ID Casino</strong></td><td>Numérico</td><td>Filtra por el casino asociado.</td></tr><tr><td><strong>Estado</strong></td><td>Lista desplegable</td><td>Filtra por el estado del regalo <em>(ej. Comprado, Entregado).</em></td></tr><tr><td><strong>Fecha</strong></td><td>Calendario</td><td>Fecha en que fue entregado el regalo.</td></tr><tr><td><strong>Fecha Modificó</strong></td><td>Rango de fechas</td><td>Fecha de última modificación del registro.</td></tr><tr><td><strong>País</strong></td><td>Lista desplegable</td><td>Filtra por país de origen del usuario.</td></tr><tr><td><strong>ID Regalo</strong></td><td>Numérico</td><td>Filtra por identificador del regalo.</td></tr><tr><td><strong>Tipo</strong></td><td>Lista desplegable</td><td>Filtra por tipo de premio <em>(ej. Online, fisico).</em></td></tr><tr><td><strong>Nivel del jugador</strong></td><td>Lista desplegable</td><td>Filtra por el nivel de lealtad del jugador al momento de redimir.</td></tr><tr><td><strong>Nivel requerido del regalo</strong></td><td>Lista desplegable</td><td>Filtra por el nivel mínimo requerido para redimir el regalo.</td></tr></tbody></table>

#### 📋 3.2. Columnas del Resultado

<table><thead><tr><th width="229">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>ID</strong></td><td>Identificador único del registro.</td></tr><tr><td><strong>ID Regalo</strong></td><td>Identificador del regalo entregado.</td></tr><tr><td><strong>Fecha</strong></td><td>Fecha en la que se entregó el premio.</td></tr><tr><td><strong>Fecha Modificó</strong></td><td>Fecha de última modificación del registro.</td></tr><tr><td><strong>ID Usuario</strong></td><td>Identificador del usuario.</td></tr><tr><td><strong>ID Casino</strong></td><td>identificador de Casino asociado al usuario.</td></tr><tr><td><strong>Estado</strong></td><td>Estado actual del premio <em>(ej. Comprado, Entregado).</em></td></tr><tr><td><strong>Descripción Premio</strong></td><td>Detalle del bono entregado <em>(ej. regalo por nivel 8).</em></td></tr><tr><td><strong>Tipo Premio</strong></td><td>Tipo de bono entregado <em>(ej. Online).</em></td></tr><tr><td><a href="premios-lealtad.md#glosario"><strong>Nivel Jugador</strong></a></td><td>Nivel de lealtad del jugador al momento de redimir el regalo.</td></tr><tr><td><a href="premios-lealtad.md#glosario"><strong>Nivel Requerido del Regalo</strong></a></td><td>Nivel mínimo requerido para poder reclamar ese regalo.</td></tr><tr><td><strong>Observación</strong></td><td>Comentarios adicionales relacionados con el registro.</td></tr></tbody></table>

***

### 4.📘 Glosario

| Término                        | Definición                                                                   |
| ------------------------------ | ---------------------------------------------------------------------------- |
| **Nivel del jugador**          | Nivel lealtad que tenía el usuario al momento de redimir el regalo.          |
| **Nivel requerido del regalo** | Nivel lealtad mínimo necesario para que el regalo fuera visible o redimible. |

***



### 5.🕒 Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados       |
| ------- | ---------- | ------------- | ------------------------ |
| 1.0     | 28/07/2025 | Karol Navia.  | Documento inicial creado |
| 1.0     | 22/10/2025 | Ronald Peláez | Refinamiento de manual   |
