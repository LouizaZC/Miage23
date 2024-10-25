
# ZIANE CHAOUCHE LOUIZA

## HomeWork : 

Cette semaine, j’ai appris l’approche Hook and Template en programmation orientée objet. Cette méthode permet de définir le squelette d’un algorithme dans une méthode de la superclasse, tout en laissant aux sous-classes la possibilité de personnaliser certaines étapes. Cela remplace les structures de contrôle (comme les if/else) par un design plus flexible.

* Template Method : une méthode définie dans la superclasse qui appelle d’autres méthodes, structurant ainsi le déroulement de l’algorithme.
* Hook : des méthodes que les sous-classes peuvent redéfinir pour ajuster le comportement de l’algorithme sans en modifier le squelette.


### Dans le projet Chess, on retrouve ces principes avec :

* initialize : un hook qui permet de personnaliser l’initialisation à chaque instanciation (lors d’un new), avec des méthodes redéfinies dans les sous-classes.
printOn : une Template Method définie dans BlElement et précisée dans MyChessSquare pour gérer l’affichage propre aux éléments du jeu d’échecs.


### Révisions et Pratique
J’ai également commencé à réviser pour le DS de vendredi. En parallèle, j’avance sur mon kata.




