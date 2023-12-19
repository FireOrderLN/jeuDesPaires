- ### PatchNotes :bookmark_tabs:

*Version actuelle du jeu : v1.1*

- ##### v1.1 :
> - Implémentation des fonctionnalités suivantes :
>   - mode autoplay
> - Correction d'un bug graphique mineur

- ###### v1.0.2 :
> - Correction d'un bug qui rendait impossible la réinitialisation du fichier des scores 

- ###### v1.0.1 :
> - Correction d'un bug qui rendait impossible l'écriture et la lecture du classement

- #### v1.0 :
> - Jeu à 1 joueur totalement fonctionnel et implémenté.
> - Changement de la stucture du projet :
>   - Les patchs sont desormais déplacés dans un autre fichier

- ##### v0.5 : 
> - Implémentation des fonctionnalités suivantes :
>   - Affichage des 12 cartes intégré
>   - Contrôle de déplacement et de sélection des cartes
>   - Gestion des différents status des cartes
>   - Algorithme de comparaison des cartes
>   - Condition de victoire
> - Correction d'un bug de compilation qui faisait que les fichiers .o ne trouvaient pas leur dossier.
> - Correction d'un bug qui faisait que le programme ne conservait pas réellement le dernier input pour le mode Debug.

- ###### v0.4.4 :
> - déplacement des fonctionnalités d'après jeu dans `aftergame.c`

- ###### v0.4.3 :
> - Modification de la touche de fin de tâche du jeu basé sur les besoins du cahier des charges

- ###### v0.4.2 :
> - Optimisation de la fonction de la gestion du score
> - Mise en place d'une fenêtre de défaite différente de la fenetre de victoire
> - Ajout de commentaires à la fonction d'écriture/lecture du fichier et gestion du score
> - réécriture des fichiers .h

- ###### v0.4.1 :
> - Implémentation des fonctionnalités suivantes :
>   - Outils de debug suivant :
>       - Menu debug pour choisir ces options
>       - Possibilité de réinitialiser le fichier ``jeuhighscore.txt``
>   - Une défense, pour l'utilisateur, d'entrer des noms en-dessous et au-dessus de 4 caractères
> - Résolution d'un problème qui faisait que les noms étaient mal lus.
> - Correction d'un bug qui faisait que les sorties d'erreur ne s'affichaient pas.

- ##### v0.4 :
> - Implémentation des fonctionnalités suivantes :
>   - Écran de victoire après la fin du jeu
>   - Écriture et lecture des meilleurs scores
>   - Jeu en mode debug (accessible avec *3* dans le menu)
> - Réécriture du code de la fonctionnalité chrono avec les paramètres suivants :
>   - Calcul des secondes et millisecondes via une structure annexe 

- ###### v0.3.1 :
> - Optimisation générale dans le code du jeu :
>   - Calcul du chrono du jeu déplacé dans une fonction
>   - Debug input déplacé dans une fonction

- ##### v0.3 :
> - Implémentation des fonctionnalités suivantes :
>   - Détection des inputs utilisateur
>   - Rendre le curser invisible pendant le jeu
>   - Outils de debug suivants :
>       -   Connaître le dernier input user
>       -   Quitter rapidement le programme avec la touche *Echap*

- ###### v0.2.1 :
> - Correction de la commande a rentrer dans le terminal pour compiler.
> - Réecriture du code de la features timer avec les paramétres suivants :
>   - Utilisation de la librairie "time.h" au lieu de ncurses pour une meilleur gestion du temps
>   - Implementation direct dans la fonction de jeu pour l'utiliser en même temps que le jeu 
>   - mise en place du nodelay et timeout pour la gestion des inupts du jeu

- ##### v0.2 :
> - Implémentation des fonctionnalités suivantes :
>   - Lancement du jeu à 1 joueur
>   - Chronomètre
>   - Arrête le programme lorsque le temps est écoulé

- ###### v0.1.1 :
> - Résolution d'un problème de compilation avec le makefile

- ##### v0.1 :
> - Mise en place d'une arborescence fichier
> - Écriture du ```README.md```
> - Implémentation des fonctionnalités suivantes : 
>   - Écran titre
>   - Érreur terminal si il est trop petit
>   - Sélection du mode de jeu
>   - Erreur de sélection du mode de jeu si la valeur entrée est incorrecte
> - Mise en ligne sur GitHub du code source










