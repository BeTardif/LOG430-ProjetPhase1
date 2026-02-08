# UC-03 - Ouverture d'un compte bancaire

### Définitions 

### Objectif:
Permettre l'ouverture d'un compte chèque ou épare.

### Généralités
* Acteur principal: Client
* Déclencheur: Demande de création de compte
* Pré-conditions: Le client est authentifié avec son profil.
* Postconditions(succès - compte chèque): Le client a un nouveau compte chèque
* Postconditions(succès - compte épargne): Le client a un nouveau compte épargne.

### Flux Principal
1. Le client fournit ses informations d'identification.
2. Le système cherher les données afin de les valider.
3. Le client confirme via OTP/MFA. 
4. Le Système donne accèes au client via une session sécurisée. 

### Critère d'acceptation
Le client voit un nouveau compte 

## Notes de concpetion
Garder ce cas d'utilisation simple est la clé pour le réussir. Si c'est de créer un compte, il faut créer un compte, passer de 0 à 1.

