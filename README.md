# OC_GIT_GitHub


////////////////////////    Activité partie 3    ////////////////////////   



////    Qu'est-ce qu'un commit?    ////


  Un commit est en quelque sorte une version d'un projet informatique ou autre.
  Il prend en compte toutes les modifications depuis le dernier commit sur un ou plusieurs fichiers quels qu'ils soient.
  Chaque commit a obligatoirement un sha: un numéro d'identifiant. On peut y affecter une description des modifications, ajouts, etc... et c'est même fortement conseillé, cette description doit être claire pour pouvoir s'y retrouver si le projet est gros ou qu'on a pas travaillé dessus depuis longtemps (ex: correction du bug lors de la validation du formulaire).
  Il est possible de se placer dans un commit plus ancien et de retrouver l'état de notre projet comme il l'était, par exemple, ça permet de revenir en arrière si plus rien ne fonctionne et qu'on est perdu.
  Il est conseillé d'en faire régulièrement afin de s'y retrouver plus facilement, surtout si on travaille à plusieurs en même temps sur le même projet.


////    À quoi sert la commande git log?    ////


  La commande git log permet de lister tous les commits qui ont été effectués.
  Pour chaque commit figure le sha, un identifiant unique, l'auteur du commit et son adresse mail, la date à laquelle le commit a été effectué et la description du commit.
  Le sha peut permettre se placer dans un commit, c'est à dire, retrouver l'état dans lequel était le projet lors de ce commit.

////    Qu'est-ce qu'une branche    ////

  
  Une branche permet de développer des fonctionalités sans affecter la branche principale (master).
  On peut y faire des essais et quand on est sûr de notre code, le fusionner à la branche master.
  Lorsqu'on se trouve dans la branche master, les modifications des autres branches ne sont pas prises en compte.
  Les branches permettent donc de développer une fonctionnalité pendant longtemps sans affecter et en laissant fonctionnel le code de la branche master.
