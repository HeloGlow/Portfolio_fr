# Projet 3️⃣ : Clustering de clients potentiels selon des critères démographiques et économiques

## 🧩 Problématique :

HéloGlow va bientôt ouvrir un nouveau magasin au sein d’un centre commercial. Nous avons obtenu des données sur la clientèle du centre, et nous souhaitons les utiliser pour créer des clusters afin de mieux comprendre notre future potentielle clientèle. Ainsi, nous serons en mesure d'optimiser l’assortiment, d'activer les bons leviers marketing et de personnaliser la communication auprès des cibles.

## ⚙️ Démarche :

### 1) Recherche d’un dataset

J'ai trouvé sur Kaggle un dataset se prêtant bien à cette analyse : [Mall Customers Segmentation](https://www.kaggle.com/datasets/abdallahwagih/mall-customers-segmentation). Il contient une liste de clients d'un centre commercial, avec leurs caractéristiques démographiques, leur revenu annuel et leur score de dépenses.

### 2) Clustering en Python

J'ai réalisé l'analyse en Python sur un Jupyter Notebook, en détaillant et expliquant chaque étape : [code Python](https://github.com/HeloGlow/Portfolio_fr/blob/main/Projet_3/HeloGlow_clustering_clients.ipynb)
- Vérification des données
- Création de nouveaux champs
- Réduction de dimensions avec une ACP (Analyse en Composantes Principales)
- Clustering K-means
- Clustering hiérarchique

### 3) Détermination de portraits-robots et personas

Suite au clustering, j'ai précisé les portraits-robots des différents types de clients potentiels et je leur ai donné vie au travers de personas. J'ai également déterminé les cibles prioritaires.

## 🗂️ Livrables :

**Livrable 1) : le Jupyter Notebook du clustering**

[Jupyter Notebook](https://github.com/HeloGlow/Portfolio_fr/blob/main/Projet_3/HeloGlow_clustering_clients.ipynb)

**Livrable 2) : l'identification de personas et la priorisation des cibles**

**🎯 Cible principale : le 2<sup>e</sup> cluster**

<img src="https://github.com/HeloGlow/Portfolio_fr/blob/main/Projet_3/Personas/Persona%202e%20cluster.png?raw=true" width="600">

**🥈 Cible secondaire : le 3<sup>e</sup> cluster**

<img src="https://github.com/HeloGlow/Portfolio_fr/blob/main/Projet_3/Personas/Persona%203e%20cluster.png?raw=true" width="600">

**🗑️ Cluster à ne pas cibler : le 1<sup>er</sup> cluster**

<img src="https://github.com/HeloGlow/Portfolio_fr/blob/main/Projet_3/Personas/Persona%201er%20cluster.png?raw=true" width="600">
