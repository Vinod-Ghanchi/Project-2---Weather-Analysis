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
- 

## Tableau Analysis:

1. **Rainfall Distribution:**
   - Utilized a Bar Plot to assess the frequency of rainfall occurrences, providing insights into the distribution of rainfall counts.
     ![image](https://github.com/Vinod-Ghanchi/Project-2---Weather-Analysis/assets/80514865/eb0c6137-30e8-40ff-9d9a-ca604722d339)


2. **Temperature Distribution:**
   - Employed a Bar Plot to examine both the count of Minimum and Maximum Temperatures, presented side by side for easy comparison.
     ![image](https://github.com/Vinod-Ghanchi/Project-2---Weather-Analysis/assets/80514865/6cdad236-9f6e-4e33-8886-2058e4873715)


3. **Windspeed In Different Directions:**
   - Developed a TreeMap to visualize the average Wind Speed at 3 pm and a Pie Chart for the average Wind Speed at 9 am across various directions.
     ![image](https://github.com/Vinod-Ghanchi/Project-2---Weather-Analysis/assets/80514865/c823410d-8e7b-4242-b6da-496191d4c9dc)


4. **Rain Status V/S Sunshine and Evaporation:**
   - Constructed a Bar Chart to explore the relationship between rain status, sunshine, and evaporation, offering a comprehensive view of their interplay.
     ![image](https://github.com/Vinod-Ghanchi/Project-2---Weather-Analysis/assets/80514865/38d51329-4e36-476d-9aac-523e72d4051a)


5. **Sunshine V/S Cloudiness:**
   - Created a Line Chart to compare Sunshine and Cloudiness at 9 am and 3 pm, facilitating an analysis of their trends and variations.
     ![image](https://github.com/Vinod-Ghanchi/Project-2---Weather-Analysis/assets/80514865/05b83f63-ab08-4a16-9be8-85b8f7f6c04c)


6. **Rainfall V/S Temperature:**
   - Implemented a Line Chart to illustrate the correlation between Rainfall and both Minimum and Maximum Temperatures, aiding in understanding temperature variations concerning rainfall.
     ![image](https://github.com/Vinod-Ghanchi/Project-2---Weather-Analysis/assets/80514865/2e2f9986-4c0a-4c1e-a504-0dac531b5641)


This Tableau analysis involves a diverse set of visualizations, each tailored to provide meaningful insights into specific aspects of the dataset, enhancing the overall understanding of weather patterns and relationships.

