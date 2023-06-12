# Stroke Prediction

This repository contains the code and data files for a stroke prediction project using classification models. The goal of this analysis is to explore and gain insights into the factors associated with strokes in a given dataset,
as well as develop models to make predictions on the possible occurence of stroke

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Summary](#Summary)
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

Classfiers:
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

## Summary 
The analysis provides insights into the relationship between various factors and the occurrence of strokes. The results include descriptive statistics, data visualizations, correlation and significant or patterns discovered during the analysis. Here is the summary:

* From the analysis, the dataset has a high level of inbalance, 95% negative stroke cases, and 5% positive stroke cases, affecting the ability for the model to return better  F1 score(26%). Building a better model would require more data (preferably, one relatively balanced)
* There are a lot of missing data in the BMI column.
* There are outliers present in both the BMI data, and th average glucose level data.
* Age shows a much stronger correlation to the target, followed by prevailing illness(heart_disease and hypertension). It is safe to say that elderly patients with these deases have higher likelihood of having stroke.


## Contributing
Contributions to this analysis are welcome. If you find any issues or have suggestions for improvements, please submit a pull request or open an issue in this repository.
