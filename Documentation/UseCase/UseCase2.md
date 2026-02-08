# UC-02 - Authentification & MFA

### Définitions 
OTP: (One Time Password) Sert à authentifier l'utilisateur.
MFA: (Multi Factor Authentification) Sert à assurer l'authentification d'un utilisateur.

### Objectif:
Garantir un accès sécurisé aux services bancaires.

### Généralités
* Acteur principal: Client
* Déclencheur: Demande de connexion
* Pré-conditions: Avoir un profil
* Postconditions(succès): Le client est authentifié.
* Postconditions(échec - profil existant):  L'accès est refusé et le client est notifié de l'information éronnée.
* Postconditions(échec - profil innexistant):  L'accès est refusé et le client est notifié qu'aucun profil n'existe avec ces informations.

### Flux Principal
1. Le client fournit ses informations d'identification.
2. Le système cherher les données afin de les valider.
3. Le client confirme via OTP/MFA. 
4. Le Système donne accèes au client via une session sécurisée. 

### Critère d'acceptation
Un client est authentifié et les informations concernant son profil bancaire sont présentées dans une session sécurisée.

## Notes de concpetion
L'emphase ici est sur la session sécurisée. La conception doit être produite avec cette idée et la protection doit être assurée lors de la recherche des données ainsi que lors de la session sécurisé. 

