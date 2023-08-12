# Carnet de suivi

## Introduction

Carnet de suivi permet à l'utilisateur d'enregistrer ses séances de musculation et de visualiser graphiquement ses performances.
Etant insatisfait des applications existantes, voici les fonctionnalités que je souhaitais implémenter, divisées en deux sous parties. L'une correspond à la création (le setup initial) d'un programme d'entrainement, l'autre à l'utilisation de l'application pendant la séance.

### Avant la séance : Création d'un programme d'entrainement

- Création, modification et téléchargement de programmes d'entrainements :
  - Chaque programme d'entrainement contient une ou plusieurs séances.
  - Chaque séance contient un ou plusieurs exercices.
  - Chaque exercice est composé de :
    - Un nom
    - Un lien externe modifiable vers une explication de l'exercice (J'aime utiliser [DrFitness](https://www.docteur-fitness.com/))
    - Un nombre de séries (définie initialement)
    - Un intervalle de répétitions (définie initialement)
    - Un intervalle de charge `[charge d'échauffement, charge de travail]`

## Pendant la séance : Utilisation d'un programme d'entrainement

Lors de chaque séance, l'UI affiche les informations suivantes dépendant de la séance actuelle :

- Pour l'interface "Programme d'entrainement"
- Pour l'interface "Exercice" :
  - Un array d'évolution de charge du début à la fin de l'exercice


## Organisation de la Base de Donnée

- [] Enregistrement d'exercices selon le modèle suivant
  - Nom de l'exercice
  - L
  - Poids