# Cercle des Experts : les notebooks

Les notebooks qui accompagnent les mini-cours de [MonShotData](https://www.monshotdata.com). Chaque mini-cours explique **pourquoi** une méthode fonctionne ; son notebook te permet de **la faire tourner et de la modifier** toi-même.

Clique sur le badge **Open in Colab** en haut d'un notebook pour l'exécuter dans ton navigateur, sans rien installer. Chaque notebook commence par un court « Avant de lancer » qui indique ce dont il a besoin (CPU suffisant, données téléchargées automatiquement, etc.).

## Les notebooks


### [ML classique et Deep Learning](https://www.monshotdata.com/mini-cours/ml-classique-et-deep-learning)


**2.1 Fondations mathématiques**

| Mini-cours | Notebook |
|---|---|
| [Régression Logistique : Pourquoi la Sigmoïde (et pas une autre) ?](https://www.monshotdata.com/p/regression-logistique-sigmoide) | [`regression-logistique-sigmoide/`](regression-logistique-sigmoide) |
| [Comprendre enfin pourquoi le bagging marche (et pas seulement comment)](https://www.monshotdata.com/p/bagging) | [`bagging/`](bagging) |

**2.2 Régression et classification**

| Mini-cours | Notebook |
|---|---|
| [Modèles Linéaires Généralisés (GLM) : la régression linéaire réinventée](https://www.monshotdata.com/p/modeles-lineaires-generalises-glm) | [`modeles-lineaires-generalises-glm/`](modeles-lineaires-generalises-glm) |
| [Le tuning d'hyperparamètres (mais sans migraine)](https://www.monshotdata.com/p/tuning-hyperparametres) | [`tuning-hyperparametres/`](tuning-hyperparametres) |
| [Booste tes modèles ML sans changer d'algorithme (Partie 2)](https://www.monshotdata.com/p/techniques-ml-avancees-focal-loss-breathing-kmeans-features-cycliques) | [`techniques-ml-avancees-focal-loss-breathing-kmeans-features-cycliques/`](techniques-ml-avancees-focal-loss-breathing-kmeans-features-cycliques) |
| [CORAL : comment forcer tes réseaux de neurones à respecter l'ordre naturel des classes](https://www.monshotdata.com/p/coral-classification-ordinale-pytorch) | [`coral-classification-ordinale-pytorch/`](coral-classification-ordinale-pytorch) |

**2.3 Clustering et réduction de dimension**

| Mini-cours | Notebook |
|---|---|
| [Comprendre les Modèles de Mélange Gaussien (GMMs)](https://www.monshotdata.com/p/modeles-melange-gaussien-gmm) | [`modeles-melange-gaussien-gmm/`](modeles-melange-gaussien-gmm) |
| [DBSCAN++ : Passe ton Clustering à l'échelle supérieure](https://www.monshotdata.com/p/dbscan-plus-plus-clustering-scalable) | [`dbscan-plus-plus-clustering-scalable/`](dbscan-plus-plus-clustering-scalable) |
| [t-SNE depuis Zéro (Partie 2)](https://www.monshotdata.com/p/formulation-implementation-algorithme-t-sne-partie-2) | [`formulation-implementation-algorithme-t-sne-partie-2/`](formulation-implementation-algorithme-t-sne-partie-2) |

**2.4 Architectures et entraînement en Deep Learning**

| Mini-cours | Notebook |
|---|---|
| [KAN from scratch : implémentation complète en PyTorch](https://www.monshotdata.com/p/implementer-kan-from-scratch-pytorch) | [`implementer-kan-from-scratch-pytorch/`](implementer-kan-from-scratch-pytorch) |
| [Apprentissage Fédéré : Entraîne l'IA, Sécurise les Données](https://www.monshotdata.com/p/guide-pratique-apprentissage-federe) | [`guide-pratique-apprentissage-federe/`](guide-pratique-apprentissage-federe) |

### [Bonnes pratiques d'ingénierie](https://www.monshotdata.com/mini-cours/bonnes-pratiques-ingenierie)


**1.3 Déploiement et optimisation de modèles**

| Mini-cours | Notebook |
|---|---|
| [Compression de modèles : un levier clé pour un ML efficace](https://www.monshotdata.com/p/compression-modeles-machine-learning-efficace) | [`compression-modeles-machine-learning-efficace/`](compression-modeles-machine-learning-efficace) |

### [LLM & fine-tuning](https://www.monshotdata.com/mini-cours/llm-fine-tuning)


**1.1 Fondations des représentations de texte**

| Mini-cours | Notebook |
|---|---|
| [Bases de données vectorielles : index avancés et pratique (Partie 2)](https://www.monshotdata.com/p/bases-de-donnees-vectorielles-partie-2) | [`bases-de-donnees-vectorielles-partie-2/`](bases-de-donnees-vectorielles-partie-2) |

Les notebooks avec un exercice (bagging, t-SNE) existent en deux versions : `-exercice` (à compléter) et `-solution`.

## Organisation

Un dossier par mini-cours, nommé comme son adresse sur MonShotData. Il contient le notebook et, si besoin, ses données (`*.pkl`, `*.pickle`, images). Les notebooks téléchargent eux-mêmes leurs données depuis ce dépôt : tu n'as rien à préparer.

## Droits d'utilisation

© 2026 MonShotData. Tous droits réservés. Aucune licence n'est accordée sur le contenu de ce dépôt : tu peux le consulter et exécuter les notebooks pour ton apprentissage personnel, mais pas le republier, le revendre ni l'intégrer à une formation ou un produit, en tout ou en partie, sans accord écrit préalable.

## Une erreur, une question ?

Les Issues sont désactivées sur ce dépôt. Écris-nous via [monshotdata.com](https://www.monshotdata.com).
