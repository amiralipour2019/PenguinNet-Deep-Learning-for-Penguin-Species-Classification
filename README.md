# PenguinNet: Deep Learning for Penguin Species Classification

PenguinNet is a deep learning framework implemented in PyTorch designed to accurately classify penguin species from the Palmer Archipelago. This repository contains the datasets, model architecture, training procedures, and evaluation scripts used in the study.

## Dataset

The dataset comprises morphological measurements of three penguin species (Adélie, Gentoo, and Chinstrap) from the Palmer Archipelago in Antarctica. Features include culmen length and depth, flipper length, and body mass, collected for ecological research.

## Model

The PenguinNet model consists of:
- An input layer that takes four morphological measurements.
- A hidden layer with ReLU activation.
- An output layer with a softmax function for classification.

The model is trained over 100 epochs, showcasing an impressive convergence and generalization capability, evidenced by a consistent decrease in loss and high validation accuracy.

## Repository Structure

```plaintext
/
├── data/
│   └── penguins_size.csv       # Dataset file
├── src/
│   ├── penguin_net.py          # Main model definition
│   ├── train.py                # Training script
│   └── predict.py              # Prediction script
├── models/
│   └── penguin_classifier.pt   # Trained model weights
├── README.md
└── LICENSE
```
## Results
The trained PenguinNet model achieves a 99% accuracy on the validation dataset. The confusion matrix and loss graphs,
illustrating the model's performance, can be found in the results section within the repository.

## Citation
Gorman KB, Williams TD, Fraser WR (2014). Ecological Sexual Dimorphism and Environmental Variability within a Community of Antarctic Penguins (Genus Pygoscelis). PLoS ONE 9(3): e90081. doi:10.1371/journal.pone.0090081

