# Stroke Prediction

This repository contains code for predicting strokes using machine learning techniques. The dataset used for this prediction task is the Stroke Prediction Dataset, which can be found on Kaggle (https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset).

## Setup

To run the code in this repository, follow these steps:

1. Install required dependencies using pip

2. Upload your Kaggle API key (kaggle.json) using the provided code snippet. Make sure you have downloaded your API key from your Kaggle account settings.

3. Download the Stroke Prediction Dataset from Kaggle using the Kaggle API

4. Unzip the dataset

## Usage
The main script stroke_prediction.py contains the following functionalities:

## Data preprocessing
Model training
Model evaluation
To run the script, simply execute the cells in the notebook. The notebook includes detailed comments explaining each step of the process.

## Models
Two types of models are trained and evaluated in this repository:

1. Random Forest Classifier
2. Artificial Neural Network (ANN)

and the ANN model has been optimized with two different optimizers which is:
1. Adam
2. RMSProp
 
Evaluation
Model performance is evaluated using accuracy, confusion matrix, and classification report. Additionally, visualizations such as confusion matrices are provided for better understanding of the results.
