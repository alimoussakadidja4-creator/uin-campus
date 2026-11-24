# UIN-Campus

Système de gestion académique de l'UIN (projet du cours de POO en C++ moderne).

## Versions des outils utilisés

- g++ (Ubuntu 15.2.0-16ubuntu1) 15.2.0
- Ubuntu clang version 21.1.8 (6ubuntu1)
- cmake version 4.2.3
- ninja 1.13.2
- GNU gdb (Ubuntu 17.1-2ubuntu1) 17.1
- git version 2.53.0

## Construire et exécuter

    cmake --preset debug
    cmake --build --preset debug
    ./build/debug/uin-campus

## Options de la ligne de commande

    ./build/debug/uin-campus --version
    ./build/debug/uin-campus --aide

## Organisation du code

- version.hpp, version.cpp : version du projet
- regles.hpp, regles.cpp : barème, seuils et mentions (chapitres 3 et 5)
- saisie.hpp, saisie.cpp : saisie robuste (chapitres 3 et 4)
- calculs.hpp, calculs.cpp : moyennes simple et pondérée, statistiques (chapitres 4 et 5)
- app/main.cpp : programme principal

## Exemple

Notes 12 (coefficient 2) et 15 (coefficient 1) : moyenne pondérée 13.00,
moyenne simple 13.50, mention Assez bien.
