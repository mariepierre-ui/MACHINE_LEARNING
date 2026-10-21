# Machine Learning

Travaux pratiques réalisés dans le cadre de mon M2 Mathématiques appliquées : des algorithmes d'apprentissage implémentés de zéro en Python, comparés ensuite aux implémentations de scikit-learn.

## Contenu

- **TP1 : Prise en main des données avec scikit-learn** : chargement et exploration de jeux de données (Iris, MNIST via OpenML), statistiques descriptives par variable, génération de données synthétiques (make_blobs) et visualisation.
- **TP2 : Prétraitement, visualisation et réduction de dimension** : standardisation et normalisation MinMax, visualisation des combinaisons de variables, réduction de dimension par ACP et analyse discriminante linéaire (LDA), avec une comparaison des deux projections.
- **TP3 : Descente de gradient** : implémentation de la descente de gradient en une dimension (pas d'apprentissage, bassins d'attraction, critères d'arrêt), puis application à la régression linéaire et ouverture sur la descente de gradient stochastique.
- **TP4 : k plus proches voisins et classifieur bayésien naïf** : implémentation from scratch du 1-PPV et du k-PPV avec estimation de l'erreur en leave-one-out, distinction entre erreur d'apprentissage et erreur de généralisation, et étude du sous-apprentissage selon k. Implémentation d'un classifieur bayésien naïf, puis d'une version gaussienne qui retrouve les performances de GaussianNB.
- **TP5 : Clustering et classification, étude comparative** : implémentation de k-means avec sélection automatique du nombre de groupes. Comparaison de plusieurs algorithmes de clustering (k-means, MeanShift, Affinity Propagation, Spectral Clustering, DBSCAN) avec des scores internes (Silhouette, Davies-Bouldin) et externes (AMI, ARI). Comparaison de classifieurs (k-PPV, Bayes naïf, SVM, perceptron multicouche) en validation croisée leave-one-out (precision, recall, F1-score), appliquée aux jeux Iris et Wine.

## Outils

Python (Jupyter Notebook), numpy, matplotlib, scikit-learn

## Compétences

- Implémentation d'algorithmes d'apprentissage from scratch
- Prétraitement et réduction de dimension (ACP, LDA)
- Optimisation par descente de gradient
- Classification supervisée et clustering
- Évaluation de modèles : validation croisée, métriques internes et externes, precision/recall/F1