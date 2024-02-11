Description du Projet :
Nous allons développer une version JavaScript du célèbre jeu 2048. L'idée est de déplacer des tuiles numérotées sur un plateau de jeu N x N (au lieu du classique 4 x 4). Les déplacements sont effectués à l'aide des flèches du clavier, et une tuile peut se déplacer tant qu'elle ne heurte pas une autre tuile ou le bord du jeu. Si deux tuiles de même valeur se touchent, elles fusionnent, avec la valeur de la tuile résultante égale à la somme des deux.

Initialisation du Jeu :
Le jeu commence avec deux tuiles de valeur 2 ou 4, placées au hasard sur le plateau. Après chaque déplacement, une nouvelle tuile apparaît au hasard sur une case libre.

Conditions de Fin du Jeu :
Le jeu peut se terminer de deux manières :

Aucune case libre n'est disponible, et le joueur n'a pas réussi à fusionner des tuiles après un mouvement.
Le joueur parvient à créer une tuile de valeur 2048.
Déroulement du Jeu :
Nous allons généraliser le jeu à un tableau N x N plutôt que de le limiter à 4 x 4. Vous devez programmer le déplacement des tuiles en copiant les colonnes ou les lignes du jeu, les compressant et remplaçant les éléments copiés par les valeurs résultantes de la compression.

React est utilisee pour développer ce jeu.
L'implémentation permet de calculez le nombre de déplacements nécessaires pour atteindre le nombre spécifié et la détection des conditions de fin du jeu et affichez un message approprié.
