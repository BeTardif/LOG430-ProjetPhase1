# UC-01 - Inscription & Vérification d'identité (KYC)

### Définitions
AML: Anti-money laundering  
KYC: (Know Your Customer) Étape par laquelle une institution financière vérifie l'identité d'un client.  
OTP: (One Time Password) Sert à authentifier l'utilisateur.
MFA: (Multi Factor Authentification) Sert à assurer l'authentification d'un utilisateur.

### Objectif:
Permettre à un client d'ouvrir un profil bancaire conforme aux exigences KYC/AML.

### Généralités
* Acteur principal: Client
* Déclencheur: Demande d'ouverture de compte
* Pré-conditions: Aucune
* Postconditions(succès): Profile client Active
* Postconditions(échec):  Porfil client non active

### Flux Principal
1. Le client fournit des données personnelles (nom, adresse, NAS simulé).
2. Le système valide les données et crée un profil Pending.
3. Le client confirme via OTP/MFA. 
4. Le Système valide le KYC et active le profil. 

### Critère d'acceptation
Un client valide son identité et obtient un profil bancaire actif.

## Notes de concpetion
Le but de ce cas d'utilisation est de créer un système d'authentification sécurisé avec une protection multifacteur. Le principe décrit du KYC tient à gérer les états suivants : 
* **PENDING** Les données sont soumises et en attente de validation.
* **VERIFIED** Les données sont soumises et validées.
* **REJECTED** Les données sont soumises et rejetées.
* **ACTIVE** Les données ont permis la création d'un compte.

Dans un système bancaire, les données soumises sont utilisées pour rechercher les antécédents d'un client. 

**Note**  
Ce cas d'utilisation est probablement le plus important. Il va définir les informations générales d'un client à son initiation. À son initiation, un compte client devrait avoir les informations suivantes:

1. Un compte avec un numéro et un montant
2. Les informations relatives à client et son KYC

### Test à produire

