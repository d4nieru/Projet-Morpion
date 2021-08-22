# Projet-Morpion NSI #1
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

◆ Projet achevé le 8/01/2020 [X]

# À propos

C'est un projet de NSI (Numérique et Sciences Informatiques) sur un Morpion en groupe, les fonctions initiales etaient déjà écrits et on devait compléter le programme.

# Logiciel requis

• Un environnement de développement intégré pour le langage Python.

# Installation

**IMPORTANT** : Si vous comprenez le language python et la structure de notre projet, vous pouvez le modifer a votre guise.

Après avoir copier-coller le programme, pour se servir du programme, voici les commandes que vous pouvez executer. 

***Les commandes à uniquement taper dans la console***

Poser un pion : pose_pion("Numero du joueur","Coordonnée Horizontale","Coordonnée Verticale")

Si la case est jouable : case_jouable("Coordonnée Horizontale","Coordonnée Verticale") "Les coordonnées de la case doivent etre comprise entre 0 et 2 et la case doit etre vide"

Savoir qui est le joueur gagnant si la partie est terminée : joueur_gagnant()

Vous pouvez afficher le tableau de jeu de morpion en tapant cette commande dans la console : affiche_tableau_de_jeu()

***Pour + de contexte :***

JOUEURS = ('O', 'X') | 'O' = 0 'X' = 1 en programmation

Prenons un exemple, si vous voulez faire comme ceci : https://i.imgur.com/5BzEZLK.png

| Le premier 1 qui symbolise le Joueur X, Le deuxieme 1 correspond a la coordonnée horizontale, Le 2 correspond a la coordonnée verticale.

Deuxieme exemple : https://i.imgur.com/EFw8W6f.png

| Le 0 qui symbolise le Joueur O, Le 2 correspond a la coordonnée horizontale, Le 1 correspond a la coordonnée verticale.
