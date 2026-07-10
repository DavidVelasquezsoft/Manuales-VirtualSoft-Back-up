# PlaceBet

Este diagrama describe el proceso completo para realizar una apuesta (PlaceBet), incluyendo validaciones de seguridad, usuario, saldo, verificación de transacción única y registro final de la apuesta.

<figure><img src="../../../.gitbook/assets/image (100).png" alt=""><figcaption><p>Figura #1: Captura de pantalla diagrama de flujo.</p></figcaption></figure>

#### Pasos Detallados:

1. Request&#x20;
   1. Inicio del proceso al recibir una solicitud de apuesta.&#x20;
2. PlaceBet&#x20;
   1. Función principal que gestiona la petición.&#x20;
3. SUCCESS&#x20;
   1. Confirmación de que la solicitud es válida y puede procesarse.&#x20;
4. validateToken&#x20;
   1. Valida el token de seguridad del usuario.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Token válido → avanza a validate (reglas de negocio).&#x20;
      2. ERROR: Token inválido → retorna error (returnDataError).&#x20;
5. validate&#x20;
   1. Valida todas las reglas de negocio (ej.: juego disponible, límites de apuesta, etc.).&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Cumple todas las reglas → avanza a validateUser.&#x20;
      2. ERROR: No cumple alguna regla → retorna error (returnDataError).&#x20;
6. validateUser&#x20;
   1. Verifica el estado y permisos del usuario.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Usuario válido → avanza a validateBalance.&#x20;
      2. ERROR: No cumple alguna regla → retorna error (returnDataError).&#x20;
7. validateBalance&#x20;
   1. Confirma que el usuario tiene saldo suficiente.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Saldo adecuado → avanza a placeBet.&#x20;
      2. ERROR: No cumple alguna regla → retorna error (returnDataError).&#x20;
8. validateTxId&#x20;
   1. Verificación de que el ID de transacción no existe previamente&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: TxID no existe → avanza a placeBet.&#x20;
      2. ERROR: TxID duplicado → retorna error (returnDataError).&#x20;
9. placeBet&#x20;
   1. Registra la apuesta en el sistema.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Apuesta registrada → avanza a generateToken2.&#x20;
      2. ERROR: No cumple alguna regla → retorna error (returnDataError).&#x20;
10. generateToken2&#x20;
    1. Genera un nuevo token de usuario.&#x20;
11. Response&#x20;
    1. Devuelve al cliente:&#x20;
       1. Confirmación de apuesta (returnDataSuccess).&#x20;
       2. Mensaje de error (returnDataError) si falló en cualquier paso.
