# UC-05.1 - Virement bancaire (Inter profil.)

### Définitions 
AML: Anti money laundering 

### Objectif:
Permettre un transfert de fonds sécurisé.

### Généralités
* Acteur principal: Client
* Déclencheur: Requête de transfert.
* Pré-conditions: Être authentifié, avoir un compte avec les fonds suffisants, que le compte visé existe.
* Postconditions(succès): Le compte visé à la somme transférée. Le compte initial n'a plus la somme transférée 

### Flux Principal
1. Le client sélectionne l'action de transfert.
2. Le client sélectionne un montant à transférer.
3. Le système vérifie si le compte a assez de fonds.
4. Le système vérifie si le compte visé existe
5. La somme est transférée.

### Critère d'acceptation
La somme est transférée d'un compte à l'autre.
Les clients sont notifiés du transfert.

## Notes de concpetion
Ce use case est divisée en deux. Cette partie concerne le transfert de compte à l'intérieur d'un même profil. Le UC-05.2 Concerne le transfert inter profils.