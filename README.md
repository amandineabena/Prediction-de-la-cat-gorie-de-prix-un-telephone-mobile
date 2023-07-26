# Prediction-de-la-cat-gorie-de-prix-un-telephone-mobile
## Apprentissage Statistique

### Introduction
Bob est un fabriquant de téléphones mobiles, qui a récolté des données sur ses produits, et
qui souhaite en fonction des caractéristiques communes des téléphones obtenir une fourchette
de prix, donc avoir des gammes de téléphones. C’est une problématique de classification, car
notre objectif ici est de prédire la classe de prix la plus probable pour un téléphone.
Il était donc question, dans ce projet, de mettre en oeuvre certaines stratégies que nous avons
vu en cours d’apprentissage statistique afin d’aider Bob à estimer au mieux les catégories
de prix des téléphones qu’il produit. Nous avons donc testé de multiples algorithmes dans le
but de déterminer celui qui prédit le mieux les catégories de prix.
Afin d’évaluer la performance de chacun, nous avons choisi une métrique commune qui est
l’accuracy_score. Cette dernière permet de mesurer la proportion de bonnes prédictions sur
les données de la base de validation. Nous avons commencé ce travail par une rapide analyse
des données, puis nous avons appliqué les différents modèles et enfin nous avons sélectionné
celui qui nous semblait le plus pertinent afin de prédire les catégories de prix.


### Description de la base de données 
Nous avons importé nos données dans deux dataframe distincts, train et test. Dans
cette analyse descriptive nous nous sommes focalisé sur la base train afin de dégager
les informations nécessaires pour la modélisation. Ainsi, notre base train contient 21
variables et 2000 observations. Les variables correspondent aux caractéristiques du téléphone, comme par exemple la taille de l’écran en pixels, la puissance de la batterie, la ram
etc. mais également les catégories de prix.

