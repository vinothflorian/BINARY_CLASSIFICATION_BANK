Bank Dataset Binary Classification Notebook
Overview

This notebook is designed for performing binary classification on a bank dataset, aiming to predict customer behavior (e.g., credit default, churn, or marketing response). It is part of a Kaggle playground competition and demonstrates end-to-end steps from data exploration to model evaluation.

Features

Data loading and preprocessing

Exploratory Data Analysis (EDA) with visualizations

Feature engineering and selection

Model training and evaluation

Cross-validation and performance metrics (AUC, accuracy)

Prediction on test data for Kaggle submission

Dataset

The dataset used in this notebook contains various customer-related features from a bank. Ensure the dataset is available in the appropriate location when running the notebook.

Dependencies

This notebook requires the following Python libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

xgboost / lightgbm (if used in the notebook)

Install dependencies using pip:

pip install pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm

Usage

Open the notebook in Jupyter Notebook or JupyterLab.

Run the cells sequentially.

Modify paths or hyperparameters if needed.

Review the output, including model evaluation metrics and visualizations.

Generate predictions for submission to Kaggle.

Author

Vinoth Zavier

Notes

The notebook focuses on binary classification using structured bank data.

Achieved AUC score in the competition: 0.9695 (can be tuned further).

Follow best practices for feature engineering and model selection to improve performance.
