# Income Classification Machine Learning Project

## Overview

This project aims to predict whether an individual's income exceeds $50,000 per year based on various demographic and employment-related features. The classification models are trained using the provided dataset, and their performances are evaluated based on accuracy, precision, recall, F1-score, and AUC-ROC.

## Features

- Python-based Jupyter Notebook for data preprocessing, model training, and evaluation.
- Utilizes popular machine learning libraries such as Scikit-learn for model implementation and evaluation.
- Includes various classification algorithms:
  - Linear Discriminant Analysis (LDA)
  - Quadratic Discriminant Analysis (QDA)
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest
  - Gradient Boosting
- Features one-hot encoding for categorical variables and standard scaling for numerical variables.
- Provides detailed evaluation metrics for each model.

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/username/income-classification.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Download the dataset (adult.data and adult.test) from UCI Machine Learning Repository and place them in the project directory.

4. Run the Jupyter Notebook income_classification.ipynb to preprocess the data, train the models, and evaluate their performance.

## Dataset
The dataset contains demographic information such as age, education, occupation, marital status, etc., along with the corresponding income level (>50K or <=50K). It consists of both training and testing sets for model evaluation.

## Results
* LDA:
  * Testing accuracy: 0.8389
  * Precision: 0.7164
  * Recall: 0.5700
  * F1-score: 0.6349
  * AUC-ROC: 0.7482
