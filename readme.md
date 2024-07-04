# 🦜 Analyse de la Diversité des Espèces d'Oiseaux à Bordeaux et Périphérie

## 🌟 Introduction

Dans le cadre de notre projet de statistiques, nous avons travaillé sur un jeu de données environnementales composé de plusieurs fichiers contenant des informations sur les oiseaux, les stations de mesure, les caractéristiques des oiseaux, leurs régimes alimentaires et la biodiversité.

Ce rapport a pour objectif de présenter les différentes analyses réalisées sur ces données. Il est composé de plusieurs parties principales où nous explorons les relations entre la diversité des espèces d’oiseaux, l’artificialisation des sols et la distance avec le centre-ville de Bordeaux. Nous avons également étudié les régimes alimentaires des oiseaux et les modes de nidification en fonction de certaines zones géographiques.

## 🔍 Exploration des données

Nous avons commencé par charger les données et les explorer pour mieux comprendre leur structure. Une colonne avec les noms latins des oiseaux a été ajoutée pour faciliter les analyses. Voici un tableau qui montre les 10 espèces d’oiseaux les plus fréquemment observées dans l’ensemble des données :

| Espèce                   | Fréquence |
|--------------------------|-----------|
| Sylvia atricapilla       | 308       |
| Parus major              | 300       |
| Turdus merula            | 299       |
| Columba palumbus         | 291       |
| Phylloscopus collybita   | 251       |
| Erithacus rubecula       | 230       |
| Sturnus vulgaris         | 221       |
| Troglodytes troglodytes  | 211       |
| Fringilla coelebs        | 198       |
| Certhia brachydactyla    | 169       |

Nous avons également exploré la fréquence des espèces d’oiseaux par année, et nous avons mesuré la diversité à l’aide de plusieurs entropies (proportion d’espèces, indice de Shannon, indice de Simpson) en nous focalisant sur les surfaces artificialisées (MOS11).

## 🌆 Tendance de diversité par rapport à la distance avec le centre-ville

Nous avons analysé la diversité des espèces d’oiseaux en fonction de la distance avec le centre-ville de Bordeaux. Les résultats montrent que la diversité est maximale à environ 9 km du centre-ville, corroborant les observations faites avec la variable d’artificialisation des sols.

## 🌐 Analyses interactives et géographiques
Nous avons réalisé des analyses géographiques et interactives pour visualiser comment les oiseaux de la Gironde évoluent en fonction de l’artificialisation des sols, des régimes alimentaires et des modes de nidification.  

- 🗺️ Carte interactive des mailles de mesure et des oiseaux les plus observés : Permet de visualiser les espèces d’oiseaux par zone géographique.
- 🍽️ Carte des régimes alimentaires : Montre la répartition des régimes alimentaires des oiseaux par maille.
- 🏡 Carte des modes de nidification : Illustre les types de nidification en fonction des zones géographiques.

## 🚀 Pour aller plus loin
Nous avons créé un Parallel Coordinates Plot et un sunburst plot pour illustrer les caractéristiques des différentes espèces d’oiseaux. Ces visualisations interactives permettent de mieux comprendre les relations entre les différentes variables.

## 📝 Conclusion
Notre étude a révélé que la diversité des espèces d’oiseaux est étroitement liée à l’artificialisation des sols et à la distance au centre-ville. Les zones de transition entre les espaces urbains et ruraux sont des zones clés pour la diversité des espèces d’oiseaux. Nous avons également constaté que les oiseaux sont capables de s’adapter à leur environnement et de trouver de la nourriture même dans les zones urbaines. Ces résultats soulignent l’importance de préserver les habitats naturels dans les zones urbaines pour maintenir la biodiversité des oiseaux.

## 👥 Auteurs
- Alexandre Leys
- Baptiste Gerbouin
- Hamad Tria
- Louis Delignac
- Théo Lavandier
