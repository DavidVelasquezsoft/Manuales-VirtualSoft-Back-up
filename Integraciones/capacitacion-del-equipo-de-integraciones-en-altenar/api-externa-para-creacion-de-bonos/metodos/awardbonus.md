# AwardBonus

Este diagrama describe el proceso para otorgar bonificaciones (AwardBonus), incluyendo validaciones de usuario, verificación de estado, creación del bono y confirmación final.

<figure><img src="../../../.gitbook/assets/image (16).png" alt=""><figcaption><p>Figura #1: Captura de pantalla diagrama de flujo.</p></figcaption></figure>

#### Pasos Detallados&#x20;

1. Request&#x20;
   1. Inicio del proceso al recibir una solicitud de otorgamiento de bono.&#x20;
2. AwardBonus&#x20;
   1. Función principal que gestiona la bonificación.&#x20;
3. validateUser&#x20;
   1. Validación del usuario.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Usuario válido → avanza a bonusBefore.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
4. bonusBefore&#x20;
   1. Verificación inicial de elegibilidad para el bono.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Cumple condiciones → avanza a validateBonus.&#x20;
      2. ERROR: No cumple → retorna returnDataError.&#x20;
5. validateBonus&#x20;
   1. Validación específica de las reglas del bono.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Bono válido → avanza a statusBonus.&#x20;
      2. ERROR: No cumple → avanza a createBonus.&#x20;
6. createBonus&#x20;
   1. Confirmación y registro final del bono a un usuario.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: → Bono válido → avanza a statusBonus.&#x20;
7. statusBonus&#x20;
   1. Verificación del estado del bono.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Estado adecuado → avanza a validate.&#x20;
      2. ERROR: Estado inválido → retorna returnDataError.&#x20;
8. validate&#x20;
   1. Validación final de condiciones.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Condiciones cumplidas → avanza a bonusCreate.&#x20;
9. bonusCreate&#x20;
   1. Proceso de creación del bono.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Bono creado → avanza a createBonus.&#x20;
      2. ERROR: Fallo en creación → retorna returnDataError.&#x20;
10. AwardBonus&#x20;
    1. Proceso de asignación del bono.&#x20;
    2. Ramas:&#x20;
       1. SUCCESS: Bono asignado → avanza a returnDataSuccess.&#x20;
       2. ERROR: Fallo en asignación → retorna returnDataError.&#x20;
11. Response&#x20;
    1. Entrega al cliente:&#x20;
       1. Confirmación exitosa (returnDataSuccess).&#x20;
       2. Mensaje de error (returnDataError) si falló en cualquier paso.&#x20;
