# Autoexclusión.

## Autoexclusión

### Configuración general

#### 1. Acceso al Módulo:

**Ruta de Acceso**: Menú principal → Autoexclusión

***

#### 2. Visualización:

En la parte superior de la sección se muestra una descripción informativa sobre en qué consiste la autoexclusión.

<figure><img src="../../../.gitbook/assets/image (23) (2).png" alt=""><figcaption></figcaption></figure>

Debajo del texto, el usuario podrá configurar los parámetros de su autoexclusión mediante un formulario:

<figure><img src="../../../.gitbook/assets/image (24) (2).png" alt=""><figcaption></figcaption></figure>

***

#### 🧑‍💻 3. Acciones del Usuario

| Sección                     | Acción               | Descripción                                                                  |
| --------------------------- | -------------------- | ---------------------------------------------------------------------------- |
| Formulario de configuración | Ingreso de datos     | Define el tipo, el período y el motivo de autoexclusión.                     |
| Botón "Guardar"             | Confirmación         | Guarda la solicitud de autoexclusión si todos los campos fueron completados. |
| Tabla de registros          | Consulta y anulación | Permite visualizar el historial de autoexclusiones y anular si aplica.       |

***

#### 📋 4. Campos del formulario de Autoexclusión

| Campo                         | Tipo de control  | Descripción                                                               | Observaciones                                              |
| ----------------------------- | ---------------- | ------------------------------------------------------------------------- | ---------------------------------------------------------- |
| Tipo                          | Menú desplegable | Permite seleccionar la vertical a excluir.                                | Opciones: Sportsbook, Virtual Sport, Casino, Live Casino.  |
| Fecha Límite de Autoexclusión | Menú desplegable | Define el período durante el cual la autoexclusión estará activa.         | Opciones: 1 día, 1 semana, 1 mes, 3 meses, 6 meses, 1 año. |
| Motivo de Autoexclusión       | Campo de texto   | Permite ingresar el motivo por el cual se desea activar la autoexclusión. | Campo obligatorio.                                         |
| Guardar                       | Botón            | Guarda la configuración ingresada.                                        |                                                            |

***

{% hint style="warning" %}
**Nota:** Selecciona cuidadosamente el período de autoexclusión, ya que, una vez activado, no podrá ser revertido hasta que hayan transcurrido al menos 24 horas.
{% endhint %}

***

#### 📄 5. Tabla de autoexclusiones registradas

Una vez guardada la autoexclusión, se listará en la tabla inferior con la siguiente información:

| Columna               | Descripción                                                                                                      |
| --------------------- | ---------------------------------------------------------------------------------------------------------------- |
| ID                    | Identificador único del registro de autoexclusión.                                                               |
| Anular                | Botón disponible para cancelar la autoexclusión, habilitado luego de transcurridas 24 horas desde su activación. |
| Tipo                  | Vertical o línea de producto seleccionada para la autoexclusión.                                                 |
| Fecha de Creación     | Fecha en la que se generó la autoexclusión.                                                                      |
| Fecha de Finalización | Fecha en la que la autoexclusión expira automáticamente.                                                         |
| Estado                | Estado actual de la autoexclusión.                                                                               |

**Estados posibles:**

* **Activo**: La autoexclusión está en vigor. No se puede acceder a la vertical seleccionada.
* **Inactivo**: La autoexclusión ha finalizado. El usuario puede volver a acceder a la vertical.
* **Cancelado**: La autoexclusión fue anulada antes de la fecha de finalización.

***

#### 🕒 6. Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados            |
| ------- | ---------- | ------------- | ----------------------------- |
| 1.0     | 23/07/2025 | Ronald Peláez | Documento inicial del módulo. |
