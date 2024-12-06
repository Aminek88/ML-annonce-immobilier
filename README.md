# ML-annonce-immobilier

Ce projet utilise des modèles de régression et de classification pour prédire les prix immobiliers et classer les propriétés en fonction de la présence ou de l'absence d'ascenseur.

# Aperçu du projet
Ce projet combine :

Régression polynomiale pour prédire les prix des biens immobiliers.
Classification avec des modèles de machine learning (Logistic Regression, Random Forest, XGBoost, Gradient Boosting) pour identifier les propriétés disposant d'un ascenseur.
Les données incluent des caractéristiques telles que :

Nombre de chambres, salons, salles de bain.
Superficie, étage, âge de la propriété, etc.

# Prérequis
Avant de commencer, assurez-vous d'avoir :

Python 3.7+ installé.
Les bibliothèques nécessaires installées :
  {pandas
  numpy
  scikit-learn
  matplotlib  
  seaborn
  imbalanced-learn
  xgboost}.
Un IDE comme Jupyter Notebook ou Visual Studio Code.


# Structure du projet
Voici la structure des fichiers principaux du projet :
.

├── data/

│   ├── dataset.csv        # Données initiales

│   ├── processed_data.csv         # Données après prétraitement

├── notebooks/

│   ├── regression_analysis.ipynb  # Analyse et prédiction des prix

│   ├── classification.ipynb       # Classification pour l'ascenseur

├── src/

│   ├── preprocessing.py           # Code de prétraitement

│   ├── models.py                  # Construction et évaluation des modèles

├── requirements.txt               # Liste des dépendances

└── README.md                      # Ce fichier


# Instructions pour exécuter le projet

1. Préparer les données
Placez le fichier dataset.csv dans le dossier data/.

2. Exécuter les analyses
Régression : Ouvrez et exécutez notebooks/regression_analysis.ipynb pour prédire les prix.
Classification : Ouvrez et exécutez notebooks/classification.ipynb pour prédire la présence d'un ascenseur.

3. Résultats
Les fichiers générés, tels que les graphiques et les métriques, seront sauvegardés dans le dossier output/.

# Résultats
Régression Polynomiale (degré 2) :

MSE : 0.0019

R² : 0.60264

Classification (Meilleur modèle : Random Forest) : 0.80


recall = 0.89

Accuracy : 0.80

Rapport de classification : 0.80


# Auteur
Nom : Mohammed Amine Ait Khazant
Contact : amine.kon@gamail.com



