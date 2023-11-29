# Shoe Classifier Project

## Overview

This project is aimed at creating a shoe classifier using images captured through the camera of a notebook. The process involves generating a dataset of shoe images, visualizing the data, preparing it for training, training a model, and evaluating its performance.

## Notebooks

### 01_generate_data.ipynb

In this notebook, the data generation process takes place. Images of shoes are captured using the camera of the notebook, and the dataset is saved for further use in training the classification model.

### 02_data_visualization.ipynb

This notebook focuses on visualizing the generated shoe dataset. It includes plots illustrating the class distribution of the data and showcases examples of shoes from each class. Visualizing the data is essential for understanding its characteristics before proceeding with model training.

### 03_data_preparation.ipynb

Here, the data is prepared for model training. The notebook involves tasks such as splitting the dataset into training, testing, and validation sets. Proper data preparation is crucial for ensuring the model's effectiveness and generalization.

### 04_training_model.ipynb

This notebook covers the training of the shoe classification model. It includes the actual training process and the evaluation of the model's performance. Metrics and insights gained during the evaluation provide valuable information about the model's capabilities.

## requirements.txt

The `requirements.txt` file contains a list of dependencies necessary to run the notebooks and execute the project successfully. It is recommended to create a virtual environment and install these dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Run `01_generate_data.ipynb` to capture and save images for the shoe dataset.
2. Execute `02_data_visualization.ipynb` to visualize the dataset and understand its distribution.
3. Move on to `03_data_preparation.ipynb` to prepare the data for training, performing necessary splits.
4. Finally, run `04_training_model.ipynb` to train the shoe classification model and evaluate its performance.

Ensure that the dependencies specified in `requirements.txt` are installed before running the notebooks.

Feel free to customize and extend the project according to your needs. If you encounter any issues or have suggestions for improvement, please provide feedback.

Happy classifying! 🥿👟👢