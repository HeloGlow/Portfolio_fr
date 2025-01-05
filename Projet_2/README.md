# Projet 2️⃣ : Reporting et dashboard automatisés sur les performances du programme de fidélité

## 🧩 Problématique :

Dans un secteur aussi compétitif que celui des cosmétiques, il est essentiel pour HéloGlow de bien comprendre son marché pour innover et se démarquer. Notre objectif est donc d'analyser en profondeur les dynamiques du secteur, d'identifier les tendances clés et de repérer les besoins non satisfaits. Ces insights permettront d’orienter le développement de nouveaux produits adaptés aux attentes des consommateurs.

## ⚙️ Démarche :

### 1) Recherche de datasets

J'ai trouvé sur Kaggle un dataset pouvant coller à ce scénario : [Top Beauty & Cosmetics Products Worldwide 2024](https://www.kaggle.com/datasets/waqi786/most-used-beauty-cosmetics-products-in-the-world). Attention, il s'agit d'un dataset d'entraînement, qui ne reflète pas la réalité.

Par ailleurs, j'ai complété mon analyse avec des données Google Trends. Pour récupérer la volumétrie des recherches en valeur absolue, j'ai utilisé l'extension Chrome "Google Trends Glimpse".

### 2) Vérification et traitement des données en SQL sur Dataiku

Après avoir importé mon dataset Kaggle dans Dataiku, j'ai effectué des vérifications et des corrections sur la table initiale à l’aide d’un script SQL.

Ensuite, j'ai manipulé les données en SQL pour générer les tables nécessaires à l'alimentation du dashboard Tableau. Les étapes détaillées sont présentées ici sous forme de codes commentés : [codes SQL](https://github.com/HeloGlow/Portfolio_fr/blob/main/Projet_2/SQL_Dataiku_Projet_2).<br>

### 3) Réalisation d'un dashboard sur Tableau

Avec Tableau Desktop, j'ai construit un dashboard en deux parties :
- Une vue d'ensemble du marché, présentant les chiffres clés du secteur des cosmétiques, les principales forces en présence, ainsi qu'une analyse par catégorie (avec des filtres dynamiques)
- Des analyses complémentaires pour déterminer quel nouveau produit nous devrions commercialiser : satisfaction par type de client, identification de niches de marché à combler, choix de la formulation, du packaging, du pricing, de la période idéale pour le lancement..."

## 🗂️ Livrable : le dashboard Tableau

Téléchargeable sur mon GitHub : [Fichier Tableau](https://github.com/HeloGlow/Portfolio_fr/blob/main/Projet_2/HeloGlow_Tableau_fr.twbx)<br>

Consultable en ligne sur Tableau Public :
[1) Vue d'ensemble du marché](https://public.tableau.com/app/profile/h.lo.se.vrt/viz/HeloGlow_Projet2_Page1/Vuedensembledumarch) - 
[2) Notre futur produit](https://public.tableau.com/app/profile/h.lo.se.vrt/viz/HeloGlow_Projet2_Page2/Notrefuturproduit)<br>

<img src="https://github.com/HeloGlow/Portfolio_fr/blob/main/Projet_2/HeloGlow_Tableau_Page1.png?raw=true">
<img src="https://github.com/HeloGlow/Portfolio_fr/blob/main/Projet_2/HeloGlow_Tableau_Page2.png?raw=true">
