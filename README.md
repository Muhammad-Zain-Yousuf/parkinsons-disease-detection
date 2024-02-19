# Parkinson's Disease Detection Using ML

This Python project aims to detect Parkinson's disease using machine learning techniques, specifically employing the powerful `XGBoost` algorithm. The project leverages the `pandas` library for data manipulation, `scikit-learn` for data preprocessing and evaluation, and XGBoost for building the predictive model.

## Key Features ##
1. ### Data Preparation: ###
   The project reads data from a CSV file (`parkinsons.csv`) containing various features related to Parkinson's disease.

2. ### Feature Engineering: ###
   Features and labels are extracted from the dataset, where features are selected excluding the 'status' column, and labels correspond to the 'status' column.

3. ### Data Scaling: ###
   The features are scaled using Min-Max scaling to normalize the data within a specific range (-1 to 1).

4. ### Model Training: ###
   The `XGBoost classifier` (XGBClassifier) is initialized and trained on the preprocessed data to learn patterns and make predictions.

5. ### Evaluation: ###
   The trained model's performance is evaluated using a test set split from the dataset. Accuracy score and confusion matrix metrics are calculated and printed to assess the model's predictive capability.
