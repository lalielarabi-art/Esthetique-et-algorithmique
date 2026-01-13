Description du projet

Lors de la présentation des automates cellulaires j’ai rapidement pensé à la propagation d’une épidémie que l’on étudie souvent en mathématiques à l’aide des probabilités.
J’ai donc créé une grille où les cellules sont au départ saines (blanches) ou infectées (rouges). Les cellules saines peuvent ensuite s’infecter de façon aléatoire.
Un nombre aléatoire entre 0 et 1 est généré et si ce nombre est inférieur à la probabilité P, qui dépend du nombre de voisins infectés, la cellule s’infecte.

Pour répertorier les voisins infectés j'ai créer une boucle qui vérifie les 8 cases autour à l'aide de leurs coordonées.

On observe que plus la probabilité p est grande, plus l’infection se propage rapidement. On peut donc observer différents comportements en modifiant la valeur de p ou le nombre de cellules infectées au départ.

