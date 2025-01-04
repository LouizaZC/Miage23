# Louiza ZIANE CHAOUCHE

## Cours :
Cette semaine, nous avons étudié les types (statiques et dynamiques)

* Messages et types :
Lorsqu’un message est envoyé, le programme suit deux étapes : la recherche de la méthode dans la classe de l’objet récepteur (et éventuellement dans ses superclasses) et l’exécution de cette méthode.

Les types statiques sont fixés à la compilation, ce qui permet de prévenir les erreurs dès cette étape mais limite la souplesse du code.
Les types dynamiques, déterminés à l’exécution, offrent une plus grande flexibilité mais rendent la détection des erreurs plus délicate.

## Kata:
Concernant le kata, j’ai réfléchi plus en détail au mouvement "en passant", qui est une règle particulière des échecs.
J’ai compris que pour que ce mouvement soit valide, il est nécessaire d’enregistrer le dernier coup joué dans la partie.
Cela permet de s’assurer que "en passant" ne soit autorisé que juste après qu’un pion adverse ait avancé de deux cases. 
 Pour gérer cette règle, j’ai décidé de créer une classe dédiée au mouvement. Cette classe inclut des informations telles que la pièce impliquée et les détails du déplacement.
 Ensuite, j’instancie cette classe dans la classe Game, où elle stocke le dernier mouvement joué. 
 Cette approche centralisée facilite la gestion du suivi des coups et garantit que le mouvement "en passant" reste conforme à la règle officielle.
