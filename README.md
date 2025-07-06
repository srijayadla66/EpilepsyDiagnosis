Overview

This project focuses on diagnosing epilepsy using machine learning techniques applied to EEG data. It implements data preprocessing, feature extraction, feature selection using Genetic Algorithms, and classification using various machine learning models to accurately detect epileptic seizures.

Project Structure

Epilepsy.ipynb: Jupyter notebook containing the full pipeline — data preprocessing, feature extraction, feature selection, model training, and evaluation.

Dataset: EEG datasets used for training and testing the models (referenced within the notebook).

Feature Selection: Genetic Algorithm applied to identify the most relevant features.

Classification Models: Includes Random Forest, XGBoost, Gradient Boosting, and Logistic Regression.

Key Features

Conversion of raw EEG signals to tabular data via statistical feature extraction.

Handling imbalanced datasets using SMOTE-Tomek.

Application of Genetic Algorithm for feature subset selection.

Evaluation of model performance with metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

Visualization of feature importance and model results.

Technologies & Libraries Used

Python 3.x

pandas, numpy

scikit-learn

imbalanced-learn

geneticalgorithm (for feature selection)

matplotlib, seaborn (for visualization)
