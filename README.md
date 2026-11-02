# Machine Learning Model Evaluation

A machine learning project focused on training, testing, and comparing multiple classification models across 10 experimental runs. The workflow evaluates each model using accuracy, precision, recall, and F1-score to identify the strongest-performing approach for the prediction task.

## Overview

This project demonstrates a complete supervised learning pipeline for model comparison and evaluation. It includes data loading, preprocessing, feature handling, model training, and performance assessment across repeated runs to provide a fair comparison of alternative algorithms.

The notebook is designed to help visualize how different models behave on the same dataset and which configuration yields the best predictive results.

## Dataset

The project uses the Titanic survival dataset from the Seaborn library. The target variable is whether a passenger survived, and the input features include:

- Passenger class
- Sex
- Age
- Siblings/spouses aboard
- Parents/children aboard
- Fare
- Embarked port
- Cabin/deck information
- Other derived passenger attributes

This creates a classic binary classification problem that is well-suited for comparing multiple machine learning models.

## Objectives

- Prepare and clean the dataset for model training
- Train several machine learning classifiers
- Evaluate performance with standard classification metrics
- Compare model results across 10 experimental runs
- Summarize findings in a clear, interpretable format

## Models and Evaluation

The notebook evaluates multiple classification algorithms and compares their results using:

- Accuracy
- Precision
- Recall
- F1-score
- Data summaries and comparative tables

The results are organized so that different models can be compared directly, making it easier to select the best-performing model based on the chosen metric or overall balance across metrics.

## Repository Contents

- `model_training_and_evaluation.ipynb` — notebook containing data loading, preprocessing, training, and evaluation steps
- `model_evaluation_10_runs.xlsx` — Excel file with the aggregated model evaluation results across 10 runs
- `README.md` — project overview and usage guidance

## How to Use

1. Open `model_training_and_evaluation.ipynb` in Jupyter Notebook or Google Colab.
2. Run all cells in sequence.
3. Review the dataset summary and model comparison outputs.
4. Inspect the evaluation metrics table and identify the best-performing model.
5. Use the Excel workbook for a quick summary of the repeated experimental results.

## Typical Workflow

- Load data
- Inspect missing values and feature types
- Clean and transform categorical data
- Split data into training and testing sets
- Train multiple models
- Evaluate using classification metrics
- Compare results across runs

## Notes

This project is useful as a practical example of model benchmarking in a supervised learning context and demonstrates how to assess the effectiveness of multiple algorithms on the same dataset.

## License

This project is provided for educational and demonstration purposes.
