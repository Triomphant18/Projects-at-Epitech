# Projet de Classification des espèces d'Iris

Ce projet vise à construire des classificateurs binaires pour trois espèces différentes d'Iris (Iris setosa, Iris virginica et Iris versicolor) en utilisant l'algorithme LinearSVC de la bibliothèque scikit-learn.

## Dataset

Le jeu de données se compose de 50 échantillons de chaque espèce d'Iris. Pour chaque échantillon, vous disposez de la longueur et de la largeur des pétales en centimètres.

## Objectifs

Les objectifs principaux de ce projet sont les suivants :

1. Créer un classificateur binaire pour détecter chaque espèce d'Iris en utilisant LinearSVC.
2. Tracer les frontières de décision des modèles.
3. Afficher les indicateurs de performance des modèles tels que le score de précision, le score de rappel, la matrice de confusion et la courbe ROC.
4. Utiliser StandardScaler pour standardiser le jeu de données en tant qu'étape de prétraitement et évaluer si cela améliore les scores des modèles.
5. Essayer différentes valeurs de l'hyperparamètre C (marge séparant les deux vecteurs de support) pour obtenir le meilleur score. Identifier la meilleure valeur de C.

## Auteur

Triomphant Ben Ali SUANON

## Ressources

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Documentation LinearSVC](https://scikit-learn.org/stable/modules/generated/sklearn.svm.LinearSVC.html)
- [Documentation StandardScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)
