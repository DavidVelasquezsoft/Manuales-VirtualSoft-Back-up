# Anular nota retiro.

### Configuración general

#### 1. Acceso al Módulo:

**Ruta de Acceso**: Menú principal → Gestión → Anular nota retiro.

***

#### 2. Visualización:

<figure><img src="../../../.gitbook/assets/image (27) (2).png" alt=""><figcaption><p>Figura #1: Captura de pantalla anular nota de retiro.</p></figcaption></figure>

**🧑‍💻 2.1. Acciones del Usuario**

| Sección         | Tipo de control    | Acción                                                  |
| --------------- | ------------------ | ------------------------------------------------------- |
| Filtro de tabla | selección múltiple | Filtra la tabla de las notas de retiro según el estado. |

**2.2. Tabla notas de retiro:**

| Campo              | Descripción                                                                                   |
| ------------------ | --------------------------------------------------------------------------------------------- |
| No. Nota de retiro | Visualiza el Número asociado a la nota de retiro.                                             |
| Botón anular       | Elimina la nota de retiro y retorna el saldo al usuario para que le permita seguir apostando. |
| Tipo               | Visualiza el medio por el cual se generó la nota de retiro                                    |
| Estado             | Visualiza el estado en el que se encuentra la nota de retiro                                  |
| Fecha de creación  | Fecha en la que se generó la nota de retiro.                                                  |
| Valor              | Monto por el cual se generó la nota de retiro                                                 |
| Moneda             | Tipo de divisa por el cual se generó la nota de retiro.                                       |

***

**✅ 3. Validaciones y Reglas de Negocio**

* Al generarse una nota de retiro, el valor correspondiente será descontado del saldo del usuario. En caso de que la nota sea anulada, dicho monto se reintegrará automáticamente al saldo, quedando nuevamente disponible para realizar apuestas.

***

**🕒 4. Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados                      |
| ------- | ---------- | ------------- | --------------------------------------- |
| 1.0     | 17/07/2025 | Ronald Peláez | Sección de inicio de sesión incorporada |
