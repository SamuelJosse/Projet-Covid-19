# Projet COVID-19

## Introduction
Ce projet se concentre sur l'analyse de données provenant de tests sanguins et viraux pour des patients atteints ou non du COVID-19. L'objectif principal est de comprendre les relations entre certaines caractéristiques biologiques et le statut COVID-19 des patients, ainsi que de tester des hypothèses biologiques.

## Structure du projet
- **Données** : Le dataset inclut des variables comme :
  - `Patient ID` : Identifiant du patient
  - `Patient age quantile` : Quantile d'âge du patient
  - `SARS-Cov-2 exam result` : Résultat du test COVID-19 (positif/négatif)
  - `Hematocrit`, `Hemoglobin`, `Platelets`, `Red blood cells`, `Lymphocytes`, etc.
- **Préparation des données** :
  - Gestion des valeurs manquantes, avec des taux élevés de données manquantes pour certaines variables.
- **Exploration des données** :
  - Étude des corrélations entre variables sanguines et virales.
  - Identification de relations possibles entre l'âge, les résultats des tests sanguins, et le statut COVID-19.
  
## Analyses clés
- **Relation entre les variables** :
  - Corrélation entre certaines variables sanguines (ex. monocytes, plaquettes) et le statut COVID-19.
  - Corrélation entre l'âge et les taux sanguins très faible.
  - Identification d'hypothèses à tester pour les taux de leucocytes et autres marqueurs sanguins.
- **Hypothèses à tester** :
  - Les patients COVID-19 positifs ont des taux de `Leukocytes`, `Monocytes`, et `Platelets` significativement différents des patients négatifs.
  - Vérifier si les personnes atteintes d'autres maladies virales montrent des caractéristiques sanguines similaires.

## Conclusions initiales
- Les données présentent beaucoup de valeurs manquantes (jusqu'à 80% pour certaines variables).
- Il n'existe pas de variables très fortement discriminantes, mais certaines relations méritent une exploration plus approfondie.
- Deux types de données intéressants à analyser : les résultats des tests viraux et sanguins.

## Utilisation
1. Exécuter le notebook pour visualiser les résultats de l'analyse exploratoire.
2. Les analyses incluent des visualisations de corrélations, des statistiques descriptives et des hypothèses à tester.

## Prérequis
- Python 3.x
- Bibliothèques nécessaires : `pandas`, `numpy`, `matplotlib`, `seaborn`

## Auteurs
- [Samuel JOSSE]

