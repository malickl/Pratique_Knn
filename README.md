# Projet de Classification avec K-Nearest Neighbors (KNN)

## Introduction
Ce projet démontre l'application de l'algorithme K-Nearest Neighbors (KNN) pour la classification d'images de chiffres manuscrits, en utilisant le dataset `digits`. L'objectif est d'illustrer la mise en œuvre de KNN en Python pour résoudre un problème de classification de manière efficace.

## Technologies Utilisées
- Python
- Libraries : NumPy, pandas, matplotlib, scikit-learn

## Dataset
Le dataset `digits`, intégré à scikit-learn, comprend des images de chiffres manuscrits. Chaque image est représentée sous forme d'un array 8x8, où chaque élément est un pixel en niveau de gris.

## Méthodologie
1. **Importation des librairies** : Utilisation de numpy pour le calcul numérique, pandas pour la manipulation des données, matplotlib pour la visualisation, et scikit-learn pour le prétraitement et l'application de l'algorithme KNN.
2. **Chargement du dataset** : Le dataset `digits` est chargé pour servir de base à notre modèle de classification.
3. **Visualisation des données** : Affichage des images avec matplotlib pour comprendre les données avec lesquelles nous travaillons.
5. **Modélisation avec KNN** : Implémentation de l'algorithme KNN pour classifier les images de chiffres manuscrits.
6. **Évaluation du modèle** : Utilisation de la matrice de confusion pour évaluer la performance du modèle.

