# CashoutBet

Este diagrama describe el proceso para manejar un retiro voluntario de apuesta (CashoutBet), donde se convierte un débito existente en un crédito al usuario, previa validación de que no exista un cashout previo y que el débito esté abierto.

<figure><img src="../../../.gitbook/assets/image (22).png" alt=""><figcaption><p>Figura #1: Captura de pantalla diagrama de flujo.</p></figcaption></figure>

Pasos Detallados&#x20;

1. Request&#x20;
   1. Inicia al recibir solicitud de retiro voluntario (cashout).&#x20;
2. CashoutBet&#x20;
   1. Función principal del proceso.&#x20;
3. validateUser&#x20;
   1. Verifica identidad y estado del usuario.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Usuario válido → avanza a debitBefore.&#x20;
      2. ERROR: Usuario inválido → retorna error.&#x20;
4. debitBefore&#x20;
   1. Confirma existencia del débito/apuesta a retirar.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Débito existe → avanza a Open Status.&#x20;
      2. ERROR: No existe débito → retorna returnDataError.&#x20;
5. Open Status&#x20;
   1. Verifica que el débito esté abierto para cashout.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Estado "abierto" → avanza a CashoutBefore.&#x20;
      2. ERROR: No existe débito → retorna returnDataError.&#x20;
6. CashoutBefore&#x20;
   1. Valida que no exista un cashout previo para esta apuesta.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: No hay cashouts anteriores → avanza a validate.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
7. validate&#x20;
   1. Chequea consistencia de datos para el retiro.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Datos válidos → avanza a procesamiento principal.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
8. CashoutBet&#x20;
   1. Convierte el débito en crédito (retiro efectivo).
   2. Rama:&#x20;
      1. SUCCESS: Retiro exitoso → genera returnDataSuccess.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
9. Response&#x20;
   1. Retorna:&#x20;
      1. Confirmación con detalles del crédito (returnDataSuccess).&#x20;
      2. Error (returnDataError) si falló en validaciones.&#x20;
