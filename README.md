# Customer Churn Analysis Prediction

## Overview
This repository contains a Python script for analyzing customer churn using machine learning techniques. The script performs data preprocessing, exploratory data analysis (EDA), and model training to predict customer churn based on various features.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [License](#license)

## Introduction
Customer churn refers to the phenomenon where customers stop doing business with a company. Understanding the reasons behind churn is crucial for businesses to improve retention strategies. This project aims to analyze customer churn data and build a predictive model to identify potential churners.

## Dataset
The dataset used in this analysis is `Customer_Churn_Dataset.csv`, which contains various features related to customer behavior and service usage. The dataset can be found in the same directory as this script.

## Installation
To run this script, ensure you have the following libraries installed:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project-directory>
   ```
3. Run the script:
   ```bash
   python customer_churn_analysis_prediction.py
   ```

## Exploratory Data Analysis
The script includes EDA to understand the distribution of churners versus non-churners. Key visualizations include histograms and box plots that illustrate customer service call patterns between churners and non-churners.

### Key Findings from EDA:
- Churners tend to make more customer service calls than non-churners.
- Certain states exhibit higher churn rates compared to others.

## Data Preprocessing
The preprocessing steps involve:
- Encoding categorical variables using Label Encoding and One-Hot Encoding.
- Splitting the dataset into training and test sets.
- Scaling features for better performance in machine learning models.

## Model Training and Evaluation
A Random Forest Classifier is used to predict customer churn. The model's performance is evaluated using accuracy, precision, recall, and a confusion matrix.

### Key Metrics:
- Accuracy: 100%
- Precision and Recall: Calculated from the confusion matrix.
- True Positives (TP): 0
- True Negatives (TN): 20
- False Positives (FP): 0
- False Negatives (FN): 0
- Accuracy: 1.0000
  
