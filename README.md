# Arbres de Décision : De la Théorie à l'Implémentation

## Description
Ce projet illustre le fonctionnement des **arbres de décision** (classification). Il décompose l'algorithme en deux parties :
1. **Implémentation Mathématique** : Calcul manuel de l'entropie et du gain d'information pour comprendre comment l'algorithme choisit le meilleur critère de division.
2. **Implémentation Automatisée** : Utilisation du package `rpart` pour construire et visualiser un arbre de classification efficace sur un dataset de prise de décision.

## Contenu du Script
- **Entropie** : Fonction calculant l'impureté des données pour quantifier l'incertitude.
- **Gain d'Information** : Calcul pour les variables *Météo, Amis, Vent et Jour* afin de déterminer le facteur le plus discriminant.
- **Modélisation** : Construction d'un arbre `rpart` avec contrôle des paramètres de split (`minsplit`) et de complexité (`cp`).

## Compétences Démontrées
- Algorithmes supervisés (CART).
- Analyse statistique de l'incertitude.
- Visualisation de modèles prédictifs.

## Comment lancer le projet
1. Assure-toi d'avoir R installé avec le package `rpart` : `install.packages("rpart")`.
2. Exécute le script `decision_tree.R`.
3. L'arbre s'affichera directement dans ta fenêtre graphique RStudio.
