# GetAccountDetails

Este diagrama describe el flujo completo para obtener detalles de una cuenta, desde la solicitud inicial hasta la respuesta, incluyendo validaciones de seguridad, reglas de negocio y manejo de errores.

<figure><img src="../../../.gitbook/assets/image (25).png" alt=""><figcaption><p>Figura #1: Captura de pantalla diagrama de flujo.</p></figcaption></figure>

#### Pasos Detallados:

1. Request&#x20;
   1. Inicia el proceso al recibir una solicitud de detalles de cuenta.&#x20;
2. GetAccountDetails&#x20;
   1. Función principal que gestiona la petición.&#x20;
3. SUCCESS&#x20;
   1. Confirmación de que la solicitud es válida y puede procesarse.&#x20;
4. validateToken&#x20;
   1. Valida el token de seguridad del usuario.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Token válido → avanza a validate (reglas de negocio).&#x20;
      2. ERROR: Token inválido → retorna error (returnDataError).&#x20;
5. validate&#x20;
   1. Valida todas las reglas de negocio (ej.: saldo mínimo, permisos, límites de cuenta, etc.).&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Cumple con todas las reglas → avanza a authenticate.&#x20;
      2. ERROR: Incumple alguna regla → retorna error (returnDataError).&#x20;
6. authenticate&#x20;
   1. Verifica credenciales adicionales si son requeridas.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Autenticación exitosa → retorna datos (returnDataSuccess).&#x20;
      2. ERROR: Fallo en autenticación → retorna error (returnDataError).&#x20;
7. Response&#x20;
   1. Devuelve al cliente:&#x20;
      1. Datos de la cuenta (returnDataSuccess).&#x20;
      2. Mensaje de error (returnDataError) si falló en cualquier paso previo.&#x20;
