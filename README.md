# MNIST Classification Notebook
## Overview
This notebook is used  for exploratory learning and building machine learning models for the MNIST dataset, which is a collection of handwritten digit images, typically used for classification tasks. The notebook covers various machine learning techniques and evaluates performance of models.

## Key Features

### Retrieving Data:

- Load and preprocess the MNIST dataset.

### Multiclass Classification:
- Implement a multiclass classification model to distinguish between digits (0-9).
- Multioutput Classification (Cleaning Noise):
- Perform classification tasks while handling noisy data.
- Introduce techniques for cleaning and improving the dataset quality.

### Building Accurate Model:
- Experiment with different architectures and hyperparameters to optimize model performance.
- Manually Creating Augmented Images:
- Generate new training data using manual augmentation techniques to improve generalization.

### Binary Classifier, PR & ROC:
- Develop a binary classification model for specific digit pairs.
- Evaluate the model using Precision-Recall (PR) curves and ROC analysis.

## Dependencies
Following libraries are required:
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- scikit-learn
Make sure these libraries are installed in your environment before running the notebook.

## How to Use
- Clone the repository or download the notebook file.
- Open the notebook in Jupyter Notebook or Google Colaboratory.

### Run each cell sequentially to:
- Load the MNIST dataset.
- Train and test different models.
- Visualize results and analyze performance metrics.

## Results
The notebook demonstrates the application of multiclass and binary classification techniques on the MNIST dataset.
Performance metrics such as accuracy, PR curves, and ROC analysis are used to evaluate the models.

## Acknowledgements
Dataset was provided by the UCI Machine Learning Repository and published on Kaggle.
- Zhan Kazikhanov
- jkazikhanov@gmail.com
- https://github.com/don-juann
