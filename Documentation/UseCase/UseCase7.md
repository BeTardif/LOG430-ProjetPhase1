# UC-07 - Détection d'activités suspectes

### Définitions 
AML : Anti money laundering

### Objectif:
Identifier et signale des transactions suspectes.

### Généralités
* Acteur principal: Système
* Déclencheur: transaction suspectes identifiés.
* Pré-conditions: Une transaction suspectes est survenues
* Postconditions(succès): L'état des comptes a priori à la transaction est restauré.

### Flux Principal
1. Analyse post-trade des transactions
2. Détection de patterns anormaux.
3. Signalement interne et audit.

### Critère d'acceptation
L'état des comptes est retourné à celui avant la transaction.

## Notes de concpetion
Je suppose que c'est un outil de contrôle qui s'accroche aux transactions.

Conséquement, tout l'engin de transaction doit être produit avant la réalisation de ce cas d'utilisation. 
