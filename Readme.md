# Mobile Price Prediction

## Project Overview

The Mobile Price Prediction project aims to analyze the features of mobile phones and classify them into different price ranges. This project utilizes various machine learning models to understand the relationship between mobile phone features and their price ranges. Companies can leverage these insights to make informed decisions about product development, marketing strategies, and competitive positioning.

## Project Type

**Classification**

## Project  Objective

The primary objective of this project is to analyze the features of mobile phones and classify them into different price ranges. By understanding the relationship between the features and the price range, companies can make informed decisions regarding product development, marketing strategies, and competitive positioning.

## Data Preprocessing

### Steps

1. Handling missing values
2. Encoding categorical variables
3. Feature scaling

## Feature Engineering

- Created new features by combining existing ones such as pixel dimensions and screen dimensions.
- Dropped less significant features to simplify the model.

## Exploratory Data Analysis (EDA)

- Distribution analysis of various features using pie charts.
- Relationship analysis between features and price range using box plots and histograms.
- Multicollinearity check using a heatmap.
- Pairplot for visualizing relationships between all features.

## Model Development

### Implemented Models

1. **K-Nearest Neighbors (KNN)**
2. **Naive Bayes**
3. **XGBoost**
4. **Support Vector Machine (SVM)**
5. **Stacking**

### Model Evaluation

- Accuracy scores for each model
- Confusion matrix and classification report for detailed performance metrics

## Results

- **KNN Classifier:** 75.2% accuracy
- **Naive Bayes:** 80.8% accuracy
- **XGBoost:** 89.2% accuracy
- **Support Vector Machine:** 93.6% accuracy
- **Stacking:** 93.8% accuracy

## Conclusion

- From the EDA, we observed that features like RAM, battery power, and pixel dimensions played a significant role in determining the price range.
- Among the models implemented, the Support Vector Machine and Stacking Classifier performed the best, achieving accuracies of 93.6% and 93.8%, respectively.
- These models and the insights derived can help mobile phone companies optimize their product offerings and pricing strategies.

