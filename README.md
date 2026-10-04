# Titanic---Machine-Learning-from-Disaster
A simple PyTorch neural network for the Kaggle Titanic challenge

# PyTorch Titanic Classifier

A straightforward deep learning project for predicting Titanic survival on Kaggle. The script handles feature engineering, data cleaning, and trains a PyTorch neural network.

## Features

* Data preprocessing using Pandas
* Extracting passenger titles to accurately impute missing ages
* Ticket grouping and cabin availability detection
* One hot encoding for embarkation ports
* Three layer feedforward neural network built with PyTorch
* Automated generation of the final submission CSV file

## Setup

Install the required dependencies:

pip install numpy torch pandas matplotlib scikit-learn

## Usage

Run the Python script directly:

python titanic_ml.py

The model trains over 100 epochs, displays the loss graph, and outputs the `submission.csv` file for Kaggle.
