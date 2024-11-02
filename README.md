# Artificial-Intelligence-Project
Premier League Win Predictor
# Artificial Intelligence Project

This project involves an in-depth analysis of a dataset, applying preprocessing steps to handle missing data, and building machine learning models to classify data. The project uses various Python libraries for data manipulation, visualization, and model evaluation, with a focus on using the Gradient Boosting Classifier for predictive modeling.

## Table of Contents

1. [Project Overview](#project-overview)
2.  [Dataset](#dataset)
3. [Data Preparation](#data-preparation)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Model Training and Evaluation](#model-training-and-evaluation)
6. [Requirements](#requirements)
7. [Usage](#usage)
8. [License](#license)
9. [Contact](#contact)

### Project Overview

This project loads a dataset in `.csv` format and performs preprocessing to address missing values. Key steps include exploratory data analysis, feature encoding, and splitting the data for model training and testing. The primary goal is to classify data points accurately using machine learning techniques.

### Dataset

The dataset used in this project is from the English Premier League and can be accessed on Kaggle:

[English Premier League Dataset](https://www.kaggle.com/datasets/saife245/english-premier-league?select=final_dataset.csv)

### Data Preparation

- **File Reading**: The dataset is read from `final_dataset.csv` after downloading it from Kaggle.
- **Missing Values**: Identifies columns with missing data and applies imputation techniques to handle these gaps.
- **Label Encoding**: Converts categorical features to numeric form, preparing the data for machine learning models.

### Exploratory Data Analysis

The following analyses are performed on the dataset:

- Dataset shape and structure inspection
- Column-wise summary statistics
- Sample data display for initial inspection
- Categorical feature identification
- Null/missing value checks



### Model Training and Evaluation

The project utilizes a Gradient Boosting Classifier, with the following metrics to evaluate model performance:

- **Accuracy**
- **Recall**
- **Precision**
- **F1 Score**

These metrics help assess the model's effectiveness in classifying the data accurately.

### Requirements

To run this project, install the following packages:

```bash
pip install pandas matplotlib numpy seaborn scikit-learn
```
### Usage 
-Download the dataset from Kaggle and place final_dataset.csv in the project directory.
-Run the notebook cells sequentially to preprocess the data, perform analysis, and train the model.
-Evaluate the model performance based on the printed metrics.
### License
This project is licensed under the Apache License, Version 2.0.

## Contact
For questions or contributions:

Your Name: nahianmahmood12@gmail.com
GitHub Profile: https://github.com/NAHIAN-KAZI
