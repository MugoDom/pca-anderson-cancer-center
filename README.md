# Breast Cancer Classification with PCA and Logistic Regression

This project implements Principal Component Analysis (PCA) for dimensionality reduction and logistic regression for classification to a breast cancer dataset available using the sklearn module. The project goal is to classify tumor samples as **Benign** or **Malignant** based on features extracted from cell nuclei images. 

## Project Overview

1. **Data Preprocessing**
2. **Dimensionality Reduction using PCA**
3. **Classification**: Logistic regression used as the classifier
4. **Evaluation**: The model is evaluated using  five metrics namely : accuracy, confusion matrix, precision, recall, and F1-score.

## Results

The logistic regression model had an accuracy of 99%.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MugoDom/pca-anderson-cancer-center.git
   cd pca-anderson-cancer-center
   ```

2. **Install the required packages**:
   ```bash
   pip install sklearn
   ```

## Usage

1. **Run the main script** on a jupyter notebook to load the data, process it and perform PCA:
   ```bash
   pca_analysis.ipynb
   ```

2. **Output**: The notebook will run and  will output the model results.

## Files

- `pca_analysis.ipynb`: This is the notebook to preprocess data, perform PCA, fit the logistic regression model, and display results.
- `README.md`: Project description and instructions.
  
## Dependencies

- Python 3.9
- `scikit-learn`
- `matplotlib`
- `numpy`
- `pandas`

## Acknowledgments

- The breast cancer dataset is part of the `sklearn.datasets` module.
- Many thanks to [scikit-learn](https://scikit-learn.org/).
