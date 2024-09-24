# Classification Audio : Comparaison des MLP et CNN sur des Spectrogrammes

## Vue d'ensemble du projet
Ce projet présente une analyse comparative de deux architectures de réseaux neuronaux — le **Perceptron Multi-Couches (MLP)** et le **Réseau de Neurones Convolutif (CNN)** — pour la classification de spectrogrammes audio. L'objectif est d'évaluer les performances de ces modèles sur des enregistrement audio sous forme de spectogrammes et de démontrer l'avantage des CNN pour le traitement et la classification d'images.

Le jeu de données utilisé se compose d'échantillons audio de 10 catégories sonores différentes (par exemple, crépitement de feu, pleurs de bébé, aboiement de chien, etc.), convertis en spectrogrammes pour être utilisés en entrée des réseaux neuronaux. Ce projet inclut l'article de recherche (PDF) et le notebook Jupyter contenant le code pour l'entraînement, l'évaluation et la comparaison des modèles.

## Fichiers

- `Comparaison_MLP_CNN_classification_spectrogrammes.pdf` : Article de recherche intitulé _Comparaison des MLP et CNN pour la classification de spectrogrammes_.
- `classification_spectogrammes.ipynb` : Notebook Jupyter contenant le code pour le traitement des données, l'entraînement des modèles, et l'évaluation des résultats.


## Résultats
Le CNN surpasse nettement le MLP en termes de précision de classification, en particulier lorsqu'il est combiné à des techniques de normalisation. La précision finale obtenue sur les données de test pour chaque modèle est la suivante :
- **MLP** : 60% de précision sur le test
- **CNN** : 76,2% de précision sur le test

L'utilisation des CNN pour les tâches de classification d'images, grâce à leur capacité à extraire des caractéristiques spatiales à partir des formes, offre des performances supérieures comparativement aux MLP.
