## Mini calculatrice pour le profit
### Contexte du projet

Les agriculteurs souhaitent disposer d'un outil web simple et accessible pour automatiser les calculs et les améliorer .
L'objectif est d'utiliser les calculs manuels et de faciliter ces décisions.

### L'outil qui vous permet de saisir 

Coût de production (semences, engrais, main-d'œuvre, etc.)

Prix d'entrée des produits agricoles

Puis, le système calcule automatiquement la marge et affiche un message adapté.

### Fonctionnalités

formule simple et intuitive

Calculer l'utilisation instantanée de la batterie sans recharger la page

### Différents messages issus des résultats :

 Louable si positif

Équilibre si marge nulle

Perte si marge négative

 ### Technologies utilisées

HTML5 pour la structure de la page

CSS3 pour le format de mise en base

JavaScript (DOM) pour le Journal de calcul et ajustement dynamique


## reponse aux questions

### Pourquoi est-il important d’utiliser une fonction pour le calcul de la marge bénéficiaire ?

Une fonction rend le code plus clair et mieux structuré.

Elle permet de réutiliser le calcul sans le réécrire.

Elle facilite la maintenance : si la formule change (ajout de taxes, frais, etc.), il suffit de modifier la fonction.

Elle sépare la logique métier (le calcul) de l’affichage vers une meilleure organisation.

### Quelles conditions pourraient être testées pour afficher un message différent selon la marge ?

Si marge > 0 cela  afficher que l’activité est rentable.

Si marge = 0 ceci afficher que l’activité est à l’équilibre.

Si marge < 0  afficher que l’activité est en perte.
