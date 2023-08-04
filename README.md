# Predict Credit Card Consumption for a Leading Bank

## Team Members
- SIM Daro
- THON Manivourn
- THEARA Sreynit
- YON KimKosal

## Introduction
This report aims to predict the credit card consumption of customers for a leading bank. By analyzing customer demographics, behavior data, and credit consumption data, we can understand spending patterns and offer personalized services. The prediction is based on machine learning techniques, specifically Linear Regression.

## Data Preprocessing
Data from various sources were merged, and missing values were removed from all columns except 'cc_cons,' the target variable. Outliers were handled using IQR and z-scores to maintain data integrity.

## Data Exploration & Visualization
Summary statistics and visualizations, such as bar plots and pie charts, were used to understand average monthly spending, customer income levels, and loan status across income groups. Scatter plots helped examine the relationship between spending and regions.

## Model Training with Linear Regression
Using Linear Regression, we trained the model on selected features obtained through Recursive Feature Elimination. The model provided an RMSPE score of approximately 37.86%, indicating reasonable prediction accuracy. Predictions were made for new customers with missing data.

## Results and Model Interpretation
We gained insights into influential features such as tenure with the bank, average days between transactions, and credit card counts in April. These features impact credit card consumption significantly.

## Conclusion
The Linear Regression model successfully predicted credit card consumption for the bank's customers. The predictions offer valuable insights to optimize services and enhance customer satisfaction. Further improvements can be explored by considering advanced algorithms and refining feature engineering. Using these predictions, the bank can make data-driven decisions and offer tailored services to its customers.
