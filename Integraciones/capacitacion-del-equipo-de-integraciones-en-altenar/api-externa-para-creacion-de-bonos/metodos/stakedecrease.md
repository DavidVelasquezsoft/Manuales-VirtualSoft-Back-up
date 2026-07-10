# StakeDecrease

Este diagrama describe el proceso para manejar una reducción de apuesta (StakeDecrease), donde se devuelve parcialmente el monto debitado inicialmente, registrándose como un crédito al usuario. Incluye validaciones de usuario, verificación del débito original y actualización del saldo.

<figure><img src="../../../.gitbook/assets/image (21).png" alt=""><figcaption><p>Figura #1: Captura de pantalla diagrama de flujo.</p></figcaption></figure>

Pasos Detallados&#x20;

1. Request
   1. Inicia al recibir solicitud de reducción de apuesta.&#x20;
2. StakeDecrease&#x20;
   1. Función principal del proceso.&#x20;
3. validateUser&#x20;
   1. Valida identidad y estado del usuario.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Usuario válido → avanza a debitBefore.&#x20;
      2. ERROR: Usuario inválido → retorna returnDataError.&#x20;
4. debitBefore&#x20;
   1. Verifica existencia del débito original a reducir.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Débito existe → avanza a Open Status.&#x20;
      2. ERROR: Débito no encontrado → retorna returnDataError.&#x20;
5. Open Status&#x20;
   1. Confirma que el estado permite la reducción.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Estado válido → avanza a validate.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
6. validate&#x20;
   1. Verifica integridad de la operación.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Datos correctos → avanza a stateDecrease.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
7. stateDecreas&#x20;
   1. Calcula y aplica la reducción (registra como crédito).&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Reducción aplicada → avanza a generateToken3.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
8. generateToken3&#x20;
   1. Genera identificador de usuario.
   2. Rama:&#x20;
      1. SUCCESS: → retorna returnDataSuccess.&#x20;
9. Response&#x20;
   1. Resultado final:&#x20;
      1. Confirmación con nuevo saldo (returnDataSuccess).&#x20;
      2. Error (returnDataError) si falló validaciones.
