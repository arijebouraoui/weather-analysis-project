Analyse des patterns météorologiques – Szeged (2006–2016)
📌 Présentation du projet

Ce projet consiste en une analyse exploratoire approfondie de données météorologiques horaires collectées à Szeged (Hongrie) sur une période de 10 ans (2006–2016), représentant 96 453 observations.

L’objectif principal est de comprendre les comportements climatiques, les variations temporelles et les relations entre les principales variables météorologiques, à travers une approche structurée et reproductible en R.


🎯 Objectifs de l’analyse

Nettoyer et préparer les données (valeurs manquantes, doublons, valeurs aberrantes)

Étudier l’évolution de la météo selon différentes échelles temporelles (heure, mois, saison, année)

Mettre en évidence les corrélations entre les variables climatiques

Identifier d’éventuelles tendances climatiques sur la décennie étudiée

Produire des visualisations claires et interprétables

🔍 Démarche analytique

L’analyse a été menée étape par étape :

Vérification de la structure et de la qualité du dataset

Suppression de 24 observations dupliquées

Détection des valeurs aberrantes à l’aide de la méthode IQR

Analyse descriptive des variables principales

Étude des variations temporelles (journalières, mensuelles et saisonnières)

Construction d’une matrice de corrélation

Création de 16 visualisations pour appuyer les résultats (courbes, heatmaps, boxplots)

📊 Principales observations

Saisonnalité marquée :
La température moyenne varie d’environ 0 °C en hiver à 22 °C en été.

Relation température–humidité :
Une corrélation négative forte est observée (r ≈ −0,65), indiquant que l’humidité diminue lorsque la température augmente.

Cycle journalier clair :
Les températures minimales apparaissent généralement entre 5h et 6h, tandis que les maximales se situent entre 14h et 15h.

Évolution sur le long terme :
Une légère tendance à la hausse des températures est perceptible sur la période étudiée.

🛠️ Outils et technologies utilisés

Langage : R (v4.5)

Environnement : RStudio

Rapport reproductible : Quarto

Packages principaux :

tidyverse

ggplot2

lubridate

corrplot

▶️ Exécution du projet
# Cloner le dépôt
git clone https://github.com/arijebouraoui/weather-analysis-project.git
cd weather-analysis-project


Ouvrir le projet dans RStudio

Ouvrir le fichier qmd/weather-analysis.qmd

Cliquer sur Render pour générer le rapport

📁 Source des données

Weather History Dataset – Szeged, Hungary (2006–2016)
Disponible sur Kaggle

👤 Auteur

Arije Bouraoui
Projet d’analyse de données
Décembre 2026
