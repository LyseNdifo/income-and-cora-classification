# Classification sur Adult et Cora

Ce dépôt regroupe deux exercices d’apprentissage supervisé appliqués à des jeux de données différents :  
- prédiction du revenu (>50K) sur le dataset Adult (UCI),  
- classification d’articles scientifiques sur le dataset Cora.

L’objectif est d’explorer les étapes essentielles d’un projet de classification : préparation des données, encodage, équilibrage, réduction de dimension, choix de modèle et évaluation.


## 🎯 Objectifs

- Préparer des données tabulaires et relationnelles.  
- Gérer les valeurs manquantes et les variables catégorielles.  
- Traiter un déséquilibre de classes avec **SMOTEENN**.  
- Standardiser les variables numériques.  
- Réduire la dimension avec **ACP** lorsque nécessaire.  
- Entraîner et évaluer un modèle **KNN** sur Adult.  
- Construire une matrice enrichie pour Cora.  
- Entraîner un modèle **Gradient Boosting** et analyser ses performances.


## 📁 Contenu
```
income-and-cora-classification/
│
├── notebook/
│   ├── KNN_adult&GradientBoosting_cora.ipynb
└── README.md
```


## 🧠 Méthodes utilisées

### KNN sur Adult
- Nettoyage des valeurs manquantes  
- Encodage catégoriel  
- Équilibrage SMOTEENN  
- Standardisation  
- ACP  
- Optimisation du nombre de voisins  
- Évaluation sur test

### Gradient Boosting sur Cora
- Données relationnelles (adjacency + features)  
- Construction d’une matrice enrichie  
- Standardisation  
- Validation croisée  
- Analyse ROC


## 📈 Visualisations

- Distribution des classes  
- Matrices de confusion  
- Courbes ROC  
- Variance expliquée (ACP)  
- Résultats d’optimisation  


## 🛠️ Technologies
 
- scikit‑learn  
- imbalanced‑learn   
