# Kickstarter Project Analysis

## Introduction
The Kickstarter platform is a popular crowdfunding website that enables individuals to create projects and raise funds from backers. With a wealth of data on projects launched, their funding goals, outcomes, and backer involvement, there is significant potential to analyze this dataset for insights into what drives successful campaigns.

## Objective
The objective of this project is to analyze Kickstarter campaign data to identify factors influencing campaign success. The focus is on building predictive models to classify campaigns based on their outcomes (e.g., successful, failed, canceled, etc.) and to understand the characteristics of successful campaigns.

## The "Process":
1. **Data Exploration and Preprocessing**:
   - Load the Kickstarter dataset and perform exploratory data analysis (EDA) to understand the distribution of various features.
   - Handle missing values and outliers to ensure data quality.
   - Convert categorical variables into numerical representations suitable for modeling.
   
2. **Feature Engineering**:
   - Extract relevant features such as launch year, month, and campaign duration.
   - Transform features to improve model performance, including log transformations for skewed distributions.

3. **Model Development**:
   - Implement various machine learning models, including:
     - Logistic Regression
     - Decision Trees
     - Random Forest
     - XGBoost
     - Neural Networks
     - LSTM (for time series analysis)
   - Utilize techniques like Grid Search and Randomized Search for hyperparameter tuning to optimize model performance.

4. **Evaluation**:
   - Assess model performance using metrics such as F1-score, accuracy, and confusion matrices.
   - Implement cross-validation to ensure the robustness of the models.

5. **Deployment**:
   - Create a REST API using Flask to serve the trained models for real-time predictions.
   - Document the API endpoints and usage for easy integration.

## Conclusion
Through this analysis, we aim to provide insights into the key factors that contribute to Kickstarter campaign success. The models built will enable potential campaign creators to better understand their target audience and refine their project proposals.
## Model Performance Results

| Model               | Accuracy | F1-Score | Other Metrics      |
|---------------------|----------|----------|---------------------|
| Logistic Regression  | 0.84     | 0.79     | Precision: 0.79     |
| Decision Tree        | 0.85     | 0.80     | Precision: 0.80     |
| Random Forest        | 0.87     | 0.82     | Precision: 0.82     |
| XGBoost              | 0.88     | 0.84     | Precision: 0.84     |
| Neural Network       | 0.90     | 0.87     | Precision: 0.87     |


## Getting Started
Please check out the file to see the entire project and the objectives worked upon by clicking here:
