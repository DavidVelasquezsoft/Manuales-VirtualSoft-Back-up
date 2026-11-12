# Checklist de Revisión de Integración

Aquí encontrarás un checklist básico sobre casos a tener en cuenta al momento de utilizar la API.

### Antes de Implementar:

* **Configuración**:&#x20;
  * API Keys y endpoints correctos (dev/prod).
  * Tiempos de timeout definidos.
* **Validaciones**:&#x20;
  * Flujos mapeados según documentación (PlaceBet, RefundBet, etc.).&#x20;
  * Códigos de error integrados (Anexo 1).

### Pruebas:

* **Casos de Éxito**:&#x20;
  * Creación de bonos.&#x20;
  * Registro de apuestas.&#x20;
* **Errores**:&#x20;
  * Simular token expirado.&#x20;
  * Fondos insuficientes.&#x20;
  * Usuario no encontrado.

### Post-Implementación&#x20;

* **Monitoreo**:&#x20;
  * Alertas para errores críticos (ej: código 99).&#x20;
  * Dashboard de transacciones fallidas.&#x20;
* **Documentación**:&#x20;
  * Actualizar cambios en endpoints del proveedor.&#x20;
  * Registrar nuevos códigos de error.

## Recomendación Final:&#x20;

* Realizar pruebas en entorno _sandbox_ antes de producción.&#x20;
* Documentar cualquier cambio en los endpoints o reglas de negocio externas.&#x20;
