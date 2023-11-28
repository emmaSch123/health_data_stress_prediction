# health_data_stress_prediction

Objectif : Identifier les facteurs ayant la plus forte corrélation avec le stress et utiliser une base de données acquise afin d'optimiser la précision de la prédiction des données par modèles d'apprentissage automatique.

Observations : 

·       Pré-traitement des Données : Conversion de la variable "stress" de type chaîne en données numériques pour permettre la génération de matrices de corrélation.

·       Génération de la Matrice de Corrélation : Après le changement des types de données, une matrice de corrélation a été générée pour examiner l'impact de différentes variables sur le niveau de stress. Il a été observé que certains paramètres varient en fonction de l'état de stress de l'individu​​. 

·       Division des Données et Choix de l'IA : Les données ont été divisées en données d'entraînement (80%) et de test (20%). Utilisation de modèles de classification en raison de la nature labellisée des données.

Performance des Modèles d'apprentissage automatique : Différents algorithmes ont été testés, et ceux avec les meilleurs scores ont été retenus : Decision Tree Classifier, K-Neighbor Classifier, Random Forest
