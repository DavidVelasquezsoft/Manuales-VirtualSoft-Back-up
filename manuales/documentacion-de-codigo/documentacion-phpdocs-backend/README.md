---
description: >-
  Este manual contiene la plantilla de la documentación y una guía de errores
  comunes
---

# Documentación PHPdocs (Backend)

#### 📦 Propiedad de clase

```php
/**
 * Descripción de la propiedad.
 *
 * @var Tipo
 */
public $propiedad;
```

**Ejemplo:**

```php
/**
 * Conector de base de datos principal.
 *
 * @var PDO
 */
private $conexion;
```

***

#### 🧩 Variable local

```php
/** @var Tipo Descripción breve. */
$variable = valor;
```

**Ejemplo:**

```php
/** @var int Cantidad de ítems. */
$contador = 0;
```

***

#### ⚙️ Función o método

```php
/**
 * Descripción clara de lo que hace la función.
 *
 * @param Tipo $ejm  Descripción del parámetro.
 * @param Tipo $ejm2 Descripción del parámetro.
 *
 * @throws ExceptionTipo Condición bajo la cual lanza la excepción.
 *
 * @return Tipo Qué devuelve esta función.
 */
function nombreFuncion($ejm, $ejm2) {
    // ...
}
```

**Ejemplo real:**

```php
/**
 * Calcula el total aplicando descuento.
 *
 * @param float $subtotal  Monto sin descuento.
 * @param float $descuento Porcentaje de descuento.
 *
 * @throws InvalidArgumentException Si el descuento excede 100%.
 *
 * @return float Total con el descuento aplicado.
 */
function calcularTotal($subtotal, $descuento) {
    // ...
}
```

***

#### 🧱 Clase

```php
/**
 * Descripción general de la clase.
 *
 * @package App\Módulo
 * @author 
 * @license MIT
 */
class NombreClase {
    // ...
}
```

***

#### 🗂️ Orden recomendado de tags

1. `@param`
2. `@throws`
3. `@return`

> **Nota:** Nunca pongas `@return` antes de `@param` .

***

#### 🏷️ Tags válidos y su propósito

| Tag        | Propósito                                  |
| ---------- | ------------------------------------------ |
| `@param`   | Describe un parámetro de entrada.          |
| `@return`  | Indica qué devuelve la función.            |
| `@throws`  | Excepciones que pueden lanzarse.           |
| `@var`     | Tipo de una propiedad o variable.          |
| `@package` | Agrupa clases por módulo o carpeta lógica. |
| `@license` | Tipo de licencia del archivo.              |
| `@since`   | Desde qué versión está disponible.         |
| `@see`     | Referencia externa o relacionada.          |

***

#### ✅ Buenas prácticas

* ✅ Comienza las descripciones con **mayúscula**.
* ✅ Finaliza con **punto** si es una oración completa.
* ✅ Usa nombres de parámetros iguales a los usados en la función.
* ✅ Agrupa los tags siempre en este orden: `@param`, `@throws`, `@return`.
* ❌ No uses tags inventados como `@example`, `@todo`.
* ✅ Documenta incluso funciones privadas si tienen lógica crítica.

***

## 🛠️ Errores comunes y soluciones

***

**Mensaje en logs:**\
`Missing function doc comment`

❌ Incorrecto:

```php
function procesarPago($monto) {
    // lógica de pago
}
```

✅ Solución:

```php
/**
 * Procesa un pago según el monto especificado.
 *
 * @param float $monto Monto a procesar.
 *
 * @return bool `true` si el pago fue exitoso, `false` en caso contrario.
 */
function procesarPago($monto) {
    // lógica de pago
}
```

📌 **Nota:** Si la función **no retorna nada**, **no pongas `@return` con tipo incorrecto**, ni pongas descripción falsa.

***

#### 🛑 Error: Missing parameter type

**Mensaje en logs:**\
`Missing parameter type`

❌ Incorrecto:

```php
/**
 * Guarda el usuario.
 *
 * @param $usuario
 */
function guardar($usuario) {
    // ...
}
```

✅ Solución:

```php
/**
 * Guarda el usuario.
 *
 * @param array $usuario Datos del usuario.
 */
function guardar(array $usuario) {
    // ...
}
```

***

#### 🛑 Error: Missing member variable doc comment

**Mensaje en logs:**\
`Missing member variable doc comment`

❌ Incorrecto:

```php
private $conector;
```

✅ Solución:

```php
/**
 * Conector de base de datos.
 *
 * @var PDO
 */
private $conector;
```

***

#### 🛑 Error: Expected "@var" type but found "texto"

**Mensaje en logs:**\
`Expected "@var" type but found "texto"`

❌ Incorrecto:

```php
/** @var texto */
public $nombre;
```

✅ Solución:

```php
/** @var string */
public $nombre;
```

🎯 Tipos válidos recomendados:\
`string`, `int`, `float`, `bool`, `array`, `object`, `mixed`, `callable`, `iterable`, `DateTime`, `PDO`, etc.

***

#### 🛑 Error: Comentario sin descripción

**Mensaje en logs:** _(cuando el bloque PHPDoc no tiene descripción inicial)_

❌ Incorrecto:

```php
/**
 *
 * @param string $nombre
 */
```

✅ Recomendado:

```php
/**
 * Retorna el saludo para un usuario.
 *
 * @param string $nombre Nombre del usuario.
 *
 * @return string Mensaje de saludo.
 */
```

***

#### 🛑 Error: Missing tag @return

**Mensaje en logs:**\
`Missing tag @return`

❌ Incorrecto:

```php
/**
 * Calcula el total.
 *
 * @param float $subtotal
 */
function calcular($subtotal) {
    return $subtotal * 1.19;
}
```

✅ Solución:

```php
/**
 * Calcula el total con IVA.
 *
 * @param float $subtotal Subtotal sin impuestos.
 *
 * @return float Total con IVA incluido.
 */
function calcular($subtotal) {
    return $subtotal * 1.19;
}
```

***

#### 🛑 Error: Function return type is not void, but function has no return

**Mensaje en logs:**\
`Function return type is not void, but function has no return`

❌ Incorrecto:

```php
/**
 * Establece el monto.
 *
 * @param float $monto
 * @return Void función que retorna el monto
 */
public function setMonto($monto) {
    $this->monto = $monto;
}
```

✅ Solución correcta (si **no retorna nada**):

```php
/**
 * Establece el monto.
 *
 * @param float $monto Monto del pago.
 *
 * @return void
 */
public function setMonto($monto): void {
    $this->monto = $monto;
}
```

✅ Alternativa correcta (si retorna `$this`):

```php
/**
 * Establece el monto y permite encadenamiento.
 *
 * @param float $monto Monto del pago.
 *
 * @return self
 */
public function setMonto($monto): self {
    $this->monto = $monto;
    return $this;
}
```

📌 **Importante:**

* `@return Void` (con mayúscula) es inválido → debe ser `@return void`
* Si la función **no tiene `return`**, debes declarar `:void` en la firma y documentar `@return void`.

{% hint style="info" %}
**Nota**: self se usa para indicar que una función retorna una instancia de su propia clase.
{% endhint %}

***

#### 🛑 Error: Superfluous parameter comment **Mensaje en logs:** `Superfluous parameter comment`

🔍 Esto pasa cuando documentas un parámetro en el PHPDoc que **no está en la función**.

**❌ Incorrecto:**

```php
/**
 * Suma dos números.
 *
 * @param int $a
 * @param int $b
 * @param int $extra Un parámetro extra
 *
 * @return int
 */
function sumar($a, $b) {
    return $a + $b;
}
```

**✅ Solución:**

```php
/**
 * Suma dos números.
 *
 * @param int $a Primer número.
 * @param int $b Segundo número.
 *
 * @return int Resultado de la suma.
 */
function sumar($a, $b) {
    return $a + $b;
}
```

***

#### 🛑 Error: Missing parameter comment **Mensaje en logs:** `Missing parameter comment`

🔍 Pasa cuando pones `@param` con tipo y nombre, **pero sin descripción**.

**❌ Incorrecto:**

```php
/**
 * Guarda un dato.
 *
 * @param string $nombre
 *
 * @return void
 */
function guardar($nombre): void {
    // ...
}
```

**✅ Solución:**

```php
/**
 * Guarda un dato.
 *
 * @param string $nombre Nombre del dato a guardar.
 *
 * @return void
 */
function guardar($nombre): void {
    // ...
}
```

<details>

<summary>🔽<strong>Historial de versiones.</strong></summary>

<table><thead><tr><th width="91">Versión</th><th width="110">Fecha</th><th width="342">Cambios</th><th>Responsable</th></tr></thead><tbody><tr><td>1.0</td><td>24/11/2026</td><td>Documento inicial</td><td>Ronald Peláez</td></tr></tbody></table>

</details>
