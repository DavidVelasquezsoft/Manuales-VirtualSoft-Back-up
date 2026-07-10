# Lista de Errores

Este es un listado de los posibles errores que se pueden encontrar al momento de utilizar la API.



1. **Errores de Autenticación y Sesión**&#x20;
   1. 10011: Token expirado → codeProveedor: 1&#x20;
   2. 21: Token expirado (caso especial) → codeProveedor: 90&#x20;
2. **Errores de Usuario**&#x20;
   1. 10013, 22: Usuario no encontrado → codeProveedor: 7&#x20;
   2. 100085, 20004: Usuario autoexcluido → codeProveedor: 10&#x20;
3. **Errores de Transacciones**&#x20;
   1. 10005: Transacción no existe → codeProveedor: 2&#x20;
   2. 20001: Fondos insuficientes → codeProveedor: 10&#x20;
4. **Errores de Bonos**&#x20;
   1. 300000, 300001: No existen bonos → codeProveedor: 15 y 16&#x20;
   2. 300002, 300003: Error general de bono → codeProveedor: 2 y 3&#x20;
5. **Errores Genéricos**&#x20;
   1. 0, 24, 27-29, 10004, 10014: Error general → codeProveedor: 2&#x20;
   2. default: Error no mapeado → codeProveedor: 99&#x20;
6. **Casos Exitosos**&#x20;
   1. 10001: OK → codeProveedor: 0 (idepotency)&#x20;

## Errores Frecuentes y Soluciones:

1. **Errores de Autenticación (Códigos 1, 90)**
   1. Caso:
      1. Token Expired (10011, 21)
   2. Revisar:
      1. Validez del token
      2. Configuración del tiempo de expiración
2. **Usuario No Encontrado (Código 7)**
   1. Caso:
      1. User not found (10013, 22)
   2. Sugerencias:
      1. Verificar sincronización de usuarios con el proveedor
      2. Confirmar que el ID de usuario esté correctamente codificado
3. **Fondos Insuficientes (Código 10)**
   1. Casos:
      1. Insufficient funds (20001), Usuario autoexcluido (100085, 20004)
   2. Acciones:
      1. Validar saldo antes de operar (validateBalance)
      2. Chequear restricciones de usuario en nuestro sistema
4. **Problemas con Bonos (Códigos 15, 16, 2, 3)**
   1. Casos:
      1. No existen bonos (300000, 300001), General Error (300002, 300003)
   2. Revisar:
      1. Existencia del bono en el proveedor (validateBonus)
      2. Reglas de asignación (fechas, límites por usuario)
5. **Errores Genéricos (Código 2, 99)**
   1. Caso:
      1. General Error (0, 24, 27-29, 10004, 10014)
   2. Debugging:
      1. Loggear el cuerpo completo de la respuesta del proveedor
      2. Verificar logs de transacciones previas
