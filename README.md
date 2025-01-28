# Clustering PCA et KMeans sur Kaggle

Ce dépôt contient un projet réalisé sur Kaggle, utilisant une combinaison de l'analyse en composantes principales (PCA) et du clustering KMeans pour analyser un ensemble de données.

### Objectif du projet
L'objectif de ce projet est d'appliquer l'algorithme de PCA pour réduire la dimensionnalité d'un jeu de données et d'utiliser l'algorithme de KMeans pour effectuer un clustering. Ensuite, nous visualiserons les résultats obtenus sous forme de graphiques pour comprendre la distribution des données et des clusters.

### Étapes du projet
1. **Prétraitement des données** : 
   - Chargement et nettoyage des données.
   - Mise à l'échelle des données pour les rendre compatibles avec les algorithmes de PCA et KMeans.
   
2. **Application de PCA** : 
   - Réduction des dimensions du jeu de données pour obtenir les deux principales composantes.
   
3. **Application de KMeans** : 
   - Clustering des données réduites en deux dimensions à l'aide de l'algorithme KMeans.
   - Identification des clusters formés.

4. **Visualisation** : 
   - Création de graphiques pour afficher les résultats du clustering et la distribution des données dans l'espace réduit.

### Structure du projet
Le projet est structuré de manière à être facilement compréhensible et réutilisable. Les fichiers principaux sont les suivants :

- `PCA_KMeans_Clustering.ipynb` : Le notebook principal contenant l'analyse des données, la réduction de dimension avec PCA, et l'application de KMeans pour le clustering.
- `requirements.txt` : Ce fichier contient toutes les dépendances nécessaires pour exécuter le projet localement.
- `data/` : Ce répertoire contient les fichiers de données utilisés pour l'analyse (si applicable).

### Pré-requis
Pour exécuter ce projet sur votre machine locale, vous devez avoir Python 3.x installé ainsi que les bibliothèques suivantes :
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

Vous pouvez installer ces bibliothèques en exécutant la commande suivante dans votre terminal (si vous avez un fichier `requirements.txt`) :

```bash
pip install -r requirements.txt
