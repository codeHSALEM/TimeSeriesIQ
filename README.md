## TimeSeriesIQ

**Projet d'apprentissage automatique pour la classification de signaux en série temporelle**

**Vue d'ensemble du projet**

TimeSeriesIQ est un projet d'apprentissage automatique qui vise à classifier différents types de signaux en fonction de leurs données en série temporelle. Le projet a été développé avec Google Colab et utilise diverses techniques d'apprentissage automatique, notamment l'analyse en composantes principales (PCA) et les auto-encodeurs.

**Préparation des données**

Le projet utilise un ensemble de données de signaux en série temporelle de cinq catégories différentes : Normal, Un_barre, Deux_barre, Trois_barre et Quatre_barre. Les données ont été prétraitées pour garantir la cohérence et normaliser les valeurs.

**Extraction de caractéristiques**

La PCA a été utilisée pour réduire la dimensionnalité des données et extraire les caractéristiques les plus significatives. Ce processus a aidé à identifier les motifs clés qui distinguent les différents types de signaux.

**Classification basée sur les auto-encodeurs**

Un modèle d'auto-encodeur a été formé pour apprendre la structure sous-jacente des données en série temporelle. Les sorties reconstruites de l'auto-encodeur ont ensuite été utilisées comme caractéristiques d'entrée pour un modèle de classification.

**Résultats et évaluation**

L'approche proposée a atteint une précision de 90 % sur l'ensemble de données de test, ce qui démontre son efficacité pour classer les différents types de signaux.

**Travail futur**

Une exploration plus approfondie de différentes architectures d'apprentissage automatique et de techniques d'optimisation pourrait potentiellement améliorer la précision de la classification et généraliser le modèle à une gamme plus large de types de signaux.

**Installation**

Pour installer et exécuter le projet TimeSeriesIQ, suivez ces étapes :

1. Clonez le référentiel à partir de GitHub :

```bash
git clone https://github.com/votre-nom-d'utilisateur/TimeSeriesIQ.git
```

2. Installez les dépendances requises :

```bash
pip install tensorflow keras pandas numpy matplotlib seaborn
```

3. Changez de répertoire pour le dossier du projet :

```bash
cd TimeSeriesIQ
```

**Contributions**

Nous encourageons les contributions pour améliorer le projet TimeSeriesIQ. N'hésitez pas à forker le référentiel, à apporter des modifications et à soumettre des demandes de tirage avec vos améliorations proposées.
