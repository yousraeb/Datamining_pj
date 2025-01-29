# Projet d'Analyse de Campagne Marketing avec PCA et KMeans

## Aperçu
Ce projet explore l'application de la réduction de dimensionnalité avec PCA (Principal Component Analysis) et le clustering avec KMeans sur les données d'une campagne marketing. Le but est d'analyser les caractéristiques des clients et de les regrouper en différents segments pour mieux comprendre les comportements d'achat.

Les étapes principales du projet incluent :
1. Prétraitement des données.
2. Application de PCA pour réduire la dimensionnalité.
3. Application de KMeans pour segmenter les clients en différents groupes.

## Structure du Projet
Le projet est organisé comme suit :
```plaintext
Répertoire du Projet
|
|-- marketing_campaign.csv        # Fichier CSV contenant les données de la campagne marketing
|-- notebook651aaf7c99.ipynb      # Notebook Jupyter contenant l'analyse complète (PCA, KMeans, Visualisations)
|-- README.md
## Jeu de Données
Le jeu de données utilisé pour ce projet provient d'une campagne marketing et contient des informations sur les clients, leurs caractéristiques démographiques et leurs comportements d'achat. Vous pouvez trouver le fichier CSV dans le répertoire du projet sous le nom marketing_campaign.csv.

## Flux de Travail

### 1. Pré-traitement des Données
Le jeu de données est chargé depuis le fichier marketing_campaign.csv et les étapes suivantes sont réalisées :
   -Nettoyage des valeurs manquantes.
   -Transformation des données catégorielles en variables numériques si nécessaire.
   -Normalisation des données pour le clustering et la réduction de dimensionnalité.

### 2. Application de PCA (Réduction de Dimensionnalité)
-PCA est appliqué pour réduire la dimensionnalité des données tout en préservant l'essentiel de l'information.
-Le notebook présente la variance expliquée par chaque composant principal.

### 3. Application de KMeans (Clustering)
Chaque ensemble de caractéristiques sélectionné est testé avec trois algorithmes de classification :

- L'algorithme KMeans est utilisé pour segmenter les clients en différents groupes basés sur leurs caractéristiques.
- Le nombre optimal de clusters est déterminé à l'aide de la méthode du coude et les résultats sont visualisés.

### 4. Visualisations et Résultats
- Des visualisations sont générées dans le notebook pour illustrer les segments de clients obtenus après le clustering.
- Le notebook présente des graphiques pour mieux comprendre les clusters et leurs caractéristiques principales.

## Comment Exécuter le Projet
1. Clonez le répertoire :
   ```bash
   git clone <repository_link>
   ```
2. Installez les packages Python requis :
   ```bash
   pip install -r requirements.txt
   ```
3. Ouvrez le notebook Jupyter pour exécuter l'analyse :
   ```bash
   jupyter notebook notebook651aaf7c99.ipynb
   ```
4. Suivez les étapes dans le notebook pour effectuer le prétraitement, appliquer PCA et KMeans, et générer des visualisations.

## Résultats 
Les résultats de l'analyse seront générés dans le notebook. Les visualisations des clusters et la variance expliquée par PCA seront affichées directement dans le notebook. Assurez-vous de vérifier les graphiques générés pour mieux comprendre les segments créés.

## Travaux Futurs
- Tester d'autres techniques de réduction de dimensionnalité comme t-SNE ou UMAP.
- Appliquer d'autres algorithmes de clustering, comme DBSCAN, pour comparer les résultats.
- Intégrer des données supplémentaires pour enrichir l'analyse et les segments clients.

---

Pour toute question ou contribution, n'hésitez pas à nous contacter !

