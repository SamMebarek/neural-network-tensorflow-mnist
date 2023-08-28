
# Neural Network avec TensorFlow

Ce fichier décrit la construction, l'entraînement, et l'évaluation d'un réseau de neurones profond pour la classification d'images de chiffres manuscrits à l'aide de TensorFlow.

## Contenu

1. **Préparation des données**: Chargement du dataset MNIST, mise à l'échelle des images, division en ensembles d'entraînement, de validation et de test.
2. **Construction du modèle**: Création d'un réseau de neurones avec deux couches cachées.
3. **Entraînement du modèle**: Utilisation de l'optimiseur Adam et de la fonction de perte `sparse_categorical_crossentropy`.
4. **Évaluation du modèle**: Mesure de la perte et de la précision sur l'ensemble de test.
