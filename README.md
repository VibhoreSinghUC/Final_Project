# Flight Delays Analysis 
# Data Science Techniques

## Project Overview
This project analyzes flight delay data from 2014 to 2018. The goal is to understand the factors responsible in flight delays, perform exploratory data analysis (EDA), and build a predictive model to assess factors contributing to delays. We trained a linear regression model to predict delays and evaluated the model's performance using various metrics.

## Data Preparation
1. **Data Extraction**: We extracted individual files containing flight delay data for each month of each year from 2014 to 2018.
2. **Dataset Exploration**: Before combining, we analyzed a single file to understand the structure and contents of the data.
3. **Data Consolidation**: All the files were merged into a single CSV file for  analysis .

## Exploratory Data Analysis (EDA)
Once the data was consolidated, we performed EDA to identify trends, visualize distributions, and check for any data imbalance or missing values.

## Model Training
We trained a logistic regression model on the dataset . The results were assessed with various evaluation metrics.

## Model Evaluation
The performance of the model was evaluated using several metrics:
- **Precision**: Measures the accuracy of delay predictions when the model predicts a delay.
- **Recall**: Measures how well the model identifies all actual delays.
- **Specificity**: Indicates the model’s ability to correctly identify non-delayed flights.
- **Confusion Matrix**: Provides a breakdown of true positives, true negatives, false positives, and false negatives.
- **Accuracy**: Overall correctness of the model in predicting delays and non-delays.

These metrics helped us understand the model’s strengths and areas for improvement.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/VibhoreSinghUC/Flight_Delays_Analysis.git
   cd Flight_Delays_Analysis