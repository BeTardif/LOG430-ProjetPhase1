# UC-08 - Clôture journalière & relevés (EOD)

### Définitions 
EOD : End of day

### Objectif:
Produire les relevés bancaires quotidiens.

### Généralités
* Acteur principal: Système
* Déclencheur: la fin de la journée.
* Pré-conditions: Aucune.
* Postconditions(succès): Le relevé de la bancaire de la journée est produit.

### Flux Principal
1. Aggrégation des transactions.
2. Génération des relevés.
3. Archivage et mise à disposition du client.

### Critère d'acceptation
Un relevé est produit, archivé et envoyé au client.

## Notes de concpetion
Archivage? 