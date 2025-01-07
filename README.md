# Stage GIREF 2024


Ce stage s'est déroulé en deux parties principales :

## 1. Apprentissage de la Méthode des Éléments Finis
La première partie était consacrée à l'apprentissage théorique et pratique de la **méthode des éléments finis (MEF)**. J'ai implémenté cette méthode en 1D en Python afin de mieux comprendre les concepts fondamentaux.

   **Fichier à consulter** : [`giref.ipynb`](./giref.ipynb)

## 2. Recherche : Quantification d'Incertitude
La seconde partie était orientée vers la recherche et consistait à intégrer des **paramètres aléatoires** dans les modèles d'EDP pour quantifier l'incertitude via des simulations Monte Carlo.

- **Application 1D** : Simulation en 1D avec des paramètres aléatoires.  
    **Fichier à consulter** : [`giref.ipynb`](./giref.ipynb)
  
- **Application 3D** : Étude des déformations et du stress de von Mises sur une poutre en acier.  
  - Les simulations Monte Carlo ont été réalisées à l'aide du logiciel **MEF++**, développé par le GIREF.  
  - L'analyse des résultats a été effectuée en Python.  
     **Fichier à consulter** : [`giref_3D.ipynb`](./giref_3D.ipynb)



En conclusion du stage, j'ai réalisé une présentation détaillée lors du **CIMMUL** (Université Laval). Cette présentation a couvert :  
- La méthodologie et les résultats des simulations Monte Carlo en 1D et 3D.
- L'évaluation des incertitudes et l'application des méthodes statistiques (percentiles, bootstrap-t, etc.).
- L'interprétation des résultats, notamment sur la déformation de matériaux sous contraintes aléatoires.
- 
 **Fichier PDF** : [`stage_giref.pdf`](./stage_giref.pdf)

---

Ce stage a été supervisé par le professeur **Félix Kwok**, membre du GIREF. Vous pouvez consulter son profil ici : https://giref.ulaval.ca/~fkwok/index_en.htm

