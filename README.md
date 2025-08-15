**Fraud Detection**

Ce projet a pour but de détecter les fraudes dans des transactions bancaires grâce à l'analyse de données et à des modèles de machine learning. Il s'agit d'une mise en œuvre complète d'un pipeline de détection d'anomalies dans un dataset financier réel.

**Fichier principal**

Fraud_Detection.ipynb : Notebook Jupyter contenant toutes les étapes du projet, de l’exploration des données à l’évaluation du modèle.

**Objectif du projet**

Le but est de :

- Comprendre les caractéristiques des transactions frauduleuses.

- Construire un modèle robuste capable de détecter ces anomalies malgré un fort déséquilibre de classes.

- Mettre en œuvre des techniques de preprocessing et de sélection de variables adaptées.

**Dataset utilisé**

Nom : Credit Card Fraud Detection (anonymisé)

Source : Kaggle

Dimensions :

Variables anonymisées V1 à V28 (résultant d'une PCA)

Time, Amount, Class (0 = transaction normale, 1 = fraude)

**Étapes du projet**

Exploration des données (EDA) : compréhension du déséquilibre, visualisation.

Prétraitement :

Standardisation des variables Time et Amount

Sélection des variables utiles

Modélisation :

Entraînement d’un modèle de classification (RandomForest ou LogisticRegression selon version)

Évaluation :

Matrice de confusion, F1-score, Recall, Précision

Courbes ROC/AUC optionnelles

**Limitations**

Dataset très déséquilibré : les modèles doivent être adaptés pour éviter les biais.

Les variables sont anonymisées, limitant l'interprétabilité métier.

**Pistes d’amélioration**

Tester d’autres modèles (XGBoost, LightGBM)

Implémenter un système de cross-validation

Déployer sous forme d’API ou d’interface interactive (ex. : Streamlit)

**Auteur**

Hadjira Riad
