# Data-visualization-including-PCA-3D-plotting-and-classification-models.
 A robust toolkit for machine learning and data visualization, featuring implementations from simple scatter plots to complex neural network models and KNN classifiers across various datasets.
# DataVisMLToolkit

Welcome to DataVisMLToolkit, a comprehensive suite designed to demonstrate advanced machine learning applications coupled with robust data visualization techniques. This repository contains a variety of Python scripts that tackle tasks ranging from simple scatter plots to complex neural network models and KNN classifiers across various datasets.

## Features

- **Random 3D Scatter Plot**: Visualization of random data points in 3D space.
- **KNN on Iris Dataset for 3D Visualization**: Application of the K-Nearest Neighbors algorithm on the Iris dataset with a 3D scatter plot output.
- **Deep Learning Model for Image Classification**: Training and validation of convolutional neural networks on image datasets with TensorFlow and Keras.
- **PCA and KNN Visualization on Validation Images**: Feature extraction using pre-trained CNNs, dimensionality reduction with PCA, and classification using KNN, visualized in a 3D scatter plot.
- **Scikit-learn Datasets for KNN Classification**: Demonstrations using multiple scikit-learn datasets to apply and visualize KNN classification results.
- **Handling Multiple Data Formats with KNN**: Scripts to load and process data from CSV, XLSX, and text files, implement KNN classification, and visualize the results.

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/Dan-445/DataVisMLToolkit.git
Navigate into the project directory:

bash
Copy code
cd DataVisMLToolkit
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Each script in the repository is standalone and can be run individually. Below is an example of how to execute a script:

bash
Copy code
python image_classification_cnn.py
Scripts Overview
random_3d_scatter.py: Generates a 3D scatter plot using matplotlib.
knn_iris_3d.py: Applies KNN to the Iris dataset and plots the results in 3D.
image_classification_cnn.py: Trains a CNN using TensorFlow and Keras and displays progress through training and validation loss and accuracy plots.
pca_knn_validation.py: Extracts features from images, reduces dimensionality with PCA, and uses KNN for classification.
scikit_learn_knn_datasets.py: Uses KNN on different scikit-learn datasets and provides confusion matrix and classification report outputs.
data_formats_knn_classification.py: Demonstrates how to work with various data formats to prepare data, apply KNN, and visualize results.
Contributing
Contributions to DataVisMLToolkit are welcome! Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.
