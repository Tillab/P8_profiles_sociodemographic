# Détecter des faux billets avec le Machine Learning
Projet 8 OpenClassrooms

### Contexte et démarche
L’Organisation nationale de lutte contre le faux-monnayage (ONCFM, organisation fictive) cherche à améliorer l’identification des faux billets. À partir d’un jeu de données de 1 500 billets scannés, dont l’authenticité était connue, j’ai entraîné et évalué plusieurs algorithmes de Machine Learning afin d’identifier l’approche la plus adaptée à cette tâche.

<img src = presentation/P8_sociodemograpique_heatmap.png height = 300 >

### Résultats et impact
Les algorithmes testés — régression logistique, K-means, K plus proches voisins, Random Forest et réseau de neurones — ont obtenu de bons résultats sur le jeu de données disponible. J’ai retenu la régression logistique pour sa simplicité et son interprétabilité, puis je l’ai utilisée pour prédire l’authenticité de billets dans un jeu de données distinct.

**Compétences :** Python (pandas, scikit-learn), algorithmes de Machine Learning, évaluation de modèles.

**Limite :** Les performances obtenues sur le jeu de données disponible ne garantissent pas le même niveau de précision pour des billets provenant d’autres sources ou numérisés dans des conditions différentes.

<img src = presentation/P8_sociodemographique_DAG.png = 300 >
