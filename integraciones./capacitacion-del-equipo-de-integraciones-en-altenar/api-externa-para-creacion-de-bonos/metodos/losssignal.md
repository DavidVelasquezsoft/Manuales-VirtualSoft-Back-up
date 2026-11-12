# LossSignal

Este diagrama describe el proceso para registrar una pérdida en una apuesta (LossSignal), donde se acredita una ganancia de 0 al usuario, incluyendo validaciones de usuario, estado y confirmación del resultado.

<figure><img src="../../../.gitbook/assets/image (18).png" alt=""><figcaption><p>Figura #1: Captura de pantalla diagrama de flujo.</p></figcaption></figure>

#### Pasos Detallados:

1. Request&#x20;
   1. Inicia al recibir la solicitud de registro de pérdida.&#x20;
2. LossSignal&#x20;
   1. Función principal del proceso.&#x20;
   2. validateUser&#x20;
   3. Valida la existencia y estado del usuario.&#x20;
   4. Rama:&#x20;
      1. SUCCESS: Usuario válido → avanza a debitBefore.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
3. debitBefore&#x20;
   1. Verifica condiciones iniciales para el registro.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Cumple requisitos → avanza a Open Status.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
4. Open Status&#x20;
   1. Confirma que el estado permite registrar la pérdida.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Estado válido → avanza a LawardBefore.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
5. awardBefore&#x20;
   1. Verifica que no exista un registro de ganancia.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: → avanza a LossSignal (proceso principal).&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
6. LossSignal&#x20;
   1. Registra oficialmente la pérdida con ganancia 0.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Registro exitoso → avanza a generateToken2.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
7. generateToken2&#x20;
   1. Genera identificador de usuario.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: → retorna returnDataSuccess.&#x20;
8. Response&#x20;
   1. Entrega resultado final:&#x20;
      1. Confirmación (returnDataSuccess).&#x20;
      2. Error (returnDataError) si falló en validaciones.&#x20;
