# Project-2---Weather-Analysis

# Correlation and Regression Analysis Documentation:

## 1. Correlation Analysis:

### Correlation Matrix:
- A correlation matrix is computed for the preprocessed weather data using the `corr` function.
- The correlation matrix provides an overview of the relationships between different weather parameters.

### Correlation Heatmap:
- A heatmap is generated using Seaborn to visually represent the correlation matrix.
- The heatmap helps identify patterns and strengths of correlations between weather parameters.

### Threshold Filtering:
- A threshold is set to filter out correlations below a certain value (e.g., 0.5).
- A high correlation heatmap is created to focus on strong correlations between weather parameters.

## 2. Scatter Matrix Visualization:

### Pairwise Relationships:
- Scatter matrix plots are created to visualize pairwise relationships between selected weather parameters.
- Different subsets of columns are chosen to observe relationships more closely.

### Insights from Scatter Matrix:
- Interpretation of scatter matrix plots helps understand the associations and patterns between specific pairs of weather parameters.

## 3. Regression Analysis for 'MaxTemp' and 'Humidity3pm':

### Linear Regression Model:
- Linear regression models are implemented to predict 'MaxTemp' and 'Humidity3pm' based on selected features.
- The datasets are split into training and testing sets using the `train_test_split` function.
- Separate models are trained for 'MaxTemp' and 'Humidity3pm' prediction.

### Model Performance Evaluation:
- Mean Squared Error (MSE) is calculated to assess the accuracy of the regression models.
- Actual vs. Predicted scatter plots with different colors are generated to visualize model performance.

### Insights from Regression Analysis:
- The regression analysis provides insights into how well the models capture variations in 'MaxTemp' and 'Humidity3pm' based on the selected features.

## 4. Additional Regression Analysis for 'Rainfall':

### Linear Regression Model for 'Rainfall':
- A new linear regression model is implemented to predict 'Rainfall' based on selected features: 'MinTemp', 'MaxTemp', 'Sunshine', 'WindGustSpeed', and 'Humidity3pm'.
- The dataset is split into training and testing sets using the `train_test_split` function.
- The model is initialized, trained on the training data, and used to make predictions on the test set.

### Model Performance Evaluation for 'Rainfall':
- The Mean Squared Error (MSE) is calculated to assess how well the model performs in predicting 'Rainfall'.
- The calculated MSE provides a quantitative measure of the accuracy of the 'Rainfall' predictions.

### Actual vs. Predicted Plots for 'Rainfall':
- Scatter plots are generated to compare actual and predicted 'Rainfall' values.
- Different colors are used to distinguish between actual and predicted values in the plots.

### Insights from 'Rainfall' Regression Analysis:
- The analysis of 'Rainfall' aims to understand how well the model captures the variations in rainfall based on the selected features.
- Interpretation of the actual vs. predicted plots provides insights into the model's performance in predicting 'Rainfall'.
