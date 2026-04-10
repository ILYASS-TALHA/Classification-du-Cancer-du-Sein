🧠 Breast Cancer Classification (Advanced ML)
📌 Description

Ce projet implémente une solution avancée de classification du cancer du sein en utilisant des techniques modernes de Machine Learning et d’optimisation.

L’objectif est de prédire si une tumeur est bénigne ou maligne à partir de caractéristiques médicales.

⚙️ Technologies utilisées
Python
Scikit-learn
CatBoost
Optuna (Hyperparameter Optimization)
SHAP (Explainable AI)
Matplotlib / Seaborn
🧪 Pipeline du projet
1. Analyse exploratoire (EDA)
Distribution des classes
Corrélation des features
Boxplots des variables importantes
2. Prétraitement
Split train/test (80/20)
Normalisation des données
3. Modèles de base
Logistic Regression
KNN
SVM
Random Forest
4. Modèle avancé
CatBoost Classifier
5. Optimisation
Optuna (TPE Sampler)
150 essais pour trouver les meilleurs hyperparamètres
6. Interprétabilité
SHAP values
Importance des features
📊 Résultats
Modèle final : CatBoost optimisé
Très haute précision (≈ 97–99%)
Bon équilibre entre précision et recall
📈 Visualisations
Heatmap de corrélation
Courbes ROC
SHAP plots
📂 Structure
├── cancer_sein.ipynb
├── figures/
├── models/
├── README.md
└── requirements.txt
🚀 Lancer le projet
pip install -r requirements.txt
jupyter notebook cancer_sein.ipynb
💡 Points forts
Optimisation automatique avec Optuna
Modèle performant (CatBoost)
Explicabilité avec SHAP
