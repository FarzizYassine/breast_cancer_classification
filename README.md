# Breast Cancer Classification

## Introduction

This repository contains code for a simple breast cancer classification using the k-Nearest Neighbors (KNN) algorithm. The dataset used is the Breast Cancer Wisconsin (Diagnostic) dataset from the Scikit-Learn library.

## Prerequisites

Make sure you have the required libraries installed. You can install them using the following:

```bash
pip install scikit-learn numpy pandas seaborn matplotlib
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/FarzizYassine/breast-cancer-classification.git
cd breast-cancer-classification
```

2. Run the code:

```bash
python breast_cancer_classification.py
```

## Code Explanation

- The script uses the `load_breast_cancer` function from Scikit-Learn to load the breast cancer dataset.
- It splits the data into training and testing sets using the `train_test_split` function.
- The k-Nearest Neighbors classifier is then instantiated and trained on the training data.
- A Pandas DataFrame is created with the features and target variable, and a heatmap is generated using Seaborn to visualize the correlation between features.

## Results

The script displays a heatmap showing the correlation between different features and the target variable (class). This visualization helps to understand the relationships between variables.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
