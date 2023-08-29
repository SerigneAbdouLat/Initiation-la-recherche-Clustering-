# Initiation-la-recherche-Clustering-
Optimisation de la stabilité  des résultats de Kmeans en utilisant une approche de clustering hybride avec Hierarchical clustering (HCA).

Le clustering non supervise est une technique couramment utilisée pour explorer des structures dans des donnees sans étiquette préalable.
K-means est une méthode populaire de clustering non supervise, cependant, il est connu pour être sensible à l’initialisation des centres, ce qui peut conduire a une faible stabilité des résultats. 

Pour remedier à ce problème, nous proposons dans cet article une approche hybride de cluster-ing  qui utilise le clustering hierarchique (HCA) pour initialiser les centres de K-means.
Notre objectif est d’optimiser la stabilite des résultats de K-means tout en préservant la qualité des clusters obtenus.
Nous avons utilise les indices de mesure ARI et Silhouette scores pour évaluer la qualité de nos clusters. 
Nous avons egalement effectué plusieurs exécutions de K-means et notre approche hybride pour verifier la stabilité de notre solution.
Les résultats de nos expériences montrent que notre approche hybride ameliore significativement la stabilité des clusters par rapport à K-means seul, ce qui en fait une technique prometteuse pour une varieté d’applications de clustering ou
la stabilite des résultats est critique.
