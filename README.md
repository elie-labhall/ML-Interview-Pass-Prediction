# Software Engineering Interview Pass Prediction

## Overview
This project aims to determine if an interviewee will pass or fail a software engineering interview using machine learning techniques. By analyzing specific features related to the candidate's background, experience, and skills, the model provides a prediction that can assist recruiters in the selection process.

The project was made within the Machine Learning course of my degree and won first place for highest performance (AUC = 0.984).

### Key Features:
- **Purpose**: Predict interview outcomes (pass/fail) for software engineering candidates.
- **AdaBoost Classifier**: Employs boosted decision trees to enhance prediction accuracy.
- **KNN Imputation**: Handles missing data by imputing values based on nearest neighbors.
- **Feature Engineering & Selection**: Processes and selects relevant features influencing interview success.
- **Hyperparameter Tuning**: Utilizes Optuna for efficient hyperparameter optimization.
- **Evaluation Metrics**: Assesses model performance using ROC-AUC scores.

## Project Structure:
- `train.csv` & `test.csv`: Datasets containing candidate features and interview outcomes.
- `model_training.py`: Main script for data preprocessing, model training, and prediction generation.
- `results.csv`: Output file with predictions indicating the probability of passing the interview.
