# Malaria Detection

## Overview

This project focusses on detecting malaria disease from images of infected and uninfected cell. Basically this project was created for learning process which includes different types of Data Augmentation, Callbacks, different ways of model development also techninques like dataset versoning, model versoining, Albumenations also technologies like Tensorboard, Wandb etc


## Requirements

- Google Colaboratory account/Jupyter Notebook
- Weights and Biases (Wandb) account
- Internet connection (for accessing dataset and training in Colab)
- Understanding of Python, TensorFlow, Keras and Data Visualization tools

## Installation

1. Open the .ipynb file 

2. Click on "Open in Colab" to load the notebook in Google Colaboratory.

## Dataset

The dataset used in this project is sourced from tensorflow_datasets. Follow the instructions in the Colab notebook to download and preprocess the dataset.

## Data Augmentation

Data augmentation is implemented directly within the Colab notebook. Refer to the "Data Augmentation" section in the notebook. The section containg different types:
- Normal that includes resize,rescale adn flip
- Mixup Data Augementation
- Cutmix Data Augementation
- Albumenations

## Model Architecture

The CNN architecture is defined within the Colab notebook. Look for the code cells related to model architecture to understand the layers and structure. There are different ways define for model architecture:
- Sequential Model
- Sequential Model using Wandb
- Functional Model 
- Model Subclassing
- Custom Layers

## Training

Follow the training steps outlined in the Colab notebook. Execute the cells related to model training to initiate the training process.

## Callbacks

- **Early Stopping:** The training process in the Colab notebook incorporates early stopping to prevent overfitting.

- **Model Checkpoint:** The model checkpoint callback is implemented in the Colab notebook, saving the model with the best validation performance.

-Other Callbacks implemented are:
 LossCallback
 CSV Logger
 Learning Rate Scheduler
 Reduce Learning Rate on Plateau
 For more information please visit tensorflow documentation for callbacks

## Hyperameter Tuning

 1 It is a kind of Grid search cv implemented from scratch where we check for each combinations of the hyperparameter values provides
 2 Hyperparameter tuning using wandb in this we have implemented randomized search where hyperparameter combinations are selected randomly

## Evaluation

Evaluate the model on a test set using the evaluation cells provided in the Colab notebook.

## Usage

Refer to the prediction cells in the Colab notebook to understand how to use the trained model for emotion detection.

## Contributing

If you'd like to contribute to this project, please feel free to open an issue or submit a pull request in this GitHub repository.

## Why Wandb
Wandb (Weights & Biases) helps developer build models better and faster. Helps in tracking experimensts, version, evaluate model performance, and mange ML workflows end-to-end
