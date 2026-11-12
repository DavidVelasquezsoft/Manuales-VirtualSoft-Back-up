# Manual técnico API (ejemplo)

## Servicio de Gestión de Recargas Virtuales

### 1. Descripción General

El Servicio de Gestión de Recargas Virtuales permite:

* Crear solicitudes de recarga.
* Consultar el estado de una recarga.
* Registrar transacciones en base de datos.
* Gestionar logs y errores del sistema.

Este servicio está diseñado bajo arquitectura RESTful y responde en formato JSON.

***

### 2. Arquitectura del Sistema

#### 2.1 Componentes

* **Controlador (Controller):** Maneja la entrada HTTP.
* **Servicio (Service):** Contiene la lógica de negocio.
* **Repositorio (Repository):** Gestiona persistencia en base de datos.
* **Cliente HTTP (si aplica):** Consume proveedor externo.

#### 2.2 Flujo General

1. Cliente envía solicitud HTTP.
2. El Controller valida la entrada.
3. El Service ejecuta la lógica de negocio.
4. El Repository persiste la información.
5. Se retorna respuesta estructurada en JSON.

***

### 3. Especificaciones Técnicas

<table><thead><tr><th width="287.3333740234375">Elemento</th><th>Valor</th></tr></thead><tbody><tr><td>Lenguaje</td><td>PHP 8.2</td></tr><tr><td>Base de Datos</td><td>MySQL 8</td></tr><tr><td>Formato de Respuesta</td><td>JSON</td></tr><tr><td>Autenticación</td><td>Token Bearer</td></tr><tr><td>Logs</td><td>Archivo local /logs/app.log</td></tr></tbody></table>

***

### 4. Endpoints Disponibles

#### 4.1 Crear Recarga

**Método:** POST\
**URL:** `/api/recargas`\
**Headers:**

```
Authorization: Bearer {token}
Content-Type: application/json
```

**Request Body**

```json
{
  "usuario_id": 15,
  "telefono": "3001234567",
  "valor": 20000,
  "operador": "CLARO"
}
```

**Validaciones**

* `usuario_id`: obligatorio, entero.
* `telefono`: obligatorio, 10 dígitos.
* `valor`: obligatorio, mayor a 0.
* `operador`: obligatorio, string.

**Response Exitosa (200)**

```json
{
  "status": "success",
  "message": "Recarga procesada correctamente",
  "data": {
    "recarga_id": 1025,
    "estado": "PROCESANDO"
  }
}
```

**Response Error (400)**

```json
{
  "status": "error",
  "message": "Datos inválidos"
}
```

***

#### 4.2 Consultar Estado de Recarga

**Método:** GET\
**URL:** `/api/recargas/{id}`

**Response Exitosa (200)**

```json
{
  "status": "success",
  "data": {
    "recarga_id": 1025,
    "telefono": "3001234567",
    "valor": 20000,
    "estado": "EXITOSA",
    "fecha_procesamiento": "2026-02-23 14:32:10"
  }
}
```

***

### 5. Modelo de Base de Datos

#### 5.1 Tabla: recargas

| Campo       | Tipo          | Descripción         |
| ----------- | ------------- | ------------------- |
| id          | INT (PK)      | Identificador único |
| usuario\_id | INT           | ID del usuario      |
| telefono    | VARCHAR(20)   | Número recargado    |
| valor       | DECIMAL(10,2) | Valor de la recarga |
| operador    | VARCHAR(50)   | Operador móvil      |
| estado      | VARCHAR(30)   | Estado actual       |
| created\_at | DATETIME      | Fecha creación      |
| updated\_at | DATETIME      | Fecha actualización |

***

### 6. Manejo de Errores

#### 6.1 Errores Controlados

* Validación de datos incorrectos.
* Usuario inexistente.
* Operador no soportado.

#### 6.2 Errores No Controlados

* Fallo de conexión a base de datos.
* Timeout con proveedor externo.
* Excepciones no capturadas.

Todos los errores son registrados en el archivo de logs.

***

### 7. Sistema de Logs

Ubicación: `/storage/logs/app.log`

Formato:

```
[YYYY-MM-DD HH:MM:SS] NIVEL: Mensaje | Contexto JSON
```

Ejemplo:

```
[2026-02-23 14:32:10] ERROR: Error al conectar con proveedor | {"recarga_id":1025}
```

***

### 8. Seguridad

* Validación estricta de entradas.
* Uso de prepared statements.
* Autenticación mediante token.
* No exposición de errores internos en producción.

***

### 9. Consideraciones Técnicas

* El servicio es síncrono.
* El tiempo máximo de espera con proveedor es 30 segundos.
* Se recomienda implementar reintentos automáticos en caso de timeout.
* El sistema debe escalar horizontalmente si supera 500 solicitudes por minuto.

***

### 10. Control de Versiones

| Versión | Fecha      | Cambios                        |
| ------- | ---------- | ------------------------------ |
| 1.0.0   | 2026-02-23 | Versión inicial                |
| 1.1.0   | 2026-03-01 | Se agrega endpoint de consulta |

***
