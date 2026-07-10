# NewDebit

Este diagrama describe el proceso para registrar un nuevo débito sobre uno existente (NewDebit), independientemente de su estado de cierre, incluyendo validaciones de usuario, token, saldo y estado.

<figure><img src="../../../.gitbook/assets/image (20).png" alt=""><figcaption><p>Figura #1: Captura de pantalla diagrama de flujo.</p></figcaption></figure>

#### Pasos Detallados:

1. Request&#x20;
   1. Inicia al recibir la solicitud de nuevo débito.&#x20;
2. NewDebit&#x20;
   1. Función principal del proceso.&#x20;
3. validateUser&#x20;
   1. Valida la existencia y estado del usuario.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Usuario válido → avanza a validateToken2.&#x20;
      2. ERROR: Token inválido → retorna returnDataError.&#x20;
4. validateToken2&#x20;
   1. Verifica token de seguridad secundario.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Token válido → avanza a debugBefore.&#x20;
      2. ERROR: Token inválido → retorna returnDataError.&#x20;
5. debitBefore&#x20;
   1. Verifica integridad del débito anterior.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Débito válido → avanza a Open Status.&#x20;
      2. ERROR: Problema con débito → retorna returnDataError.&#x20;
6. Open Status&#x20;
   1. Evalúa estado del débito de referencia (sin bloquear por estado cerrado).&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Continúa proceso (independiente del estado) → avanza a validateBalance.&#x20;
7. validateBalance&#x20;
   1. Confirma saldo suficiente para el nuevo débito.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Saldo ok → avanza a NewDebit (proceso principal).&#x20;
      2. ERROR: Saldo insuficiente → retorna returnDataError.&#x20;
8. validate&#x20;
   1. Valida los datos para procesar el nuevo débito.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Datos correctos → avanza a newCredit.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
9. NewDebit&#x20;
   1. Registra el nuevo débito vinculado al anterior.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Débito registrado → avanza a generateToken3.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
10. generateToken3&#x20;
    1. Genera identificador de usuario.&#x20;
    2. Rama:&#x20;
       1. SUCCESS: → retorna returnDataSuccess.&#x20;
       2. ERROR: No cumple → retorna returnDataError.&#x20;
11. Response&#x20;
    1. Entrega resultado:&#x20;
       1. Confirmación (returnDataSuccess).&#x20;
       2. Error (returnDataError) si falló en validaciones.&#x20;
