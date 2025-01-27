# CustomKNNComparison

# Custom KNN Implementation and Comparison

This repository contains a Python implementation of the K-Nearest Neighbors (KNN) classification algorithm. It includes:

# Custom KNN Class:
Implements core KNN functionalities:
* Euclidean distance calculation.
* Neighbor search (finding the k-nearest neighbors).
* Classification based on majority vote of neighbors.

# Data Handling:
DatasetLoader class for loading and handling different datasets (breast-cancer, car, hayes-roth).
Preprocessor class for data preprocessing, including handling missing values and label encoding.

# Cross-Validation:
K-fold cross-validation is implemented to assess the performance of the custom KNN classifier.

# Comparison:
Performance of the custom KNN implementation is compared with scikit-learn's KNeighborsClassifier.
Statistical significance of performance differences is evaluated using a paired t-test.

# Getting Started

# Clone the repository:
Bash
git clone <https://github.com/Aarthicjujjavarapu/CustomKNNComparison.git>

# Install dependencies:
Bash
cd CustomKNNComparison 
pip install -r requirements.txt 
Running the Code

# Execute the main script:
Bash

python main.py

# Output:

The script will output:
* Fold-by-fold accuracy of both the custom KNN and scikit-learn KNN classifiers.
* T-test results to determine the statistical significance of performance differences.
* Summary table showing the mean accuracy of both classifiers for each dataset.

# Datasets
The project includes sample datasets in the dataset/ directory:
* breast-cancer.data
* car.data
* hayes-roth.data

# Contributing
 Contributions are welcome! Please feel free to fork this repository, make changes, and submit a pull request.
