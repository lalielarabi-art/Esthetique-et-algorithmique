Description du projet

Ce programme génère un parterre de fleurs animées à l’aide de Processing . Les fleurs sont disposées sur une grille et varient en couleur et comportment pour créer un jardin vivant.
Les fleurs ne pulsent pas toutes de la même manière, les fleurs roses pulsent plus rapidement, donnant l’impression qu’elles sont plus vivantes et dynamiques. Et les oranges pulsent un peu plus vite que les marrons.

Pour l’orientation des pétales, je n’y arrivais pas, au début ils restaient en position horizontale. 
J’ai donc demandé de l’aide à l’IA et utilisé les fonctions pushMatrix(), popMatrix(), translate(), et rotate(), ce qui m’a permis de faire tourner chaque pétale autour du centre de la fleur.

J'ai égalment utilisé la fonction lerpColor pour le dégradé entre les pétales.

Les fleurs sont alignées sur une grille et espacése selon la largeur et la hauteur de la page. Elles sont alternées selon leur type afin de varier les formes et les couleurs dans le parterre.
