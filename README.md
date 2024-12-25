# CSCI303: Data Science - Clustering with Gaussian Mixture Models (GMM)

#### *Melody Goldanloo*

## Overview
This Project applies Gaussian Mixture Models (GMM) for clustering and anomaly detection using the Credit Card Fraud Detection Dataset. The main goal is to build an unsupervised learning model that identifies patterns and anomalies within the dataset.

## Key Features
- ### Data Preprocessing:
    - Handled missing values and scales data for consistency.
    - Separated the target variable ("Class") for evaluation purposes.
- ### Clustering Model Implementation
    - Implemented GMM with different covariance types (full, tied, diag, and spherical).
    - Tested various hyperparameters to optimize clustering performance.
- ### Performance Evaluation
    - Measured accuracy and confusion matrices to assess model effectiveness.
    - Compared results across models to identify the best-performing configuration.

## Technologies Used
**Programming Language:** Python

### Libraries
- `pandas` - Data manipulation, cleaning, and analysis.
- `numpy` - Mathematical operations and handling arrays.
- `scikit-learn` - Model building and evaluation.
- `matplotlib` - Data visualization.

## Dataset
- **Name:** Credit Card Fraud Detection Dataset
- **Source:** [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Description:**
    - Contains transactions labeled as fraud (1) or non-fraud (0)
    - Features represent time, transaction amount, and transformed numerical inputs.

## Installation and Usage
1. Clone this repository:
  ```
  git clone https://github.com/username/csci303_clustering_gmm.git
  cd csci303_clustering_gmm
  ```
2. Download the dataset and save it as `creditcard.csv` in the project directory.
3. Open the `Project - GMMs.ipynb` file.
4. Follow the steps outlined and run the corresponding scripts to build the model.
   - View the comments in the **Building the GMM Model** section.
   - Uncomment lines with different models to see how they perform.
6. Outputs: Model accuracy and confusion matrix.

## Acknowledgements
This project was developed as part of CSCI303 - Data Science at the Colorado School of Mines. Special thanks to Professor Morgan Cox and Dr. Wendy Fisher for guidance and course resources and materials.
