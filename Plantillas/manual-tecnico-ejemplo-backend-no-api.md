# Manual técnico ejemplo backend (no api)

## Servicio de Cálculo de Comisiones

### 1. Descripción General

El archivo `ComisionService.php` es responsable de calcular las comisiones generadas por ventas realizadas en la plataforma.

Este componente:

* Recibe información de una venta.
* Aplica reglas de negocio según el tipo de usuario.
* Calcula porcentaje de comisión.
* Devuelve el valor final a registrar en base de datos.

No expone endpoints HTTP. Es utilizado internamente por el módulo de facturación.

***

### 2. Ubicación en el Proyecto

Ruta del archivo:

```
/app/Services/ComisionService.php
```

Dependencias directas:

* VentaRepository
* UsuarioRepository
* LoggerService

***

### 3. Responsabilidad del Componente

El servicio debe:

1. Validar que la venta exista.
2. Verificar el tipo de usuario.
3. Determinar el porcentaje aplicable.
4. Calcular el valor de comisión.
5. Retornar el resultado estructurado.

No debe:

* Persistir datos directamente.
* Manejar solicitudes HTTP.
* Renderizar vistas.

***

### 4. Flujo Interno

#### 4.1 Entrada

El método principal recibe:

* `venta_id` (int)

#### 4.2 Proceso

1. Se consulta la venta en base de datos.
2. Se obtiene el usuario asociado.
3. Se determina el tipo de usuario:
   * Básico
   * Premium
   * Corporativo
4. Se aplica regla de comisión:
   * Básico → 5%
   * Premium → 8%
   * Corporativo → 12%
5. Se calcula:

```
comision = valor_venta * porcentaje
```

6. Se retorna resultado.

#### 4.3 Salida

Estructura retornada:

```
[
  "venta_id" => int,
  "porcentaje" => float,
  "valor_comision" => float
]
```

***

### 5. Logica de Negocio

* La comisión solo se calcula si la venta está en estado `APROBADA`.
* Si la venta está `ANULADA`, se retorna comisión 0.
* Si el usuario no existe, se lanza excepción controlada.
* El porcentaje puede cambiar según configuración futura.

***

### 6. Manejo de Errores

Errores controlados:

* Venta no encontrada.
* Usuario no encontrado.
* Venta en estado inválido.

Errores no controlados:

* Fallo de conexión a base de datos.
* Excepción inesperada.

Todos los errores se registran en el sistema de logs.

***

### 8. Consideraciones de Rendimiento

* El servicio realiza 2 consultas a base de datos.
* No contiene operaciones costosas en memoria.
* El archivo depende de crons
  * cron 1: se ejecuta cada 15 min

***

### 9. Pruebas

Casos mínimos de prueba:

* Venta aprobada usuario básico.
* Venta aprobada usuario premium.
* Venta anulada.
* Venta inexistente.
* Usuario inexistente.

***

### 10. Historial de Cambios

| Versión | Fecha      | Cambio                         |
| ------- | ---------- | ------------------------------ |
| 1.0.0   | 2026-02-23 | Implementación inicial         |
| 1.1.0   | 2026-03-10 | Se agrega validación de estado |

***
