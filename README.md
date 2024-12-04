### **Customer Purchasing Behaviours** - Team Project

## **Team Members :** </br>
Anshu Dwivedi </br>
Henry Giorgi </br>
Maral Barkhordari </br>
Sonu Abraham </br>
Keyuan Huang

## **Business case** : </br>
Use predictive analytics to recommend the most effective marketing strategies for different customer segments based on their purchasing frequency, loyalty score, and annual income.</br>

Our team has chosen the **Customer Purchasing Behavior Dataset** for in-depth analysis, aiming to derive valuable insights into customer purchasing behaviors. </br>

The objective of this project is to understand how various features correlate to determine the effective marketing strategies. By utilizing regression model, we aim to predict marketing strategies that adddress the diverse interests of various customer segments.This analysis will leverage details from the dataset including customer age, annual income, region,loyalty score and purchashing frequency.

## **About Dataset:**</br>
**customer_id**: Unique ID of the customer.</br>
**age**: The age of the customer.</br>
**annual_income**: The customer's annual income (in USD).</br>
**purchase_amount**: The total amount of purchases made by the customer (in USD).</br>
**purchase_frequency**: Frequency of customer purchases (number of times per year).</br>
**region**: The region where the customer lives (North, South, East, West).</br>
**loyalty_score**: Customer's loyalty score (a value between 0-100).</br>

## Our Approach </br>

Step 1: **Defined Project Goals** </br>

What are the key factors influencing purchasing frequency, loyalty score, and annual income?
How can we segment customers based on these factors?

Step 2: **Data Understanding**</br>
Explore the Dataset:

Loaded, inspected, and cleaned the dataset, addressing missing values and outliers.

Step 3: **Data Preprocessing** </br>
Created new features, scaled numerical data, and encoded categorical variables.

Step 4: **Exploratory Data Analysis (EDA)** </br>
Segmentation Analysis:

Customers were segmented based on income (categorized as Low, Medium, High) and loyalty (Low, Medium, High) to explore purchasing behaviors across different demographics.
Heatmaps were employed to visualize customer distributions across segments, providing insights into where marketing efforts could be focused.

Visualizations:

Histograms revealed the distribution of purchase amounts and loyalty scores, showing the concentration of customers in specific ranges.
Scatter plots illustrated relationships between annual income and purchase frequency, further validating the hypothesis of higher engagement among high-income customers.
Box plots were created to examine how income segments relate to loyalty scores, indicating distinct purchasing patterns tied to loyalty.

Step 5: **Model Selection and Training**</br>
Evaluated Linear Regression, Decision Tree, and focused on Random Forest Regressor.

1. Linear Regression: Assumed a linear relationship to predict purchase frequency.

2. Decision Tree Regressor:Employed a tree based model to make predictions based on feature splits.

3. Random Forest Regressor: An ensemble model of multiple Decision Trees to improve prediction accuracy and reduce overfitting.


Among these, Random Forest appears to be the main focus for further analysis, as indicated by the feature importance plot and likely better performance based on evaluation metrics.

Models were trained using an 80-20 split of the dataset, allocating the larger portion for training purposes.
Each model's performance was assessed through predictions made on both the training and test datasets.

Applied GridSearchCV for the Random Forest model to optimize hyperparameters and enhance predictive performance.

Step 6: **Model Evaluation**</br>
Assessed performance using R², MAE, and RMSE, ensuring reliability through cross-validation.

R² Score : Random Forest showcased strong performance with high R² values.

Mean Absolute Error (MAE): Provided insights into the average error between predicted and actual values.

Root Mean Squared Error (RMSE): Assessed the model's accuracy, confirming the reliability of predictions.

Results were visualized through various plots, including predictions compared against actual values to verify model performance.
Feature importance plots illustrated which predictors had the greatest impact on the model's predictions, guiding future marketing strategies.

Step 7: **Interpretation and Insights**</br>
Feature Importance:
Analyze which features contribute most to the predictions.
Segment Recommendations:
Use the model outputs to make marketing strategy recommendations tailored to different customer segments.

**Key Insights:**
The analysis indicated that loyalty scores and purchasing frequency are significantly influenced by annual income.

The Random Forest model emerged as the most effective for predicting customer purchasing behavior, providing actionable insights for targeted marketing strategies.






