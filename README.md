# growth hacker job
Sujet du test technique pour le poste de growth hacker

## Exercice 1 : gestion de collègues

Le but de cet exercice est de fournir un ou plusieurs fichiers js qui permettent de traiter les problématiques suivantes.
Attention, comme ce sont des problèmes sérieux sur lesquels on voudra retravailler et qu'on voudra améliorer, il faut que le code soit facilement réutilisable avec dans des situations différentes (avec des listes de collègues différentes par exemple, ou carrément sur une autre application)

### 1 : secret santa
On récupère une liste de collègues de type `['frodo', 'sam', 'merry', 'pipin', 'bilbo']`.
On veut récupérer une liste de secret santa qui attribue aléatoirement à chaque personne une autre à qui elle offre un cadeau, sachant qu'on ne peut avoir comme secret santa son propre secret santa.

### 2 : une entreprise familliale
Certains collègues sont de la même famille. Ils ne peuvent pas offrir de cadeau aux gens de la même famille.
On récupère désormais une liste de type `[{name: 'frodo', family: 'baggins'}, {name: 'bilbo', family: 'baggins'}, {name: 'sam'}, {name: 'merry'}, {name: 'pipin}]`

### 3 : des absents
Certaines personnes ne seront pas présente le jour du secret santa, elle apparaissent sous la forme : `{name: 'gandal', absent: true}`. Ce qui donne une liste comme `[{name: 'frodo', family: 'baggins'}, {name: 'bilbo', family: 'baggins'}, {name: 'waldo', family: 'baggins', absent: true}, {name: 'sam', absent: true}, {name: 'merry'}, {name: 'pipin}]`

### 4-bonus : une interface

Il faut réutiliser ce qui a été fait dans une mini interface web qui permet de créer la liste (avec prenom, famille et presence/absence) puis d'appuyer sur un bouton pour générer la liste. Cette interface peut être en pur front, mais de préférence avec une framework web comme react ou vuejs. Pas besoin de travailler plus que de raison le css.

## Exercice 2 : Elevator saga

Fournir du code pour aller le plus loin possible sur https://play.elevatorsaga.com/