# Predictive Analytics for IPO Investment Decisions

## Overview

This project aims to improve investment strategies for Initial Public Offerings (IPOs) using advanced data analytics and machine learning techniques. By analyzing a dataset with various IPO metrics, including issue size, subscription rates, and listing gains, the project builds a predictive model to classify IPOs based on their potential profitability.

## Objectives

- **Analyze and preprocess IPO data** to identify and treat outliers, normalize variables, and select relevant features.
- **Develop a predictive model** using TensorFlow/Keras to classify IPOs into profitable or non-profitable categories.
- **Evaluate and visualize model performance** to provide insights and aid decision-making for investors.

## Dataset

The dataset used in this project includes the following columns:

- `Date`: Date of the IPO.
- `IPOName`: Name of the IPO.
- `Issue_Size`: Size of the issue (in millions).
- `Subscription_QIB`: Subscription amount from Qualified Institutional Buyers (QIBs).
- `Subscription_HNI`: Subscription amount from High Net-worth Individuals (HNIs).
- `Subscription_RII`: Subscription amount from Retail Individual Investors (RIIs).
- `Subscription_Total`: Total subscription amount.
- `Issue_Price`: Price at which the IPO was issued.
- `Listing_Gains_Percent`: Percentage gain or loss on listing.
- `Listing_Gains_Profit`: Binary target variable indicating profit (1) or loss (0).

## Methodology

1. **Data Exploration and Preprocessing**
   - Identification and treatment of outliers.
   - Normalization of predictor variables.
   - Feature selection based on summary statistics and visual analysis.

2. **Model Development**
   - Building a neural network using the TensorFlow/Keras Sequential API.
   - Training the model with a validation split to ensure performance.

3. **Model Evaluation**
   - Assessing model performance using metrics like accuracy, loss, and comparison of actual vs. predicted values.
   - Visualizing model performance and predictions.

4. **Visualization**
   - Creating bar plots and other visualizations to compare continuous variables and their impact on the target variable.
   - Plotting actual vs. predicted values to assess model accuracy.

## Results

- **Training Accuracy:** 96.86%
- **Test Accuracy:** 95.31%
- **Training Loss:** 0.0839
- **Test Loss:** 0.1110

The model demonstrated high accuracy on both training and test datasets, indicating its effectiveness in predicting IPO profitability.

## Future Work

- Explore alternative machine learning models and techniques to further improve prediction accuracy.
- Implement additional features or external data sources to enhance model performance.
- Conduct in-depth analysis of factors influencing IPO profitability beyond the current dataset.
