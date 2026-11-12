# BonusBalance

Este diagrama describe el proceso para acreditar el balance de un bono (BonusBalance), verificando su existencia, asignación a usuario y estado, con la capacidad de asignarlo si no está vinculado.

<figure><img src="../../../.gitbook/assets/image (17).png" alt=""><figcaption><p>Figura #1: Captura de pantalla diagrama de flujo.</p></figcaption></figure>

#### Pasos Detallados:

1. Request&#x20;
   1. Inicia al recibir solicitud de acreditación de bono.&#x20;
2. BonusBalance&#x20;
   1. Función principal del proceso.&#x20;
3. validateUser&#x20;
   1. Valida usuario existente.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Usuario válido → avanza a validateBonus.&#x20;
      2. ERROR: Usuario no válido → retorna returnDataError.&#x20;
4. validateBonus&#x20;
   1. Verifica existencia del bono.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Bono existe → avanza a statusBonus.
      2. ERROR: Bono no existe → retorna returnDataError.&#x20;
5. statusBonus&#x20;
   1. Chequea estado actual del bono.
   2. Ramas:&#x20;
      1. SUCCESS: Estado válido → avanza a asigneUser Bono\_A.&#x20;
      2. ERROR: Estado inválido → ejecuta searchUser.&#x20;
6. asigneUser Bono\_A&#x20;
   1. Asigna la ganancia del bono al usuario.&#x20;
   2. Ramas:&#x20;
      1. SUCCESS: Estado válido → avanza a validate.&#x20;
7. searchUser (Flujo alternativo)&#x20;
   1. Busca usuario asignable al bono (Bono\_E = bono existente).&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Usuario encontrado → asigna y va a createUser.&#x20;
8. createUser Bono\_E&#x20;
   1. Asigna bono a usuario nuevo o existente.&#x20;
   2. Rama:
      1. SUCCESS: Asignación exitosa → avanza a validate.&#x20;
9. updateUser Bono\_E (Flujo principal)&#x20;
   1. Actualiza balance del usuario con el bono.&#x20;
   2. Rama:&#x20;
      1. SUCCESS: Actualización exitosa → va a validate.&#x20;
10. validate&#x20;
    1. Validación final de condiciones.&#x20;
    2. Rama:&#x20;
       1. SUCCESS: Condiciones cumplidas → avanza a BonusBalance.&#x20;
11. BonusBalance&#x20;
    1. Asignación de la ganancia otorgada por el bono.&#x20;
    2. Rama:&#x20;
       1. SUCCESS: Condiciones cumplidas → avanza a returnDataSuccess.&#x20;
       2. ERROR: Bono no existe → retorna returnDataError.&#x20;
12. runDataSuccess&#x20;
    1. Prepara datos de respuesta exitosa.&#x20;
    2. Rama:&#x20;
       1. SUCCESS: → retorna returnDataSuccess.&#x20;
13. Response&#x20;
    1. Resultado final:&#x20;
       1. Confirmación con datos actualizados (returnDataSuccess).&#x20;
       2. Error (returnDataError) si falló en pasos críticos.&#x20;
