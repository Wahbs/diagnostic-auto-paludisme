# Prédiction du Diagnostic du Paludisme

Ce projet utilise plusieurs algorithmes de machine learning pour prédire le diagnostic du paludisme à partir des données collectées via un site web conçu à cet effet. 

## Table des Matières

- [Introduction](#introduction)
- [Technologies Utilisées](#technologies-utilisées)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Structure du Projet](#structure-du-projet)
- [Modèles Entraînés](#modèles-entraînés)
- [Résultats](#résultats)
- [Contribuer](#contribuer)
- [Licence](#licence)

## Introduction

Le paludisme est une maladie grave et potentiellement mortelle. Une détection précoce et précise est essentielle pour un traitement efficace. Ce projet vise à améliorer la précision du diagnostic en utilisant diverses techniques de machine learning.

## Technologies Utilisées

- Python
- Scikit-learn
- CatBoost
- XGBoost
- Support Vector Machine (SVM)
- Flask (pour le site web)
- Pandas
- Numpy
- Jupyter Notebook

## Installation

1. Clonez le dépôt GitHub :
    ```bash
    git clone https://github.com/wahbs/diagnostic-auto-paludisme.git
    ```
2. Naviguez dans le répertoire du projet :
    ```bash
    cd diagnostic-auto-paludisme
    ```
3. Installez les dépendances :
    ```bash
    pip install -r requirements.txt
    ```

## Utilisation

Pour entraîner les modèles de machine learning, exécutez le notebook Jupyter correspondant :
    ```bash
    jupyter notebook analyse_donnees_patients.ipynb
    ```

## Structure du Projet

- `data/` : Répertoire contenant les données collectées.
- `models/` : Répertoire contenant les modèles entraînés.
- `notebooks/` : Répertoire contenant les notebooks Jupyter pour l'entraînement et l'évaluation des modèles.
- `requirements.txt` : Liste des dépendances nécessaires.
- `README.md` : Documentation du projet.

## Modèles Entraînés

Les modèles suivants ont été entraînés et évalués :

1. **RandomForestClassifier**
2. **GradientBoostingClassifier**
3. **DecisionTreeClassifier**
4. **CatBoostClassifier**
5. **SVM (Support Vector Machine)**
6. **XGBClassifier (XGBoost)**
7. **VotingClassifier** : Une combinaison de plusieurs modèles pour améliorer la performance globale.

## Résultats

Les résultats des modèles sont documentés dans le notebook Jupyter `resultats_modeles.ipynb`. Vous y trouverez les métriques de performance telles que la précision, le rappel, le F1-score et les courbes ROC.

## Contribuer

Les contributions sont les bienvenues ! Veuillez créer une issue pour discuter de ce que vous souhaitez modifier.

1. Fork le projet
2. Créez votre branche de fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. Commitez vos modifications (`git commit -m 'Add some AmazingFeature'`)
4. Poussez vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

## Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.
