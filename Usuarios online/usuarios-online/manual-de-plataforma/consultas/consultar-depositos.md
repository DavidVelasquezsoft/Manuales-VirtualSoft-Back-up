---
description: >-
  En esta sección podrás visualizar el histórico de los depósitos que has
  realizado en tu cuenta, con la opción de buscar la información mediante
  filtros de fechas.
---

# Consultar depositos

### Configuración general

#### 1. Acceso al Módulo:

**Ruta de Acceso**: Menú principal → Consultas → Consultar depósitos

***

#### 2. Visualización:

<figure><img src="../../../.gitbook/assets/image (174) (1).png" alt=""><figcaption><p><strong>Figura #1</strong>: Captura de pantalla – Consulta de depósitos</p></figcaption></figure>

***

#### 2.1. Filtros de búsqueda:

| Campo        | Tipo de Control | Descripción                                                      | Validaciones                                                |
| ------------ | --------------- | ---------------------------------------------------------------- | ----------------------------------------------------------- |
| Fecha Inicio | Calendario      | Fecha desde la cual se desea consultar los depósitos realizados. | Campo obligatorio. Formato: DD/MM/AAAA.                     |
| Fecha Fin    | Calendario      | Fecha hasta la cual se desea consultar.                          | Campo obligatorio. No debe ser anterior a la fecha inicial. |

***

#### 2.2. Resultados mostrados:

| Campo                   | Descripción                                                          |
| ----------------------- | -------------------------------------------------------------------- |
| `Número de Depósito`    | Identificador único del depósito realizado.                          |
| `Fecha Depósito`        | Fecha en la que se realizó el depósito.                              |
| `Medio`                 | Método utilizado para realizar el depósito (Ej. PSE, tarjeta, etc.). |
| `Código de Transacción` | Código generado por el sistema o entidad financiera.                 |
| `Valor`                 | Monto depositado por el usuario.                                     |
| `Bono`                  | Valor adicional otorgado como bono (si aplica).                      |
| `Total`                 | Suma del valor depositado más el bono recibido.                      |
| `Moneda`                | Tipo de moneda en la que se hizo el depósito (Ej. COP, USD).         |

***

### Validaciones y Reglas de Negocio

* Deben seleccionarse ambas fechas para ejecutar la consulta.
* El sistema solo mostrará los depósitos realizados dentro del rango de fechas seleccionado.
* El campo de bono puede estar vacío si no se recibió beneficio adicional en el depósito.

***

### Control de Versiones

| Versión | Fecha      | Autor       | Cambios Realizados                      |
| ------- | ---------- | ----------- | --------------------------------------- |
| 1.0     | 22/07/2025 | Karol Navia | Versión inicial – Consulta de depósitos |
