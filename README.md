# Projet d'Économétrie - Analyse des facteurs de risque sur le nombre de cancers

## 📌 Description

Ce projet est une analyse économétrique cherchant à analyser l’impact de facteurs de risque sur le nombre de cancer en France entre 1990 et 2016. Il utilise une approche statistique et de séries temporelles pour identifier les tendances et les corrélations entre ces variables sur la période donnée.

✅ **Résultat** : Modélisation permettant de mieux comprendre l’influence des facteurs de risque sur la mortalité due au cancer, avec mise en évidence d’une rupture structurelle en 2004 dans l’évolution du taux d’obésité.


## 🚀 Objectifs

✔️ Préparer et nettoyer les données (conversion en dollars constants, transformations logarithmiques)

✔️ Analyser les relations entre les variables à l’aide de modèles économétriques

✔️ Utiliser des séries temporelles pour détecter des tendances à long terme

✔️ Tester la robustesse des modèles avec des tests statistiques

## 📂 Arborescence

- Projet_econometrie.Rmd : Script principal avec analyse et visualisations
- Donnees.csv : Base de données contenant les variables étudiées

## ⚙️ Méthodes et outils utilisés

- Régressions linéaires (lm)
- Tests économétriques (lmtest, car, sandwich)
- Visualisation de corrélations (corrplot)
- Séries temporelles (ts)
