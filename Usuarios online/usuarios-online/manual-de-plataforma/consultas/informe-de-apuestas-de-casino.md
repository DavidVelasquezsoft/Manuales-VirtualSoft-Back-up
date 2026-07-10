---
description: >-
  En esta sección podrás visualizar el histórico de las apuestas que has
  realizado desde la sección de juegos casino. Aquí podrás filtrar por fechas
  para obtener el detalle de tus tickets de juego.
---

# Informe de apuestas de casino

### Configuración general

#### 1. Acceso al Módulo:

**Ruta de Acceso**: Menú principal → Consultas → Informe de otras apuestas

***

#### 2. Visualización:

<figure><img src="../../../.gitbook/assets/image (173) (1).png" alt=""><figcaption><p><strong>Figura #1</strong>: Captura de pantalla – Informe de otras apuestas</p></figcaption></figure>

Al dar clic en el botón **Buscar**, se cargará automáticamente la información correspondiente a las fechas seleccionadas. El resultado se muestra en la tabla ubicada en la parte inferior de la pantalla.

#### 2.1. Acciones del Usuario:

| Campo        | Tipo de Control | Descripción                                                                | Validaciones                                                |
| ------------ | --------------- | -------------------------------------------------------------------------- | ----------------------------------------------------------- |
| Fecha Inicio | Calendario      | Fecha desde la cual se desea consultar el historial de apuestas de casino. | Campo obligatorio. Formato: DD/MM/AAAA.                     |
| Fecha Fin    | Calendario      | Fecha hasta la cual se desea consultar el historial.                       | Campo obligatorio. No debe ser anterior a la fecha inicial. |

📌 Nota: Las validaciones pueden variar dependiendo del **partner**.

***

### Validaciones y Reglas de Negocio

* Se deben ingresar ambas fechas para ejecutar la consulta.
* El sistema no cargará datos si no existen registros en el rango de fechas seleccionado.
* Las validaciones pueden estar sujetas a reglas específicas definidas por cada **partner**.

***

### Control de Versiones

| Versión | Fecha      | Autor       | Cambios Realizados                                        |
| ------- | ---------- | ----------- | --------------------------------------------------------- |
| 1.0     | 22/07/2025 | Karol Navia | Documento inicial para informe de otras apuestas (casino) |
