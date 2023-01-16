---
title: Super Duper Maze Solver
dateMonthYear: January 2023
lastmod: 2023-01-16
description:  A simple editor and solver hexagonal maze coded in Java. 
type: page
topic: project
link: ""
image: "/images/maze-inf103.png"
---

Ce projet est un programme écrit en Java qui permet de visualiser, de modifier et de résoudre des labyrinthes hexagonaux stockés dans des fichiers de type .maze. Il utilise la bibliothèque Swing pour l'affichage graphique.

## Fonctionnalités
 - Ouvrir un fichier *.maze* pour visualiser le labyrinthe
 - Modifier le labyrinthe en ajoutant/supprimant des murs
 - Résoudre le labyrinthe à l'aide de l'algorithme de Dijkstra
 - Afficher la solution sous forme de chemin sur le labyrinthe

## Utilisation

1. Téléchargez le projet sur GitHub
```console
foo@bar:~$ git clone https://github.com/noevernier/maze-inf103.git
```
2. Ouvrez le projet dans un environnement de développement (ex: vscode)
```console
foo@bar:~$ cd maze-inf103
foo@bar:~$ code .
```
3. Exécutez la classe principale (Main)
```console
foo@bar:~$ java main/Main.js
```
4. Utilisez les boutons de l'interface pour ouvrir un fichier, effectuer des modifications et résoudre le labyrinthe

## Format des fichiers .maze

Les fichiers .maze doivent respecter le format suivant :

 - Chaque ligne représente une rangée d'hexagones
 - Les hexagones sont séparés par des espaces
 - Un ```E``` représente un hexagone vide
 - Un ```W``` représente un hexagone occupé
 - Un ```A``` représente l'hexagone d'arrivé
 - Un ```D``` représente l'hexagone de depart

Exemple :

```console
DEEEEEWWEEEE
EEEWWWEWWWWW
EEEEEEEWEEWW
EEEEEEEEEEWE
EWEEEEEEEEWE
WWEEEEEEEEWE
EWEEEEEEEEEE
EWWWEWEAEEEW
EEEEEEEEEEWE
EWEEEEEEEEWE
WWEEEEEEEEWE
EWEEEEEEEEEE
```

## Remarques

- Le projet utilise des images d'hexagones pour l'affichage graphique, vous pouvez remplacer ces images par vos propres images si vous le souhaitez.

- L'algorithme de Dijkstra utilisé pour résoudre le labyrinthe n'est pas optimisé pour des labyrinthes de grandes tailles, il peut prendre un certain temps pour résoudre un labyrinthe très grand.