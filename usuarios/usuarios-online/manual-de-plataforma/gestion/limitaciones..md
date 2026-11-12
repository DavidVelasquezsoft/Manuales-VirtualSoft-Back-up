# Limitaciones.

En la sección de **Limitaciones**, puedes establecer restricciones voluntarias para fomentar el juego responsable. Aquí podrás limitar montos relacionados con depósitos o apuestas, definidos por tipo de actividad y por un periodo de tiempo determinado.

***

## Configuración general

### 1. Acceso al Módulo:

**Ruta de Acceso**: Menú principal → Limitaciones

***

### 2. Visualización

<figure><img src="https://3756725920-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FI1JHf1oqcL4UapE69pFw%2Fuploads%2FMtctdkHrj4sHpT2kHDYn%2Fimage.png?alt=media&#x26;token=382a8d5b-93d7-4650-9d99-3135f9f8b84c" alt=""><figcaption><p>Figura #1: Captura de pantalla sección Limitaciones.</p></figcaption></figure>

### 3.🧑‍💻 Formulario de limitaciones

| Elemento             | Tipo de Control   | Descripción                                                                                                                     |
| -------------------- | ----------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| Tipo                 | Lista de opciones | Permite seleccionar la actividad a la que se le aplicará la limitación (Depósito, Apuestas Deportivas, Casino, Casino en Vivo). |
| Periodo de Tiempo    | Lista de opciones | Define el intervalo en el que estará activa la limitación (día, semana o mes).                                                  |
| Monto                | Campo numérico    | Valor máximo permitido para gastar o depositar durante el periodo indicado.                                                     |
| Motivo de Limitación | Campo de texto    | Campo libre para detallar la razón de la restricción.                                                                           |
| Guardar              | Botón             | Guarda y aplica la limitación configurada.                                                                                      |

***

#### 3.1. Tabla de visualización de registros

En la parte inferior se muestra una tabla con todas las limitaciones configuradas:

| Columna           | Descripción                                                                                                                                                                                                                                   |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ID                | Identificador único de la limitación.                                                                                                                                                                                                         |
| Anular            | Botón para cancelar la limitación. Solo disponible después de 24 horas desde su creación.                                                                                                                                                     |
| Periodo de Tiempo | Duración de la limitación activa (día, semana o mes).                                                                                                                                                                                         |
| Tipo              | Actividad sobre la que se aplica la limitación.                                                                                                                                                                                               |
| Estado            | <p>Estado actual de la limitación:<br>- <strong>Activo</strong>: la limitación está en vigor.<br>- <strong>Inactivo</strong>: expiró o fue desactivada.<br>- <strong>Cancelado</strong>: fue anulada manualmente antes de su vencimiento.</p> |
| Fecha generación  | Fecha en la que se creó la limitación.                                                                                                                                                                                                        |
| Fecha de Fin      | Fecha en que la limitación deja de estar vigente.                                                                                                                                                                                             |
| Valor             | Monto límite configurado.                                                                                                                                                                                                                     |

***

### 4. Validaciones y reglas de negocio

* La opción de anular una limitación solo estará habilitada 24 horas después de haber sido creada.
* El sistema validará que no existan varias limitaciones activas para el mismo tipo y periodo.

***

### 5. Control de versiones

| Versión | Fecha      | Autor         | Cambios Realizados          |
| ------- | ---------- | ------------- | --------------------------- |
| 1.0     | 23/07/2025 | Ronald Pelaez | Documento funcional inicial |
