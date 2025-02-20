# Formule-1-analyse-de-la-relation-masse-salariale-et-performance-des-écuries

Cette étude examine l'impact des budgets des équipes de Formule 1 sur leurs performances sportives entre 2010 et 2022. L'objectif est de déterminer si un budget plus élevé conduit systématiquement à de meilleurs résultats en championnat.

Données utilisées

Performance des équipes : Nombre total de points obtenus par saison (source : site officiel Formula 1).
Budgets des écuries : Dépenses annuelles en millions d'euros, incluant les coûts liés à la performance des voitures (source : Sportune).

Variables de contrôle :
Nombre de poles positions par saison et par équipe.
Temps moyen d'arrêt aux stands par équipe et par saison.
Nombre moyen de spectateurs par course.
Nombre d’employés par écurie et par saison.

Méthodologie
Nous avons modélisé la relation entre le budget et la performance à l'aide de régressions économétriques :
Modèle 1 MCO simple
Modèle 2 MCO avec variables de contrôle
Modèle 3 GLS pour résorber l'autocorrélation

Résultats

Le modèle simple explique 28,4 % de la variance des points obtenus.
L'ajout des variables de contrôle améliore considérablement l'explication avec un R² ajusté de 0,780.
Le nombre de salariés et les poles positions ont une influence significative sur la performance.
L’autocorrélation des résidus n'a pas été corrigée même avec un modèle de moindres carrés généralisés (GLS), ce qui constitue une limite importante de notre analyse.

Conclusion

Bien que le budget soit un facteur clé de la performance en Formule 1, il ne suffit pas à lui seul pour expliquer les résultats des équipes. D'autres variables, comme le personnel et les performances en qualifications, jouent un rôle déterminant.
