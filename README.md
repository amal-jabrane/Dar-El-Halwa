Nom:Jabrane
Prenom:Amal
classe: 1 ere info 15
## Problémes recontrés pendant la séance
1. ** Problèmes 1: Erreur dans le pattern du numéro de téléphone**
- **Symptomes :** Le formulaire refusait des numéros de téléphone tunisiens valides.
- **Causr identifiée :** La regex initiale ne correspondaits pas au format +216 suivi de 8 chiffres.
- **Correction appliquée :** Utlisation de l'expression réguliére ^\+216[0-9]{8}$ et ajout d'un attribut title.
2. **probléme 2: Association incorrecte entre label et input**
- **Symptome :** Cliquer sur le text du label ne sélectionnait pas le champ de saisie.
- **Cause identifiée :** Utlisation de l'attribut name ou d'une majuscule incorrecte au lieu de l'id exact dans l'attribut for.
- **Correction appliquée :**Correction des attributs for pour correspondre exactement aux id des champs (ex: for="nom").
## type HTML5  employés dand le projet :
-**text/ number** : Utillisés dand la formulaire de commande pour les quantités et les informations textuelles.
-**ul** : Utilisé pour le champ optionnel du site web ou de la page Instagram
-**time** : Utilisé pour choisir l'heure de retrait souhaitée