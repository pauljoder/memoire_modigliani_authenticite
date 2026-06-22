# L'authenticité à l'épreuve de l'algorithme

Mémoire de Master 1 SDHC — Paris 1 Panthéon-Sorbonne (2025-2026)

Auteur : Paul Joder
Directeurs : Sophie Cras et Vincenzo Capozzoli

## Description

Ce dépôt contient le code source du dispositif expérimental développé pour le mémoire intitulé *L'Authenticité à l'épreuve de l'algorithme : vers une hybridation de l'expertise en histoire de l'art ?*

Le dispositif repose sur un classifieur stylistique (ResNet18) entraîné à distinguer les œuvres d'Amedeo Modigliani de celles de ses contemporains (Picasso, Matisse, Chagall). Il est complété par une visualisation Grad-CAM des zones d'attention du modèle.

## Contenu

- `notebook_modigliani.ipynb` : notebook Jupyter principal (préparation du corpus, entraînement du modèle, évaluation, génération des cartes Grad-CAM)
- `requirements.txt` : liste des bibliothèques utilisées

## Corpus

Le corpus est extrait du jeu de données *Best Artworks of All Time* (ikarus777, Kaggle) :
https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time

## Résultats principaux

- Exactitude globale sur le jeu de test : 91,5 %
- Démonstration de l'écart entre reconnaissance stylistique et authentification

## Licence

Code distribué sous licence libre à des fins de recherche et d'enseignement.
