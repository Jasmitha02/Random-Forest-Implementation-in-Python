

---
# Random Forest Implementation and Data Analysis

## Overview
This repository contains a Python implementation of the Random Forest algorithm from scratch, along with a comprehensive data analysis using the implemented Random Forest on a dataset. The Random Forest implementation includes all the essential components such as decision tree helper functions and supports both classification and regression tasks. The data analysis section provides insights into each part of the Random Forest algorithm, accompanied by exclusive visualizations for better understanding.

## Random Forest Implementation
The Random Forest implementation consists of the following components:

- **Decision Tree Helper Functions**: Functions to build decision trees, including checking purity, classifying data, determining potential splits, calculating entropy, and splitting data.
- **Decision Tree Algorithm**: Recursive algorithm to build decision trees based on the provided dataset. Includes parameters for controlling tree depth, minimum samples for splitting, and random subspace sampling.
- **Predictions**: Functions to make predictions using the trained Random Forest model on test data.

## Data Analysis
The data analysis section includes the following:

- **Exploratory Data Analysis (EDA)**: Initial exploration of the dataset to understand its structure, features, and target variable.
- **Preprocessing**: Necessary preprocessing steps such as handling missing values, encoding categorical variables, and splitting data into training and testing sets.
- **Random Forest Usage**: Application of the implemented Random Forest algorithm on the dataset, including training, testing, and evaluating model performance.
- **Visualizations**: Exclusive visualizations to showcase the insights gained from the Random Forest analysis, including feature importance, decision boundaries, and model evaluation metrics.

## Usage
To use the Random Forest implementation and explore the data analysis:

1. Clone the repository to your local machine.
2. Navigate to the directory containing the code.
3. Run the `random_forest.py` script to execute the Random Forest implementation.
4. Explore the Jupyter Notebook `data_analysis.ipynb` for detailed data analysis and visualizations.

## Dependencies
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
