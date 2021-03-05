# [Kaggle] Handwritten Arabic Character Recognition

```
Master 2 MIAGE
Méthodes Informatiques Appliquées à la Gestion des Entreprises
UE : FST (Fouille de Données Statistiques)
University of Rennes 1 - France
Author : Pierre Delaunay
Contact : pierre.delaunay@etudiant.univ-rennes1.fr
```

## Results & Ranking

The best entry (using LeNet v5 described below) scored an accuracy of 99.50% on the test set given by Kaggle.

|     Model    | Train Accuracy (%) | Validation Accuracy (%) | Final Score         (%) |
|:------------:|:------------------:|:-----------------------:|:-----------------------:|
|    LeNet-5   |        98.09       |          96.48          |          99.50          |

## Model

ConvNet --> Pool --> ConvNet --> Pool --> ConvNet --> (Flatten) --> FullyConnected --> Softmax 

**epochs** - 100
**loss** - 0.0509
**train_accuracy** - 0.9809
**val_loss** - 0.0955
**val_accuracy** - 0.9648

## References

> [LeCun et al., Gradient-based learning applied to document recognition (1998)](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf)