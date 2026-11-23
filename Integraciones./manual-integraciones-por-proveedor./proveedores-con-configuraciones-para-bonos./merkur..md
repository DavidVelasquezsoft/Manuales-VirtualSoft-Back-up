---
description: >-
  En este documento se detallan únicamente los campos y consideraciones
  particulares que aplican al momento de crear un bono FreeSpin específicamente
  para el proveedor Merkur.
---

# Merkur.

#### Configuración general

**1. Acceso al Módulo:**

**Ruta de Acceso**: BackOffice > Torneos y Bonos > Bono FreeSpin

***

**2. Visualización**

<figure><img src="https://2840730235-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FpVk1Kqoe0aInaa5Ofl6i%2Fuploads%2FFUlicOkqx8uXklhf4Ref%2Fimage.png?alt=media&#x26;token=56f20060-ef27-4750-a5e2-995f108717a7" alt="" width="563"><figcaption><p>Figura #1: Captura de pantalla de la sección FreeSpin.</p></figcaption></figure>

***

#### 🧑‍💻 3. Acciones del Usuario

<table><thead><tr><th>Sección</th><th width="236">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td>Rango de fechas</td><td>Botón "Agregar"</td><td>Permite seleccionar la fecha inicial y final de vigencia del bono.</td></tr><tr><td>Botón proveedores</td><td>Lista desplegable (Dropdown)</td><td>Despliega los proveedores con Bonus System activo. Seleccionar "Merkur".</td></tr><tr><td>Botón productos</td><td>Lista desplegable (Dropdown)</td><td>Seleccionar nuevamente "Merkur" para ver los juegos disponibles.</td></tr><tr><td>Valor por ronda</td><td>Texto numérico</td><td>Define el monto del bono por cada jugada gratuita.</td></tr><tr><td>Rondas gratuitas</td><td>Texto numérico</td><td>Ingresa la cantidad de rondas gratuitas que se asignarán al bono.</td></tr><tr><td>Jugadores</td><td>Archivo CSV</td><td>Cargar el archivo en formato .csv con los ID de usuarios que recibirán el bono.</td></tr></tbody></table>

{% hint style="warning" %}
📌 _Nota: Los campos marcados con un asterisco (\*_) en el formulario son obligatorios.
{% endhint %}

***

#### ✅ 4. Validaciones y Reglas de Negocio

* Al seleccionar **Proveedores** y **Productos**, se mostrará una tabla donde se debe definir el porcentaje del bono que asumirá el proveedor.
*   El valor ingresado en el campo **Valor por ronda** debe coincidir exactamente con el permitido por el juego, En caso que no coincida el numero , el bono no se activara.

    <div data-gb-custom-block data-tag="hint" data-style="info" class="hint hint-info"><p><strong>Ejemplo:</strong> Si el juego permite máximo 5 y se configura 10, el bono no funcionará.</p></div>
* Los ID de los jugadores deben estar correctamente estructurados en el archivo .CSV, ya que el sistema activa automáticamente los bonos según este archivo.
* Solo se podrán seleccionar juegos disponibles del proveedor **Merkur**.
* La selección de moneda es obligatoria para habilitar los campos del bono.
* Si ocurre un error durante la ejecución del juego, se mostrará un mensaje emergente (pop-up) y se redireccionará al lobby.

***

#### 📘 Glosario

| Término          | Definición                                                                |
| ---------------- | ------------------------------------------------------------------------- |
| Valor por ronda  | Monto económico asignado a cada jugada gratuita otorgada por el bono.     |
| Rondas gratuitas | Cantidad total de jugadas que se asignan al jugador como parte del bono.  |
| CSV              | Archivo de valores separados por comas, debe contener los ID de usuarios. |
| Bono FreeSpin    | Bono que otorga jugadas gratuitas en juegos específicos.                  |

***

#### 🕒 5. Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados            |
| ------: | ---------- | ------------- | ----------------------------- |
|     1.0 | 18/07/2025 | Ronald Peláez | Aplicación inicial de formato |
