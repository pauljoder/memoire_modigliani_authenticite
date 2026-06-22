# L'authenticité à l'épreuve de l'algorithme

Mémoire de Master 1 SDHC - Paris 1 Panthéon-Sorbonne (2025-2026)

Auteur : Paul Joder

Directeurs : Sophie Cras et Vincenzo Capozzoli

## Description

Ce dépôt contient le code source du dispositif expérimental développé pour le mémoire intitulé *L'Authenticité à l'épreuve de l'algorithme : vers une hybridation de l'expertise en histoire de l'art ?*

Le dispositif repose sur un classifieur stylistique (ResNet18) entraîné à distinguer les œuvres d'Amedeo Modigliani de celles de ses contemporains (Picasso, Matisse, Chagall). Il est complété par une visualisation Grad-CAM des zones d'attention du modèle.

## Contenu du dépôt

- Le notebook Jupyter principal, qui couvre la préparation du corpus, l'entraînement du modèle ResNet18, l'évaluation sur le jeu de test et la génération des cartes Grad-CAM
- Le dossier `Test pictures` contenant les images utilisées pour les tests critiques

## Prérequis

L'exécution du notebook nécessite un fichier d'authentification API Kaggle (`kaggle.json`) pour télécharger automatiquement le jeu de données. Ce fichier est obtenu depuis le compte personnel Kaggle de l'utilisateur (Settings → API → Create New Token).

## Corpus

Le corpus principal est extrait du jeu de données *Best Artworks of All Time* (ikarus777, Kaggle) :
https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time

## Résultats principaux

- Exactitude globale sur le jeu de test : environ 90 %
- Démonstration de l'écart entre reconnaissance stylistique et authentification

## Licence

Code distribué sous licence libre à des fins de recherche et d'enseignement.
