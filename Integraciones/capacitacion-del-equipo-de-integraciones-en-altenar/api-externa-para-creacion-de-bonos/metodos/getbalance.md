# GetBalance

Este diagrama describe el proceso para obtener el balance de una cuenta, desde la solicitud inicial hasta la respuesta, incluyendo validaciones de seguridad, reglas de negocio y manejo de errores.

<figure><img src="../../../.gitbook/assets/image (24).png" alt=""><figcaption><p>Figura #1: Captura de pantalla diagrama de flujo.</p></figcaption></figure>

#### Pasos Detallados:

1. Request&#x20;
   1. Inicia cuando el sistema recibe una solicitud para consultar el balance (GetBalance).&#x20;
2. GetBalance&#x20;
   1. Función principal que procesa la petición.&#x20;
3. SUCCESS&#x20;
   1. Confirma que la solicitud es válida y puede proceder.&#x20;
4. validateToken&#x20;
   1. Verifica la autenticidad del token de seguridad.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Token válido → avanza a validate (reglas de negocio).&#x20;
      2. ERROR: Token inválido → retorna error (returnDataError).&#x20;
5. validate&#x20;
   1. Valida todas las reglas de negocio (ej.: cuenta activa, límites de acceso, etc.).&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Cumple todas las reglas → avanza a getBalance.&#x20;
      2. ERROR: No cumple alguna regla → retorna error (returnDataError).&#x20;
6. getBalance&#x20;
   1. Recupera el balance de la cuenta desde la base de datos o sistema externo.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Datos obtenidos → retorna información (returnDataSuccess).&#x20;
      2. ERROR: No cumple alguna regla → retorna error (returnDataError).&#x20;
7. Response&#x20;
   1. Entrega al cliente:&#x20;
      1. El balance solicitado (returnDataSuccess).&#x20;
      2. Mensaje de error (returnDataError) si falló en cualquier paso previo.&#x20;

&#x20;
