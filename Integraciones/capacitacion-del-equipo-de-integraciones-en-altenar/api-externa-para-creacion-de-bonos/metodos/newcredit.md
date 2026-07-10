# NewCredit

Este diagrama describe el proceso para acreditar una nueva ganancia sobre un débito anterior (NewCredit), independientemente del estado de cierre, incluyendo validaciones de usuario, verificación del débito previo y registro de la nueva acreditación.

<figure><img src="../../../.gitbook/assets/image (19).png" alt=""><figcaption><p>Figura #1: Captura de pantalla diagrama de flujo.</p></figcaption></figure>

#### Pasos Detallados:

1. Request&#x20;
   1. Inicia al recibir la solicitud de nueva acreditación.&#x20;
2. NewCredit&#x20;
   1. Función principal del proceso.&#x20;
3. validateUser&#x20;
   1. Valida la existencia y estado del usuario.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Usuario válido → avanza a debitBefore.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
4. debitBefore&#x20;
   1. Verifica la existencia del débito anterior.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Débito existe → avanza a Open Status.&#x20;
      2. ERROR: Débito no existe → retorna returnDataError.&#x20;
5. Open Status&#x20;
   1. Evalúa el estado actual del débito (opcional, según flujo).&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Continúa el proceso a NewCredit (independientemente del estado).&#x20;
      2. ERROR: Flujo alternativo (NewCredit).&#x20;
6. awardBefore&#x20;
   1. Confirmación final de que no exista el nuevo crédito antes de completar el proceso.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: → Datos correctos → avanza a validate.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
7. validate&#x20;
   1. Valida los datos de la acreditación realizada.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Datos correctos → avanza a newCredit.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
8. NewCredit&#x20;
   1. Procesa la nueva acreditación sobre el débito.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Acreditación exitosa → avanza a response.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
9. Response&#x20;
   1. Entrega resultado final:&#x20;
      1. Confirmación de acreditación (returnDataSuccess).&#x20;
      2. Error (returnDataError) si falló en validaciones iniciales.
