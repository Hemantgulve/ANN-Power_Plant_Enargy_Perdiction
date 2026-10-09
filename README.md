# Artificial Neural Network — Power Plant Energy Prediction

## Project Overview

This project implements an Artificial Neural Network (ANN) using PyTorch to predict power plant energy output from environmental measurements.

## Objectives

* Understand the fundamentals of neural networks.
* Apply data preprocessing and feature scaling.
* Build and train an ANN regression model using PyTorch.
* Evaluate model performance on unseen test data.

## Features Used

* **AT:** Ambient Temperature
* **V:** Exhaust Vacuum
* **AP:** Ambient Pressure
* **RH:** Relative Humidity

**Target Variable:** PE — Power Output

## Technologies

* Python
* Pandas and NumPy
* PyTorch
* Scikit-learn
* Matplotlib and Seaborn

## Project Workflow

1. Load and explore the dataset.
2. Check missing values and duplicate records.
3. Select input features and target variable.
4. Split the data into training and testing sets.
5. Standardize input features.
6. Convert data into PyTorch tensors and DataLoaders.
7. Build and train the ANN regression model.
8. Evaluate model performance.

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries.
3. Ensure the CSV file is available at `datasets/powerplant_data.csv`.
4. Open `ANN Models.ipynb` in Jupyter Notebook or Google Colab.
5. Run the notebook cells in order.

## Project Status

Learning project — Artificial Neural Networks and regression using PyTorch.
