# AwardWinnings

Este diagrama describe el proceso para adjudicar premios (AwardWinnings), incluyendo validaciones de usuario, verificación de estado, ejecución del premio y generación de comprobante.

<figure><img src="../../../.gitbook/assets/image (101).png" alt=""><figcaption><p>Figura #1: Captura de pantalla diagrama de flujo.</p></figcaption></figure>

#### Pasos Detallados:

1. Request&#x20;
   1. Inicio del proceso al recibir una solicitud de adjudicación de premios.&#x20;
2. AwardWinnings&#x20;
   1. Función principal que gestiona la adjudicación.&#x20;
3. validateUser&#x20;
   1. Validación del usuario.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Usuario válido → avanza a debitBefore.&#x20;
      2. ERROR: Fallo en verificación → retorna returnDataError.&#x20;
4. debitBefore&#x20;
   1. Verificación inicial de existencia o estado.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Condiciones cumplidas → avanza a Open Status.&#x20;
      2. ERROR: Fallo en verificación → retorna returnDataError.&#x20;
5. Open Status&#x20;
   1. Verificación de estado abierto para adjudicación.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Estado válido → avanza a AwardWinning.&#x20;
      2. ERROR: Fallo en verificación → retorna returnDataError.&#x20;
6. validate&#x20;
   1. Valida todas las reglas de negocio (ej.: juego disponible, límites de apuesta, etc.).&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Cumple todas las reglas → avanza a awardBefore.&#x20;
      2. ERROR: No cumple alguna regla → retorna error (returnDataError).&#x20;
7. awardBefore&#x20;
   1. Valida que no exista una ganancia previa asociada a la ronda.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Cumple todas las reglas → avanza a AwardWinning.&#x20;
      2. ERROR: No cumple alguna regla → retorna error (returnDataError).&#x20;
8. AwardWinning&#x20;
   1. Proceso de adjudicación del premio.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Premio adjudicado → avanza a generateToken2.&#x20;
      2. ERROR: Fallo en verificación → retorna returnDataError.&#x20;
9. generateToken2&#x20;
   1. Generación de identificador de usuario.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: → retorna returnDataSuccess.&#x20;
10. Response&#x20;
    1. Entrega al cliente:
       1. Confirmación exitosa (returnDataSuccess).&#x20;
       2. Mensaje de error (returnDataError) si falló en cualquier paso.&#x20;
