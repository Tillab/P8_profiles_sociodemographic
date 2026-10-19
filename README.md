# Étudier l’évolution du profil sociodémographique des étudiants Data d’OpenClassrooms
Projet 8 OpenClassrooms

### Contexte et démarche

La plateforme de formation en ligne OpenClassrooms souhaitait mieux comprendre le profil sociodémographique des étudiants inscrits à ses formations Data. J’ai analysé des données internes d’inscription couvrant la période 2022–2025, que j’ai complétées avec des données démographiques publiques de l’INSEE.
J’ai construit un pipeline de transformation avec dbt Cloud et Snowflake pour préparer, transformer et valider les données. J’ai ensuite réalisé l’analyse exploratoire et les visualisations en Python.

<img src = presentation/P8_sociodemograpique_heatmap.png height = 300 >

### Résultats et impact
L’analyse a apporté des éléments pour alimenter la réflexion sur les moyens de rendre les formations d’OpenClassrooms plus accessibles et plus équitables.

**Compétences :** dbt Cloud, Snowflake, transformation et modélisation des données, Python (Matplotlib, Seaborn), qualité des données, prise en compte du RGPD.

**Limite :** Les résultats décrivent les données d’inscription disponibles et dépendent de la compatibilité entre les données internes et les données démographiques publiques, notamment en matière de période, de catégories et de couverture.

<img src = presentation/P8_sociodemographique_DAG.png height = 300 >
