# RefundBet

Este diagrama describe el proceso para manejar devoluciones de apuestas (RefundBet), donde se reversa un débito existente siempre que el débito no esté cerrado, no tenga una ganancia asociada registrada y cumpla con todas las validaciones de seguridad.

<figure><img src="../../../.gitbook/assets/image (23).png" alt=""><figcaption><p>Figura #1: Captura de pantalla diagrama de flujo.</p></figcaption></figure>

Pasos Detallados&#x20;

1. Request&#x20;
   1. Inicia al recibir solicitud de devolución desde API externa o por fallos internos&#x20;
2. RefundBet&#x20;
   1. Función principal que gestiona el proceso completo&#x20;
3. validateUser&#x20;
   1. Verifica identidad y permisos del usuario&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Usuario válido → avanza a debitBefore&#x20;
      2. ERROR: Usuario inválido → retorna error&#x20;
4. debitBefore&#x20;
   1. Confirma existencia del débito a devolver&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Débito existe → avanza a Open Status&#x20;
      2. ERROR: Débito no encontrado → retorna returnDataError&#x20;
5. Open Status&#x20;
   1. Verifica que el débito esté en estado "abierto"&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Estado correcto → avanza a winBefore.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
6. winBefore&#x20;
   1. Valida que no exista ganancia registrada para esta apuesta&#x20;
   2. Rama:&#x20;
      1. SUCCESS: No hay ganancia → avanza a validate&#x20;
      2. ERROR: Ganancia existente → retorna returnDataError&#x20;
7. validate&#x20;
   1. Chequeo final de consistencia de datos&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Datos válidos → avanza a procesamiento principal.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
8. RefundBet&#x20;
   1. ecuta la devolución completa del débito
   2. Rama:&#x20;
      1. SUCCESS: Devolución exitosa → genera refundDataSuccess.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
9. Response&#x20;
   1. Retorna:&#x20;
      1. Confirmación de devolución (refundDataSuccess).&#x20;
      2. Error (returnDataError) si falló validaciones.&#x20;
