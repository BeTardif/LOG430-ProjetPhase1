# UC-06 - Paiement de factures (Blind transfer)

### Définitions 

### Objectif:
Permettre le paiement de fournisseurs.

### Généralités
* Acteur principal: Client
* Déclencheur: Requête de paiement d'uane facture.
* Pré-conditions: Être authentifié, avoir un compte avec les fonds suffisants, que le fournisseur visé existe.
* Postconditions(succès): Le compte visé a la somme transférée. Le compte initial n'a plus la somme transférée.

### Flux Principal
1. Sélection du fournisseur
2. Numéro de facture
3. Sélection d'un compte avec la provenance de la somme.
4. Exécution du paiement
5. Validation de l'exécution (STATE comme la création de compte?)
6. Confirmation et audit. 

### Critère d'acceptation
La somme est transférée d'un compte à l'autre.
Les clients sont notifiés du transfert.

## Notes de concpetion
Qu'est-ce que Audit veut dire ici?
Pas mal ambigue comme situation? 

Probablement à définir a force que l'application se développe
