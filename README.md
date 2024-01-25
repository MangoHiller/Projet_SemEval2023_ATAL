# Projet d'Analyse de Texte Juridique ⚖️

## Description 📃
Ce projet explore différentes approches de traitement automatique du langage naturel (NLP) pour la classification de textes juridiques, dans le cadre de la compétition LegalEval de l’atelier SemEval2023.

Ce projet a pour but d'analyser et de classifier des textes juridiques en utilisant des modèles de traitement du langage naturel (NLP). Le projet se concentre sur des documents de la cour indienne, en appliquant des techniques d'apprentissage automatique pour identifier les rôles rhétoriques et les erreurs de classification.

## Objectifs 🎯

L'objectif principal est de mettre en œuvre et de comparer deux approches :
1. Une approche basée sur les traits (feature-based).
2. Une approche utilisant des modèles Transformer.

- Classifier les textes en différentes catégories rhétoriques.
- Comparer les performances de différents modèles pré-entraînés comme LegalBERT, DistilBERT et Roberta.
- Analyser les erreurs de classification et identifier les patterns communs.
- Améliorer la performance des modèles grâce à l'auto-apprentissage sur un dataset étendu.

## Structure du Repository 📄
Le dépôt est organisé comme suit :
- `BUILD/` : Contient les fichiers CSV pour l'entraînement, le développement et les tests.
- `2023_Sujet_projet.pdf` : Description détaillée du sujet du projet.
- `LegalEval_Transformers.ipynb` : Notebook pour l'approche à base de Transformer.
- `LegalEval_baseline_feature_based.ipynb` : Notebook pour l'approche basée sur les traits.


## Dataset 📁
Les données utilisées dans ce projet incluent plus de 1.5 million de cas contenant des textes de procédures judiciaires indiennes. Les textes ont été prétraités et convertis en un format compatible pour l'entraînement et l'évaluation des modèles.

## Modèles 🤖
Les modèles suivants ont été entraînés et évalués :
- **LegalBERT** : Modèle BERT entraîné sur des données juridiques.
- **DistilBERT** : Version allégée de BERT pour une inférence plus rapide.
- **Roberta** : Modèle basé sur BERT avec des modifications pour une meilleure performance.

## Résultats 
Les résultats montrent une variation dans la précision des classifications entre les modèles. Les analyses d'erreur révèlent que certains rôles rhétoriques sont plus difficiles à prédire que d'autres.

## Utilisation 
Pour utiliser ce projet, clonez le dépôt et suivez les instructions dans les notebooks Jupyter fournis. Assurez-vous d'avoir installé toutes les dépendances nécessaires.

## Contributeurs 

Pour toute question ou commentaire, n'hésitez pas à nous contacter :

|                                                    |                  |
| -------------------------------------------------- | ---------------- |
| [@MangoHiller](https://github.com/MangoHiller)     | Hugo LEGUILLIER  |
| [@miranovic](https://github.com/miranovic)         | Imran NAAR       |


---

<p align="center"> ✨ Merci d'avoir visité ce projet ! N'hésitez pas à étoiler ce repo si vous l'avez trouvé intéressant ! ✨</p>
