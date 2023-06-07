# Stroke Prediction

This repository contains the code and data files for a stroke prediction project using classifier models. The goal of this analysis is to explore and gain insights into the factors associated with strokes in a given dataset,
as well as develop models to make predictions on the possible occurence of stroke

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Overview
In this analysis, we investigate the relationship between various factors and the occurrence of strokes. By examining the dataset and performing exploratory data analysis, we aim to identify patterns, correlations, and potential risk factors associated with strokes.
It also includes several classifier models used to make a predition on the occurence of stroke.

## Dataset
The dataset used in this analysis contains information on individuals, including their age, hypertension status, heart disease status, average glucose level, BMI, and stroke occurrence. This dataset forms the basis for our analysis and insights.
You can download a copy of the dataset from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset).

## Dependencies
The following dependencies are required to run the code in this repository:
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Classfier Models:
- RandomForest Classifier
- DecisionTree Classifier
- AdaBoost Classifier
- KNeigbhors Classifier
- Xgboost Classfier

Evaluation Metrics:
- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- ROC_AUC Score
- Confusion Matrix

## Installation
To set up the required environment and dependencies, follow these steps:
1. Clone this repository to your local machine.
2. Install Python 3 from the official [Python website](https://www.python.org) if not already installed.
3. Install the necessary Python packages using the following command:
   ```
   pip install -r requirements.txt
   ```

## Usage
To run the analysis and reproduce the results, follow these steps:
1. Ensure that the dataset file is placed in the appropriate directory (`/data/`) within the cloned repository.
2. Open and run the Jupyter Notebook or Python script provided in the repository.
3. The code will perform data preprocessing, exploratory analysis, modeling (if applicable), and generate visualizations to gain insights into the stroke analysis.

## Results
The analysis provides insights into the relationship between various factors and the occurrence of strokes. The results include descriptive statistics, data visualizations, correlation and significant or patterns discovered during the analysis. It also includes
performance of the perfect classifier for making future stroke predictions.

## Contributing
Contributions to this analysis are welcome. If you find any issues or have suggestions for improvements, please submit a pull request or open an issue in this repository.


Feel free to customize this README file based on the specifics of your analysis and include any additional information or sections as needed.
