# Comparison of ResNet and EfficientNet CNN Models for Plant Disease and Pest Detection

The goal of this project was the application of
different Convolutional Neural Network (CNN) architectures for
the resolution of the plant disease and pest detection problem,
based on the examples present in the PlantVillage dataset. For
this, different ResNet and EfficientNet models were trained and
compared based on various performance metrics, with these
models being either trained fully from scratch on the previously
mentioned dataset, or trained with transfer learning from other
models pre-trained on either the broad ImageNet dataset, or a
more specific plant disease dataset curated by other researchers
in previous work. The models trained from scratch proved to be
more efficient, with ResNet-9 achieving a validation accuracy of
99.37% and a validation loss of 0.020, while the best performing
pre-trained model had a validation accuracy of 97.98% and
validation loss of 0.096. EfficientNet managed to compete with
ResNet, while offering much lower training times, making this
architecture a very good solution for real-world applications.
