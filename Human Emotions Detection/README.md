# Human-Emotions-Detection
This project focuses on detecting human emotions from facial expressions using a Convolutional Neural Network (CNN). The model is trained on an image dataset obtained from Kaggle, and data augmentation techniques have been applied to improve model generalization. The training process incorporates Early Stopping and Model Checkpoint callbacks to optimize the training workflow.

## Requirements

- Google Colaboratory account/Jupyter Notebook
- Internet connection (for accessing Kaggle dataset and training in Colab)
- Understanding of Python, TensorFlow, and Keras

## Installation

1. Download the .ipynb file.

2. Upload the file to your drive and open it as a google colab file or use jupyter notebook

## Dataset

The dataset used in this project is sourced from Kaggle and can be found [here](https://www.kaggle.com/datasets/muhammadhananasghar/human-emotions-datasethes).You can download the dataset from here and manually upload it to the file or you can go to your kaggle profile and under the settings section under API click on create new token and a kaggle.json file will be downloaded upload this file and this will help in automatically downloading the dataset to the notebook.

## Data Augmentation

Data augmentation is implemented within the notebook. Refer to the "Data Augmentation" section in the notebook for details on how augmentation is applied during the training process.

## Model Architecture

The CNN architecture is defined within the Colab notebook. Look for the code cells related to model architecture to understand the layers and structure.

## Training

Follow the training steps outlined in the Colab notebook. Execute the cells related to model training to initiate the training process.

## Callbacks

- **Early Stopping:** The training process in the Colab notebook incorporates early stopping to prevent overfitting.

- **Model Checkpoint:** The model checkpoint callback is implemented in the Colab notebook, saving the model with the best validation performance.

## Evaluation

Evaluate the model on a test set using the evaluation cells provided in the Colab notebook.


## Contributing

If you'd like to contribute to this project, please feel free to open an issue or submit a pull request in this GitHub repository.


