Spécification d'interopérabilité pour les Katapostes modèles 165
================================================================


Les trois parties d'un Kataposte
--------------------------------

Un Kataposte est composé de trois parties principales :

- La coque. C'est le caisson qui accueille les haut-parleurs et l'amplification.
- Le coeur. Il est composé de deux parties : le volume fonctionnel et l'interface utilisateur.
- Les haut-parleurs. Il doivent être d'une gamme de 165mm de diamètre.

Ce document vise à décrire les interfaces entre ces différentes parties.

Le but est de pouvoir concevoir et construire celles-ci de manière indépendante.


Le coeur
--------

Tous les trous dont il est question ici font 4mm de diamètre.

L'interface utilisateur doit tenir sur une surface de 100x145mm avec 10 mm de surface de contact.
Les trous des vis sont situés aux quatre coins et au centre d'un carré de 10mm de côté.

![plan de la façade utilisateur](doc/images/interface-utilisateur.png)

Le volume fonctionnel accueille toute l'amplification du son et, si elle existe,
"l'intelligence" (mini ordinateur par exemple).

La surface de travail fait 150x250mm. Les trous de vis qui font la liaison avec
la coque sont écartés de 120mm, sont centrés dans la longueur. Ils sont centrés
eux aussi dans un carré de 10mm

![plan 3d du coeur](doc/images/coeur-3d.png)

![plan du coeur](doc/images/coeur.png)

La longueur des cables entre ces deux parties doit être de 40cm minimum.


Les haut-parleurs
-----------------

Ils doivent faire partie d'une gamme 165mm de diamètre. Le positionnement des trous de vis et les diamètres
des trous du saladier et des grilles est décrit dans le plan ci-dessous.

![plan du trou haut-parleur](doc/images/hp.png)


La coque
--------

La coque est le support des deux précédentes parties. Quelle que soit sa forme, elle
doit respecter les points suivants :

- Trous et diamètres pour les haut-parleurs.
- Trous et surface de contact pour l'interface utilisateur.
- Trous et volume pour la partie fonctionnelle.
- S'assurer qu'il ne peut y avoir de collision entre les haut-parleurs et le volume fonctionnel.


La mention certifiant l'interopérabilité
----------------------------------------

Toute personne respectant ces contraintes techniques est autorisée à apposer sur ses créations
la mention "Compatible Kataposte 165".
