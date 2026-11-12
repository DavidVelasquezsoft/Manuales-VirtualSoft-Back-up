---
description: >-
  En esta sección podrás visualizar el histórico de los retiros que has
  realizado en tu cuenta, con la opción de buscar la información con los filtros
  de fechas.
---

# Consultar retiros

### Configuración general

#### 1. Acceso al Módulo:

**Ruta de Acceso**: Menú principal → Consultas → Consultar retiros

***

#### 2. Visualización:

<figure><img src="../../../.gitbook/assets/image (175) (1).png" alt=""><figcaption><p><strong>Figura #1</strong>: Captura de pantalla sección consulta de retiros</p></figcaption></figure>

***

#### 2.1. Filtros de búsqueda:

| Campo        | Tipo de Control | Descripción                                                    | Validaciones                                                |
| ------------ | --------------- | -------------------------------------------------------------- | ----------------------------------------------------------- |
| Fecha Inicio | Calendario      | Fecha desde la cual se desea consultar los retiros realizados. | Campo obligatorio. Formato: DD/MM/AAAA.                     |
| Fecha Fin    | Calendario      | Fecha hasta la cual se desea consultar.                        | Campo obligatorio. No debe ser anterior a la fecha inicial. |

***

#### 2.2. Resultados mostrados:

| Campo            | Descripción                                                                       |
| ---------------- | --------------------------------------------------------------------------------- |
| Número de Retiro | Identificador único del retiro realizado.                                         |
| Medio            | Método utilizado para realizar el retiro (Ej. transferencia, corresponsal, etc.). |
| Estado           | Estado actual del retiro (Ej. aprobado, pendiente, rechazado).                    |
| Fecha Retiro     | Fecha en la que se solicitó el retiro.                                            |
| Fecha Pago       | Fecha en la que se procesó el pago del retiro.                                    |
| Valor            | Monto solicitado para retiro.                                                     |
| Moneda           | Tipo de moneda del retiro (Ej. COP, USD).                                         |

***

### Validaciones y Reglas de Negocio

* Ambos campos de fecha son obligatorios para realizar la búsqueda.
* La fecha de fin no puede ser anterior a la fecha de inicio.
* Los resultados solo muestran los retiros realizados dentro del rango de fechas establecido.

***

### Control de Versiones

| Versión | Fecha      | Autor       | Cambios Realizados                    |
| ------- | ---------- | ----------- | ------------------------------------- |
| 1.0     | 22/07/2025 | Karol Navia | Versión inicial – Consulta de retiros |
