# CSCI303: Data Science - Clustering with Gaussian Mixture Models (GMM)

#### *Melody Goldanloo*

## Overview
This Project applies Gaussian Mixture Models (GMM) for clustering and anomaly detection using the Credit Card Fraud Detection Dataset. The main goal is to build an unsupervised learning model that identifies patterns and anomalies within the dataset.

## Key Features
- ### Data Preprocessing:
    - Handles missing values and scales data for consistency.
    - Separates the target variable ("Class") for evaluation purposes.
- ### Clustering Model Implementation
    - Implements GMM with different covariance types (full, tied, diag, and spherical).
    - Tests various hyperparameters to optimize clustering performance.
- ### Performance Evaluation
    - Measures accuracy and confusion matrices to assess model effectiveness.

## Technologies Used
**Programming Language:** Python

### Libraries
- `pandas` - Data manipulation, cleaning, and anlysis.
- `numpy` - Mathematical operations and handling arrays.
- `scikit-learn` - Model building and evaluation.
- `matplotlib ` - Data visualization.

## Dataset
- **Name:** Credit Card Fraud Detection Dataset
- **Source:** Kaggle
- **Description:**
    - Contains transactions labeled as fraud (1) or non-fraud (0)
    - Features represent time, transaction amount, and transformed numerical inputs.

## Installation and Usage
1. Clone this repository:
  ```
  git clone https://github.com/username/repository-name.git
  cd repository-name
  ```
2. Download the dataset and save it as `creditcard.csv` in the project directory.
3. Open the `Project - GMMs.ipynb` file.
4. Follow the steps outlined and run the corresponding scripts to build the model.
5. Outputs: Model accuracy and confusion matrix.

## Acknowledgements
This project was developed as part of CSCI303 - Data Science at the Colorado School of Mines. Special thanks to Professor Morgan Cox and Dr. Wendy Fisher for guidance and course resources and materials.
