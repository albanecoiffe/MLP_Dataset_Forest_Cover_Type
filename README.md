# Lab : Classification Multi-Classes avec scikit-learn MLPClassifier sur le Dataset Forest Cover Type 🌲   

## 🎯 Objectif :   
Dans ce laboratoire, vous allez implémenter un modèle de `Multi-Layer Perceptron (MLP)` en utilisant scikit-learn pour classifier les différents types de couvertures forestières.    
Les étapes de profiling des données et de prétraitement ont déjà été effectuées dans un laboratoire précédent.

## 🛠️ Étapes

**Prétraitement des Données (réalisé dans un lab précédent) :**
- Normalisation des données avec StandardScaler.
- Encodage des labels cibles avec One-Hot Encoding.
- Division des données en ensembles d'entraînement et de test (80/20).

**Construction du Modèle MLP :**
- Utilisation du MLPClassifier de scikit-learn.
- Architecture : 2 couches cachées avec 128 et 64 neurones respectivement, activation ReLU, optimiseur Adam.

**Entraînement du Modèle :**
- Ajustement du modèle sur l'ensemble d'entraînement sans besoin d'encodage des labels en one-hot.

**Évaluation du Modèle :**
- Prédiction des labels sur l'ensemble de test.
- Génération de métriques d'évaluation : précision, matrice de confusion, rapport de classification.

**Visualisation de la Matrice de Confusion :**
- Affichage de la matrice de confusion sous forme de heatmap pour mieux comprendre les performances du modèle.

**Expérimentation avec les Hyperparamètres :**
- Exploration de l'impact des hyperparamètres tels que le nombre de couches cachées, le taux d'apprentissage et la régularisation sur les performances du modèle.

